#Метод інтервалів

<p>Коли рівняння має багато знаків модуля, зручно користуватись методом інтервалів. Цей метод є також базовим під час розв'язання нерівностей.</p>

<div class="space">
<div class="alg-wrap">
<span class="alg">Алгоритм</span> <b>Метод інтервалів</b>
<div class="alg-text">

<ol>
<li>Знайти, за яких значень змінної підмодульні вирази рівні нулеві.</li>
<li>Відкласти ці точки на числовій прямій, розбивши її на проміжки знакосталості.</li>
<li>Знайти знак підмодульного виразу на кожному проміжку та позначити це на числовій прямій.</li>
<li>Розв’язати рівняння на кожному проміжку, позбавляючись знаків модуля, враховуючи знаки підмодульного виразу на кожному проміжку.</li>
<li>Перевірити відповідність знайдених коренів числовому проміжку, на якому розв’язують рівняння.</li>
</ol>
</div>
</div>
</div>

<div class="space">
<div class="task-wrap">
<span class="task">Приклад</span>
<div class="task-text">
<p>Розв’язати рівняння $$|x+1|-|x+3|+|2-x|=4$$.</p>
<p>
<ul class="nav-tab" id="mytab">
    <button class="btn" data-target="#decision" data-toggle="pill">Розв’язок</button>
    <button class="btn" data-target="#answer" data-toggle="pill">Вiдповiдь</button>
    <button class="btn" data-target="#hide" data-toggle="pill">Приховати</button>
</ul>
<div id="mytab" class="tab-content">
    <div class="tab-pane" id="decision">
<p><b><i>Розв'язок.</i></b></p>
<p>Йдемо по пунктах алгоритму для методу інтервалів:</p>
<ol>
<li>Вираз $$x+1$$ рівний нулеві при $$x=-1$$, $$x+3$$ при $$x=-3$$, а $$2-x$$ при $$x=2$$.</li>
<div class="fluidMedia">
<iframe align="center" width="560" height="315" src="https://www.youtube.com/embed/ufMgLGCE2I4" frameborder="0" allowfullscreen></iframe>
</div>
<div class="popup">
</div>
<br>
<li>Відкладаємо значення $$-3$$, $$-1$$ та $$2$$ на числовій прямій.</li>
<li>Визначаємо знаки підмодульних виразів на кожному проміжку та позначаємо їх на числовій прямій (знаки стоять у тому ж порядку, що й модулі в рівнянні).</li>
<table border="0">
<tr>
<td>$$x\in (-\infty;-3)$$</td>
<td>$$x \in[-3;-1)$$</td>
<td>$$x\in [-1;2]$$</td>
<td>$$x\in (2;+\infty)$$</td>
</tr>
<tr>
<td>$$x+1<0$$,</td>
<td>$$x+1<0$$,</td>
<td>$$x+1>0$$,</td>
<td>$$x+1>0$$,</td>
</tr>
<tr>
<td>$$x+3<0$$,</td>
<td>$$x+3>0$$,</td>
<td>$$x+3>0$$,</td>
<td>$$x+3>0$$,</td>
</tr>
<tr>
<td>$$2-x>0$$;</td>
<td>$$2-x>0$$;</td>
<td>$$2-x>0$$;</td>
<td>$$2-x<0$$.</td>
</tr>
</table>
<li><p>Розв’язуємо рівняння на чотирьох інтервалах, позбавляючись знаків модуля, та перевіряємо відповідність коренів інтервалу:</p>
<ul>
<li><p>$$x\in (-\infty;-3)$$</p>
<p>Розкриваємо знаки модуля:</p>
<p align="center">$$-(x+1)-(-(x+3))+(2-x)=4\Longleftrightarrow-x+4=4\Longleftrightarrow x=0$$</p>
<p>Але $$x=0\notin(-\infty;-3)$$ — розв’язок лежить не на інтервалі, що розглядаємо, тому $$x\in \emptyset$$ на даному інтервалі.</p></li>
<li><p>$$x \in[-3;-1)$$</p>
<p>Розкриваємо знаки модуля:</p>
<p align="center">$$-(x+1)-(x+3)+(2-x)=4\Longleftrightarrow-3x-2=4\Longleftrightarrow x=-2.$$</p>
<p>$$x=-2\in[-3;-1)$$, тому є коренем.</p></li>
<li><p>$$x\in [-1;2]$$</p>
<p>Розкриваємо знаки модуля:</p>
<p align="center">$$(x+1)-(x+3)+(2-x)=4\Longleftrightarrow-x=4\Longleftrightarrow x=-4.$$</p>
<p>Але $$x=-4\notin[-1;2]$$ – розв’язок лежить не на інтервалі, що розглядаємо, тому $$x\in \emptyset$$ на даному інтервалі.</p></li>
<li><p>$$x\in (2;+\infty)$$</p>
<p>Розкриваємо знаки модуля:</p>
<p align="center">$$(x+1)-(x+3)-(2-x)=4\Longleftrightarrow x-4=4\Longleftrightarrow x=8.$$</p>
<p>$$x=8\in(2;+\infty),$$ тому є коренем.</p></li>
</ul></li>
</ol>
    </div>
    <div class="tab-pane" id="answer">
<p><b>Відповідь.</b> $$\{-2; 8\}$$.</p>
    </div>
    <div class="tab-pane" id="hide"></div>
</div>
</p>
</div>
</div>
</div>
<div class="space"></div>

<quiz correctLabel="correct" incorrectLabel="incorrect" checkLabel="check">
    <question text="">
        <p>На якому числовому проміжку всі підмодульні вирази рівняння $$|2x+2|+|x−1|−|5+x|−|2−x|=10$$ є невід’ємними?</p>
        <answer> $$(-\infty;-5)$$</answer>
        <answer correct> $$(1;2]$$</answer>
        <answer> $$(-1;1]$$</answer>
        <answer> $$(2;\infty)$$</answer>
        </question>
</quiz>