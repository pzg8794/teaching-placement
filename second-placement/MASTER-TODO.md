# Fall 2026 Second Teaching Placement Master

**Project role:** Public-safe index and execution tracker for the Grade 6–12 placement; sensitive evidence stays local/private
**Course owner:** [EDF436 master](https://github.com/pzg8794/EDF436/blob/main/MASTER-TODO.md)
**Placement period:** September 8–November 20, 2026
**Last reconciled:** September 7, 2026

This project indexes placement logistics, private-source locators, public-safe
planning, and de-identified reflections. Original private evidence stays in the
authenticated mailbox, approved private storage, or ignored local directories.
EDF436 owns course deadlines and submission status. Do not duplicate course
completion states here.

## Source status at a glance

- Written Gmail evidence is indexed in the
  [placement source summary](communications/PLACEMENT-SOURCE-SUMMARY.md).
- The written chain proves a September 2 call was arranged, but not that it
  occurred or what was discussed.
- **The September 2 call transcript is not found locally.** Do not attribute
  start/end-time or recurrence claims to that transcript unless it is recovered.

## Current actions

| Priority | Action | Deadline / trigger | Source | State | Evidence location | Next step |
|---|---|---|---|---|---|---|
| P0 | Begin Grade 6–12 placement | **Sep 8; planning record says arrive 7:00 AM for 7:30 AM class** | Current project planning record; the previously cited call transcript is not found locally | SCHEDULED IN PROJECT; underlying primary source needs recovery/reverification; attendance not yet evidenced | Keep attendance/private notes outside public Git | Verify against the authoritative calendar/form if available, pack materials, and retain private attendance evidence |
| P0 | Follow the SBTE-confirmed daily schedule | Sep 8 and subsequent assigned placement days | [Gmail source summary](communications/PLACEMENT-SOURCE-SUMMARY.md) plus authoritative private schedule | Recurring weekdays and daily departure time still not recorded in this project | [`communications/`](communications/) | Capture the current schedule from the authoritative communication; do not infer recurrence |
| P1 | Recover or reverify the September 2 call record | Before using call-derived facts as confirmed evidence | [Gmail source summary](communications/PLACEMENT-SOURCE-SUMMARY.md) | Call was arranged; transcript not found locally | Ignored `transcripts/private/` if recovered; only a de-identified summary may enter Git | Search the private Plaud/export archive or independently verify the schedule from an authoritative form/calendar |
| P1 | Record privacy-safe placement reflection/evidence | After each placement day | Direct placement experience | NOT STARTED | [`transcripts/de-identified/`](transcripts/de-identified/) or private evidence area | Record grade band, lesson/context, action, learning, and next move without student identifiers |
| P1 | Coordinate MCQ, Collaborative Noticing, Snapshot, Letter, observations, and Resource Guide | Per EDF436 deadlines | [EDF436 master](https://github.com/pzg8794/EDF436/blob/main/MASTER-TODO.md) | OPEN | [`planning/`](planning/) | Link artifacts back to the owning EDF436 row; keep signatures, media, and evaluations private |

## Source and evidence map

| Area | Purpose | Boundary |
|---|---|---|
| [Placement source summary](communications/PLACEMENT-SOURCE-SUMMARY.md) | Exact Gmail message/thread locators plus privacy-safe evidence states | Do not copy raw messages, contact details, signatures, or attachments into Git |
| [`communications/`](communications/) | Public-safe action summaries and indexes to authoritative private messages | Do not publish names/contact details or raw message exports |
| [`planning/`](planning/) | Schedule, lesson-preparation, observation, and coordination records | Link to course requirements instead of copying canonical source files |
| `transcripts/private/` | Raw PLAUD exports and identifiable placement transcripts | Local/private and excluded from Git |
| [`transcripts/de-identified/`](transcripts/de-identified/) | Privacy-reviewed reflections and evidence notes | Commit only after checking that no student/school-sensitive data remains |
| [EDF436 master](https://github.com/pzg8794/EDF436/blob/main/MASTER-TODO.md) | Course deadlines, preparation status, submission state, receipts | Authoritative for course work |
| [EDF435B source mirror](https://github.com/pzg8794/EDF435B/blob/main/MASTER-TODO.md) | Cross-listed seminar syllabus and announcements | Source mirror only; no duplicate completion state |

## Evidence log

| Date | Placement event | Artifact prepared | Participation verified | Private receipt/evidence | Next action |
|---|---|---|---|---|---|
| Sep 8 | First placement day | NO | NO — future at last check | None recorded | Attend; then add a de-identified reflection and update schedule facts |

## Update protocol

After each SBTE/school message or placement day, update the exact schedule/source,
action state, evidence location, and next step here. Then update EDF436 only for
course obligations affected by that evidence. Never treat a calendar hold as
attendance, an arranged call as a completed call, or a draft as submission.
