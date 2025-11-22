# **Wrong Values in "Movie Search" Bar in Header Return Random Results**

**Bug Report ID:** BR-004  
**Status:** New  
**Reporter:** Vladyslav Levytskyi  
**Assignee:** Developer  
**Date:** 04.11.2025  

**Related Test Case ID:** TC-002  
**Module:** Search  
**Release Version:** Alpha 0.1  
**Type:** Functional  
**Priority:** Trivial  
**Severity:** Lowest  

**Environment:** 

**Demo website:** https://goitstudentsworks.github.io/js_70_melvinsz/  
**OS:** Arch Linux x86_64 (Linux Kernel 6.17.7-lqx1-1-lqx)  
**Browser:** Firefox 144.0.2 (64-bit)  

---
## Summary

Entering wrong values in the search bar in the header returns random movies cards.

---
## Preconditions

- Browser cache and cookies are cleared
- Third-party plugins are turned off
- The homepage is open

---
## Test Data

| Field        | Value            |
| ------------ | ---------------- |
| Movie Search | 43)())84uigDSU9@ |
- - -
## Steps to Reproduce

| Step № | Action                                                                 |
| ------ | ---------------------------------------------------------------------- |
| 1      | Type "43)())84uigDSU9@" in the "Movie Search" bar input in the header. |
| 2      | Click the magnifying glass icon near the search bar.                   |

---
## Actual Result

Random or unrelated movies cards are visible.

---
## Expected Result

An empty results page is open. An incorrect input error message is displayed.

---
## Notes

> Additional notes.

- - -
## Attachments

- Screenshot1.png

