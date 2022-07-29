# 0727 패키지 설치

**패키지 설치** 

    1. 먼저 VS code에서 가상환경에 접속하고

>source venv/bin/activate

# **아파치 에어플로 설치하기**

p25

 

     2. 아파치 에어플로를 설치하는 명령 입력후 엔터

>pip3 install ‘apache-airflow[postgres,slack,celery]’

시간이 조금 소요됨

![Untitled](0727%20%E1%84%91%E1%85%A2%E1%84%8F%E1%85%B5%E1%84%8C%E1%85%B5%20%E1%84%89%E1%85%A5%E1%86%AF%E1%84%8E%E1%85%B5%209c5007d1f5dc4db1a19efde38d48a47d/Untitled.png)

       3. 

>airflow db init 명령으로 데이터 베이스를 초기화한다

![Untitled](0727%20%E1%84%91%E1%85%A2%E1%84%8F%E1%85%B5%E1%84%8C%E1%85%B5%20%E1%84%89%E1%85%A5%E1%86%AF%E1%84%8E%E1%85%B5%209c5007d1f5dc4db1a19efde38d48a47d/Untitled%201.png)

    4. 1

>airflow webserver 

만 입력하면 기본포트 8080으로 실행된다

![Untitled](0727%20%E1%84%91%E1%85%A2%E1%84%8F%E1%85%B5%E1%84%8C%E1%85%B5%20%E1%84%89%E1%85%A5%E1%86%AF%E1%84%8E%E1%85%B5%209c5007d1f5dc4db1a19efde38d48a47d/Untitled%202.png)

참고)  >airflow webserver -p 8081 로 진입할수도 있음

커서가 안보일때

cltr+c 하면 입력할 수 있도록 커서 나옴

  4. 2 

>`airflow users create --username airflow --password airflow --firstname evan --lastname airflow --role Admin --email your_email@some.com` 입력 후 엔터

>airflow webserver -p 8081 로 다시 실행하고

웹 주소창에  [http://localhost:8081/](http://localhost:8081/)에 접속하면 에어플로의 GUI를 볼 수 있다

![Untitled](0727%20%E1%84%91%E1%85%A2%E1%84%8F%E1%85%B5%E1%84%8C%E1%85%B5%20%E1%84%89%E1%85%A5%E1%86%AF%E1%84%8E%E1%85%B5%209c5007d1f5dc4db1a19efde38d48a47d/Untitled%203.png)

아이디airflow , 비번 airflow

![Untitled](0727%20%E1%84%91%E1%85%A2%E1%84%8F%E1%85%B5%E1%84%8C%E1%85%B5%20%E1%84%89%E1%85%A5%E1%86%AF%E1%84%8E%E1%85%B5%209c5007d1f5dc4db1a19efde38d48a47d/Untitled%204.png)