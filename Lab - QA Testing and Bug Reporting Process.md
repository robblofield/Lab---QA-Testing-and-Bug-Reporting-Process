
# Lab - QA Testing and Bug Reporting Process

*In this lab we are aiming to establish a clear, standardized process for the **systematic playtesting, bug identification, documentation, and reporting** to ensure the game meets the highest quality standards before release/exhibition.*

---

## 1. Playtesting Preparation
**Before Testing Begins:**
- Ensure you have the latest build installed.
- Confirm that debug/dev tools are accessible (if permitted).
- Verify access to the current **Test Case Checklist** and **Known Issues List**.
- Set up screen recording or screenshot capture tools.

**Required Materials:**
- Test device(s) (PC, console, mobile, etc.)
- Bug Reporting Template (see section 5)
- Version number and build notes

---

## 2. Playtesting Procedure
Each phase of playtesting is likely to have different rules or a specific structure based on what the test is looking to observe in user-centric traits such as behaviour/enjoyment/dificulty etc. and technical aspects such as game stability, glitches/bugs etc. You will need to adapt the session rules accordingly for the specific session.

**Session Rules (Example):**
- Follow assigned test cases **methodically** before free exploration.
- Stay consistent with **documenting time spent** per section/level.
- **Record** abnormal behavior even if unsure whether it's a bug.
- Prioritize **reproducibility**: if you spot an issue, **retest** it immediately.

**Play Modes to Cover (Example):**
- Story Mode / Main Progression
- Multiplayer (if applicable)
- Settings and UI/UX Testing
- Edge cases (e.g., quitting mid-save, changing resolution in gameplay)

**Focus Areas (Example):**
- Stability (crashes, freezes)
- Performance (frame rate drops, loading times)
- Gameplay (mechanics, balance, sequence breaks)
- Graphics/Art (glitches, texture errors, clipping)
- Sound (missing effects, wrong audio triggers)
- UI/UX (menu bugs, navigation issues, font problems)
- Localization (if multilingual)
- Accessibility Features (if applicable)

---

## 3. Bug Identification
When finding an issue:
- Try to **reproduce** it at least twice.
- Determine if it's **build-specific** or potentially **platform-specific**.
- Classify the severity:
  - **Blocker**: Game-breaking, crash, major progression loss.
  - **Critical**: Severely impacts user experience.
  - **Major**: Functional, but non-critical failure.
  - **Minor**: Cosmetic, low-priority.
  - **Suggestion**: Not a bug but a potential improvement.

---

## 4. Bug Reporting Workflow
**Immediate Action:**
- **Log** the issue in the shared Bug Tracker (JIRA, Trello, Notion, etc.).
- Include all **required fields** from the Bug Report Template.
- Upload any **recordings/screenshots** for reference.
- Assign appropriate **labels** (e.g., [Platform], [Severity], [Feature Area]).

**Communication:**
- If a **Blocker or Critical** issue is found, immediately notify the team via the agreed urgent channel (Slack, Teams, etc.).

---

## 5. Bug Report Template

| Field | Description |
|:------|:------------|
| **Title** | Short, descriptive summary of the issue. |
| **Environment** | Platform, OS, build version. |
| **Severity** | Blocker / Critical / Major / Minor / Suggestion. |
| **Description** | Detailed explanation of what happened. |
| **Steps to Reproduce** | Clear, step-by-step list to recreate the bug. |
| **Expected Result** | What should have happened. |
| **Actual Result** | What actually happened. |
| **Attachments** | Screenshots, video recordings, logs (if any). |
| **Frequency** | Always / Sometimes / Rarely. |

---

## 6. Post-Testing Debrief
At the end of a session:
- QA team holds a **15-minute debrief** to discuss:
  - Trends or recurring issues.
  - Areas that need retesting after fixes.
  - Suggestions for improvements to the testing process.

---

## 7. Regression Testing
- Once a bug is marked "Fixed", the same QA who reported it (or another assigned QA) will **retest** it following the **Steps to Reproduce**.
- If verified fixed, mark as **"Closed"**.
- If still occurring, **reopen** with updated notes.

---

## 8. Metrics and Reporting
At the end of each week or milestone:
- Summarize:
  - Total bugs found (by severity).
  - Total bugs resolved.
  - Areas with highest bug density.
- Track QA hours logged and coverage achieved.

---

# Key Rules to Remember
- **Be Objective**: Focus on facts, not opinions (unless clearly labeled as suggestions).
- **Be Thorough**: Better to over-report than to miss a serious issue.
- **Be Clear**: Reports should be understandable to anyone, not just developers.
