# Decision and verification worklog

## November 12, 2026 — peer issue #1
- Observation: supplied availability wording conflicted with the independent-verification disclaimer.
- Decision: implement clearer provenance and investigate employer sources. The user authorized repository changes; AI proposed and implemented the correction. Student accuracy review remains pending.
- Changes: public source ledger, dated status per role, professional-goal summary, private-reflection boundary, review workflow and submission checklist.
- Verification: Amazon employer text retrieved with title/job ID and Apply now; Palantir returned HTTP 403, which does not prove closure. Static checks recorded in the implementation commit.
- Resolution: open. Next: reviewer retries the wording/source trace and student checks Palantir manually. Link implementation commit in issue #1. Do not close before reviewer confirmation.

## Privacy limit
Current files remove personal eligibility assessments and full reflective prose. Earlier public Git commits still contain old versions. This revision does not erase Git history or copies. No history rewrite was performed.

## Browser verification
Initial site layout, checklist counter and role disclosure were browser-checked during creation. Revised production browser checks must be recorded separately after publication; no new user-test result is claimed here.

## Published verification — November 12, 2026
- Pages build [43240472324](https://github.com/aka223-ui/career-fieldnotes-is117/actions/runs/43240472324) succeeded for d929f9d.
- Browser opened https://aka223-ui.github.io/career-fieldnotes-is117/ and followed its research link to /docs/ successfully.
- Checked one checklist control: counter changed from 0/6 to 1/6, stayed checked after reload, and returned to 0/6 after unchecking.
- Opened Palantir disclosure and observed the blocked/unverified status. Documentation showed the source ledger and finding/decision/check tables.
- Static checks passed for HTML titles, internal fragment links, six checklist controls and removal of personal eligibility assertions. No new mobile viewport or human usability test is claimed.
- Student accuracy review, manual Palantir source check, reviewer retry and Canvas submission remain pending.
