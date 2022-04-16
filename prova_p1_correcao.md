<div align=center>
  <img src="brasaooficialcolorido.png">
</div>

#### <p style="text-align: center;">Universidade Federal de Goiás</p>
#### <p style="text-align: center;">Instituto de Informática</p>
#### <p style="text-align: center;">Bacharelado em Engenharia de Software</p>
#### <p style="text-align: center;">Métodos e Ferramentas de Engenharia de Software - 2021/2</p>
#### <p style="text-align: center;">Gilmar Ferreira Arantes</p>
####  <p style="text-align: center;"> Prova P1 - 16/02/2022</p>

Matrícula:
Nome:

1. (**2.00**) Você é o encarregado da área de desenvolvimento de software da sua empresa e foi convidado para coordenar os trabalhos necessários para migrar o banco de dados do _Oracle_ para o _Postgresql_. Sob a perspectiva das "Técnicas para a Resolução de Problemas", descreva pelo menos cinco atividades imprescindíveis neste trabalho.

* Registre todo o processo.
* Migre primeiros os sistemas não crítivos.
* Migre primeiro o que é mais simples como tabelas e índeces (índices).
* Se possível, gere scripts em texto puro como DDL e DML.
* Importe tabelas, dados e constrainsts separadamente.
* Habilitar e checar logs durante exportações e importações.
* Homologue cada etapa antes de prosseguir.

**Nota = 2.0**

2. (**2.00**) Seguindo os preceitos da Orientação a Objetos, solicita-se a implementação das classes constantes do diagrama de classes abaixo.
<div align=center>
  <img src="oo.png">
</div>

**Não entregue, nota = 0.0**

3. (**2.00**)Explique porque, em geral, é preferível a **composição** a **herança** nos projetos atuais de desenvolvimento de software.

A utilização da composição e herança nos projetos atuais está relacionado ao reuso de código deixando os projetos  mais simples e reutilizáveis. A composição é considerada muito superior à herança na maioria dos casos pois entre as suas principais vantagens a composição permite mudar a associação entre classes em tempo de execução, os objetos podem assumir mais de um comportamento. A herança facilita o compartilhamento de comportamento comum entre um conjunto de classes semelhantes. Além disso, as diferenças ou variações entre classes em relação àquilo que é comum entre elas podem ser organizadas de forma mais clara, mas com o uso incorreto da  herança pode acarretar em problemas como mudar a classe pai pode afetar todas as classes filhas, mesmo quando isso não for intencional, o encapsulamento costuma ficar fraco e o acoplamento forte.

**Nota 2.0**

4. (**2.00**) Considerando Linguagens de Programação compiladas e interpretadas, descreva vantagens e desvantagens de um modelo sobre o outro e em que cenários estas vantagens e desvantagens se apresentam.

Linguagem de programação compilada tem como vantagem: ser  mais rápido de ser acessado Impossibilita ou pelo menos dificulta ser quebrado e visualizado o código-fonte original. Permite otimização pelo compilador, compila apenas se o código estiver sem erros. Desvantagem:  O compilador, analisa totalmente o código fonte em busca de erros léxicos ou sintáticos, de uma maneira que o programa somente será executado, se não houver nenhum erro.

Linguagem de programação interpretada utilizado geralmente por linguagem de script, tem como vantagem: Correções e alterações são mais rápidas de realizar,Código não precisar ser compilado,Consomem menos memória.
Desvantagem: Qualquer erro no código afeta o sistema todo, Necessita sempre ter lido o código original para ser executado

**Nota 2.0**


5. (**2.00**) Sob a perspectiva do usuário/cliente, qual a vantagem de se empregar o paradigma de desenvolvimento orientado a objetos ao invés do paradigma estruturado?

Ao desenvolver um sistema com paradigma orietado a objetos podemos utilizar a vantagem do desenvolvimento iterativo incremental, como o objeto é uma abstração do mundo real e carrega consigo suas propriedades e seus metodos,  podemos entregar o sistema  em partes até compor o todo, sob essa perespectiva o cliente pode obter feedbacks do sistema que está sendo desenvolvido garantindo a entrega e a satisfação.

**Nota 2.0**

INSTRUÇÕES:
1. Tipo: Prova individual;
2. Local de Entrega: Plataforma Turing
3. Forma de Entrega:
   1. As questões discursivas devem ser respondidas neste mesmo arquivo, logo abaixo da sua definição.
   2. Quanto a questão 2, deverá ser implementada na Linguagem de Programação e IDE de sua preferência. Terminando a implementação, junte todo o código fonte, com este arquivo **prova_p1.md** e crie um arquivo compactado chamado **prova_p1_mat.md**, onde mat é o número da sua matrícula. Este arquivo compactado é que deverá ser submetido.
3. Data da Entrega: 16/02/2022, as 23h59min.
4. Critério de Aceitação: arquivos entregues, conforme solicitado.
