---


---

<hr>
<h2 id="title-이동평균moving-averagedate-2018-7-4-140000categories-hardwaretags-전자공학-ma-moving-average-이동평균">title: 이동평균(Moving Average)<br>
date: 2018-7-4 14:00:00<br>
categories: hardware<br>
tags: 전자공학, MA, moving average, 이동평균</h2>
<p>하드웨어 신호처리중 이동평균과 관련해서 몇가지를 정리한 것이다.</p>
<p>이동평균(Moving Average, MA)이란 2개 이상의 연속된 데이터 값의 평균을 연속적으로 계산해내는 평균화 방법으로, 아래 공식에 기초한다.</p>
<pre><code>MA = (지난 n번째 기간의 합) / (MA에서 사용된 기간의 수)
</code></pre>
<p><img src="http://ktword.co.kr/img_data/3665_1.JPG" alt=""></p>
<h3 id="smasimple-moving-average---단순이동평균">SMA(Simple Moving Average) - 단순이동평균</h3>
<p>단순이동평균의 수식은 아래와 같다.<br>
<span class="katex--display"><span class="katex-display"><span class="katex"><span class="katex-mathml"><math><semantics><mrow><mi>M</mi><mi>A</mi><mo>(</mo><mi>v</mi><mi>a</mi><mi>l</mi><mi>u</mi><mi>e</mi><mo separator="true">,</mo><mi>n</mi><mo>)</mo><mo>=</mo></mrow><annotation encoding="application/x-tex">
MA(value, n) = 
</annotation></semantics></math></span><span class="katex-html" aria-hidden="true"><span class="strut" style="height: 0.75em;"></span><span class="strut bottom" style="height: 1em; vertical-align: -0.25em;"></span><span class="base"><span class="mord mathit" style="margin-right: 0.10903em;">M</span><span class="mord mathit">A</span><span class="mopen">(</span><span class="mord mathit" style="margin-right: 0.03588em;">v</span><span class="mord mathit">a</span><span class="mord mathit" style="margin-right: 0.01968em;">l</span><span class="mord mathit">u</span><span class="mord mathit">e</span><span class="mpunct">,</span><span class="mord mathit">n</span><span class="mclose">)</span><span class="mrel">=</span></span></span></span></span></span></p>
<h3 id="emaexponential-moving-average---지수이동평균">EMA(Exponential Moving Average) - 지수이동평균</h3>
<h3 id="lwma---가중이동평균">LWMA() - 가중이동평균</h3>
<h3 id="lrmalinear-regression-moving-average">LRMA(Linear Regression Moving Average)</h3>
<p>정보통신기술용어해설<br>
<a href="http://ktword.co.kr/abbr_view.php?nav=&amp;m_temp1=3665&amp;id=133">http://ktword.co.kr/abbr_view.php?nav=&amp;m_temp1=3665&amp;id=133</a></p>
<p>The Scientist and Engineer’s Guide to Digital Signal Processing Moving Average Filters<br>
<a href="http://www.analog.com/media/en/technical-documentation/dsp-book/dsp_book_Ch15.pdf">http://www.analog.com/media/en/technical-documentation/dsp-book/dsp_book_Ch15.pdf</a></p>
<p>ALGIB - Moving average filters (SMA, EMA, LRMA)<br>
<a href="http://www.alglib.net/time-series/moving-average-filter.php">http://www.alglib.net/time-series/moving-average-filter.php</a></p>

