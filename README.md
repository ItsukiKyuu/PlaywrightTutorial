# PlaywrightTutorial
Learning playwright


install:  npm init playwright@latest


reports:  npx playwright show-report


run all tests:  npx playwright test

run one test:  npx plywright test landing-page.spec.ts

run a set of tests:  npx playwright test tests/todo-page/ tests/landing-page/

run files with landing or login:  npx playwright test landing login

run test with title:  npx playwright test -g "add a todo item"

run test in headed mode:  npx playwright test landing-page.spec.ts --headed

run test on specific project:  npx playwright test landing-page.ts --project=chromium


debug all tests:  npx playwright test --debug

debug one test:  npx playwright test example.spec.ts --debug

debug test from line with defined test:  npx playwright test example.spec.ts:42 --debug


run codegen:  npx playwright codegen demo.playwright.dev/todomvc


trace on:  npx playwright test --trace on


show folder:  npx playwright show-report name-of-my-extracted-playwright-report