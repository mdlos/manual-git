
<img width=100% src="https://capsule-render.vercel.app/api?type=waving&color=02A6F4&height=120&section=header"/>
<h1 align="center">Manual Git</h1>

<div align="center">  
  <img width=40% src="http://img.shields.io/static/v1?label=STATUS&message=%20PRONTO&color=02A6F4&style=for-the-badge"/>
</div>

<div align="center">
 <a href="#-sobre-o-projeto"> Sobre</a> • 
 <a href="#-tecnologias"> Tecnologias</a> • 
 <a href="#-instalacao"> Instalação</a> • 
 <a href="#-desenvolvedores"> Desenvolvedores</a>
</div>

## 🗒️ Sobre o GIT

## 📌 O que é o GitHub?

O **GitHub** é uma plataforma para hospedagem de código que usa o **Git**, um sistema de controle de versão. 
Ele permite que você acompanhe alterações no seu código e colabore com outras pessoas.

## 🛠 Tecnologias

1. **Git e Github**;
2. **VScode**;
3. **Arquivo**;

## 👨‍💻 Conta do git
 **1. Criar uma Conta no GitHub**
1. Acesse: <https://github.com>
2. Clique em **Sign up**.
3. Preencha:
   * Nome de usuário
   * E-mail
   * Senha
4. Confirme o e-mail enviado pela GitHub.

## ✅ **2. Instalar o Git no seu computador**

### No Linux (ex: Manjaro):
```
sudo pacman -S git
```
### No Windows:
* Baixe e instale: <https://git-scm.com>

## ✅ **3. Configurar o Git no Terminal**
```
git config --global user.name "Seu Nome"
git config --global user.email "seuemail@exemplo.com"
```
## ✅ **4. Criar um Repositório no GitHub**
1. Acesse o site do GitHub e faça login.
2. Clique em **+** no canto superior direito → **New repository**.
3. Preencha:
   * Nome do repositório
   * Descrição (opcional)
   * Público ou Privado

4. Clique em **Create repository**.

## ✅ **5. Subir Arquivos Locais para o GitHub pela Primeira Vez (sem clonar)**
Se você já tem um projeto local e quer enviar para um repositório novo no GitHub:

### a) Crie o repositório no GitHub (como mostrado no passo 4)
### b) No terminal, entre na pasta do seu projeto:
```
cd /caminho/do/seu/projeto
```
### c) Inicialize o repositório Git:
```
git init
```
### d) Adicione os arquivos:
```
git add .
```
### e) Faça o commit:
```
git commit -m "Primeiro commit"
git log # verificar se os commits foram salvos por meio de um hash
```
### f) Conecte ao repositório remoto:
```
git remote add origin https://github.com/seuusuario/seurepositorio.git
```
### g) Envie os arquivos para o GitHub:
```
git push -u origin main
```
```
git checkout -b func_1
```
significa:
🟡 **Criar e mudar para uma nova branch chamada `func_1`**.
### 🔍 Explicação:
* `git checkout`: comuta (troca) entre branches.
* `-b func_1`: cria uma nova branch chamada `func_1` e já muda para ela.
* 
### ✅ Quando usar?
Esse comando é útil quando você quer começar a trabalhar em uma nova funcionalidade, correção ou experimento, mantendo o código separado da branch principal (`main` ou `master`).
### 🧠 Exemplo de fluxo completo:
```
git checkout -b func_1        # cria e entra na nova branch
# faz suas alterações...
git add .
git commit -m "Adiciona funcionalidade 1"
git push origin func_1        # envia a nova branch para o GitHub
```
Depois, no GitHub, você pode abrir um **Pull Request** para juntar essa branch (`func_1`) com a branch principal.

Para sair da branch `func_1` e voltar para a branch `main`, use:

### ✅ Passo a passo:

1. **Verifique a branch atual (opcional):**
   ```
   git branch
   ```
2. **Mude para a branch `main`:**
   ```
   git checkout main
   ```
```
	git merge func_1
```
significa:

🔄 **Mesclar o conteúdo da branch `func_1` na branch atual** (normalmente `main`).***

### ✅ Passo a Passo Completo para fazer o merge:

1. **Mude para a branch que receberá as mudanças** (ex: `main`):

   ```
   git checkout main
   ```
2. **Execute o merge da branch `func_1`:**
   ```
   git merge func_1
   ```
### ✅ **6. Criar um novo repositorio no GitHub**
Esse comando:
```
git remote add origin https://github.com/mdlos/manual-git.git
```
significa:

🔗 **Conectar seu repositório local ao repositório remoto no GitHub**.
***
### 🧠 Explicação:
* `git remote add`: adiciona um repositório remoto.
* `origin`: é o **apelido** usado para o repositório remoto (padrão do Git).
* `https://github.com/mdlos/manual-git.git`: é a **URL do repositório** no GitHub.
***
### ✅ Depois de adicionar o remoto, o que fazer?

1. **Enviar o projeto para o GitHub (primeira vez):**
   ```
   git push -u origin main
   ```
   2. **Nas próximas vezes, apenas:**
   ```
   git push
   ```
***
## 💻 Desenvolvedor
 
<table>
  <tr>
    <td align="center"><img style="" src="https://avatars.githubusercontent.com/u/72825281?v=4" width="100px;" alt=""/><br /><sub><b> Marcio Fonseca </b></sub></a><br />👨‍💻</a></td>
  </tr>
</table>


