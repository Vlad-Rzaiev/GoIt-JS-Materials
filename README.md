# GoIt-JS-Materials

# Заняття 28.10.2024

Посилання на репозиторій: <br>
https://github.com/Olexiy-repin/js-112/tree/module-01-lesson-01 <br>

Таблиця з пріорітетністю операторів: <br>
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Operator_precedence#table <br>
Корисні розширення: <br>
https://marketplace.visualstudio.com/items?itemName=xabikos.JavaScriptSnippets (корисні скорочення, наприклад якщо ввести clg + tab, то створеться console.log()). <br>
https://marketplace.visualstudio.com/items?itemName=jrebocho.vscode-random (розширення для генерування рандомних даних). <br>
https://marketplace.visualstudio.com/items?itemName=aaron-bond.better-comments (розширення для створення читабельних коментарів різного кольору). <br>

# Заняття 30.10.2024

Посилання на репозиторій: <br>
https://github.com/Olexiy-repin/js-112/tree/module-01-lesson-02 <br>
Таблиця юнікодів: <br>
https://en.wikipedia.org/wiki/List_of_Unicode_characters#Latin_script <br>

# Шпаргалка по методам рядків:<br>
slice() -- створює копію частини або всього рядка.<br>
toLowerCase()/toUpperCase() -- приводить рядок до нижнього/верхнього регістра відповідно.<br>
includes() -- перевіряє наявність підрядка в рядку.<br>
startsWith()/endsWith() -- перевіряє чи починаться/закінчується рядок зазначеним підрядком.<br>
indexOf() - шукає перше входження рядка в підрядок і повертає його індекс (або -1).<br>
trim() -- видаляє початкові і кінцеві пробіли з рядка.<br>
Цикл for:<br>
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/for <br>
Цикл for...of:<br>
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/for...of <br>
Корисні методи рядків<br>
https://developer.mozilla.org/en-US/docs/Learn/JavaScript/First_steps/Useful_string_methods

# Заняття 04.11.2024

Посилання на репозиторій: <br>
https://github.com/Olexiy-repin/js-112/tree/module-02-lesson-01 <br>

# Заняття 06.11.2024

https://github.com/Olexiy-repin/js-112/tree/module-02-lesson-02<br>

# Заняття 11.11.2024

https://github.com/Olexiy-repin/js-112/tree/module-03-lesson-01 <br>

# Шпаргалка по методам масивів:<br>
split/join -- перетворює рядок на масив і назад.<br>
push() -- додає елементи до кінця,<br>
pop() -- видаляє елемент з кінця,<br>
shift() -- видаляє елемент із початку,<br>
unshift() - додає елементи на початок.<br>
splice(index, deleteIndex, ...arr) -- починаючи з індексу index, видаляє deleteIndex елементів і вставляє arr. slice(start, end) -- створює новий масив, копіюючи елементи з позиції start до end (не включаючи end).<br>
Функція повинна робити лише те, що очевидно мається на увазі її назвою. І це має бути однією дією. Якщо коротко і зрозуміло: Одна функція -- одна дія.<br>
Якщо функція має повернути бульове значення, не обов’язково повертати з функції true чи false. Скоріш за все ви можете повернути з функції безпосередньо саму умову з if. Наприклад, замість:<br>
function isAdult(age) {<br>
  if (age >= 18) {<br>
    return true;<br>
  } else {<br>
    return false;<br>
  }<br>
}<br>
краще написати:<br>
function isAdult(age) {<br>
  return age >= 18;<br>
}<br>
Шпаргалка з оголошення функцій у JS:<br>
Функціональний вираз (function expression)<br>
const greet = function (name) {<br>
 return `Hello, ${name}`;<br>
};<br>
Оголошення функції (function declaration)<br>
function greet(name) {<br>
 return `Hello, ${name}!`;<br>
}<br>
Для того, щоб щось повернути з функції/методу або умови, можна використовувати оператор return. Також з функції можна повертати відразу будь-який тип даних, наприклад return 'hello' // (повернемо рядок) чи return true // (повернемо буль) чи return [1, 2] // (повернемо масив)<br>
Паттерн раннє повернення, говорить про те, що якщо умова всередині нашего if повертає true, то нам одразу же треба щось повернути із тіла цієї умови, з допомогою return.<br>
Не забувайте, що оператор = це оператор присвоєння, а не порівняння.<br>
Декілька лайфхаків при роботі з масивами.<br>
Як швидко очистити масив<br>
const fruits = ['banana', 'apple', 'orange', 'watermelon', 'apple', 'orange', 'grape', 'apple'];<br>
fruits.length = 0;<br>
console.log(fruits); // поверне []<br>
Як об'єднати більше двох масивів<br>
const fruits = ['apple', 'banana', 'orange'];<br>
const meat = ['poultry', 'beef', 'fish'];<br>
const vegetables = ['potato', 'tomato', 'cucumber'];<br>
const food = [...fruits, ...meat, ...vegetables];<br>
console.log(food); // поверне ["apple", "banana", "orange", "poultry", "beef", "fish", "potato", "tomato", "cucumber"]<br>
Як отримати рандомне значення масиву<br>
const fruits = [ 'banana', 'apple', 'orange', 'watermelon', 'apple', 'orange', 'grape', 'apple', ];<br>
const randomFruit = fruits[Math.floor(Math.random() * fruits.length)];<br>
console.log(randomFruit); // поверне рандомний фрукт із масиву<br>

