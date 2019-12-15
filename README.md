# 주제:다음 영화 리뷰 분석
## 데이터
![영화](https://user-images.githubusercontent.com/58911465/70865669-538b7480-1fa3-11ea-8f40-9dd25a1c38b6.PNG)

  1. 데이터가 하루에도 수십번씩 갱신된다.
  2. 1에서 30페이지까지 데이터 수집
  3. 페이지당 10개의 리뷰가 있다.
## 과정
  1. 홈페이지에서 데이터를 크롤링한다.
  2. 1페이지에서 30페이지까지의 리뷰를 가져온다.
  3. 데이터를 정제한다.
  4. 정제한 데이터로 단어의 빈도수를 구한다.
## 결과
정제한 단어

![영화단어](https://user-images.githubusercontent.com/58911465/70865837-5ab38200-1fa5-11ea-9072-9ee5c77e42f1.PNG)

### 워드클라우드
R프로그램에서 만들 수 있다.

![wordcloud](https://user-images.githubusercontent.com/58911465/70865817-2f309780-1fa5-11ea-891b-31f52af45d75.png)

### pie chart
R프로그램에서 만들 수 있다.

![piechart](https://user-images.githubusercontent.com/58911465/70865829-47a0b200-1fa5-11ea-885d-b1c634b3b4a4.png)

영화 리뷰이므로 영화라는 단어를 제외하면 노래와 관련된 영화이므로 노래라는 단어가 가장 많다.
그 외에도 디즈니, 겨울이라는 단어가 들어간 것을 보면 디즈니에서 만든 겨울 영화라는 것을 알 수 있다.
