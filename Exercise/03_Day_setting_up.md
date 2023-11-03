
# Level 1 React Exercises

### What is a module?
- A module is a self-contained unit of code in a program. It encapsulates a specific functionality and can be used to organize and manage code in a modular and maintainable way.

### What is a package?
- A package is a collection of modules and resources that are bundled together for distribution. Packages typically include metadata and dependencies needed for a software component to function.

### What is the difference between a module and a package?
- A module is a single unit of code, while a package is a collection of modules and resources bundled together. Modules are used to organize code within a program, while packages are used to distribute and manage dependencies in software projects.

### What is NPM?
- NPM (Node Package Manager) is a package manager for JavaScript. It is used to install, manage, and publish packages and modules, making it easier for developers to work with external code libraries and dependencies.

### What is Webpack?
- Webpack is a popular open-source JavaScript module bundler. It is used to bundle and package JavaScript, CSS, and other assets into optimized files for use in web applications. Webpack is often used in conjunction with modern JavaScript frameworks like React.

### How do you create a new React project?
- To create a new React project, you can use a tool called "Create React App." Here are the steps:
   1. Open your terminal.
   2. Run the following command: `npx create-react-app my-react-app` (replace "my-react-app" with your project name).
   3. Once the project is created, navigate to the project folder using `cd my-react-app`.
   4. You can start the development server with `npm start`.

### What are the files and folders inside a project folder (package.json, package-lock.json or yarn.lock, .gitignore, node_modules, and public)?
- Inside a typical React project folder, you'll find:
   - `package.json`: A file that describes the project, including its name, version, dependencies, and scripts.
   - `package-lock.json` or `yarn.lock`: Files that lock the versions of project dependencies to ensure consistency.
   - `.gitignore`: A file that specifies which files and directories should be ignored by version control (e.g., Git).
   - `node_modules`: A directory that contains the project's dependencies (libraries and modules).
   - `public`: A directory for static assets that will be served as-is, like HTML, images, and manifest files.

### What is your favorite code editor (I believe that it is Visual Studio Code)?
- Yes, Visual Studio Code is a popular code editor and widely used by developers for its features, extensions, and flexibility. It's a versatile and extensible editor suitable for a wide range of programming languages and projects.

### Add different Visual Studio Code extensions to improve your productivity (e.g., Prettier, ESLint, etc).
- Visual Studio Code has a rich ecosystem of extensions. Some popular ones for improving productivity include:
   - **Prettier**: Code formatter for various languages.
   - **ESLint**: JavaScript linter for identifying and fixing code issues.
   - **GitLens**: Enhances Git integration with annotations and more.
   - **Auto Rename Tag**: Automatically renames paired HTML/XML tags.
   - **Live Server**: Launches a local development server for live preview.
   - **Bracket Pair Colorizer**: Matches and colorizes bracket pairs for better code readability.

### Try to make a different custom module in a different file and import it into index.js.
- You can create a custom module by creating a separate JavaScript file (e.g., `myModule.js`) and then importing it into your `index.js` file. Here's an example:

**myModule.js**
```javascript
// myModule.js
export const greeting = "Hello, World!";
```

**index.js**
```javascript
// index.js
import { greeting } from "./myModule.js";

console.log(greeting); // Output: Hello, World!
```

In this example, we've created a custom module (`myModule.js`) with an exported variable (`greeting`) and imported it into `index.js`.

