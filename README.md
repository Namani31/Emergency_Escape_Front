# Evacuation Map

# 시작하기에 앞서
**절대 메인 브랜치에 바로 커밋, 푸시하지 말 것**


각자의 브랜치에 작업을 하고, 리뷰한 뒤에 최종으로 올라갈 코드를 머지 리퀘스트 할 예정임
---


## 클론하기
```
1. 브랜치를 main 으로 체크하기
2. 파란색의 [Clone] 버튼 클릭
3. "Clone with HTTPS" 의 주소를 복사하기
4. 인텔리제이 켜고, 기존 프로젝트가 열려져있다면 닫음
5. 인텔리제이 메인화면의 [VCS에서 받기] 클릭
6. URL 부분에 3번 에서 복사한 주소를 넣고, 깃랩의 아이디와 비번으로 로그인
```
---


## 커밋 메시지 작성 방법
```
1. 커밋 유형 지정
FEAT : 새로운 기능의 추가
FIX: 버그 수정
DOCS: 문서 수정
STYLE: 스타일 관련 기능(코드 포맷팅, 세미콜론 누락, 코드 자체의 변경이 없는 경우)
REFACTOR: 코드 리펙토링
TEST: 테스트 코트, 리펙토링 테스트 코드 추가
CHORE: 빌드 업무 수정, 패키지 매니저 수정(ex .gitignore 수정 같은 경우)

2. 한글로 적어도 되고, 영어로 적어도 되지만 영어로 하는게 좋음
3. 제목과 본문을 빈 행으로 분리할 것
4. 제목 행의 첫 글자는 대문자로 시작할 것
5. 제목 행에 마침표 넣지 말 것
6. 본문에 변경 한 내용과 **이유** 설명 (어떻게 X, 무엇과 왜 O)
7. 본문에 내용 적을 때, 여러 내용이 들어간다면 하이픈 (-) 사용할 것
```
---


## 해야 할 일들
```
아래의 사항이 완료될 경우, 취소선 그을 것임
1. 각자 맡은 역할을 토대로 클론 코딩 시작
2. 와이어프레임 작성
3. 데이터베이스 구축
4. CI/CD 구축
```
---


## 팀과 협업
- [ ] [새 머지 리퀘스트 생성](https://docs.gitlab.com/ee/user/project/merge_requests/creating_merge_requests.html)
- [ ] [머지 리퀘스트에서 자동으로 이슈 종료](https://docs.gitlab.com/ee/user/project/issues/managing_issues.html#closing-issues-automatically)
- [ ] [머지 리퀘스트 승인 활성화](https://docs.gitlab.com/ee/user/project/merge_requests/approvals/)
- [ ] [파이프라인 성공 시 자동 병합](https://docs.gitlab.com/ee/user/project/merge_requests/merge_when_pipeline_succeeds.html)
---


## 테스트 및 배포
GitLab 에 내장된 CI/CD 사용하기

- [ ] [GitLab CI/CD 시작하기](https://docs.gitlab.com/ee/ci/quick_start/index.html)
- [ ] [SAST를 사용하여 알려진 취약점에 대한 코드 분석](https://docs.gitlab.com/ee/user/application_security/sast/)
- [ ] [Auto Deploy를 이용하여 쿠버네티스, 아마존 EC2 또는 아마존 ECS에 배포하기](https://docs.gitlab.com/ee/topics/autodevops/requirements.html)
- [ ] [개선된 쿠버네티스 관리를 위해 pull-based 배포 사용](https://docs.gitlab.com/ee/user/clusters/agent/)
- [ ] [보호된 환경 설정](https://docs.gitlab.com/ee/ci/environments/protected_environments.html)

***
