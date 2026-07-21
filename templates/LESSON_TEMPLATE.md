# Lesson Template

## The Complete n8n Bootcamp

**Module:** [Module Number and Title]
**Lesson:** [Lesson Number and Title]
**Difficulty:** [Foundation / Beginner / Intermediate / Advanced]
**Estimated Reading Time:** [XX minutes]
**Estimated Practice Time:** [XX hours]
**Prerequisites:** [Required lessons or skills]
**Related Competencies:** [Reference relevant competencies]
**Skills Unlocked:** [Reference relevant Skill Tree branches]

---

# 1. Lesson Purpose

Explain why this lesson exists and how it contributes to the learner’s development as an Automation Engineer.

The purpose should connect the lesson to:

- A real business need
- A professional responsibility
- A future project or competency
- The learner’s job-readiness journey

Avoid opening with a feature description.

Start with the problem the learner must be able to solve.

---

# 2. Learning Objectives

By the end of this lesson, the student will be able to:

- [Use a measurable action verb]
- [Build, configure, analyze, compare, debug, evaluate, or explain]
- [Demonstrate an observable skill]
- [Apply the skill in a business context]

Use measurable verbs such as:

- Configure
- Build
- Trace
- Transform
- Validate
- Diagnose
- Compare
- Design
- Implement
- Evaluate
- Refactor

Avoid vague objectives such as:

- Learn
- Know
- Become familiar with
- Understand

---

# 3. Business Scenario

Introduce a realistic business situation that creates a need for the lesson.

Include:

- The organization or team
- The existing process
- The problem or inefficiency
- The people affected
- The desired result
- Important constraints

## Example Structure

A growing company receives employee requests through email. The HR team manually copies the information into a spreadsheet, checks whether required fields are present, and notifies the hiring manager.

The process is slow and frequently produces incomplete records.

The company needs a workflow that validates incoming employee information, stores valid records, and routes incomplete submissions for review.

---

# 4. Why This Matters Professionally

Explain where this skill appears in real Automation Engineer work.

Cover:

- Common business use cases
- How employers expect the skill to be applied
- Problems caused by weak implementation
- How the skill connects to later modules

---

# 5. Core Concepts

Explain the theory behind the lesson before giving implementation instructions.

For every important concept, include:

## Concept Name

### Definition

Explain the concept clearly.

### Why It Exists

Describe the problem it solves.

### How It Works

Explain the mechanism or data flow.

### When to Use It

Give realistic use cases.

### When Not to Use It

Explain common misuse or unnecessary complexity.

### Example

Provide a small practical example.

---

# 6. Mental Model

Give the learner a simple way to reason about the concept.

Use one or more of the following:

- Analogy
- Diagram
- Input-process-output model
- Decision tree
- Data-flow example
- Before-and-after comparison

The mental model must simplify the concept without becoming technically misleading.

---

# 7. Technical Reference

Document the relevant n8n behavior.

Include where applicable:

- Nodes used
- Important node settings
- Expected input
- Expected output
- Expressions
- Data structure
- Credentials
- Execution behavior
- Limitations
- Version-sensitive details

Do not copy official documentation unnecessarily.

Summarize only what the learner needs for the lesson.

---

# 8. Guided Demonstration

Build a small example step by step.

For every step, include:

1. What to do
2. Why it is being done
3. What data should exist before the step
4. What output should appear after the step
5. How to verify that the step worked

## Step 1 — [Action]

**Action**

[Instruction]

**Reason**

[Why this step is necessary]

**Expected Input**

```json
{}
```

**Expected Output**

```json
{}
```

**Verification**

[How the learner confirms success]

Repeat this format for each implementation step.

---

# 9. Guided Lab

The learner reproduces a complete workflow with structured support.

## Lab Objective

[Describe the finished result]

## Business Requirement

[State the practical requirement]

## Required Components

- [Trigger]
- [Processing steps]
- [Validation]
- [Output]
- [Error handling]

## Starter Data

```json
{}
```

## Implementation Tasks

- [Task 1]
- [Task 2]
- [Task 3]
- [Task 4]

## Acceptance Criteria

The lab is complete when:

- [Observable requirement]
- [Observable requirement]
- [Observable requirement]
- [Failure case requirement]

## Evidence to Save

- Workflow export
- Screenshot
- Sample execution
- Short explanation
- Git commit

---

# 10. Independent Lab

The learner applies the concept with limited guidance.

## Scenario

[Describe a related but different business problem]

## Requirements

- [Requirement]
- [Requirement]
- [Requirement]
- [Requirement]

## Constraints

- [Constraint]
- [Constraint]

## Deliverables

- Working workflow
- Workflow export
- README update
- Test evidence
- Reflection

Do not provide complete implementation steps.

Hints may be included only when necessary.

---

# 11. Design Challenge

Provide an open-ended business problem.

The learner must decide:

- Workflow architecture
- Nodes
- Data model
- Validation
- Error handling
- Testing strategy
- Documentation

## Challenge Brief

[Business problem]

## Available Information

[Known requirements and constraints]

## Unknowns

[List issues the learner should clarify or make assumptions about]

