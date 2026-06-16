# API Security Risk Analysis

## Overview

This project focuses on analyzing the security posture of a public API using Postman. The objective was to test API endpoints, identify potential security risks, assess their impact, and recommend mitigation strategies.

---

## Objective

* Understand API functionality and communication.
* Test API endpoints using Postman.
* Identify common API security risks.
* Analyze security weaknesses.
* Suggest remediation measures.

---

## Tools Used

* Postman
* JSONPlaceholder API
* GitHub

---

## API Tested

**Base URL:**

https://jsonplaceholder.typicode.com

**Endpoints Tested:**

* GET /users
* GET /posts

---

## Testing Methodology

1. Sent API requests using Postman.
2. Examined API responses.
3. Reviewed exposed data.
4. Evaluated authentication requirements.
5. Identified security risks.
6. Documented findings and recommendations.

---

## Security Findings

### 1. No Authentication Mechanism

**Severity:** Medium

The API endpoints were accessible without authentication, which may allow unauthorized access to data.

### 2. Excessive Data Exposure

**Severity:** Medium

User-related information such as names, emails, and addresses was visible in API responses.

### 3. Missing Rate Limiting

**Severity:** Low

No visible rate-limiting controls were identified during testing.

---

## Recommendations

* Implement API authentication mechanisms.
* Limit exposure of sensitive information.
* Apply rate-limiting controls.
* Monitor API activity and logs.
* Conduct periodic security assessments.

---

## Project Structure

```text
FUTURE_CS_03_API_SECURITY_RISK_ANALYSIS
│
├── README.md
│
├── Report
│   └── API_Security_Risk_Analysis_Report.pdf
│
└── Screenshots
    ├── users_endpoint.png
    └── posts_endpoint.png
```

---

## Conclusion

This project provided practical experience in API testing and security analysis. The assessment identified common API security concerns and demonstrated the importance of implementing security controls to protect APIs from misuse and unauthorized access.
