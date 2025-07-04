<div align= "center">
<img src="https://capsule-render.vercel.app/api?type=waving&color=timeGradient&height=180&text=%20EUN-HWA's%20GitHub%20&animation=fadeIn&fontColor=000000&fontSize=60" />
</div>

##   🙌 소개
- 이름: 이은화 / Lee Eun-hwa
- 소속: 한림대학교 정보과학대학 소프트웨어학부 빅데이터 전공 /  콘텐츠IT 복수전공
- Email: eunhwa066@gmail.com
- Huggingface : _[Huggingface Profile](https://huggingface.co/EUNHWA11)_

<br>



<div style="text-align: left;">
    <h2 style="border-bottom: 1px solid #d8dee4; color: #282d33;"> 🛠️ 기술 스택 </h2> <br> 
    <div align="center">

![js](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white?style=for-the-badge&logo=JavaScript&logoColor=white) 
![js](https://img.shields.io/badge/R-276DC3?style=for-the-badge&logo=r&logoColor=white?style=for-the-badge&logo=JavaScript&logoColor=white)
![js](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white?style=for-the-badge&logo=JavaScript&logoColor=white)

![js](https://img.shields.io/badge/HTML-239120?style=for-the-badge&logo=html5&logoColor=white?style=for-the-badge&logo=JavaScript&logoColor=white)
![js](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=JavaScript&logoColor=white?style=for-the-badge&logo=JavaScript&logoColor=white)
![js](https://img.shields.io/badge/CSS-239120?&style=for-the-badge&logo=css3&logoColor=white?style=for-the-badge&logo=JavaScript&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)


</div>

    

## 📚 수강 과목
<details><summary>전공
</summary>


- 데이터베이스시스템
- 통신네트워크시스템
- 인공지능생체시스템개론
- 데이터사이언스기초
- 텍스트정보처리
- 소프트웨어특강II
- 소프트웨어특강I
- 소프트웨어공학
- 모바일프로그래밍
- 소프트웨어캡스톤디자인
- 파이썬과학프로그래밍기초
- 영상처리프로그래밍
- 머신러닝
- 컴퓨터구조
- 웹프로그래밍
- C프로그래밍
- 선형대수
- 이산구조론
- 자바프로그래밍II
- 자바프로그래밍I

</details>

<br>

## 👩🏻‍🎓 교내외 활동
- [2025.06.30~07.18] 어학연수 Utah State University, Dept. of Computer Science (Data Science)
- [2025.05] 한림대학교 디지털 경진대회 참가
- [2024.11.28] 정보과학대학 학술제 '서공제' 완성작 부문 참가
- [2024.11.28] 정보과학대학 학술제 '서공제' 데이터 분석 부분 금상(총장상)
- [2024.11.15] 강원 ICT 이노베이션스퀘어 AI 해커톤 대회 모의크라우드펀딩 5등(Amazon Web Services Korea)
- [2024.11.07] 제 7회 Hallym SW Week [아이디어 해커톤 경진대회] 은상

<br>

## 💻 프로젝트




<br>

**AI 생성 텍스트 분류 (TEAM) 🔎 _[깃허브](https://github.com/LeeEunHwaa/AI-Text-Classifier)_**
- *2025.05.13 ~ 2025.05.26*

- AI 생성 텍스트인지 사람이 쓴 텍스트인지 구분하는 모델 생성

- 기술 스택: Python
    -  BERT 토크나이저 + BERT 임베딩 + LSTM 기반 분류기
    - 한국어 기반의 KLUE BERT 토크나이저 사용
    - 경험적 하이퍼파라미터 탐색,  AdamW+ scheduler로 학습률 조절
    - 탐색된 최적의 학습방법 기반으로 성능 향상 위해 K-Fold 적용
    - 5개의 모델을 만든 후 Soft voting으로 예측 결과 도출


</br>

<br>

**음성인식 + RAG 기반 AI 튜터 (TEAM) 🔎 _[깃허브](https://github.com/LeeEunHwaa/Lecture_Tutor)_**
- *2024.11.12 ~ 2024.11.22*

- 강의 녹음본을 업로드 후 텍스트 변환 / 변환된 텍스트 기반 질의응답 시스템

- 기술 스택: Python, streamlit

  - whisper모델을 이용하여 녹음본을 텍스트 변환
  - 임베딩 모델로는 QA 작업에 특화된 'multi-qa-mpnet-base-dot-v1'을 사용
  - search_txt_file 함수는 사용자 질문과 가장 유사한 5개의 문서를 MMR(Maximum Marginal Relevance) 방식으로 검색
  - Llama3 모델 사용
  - tool_rag 함수는 통합 검색-응답 기능을 제공
      - 텍스트 파일에서 관련 정보를 검색
      - 검색 결과를 바탕으로 LLM이 한국어로 답변을 생성
      - 검색 결과가 없으면 LLM이 자체 지식을 활용하여 답변


</br>

<br>

**강원 교통사고 데이터분석 (TEAM) 🔎 _[깃허브](https://github.com/LeeEunHwaa/Traffic_Accident_Data_Analysis)_**

- *2024.11.12 ~ 2024.11.22*

    - [TAAS Open API](https://opendata.koroad.or.kr/)에서 사망교통사고정보 데이터셋 호출
    - Python을 이용해 시각화
    - R을 이용해 데이터전처리
    - Random Forest로 교통사고 피해 예측 모델 생성
    - LightGBM으로 사고 유형 예측 모델 생성
</br>

<br>

**한림대학교 챗봇 Da-Ara (TEAM) 🔎 _[깃허브](https://github.com/LeeEunHwaa/Hallym_Chat-bot)_**
- *2024.03.04 ~ 2024.05.22*

- 학생들을 위한 한림대학교 챗봇 개발

- 한림대학교에 대한 전반적인 정보 / 선배를 통해 알 수 있었던 꿀팁까지 알 수 있는 챗봇 

- 기술 스택: Python, React, MariaDB, Flask, Spring Boot

  - 학습 데이터셋 구축
  - Koalpaca-Polyglot-5.8B 모델 파인튜닝 후 Huggingface에 모델 업로드 _[허깅페이스](https://huggingface.co/EUNHWA11/koalpaca_step_8000_hallym_DaAra)_
  - 속도 향상을 위한 RAG모델 개발
  - Flask를 이용해 모델을 API로 구현


</br>









