# TestNeoX
inColab
(For 2023 Duksung Women's University's Computer Science Graduation Project)


20230731
- Colab에서 NeoX Github 패키지를 사용하려고 하였으나 실패
- GPT-neox의 코드를 직접 실행하는 대신, EleutherAI가 제공하는 사전 훈련된 모델과 tokenizer를 Hugging Face Transformers 라이브러리를 통해 사용하는 것으로 방법을 바꾸었음> 성공하여 간단한 문장 만들기에 성공
- *GPT-neo-1.3B는 GPT-NeoX 저장소에서 사용되는 모델 중 하나로, 약 13억 개의 파라미터를 가진 GPT-Neo 모델을 의미

20230809
- NeoX모델을 불완전한 임의 데이터로 학습 완료
> 확인 완료함(23.08.09)
- 수정사항
  > 질문에 대한 대답의 형태로 생성하기
  > 성능이 안좋다(학습 데이터가 너무 적음 : https://github.com/songys/Chatbot_data clone하여 다시 학습해볼것

20230810
Learn3.ipynb 작성, 전체 데이터셋 학습하려고 했는데 런타임 사용량 제한

20230814
Fewdata.ipynb 작성, 전체 데이터셋 중 3000개 정도만 학습하여 진행 시도
