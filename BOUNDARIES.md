# A2A-SIN-Teams Boundaries

## Role
`A2A-SIN-Teams` owns Microsoft Teams messaging integration, channel workflows, and Teams-specific contracts.

## This repo should own
- Teams messaging, channel coordination, and meeting-support workflows
- Teams evidence, recovery, auth, and session handling
- Teams contracts used by downstream communication automation agents
- runbooks tied to channel delivery, meetings, and Teams automation

## This repo must not own
- generic messaging ownership outside Teams
- unrelated social, meeting, or chat platform behavior not tied to Teams
- organization SSOT docs or architecture canon

## Hard rules
- Keep changes scoped to Microsoft Teams messaging and collaboration workflows.
- Move non-Teams behavior back to the repos that own those surfaces.
- Keep reusable contracts focused on Teams delivery, channels, and meeting support.
