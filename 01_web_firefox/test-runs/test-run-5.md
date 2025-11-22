# **Verify "Movie Search" Bar Input in Header Resists SQL Injection P1**

**Test Case ID:** TC-005  
**Executor:** Vladyslav Levytskyi  
**Date:** 04.11.2025

**Module:** Search  
**Release Version:** Alpha 0.1  
**Type:** Security  
**Priority:** Highest  

**Environment:** 

**Demo website:** https://goitstudentsworks.github.io/js_70_melvinsz/  
**OS:** Arch Linux x86_64 (Linux Kernel 6.17.7-lqx1-1-lqx)  
**Browser:** Firefox 144.0.2 (64-bit)

**Automation Status:** Manual  

---
## Preconditions

- Browser cache and cookies are cleared
- Third-party plugins are turned off
- The homepage is open

---
## **Test Data**

| Field      | Value                                  |
| ---------- | -------------------------------------- |
| Movie Search | P1: `admin' or 1=1 or ''='<br><br><br> |

## Test Steps

| Step № | Action                                                                           | Expected Result                                                                                                 | Pass | Fail | Bug Report ID |
| ------ | -------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------- | ---- | ---- | ------------- |
| 1      | Enter Test Data in the "Movie Search" bar input in the header.                   | Test data is displayed in the "Movie Search" bar input in the header.                                           | Y    |      |               |
| 2      | Press the magnifying glass icon near the "Movie Search" bar input in the header. | The input is treated as plain text; request returned HTTP status code 200 or 4xx. No sensitive data is exposed. | Y    |      |               |

---
## Postconditions

- Input data is treated as plain text
- No sensitive data is exposed

---
## Notes

Stage-safe, non-destructive. The request was handled expectantly with an error message. 
