To install Playwright & Select Configurations
npm init playwright@latest
select the below options while installing

Getting started with writing end-to-end tests with Playwright:
Initializing project in '.'
✔ Do you want to use TypeScript or JavaScript? · JavaScript
✔ Where to put your end-to-end tests? · tests
✔ Add a GitHub Actions workflow? (y/N) · false
✔ Install Playwright browsers (can be done manually via 'npx playwright install')? (Y/n) · false

✔ /Users/anbu.pandian/Documents/brit/brit_apitests/playwright.config.js already exists. Override it? (y/N) · true


node_modules
playwright.config.js
package.json
package-lock.json
tests/ example.spec.js
tests-examples/ demo-todo-app.spec.js

delete the below files
tests/ example.spec.js

delete the below folder
tests-examples


To start the interactive UI mode 
npx playwright test --ui 

To run end to end tests with reports
npx playwright test --reporter html

To view reports
open - playwright-report  - index.html in browser

