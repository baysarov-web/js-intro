# Task: использовать на практике основы JavaScript

## Постановка задачи

Данные задачи нужно выполнять не дольше одного часа, иначе не успеешь выполнить последующие таски. В случае, если задачи занимают больше времени, то оставь их сейчас, переходи к следующей таске и вернись к завершению после рабочего дня.

Ни в одном из заданий не разрешается копировать/вставлять решения или даже фрагменты кода. Весь код нужно писать вручную.

Названия переменных должны иметь хорошие названия, по которым будет понятно что в этих переменных находится. Разрешается пользоваться [переводчиком](https://translate.google.com/?sl=ru&tl=en&op=translate).

### Как запустить код из заданий?

Сейчас запускать код не нужно. Это простые задания, которые нужны скорее для разогрева, чем для реального опыта. Если тебе всё-таки очень хочется запустить код, к примеру чтобы проверить нет ли в нём ошибок, то ты можешь воспользоваться какой-нибудь онлайн песочницей для запуска кода: [repl.it](https://repl.it), [codepen.io](https://codepen.io/pen), [jsbin.com](https://jsbin.com/).

## Subtask 1. Переменные

Представь, что мы собрались написать игру на JavaScript. Нам нужны названия переменных, в которых мы будем хранить разного рода значения.

В данной части нужно только создавать переменные (`let`), не задавая им значения.

Перед созданием переменной вставляй [однострочный комментарий](https://learn.javascript.ru/structure#kommentarii) о том, для чего переменная создается.

Пример:
```javascript
// версия языка программирования, на которой написана игра
let programmingLanguageVersion;
```


**Задача 1.1**: Создай файл `variables.js`. В нем создай переменные, в которых мы будем хранить:

- название игры;
- описание игры
- версия игры;
- имя основного персонажа игры;
- имя разработчика игры;
- язык программирования, на которой написана игра;
- версия языка программирования, на которой написана игра;
- название карты, на которой происходят действия игры;
- сайт разработчика игры;
- язык интерфейса;

Выводить в консоль ничего не нужно.


**Задача 1.2**: 
Создай файл `wrongs.js`. В нем создай пять разных переменных [с недопустимыми названиями](https://learn.javascript.ru/variables#variable-naming).

Выводить в консоль ничего не нужно.

## Subtask 2. Числа

**Задача 2.1**: Создай файл `numbers.js`. 
Создай в нем переменные и сразу задай им значениями для следующих сущностей:
- твой возраст;
- год рождения;
- число рождения (без нолика в начале);
- количество родных братьев;
- количество родных сестер;
- количество человек в семье;
- стоимость проезда до места обучения;
- текущий год;
- курс доллара;
- курс евро;
- курс биткоина;

Помни, что числа могут иметь дробную часть.

Выводить в консоль ничего не нужно.

**Задача 2.2**: В файле из предыдущего задания создай в конце переменные, значения которых являются вычисляемыми.

Подсказка: вместо того, чтобы повторять ранее указанные значения просто используй переменные с этими значениями.
- `текущий год минус год рождения`; 
- `текущий год минус твой возраст`;
- `количество родных братьев плюс количество родных сестер`;
- `курс евро умноженный на 1000`;
- `курс доллара умноженный на 2.5`;
- `курс биткоина разделенный на 10000`;
- `стоимость проезда до места обучения разделенная на курс доллара`;
- `количество человек в семье минус количество братьев минус количество сестер`;
- `0 деленный на твой возраст`;
- `35 минус твой возраст`;

Выводить в консоль ничего не нужно.

## Subtask 3. Строки

**Задача 3.1**: В файле `strings.js` создай _константы_ со следующими значениями:

- название любимого фильма;
- название приложения, в котором проводишь больше всего времени;
- адрес статьи про JavaScript в википедии;
- весь текст "Lorem Ipsum...(до конца)"

Каждую константу выведи в консоль сразу после ее создания.

**Задача 3.2**: Создай файл `all-my-skills.js` и используй в нем:
- переменные (`let`);
- константы (`const`);
- вывод в консоль;
- арифметические операторы;
- три вида кавычек.

Не важно как именно ты их используешь и в каком количестве. Можешь придумать любой
пример использования указанных тем. Главное, чтобы в файле не было синтаксических ошибок.

**Задача 3.3**: В файле `concat.js` приведи пример [конкатенации строк](https://ru.code-basics.com/languages/javascript/lessons/string-concatenation). 
В примере должны участвовать минимум три переменные, однострочный комментарий и `console.log()`.

## Subtask 4. null, undefined, boolean

**Задача 4.1**: Создай файл `null.js`. В самом начале файла напиши многострочный 
комментарий о типе данных `null` (текст можешь скопировать к примеру [отсюда](https://developer.mozilla.org/ru/docs/Web/JavaScript/Reference/Global_Objects/null))

Ниже приведи один пример использования `null` с переменной и один пример с константой.

Выведи обе переменные в консоль.

**Задача 4.2**: Создай файл `undefined.js` и сделай всё по аналогии с предыдущим заданием.

Дополнительно приведи в пример переменную, значение которой не задали 
(напомним, её значение [будет undefined](https://doka.guide/js/undefined/)).

**Задача 4.3**: Создай файл `boolean.js` и сделай всё по аналогии с предыдущим заданием.

Приведи также пример, когда значения `true` или `false` не указываются напрямую, а вычисляются (см. [операторы сравнения](https://learn.javascript.ru/comparison)).

В конец файла перенеси следующий код и дополни его подходящими значениями (`true` или `false`).

Чтобы узнать какое значение подходит отталкивайся от названий переменных (может пригодиться [переводчик](https://translate.google.com/?sl=ru&tl=en&op=translate)).

```javascript
const iAmAStudent = 
const isSpring = 
const javaSciptIsBeauty = 
const constCanBeChanged = 
const letCanBeChanged = 
const nullIsADataType = 
const nullIsAValue = 
const iAmFromGrozny = 
```

## Subtask 5. Условия, if

**Задача 5.1**: Создай файл `conditions.js`, скопируй туда следующий код и следуй указаниям в комментариях.

При решении заданий комментарии не убирай.

Для проверки работоспособности кода можешь менять значения переменных.

⚠️ Ни в одном из заданий внутри этого файла не нужно использовать `else`.

```javascript
// задание 1
const userAge = 20;

/*
  напиши ниже условие, которое выведет в консоль текст "ты пацан" 
  если userAge меньше 35
*/
// тут твой код


//задание 2
const isAdmin = false;

/* 
  напиши ниже условие, которое выведет в консоль текст "доступ запрещен", 
  если значение константы isAdmin ложно
*/
// тут твой код


//задание 3
const password = "sherlock";
const realPassword = "holmes";

/* 
   напиши ниже условие, которое выведет в консоль текст "правильный пароль" 
   только в том случае, если значения констант password и realPassword совпадают.
*/   
// тут твой код


// задание 4
const myAge = "20";

/*
  напиши ниже условие, которое выведет в консоль текст "возраст указан верно" 
  только в том случае, если ТИПОМ переменной myAge является number.
  Тебе понадобится оператор typeof: https://learn.javascript.ru/types#type-typeof
*/
// тут твой код

// задание 5
const x = 2.7;
const y = -6;
/*
  напиши ниже условие, которое выведет в консоль "икс меньше игрик" только 
  в том случае, если значение переменной x меньше, чем значение переменной y
*/
// тут твой код
```

**Задача 5.2**: Создай файл `conditions-with-else.js`, скопируй туда следующий код и следуй указаниям в комментариях.

При решении заданий комментарии не убирай.

Для проверки работоспособности кода можешь менять значения переменных.

⚠️ Не подсматривай ни в одно из предыдущих своих решений!

```javascript
// задание 1
const userAge = 20;

/*
  напиши ниже условие, которое выведет в консоль текст "ты пацан" 
  если userAge меньше 35, иначе выведет текст "не по-пацански"
*/
// тут твой код


//задание 2
const isUser = false;

/* 
  напиши ниже условие, которое выведет в консоль текст "привет, юзер", если 
  значение константы isTrue истинно, иначе нужно вывести "не пользователь ты мне"
*/
// тут твой код


//задание 3
const password = "sherlock";
const realPassword = "holmes";

/* 
   напиши ниже условие, которое выведет в консоль текст "правильный пароль" 
   только в том случае, если значения констант password и realPassword совпадают,
   иначе необходимо вывести "неверный пароль".
*/   
// тут твой код


// задание 4 (со звездочкой)
const email = "admin@work.ru";

/*
  напиши ниже условие, которое выведет в консоль текст "неверный эмайл" если
  в значении переменной email нет символа "@", иначе выведи "ты зареган"
  Тебе понадобится метод indexOf: https://developer.mozilla.org/ru/docs/Web/JavaScript/Reference/Global_Objects/String/indexOf
*/
// тут твой код

// задание 5
const x = 2.7;
const y = -6;
/*
  напиши ниже условие, которое выведет в консоль значение переменной x, если
  оно больше значения переменной y, иначе выведи значение переменной y
*/
// тут твой код
```

## Закрываем задачу
