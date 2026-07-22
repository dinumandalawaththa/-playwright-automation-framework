# Playwright Automation Framework

A scalable, maintainable, and production-ready end-to-end test automation framework built with **Playwright** and **TypeScript**. This framework follows industry best practices, including the **Page Object Model (POM)**, reusable utilities, data-driven testing, and CI/CD integration.

---

## 🚀 Features

- End-to-End (E2E) UI Automation
- Cross-browser testing (Chromium, Firefox, WebKit)
- Page Object Model (POM)
- API Testing
- Data-driven testing
- Parallel test execution
- Automatic screenshots and videos on test failures
- HTML test reports
- Environment configuration support
- GitHub Actions CI/CD integration
- Easy to extend and maintain

---

## 🛠️ Technology Stack

- Playwright
- TypeScript
- Node.js
- npm
- Git
- GitHub Actions

---

## 📁 Project Structure

```text
playwright-automation-framework/
│
├── tests/                  # Test cases
├── pages/                  # Page Object Models
├── fixtures/               # Test fixtures
├── utils/                  # Utility functions
├── test-data/              # Test data
├── reports/                # HTML reports
├── screenshots/            # Failure screenshots
├── playwright.config.ts    # Playwright configuration
├── package.json
└── README.md
```

---

## ⚙️ Installation

Clone the repository:

```bash
git clone https://github.com/dinumandalawaththa/playwright-automation-framework.git
```

Navigate to the project:

```bash
cd playwright-automation-framework
```

Install dependencies:

```bash
npm install
```

Install Playwright browsers:

```bash
npx playwright install
```

---

## ▶️ Running Tests

Run all tests:

```bash
npx playwright test
```

Run tests in headed mode:

```bash
npx playwright test --headed
```

Run a specific test:

```bash
npx playwright test tests/login.spec.ts
```

Run tests in a specific browser:

```bash
npx playwright test --project=chromium
```

---

## 📊 Test Reports

Generate and open the HTML report:

```bash
npx playwright show-report
```

---

## 📸 Failure Evidence

This framework can be configured to automatically capture:

- Screenshots
- Videos
- Trace files

These artifacts help with debugging failed test executions.

---

## 🧪 Sample Test Scenarios

- User Login
- User Logout
- Product Search
- Add to Cart
- Checkout
- Form Validation
- API Response Validation

---

## 🔄 CI/CD

This framework is designed to integrate with GitHub Actions for automated test execution on every push or pull request.

Future enhancements include:

- Scheduled test execution
- Slack notifications
- Allure Reporting
- Docker support

---

## 📈 Future Improvements

- Docker support
- Allure Reports
- Database validation
- Visual testing
- Performance testing integration
- Mobile web testing

---

## 👨‍💻 Author

**Dinu Mandalawaththa**

Senior QA Engineer | Test Automation | API Testing | Playwright | Selenium

📍 New Zealand

---

## ⭐ Support

If you find this project useful, consider giving it a ⭐ on GitHub.
