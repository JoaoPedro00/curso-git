# 📚 Guia de Estudo: Comandos Git (Repositórios Remotos)

Este guia foca na interação com repositórios remotos, ensinando como clonar projetos, enviar suas alterações para o servidor e receber atualizações.

---

## 🌐 Interagindo com Servidores (Remotes)

* **`git clone {caminho/URL do repositório} {novo_nome_opcional}`**
  * **O que faz:** Clona (baixa) um repositório do servidor para a sua máquina. O `{novo_nome_opcional}` permite que você dê um novo nome para a pasta local onde os arquivos serão salvos.
* **`git remote`**
  * **O que faz:** Descobre e lista os nomes dos repositórios remotos configurados no seu projeto. Geralmente, o servidor principal recebe o nome padrão de `origin`.

## ⬆️ Enviando e ⬇️ Recebendo Alterações

* **`git push origin master`**
  * **O que faz:** Envia (empurra) as suas alterações locais. Neste comando, você está dizendo para o Git enviar os arquivos e commits que estão atualmente no seu branch `master` para o servidor remoto chamado `origin`.
* **`git pull origin master`**
  * **O que faz:** Puxa (baixa e mescla) os arquivos com mudanças do servidor remoto (`origin`) para o seu branch atual (`master`). É essencial para atualizar o seu projeto local com as alterações feitas por outras pessoas no servidor.

---
*💡 **Dica de Estudo:** O fluxo de trabalho em equipe geralmente envolve fazer um `git pull` antes de começar a programar para garantir que você tem a versão mais recente, e um `git push` ao finalizar suas tarefas para compartilhar seu código com o time.*
"""

