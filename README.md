# Bash Scripts Collection

**Author:** Toni Mertanen

This repository contains a collection of useful Bash scripts designed to automate various tasks. Below are descriptions of each script:

## Scripts

- **gauto**: This script is used to automate the process of initializing npm/typescript/prettier/eslint/ts-node/express/nodemon/browser-sync and type libraries for express/node/mocha/chai for JavaScript project or pylint/mypy/black for Python project and initializing git and creating the .gitignore, linking the local repo with the remote one, adding and committing the changes with user given message to the the remote repository. If typescript is installed it also adds predev script which run automatically when npm run dev is used. The script will start tsc compiling in watch mode. When npm run dev is used it will start nodemon and browser syncing. With script it is also possible to automate running of code formatter and linter before each git commit. Script will run the necessary commands and ask for user input when needed.
- **guessNumber**: A simple number guessing game where the user guesses a number, and the script provides feedback.
- **readLines**: Reads lines from a file and processes them.
- **simpleCountdown**: Implements a countdown timer that counts down from a user-specified number of seconds.
