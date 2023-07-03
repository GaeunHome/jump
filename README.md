# 數字跳躍
<div data-step="14" data-intro="<p>描述中 <i class='fa fa-clipboard'></i> 按鈕可協助你複製到剪貼簿，並貼到本機實驗。</p> <p>若題目有特殊的字元格式，那在範例輸入/輸出測資不適用複製貼上，請務必小心</p>">
<p>考慮整數數線上的一隻蚱蜢，從數字x的地方往數字y的地方跳躍(數字x小於數字y)。</p>
<p>一開始蚱蜢每次跳躍的距離為L，當它發現下次跳躍會超過y時，</p>
<p>也就是目前的位置P，再跳一次的位置P+L會大於y (P + L &gt; y)時，</p>
<p>蚱蜢會由位置P轉身往x的方向跳回去，此時蚱蜢每次往回跳的距離仍然是L。</p>
<p>當蚱蜢跳跳回起點x時，它就會停下來。</p>
<p>請根據輸入的三個正整數x, y, L，將蚱蜢經過的地方全部印出來，</p>
<p>其中一個數字輸出一行。</p>
<p>Hint：若在目前的位置P再往前跳一次會超過y，表示P + L &gt; y，也就是當 P + L &lt;= y 時，要繼續往前跳。</p>
<p>同理，在往回跳的過程中，若是目前的位置Q還沒回到起點x，則要繼續往回跳，也就是Q &gt; x時，要繼續往回跳。</p>
<h2 class="content-subhead">Sample Input 1</h2><pre><code><span class="fw-code-copy-button pure-button"><i class="fa fa-clipboard"></i></span><div id="highlighter_262198" class="syntaxhighlighter nogutter  "><table border="0" cellpadding="0" cellspacing="0"><tbody><tr><td class="code"><div class="container"><div class="line number1 index0 alt2"><code class="plain">1 13 4</code></div></div></td></tr></tbody></table></div></code></pre><h2 class="content-subhead">Sample Output 1</h2><pre><code><span class="fw-code-copy-button pure-button"><i class="fa fa-clipboard"></i></span><div id="highlighter_364323" class="syntaxhighlighter nogutter  "><table border="0" cellpadding="0" cellspacing="0"><tbody><tr><td class="code"><div class="container"><div class="line number1 index0 alt2"><code class="plain">1</code></div><div class="line number2 index1 alt1"><code class="plain">5</code></div><div class="line number3 index2 alt2"><code class="plain">9</code></div><div class="line number4 index3 alt1"><code class="plain">13</code></div><div class="line number5 index4 alt2"><code class="plain">9</code></div><div class="line number6 index5 alt1"><code class="plain">5</code></div><div class="line number7 index6 alt2"><code class="plain">1</code></div></div></td></tr></tbody></table></div></code></pre><h2 class="content-subhead">Sample Input 2</h2><pre><code><span class="fw-code-copy-button pure-button"><i class="fa fa-clipboard"></i></span><div id="highlighter_740966" class="syntaxhighlighter nogutter  "><table border="0" cellpadding="0" cellspacing="0"><tbody><tr><td class="code"><div class="container"><div class="line number1 index0 alt2"><code class="plain">1 5 2</code></div></div></td></tr></tbody></table></div></code></pre><h2 class="content-subhead">Sample Output 2</h2><pre><code><span class="fw-code-copy-button pure-button"><i class="fa fa-clipboard"></i></span><div id="highlighter_456466" class="syntaxhighlighter nogutter  "><table border="0" cellpadding="0" cellspacing="0"><tbody><tr><td class="code"><div class="container"><div class="line number1 index0 alt2"><code class="plain">1</code></div><div class="line number2 index1 alt1"><code class="plain">3</code></div><div class="line number3 index2 alt2"><code class="plain">5</code></div><div class="line number4 index3 alt1"><code class="plain">3</code></div><div class="line number5 index4 alt2"><code class="plain">1</code></div></div></td></tr></tbody></table></div></code></pre></div>
