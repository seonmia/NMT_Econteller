# Neural Machine Translation_(Econteller - Eng-Kor NEWS Translation for MZ generation)
Using Transformer models for translate English economic NEWS into Korean and apply style transfer 

## Goorm Project #3
구름 AI 기술 자연어처리 전문가 양성 과정 4기 프로젝트 

## 실행 환경
* 구글 코랩 Pro+ 에서 테스트했습니다.
## 설치 패키지
* !pip install flask_ngrok
* !pip install pyngrok==4.1.1
* !pip install transformers
* !pip install sentencepiece
* !pip install torch
* !pip install kss
* !pip install nltk
* !pip install bert_score

## ngrok에서 가입후 토큰을 받아온다.
* 주소 : https://ngrok.com/
* !ngrok authtoken "토큰" # 쌍따옴표를 남긴다.

## 학습모델은 팀 프로젝트 드라이브에 올림, 위치는 다음과 같이 세팅한다.
![model파일경로](https://user-images.githubusercontent.com/37838776/185463610-3ebc501f-e290-419f-b8e0-ee0ac918f5fc.png)

## Usage
* server.py 코드를 복사 후 코랩에 붙여넣기 해서 실행한다.
