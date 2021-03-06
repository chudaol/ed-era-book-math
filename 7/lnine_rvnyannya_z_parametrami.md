#Лінійне рівняння з параметрами

<p>В загальному випадку лінійне рівняння $$a\cdot x=b$$ теж є рівнянням з параметрами $$a$$ i $$b$$.</p>

<p>Це рівняння задає множину лінійних рівнянь (для всіх значень параметрів).</p>

<p><i>Наприклад:</i> $$3x=5; -x=8$$.</p>

<p>Насправді це рівняння з параметрами було вже розв’язане в попередній лекції:</p>

<ul>
<li>при $$a\neq0$$, рівняння має один корінь: $$x=\dfrac{b}{a}$$;</li>
<li>при $$a=0,b\neq0$$, рівняння не має жодного кореня: $$0\cdot x=b$$;</li>
<li>при $$a=0,b=0$$, рівняння має безліч коренів: $$0\cdot x=0$$.</li>
</ul>

<p>В процесі розв’язання рівняння були розглянуті різні значення параметрів та знайдені для них корені.</p>

<p>Для лінійного рівняння «<b>контрольним</b>» є значення параметра, яке дає <b>нульовий коефіцієнт при змінній</b> (в даному прикладі це $$a=0$$).</p>

<div class="space">
<div class="task-wrap">
<span class="task">Приклад</span>
<div class="task-text">
<p>Розв’язати рівняння $$4x-n=8$$.</p>
<p>
<ul class="nav-tab" id="mytab">
    <button class="btn" data-target="#decision" data-toggle="pill">Розв’язок</button>
    <button class="btn" data-target="#answer" data-toggle="pill">Вiдповiдь</button>
    <button class="btn" data-target="#hide" data-toggle="pill">Приховати</button>
</ul>
<div id="mytab" class="tab-content">
    <div class="tab-pane" id="decision">
<p><b><i>Розв'язок.</i></b></p>
<p>Тут нічого складного, «контрольних» значень немає, просто виражаємо $$x$$:</p>
<p align="center">$$x=\dfrac{8+n}{4}.$$</p>
    </div>
    <div class="tab-pane" id="answer">
<p><b>Відповідь.</b> $$x=\dfrac{8+n}{4}.$$</p>
    </div>
    <div class="tab-pane" id="hide"></div>
</div>
</p>
</div>
</div>
</div>
<div class="space"></div>

<div class="space">
<div class="task-wrap">
<span class="task">Приклад</span>
<div class="task-text">
<p>1. Розв’язати рівняння $$(m^2-1)\cdot x=8$$.</p>
<p>
<ul class="nav-tab" id="pr1">
<button class="btn" data-target="#decision1" data-toggle="tab">Розв’язок</button>
<button class="btn" data-target="#answer1" data-toggle="tab">Вiдповiдь</button>
<button class="btn" data-target="#hide1" data-toggle="tab">Приховати</button>
</ul>

<div id="pr1" class="tab-content">
  <div class="tab-pane" id="decision1">
<p><b><i>Розв'язок.</i></b></p>
<p>Знайдемо «контрольні» значення параметра $$m$$, при яких коефіцієнт при $$x$$ стане рівним нулеві:</p>
<p align="center">$$m^2-1=0\Longleftrightarrow m^2=1\Longleftrightarrow m=\pm1.$$</p>
<p>Розв’яжемо рівняння при $$m=-1$$:</p>
<p align="center">$$((-1)^2-1)\cdot x=8\Longleftrightarrow0\cdot x=8\Longleftrightarrow x\in\emptyset.$$</p>
<p>Розв'яжемо рівняння при $$m=1$$:</p>
<p align="center">$$(1^2-1)\cdot x=8\Longleftrightarrow0\cdot x=8\Longleftrightarrow x\in\emptyset.$$</p>
<p>Розв'яжемо рівняння при $$m\neq\pm1$$:</p>
<p align="center">$$(m^2-1)\cdot x=8\Longleftrightarrow x=\dfrac{8}{m^2-1}.$$</p>
<p>Записуємо відповідь, вказавши всі корені та значення параметрів, за яких ці корені знайдені.</p>
    </div>
  <div class="tab-pane" id="answer1">
<p><b>Відповідь.</b> при $$m=\pm1$$, $$x\in\emptyset;$$</p>
<p>при $$m\neq\pm1$$, $$x=\dfrac{8}{m^2-1}.$$</p>
<p></p>
   </div>
  <div class="tab-pane" id="hide1"></div>
</div>
</p>    
<div class="space"></div>


<p>2. Розв’язати рівняння $$2(5-a)x+a^2=25$$.</p>
<p>
<ul class="nav-tab" id="pr2">
<button class="btn" data-target="#decision2" data-toggle="tab">Розв’язок</button>
<button class="btn" data-target="#answer2" data-toggle="tab">Вiдповiдь</button>
<button class="btn" data-target="#hide2" data-toggle="tab">Приховати</button>
</ul>

<div id="pr2" class="tab-content">
  <div class="tab-pane" id="decision2">
<p><b><i>Розв'язок.</i></b></p>
<p>Знайдемо «контрольні» значення параметра $$a$$, за яких коефіцієнт при $$x$$ стане рівним нулеві:</p>
<p align="center">$$2(5-a)=0\Longleftrightarrow a=5.$$</p>
<p>Розв’яжемо рівняння при $$a=5$$:</p>
<p align="center">$$0\cdot x+5^2=25\Longleftrightarrow x\in\mathbb{R}.$$</p>
<p>Розв'яжемо рівняння при $$a\neq5$$:</p>
<p align="center">$$2(5-a)x+a^2=25\Longleftrightarrow x=\dfrac{25-a^2}{2(5-a)}.$$</p>
<p>Розкладемо чисельник на множники та скоротимо на $$(5-a)$$, бо $$a\neq5$$:</p>
<p align="center">$$x=\dfrac{(5+a)(5-a)}{2(5-a)}\Longleftrightarrow x=\dfrac{5+a}{2}.$$</p>
<p>Записуємо відповідь, вказавши всі корені та значення параметрів, за яких ці корені знайдені.</p>
    </div>
  <div class="tab-pane" id="answer2">
<p><b>Відповідь.</b> при $$a=5$$, $$x\in\mathbb{R};$$</p>
<p>при $$a\neq5$$, $$x=\dfrac{5+a}{2}.$$</p>
   </div>
  <div class="tab-pane" id="hide2"></div>
</div>
</p>    
</div>
</div>
</div>
<div class="space"></div>