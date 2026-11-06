# Project update rules

- Show the current version as MAJOR.MINOR in the small centered home-only footer in 1_응급처치수업/index.html (#site-version). Initial release: 1.0.
- For every subsequent user-requested site update, bump the version once for the completed update, not for each file edit, test, retry, or commit. Text fixes, answer revisions, styling, and small features increment MINOR (1.0 -> 1.1). Large changes to the game structure, main workflow, or substantial feature redesign increment MAJOR and reset MINOR (1.9 -> 2.0). Treat the two parts as integers (1.9 -> 1.10 for another minor release).
- Keep the visible version and its aria-label synchronized. Do not bump for read-only questions or documentation-only changes.
- Keep 정답지.txt synchronized whenever questions, equipment requirements, correct answers, or explanations change.
- Refresh 1_응급처치수업/보건게임-사진포함.zip after game updates, including that lesson's index.html and assets/ at the archive root.
- The user has authorized committing updates to main and pushing to origin for the existing GitHub Pages site. Preserve unrelated work and remote history.

- Repository: https://github.com/morningbreadteacher/health_class.git (origin). Keep the original mia remote as previous-origin for reference; do not push updates there unless asked.
- Organize lessons in their own folders. The emergency first aid lesson is in 1_응급처치수업/. Its 정답지.txt and assets/ live alongside its index.html.
- Keep the root free of HTML, shortcuts, archives, and other lesson artifacts. Only Git metadata, Markdown documents, and lesson folders belong at the root. The root README.md describes the entire repository; each lesson folder has its own README.md.
- The former root lesson directory is preserved as 1_응급처치수업/수업목록.html. Keep its links relative to that folder. Synchronize lesson version references in its README.md and preserved directory page when updating the lesson.

- For all future commits in this repository, use author and committer morningbreadteacher with 353308911+morningbreadteacher@users.noreply.github.com. Do not rewrite historical commits.
- Keep Windows Internet shortcuts (.url) synchronized with published lesson URLs.
