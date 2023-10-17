# Тиждень 4

## Кольори в CSS, браузерні префікси, основи адаптивної верстки
- Кольори в css
- Кастомні шрифти
- Браузерні префікси https://itnext.io/css-fundamentals-vendor-prefixing-b339d3c9859a
- Типи версток сайтів(фіксована/відзивчіва/адаптивна) [приклад адаптивного сайту](https://ilyaillych.wixstudio.io/adoptive-example)
- Mobile/desktop first min-width/max-width
- Media queries [Документація MDN](https://developer.mozilla.org/ru/docs/Web/CSS/Media_Queries/Using_media_queries)
- Верстка за допомогою медіа-запитів (Media queries) 
- Приклад верстки меню сайта https://www.figma.com/file/x8GJjftmuukbZcb1sEmEuo/Responsive-site-example?type=design&node-id=1%3A59&mode=dev

  **Перевірка:** Верстка сторінки з адаптацією під різні пристрої з адаптивними картинками https://www.figma.com/file/x8GJjftmuukbZcb1sEmEuo/Responsive-site-example?type=design&node-id=1%3A59&mode=dev

## Адаптивні зображення
- контентні зображення
- img vs background image
- container + width/max-width
- object-fit: fill/contain/cover
- object-position: center/top/bottom/left/right/px
- responsive height position: relative+absolute   
  `.cards__image {
  	margin: 0 0 20px 0;
  	padding-top: 58%;
  	overflow: hidden;
  	position: relative;
  	width: 100%;
  }
  
  .cards__image img {
  	width: 100%;
  	height: 100%;
  	object-fit: cover; 
  	position: absolute;
  	top: 0;
  	left: 0;
  }`
- picture + source

## Препроцесори SCSS

- Обзор, що, для чого?
- Встановлення SASS 
- Основи SCSS
- Синтаксис
- Змінні та їх відмінність від CSS-змінних
- Міксіни
- Цикли

**Перевірка:** Верстка сторінки з використанням препроцесорів https://www.figma.com/file/ILqzGGBmB9kEqoN3w7zCZK/Fitness-Landing-Page-(Community)-(Copy)?type=design&node-id=1%3A12&mode=dev
