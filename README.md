# movie-ticket
Movie Ticket E-Ticket
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>PVR INOX E-Ticket</title>
  <link href="https://fonts.googleapis.com/css2?family=Roboto&display=swap" rel="stylesheet">
  <style>
    body {
      margin: 0;
      font-family: 'Roboto', sans-serif;
      background-color: #f4f4f4;
      color: #333;
    }
    .container {
      max-width: 550px;
      margin: 50px auto;
      background: #fff;
      border-radius: 8px;
      box-shadow: 0 0 15px rgba(0,0,0,0.1);
      padding: 25px;
    }
    .header {
      text-align: center;
    }
    .header img {
      height: 40px;
    }
    .ticket-info {
      margin-top: 20px;
      font-size: 15px;
      line-height: 1.7;
    }
    .ticket-info p {
      margin: 8px 0;
    }
    .qr-section {
      text-align: center;
      margin: 25px 0;
    }
    .qr-section img {
      width: 150px;
      height: 150px;
      border: 1px solid #ddd;
      padding: 8px;
    }
    .footer {
      font-size: 13px;
      color: #777;
      text-align: center;
      line-height: 1.6;
    }
    .footer a {
      color: #1976d2;
      text-decoration: none;
    }
  </style>
</head>
<body>
  <div class="container">
    <div class="header">
      <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/5/55/PVR_Cinemas_Logo.svg/2560px-PVR_Cinemas_Logo.svg.png" alt="PVR INOX Logo">
      <h2>E-Ticket Confirmation</h2>
    </div>
    <div class="ticket-info">
      <p><strong>Movie:</strong> From the World of John Wick: Ballerina</p>
      <p><strong>Date:</strong> 15 jun, Sunday</p>
      <p><strong>Time:</strong> 23:15 (24-hour format)</p>
      <p><strong>Theatre:</strong> PVR INOX HIMALIA MALL</p>
      <p><strong>Screen:</strong> AUDI - SCREEN 2</p>
      <p><strong>Seats:</strong> D:1, D:2</p>
      <p><strong>Total Amount:</strong> Rs 540</p>
      <p><strong>Transaction ID:</strong> 546420</p>
    </div>
    <div class="qr-section">
      <img src="https://api.qrserver.com/v1/create-qr-code/?size=150x150&data=https://pvrinox.com/PVRCIN/Irh3KE" alt="QR Code">
    </div>
    <div class="footer">
      Your ticket has been generated for <strong>From the World of John Wick: Ballerina</strong> on <strong>Sunday</strong> at <strong>11:15</strong>.<br>
      Venue: <strong>PVR INOX HIMALIA MALL (AUDI - SCREEN 2)</strong><br>
      2 Seat(s): <strong>D:1, D:2</strong><br>
      Total Amount: <strong>Rs 540</strong><br>
      Transaction ID: <strong>546420</strong><br><br>
      Download your e-ticket from <a href="https://pvrinox.com/PVRCIN/Irh3KE">https://pvrinox.com/PVRCIN/Irh3KE</a><br>
      GST Invoice: <a href="https://pvrinox.com/PVRCIN/1rh3KQ">https://pvrinox.com/PVRCIN/1rh3KQ</a><br><br>
      Please show this QR code at the theatre to enter.<br>
      Physical ticket is not required.<br>
      Thank you for choosing PVR INOX!
    </div>
  </div>
</body>
</html>
