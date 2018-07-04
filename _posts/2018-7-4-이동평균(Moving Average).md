---
title: 이동평균(Moving Average)
categories: MISC
tags: MA, moving average
---

대체 왜 안되는 거지
http://blog.naver.com/PostView.nhn?blogId=swatpjs&logNo=220256081171

http://pepic.tistory.com/255

https://medium.com/@igniter.yoo/%EA%B8%B0%EC%88%A0%EC%A0%81-%EB%B6%84%EC%84%9D%EC%9D%98-%EA%B8%B0%EC%B4%88-basics-of-technical-analysis-10-%EC%9D%B4%EB%8F%99-%ED%8F%89%EA%B7%A0-46b0d8ddf576

http://www.analog.com/media/en/technical-documentation/dsp-book/dsp_book_Ch15.pdf

http://www.alglib.net/time-series/moving-average-filter.php

하드웨어 신호처리중 이동평균과 관련해서 몇가지를 정리한 것이다.

이동평균(Moving Average, MA)이란 2개 이상의 연속된 데이터 값의 평균을 연속적으로 계산해내는 평균화 방법이다.

![](http://ktword.co.kr/img_data/3665_1.JPG)



### SMA(Simple Moving Average) - 단순이동평균
이동평균의 가장 일반적인 방식으로, 가장 간단하다.
단순이동평균의 수식은 아래와 같다.

$$
MA(P, n) = \frac{P_t + P_t-1 + P_t-2 + ... +P_{t-n}}{n}
$$

P는 데이터값, t는 시점, n은 이동평균기간을 의미한다.

### EMA(Exponential Moving Average) - 지수이동평균
최근의 데이터에 더 높은 가중치를 부여하여 오래된 값의 가중치를 낮추는 방법으로, 오래된 값이라도 완전히 무시하지는 않고 반영시키는 계산방법이다.

### LWA(Linear Weighted Average) - 선형 가중 평균

### LWMA() - 가중이동평균

### LRMA(Linear Regression Moving Average)




정보통신기술용어해설
http://ktword.co.kr/abbr_view.php?nav=&m_temp1=3665&id=133

The Scientist and Engineer's Guide to Digital Signal Processing Moving Average Filters
http://www.analog.com/media/en/technical-documentation/dsp-book/dsp_book_Ch15.pdf

ALGIB - Moving average filters (SMA, EMA, LRMA)
http://www.alglib.net/time-series/moving-average-filter.php
