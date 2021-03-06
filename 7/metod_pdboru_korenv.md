#Метод підбору коренів

<div class="space">
<div class="ebio-wrap">
<span class="ebio">Теорема</span>
<div class="ebio-text">
Якщо рівняння з цілими кофіцієнтами $$P_n(x) = 0$$ має цілі корені ($$\mathbb{Z}$$-корені), то вони є дільниками вільного доданка $$a_n$$ цього рівняння.
</div>
</div>
</div>

<div class="space">
<div class="ebio-wrap">
<span class="ebio">Доведення</span>
<div class="ebio-text">
<p>Нехай $$x = a$$ — цілий корінь рівняння $$a_0x^n + a_1x^{n - 1} + a_2x^{n - 2} + \dots + a_{n - 2}x^2 + a_{n - 1}x + a_n = 0, де a_0,a_1,\dots,a_n$$ — цілі числа. Тоді виконується рівність:</p>
<p align="center">$$a_0a^n + a_1a^{n - 1} + a_2a^{n - 2} + \dots + a_{n - 2}a^2 + a_{n - 1}a + a_n = 0.$$</p>
<p>Виразимо вільний доданок $$a_n$$:</p> 
<p align="center">$$a_n = -a_0a^n - a_1a^{n - 1} - a_2a^{n - 2} - \dots - a_{n - 2}a^2 - a_{n - 1}a,$$</p>
<p align="center">$$a_n= -a\cdot(a_0a^{n - 1} + a_1a^{n - 2} + a_2a^{n - 3} + \dots + a_{n - 2}a + a_{n - 1}).$$</p>
<p>З останньої рівності випливає, що ціле число $$a$$ є дільником цілого вільного доданка $$a_n$$.</p>
</div>
</div>
</div>

<div class="space">
<div class="alg-wrap">
<span class="alg">Алгоритм</span> <b>Розв'язання рівнянь вищих степенів $$P_n(x)=0$$</b>
<div class="alg-text">
<ol>
<li>Знайти множину дільників вільного доданка $$a_n$$.</li>
<li>За т. Безу перевірити, чи є коренями дільники $$a_n$$.</li>
<li>Якщо знайдений корінь $$x = x_1$$, розділити за схемою Горнера чи методом кута многочлен $$P_n(x)$$ на двочлен $$x - x_1$$. Часткою буде многочлен степеня $$n - 1$$: $$Q_{n - 1}(x)$$.</li>
<li>Шукати корені рівняння $$Q_{n-1}(x) = 0$$, користуючись п.1-4, які теж є коренями вихідного рівняння (якщо такі є).</li>
</ol>
</div>
</div>
</div>

<div class="space">
<div class="task-wrap">
<span class="task">Приклад</span>
<div class="task-text">
<p>Розв’язати рівняння $$2x^4 + 11x^3 - 2x^2 - 41x - 30 = 0$$.</p>

<p>
<ul class="nav-tab" id="mytab">
    <button class="btn" data-target="#decision" data-toggle="pill">Розв’язок</button>
    <button class="btn" data-target="#answer" data-toggle="pill">Вiдповiдь</button>
    <button class="btn" data-target="#hide" data-toggle="pill">Приховати</button>
</ul>
<div id="mytab" class="tab-content">
    <div class="tab-pane" id="decision">
