# Playwright Test Suite

## Author

**Juan Sebastian Zapata**

---

## Description

This project is a Playwright-based test automation suite designed for LoopQA technical evaluation. It uses **TypeScript** and follows best practices such as the **Page Object Model (POM)** to ensure maintainability and scalability.

---

## Prerequisites

Before running the tests, ensure you have the following installed:

1. **Node.js**: Version `18.20.x` is required.
2. **npm**: Comes bundled with Node.js.
3. A modern browser (I used Chrome-Chromium) (Playwright will handle browser installation automatically). by running

```bash
> npx playwright install
```

---

## Installation

Follow these steps to set up the project:

1. Clone the repository:

   ```bash
   git clone <repository-url>
   cd <repository-directory>
   ```

2. Copy the file `.env-template` and change the name to `.env` (I left the values there since is not sencitive data, otherwise, this file is going to be empty)

3. Install dependencies:

   ```bash
   npm i
   ```

4. Install browsers if not installed

   ```bash
   npx playwright install
   ```

5. Run tests:

   ```bash
   # For running test in standalone version
   > npm run tests

   # For running tests with the ui
   > npm run test:ui
   ```

6. Visualize reports:

   ```bash
   > npm run test:show-report
   ```

## Notes:

Thanks for the opportunity!
