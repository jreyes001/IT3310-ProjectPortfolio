# Project Schedule: RCHN Patient Intake and Scheduling System
**Consultant:** [Jesus Reyes]
**Role:** Associate Consultant, Project Manager, NovaTech Consulting
**Engagement:** Regional Care Health Network (RCHN)
**Date:** [10/27/2026]
---
## Work Breakdown Structure

### Grouping 1: [1.0 Project Initiation and Assesment]
- [1.1 Outdated System Audit and Technical Evaluation]
- [1.2 Stakeholder Alignment and Scope Baseline]
- [1.3 Project Plan and Governance Setup]

### Grouping 2: [2.0 Intake and Scheduling Redesign]
- [2.1 Current Intake Workflow Analysis]
- [2.2 New Intake and Scheduling System Architecture]
- [2.3 Interface Prototype and Workflow Validation]

### Grouping 3: [3.0 Data re-entry and Migration]
- [3.1 Data Extraction of old system]
- [3.2 Data Re-Entry Protocols]
- [3.3 Data Migration and Execution]

### Grouping 4: [4.0 Testing, Deployment and Transistion]
- [4.1 System Integration and USer Acceptance Testing (UAT)]
- [4.2 Old System Cutover and Deployement]
- [4.3 Staff Training and Post-Implementation Review]

### WBS Rationale
[My WBS addresses an outdated system that focuses on fixing the workflow problem for all six RCHN clinics. Phase 1 establishes a stakeholder to scope alignment and project plan,  phase 2 focuses on the need for a fast and reliable intake and scheduling system, and phase 3 tackles the data re-entry and migration problem. 
What I decided to intentionally exclude was hardware replacement. This so far is not a requirement . 
Security compliance checks and user permission updates have been added into phase for testing and deployment. 
]
---
## Task Dependencies

- [Outdated System Audit & Technical Evaluation] → [New Intake & Scheduling System], [Dependency type: Finish-to-Start]

- [New Intake & Scheduling System] → [Data Re-Entry], [Dependency type: Finish-to-Start]

- [Data Re-Entry] → [Data Migration], [Dependency type: Start-to-Start]

### Dependency Logic
[The Finish-to-Start outdated system audit and evaluation is a dependency that could affect the schedule. If the outdated system audit slips by two weeks the design phase for the new intake and scheduling system cannot begin. Since intake and scheduling is the projects focus it would create a ripple effect slowing down any task that comes after the system audit and evaluation which would create a ripple effect. It would push back task such as data migration, prototypes, and final testing. To mitigate the impact the team could compress other task to regain the lost two weeks. ]
---
## Activity Schedule
| ID | Activity | Duration (working days) | Predecessors | Start week |
|---|---|---:|---|---:|
| A | [Current System Audit and Intake requirements] | [Days 5] | None | [Week 1] |
| B | [Design Intake and Scheduling Workflow Prototypes] | [Days 10] | [A] | [Week 2] |
| C | [Develop Legacy Data Re-Entry and Migration] | [Days 5] | [A] | [Week 2] |
| D | [Execute User Acceptance Testing for Intake form] | [Days 5] | [B,C] | [Week 4] |

### Scheduling Assumptions
[The schedule is built on a five-day workweek. Starting in week 1 with task A, a five-day audit to map out system bottlenecks and baseline requirements. In week 2  task B, there are two task that run at the same time making the duration of these tasks ten days which would run through weeks 2 and 3. Task C works in week 2 to establish any data re-entry rules. Task A must be completed for task B and C to begin. For the last task, task D which starts in week four after B and C are completed focuses on five days to complete any user testing. An uncertainty that could change the schedule would be any unexpected data corruption which means task C would take longer and would delay task D. ]
---
## Milestones
[Milestone 1]
- [Intake & Scheduling Design Baseline Approved], [Exit criteria:A sign off from the project lead and key stakeholders approving the finalized intake user interface ]

[Milestone 2]
- [System Integration & User Acceptance Testing (UAT) Completed], [Exit criteria:A 100% success rate with the automated scheduling, and data re-entry, with any bugs resolved and a sign- off from the testing leads.]

### Critical Path Analysis
[The critical path would be path 2 (A→C→D). The duration of this path would be 11 days making path 1 the ideal path to take.  If a 2-day delay happens at the critical path, then the total project is delayed by 2 days because there is a zero total float making it 13 days. In comparison my own preliminary schedule is cut out in weeks of 5 days each. ]
---
## Schedule Reflection
### Scope Connection
[The Intake and scheduling redesign phase targets the primary goal of the project by replacing a slow system with a faster and more reliable one. The assumptions made are that the operational stakeholders will be able to review in week 3 but will also still need final confirmation on the review approval window. ]

### Objective Connection
[The Intake & Scheduling Design Baseline Approved milestone supports NovaTech's core objective of modernizing the outdated system while serving as a critical delivery transition point. Achieving sign-off on this milestone marks the formal completion of the design phase and authorizes the team to move into full technical development and testing. ]
---
*NovaTech Consulting | IT 3310 | Governors State University | Fall 2026*
