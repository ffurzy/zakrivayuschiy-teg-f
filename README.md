
https://github.com/ffurzy/zakrivayuschiy-teg-f

https://ffurzy.github.io/zakrivayuschiy-teg-f/


2/28/2050

1. Исправил ошибки через валидатор
2. Удалил header__content. Почему-то для меня чисто логически удобно создавать еще один блок. 
3. Добавил <h1 class="logo__text">закрывающий тег</h1>
4. Разметил </HTML> ссылкой. 
5. Заменил теги <section> на <article>.
6. Добавил атрибут loading="lazy".
7. Добавил атрибут aria-hidden="true".
8. Обернул текст в "text__wrapper">
9. Добавил type="button"
10. Добавил анимацию для кнопки модального окна


css
1. Поправил line-height у шапки для мобилок. 
2. Исправил классы в шапке
3. Убрал overflow: hidden, но нашел такое свойство clip-path: inset(0 0 0 0);. Так как у меня длинные фотки. Они либо растягивают родителя если убираю max-height: 696px; либо вылазят за пределы.
4. post__image-container добавил рамку
5. добавил классы фильтров
6. поправил пиксели для лейбла, убрал для мобилки
7. поправил box-shadow у кнопок 
8. .button:focus - сбросил значения и добавил .button:focus-visible
9. добавил для .like-icon.is-liked .heart - transform-origin: center; - раньше не понимал почему иконку уползает вправо при анимации.
10. Убрал фиксированные размеры у кнопок
11. Удалил дублирования в медиа запросах
12. Поправил padding .modal[open] на 30 
13. Поправил фиксированное значение у кнопку попапа
14. Убрал анимацию у кнопок и сделал замену цвета текста другим способом. Сначала не понимал как
15. Переопределил стили для модельного окна заранее.
16. Убрал modal__button переопределил размеры для него через .modal > .button
17. Оставил одинаковый класс для текстов в кнопках.

variables
1. Добавил альтернативные шрифты
2. Сделал единообразный формат переменных

animations
1. Исправил ошибки через валидатор
2. Поправил названия анимаций
3. Поправил задержку у core


3/2/2025
1. .button-heart удалил дублирование. Не знаю как так вышло
2. https://disk.yandex.ru/i/4-p-YnZbTvniAQ не вижу проблем с шапкой по пиксель перфекту. Пользуюсь данным макетом https://www.figma.com/design/w2xSZuydbaTSe0GyNHBWeo/4-%D1%81%D0%BF%D1%80%D0%B8%D0%BD%D1%82.-%D0%9F%D1%80%D0%BE%D0%B5%D0%BA%D1%82%D0%BD%D0%B0%D1%8F-%D1%80%D0%B0%D0%B1%D0%BE%D1%82%D0%B0?node-id=0-1&p=f&t=Bo26l8kGk3yx8IhD-0
3. row-gap: 20px; оставил. Без него у меня у меня слова слипаются
4. Поправил рамку
5. По поводу .post__label получал от вас замечание - как можно лучше и попытался сделать что-то усредненное. Добавил отдельные значение для мобильной версии. 

я сначала думал в сторону вообще анимации.. по видео понял что речь про box-shadow