<p><b><i>Розв'язок.</i></b></p>
<ol>
<li>Знаходимо множину дільників вільного доданка $$-30$$ : $$\pm1$$, $$\pm2$$, $$\pm3$$, $$\pm5$$, $$\pm6$$, $$\pm10$$, $$\pm15$$, $$\pm30$$.</li>
<div class="fluidMedia">
<iframe align="center" width="560" height="315" src="https://www.youtube.com/embed/9NsQmA7E6Z8" frameborder="0" allowfullscreen></iframe>
</div>
<div class="popup">
</div>
<br>
<li><p>Перевіряємо, чи є коренями знайдені дільники за схемою Горнера (працюємо завжди з верхнім рядком):</p>
<table>
<tr>
<td></td>
<td>$$2$$</td>
<td>$$11$$</td>
<td>$$-2$$</td>
<td>$$-41$$</td>
<td>$$-30$$</td>
<td></td>
</tr>
<tr>
<td>$$1$$</td>
<td>$$2$$</td>
<td>$$13$$</td>
<td>$$11$$</td>
<td>$$-30$$</td>
<td>$$-60$$</td>
<td>не є коренем</td>
</tr>
<tr>
<td>$$-1$$</td>
<td>$$2$$</td>
<td>$$9$$</td>
<td>$$-11$$</td>
<td>$$-30$$</td>
<td>$$0$$</td>
<td>є коренем</td>
</tr>
<tr>
<td>$$2$$</td>
<td>$$2$$</td>
<td>$$15$$</td>
<td>$$28$$</td>
<td>$$15$$</td>
<td>$$0$$</td>
<td>є коренем</td>
</tr>
<tr>
<td>$$-2$$</td>
<td>$$2$$</td>
<td>$$7$$</td>
<td>$$-16$$</td>
<td>$$-9$$</td>
<td>$$-12$$</td>
<td>не є коренем</td>
</tr>
</table>
<p>Інші дільники перевіряти немає сенсу — вже два корені відомі, тому після ділення отримаємо квадратне рівняння, яке легко розв’язується.</p>
<p>Отже, $$x_1=-1$$  та $$x_2=2$$ — корені рівняння.</p>
<p>Тому далі необхідно розділити многочлен $$P(x)$$ на $$(x+1)(x-2)$$.</p>
</li>
<li><p>З таблиці вище дістаємо, що  частка від ділення многочлена $$P(x)=2x^4 + 11x^3 - 2x^2 - 41x - 30$$ на $$(x + 1)$$:</p>
<p align="center">$$2x^3 + 9x^2 - 11x - 30.$$</p>
<p>Маємо $$P(x)=(x + 1)(2x^3 + 9x^2 - 11x - 30)$$. Залишилось розділити на $$(x - 2)$$.</p></li>
<li><p>Ділимо многочлен $$2x^3 + 9x^2 - 11x - 30$$ за схемою Горнера на $$(x - 2)$$:</p>
<table>
<tr>
<td></td>
<td>$$2$$</td>
<td>$$9$$</td>
<td>$$-11$$</td>
<td>$$-30$$</td>
</tr>
<tr>
<td>$$2$$</td>
<td>$$2$$</td>
<td>$$13$$</td>
<td>$$15$$</td>
<td>$$0$$</td>
</tr>
</table>
<p>Частка від ділення: $$2x^2 + 13x + 15$$.</p>
<p>Маємо $$P(x)=(x + 1)(x - 2)(2x^2 + 13x + 15)$$.</p>
</li>
<li><p>Розв’яжемо квадратне рівняння $$2x^2 + 13x + 15$$.</p>
<p>Шукаємо дискримінант: $$D=(13)^2 - 4\cdot2\cdot15 = 49 > 0$$, отже, рівняння має два дійсних корені:</p>
<p align="center">$$x_3 = \dfrac{-13 + \sqrt{49}}{2\cdot2} = -1,5; x_4 = \dfrac{-13 - \sqrt{49}}{2\cdot2} = -5.$$</p>
<p>Таким чином всі корені знайдені, а многочлен $$P(x)$$ можна записати як:</p>
<p align="center">$$P(x)=(x+1)(x-2)(x+1,5)(x+5).$$</p></li>
</ol>
    </div>
    <div class="tab-pane" id="answer"> <p><b>Відповідь.</b> $$\{-5; -1,5; -1; 2\}$$.</p>
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
        <p>Яке з наведених чисел НЕ МОЖЕ бути коренем рівняння $$x^3-6x^2+11x-6$$?</p>
        <answer correct> $$0$$</answer>
        <answer> $$1$$</answer>
        <answer> $$2$$</answer>
        <answer> $$3$$</answer>
        </question>
</quiz>