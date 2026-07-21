# The Complete n8n Bootcamp

## Employer Competency Matrix

**Version:** 1.0
**Document Type:** Curriculum Alignment and Job-Readiness Standard

---

# 1. Purpose

This document defines the technical, engineering, business, and professional competencies developed throughout The Complete n8n Bootcamp.

It connects:

- Employer expectations
- Bootcamp modules
- Learning activities
- Portfolio evidence
- Interview preparation
- Job-readiness standards

The matrix ensures that every lesson, lab, assessment, and project contributes to a workplace-relevant capability.

The bootcamp must not teach topics merely because they are available in n8n. Each topic must support a professional responsibility performed by an Automation Engineer, n8n Developer, Integration Engineer, AI Automation Engineer, or related role.

---

# 2. How to Use This Matrix

This document serves four audiences.

## Curriculum Designers

Use the matrix to verify that lessons and projects develop relevant employer competencies.

## Students

Use the matrix to track progress and identify areas requiring additional practice.

## Instructors and Reviewers

Use the matrix when evaluating assignments, projects, and capstone submissions.

## Employers and Clients

Use portfolio evidence mapped to this matrix to understand what the graduate can perform professionally.

---

# 3. Competency Levels

Each competency is evaluated using four proficiency levels.

## Level 1 — Foundation

The student can:

- Define the concept.
- Recognize common use cases.
- Follow guided instructions.
- Complete simple tasks with support.

## Level 2 — Applied

The student can:

- Use the competency in familiar scenarios.
- Complete small tasks independently.
- Identify common errors.
- Explain basic implementation decisions.

## Level 3 — Professional

The student can:

- Apply the competency in realistic business systems.
- Select appropriate implementation patterns.
- Test and debug the solution.
- Document and explain technical decisions.
- Consider security, maintainability, and reliability.

## Level 4 — Job Ready

The student can:

- Apply the competency to unfamiliar and open-ended problems.
- Evaluate alternative approaches.
- Defend architecture decisions.
- Anticipate failure conditions.
- Deliver production-oriented work independently.
- Communicate effectively with technical and non-technical stakeholders.

---

# 4. Competency Domains

The bootcamp develops competencies across six domains.

1. Automation and Workflow Design
2. Data and Integration Engineering
3. AI Automation
4. Production and Operations
5. Business Analysis and Solution Design
6. Professional and Career Readiness

---

# 5. Automation and Workflow Design Competencies

| Competency                   | Employer Expectation                                                             | Target Level | Primary Modules | Required Evidence                             |
| ---------------------------- | -------------------------------------------------------------------------------- | -----------: | --------------- | --------------------------------------------- |
| Workflow Fundamentals        | Explain triggers, actions, inputs, outputs, dependencies, and execution flow     |            3 | 1, 2            | End-to-end workflow and data-flow explanation |
| n8n Interface and Execution  | Navigate n8n, inspect executions, configure nodes, and troubleshoot basic issues |            3 | 0, 1, 2         | Exported workflows and execution screenshots  |
| Conditional Logic            | Build branching workflows using conditions and routing rules                     |            4 | 2, 8, 12        | Multi-branch business workflow                |
| Looping and Batch Processing | Process collections safely using loops, batching, and iteration patterns         |            3 | 2, 3, 4         | Batch-processing workflow                     |
| Expressions                  | Reference and manipulate workflow data using expressions                         |            4 | 1, 2, 3         | Expression-based transformations              |
| Reusable Workflows           | Separate repeated logic into modular sub-workflows                               |            3 | 8, 9, 12        | Reusable workflow component                   |
| Workflow Organization        | Apply meaningful node names, notes, sections, and layout conventions             |            4 | 2–12            | Professionally organized workflows            |
| Workflow Refactoring         | Improve readability, maintainability, and reliability of existing workflows      |            3 | 2, 8, 9         | Before-and-after refactoring exercise         |
| Scheduling                   | Configure scheduled, recurring, and time-based automations                       |            3 | 5, 8            | Scheduled reporting or maintenance workflow   |
| Event-Driven Design          | Design workflows that respond to webhooks and external events                    |            4 | 5, 8, 12        | Secure webhook-driven integration             |

