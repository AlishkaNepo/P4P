<html lang="ru">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1, maximum-scale=1" />
  <title>P4P Рейтинг — Mobile</title>

  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700&display=swap" rel="stylesheet">

  <style>
    :root{
      --bg:#0f0f0f;
      --card:#1a1a1a;
      --red:#e60000;
      --text:#ffffff;
      --muted:#bdbdbd;
    }

    *{
      margin:0;
      padding:0;
      box-sizing:border-box;
      font-family:'Inter',sans-serif;
      -webkit-tap-highlight-color: transparent;
    }

    body{
      background:var(--bg);
      color:var(--text);
    }

    /* HEADER */
    header{
      position:sticky;
      top:0;
      z-index:10;
      background:#141414;
      border-bottom:2px solid var(--red);
    }

    .header-inner{
      display:flex;
      justify-content:space-between;
      align-items:center;
      padding:14px 16px;
    }

    .logo{
      font-size:18px;
      font-weight:700;
      color:var(--red);
    }

    .btn{
      background:var(--red);
      color:#fff;
      text-decoration:none;
      padding:7px 14px;
      border-radius:20px;
      font-size:13px;
      font-weight:600;
    }

    /* LIST */
    .list{
      padding:12px 10px 20px;
    }

    .fighter-card{
      display:flex;
      align-items:center;
      gap:12px;
      background:var(--card);
      border:2px solid var(--red);
      border-radius:14px;
      padding:12px;
      margin-bottom:12px;
    }

    .rank{
      font-size:18px;
      font-weight:700;
      color:var(--red);
      width:36px;
      text-align:center;
    }

    .photo{
      width:56px;
      height:56px;
      border-radius:50%;
      overflow:hidden;
      border:3px solid var(--red);
      flex-shrink:0;
    }

    .photo img{
      width:100%;
      height:100%;
      object-fit:cover;
    }

    .info{
      display:flex;
      flex-direction:column;
    }

    .name{
      font-size:15px;
      font-weight:600;
    }

    .subtitle{
      font-size:12px;
      color:var(--muted);
    }

    /* SMALL PHONES */
    @media (max-width:360px){
      .photo{width:50px;height:50px;}
      .name{font-size:14px;}
      .rank{font-size:16px;}
    }
  </style>
</head>
<body>

<header>
  <div class="header-inner">
    <div class="logo">P4P Рейтинг</div>
    <a class="btn" href="https://AlishkaNepo.github.io/UFC-S/" target="_blank">UFC 344</a>
  </div>
</header>

<section class="list">

  <div class="fighter-card">
    <div class="rank">#1</div>
    <div class="photo"><img src="tomi.jpg" alt="Танат"></div>
    <div class="info">
      <div class="name">Танат</div>
      <div class="subtitle">Pound for Pound</div>
    </div>
  </div>

  <div class="fighter-card">
    <div class="rank">#2</div>
    <div class="photo"><img src="ali.jpg" alt="Али"></div>
    <div class="info">
      <div class="name">Али</div>
      <div class="subtitle">Pound for Pound</div>
    </div>
  </div>

  <div class="fighter-card">
    <div class="rank">#3</div>
    <div class="photo"><img src="beka2.jpg" alt="Бексултан"></div>
    <div class="info">
      <div class="name">Бексултан</div>
      <div class="subtitle">Pound for Pound</div>
    </div>
  </div>

  <div class="fighter-card">
    <div class="rank">#4</div>
    <div class="photo"><img src="era.jpg" alt="Ерасыл"></div>
    <div class="info">
      <div class="name">Ерасыл</div>
      <div class="subtitle">Pound for Pound</div>
    </div>
  </div>

  <div class="fighter-card">
    <div class="rank">#5</div>
    <div class="photo"><img src="jahan.jpg" alt="Жахан"></div>
    <div class="info">
      <div class="name">Жахан</div>
      <div class="subtitle">Pound for Pound</div>
    </div>
  </div>

  <div class="fighter-card">
    <div class="rank">#6</div>
    <div class="photo"><img src="roma.jpg" alt="Рома"></div>
    <div class="info">
      <div class="name">Рома</div>
      <div class="subtitle">Pound for Pound</div>
    </div>
  </div>

</section>

</body>
</html>
