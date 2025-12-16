<html lang="ru">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>P4P Рейтинг Бойцов</title>

  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700&display=swap" rel="stylesheet">

  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: 'Inter', sans-serif;
    }

    body {
      background: #111;
      color: #fff;
      padding: 15px;
    }

    header {
      display: flex;
      justify-content: space-between;
      align-items: center;
      background: #1a1a1a;
      padding: 15px 20px;
      border-bottom: 2px solid #e60000;
      margin-bottom: 20px;
    }

    .logo {
      font-size: 24px;
      font-weight: 700;
      color: #e60000;
    }

    header a {
      background: #e60000;
      color: #fff;
      padding: 8px 16px;
      border-radius: 6px;
      text-decoration: none;
      font-weight: 600;
      font-size: 14px;
    }

    table {
      width: 100%;
      border-collapse: collapse;
      background: #1a1a1a;
      border: 2px solid #e60000;
      border-radius: 12px;
      overflow: hidden;
    }

    thead {
      background: #e60000;
    }

    th {
      padding: 15px;
      font-size: 18px;
    }

    td {
      padding: 14px;
      text-align: center;
    }

    tbody tr:nth-child(even) {
      background: #161616;
    }

    .photo {
      width: 70px;
      height: 70px;
      border-radius: 50%;
      overflow: hidden;
      border: 3px solid #e60000;
      margin: auto;
    }

    .photo img {
      width: 100%;
      height: 100%;
      object-fit: cover;
    }

    @media (max-width: 480px) {
      th, td {
        font-size: 14px;
        padding: 10px;
      }

      .photo {
        width: 55px;
        height: 55px;
      }

      .logo {
        font-size: 20px;
      }
    }
  </style>
</head>
<body>

<header>
  <div class="logo">P4P Рейтинг</div>
  <a href="https://AlishkaNepo.github.io/UFC-S/" target="_blank">UFC 344</a>
</header>

<table>
  <thead>
    <tr>
      <th>Место</th>
      <th>Фото</th>
      <th>Боец</th>
    </tr>
  </thead>

  <tbody>
    <tr>
      <td>#1</td>
      <td>
        <div class="photo">
          <img src="tomi.jpg" alt="Танат">
        </div>
      </td>
      <td>Танат</td>
    </tr>

    <tr>
      <td>#2</td>
      <td>
        <div class="photo">
          <img src="ali.jpg" alt="Али">
        </div>
      </td>
      <td>Али</td>
    </tr>

    <tr>
      <td>#3</td>
      <td>
        <div class="photo">
          <img src="beka2.jpg" alt="Бексултан">
        </div>
      </td>
      <td>Бексултан</td>
    </tr>

    <tr>
      <td>#4</td>
      <td>
        <div class="photo">
          <img src="era.jpg" alt="Ерасыл">
        </div>
      </td>
      <td>Ерасыл</td>
    </tr>
  </tbody>
</table>

</body>
</html>
