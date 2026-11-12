# persona-cjm 스킬 패키지 안내 (Claude용)

- `SKILL.md`: 스킬 본문 (작업 폴더 `.claude/skills/persona-cjm/SKILL.md`와 동일, 2026-11-12 기준)
- `examples/lalasweet-pint.md`: 라라스윗 저당 아이스크림 파인트 적용 사례 (퍼소나 5-Whys, 6단계 CJM)
- `references/` (사례 근거 데이터, 확인일 2026-11-12)
  - `lalasweet-realdata.md` = 작업 폴더의 `라라스윗_저당딸기듬뿍바_쿠팡_실데이터_2026-11-12.md` (쿠팡 듬뿍바 + 공식몰 파인트 실데이터 수집 기록)
  - `lalasweet-review-5types.md` = `라라스윗_리뷰5유형_분석_2026-11-12.md` (리뷰 5유형 비율, 고객 언어)
  - `lalasweet-reviews-660.csv` = `라라스윗_저당딸기듬뿍바_쿠팡리뷰_전체660_2026-11-12.csv` (리뷰 원문, 작성자 익명화)
  - `lalasweet-review-tags-660.csv` = `라라스윗_리뷰근거태그_전체660_2026-11-12.csv` (리뷰별 5유형·Why·이탈 태그)
- 사례 파일 안의 `data/lalasweet/...` 경로는 위 `references/` 파일로 바꿔 읽는다.
- 규칙: SKILL.md는 사용자가 수정하라고 할 때만 고친다.
