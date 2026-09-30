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


## Monday 2026-09-28 schedule (set by Jovita on 2026-09-27)

Jovita asked on 2026-09-27 for **all** approved emails to go out on **Monday 2026-09-28**, each at **8:00 AM in the professor's local time**, with the CV attached. This replaces the earlier spread-out dates below. Jahanshad now has a date too.

The emails are **not auto-sent**, because the CV cannot be attached through the Gmail connector. For each draft, Jovita attaches `Resume_Jovita_PhD_2026.pdf` and uses Gmail **Schedule send** with the Abu Dhabi time below.

| Professor | Email | Draft ID | 8:00 AM local | Abu Dhabi (Mon) |
|---|---|---|---|---|
| Shanmugan (Penn) | sheila.shanmugan@pennmedicine.upenn.edu | r9037505943546523891 | EDT | 4:00 PM |
| Corder (Penn) | gcorder@upenn.edu | r-6335545302230780453 | EDT | 4:00 PM |
| Bhatnagar (Penn/CHOP) | bhatnagars@chop.edu | r2272896813349266764 | EDT | 4:00 PM |
| De Jonghe (Penn) | bartd@nursing.upenn.edu | r-7152000380859652891 | EDT | 4:00 PM |
| Taylor (Yale) | hugh.taylor@yale.edu | r3356746445218718000 | EDT | 4:00 PM |
| Kahn (NYU) | Linda.Kahn@nyulangone.org | r6677620909064397543 | EDT | 4:00 PM |
| Tollkuhn (CSHL) | tollkuhn@cshl.edu | r5381755111858171478 | EDT | 4:00 PM |
| Mielke (Wake Forest) | Michelle.Mielke@wfusm.edu | r5422263701100224349 | EDT | 4:00 PM |
| Kantarci (Mayo, MN) | kantarci.kejal@mayo.edu | r-8284970108665163383 | CDT | 5:00 PM |
| Farland (Arizona) | lfarland@arizona.edu | r188973349992987672 | MST (no DST) | 7:00 PM |
| Jahanshad (USC) | njahansh@usc.edu | r-6773154793358235377 | PDT | 7:00 PM |
| Herting (USC) | herting@usc.edu | r-2656741137213644653 | PDT | 7:00 PM |
| Petersen (UCLA) | npetersen@ucla.edu | r2632759733767841163 | PDT | 7:00 PM |
| Church (UCLA) | agupta@mednet.ucla.edu | r6313646368871436664 | PDT | 7:00 PM |
| Correa (UCLA) | stephaniecorrea@ucla.edu | r9186801278038097167 | PDT | 7:00 PM |

**Status (2026-09-27):** Jovita confirmed that **Jahanshad, Shanmugan, Corder, Bhatnagar and De Jonghe are scheduled in Gmail with the CV attached** for Monday 2026-09-28 at 8:00 AM local time. That is why Gmail no longer lists them as drafts. They keep their original formatting (bold section labels only). They will be logged in `LOG.md` once Jovita confirms they went out.

Jovita also confirmed on 2026-09-27 that **all 10 Batch 5 emails (Taylor to Kantarci) are scheduled in Gmail for Monday 2026-09-28**. **All 15 approved emails are now scheduled**, and none has been confirmed as sent yet.

Reminder: Mon 8:00 PM Abu Dhabi, to confirm which emails went out so they can be logged. The 10:00 AM reminder was cancelled because everything is already scheduled, and the earlier per-date reminders were cancelled too.

## Queue (original dates, superseded by the Monday schedule above)

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

## Batch 6 (approved and drafted 2026-09-30; not yet scheduled or sent)

Jovita asked to "highlight the important keywords and draft all the emails in gmail" right after receiving all 9 packets, so all 9 are treated as approved. The Gmail drafts use the same keyword bolding as Batch 5. The CV is **not attached** and needs to be added by Jovita.

Proposed send: **Mon 2026-10-05, 8:00 AM local time**. Jovita has not yet confirmed a date.

| Professor | Email | Draft ID | 8:00 AM local | Abu Dhabi (Mon Oct 5) |
|---|---|---|---|---|
| Stevens (Emory) | jennifer.stevens@emory.edu | r7142012254724634176 | EDT | 4:00 PM |
| Goldstein (Harvard/MGH) | jill_goldstein@hms.harvard.edu | r-6358161014067575713 | EDT | 4:00 PM |
| Shansky (Northeastern) | r.shansky@northeastern.edu | r-9111994840096380054 | EDT | 4:00 PM |
| Hellman (UChicago) | kevin.hellman@endeavorhealth.org | r-2058771657136860669 | CDT | 5:00 PM |
| Gore (UT Austin) | andrea.gore@austin.utexas.edu | r8284844805872823769 | CDT | 5:00 PM |
| Barch (WashU) | dbarch@wustl.edu | r7692570867869571479 | CDT | 5:00 PM |
| Ingraham (UCSF) | Holly.Ingraham@ucsf.edu | r5667408105532076626 | PDT | 7:00 PM |
| Shah (Stanford) | nirao@stanford.edu | r6583482288538359202 | PDT | 7:00 PM |
| Yang (UCLA) | xyang123@ucla.edu | r-6364422619493048796 | PDT | 7:00 PM |

Reminders (set 2026-09-30): Sun 2026-10-04 at 10:00 AM Abu Dhabi (all 9 due the next day; attach CV and Schedule send), and Mon 2026-10-05 at 8:00 PM Abu Dhabi (confirm sends so they can be logged).

Check before sending: Hellman's, Ingraham's and Shah's addresses come from a lab site or papers, not a faculty page. Yang would be the 4th UCLA contact, in the same department as Correa; consider holding her.

## Awaiting Jovita's decision (packets sent, no YES yet)
- Batch 1: Jacobs (UCSB), Casaletto (UCSF), Kommagani (Baylor), with packets proposed for 2026-09-21 (passed).
- Batch 2: Tronson (Michigan), with packet proposed for 2026-09-22 (passed).
- Batch 3: all 16 packets, proposed for 2026-09-24 to 2026-09-29 (passed; need new dates).


## Sent
- **Christine Metz** (Feinstein/Northwell), cmetz@northwell.edu: sent manually by Jovita on or before 2026-09-23 (exact date not recorded). Logged in `LOG.md`.
