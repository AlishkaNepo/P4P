<html lang="ru">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>P4P Рейтинг Бойцов</title>

  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700&display=swap" rel="stylesheet">

  <style>
    *{
      margin:0;
      padding:0;
      box-sizing:border-box;
      font-family:'Inter', sans-serif;
    }

    body{
  background:#111;
  color:#fff;
  min-height:100vh;
  display:flex;
  justify-content:center;
  padding:0; /* ← убрали отступы */
}


    /* ===== CONTAINER ===== */
    .container{
  width:1250px;          /* ← фиксированная ширина */
  max-width:1250px;
  background:#1a1a1a;
  border-radius:18px;
  overflow:hidden;
  border:2px solid #e60000;
  margin:0 auto 0 -40px;         /* ← центр по экрану */
}


    /* ===== HEADER ===== */
    .header{
      display:flex;
      justify-content:space-between;
      align-items:center;
      padding:16px 20px;
      border-bottom:2px solid #e60000;
    }

    .logo{
      font-size:24px;
      font-weight:700;
      color:#e60000;
    }

    .header a{
      background:#e60000;
      color:#fff;
      text-decoration:none;
      padding:8px 14px;
      border-radius:6px;
      font-weight:600;
      font-size:14px;
    }

    /* ===== TABLE HEADER ===== */
    .table-head{
      display:grid;
      grid-template-columns: 1fr 1fr 2fr;
      background:#e60000;
      font-size:18px;
      font-weight:600;
    }

    .table-head div{
      padding:15px;
      text-align:center;
    }

    /* ===== ROWS ===== */
    .row{
      display:grid;
      grid-template-columns: 1fr 1fr 2fr;
      align-items:center;
      padding:14px 0;
    }

    .row:nth-child(even){
      background:#161616;
    }

    .cell{
      text-align:center;
      font-size:16px;
    }

    /* ===== PHOTO ===== */
    .photo{
      width:70px;
      height:70px;
      border-radius:50%;
      overflow:hidden;
      border:3px solid #e60000;
      margin:auto;
    }

    .photo img{
      width:100%;
      height:100%;
      object-fit:cover;
    }

    /* ===== MOBILE ===== */
    @media(max-width:480px){
      .table-head, .row{
        grid-template-columns: 1fr 1fr 1.5fr;
      }

      .table-head div{
        font-size:14px;
        padding:10px;
      }

      .cell{
        font-size:14px;
      }

      .photo{
        width:55px;
        height:55px;
      }

      .logo{
        font-size:20px;
      }
    }
  </style>
</head>

<body>

<div class="container">

  <div class="header">
    <div class="logo">P4P Рейтинг</div>
    <a href="https://AlishkaNepo.github.io/UFC-S/" target="_blank">UFC 344</a>
  </div>

  <div class="table-head">
    <div>Место</div>
    <div>Фото</div>
    <div>Имя</div>
  </div>

  <div class="row">
    <div class="cell">#1</div>
    <div class="cell">
      <div class="photo"><img src="tomi.jpg" alt="Танат"></div>
    </div>
    <div class="cell">Танат</div>
  </div>

  <div class="row">
    <div class="cell">#2</div>
    <div class="cell">
      <div class="photo"><img src="ali.jpg" alt="Али"></div>
    </div>
    <div class="cell">Али</div>
  </div>

  <div class="row">
    <div class="cell">#3</div>
    <div class="cell">
      <div class="photo"><img src="beka2.jpg" alt="Бексултан"></div>
    </div>
    <div class="cell">Бексултан</div>
  </div>

  <div class="row">
    <div class="cell">#4</div>
    <div class="cell">
      <div class="photo"><img src="era.jpg" alt="Ерасыл"></div>
    </div>
    <div class="cell">Ерасыл</div>
  </div>

</div>

</body>
</html>
