# Módulo 1 - Compartilhar Projetos.

1. **Crie uma conta no GitHub.**  
   Acesse o site: [https://github.com/](https://github.com/) e clique em **Sign up**.

2. **Crie um repositório para um projeto pessoal.**  
   Acesse seu GitHub e, em repositórios, clique em **New**.  
   ![image](https://github.com/user-attachments/assets/1ec04c39-50c5-4942-959f-750ba9644e85)

   Após isso, você será redirecionado para definir o nome do repositório. Após definir, clique em **Create repository**.  
   ![image](https://github.com/user-attachments/assets/90fb05fe-044d-47fb-9832-08cca76ede76)

3. **Faça a instalação do Git.**  
   Acesse o site do Git: [https://git-scm.com/downloads](https://git-scm.com/downloads) e faça o download de acordo com seu sistema operacional.

4. **Crie um repositório localmente para o seu projeto pessoal.**  
   Digite o seguinte comando no terminal:  
   `git init`

5. **Adicione alguns arquivos no seu repositório local.**  
   Digite no terminal o comando:  
   `git add .`

6. **Faça o commit das alterações.**  
   Digite no terminal o comando:  
   `git commit -m "mensagem de commit"`

7. **Configure a identidade do autor do commit.**  
   Digite no terminal os seguintes comandos:  
   `git config --global user.email "seuemailaqui@example.com"`  
   `git config --global user.name "seu nome aqui"`

8. **Crie a branch Main.**  
   Digite no terminal o comando:  
   `git branch -M main`

9. **Realize a conexão do seu repositório local com o remoto.**  
   Via SSH, digite no terminal:  
   `git remote add origin git@github.com:seunomedeusuario/seu-repositorio.git`

10. **Envie as alterações no repositório local para o remoto.**  
    Digite o seguinte comando no terminal:  
    `git push -u origin main`

11. **Utilize o comando `git status`.**  
    Digite o seguinte comando no terminal:  
    `git status`  
    O `git status` permite monitorar as alterações no repositório, identificar o estado dos arquivos e tomar decisões de gerenciamento de commits de forma eficiente.
