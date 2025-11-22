# **Entering Wrong Values in "Movie Search" Bar Input in Header**

**Test Case ID:** TC-004  
**Executor:** Vladyslav Levytskyi  
**Date:** 04.11.2025

**Module:** Search  
**Release Version:** Alpha 0.1  
**Type:** Functional  
**Priority:** Lowest

**Environment:** 

**Demo website:** https://goitstudentsworks.github.io/js_70_melvinsz/  
**OS:** Arch Linux x86_64 (Linux Kernel 6.17.7-lqx1-1-lqx)  
**Browser:** Firefox 144.0.2 (64-bit)

**Automation Status:** Manual  

---
## Preconditions

- Browser cache and cookies are cleared
- Third-party plugins are turned off
- The home page of the website is open

---
## Test Data

| Field        | Value            |
| ------------ | ---------------- |
| Movie Search | 43)())84uigDSU9@ |

---
## Test Steps

| Step № | Action                                                                 | Expected Result                                                                | Pass | Fail | Bug Report ID |
| ------ | ---------------------------------------------------------------------- | ------------------------------------------------------------------------------ | ---- | ---- | ------------- |
| 1      | Type "43)())84uigDSU9@" in the "Movie Search" bar input in the header. | "43)())84uigDSU9@" in the "Movie Search" bar input in the header is visible.   | Y    |      |               |
| 2      | Click the magnifying glass icon near the search bar.                   | No search results are returned. An incorrect input error message is displayed. | Y    |      |               |

---
## Postconditions

- No search results are returned
- An incorrect input error message is displayed

---
## Notes

> Additional notes.
