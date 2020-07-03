<!DOCTYPE html>
<html lang="ru">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Project</title>
    <style>
      body,
h1,
h2,
h3,
h4,
p,
a {
  margin: 0;
  font-size: 100%;
  font-weight: normal;
}

.title-text {
  text-align: center;
  font-weight: 500;
  font-size: 40px;
  font-family: cursive;
  margin-top: 10px;
}

.content {
  margin: 50px auto 50px;
  font-size: 0;
  width: 800px;
}

.card {
  display: inline-block;
  box-shadow: 5px 5px 5px rgba(250, 50, 50, 0.5);
  margin-bottom: 50px;
  width: 320px;
  margin-right: 72px;
  padding: 20px;
  border: 2px double red;
}

.card:hover {
  box-shadow: 7px 7px 3px rgba(220, 0, 0, 0.8);
}

.no {
  margin-right: 0;
}

.title {
  color: black;
  font-size: 20px;
  text-align: center;
  font-weight: 600;
  margin-bottom: 5px;
  font-family: cursive;
}

.card-image {
  width: 100%;
  margin-bottom: 15px;
}

.footer {
  height: 200px;
  background-color: #000;
  display: flex;
}

.footer-title {
  color: #fff;
  font-size: 20px;
  margin: auto;
}
    </style>
  </head>
  <body>
    <header class="header">
      <h1 class="title-text">Day and Night</h1>
    </header>
    <section class="content">
      <a href="http://htmlbook.ru/html"
        ><div class="card">
          <h1 class="title">Moon</h1>
          <img
            src="photo-1563630381190-77c336ea545a.jpg"
            class="card-image"
          /></div
      ></a>
      <a href="https://webref.ru/css"
        ><div class="card no">
          <h1 class="title">Sun</h1>
          <img
            src="photo-1532767153582-b1a0e5145009.jpg"
            class="card-image"
          /></div
      ></a>
    </section>
    <footer class="footer">
      <h4 class="footer-title">Сделано 27.06.2020</h4>
    </footer>
  </body>
</html>
