# JIRA

## JIRA 가 뭐야?

jira는 이슈 트랙킹 시스템 중 하나로 인기 많음

요새 JIRA가 더 중요해지는 이유로는 DevOps(운영)팀과 협력이 가능해짐

개발팀과 DevOps 팀들간의 커뮤니케이션에 도움을 줌. 요새 같이 애자일이 중요해지는 시기일수록 서로간의 대화가 중요해짐



![image-20210707150244687](C:\Users\fromecha\AppData\Roaming\Typora\typora-user-images\image-20210707150244687.png)

![image-20210707150330734](C:\Users\fromecha\AppData\Roaming\Typora\typora-user-images\image-20210707150330734.png)

![image-20210707150703539](C:\Users\fromecha\AppData\Roaming\Typora\typora-user-images\image-20210707150703539.png)



## 이슈 관리

![image-20210707151055289](C:\Users\fromecha\AppData\Roaming\Typora\typora-user-images\image-20210707151055289.png)

Epic: 하나의 큰 틀?(유저 관리)

STORY: 로그인 / sub-task ?

TASK: 로그인을 하기 위해 할일(로그인창 개발, 회원가입 등등)

BUG: 말 그대로 BUG

epic > story > sub-task 



![image-20210707151423937](C:\Users\fromecha\AppData\Roaming\Typora\typora-user-images\image-20210707151423937.png)

Assign: 담당자

Status: Todo / progress / Done - 세부화할 수 있음

Components: Backend / Frontend / DevOps  



## JIRA의 언어 JQL

![image-20210707150921343](C:\Users\fromecha\AppData\Roaming\Typora\typora-user-images\image-20210707150921343.png)



### ISSUE 검색

![image-20210707151740295](C:\Users\fromecha\AppData\Roaming\Typora\typora-user-images\image-20210707151740295.png)

![image-20210707151801659](C:\Users\fromecha\AppData\Roaming\Typora\typora-user-images\image-20210707151801659.png)

![image-20210707151827989](C:\Users\fromecha\AppData\Roaming\Typora\typora-user-images\image-20210707151827989.png)

이렇게 하는게 기본 검색이고 더 고급은 Advanced 클릭하면 직접 쿼리로 검색가능



![image-20210707151938830](C:\Users\fromecha\AppData\Roaming\Typora\typora-user-images\image-20210707151938830.png)

![image-20210707151956498](C:\Users\fromecha\AppData\Roaming\Typora\typora-user-images\image-20210707151956498.png)



### JQL 연산자

![image-20210707152106297](C:\Users\fromecha\AppData\Roaming\Typora\typora-user-images\image-20210707152106297.png)

![image-20210707152224663](C:\Users\fromecha\AppData\Roaming\Typora\typora-user-images\image-20210707152224663.png)



### 날짜 (어제 이후 수정된 이슈 검색)

![image-20210707152318652](D:\github\image-20210707152318652.png)

![image-20210707152344079](C:\Users\fromecha\AppData\Roaming\Typora\typora-user-images\image-20210707152344079.png)



### 키워드

![image-20210707152357799](D:\github\image-20210707152357799.png)



### 함수

endOfday: 저녁12시

startOfDay: 아침

endofWeek: 토요일 startofWeek: 일요일

currentLogin: 지금 Login 했을때 변경된 것들

currentUser: 내가 변경한것들

![image-20210707152410477](C:\Users\fromecha\AppData\Roaming\Typora\typora-user-images\image-20210707152410477.png)

![image-20210707152646531](C:\Users\fromecha\AppData\Roaming\Typora\typora-user-images\image-20210707152646531.png)



내가 검색한 걸 저장해서 편하게 Filter로 사용할수도 있음

![image-20210707152825611](C:\Users\fromecha\AppData\Roaming\Typora\typora-user-images\image-20210707152825611.png)



아직 안끝나고 내가 담당자인거 검색(status는 인간, resolution이 쿼리검색시 판단)

![image-20210707153136896](C:\Users\fromecha\AppData\Roaming\Typora\typora-user-images\image-20210707153136896.png)



## 나만의 대쉬보드 만들어서 관리하기

![image-20210707153352662](C:\Users\fromecha\AppData\Roaming\Typora\typora-user-images\image-20210707153352662.png)

![image-20210707153405642](C:\Users\fromecha\AppData\Roaming\Typora\typora-user-images\image-20210707153405642.png)



대쉬보드 만들고 가젯 만들어서 추가하기

![image-20210707153500768](C:\Users\fromecha\AppData\Roaming\Typora\typora-user-images\image-20210707153500768.png)

Assigned to me(나의 미완료 이슈 를 나타내주는 가젯), Filter Results, heat map, pie chart, 

파이차트(만든 필터, components 별로 나눠줄수 있음)

![image-20210707153859489](C:\Users\fromecha\AppData\Roaming\Typora\typora-user-images\image-20210707153859489.png)

![image-20210707153920717](C:\Users\fromecha\AppData\Roaming\Typora\typora-user-images\image-20210707153920717.png)



### Agile Board

![image-20210707154027141](C:\Users\fromecha\AppData\Roaming\Typora\typora-user-images\image-20210707154027141.png)



![image-20210707154205134](C:\Users\fromecha\AppData\Roaming\Typora\typora-user-images\image-20210707154205134.png)

![image-20210707154315241](C:\Users\fromecha\AppData\Roaming\Typora\typora-user-images\image-20210707154315241.png)

![image-20210707164706655](JIRA.assets/image-20210707164706655.png)





스크럼보드(Backlog는 전체 할일, sprint는 기능별 할일? 이 정도로 나뉘면 될듯)는 프로젝트 이슈 기준으로 생성된 화면의 board이고 kanban 보드는 필터를 기준으로 만들어주는 board임



## 현업에서의 jira 활용

DevOps에서 JIRA는 정말 많이 쓰임

![image-20210707154504239](C:\Users\fromecha\AppData\Roaming\Typora\typora-user-images\image-20210707154504239.png)



스마트 커밋 기능? -지라를 통해 깃헙, 깃랩도 관리 가능함

![image-20210707154754319](C:\Users\fromecha\AppData\Roaming\Typora\typora-user-images\image-20210707154754319.png)



경험해봐야 할 플러그인?: 

나중에 export하면 csv나 깃허브같은데로 migration 할 수 있음

