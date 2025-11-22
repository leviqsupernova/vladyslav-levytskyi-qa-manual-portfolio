# **Fooyin Player Regression Testing Plan v1.0**

**Author:** Vladyslav Levytskyi  
**Application:** Fooyin Player  
**Version:** 0.9.2  
**Build:** N/A  
**Date:** 21.11.2025

---
**Environment**

- **OS:** Arch Linux x86_64 (Kernel: 6.17.8-lqx2-1-lqx).
- **Desktop environment:** Plasma 6.5.3.
- **Window manager** / **compositor:** KWin 6.5.3-1.
- **Display server:** qt6-wayland 6.10.0-1.

---
**Hardware**

- **Motherboard:** B550M PRO-VDH (MS-7C95).
- **CPU:** AMD Ryzen 7 5700X (16 threads) @ 3.4 GHz, OC.
- **GPU:** AMD ATI Radeon RX 570.
- **RAM:** Kingston KF3200C16D4/16GX DDR4, 16 GB x 2 DIMM, OC, custom timings.

---
**Dependencies** 

- org.kde.Platform/x86_64/6.9.

**Purpose**

- Validate the core functionality after the recent dependencies update.

---
**Scope of Testing**

- **In Scope:** playback, playlist operations, media management, user interface behavior.
- **Out of Scope:** audio quality, performance, security, network, settings.

---
**Test Objectives**

- Ensure all core playback operations (play, pause, stop, seek, repeat, shuffle, volume, last track. position) work correctly with local media files and persist across sessions.
- Confirm playlists can be created, edited, deleted, and saved, and changes persist across sessions.
- Verify media files are imported correctly, metadata is recognized, and search/filter/sort features behave as expected.
- Validate UI elements respond properly, display correct track info and progress, and support common interactions (drag-and-drop, menu navigation).

---
**Testing Approach**

- **Methodologies:** black box, test-case-driven.
- **Types of Testing:** functional, regression, system.
- **Tools Used:** Qase.

---
**Test Schedule**:

| **Phase**           | **Start Date** | **End Date** |
| :------------------ | :------------- | :----------- |
| Test planning       | 22/11          | 24/11        |
| Test case Design    | 24/11          | 25/11        |
| Test implementation | 27/11          | 27/11        |
| Test execution      | 28/11          | 28/11        |
| Re-testing          | N/A            | N/A          |
| Test completion     | N/A            | N/A          |
| Test reporting      | N/A            | N/A          |

---
**QA Lead:** [name], test plan, coordination.  
**Test Engineers:** [names], test analysis, design, implementation, execution, completion, reporting.

---
**Risks**

- **Risk 1**: tight release schedule.
- **Mitigation:** prioritize critical tests.
- **Risk 2:** limited environment coverage.
- **Mitigation:** cloud testing.

---
 **Test Deliverables**

- Test plan, traceability matrix, test cases,  test runs, test checklist, test completion report, bug reports, traceability matrix.

---
 **Entry Criteria** 

- Build complete, environment stable, test cases reviewed and approved.

---
**Exit Criteria** 

-  95% test case pass rate, no major/critical/blocker open bugs.
