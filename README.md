# Заголовок h1 уровня #
## Заголовок h2 уровня ##
###### Заголовок h6 ######

Lorem ipsum dolor sit amet, consectetur adipisicing elit. Quasi autem sequi quo eaque soluta, id consectetur consequuntur rerum molestiae, iusto corporis ipsa sed, nam, animi repellendus debitis. Sequi ratione corrupti molestiae dolor deleniti neque eveniet dolorem ducimus inventore voluptates nam non, repellendus quisquam numquam perferendis totam a aspernatur! Similique maiores delectus, dicta repudiandae placeat quidem unde ad debitis! Voluptate, similique sunt ab soluta modi vel unde id autem adipisci dignissimos eos commodi tenetur nesciunt harum quo cumque, minus voluptatibus. Nisi iure accusantium alias asperiores sapiente quo. Voluptatem eaque iste ea saepe, inventore praesentium accusantium rem quam, qui mollitia, id fuga.

Текст  
...оборвался


## Списки ##
* 1
* 2
    * 2.1
    * 2.2
* 3

### Упорядоченный список ###

0. Element #1
0. Element #2
0. Element #3

## Исходный код ##
```html
<nav class="menu">
	<li class="menu__item">Item #1</li>
	<li class="menu__item">Item #2</li>
</nav>
```

```php
<?php var_dump(true); ?>
```

## Горизонтальная черта ##
***

## Ссылки ##
This is a [link](https://github.com/sunday-killer/markdown "This is a title")

Вот тут будут несколько ссылок: [ссылка №1][1], [ссылка №2][2], [ссылка №3][]

[1]: https://github.com/sunday-killer/markdown "Title here"
[2]: https://github.com/sunday-killer
[ссылка №3]: https://github.com

## Выделение ##
*italic*
**Strong**
***Strong Italic***
~~crossed out~~

## Картинки ##

Картинка без `alt` и `title`

![](//placehold.it/150x100)

Картинка с `alt` и `title`

![Alt text](//placehold.it/150x100 "Here is a title")

Картинки «сноски»:

![Картинка][image1]

[image1]: //placehold.it/150x100 "Here is a title"

Картинки-ссылки:

[![Alt text](//placehold.it/150x100)](https://github.com "Title for image-link")