## Required Submission

- Requirements summary
- Assumptions
- Architecture diagram
- Workflow
- Test cases
- Technical explanation
- Improvement ideas

No step-by-step solution should be included in the main challenge.

---

# 12. Debugging Exercise

Provide an intentionally broken workflow or configuration.

## Symptoms

Describe what the learner observes.

Examples:

- Incorrect output
- Missing records
- Duplicate records
- Authentication failure
- Partial execution
- Invalid data
- Workflow timeout

## Investigation Questions

- Where does the output first become incorrect?
- What evidence supports the diagnosis?
- Is the failure caused by data, logic, configuration, or an external service?
- What is the smallest safe correction?

## Expected Debugging Process

The learner should:

1. Reproduce the issue.
2. Inspect execution data.
3. Isolate the failing step.
4. Identify the root cause.
5. Apply a correction.
6. Retest successful and failure cases.
7. Document the issue and resolution.

---

# 13. Common Mistakes

For each mistake, explain:

- What the learner may do
- Why it fails
- How to recognize it
- How to correct it
- How to prevent it in production

## Mistake 1 — [Title]

**Problem**

[Description]

**Cause**

[Root cause]

**Correction**

[Fix]

**Prevention**

[Professional practice]

---

# 14. Production Considerations

Discuss the lesson from a production perspective.

Include applicable topics:

- Security
- Credentials
- Privacy
- Idempotency
- Error handling
- Retries
- Logging
- Monitoring
- Performance
- Rate limits
- Scalability
- Maintainability
- Cost
- Ownership
- Recovery

Not every lesson needs every topic, but production concerns must not be ignored when relevant.

---

# 15. Testing Strategy

Define how the workflow should be tested.

At minimum, consider:

| Test Type          | Example                                |
| ------------------ | -------------------------------------- |
| Happy path         | Valid input produces expected output   |
| Missing data       | Required field is absent               |
| Invalid data       | Incorrect format or unsupported value  |
| Empty input        | No records are received                |
| Duplicate input    | Same event is processed more than once |
| External failure   | API or database is unavailable         |
| Permission failure | Credential lacks required access       |
| Volume test        | Multiple records are processed         |

## Test Cases

| Test   | Input   | Expected Result | Actual Result   | Status      |
| ------ | ------- | --------------- | --------------- | ----------- |
| [Name] | [Input] | [Expected]      | [Student fills] | [Pass/Fail] |

---

# 16. Best Practices

Summarize professional practices introduced in the lesson.

Examples:

- Use meaningful node names.
- Validate data before external requests.
- Keep credentials out of workflow documentation.
- Add notes for non-obvious decisions.
- Separate reusable logic.
- Test failure conditions.
- Document assumptions.
- Prefer simple designs unless complexity is justified.

---

# 17. Architecture and Trade-Off Discussion

Ask the learner to evaluate the implementation.

Questions may include:

- Why was this design selected?
- What alternatives exist?
- What are the trade-offs?
- What would change at higher volume?
- What would change if the external service were unreliable?
- Which parts should become reusable?
- Where should human review be added?
- What security risks exist?

---

# 18. Portfolio Upgrade

Explain how the lesson improves the learner’s portfolio.

Required actions may include:

- Export the workflow.
- Add a business problem statement.
- Add architecture or workflow diagrams.
- Add screenshots.
- Document test cases.
- Add error-handling notes.
- Record lessons learned.
- Update the project README.
- Commit the work using a meaningful message.

## Suggested Commit

```text
Complete [lesson or project name]
```

---

# 19. Interview Preparation

Include questions in four categories.

## Technical Questions

- [Question]
- [Question]

## Scenario Questions

- [Question]
- [Question]

## Architecture Questions

- [Question]
- [Question]

## Reflection Questions

- [Question]
- [Question]

Where appropriate, include an answer guide for instructors without encouraging memorization.

---

# 20. Knowledge Check

Use short questions to confirm conceptual understanding.

The knowledge check may include:

- Multiple choice
- Short answer
- Predict-the-output
- Identify-the-error
- Compare two designs
- Explain a decision

Knowledge checks support learning but do not replace practical assessment.

---

# 21. Lesson Summary

Summarize:

- The business problem
- The main concept
- The implementation pattern
- The professional consideration
- The skill unlocked

Keep this section concise.

---

# 22. Reflection

The student answers:

1. What was the most important concept in this lesson?
2. What part of the workflow was most difficult?
3. What mistake did I make, and how did I diagnose it?
4. What would I improve in a production version?
5. Where could this pattern be used in a real business?
6. How would I explain this workflow during an interview?

---

# 23. Definition of Done

The lesson is complete only when:

- Learning objectives can be demonstrated.
- Guided lab is working.
- Independent lab is completed.
- Required test cases have been executed.
- At least one failure case has been tested.
- Workflow is organized and named clearly.
- Workflow export is saved.
- Documentation is updated.
- Reflection is completed.
- Interview questions can be answered.
- Work is committed to Git.

---

# 24. Next Lesson

Explain:

- What comes next
- Why the next topic follows this lesson
- Which current skills will be reused
- What the learner should prepare
