# 2023 서대연 ChatGPT 세미나

ChatGPT를 사용하여 2가지 작업을 2번의 세미나로 진행합니다.<br>
<br>
작업1. 네이버지식인의 건강 QnA의 자료를 크롤링하여 이를 ChatGPT로 학습시키고, 건강 질문에 대하여 medical speciality를 예측하도록 합니다.  <br>
작업2. ChatGPT를 가지고 논문과 같은 의학문서에 기반한 QnA엔진을 구축합니다.  <br>
<br>
ChatGPT에 대한 소개와 이를 프로그래밍 언어로 호출하기 위한 OpenAI API를 소개합니다. 더불어 ChatGPT의 한계와 의학적 사용에서의 제약등 기반적인 것도 설명 드립니다. 프로그래밍 코드로 실제 동작하는 시스템을 구축합니다.

<br>

# 공통
- ChatGPT 소개, OpenAI API 소개 : [ChatGPT_소개.pdf](ChatGPT_소개.pdf)
- GPT 구조 : [from_DNN_to_GPT.pptx](from_DNN_to_GPT.pptx)
- 실습을 위한 환경 준비 [실습위한_환경_준비.pdf](실습위한_환경_준비.pdf)
- [OpenAI_API_사용_기초.pdf](OpenAI_API_사용_기초.pdf)
- API 단순 호출 방법 : [practice/api_call_basic.ipynb](practice/api_call_basic.ipynb)
- API 역활 설정과 호출 방법 : [practice/api_call_basic.ipynb](practice/api_call_basic.ipynb)


<br>

# 세미나 1. 네이버 지식인 의학전공 예측
- GPT 파인튜닝 방법 : [practice/how_to_fine_tuning.ipynb](practice/how_to_fine_tuning.ipynb)
- 지식인 데이터 크로울링과 학습 : [practice/task1_medical_speciality.ipynb](practice/task1_medical_speciality.ipynb)


<br>

# 세미나 2. 눈문에 근거한 QnA 엔진 구축
- 임베딩 방법 [practice/how_to_embedding.ipynb](practice/how_to_embedding.ipynb)
- 논문 기반한 QnA 구현 : [practice/task2_customer_qna_engine.ipynb](practice/task2_customer_qna_engine.ipynb)



<br>

# 참고 자료

- OpenAI 홈 : https://openai.com/
- ChatGpt 홈 : https://chat.openai.com/
- OpenAI Platform 홈 : https://platform.openai.com/
    - API 레퍼런스 : https://platform.openai.com/docs/api-reference
    - 웹에서 설명한 사용 예제 : https://platform.openai.com/examples
- OpenAI API CookBook : https://github.com/openai/openai-cookbook
