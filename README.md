🚀 MPS Playwright UI Automation Framework
A lightweight and scalable UI automation framework built using Playwright for the MPS Application, designed for ease of use, fast execution, and rich reporting via Allure.

📦 Features
✅ Built on Playwright
📊 Integrated with Allure Reports
🧪 Supports modular test structure
🔄 Easy configuration and environment setup
🧹 Auto cleanup and retry logic
📁 Page Object Model (POM) structure
🧵 Parallel test execution
📤 CI/CD read

🛠️ Tech Stack
Language: TypeScript / JavaScript
Test Runner: Playwright Test
Reporting: Allure
CI/CD: GitHub Actions / Jenkins (optional)

📁 Project Structure
├── tests/                # Test specs
├── pages/                # Page objects
├── utils/                # Helpers and utilities
├── reports/              # Allure reports
├── playwright.config.ts  # Playwright configuration
└── README.md             # Project documentation

🚀 Getting Started:-
# Install dependencies
npm install

# Run tests
npx playwright test

# Generate Allure report
npx allure generate reports/allure-results --clean -o reports/allure-report
npx allure open reports/allure-report

