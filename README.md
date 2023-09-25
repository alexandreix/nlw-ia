<h1 align="center">
  
![Logo](https://github.com/guisant/nlwia/assets/37338838/28640e18-c592-4495-b810-df387c6c52aa)
</h1>


## 💻 Descrição

<p>Esse projeto é uma aplicação web para criar resumo de vídeos shorts do YouTube utilizando Inteligência Artificial. 
Modelosde IA utilizados: Whisper para reconhecimento automático de fala (ASR - automatic speech recognition) e Bart para resumo de texto.
  
Esse projeto foi desenvolvido na trilha Foundations na edição NLW IA da Rockeseat..</p>

<br><br>

## 🚀 Como executar o projeto

### Pré-requisitos

Ter instalado em sua máquina as seguintes ferramentas:
[Git](https://git-scm.com), [Node.js](https://nodejs.org/en/). 
e um editor de código como [VSCode](https://code.visualstudio.com/), por exemplo.

#### 🎲 Rodando o Backend (servidor)

```bash

# Clone este repositório
$ git clone https://github.com/guisant/nlwia.git

# Acesse a pasta do projeto no seu terminal/cmd
$ cd nlw-ia

# Instale as dependências
$ npm install

# Execute a aplicação em modo de desenvolvimento
$ npm run server

# O servidor iniciará na porta:3333 - acesse http://localhost:3333/summary/"id do video"(codigo após /shorts/..)

```
#### 🧭 Instalando as bibliotecas

```bash
# Execute no terminal o seguinte comando:
npm i express cors axios ytdl-core@4.10.0 

# Em seguida:
npm i @xenova/transformers fluent-ffmpeg ffmpeg-static node-wav

```
#### 🧭 Rodando a aplicação web (Frontend)

```bash

# Execute a aplicação em modo de desenvolvimento
$ npm run web

# A aplicação será aberta na porta:5173 - acesse http://localhost:5173

```

<br><br>

## 🛠 Tecnologias

 
![Badge NPM](https://img.shields.io/badge/npm-CB3837.svg?style=for-the-badge&logo=npm&logoColor=white)
![Badge JS](https://img.shields.io/badge/JavaScript-F7DF1E.svg?style=for-the-badge&logo=JavaScript&logoColor=black)

<br>

<div align="center">
</p>
  <small> 2023 © Desenvolvido por <strong>Alexandre Rodrigues</strong></small>

  [![Linkedin Badge](https://img.shields.io/badge/-Alexandre%20Rodrigues-0081d2?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/alexandrerodriguesd/)](https://www.linkedin.com/in/alexandrerodriguesd/) 
</div>
