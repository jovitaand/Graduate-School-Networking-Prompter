# Approved Send Queue

Emails Jovita has explicitly approved (YES) that have **not been sent yet**. Nothing here has gone out.

**History:** Gmail originally had read-only access (every draft attempt returned `Insufficient scope`). After Jovita reconnected it, draft creation started working on 2026-09-23.

## Rules for whoever sends these
- Send the **exact approved text** from the linked candidate file. Only email-system formatting may change.
- Attach `Resume_Jovita_PhD_2026.pdf` (Jovita's uploaded CV; not stored in this repo). Verify it opens.
- Send at **8:00 AM in the professor's local time** on the scheduled date.
- If a scheduled time has already passed, **do not pick a new time yourself**. Ask Jovita for a new send date first.
- After each send, add a row to `LOG.md` (Status `Pending`), move the entry below to "Sent", and commit.

## Gmail drafts

Drafts now exist in Jovita's Gmail (jovitaandrewsw@gmail.com) for every queued email. None has been sent.

- **Formatting (2026-09-23):** each draft now has an HTML version with bold section labels (Current research, Technical background, Research interest, Why your work, PhD goal). The approved wording is unchanged.
- **CV: not attached. Jovita must attach it manually.** The connector requires the PDF to be pasted in as base64 text. A test attachment on the Shanmugan draft came out corrupted, so it was removed. Before sending, drag `Resume_Jovita_PhD_2026.pdf` into each draft and check that it opens.

| Professor | Gmail draft ID |
|---|---|
| Jahanshad | r-6773154793358235377 |
| Shanmugan | r9037505943546523891 |
| Corder | r-6335545302230780453 |
| Bhatnagar | r2272896813349266764 |
| De Jonghe | r-7152000380859652891 |
| Taylor | r3356746445218718000 |
| Farland | r188973349992987672 |
| Kahn | r6677620909064397543 |
| Herting | r-2656741137213644653 |
| Tollkuhn | r5381755111858171478 |
| Petersen | r2632759733767841163 |
| Church | r6313646368871436664 |
| Correa | r9186801278038097167 |
| Mielke | r5422263701100224349 |
| Kantarci | r-8284970108665163383 |

**Batch 5 drafts (created 2026-09-27):** these use keyword highlighting. Besides the bold section labels, key phrases are bolded: degree, role, lab, skills, research interest, the cited finding, funding goal, and "accepting PhD students for Fall 2027". The wording is identical to the packets.

**Reminders:** a one-time reminder fires at 10:00 AM Abu Dhabi the day before each dated send (Penn and Batch 5). Jahanshad has none because she has no date yet. Emails are **not** auto-sent, because the CV cannot be attached through the connector. Jovita attaches the CV and uses Gmail "Schedule send" for the listed time.

## Queue

| # | Professor | To | Subject | Scheduled (local) | Abu Dhabi | Approved | Source |
|---|---|---|---|---|---|---|---|
| 1 | Neda Jahanshad (USC) | njahansh@usc.edu | Prospective Fall 2027 PhD Applicant – Computational Neuroscience | ~~Thu 2026-09-17, 8:00 AM PT~~ **passed; needs new date** | — | 2026-09-16 | `candidates/batch-1-2026-09-15.md` #1 |
| 3 | Sheila Shanmugan (Penn) | sheila.shanmugan@pennmedicine.upenn.edu | Prospective Fall 2027 PhD Applicant – Computational Neuroscience | Wed 2026-09-30, 8:00 AM ET | 4:00 PM | 2026-09-23 | `candidates/batch-4-penn-ngg-2026-09-23.md` #1 |
| 4 | Gregory Corder (Penn) | gcorder@upenn.edu | Prospective Fall 2027 PhD Applicant – Computational Neuroscience | Thu 2026-10-01, 8:00 AM ET | 4:00 PM | 2026-09-23 | `candidates/batch-4-penn-ngg-2026-09-23.md` #2 |
| 5 | Seema Bhatnagar (Penn/CHOP) | bhatnagars@chop.edu | Prospective Fall 2027 PhD Applicant – Computational Neuroscience | Fri 2026-10-02, 8:00 AM ET | 4:00 PM | 2026-09-23 | `candidates/batch-4-penn-ngg-2026-09-23.md` #3 |
| 6 | Bart De Jonghe (Penn) | bartd@nursing.upenn.edu | Prospective Fall 2027 PhD Applicant – Computational Neuroscience | Mon 2026-10-05, 8:00 AM ET | 4:00 PM | 2026-09-23 | `candidates/batch-4-penn-ngg-2026-09-23.md` #4 |
| 7 | Hugh Taylor (Yale) | hugh.taylor@yale.edu | Prospective Fall 2027 PhD Applicant – Computational Neuroscience | Tue 2026-10-06, 8:00 AM EDT | 4:00 PM | 2026-09-27 | `candidates/batch-5-us-sweep-2026-09-27.md` #1 |
| 8 | Leslie Farland (Arizona) | lfarland@arizona.edu | Prospective Fall 2027 PhD Applicant – Computational Neuroscience | Wed 2026-10-07, 8:00 AM MST | 7:00 PM | 2026-09-27 | `candidates/batch-5-us-sweep-2026-09-27.md` #2 |
| 9 | Linda Kahn (NYU) | Linda.Kahn@nyulangone.org | Prospective Fall 2027 PhD Applicant – Computational Neuroscience | Thu 2026-10-08, 8:00 AM EDT | 4:00 PM | 2026-09-27 | `candidates/batch-5-us-sweep-2026-09-27.md` #3 |
| 10 | Megan Herting (USC) | herting@usc.edu | Prospective Fall 2027 PhD Applicant – Computational Neuroscience | Fri 2026-10-09, 8:00 AM PDT | 7:00 PM | 2026-09-27 | `candidates/batch-5-us-sweep-2026-09-27.md` #4 |
| 11 | Jessica Tollkuhn (CSHL) | tollkuhn@cshl.edu | Prospective Fall 2027 PhD Applicant – Computational Neuroscience | Mon 2026-10-12, 8:00 AM EDT | 4:00 PM | 2026-09-27 | `candidates/batch-5-us-sweep-2026-09-27.md` #5 |
| 12 | Nicole Petersen (UCLA) | npetersen@ucla.edu | Prospective Fall 2027 PhD Applicant – Computational Neuroscience | Tue 2026-10-13, 8:00 AM PDT | 7:00 PM | 2026-09-27 | `candidates/batch-5-us-sweep-2026-09-27.md` #6 |
| 13 | Arpana Church (UCLA) | agupta@mednet.ucla.edu | Prospective Fall 2027 PhD Applicant – Computational Neuroscience | Wed 2026-10-14, 8:00 AM PDT | 7:00 PM | 2026-09-27 | `candidates/batch-5-us-sweep-2026-09-27.md` #7 |
| 14 | Stephanie Correa (UCLA) | stephaniecorrea@ucla.edu | Prospective Fall 2027 PhD Applicant – Computational Neuroscience | Thu 2026-10-15, 8:00 AM PDT | 7:00 PM | 2026-09-27 | `candidates/batch-5-us-sweep-2026-09-27.md` #8 |
| 15 | Michelle Mielke (Wake Forest) | Michelle.Mielke@wfusm.edu | Prospective Fall 2027 PhD Applicant – Computational Neuroscience | Fri 2026-10-16, 8:00 AM EDT | 4:00 PM | 2026-09-27 | `candidates/batch-5-us-sweep-2026-09-27.md` #9 |
| 16 | Kejal Kantarci (Mayo) | kantarci.kejal@mayo.edu | Prospective Fall 2027 PhD Applicant – Computational Neuroscience | Mon 2026-10-19, 8:00 AM CDT | 5:00 PM | 2026-09-27 | `candidates/batch-5-us-sweep-2026-09-27.md` #10 |

Notes:
- Batch 5 approval: Jovita wrote "schedule all the emails by highlighting the keywords of the email" on 2026-09-27, after receiving all 10 packets.
- Batch 5 addresses to double-check before sending: Church (uses her former surname Gupta) and Mielke (taken from page contact metadata).
- Bhatnagar: CHOP's page lists bhatnagars@chop.edu; her Penn BGS page lists bhatnagars@email.chop.edu (likely the same inbox).
- The Penn subject line was not part of the approval packets (packets covered body text only). Confirm with Jovita if she wants a different subject.

## Awaiting Jovita's decision (packets sent, no YES yet)
- Batch 1: Jacobs (UCSB), Casaletto (UCSF), Kommagani (Baylor), with packets proposed for 2026-09-21 (passed).
- Batch 2: Tronson (Michigan), with packet proposed for 2026-09-22 (passed).
- Batch 3: all 16 packets, proposed for 2026-09-24 to 2026-09-29 (passed; need new dates).

## Sent
- **Christine Metz** (Feinstein/Northwell), cmetz@northwell.edu: sent manually by Jovita on or before 2026-09-23 (exact date not recorded). Logged in `LOG.md`.
