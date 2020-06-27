# simply_slider
***

#### Добавьте в ```<head>```
```html
<link rel="stylesheet" href="./simply-slider.css">
```

#### Добавьте в конце ```<body>```
```html
<script src="./simply-slider.js"></script>
```
---
### Подключаем...
```html
<div class="main_slider">
      <div><img src="#" alt="#"></div>
      <div><img src="#" alt="#"></div>
      <div><img src="#" alt="#"></div>
</div>
```
### main_slider класс для примера, чтобы он использовал simply_slider нужно в собственном файле скрипта указать:
```js
let mainSlider = document.querySelector('.main_slider');
mainSlider.simplySlider({ settings });
```
### Оставив ***settings*** пустым, будут использоваться стандартные настройки
Настройки | Тип | Стандартное значение | Описание
------ | ---- | ------- | -----------
slidesWidth | int | 300 | Ширина слайда в пикселях
slidesHeight | int | 200 | Высота слайда в пикселях
nav | boolean | true | Использование конпок слайдера. Если false, то autoplay:true
autoplay | boolean | false | Автовоспроизведение
autoplaySpeed | int | 2000 | Скорость автовоспроизведения в мс.
slides | int | 1 | Количество отображаемых слайдов
