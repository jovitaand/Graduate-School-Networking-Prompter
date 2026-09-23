# Approved Send Queue

Emails Jovita has explicitly approved (YES) that have **not been sent yet**. Nothing here has gone out.

**Why they're queued:** the Gmail connector in the original session only had read access (every draft/send attempt returned `Insufficient scope`). Connectors are loaded when a session starts, so Gmail must be reconnected at https://claude.ai/customize/connectors with compose/send/drafts permission and a **new session** started before these can be sent.

## Rules for whoever sends these
- Send the **exact approved text** from the linked candidate file. Only email-system formatting may change.
- Attach `Resume_Jovita_PhD_2026.pdf` (Jovita's uploaded CV; not stored in this repo). Verify it opens.
- Send at **8:00 AM in the professor's local time** on the scheduled date.
- If a scheduled time has already passed, **do not pick a new time yourself**. Ask Jovita for a new send date first.
- After each send, add a row to `LOG.md` (Status `Pending`), move the entry below to "Sent", and commit.

## Queue

| # | Professor | To | Subject | Scheduled (local) | Abu Dhabi | Approved | Source |
|---|---|---|---|---|---|---|---|
| 1 | Neda Jahanshad (USC) | njahansh@usc.edu | Prospective Fall 2027 PhD Applicant – Computational Neuroscience | ~~Thu 2026-09-17, 8:00 AM PT~~ **passed; needs new date** | — | 2026-09-16 | `candidates/batch-1-2026-09-15.md` #1 |
| 2 | Christine Metz (Feinstein/Northwell) | cmetz@northwell.edu | Prospective Fall 2027 PhD Applicant – Endometriosis/PCOS Multi-Omics Research | ~~Mon 2026-09-21, 8:00 AM ET~~ **passed; needs new date** | — | 2026-09-21 | `candidates/batch-1-2026-09-15.md` #5 |
| 3 | Sheila Shanmugan (Penn) | sheila.shanmugan@pennmedicine.upenn.edu | Prospective Fall 2027 PhD Applicant – Computational Neuroscience | Wed 2026-09-30, 8:00 AM ET | 4:00 PM | 2026-09-23 | `candidates/batch-4-penn-ngg-2026-09-23.md` #1 |
| 4 | Gregory Corder (Penn) | gcorder@upenn.edu | Prospective Fall 2027 PhD Applicant – Computational Neuroscience | Thu 2026-10-01, 8:00 AM ET | 4:00 PM | 2026-09-23 | `candidates/batch-4-penn-ngg-2026-09-23.md` #2 |
| 5 | Seema Bhatnagar (Penn/CHOP) | bhatnagars@chop.edu | Prospective Fall 2027 PhD Applicant – Computational Neuroscience | Fri 2026-10-02, 8:00 AM ET | 4:00 PM | 2026-09-23 | `candidates/batch-4-penn-ngg-2026-09-23.md` #3 |
| 6 | Bart De Jonghe (Penn) | bartd@nursing.upenn.edu | Prospective Fall 2027 PhD Applicant – Computational Neuroscience | Mon 2026-10-05, 8:00 AM ET | 4:00 PM | 2026-09-23 | `candidates/batch-4-penn-ngg-2026-09-23.md` #4 |

Notes:
- Bhatnagar: CHOP's page lists bhatnagars@chop.edu; her Penn BGS page lists bhatnagars@email.chop.edu (likely the same inbox).
- The Penn subject line was not part of the approval packets (packets covered body text only). Confirm with Jovita if she wants a different subject.

## Awaiting Jovita's decision (packets sent, no YES yet)
- Batch 1: Jacobs (UCSB), Casaletto (UCSF), Kommagani (Baylor), with packets proposed for 2026-09-21 (passed).
- Batch 2: Tronson (Michigan), with packet proposed for 2026-09-22 (passed).
- Batch 3: all 16 packets, proposed for 2026-09-24 to 2026-09-29.

## Sent
_None yet._
