# 🃏 BlackJack (Python CLI)

`알고리즘과 게임콘텐츠` 수업에서 진행한 **Python 기반 CLI(터미널) 블랙잭 게임**입니다.  
사용자 입력을 통해 게임을 진행하며, **ASCII 카드 UI 출력**, **칩/베팅 계산**, **플레이 로그 저장** 기능을 포함합니다.


---

## 🎮 주요 기능

- **CLI 블랙잭 게임 진행**
  - 플레이어 이름 입력 → 로비 진입 → 게임 진행 흐름

- **Chip / Betting 계산**
  - money → 칩 배열 변환, 칩 배열 → money 환산  
  - (구현 파일) `calc_chip.py`

- **ASCII 카드 UI 출력**
  - 카드들을 가로로 정렬해 보여주고, 플레이어 수에 따라 레이아웃을 구성  
  - (구현 파일) `game.py`

- **플레이 로그/기록 관리**
  - 플레이어 정보 txt 저장/로드  
  - 로그 csv export, 로그 zip 다운로드 등  
  - (구현 파일) `logs.py`

---

## 📄 발표자료 / 보고서

- 발표자료(PDF): `docs/blackjack_presentation.pdf`

---

## 🧩 프로젝트 구조 (핵심)

- `main.py`  
  - 플레이어 이름 입력 → DB 초기화 → 로비 진입

- `calc_chip.py`  
  - 칩 단위 계산(금액 ↔ 칩 변환)

- `features/game.py`  
  - ASCII 카드 출력 및 레이아웃 처리

- `features/logs.py`  
  - 로그 저장/로드, csv export, zip 다운로드

---

## ▶️ 실행 방법

```bash
python main.py
