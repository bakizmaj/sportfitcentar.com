<!DOCTYPE html>
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
      text-align: center;
      font-size: 36px;
      font-weight: bold;
      margin-top: 50px;
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
  </div>
  <div class="images">
    <img class="image" src="physiotherapy1.jpg" alt="Physiotherapy 1">
    <img class="image" src="physiotherapy2.jpg" alt="Physiotherapy 2">
    <img class="image" src="physiotherapy3.jpg" alt="Physiotherapy 3">
  </div>
  <div class="description">
    <p>At Sport Fit Center, we provide personalized physiotherapy services to help you recover from injury and improve your physical performance. Our team of expert therapists use the latest techniques and equipment to help you achieve your goals and live a pain-free life.</p>
  </div>
  <div class="contact">
    <h2>Contact Us</h2>
    <p>Phone: (123) 456-7890</p>
    <p>Email: sportfitcenter@email.com</p>
    <p>Address: 123 Main St, Anytown USA 12345</p>
  </div>
  <div class="form">
    <h2>Subscribe to Our Newsletter</h2>
    <form>
      <input type="email" placeholder="Enter your email">
      <input type="submit">
