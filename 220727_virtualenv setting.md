# 220727 가상환경설치

# 가상환경설치

  1. C드라이브에 새폴더 만들기

![Untitled](220727%20%E1%84%80%E1%85%A1%E1%84%89%E1%85%A1%E1%86%BC%E1%84%92%E1%85%AA%E1%86%AB%E1%84%80%E1%85%A7%E1%86%BC%E1%84%89%E1%85%A5%E1%86%AF%E1%84%8E%E1%85%B5%20cffdfc7ef2a04c4085104e2540765e54/Untitled.png)

  2. WSL 접속

![Untitled](220727%20%E1%84%80%E1%85%A1%E1%84%89%E1%85%A1%E1%86%BC%E1%84%92%E1%85%AA%E1%86%AB%E1%84%80%E1%85%A7%E1%86%BC%E1%84%89%E1%85%A5%E1%86%AF%E1%84%8E%E1%85%B5%20cffdfc7ef2a04c4085104e2540765e54/Untitled%201.png)

추후 리눅스 기본 명령어 공부하기

   3. 

![Untitled](220727%20%E1%84%80%E1%85%A1%E1%84%89%E1%85%A1%E1%86%BC%E1%84%92%E1%85%AA%E1%86%AB%E1%84%80%E1%85%A7%E1%86%BC%E1%84%89%E1%85%A5%E1%86%AF%E1%84%8E%E1%85%B5%20cffdfc7ef2a04c4085104e2540765e54/Untitled%202.png)

code . 입력/실행하여 VS code로 접속

  4. 터미널 열면 기존에 보던 화면과 조금 다름

![Untitled](220727%20%E1%84%80%E1%85%A1%E1%84%89%E1%85%A1%E1%86%BC%E1%84%92%E1%85%AA%E1%86%AB%E1%84%80%E1%85%A7%E1%86%BC%E1%84%89%E1%85%A5%E1%86%AF%E1%84%8E%E1%85%B5%20cffdfc7ef2a04c4085104e2540765e54/Untitled%203.png)

**본격적으로 가상환경 설치**

   5. 

>sudo apt install python3-pip

![Untitled](220727%20%E1%84%80%E1%85%A1%E1%84%89%E1%85%A1%E1%86%BC%E1%84%92%E1%85%AA%E1%86%AB%E1%84%80%E1%85%A7%E1%86%BC%E1%84%89%E1%85%A5%E1%86%AF%E1%84%8E%E1%85%B5%20cffdfc7ef2a04c4085104e2540765e54/Untitled%204.png)

에러있다면 

  6. 

>sudo apt-get update

![Untitled](220727%20%E1%84%80%E1%85%A1%E1%84%89%E1%85%A1%E1%86%BC%E1%84%92%E1%85%AA%E1%86%AB%E1%84%80%E1%85%A7%E1%86%BC%E1%84%89%E1%85%A5%E1%86%AF%E1%84%8E%E1%85%B5%20cffdfc7ef2a04c4085104e2540765e54/Untitled%205.png)

실행 완료 후 다시 입력하고 실행하면 잘된다

다시 하단 명령 입력 

>sudo apt install python3-pip

![Untitled](220727%20%E1%84%80%E1%85%A1%E1%84%89%E1%85%A1%E1%86%BC%E1%84%92%E1%85%AA%E1%86%AB%E1%84%80%E1%85%A7%E1%86%BC%E1%84%89%E1%85%A5%E1%86%AF%E1%84%8E%E1%85%B5%20cffdfc7ef2a04c4085104e2540765e54/Untitled%206.png)

설치 완료 되면  

  7. 

>sudo pip3 install virtualenv

![Untitled](220727%20%E1%84%80%E1%85%A1%E1%84%89%E1%85%A1%E1%86%BC%E1%84%92%E1%85%AA%E1%86%AB%E1%84%80%E1%85%A7%E1%86%BC%E1%84%89%E1%85%A5%E1%86%AF%E1%84%8E%E1%85%B5%20cffdfc7ef2a04c4085104e2540765e54/Untitled%207.png)

  8. 

>virtualenv venv

>source venv/bin/activate

![Untitled](220727%20%E1%84%80%E1%85%A1%E1%84%89%E1%85%A1%E1%86%BC%E1%84%92%E1%85%AA%E1%86%AB%E1%84%80%E1%85%A7%E1%86%BC%E1%84%89%E1%85%A5%E1%86%AF%E1%84%8E%E1%85%B5%20cffdfc7ef2a04c4085104e2540765e54/Untitled%208.png)

  9. **환경변수 설정**

>pwd 로 현재경로 확인

/mnt/c/dataEngineering 기억하기

![Untitled](220727%20%E1%84%80%E1%85%A1%E1%84%89%E1%85%A1%E1%86%BC%E1%84%92%E1%85%AA%E1%86%AB%E1%84%80%E1%85%A7%E1%86%BC%E1%84%89%E1%85%A5%E1%86%AF%E1%84%8E%E1%85%B5%20cffdfc7ef2a04c4085104e2540765e54/Untitled%209.png)

*평상시에 vi편집기 연습 많이 할 것 

  10. 

>**vi ~/.bashrc**

![Untitled](220727%20%E1%84%80%E1%85%A1%E1%84%89%E1%85%A1%E1%86%BC%E1%84%92%E1%85%AA%E1%86%AB%E1%84%80%E1%85%A7%E1%86%BC%E1%84%89%E1%85%A5%E1%86%AF%E1%84%8E%E1%85%B5%20cffdfc7ef2a04c4085104e2540765e54/Untitled%2010.png)

맨 하단에 가서  **i 누르고** **키보드로** 공란가서 엔터 (마우스로는 안됨)

  11. 

“# 환경변수설정” 

export AIRFLOW_HOME=/mnt/c/dataEngineering

입력하기  / 참고) 입력한 사항을 지우려면 d 두번 누르면 없어짐

![Untitled](220727%20%E1%84%80%E1%85%A1%E1%84%89%E1%85%A1%E1%86%BC%E1%84%92%E1%85%AA%E1%86%AB%E1%84%80%E1%85%A7%E1%86%BC%E1%84%89%E1%85%A5%E1%86%AF%E1%84%8E%E1%85%B5%20cffdfc7ef2a04c4085104e2540765e54/Untitled%2011.png)

  12. 

esc 누르면 나간다  +  “- - INSERT - -” 없어짐

![Untitled](220727%20%E1%84%80%E1%85%A1%E1%84%89%E1%85%A1%E1%86%BC%E1%84%92%E1%85%AA%E1%86%AB%E1%84%80%E1%85%A7%E1%86%BC%E1%84%89%E1%85%A5%E1%86%AF%E1%84%8E%E1%85%B5%20cffdfc7ef2a04c4085104e2540765e54/Untitled%2012.png)

그다음 shift 세미콜론 하고

**:wq!** 입력> 엔터 (**저장하고 나가기** )

참고) **:q!** 입력> 엔터 하면 **저장 안하고 나가기** 

        

  13.

>**source ~/.bashrc** 하면 **반영**됨

실제 반영되었는지 확인하려면 

>echo $AIRFLOW_HOME 실행하면 경로확인됨

![Untitled](220727%20%E1%84%80%E1%85%A1%E1%84%89%E1%85%A1%E1%86%BC%E1%84%92%E1%85%AA%E1%86%AB%E1%84%80%E1%85%A7%E1%86%BC%E1%84%89%E1%85%A5%E1%86%AF%E1%84%8E%E1%85%B5%20cffdfc7ef2a04c4085104e2540765e54/Untitled%2013.png)

가상환경 설치완료됨