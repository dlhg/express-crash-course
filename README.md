# Express Crash Course

This is a simple Express.js application that comes from this YouTube tutorial video by Web Dev Simplified. 

## Project Structure

```
.
├── package.json
├── public/
│   ├── index.html
│   └── test/
│       └── test.html
├── routes/
│   └── users.js
├── server.js
└── views/
    └── users/
        └── new.ejs
```

## Key Files

- [`package.json`](command:_github.copilot.openSymbolInFile?%5B%22package.json%22%2C%22package.json%22%5D "package.json"): Contains the list of project dependencies and scripts.
- [`public/index.html`](command:_github.copilot.openSymbolInFile?%5B%22public%2Findex.html%22%2C%22public%2Findex.html%22%5D "public/index.html"): The main HTML file that is served when you access the root of the server.
- [`public/test/test.html`](command:_github.copilot.openSymbolInFile?%5B%22public%2Ftest%2Ftest.html%22%2C%22public%2Ftest%2Ftest.html%22%5D "public/test/test.html"): A test HTML file.
- [`routes/users.js`](command:_github.copilot.openSymbolInFile?%5B%22routes%2Fusers.js%22%2C%22routes%2Fusers.js%22%5D "routes/users.js"): Defines the routes related to users.
- [`server.js`](command:_github.copilot.openSymbolInFile?%5B%22server.js%22%2C%22server.js%22%5D "server.js"): The entry point to the application. This file defines our Express server, sets it up and starts it.
- [`views/users/new.ejs`](command:_github.copilot.openSymbolInFile?%5B%22views%2Fusers%2Fnew.ejs%22%2C%22views%2Fusers%2Fnew.ejs%22%5D "views/users/new.ejs"): The EJS template for the new user form.

## Running the Project

To run this project, you need to have Node.js installed. Once you have Node.js installed, follow these steps:

1. Install the project dependencies:

```sh
npm install
```

2. Start the server:

```sh
npm run devStart
```

The server will start on port 3000. You can access it at `http://localhost:3000`.

## Features

- Serve static files from the [``public``](command:_github.copilot.openRelativePath?%5B%7B%22scheme%22%3A%22file%22%2C%22authority%22%3A%22%22%2C%22path%22%3A%22%2Fc%3A%2FUsers%2F14388%2Fcode%2Fexpress-crash-course%2Fpublic%22%2C%22query%22%3A%22%22%2C%22fragment%22%3A%22%22%7D%5D "c:\Users\14388\code\express-crash-course\public") directory.
- Render dynamic HTML using EJS templates.
- Handle form submissions with the Express [`urlencoded`](command:_github.copilot.openSymbolFromReferences?%5B%7B%22%24mid%22%3A1%2C%22external%22%3A%22file%3A%2F%2F%2Fc%253A%2FUsers%2F14388%2FAppData%2FLocal%2FMicrosoft%2FTypeScript%2F5.4%2Fnode_modules%2F%2540types%2Fbody-parser%2Findex.d.ts%22%2C%22path%22%3A%22%2FC%3A%2FUsers%2F14388%2FAppData%2FLocal%2FMicrosoft%2FTypeScript%2F5.4%2Fnode_modules%2F%40types%2Fbody-parser%2Findex.d.ts%22%2C%22scheme%22%3A%22file%22%7D%2C%7B%22line%22%3A33%2C%22character%22%3A8%7D%5D "../../AppData/Local/Microsoft/TypeScript/5.4/node_modules/@types/body-parser/index.d.ts") middleware.
- Organize routes with the Express [`Router`](command:_github.copilot.openSymbolFromReferences?%5B%7B%22%24mid%22%3A1%2C%22path%22%3A%22%2FC%3A%2FUsers%2F14388%2FAppData%2FLocal%2FMicrosoft%2FTypeScript%2F5.4%2Fnode_modules%2F%40types%2Fexpress%2Findex.d.ts%22%2C%22scheme%22%3A%22file%22%7D%2C%7B%22line%22%3A62%2C%22character%22%3A4%7D%5D "../../AppData/Local/Microsoft/TypeScript/5.4/node_modules/@types/express/index.d.ts").

## Dependencies

- [Express.js](https://expressjs.com/): A fast, unopinionated, minimalist web framework for Node.js.
- [EJS](https://ejs.co/): Embedded JavaScript templates.
