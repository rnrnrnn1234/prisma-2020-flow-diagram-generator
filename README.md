# prisma_2020_flow_diagram_generator
PRISMA 2020 flow diagram generator web app for reviews

문헌고찰 연구를 위한 논문 투고용 PRISMA 2020 흐름도를 만들어주는 무료 웹 도구입니다. 설치나 코딩 없이, 브라우저에서 선별 단계별 숫자만 입력하면 고해상도 그림을 다운로드할 수 있습니다.

**🔗 바로 사용하기:** https://rnrnrnn1234.github.io/prisma-2020-flow-diagram-generator

![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)
![PRISMA 2020](https://img.shields.io/badge/PRISMA-2020-blue.svg)
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.21373605.svg)](https://doi.org/10.5281/zenodo.21373605)

## 주요 기능

- **인터랙티브 입력 폼** — 데이터베이스 선택(PubMed, CINAHL, Embase, PsycINFO, Web of Science, Cochrane Library, RISS, KISS, KoreaMed 또는 직접 추가) 후 검색 건수 입력
- **자동 계산** — Records screened, Reports sought, Reports assessed, Studies included가 자동으로 계산되어 산술 오류를 방지
- **수기검색 지원** — 수기검색(웹사이트, 기관, 인용 검색) 입력이 있을 때만 "Identification of studies via other methods" 열이 PRISMA 2020 양식에 맞추어 표시
- **제외 사유 입력** — 전문 검토 제외 사유를 개수 제한 없이 추가하고 레이블 수정 가능
- **고해상도 출력** — 학술지 투고 가능한 PNG 다운로드

## 사용 방법

1. [웹 앱](https://rnrnrnn1234.github.io/prisma-2020-flow-diagram-generator) 접속
2. 검색한 데이터베이스를 체크하고 각각의 검색 건수 입력
3. 중복 제거 수와 제목/초록 제외 수 입력 — 나머지는 자동 계산 (자동 계산 값도 직접 수정 가능)
4. 전문 검토 제외 사유와 건수 입력
5. 요약 확인 후 **생성** 버튼 클릭
6. PNG를 다운로드하여 원고에 삽입

## 인용 및 출처

연구에 이 도구를 사용하셨다면 PRISMA 2020 원 논문을 인용해 주세요:

> Page MJ, McKenzie JE, Bossuyt PM, Boutron I, Hoffmann TC, Mulrow CD, et al. The PRISMA 2020 statement: an updated guideline for reporting systematic reviews. *BMJ* 2021;372:n71. doi: [10.1136/bmj.n71](https://doi.org/10.1136/bmj.n71)

PRISMA 2020 흐름도 양식은 [PRISMA statement](https://www.prisma-statement.org/)가 [크리에이티브 커먼즈 저작자표시(CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/) 라이선스로 배포하며, 원 저작물을 올바르게 인용하는 조건으로 배포·수정·활용이 허용됩니다. 이 도구는 해당 양식을 기반으로 한 독립 구현물이며 PRISMA 그룹의 공식 승인을 받은 것은 아닙니다.

**이 도구 자체의 인용은 필수가 아닙니다** — 원고에 필요한 인용은 위의 PRISMA 원 논문입니다. 그래도 이 도구를 언급하고 싶으시다면 아래 형식을 사용하실 수 있습니다:

> Park, S. (2026). PRISMA 2020 Flow Diagram Generator (Version 1.0.0) [Computer software]. Zenodo. https://doi.org/10.5281/zenodo.21373605

## 라이선스

- **소스 코드:** [MIT License](LICENSE) © 2026 Soyeon Park
- **PRISMA 2020 흐름도 양식 디자인:** © PRISMA, [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/)

## 제작자

**박소연 (Soyeon Park)** — 서울대학교 간호대학 박사과정

rnsy1029@snu.ac.kr

## 지도교수

**우경미 (Kyungmi Woo)** — 서울대학교 간호대학 부교수

ANDA Lab: https://andalab.snu.ac.kr/

## 감사의 말

이 도구는 AI 도구(Claude, Anthropic)를 활용하여 개발되었습니다. 모든 설계 결정, 요구사항 정의 및 검증은 제작자가 수행했습니다.

---

<br>

# PRISMA 2020 Flow Diagram Generator (English)

A free, browser-based tool for generating publication-ready PRISMA 2020 flow diagrams for reviews. No installation, no coding — enter your screening numbers and download a high-resolution figure.

**🔗 Live app:** https://rnrnrnn1234.github.io/prisma-2020-flow-diagram-generator

## Features

- **Interactive input form** — select databases (PubMed, CINAHL, Embase, PsycINFO, Web of Science, Cochrane Library, RISS, KISS, KoreaMed, or add your own) and enter record counts
- **Automatic calculation** — records screened, reports sought, reports assessed, and studies included are computed automatically to prevent arithmetic errors
- **Hand-searching support** — the "Identification of studies via other methods" column appears only when other-methods sources (websites, organisations, citation searching) are entered, following the PRISMA 2020 template
- **Unlimited exclusion reasons** — add and rename full-text exclusion reasons without limits
- **Adaptive layout** — the database box and the Identification band grow together as more databases are added, keeping the official template proportions
- **High-resolution export** — download the diagram as a PNG suitable for journal submission

## How to Use

1. Open the [live app](https://rnrnrnn1234.github.io/prisma-2020-flow-diagram-generator)
2. Check the databases you searched and enter the number of records for each
3. Enter duplicates removed and records excluded — the rest is calculated automatically (auto-calculated fields can still be edited manually)
4. Add full-text exclusion reasons with counts
5. Review the summary and click **Generate**
6. Download the PNG and insert it into your manuscript

## Citation & Attribution

This tool is based on the PRISMA 2020 statement. If you use this tool in your research, please cite the original PRISMA 2020 publication:

> Page MJ, McKenzie JE, Bossuyt PM, Boutron I, Hoffmann TC, Mulrow CD, et al. The PRISMA 2020 statement: an updated guideline for reporting systematic reviews. *BMJ* 2021;372:n71. doi: [10.1136/bmj.n71](https://doi.org/10.1136/bmj.n71)

The PRISMA 2020 flow diagram template is distributed by the [PRISMA statement](https://www.prisma-statement.org/) under the [Creative Commons Attribution (CC BY 4.0) license](https://creativecommons.org/licenses/by/4.0/), which permits others to distribute, remix, adapt and build upon the work, provided the original work is properly cited. This tool is an independent implementation built upon that template and is not officially endorsed by the PRISMA group.

Citing this tool itself is **not required** — the citation above is what matters for your manuscript. If you would nevertheless like to acknowledge this tool, you may use:

> Park, S. (2026). PRISMA 2020 Flow Diagram Generator (Version 1.0.0) [Computer software]. https://github.com/rnrnrnn1234/prisma-2020-flow-diagram-generator

## License

- **Source code:** [MIT License](LICENSE) © 2026 Soyeon Park
- **PRISMA 2020 flow diagram template design:** © PRISMA, [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/)

## Author

**Soyeon Park (박소연)** — Doctoral Student, College of Nursing, Seoul National University

rnsy1029@snu.ac.kr

## Advisor

**Kyungmi Woo (우경미)** — Associate Professor, College of Nursing, Seoul National University

ANDA Lab: https://andalab.snu.ac.kr/

## Acknowledgements

Developed with the assistance of AI tools (Claude, Anthropic). All design decisions, requirements, and validation were performed by the author.