---

# 6. Data and Integration Engineering Competencies

| Competency               | Employer Expectation                                                                   | Target Level | Primary Modules | Required Evidence                  |
| ------------------------ | -------------------------------------------------------------------------------------- | -----------: | --------------- | ---------------------------------- |
| JSON Literacy            | Read, navigate, and explain JSON objects and arrays                                    |            4 | 1, 3, 4         | JSON interpretation exercises      |
| Data Mapping             | Map data accurately between systems with different schemas                             |            4 | 3, 4, 6, 8      | Cross-system integration           |
| Data Transformation      | Clean, normalize, restructure, and format data                                         |            4 | 3               | Data-cleaning project              |
| Data Validation          | Detect missing, invalid, duplicated, or malformed data                                 |            4 | 3, 5, 6, 9      | Validation and rejection workflow  |
| Date and Time Handling   | Convert time zones, format dates, and perform date calculations                        |            3 | 3, 5, 8         | Time-sensitive automation          |
| File Processing          | Handle CSV, JSON, spreadsheets, PDFs, and binary files where appropriate               |            3 | 3, 7, 8         | File-processing project            |
| REST API Fundamentals    | Read API documentation and use common HTTP methods                                     |            4 | 4               | Multi-endpoint API project         |
| API Authentication       | Implement API keys, bearer tokens, basic authentication, and OAuth                     |            4 | 4, 9            | Authenticated integration          |
| Request Construction     | Configure headers, parameters, bodies, and content types                               |            4 | 4               | Documented HTTP requests           |
| API Pagination           | Retrieve and combine paginated records reliably                                        |            3 | 4               | Paginated data workflow            |
| Rate-Limit Handling      | Recognize and manage rate limits using delays, batching, or retries                    |            3 | 4, 9            | Rate-limit-safe workflow           |
| Webhook Processing       | Receive, validate, process, and respond to webhook payloads                            |            4 | 5               | Webhook integration                |
| Database CRUD            | Create, read, update, and delete database records                                      |            4 | 6               | Database-backed automation         |
| Relational Data Concepts | Work with identifiers, relationships, references, and basic schemas                    |            3 | 6               | Schema diagram and CRUD project    |
| Data Synchronization     | Synchronize data between systems while preventing duplication                          |            4 | 6, 8, 12        | Two-way or one-way synchronization |
| Idempotency              | Prevent repeated executions from creating duplicate results                            |            3 | 5, 6, 9         | Duplicate-safe automation          |
| JavaScript in Code Nodes | Write and review small JavaScript transformations when standard nodes are insufficient |            3 | 3, 4, 7, 9      | Documented Code node examples      |

---

# 7. AI Automation Competencies

| Competency                | Employer Expectation                                                        | Target Level | Primary Modules | Required Evidence                      |
| ------------------------- | --------------------------------------------------------------------------- | -----------: | --------------- | -------------------------------------- |
| AI Use-Case Selection     | Distinguish suitable AI tasks from deterministic automation tasks           |            4 | 7, 8            | AI use-case evaluation                 |
| Prompt Design             | Write clear prompts with context, constraints, and expected outputs         |            4 | 7               | Prompt documentation                   |
| Structured Output         | Require AI responses that follow defined schemas                            |            4 | 7               | Validated structured-output workflow   |
| AI Classification         | Categorize messages, documents, requests, or records                        |            3 | 7, 8            | Classification workflow                |
| AI Extraction             | Extract structured data from unstructured text or documents                 |            4 | 7, 12           | Document-extraction project            |
| AI Summarization          | Produce concise and relevant summaries for business use                     |            3 | 7, 8            | Reporting or meeting-summary workflow  |
| AI Content Generation     | Generate useful drafts while applying review and quality controls           |            3 | 7               | Controlled content-generation workflow |
| Confidence and Validation | Validate AI output and route uncertain cases for review                     |            4 | 7, 8, 12        | Human-in-the-loop workflow             |
| AI Failure Handling       | Handle invalid, incomplete, unsafe, or unavailable model responses          |            4 | 7, 9            | AI fallback and recovery logic         |
| Cost Awareness            | Consider model selection, request volume, token usage, and operational cost |            3 | 7, 9            | Cost and usage estimate                |
| Responsible AI            | Document privacy, accuracy, bias, and human-review considerations           |            3 | 7, 12           | Responsible-use section                |
| AI Workflow Architecture  | Combine AI with deterministic logic, APIs, databases, and approvals         |            4 | 7, 8, 12        | AI-enabled business system             |

