# study-KoELECTRA_fine_tuning

> 아시아경제 교육센터 파이썬 기반 응용AI 개발자 양성과정 프로젝트

## 주제

사전 학습된 모델을 사용하여 다양한 task를 fine-tuning하는 실습 

## 팀 소개

팀명: 오프라인 팀플

팀원: 정현주, 박강인, 황유선, 이정우

## 스터디 내용

- Transformer, BERT, ELECTRA 스터디
- KoELECTRA를 기반으로 fine-tuning 실습
  1. KorSTS : 주어진 두 문장의 유사도(0~5) 측정 (https://github.com/kakaobrain/KorNLUDatasets)
  2. NSMC : 네이버 영화리뷰 감정 분석(https://github.com/e9t/nsmc)
  3. KorQuAD : 질문에의 답변 찾기(https://korquad.github.io/KorQuad%201.0/)
  4. Naver NER : 개체명(인명, 기관명, 지명 등) 추출 (https://github.com/naver/nlp-challenge)
  
참고: [KoELECTRA](https://github.com/monologg/KoELECTRA)


## KoELECTRA 기반 fine-tuning

- 각 task 별로 필요한 함수들 재구성 및 주석 작업
- transformer 4.5.0 기준으로 코드 수정

1. KoELECTRA_seq_cls_KorSTS.ipynb
2. KoELECTRA_seq_cls_nsmc_0406.ipynb
3. KoElectra_run_korquad.ipynb
4. koelectra_ner.ipynb
