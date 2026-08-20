# 📚 Guia de Estudo: Comandos Git (Início e Fluxo Básico)

Este guia aborda os passos iniciais para criar um repositório, verificar o status e entender o fluxo básico de adicionar e salvar arquivos no Git.

---

## 🚀 Iniciando e Monitorando

* **`cd {nome do diretorio}`** *(Nota: comando de terminal)*
  * **O que faz:** Permite mudar de diretórios no terminal para acessar a pasta do seu projeto onde o Git será utilizado.
* **`git init`**
  * **O que faz:** Inicia um novo repositório Git vazio na pasta atual.
* **`git status`**
  * **O que faz:** Verifica o status atual do repositório, mostrando quais arquivos foram modificados, rastreados ou estão prontos para o commit.

---

## ➕ Preparando Arquivos (Staging Area)

Existem 3 formas principais de adicionar arquivos do seu *working directory* (diretório de trabalho) para a *staging area* (área de preparação):

* **`git add {nome do arquivo}`**
  * **O que faz:** Adiciona apenas um arquivo específico.
* **`git add *.{extensao}`**
  * **O que faz:** Adiciona vários arquivos do mesmo tipo de uma vez (Ex: `git add *.js` para adicionar todos os arquivos JavaScript).
* **`git add .`**
  * **O que faz:** Adiciona **todos** os arquivos modificados e novos de uma só vez.

---

## 💾 Salvando as Alterações (Git Directory)

* **`git commit -m "{mensagem sobre o commit}"`**
  * **O que faz:** Move os arquivos preparados da *staging area* para o *git directory*, salvando de fato o seu trabalho no histórico do repositório com uma mensagem descritiva.

---

## 🙈 Ignorando Arquivos

* **Arquivo `.gitignore`**
  * **O que faz:** Você cria este arquivo na raiz do projeto e escreve nele os nomes de arquivos e diretórios que você quer que o Git ignore (como senhas, chaves de API, arquivos temporários).


