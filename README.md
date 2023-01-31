
<html>
<head>
  <title>Sport Fit Center</title>
  <style>
    /* Add your CSS styles here */
    body {
      background-color: lightblue;
      font-family: sans-serif;
    }
    .header {
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 20px;
    }
    .header h1 {
      font-size: 36px;
      font-weight: bold;
    }
    .navigation {
      display: flex;
      justify-content: center;
      list-style: none;
      margin: 0;
      padding: 0;
    }
    .navigation li {
      margin: 0 20px;
    }
    .navigation a {
      text-decoration: none;
      color: white;
      font-size: 18px;
    }
    .images {
      display: flex;
      justify-content: space-around;
      margin-top: 50px;
    }
    .image {
      width: 300px;
      height: 200px;
      object-fit: cover;
      border-radius: 10px;
      margin-bottom: 50px;
      box-shadow: 5px 5px 10px gray;
    }
    .description {
      text-align: center;
      font-size: 18px;
      margin-top: 20px;
    }
    .contact {
      text-align: center;
      margin-top: 50px;
    }
    .form {
      display: flex;
      flex-direction: column;
      align-items: center;
      margin-top: 50px;
    }
    .form input[type="email"] {
      width: 50%;
      padding: 10px;
      margin-bottom: 20px;
      border-radius: 10px;
      border: none;
      font-size: 18px;
    }
    .form input[type="submit"] {
      width: 30%;
      padding: 10px;
      background-color: white;
      color: lightblue;
      border-radius: 10px;
      border: none;
      cursor: pointer;
      font-size: 18px;
    }
  </style>
</head>
<body>
  <div class="header">
    <h1>Sport Fit Center</h1>
    <ul class="navigation">
      <li><a href="about.html">About</a></li>
      <li><a href="services.html">Services</a></li>
      <li><a href="contact.html">Contact</a></li>
    </ul>
  </div>
</body>
</html>
