# 📚 Guia de Estudo: Comandos Essenciais do Git
Este guia rápido contém comandos fundamentais para visualização de histórico, manipulação de commits e controle de arquivos no Git.

---

## 🔍 Visualização e Histórico

* **`git diff`**
  * **O que faz:** Mostra as alterações no arquivo. Exibe a diferença entre o seu diretório de trabalho atual e o que está na *staging area*.
* **`git log`**
  * **O que faz:** Mostra todos os commits, exibindo o histórico cronológico de alterações do repositório.
* **`gitk`**
  * **O que faz:** Abre uma interface gráfica para ver os logs dos commits (ótimo para visualizar ramificações e o histórico de forma mais amigável).

## ✍️ Modificação de Commits

* **`git commit --amend -m "{mensagem}"`**
  * **O que faz:** Edita o último commit. É muito útil para alterar a mensagem do commit anterior ou para incluir uma modificação que você esqueceu de adicionar.

## ⏪ Reversão e Manipulação de Arquivos

* **`git reset HEAD {nome do arquivo}`**
  * **O que faz:** Remove um arquivo da *staging area* 
* **`git checkout -- {nome do arquivo}`**
  * **O que faz:** Reverte um arquivo para o status original do último commit. **Aviso:** Isso descarta todas as alterações locais não comitadas daquele arquivo.
* **`git rm {nome do arquivo}`**
  * **O que faz:** Remove arquivos que foram deletados e atualiza a *staging area* para que a remoção seja incluída no próximo commit.

---
