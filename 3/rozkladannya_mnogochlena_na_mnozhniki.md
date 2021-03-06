# Розкладання многочлена на множники
<ol>
<li><p><b>Винесення спільного множника за дужки</b>. Якщо кілька доданків многочлена містять одну й ту саму змінну, то її можна винести за дужки у найменшому степені.</p></li>
<div class="space"></div>
<p><i>Наприклад:</i> $$21a^3 b-7ab^2+4ab+15a^5 b^7=ab\cdot(21a^2-7b+4+15a^4 b^6).$$</p>
<div class="space"></div>
<li><p><b>Метод групування</b>. В цьому методі використовується винесення многочлена за дужки. Для цього групують доданки так, щоб після винесення спільних множників, у кожній групі в дужках лишився один і той самий многочлен, який після цього виносять за дужки.</p></li>
<div class="space"></div>
<p><i>Наприклад:</i> $$12a^2+3ab-4b^3-16ab^2=(12a^2-16ab^2 )+(3ab-4b^3 )=4a(3a-4b^2)+$$<br>$$+b(3a-4b^2)=(3a-4b^2 )(4a+b).$$</p>
</ol>
<div class="space">
</div>

<div class="space">
<div class="alg-wrap">
<span class="alg">Алгоритм</span> <b>Видiлення повного квадрата з тричлена</b>
<div class="alg-text">
<p>Вирази вигляду $$Ax^{2n}+Bx^n y^m+Cy^{2m}$$, що не є квадратами двочлена, можна розкласти на множники виділивши повний квадрат з тричлена.</p>
<p>Для цього потрібно:</p>
<p>а) записати один з доданків у вигляді квадрату деякого виразу $$X$$;</p>
<p>б) записати другий доданок у вигляді $$2XY$$, звідки знайти вираз $$Y$$;</p>
<p>в) додати та відняти одночасно квадрат виразу $$Y$$;</p>
<p>г) застосувати формулу квадрату суми чи різниці.</p>
</div>
</div>
</div>

<div class="space">
<div class="task-wrap">
<span class="task">Приклад</span>
<div class="task-text">
<p>Розкласти на множники тричлен $$16x^6+40x^3 y-11y^2$$.</p>


<p>
<ul class="nav-tab" id="mytab">
<button class="btn" data-target="#decision" data-toggle="pill">Розв’язок</button>
<button class="btn" data-target="#answer" data-toggle="pill">Вiдповiдь</button>
<button class="btn" data-target="#hide" data-toggle="pill">Приховати</button>
</ul>

<div id="mytab" class="tab-content">
  <div class="tab-pane" id="decision">
<p><b><i>Розв’язок.</i> </b> </p>
<p>а) Представляємо перший доданок у вигляді квадрату деякого виразу $$X$$: $$ 16x^6=$$<br>$$=(4x^3 )^2,$$ тоді $$X=4x^3.$$</p>
<p>б) Шукаємо вираз $$Y$$ з другого доданку, представивши його у вигляді $$2XY$$: $$40x^3 y=2\cdot(4x^3 )\cdot(5y),$$ тоді $$Y=5y$$.</p>
<p>в-г) Додаємо та віднімаємо $$Y^2=(5y)^2=25y^2,$$ після чого групуємо доданки, щоб утворити повний квадрат та скористатись формулою різниці квадратів:</p>
<p>$$16x^6 + 40x^3 y - 11y^2 + 25y^2 - 25y^2 = (16x^6 + 40x^3 y + 25y^2) - 11y^2 - 25y^2 = $$<br>$$ = (4x^3 + 5y)^2 - 36y^2 = (4x^3 + 5y - 6y)(4x^3 + 5y + 6y) = (4x^3 - y)(4x^3 + 11y).$$</p>
  </div>
  <div class="tab-pane" id="answer"><p><b>Вiдповiдь.</b> $$(4x^3-y)(4x^3+11y).$$</p></div>
  <div class="tab-pane" id="hide"></div>
</div>
</p>
</div>
</div>
</div> 

<ol start="3">
<li><b>Розкладання на множники квадратного тричлена</b>. Кожний квадратний тричлен $$ax^2+bx+c$$ може бути розкладений на множники першого степеня наступним чином:</li>
<div class="space"></div>
<p align="center">$$ax^2+bx+c=a(x-x_1)(x-x_2),$$</p>
<div class="space"></div>
<p>де $$x_{1,2}$$ – корені квадратного тричлена (корені рівняння  $$ax^2+bx+c=0$$).</p>
<p>Вони визначаються за формулами</p>
<div class="space"></div>
<p align="center">$$x_{1,2} = - \dfrac{b \pm \sqrt{b^2 - 4ac}}{2a}.$$</p>
</ol>

<div class="space">
</div>

<div class="task-wrap">
<span class="task">Приклад</span>
<div class="task-text">
<p>Розкласти многочлен $$3x^2-12x-15$$ на множники.</p>

<p>
<ul class="nav-tab" id="mytab1">
<button class="btn" data-target="#decision1" data-toggle="pill">Розв’язок</button>
<button class="btn" data-target="#answer1" data-toggle="pill">Вiдповiдь</button>
<button class="btn" data-target="#hide1" data-toggle="pill">Приховати</button>
</ul>

<div id="mytab1" class="tab-content">
  <div class="tab-pane" id="decision1">
<p><b><i>Розв’язок.</i> </b> </p>
<p>Знайдемо корені рівняння $$3x^2-12x-15=0:$$</p>
<p align="center">$$x_{1,2} = - \dfrac{-12 \pm \sqrt{(-12)^2 -4\cdot3\cdot(-15)}}{2\cdot 3} = \dfrac{12 \mp \sqrt{324}}{6} = \dfrac{12 \mp 18}{6} \Rightarrow \begin{cases} x_1 = -1; \\ x_2 = 5. \end{cases}.$$</p>
<p>Отже, скориставшись формулою розкладу маємо: $$3x^2-12x-15=3(x+1)(x-5)$$.</p>

  </div>
  <div class="tab-pane" id="answer1"><p><b>Вiдповiдь.</b> $$3(x+1)(x-5).$$</p></div>
  <div class="tab-pane" id="hide1"></div>
</div>
</p>

</div>
</div>

<div class="space"></div>

<quiz correctLabel="correct" incorrectLabel="incorrect" checkLabel="check">
    <question text="">
        <p>Винесіть спільний множник за дужки: $$2\cdot a^2\cdot b + 6\cdot a\cdot b^2 + 4\cdot a\cdot b\cdot x$$</p>
        <answer> $$6ab(\dfrac{a}{3}+b+x)$$</answer>
        <answer> $$a^2 \cdot b(2+3a \cdot b + 4x)$$</answer>
        <answer correct> $$2ab(a+3b+2x)$$</answer>
    </question>
</quiz>