## Don't forget to give a :star: to make the project popular.

## :question: What is this Repository about?

This project is the outcome of my self-learning mobile test automation with [WebDriverIO](https://webdriver.io/) Test Automation framework

## :briefcase: What does this repo contain?
- This repo contains example codes of Android Mobile Automation with TypeScript using [WebdriverIO Demo App](https://github.com/webdriverio/native-demo-app/releases) 
- Checkout [this page](https://webdriver.io/docs/typescript/) for more details related to WebDriverIO TypeScript Setup.

## Scenario covered
- On the Home page of the WebDriverIO demo app, verify the title `WEBDRIVER` is displayed correctly.
- Navigate to the Login page, login using dummy credential and check the success message text and its title.

## Running the tests 
- [NodeJS](https://nodejs.org/en/download/) should be installed on the local machine where tests needs to be run.
- Clone this repository using the command `git@github.com:mfaisalkhatri/webdriverio_tutorial.git`
- Navigate to the root folder of the project and Run the command `npm install`
- To run the tests - `npm run wdio`
- To generate allure report: 
  - brew install allure
  - allure server ./allure-results
  - Checkout [allure Reporter](https://webdriver.io/docs/allure-reporter/) for more details

Thanks to - https://www.linkedin.com/in/faisalkhatri for helping the community by sharing the knowledge.
