<!DOCTYPE html>
<html>
	<head>
		<title>Easy Breezy English</title>

  <style>
    /* CSS reset */
    html, body, div, span, applet, object, iframe,
    h1, h2, h3, h4, h5, h6, p, blockquote, pre,
    a, abbr, acronym, address, big, cite, code,
    del, dfn, em, img, ins, kbd, q, s, samp,
    small, strike, strong, sub, sup, tt, var,
    b, u, i, center,
    dl, dt, dd, ol, ul, li,
    fieldset, form, label, legend,
    table, caption, tbody, tfoot, thead, tr, th, td,
    article, aside, canvas, details, embed,
    figure, figcaption, footer, header, hgroup,
    menu, nav, output, ruby, section, summary,
    time, mark, audio, video {
        margin: 0;
        padding: 0;
        border: 0;
        font-size: 100%;
        font: inherit;
        vertical-align: baseline;
    }
    /* HTML5 display-role reset for older browsers */
    article, aside, details, figcaption, figure,
    footer, header, hgroup, menu, nav, section {
        display: block;
    }

    .my-image {
      float: right;
      margin-top: 50px;
      margin-left: 50px;
    }

    .my-nav a {
      margin-right: 30px;
    }

    .wrapper {
      margin-left: 0;
    }

    .my-nav {
      padding-left: 0;
    }

    .contact-info {
      margin-top: 20px;
      text-align: left;
    }
    .contact-info a {
      /* add some right margin to separate the links */
      margin-right: 20px;
      font-size: 30px;
    }
    h2 {
      text-align: left;
    }
  </style>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.1.0/css/all.min.css">
	</head>
	<body>
    <div class="wrapper">
      <nav class="my-nav">
        <a href="#about-me">Обо мне</a>
        <a href="#how-it-works">Как проходит обучение</a>
        <a href="#reviews">Отзывы</a>
        <a href="#contacts">Контакты</a>
      </nav>
      <img src="pics/prof.jpg" class="my-image" width="300">
    </div>
		<div class="container">
    		<div class="blurb">
        		<h2 id="about-me">Обо мне</h2>
         <!-- add content for the "Обо мне" section here -->
    		</div><!-- /.blurb -->

        <div id="how-it-works">
            <h2>Как проходит обучение</h2>
            <!-- add content for the "Как проходит обучение" section here -->
        </div>

        <div id="reviews">
            <h2>Отзывы</h2>
            <!-- add content for the "Отзывы" section here -->
        </div>

        <div id="contacts">
            <h2>Контакты</h2>
            <div class="contact-info">
              <a href="https://telegram.me/easy_breezy_english"><i class="fab fa-telegram-plane"></i></a>
              <a href="mailto:easy2breezy@yandex.ru"><i class="fas fa-envelope"></i></a>
            </div>
        </div>

		</div><!-- /.container -->

</body>
</html>
