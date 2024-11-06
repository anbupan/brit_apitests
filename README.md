To install Playwright & Select Configurations
npm init playwright@latest
select Javascript in the options between javascript and typescript
Playwright will download the browsers needed as well as create the following files.

node_modules
playwright.config.js
package.json
package-lock.json
tests/ example.spec.js
tests-examples/ demo-todo-app.spec.js

delete the below files
tests/ example.spec.js
tests-examples/ demo-todo-app.spec.js
delete the below folder
tests-examples


To start the interactive UI mode 
npx playwright test --ui 

To run end to end tests
npx playwright test

