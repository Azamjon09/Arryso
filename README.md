# Arryso
![Screenshot 2025-02-19 115609](https://github.com/user-attachments/assets/ace8dd04-2b44-46e3-8957-419606d80c62)
#Array -chist? va dar js chiguna kormekunad?
Албатта, биёед массивҳоро дар JavaScript омӯзем.

Массив чист?

Массив маҷмӯи арзишҳои тартибдодашуда дар JavaScript мебошад. Ин арзишҳо, ки метавонанд аз ҳама намуди додаҳо (рақамҳо, сатрҳо, объектҳо ва ғ.) бошанд, бо тартиби муайян нигоҳ дошта мешаванд. Ҳар як арзиш дар массив дорои индекси таъиншуда аз 0 сар мешавад. Чӣ тавр массивро дар JavaScript эҷод кардан мумкин аст

Шумо метавонед бо истифода аз синтаксиси зерин массив дар JavaScript эҷод кунед:  array -boz dar daruni khudash 12 metodi digar dorad Усули push()-и мисолҳои Array унсурҳои муайяншударо ба охири массив илова мекунад ва дарозии нави массивро бармегардонад.

Усули push() арзишҳоро ба массив замима мекунад. Усулҳои массив pop()

Усули pop()-и мисолҳои Array элементи охиринро аз массив хориҷ мекунад ва бармегардонад он элемент. Ин усул дарозии массивро тағир медиҳад. Усулҳои массив unshift() 

Усули unshift()-и мисолҳои Array унсурҳои муайяншударо ба оғози массив ва дарозии нави массивро бармегардонад.

Усули unshift() арзишҳои додашударо ба оғози объекти массив монанд мегузорад.

push() рафтори шабеҳи unshift() дорад, аммо дар охири массив истифода мешавад. Усулҳои массив гузариш ()

Усули shift()-и мисолҳои Array элементи аввалро аз массив хориҷ мекунад ва унсури хориҷшударо бармегардонад. Ин усул дарозии массивро тағир медиҳад.

Усули pop() рафтори шабеҳ ба shift() дорад, аммо ба унсури охирини як массив. Усулҳои массив concat()

Усули concat()-и мисолҳои Array барои якҷоя кардани ду ё зиёда массивҳо истифода мешавад. Ин метод массивҳои мавҷударо тағир намедиҳад, балки ба ҷои он массиви навро бармегардонад.

Усулҳои массив slice()

Усули slice()-и мисолҳои Array нусхаи ками як қисми массивро ба объекти массиви наве, ки аз аввал то ба охир интихоб шудааст (охираш дохил карда нашудааст), ки дар он оғоз ва ба охир мерасад индекси ҷузъҳои ин массивро ифода мекунад. Массиви аслӣ тағир дода намешавад Усулҳои массив пайвастшавӣ()

Усули join()-и мисолҳои Array бо роҳи пайвастшавӣ сатри навро эҷод ва бармегардонад ҳамаи унсурҳои ин массив, ки бо вергул ё сатри ҷудокунандаи муайян ҷудо карда шудаанд. Агар массив танҳо як адад дорад, пас он ҷузъ бидуни истифодаи ҷудокунанда баргардонида мешавад. Усулҳои массив splice()

Усули splice()-и мисолҳои Array мундариҷаи массивро тавассути нест кардани ё тағир медиҳад иваз кардани унсурҳои мавҷуда ва/ё илова кардани унсурҳои нав дар ҷои худ. Усулҳои массив ба Reversed()

Усули toReversed() намунаҳои Array ҳамтои нусхабардории reverse() мебошад. усул. Он массиви навро бо унсурҳо бо тартиби баръакс бармегардонад.

js mechanism - ba 3 gruh judo meshavand ;
Доираи классикӣ Доираи классикӣ Доираи классикӣ Чархи механики js нишонаи навъи файл Механизми JS

01

02

03

Супориши вайронкунӣ

Синтаксиси таъиноти вайронкунанда JavaScript мебошад ифодае, ки имкон медиҳад, ки арзишҳо аз массивҳо кушода шаванд, ё хосиятҳо аз объектҳо ба тағирёбандаҳои ҷудогона.

Синтаксиси паҳншуда (...)

Синтаксиси паҳншуда метавонад ҳангоми ҳама унсурҳои объект истифода шавад ё массив бояд ба массив ё объекти нав дохил карда шавад, ё бояд як ба як дар аргументҳои занги функсия истифода шаванд рӯйхат.

Параметрҳои истироҳат

Синтаксиси параметри боқимонда имкон медиҳад, ки функсия қабул кунад шумораи номуайяни аргументҳо ҳамчун массив, таъмин кардани роҳ барои ифода кардани функсияҳои вариантӣ дар JavaScript. 


# JavaScript Destructuring, Spread, and Rest

## 1. Destructuring

### Array Destructuring
let fruits = ['Apple', 'Banana', 'Orange'];
let [first, second] = fruits;
console.log(first);  // 'Apple'
console.log(second); // 'Banana'
You can skip elements: 
let [, secondFruit] = fruits;
console.log(secondFruit); // 'Banana'
Object Destructuring
let person = { name: 'John', age: 30 };
let { name, age } = person;
console.log(name); // 'John'
console.log(age);  // 30 
## You can also rename variables:

let { name: fullName, age: years } = person;
console.log(fullName); // 'John'
console.log(years);    // 30
## 2. Spread Operator

### Spread in Arrays
let fruits = ['Apple', 'Banana', 'Orange'];
let moreFruits = [...fruits, 'Mango', 'Peach'];
console.log(moreFruits);  // ['Apple', 'Banana', 'Orange', 'Mango', 'Peach']

## Spread in Objects
let person = { name: 'John', age: 30 };
let updatedPerson = { ...person, city: 'New York' };
console.log(updatedPerson); // { name: 'John', age: 30, city: 'New York' }
## 3. Rest Operator

Rest in Function Parameters
function sum(...numbers) {
  return numbers.reduce((total, num) => total + num, 0);
}
console.log(sum(1, 2, 3, 4)); // 10
Rest in Array Destructuring
let fruits = ['Apple', 'Banana', 'Orange', 'Mango'];
let [firstFruit, secondFruit, ...restFruits] = fruits;
console.log(firstFruit);   // 'Apple'
console.log(secondFruit);  // 'Banana'
console.log(restFruits);   // ['Orange', 'Mango']
### Rest in Object Destructuring
let person = { name: 'John', age: 30, city: 'New York' };
let { name, ...otherDetails } = person;
console.log(name);         // 'John'
console.log(otherDetails); // { age: 30, city: 'New York' }
### Conclusion

*Destructuring allows you to unpack values from arrays and objects into variables.
Spread lets you copy and merge elements from arrays and objects.
Rest enables you to collect multiple elements into a single variable, useful in functions and destructuring.
These features make working with arrays and objects more concise and readable.*


![Screenshot 2025-02-13 022822](https://github.com/user-attachments/assets/625d7e91-c00f-4016-b3be-8021fcb0975a)

