 # **Fooyin Player Regression Testing Completion Report v1.0**

**Test Owner:** Vladyslav Levytskyi  
**Test Executor:** Vladyslav Levytskyi  
**Test Date:** 28.11.2025 - 28.11.2025  
**Application:** Fooyin Player  
**Version:** 0.9.2  
**Build:** N/A  
**System:** Arch Linux x86_64 (Kernel: 6.17.8-lqx2-1-lqx), Plasma 6.5.3, KWin 6.5.3-1, qt6-wayland 6.10.0-1

---
**Purpose**

- This report provides a summary of the results of the tests performed as outlined in the Fooyin Regression Test Suite v1.0 (Qase Suite ID: ID001 and in accordance with the Fooying Player Regression Testing Plan v1.0.

---
**Functional testing**
 
- The core functions were tested, that is playback, playlist operations, media management, user interface behavior.

---
**Test Results** 

- No deviations from the test plan v1.0 and test cases were observed during the testing. The test coverage was 100%. During the testing, one critical and one major failures happened:

---
1. **Critical:** the seek bar slider wouldn’t change the position with a mouse or keyboard action.

- **Observed:** clicking and dragging the slider had no effect; keyboard arrow keys didn’t move it.

2. **Major:** the repeat function didn’t repeat a track, album, or playlist even when active.

- **Observed:** activating repeat of a track, album, or playlist played once and stopped.

---
**Test Assessment**

- Regression testing for Fooyin Player version 0.9.2 is complete. All core functions were thoroughly tested in a timely manner. Two significant failures were observed in the playback module, blocking the release.

---
**Suggested Actions**

- A fix and re-testing are required.