---

# 8. Production and Operations Competencies

| Competency               | Employer Expectation                                                 | Target Level | Primary Modules | Required Evidence                  |
| ------------------------ | -------------------------------------------------------------------- | -----------: | --------------- | ---------------------------------- |
| Error Handling           | Anticipate and manage node, API, data, and business-rule failures    |            4 | 2, 4, 5, 8, 9   | Failure-tested workflow            |
| Retry Strategies         | Apply retries, delays, backoff, and recovery appropriately           |            4 | 4, 9            | Retry and recovery demonstration   |
| Error Workflows          | Route failures to centralized error-handling processes               |            3 | 9               | Reusable error workflow            |
| Logging                  | Record useful execution, business, and failure information           |            4 | 5, 8, 9         | Logging implementation             |
| Monitoring               | Define how workflow health and failures will be observed             |            3 | 9               | Monitoring plan                    |
| Alerting                 | Notify responsible users when intervention is required               |            4 | 5, 8, 9         | Failure-alert workflow             |
| Credential Security      | Configure and manage credentials without exposing secrets            |            4 | 0, 4, 9         | Secure configuration documentation |
| Environment Variables    | Separate configuration from workflow logic                           |            3 | 9               | Environment setup guide            |
| Least Privilege          | Limit service access to only the permissions required                |            3 | 4, 6, 9         | Security review                    |
| Data Privacy             | Recognize and reduce unnecessary exposure of sensitive information   |            3 | 6, 7, 9         | Privacy considerations             |
| Testing                  | Test successful, invalid, empty, duplicate, and failure scenarios    |            4 | 2–12            | Test cases and results             |
| Debugging                | Trace data and isolate workflow failures systematically              |            4 | 2–12            | Broken-workflow exercises          |
| Performance Optimization | Reduce unnecessary executions, requests, processing, and duplication |            3 | 8, 9            | Optimization review                |
| Scalability Analysis     | Identify bottlenecks and explain how a workflow could scale          |            3 | 9, 12           | Scalability section                |
| Version Control          | Store documentation and workflow exports using Git                   |            4 | 0–12            | Repository history                 |
| Deployment               | Deploy n8n in a production-like environment                          |            3 | 9, 12           | Deployment evidence                |
| Backup and Recovery      | Document backup, restoration, and failure-recovery practices         |            3 | 9, 12           | Recovery plan                      |
| Maintenance              | Update, monitor, and support workflows after deployment              |            3 | 9, 12           | Maintenance guide                  |

---

# 9. Business Analysis and Solution Design Competencies

