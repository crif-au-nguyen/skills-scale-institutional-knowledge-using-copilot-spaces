# Role-Responsibility Mapping Template

## Purpose
This template helps project teams define and communicate who is responsible, accountable, consulted, and informed (RACI) for key project activities. Use it during project initiation to clarify roles and prevent accountability gaps.

## How to Use
1. Copy this template into your project repository
2. Fill in the roles present on your project team
3. Mark each activity with the appropriate designation:
   - **R** = Responsible (does the work)
   - **A** = Accountable (ultimate ownership, approves)
   - **C** = Consulted (provides input)
   - **I** = Informed (kept in the loop)
4. Review with the team during kickoff to ensure alignment
5. Update as roles or responsibilities change

---

## Project: [Project Name]
**Last Updated**: [Date]

| Activity / Deliverable | Product Owner | Scrum Master | Developer | Technical Lead | Business Analyst | Product Manager | Project Manager | Stakeholder | QA/Testing |
|------------------------|---------------|--------------|-----------|----------------|------------------|-----------------|-----------------|-------------|------------|
| **Initiation Phase** |
| Project Charter | C | I | I | C | C | A | R | C | I |
| Problem Statement | C | I | I | I | R | A | C | C | I |
| Success Metrics | C | I | I | I | R | A | C | C | I |
| **Planning Phase** |
| Backlog Creation | A,R | C | C | C | C | C | C | I | I |
| User Story Definition | A,R | C | C | C | C | I | I | C | I |
| Sprint Planning | A | R | C | C | I | I | C | I | C |
| Technical Architecture | C | I | C | A | I | C | C | I | I |
| Estimation | C | R | R | A | I | I | C | I | C |
| Risk Identification | C | R | C | C | C | C | A | C | I |
| **Execution Phase** |
| Daily Standup | C | R | R | C | I | I | I | I | I |
| Feature Development | C | I | A,R | C | I | I | I | I | I |
| Code Review | I | I | R | A | I | I | I | I | I |
| Story Acceptance | A | I | I | I | I | C | I | I | C |
| Blocker Resolution | C | A | R | C | I | I | R | I | I |
| Technical Decisions | C | I | C | A | I | C | I | I | I |
| Requirements Clarification | A | I | C | I | R | C | I | C | I |
| **Quality & Testing** |
| Test Planning | C | I | C | C | I | I | C | I | A |
| Unit Testing | I | I | A,R | C | I | I | I | I | I |
| Integration Testing | C | I | R | C | I | I | I | I | A |
| User Acceptance Testing | A | I | I | I | R | I | C | C | R |
| Bug Triage | C | R | R | C | I | C | C | I | A |
| **Release & Deployment** |
| Release Planning | C | I | C | C | I | A | R | C | I |
| Deployment Execution | I | I | R | C | I | I | C | I | A |
| Smoke Testing | I | I | R | C | I | I | C | I | A |
| Rollback Decision | I | I | C | C | I | C | A | I | I |
| Release Communication | I | I | I | I | I | C | A,R | I | I |
| **Monitoring & Improvement** |
| Sprint Review/Demo | A | R | R | C | I | C | C | C | C |
| Retrospective | C | A,R | R | R | C | I | C | I | C |
| Metrics Tracking | C | R | I | I | I | A | R | I | I |
| Process Improvement | C | A | C | C | C | C | R | I | C |

---

## Notes
- Adapt this matrix to your project's specific needs
- Some activities may have multiple Responsible parties (joint responsibility) when they perform different aspects of the same activity
- Only one person/role should be Accountable for each activity (exception: A,R when same role does both)
- **Product Owner** is both Accountable and Responsible for Backlog Creation and User Story Definition in standard Agile practices. Business Analysts support this work but don't typically own it.
- **User Acceptance Testing**: Product Owner is Accountable for acceptance decisions. Business Analyst is Responsible for coordinating UAT activities (scheduling, communication, documentation), while QA/Testing is Responsible for executing tests. Both R assignments are valid as they cover different aspects of UAT.
- Review and update this matrix at major project milestones
- Use this as a reference during role handoffs or onboarding

## Related Documents
- [Roles & Personas](octoacme-roles-and-personas.md)
- [Project Management Overview](octoacme-project-management-overview.md)
- [Role Onboarding Checklist](template-role-onboarding-checklist.md)
