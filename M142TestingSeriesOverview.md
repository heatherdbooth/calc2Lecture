<!DOCTYPE html>
<html>
  <head>
    <title>Title</title>
    <meta charset="utf-8">
    <style>
      @import url(https://fonts.googleapis.com/css?family=Yanone+Kaffeesatz);
      @import url(https://fonts.googleapis.com/css?family=Droid+Serif:400,700,400italic);
      @import url(https://fonts.googleapis.com/css?family=Ubuntu+Mono:400,700,400italic);

      body { font-family: 'Droid Serif'; }
      h1, h2, h3 {
        font-family: 'Yanone Kaffeesatz';
        font-weight: normal;
      }
      .remark-code, .remark-inline-code { font-family: 'Ubuntu Mono'; }
    </style>
  </head>
  <body>
    <textarea id="source">


class:

<h4>Math 142 Dr. Booth</h4>
<h4>11.8 Strategies for Testing Series: "Obvious" Types</h4>
<table border="2" width="100%">
  <col style="width:20%">
  <col style="width:25%">
  <col style ="width:55%">
  <tr>
    <td><b><b>Test</b></b></td><td><b>Looks Like</b></td><td><b>Converges if...</b></td></tr>
  <tr>
    <td>Geometric</td><td></td><td></td><td></td></tr>
    <td>p-series</td><td></td><td></td><td></td></tr>
    <td>Alternating Series</td><td></td><td></td></tr>
    <td>Ratio Test</td><td></td><td></td><td></td></tr>
    <td>Root Test</td><td></td><td></td><td></td></tr>
  </tr>
</table>
---
<h4>Math 142</h4>
<h4>11.8 Strategies for Testing Series: "Obvious" Types</h4>
<table border="2" width="100%">
  <col style="width:20%">
  <col style="width:25%">
  <col style ="width:55%">
  <tr>
    <td><b>Test</b></td><td><b>Looks Like</b></td><td><b>Converges if...</b></td></tr>
  <tr>
    <td>Geometric</td><td>\(\sum_{n=1}^{\infty}r^n\)</td><td></td></tr>
    <td>p-series</td><td></td><td></td></tr>
    <td>Alternating Series</td><td></td><td></td></tr>
    <td>Ratio Test</td><td></td><td></td></tr>
    <td>Root Test</td><td></td><td></td></tr>
  </tr>
</table>
---
<h4>Math 142</h4>
<h4>11.8 Strategies for Testing Series: "Obvious" Types</h4>
<table border="2" width="100%">
  <col style="width:20%">
  <col style="width:25%">
  <col style ="width:55%">
  <tr>
    <td><b>Test</b></td><td><b>Looks Like</b></td><td><b>Converges if...</b></td></tr>
  <tr>
    <td>Geometric</td><td>\(\sum_{n=1}^{\infty}r^n\)</td><td>\(|r|<1\), diverges otherwise</td></tr>
    <td>p-series</td><td></td><td></td></tr>
    <td>Alternating Series</td><td></td><td></td></tr>
    <td>Ratio Test</td><td></td><td></td></tr>
    <td>Root Test</td><td></td><td></td></tr>
  </tr>
</table>

---
<h4>Math 142</h4>
<h4>11.8 Strategies for Testing Series: "Obvious" Types</h4>
<table border="2" width="100%">
  <col style="width:20%">
  <col style="width:25%">
  <col style ="width:55%">
  <tbody>
  <tr>
    <td><b>Test</b></td><td><b>Looks Like</b></td><td><b>Converges if...</b></td></tr>
  <tr>
    <td>Geometric</td><td>\(\sum_{n=1}^{\infty}r^n\)</td><td>\(|r|<1\), diverges otherwise</td></tr>
    <td>p-series</td><td>\(\sum_{n=1}^{\infty} \frac {1} {n^p}\) </td><td></td></tr>
    <td>Alternating Series</td><td></td><td></td></tr>
    <td>Ratio Test</td><td></td><td></td></tr>
    <td>Root Test</td><td></td><td></td></tr>
  </tr>
</tbody>
</table>

---
<h4>Math 142</h4>
<h4>11.8 Strategies for Testing Series: "Obvious" Types</h4>
<table border="2" width="100%">
  <col style="width:20%">
  <col style="width:25%">
  <col style ="width:55%">
  <tbody>
  <tr>
    <td><b>Test</b></td><td><b>Looks Like</b></td><td><b>Converges if...</b></td></tr>
  <tr>
    <td>Geometric</td><td>\(\sum_{n=1}^{\infty}r^n\)</td><td>\(|r|<1\), diverges otherwise</td></tr>
    <td>p-series</td><td>\(\sum_{n=1}^{\infty} \frac {1} {n^p}\) </td><td>\(p>1\), diverges otherwise</td></tr>
    <td>Alternating Series</td><td></td><td></td></tr>
    <td>Ratio Test</td><td></td><td></td></tr>
    <td>Root Test</td><td></td><td></td></tr>
  </tr>
</tbody>
</table>

---
<h4>Math 142</h4>
<h4>11.8 Strategies for Testing Series: "Obvious" Types</h4>
<table border="2" width="100%">
  <col style="width:20%">
  <col style="width:25%">
  <col style ="width:55%">
  <tbody>
  <tr>
    <td><b>Test</b></td><td><b>Looks Like</b></td><td><b>Converges if...</b></td></tr>
  <tr>
    <td>Geometric</td><td>\(\sum_{n=1}^{\infty}r^n\)</td><td>\(|r|<1\), diverges otherwise</td></tr>
    <td>p-series</td><td>\(\sum_{n=1}^{\infty} \frac {1} {n^p}\) </td><td>\(p>1\), diverges otherwise</td></tr>
    <td>Alternating Series</td><td>\(\sum_{n=1}^{\infty} (-1)^n b_n\)</td><td></td></tr>
    <td>Ratio Test</td><td></td><td></td></tr>
    <td>Root Test</td><td></td><td></td></tr>
  </tr>
</tbody>
</table>

---
<h4>Math 142</h4>
<h4>11.8 Strategies for Testing Series: "Obvious" Types</h4>
<table border="2" width="100%">
  <col style="width:20%">
  <col style="width:25%">
  <col style ="width:55%">
  <tbody>
  <tr>
    <td><b>Test</b></td><td><b>Looks Like</b></td><td><b>Converges if...</b></td></tr>
  <tr>
    <td>Geometric</td><td>\(\sum_{n=1}^{\infty}r^n\)</td><td>\(|r|<1\), diverges otherwise</td></tr>
    <td>p-series</td><td>\(\sum_{n=1}^{\infty} \frac {1} {n^p}\) </td><td>\(p>1\), diverges otherwise</td></tr>
    <td>Alternating Series</td><td>\(\sum_{n=1}^{\infty} (-1)^n b_n\)</td><td>Converges if both are true:<br> (i) \(b_{n+1}\leq b_n\) and<br> (ii) \( lim_{n\to\infty}b_n=0\) <br>Failure doesn't imply divergence.</td></tr>
    <td>Ratio Test</td><td></td><td></td></tr>
    <td>Root Test</td><td></td><td></td></tr>
  </tr>
</tbody>
</table>

---
<h4>Math 142</h4>
<h4>11.8 Strategies for Testing Series: "Obvious" Types</h4>
<table border="2" width="100%">
  <col style="width:20%">
  <col style="width:25%">
  <col style ="width:55%">
  <tbody>
  <tr>
    <td><b>Test</b></td><td><b>Looks Like</b></td><td><b>Converges if...</b></td></tr>
  <tr>
    <td>Geometric</td><td>\(\sum_{n=1}^{\infty}r^n\)</td><td>\(|r|<1\), diverges otherwise</td></tr>
    <td>p-series</td><td>\(\sum_{n=1}^{\infty} \frac {1} {n^p}\) </td><td>\(p>1\), diverges otherwise</td></tr>
    <td>Alternating Series</td><td>\(\sum_{n=1}^{\infty} (-1)^n b_n\)</td><td>Converges if both are true:<br> (i) \(b_{n+1}\leq b_n\) and<br> (ii) \( lim_{n\to\infty}b_n=0\) <br>Failure doesn't imply divergence.</td></tr>
    <td>Ratio Test</td><td>\(\sum_{n=1}^{\infty} a_n\)</td><td></td></tr>
    <td>Root Test</td><td></td><td></td></tr>
  </tr>
</tbody>
</table>

---
<h4>Math 142</h4>
<h4>11.8 Strategies for Testing Series: "Obvious" Types</h4>
<table border="2" width="100%">
  <col style="width:20%">
  <col style="width:25%">
  <col style ="width:55%">
  <tbody>
  <tr>
    <td><b>Test</b></td><td><b>Looks Like</b></td><td><b>Converges if...</b></td></tr>
  <tr>
    <td>Geometric</td><td>\(\sum_{n=1}^{\infty}r^n\)</td><td>\(|r|<1\), diverges otherwise</td></tr>
    <td>p-series</td><td>\(\sum_{n=1}^{\infty} \frac {1} {n^p}\) </td><td>\(p>1\), diverges otherwise</td></tr>
    <td>Alternating Series</td><td>\(\sum_{n=1}^{\infty} (-1)^n b_n\)</td><td>Converges if both are true:<br> (i) \(b_{n+1}\leq b_n\) and<br> (ii) \( lim_{n\to\infty}b_n=0\) <br>Failure doesn't imply divergence.</td></tr>
    <td>Ratio Test</td><td>\(\sum_{n=1}^{\infty} a_n\)</td><td>Find \(L=lim_{n\to\infty}|\frac{a_{n+1}}{a_n}|\)<br>L<1: converge<br> L> 1: diverge<br>L=1: inconclusive</td></tr>
    <td>Root Test</td><td></td><td></td></tr>
  </tr>
</tbody>
</table>
---
<h4>Math 142</h4>
<h4>11.8 Strategies for Testing Series: "Obvious" Types</h4>
<table border="2" width="100%">
  <col style="width:20%">
  <col style="width:25%">
  <col style ="width:55%">
  <tbody>
  <tr>
    <td><b>Test</b></td><td><b>Looks Like</b></td><td><b>Converges if...</b></td></tr>
  <tr>
    <td>Geometric</td><td>\(\sum_{n=1}^{\infty}r^n\)</td><td>\(|r|<1\), diverges otherwise</td></tr>
    <td>p-series</td><td>\(\sum_{n=1}^{\infty} \frac {1} {n^p}\) </td><td>\(p>1\), diverges otherwise</td></tr>
    <td>Alternating Series</td><td>\(\sum_{n=1}^{\infty} (-1)^n b_n\)</td><td>Converges if both are true:<br> (i) \(b_{n+1}\leq b_n\) and<br> (ii) \( lim_{n\to\infty}b_n=0\) <br>Failure doesn't imply divergence.</td></tr>
    <td>Ratio Test</td><td>\(\sum_{n=1}^{\infty} a_n\)</td><td>Find \(L=lim_{n\to\infty}|\frac{a_{n+1}}{a_n}|\)<br>L<1: converge<br> L> 1: diverge<br>L=1: inconclusive</td></tr>
    <td>Root Test</td><td>\(\sum_{n=1}^{\infty} (a_n)^n\)</td><td></td></tr>
  </tr>
</tbody>
</table>
---
<h4>Math 142</h4>
<h4>11.8 Strategies for Testing Series: "Obvious" Types</h4>
<table border="2" width="100%">
  <col style="width:20%">
  <col style="width:25%">
  <col style ="width:55%">
  <tbody>
  <tr>
    <td><b>Test</b></td><td><b>Looks Like</b></td><td><b>Converges if...</b></td></tr>
  <tr>
    <td>Geometric</td><td>\(\sum_{n=1}^{\infty}r^n\)</td><td>\(|r|<1\), diverges otherwise</td></tr>
    <td>p-series</td><td>\(\sum_{n=1}^{\infty} \frac {1} {n^p}\) </td><td>\(p>1\), diverges otherwise</td></tr>
    <td>Alternating Series</td><td>\(\sum_{n=1}^{\infty} (-1)^n b_n\)</td><td>Converges if both are true:<br> (i) \(b_{n+1}\leq b_n\) and<br> (ii) \( lim_{n\to\infty}b_n=0\) <br>Failure doesn't imply divergence.</td></tr>
    <td>Ratio Test</td><td>\(\sum_{n=1}^{\infty} a_n\)</td><td>Find \(L=lim_{n\to\infty}|\frac{a_{n+1}}{a_n}|\)<br>L<1: converge<br> L> 1: diverge<br>L=1: inconclusive</td></tr>
    <td>Root Test</td><td>\(\sum_{n=1}^{\infty} (a_n)^n\)</td><td>Find \(L=lim_{n\to\infty}\sqrt[n]{|a_n|}\)<br>See Ratio Test rule for L </td></tr>
  </tr>
</tbody>
</table>

</textarea>
 <script src="http://gnab.github.io/remark/downloads/remark-latest.min.js" type="text/javascript"></script>
 <script src="https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.5/MathJax.js?config=TeX-AMS_HTML&delayStartupUntil=configured" type="text/javascript"></script>
 <script type="text/javascript">
   var slideshow = remark.create();

   // Setup MathJax
   MathJax.Hub.Config({
       tex2jax: {
       skipTags: ['script', 'noscript', 'style', 'textarea', 'pre']
       }
   });

   MathJax.Hub.Configured();
 </script>
</body>
</html>
