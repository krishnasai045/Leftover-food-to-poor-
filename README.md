<!DOCTYPE html><html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Leftover Food Donation</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background: #f5f5f5;
      margin: 0;
      padding: 0;
    }
    .container {
      max-width: 600px;
      margin: 50px auto;
      background: #fff;
      padding: 20px;
      box-shadow: 0 0 10px rgba(0,0,0,0.1);
      border-radius: 10px;
    }
    h2 {
      text-align: center;
      color: #333;
    }
    form {
      display: flex;
      flex-direction: column;
    }
    label {
      margin-top: 10px;
    }
    input, textarea, button {
      padding: 10px;
      margin-top: 5px;
      border: 1px solid #ccc;
      border-radius: 5px;
    }
    button {
      background-color: #4CAF50;
      color: white;
      font-size: 16px;
      cursor: pointer;
      margin-top: 20px;
    }
    button:hover {
      background-color: #45a049;
    }
  </style>
</head>
<body>
  <div class="container">
    <h2>Leftover Food Donation Form</h2>
    <form action="https://formspree.io/f/your-id-here" method="POST">
      <label for="name">Name *</label>
      <input type="text" id="name" name="name" required /><label for="address">Address *</label>
  <input type="text" id="address" name="address" required />

  <label for="type">Type of Food *</label>
  <input type="text" id="type" name="type" required />

  <label for="quantity">Quantity *</label>
  <input type="text" id="quantity" name="quantity" required />

  <label for="contact">Contact Number *</label>
  <input type="text" id="contact" name="contact" required />

  <label for="time">Preferred Pickup Time *</label>
  <input type="text" id="time" name="time" required />

  <button type="submit">Submit Donation</button>
</form>

  </div>
</body>
</html>