# Метод інтервалів

<p>Будь-яку раціональну нерівність можна легко розв'язати за допомогою <b>методу інтервалів</b>. Зі схожою процедурою ми вже зустрічалися під час розв'язання рівнянь з модулями (див. розділ 8.2 <a href="http://math.ed-era.com/7/prost_rvnyannya_z_modulyami.html">Рівняння з модулями</a>). Саме таким методом ми скористалися для знаходження часу на відкриття парашуту у попередній задачі.</p>

<div class="space"><p align="center"><img align="middle" width="75%" class="image" src="../pics/142/p24_3.png"/></p></div>

<p>Графіки допоможуть нам зрозуміти сутність методу інтервалів. Наприклад, поглянемо на графік функції</p> <p align="center">$$f(x)=x^3+2x^2-5x-6$$</p>

<p>Основна думка полягає у тому, що <b>раціональна функція може змінювати знак лише у точках, в яких вона рівна нулеві.</b></p>

<p>Точки $$-3;-1;2$$ – це <b>граничні точки}, між якими графік знаходиться або вище вісі $$x$$ (зображено синім), або нижче вісі $$x$$ (зображено оранжевим).</p>

<p>Знаходження граничних точок функції, що стоїть в нерівності – це дуже важливий крок при розв’язанні раціональних нерівностей. Ці точки можна знайти розв’язавши рівняння $$f(x)=0$$.</p>

<p>Все, що залишиться – обрати необхідні інтервали в залежності від знаку нерівності.</p>

<div class="space">
<div class="alg-wrap">
<span class="alg">Алгоритм</span><b>Метод інтервалів</b>
<div class="alg-text">
<ol>
<li>Виразити нерівність у вигляді $$P(x)>0$$ або $$P(x)<0$$, де $$P(x)$$ – многочлен.</li>
<li>Розв’язати рівняння $$P(x)=0$$ знайшовши <b>граничні точки</b>.</li>
<li>Зобразити граничні точки на числовій прямій, розбивши її на інтервали.</li>
<li>Знайти знаки функції $$P(x)$$ на кожному інтервалі.</li>
<li>Обрати ті інтервали, на яких знаки $$P(x)$$ задовольняють вихідній нерівності.</li>
</ol>
</div>
</div>
</div>

<div class="space">
<div class="task-wrap">
<span class="task">Приклад</span>
<div class="task-text">
Розв’язати нерівність $$x^3+8x-16>4(3x-x^2)$$.
<p><b><i>Розв’язок</i></b>.</p>
<ol>
<li>Виразимо нерівність у вигляді $$P(x)>0$$ або $$P(x)<0$$:</li>
<p>Перетворюємо нерівність таким чином, аби праворуч залишився нуль:</p>
<div class="space"><p align="center"><img align="middle" width="70%" height="70%" class="image" src="../pics/p24_e1.png"/></p></div>
<li>Розв’яжемо рівняння $$P(x)=0$$ розклавши многочлен у лівій частині на множники:</li>
<div class="space"><p align="center"><img align="middle" width="70%" height="70%" class="image" src="../pics/p24_e2.png"/></p></div>
<p>Отже, граничні точки: $$-4;-2;2$$.</p>
<li>Зобразимо ці точки на числовій прямій.</li>
<p>В результаті утворилося чотири інтервали:</p>
<div class="space"><p align="center"><img align="middle" width="75%" class="image" src="../pics/142/p24_4.png"/></p></div>
<li>Шукаємо знаки функції $$P(x)$$ на кожному інтервалі. Для цього беремо якесь тестове значення $$x$$ з кожного інтервалу, підставляємо його у функцію та дивимося на її знак:</li>
<table>
<tr>
<td>Інтервал</td>
<td>Тестове значення</td>
<td>Підстановка у функцію</td>
<td>Знак функції</td>
</tr>
<tr>
<td>$$(-\infty;-4)$$</td>
<td>$$-5$$</td>
<td>$$P(-5)=(-5)^3+4(-5)^2-4\cdot(-5)-16=-21$$</td>
<td>$$-$$</td>
</tr>
<tr>
<td>$$(-4;-2)$$</td>
<td>$$-3$$</td>
<td>$$P(-3)=(-3)^3+4(-3)^2-4\cdot(-3)-16=5$$</td>
<td>$$+$$</td>
</tr>
<tr>
<td>$$(-2;2)$$</td>
<td>$$0$$</td>
<td>$$P(0)=(0)^3+4(0)^2-4\cdot0-16=-16$$</td>
<td>$$-$$</td>
</tr>
<tr>
<td>$$(2;\infty)$$</td>
<td>$$3$$</td>
<td>$$P(3)=(3)^3+4(3)^2-4\cdot3-16=35$$</td>
<td>$$+$$</td>
</tr>
</table>
<li>Зобразимо ці знаки на числовій прямій та оберемо лише необхідні інтервали. </li>
<div class="space"><p align="center"><img align="middle" width="75%" class="image" src="../pics/142/p24_5.png"/></p></div>
<p>Нерівність післе зведення набула вигляду $$P(x)>0$$, де $$P(x)=x^3+4x^2-4x-16$$ </p>
<p>Тому, підходять лише ті інтервали, функція $$P(x)$$ набуває додатних значень: $$(-4;-2)$$ та $$(2;\infty)$$. Таким чином $$x \in (-4;-2) \cup (2;\infty)$$.</p>
<ol>
<b>Вiдповiдь.</b> $$x \in (-4;-2) \cup (2;\infty).$$
</div>
</div>
</div>

<div class="space">
<div class="ebio-wrap">
<span class="ebio">Метод «пелюстки»</span>
<div class="ebio-text">
<p>Насправді, розв’язувати нерівності можна набагато простіше, зокрема шукати знак функції на всіх інтервалах підстановкою не потрібно. Достатньо знайти його на самому правому інтервалі.  Цей інтервал завжди має вигляд: $$(a;\infty)$$ – він необмежений справа. Для визначення знаку, можна підставити будь яке число з інтервалу.</p>
<p>Візьмемо щось велике, наприклад, <font color="#0F5180"><i>мільярд</i></font>. Підставляючи <font color="#0F5180"><i>мільярд</i></font> у функцію, одразу стає зрозуміло, який знак приймає ця функція без обчислення фактичного значення.</p>
<p>Всі решта знаків вже автоматично відомі. При переході через граничну точку <b>знак інтервалу буде змінюватись на протилежний.</b></p>
<p>У випадку, коли гранична точка є <b>кратним коренем</b>, або, іншими словами, у розкладі на множники двочлен з таким коренем стоїть у степені більше за одиницю, тобто присутній множник вигляду $$(x-x_i )^k$$ – починаємо малювати «<b>пелюстки</b>».</p>
<p>Нехай корінь має кратність $$2$$ – можна вважати що це два окремих корені між якими є інтервал, що злилися в одну точку на числовій вісі. Початок і кінець інтервалу співпадає, і він згортається у «пелюстку». При кратності $$3$$, відповідно, маємо три однакові корені між якими є два інтервали, що згортаються у дві «пелюстки», і т.д.</p>
</div>
</div>
</div>