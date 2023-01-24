<h1 align="center"> Habits </h1>

<p align="center">
Projeto desenvolvido no evento NLW - Habtis promovido pela Rocketseat para ensino de tecnologias WEB.
</p>

<p align="center">
  <a href="#-tecnologias">Tecnologias</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-projeto">Projeto</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-instruções">Instruções</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-layout">Layout</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#memo-licença">Licença</a>
</p>

<br>

<p align="center">
  <img alt="capa" src=".github/cover.png" width="100%">
</p>

## 🚀 Tecnologias

Esse projeto foi desenvolvido com as seguintes tecnologias:

- [NodeJS](https://nodejs.org/)
- [TypeScript](https://www.typescriptlang.org/)
- [Fastify](https://www.fastify.io/)
- [Prisma](https://www.prisma.io/)
- [ViteJS](https://vitejs.dev/)
- [ReactJS](https://reactjs.org/)
- [TailwindCSS](https://tailwindcss.com/)
- [React Native](https://reactnative.dev/)
- [Expo](https://expo.io/)

## 💻 Projeto

O Habits é um projeto para monitorar seus hábitos durante todo o ano, nele é possível escolher o hábito que deseja monitorar, a frequência que ele vai se repetir, além de possuir um identidade visual que facilita o acompanhamento das atividades criadas, concluídas e não concluídas. Vale ressaltar que o sistema possui um banco de dados para armazenamento dos hábitos, possui uma interface web e também possui um app mobile.


## 📋 Instruções

### Clone o projeto e acesse a pasta.

```bash
$ git clone https://github.com/ThiagoMonts/nlw-habits.git
```
```bash
$ cd nlw-habits
```

<br>

### Siga o passo a passo:

#### Versão Web

Instale as dependências
```bash
$ cd web
```
```bash
$ npm install
```

<br>

Inicie o projeto web
```bash
$ npm run dev
```

<br>

#### Servidor

Instale as dependências
```bash
$ cd server
```
```bash
$ npm install
```
Verifique se o arquivo .env encontra-se na raíz do projeto

<br>

Inicie o servidor do projeto
```bash
$ npx prisma migrate deploy
```
```bash
$ npm run dev
```

<br>

#### Versão Mobile

Instale as dependências
```bash
$ cd mobile
$ npm install
```

<br>

Inicie o projeto mobile
```bash
$ npx expo start
```

<br>

## 🔖 Layout

Você pode visualizar o layout do projeto através [DESSE LINK](https://www.figma.com/file/pJpaMSKVfCmPUMZJOVwquQ/Habits-(i)-(Community)?node-id=6%3A343&t=P3uqRu2nePSevUMT-1).

## :memo: Licença

Esse projeto está sob a licença MIT.

---

Desenvolvido por [Thiago Honorato](https://www.linkedin.com/in/honoratothiago/)
