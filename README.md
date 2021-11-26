# Information Retrieval Project
## - Naver Movie Review Sentiment Analysis

### 정보검색 프로젝트로 진행한 영화 추천 서비스
- 프로젝트 설명 : 영화 이름을 입력하면 유사한 영화를 추천
- 프로젝트 구조 : 2단계를 거쳐서 최종 추천
  - 1차 추천 : 영화 장르, 감독, 줄거리등 비감정적인 요소만으로 추천
  - 2차 추천 : 1단계를 거쳐서 고른 유사한 영화중 리뷰데이터(감정요소)를 기반으로 추천
  - 최종 추천 : 최종적으로 유사한 top 10 영화를 추천

[한국어 불용어 리스트](https://github.com/nooblette/SentimentAnalysis/blob/main/K_Stopword.txt) : The list of Korean idioms that I use often.  
[추가 리뷰 데이터 크롤링]
  
  
--------------------------------------------------------------------------------
## *Sources*  
https://github.com/e9t/nsmc  
https://www.ranks.nl/stopwords/korean  
https://github.com/e9t/nsmc/blob/master/raw/10001.json  
https://hyemin-kim.github.io/2020/08/29/E-Python-TextMining-2/  
https://rfriend.tistory.com/475  
https://www.ranks.nl/stopwords/korean  
https://shakeratos.tistory.com/18  
https://github.com/e9t/nsmc/blob/master/code/crawl_ratings.py  
