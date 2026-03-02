## Scenario
The Problem Management team wants to prevcent IT Analysts from reopening Problem records that is oolder than 30 days to document ongoing work performed on the same Configuration Item (CI).

## Objective
Prevcent IT Analysts from reopening Problem records that is oolder than 30 days using UI Policy and Java Script

## Tasks Completed
- Configure UI Actions
- GlideDateTime usage
- GlideDuration usage
- Server-side validation
- Business Rule enforcement
- Script Include utilization
- Defensive error handling

## Result
When someone try to open a Problem a Problem, the script calculate how old the Problem has been closed, blocks reoprning if more thanm 30 days, allows reanalysis if 30days or less. 
