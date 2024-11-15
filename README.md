# Digital Aid Seattle QA Challenge

## Project Overview
This project focuses on the QA testing of a **Random Date Generator** application. The goal of this assessment was to evaluate and validate the functionality, accessibility, stability, and user experience of the application, which generates random dates based on various input parameters. The testing process involved creating comprehensive checklists, identifying bugs, and suggesting improvements to enhance the application's robustness and usability.

## Table of Contents
- [Project Overview](#project-overview)
- [Testing Scope](#testing-scope)
- [Features Tested](#features-tested)
- [Bug Reports](#bug-reports)
- [Improvement Suggestions](#improvement-suggestions)
- [Checklists, Bug Report, and Improvement Report](#checklists-bug-report-and-improvement-report)
- [Technologies Used](#technologies-used)
- [Environment](#environment)
- [License](#license)

## Testing Scope
Testing for the Random Date Generator application covered:
1. **Functional Testing**: Verification of correct date generation across different formats and boundary values.
2. **Non-Functional Testing**: Analysis of response time, load handling, and stability.
3. **Accessibility Testing**: Validation against WCAG standards for color contrast and screen reader compatibility. (I included accessibility testing because Digital Aid Seattle supports other non-profits, making inclusive, accessible technology essential to their mission.)

## Features Tested
- **Date Generation with Various Formats**: Ensuring that each format option in the "Date output format" dropdown generates dates in the selected format.
- **Boundary Testing**: Testing boundary values for inputs, such as start and end dates, number of dates, and year limitations.
- **Leap Year Handling**: Validating date generation for leap years and ensuring appropriate restrictions for February dates.
- **Error Handling and Validation**: Ensuring clear error messages are displayed for invalid inputs and guiding the user for correct inputs.

## Bug Reports
Several bugs were identified during testing. Key bugs included:
- Incorrect display of the "Year Date Month hh:mm:ss" format in the generated output.
- Application failure to restrict the input of invalid dates such as February 30th or extremely high year values.
- Lack of error messages for invalid inputs, causing user confusion.

## Improvement Suggestions
In addition to bug reports, several improvement suggestions were made:
1. **Date Format Clarity**: Add a format guide near the date input fields.
2. **Year Range Limit**: Restrict year input to a realistic range (e.g., 1900-2100) to prevent excessive values that may affect performance.
3. **Enhanced Leap Year Validation**: Ensure the app only allows valid days for February based on leap year rules.
4. **Error Messaging for Invalid Inputs**: Provide clear error messages and input guidelines for non-date values or unrealistic ranges.

## Checklists, Bug Report, and Improvement Report
For detailed checklists, bug reports, and improvement suggestions, refer to the **[Google Sheets document](https://docs.google.com/spreadsheets/d/1mmflmu1XJQJeOenwloYcXN9q1vN0nB5OO-OmHQBqCak/edit?usp=sharing)**.
I also created bug report on **[Jira](https://waruneed.atlassian.net/jira/software/c/projects/DASQC/issues?jql=project%20%3D%20%22DASQC%22%20ORDER%20BY%20created%20DESC)** that you can check it out.

## Technologies Used
- **Browser**: Google Chrome (Version 130.0.6723.117)
- **Operating System**: macOS Sonoma 14.6.1
- **Testing Tools**: Google Sheets, Colour Contrast Analyser (CCA), VoiceOver for accessibility testing
  
## Environment
Testing was conducted on:
- **Browser**: Google Chrome
- **Device**: MacBook Pro
- **Operating System**: macOS Sonoma 14.6.1

## License
This project is for educational and assessment purposes only.

---

Feel free to contribute or reach out with any questions regarding the testing process or the findings documented in this repository.
