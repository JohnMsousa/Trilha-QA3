# Módulo 4 - Voltando no tempo.

1. **Acesse todos os commits realizados**  
   Para acessar todos os commits, use o comando:  
   `git log`

2. **Modifique o último commit**  
   Para modificar o último commit, use o comando:  
   `git commit --amend`

3. **Reverta mudanças no repositório local**  
   Para reverter automaticamente as mudanças feitas no último commit sem excluir o histórico, use o comando:  
   `git revert <hash-do-commit>`  
   Será necessário realizar um novo commit para aplicar a reversão ao repositório.

4. **Apague um ou mais commits**  
   Para apagar um ou mais commits, use o comando:  
   `git reset --hard <hash-do-ultimo-commit-a-manter>`

5. **Sincronize as modificações com o repositório remoto**  
   Para sincronizar, use o comando:  
   `git push`

6. **Analise as mensagens de commits realizados e faça as alterações de acordo com as boas práticas.**  
   Para visualizar os commits e suas mensagens, use o comando:  
   `git log`

   ![image](https://github.com/user-attachments/assets/74b534d7-ffcc-4027-a30d-d09d08b708b5)

   Para seguir as boas práticas de mensagens de commit, utilize o verbo no infinitivo, como "adicionar", "corrigir" ou "atualizar", para descrever a alteração. Seja conciso, incluindo apenas o essencial da mudança, como no exemplo: “Atualizar texto do título da página”.  
   Evite detalhes técnicos complexos nas mensagens; esses devem ser documentados no código ou em comentários apropriados.
