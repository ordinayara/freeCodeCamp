---
id: 5900f4be1000cf542c50ffd1
challengeType: 5
title: 'Problem 338: Cutting Rectangular Grid Paper'
videoUrl: ''
localeTitle: 'Задача 338: Резка прямоугольной сетчатой ​​бумаги'
---

## Description
<section id="description"> Дается прямоугольный лист сетчатой ​​бумаги с целыми размерами w × h. Его сетчатый интервал равен 1. Когда мы разрезаем лист вдоль линий сетки на две части и переставляем эти части без перекрытия, мы можем создавать новые прямоугольники с различными размерами. Например, из листа с размерами 9 × 4 мы можем сделать прямоугольники размером 18 × 2, 12 × 3 и 6 × 6 путем резки и перестановки, как показано ниже: <p> Аналогично, из листа с размерами 9 × 8 мы можем создавать прямоугольники с размерами 18 × 4 и 12 × 6. </p><p> Для пары w и h пусть F (w, h) - число различных прямоугольников, которые могут быть сделаны из листа с размерами w × h. Например, F (2,1) = 0, F (2,2) = 1, F (9,4) = 3 и F (9,8) = 2. Заметим, что прямоугольники, совпадающие с исходными, не учитываются в F (w, h). Отметим также, что прямоугольники с размерами w × h и размерами h × w не считаются раздельными. </p><p> Для целого числа N пусть G (N) - сумма F (w, h) для всех пар w и h, удовлетворяющих 0 &lt;h ≤ w ≤ N. Мы можем проверить, что G (10) = 55, G (103 ) = 971745 и G (105) = 9992617687. </p><p> Найти G (1012). Дайте свой ответ по модулю 108. </p></section>

## Instructions
<section id="instructions">
</section>

## Tests
<section id='tests'>

```yml
tests:
  - text: <code>euler338()</code> должен вернуть 15614292.
    testString: 'assert.strictEqual(euler338(), 15614292, "<code>euler338()</code> should return 15614292.");'

```

</section>

## Challenge Seed
<section id='challengeSeed'>

<div id='js-seed'>

```js
function euler338() {
  // Good luck!
  return true;
}

euler338();

```

</div>



</section>

## Solution
<section id='solution'>

```js
// solution required
```
</section>
