# Repository identity after the rename

The previous implementation remains maintained. The rename does not archive
this repository, transfer its open work, or combine it with the current compiler.

| Project | GitHub repository ID | Previous name | Canonical name |
| --- | --- | --- | --- |
| This repository | `1071732997` | `buster14a/buster` | `buster14a/buster-legacy` |
| Current compiler | `1421805693` | `buster14a/buster-fast` | `buster14a/buster` |

The coordinated work is tracked in
[current compiler #164](https://github.com/buster14a/buster-fast/issues/164),
[#165](https://github.com/buster14a/buster-fast/issues/165), and
[#166](https://github.com/buster14a/buster-fast/issues/166).
Those records contain the actual migration status, revisions and validation.
This document describes the intended final identities; its presence on a
preparation branch is not evidence that a rename or deployment has happened.

## Live destinations and preserved records

Use `buster14a/buster-legacy` for this repository's Git remotes, explicit push
URLs, GitHub API destinations, hosted Actions and maintained historical links.
Verify the numeric repository ID before changing an unattended writer.
Once the current compiler takes `buster`, an old `buster` URL selects that
compiler, even if its issue or pull-request number also exists here.
Externally published old links cannot all be repaired.

Continuing workflows retain their job and check names, action revisions,
permissions, runner labels, trigger conditions and shared host lock. Repository
conditions use the stable ID. The trusted integration writer obtains its
unchanged pinned machine reporter from its own current repository identity;
other hosted reporter calls use the canonical legacy path.

Live benchmark admissions, controller clones, publication checks, physical
clock guards and the current routing policies use the legacy name. Existing
disabled routing stays disabled; the rename does not issue a new benchmark
request, reopen an experiment, change its frozen plan or grant an extra retry.

Raw audits, original API envelopes, historical declarations, native dependency
receipts, frozen plans and archived experiment bytes retain their original
repository spelling and hashes. The read-only historical sampling/prerequisite
and campaign readers continue to interpret that original namespace as data.
Their results never grant execution authority. When collecting additional
original records, select the legacy API destination explicitly; do not send
requests to the historical spelling after it has been reassigned.
The fixed #2610 population and qualification formats likewise retain their
original captured identities. Its dispatch collector uses the legacy endpoint,
and its reader accepts either recorded endpoint without rewriting the capture.

Main-CI benchmark receipt reuse admits the old spelling only after the run and
request prove repository ID `1071732997` and all existing revision, actor,
attempt and workflow checks. Comparison of the old navigation spelling occurs
on a copy of the receipt. Repository ID `1421805693` cannot inherit those receipts.

Local directory names, the runner installation, benchmark workspaces and lock
paths are independent of the GitHub repository name. Preserve them during the
handover. The current compiler's `buster-fast-bench` and memory directories
continue to belong to the current compiler.

## Activation order

1. Land and validate the current compiler's stable-ID guard and this
   repository's rename-safe trusted integration writer.
2. Prepare the legacy source changes and separate automation-policy change.
   Pause repository-writing agents and automation, retaining their previous
   enabled or paused state.
3. Rename repository ID `1071732997` to `buster-legacy`. Apply the source
   changes through the protected bootstrap process now that the hosted Action
   path exists. The automation-policy repository string is a separate policy
   transition; preserve its existing grant, allowed classes and paused PRs.
4. Verify or retarget known remotes, scheduled clients, app selections and
   runner-group workflow restrictions. Keep unresolved writers paused.
   Read back rulesets and environments, and validate continuing CI and
   [Pages](github-pages.md) at the legacy path.
5. Only after legacy readiness is recorded, give repository ID `1421805693`
   the `buster` name, apply its staged references and verify actual 9700X
   execution. Resume only the writers whose destinations have been verified.

Repository settings and organization runner-group settings require separate
access checks. An unavailable organization-settings API is not evidence that
selected-workflow restrictions or installed-app configuration are correct.
OIDC trust, if consumed by an external integration, must be checked against the
actual post-rename claims. Preserve existing Pages domain and HTTPS settings;
verify a new deployment rather than treating an old deployment as proof.
