---
id: argue-w-artifact-claims
title: Integration claims name their observation
summary: Whether a run's work is "on main" is read from the run's integration record and the published branch, not from a local checkout, and a claim says which observation and time it rests on; several agents repeating one claim are one source. Two cases, each seen once.
categories: [verification, process]
tags: [integration, claims, observation, conductor, facilitation]
status: observed-repeatedly
references:
  - {role: evidence, ref: "ponderer@042714c:episodes/argue-p4.md", note: "second case: conductor #240 said a report was on branch for jevlab/experiment/run-003 that --integration showed integrated one second earlier"}
  - {role: evidence, ref: "ponderer@a1fdab5:knowledge/artifact-claims.md", note: "first statement, from the argue p3 ex1 case where three owners said not on main of runs the executor had integrated"}
  - {role: context, ref: "jevlab/experiment/run-003", note: "the run of the second case"}
  - {role: unchecked, ref: "argue p3 ex1 report4 (an internal report, not published)", note: "the first-case report named in the body; not read again for this header"}
---
# Integration claims name their observation

**Finding.** Whether a run's work is "on main" is read from the run's
`run.integrate` record and the published branch (`wfe projects run <p>
<wf>/<run> --integration`), not from a local checkout; a claim says which
observation and time it rests on. Several agents repeating one claim are
one source.

**Sources.** argue p3 ex1 report4: three owners said "not on main" of
two runs of other projects that the executor had integrated; the
coordinator workspaces had not followed `origin/main`. No reviewer caught it.

**Second trial (argue p4, `ponderer@042714c:episodes/argue-p4.md`).** The
conductor's #240 said a report was "on branch" for `jevlab/experiment/run-003`
that `--integration` showed integrated one second earlier (observed
2026-10-21T05:14Z). Same pattern from the conductor side; one run each.

**Status.** Adopted with argue p4 (the integration read); a second case seen.

## Revisions

- r1 (argue p4): first statement.
- r1 moved (argue p4 ex1 step 2): moved unchanged from `ponderer@a1fdab5:knowledge/artifact-claims.md` to wedo-argue.
- r2 (ponderer evaluate/run-001, 2026-10-21): added the p4 case; statement unchanged. Superseded commit: wedo-argue 56cd52a.
- r3 (freework/run-003, 2026-11-04): added the knowledge header (id,
  categories, references); text unchanged. The id `argue-w-artifact-claims`
  is new.
