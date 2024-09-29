# gemma_chatbot
gemma api 를 활용한 자소서 작성 챗봇 만들기

주제) 생성형 AI와 프레임워크를 활용하여 자소서를 작성해주는 생성형 챗봇을 만들고자 함
배경)



사용 프레임 워크)
- langchain
젬마는 트랜스포머 디코더 아키텍처를 기반으로 사전학습된 모델입니다.
다른 거대 자연어 모델과 달리 google의 자체 기술로 경량화 시킨 자연어 모델이다.

- RAG
  <img width="531" alt="image" src="https://github.com/user-attachments/assets/14844b8e-3a24-44a1-91bb-1e60c72548a8">
  [rag 방법론](https://proceedings.neurips.cc/paper_files/paper/2020/file/6b493230205f780e1bc26945df7481e5-Paper.pdf)

[최신 정보들을 빠르게 업데이트하기 위해서는 모델을 추가적으로 학습시키는 것(fine-tuning)이 아니라, 모델에게 정해진 데이터를 검색할 수 있도록 하는 Retrieval-Augmented Generation(RAG)를 사용하는 것이 바람직할 수 있음](https://inblog.ai/moondb/13538)

향후 발전 과제
gemma는 영어에 대해서만 사전 훈련되어 있기 때문에 영어 이외의 작업에 대해서 최적화된 성능을 보장할 수 없다는 한계가 있다.
해당 모델에 추가 이력서 관련 데이터 셋을 학습시켜 '자기 소개서 작성'이라는 주제에 부합한 챗봇이 될 수 있도록 한다.

[gemma 기술 문서](https://storage.googleapis.com/deepmind-media/gemma/gemma-report.pdf)
[gemma 캐글](https://www.kaggle.com/models/google/gemma/)

