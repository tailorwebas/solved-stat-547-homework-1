Download Link: https://assignmentchef.com/product/solved-stat-547-homework-1
<br>
Exercise 1.1 (b) &amp; (c), Kokoszka and Riemherr (2017).

Exercise 1.4, Kokoszka and Riemherr (2017). The datasets in the book can be found here: http://www.personal.psu.edu/mlr36/Documents/KRBook_DataSets.zip

For this and the next question, consider a multivariate random variable <em>X </em>∈ R<em><sup>d</sup></em>, <em>d </em>≥ 2. Find the projection directions <em>v<sub>k</sub></em>, <em>k </em>= 1<em>,…,d </em>for the principal component analysis obtained in the following stepwise fashion:

<em>v</em><sub>1 </sub>= argmax Var(<em>l</em><sub>1</sub><sup>|</sup><em>X</em>)

k<em>l </em>k

<em>v<sub>k </sub></em>= argmax

k<em>l<sub>k</sub></em>k=1 <em>l</em><em>k</em>|<em>l</em><em>j</em>=0<em>, j</em>=1<em>,…,k</em>−1

<ol start="4">

 <li>Let <em>ξ<sub>k </sub></em>= <em>v<sub>k</sub></em><sup>|</sup>(<em>X </em>− <em>µ</em>), <em>k </em>= 1<em>,…,d</em>, where <em>µ </em>= <em>E</em>(<em>X</em>). Then

  <ul>

   <li><em>E</em>(<em>ξ<sub>k</sub></em>) = 0</li>

   <li>Var(<em>ξ<sub>k</sub></em>) = <em>λ<sub>k</sub></em></li>

   <li>Cov(<em>ξ<sub>j</sub>,ξ<sub>k</sub></em>) = <em>λ<sub>k</sub>δ<sub>jk</sub></em>, where <em>δ<sub>jk </sub></em>= 1 if <em>j </em>= <em>k </em>and 0 otherwise.</li>

  </ul></li>

</ol>

√       √

<ul>

 <li>Corr(<em>X<sub>j</sub>,ξ<sub>k</sub></em>) = <em>λ<sub>k</sub>v<sub>jk</sub>/ σ<sub>jj</sub></em>, where <em>X<sub>j </sub></em>and <em>v<sub>jk </sub></em>are the <em>j</em>th entry of <em>X </em>and <em>v<sub>j</sub></em>, respectively, and <em>σ<sub>jj </sub></em>is the <em>j</em>th diagonal entry of Σ = Cov(<em>X</em>).</li>

</ul>

<ol start="5">

 <li>Exercise 10.1, Kokoszka and Reimherr 2017</li>

 <li>Exercise 10.3, Kokoszka and Reimherr 2017</li>

 <li>Let <em>X</em>(<em>t</em>), <em>t </em>∈ [0<em>,</em>1] be a stochastic process for which the sample paths lie in <em>L</em><sup>2</sup>([0<em>,</em>1]). Show that the solution to the following problem minimizing the residual variance coincides with the projection directions in the functional principal component analysis:</li>

</ol>

<em>K </em>min<em>E</em>k<em>X </em>−<sup>X</sup>h<em>X,e<sub>k</sub></em>i<em>e<sub>k</sub></em>k<sup>2</sup><em>.</em>

<em>k</em>=1

The minimum is taken over orthonormal functions <em>e</em><sub>1</sub><em>,…,e<sub>K</sub></em>, <em>K </em>≥ 1.

1