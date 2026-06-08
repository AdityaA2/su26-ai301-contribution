# Contribution [1]: 
Enable skipped tests on aarch64 by making them architecture-agnostic (x86-64 & aarch64)


**Contribution Number:** 1  
**Student:** Aditya Arya  
**Issue:** [https://github.com/pwndbg/pwndbg/issues/3495]  
**Status:** [Phase I] [Complete]

---

## Why I Chose This Issue

As an engineering student, this project caught my eye because it deals with a massive shift happening in technology right now: making software work seamlessly across different types of computers. A lot of older software tools were built assuming everyone was using traditional Intel or AMD processors. Now that so many people use newer, efficient chips—like Apple's M-series processors or ARM chips in modern servers—tools have to adapt. Right now, this project has to skip its automated tests on those newer chips because the test files were written with old assumptions. By fixing this, I can help ensure that when developers update the tool, it won't accidentally break for millions of users on newer computers.

By working on this, I hope to learn how professional software teams manage and test their code automatically behind the scenes. I want to move past just writing small personal scripts and instead learn how to write flexible tests that adapt to whatever computer they are running on. On top of that, diving into this codebase will give me a much closer look at how software interacts directly with different computer systems and hardware layouts, which is exactly the kind of practical engineering experience I want to build.

---

## Understanding the Issue

### Problem Description

[In your own words, what's broken or missing?]

### Expected Behavior

[What should happen?]

### Current Behavior

[What actually happens?]

### Affected Components

[Which parts of the codebase are involved?]

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

