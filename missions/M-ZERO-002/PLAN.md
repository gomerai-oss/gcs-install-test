# M-ZERO-002: Prove an agent can delete a file

## Goal

Show that A2 can delete a file, not only create or edit one.

## Build (A2)

Delete `docs/PIPELINE-PROOF.md`. Do not empty it: the file must no longer exist. Change nothing else.

## Review (A3)

PASS only if the build deleted `docs/PIPELINE-PROOF.md` (the file is gone, not left empty) and changed nothing else.
The plan's check `test ! -e docs/PIPELINE-PROOF.md` must pass. Otherwise FAIL, naming what is wrong.
