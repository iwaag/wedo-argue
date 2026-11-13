---
id: argue-w-owed-work
title: Agreed follow-ups are carried as planned work
summary: A review, summary or hand-off the discussion agreed to is kept as a node of the conductor's graph until done or explicitly dropped, and a closing account is checked against the recorded obligations. One local trial showed the failure; the practice itself is untested.
categories: [process, verification]
tags: [discussion, conductor, obligations, closing-account, facilitation]
status: working-practice
references:
  - {role: evidence, ref: "ponderer@042714c:episodes/argue-p4.md", note: "re-evaluation of the p4 trial: no review node, closing account said none owed while the snapshot listed 2 items; one run, cause not established"}
  - {role: evidence, ref: "ponderer@a1fdab5:knowledge/owed-work.md", note: "the first statement, written in argue p3 ex1 from the omitted review and summary"}
  - {role: context, ref: "study-argue@d6c7eff:topics/followup-drop-and-account-fidelity.md", note: "abstract-level external evidence on benchmark agents, not facilitators; none on dropped follow-ups in discussions"}
  - {role: unchecked, ref: "devdocs episodes/argue/p3/ex1/report.md (Assistance)", note: "the p3 ex1 report named in the body; kept in the agdevworld devdocs, not read again for this header"}
---
# Agreed follow-ups are carried as planned work

**Finding.** A review the protocol calls for, a summary the requester asked
for, or a hand-off is an obligation of the discussion. Planned as nodes of
the conductor's graph, it stays visible until it is done or explicitly
dropped.

**Sources.** argue p3 ex1: the facilitator asked the Developer to choose
between stopping and a follow-up at #191 instead of starting the agreed
review (hint 1, #192), and no summary or disposition was produced until
hint 2 (#199) (devdocs `episodes/argue/p3/ex1/report.md`, *Assistance*).
argue p3: no `synthesize` run was requested, so no summary exists
(`episodes/argue/p3/report.md`).

**Local trial (argue p4, `ponderer@042714c:episodes/argue-p4.md`, re-evaluation).**
Contrary to the practice, the conductor planned "then review the result" in
decision prose only: its graph never had a review node, and it concluded
(decision 34) after asking only whether the task's goal was met. No review or
summary happened; the closing account said "still owed: none" while the
obligations snapshot attached to the closing announce listed 2 items (a
participant's held run and its delegation, closed by recovery 80 s later).
Contrary reading kept: "none" may be true of subject-level work. One run, no
repetition; the cause (guide wording, prose-only plan, chance) is not
established.

**What to notice (for the conductor).** An agreed item lives as a node or an
explicit drop, not as a sentence in a decision. Before concluding, ask what
the discussion itself still owes (planned reviews, requested summaries, the
obligations snapshot), not only whether the task's goal is met; a closing
account is checked against that record, not against the conductor's memory.

**External evidence (`study-argue@d6c7eff:topics/followup-drop-and-account-fidelity.md`,
abstract-level, benchmark agents, not facilitators).** Self-declared
completion is unreliable across studies (MAST premature/no/incorrect
verification ≈23% of traces; false-success and overclaiming studies);
verification helps but is not sufficient; task state kept outside the agent
and checked against recorded facts is the mitigation named most directly,
from one preprint and one engineering report. No study of dropped follow-ups
in LLM facilitators or discussions was found; whether gating closure on an
obligations list helps is open.

**Status.** Working practice, supported by one local trial that shows the
failure it addresses (not a measured effect of the practice) and indirect
external evidence. Still open: whether a graph node would have prevented the
p4 omission.

## Revisions

- r1 (argue p4): first statement.
- r1 moved (argue p4 ex1 step 2): moved unchanged from `ponderer@a1fdab5:knowledge/owed-work.md` to wedo-argue.
- r2 (ponderer evaluate/run-001, 2026-10-21): status changed from "to be
  checked against the p4 trial" to the above; added the p4 trial as a case of
  the failure, the closing-account check, and study-argue@d6c7eff. Statement
  unchanged. Superseded commit: wedo-argue 56cd52a.
- r3 (freework/run-003, 2026-11-04): added the knowledge header (id,
  categories, references); text unchanged. The id `argue-w-owed-work` is
  new and stays with the finding if its file or title changes.
