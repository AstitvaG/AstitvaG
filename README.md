<!-- <html>

<head>
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@100&display=swap" rel="stylesheet">
  <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@300&display=swap" rel="stylesheet">
</head>

<body> -->
  <div class="background">
    <div class="container">
      <div class="photo-section">
        <img class="img" src="https://drive.google.com/uc?export=view&id=1IPtbmFFWZIl1OUsaTMjXlpDV7-qccXa-" />
      </div>
      <div class="info-section">
        <div class="p-name">
          Astitva
        </div>
        <div class="p-role">
          Developer
        </div>
      </div>
      <div class="logo-section">
        
      </div>
    </div>
  </div>
  <style>
    .background {
      /*   background: linear-gradient(90deg, #efd5ff 0%, #515ada 100%); */
      background: white;
      background: rgb(14, 17, 22);
      padding: 20px;
    }

    .container {
      height: 300px;
      width: 500px;
      border-radius: 20px;
      border-style: solid;
      border-color: #777777;
      display: grid;
      padding-left: 40px;
      grid-template-areas:
        'logo logo logo photo'
        'info info info photo';
    }

    .photo-section {
      grid-area: photo;
    }

    .info-section {
      grid-area: info;
    }

    .logo-section {
      grid-area: logo;
    }

    .logo-section {
      /*   color : #888888; */
      color: #d96b30;
      font-size: 56px;
      margin-top: 30px;
    }

    .img {
      height: 300px;
      /*   filter: drop-shadow(10px 10px 24px rgba(0,0,0,0.37)); */
    }

    .p-name {
      font-family: 'Roboto', sans-serif;
      font-size: 80px;
      font-weight: 100;
      color: #888888;
    }

    .p-role {
      font-family: 'Roboto', sans-serif;
      font-size: 32px;
      font-weight: 300;
      color: #d96b30 !important;
      margin-top: -20px;
    }
  </style>
<!-- </body>

</html> -->
