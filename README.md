# tech-interview

예상으로 나올 것 같아 정리했던 내용과, 면접에서 나온 문제를 정리한 레포입니다. 요약이 아닌 인터뷰 형식으로 정리했습니다.

아래는 문제 리스트로 되어있으며, 해당 답변은 관련.md  파일을 봐주세요!

__면접에서 실제로 나온 내용은 ⭐️ 처리 하였습니다.__ 여러번 나오면 여러번 별표를 넣겠습니당! 

##### 

## Algorithm & Data Stcture.md

1. ##### 버블 정렬에 대해 알려주세요

2. ##### 삽입 정렬에 대해 알려주세요.

3. ##### 선택 정렬에 대해 알려주세요

4. ##### 합병 정렬에 대해 설명해 주세요. 

5. ##### 퀵 정렬에 대해 설명해 주세요.

6. ##### 힙 정렬

7. ##### Stack ⭐️

8. ##### Queue ⭐️

9. ##### Heap 

10. ##### Tree

11. ##### 이진트리

12. ##### 이진탐색 ⭐️

13. ##### Stack vs Queue vs Deque

14. ##### Dictionary 와 Array에서 각각의 시간복잡도와 왜 그렇게 생각하는지 ⭐️

15. ##### python 에서는 quick 을 쓸까요 merge 를 쓸까요? ⭐️

16. ##### Tree / Graph 차이를 알려주세요 ⭐️

17. ##### BFS / DFS 쓰는 자료구조 형식? 뭐가 더 효율이 안좋은지? ⭐️

18. ##### Array vs List, 시간복잡도, 구조 차이 ⭐️



## Python

1. ##### 파이썬 제너레이터에 대해 설명해주세요

2. ##### list 와 튜플의 차이가 뭔가요?

3. ##### 파이썬의 메모리관리

4. ##### lambda 가 뭔가요?

5. ##### docstring이란 무엇인가요?

6. ##### *Args 와 *kwargs 차이 

7. ##### python 에 Main() 메서드가 있나요?

8. ##### iterable 과 iterator 의 의미와 차이를 알려주세요

9. ##### 클래스 메서드의 self 뜻



## OOP

1. ##### Class, Object, Instance의 차이점이 무엇인가요?

2. ##### Overriding 과 Overloading 의 차이점

3. ##### 객체 지향이란 무엇인가요?

4. ##### 객체 지향의 장점 단점이 뭔가요?



## Docker

해당 내용은 제 경험이 들어가서 조금 특이할 수 있습니다! ⭐️ 는 면접에서 나온 질문입니다.

1. ##### Docker 를 사용했다고 했는데 왜 사용했나요?

2. ##### docker volumn이란 무엇인가요?

3. ##### 컨테이너가 종료되면 postgresql 데이터가 날라가는데 어떻게 해결하셨나요?

4. ##### health check?

5. ##### 도커파일이란

6. ##### 다른 VM 과 Docker 의 차이가 무엇인가요?

7. ##### 도커란 무엇인가요?

8. ##### 도커의 저장 방식은 어떤 방식을 이용하나요?

9. ##### 오케스트레이션

10. ##### 도커란 가상 머신인가요? ⭐️

11. ##### 맥도 리눅스가 아닌데 맥에서 어떻게 리눅스 커널을? 열게되나요?⭐️

12. ##### 두개의 도커 컴포즈를 올렸습니다. 다른 컴포즈의 컨테이너에서 접속이 가능할까요? ⭐️



## Network

1. ##### 프로세스와 스레드의 차이를 설명해주세요. 

2. ##### 도메인 연결 과정을 설명해 주세요. ⭐️

3. ##### 대칭키와 공개키를 알려주세요. ⭐️

4. ##### HTTP 와 HTTPS 차이를 알려주세요. ⭐️

5. ##### SSL 과 TLS 차이 ⭐️

6. ##### 프로토콜에 대한 개념을 알려주세요. ⭐️

7. ##### CGI 에 대해 말해주세요.

#### 정리해야 할 내용 

```

- 장고 api 가 구성하는 방식 
> django 로 설명한댓고 drf 개념으로알려달라 코멘트받음

- runserver 도 있는데 왜 nginx 를 쓰냐(잘멋대답)

- ec2 에 nginx app 다 올렸나 (몰겟다고사과함)

- runserver 구려서 uwsgi 썻다고햇느데 뭐 질문했는데 몰라서 사과함

- 10000개 데이터 속도 저하. 어디부터 볼꺼냐
> 쿼리 속도 측정. 인덱스 사용할것
- 인덱스 사용하면 왜 빨라지냐? (사과)



rest api 
사용자가 리퀘스트 요청했을때 동작방식

nginx 를 ec2 에 올렷냐  > 맞다

uwsgi ?
```



