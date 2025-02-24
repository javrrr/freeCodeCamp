---
id: bd7168d8c242eddfaeb5bd13
title: Візуалізуйте дані за допомогою стовпчикової діаграми
challengeType: 3
forumTopicId: 301464
dashedName: visualize-data-with-a-bar-chart
---

# --description--

**Мета:** створити застосунок, функціонально схожий до цього: <a href="https://bar-chart.freecodecamp.rocks" target="_blank" rel="noopener noreferrer nofollow">https://bar-chart.freecodecamp.rocks</a>.

Виконайте історію користувача та пройдіть тести. Використовуйте необхідні вам бібліотеки або API. Оформте за власним стилем.

Ви можете скористатися HTML, JavaScript, CSS та бібліотекою візуалізації, що базується на D3 svg. Для тестів потрібно згенерувати осі, використовуючи властивість осі D3, що автоматично створює відмітки вздовж осі. Ці відмітки потрібні для проходження D3 тестів, тому що їх положення використовуються для визначення вирівнювання зображених елементів. Ви можете знайти інформацію про генерування осей тут <https://github.com/d3/d3/blob/master/API.md#axes-d3-axis>. Необхідні (невіртуальні) DOM-елементи запитуються під час кожного тесту. Якщи ви використовуєте фронтенд-фреймворк (як-от, наприклад, Vue), результати тестів можуть бути неточними для динамічного контенту. Ми сподіваємося скоро їх налагодити, однак наразі ці фреймворки не підтримуються для проєктів D3.

**User Story #1:** Моя діаграма повинна мати назву з відповідним `id="title"`.

**User Story #2:** Моя діаграма повинна мати елемент осі X `g` з відповідним `id="x-axis"`.

**User Story #3:** Моя діаграма повинна мати елемент осі Y `g` з відповідним `id="y-axis"`.

**User Story #4:** Обидві осі повинні містити по кілька позначок, кожна з відповідним `class="tick"`.

**User Story #5:** Моя діаграма повинна мати елемент `rect` для кожної точки даних з відповідним `class="bar"`, що відображає дані.

**User Story #6:** Each `.bar` should have the properties `data-date` and `data-gdp` containing `date` and `GDP` values.

**User Story #7:** The `.bar` elements' `data-date` properties should match the order of the provided data.

**User Story #8:** The `.bar` elements' `data-gdp` properties should match the order of the provided data.

**User Story #9:** Each `.bar` element's height should accurately represent the data's corresponding `GDP`.

**User Story #10:** The `data-date` attribute and its corresponding `.bar` element should align with the corresponding value on the x-axis.

**User Story #11:** The `data-gdp` attribute and its corresponding `.bar` element should align with the corresponding value on the y-axis.

**User Story #12:** Я можу навести курсор на область і побачити спливаючу підказку з відповідним `id="tooltip"`, що відображає більше інформації про область.

**User Story #13:** Моя спливаюча підказка повинна мати показник `data-date`, що відповідає `data-date` активної області.

Тут ви знайдете набір даних, необхідний для виконання цього проєкту: `https://raw.githubusercontent.com/freeCodeCamp/ProjectReferenceData/master/GDP-data.json`

Ви можете створити свій проєкт, <a href='https://codepen.io/pen?template=MJjpwO' target="_blank" rel="noopener noreferrer nofollow">використовуючи цей шаблон CodePen</a> і натиснувши `Save`. Або ж ви можете використати це CDN-посилання, щоб провести тести в будь-якому середовищі: `https://cdn.freecodecamp.org/testable-projects-fcc/v1/bundle.js`.

Щойно впораєтеся, прикріпіть URL-адресу із пройденими тестами до проєкту, над яким працюєте.

# --solutions--

```js
// solution required
```
