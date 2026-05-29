# AI_WORKLOG

Shared project work log for Codex, Claude Code, Antigravity, and humans.
Read the latest relevant entries before substantial work. Append a concise entry after non-trivial work.

## 2026-05-29 10:17 KST - Codex - 모바일 FAQ 공지/상단 배치 개선

- Summary:
  - 상단 부제를 모바일 버전으로 정리하고, H1을 환영 문구로 변경했으며, 공지사항 접어두기 버튼과 FAQ 개수/전체펼치기 위치 이동을 반영함.
- Files:
  - index.html
  - AI_WORKLOG.md
- Verification:
  - 인라인 JS 문법 검사 통과; Chrome headless 390x844 스크린샷 확인; 공지 접기 DOM 동작 확인; GitHub Pages 새 HTML 반영 확인
- Next:
  - 공지 문구는 NOTICE_DATA 배열만 수정하면 되며, PWA 아이콘/manifest 구조는 유지할 것.

## 2026-05-29 10:37 KST - Codex - 공지 상세 팝업 및 검색 결과 이동 개선

- Summary:
  - 공지 카드를 2줄 요약으로 제한하고 카드 클릭 시 전체 공지 팝업을 열도록 추가했으며, 검색 제출 시 FAQ 결과 영역으로 이동하는 로직을 추가함. 팝업 우측 상단 닫기 버튼을 명확한 원형 X 버튼으로 보강함.
- Files:
  - index.html
  - AI_WORKLOG.md
- Verification:
  - 인라인 JS 문법 검사 통과; Chrome headless에서 공지 팝업/닫기 버튼 DOM 확인; 파일 용량 확인
- Next:
  - 실기기에서 검색 키보드 Enter 후 스크롤 위치를 한 번 확인할 것. GitHub Pages 파일 링크는 Pages 대역폭에 포함되는 것으로 안내함.

