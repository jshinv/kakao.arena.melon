# README



### 01. 데이터 정제 및 전처리

작업 : 01. Pre_text_com.ipynb

필요한 파일 : botchan.txt (SentencePieceTrainer 을 사용하기 위해 필요)



1. 정규화

   1. 특수문자 제거

2. 토큰화 (Tokenization)

   1. 문자열에서 단어로 분리시키는 단계

3. 불용어 제거 (Stop word elimination)

   1. 전치사, 관사 등 너무 많이 등장하는 단어 등 문장이나 문서의 특징을 표현하는데 불필요한 단어 제거

4. 어간 추출 (Stemming)

   1. 단어의 기본 형태를 추출하는 단계

5. 인코딩(Encoding)

   

6. 벡터화 (Representaion) - 미진행

   1. 주어진 문서나 문장을 하나의 벡터로 표현하는 단계
   2. 단어들을 모두 인덱싱(indexing)하고 주어진 문서에 존재하는 단어의 빈도수를 사용하여 문서를 표현



### 02. 인기곡 리스트업

> 각 음원별 순위는 없는 상태, 플레이 리스트에 등록된 음악들 중 인기높은 순으로 리스트업

1. 플레이 리스트에서 좋아요 높은 순으로 상위 1000개의 플레이 데이터를 추출한다

2. 1000개의 플레이 리스트를 모두 결합뒤 최빈 음원 1000개의 데이터를 추출한다

3. 최빈 음원 1000개에 포함된 곡 세부 장르 리스트를 모두 결합한뒤 최빈 50개의 장르를 추출한다

   파일명 : './data_test/top/grn_data50.csv'



---

### 관련된 글

- 데이터 전처리 : https://aileen93.tistory.com/128
- sentencepiece : https://paul-hyun.github.io/vocab-with-sentencepiece/



