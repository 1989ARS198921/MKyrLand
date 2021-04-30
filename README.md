# Курсовой проект Лэндинг

Этот проект сделан в качестве курсовой работы Марии Кашниковой для РГРТУ г.8040

## Привет! 👋

## Table of contents

  - [Обзор](#overview)
  - [Вызов](#the-challenge)
  - [Скрин](#screenshot)
  - [Ссылки](#links)
  - [Процесс](#my-process)
  - [Технологии](#built-with)
  - [Интерес](#learned)
  - [Автор](#author)

## Overview

### The challenge

Пользователи должны иметь возможность:

- Просмотр оптимального макета сайта в зависимости от размера экрана их устройства
- Смотрите состояния наведения для всех интерактивных элементов на странице

### Screenshot

![Blogr landing page coding challenge](./design/desktop-design.jpg)

### Links

https://cdo.rsreu.ru/user/profile.php?id=14402
## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Desktop-версия и версия Mobile
- Vanilla JS для мобильной навигации 

### learned

Выпадающее меню - это изюминка моего обучения во время работы над этим проектом. Это то, над чем я никогда раньше не работал и не знал, как это сделать. Мне пришлось провести небольшое исследование (переполнение стека на помощь... лол). В конце концов, я смог завершить выпадающее меню, используя только HTML и CSS - без JS.

Я столкнулся с небольшой проблемой, имея цвет фона и фоновое изображение для родительского контейнера. Ниже приведен фрагмент кода о том, как мне удалось этого достичь.

```css
.header{
    width: 100%;
    height: 100vh;
    position: relative;
    background: url(images/bg-pattern-intro.svg);
    background-position: center;
    background-size: 150%;
    padding: 4rem 10rem;
    border-bottom-left-radius: 6rem;
    background-repeat: no-repeat;
    background-color: hsl(353, 100%, 62%);
}
```



## Author

-- Мария Андреенва Кашникова группа 8040 
-- Информатика и вычислительная техника.
