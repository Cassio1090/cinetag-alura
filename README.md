## Cinetag
O Cinetag é uma aplicação web do curso de React da alura. Ele se trata de um site similar a youtube.

## ✨ Funcionalidades
Listagem dinâmica de produtos via API 
Navegação entre paginas "Home" e "Favoritos"
Funcionalidade de favoritar vídeos

## 🚀 Tecnologias utilizadas
- ![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)
- ![React Hook Form](https://img.shields.io/badge/React%20Hook%20Form-%23EC5990.svg?style=for-the-badge&logo=reacthookform&logoColor=white): useState, useEffect, useParams
- ![React Router](https://img.shields.io/badge/React_Router-CA4245?style=for-the-badge&logo=react-router&logoColor=white)
- ![Context-API](https://img.shields.io/badge/Context--Api-000000?style=for-the-badge&logo=react) Context para a criação do context do Favoritos 
- ![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
- ![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)
- ![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)

## 📍 Rotas da Aplicação 

Rotas Descrições
/home	pagina home onde lista todos os videos
/favoritos	pagina para ver os videos favoritados


## 📦 Como rodar o projeto
Pré-requisitos

NodeJS 
Git 


Clone o repositório:
git clone https://github.com/Cassio1090/cinetag-alura
2.Acesse a pasta do projeto:

cd cinetag

3.Instale o json-server globalmente (caso o db.json seja criado dentro da aplicação):

npm install -g json-server

4.Inicie o json-server com o arquivo de dados na pasta especifica do json

json-server --watch db.json
 
5.Abra o terminal para iniciar a aplicação no navegador e executer comando npm.

npm start

