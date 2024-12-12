# Módulo 2 - Colaborando em Projetos.

1. **Crie um novo repositório remoto no GitHub e insira um arquivo.**  
   Entre na sua conta do GitHub.  
   Clique no sinal de "+" no canto superior direito e escolha **New repository**.  
   ![image](https://github.com/user-attachments/assets/a338035a-c819-4338-8e9a-0c770a1c1375)

2. **Faça um clone do seu repositório remoto para o local.**  
   **Passo 1** - Entre no projeto que deseja fazer o clone, clique em "<> Code" e selecione a maneira que deseja clonar (exemplo: SSH), depois copie a URL.  
   ![image](https://github.com/user-attachments/assets/dc40e41e-f4f1-4f2d-af15-30dd8d156e4d)

   **Passo 2** - Abra o terminal ou o Git Bash e defina o local onde o repositório será armazenado. Após isso, execute o comando:  
   `git clone <url-do-seu-repositorio>`

3. **Faça uma nova modificação no repositório remoto.**  
   Acesse o seu repositório no GitHub.  
   Abra um arquivo existente ou crie um novo.  
   Faça as alterações desejadas diretamente no GitHub e salve.  
   ![image](https://github.com/user-attachments/assets/c559bf4f-db0b-473a-87b7-1c1a26bb0dc1)  
   Clicando em **editar**, você pode modificar o arquivo e depois salvar as alterações.

4. **Atualize seu repositório local a partir do remoto.**  
   Navegue até o diretório do seu repositório local usando o terminal.  
   Execute o comando:  
   `git pull origin main`  
   Isso trará as últimas alterações do repositório remoto para o seu repositório local.

5. **Utilize o comando `git remote -v` no terminal.**  
   O comando `git remote -v` irá listar todas as entradas remotas configuradas no repositório Git atual.  
   ![image](https://github.com/user-attachments/assets/33ea05d4-f3d9-4375-a755-e845104fe6a0)

   - **fetch**: Baixar alterações do repositório remoto para o local.
   - **push**: Enviar suas alterações locais para o repositório remoto.

6. **Confira as mudanças nos arquivos.**  
   Digite `git status` no terminal para ver os arquivos modificados no seu repositório local.
