# quick-calc

<<<<<<< HEAD
## Instructions for `dev-agk`

Clone this repository to your local machine

```bash
git clone git@github.com:dev-agk/quick-calc.git
```

Switch to your dev branch

```bash
git checkout dev_2
```

## Instructions for `juzQrios`

Clone this repository to your local machine

```bash
git clone git@github.com:dev-agk/quick-calc.git
```

Switch to your dev branch

```bash
git checkout dev_1
```
## References
WebPack -> https://webpack.js.org/concepts/
NVM -> https://medium.com/@Joachim8675309/installing-node-js-with-nvm-4dc469c977d9


=======
Hey AGK, try out anything/everything in this branch.

## JavaScript Project Setup

1. `npm init -y`
2. `npm install --save-dev eslint webpack webpack-cli`
    Add `node_modules` to `.gitignore` -- I think you could skip it, as VS Code prompts you to do it anyway.
3. `npx eslint --init` 

Select:
  - To check syntax, find problems, and enforce code style
  - JavaScript modules (import/export)
  - None of these
  - Browser
  - Use a popular style guide
  - Airbnb
  - JSON
  - Y

4. Add `webpack.config.js` with following content

```
const path = require('path');

module.exports = {
  entry: './src/index.js',
  output: {
    filename: 'main.js',
    path: path.resolve(__dirname, 'dist'),
  },
};
```
  Add following line to `package.json`:
  ```
  ...
  "scripts": {
      "test": "jest",
      "build-dev": "webpack -d --watch --mode development"
    },
  ...
  ```

5. Add `.eslintignore` file with following content

```
/dist/main.js
webpack.config.js
```

6. Add `src` & `dist` folders

つづく
>>>>>>> 5a32b079d49d6e482935c4eb9a70e72b856439b0
