# epidemic_worldwide
빅데이터, 인공지능 기술을 기반으로 한 질병정보 제공 시스템 개발 구축 및 운영


| 프로젝트 명 | 주최/기관 | 기간 | 역할 | 프로젝트 기여도 | Skill | 
| :---: | :---: | :---: | :---: | :---: | :--: |
| 빅데이터, 인공지능 기술을 기반으로 한 질병정보 제공 시스템 개발 구축 및 운영| 한국연구재단,상명대학교 | 2019.11 ~ 현재 | PL | 50% | Python, Java, TensorFlow, Keras|


## 1) 개발 내용
### <개요>
 * 세 가지 빅데이터를 (웹, 게놈, 이동경로) 기반으로, 질병정보 시스템을 구축하고, 데이터공유를 위한 API제공

### <개발 내용>
 * 웹  크롤러
     - 웹 데이터(News, Twitter , Google query) 수집을 위한 크롤러 생성
 * 텍스트 분류
     - 수집한 데이터의 임베딩과 필터링를 위한 텍스트 분류를 한다. 
 * 랭킹 알고리즘
     - 필터링된 단어들을 랭킹 알고리즘을 사용하여 토픽 랭킹을 생성한다. 
 * 데이터 시각화
     - 데이터 시각화를 위한 서버와 클라이언트의 연동
 
     
### <역 할>
 * 데이터 수집
     - 영어 기반의 전세계 질병관련 뉴스, 트윗, 구글 검색 쿼리를 수집한다.
     - 질병명(키워드)를 포함하는 일자별로 수집
     - NewsAPI.org, Twitter API, Google Search API를 사용한다.
     - 사용 언어 Python , 데이터 타입 JSON
  
 * 데이터 전처리
     - 수집한 데이터의 필터링을 위한 텍스트 분류 실시
     - Word2vec, Bi-LSTM을 결합한 모델
     - 사용 언어 Python, 라이브러리 TensorFlow, Keras
     
 * 데이터 처리
     - 키워드 랭킹을 생성한다
     - 알고리즘 : Tf-Idf, SMART, Inquery, CCA
     - 사용 언어 Python
 
 * 데이터 시각화
     - 홈페이지 제작을 위한 데이터 시각화
     - JavaScript와 XML을 사용하여 서버와 데이터를 요청하고, chart.js, dataTable.js를 통해 시각화를 실시
     
  
## 2) 프로젝트 구성

### <시스템 구성도 >

![시스템 구성](https://user-images.githubusercontent.com/74284500/98916660-c6340580-250e-11eb-8008-faf87cd98f9e.JPG)

### <모델 구성>
![모델 구성](https://user-images.githubusercontent.com/74284500/98916724-d8ae3f00-250e-11eb-90c8-29ef44b45e76.JPG)




### <시스템 결과>
![그림3](https://user-images.githubusercontent.com/74284500/98916893-0dba9180-250f-11eb-83bb-2962d4fb51e3.png)

![그림4](https://user-images.githubusercontent.com/74284500/98916880-0bf0ce00-250f-11eb-97c7-1eea8fd01cb2.PNG)

![그림5](https://user-images.githubusercontent.com/74284500/98916897-0eebbe80-250f-11eb-9c4d-cc382d3baed9.PNG)

