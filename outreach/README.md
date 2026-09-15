# Outreach Tracking

This folder is the system of record for PhD professor outreach (Fall 2027 applications).

- **[`LOG.md`](./LOG.md)** — master table of every professor contacted, sorted by date sent. Tracks research fit, funding confidence, and response status (`Pending` / `Yes` / `No` / `Ghosted`) with notes on what each professor actually said.
- **`drafts/`** — one file per approved, professor-specific email (created once outreach research begins), named `YYYY-MM-DD-lastname-university.md`. Kept for reference and duplicate-prevention (never re-contact the same professor/lab/department about the same opportunity).

## Workflow

1. Professor is researched (position, funding evidence, publications) and an email is drafted.
2. Draft is presented for proofreading and requires explicit approval before scheduling.
3. Once sent, a row is added to `LOG.md` with `Status = Pending`.
4. As responses come in, `Status` and `Response Notes` are updated in place.
