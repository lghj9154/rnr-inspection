# RNR 정기점검 현황 (정식 버전)

- 화면: `index.html` 한 파일 (Cloudflare Pages에 그대로 게시, 빌드 없음)
- 로그인·데이터: Supabase `rnr-tech-report` 프로젝트
  - 로그인: Google, @rnrvh.com 계정만
  - 보기: @rnrvh.com 로그인 사용자 전체
  - 수정: `inspection_editors` 명단에 있는 사람만
- 주요 테이블: `inspection_sites`, `inspection_visits`, `inspection_visit_log`(수정 기록),
  `inspection_site_contract`(계약 요약 뷰), `inspection_maint_changes`(계약 변경 내역)
- 유지보수 계약 시트: Apps Script「정기점검웹_유지보수계약_동기화」가 매주 월요일 7시 업로드
