### upload-ai

[![](https://img.shields.io/github/repo-size/wladimirgrf/upload-ai?color=%23FFB000&labelColor=000000)]()
[![](https://img.shields.io/github/last-commit/wladimirgrf/upload-ai?color=%23FFB000&labelColor=000000)](https://github.com/wladimirgrf/certification/commits/master)
[![](https://img.shields.io/github/issues/wladimirgrf/upload-ai?color=%23FFB000&labelColor=000000)](https://github.com/wladimirgrf/certification/issues)

This project is a proof of concept for the Bitcoin's Mainnet and Testnet. 
This RESTful API is designed to support multiple blockchain providers. Can be an external API like BlockCypher or even a full node. The goal is to ensure availability even if one of the providers is offline.

## 🌍 Ecosystem

Below the frameworks, used to build the APP:

|                      Name                                   |                         Status                          |
|:-----------------------------------------------------------:|:-------------------------------------------------------:|
|<img height="58" src="https://cdn.worldvectorlogo.com/logos/nodejs-1.svg"> | <img alt="node version" src="https://img.shields.io/badge/nodejs-v18.17-%23FFB000?labelColor=000000"> |
|<img height="50" src="https://cdn.worldvectorlogo.com/logos/fastify.svg"> | <img alt="fastify version" src="https://img.shields.io/badge/fastify-v4.26-%23FFB000?labelColor=000000">|
|<img height="60" src="https://cdn.worldvectorlogo.com/logos/prisma-3.svg"> | <img alt="prisma version" src="https://img.shields.io/badge/prisma-v5.9-%23FFB000?labelColor=000000">|
|<img height="67" src="https://raw.githubusercontent.com/colinhacks/zod/master/logo.svg"> | <img alt="zod version" src="https://img.shields.io/badge/zod-v3.22-%23FFB000?labelColor=000000">|
|<img height="53" src="https://cdn.worldvectorlogo.com/logos/openai-2.svg"> | <img alt="openai version" src="https://img.shields.io/badge/openai-v4.26-%23FFB000?labelColor=000000"> |
|<img height="64" src="https://cdn.worldvectorlogo.com/logos/react-2.svg"> | <img alt="react version" src="https://img.shields.io/badge/react-v18.2-%23FFB000?labelColor=000000"> |
|<img height="50" src="https://cdn.worldvectorlogo.com/logos/vitejs.svg"> | <img alt="vite version" src="https://img.shields.io/badge/vite-v4.5-%23FFB000?labelColor=000000">|
|<img height="40" src="https://cdn.worldvectorlogo.com/logos/tailwind-css-2.svg"> | <img alt="tailwind version" src="https://img.shields.io/badge/tailwind-v3.4-%23FFB000?labelColor=000000">|
|<img height="45" src="https://cdn.worldvectorlogo.com/logos/typescript.svg"> | <img alt="typescript version" src="https://img.shields.io/badge/typescript-v5.5-%23FFB000?labelColor=000000"> |
|<img height="48" src="https://cdn.worldvectorlogo.com/logos/eslint-1.svg"> | <img alt="eslint version" src="https://img.shields.io/badge/eslint-v8.56-%23FFB000?labelColor=000000"> |

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
