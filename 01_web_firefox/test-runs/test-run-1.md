# **Verify Movie Search via "Movie Search" Bar Input From Header**

**Test Case ID:** TC-001  
**Executor:** Vladyslav Levytskyi  
**Date:** 04.11.2025

**Module:** Search  
**Release Version:** Alpha 0.1  
**Type:** Functional   
**Priority:** High

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

| Field        | Value         |
| ------------ | ------------- |
| Movie Search | Haunted House |

---
## Test Steps

| Step № | Action                                                              | Expected Result                                                           | Pass | Fail | Bug Report ID |
| ------ | ------------------------------------------------------------------- | ------------------------------------------------------------------------- | ---- | ---- | ------------- |
| 1      | Type "Haunted House" in the "Movie Search" bar input in the header. | "Haunted House" in the "Movie Search" bar input in the header is visible. | Y    |      |               |
| 2      | Click the magnifying glass icon near the search bar.                | A page with movies containing "Haunted House" in their titles is open.    | Y    |      |               |

---
## Postconditions

- Search results are displayed according to the entered keywords
- No errors or broken layout elements are present

---
## Notes

> Additional notes.