| Competency                            | Employer Expectation                                                    | Target Level | Primary Modules | Required Evidence                     |
| ------------------------------------- | ----------------------------------------------------------------------- | -----------: | --------------- | ------------------------------------- |
| Process Analysis                      | Describe an existing business process and identify inefficiencies       |            4 | 1, 8, 12        | Current-state process diagram         |
| Automation Opportunity Identification | Determine which tasks should and should not be automated                |            4 | 1, 7, 8         | Opportunity assessment                |
| Requirements Gathering                | Ask focused questions about users, data, rules, risks, and outcomes     |            4 | 8, 12           | Requirements document                 |
| Scope Definition                      | Define what is included, excluded, assumed, and dependent               |            4 | 8, 10, 12       | Project scope                         |
| User Stories                          | Translate needs into clear user-centered requirements                   |            3 | 8, 12           | User stories and acceptance criteria  |
| Architecture Design                   | Represent triggers, systems, data movement, and failure paths           |            4 | 4–12            | Architecture diagram                  |
| Solution Evaluation                   | Compare alternative approaches and explain trade-offs                   |            4 | 8, 9, 11, 12    | Architecture decision record          |
| Business Rules                        | Translate policies and decisions into workflow logic                    |            4 | 2, 8, 12        | Rules-based automation                |
| Human-in-the-Loop Design              | Identify where approvals or manual review are required                  |            4 | 7, 8, 12        | Approval or review workflow           |
| Business Value Estimation             | Explain time savings, risk reduction, speed, or service improvements    |            3 | 8, 10, 12       | Business-impact statement             |
| Stakeholder Communication             | Explain the solution in language appropriate to the audience            |            4 | 8, 10, 11, 12   | Technical and non-technical summaries |
| Change Management Awareness           | Consider user adoption, training, ownership, and process changes        |            3 | 8, 12           | Rollout plan                          |
| Client Handoff                        | Deliver setup, operation, troubleshooting, and maintenance instructions |            4 | 8, 10, 12       | Client-ready documentation            |

---

# 10. Professional and Career-Readiness Competencies

| Competency              | Employer Expectation                                                              | Target Level | Primary Modules | Required Evidence                      |
| ----------------------- | --------------------------------------------------------------------------------- | -----------: | --------------- | -------------------------------------- |
| Technical Documentation | Produce clear setup, architecture, testing, and maintenance documentation         |            4 | 0–12            | Project READMEs                        |
| Workflow Presentation   | Walk through an automation clearly and logically                                  |            4 | 10, 11, 12      | Recorded or live demonstration         |
| Technical Communication | Explain technical decisions without unnecessary complexity                        |            4 | 8, 10, 11, 12   | Project presentation                   |
| Business Communication  | Explain value, risk, assumptions, and limitations to stakeholders                 |            4 | 8, 10, 11, 12   | Executive summary                      |
| Git Practices           | Use branches, commits, repository organization, and version history appropriately |            3 | 0–12            | Git repository                         |
| Portfolio Development   | Convert technical work into compelling case studies                               |            4 | 10              | Completed portfolio                    |
| Resume Alignment        | Connect projects and competencies to job requirements                             |            3 | 10, 11          | Role-aligned project descriptions      |
| Interview Storytelling  | Explain challenges, actions, decisions, and results                               |            4 | 11              | Structured interview answers           |
| Technical Interviewing  | Answer workflow, API, database, AI, debugging, and architecture questions         |            4 | 11              | Mock interview performance             |
| Live Problem Solving    | Analyze an unfamiliar scenario and propose an automation approach                 |            4 | 11, 12          | Design challenge                       |
| Professional Judgment   | Recognize limitations, risks, and when additional expertise is needed             |            4 | 7, 8, 9, 11, 12 | Project reflection                     |
| Independent Learning    | Use documentation, experimentation, and testing to learn unfamiliar tools         |            4 | 4–12            | Integration with an unfamiliar service |
| Ownership               | Move a project from requirements through delivery and maintenance planning        |            4 | 8, 12           | End-to-end project delivery            |

---

# 11. Role Alignment

## Automation Engineer

Priority competencies:

- Workflow architecture
- Business process analysis
- Data transformation
- API integration
- Error handling
- Testing
- Monitoring
- Documentation

## n8n Developer

Priority competencies:

- n8n workflow design
- Expressions
- Code nodes
- APIs
- Webhooks
- Databases
- Reusable workflows
- Debugging
- Deployment

## Integration Engineer

Priority competencies:

- API documentation
- Authentication
- Data mapping
- Webhooks
- Data synchronization
- Idempotency
- Rate-limit handling
- System reliability

## AI Automation Engineer

Priority competencies:

- AI use-case analysis
- Prompt design
- Structured output
- AI extraction and classification
- Validation
- Human review
- Cost awareness
- Responsible AI
- AI workflow architecture

## Automation Consultant

Priority competencies:

- Requirements gathering
- Scope definition
- Process analysis
- Architecture design
- Business value
- Stakeholder communication
- Documentation
- Client handoff

