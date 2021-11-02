# DevFest: 개발자의 취업과 진로- 카카오, 토스 개발자

> 현직 카카오, 토스 개발자의 취업 이야기와 백엔드, 프론트엔드의 진로에 대한 소개와 질의응답 시간을 가집니다!

## 카카오 주니어 프론트엔드 개발자 오승영 선배님

### 공개 채용 vs 수시 채용

- 코딩 테스트:프로젝트:CS지식 비율
  - 공개 채용 => `1 : 1 : 1`
  - 수시 채용 => `프로젝트 >> 코테 == CS`

### 학교 재학중 Tip

- 핵심 CS 과목들 위주로 신경써서 듣기 (자료구조, 운영체제, 네트워크, 알고리즘 ...)
  - 회사에서 핵심 CS 과목 학점을 요구하는 곳이 있음.
- 깃헙 관리 잘하기
- 프로젝트 수업, 졸업 논문은 나중에 취업과 연관해서 생각해보면 좋을 것 같다.
- 스터디 적극 활용 (교내 스터디 or 캠퍼스 픽)
  - 스터디는 다른 대외활동이나 인턴 활동보다 진입장벽도 낮고 부담없이 시작할 수 있어서 좋았다.
- 공모전 참가해보기
- 내가 해보진 않았지만 좋아보였던 것들
  - 외부 개발 동아리 (YAPP, SOPT, 멋쟁이 사자처럼 ...)
  - 기업 연계 활동(부스트캠프, 우아한테크코스, SAFFY) => 이런건 여러분들이 무조건 한번쯤은 신청해봤으면 좋겠어요. 이런 체계적인 교육을 받을 수 있는 기회가 살면서 몇 없음.

### 취준 Tip

- 준비 방향을 미리미리 정해놓자
  - 사기업 or 공기업
  - 공채 or 수시
  - 분야 => 프론트엔드, 백엔드, IOS, Android, Infra, ML ...
  - 도메인 => 제조, 통신사, 금융, IT ...
- 서류는 돌려쓰는게 좋은 것 같다.
  - 자기소개서
  - 프로젝트 경험 (트러블 슈팅 위주)
  - 협업 경험
  - 분야 특성 문항 (ex. 은행권에 관심을 갖게 된 이유..)
- 코테는 취준 전에 탄탄히 해두자
  - 서류, 면접 시즌 가면 집중하기가 힘들다.
  - 코테 떨어지면 서류와 같은 준비했던 다른 것들이 전부 물거품이 되기 때문에 ㅠ
  - 잘 나오는 유형 위주로, 전략적으로
    - DFS, BFS, 그리디, 구현, 투 포인터, 순열 조합, 다익스트라, ...
  - 네카라 기준 sloved.ac 골드 티어 문제 100~150개 풀어보자
  - 백준 + solved.ac 조합이 많이 도움이 되었음.
- CS는 평소에 꾸준히 해놓고 면접 직전에 벼락치기!
  - 면접 전에 볼 수 있게 정리해두기
    - TIL 관리하기 (언제든 쉽게 볼 수 있게 내 깃헙에 정리!)
    - https://github.com/JaeYeopHan/Interview_Question_for_Beginner
    - 키워드 찾아가면서 확장해 나가기
  - 스터디 활용
    - 서로 질답하면서 꼬리 질문 대비
    - 면접 질문 공유
- 프로젝트는 굵직한 걸로 정리를 잘 해두자
  - 기술 스택보단 트러블 슈팅 위주로 정리해두기
    - 단순히 기술 스택을 나열해서 정리 X
    - 프로젝트를 진행하면서 어떤 문제들이 생겼고 어떤식으로 해결을 했는지를 기록해두자.
    - 프로젝트의 내용이 면접 질문으로 이어질 수 있으니 숙지해둘 것
      - ex) http 적용 => TLS HandShaking 과정, 비대칭 키 암호화, ...

## Toss 5년차 백엔드 개발자 김효진 선배님

### 서버 개발자의 포트폴리오 만들기

