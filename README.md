# Contribution: PO: parts with different project codes get merged into single line #10947


**Contribution Number:** 1

**Student:** Yuting
**Issue:** [issue link](https://github.com/issues/recent?issue=inventree%7CInvenTree%7C10947)
**Status:** [**Phase I** / **Phase II** / Phase III / Phase IV] [**In Progress** / Complete]

---

## Why I Chose This Issue



---

## Understanding the Issue

### Problem Description
The "Add Line Item" form in Purchase Orders includes a "Merge Items" checkbox, which is currently hardcoded to True by default. When enabled, adding a line item for a part that already exists in the PO will merge it into the existing line — including overwriting the project code. There is no system-level setting to change this default behavior.

### Current Behavior
The "Merge Items" checkbox in the PO line item form always defaults to True. Users who need items with different project codes to remain as separate lines must manually uncheck "Merge Items" every time they add a line item, with no way to configure a different default.

### Expected Behavior
A configurable setting should be added to the system settings that controls the default state of the "Merge Items" checkbox — allowing administrators to set it to False by default for instances where per project-code tracking is important.

### Affected Components
- PO "Add Line Item" form — Merge Items checkbox default value
- System settings — new configurable toggle for the above default
---

## Reproduction Process

### Environment Setup

[Notes on setting up your local development environment - challenges you faced, how you solved them]

### Steps to Reproduce

1. [Step 1]
2. [Step 2]
3. [Observed result]

### Reproduction Evidence

- **Commit showing reproduction:** [Link to commit in your fork]
- **Screenshots/logs:** [If applicable]
- **My findings:** [What you discovered during reproduction]

---

## Solution Approach

### Analysis

[Your analysis of the root cause - what's causing the issue?]

### Proposed Solution

[High-level description of your fix approach]

### Implementation Plan

Using UMPIRE framework (adapted):

**Understand:** [Restate the problem]

**Match:** [What similar patterns/solutions exist in the codebase?]

**Plan:** [Step-by-step implementation plan]
1. [Modify file X to do Y]
2. [Add function Z]
3. [Update tests]

**Implement:** [Link to your branch/commits as you work]

**Review:** [Self-review checklist - does it follow the project's contribution guidelines?]

**Evaluate:** [How will you verify it works?]

---

## Testing Strategy

### Unit Tests

- [ ] Test case 1: [Description]
- [ ] Test case 2: [Description]
- [ ] Test case 3: [Description]

### Integration Tests

- [ ] Integration scenario 1
- [ ] Integration scenario 2

### Manual Testing

[What you tested manually and results]

---

## Implementation Notes

### Week [X] Progress

[What you built this week, challenges faced, decisions made]

### Week [Y] Progress

[Continue documenting as you work]

### Code Changes

- **Files modified:** [List]
- **Key commits:** [Links to important commits]
- **Approach decisions:** [Why you chose certain approaches]

---

## Pull Request

**PR Link:** [GitHub PR URL when submitted]

**PR Description:** [Draft or final PR description - much of the content above can be adapted]

**Maintainer Feedback:**
- [Date]: [Summary of feedback received]
- [Date]: [How you addressed it]

**Status:** [Awaiting review / Iterating / Approved / Merged]

---

## Learnings & Reflections

### Technical Skills Gained

[What you learned technically]

### Challenges Overcome

[What was hard and how you solved it]

### What I'd Do Differently Next Time

[Reflection on your process]

---

## Resources Used

- [Link to helpful documentation]
- [Tutorial or Stack Overflow post that helped]
- [GitHub issues or discussions that helped]
