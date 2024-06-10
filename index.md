<html lang="ru">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Easy Breezy English</title>

  <!-- Add Bootstrap CSS and JS -->
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-KyZXEAg3QhqLMpG8r+Knujsl5/XVU5K5y5f38F6UmJgf5gDJz3xjm75UaKdMRKf" crossorigin="anonymous">
  <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.11.6/dist/umd/popper.min.js" integrity="sha384-oBqDVmMz4fnFO9gybBud7TlRbs/ic4AwGcFZOxg5DpPt8EgeUIgIwzjWfXQKWA3" crossorigin="anonymous"></script>
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/js/bootstrap.min.js" integrity="sha384-cn7l7gDp0eyniUwwAZgrzD06kc/tftFf19TOAs2zVinnD/C7E91j9yyk5//jjpt/" crossorigin="anonymous"></script>

  <!-- Add Font Awesome icons -->
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.1.0/css/all.min.css">

  <style>
    .my-image {
      max-width: 90%;
      height: auto;
      margin-top: 30px;
      margin-bottom: 30px;
    }

    .headline-container {
      display: flex;
      flex-wrap: wrap;
    }

    .headline-content {
      flex-grow: 1;
      margin-right: 20px;
    }

    .headline-image {
      flex-basis: 300px;
      margin-top: 20px;
    }

    @media only screen and (max-width: 768px) {
      .headline-content {
        margin-right: 0;
      }

      .headline-image {
        flex-basis: 100%;
        margin-top: 20px;
      }
    }

    .headline-content ul {
      line-height: 1.3;
    }

    #how-it-works ul {
      line-height: 1.5;
    }

    .contact-info a {
      margin-right: 20px;
    }

    .contact-info a[href*="youtube.com"] {
      color: #ff0000;
    }

    .studying-container,
    .success-container {
      display: flex;
      flex-wrap: wrap;
      margin-bottom: 50px;
    }

    .studying-image,
    .success-image {
      flex-basis: 40%;
      max-width: 40%;
      height: auto;
      margin-right: 20px;
    }

    .studying-content,
    .success-content {
      flex-grow: 1;
      margin-top: 20px;
    }

    .studying-content h2 {
      margin-bottom: 10px;
    }

    @media only screen and (max-width: 768px) {
      .studying-image,
      .success-image {
        flex-basis: 100%;
        max-width: 100%;
        margin-right: 0;
      }

      .studying-content,
      .success-content {
        margin-top: 20px;
      }
    }

    ul li {
      margin-bottom: 10px;
    }

    #reviews,
    #contacts {
      display: block;
      margin-bottom: 30px;
    }

    .review-content {
      display: none;
    }

    .review h4 {
      background-color: #f0f0f0;
      padding: 10px;
      cursor: pointer;
    }

    .review.active h4 {
      background-color: #ccc;
    }
  </style>
