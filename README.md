# Cópia do Youtube

O projeto é uma cópia do Youtube.

## 🔨 Funcionalidades do projeto

Atualmente, o projeto já possui algumas funcionalidades, como busca de vídeos a uma API.

Agora utilizaremos o ChatGPT para nos ajudar a implementar novas funcionalidades, como o modo escuro, validação de email com regex e modal.

## ✔️ Técnicas e tecnologias utilizadas

- HTML, CSS e JavaScript
- JSON Server

## 🛠️ Abrir e rodar o projeto

Após baixar ou clonar o projeto deste repositório, você precisa ter o [Node.js](https://nodejs.org/) e o [`json-server`](https://www.npmjs.com/package/json-server) instalados.

Caso não tenha o `json-server` instalado globalmente, execute o seguinte comando:

```bash
npm install -g json-server@0.17.4
```

Com o Node.js e o `json-server` instalados, execute o seguinte comando para disponibilizar a API local de vídeos:

```bash
json-server --watch backend/videos.json
```
![Imagem projeto](img/readme/print01.png)

![Imagem projeto](img/readme/print02.png)
