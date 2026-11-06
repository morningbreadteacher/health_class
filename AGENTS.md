# Project update rules

## Repository and commits

- Repository: https://github.com/morningbreadteacher/health_class.git (origin). Branch: main.
- Keep the original mia remote as previous-origin for reference. Do not push there unless asked. Preserve existing commit history and unrelated work.
- The user has authorized committing completed updates to main and pushing to origin for this GitHub Pages site.
- Use author and committer morningbreadteacher with 353308911+morningbreadteacher@users.noreply.github.com for future commits. Do not rewrite historical authors.

## Files and documentation

- AGENTS.md is the only Markdown document in the repository. Keep project rules, structure, lesson descriptions, and usage notes here. Do not create README.md, 공개안내.md, or other Markdown files unless the user explicitly requests them.
- At the root, keep only Git metadata, AGENTS.md, and lesson directories. Do not create a lesson-directory HTML page.
- The first lesson directory is 1_응급처치수업/. Its top level contains only 응급처치수업.url and 수업자료/.
- 수업자료/ contains 응급처치수업.html, assets/, 정답지.txt, and 이미지-제작안.txt.
- Match the HTML and Internet shortcut base names: 응급처치수업.html and 응급처치수업.url. The shortcut must open the actual HTTPS GitHub Pages URL, never a local file. Keep it synchronized after path changes.
- Do not create or retain ZIP archives unless explicitly requested.

## Versions and game changes

- Show MAJOR.MINOR as a small centered home-only footer in 1_응급처치수업/수업자료/응급처치수업.html (#site-version). Initial release was 1.0; current release is 1.9. Keep the displayed version and aria-label synchronized.
- Bump once per completed user-requested site update, not for each edit, retry, test, or commit. Text fixes, answer revisions, styling, and small features increment MINOR. Treat both parts as integers: 1.9 -> 1.10. Large changes to the game structure or main workflow increment MAJOR and reset MINOR: 1.9 -> 2.0. Do not bump for read-only questions or documentation-only changes. Update the current release recorded here when bumping.
- Keep 정답지.txt synchronized with changes to questions, equipment requirements, correct answers, and explanations.
- Keep creator credits and the blog link visible on every game screen; the version stays home-only.
- Do not reveal correct equipment or treatment order in incorrect-answer feedback. Keep shuffled choices stable within a mission, including after selecting answers or reloading.

## Lesson 1: emergency first aid

- Title: 출동! 꼬마 구조대. Elementary health lesson on scrapes, nosebleeds, burns, ankle sprains, dust in the eye, and bee stings.
- Workflow: situation -> equipment -> treatment order -> reason quiz -> changed situation -> completion. Wound and burn content follows the textbook image supplied by the user while distinguishing mild situations from severe emergencies.
- Online game: https://morningbreadteacher.github.io/health_class/1_%EC%9D%91%EA%B8%89%EC%B2%98%EC%B9%98%EC%88%98%EC%97%85/%EC%88%98%EC%97%85%EC%9E%90%EB%A3%8C/%EC%9D%91%EA%B8%89%EC%B2%98%EC%B9%98%EC%88%98%EC%97%85.html
- Double-click 1_응급처치수업/응급처치수업.url for the hosted game. Open 수업자료/응급처치수업.html for local use; assets/ must remain beside it.
- Entering a team name and confirming resets previous completion records. Team name and badges stay in browser storage and are not submitted to the teacher. Completed missions retain badges when returning home or reloading.
- Equipment, order, quiz answers and explanations are in 수업자료/정답지.txt. Choice letters vary because options are shuffled; assess answers by content.
- assets/ holds six AI-generated educational reenactment images, shown inside cases only. Image production notes are in 이미지-제작안.txt.
- Credits: 제작 및 개발 : 네이버 블로그 '모닝빵의 여행일기'. Blog: https://blog.naver.com/mimi30419 . Copyright © 모닝빵의 여행일기. All rights reserved.

## Publication scope

- This repository is public. All committed files and history can be viewed on GitHub.
- Renaming Markdown files is not access control. Pages can publish Markdown as HTML and may expose other files by known paths. Do not claim that AGENTS.md or an unlinked file is private without checking deployment settings and results.
