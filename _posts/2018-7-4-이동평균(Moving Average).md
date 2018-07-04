---
title: 이동평균(Moving Average)
categories: MISC
tags: MA, moving average
---

http://blog.naver.com/PostView.nhn?blogId=swatpjs&logNo=220256081171

http://pepic.tistory.com/255

https://medium.com/@igniter.yoo/%EA%B8%B0%EC%88%A0%EC%A0%81-%EB%B6%84%EC%84%9D%EC%9D%98-%EA%B8%B0%EC%B4%88-basics-of-technical-analysis-10-%EC%9D%B4%EB%8F%99-%ED%8F%89%EA%B7%A0-46b0d8ddf576

http://www.analog.com/media/en/technical-documentation/dsp-book/dsp_book_Ch15.pdf

http://www.alglib.net/time-series/moving-average-filter.php

하드웨어 신호처리중 이동평균과 관련해서 몇가지를 정리한 것이다.

이동평균(Moving Average, MA)이란 2개 이상의 연속된 데이터 값의 평균을 연속적으로 계산해내는 평균화 방법이다.

![](http://ktword.co.kr/img_data/3665_1.JPG)

일반적으로 처음부터 끝까지, 전 구간을 대상으로 평균을 내기에는 정확도가 떨어지므로, 평균을 산출할 데이터의 개수(지난 2시간의 데이터, 최신 데이터 200개···)를 정한 후, 그 데이터로만 평균을 낸다.


### SMA(Simple Moving Average) - 단순이동평균
이동평균의 가장 간단한 방식으로, 주어진 구간에서의 평균을 산출하는 방식이다


### LWMA() - 가중이동평균
SMA의 둔한 반응속도를 보완할 수 있는 계산방법으로, 오래된 값이라도 완전히 무시하지는 않고 반영시키나, 가중치를 낮춘다.

예를 들어 10개의 데이터를 대상으로 EMA를 구한다면, 가장 최근의 데이터에는 10을 곱해주고, 그 다음 데이터에는 9를 곱해주는 식으로 합을 구해서 데이터의 개수로 나눠준다.


### EMA(Exponential Moving Average) - 지수이동평균
최근의 데이터에 더 높은 가중치를 부여하여 오래된 값의 가중치를 낮추는 방법으로, LWMA보다 더 민감하다. 지수가 2인 이동평균은 DEMA, 지수가 3인 이동평균은 TEMA라고 부른다.

$$
EMA(value, n) = \alpha \times price_i + (1 - \alpha) \times EMA(price, n)_{i-1}
$$

$$
\alpha = \frac{2}{n+1}
$$

P는 데이터값, t는 시점, n은 이동평균기간을 의미한다.

### LWA(Linear Weighted Average) - 선형 가중 평균
이동 평균의 특정 기간의 종가의 합을 구한 후, 그 데이터 지점의 위치를 곱하고, 기간의 합으로 나누는 방식이다.

### LRMA(Linear Regression Moving Average)




정보통신기술용어해설
http://ktword.co.kr/abbr_view.php?nav=&m_temp1=3665&id=133

The Scientist and Engineer's Guide to Digital Signal Processing Moving Average Filters
http://www.analog.com/media/en/technical-documentation/dsp-book/dsp_book_Ch15.pdf

ALGIB - Moving average filters (SMA, EMA, LRMA)
http://www.alglib.net/time-series/moving-average-filter.php
