# Issue Log and Escalation Record

**Simulation scenario** | **Status:** Active

| ID | Related risk | Issue description | Date raised | Impact | Owner | Corrective action | Target resolution | Status |
|---|---|---|---|---|---|---|---|---|
| I-001 | R-02 | Customer master data contains duplicate and incomplete records, preventing trial migration | Month 5 | High — migration and testing delay | Data Lead | Assign business data owners; run deduplication and completion sprint; repeat validation before retry | Month 6 | In progress |
| I-002 | R-04 | Legacy inventory API returns inconsistent data formats | Month 5 | Medium — integration rework | Technical Lead | Add transformation layer; update interface specification; rerun integration tests | Month 6 | In progress |
| I-003 | R-05 | Two key finance users are unavailable during planned user acceptance testing | Month 7 | High — testing coverage gap | PMO Analyst | Approve trained delegates; revise test schedule; prioritize critical test cases | Month 7 | In progress |

## Escalation record — I-001

| Field | Detail |
|---|---|
| Escalation trigger | Data-quality issue remained unresolved after the first remediation sprint |
| Escalated to | Project sponsor and steering committee |
| Business impact | Trial migration delayed by two weeks; user acceptance testing at risk |
| Decision requested | Approve additional data-cleansing support and revise the migration baseline |
| Decision | Approve temporary data analyst support and shift trial migration by two weeks |
| Contingency used | €18,000 from contingency reserve |
| Follow-up | Data owners to sign off validated records before the revised migration date |
