
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
    /* Updated styles for the image */
    .my-image {
      max-width: 90%;
      height: auto;
      margin-top: 30px;
      margin-bottom: 30px;
    }

    /* New styles for the headline 1 content and image container */
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

    /* New style for the YouTube icon */
    .contact-info a[href*="youtube.com"] {
      color: #ff0000;
    }

     .text-center img {
      width: 80%; /* adjust the value as needed */
      height: auto; /* maintain the aspect ratio */
       margin-top: 30px;
      margin-bottom: 30px;
    }
    ul li {
  margin-bottom: 10px; /* adjust the value as needed */
}
  </style>
</head>

<body>

  <!-- Use Bootstrap's grid system for the main content -->
  <div class="container">
    <!-- New container for the headline 1 content and image -->
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
        <!-- Updated the image to be responsive and placed to the right of the headline 1 -->
        <img src="pics/prof.jpg" class="my-image img-fluid" alt="Teacher's profile picture">
      </div>
    </div><!-- /.headline-container -->

    <div class="blurb">
      <h2 id="about-me">Обо мне</h2>
      <p>Здравствуйте, друзья!</p>

      <p>
        "Hello, I'm Jane Doe, and I'm passionate about helping students of all ages and backgrounds improve their English language skills. I have a degree in English literature from the University of XYZ, and I've been teaching English for over 10 years.
      </p>

      <p>
        I believe that learning a new language is not just about memorizing grammar rules and vocabulary lists, but about immersing yourself in the culture and history of the people who speak it. That's why I incorporate a variety of engaging and interactive activities into my lessons, such as watching and discussing movies and TV shows, reading and analyzing literature, and exploring current events and social issues.
      </p>

      <!-- Add the new image before the how-it-works section -->
      <div class="text-center">
        <img src="pics/studying.jpeg" class="img-fluid" alt="Studying English">
      </div>

      <div id="how-it-works">
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
      </div><!-- Add the closing div tag for how-it-works -->

      <div id="reviews">
        <h2>Отзывы</h2>
        <!-- add content for the "Отзывы" section here -->
      </div>

      <div id="contacts">
        <h2>Контакты</h2>
        <div class="contact-info text-center">
          <a href="https://telegram.me/easy_breezy_english"><i class="fab fa-telegram-plane fa-2x"></i></a>
          <a href="mailto:easy2breezy@yandex.ru"><i class="fas fa-envelope fa-2x"></i></a>
          <a href="http://www.youtube.com/c/EasyBreezyEnglish" target="_blank"><i class="fab fa-youtube fa-2x"></i></a>
        </div>
      </div>
    </div><!-- /.blurb -->
  </div><!-- /.container -->

</body>

</html>
