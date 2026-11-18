# 07장: 트랜잭션

> [Part 2] 분산 데이터

## 📖 목차

- 애매모호한 트랜잭션의 개념
  - ACID의 의미
  - 단일 객체 연산과 다중 객체 연산
- 완화된 격리 수준
  - 커밋 후 읽기
  - 스냅숏 격리와 반복 읽기
  - 갱신 손실 방지
  - 쓰기 스큐와 팬텀
- 직렬성
  - 실제적인 직렬 실행
  - 2단계 잠금(2PL)
  - 직렬성 스냅숏 격리(SSI)

## 📝 정리

| 멤버 | 문서 |
| --- | --- |
| [DongChyeon](https://github.com/DongChyeon) | [DongChyeon.md](./DongChyeon.md) |
| [jihee-dev](https://github.com/jihee-dev) | [jihee-dev.md](./jihee-dev.md) |
| [lluke0](https://github.com/lluke0) | [lluke0.md](./lluke0.md) |

## 📂 파일 규칙

- 정리 문서 : `07장_트랜잭션/${닉네임}.md` (장이 여러 회차에 걸치면 같은 파일에 이어서 작성)
- 이미지 : `07장_트랜잭션/images/${닉네임}/` 에 저장
- 다른 장에 해당하는 내용은 해당 장 폴더에 작성
