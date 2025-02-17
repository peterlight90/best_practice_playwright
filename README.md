
## Prerequisites
```
VSCode
Nodejs: ^16.15.0
Playwright
Typescript
```

## Reference
- Playwright Typescript -> https://playwright.dev/docs/test-typescript
- Best Practice         -> https://playwright.dev/docs/best-practices
- Allure Report         -> https://allurereport.org/docs/playwright/
- Practice site         -> 

## Installation
- Install Nodejs -> https://nodejs.org/en/download/

Navigate to project folder and execute command below
```bash
npm install             <- installs dependencies listed in package.json
```

### Run on local machine
- Windows
```bash
$env:ENV = 'dev'        <- Set ENV
npm run test            <- Run test with env was set or use default
```

- MAC/Linux
```bash
npm run test            <- Run all test with default environment
npm run test:dev        <- Run all test with dev environment
```

## Project Structure

```
-----------
    ├── pages                       <- Page Object Model (POM) for web/mobile  
    ├── fixtures                    <- Test data (e.g., mock data, JSON files)
    ├── tests                       <- Included script to run testcases
    ├── utils                       <- Included all utility functions
    ├── .eslintrc                   <- ESLint format file
    ├── .gitignore                  <- Git ignore file
    ├── .prettierrc                 <- Prettier format file
    ├── package.json                <- Included information about source, package, requires, scripts,...
    ├── playwright.config.ts        <- playwright configuring
    ├── README.md                   <- The top-level README for users using this project.
    ├── setup.ts                    <- Init setup for test
    ├── .env
    └── tsconfig.json               <- Compile option to convert TS to JS.
```
## Author
```
Name: Minh Pham (Peter)
Email: peterlight90@gmail.com
```
