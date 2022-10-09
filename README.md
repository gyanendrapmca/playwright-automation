1. Installing pnpm globally
`npm install -g pnpm`
2. Create the framework using pnpm
`pnpm dlx create-playwright`
3. Runs the end-to-end tests
`pnpm dlx playwright test`
4. Runs the tests only on Desktop Chrome
`pnpm dlx playwright test --project=chromium`
5. Runs the tests in a specific file
`pnpm dlx playwright test example`
6. Runs the tests in debug mode
`pnpm dlx playwright test --debug`
7. Auto generate tests with Codegen
`pnpm dlx playwright codegen`
