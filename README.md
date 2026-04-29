# Java Selenium Automation

A Java-based web automation testing framework built with Selenium WebDriver and TestNG, supporting parallel, group, and suite-level test execution.

---

## 📁 Project Structure

```
Java-selenium/
├── .settings/              # Eclipse IDE project settings
├── Apache/                 # Apache configuration or related libraries
├── Data/                   # Test data files
├── Screenshots/            # Captured screenshots during test runs
├── bin/                    # Compiled class files
├── drivers/                # Browser driver binaries (ChromeDriver, GeckoDriver, etc.)
├── lib/                    # External JAR dependencies
├── src/                    # Java source code (test scripts and page objects)
├── test-output/            # TestNG-generated test reports
├── upload/                 # Files used for upload test scenarios
├── .classpath              # Eclipse classpath configuration
├── .project                # Eclipse project configuration
├── AutomationSuite1.xml    # TestNG suite file – Automation Suite 1
├── AutomationSuite2.xml    # TestNG suite file – Automation Suite 2
├── GroupExecution1.xml     # TestNG XML for group-based test execution (set 1)
├── GroupExecution2.xml     # TestNG XML for group-based test execution (set 2)
├── ParellelExecution.xml   # TestNG XML for parallel test execution
├── parameter.xml           # TestNG XML with parameterized test configurations
├── practice.xml            # TestNG XML for practice/sandbox test runs
├── testing.txt             # Notes or scratch test output
└── ScreenshotsFacebook – log in or sign up.png  # Reference screenshot for Facebook login test
```

---

## 🛠️ Tech Stack

| Tool/Library       | Purpose                              |
|--------------------|--------------------------------------|
| Java               | Primary programming language         |
| Selenium WebDriver | Browser automation                   |
| TestNG             | Test framework and execution engine  |
| Eclipse IDE        | Development environment              |
| Apache (lib)       | Supporting utilities/libraries       |

---

## ✅ Features

- **Suite Execution** – Run full automation suites via `AutomationSuite1.xml` and `AutomationSuite2.xml`
- **Group Execution** – Selectively run test groups using `GroupExecution1.xml` and `GroupExecution2.xml`
- **Parallel Execution** – Run tests concurrently using `ParellelExecution.xml`
- **Parameterized Tests** – Pass dynamic parameters to tests via `parameter.xml`
- **Screenshot Capture** – Automatic screenshot capture saved to the `Screenshots/` directory
- **Data-Driven Testing** – External test data managed under the `Data/` folder
- **Cross-Browser Support** – Browser drivers managed in the `drivers/` directory

---

## 🚀 Getting Started

### Prerequisites

- Java JDK 8 or higher
- Eclipse IDE (recommended) or any Java IDE
- TestNG plugin installed in your IDE
- Browser drivers (ChromeDriver / GeckoDriver) placed in the `drivers/` folder

### Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/Kishor-Arasiddi/Java-selenium.git
   ```

2. Open the project in Eclipse:
   - `File` → `Import` → `Existing Projects into Workspace`
   - Select the cloned folder

3. Add JAR dependencies from the `lib/` folder to your build path:
   - Right-click project → `Build Path` → `Configure Build Path` → `Add JARs`

4. Place the appropriate browser drivers in the `drivers/` folder and update the driver path in your source code if needed.

---

## ▶️ Running Tests

### Run a Full Suite
Right-click on any `.xml` file in Eclipse and select **Run As → TestNG Suite**.

| XML File                | Description                        |
|-------------------------|------------------------------------|
| `AutomationSuite1.xml`  | Full automation suite – batch 1    |
| `AutomationSuite2.xml`  | Full automation suite – batch 2    |
| `GroupExecution1.xml`   | Group-filtered execution – set 1   |
| `GroupExecution2.xml`   | Group-filtered execution – set 2   |
| `ParellelExecution.xml` | Parallel multi-threaded execution  |
| `parameter.xml`         | Parameterized test execution       |
| `practice.xml`          | Practice / exploratory test runs   |

---

## 📸 Screenshots

Failed or captured test screenshots are automatically saved to the `Screenshots/` directory. A sample reference screenshot (`ScreenshotsFacebook – log in or sign up.png`) is included to demonstrate the Facebook login test scenario.

---

## 📊 Test Reports

TestNG generates HTML reports automatically after each run. Find them under:
```
test-output/
├── index.html       ← Main test report
├── emailable-report.html
└── ...
```

---

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch: `git checkout -b feature/your-feature`
3. Commit your changes: `git commit -m "Add your feature"`
4. Push and open a Pull Request

---
