<!DOCTYPE html>
<html lang="ru">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Мир естественных наук</title>
  <style>
    body, html {
      margin: 0;
      padding: 0;
      height: 100%;
      font-family: Arial, sans-serif;
    }

    .background {
      background: url('главная.avif') no-repeat center center fixed;
      background-size: cover;
      height: 100%;
      position: relative;
      display: flex;
      justify-content: center;
      align-items: center;
      text-align: center;
      color: white;
    }

    .overlay {
      background-color: rgba(0, 0, 0, 0.5);
      padding: 50px;
      border-radius: 20px;
    }

    .overlay h1 {
      font-size: 40px;
      margin-bottom: 25px;
    }

    .overlay p {
      font-size: 22px;
      margin-bottom: 20px;
    }

    .overlay ul {
      list-style: none;
      padding: 0;
      font-size: 24px;
    }

    .overlay ul li {
      margin: 10px 0;
    }

    .overlay ul li a {
      color: white;
      text-decoration: none;
    }

    .overlay ul li a:hover {
      text-decoration: underline;
    }
  </style>
</head>
<body>
  <div class="background">
    <div class="overlay">
      <h1>Добро пожаловать в мир естественных наук!</h1>
      <p>На данном сайте вы найдете материал, который будет очень полезен для одиннадцатиклассников, так как учащиеся изучают данный материал в рамках школьных уроков, а также найдете интересные факты для себя по следующим предметам:</p>
      <ul>
        <li><a href="astronomy.html" target="_blank">Физика</a></li>
        <li><a href="file:///C:/Users/User/Desktop/biology.html" target="_blank">Биология</a></li>
        <li><a href="file:///C:/Users/User/Desktop/chemistry.html" target="_blank">Химия</a></li>
        <li><a href="file:///C:/Users/User/Desktop/geography.html" target="_blank">География</a></li> 
      </ul>
    </div>
  </div>
</body>
</html>
