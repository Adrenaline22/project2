# Практическая работа №2 "Научиться учиться: анимация, шрифты, фреймы."

---

## Оглавление

### Шапка сайта, блок header;
### Основное содержимое страницы, блок content;
- Секция, блок description;
- Секция, блок techniques;
- Секция, блок video;
- Секция, блок oakley;
- Секция, блок feynman;
- Секция, блок digits;
- Секция, блок khan;
- Секция, блок kaufman;
- Секция, блок resources;
### Подвал сайта, блок footer.

---

## Описание

Проект представляет собой лендинг, содержащий в себе проектную работу №1 с новыми секциями такими, как techniques, video, oakley, khan и resources, и функциями такими, как анимация, шрифты, фреймы.

---

## Функциональность

Данный сайт обладает следующими критериями функциональности:
- дизайн;
- контент;
- структура;
- доступные функции;

Под функциями понимаются следующие возможности:
- просмотра текта и видео-материала без перехода на сторонние сайты;
- получения дополнительного полезного материала;
- переход на другую страницу с целью ознакомления с наставниками, концепции и главной страницы Практикума;
- переход на другую страницу с целью ознакомления с соцсетями Практикума.

---

## Технологии

В проекте были применены новые изученные технологии в сравнении с предыдуще работой:
- анимация;
- шрифты;
- фреймы;
- файловая структура проекта по правилам Nested БЭМ;
- сгругление картинки;
- добавление линейности блочным элементам.


### Анимация

```
CSS:
@keyframes rotation {
to {...}
from {...}
}
.rotation {
animation-name:...;
animation-duration:...;
animation-iteration-count:...;
}
```


### Шрифты

Возможность подключения любых шрифтов в свободное время.


### Фреймы

```
HTML:
<iframe class="..." allowfullscreen title="..." frameborder="..." width="..." height="..." src="..."></frame>
```


### Файловая структура проекта по правилам Nested БЭМ;

```
папка "блок"
    папка "__элемент"
        папка "_ключ модификатора"
            папка "_значение модификатора"
                файл  "блок__элемент_значение модификатора"
    файл "блок__элемент.css"
файл "блок.css"
```


### Сгругление картинки

```
border: radius(...%)
```


### Добавление линейности блочным элементам;
```
display: inline-block
```
или
```
display: inline
```

---

## Планы по доработке проекта

1. Замена адреса ссылок на действительные URL;
2. Замена на другую цветовую гамму;
3. Вставка юзерфрендли элементов:
   - "время чтения статьи ...мин";
   - "была полезна статья?".