# Заняття 13.11.2024

Посилання на репозиторій:<br>
https://github.com/Olexiy-repin/js-112/tree/module-03-lesson-02<br>
Посилання на сервіс для імітації Call Stack:<br>
http://latentflip.com/loupe/<br>

# Заняття 18.11.2024

Посилання на репозиторій:<br>
https://github.com/Olexiy-repin/js-112/tree/module-04-lesson-01<br>

# Заняття 20.11.2024

Посилання на репозиторій:<br>
https://github.com/Olexiy-repin/js-112/tree/module-04-lesson-02<br>

# Заняття 25.11.2024

Посилання на репозиторій:<br>
https://github.com/Olexiy-repin/js-112/tree/module-05-lesson-01<br>

Специфікація, тут описано все, що є в JavaScript:<br>
https://ecma-international.org/publications-and-standards/standards/ecma-262/<br>

Чернетка з інфорацією, що має зʼявитися в новій версій JS:<br>
https://tc39.es/ecma262/<br>

Сервіс MDN, де описані різноманітні функції, методи, механізми, які є в JS:<br>
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference<br>



Ознайомтеся з функціями вищого порядку, стрілочними та чистими функціями та у яких випадках їх використовують.<br>
Розгляньте імперативний та декларативний підхід до написання коду та побачите сучасність останнього.<br>
Навчіться використовувати функціональні методи масивів - це ще одна крута штука, без якої в розробці не обійтися.<br>
Потрібно розуміти, де і коли правильно використовувати той чи інший метод, для цього необхідно знати, що повертає метод, який ви використовуєте.<br>
Буде лише плюсом, якщо вивчили дод. матеріали самостійно (крім конспекту та задач).<br>
Не соромимося повертатися до тем, у яких не вдалося розібратися відразу – це нормально, коли з першого разу інформація “не зайшла“.<br>
:pushpin:Прикріплюю корисні посилання на функціональні методи для роботи з масивами, щоб можна було швидко підглянути як використовувати і що повертає той чи інший метод.<br>
Функціональні методи роботи з масивами<br>
А також наглядна схема з популярними перебираючими методами :wink:<br>
:point_up:Виділю важливу (на мою думку) інформацію:<br>
Щоразу, коли потрібно обробити масив, не обов‘язково використовувати цикли або винаходити велосипед. Найімовірніше, це вже зробили за вас.<br>
Пошукайте відповідний метод. У більшості випадків завдання можна буде вирішити за допомогою методів map(), filter(), reduce() або spread-оператора.<br>
Ніколи не завадить вміння застосовувати методи slice(), some(), flatMap() тощо. Використовуйте їх, коли це буде доцільно.<br>
Завжди пам‘ятайте, які методи створюють новий масив, а які модифікують (мутують) вже існуючий. Інакше можна наламати дров.<br>
Метод slice() та spread-оператор роблять поверхневу копію масиву. Тому масиви та підмасиви будуть посилатися на один і той самий об‘єкт у пам’яті.<br>
“Старі” методи, що змінюють масив, мають сучасні аналоги. Ретельно вибирайте використовувані методи.<br>