- 절대 회사에서 요구하는 기술 스택들을 따로 공부할 필요가 없음
- 게시판을 만들자! => 아래와 같은 흐름으로 진행된다면 좋을 것 같아요
  - 1. 게시판의 경우 데이터가 날아가면 안되니까 in-memory DB는 쓰면 안되겠다.
    2. MySQL을 사용해볼까?
    3. 근데 만약 동시접속 유저수가 많으면 IO 감당이 안될 것 같아.
    4. Redis가 메모리에 올려서 사용해서 빠르다던데 이걸로 해보자. 대신 persistency를 유지하기 위해 AOF 옵션을 키자.
- 해당 기술 스택을 왜 선택했으며, 해당 기술 스택에 대해 얼마나 깊게 이해를 하였는가
  - 공부해야할 것은 점점 늘어난다.
    - 중요한 것은 새로운 것을 습득하는 능력과 제대로된 설계 & 개발을 할 줄 아는 사람인지를 보여주는 것!
    - 실제로 회사에서 요구하는 기술 스택을 써봤다고 뽑는게 아니라 스택이 틀리더라도 자기가 공부해왔던 기술에 대해 얼마나 이해를 하고있고 심도있게 공부했느냐가 더 중요한 것 같다.
- CS는 그냥 필수.
- 포트폴리오는 트러블 슈팅 위주로 작성하자.



### Q&A

1. 나와 잘 맞는 분야는 어떻게 찾아야 하나요?  
   => 여러가지 다양하게 해보는게 좋은 것 같다.
2. 깃허브는 어떻게 관리해야하나요? 개발자 포트폴리오는 어떻게 준비해야할지?  
   => 깃헙은 플젝 여러개 하다보면 자연스럽게 쌓이는 것 같다. 그 와중에 커밋을 어떻게 남겨야 하는지, 브랜치 전략을 어떻게 짜야할지 고민해보면 좋다.  
3. 좋은 코드는 어디서 봐야 하나요?  
   => 현재 나와 비슷한 수준의 좋은 코드를 보는게 중요하다고 생각하는데 부스트캠프, 우테코와 같은 단체의 깃헙에 가보면 취준 레벨의 좋은 코드를 구경해볼 수 있다.
4. 프론트 개발자가 되기 위해 갖추어야 할 자세, 공부 해야할 루트가 있을까요?  
   => 사실 어떤 자세나 기술 스택 보다는 기본적인 CS지식, 알고리즘 이런 기본기를 탄탄히 갖추는게 중요하다고 생각해요. 그리고 어떤 스택을 사용할 때 왜 그 기술을 사용했는지 항상 근거가 있으면 좋은 것 같아요.
5. 취준생으로 돌아간다면 어떻게 코딩 공부를 시작할건지 궁금합니다  
   => 크게 다른 방법으로 공부를 하진 않았을 것 같다. 비슷한 사람들끼리 모여서 스터디를 만들어 같이 성장하면서 공부했으면 좋을 것 같다. 하지만 가장 중요한 것은 개발자로서의 기본적인 역량을 갖추는 것이라고 생각한다.
6. 프론트 개발자에게 추천하는 책이 있다면?  
   => `You don't know JS', '리팩토링(2판, 자바스크립트로 쓰여짐)', 'http 완벽 가이드'
7. 스프링, node.js, nestjs 중 추천하는 기술이 있나요?  
   => 스프링을 제일 추천해요. 스프링이 가장 많은 회사에서 사용하고 있습니다.
8. 백엔드에게 중요한 3가지는 무엇인가요?  
   => 탄탄한 CS 지식, 하나를 파고들면 끝까지 물고 늘어지는 집요한 면, 끊임 없이 공부를 해야하는 상황을 즐기는 성격.
9. 학생들에게 현실적인 조언을 해주세요!  
   => 코테 준비를 열심히 하셔야 합니다.. 실제로 매년마다 코테의 난이도가 점점 어려워지는 것 같아요.
10. CS공부는 구체적으로 어떻게 하셨나요?  
    => 수업 열심히 듣고, 취준 때 글로 정리를 해서봤어요. 가끔 면접에서 내가 답하지 못한 질문들은 따로 모아서 다시 보면서 공부했습니다.
