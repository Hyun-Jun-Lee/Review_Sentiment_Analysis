# Review_Sentiment_Analysis

***

## Dataset

"https://movie.naver.com/movie/point/af/list.naver?&page={}"

![image](https://user-images.githubusercontent.com/76996686/145707505-e31f896a-20f5-43ac-8ace-1518b92b41d5.png)


네이버 영화 리뷰 1 ~ 1000 page crawling

<br>

## Skils

- DB : MongoDB
- Crawling : BeautifulSoup
- Preprocessing : Konlpy, Tokenizer, pad_sequences
- Modeling : LSTM

<br>

## Result 

- Accuracy

![image](https://user-images.githubusercontent.com/76996686/145710740-21d105a9-7815-4318-8234-cd1d8d65a13e.png)

<br>

- test

![image](https://user-images.githubusercontent.com/76996686/145710819-8e926f38-5c01-479c-8389-f258e2a18526.png)

## 개선점

- [ ] 추가 데이터 수집 및 크롤링 자동화
- [ ] Text 데이터 증강
- [ ] BERT
- [ ] 서비스 구현 및 배포