</head>
<body>

  <div class="container">
    <div class="headline-container">
      <div class="headline-content">
        <h1>Помогаю достигать цели и преодолевать барьеры</h1>
          <p>Меня зовут Анастасия, я профессиональный преподаватель английского для взрослых</p>
      </div>
      <div class="headline-image">
        <img src="pics/prof.jpg" class="my-image img-fluid" alt="Фотография профиля преподавателя">
      </div>
    </div>
   <div class="about-me">
      <h2 id="about-me">Обо мне</h2>
       <ul>
          <li>Билингв, много лет прожила в США и Европе</li>
         <li>Магистр лингвистики, Бирмингемский университет (UK)</li>
        <li>15 лет успешной практики в США, Европе и России</li>
        </ul>
      </p>
     <p> <b> Опыт работы</b>
       <ul>
          <li>Переводчик в «РИА Новости», Библиотеке Конгресса США, Государственном Эрмитаже </li>
         <li>Старший преподаватель в Яндекс Практикуме</li>
         <li>Курсы делового английского для крупнейших корпораций Финляндии</li>
          <li>Корпоративные тренинги для компании «Лукойл»</li>
         <li>Обширная частная практика: индивидуальные курсы для топ-менеджеров Яндекса, Ozon, Сбербанка, VK, Магнита</li>
        </ul>
      </p>
     <p> <b> Образование и сертификаты</b>
       <ul>
          <li>University of Birmingham, UK<br>
            Applied Linguistics</li>
          <li>University of Kansas, USA<br>
          Marketing and Public Relations</li>
          <li>University of Cambridge Teaching Knowledge Test</li>
          <li>TEFL Certificate and TEFL Certificate in Business English</li>
         <li>TOEFL: 119 баллов из 120 возможных</li>
        </ul>
      </p>
    </div>

    <div id="how-it-works">
      <div class="studying-container">
        <img src="pics/studying.jpeg" alt="Изучение английского" class="studying-image">
        <div class="studying-content">
          <h2>Как проходит обучение</h2>
          <ul>
            <li><b>Шаг 1: Бесплатная часовая диагностика</b><br>
              Анализируем опыт изучения, ставим цели, намечаем путь к успеху
            </li>
            <li><b>Шаг 2: Радость изучения</b><br>
              Получаем удовольствие от растущих компетенций и интереснейших встреч с английским
            </li>
            <li><b>Шаг 3: Оценка прогресса</b><br>
              Обсуждаем достижения и точки роста, отслеживаем метрики, корректируем стратегию
            </li>
          </ul>
        </div>
      </div>
    </div>

   <div id="reviews-section">
      <div class="success-container">
        <div class="success-image">
          <img src="pics/success.jpeg" alt="Успех" class="studying-image">
        </div>
        <div class="success-content">
      <h2>Истории успеха</h2>
      <div class="review">
        <h4 onclick="toggleReviewContent(0)" style="color: #1e6bb8;">Любовь, юрист <br> TOEFL, поступление в америкаский колледж</h4>
        <div class="review-content">
          <p><i>Очень довольна уроками. Из профиля было видно, что Анастасия большой профессионал в своём деле, и занятия это только подтвердили. Идеальный баланс серьезной теоретической подготовки и реального опыта разговорного английского. С Анастасией очень эффективно работать над всеми аспектами - грамматикой, произношением, словарным запасом, качеством и скоростью речи. Уроки очень живые и интересные. Я получаю большое удовольствие и от самих занятий, и от общения. Я на данный момент живу в англоязычной среде, и Анастасия оказывает мне неоценимую помощь в понимании нюансов английской разговорной речи, а также отработке популярных фраз и оборотов речи.</i></p>
        </div>
      </div>
      <div class="review">
        <h4 onclick="toggleReviewContent(1)" style="color: #1e6bb8;">Нина, преподаватель <br> Преподавание на английском в Хельсинкском университете </h4>
        <div class="review-content">
          <p><i>Занятиями очень довольна. Как раз искала русскоязычного преподавателя с лингвистическим образованием и опытом проживания в Великобритании или США. Занимаемся по коммуникативной методике, много разговорной практики, но про грамматику не забываем тоже. Анастасия использует современные британские пособия, аудио, видео. Как раз то, что я хотела. Уже чувствую эффект от занятий. I like our lessons very much. They are interesting and fun. We talk a lot and watch videos in English, but we also discuss grammar because I think that this is important. I feel like I am making progress all the time. Anastasia is a great teacher!</i></p>
        </div>
      </div>
      <div class="review">
        <h4 onclick="toggleReviewContent(2)" style="color: #1e6bb8;">Марина и Слава, фронтенд-разработчики <br> Адаптация к жизни в США, собеседование при приеме на работу</h4>
        <div class="review-content">
          <p><i>Мы с мужем уже почти полтора месяца изучаем английский с Анастасией, и просто бесконечно довольны! Нам удалось с первой попытки найти прекрасного преподавателя: с идеальным произношением, с отличными профессиональными качествами и умением доносить информацию. На занятиях всегда очень интересно, Анастасия постоянно добавляет много интерактива в дополнение к учебнику, мы и злободневные темы обсуждаем, и загадки загадываем, и рисуем, и шутим - в общем, скучно точно никогда не бывает :-) В то же время, Анастасия - достаточно строгий преподаватель в самом лучшем значении этого слова: не дает отлынивать и расслабляться, и если нужно что-то выучить, то будет помогать нам практиковаться с неподдающейся темой, пока не выучим :-) В общем, всё прекрасно - английский прокачивается, и мы планируем оставаться с Анастасией еще на много месяцев: в планах когда-нибудь добраться до высот уровня С1 и сдать IELTS на соответствующий балл. Верим, что с таким преподавателем у нас всё получится!</i></p>
        </div>
          </div>
<div class="review">
        <h4 onclick="toggleReviewContent(3)" style="color: #1e6bb8;" >Виктор, режиссер-документалист <br> Адаптация к жизни в США </h4>
        <div class="review-content">
          <p><i>Русскоязычный преподаватель с идеальным английским произношением. Редкое сочетание для этого сайта. Интеллигентно, спокойно, но верно наращивает ваши говорительные, слушательные и грамматические навыки. Рекомендую!</i></p>
        </div>
      </div>
        </div>
      </div>
    </div>

    <div id="contacts">
      <h2>Контакты</h2>
      <div class="contact-info text-center">
        <a href="https://telegram.me/easy_breezy_english"><i class="fab fa-telegram-plane fa-2x"></i></a>
        <a href="mailto:easy2breezy@yandex.ru"><i class="fas fa-envelope fa-2x"></i></a>
        <a href="http://www.youtube.com/c/EasyBreezyEnglish" target="_blank"><i class="fab fa-youtube fa-2x"></i></a>
      </div>
    </div>
  </div>

  <script>
    function toggleReviewContent(index) {
      var reviewContent = document.getElementsByClassName("review-content");
      for (var i = 0; i < reviewContent.length; i++) {
        if (i === index) {
          if (reviewContent[i].style.display === "block") {
            reviewContent[i].style.display = "none";
          } else {
            reviewContent[i].style.display = "block";
          }
        } else {
          reviewContent[i].style.display = "none";
        }
      }
    }
  </script>

</body>
</html>
