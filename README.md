
# FUTURE_CS_03 — API Security Risk Analysis

## Intern: Maramakshaya
## Date: 20 May 2026
## Deadline: 10/06/2026

---

## ✅ Task 3 — API Security Risk Analysis Report

### Tool Used
- Postman Web (web.postman.co)
- Browser DevTools

### APIs Tested
| API | Endpoint | Issue Found |
|-----|---------|-------------|
| JSONPlaceholder | jsonplaceholder.typicode.com/users | PII Data Exposed |
| ReqRes | reqres.in/api/users | Email & Names Exposed |
| HTTPBin | httpbin.org/get | IP Address Leaked |

### Risk Summary
| Risk Level | Count |
|------------|-------|
| 🔴 High | 3 |
| 🟠 Medium | 2 |
| 🔵 Low | 2 |

### Key Vulnerabilities Found
- No Authentication on all APIs
- PII Data Exposure (name, email, phone, address)
- IP Address Leakage
- Missing Rate Limiting
- Missing Security Headers
- Server Information Disclosed
- Internal Token Exposed

### Deliverables
- 📄 Task3_API_Security_Risk_Analysis_Maramakshaya.pdf
- 📸 API 1 Screenshot — JSONPlaceholder response
- 📸 API 2 Screenshot — ReqRes response
- 📸 API 3 Screenshot — HTTPBin response
- 📸 Headers Screenshot — Response headers analysis
