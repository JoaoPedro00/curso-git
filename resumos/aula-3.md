# 📚 Guia de Estudo: Comandos Git (Tags e Branches)

Este guia cobre o gerenciamento de versões (tags) e ramificações (branches) no Git.

---

## 🏷️ Trabalhando com Tags (Versionamento)
* **tag é um ponteiro para um commit**
* **`git tag -a v1.0 -m "{mensagem}"`**
  * **O que faz:** Cria uma tag anotada no commit atual (a flag `-a` serve para incluir informações adicionais), permitindo colocar uma mensagem como "versão 1.0". Ideal para marcar entregas (releases) oficiais.
* **`git show {nome da versao}`**
  * **O que faz:** Mostra informações específicas e detalhadas de uma tag, como quem a criou, quando, e as alterações do commit que ela aponta.
* **`git checkout {nome da versao}`**
  * **O que faz:** Muda o estado de todos os arquivos no seu diretório de trabalho para corresponder à versão exata desejada (ex: `git checkout v1.0`).

---

## 🌿 Trabalhando com Branches (Ramificações)

> ℹ️ **Nota:** O branch principal padrão nos repositórios Git é geralmente chamado de **`master`** (ou `main`).

* **Criar e mudar de branch (Duas formas):**
  * **Forma 1 (Passo a passo):** `git branch teste` (cria) e depois `git checkout teste` (muda para ele).
  * **Forma 2 (Atalho):** **`git checkout -b teste`**
  * **O que faz:** Cria um novo branch chamado `teste` e automaticamente muda o seu diretório de trabalho para ele.
* **`git merge {nome do branch}`**
  * **O que faz:** Mescla (puxa) as informações e alterações de um branch específico para o branch em que você está atualmente.
  * **Como usar:** Certifique-se de estar no branch que vai receber as mudanças (ex: `git checkout master`) e, em seguida, execute `git merge teste`.
* **`git branch -d {nome do branch}`**
  * **O que faz:** Deleta o branch especificado (ex: `git branch -d teste`).

---
*💡 **Dica de Estudo:** Tags são como "fotografias" de momentos importantes do seu projeto, enquanto branches são "caminhos alternativos" onde você pode testar e criar novas funcionalidades sem quebrar o código principal.*


