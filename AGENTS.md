# Project update rules

- Show the current version as MAJOR.MINOR in the small centered home-only footer in 1_응급처치수업/수업자료/응급처치게임.html (#site-version). Initial release: 1.0.
- For every subsequent user-requested site update, bump the version once for the completed update, not for each file edit, test, retry, or commit. Text fixes, answer revisions, styling, and small features increment MINOR (1.0 -> 1.1). Large changes to the game structure, main workflow, or substantial feature redesign increment MAJOR and reset MINOR (1.9 -> 2.0). Treat the two parts as integers (1.9 -> 1.10 for another minor release).
- Keep the visible version and its aria-label synchronized. Do not bump for read-only questions or documentation-only changes.
- Keep 정답지.txt synchronized whenever questions, equipment requirements, correct answers, or explanations change.
- Do not create or retain ZIP archives unless the user explicitly asks for one. The site deploys directly from its HTML and assets.
- The user has authorized committing updates to main and pushing to origin for the existing GitHub Pages site. Preserve unrelated work and remote history.

- Repository: https://github.com/morningbreadteacher/health_class.git (origin). Keep the original mia remote as previous-origin for reference; do not push updates there unless asked.
- Organize lessons in their own folders. In 1_응급처치수업/, keep only README.md, one 응급처치수업.url shortcut, and the 수업자료/ directory. Store the HTML, assets, answer sheet, and image notes inside 수업자료/.
- Keep the root free of HTML, shortcuts, archives, and other lesson artifacts. Only Git metadata, Markdown documents, and lesson folders belong at the root. The root README.md describes the entire repository; each lesson folder has its own README.md.
- Do not create a lesson-directory HTML page. Use the root README.md for the lesson listing. Keep the lesson README.md version synchronized with its game.

- For all future commits in this repository, use author and committer morningbreadteacher with 353308911+morningbreadteacher@users.noreply.github.com. Do not rewrite historical commits.
- Keep Windows Internet shortcuts (.url) synchronized with published lesson URLs.
