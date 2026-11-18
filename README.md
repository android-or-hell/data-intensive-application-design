# 📚 데이터 중심 애플리케이션 설계 서적 스터디

## 🙌 목표

- [데이터 중심 애플리케이션 설계 (Designing Data-Intensive Applications)](https://dataintensive.net/) 서적 완독 (1판 번역서 기준)
- 책에서 다루는 개념을 이해하는 데 필요한 **배경지식까지 직접 조사하고 공유**하기

## 📌 진행 방식

- 매주 수요일 오후 9시 30분 진행
- 매주 지정된 범위까지 독서 후 주요 내용 요약 및 정리
- 배경지식이 많이 필요한 책이므로, 책 내용뿐 아니라 **별도로 조사한 내용까지 함께 발표**
  - e.g. B-Tree / LSM-Tree 의 실제 구현, 분산 합의 알고리즘(Raft, Paxos), 사용 중인 DB의 격리 수준 등
  - 조사한 내용은 출처를 반드시 남기기
- 발표 후 토론 및 질의 진행

## 📝 정리 문서 구성

각자의 `md` 파일은 아래 구성을 권장합니다.

1. **책 내용 정리** : 해당 주차 범위의 핵심 개념 요약
2. **배경지식 / 추가 조사** : 책만으로는 이해하기 어려웠던 개념, 직접 찾아본 내용
3. **토론 거리** : 다른 멤버와 이야기해보고 싶은 질문
4. **출처** : 참고한 공식 문서, 논문, 블로그 등

## 📌 기타

### PR

- 제목 : [WEEK `${02d}`] `${장}` `닉네임`
- e.g. : [WEEK 01] 01장 DongChyeon
- PR 본문은 [PR 템플릿](./.github/PULL_REQUEST_TEMPLATE.md)에 맞춰 작성

### 패키지 구조

책의 **Part → 장** 구성을 그대로 따릅니다. 주차 정보는 PR 제목으로 관리합니다.

- 정리 문서 : `Part${n}_${부 제목}/${nn}장_${장 제목}/${닉네임}.md`
- 이미지 : `${nn}장_${장 제목}/images/${닉네임}/`
- 한 장을 여러 주에 걸쳐 읽으면 **같은 파일에 이어서 작성**
- 각 장 폴더의 `README.md` 에 해당 장의 목차와 멤버별 문서 링크가 있습니다
- Part 2 도입부(고부하로 확장)는 05장 폴더에서 함께 정리

```
📂Part1_데이터_시스템의_기초
  📃README.md
  📂01장_신뢰성_확장성_유지보수성
    📃README.md          ← 장 목차 + 멤버별 문서 링크
    📃DongChyeon.md
    📃jihee-dev.md
    📃lluke0.md
    📂images
      📂DongChyeon
  📂02장_데이터_모델과_질의_언어
  📂03장_저장소와_검색
  📂04장_부호화와_발전
📂Part2_분산_데이터
  📂05장_복제
  📂06장_파티셔닝
  📂07장_트랜잭션
  📂08장_분산_시스템의_골칫거리
  📂09장_일관성과_합의
📂Part3_파생_데이터
  📂10장_일괄_처리
  📂11장_스트림_처리
  📂12장_데이터_시스템의_미래
```

### 목차

| Part | 장 |
| --- | --- |
| [Part 1. 데이터 시스템의 기초](./Part1_데이터_시스템의_기초) | [01장 신뢰할 수 있고 확장 가능하며 유지보수하기 쉬운 애플리케이션](./Part1_데이터_시스템의_기초/01장_신뢰성_확장성_유지보수성)<br>[02장 데이터 모델과 질의 언어](./Part1_데이터_시스템의_기초/02장_데이터_모델과_질의_언어)<br>[03장 저장소와 검색](./Part1_데이터_시스템의_기초/03장_저장소와_검색)<br>[04장 부호화와 발전](./Part1_데이터_시스템의_기초/04장_부호화와_발전) |
| [Part 2. 분산 데이터](./Part2_분산_데이터) | [05장 복제](./Part2_분산_데이터/05장_복제)<br>[06장 파티셔닝](./Part2_분산_데이터/06장_파티셔닝)<br>[07장 트랜잭션](./Part2_분산_데이터/07장_트랜잭션)<br>[08장 분산 시스템의 골칫거리](./Part2_분산_데이터/08장_분산_시스템의_골칫거리)<br>[09장 일관성과 합의](./Part2_분산_데이터/09장_일관성과_합의) |
| [Part 3. 파생 데이터](./Part3_파생_데이터) | [10장 일괄 처리](./Part3_파생_데이터/10장_일괄_처리)<br>[11장 스트림 처리](./Part3_파생_데이터/11장_스트림_처리)<br>[12장 데이터 시스템의 미래](./Part3_파생_데이터/12장_데이터_시스템의_미래) |

## 👥 멤버

<div align="center">
  <table style="font-weight: bold">
      <tr>
          <td align="center">
              <a href="https://github.com/DongChyeon">
                  <img alt="DongChyeon" src="https://avatars.githubusercontent.com/DongChyeon" width="80" />
              </a>
          </td>
          <td align="center">
              <a href="https://github.com/jihee-dev">
                  <img alt="jihee-dev" src="https://avatars.githubusercontent.com/jihee-dev" width="80" />
              </a>
          </td>
          <td align="center">
              <a href="https://github.com/lluke0">
                  <img alt="lluke0" src="https://avatars.githubusercontent.com/lluke0" width="80" />
              </a>
          </td>
      </tr>
      <tr>
          <td align="center"><a href="https://github.com/DongChyeon">DongChyeon</a></td>
          <td align="center"><a href="https://github.com/jihee-dev">jihee-dev</a></td>
          <td align="center"><a href="https://github.com/lluke0">lluke0</a></td>
      </tr>
  </table>
</div>
