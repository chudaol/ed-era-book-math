#Теорема Безу та схема Горнера

<p>При розв’язанні цілих рівнянь вищих степенів знадобиться знання теореми Безу та схеми Горнера для ділення многочлена на двочлен.</p>

<div class="space">
<div class="ebio-wrap">
<span class="ebio">Теорема Безу</span>
<div class="ebio-text">
Остача від ділення многочлена $$P(x)$$ на двочлен $$x - a$$ рівна $$P(a)$$.
</div>
</div>
</div>

<div class="fluidMedia">
<iframe align="center" width="560" height="315" src="https://www.youtube.com/embed/qUREL_CCrOI" frameborder="0" allowfullscreen></iframe>
</div>
<div class="popup">
</div>

<p><div class="space">
<div class="ebio-wrap">
<span class="ebio">Доведення</span>
<div class="ebio-text">
<p>Нехай остача від ділення многочлена $$P(x)$$ на двочлен рівна $$r$$, а частка — многочлен $$Q(x)$$. Тоді можна записати:</p>
<p align="center">$$P(x) = Q(x)\cdot(x - a) + r.$$</p>
<p>Підставивши $$x = a$$ у многочлен $$P$$, маємо:</p>
<p align="center">$$P(a) = Q(a)\cdot(a - a) + r = r,$$</p>
<p>це доводить теорему.</p>
</div>
</div>
</div>
</p>

<div class="space">
<div class="alg-wrap">
<span class="alg">Алгоритм</span> <b>Схема Горнера</b>
<div class="alg-text">

<ol>
<li>Записати таблицю з двох рядків.</li>
<li>У верхньому записують всі коефіцієнти многочлена $$P(x)$$ (повинен бути записаний у стандартному вигляді).</li>
<li>Старший коефіцієнт дублюється в нижній рядок, а зліва від нього записують $$a$$.</li>
<li>Нижній рядок заповнюють за таким правилом: крайнє справа число множиться на $$a$$ та додається до числа, що стоїть над порожньою клітинкою.</li>
<li>Отриманий результат записують у порожню клітинку.</li>
</ol>
</div>
</div>
</div>

<p>Продемонструємо процес складання таблиці на попередньому прикладі: знайти остачу від ділення многочлена $$P(x)=x^5 - 3x^3 + x - 7$$ на $$x + 2.$$</p>

<p>Записуємо таблицю з двох рядків. У верхньому записуємо всі коефіцієнти многочлена $$P(x)$$. Старший коефіцієнт дублюється в нижній рядок, а зліва від нього записуємо $$a = -2$$:</p>

<div class="space"><p align="center"><img align="middle" width="85%" class="image" src="../pics/132_p1.png"/></p></div>

<p>Тепер заповнюємо порожні клітинки нижнього рядка:</p>

<ul>
<li>перша: $$(-2)\cdot$$<span color="#faaf00">$$1$$</span> + <span color="#0F5181">$$0$$</span> $$=$$ <span color="#faaf00">$$-2$$</span>,</li>
<li>друга: $$(-2)\cdot($$<span color="#faaf00">$$-2$$</span>$$) + ($$<span color="#0f5181">$$-3$$</span>$$) = $$<span color="#faaf00">$$1$$</span>,</li>
<li>третя: $$(-2)\cdot$$<span color="#faaf00">$$1$$</span> $$+$$ <span color="#0f5181">$$0$$</span> $$=$$ <span color="#faaf00">$$-2$$</span>,</li>
<li>четверта: $$(-2)\cdot($$<span color="#faaf00">$$-2$$</span>$$) + $$<span color="#0f5181">$$1$$</span>$$ = $$<span color="#faaf00">$$5$$</span>,</li>
<li>п’ята: $$(-2)\cdot$$<span color="#faaf00">$$5$$</span>$$ + ($$<span color="#0f5181">$$-7$$</span>$$) = -17$$.</li>
</ul>

<div class="space"><p align="center"><img align="middle" width="85%" class="image" src="../pics/132_p2.png"/></p></div>

<p>Як бачимо, можна тоді записати</p> 

<p align="center">$$x^5 - 3x^3 + x - 7 = (x + 2)(x^4 - 2x^3 +x^2 - 2x + 5) - 17.$$</p>

<quiz correctLabel="correct" incorrectLabel="incorrect" checkLabel="check">
    <question text="">
        <p>Якою буде остача від ділення $$x^4+3x^3-4x^2-10$$ на $$x-2$$?</p>
        <answer> $$-4$$</answer>
        <answer> $$-2$$</answer>
        <answer correct> $$14$$</answer>
        <answer> $$11$$</answer>
        <explanation>
        Перший член частки $$x^3$$, тоді маємо:
        $$5x^3-4x^2-10.$$<br>
        Другий член частки $$5x^2$$, тоді маємо:
        $$6x^2-10.$$<br>
        Третій член частки $$6x$$, тоді маємо:
        $$12x-10.$$<br>
        Четвертий член частки $$12$$, тоді маємо остачу: $$14.$$
        </explanation>
        </question>
</quiz>
