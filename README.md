# 📖 Korean-Bible-1961-KRV (1961년 개역한글 성경)

[![Language](https://img.shields.io/badge/Language-Korean-blue.svg)](https://en.wikipedia.org/wiki/Bible_translations_into_Korean)
[![License](https://img.shields.io/badge/License-Public_Domain-green.svg)](https://www.bskorea.or.kr/bbs/board.php?bo_table=copyright_faq&wr_id=5)

This repository provides the **1961 Korean Revised Version (KRV) Bible** in digital format (JSON). The data is strictly based on the standards of the **Bible Society of Korea (BSK)** and has been rigorously cross-validated for maximum integrity.

---

## 🇰🇷 데이터 개요 (Korean Overview)

본 데이터셋은 1961년 판 개역한글 성경의 디지털 자료입니다. 2026년 3월 기준, 대한성서공회(BSK) 공식 데이터와의 1:1 전수 대조 시 **오차율 0%**를 기록하였습니다. 또한 외부 자료(HolyBible)와도 1:1 전수 대조를 하여 **오차율 0.00736%**를 기록한 신뢰 할 수 있는 자료입니다. (상세 근거는 [교차 검증 리포트](docs/validation_report.md)를 참조하십시오.)

### ✨ 주요 특징 (Key Features)

- **완벽한 정합성 (Structural Integrity)**: 66권, 1,189장, 31,102절의 성경 표준 구조를 100% 충족합니다.
- **고어 완벽 보존 (Archaic Language Preservation)**: '쁄라', '맟도록', '하살마웻' 등 인코딩 문제로 깨지기 쉬운 고어 표기가 유니코드(UTF-8)로 정확하게 보존되어 있습니다.
- **검증된 정확도 (Verified Accuracy)**: 대조 검증을 통해 오타 및 누락이 없음을 확증하였습니다.

---

## 📂 파일 구조 (File Structure)

- `data/*.json`: 권별 개별 JSON 파일 (English book titles used for filename compatibility).
- `bible_1961_krv.json`: 성경 전체 통합 JSON 파일.
- `docs/bsk_bible_statistics.md`: 권별 장/절 통계 참조표.
- `docs/bible_abbreviations.md`: 대한성서공회 표준 성경 약어표.

---

## 📊 성경 통계 요약 (Bible Statistics Summary)

- **Total**: 66 Books / 1,189 Chapters / 31,102 Verses
- **Old Testament**: 39 Books / 929 Chapters / 23,145 Verses
- **New Testament**: 27 Books / 260 Chapters / 7,957 Verses

---

## ⚖️ 저작권 및 이용 안내 (Copyright & License)

『성경전서 개역한글판』의 저작재산권 보호기간은 50년(2013년 이후 70년)이 경과되어 **저작권료 지급 없이 자유롭게 사용이 가능**합니다. (출처: [대한성서공회 공지](https://www.bskorea.or.kr/bbs/board.php?bo_table=copyright_faq&wr_id=5))

단, 사용 시 아래의 인격저작권을 준수해주시기 바랍니다:

1. **성명표시권**: 저작자(대한성서공회)의 성명을 올바르게 표시해야 합니다.
2. **동일성유지권**: 저작물의 내용과 형식을 무단으로 개작하지 않고 본연의 가치를 유지해야 합니다.

---

## 🤝 기여 및 문의 (Contribution)

본 데이터는 디지털 환경에서의 성경 보급을 위해 제작되었습니다. 데이터 결함 발견 시 이슈(Issue)를 통해 제보해주시면 감사하겠습니다.

*Released on March 25, 2026 / Verified by SoftPinkCat, assisted by AI tools*
