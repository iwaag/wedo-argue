# wedo-argue

Reusable knowledge about designing, conducting and evaluating discussions in which a person and AI
agents with different missions and contexts work out a desire together. It is one of the two
knowledge repositories of [ponderer](https://github.com/iwaag/pj-ponderer) (the other is
[study-argue](https://github.com/iwaag/study-argue)); ponderer's agent reads it at the commit its
`wedo/wedo-argue` submodule pins, and adopting a newer revision is moving that pin. Released under
CC0-1.0.

## Layout

| Path | Holds |
| --- | --- |
| `index.md` | one line per finding, with its status |
| `findings/<name>.md` | one finding: statement, where it applies, the local trials it rests on, external evidence (from study-argue), contrary observations, status, open questions and *Revisions* |
| `knowledge.yaml` | who maintains this repository (agdev knowledge header) |

## What a finding is here

- Promoted deliberately from evaluations of named discussions and from sourced research. One trial
  is an observation, not a cause; each finding says what it rests on.
- Local observations and external evidence are kept apart, and contrary observations stay beside the
  finding they contradict.
- A revision keeps the earlier statement's rationale and commit under *Revisions*; a finding that no
  longer holds is marked superseded, not deleted.
- What a discussion found about its own subject belongs to the project that owns that subject.

## Findings today

Three, each resting on one or two trials of one development installation (not independently
reproduced); their status lines say how far they have been checked:

- [asking-the-requester](findings/asking-the-requester.md): a question to the requester is the run's
  own question, so the answer returns to the run that waits for it.
- [owed-work](findings/owed-work.md): an agreed follow-up is carried as planned work until done or
  dropped; working practice, with a local failure case and only indirect external evidence.
- [artifact-claims](findings/artifact-claims.md): an integration claim names the observation it rests
  on.

## What you cannot follow from here

The findings cite the trials they rest on by internal commit (`ponderer@<commit>:episodes/…`,
`ponderer@<commit>:knowledge/…`), run ids ("argue p3 ex1", "p4") and the development installation's
devdocs reports. Those records (ponderer's discussion archives and episode analyses, run records) are
not published, so those references cannot be opened from here. They show where a statement came
from; read each finding's own text for what was observed, how often and what is still open.
Likewise `study-argue@<commit>` names an internal commit; the public study-argue starts from one
root commit, so read its topic file directly.
