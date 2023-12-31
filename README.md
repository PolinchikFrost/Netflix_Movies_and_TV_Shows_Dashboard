# Исследование контента на Netflix

**Ссылка на датасет:** https://www.kaggle.com/datasets/shivamb/netflix-shows

**Ссылка на дашборд:** https://public.tableau.com/views/Netflix_16985791596930/sheet0?:language=en-US&publish=yes&:display_count=n&:origin=viz_share_link

## Описание датасета

В датасете представлены данные по фильмам и сериалам на Netflix с начала существования платформы и до середины 2021 года. В датасете содержится порядка 8000 строк. 

После предобработки данных в нём остались следующие столбцы:

1. **show_id** - уникальный id конетента
2. **type** - тип контента
3. **title** - название фильма/сериала
4. **director** - режиссёр
5. **country** - страна, в которой был произведён контент
6. **date_added** - дата добавления контента на платформу (дата релиза)
7. **release_year** - год релиза
8. **rating** - название рейтинга, в который входит контент
9. **duration** - продолжительность (в минутах для фильмов, в сезонах для сериалов)

## Макет дашборда

<center><img src="/images/Макет дашборда.png" ></center>

## Доля контента по типам

<center><img src="/images/Доля%20контента%20по%20типам.jpg" ></center>

На графике видно, что тип Movie преобладает над типом TV Show. Это неожиданный результат, так как большинство людей воспринимают Netflix как платформу для просмотра сериалов.

## Новый контент за последние n дней

<center><img src="/images/Новый контент.jpg" ></center>

На дашборде представлен новый контент за последние три дня. При желании пользователь может вывести наименования новых фильмов/сериалов за любое количество дней, так как на дашборде есть соответствующий фильтр.

## ТОП-10 режиссёров Netflix

<center><img src="/images/Топ режиссёров.jpg" ></center>

На графике ось Х - количество произведённого контента, ось Y - имя и фамилия режиссёра. Топ-1 режиссёр по количеству контента на Netflix - Rajiv Chilaka.

## Количество контента в динамике по годам релиза

<center><img src="/images/Количество контента по годам релиза.jpg" ></center>

На графике ось Х - год релиза, ось Y - количество произведённого контента. Видно стабильное увеличение количества контента с 2014 по 2019 года, а затем началось снижение. Максимальное количество контента произведено в 2019 году - 2016 фильмов и сериалов.

## Распределение контанта по рейтингам

<center><img src="/images/Количество контента по рейтингу.jpg" ></center>

На графике ось Х - название рейтинга, ось Y - количество контента. В топ-3 входят следующие рейтинги: TV-MA(контент для людей, старше 18 лет) - 3207 фильмов и сериалов, TV-14 (контент для людей старше 14 лет) - 2160 фильмов и сериалов, TV-PG(контент, не подходящий для детей младшего возраста) - 863 фильмов и сериалов.

## Распределение типов контента в топ-10 странах

<center><img src="/images/Контент по странам.jpg" ></center>

На графике ось Х - страна, ось Y - суммарное количество контента. Цветом выделен тип контента: красным - Movies, серым - TV Shows. Самое большое количество контента на Netflix производится в США. Также картина распределения количества контента по типам сходится с графиком "Доля контента по типам".
