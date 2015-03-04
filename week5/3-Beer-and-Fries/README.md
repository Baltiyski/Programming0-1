# Бира и пържени картофи

Мария държи известна бирария в София.

Мария е създала интересна формула, с която може да **оцени ефекта** на всяка бира или пък пържени картофи с дадена оценка - цяло число.

Когато човек си поръча дадена бира с дадени пържени картофи, общият ефект представлява произведението на оценката на бирата и пържените картофи.

Например, ако имаме бира с оценка `10` и пържени картофи с оценка `5`, то общия ефект е `5 * 10 = 50`

Мария има следния казус - ако има списък с оценките на всички бири и списък с оценките на всички пържени картофи (които по случайност са с равен брой), **то колко може да е максималната сума на комбиниран ефект между бира и пържени картофи?**

Във файл `beer_and_fries.py`, напишете функция `max_score(beer, fries)`, която:

* Взима списък от цели числа `beer`, който представлява оценката на всяка бира.
* Взима списък от цели числа `fries`, който представлява оценката на всеки вид пържени картофи.
* **Списъците `beer` и `fries` винаги ще са с равна дължина!**


Функцията трябва да върне максималната оценка, получена от някаква комбинация между `beer` и `fries`.

**Максималната оценка представлява сумата на всички оценки между бира и пържени картофи. Само че трябва да е възможно най-голямата**

## Примери

* Следната максимална оценка - `max_score([10, 11], [1, 5])` - e равна на `65`. Това става ако комбинираме `11 * 5` и го съберем с `1 * 10`
* Оценката на `max_score([5], [5])` e `25`.
* Оценката на `max_score([1000, 1010, 1020, 1030, 1040], [834, 500, -1, 0, 60])` e `1442560`.