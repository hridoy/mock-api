\# Mock API

Its a simple mock api build by: 
1. [Json Server](https://github.com/typicode/json-server). For REST API 
2. [Json Schema Faker](https://github.com/json-schema-faker/json-schema-faker). Its a middle man between JSON Server and Random data generator library. 
3. [Faker.js](http://marak.github.io/faker.js/). Generate random data 
4. [Chance.js](http://chancejs.com/). Generate random data 
5. [Randexp.js](https://github.com/fent/randexp.js). Generate random data using regular expression

To see the pramater visit the random data library document

\## Little configure:
Change the randomData-dummy.js file name to randomData.js. By default dummy schema paramter added you can customizer based on your choice.

\## Get Started

1. **Clone this repository.** - `git clone https://github.com/hridoy/mock-api.git` or [download the zip](https://github.com/hridoy/mock-api/archive/master.zip)

2. **Make sure you're in the directory you just created.** - `cd mock-api`

4. **Install Node Packages.** - `npm install`

5. **Run the app.** - `npm start-mockapi`

This will run the automated build process, start up a webserver, and open the application in your default browser. When doing development with this kit, this command will continue watching files all your files. Every time you hit save the code is rebuilt, linting runs, and tests run automatically. Note: The -s flag is optional. It enables silent mode which suppresses unnecessary messages during the build.

6. Having issues? See below.

\## Having Issues? Try these things first:

1. Run `npm install` - If you forget to do this, you'll see this: `babel-node: command not found`.

2. Make sure you're running the latest version of Node. Or, use [Node 6.9.1](https://nodejs.org/en/download/releases/) if you're having issues on Windows. Node 7 has issues on some Windows machines.

3. Make sure files with names that begin with a dot (.babelrc, .editorconfig, .eslintrc) are copied to the project directory root. This is easy to overlook if you copy this repository manually.

4. Don't run the project from a symbolic link. It will cause issues with file watches.

5. Having linting issues? Delete any .eslintrc that you're storing in your user directory. Also, disable any ESLint plugin / custom rules that you've enabled within your editor. These will conflict with the ESLint rules defined in the course.

6. Seeing `Error: listen EADDRINUSE :::3001`? That means port 3001 is already in use on your machine. You probably have another instance of this project running on your machine in a different window. So find that window and kill the other instance using Ctrl+C.

7. Nothing above work? Delete your node_modules folder and re-run npm install.
