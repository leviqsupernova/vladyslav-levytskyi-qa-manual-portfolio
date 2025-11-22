# **"User's Library" Button Doesn't Navigate to User's Library From Header**

**Bug Report ID:** BR-003  
**Status:** New  
**Reporter:** Vladyslav Levytskyi  
**Assignee:** Developer  
**Date:** 04.11.2025  

**Related Test Case ID:** TC-003  
**Module:** Navigation  
**Release Version:** Alpha 0.1  
**Type:** Functional  
**Priority:** Medium  
**Severity:** Minor  

**Environment:** 

**Demo website:** https://goitstudentsworks.github.io/js_70_melvinsz/  
**OS:** Arch Linux x86_64 (Linux Kernel 6.17.7-lqx1-1-lqx)  
**Browser:** Firefox 144.0.2 (64-bit)

---
## Summary

Pressing the "User's Library" button in the header doesn't navigate to the user's library.

---
## Preconditions

- Browser cache and cookies are cleared
- Third-party plugins are turned off
- User is logged in with a valid account
- A page different from the "My Library" page is open

---
## Steps to Reproduce

| Step № | Action                                       |
| ------ | -------------------------------------------- |
| 1      | Press the "My Library" button in the header. |

---
## Actual Result

The current page remains open; the user's library page is not displayed.

---
## Expected Result

The user's library page is open in the same window.

---
## Notes

> Additional notes.

- - -
## Attachments

- Screenrecord1.mp4
