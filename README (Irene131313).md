`1. Everything is done from Repository requirements and how to submit task section`

Выполнено в полном объеме **(30/30)**.

Все коммиты сделаны в соответствии с руководством, каждый коммит содержит метку времени.

`2. The accordion component is centered on the screen, with equal indents on the left and right`

Выполнено в полном объеме **(10/10)**.

`3. Icons, meme texts and meme images are exist`

Выполнено в полном объеме **(5/5)**.

По данному пункту не могу снижать баллы, потому что
технически иконки содержатся в проекте, но для сценария работы аккордеона на desktop устройствах они скрыты (`opacity: 0`). А вот для мобильных устройств, где `hover` не нужен, они присутствуют только при клике.
Поэтому в других разделах, связанных с плавными переходами, это, к сожалению, уже будет учитываться.

`4. Placement of the meme, icons and meme text are the same as in provided example gif images`

Выполнено в полном объеме **(5/5)**.

Опять же, технически иконки расположены в соответствии с примером, но скрыты.

`5. Smooth change (transition) of the meme images and icons is done`

Выполнено не в полном объеме **(10/20)**.

К сожалению, отсутствует плавный переход для иконок.

Как я и говорил ранее, из-за `opacity: 0` плавный переход для иконок при наведении курсора визуально отсутствует (**Note 2. hoverOverItem.gif** задания). На мобильных устройствах эффект `hover` не нужен.

`6. Responsive design with three breakpoints for mobile, tablet, and desktop exist. Accordion is displayed correctly at mobile 320x568, tablet 820x1180, desktop 1920×1080.`

Выполнено в полном объеме **(10/10)**.

`7. All visual effects when the cursor is hovering over the memes, when the mouse is down on a meme, and when a meme is selected are implemented`

Выполнено не в полном объеме **(5/10)**.

При наведении курсора на строку аккордеона, где содержится картинка, она должна раскрываться и показывать свое содержимое (**Note 2. hoverOverItem.gif** и **Note 3. clickActiveItem.gif** задания). На устройствах, поддерживающих `hover`, этот эффект скрыт.

`8. The entire row (text, icon, and meme image) clickable`

Выполнено в полном объеме **(5/5)**.

`9. Cursor over the memes (hover) effect only exists for devices that can support hover`

К сожалению, условие не выполнено **(0/10)**.

Для desktop девайсов, которые поддерживают `hover`, нужно было воспользоваться медиазапросом `@media (hover: hover)`.
Использование же медиазапроса `@media (hover: none)` определяет, когда основной механизм ввода не может навестись или не может удобно навестись, как в большинстве мобильных телефонов и планшетов.

`10. The cursor when it is hovering over the rows of the accordion is changing`

Выполнено в полном объеме **(5/5)**.

`11. Only flexible dimensions are used rem, em, %, vh, vw, fr and etc... The accordion is responsive`

Выполнено в полном объеме **(10/10)**.

`12. All blocks/parts of the accordion are in base flow of the dom elements. All elements are not positioned with top, left, right, bottom. float is not used. The value of position is only static`

Выполнено в полном объеме **(5/5)**.

`13. Pseudo-elements are not used (note 1: pseudo-classes are allowed; note 2: pseudo-elements only from FontAwesome are allowed)`

Выполнено в полном объеме **(5/5)**.

`14. Initially, the first meme should be expanded`

Выполнено в полном объеме **(5/5**).

`15. Font size is changed at each device (mobile, tablet, desktop)`

Выполнено в полном объеме **(5/5)**.

По поводу шрифта могу посоветовать не использовать настолько маленькие размеры. На мобильных устройствах текст получился совсем не читабельный. Желательно не снижаться менее 12px.
Также контрастность и использование цвета жизненно важны для доступности. Пользователи, включая пользователей с ограниченными возможностями зрения, должны иметь возможность воспринимать содержимое страницы. Существует такое понятие как `contrast ratio`. Это разница в яркости, которая выражается в виде отношения в диапазоне от 1:1 (например, белый на белом) до 21:1 (например, черный на белом). И минимальным должна быть 4.5:1.
Вот отличный сайт для проверки `contrast ratio` и подбора оптимального цвета текста и фона, на котором он присутствует.
https://webaim.org/resources/contrastchecker/

## Итого: 115
