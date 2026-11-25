# Project Status Report and Lessons Learned
## RCHN Patient Intake and Scheduling System Replacement

**Consultant:** [Jesus Reyes]
**Role:** Associate Consultant, Executive Perspective, NovaTech Consulting
**Client:** Regional Care Health Network (RCHN)
**Reporting Period:** Sprint 7 of 10 (Project Week 21 of 32)
**Report Date:** [11/25/2026]

---

## Executive Summary

[At the close of Sprint 7 (Week 21 of 32), the RCHN intake and scheduling project is overall Amber, balancing controlled scope and a nine-day interface testing slip against a $64,000 (6.4%) budget variance and a high-severity operational risk. While the schedule recovery plan protects the go-live date by deferring the pending provider mobile schedule view, the single most consequential issue is Risk R-04: clinic staff training now overlaps peak flu-season patient volume. Left unresolved, this overlap threatens front-desk throughput, patient check-in speed, and clinic staffing across RCHN locations during a high-demand period. We ask Marcus Webb and Dr. Angela Torres at Thursday's steering committee meeting to approve deferring the provider mobile schedule view to the post-launch backlog and authorize a protected training coverage or staggered cohort plan by Friday of Week 21. ]

---

## Status Reporting Fundamentals

[When a status report is incomplete or overly optimistic, it hides real problems and leads executives to make poor funding and staffing choices based on false assumptions. If a project manager marks a struggling task as Green or leaves out actual numbers, leaders won't see delays coming and can't step in to shift schedules or move staff where they are needed most. Waiting too long to share bad news shrinks the window to fix it, turning small, manageable setbacks into expensive emergencies with very few good options left. On the flip side, bringing up risks and delays early with clear facts gives leaders time to weigh trade-offs while changes are still practical. At the end of the day, being upfront about issues shows real professionalism because it puts project success ahead of keeping people temporarily comfortable.]

---

## Project Health: RAG Status

| Dimension | Rating | Basis for Rating |
|---|---|---|
| Schedule | [Amber] | [Integration testing on the insurance eligibility interface slipped by nine days after vendor documentation arrived without sample payloads, leaving two of three Sprint 7 commitments delivered. The go-live date is not currently at risk because the team has a credible recovery sequence that preserves the timeline by deferring the pending provider mobile schedule view to a post-launch release. Leadership action is required at Thursday's steering committee meeting to approve this scope deferral so the recovery plan can be executed.] |
| Budget | [Amber] | [Actual spend through Sprint 7 reached $1,062,000 against a planned spend of $998,000, creating a $64,000 (6.4 percent) unfavorable variance driven by two weeks of unplanned vendor integration support. While $418,000 remains across Sprints 8 through 10 (averaging $139,333 per sprint compared to the $151,714 historical sprint burn rate), the team can finish within the $1,480,000 approved budget by ending the temporary vendor support and deferring the pending mobile feature. Leadership approval of the scope deferral is required to prevent additional development costs, though no budget increase is requested at this time.] |
| Scope | [Amber] | [Two change requests—SMS appointment reminders and Spanish-language intake screens—were properly approved through governance, representing controlled scope growth rather than scope creep. However, the pending change request for the provider mobile schedule view is directly tied to the schedule recovery sequence and must be deferred to post-launch to protect the go-live date. Leadership decision is required from Marcus Webb and Dr. Angela Torres on Thursday to formally defer the provider mobile schedule view to the post-launch backlog.] |
| Risk | [Red] | [R-04 (clinic staff training availability during flu season) escalated from medium to high because the scheduled training window now overlaps peak patient volume, posing a direct threat to daily clinic operations and user adoption. Compounded by incomplete vendor interface documentation and a business analyst rolling off the project two weeks early, existing mitigation plans are no longer sufficient without executive intervention. Immediate leadership action is required from Dr. Angela Torres and clinic leadership to authorize protected training coverage or an adjusted training schedule during peak flu season.] |

**Budget variance:** $64,000 over planned position at end of Sprint 7 (6.4 percent).

---

## Status Narrative

### Accomplishments This Period
[During Sprint 7, the team finished building and testing two of its three planned deliverables—SMS appointment reminders and Spanish-language intake screens—and reviewed project spending, which sits at $1,062,000 out of the $1,480,000 approved budget ($418,000 left). The team also traced a $64,000 budget overrun to two weeks of unplanned vendor integration support and identified missing vendor sample payloads as the reason behind a nine-day delay in insurance eligibility testing. To keep the project on track for its Week 32 go-live date, the team mapped out a recovery plan and reassigned tasks after one business analyst left the project two weeks early.]

### Planned for Next Period
[In Sprint 8, the team plans to finish integration testing on the insurance eligibility interface using the new vendor sample payloads to clear the nine-day delay. They will also roll out the recovery plan by moving the provider mobile schedule view out of the current release and locking the core intake and scheduling build for user acceptance testing. Finally, the team will work with clinical operations leaders to update the clinic staff training plan to handle peak flu-season patient traffic.]

### Decisions or Approvals Required
[Leadership needs to make two decisions to keep the project on track. First, Marcus Webb and Dr. Angela Torres need to approve moving the provider mobile schedule view to the post-launch backlog during Thursday's steering committee meeting so Sprint 8 can move forward without delaying the launch. Second, Dr. Angela Torres and clinical operations leaders need to decide by Friday of Week 21 whether to provide backfill or overtime coverage for staff training or use a staggered training schedule to avoid clinic slowdowns during peak flu season.]

---

## Lessons Learned Register

### Entry 1
- **Category:** [What Did Not Work]
- **Project Phase:** [Execution]
- **What Happened:** [Even though earlier project plans flagged API mismatch risks and a lack of regular vendor check-ins, the insurance eligibility interface documentation arrived in Sprint 7 without sample test data. This missing information delayed integration testing by nine days and forced the team to pay for two extra weeks of unplanned vendor support, pushing actual spending to $1,062,000—which is $64,000 (6.4%) over the $998,000 budget]
- **Recommendation for Future Projects:** [: Require sample payloads, test sandbox credentials, and schema validation criteria as contractual sign-off gates at least two weeks before integration testing starts, and hold recurring status check-ins with external vendors throughout build and testing. ]

### Entry 2
- **Category:** [Risk or issue insight]
- **Project Phase:** [Monitoring and Control]
- **What Happened:** [Early planning flagged staff training availability as a workload risk (Week 5 Assumption 1 and Week 9 Risk #2), and in Sprint 7 Risk R-04 escalated from medium to high because the scheduled training window overlapped peak flu-season patient volume—threatening front-desk speed, clinic staffing, and go-live readiness.]
- **Recommendation for Future Projects:** [Check planned training and rollout dates against the client's seasonal operational peak calendar during schedule baselining, and lock in protected staff backfill or staggered training cohorts before training begins.]

### Entry 3
- **Category:** [What to do differently]
- **Project Phase:** [Monitoring and Control]
- **What Happened:** [During Sprint 7, a business analyst left the project two weeks early while two change requests—SMS reminders and Spanish-language intake screens—were approved and a third request for a provider mobile schedule view remained pending, prompting a plan to push that mobile view to a later release so the launch timeline stays intact. Earlier in Weeks 10–12, the resource plan showed how staffing changes can impact budget and schedule, and the AI review found that Microsoft Copilot scored highest (3.80) for drafting non-PHI updates, as long as teams keep strict data limits and review its output by hand.]
- **Recommendation for Future Projects:** [Require a documented knowledge-transfer handoff before any key role rolls off, evaluate every pending change request against remaining capacity and critical-path impact before adding it to a sprint, and enforce strict data boundaries plus human review on all AI-assisted reporting. ]

[Repeat this pattern for any additional entries.]

---

## Recommendation to RCHN Leadership

[RCHN leadership should approve a staggered training schedule and provide backup coverage for front-desk and clinical staff before training starts. Chief Medical Officer Dr. Angela Torres, clinic operations leaders, and Project Sponsor Marcus Webb should finalize and sign off on this plan by Friday of Week 21. This ties directly to Lessons Learned Entry 2 (Risk or issue insight), which showed that planning staff training without considering busy patient seasons raises operational risks. Matching training times and staff coverage to clinic capacity helps keep daily patient check-ins and scheduling running smoothly while staying on track for launch.]

---

*NovaTech Consulting | IT 3310 IT Project Management | Governors State University | Fall 2026*
