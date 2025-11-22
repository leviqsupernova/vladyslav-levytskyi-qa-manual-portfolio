# **Searching for Valid Movies via "Movie Search" Bar Input in Header Doesn't Return Movie Cards**

**Bug Report ID:** BR-001  
**Status:** New  
**Reporter:** Vladyslav Levytskyi  
**Assignee:** Developer  
**Date:** 04.11.2025  

**Related Test Case ID:** TC-001   
**Module:** Search   
**Release Version:** Alpha 0.1  
**Type:** Functional  
**Priority:** High  
**Severity:** Major

**Environment:** 

**Demo website:** https://goitstudentsworks.github.io/js_70_melvinsz/  
**OS:** Arch Linux x86_64 (Linux Kernel 6.17.7-lqx1-1-lqx)  
**Browser:** Firefox 144.0.2 (64-bit)  

---
## Summary

Entering valid values in the "Movie Search" bar input in the header doesn't return movie cards.

---
## Preconditions

- Third-party plugins are turned off
- The homepage is open

---
## Test Data

| Field        | Value         |
| ------------ | ------------- |
| Movie Search | Haunted House |
- - -
## Steps to Reproduce

| Step № | Action                                                              |
| ------ | ------------------------------------------------------------------- |
| 1      | Type "Haunted House" in the "Movie Search" bar input in the header. |
| 2      | Click the magnifying glass icon near the search bar.                |

---
## Actual Result

An empty results page is open; no movie cards are shown.

---
## Expected Result

Search results are displayed according to the entered keywords. No errors or broken layout elements are present.

---
## Notes

> Additional notes.
## Attachments

- Screenrecord1.mp4

