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

    /* New styles for the list items */
    .headline-content ul {
      line-height: 1.3;
    }

    #how-it-works ul {
      line-height: 1.5;
    }

    /* New style for the contact-info icons */
    .contact-info a {
      margin-right: 20px;
    }

    .contact-info a[href*="youtube.com"] {
      color: #ff0000;
    }

    .studying-container {
      display: flex;
      flex-wrap: wrap;
      margin-bottom: 50px;
    }

    .studying-image {
      flex-basis: 40%;
      max-width: 40%;
      height: auto;
      margin-right: 20px;
    }

    .studying-content {
      flex-grow: 1;
      margin-top: 20px;
    }

    .studying-content h2 {
      margin-bottom: 10px;
    }

    @media only screen and (max-width: 768px) {
      .studying-image {
        flex-basis: 100%;
        max-width: 100%;
        margin-right: 0;
      }

      .studying-content {
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
  </style>
</head>

<body>

  <div class="container">
    <div class="headline-container">
      <div class="headline-content">
        <h1>Помогаю достигать цели и преодолевать барьеры</h1>
        <ul>
          <li>Преподаватель английского-билингв</li>
          <li>Магистр лингвистики, Бирмингемский университет (UK)</li>
          <li>15 лет успешной практики в США, Европе и России</li>
        </ul>
      </div>

      <div class="headline-image">
        <img src="pics/prof.jpg" class="my-image img-fluid" alt="Фотография профиля преподавателя">
      </div>
    </div>

    <div class="blurb">
      <h2 id="about-me">Обо мне</h2>
      <p>Здравствуйте, друзья!</p>

      <p>
        "Привет, я Джейн Доу, и я страстно увлечена помощью студентам всех возрастов и происхождений в улучшении своих навыков английского языка. У меня есть степень в английской литературе от Университета XYZ, и я преподаю английский язык уже более 10 лет."
      </p>

      <p>
        Я верю, что изучение нового языка - это не только запоминание грамматических правил и списков словарного запаса, но и погружение в культуру и историю людей, говорящих на этом языке. Поэтому я включаю различные увлекательные и интерактивные активности в свои уроки, такие как просмотр и обсуждение фильмов и телешоу, чтение и анализ литературы, изучение актуальных событий и социальных проблем.
      </p>
    </div>

    <div id="how-it-works">
      <div class="studying-container">
        <img src="pics/studying.jpeg" alt="Изучение английского" class="studying-image">
        <div class="studying-content">
          <h2>Как проходит обучение</h2>
          <ul>
            <li><b>Шаг 1: Бесплатная часовая диагностика</b><br>
              Анализируем историю, определяем цели, намечаем путь к успеху
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

    <!-- Reviews Carousel -->
    <div id="reviews" class="carousel slide" data-bs-ride="carousel">
      <h2 class="text-center mb-4">Отзывы</h2>
      <div class="carousel-inner">
        <div class="carousel-item active">
          <p>Отзыв 1: Очень довольны результатами обучения!</p>
        </div>
        <div class="carousel-item">
          <p>Отзыв 2: Преподаватель отлично объясняет материал.</p>
        </div>
        <div class="carousel-item">
          <p>Отзыв 3: Занятия помогли мне значительно улучшить свой английский.</p>
        </div>
      </div>
      <button class="carousel-control-prev" type="button" data-bs-target="#reviews" data-bs-slide="prev">
        <span class="carousel-control-prev-icon" aria-hidden="true"></span>
        <span class="visually-hidden">Previous</span>
      </button>
      <button class="carousel-control-next" type="button" data-bs-target="#reviews" data-bs-slide="next">
        <span class="carousel-control-next-icon" aria-hidden="true"></span>
        <span class="visually-hidden">Next</span>
      </button>
    </div>
    <!-- End Reviews Carousel -->

    <!-- Contacts section -->
    <div id="contacts">
      <h2>Контакты</h2>
      <div class="contact-info text-center">
        <a href="https://telegram.me/easy_breezy_english"><i class="fab fa-telegram-plane fa-2x"></i></a>
        <a href="mailto:easy2breezy@yandex.ru"><i class="fas fa-envelope fa-2x"></i></a>
        <a href="http://www.youtube.com/c/EasyBreezyEnglish" target="_blank"><i class="fab fa-youtube fa-2x"></i></a>
      </div>
    </div>
  </div>

</body>

</html>
