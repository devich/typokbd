# Типографська розкладка клавіатури для Windows {#hero-title}
[![Unlicensed](https://img.shields.io/badge/license-free-gold)](#)
[![GitHub Release](https://img.shields.io/github/v/release/devich/Typography-Keyboard)](https://github.com/devich/Typography-Keyboard/releases/latest)


## Що це і для кого
Українська типографська розкладка для Windows містить основні типографські символи (лапки, тире, коротке тире, типографський апостроф, знаки валют тощо) і літери інших слов’янських кириличних абеток.

Якщо ви журналіст або публіцист і хочете писати красиві тексти; айтівець або smm-ник; тримаєте кілька кириличних розкладок; або ви просто педантичний естет :metal: — ця розкладка для вас.

Розкладка дозволяє легко вводити додаткові типографські символи через клавішу `Alt`, а також позбавляє необхідності тримати ще одну розкладку (наприклад, російську чи білоруську) в разі якщо вам потрібні літери інших слов’янських мов.


## Чіт-шит
[![Українська типографська розкладка](assets/ukrainian-layout.png)](#)

Символи, що позначені :green_circle: зеленим — вводяться через `Alt` + `відповідна клавіша`, :large_blue_circle: синім — через `Alt` + `Shift` + `відповідна клавіша`.

__Зверніть увагу:__ додаткові символи вводяться через `правий Alt` (він же `Alt Gr`). Windows не дозволяє вводити альтернативні символи через `лівий Alt`, що може бути незручним для деяких користувачів — тому нижче є інструкція з додавання такої можливості.


## Особливості розкладки
- Швидке введення типографських знаків (довге і коротке тире `— –`, лапки `« » „ “`, правильний апостроф у вигляді краплі `’`, знаки градуса `°`, параграфа `§`, гривні та інших валют `₴ $ ¢ € £`, маркери списків `• ▪`, часто вживані математичні символи `× ⋅ ÷ − ± ≠ ≈` та інше).
- Можливість введення літер інших кириличних абеток `ы ъ э ў` тощо. __Позбудьтеся нарешті зоопарку розкладок__, достатньо англійської та типографської української на всі випадки!
- Інтуїтивне розташування альтернативних символів.
- За замовчанням використовується типографський апостроф замість звичайного машинописного (який можна ввести через `правий Alt`).
- Швидкий доступ до спецсимволів (на кшталт `@ # $ & [ ]` та інших) без необхідності перемикатися на англійську розкладку.
- Можливість ставити стрілочки `← ↑ → ↓`.


## Як встановити
- Завантажте останню версію файлу `Ukr-Typo-Keyboard-Win.zip` зі [сторінки релізів](https://github.com/devich/Typography-Keyboard/releases/latest).
- Розпакуйте архів і запустіть `setup.exe`.
- Оберіть в настройках мови та регіону Windows розкладку `Ukrainian (Typography)` для української мови.
- Видаліть більше непотрібні інші розкладки.


## Як зробити лівий Alt клавішею для вводу альтернативних символів
Архів `Ukr-Typo-Keyboard-Win.zip` зі [сторінки релізів](https://github.com/devich/Typography-Keyboard/releases/latest) містить в собі два `.reg` файли: `Alts-Swap.reg` і `Alts-Restore-Defaults.reg`.

- Щоб поміняти місцями функції правого та лівого `Alt` — запустіть `Alts-Swap.reg`.
- Щоб повернути все як і було — запустіть `Alts-Restore-Defaults.reg`.
- Після внесення змін до реєстру перезавантажте Windows.

Альтернативний метод: можна скористатися застосунком [SharpKeys](https://github.com/randyrants/sharpkeys) — він дозволяє змінювати функції будь-яких клавіш у Windows через графічний інтерфейс.