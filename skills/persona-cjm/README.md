# persona-cjm 스킬 패키지 안내 (Claude용)

> 이 폴더의 기획서와 데이터는 언급된 브랜드·플랫폼(라라스윗, 프립, 마이리얼트립 등)과 무관한 **개인 학습·포트폴리오용** 자료입니다. 브랜드의 공식 자료가 아닙니다.

## 스킬
- `SKILL.md`: 스킬 본문 **v2(근거 기반)**, 2026-11-12 기준. **이 레포의 SKILL.md가 기준본**입니다. 로컬 작업 폴더에 남아 있는 v1 SKILL.md로 덮어쓰지 않습니다.
- `example-lalasweet-pint.md`: 라라스윗 저당 아이스크림 파인트 적용 사례 (퍼소나 5-Whys, 6단계 CJM)
- `persona-cjm-skill.zip`: Claude 업로드용 패키지 (ZIP 안에서는 `examples/`, `references/` 폴더 구조)

## 레퍼런스 (사례 근거 데이터, 확인일 2026-11-12)
- `reference-lalasweet-realdata.md` = 작업 폴더의 `라라스윗_저당딸기듬뿍바_쿠팡_실데이터_2026-11-12.md` (쿠팡 듬뿍바 + 공식몰 파인트 실데이터 수집 기록)
- `reference-lalasweet-review-5types.md` = `라라스윗_리뷰5유형_분석_2026-11-12.md` (리뷰 5유형 비율, 고객 언어)
- `reference-lalasweet-reviews-660.csv` = `라라스윗_저당딸기듬뿍바_쿠팡리뷰_전체660_2026-11-12.csv` (리뷰 원문, 작성자 익명화)
- `reference-lalasweet-review-tags-660.csv` = `라라스윗_리뷰근거태그_전체660_2026-11-12.csv` (리뷰별 5유형·Why·이탈 태그)
- `reference-wellness-frip-collection.md` = 프립 1박 2일 그룹 상품 5개 + 마이리얼트립 국내 투어 3개 수집 기록 (**공개본: 리뷰 원문 제외**, 건수·비율·주제·출처만)

## 산출물 (`outputs/`, 모두 persona-cjm v2 규칙 기준)
| 파일 | 모드 | 내용 |
|---|---|---|
| `outputs/lalasweet-modeA-reels.html` | A · 15초 릴스 | 라라스윗 초콜릿 파인트 「꺼냈다 넣었다」 릴스: 첫 3초 훅, 내레이션, 컷 구성표, 생성형 AI 프롬프트 |
| `outputs/lalasweet-modeB-seongsu-popup.html` | B · 팝업/전시 | 성수 팝업 「22:04 냉동실」: 존별 동선과 CJM 매핑, 스태프 응대 매뉴얼, 냉동·시식 운영 |
| `outputs/wellness-modeC-weekend-logout.html` | C · 테마 투어 (v3) | 2534 직장인 1박 2일 웰니스 투어 「주말 로그아웃」: 리뷰 210건 기반 퍼소나·CJM, 포지셔닝, 가설 검증 로드맵, 인터뷰·베타 설계, 원가 산정 틀 |

## 수집·입력 도구
- `prompts/aside-lalasweet-collect.md`: 라라스윗 실데이터를 웹에서 한 번에 모으는 수집 프롬프트
- `prompts/aside-wellness-collect.md`: 웰니스 투어 퍼소나 검증용 수집 프롬프트
- `templates/modeC-input-form.md`: 모드 C를 확정하기 위해 기획자가 채우는 입력 양식 (원가·숙소·규정·인터뷰)

## 읽는 규칙
- 사례 파일 안의 `data/lalasweet/...` 경로는 위 `reference-` 파일로(ZIP 안에서는 `references/` 폴더) 바꿔 읽는다.
- `[실데이터 입력]`은 아직 확인되지 않은 값이다. 채우지 않은 채로 숫자를 만들어 넣지 않는다.
- SKILL.md는 사용자가 수정하라고 할 때만 고친다.
