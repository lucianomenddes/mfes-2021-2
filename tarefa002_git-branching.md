### Tarefa 002: Git Branching - 15/12/2021

1. Qual o nome da _branch_ padrão do Git?  **Resposta**:_main_

2. O que o comando **<code>git branch nome</code>** realiza?  **Resposta**:-_Cria uma nova branch_

3. Como criar uma _branch_ a partir de um commit específico?  **Resposta**:_Basta passar o commit ID na hora de criar o branch git checkout -b BRANCH_NAME COMMIT_ID_ _

4. Em um repositório, qual o efeito do comando **<code>git checkout -b bugfix/234</code>**?  **Resposta**:

5. Qual o comando para se alternar para uma _branch_ de nome **experimento2**?  **Resposta**: _git checkout experimentos2_

6. Em um repositório com duas _branches_, **b1** e **b2**, onde b1 é o corrente, qual o efeito do comando **<code>git branch</code>**?  **Resposta**:_Mostar a branch atual no caso b1_

7. O que o comando **<code>git checkout -b nome</code>** faz?  **Resposta**:_Cria uma nova branch e redireciona para a mesma_

8. Qual a função do <code>**comando git branch -d teste</code>**?  **Resposta**:_Deletar a branch teste_

9. Durante o desenvolvimento de um software é comum, por exemplo, utilizar um novo recurso por meio de experimentação. Talvez uma nova tecnologia, uma nova biblioteca que pode ser útil ao que está em desenvolvimento, ou até mesmo uma nova versão de um produto já empregado. Para que o uso deste novo recurso não interfira com o que é considerado pronto, uma _branch_ pode ser criada para a experimentação. Código que for criado para a experimentação existirá apenas na _branch_ criada. Se eventualmente o experimento demonstrar um resultado satisfatório, as alterações realizadas na _branch_ poderão ser incorporadas no que é considerado pronto, ou seja, na _branch_ principal (_master_). Esta última ação é conhecida por _merge_. Neste item, crie uma sequência de comandos que simula um caso simples de criação e uso seguido de _merge_ empregando uma _branch_ para ilustrar uma experimentação conforme acima. A sequência deve incluir, obrigatoriamente:

        a. criação de uma ou mais _branches_;
        b. chaveamento para pelo menos dois branches e
        c. merge.

INSTRUÇÕES:**Resposta**:_Criar uma nova branch experimento **<code>git checkout -b experimento</code>**
fazer o merge com a branch developer **<code>git merge developer</code>**
**<code>git commit -m "merge do repositório developer para o experimento"</code>**
**<code>git push</code>**
 ao adicionar os novos arquivos do projeto de experimentação na branch experimento **<code>git add .</code>**
 efeituar as modificações com o comando **<code>git commit -m "experimento feito"</code>** **<code>git push</code>**
 agora é só  enviar para a branch(master)  **<code>git pull https://github.com/ORIGINAL_OWNER/ORIGINAL_REPOSITORY.git master<code>**
 **<code>git commit -m "merge para a master"</code>**
 **<code>git push origin master<code>**

INSTRUÇÕES:
1. A respostas podem ser adicionadas neste mesmo arquivo, imediatamente após cada questão, seguindo o seguinte padrão:
  1.1. **Resposta**: descrever a resposta na sequência.
1. Fazer o _commit_ deste arquivo no seu repositório pessoal, na _branch master_ .
3. A data limite para concluir esta tarefa é dia 18/12/2021, as 23h59min.
