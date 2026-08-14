# GeoVolt QA Testing Portfolio

This repository presents my QA work for **GeoVolt**, a spatial decision-support system designed to identify suitable electric-vehicle charging-station locations in Ankara's Çankaya district using geographic and operational criteria.

GeoVolt was developed as a team project during the **Başarsoft internship program**. My role was **QA / Software Test Intern**. This repository contains QA artifacts only; it does not claim authorship of application features implemented by other team members.

## QA Contributions

- Reviewed the project scope and requirements through static testing, identifying ambiguities, inconsistencies, missing rules, and testability gaps.
- Prepared structured feedback and clarification requests for the Business Analyst.
- Prioritized product risks using impact and likelihood.
- Prepared a test plan covering scope, environment, entry/exit criteria, defect management, and a risk-based strategy.
- Defined a requirement-based test approach and selected suitable manual, UI automation, API, and database validation methods.
- Designed and executed positive, negative, boundary, and end-to-end test cases.
- Documented defects with reproducible steps, expected and actual results, priority, and status; retested fixes where applicable.

The final test set contains **84 test cases**: 54 passed, 9 failed, 20 blocked, and 1 not run. The defect log contains **11 bug reports**.

## Repository Contents

| Artifact | Description |
|---|---|
| [`docs/static-testing/static-test-review.docx`](docs/static-testing/static-test-review.docx) | Static review of the MVP scope and requirements, including findings and clarification requests. |
| [`docs/test-plan/geovolt-test-plan.docx`](docs/test-plan/geovolt-test-plan.docx) | Test plan covering scope, environment, entry/exit criteria, defect management, risk-based testing, and the intended automation approach. |
| [`docs/qa-artifacts/geovolt-qa-artifacts.xlsx`](docs/qa-artifacts/geovolt-qa-artifacts.xlsx) | Sanitized workbook containing requirement-based test approach, risk prioritization, test cases/results, and bug reports. |

The workbook's original `Summary` sheet is intentionally excluded. Private evidence links and test-account values were removed or replaced with safe placeholders before publication, and document metadata was scrubbed.

## Original Team Project

Application source and team project: [Mertcanhirlak/GeoVolt](https://github.com/Mertcanhirlak/GeoVolt)

## Related QA Projects

- [Restful Booker Postman API Tests](https://github.com/emirbugrairmak/restful-booker-postman-tests)
- [OWASP Juice Shop JMeter Performance Testing](https://github.com/emirbugrairmak/jmeter-juice-shop-performance-testing)
