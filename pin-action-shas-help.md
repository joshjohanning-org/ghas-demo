- GitHub Action to update version references to use SHAs: https://github.com/saadmk11/github-actions-version-updater
- JavaScript app to pin tags to SHAs: https://github.com/mheap/pin-github-action
- GitHub Actions to "lint" / enforce using commit shas instead of tags:
https://github.com/marketplace/actions/ensure-sha-pinned-actions, https://github.com/marketplace/actions/action-ref-linter
- Another GitHub Action to verify SHAs: https://github.com/zgosalvez/github-actions-ensure-sha-pinned-actions
- You can use the extended (`security-extended`) CodeQL query suite for Actions to find unpinned actions (ref): https://docs.github.com/en/code-security/code-scanning/managing-your-code-scanning-configuration/github-actions-built-in-queries#built-in-queries-for-workflow-analysis
- GitHub Actions allow list as code: https://josh-ops.com/posts/github-actions-allow-list-as-code/
- New feature to require this: https://github.blog/changelog/2025-08-15-github-actions-policy-now-supports-blocking-and-sha-pinning-actions/
