<div align="center"><img src="https://i.imgur.com/S9iBF0N.png"></img></div>
<hr>
<h1 align=center>Divide Aí</h1>
<h3 align=center>The easiest way to share a bill with your friends!</h3>
<br>
<div align=center style="display:flex; justify-content: center; gap:5%">
    <h4>Divide Ai is a web application built with React.JS for people who struggle to split bills with others without any control of who paid and who didn't. One of the main focus of this app is to help people who lives together control expenses.</h4>
</div>

## Features

- Sign up
- Login (Manual and OAuth)
- Persistent sessions
- Show list of your shared bills
- Create new bill
- Delete bill
- See infos of the bill
- Select friends to share bills
- Add new friends
- Accept or refuse friends requests
- Delete users of your friend list
- Mark if you already paid the splitted bill
- View a history of your bills

<br>

## Motivation

This idea came up when I saw my girlfriend struggling to find out if her house bills had already been paid (she lives with two friends and they share all expenses).

<br>
With that in mind, I decided to create an application that would not only help her, but other people who have the same problem.

The differential of Divide Aí is the ease of splitting an account and also the friendship system that makes the app much friendlier.

<br>
So my goal is to improve this project with new features (chat with friends, notification system, and others) to help anyone ho needs a bill splitter app.

<br>

## Built with

<br>

### Front-End

<p>
  <img src="https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB" />
  <img src="https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white" />
  <img src="https://img.shields.io/badge/React_Router-CA4245?style=for-the-badge&logo=react-router&logoColor=white" />
  <img src="https://img.shields.io/badge/-React%20Query-FF4154?style=for-the-badge&logo=react%20query&logoColor=white" />
  <img src="https://img.shields.io/badge/styled--components-DB7093?style=for-the-badge&logo=styled-components&logoColor=white" />
  <img src="https://img.shields.io/badge/vite-%23646CFF.svg?style=for-the-badge&logo=vite&logoColor=white" />
  <img src="https://img.shields.io/badge/ESLint-4B3263?style=for-the-badge&logo=eslint&logoColor=white" />
  <img src="https://img.shields.io/badge/prettier-1A2C34?style=for-the-badge&logo=prettier&logoColor=F7BA3E">
  <img src="https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white" />
  <img src="https://img.shields.io/badge/firebase-ffca28?style=for-the-badge&logo=firebase&logoColor=black" />
  <img src="https://img.shields.io/badge/github%20actions-%232671E5.svg?style=for-the-badge&logo=githubactions&logoColor=white" />
  <img src="https://img.shields.io/badge/AWS-%23FF9900.svg?style=for-the-badge&logo=amazon-aws&logoColor=white" />
  <img src="https://img.shields.io/badge/nginx-%23009639.svg?style=for-the-badge&logo=nginx&logoColor=white" />
</p>

<br>

### Back-end

<p>
  <img src="https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white" />
  <img src="https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white" />
  <img src="https://img.shields.io/badge/express.js-%23404d59.svg?style=for-the-badge&logo=express&logoColor=%2361DAFB" />
  <img src="https://img.shields.io/badge/JWT-black?style=for-the-badge&logo=JSON%20web%20tokens" />
  <img src="https://img.shields.io/badge/postgres-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/Prisma-3982CE?style=for-the-badge&logo=Prisma&logoColor=white" />
  <img src="https://img.shields.io/badge/ESLint-4B3263?style=for-the-badge&logo=eslint&logoColor=white" />
  <img src="https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white" />
  <img src="https://img.shields.io/badge/-jest-%23C21325?style=for-the-badge&logo=jest&logoColor=white" />
  <img src="https://img.shields.io/badge/github%20actions-%232671E5.svg?style=for-the-badge&logo=githubactions&logoColor=white" />
  <img src="https://img.shields.io/badge/AWS-%23FF9900.svg?style=for-the-badge&logo=amazon-aws&logoColor=white" />
</p>

<br>

## How to run

1. Clone this repository

```bash
git clone --recursive https://github.com/vinicbarros/DivideAi
```

2. Populate `.env.prod` file based on `.env.example` on the back-end folder
3. Populate `.env` fole based on `.env.example` on the front-end folder (the `URL` must end with `:80/api`. ex: `http://localhost:80/api`)

4. For this step you need to have installed docker and docker-compose
5. Run docker compose

```bash
docker-compose up --build
```

6. After that, making sure that you done all the steps, you can access the app through `http://localhost:80` and the api through `http://localhost:80/api`

<br>

## Contact

Feel free to contact me in Linkedin!

[![LinkedIn][linkedin-shield]][linkedin-url]

<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->

[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=blue
[linkedin-url]: https://www.linkedin.com/in/ovinibarros/
