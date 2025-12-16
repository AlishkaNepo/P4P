<html lang="ru">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>P4P Рейтинг Бойцов</title>

  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700&display=swap" rel="stylesheet">

  <style>
    * { margin:0; padding:0; box-sizing:border-box; font-family:'Inter', sans-serif; }
    body { background-color:#111; color:#fff; padding:15px; }

    header {
      display:flex;
      justify-content:space-between;
      align-items:center;
      padding:15px;
      background:#1a1a1a;
      border-bottom:2px solid #e60000;
      margin-bottom:20px;
    }

    header .logo {
      font-size:24px;
      font-weight:700;
      color:#e60000;
    }

    header a {
      padding:8px 14px;
      background:#e60000;
      color:#fff;
      border-radius:6px;
      font-weight:600;
      text-decoration:none;
      font-size:14px;
    }

    table {
      width:100%;
      border-collapse:collapse;
      background:#1a1a1a;
      border:2px solid #e60000;
      border-radius:12px;
      overflow:hidden;
    }

    th, td { padding:15px; text-align:center; }
    th { background:#e60000; font-size:18px; }

    tr:nth-child(even) { background:#161616; }

    .photo {
      width:70px;
      height:70px;
      border-radius:50%;
      overflow:hidden;
      border:3px solid #e60000;
      margin:auto;
    }

    .photo img {
      width:100%;
      height:100%;
      object-fit:cover;
    }

    /* Мобильная адаптация */
    @media screen and (max-width:480px){
      th, td { padding:10px; font-size:14px; }
      .photo { width:55px; height:55px; }
      header .logo { font-size:20px; }
      table { border-width:1px; }
    }
  </style>
</head>
<body>

<header>
  <div class="logo">P4P Рейтинг</div>
  <a href="https://AlishkaNepo.github.io/UFC-S/">UFC 344</a>
</header>

<table>
  <tr>
    <th>Место</th>
    <th>Фото</th>
    <th>Имя</th>
  </tr>

  <tr>
    <td>#1</td>
    <td><div class="photo"><img src="tomi.jpg" alt="Танат"></div></td>
    <td>Танат</td>
  </tr>

  <tr>
    <td>#2</td>
    <td><div class="photo"><img src="ali.jpg" alt="Али"></div></td>
    <td>Али</td>
  </tr>

  <tr>
    <td>#3</td>
    <td><div class="photo"><img src="beka2.jpg" alt="Бексултан"></div></td>
    <td>Бексултан</td>
  </tr>

  <tr>
    <td>#4</td>
    <td><div class="photo"><img src="era.jpg" alt="Ерасыл"></div></td>
    <td>Ерасыл</td>
  </tr>
</table>

</body>
</html>