## Technical Solutions Engineer

Priority competencies:

- Technical discovery
- Solution design
- Integration
- Demonstration
- Troubleshooting
- Documentation
- Client communication
- Technical presentation

---

# 12. Module-to-Competency Summary

| Module                             | Primary Competency Focus                                | Expected Exit Level |
| ---------------------------------- | ------------------------------------------------------- | ------------------: |
| Module 0 — Orientation             | Tools, Git, environment, professional workflow          |                   1 |
| Module 1 — Automation Fundamentals | Process logic, workflow concepts, JSON basics           |                   2 |
| Module 2 — Core n8n                | Conditions, loops, expressions, execution control       |                 2–3 |
| Module 3 — Data Transformation     | Mapping, validation, transformation, Code nodes         |                   3 |
| Module 4 — APIs                    | HTTP, authentication, pagination, rate limits           |                   3 |
| Module 5 — Webhooks                | Event-driven design, validation, responses, security    |                   3 |
| Module 6 — Databases               | CRUD, relational concepts, synchronization, idempotency |                   3 |
| Module 7 — AI Automation           | Structured AI workflows, validation, human review       |                   3 |
| Module 8 — Business Systems        | Requirements, architecture, multi-system delivery       |                 3–4 |
| Module 9 — Production Engineering  | Reliability, monitoring, deployment, security           |                 3–4 |
| Module 10 — Portfolio Development  | Documentation, case studies, presentations              |                   4 |
| Module 11 — Interview Preparation  | Explanation, debugging, design, communication           |                   4 |
| Module 12 — Capstone               | Independent end-to-end professional delivery            |                   4 |

---

# 13. Required Portfolio Evidence

A job-ready graduate must present evidence covering all major competency domains.

The final portfolio must include:

1. A branching and rules-based workflow.
2. A data-cleaning or transformation workflow.
3. An authenticated REST API integration.
4. A webhook-driven workflow.
5. A database-backed automation.
6. An AI-enabled business workflow.
7. A workflow with tested error handling and recovery.
8. A deployed or production-oriented project.
9. A complete business-system automation.
10. A capstone integrating multiple systems and competencies.

At least three projects must demonstrate multiple competency domains.

---

# 14. Competency Assessment Methods

Competencies may be assessed through:

- Guided labs
- Independent labs
- Design challenges
- Debugging exercises
- Written explanations
- Architecture diagrams
- Workflow exports
- Code reviews
- Project documentation
- Demonstrations
- Mock interviews
- Capstone defense

No competency should be marked complete based only on a multiple-choice quiz.

Practical evidence is required.

---

# 15. Competency Completion Standard

A competency is considered achieved only when the student can:

1. Explain the purpose of the skill.
2. Apply it in a working workflow.
3. Test normal and failure cases.
4. Identify common risks.
5. Document the implementation.
6. Explain key decisions.
7. Apply the skill to a different scenario.

Completing a guided exercise alone does not demonstrate professional competency.

---

# 16. Job-Readiness Gate

Before being classified as job ready, the student must demonstrate the ability to complete an unfamiliar automation scenario with limited guidance.

The student must:

1. Analyze the business problem.
2. Ask appropriate clarification questions.
3. Define scope and assumptions.
4. Design the architecture.
5. Build the workflow.
6. Integrate required systems.
7. Test successful and failure scenarios.
8. Add appropriate error handling.
9. Document the solution.
10. Present and defend the implementation.

The student should achieve at least Level 3 in every core competency and Level 4 in the competencies most relevant to their target role.

---

# 17. Continuous Review

This competency matrix must be reviewed whenever:

- The curriculum changes.
- New modules are introduced.
- Projects are added or removed.
- n8n introduces significant capabilities.
- Employer expectations change.
- Graduate or interview feedback reveals a skills gap.

All major updates must be recorded in `CHANGELOG.md`.

The purpose of continuous review is not to chase every new tool or trend.

The purpose is to keep the bootcamp aligned with durable professional capabilities and realistic workplace responsibilities.
