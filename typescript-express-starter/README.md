<img src='https://github.com/ljlm0402/typescript-express-starter/raw/master/typescript-express-starter.jpg' border='0' alt='logo' />

[Express](https://www.npmjs.com/package/express) with [TypeScript's](https://www.npmjs.com/package/typescript) application generator.

<a href="https://www.npmjs.com/package/typescript-express-starter" target="_blank"><img src="https://img.shields.io/npm/v/typescript-express-starter.svg" alt="NPM Version" /></a>
<a href="https://www.npmjs.com/package/typescript-express-starter" target="_blank"><img src="https://img.shields.io/npm/l/typescript-express-starter.svg" alt="Package License" /></a>
<a href="https://www.npmjs.com/package/typescript-express-starter" target="_blank"><img src="https://img.shields.io/npm/dm/typescript-express-starter.svg" alt="NPM Downloads" /></a>

<br />

## 🧐 What is it?

Creates a new typescript express application.
application is configured to use TypeScript instead of plain JavaScript. 

## 🤔 Why typescript-express-starter?

Node Js is great for the rapid development of web-projects, but is often neglected because of the lack of
type safety. TypeScript solves this issue and (along with its linter file) can even make your code
more robust than some other static languages like Java.

## ⚙️ Installation

```sh
$ npm install -g typescript-express-starter
```

## 🚀 Quick Start

The quickest way to get started is use npx and pass in the name of the project you want to create.
If you don't specify a project name, the default _typescript-express-starter_ will be used instead.

### 1. Create the app

```bash
$ npx typescript-express-starter "project name"
```

Choose the template you want. We will create more templates later.

### 2. Select a templates 

<img src='https://github.com/ljlm0402/typescript-express-starter/raw/master/typescript-express-starter.gif' border='0' alt='example' />

Start your typescript-express-starter app in development mode at `http://localhost:3000/`

```bash
$ cd "project name" && npm run start
```

## 🎠 Available commands for the server.

- Run the Server in production mode : `npm run start`.
- Run the Server in development mode : `npm run dev`.
- Run all unit-tests: `npm run test`.
- Check for linting errors: `npm run lint`.

You may need to install [nodemon](https://www.npmjs.com/package/nodemon) separately if you do not currently have it installed on your machine.

## ⛑ Code Structure (default)

```bash
│
├── /src
│   ├── /controllers
│   │   ├── auth.controller.ts
│   │   ├── index.controller.ts
│   │   └── users.controller.ts
│   │
│   ├── /dtos
│   │   └── user.dto.ts
│   │
│   ├── /exceptions
│   │   └── HttpException.ts
│   │
│   ├── /interfaces
│   │   ├── auth.interface.ts
│   │   ├── routes.interface.ts
│   │   └── user.interface.ts
│   │
│   ├── /middlewares
│   │   ├── auth.middleware.ts
│   │   ├── error.middleware.ts
│   │   └── validation.middleware.ts
│   │
│   ├── /models
│   │   └── users.model.ts
│   │
│   ├── /routes
│   │   ├── auth.route.ts
│   │   ├── index.route.ts
│   │   └── users.route.ts
│   │
│   ├── /services
│   │   ├── auth.service.ts
│   │   └── user.service.ts
│   │
│   ├── /tests
│   │   ├── auth.test.ts
│   │   ├── index.test.ts
│   │   └── users.test.ts
│   │
│   ├── /utils
│   │   ├── util.ts
│   │   └── vaildateEnv.ts
│   │
│   ├── app.ts
│   └── server.ts
│
├── .env
├── .gitignore
├── jest.config.js
├── package-lock.json
├── package.json
├── tsconfig.json
└── tslint.json
```

## License

[MIT](LICENSE)

## Contributors

* Jeongwon Kim [https://github.com/swtpumpkin](https://github.com/swtpumpkin)

* Lloyd Park [https://github.com/yeondam88](https://github.com/yeondam88)

* BitYoungjae [https://github.com/BitYoungjae](https://github.com/BitYoungjae)

* strama4 [https://github.com/strama4](https://github.com/strama4)

* João Silva [https://github.com/joaopms](https://github.com/joaopms)

* sonbyungjun [https://github.com/sonbyungjun](https://github.com/sonbyungjun)
