# 0729_spark

p 279

개발할때는 ubuntu로 시작하여 VS code로 들어가서 개발하면 좋음

![Untitled](0729_spark%20e567543939744458bd142d49d62cc727/Untitled.png)

  1. **해당 파일로 이동** 

![Untitled](0729_spark%20e567543939744458bd142d49d62cc727/Untitled%201.png)

  2. **데이터 가져오기**

>cp -r data.csv ../../chapter14/

![Untitled](0729_spark%20e567543939744458bd142d49d62cc727/Untitled%202.png)

왼쪽에 data.csv 파일이 확인됨

  **3.** 기존에 설치했던  pyspark 먼저 삭제하고 

>pip uninstall pyspark 

다시 설치 

 >pip install pyspark==3.2.0

*참고: 어느 가상환경에 있는지 확인할때 

>which python3

![Untitled](0729_spark%20e567543939744458bd142d49d62cc727/Untitled%203.png)

*설치된 부분 확인시 

![Untitled](0729_spark%20e567543939744458bd142d49d62cc727/Untitled%204.png)

  **4. 주피터 노트북으로 이동해서 데이터 작업**

>jupyter notebook 

하단의 오류는 신경쓰지 말기 

출력된 링크를 통해 주피터 노트북으로 접속

![Untitled](0729_spark%20e567543939744458bd142d49d62cc727/Untitled%205.png)

![Untitled](0729_spark%20e567543939744458bd142d49d62cc727/Untitled%206.png)