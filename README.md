# LeetCode Automation

## Scope of Work

This project focuses on automating the following test cases for the LeetCode application:

1. **Verify the LeetCode Homepage URL**
   - Ensures that the homepage URL loads correctly.

2. **Verify Problem Set URL and Display First 5 Questions**
   - Validates that the problem set URL is accessible and displays the first five questions correctly.

3. **Verify the Two Sum Problem**
   - Tests the functionality of accessing and displaying the Two Sum problem.

4. **Ensure the Submissions Tab Displays "Register or Sign In"**
   - Verifies that unauthenticated users are prompted to register or sign in on the submissions tab.

---

## Skills Used

- **Selenium**: Used for automating the browser-based testing of the LeetCode web application.
- **Dynamic XPath**: Utilized to locate elements on the web pages effectively.

---

## Setup Instructions

1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd LeetCode_Automation
   ```

2. Install dependencies:
   - Ensure you have **Java JDK 11+** installed.
   - Install **Selenium WebDriver** and required browser drivers (e.g., ChromeDriver).
   
3. Configure `testng.xml`:
   - Define your test suite and include/exclude test cases as required.

4. Run the test cases:
   ```bash
   mvn test
   ```

---

## Features

- **Targeted Test Coverage**: Ensures critical functionalities of LeetCode are tested.
- **Dynamic Element Handling**: Leverages dynamic XPath for robust element location.
- **Cross-Browser Compatibility**: Supports tests on multiple browsers.
- **Detailed Reporting**: Generates test execution reports with TestNG.

---

