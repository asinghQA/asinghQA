# Mobile Automation Testing Frameworks and Tools

This hybrid framework is used for automation testing using different types of drivers and is supported for the following platforms:
* Android ([UiAutomator2](https://developer.android.com/training/testing/other-components/ui-automator))
* iOS ([XCUITest](https://developer.apple.com/documentation/xctest/user_interface_tests))
## Test Suite Execution Flow
* **Jenkins Integration**:
  * The automation test suite is initiated through Jenkins.
  * Jenkins executes the Maven build tool.
* **TestNG Execution**:
  * The Maven build triggers the execution of a TestNG file.
  * The TestNG file launches the test suite.
* **Appium Integration**:
  * The test suite communicates with the Appium server.
  * Appium acts as a bridge between the automation test code and the testing device.
  * This enables the automation testing of UI functionalities.
## Key Tools Used
1. **[Appium](https://appium.io/docs/en/latest/intro/)**:
   * Simplifies mobile app automation by leveraging the WebDriver protocol.
   * Provides a consistent approach for testing across diverse platforms.
2. **[Maven](https://maven.apache.org/)**:
   * Improves the build process, provides project information, and encourages best practices for Java-based projects.
3. **[TestNG](https://testng.org/)**:
   * Provides a flexible and robust testing framework for Java applications.
   * Covers various testing scenarios.
4. **[Selenium Grid](https://www.selenium.dev/documentation/grid/)**:
   * Empowers efficient, scalable, and cross-browser testing by distributing test execution across multiple machines.
5. **[Extent Report](https://www.extentreports.com/docs/versions/5/java/index.html)**:
   * Enhances test reporting by providing detailed, interactive, and visually appealing reports.
6. **[Sikuli](https://sikulix.com/)**:
   * Used to automate GUI interactions by leveraging image recognition.
   * Valuable for both web and desktop automation.
   * We use for handling map interactions like pan, edit features, and zoom.
## Capabilities
* **Parallel Execution**:
   * Allows parallel execution of tests.
* **Cross-Platform Testing**:
   * Supports multiple operating systems for compatibility testing (Android 13, 14, iOS 15.5, 16.4 and 17.2, etc.).
* **Device Compatibility**:
   * Supports several types of devices. (Pixel 7. Pixel 6a, iPhone 11, iPhone 12, etc.)
* **Real Device Testing**:
   * Can run on real devices for both Android and iOS.
