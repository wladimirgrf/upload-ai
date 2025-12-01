### upload-ai

![Node.js](https://img.shields.io/badge/Node.js-43853D?logo=node.js&logoColor=white)
![Fastify](https://img.shields.io/badge/Fastify-000000?logo=fastify&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?logo=prisma&logoColor=white)
![Zod](https://img.shields.io/badge/Zod-3E67B1?logo=zod&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?logo=openai&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?logo=react&logoColor=61DAFB)
![Vite](https://img.shields.io/badge/Vite-646CFF?logo=vite&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?logo=tailwind-css&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white)
![ESLint](https://img.shields.io/badge/ESLint-4B32C3?logo=eslint&logoColor=white)

## 🎯 Overview

In this project, I've structured the application into two distinct layers: the API layer, designed for video processing and integration with OpenAI, and the web layer, which facilitates user interaction and preference customization. 

The goal is to generate video transcripts and use this material in AI prompts to create content based on templates. Through the app experience demonstrated below, you can see it being used to generate video descriptions or even titles. 

The prompts are fully editable, allowing for customization to meet a wide array of needs.

## 🌟 App Experience

![](.github/assets/app-view-1.png)
![](.github/assets/app-view-2.png)
![](.github/assets/app-view-3.png)

## ▶️ Getting started

**Clone the repository**
```bash
$ git clone https://github.com/wladimirgrf/upload-ai.git && cd upload-ai
```

**Install the Project dependencies**
```bash
$ npm --prefix ./api install
$ npm --prefix ./web install
```

**API configuration**
```bash
# Make a copy of '.env.sample'
# Fill both files with YOUR environment variables.
$ cp api/.env.sample api/.env

# Run the migrations
$ npm run --prefix api db:migrate
```

**Launch the API**
```bash
$ npm run --prefix api dev
```

**Launch the Application**
```bash
$ npm run --prefix web dev
```

>The API will be launch on `http://localhost:3333`<br>
>The web APP will be available on `http://localhost:5173`


## 🤝 Contributing

**Fork the repository and clone your fork**

```bash
$ git clone fork-url && cd upload-ai
```

**Create a branch for your edits**
```bash
$ git checkout -b new-feature
```

**Make the commit with your changes**
```bash
$ git commit -m 'feat: New feature'
```

**Send the code to your remote branch**
```bash
$ git push origin new-feature
```

Create a pull request with your version. <br>
After your pull request is merged, you can delete your branch.


## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
