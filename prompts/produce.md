# 콘텐츠 한 회차 전체 실행

브랜드 기준에 맞는 새 소재를 찾아, 같은 소재로 블로그·인스타그램 카드뉴스·Threads 콘텐츠 한 회차를 만들어 줘.

## 코디네이터

- 브랜드 기준을 읽고 이번 실행 ID로 회차 폴더를 정해 모든 워커에게 알려 줘.
- 브랜드 기준이나 콘텐츠 포맷 문서가 없으면 실행하지 말고 빠진 문서를 알려 줘. 인터뷰와 전략 수립은 다시 하지 마.
- 워커 표시 이름은 실행 ID 없이 소재 수집 워커·블로그 워커처럼 역할 이름으로 붙여 줘.
- 이번 실행을 재개하는 경우에는 이미 고른 소재와 완료한 결과물을 이어서 사용해 줘.

## 작업 배정

1. 소재 수집 워커[Codex]: 콘텐츠 전략의 검색어로 agent-browser를 써서 웹 자료를 찾아 소재 선정 기준에 맞는 후보 소재를 모으고(agent-browser를 쓸 수 없으면 기본 웹 도구 사용), 후보마다 출처 링크를 후보 기록에 저장해 줘. 후보 중 이전 회차와 겹치지 않는 소재 하나를 골라, 소재 브리프 작성 기준에 따라 소재 브리프를 작성해 줘.
2. 코디네이터: 소재 브리프를 확인하고 세 워커에게 똑같이 전달해 동시에 시작해 줘.
   - 블로그 워커[Claude Code]: content-creation 스킬로 블로그 포맷 하나를 골라 원고 작성. 이미지는 직접 설계하고, 생성은 하위 워커[Codex]에게 맡겨 줘.
   - 인스타그램 워커[Codex]: social 스킬로 카드뉴스 포맷 하나를 골라 카드뉴스 작성. 이미지는 Codex 이미지 생성 기능으로 만들어 줘.
   - Threads 워커[Hermes]: content-creation 스킬로 Threads 포맷 하나를 골라 게시글 작성.
   - 모든 워커는 말투 규칙을 적용하고, 고른 포맷과 이유를 원고에 남겨 줘. 소재 브리프와 다른 워커의 파일은 수정하지 마.

## 결과

- 플랫폼에 게시하지 말고, 회차 폴더를 알려 줘.
- 내가 결과를 확인하고 정리를 승인하기 전까지는 작업이 끝난 워커도 종료하거나 터미널을 닫지 마.

## 참고자료

- 공통 지침: AGENTS.md
- 저장 규칙: README.md
- 브랜드 프로필: artifacts/rules/about-me.md
- 말투 규칙: artifacts/rules/voice.md
- 콘텐츠 전략: artifacts/rules/content-strategy.md
- 소재 브리프 작성 기준: artifacts/rules/brief-criteria.md
- 블로그 포맷: references/formats/blog-formats.md
- 카드뉴스 포맷: references/formats/instagram-carousel-formats.md
- Threads 포맷: references/formats/threads-formats.md
