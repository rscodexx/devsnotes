<p align="center">

  <img alt="Repository size" src="https://img.shields.io/github/repo-size/rscodexx/devsbook">

  <a href="https://github.com/rscode/devsbook/commits/master">
    <img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/rscodexx/devsbook">
  </a>

   <img alt="License" src="https://img.shields.io/badge/license-MIT-brightgreen">
   <a href="https://github.com/rscodexx/devsbook/stargazers">
    <img alt="Stargazers" src="https://img.shields.io/github/stars/rscodexx/rscodexx?style=social">
  </a>

  <a href="https://rscode.com.br">
    <img alt="Feito por RS CODE" src="https://img.shields.io/badge/feito%20por-RS CODE-%237519C1">
  </a>

  <a href="https://blog.rscode.com.br/">
    <img alt="Stargazers" src="https://img.shields.io/badge/Blog-RS CODE-%237159c1?style=flat&logo=ghost">
    </a>


</p>
<h1 align="center">
    DevsNotes
</h1>

<h4 align="center"> 
	🚧  Devsbook Concluído 🚧
</h4>

<p align="center">
 <a href="#-sobre-o-projeto">Sobre</a> •
 <a href="#-funcionalidades">Funcionalidades</a> •
 <a href="#-layout">Layout</a> • 
 <a href="#-como-executar-o-projeto">Como executar</a> • 
 <a href="#-tecnologias">Tecnologias</a> •
 <a href="#-autor">Autor</a> • 
 <a href="#user-content--licença">Licença</a>
</p>

## 💻 Sobre o projeto

Devsnote - É uma API de integração feita com framework laravel onde o usuário pode ter blocos de anotações, feito apenas para fins de estudo.

---

## ⚙️ Funcionalidades

- [x] Usuários podem:
    - [x] Verificar suas anotações.
    - [x] Verificar uma anotação específica.
    - [x] Enviar uma anotação.
    - [x] Editar uma anotação.
    - [x] Excluir uma anotação.

---

## ⚙ Como executar o projeto

### Pré-requisitos

Antes de começar, você vai precisar ter instalado em sua máquina as seguintes ferramentas:
[Git](https://git-scm.com), [Composer](https://getcomposer.org/).
Além disto é bom ter um editor para trabalhar com o código como [VSCode](https://code.visualstudio.com/)

#### 🎲 Instalando

```bash

# Você pode clonar este repositório OU baixar o .zip.

$link para baixar direto: https://github.com/rscodexx/devsnotes

# Para clonar:

$ git clone https://github.com/rscodexx/devsnotes.git

# Ao descompactar, é necessário rodar o composer pra instalar as dependências e gerar o autoload.

# Vá até a pasta do projeto, pelo prompt/terminal e execute:

$ composer install

# Depois é só aguardar.

```

#### 🎲 Configurando

```bash

# Abra o arquivo .env na pasta raiz do projeto e altere para os dados do seu banco:

DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=devsnotes
DB_USERNAME=root
DB_PASSWORD=root ⚙

# É necessário importar as tabelas no seu banco de dados que estão na pasta db.
```

#### 🎲 Retornando todas as anotações.

```bash

# Exemplo:

$ Parâmetros = Nenhum.

$ Método = GET

$ <url>/api/notes
```
![Resultado](https://raw.githubusercontent.com/rscodexx/devsnotes/master/examples/result1.png)

#### 🎲 Retornando uma anotação específica.

```bash

# Exemplo:

$ Parâmetros = {id}

$ Método = GET

$ <url>/api/notes/{id}
```
![Resultado](https://raw.githubusercontent.com/rscodexx/devsnotes/master/examples/result2.png)

#### 🎲 Enviando uma anotação.

```bash

# Exemplo:

$ Parâmetros = {title}, {body}

$ Método = POST

$ <url>/api/note?title={$title}&body={$body}
```
![Resultado](https://raw.githubusercontent.com/rscodexx/devsnotes/master/examples/result2.png)

#### 🎲 Editando uma anotação.

```bash

# Exemplo:

$ Parâmetros = {id}, {title}, {body}

$ Método = PUT

$ <url>/api/note?title={$title}&body={$body}
```
![Resultado](https://raw.githubusercontent.com/rscodexx/devsnotes/master/examples/result3.png)

#### 🎲 Excluindo uma anotação.

```bash

# Exemplo:

$ Parâmetros = {id}

$ Método = DELETE

$ <url>/api/note/{id}
```

---

## 🛠 Tecnologias

As seguintes ferramentas foram usadas na construção do projeto:

#### **Back-End**

<img alt="PHP" src="https://img.shields.io/badge/php-%23777BB4.svg?&style=for-the-badge&logo=php&logoColor=white"/> <img alt="Laravel" src="https://img.shields.io/badge/laravel%20-%23FF2D20.svg?&style=for-the-badge&logo=laravel&logoColor=white"/>


---

## 💪 Como contribuir para o projeto

1. Faça um **fork** do projeto.
2. Crie uma nova branch com as suas alterações: `git checkout -b my-feature`
3. Salve as alterações e crie uma mensagem de commit contando o que você fez: `git commit -m "feature: My new feature"`
4. Envie as suas alterações: `git push origin my-feature`
> Caso tenha alguma dúvida confira este [guia de como contribuir no GitHub](./CONTRIBUTING.md)

---

## 🦸 Autor

<a href="https://rscode.com.br">
 <img style="border-radius: 50%;" src="https://avatars.githubusercontent.com/u/80411629?s=460&u=b013fbff0e47f42e5f2c819849416285d380d5e7&v=4" width="100px;" alt=""/>
 <br />
 <sub><b>Rafael Santos</b></sub></a> <a href="https://rscode.com.br/"</a>
 <br />

[![Twitter Badge](https://img.shields.io/badge/-@raffrenan-1ca0f1?style=flat-square&labelColor=1ca0f1&logo=twitter&logoColor=white&link=https://twitter.com/tgmarinho)](https://twitter.com/raffrenan) [![Linkedin Badge](https://img.shields.io/badge/-Raffrenan-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/tgmarinho/)](https://www.linkedin.com/in/raffrenan/)
[![Gmail Badge](https://img.shields.io/badge/-raffrenan@gmail.com-c14438?style=flat-square&logo=Gmail&logoColor=white&link=mailto:raffrenan@gmail.com)](mailto:raffrenan@gmail.com)

---

## 📝 Licença

Este projeto esta sobe a licença [MIT](./LICENSE).

Feito com ❤️ por Rafael Santos 👋🏽 [Entre em contato!](https://www.rscode.com.br)

---
