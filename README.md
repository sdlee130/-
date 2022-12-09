# NLP-project
2022.2학기 자연언어처리 과목 프로젝트

### 설치 방법

- 파이썬 라이브러리 설치 방법
  ```
  pip3 install kiwipiepy
  ```
  ```
  pip3 install pymongo wikipedia koalanlp datasets thefuzz
  ```

### 의존성

- python == 3.8.10 
- koalanlp == 2.1.7
- datasets == 2.6.1
- slotminer (최신버전)

### 사용 방법

TBD

### 사용 데이터

모델 생성에 사용된 데이터는 아래와 같습니다.

- **대화 데이터(chat)**

  - ["utterances"][index]으로 named_entity의 관련 내용 접근 가능 # index는 문장의 인덱스
  
- **뉴스 데이터(news)**

  - ["sentences"][index]으로 named_entity의 관련 내용 접근 가능 # index는 문장의 인덱스
  
### 라이선스 

- TBD

### Author

- SeungDong-Lee, sdlee130@naver.com, ChungBuk National Univ(Undergraduate).
