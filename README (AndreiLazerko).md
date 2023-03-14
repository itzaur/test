`1. Everything is done from Repository requirements and how to submit task section`

Не выполнено **(0/30)**.

**a.** Create public repository cssBayan - не выполнено (репозиторий CSS-Bayan-task forked from DrDiman/CSS-Bayan-task);

**b.** Switched to it (gh-pages) and create folder called cssBayan. Your deployed accordion will be available, e.d.: `https://${YOUR_GITHUB_NAME}.github.io/cssBayan/cssBayan/index.html` - не выполнено (папка cssBayan отсутствует);

**c.** Implement your solutions in this folder (cssBayan). There should be at least 5 commits - не выполнено (с момента выдачи задания (10.03.2023) сделаны 4 коммита);

**d.** You should call your commits accordingly to the guideline + Each your commit should contain time-stamp - не выполнено (коммиты сделаны без указания даты);

**e.** When the solution is ready - open Pull Request from gh-pages branch to main branch. Pull Request name should be equal to the task name. Description of the Pull Request should be accordingly to the guideline. Do NOT merge this Pull Request. The link to this Pull Request should be submitted to the cross check form. Pull request should contain full description - what was done and what was skipped - не выполнено (произведен merge этого Pull Request, ссылка на Pull Request не была представлена, вместо нее - ссылка на deploy).

`2. The accordion component is centered on the screen, with equal indents on the left and right`

Выполнено в полном объеме **(10/10)**.

`3. Icons, meme texts and meme images are exist`

Выполнено в полном объеме **(5/5)**.

`4. Placement of the meme, icons and meme text are the same as in provided example gif images`

Не выполнено **(0/5)**.

Расположение мемов, иконок и текста полностью не соответствуют представленному примеру.

`5. Smooth change (transition) of the meme images and icons is done`

Выполнено в полном объеме **(20/20)**.

`6. Responsive design with three breakpoints for mobile, tablet, and desktop exist. Accordion is displayed correctly at mobile 320x568, tablet 820x1180, desktop 1920×1080.`

Выполнено в полном объеме **(10/10)**.

`7. All visual effects when the cursor is hovering over the memes, when the mouse is down on a meme, and when a meme is selected are implemented`

Не выполнено **(0/10)**.

Весь функционал баяна (в данном случае слайдера) радикально отличается от техзадания.
Отсутствует изменение курсора при наведении на баян (**Note 1. commonHover.gif** задания).

При наведении курсора на новый мем картинка не разворачивается (**Note 2. hoverOverItem.gif** и **Note 3. clickActiveItem.gif** задания).

`8. The entire row (text, icon, and meme image) clickable`

Выполнено не в полном объеме **(2.5/5)**.

Кликабельны только иконки. Изображения мемов и текст некликабельны.

`9. Cursor over the memes (hover) effect only exists for devices that can support hover`

Не выполнено **(0/10)**.

Эффект наведения остался для мобильных девайсов. Медиазапросы `@media (hover: hover)` и/или `@media (hover: none)` для таких целей не использовались.

`10. The cursor when it is hovering over the rows of the accordion is changing`

Выполнено не в полном объеме **(2.5/5)**.

Изменение курсора происходит только на иконке, но не на тексте или изображении.

`11. Only flexible dimensions are used rem, em, %, vh, vw, fr and etc... The accordion is responsive`

Выполнено не в полном объеме **(5/10)**.

Кроме `em, %` использованы `px` (например, `height: 770px`, `max-width: 1100px`)

`12. All blocks/parts of the accordion are in base flow of the dom elements. All elements are not positioned with top, left, right, bottom. float is not used. The value of position is only static`

Выполнено не в полном объеме **(2.5/5)**.

Использованы статическое и абсолютное позиционирования (`position: relative` - строка 14 style.css, `position: absolute` - строки 28 и 142 style.css), позиционирование элементов с помощью `top, left, bottom` (строки 29, 30, 89, 148, 149).

`13. Pseudo-elements are not used (note 1: pseudo-classes are allowed; note 2: pseudo-elements only from FontAwesome are allowed)`

Выполнено в полном объеме **(5/5)**.

`14. Initially, the first meme should be expanded`

Выполнено в полном объеме **(5/5**).

`15. Font size is changed at each device (mobile, tablet, desktop)`

Выполнено в полном объеме **(5/5)**.

### Всего: 72.5.

Округление в пользу студента.

## Итого 73
