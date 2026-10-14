# Publish under each repository's own identity

## Goal

Keep the private project copies separate in Git authorship, documentation and authenticated publishing while delivering equivalent application source.

## Context Pointers

The13October user decision supersedes the earlier dual-push and identical-head policy. See [identity specification](../specs/capstone/increments/repository-identities.md). Dated records describe the historical workflow; they are not permission to reconnect the histories.

## Constraints

1. Inspect the checkout's origin URL and configured author email before committing. Authenticate the publishing process as that repository's owner; check `gh api user` under the intended child-scoped profile. Do not change global credentials or Git identity.
2. Use a separate checkout and owner identity for each repository. The main development checkout's origin has one push destination. Its school readback remote is deliberately blocked for pushing.
3. The ignored `.local/repository-identities/prepare-school.mjs` prepares the school projection on this PC. It maps both authorship fields and evidence revisions, removes other-account references and preserves application files. Its private receipt maps the two histories. It never pushes. Review its output and the school checkout before delivery.
   From the unpublished 14 October reconciliation increment onward, it also applies the ignored `.local/status-reconciliation/school-documentation.mjs` adapter. The school current tree presents one standalone product repository and omits these multi-account operator records. The already published school prefix is preserved; verify it remains an ancestor. This local operator policy belongs in the personal workspace, not the school-facing documentation.
   The completed reconciliation included a reviewed incremental context-only child. Do not replay the entire migration to prepare later increments: it may compute a different already-published prefix. The14October Docker delivery uses ignored `.local/docker-checks/project-school.mjs` to extend the current receipt by one normal source child, applying the scoped documentation adapter only to changed paths. It requires a clean expected school parent, preserves its published ancestry and validates owner metadata, current text and protected application/config bytes before updating the prepared ref. Inspect the receipt, intended changes and ancestor/readback checks before normal publishing; no force-push is authorized.
4. For subsequent updates, compare the prepared school main with its remote main. Require remote main to be an ancestor; use a normal explicit main-only push from the school checkout with school authentication. Stop on divergence. Never use mirror/all-ref pushes or import the original history into the school repository.
5. Verify each destination against its own expected commit. Their heads are intentionally different. Compare protected source/tests/dependencies and artwork/capture bytes to establish content equivalence.
6. Preserve unrelated hooks, ignored secrets, learner data and local recovery material. Backups and private revision maps stay on this PC. Global CodexRecovery remains outside project publication.

An independent clone of either repository can develop normally using its own owner identity. The local projection helper is an operator migration tool, not a prerequisite for running LittleFurther.

## Done When

Each published main resolves to its independently expected SHA and owner identity; school historical content and contributors contain no other-account identity; application source remains equivalent. Record actual saved tracker and remote results without claiming identical hashes or new application tests.

## Local-only recording material

On 14 October the user requested that video scripts, storyboards and video-rehearsal documents/assets stay on this PC and outside the repositories. Existing local copies are ignored; keep future recording preparation in ignored local storage. Publish application source, regression tests and ordinary product/developer documentation through the established procedure. Do not re-add or rename the excluded packet into another published folder.

The cleanup removes the packet from current repository files with normal commits. Published ancestry is preserved; earlier commits retain historical copies. Current-tree removal is not a history purge. Source behavior and learner data remain unchanged. Scoped documentation/link checks, local-copy hashes, unchanged source bytes, independent review, owner-authenticated remote readback and saved tracker comparisons are the applicable checks; no new full application-suite result follows from this documentation change.

Verification on 14 October: all 34 excluded paths were absent from the published current tree, local copies and 86 archived owner snapshots passed hash checks, all 64 protected source/test/config files were unchanged, and independent review found no blocker. Scoped documentation checks passed for the affected records; three unrelated pre-existing local-document links remain outside this cleanup. E035 saved readbacks preserve complete Sheet/Kaneo histories and metadata. Authenticated normal publication retains existing ancestry; these checks do not purge old commits or establish a new application-suite pass.
