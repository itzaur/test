`1. Everything is done from Repository requirements and how to submit task section`

Выполнено в полном объеме **(30/30)**.

Все коммиты сделаны в соответствии с руководством, каждый коммит содержит метку времени

`2. The accordion component is centered on the screen, with equal indents on the left and right`

Выполнено в полном объеме **(10/10)**.

`3. Icons, meme texts and meme images are exist`

Выполнено в полном объеме **(5/5)**.

`4. Placement of the meme, icons and meme text are the same as in provided example gif images`

Выполнено в полном объеме **(5/5)**.

`5. Smooth change (transition) of the meme images and icons is done`

Выполнено не в полном объеме **(10/20)**.

К сожалению, отсутствует плавный переход для иконок.

Интересное решение добавления иконок через `background` и `background-position`.

Для плавной анимации появления иконки при `hover` необходимо было для `label` задать `transition: background {n}s`. Для плавного возврата иконки в исходное положение в том же `label` необходимо указать background с изначальным позиционированием, например, `background: transparent url(33.png) no-repeat 120% 50%`. Таким образом, иконка будет плавно менять свою позицию между `background-position: 120% 50%` и `background-position: 100% 50%`.

Для анимации иконок при checked состоянии нужно было добавить в `.meme input:checked + label` свойство `transition: background {n}s` (строка 146 style.css)

`6. Responsive design with three breakpoints for mobile, tablet, and desktop exist. Accordion is displayed correctly at mobile 320x568, tablet 820x1180, desktop 1920×1080.`

Выполнено в полном объеме **(10/10)**.

`7. All visual effects when the cursor is hovering over the memes, when the mouse is down on a meme, and when a meme is selected are implemented`

Выполнено не в полном объеме **(5/10)**.

При наведении курсора на картинку она не должна сворачиваться (**Note 3. clickActiveItem.gif** задания)

`8. The entire row (text, icon, and meme image) clickable`

Выполнено не в полном объеме **(2.5/5)**.

Изображения мемов некликабельны.

`9. Cursor over the memes (hover) effect only exists for devices that can support hover`

К сожалению, условие не выполнено **(0/10)**.

Hover эффект существует и для мобильных устройств,

Возможно, повлияло то, что создатели задания несколько раз меняли требования к этому условию (уточняли его), что могло запутать тех, кто готовился по первоначальному варианту задания.
В последней редакции задания была сноска на использование такого медиазапроса, как `@media (hover: hover)`. Если при использовании основного механизма ввода можно без труда навести указатель на элемент — на него отреагирует этот медиазапрос, в котором применяется значение `hover`.
Для устройств, которые не поддерживают `hover`, можно использовать медиазапрос `@media (hover: none)` (определяет, когда основной механизм ввода не может навестись или не может удобно навестись, как в большинстве мобильных телефонов и планшетов).

Вот неплохая статья на эту тему: https://www.smashingmagazine.com/2022/03/guide-hover-pointer-media-queries/

`10. The cursor when it is hovering over the rows of the accordion is changing`

Выполнено в полном объеме **(5/5)**.

`11. Only flexible dimensions are used rem, em, %, vh, vw, fr and etc... The accordion is responsive`

Выполнено не в полном объеме **(5/10)**.

Кроме `em, %` использованы `px` (например, `height: 300px` - строка 161 в style.css)

`12. All blocks/parts of the accordion are in base flow of the dom elements. All elements are not positioned with top, left, right, bottom. float is not used. The value of position is only static`

Выполнено не в полном объеме **(2.5/5)**.

Использованы абсолютное и статическое позиционирования (`position: absolute` - строка 29 style.css, `position: relative` - строки 47 и 65 style.css).
Не считаю необходимым снижать баллы за `position: relative`, но, к сожалению, есть абсолютное позиционирование, без которого в работе можно было обойтись, как этого и хотели авторы.

`13. Pseudo-elements are not used (note 1: pseudo-classes are allowed; note 2: pseudo-elements only from FontAwesome are allowed)`

Выполнено в полном объеме **(5/5)**.

`14. Initially, the first meme should be expanded`

Выполнено в полном объеме **(5/5**).

`15. Font size is changed at each device (mobile, tablet, desktop)`

Выполнено в полном объеме **(5/5)**.

## Итого: 105
