# su26-ai301-contribution
# Contribution [#]: [Allow clicking locked slots in feeder menu]

**Contribution Number:** [1]  
**Student:** [June Eguilos]  
**Issue:** [[GitHub issue link](https://github.com/Wynntils/Wynntils/issues/3860)]  
**Status:** [Phase II] [Complete]

---

## Why I Chose This Issue

[1-2 paragraphs explaining why this issue interests you, how it matches your skills/learning goals, what you hope to learn]
I really like game development and grew up on Minecraft so this project stood out to me personally. I hope to learn more on contributing to open source, then go on to tackle harder tasks/bug fixes/contributions.

---

## Understanding the Issue

### Problem Description

[In your own words, what's broken or missing?]
Seems like a small bug, when an item is locked, they just want to allow clicking locked slots in a feeder menu. 

### Expected Behavior

[What should happen?]
Allow clicking locked slots in the feeder menu. 

### Current Behavior
`[What actually happens?]`

When an item is locked, you just aren't able to interact with specific progression items, when that shouldn't be the case.

  

### Affected Components
`[Which parts of the codebase are involved?]`
`ItemLockFeature.java`

#### Setting up to reproduce Bug

1. Download Prism Launcher

2. Log into Prism Launcher

3. Modify Minecraft version to be 21.0.0

4. Download Modpack Wyntill

  

#### Setting up environment

1. Download Wynntils
2. Download Java
3. Fork git
4. Clone git in own VSCode

No challenges at all.   

### Steps to Reproduce

  

1. [Step 1]
- Play Minecraft
- Go into Server WynnCraft
- Go to any `Mount Feeder` 
- Press `I` to bring up `Wynntils User Profile`
- Click on `Settings`
- Go to `Inventory` and Click on Hover `Item Lock`
- Enable `Block All Actions on Locked Items`
- Lock the slot where your horse feed is. 
- Now go to a Horse Feeder Station in a Stable

3. [Observed result]
- You are unable to feed Horse, or click on the saddle because of the `Block All Actions on Locked Items`
  

### Reproduction Evidence

- **Commit showing reproduction:** [Link to commit in your fork]
N/A, this is a gameplay bug to reproduce. 

- **Screenshots/logs:** [If applicable]
![](Evidence1.png)
![](Evidence2.png)


- **My findings:** [What you discovered during reproduction]
You are unable to place your item into the feeder because it is Item Locked. 
  
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
