# АНАЛИЗ СОВРЕМЕННЫХ САЙТОВ
## ЛАБОРАТОРНАЯ РАБОТА № 10 по дисциплине «Веб-технологии»
**Выполнила**: Студентка группы 241-671 Панфилова А.А.

### Подбор сайтов и их описание
1. [Liqium](https://www.liqium.com/) -специализирующаяся на разработке и внедрении решений для автоматизации управления водными ресурсами.
1. [Notamedia](https://nota.media/) -  специализирующееся на разработке комплексных IT-решений, создании бренд-стратегий и медиапроектов.
1. [MWI](https://mwi.me/) - специализирующееся на цифровых стратегиях.
1. [ADV](https://adv.ru/?rrcid=173670833132867035#CoreVerticals) - специализирующаяся на предоставлении комплексных решений для цифровой рекламы.
1. [PINKMAN](https://www.pinkman.ru/) - специализирующаяся на разработке уникальных визуальных решений для брендов.
1. [Факт](https://fact.digital/) - проектирование и развитие гибких цифровых экосистем.
1. [BRAIND](https://braind.agency/?erid=2W5zFGRQtV6&utm_source=ratingruneta&utm_medium=advmiddle&utm_campaign=production&rrcid=173670833132867035) - посвящен современным решениям в области нейротехнологий, искусственного интеллекта и когнитивных наук.
1. [Космос-Веб](https://www.cosmos-web.ru/) - специализируется на предоставлении услуг в области веб-разработки и IT-решений.
1. [Uplab](https://www.uplab.ru/?utm_source=ratingruneta&utm_medium=cpc&utm_content=web&utm_campaign=hyperlink_option&rrcid=173670833132867035) - специализируется на создании современных сайтов, мобильных приложений и сложных IT-решений.
1. [Магвай](https://magwai.ru/) - специализирующаяся на разработке и внедрении технологий для автоматизации бизнес-процессов.

### Описание свойств CSS
|№|Свойство|Назначение|Где встретилось|
|-|--------|----------|---------------|
|1|-webkit-text-size-adjust|адаптирование текста  к изменениям масштаба|[Космос-Веб](https://www.cosmos-web.ru/)|
|2|--swiper-theme-color|задает основной цвет для различных элементов слайдера|[Liqium](https://www.liqium.com/)|
|3|unicode-bidi:[normal, embed, bidi-override, isolate, plaintext, initial, inherit]|отображение текста и его составляющих в зависимости от их направления|[MWI](https://mwi.me/)|
|4|--swiper-theme-color|отображение текста и его составляющих в зависимости от их направления|[ADV](https://adv.ru/?rrcid=173670833132867035#CoreVerticals)|
|5|aspect-ratio:[width/height, auto, inherit, initial, revert, unset]|явная установка соотношения сторон элемента|[Факт](https://fact.digital/)|
|6|--smart-captcha-doc-height|используется для хранения и динамического управления определённой высотой|[Uplab](https://www.uplab.ru/?utm_source=ratingruneta&utm_medium=cpc&utm_content=web&utm_campaign=hyperlink_option&rrcid=173670833132867035)|
|7|visibility:[visible;hidden;collapse; inherit;]|используется для управления видимостью элемента на веб-странице|[Notamedia](https://nota.media/)|
|8|mobile|стиль, применяющийся только к мобильным устройствам|[PINKMAN](https://www.pinkman.ru/)|
|9|list-style:[disc inside]|является сокращением для установки нескольких связанных со списком свойств|[Магвай](https://magwai.ru/)|
|10|overflow:[visible; hidden; scroll; auto;]|отображение содержимого эмемента, если оно выходит за пределы области видимости|[Космос-Веб](https://www.cosmos-web.ru/)|

### Структура страницы BRAIND до 5 уровней вложенности [BRAIND](https://braind.agency/?erid=2W5zFGRQtV6&utm_source=ratingruneta&utm_medium=advmiddle&utm_campaign=production&rrcid=173670833132867035)
```
<body>
  <!-- Уровень 1 -->
  <header class="header">
    <!-- Уровень 2 -->
    <div class="header__content">
      <div class="logo"></div> <!-- Логотип -->
      <nav class="navigation">
        <!-- Уровень 3, список навигации -->
        <ul class="navigation__list">
          <li class="navigation__item"><a href="#" class="navigation__link">About</a></li>
          <li class="navigation__item"><a href="#" class="navigation__link">Services</a></li>
          <li class="navigation__item"><a href="#" class="navigation__link">Portfolio</a></li>
        </ul>
      </nav>
    </div>
  </header>
  
  <main class="main-content">
    <!-- Уровень 2 -->
    <section class="hero-section">
      <!-- Уровень 3 -->
      <div class="hero-section__content">
        <!-- Уровень 4 -->
        <h1 class="hero-section__title">Build iconic brands</h1>
        <p class="hero-section__subtitle">We create strategies to inspire your audience.</p>
        <a href="#" class="hero-section__cta">Get in Touch</a>
      </div>
    </section>

    <section class="services-section">
      <!-- Уровень 3 -->
      <div class="services-list">
        <!-- Уровень 4 -->
        <div class="services-item">
          <h3 class="services-item__title">Strategy</h3>
          <p class="services-item__description">Business strategy for long-term success.</p>
        </div>
        <div class="services-item">
          <h3 class="services-item__title">Branding</h3>
          <p class="services-item__description">Design and identity to make your brand memorable.</p>
        </div>
      </div>
    </section>
  </main>
  
  <footer class="footer">
    <!-- Уровень 2 -->
    <div class="footer-content">
      <!-- Уровень 3 -->
      <div class="footer-contacts">
        <a href="mailto:info@braind.agency" class="footer-email">info@braind.agency</a>
      </div>
    </div>
  </footer>
</body>

```
### Характеристика сайта BRAIND

1. Использованная методология именования классов:
   Сайт использует BEM методологию.
   - Примеры классов:
     - header__content - элемент блока "header".
     - services-item__title - элемент блока "services-item".

2. Использование HTML5-тегов:
   Сайт использует HTML5-теги, такие как ``` <header>, <main>, <section>, <footer> ```.

3. Количество оберток ``` <div> ```:
   - Применяются так, чтобы не увеличивать сложность.
   - <div> используются только для группировки и стилизации элементов.

4. Насколько легко разобраться в коде:
   - Оптимально организованный код.
   - Использование BEM-методологии делает код удобным для чтения и поддержания. 
   - Семантические элементы ясны и логичны, что помогает быстро понять структуру страницы.

---
### Итог

Сайт BRAIND демонстрирует разумное использование современных подходов к разработке веб-интерфейса, таких как BEM и HTML5. Код легок в понимании и обслуживании, с логичной структурой и ясной семантикой, что подчеркивает качественный подход к веб-разработке.
