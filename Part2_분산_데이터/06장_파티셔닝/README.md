# 06장: 파티셔닝

> [Part 2] 분산 데이터

## 📖 목차

- 파티셔닝과 복제
- 키-값 데이터 파티셔닝
  - 키 범위 기준 파티셔닝
  - 키의 해시값 기준 파티셔닝
  - 쏠린 작업부하와 핫스팟 완화
- 파티셔닝과 보조 색인
  - 문서 기준 보조 색인 파티셔닝
  - 용어 기준 보조 색인 파티셔닝
- 파티션 재균형화
  - 재균형화 전략
  - 운영: 자동 재균형화와 수동 재균형화
- 요청 라우팅
  - 병렬 질의 실행

## 📝 정리

| 멤버 | 문서 |
| --- | --- |
| [DongChyeon](https://github.com/DongChyeon) | [DongChyeon.md](./DongChyeon.md) |
| [jihee-dev](https://github.com/jihee-dev) | [jihee-dev.md](./jihee-dev.md) |
| [lluke0](https://github.com/lluke0) | [lluke0.md](./lluke0.md) |

## 📂 파일 규칙

- 정리 문서 : `06장_파티셔닝/${닉네임}.md` (장이 여러 회차에 걸치면 같은 파일에 이어서 작성)
- 이미지 : `06장_파티셔닝/images/${닉네임}/` 에 저장
- 다른 장에 해당하는 내용은 해당 장 폴더에 작성
