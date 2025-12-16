<html lang="ru">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>P4P Рейтинг</title>

<link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700&display=swap" rel="stylesheet">

<style>
*{
  margin:0;
  padding:0;
  box-sizing:border-box;
  font-family:'Inter',sans-serif;
}

body{
  min-height:100vh;
  background:radial-gradient(circle at top, #222 0%, #0b0b0b 65%);
  display:flex;
  justify-content:center;
  padding:30px;
  color:#fff;
}

/* ===== MAIN CONTAINER ===== */
.container{
  width:100%;
  max-width:1100px;
  background:linear-gradient(180deg,#1a1a1a,#111);
  border-radius:18px;
  box-shadow:0 25px 60px rgba(0,0,0,.7);
  overflow:hidden;
}

/* ===== HEADER ===== */
.header{
  display:flex;
  justify-content:space-between;
  align-items:center;
  padding:22px 28px;
  background:linear-gradient(180deg,#1c1c1c,#141414);
  border-bottom:2px solid #e60000;
}

.header h1{
  color:#e60000;
  font-size:26px;
  font-weight:700;
}

.header a{
  background:#e60000;
  color:#fff;
  text-decoration:none;
  padding:10px 20px;
  border-radius:10px;
  font-weight:600;
}

/* ===== TABLE ===== */
table{
  width:100%;
  border-collapse:collapse;
}

thead tr{
  background:#e60000;
}

th{
  padding:16px;
  font-size:18px;
  text-align:center;
}

tbody tr{
  height:110px;
}

tbody tr:nth-child(odd){
  background:rgba(255,255,255,0.02);
}

td{
  text-align:center;
  font-size:16px;
}

/* ===== PHOTO ===== */
.photo{
  width:72px;
  height:72px;
  border-radius:50%;
  overflow:hidden;
  margin:auto;
  border:3px solid #e60000;
}

.photo img{
  width:100%;
  height:100%;
  object-fit:cover;
}

/* ===== MOBILE ===== */
@media(max-width:600px){
  th,td{font-size:14px}
  .photo{width:56px;height:56px}
  .header h1{font-size:20px}
}
</style>
</head>

<body>

<div class="container">

  <div class="header">
    <h1>P4P Рейтинг</h1>
    <a href="https://AlishkaNepo.github.io/UFC-S/" target="_blank">UFC 344</a>
  </div>

  <table>
    <thead>
      <tr>
        <th>Место</th>
        <th>Фото</th>
        <th>Имя</th>
      </tr>
    </thead>

    <tbody>
      <tr>
        <td>#1</td>
        <td>
          <div class="photo"><img src="tomi.jpg"></div>
        </td>
        <td>Танат</td>
      </tr>

      <tr>
        <td>#2</td>
        <td>
          <div class="photo"><img src="ali.jpg"></div>
        </td>
        <td>Али</td>
      </tr>

      <tr>
        <td>#3</td>
        <td>
          <div class="photo"><img src="beka2.jpg"></div>
        </td>
        <td>Бексултан</td>
      </tr>

      <tr>
        <td>#4</td>
        <td>
          <div class="photo"><img src="era.jpg"></div>
        </td>
        <td>Ерасыл</td>
      </tr>
    </tbody>
  </table>

</div>

</body>
</html>
