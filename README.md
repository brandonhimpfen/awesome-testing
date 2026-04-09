# Awesome Testing [![Awesome Lists](https://srv-cdn.himpfen.io/badges/awesome-lists/awesomelists-flat.svg)](https://github.com/awesomelistsio/awesome)

[![GitHub Sponsors](https://srv-cdn.himpfen.io/badges/github/github-flat.svg)](https://github.com/sponsors/awesomelistsio) &nbsp;
[![Ko-Fi](https://srv-cdn.himpfen.io/badges/kofi/kofi-flat.svg)](https://ko-fi.com/awesomelists) &nbsp;
[![PayPal](https://srv-cdn.himpfen.io/badges/paypal/paypal-flat.svg)](https://www.paypal.com/donate/?hosted_button_id=3LLKRXJU44EJJ) &nbsp;
[![Stripe](https://srv-cdn.himpfen.io/badges/stripe/stripe-flat.svg)](https://tinyurl.com/e8ymxdw3) &nbsp;
[![X](https://srv-cdn.himpfen.io/badges/twitter/twitter-flat.svg)](https://x.com/ListsAwesome) &nbsp;
[![Facebook](https://srv-cdn.himpfen.io/badges/facebook-pages/facebook-pages-flat.svg)](https://www.facebook.com/awesomelists)

> A curated list of awesome testing frameworks, tools, libraries, and resources for all levels of software testing - from unit to end-to-end.

Testing ensures the correctness, reliability, and quality of software. This list helps developers, QA engineers, and testers find the right tools and practices to ship better software.

## Contents

- [General Resources](#general-resources)
- [Testing Types](#testing-types)
- [Unit Testing](#unit-testing)
- [Integration Testing](#integration-testing)
- [End-to-End (E2E) Testing](#end-to-end-e2e-testing)
- [Performance & Load Testing](#performance--load-testing)
- [Security Testing](#security-testing)
- [Web Accessibility Testing](#web-accessibility-testing)
- [Test Automation](#test-automation)
- [Mocking & Stubbing](#mocking--stubbing)
- [Code Coverage](#code-coverage)
- [Testing Tools by Language](#testing-tools-by-language)
- [Learning Resources](#learning-resources)
- [Related Awesome Lists](#related-awesome-lists)

## General Resources

- [Software Testing Fundamentals](https://softwaretestingfundamentals.com/) - Comprehensive site covering core testing concepts.
- [Ministry of Testing](https://www.ministryoftesting.com/) - Community, courses, and conferences for software testers.
- [Test Automation University](https://testautomationu.applitools.com/) - Free courses on test automation strategies and tools.

## Testing Types

- Unit Testing - Isolated testing of small code units or functions.
- Integration Testing - Tests interactions between components or systems.
- End-to-End (E2E) Testing - Simulates user interactions across the full stack.
- Performance Testing - Measures responsiveness, speed, and scalability.
- Security Testing - Identifies vulnerabilities and exploits.
- Regression Testing – Ensures new changes haven't broken existing features.
- Accessibility Testing – Verifies websites and apps are usable by people with disabilities per WCAG standards.

## Unit Testing

- [JUnit](https://junit.org/) - Java unit testing framework.
- [NUnit](https://nunit.org/) - Unit testing framework for .NET.
- [pytest](https://docs.pytest.org/) - Powerful testing framework for Python.
- [Jest](https://jestjs.io/) - JavaScript testing framework by Facebook.
- [AVA](https://avajs.dev/) - Node.js test runner with minimal configuration.

## Integration Testing

- [Testcontainers](https://www.testcontainers.org/) - Integration testing with Docker containers.
- [Supertest](https://github.com/visionmedia/supertest) - HTTP assertions for Node.js.
- [RestAssured](https://rest-assured.io/) - Java DSL for testing REST services.

## End-to-End (E2E) Testing

- [Cypress](https://www.cypress.io/) - Fast, reliable testing for anything that runs in a browser.
- [Playwright](https://playwright.dev/) - End-to-end browser automation by Microsoft.
- [Selenium](https://www.selenium.dev/) - Web automation across browsers and languages.
- [Puppeteer](https://pptr.dev/) - Headless Chrome Node.js API.
- [TestCafe](https://testcafe.io/) - Node.js tool for automated browser testing.

## Performance & Load Testing

- [JMeter](https://jmeter.apache.org/) - Apache performance testing tool.
- [k6](https://k6.io/) - Modern load testing tool for developers.
- [Gatling](https://gatling.io/) - Load testing as code for Scala/Java.
- [Artillery](https://www.artillery.io/) - Performance testing for modern apps.

## Security Testing

- [OWASP ZAP](https://www.zaproxy.org/) - Penetration testing tool for web apps.
- [Burp Suite](https://portswigger.net/burp) - Comprehensive web security testing.
- [Nikto](https://cirt.net/Nikto2) - Web server scanner.

## Web Accessibility Testing

- [Accessibility Insights](https://accessibilityinsights.io/) - Microsoft's free tool for web and Windows accessibility testing with guided assessments.
- [axe-core](https://github.com/dequelabs/axe-core) - Open-source accessibility testing engine by Deque, the industry standard used by Chrome DevTools and Microsoft.
- [Google Lighthouse](https://developer.chrome.com/docs/lighthouse/) - Built-in Chrome DevTools auditing for accessibility alongside performance, SEO, and best practices.
- [Pa11y](https://pa11y.org/) - Command-line accessibility testing tool, ideal for CI/CD pipeline integration and automated workflows.
- [WAVE](https://wave.webaim.org/) - Browser extension providing visual accessibility evaluation with issue icons overlaid on the page.

## Test Automation

- [Robot Framework](https://robotframework.org/) - Generic automation framework.
- [Sahi](https://sahipro.com/) - Web automation and testing tool.
- [Appium](https://appium.io/) - Automation for mobile apps.

## Mocking & Stubbing

- [WireMock](http://wiremock.org/) - HTTP mocking for integration testing.
- [Sinon.js](https://sinonjs.org/) - JavaScript mocks, spies, and stubs.
- [Mockito](https://site.mockito.org/) - Java mocking framework.

## Code Coverage

- [Istanbul/nyc](https://istanbul.js.org/) - JavaScript code coverage tool.
- [Cobertura](https://cobertura.github.io/cobertura/) - Code coverage for Java.
- [Codecov](https://about.codecov.io/) - Coverage reporting platform.
- [Coveralls](https://coveralls.io/) - Track test coverage over time.
- [bough](https://github.com/CodeEnPlace/bough) - Bough is a polyglot incremental mutation tester

## Testing Tools by Language

### JavaScript

- [Mocha](https://mochajs.org/)
- [Chai](https://www.chaijs.com/)
- [Jest](https://jestjs.io/)

### Python

- [pytest](https://docs.pytest.org/)
- [unittest](https://docs.python.org/3/library/unittest.html)

### Java

- [JUnit](https://junit.org/)
- [TestNG](https://testng.org/)

### Go

- [Testify](https://github.com/stretchr/testify)
- [GoConvey](https://github.com/smartystreets/goconvey)

### Ruby

- [RSpec](https://rspec.info/)
- [Minitest](https://github.com/seattlerb/minitest)

## Learning Resources

- [Testing JavaScript by Kent C. Dodds](https://testingjavascript.com/) - Hands-on testing courses.
- [Google Testing Blog](https://testing.googleblog.com/) - Testing strategies and tools.
- [Awesome Test Automation](https://github.com/atinfo/awesome-test-automation) - Curated test automation list.

## Related Awesome Lists

- **[Awesome QA](https://github.com/awesomelistsio/awesome-qa)** - Resources for quality assurance and testing professionals.
- **[Awesome Test Automation](https://github.com/awesomelistsio/awesome-test-automation)** - Collection of test automation resources.
- **[Awesome CI](https://github.com/awesomelistsio/awesome-ci)** - Continuous integration tools and platforms.

## Contribute

Contributions are welcome. Please ensure your submission fully follows the requirements outlined in [`CONTRIBUTING.md`](CONTRIBUTING.md), including formatting, scope alignment, and category placement.

Pull requests that do not adhere to the contribution guidelines may be closed.

## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/by-sa.svg)](http://creativecommons.org/licenses/by-sa/4.0/)
