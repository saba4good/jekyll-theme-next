---


---

<hr>
<h2 id="title-이동평균moving-averagecategories-hardwaretags-ma-moving-average">title: 이동평균(Moving Average)<br>
categories: hardware<br>
tags: MA, moving average</h2>
<p>대체 왜 안되는 거지<br>
<a href="http://blog.naver.com/PostView.nhn?blogId=swatpjs&amp;logNo=220256081171">http://blog.naver.com/PostView.nhn?blogId=swatpjs&amp;logNo=220256081171</a></p>
<p><a href="http://pepic.tistory.com/255">http://pepic.tistory.com/255</a></p>
<p><a href="https://medium.com/@igniter.yoo/%EA%B8%B0%EC%88%A0%EC%A0%81-%EB%B6%84%EC%84%9D%EC%9D%98-%EA%B8%B0%EC%B4%88-basics-of-technical-analysis-10-%EC%9D%B4%EB%8F%99-%ED%8F%89%EA%B7%A0-46b0d8ddf576">https://medium.com/@igniter.yoo/기술적-분석의-기초-basics-of-technical-analysis-10-이동-평균-46b0d8ddf576</a></p>
<p><a href="http://www.analog.com/media/en/technical-documentation/dsp-book/dsp_book_Ch15.pdf">http://www.analog.com/media/en/technical-documentation/dsp-book/dsp_book_Ch15.pdf</a></p>
<p><a href="http://www.alglib.net/time-series/moving-average-filter.php">http://www.alglib.net/time-series/moving-average-filter.php</a></p>
<p>하드웨어 신호처리중 이동평균과 관련해서 몇가지를 정리한 것이다.</p>
<p>이동평균(Moving Average, MA)이란 2개 이상의 연속된 데이터 값의 평균을 연속적으로 계산해내는 평균화 방법이다.</p>
<p><img src="http://ktword.co.kr/img_data/3665_1.JPG" alt=""></p>
<h3 id="smasimple-moving-average---단순이동평균">SMA(Simple Moving Average) - 단순이동평균</h3>
<p>이동평균의 가장 일반적인 방식으로, 가장 간단하다.<br>
단순이동평균의 수식은 아래와 같다.</p>
<p>P는 데이터값, t는 시점, n은 이동평균기간을 의미한다.</p>
<h3 id="emaexponential-moving-average---지수이동평균">EMA(Exponential Moving Average) - 지수이동평균</h3>
<p>최근의 데이터에 더 높은 가중치를 부여하여 오래된 값의 가중치를 낮추는 방법으로, 오래된 값이라도 완전히 무시하지는 않고 반영시키는 계산방법이다.</p>
<h3 id="lwalinear-weighted-average---선형-가중-평균">LWA(Linear Weighted Average) - 선형 가중 평균</h3>
<h3 id="lwma---가중이동평균">LWMA() - 가중이동평균</h3>
<h3 id="lrmalinear-regression-moving-average">LRMA(Linear Regression Moving Average)</h3>
<p>정보통신기술용어해설<br>
<a href="http://ktword.co.kr/abbr_view.php?nav=&amp;m_temp1=3665&amp;id=133">http://ktword.co.kr/abbr_view.php?nav=&amp;m_temp1=3665&amp;id=133</a></p>
<p>The Scientist and Engineer’s Guide to Digital Signal Processing Moving Average Filters<br>
<a href="http://www.analog.com/media/en/technical-documentation/dsp-book/dsp_book_Ch15.pdf">http://www.analog.com/media/en/technical-documentation/dsp-book/dsp_book_Ch15.pdf</a></p>
<p>ALGIB - Moving average filters (SMA, EMA, LRMA)<br>
<a href="http://www.alglib.net/time-series/moving-average-filter.php">http://www.alglib.net/time-series/moving-average-filter.php</a></p>

