# Задачи
## Задача А
### Управление макетами с помощью типов отображения в CSS
Исходный html код:
``` html
<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <title>Типы отображения CSS</title>
</head>
<body>
<h1>Свойство display</h1>
    <div>
        <h2>display: block</h2>
        <p>Элементы с этим значением свойства display всегда начинаются с новой строки и занимают всю доступную ширину родительского контейнера. Они создают блочный контекст и могут содержать другие блочные и строчные элементы.</p>
      <span class="block">Я первый блочный элемент</span>
      <span class="block">Я второй блочный элемент</span>
      <span class="block">Я третий блочный элемент</span>
    </div>

    <div>
        <h2>display: inline</h2>
        <p>Элементы с этим значением свойства display не начинают новой строки и занимают только столько ширины, сколько необходимо для их содержимого. Они создают строчный контекст и не могут содержать другие блочные элементы.</p>
            <span class="inline">Я первый строчный элемент</span>
      <span class="inline">Я второй строчный элемент</span>
      <span class="inline">Я третий строчный элемент</span>
    </div>

    <div>
        <h2>display: inline-block</h2>
        <p>Элементы с этим значением свойства display объединяют особенности блочных и строчных элементов. Они не начинают новой строки, но при этом могут занимать только столько ширины, сколько необходимо для их содержимого, и при этом могут содержать другие блочные и строчные элементы.</p>
      
       <span class="inline-block">Я первый блочно-строчный элемент</span>
      <span class="inline-block">Я второй блочно-строчный элемент</span>
      <span class="inline-block">Я третий блочно-строчный элемент</span>
    </div>
</body>
</html>

```
### Задание
В нашей статье span играет роль примера, поэтому задача студентов заключается в том, что бы стилизовать их так, что бы они наглядно показывали особенности того ил ииного типа отображения.


## Задача В
###  Галерея изображений
Создать веб-страницу с галереей изображений. Необходимо внутри тега div написать несколько (минимум 6) тегов img с разными картинками, объединенной одной темой. Эти картинки необходимо с помощью позиционирования расположить на странице так, чтобы это выглядело красиво и интересно, так же необходимо чтобы между картинками не было отступов и они накладывались друг на друга с помощью z-index.

## Задача С
###  Галерея изображений с описанием
Доработать предыдущую  работу следующим образом:
Чтобы применить обтекание мы текст и картинку должны обернуть в общий див, текст должен быть ниже картинки в html. Также убираем позиционирование картинок, чтобы правильно применилось свойство float. Желательно каждому блоку с текстом и картинкой задать цвет фона, и так же как в прошлом задании добавить позиционирование, только  уже не к картинке, а к общему блоку.




