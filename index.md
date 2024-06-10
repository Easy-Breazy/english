<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Easy Breezy English</title>

  <!-- Add Bootstrap CSS -->
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-KyZXEAg3QhqLMpG8r+Knujsl5/XVU5K5y5f38F6UmJgf5gDJz3xjm75UaKdMRKf" crossorigin="anonymous">

  <!-- Add Font Awesome icons -->
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.1.0/css/all.min.css">

  <style>
    /* Your custom CSS styles */
    .headline-image img {
      max-width: 260px;
      width: 100%;
      height: auto;
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
        flex-basis: 80%;
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

  <div class="row mt-5">
    <div class="col-md-8 order-md-1">
      <h2 id="about-me">Обо мне</h2>
      <ul>
        <li>Билингв</li>
        <li>Магистр лингвистики, Бирмингемский университет (UK)</li>
        <li>15 лет успешной преподавательской практики в США, Европе и России</li>
      </ul>
      <p><b>Опыт работы</b></p>
      <ul>
        <li>Переводчик в «РИА Новости», Библиотеке Конгресса США, Государственном Эрмитаже</li>
        <li>Старший преподаватель в Яндекс Практикуме</li>
        <li>Курсы делового английского для крупнейших корпораций Финляндии</li>
        <li>Корпоративные тренинги для компании «Лукойл»</li>
        <li>Обширная частная практика: индивидуальные курсы для топ-менеджеров Яндекса, Ozon, Сбербанка, VK, Магнита</li>
      </ul>
      <p><b>Образование и сертификаты</b></p>
      <ul>
        <li>University of Birmingham, UK<br>Applied Linguistics</li>
        <li>University of Kansas, USA<br>Marketing and Public Relations</li>
        <li>University of Cambridge Teaching Knowledge Test</li>
        <li>TEFL Certificate and TEFL Certificate in Business English</li>
        <li>TOEFL: 119 баллов из 120 возможных</li>
      </ul>
    </div>
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
        <!-- Other reviews -->
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

<!-- JavaScript -->
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
