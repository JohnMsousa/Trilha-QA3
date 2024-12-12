# Módulo 3 - Utilizando Git na IDE.

1. **Crie um novo repositório local**  
   Abra o terminal.  
   Acesse o diretório onde você quer criar o novo repositório.  
   Inicialize um novo repositório com o comando:  
   `git init`

2. **Adicione o repositório remoto criado nos exercícios anteriores ao seu repositório local**  
   Use o comando:  
   `git remote add <nome-remoto> <url-do-repositorio-remoto>`  
   para adicionar o repositório remoto ao seu repositório local.

3. **Faça uma alteração no repositório local e envie para o remoto**  
   Após criar ou acessar o repositório, faça as alterações desejadas.  
   Adicione as mudanças com o comando:  
   `git add .`  
   Depois, execute:  
   `git commit -m "Alterações no repositório local"`  
   Para enviar as alterações para o repositório remoto, use o comando:  
   `git push <nome-remoto> main`

4. **Resolva os conflitos manualmente, escolhendo quais alterações serão mantidas**  
   No GitHub, edite o arquivo que você alterou localmente.  
   Execute o comando:  
   `git pull <nome-remoto> main`  
   no terminal para trazer as alterações do repositório remoto.  
   O Git indicará um conflito. Abra o arquivo e resolva manualmente, escolhendo as alterações a serem mantidas.

5. **Realize um commit para registrar a resolução do conflito**  
   Depois de resolver o conflito, use o comando:  
   `git add .`  
   para adicionar as alterações.  
   Em seguida, execute:  
   `git commit -m "Resolver conflito manualmente de ‘descrição do conflito’"`  
   para registrar a resolução do conflito.

6. **Verifique quais arquivos foram adicionados**  
   Com o comando:  
   `git status`  
   podemos ver se há alterações.

7. **Sincronize o repositório local com o repositório remoto no GitHub**  
   Use o comando:  
   `git push <nome-remoto> main`  
   para enviar as alterações para o repositório remoto.
