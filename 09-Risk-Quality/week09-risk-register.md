# Risk Register: RCHN Patient Intake and Scheduling System
**Consultant:** [Jesus Reyes]
**Role:** Associate Consultant, NovaTech Consulting
**Engagement:** Regional Care Health Network (RCHN)
**Date:** [11/1/2026]
---
## Risk Entries

### Risk 1
**Description:** [If data migration errors occurs, then patient appointments mayb be lost, create schedule conflicts, and breakdown clinical operations for the RCHN project.]
**Probability:** [High]
**Impact:** [High]
**Score:** [9]
**Response Strategy:** [Mitigate], [The team will mitigate this risk.]
**Trigger or Monitoring Condition:** [ They will do so by establishing and enforce a mandatory database verification audit that requires a zero percent error rate before moving over to the new system.]
**Owner:** [Risk 1 owner would be the developer. The role of a developer is responsible for inspecting migration scripts and execute validation audits for databases. 

### Risk 2
**Description:** [If incomplete staff training occurs, then front desk processing speeds will drop and cause severe patient lines that will burnout staff.]
**Probability:** [High]
**Impact:** [High]
**Score:** [9]
**Response Strategy:** [Avoid / Mitigate / Transfer / Accept], [The team will mitigate this risk ]
**Trigger or Monitoring Condition:** [the team will mitigate this risk by deploying flexible training during shifts.]
**Owner:** [Risk 2 owner would be the Scrum master. The role is responsible for enforcing the definition of done and monitoring user readiness.]

### Risk 3
**Description:** [3.	If the clinics in the RCHN network are not equipped with the proper hardware for the new system, then staff may experience bottlenecks and patient check-in delays.]
**Probability:** [Low]
**Impact:** [High]
**Score:** [3]
**Response Strategy:** [Avoid / Mitigate / Transfer / Accept], [The team will mitigate the risk ]
**Trigger or Monitoring Condition:** [The team will mitigate the risk by testing the networks bandwidth and upgrading hardware. ]
**Owner:** [Risk 3 owner is the Project manager. The role is responsible for managing the project scope and everything that is included in the scope such as vendor contracts, hardware budget, and schedule dependencies.]

### Risk 4
**Description:** [If API integration between the new and old system experiences a mismatch, then data migration will fail validation, delay site cutover and block the go-live schedule. ]
**Probability:** [Low]
**Impact:** [High]
**Score:** [3]
**Response Strategy:** [Avoid / Mitigate / Transfer / Accept], [The team will mitigate the risk]
**Trigger or Monitoring Condition:** [The team would avoid the risk by making sure that a translator is built early in the project before the execution phase. ]
**Owner:** [Risk 4 owner is the Project Manager. This role is responsible for managing backlog prioritization, define user acceptance criteria, and validating that technical deliverables are aligned with operational requirements.]

### Risk 5
**Description:** [5.	If HIPPA privacy and role-based access control configurations are not audited and verified, then unauthorized personnel may access protected health information which will affect the integrity of patient data.]
**Probability:** [Low]
**Impact:** [High]
**Score:** [3]
**Response Strategy:** [Avoid / Mitigate / Transfer / Accept], [The team will transfer the risk.]
**Trigger or Monitoring Condition:** [The team would transfer this risk to a third-party to conduct  a security audit. ]
**Owner:** [Risk 5 owner is the Project manager. This role is responsible for governance, risk compliances, and securing a formal sign-off before deployment.]

---
## Bring Forward
**Week 5 assumptions:** [Assumption 1: Clinic staff across all six RCHN locations are available and will complete mandatory system training without any disruptions before the go live date. 
Assumption 2: all RCHN locations have the right hardware, software and network that will allow for seamless deployment of the new system.
]
**Week 7 backlog item:** [As an Intake coordinator, I want to register new patients using a unified single-screen interface, so that data is carried forward automatically. ]
**Week 8 schedule item:** [Milestone: System Integration & User Acceptance Testing completed. ]
---
## Assumption Connection
[Risk 2 staff training comes from the weeks five assumption of staff being available for training. The uncertainty is whether staff can take time off from work to complete the mandatory training. This threatens the schedule and operation quality project objectives. 

Risk 3 Resources and schedule are connected to week 5 assumption 2. If there are hardware delays or network issues due to the lack of right equipment, then real time portal responsiveness will affect patient check-ins. 
]
---
## Score Justification
[For Risk 1, I rated probability as high because there is a transition of data going from an old legacy system into a newer system which can mean errors, delays, or failure. I also rated the impact as high because data is a very crucial part of daily clinic operations and the quality of the services depend on it. 
For Risk 5, I rated the probability as low because there is no need from any stakeholder to address this issue, but also rated the impact as high because if there is an issue with HIPPA compliance it is part of federal regulations. 
]
---
## Risk Reflection
### Highest Priority Risk and Project Impact
[My highest- priority threat is risk 1 with a score of 9. It deserves the most attention it’s a risk that can turn into a constant issue during clinic operations. 
If it occurred it could affect the quality of the clinic services by adding frustration to the scheduling and data processing of patients, cost by a required manual record cleanup which requires developers working overtime and go-live readiness by violating the definition of done the system cannot be deployed. 
]

### Risk vs. Issue Distinction
[After reviewing my five risks, I confirmed that each one is a future uncertainty because risk 1 has not shown any actual corruption or appointment losses that have occurred. Risk 2 is still a risk because there is still no operational failure that can show that training is not complete. Risk 3 is still a risk because there hasn’t been any latency in the live intake workflow. Risk 4 remains a risk because API mismatching is just a threat and there is no active software crash. Risk 5 remains a risk because there has been no compliance violation that has occurred in the system. 
The distinction between a risk and an issue matter because treating an issue like a risk leads to active problems such as check-ins failing at the front desk. If a risk is treated like an issue then time and resources are wasted and pull that time and resources away from the actual workflow efficiency need that the new system must provide for the clinics. 
]
---
*NovaTech Consulting | IT 3310 | Governors State University | Fall 2026*
