# **"Movie Search" Bar Input in Header Accepts SQL Injection Payload P1**

**Bug Report ID:** BR-005  
**Status:** New  
**Reporter:** Vladyslav Levytskyi  
**Assignee:** Developer  
**Date:** 04.11.2025  

**Related Test Case ID:** TC-005  
**Module:** Search  
**Release Version:** Alpha 0.1  
**Type:** Security  
**Priority:** Highest  
**Severity:** Critical  

**Environment:** 

**Demo website:** https://goitstudentsworks.github.io/js_70_melvinsz/  
**OS:** Arch Linux x86_64 (Linux Kernel 6.17.7-lqx1-1-lqx)  
**Browser:** Firefox 144.0.2 (64-bit)  

---
## Summary

The "Movie search" bar input in the header allows execution of SQL payloads.

---
## Preconditions

- Browser cache and cookies are cleared
- Third-party plugins are turned off
- The homepage is open

---
## Test Data

| Field      | Value                                  |
| ---------- | -------------------------------------- |
| Movie Search | P1: `admin' or 1=1 or ''='<br><br><br> |

- - -
## Steps to Reproduce

| Step № | Action                                           |
| ------ | ------------------------------------------------ |
| 1      | Enter Test Data in the "Movie Search" bar input. |
| 2      | Press the magnifying glass icon.                 |

---
## Actual Result

The website returns a status code 500. Body returns "ERROR: syntax error at or near "OR".

---
## Expected Result

The input is handled as plain text; status code returned is 200 or 4xx. No SQL errors are visible and no unauthorized data is returned.

---
## Notes

> Additional notes.

- - -
## Attachments

- Screenshot1.png
- Screenshot2.png
