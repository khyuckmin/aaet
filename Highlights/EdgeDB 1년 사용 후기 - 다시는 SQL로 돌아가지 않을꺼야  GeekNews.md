---
doc_type: hypothesis-highlights
url: >-
  https://news.hada.io/topic?id=7052&utm_source=slack&utm_medium=bot&utm_campaign=T02BHKQ35
---

# EdgeDB 1년 사용 후기 - "다시는 SQL로 돌아가지 않을꺼야" | GeekNews

## Metadata
- Author: [news.hada.io]()
- title: EdgeDB 1년 사용 후기 - "다시는 SQL로 돌아가지 않을꺼야" | GeekNews
- Reference: https://news.hada.io/topic?id=7052&utm_source=slack&utm_medium=bot&utm_campaign=T02BHKQ35
- Category: #article

draft: false
## Page Notes
## Highlights
- 결론 난 앞으로의 프로젝트에선 기존 RDB는 고려할 생각이 없음 SQL로 돌아가는 것은 Flutter 에서 Ncurses로 가거나, Go에서 어셈블리 언어로 돌아가는 것과 마찬가지임 나에겐, EdgeDB가 지난 20년간 DB 분야에서 가장 큰 발전임. 앞으로 더 많은 경험을 하면 바뀔수도 있겠지만, 1년 넘게 사용하면서 이 기쁨을 해치는 일이 아무것도 없었음 사용하면 할수록 EdgeDB를 신뢰하게 됨 EdgeDB 팀이 EdgeDB 자체와 언어,웹사이트,도구,커뮤니티를 만드는 일등에 한 모든 것들이 엄청 인상적임 → "Mad respect to the team" 그리고 그들은 이제 겨우 워밍업 한 것 같음 — [Updated on 2022-07-27 10:17:49](https://hyp.is/7fy8uA1JEe2gkUeATgrFIA/news.hada.io/topic?id=7052&utm_source=slack&utm_medium=bot&utm_campaign=T02BHKQ35) — Group: #Public

- EdgeQL의 표현력 그동안 SQL에 대해서 구글링하고 ORM 제한과 회피방법들을 찾아다니던 것에서 해방되었음 EdgeQL은 내가 DB에서 찾고 싶은 것들만 딱 표현할 수 있고, 실제로 읽어서 이해할 수 있음 (다른 개발자도) 종종 EdgeQL 때문에 트랜잭션도 피할수 있음. 싱글쿼리 안에서 다중 중첩 업데이트도 가능함. → "Simplicity is complicated" — [Updated on 2022-07-27 10:18:04](https://hyp.is/9xWNyg1JEe2XFde7bTlFxA/news.hada.io/topic?id=7052&utm_source=slack&utm_medium=bot&utm_campaign=T02BHKQ35) — Group: #Public

- 기능들 엄청 쉬운 many-to-many 관계 모델링 임베디드 GraphQL (프론트엔드에서 직접 연결 가능) Computed 속성 rating := math::mean(.ratings.score) backlinks : 링크를 역순으로 찾아가기 → select User.<author; User가 author 라는 이름의 필드로 연결된 테이블에서 검색 uuid, collection, scalar, abstract 및 여러 타입들 (나의 최애는 cal::local_datetime) inheritance, constraints 와 Introspection 같은 무서운 것들 — [Updated on 2022-07-27 10:18:13](https://hyp.is/_BNyVg1JEe2gkpdX0eOC5g/news.hada.io/topic?id=7052&utm_source=slack&utm_medium=bot&utm_campaign=T02BHKQ35) — Group: #Public

- 쿼리 언어 EdgeDB는 SQL이 없고 자체 언어인 EdgeQL을 사용하는데, 이게 게임체인저임 한번 사용해보니, 다시는 SQL로 돌아가고 싶지 않음 → 강력한 타입, 객체 지향, 딥쿼리가 엄청 쉬우며, 사람이 데이터를 쿼리하는 사고방식에 잘 매핑 됨(사람들이 JOIN 하는 방식으로 생각하지는 않으니까) 예전에도 SQL의 팬은 아니었지만, 실제로 대체제가 없었음 환상적인 책-스타일의 튜토리얼과 함께 몇 일 배우고 연습하고 나니, DB 스키마 모델링이 재미나고 가벼운 일이라는 걸 알게 되었음 → SQL의 복잡성이 사라졌고, SQL이 쿼리언어로써 얼마나 비효율적이고 이상한지 알게되었음 EdgeQL은 배우기 쉽고, 퀵스타트와 오버뷰 만으로 80% 정도를 익힐 수 있음 나는 EdgeQL이 너무 좋아서, 독립적인 표준이 되었으면 좋겠음. 그래서 예를 들어 파일 기반DB에서 EdgeQL사용이 가능한 EdgeDBLite 같은게 나오면 좋겠음 — [Updated on 2022-07-27 10:18:22](https://hyp.is/AXX2ag1KEe28cNOypuNaCA/news.hada.io/topic?id=7052&utm_source=slack&utm_medium=bot&utm_campaign=T02BHKQ35) — Group: #Public



