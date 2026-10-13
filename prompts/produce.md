# 콘텐츠 한 회차 전체 실행

채널 기준에 맞는 새 소재를 찾아, 같은 소재로 블로그·인스타그램 카드뉴스·Threads 콘텐츠 한 회차를 만들어 줘.

## 코디네이터

- 채널 기준을 읽고 이번 실행 ID로 회차 폴더를 정해 모든 워커에게 알려 줘.
- 채널 기준 문서가 없으면 실행하지 말고 빠진 문서를 알려 줘. 인터뷰와 전략 수립은 다시 하지 마.
- 이전 회차의 소재 브리프를 확인해 같은 소재를 반복하지 않게 해 줘. 이번 실행을 재개하는 경우에는 이미 고른 소재와 완료한 결과물을 이어서 사용해 줘.

## 작업 배정

1. 소재 수집 워커: 콘텐츠 전략의 검색어로 웹 검색해 소재 선정 기준에 맞는 후보 소재를 모으고, 후보마다 출처 링크를 후보 기록에 저장해 줘. 글의 관점·핵심 메시지·이미지 설계는 정하지 마.
2. 코디네이터: 후보 중 이전 회차와 겹치지 않는 소재 하나를 골라 공통 전달 기준에 따라 소재 브리프를 작성해 줘.
3. 소재 브리프가 저장되면 세 워커를 동시에 시작해 줘.
   - 블로그 워커 (Claude Code): /content-creation 스킬로 블로그 포맷 하나를 골라 원고 작성. 이미지는 직접 설계하고, 생성은 Codex 하위 워커에게 맡겨 줘.
   - 인스타그램 워커 (Codex, 모델 gpt-5.6-terra, 추론 medium): $social 스킬로 카드뉴스 포맷 하나를 골라 장별 문구·캡션 작성. 슬라이드는 Codex 이미지 생성 기능으로 모든 장 1080×1080px로 만들어 줘.
   - Threads 워커 (Hermes): 프로젝트 스킬 content-creation으로 Threads 포맷 하나를 골라 게시글 작성.
   - 모든 워커는 말투 규칙을 적용하고, 고른 포맷과 이유를 원고에 남겨 줘. 소재 브리프와 다른 워커의 파일은 수정하지 마.

## 결과

- 플랫폼에 게시하지 말고, 회차 폴더를 알려 줘.

## 참고자료

- 공통 지침: AGENTS.md
- 저장 규칙: README.md
- 채널 프로필: artifacts/rules/about-me.md
- 말투 규칙: artifacts/rules/voice.md
- 콘텐츠 전략: artifacts/rules/content-strategy.md
- 공통 전달 기준: artifacts/rules/delivery-criteria.md
- 블로그 포맷: references/formats/blog-formats.md
- 카드뉴스 포맷: references/formats/instagram-carousel-formats.md
- Threads 포맷: references/formats/threads-formats.md
