# Hello Microverse Project

> Built this project as part of the Microverse code reviewing exercise and training.

## Built With

- HTML, CSS
- Github flow
- VSCode

## Getting Started
- git clone https://github.com/dumbledorep/Hello-Microverse.git
## Github Actions set-up:
- In the first commit of your feature branch create a .github/workflows folder and add a copy of .github/workflows/linters.yml to that folder.
Remember to use the file linked above
Remember that .github folder starts with a dot.
## Set-up linters in your local env
Note: The npm package manager is going to create a node_modules directory to install all of your dependencies. You shouldn't commit that directory. To avoid that, you can create a .gitignore file and add node_modules to it:
      # .gitignore
      node_modules/
## Webhint
NOTE: If you are running on Windows, you need to initialize npm to create package.json file.
- Run this code to create the package.json file: npm init -y
- Run npm install --save-dev hint@7.x
- Copy .hintrc to the root directory of your project.
- Run npx hint .
## Stylelint
- Run npm install --save-dev stylelint@13.x stylelint-scss@3.x stylelint-config-standard@21.x stylelint-csstree-validator@1.x
- Copy .stylelintrc.json to the root directory of your project.
- Run npx stylelint "**/*.{css,scss}" on the root of your directory of your project.
- Fix linter errors

With that being done you are good to issue a pull request if need be.

## Author

👤 **Philip Kweku Assan**

- GitHub: [@dumbledorep](https://github.com/dumbledorep)
- Twitter: [@assanphilip17](https://twitter.com/assanphilip17)
- LinkedIn: [LinkedIn](https://www.linkedin.com/in/philip-assan-142735162/)

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!

Feel free to check out the [issues page](https://github.com/dumbledorep/Hello-Microverse/issues).

## Show your support

Give a ⭐️ if you like this project!

## Acknowledgments

- Hat tip to anyone whose code was used
- Inspiration
- etc

## 📝 License

This project is [MIT](https://github.com/microverseinc/readme-template/blob/master/MIT.md) licensed.