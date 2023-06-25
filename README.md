## **KhanAcademy WebdriverIO MobileApplicationTesting** 👨‍💻👨‍💻

## Introduction

The Khan Academy Mobile Application Testing repository aims to provide automated tests for the Khan Academy mobile application using the WebdriverIO testing framework. By automating the testing process, it becomes easier to ensure the application functions correctly and maintains its quality across different mobile platforms.

## Prerequisites🧰

Before you begin, ensure you have the following prerequisites installed on your system:

Node.js (v12 or above)
npm (Node Package Manager)

## Installation

To install the necessary dependencies, follow these steps:

Clone the repository to your local machine.

Navigate to the project directory.

Run the following command to install the dependencies:

```bash
npm install
```

## Configuration


Before running the tests, you need to configure the testing environment. The configuration can be found in the wdio.conf.js file.

In this file, you can specify the following settings:

###  Appium Configuration: Set the desired capabilities for the Appium server, including the platform, device name, and application path.
Test Environment Configuration: Specify the test environments details, such as the base URL and timeouts.
Test Suite Configuration: Customize the test suite by adding or modifying test files, defining test frameworks, or configuring reporters.
Make sure to update the necessary configuration settings to match your testing environment.

Running Tests
To run the tests, use the following command:

```bash
npx wdio
```
This command will execute the test suite using the configurations specified in the wdio.conf.js file.

## Test Reporting
Test reports are generated using the wdio-spec-reporter package. The reports will be displayed in the console during test execution, providing information about the test results, durations, and any failures or errors encountered.




Additionally, a detailed HTML report will be generated in the ./test-report directory after the test run is completed.

I generate the timeline report for this project and deployed this on netlify 
```bash
https://khanacademyreportwebdriverio.netlify.app/
```


## Thank you for visiting 😇 Show your support

#Give a ⭐️ if you like this project!
