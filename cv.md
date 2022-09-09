# Бариева Александра
+7 996 776 98 17
Alex.Genrietta@gmail.com
## Краткая информация
Своей главной целью ставлю основательное изучение frontend разработки. При накоплении достаточного опыта планирую преподавать будущим разработчикам и помогать им в развитии навыков.
## Навыки
- HTML, CSS
- SCSS, PUG
- WebPack
- JavaScript
- Git
## Примеры кода
```
const switcher = document.querySelector('.personal-info .switcher');
const switcherBtns = switcher.querySelectorAll('.switcher__item');
function hideElement (tag) {
const elem = document.querySelector(tag);
elem.classList.add('hide');
}
function showElement (tag) {
const elem = document.querySelector(tag);
elem.classList.remove('hide');
}
switcher.addEventListener('click', (event) => {
if ( !(event.target.classList.contains('switcher')) ) {
const target = event.target.closest('.switcher__item');
// Переключаем выделение на кнопках
switcherBtns.forEach( (elem, i) => {
if (elem.classList.contains('switch-checked')) {
if (elem != target) {
elem.classList.remove('switch-checked');
// Меняем содержание
if (i === 0) {
hideElement('.messages');
} else {
hideElement('.invites');
}
}
} else {
if (elem == target) {
elem.classList.add('switch-checked');
// Меняем содержание
if (i === 0) {
showElement('.messages');
} else {
showElement('.invites');
}
}
}
});
}
});
```
## Опыт работы
1. Разработка слайдера для лендинга [Firstep](https://firstep.love/)
2. Разработка веб-версии приложения Firstep
## Образование
Студентка 2 курса, направление "Прикладная информатика" СпбПУ

Обучение RS-School
## Английский язык - B2
- Свободный разговор на неускоспециализированные темы
- Свободное чтение технической литературы и документации
