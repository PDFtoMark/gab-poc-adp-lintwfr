# PoC: workflow_run artifact poisoning -> npm lifecycle RCE

Reproduces AdobeDocs devsite `post-lint-comment.yml` (triggered by `workflow_run` of "Lint")
downloading an attacker-controlled artifact and running `npm install` in the workspace.

<!-- retry 1 -->
