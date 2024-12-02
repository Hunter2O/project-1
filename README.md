<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Airtel - Homepage</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #90EE90;
        }
        .header-container {
            background-color: #90EE90;
            color: red;
            display: flex;
            justify-content: flex-start; /* Align items to the left */
            align-items: center;
            padding: 20px;
        }
        header h1 {
            margin: 0;
            color: #e60000;
            margin-right: 20px; /* Add spacing between the logo and navbar */
        }
        .navbar {
            display: flex;
            flex-grow: 0; /* Prevent navbar from stretching */
        }
        .navbar a {
            color: black;
            padding: 14px 20px;
            text-decoration: none;
            text-align: center;
            margin-right: 10px; /* Add spacing between links */
        }
        .navbar a:hover {
            color: red; /* Change text color to red on hover */
        }
        .rectangle-button {
            background-color: #e60000;
            color: white;
            padding: 15px 30px;
            font-size: 18px;
            font-weight: bold;
            border: none;
            text-transform: uppercase;
            text-decoration: none;
            border-radius: 5px;
            cursor: pointer;
            margin-left: auto; /* Push the button to the far right */
        }
        .rectangle-button:hover {
            background-color: #cc0000;
        }
        .footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 20px;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
        .content-container {
            display: flex;
            justify-content: space-between;
            align-items: center;
            margin-top: 40px;
        }
        .welcome-message {
            font-size: 50px;
            color: #e60000;
            margin-top: 150px;
            margin-left: 20px;
            white-space: pre-line;
        }
        .nourish-message {
            font-size: 30px;
            color: #333;
            margin-left: 20px;
            margin-top: 20px;
        }
        .image-container {
            width: 50%; /* Set the image container to take up 50% of the width */
            display: flex;
            justify-content: flex-end;
        }
        .airtel-5g-image {
            width: 80%; /* Adjust the image size */
            max-width: 500px; /* Set a max width for better display */
            margin-right: 20px;
        }
        .buttons-container {
            display: flex;
            justify-content: flex-start;
            margin-top: 30px;
            margin-left: 20px;
        }
        .buttons-container a {
            color: white;
            padding: 15px 30px;
            font-size: 18px;
            font-weight: bold;
            border-radius: 5px;
            margin-right: 15px;
            text-decoration: none;
            text-align: center;
        }
        .services-button {
            background-color: #4CAF50;
        }
        .services-button:hover {
            background-color: #45a049;
        }
        .contact-button {
            background-color: #e60000;
        }
        .contact-button:hover {
            background-color: #cc0000;
        }
    </style>
</head>
<body>
  <div class="header-container">
        <h1>Airtel</h1>
        <div class="navbar">
            <a href="#home">Home</a>
            <a href="#aboutus">About Us</a>
            <a href="#services">Services</a>
            <a href="#contactus">Contact Us</a>
        </div>
        <a href="#" class="rectangle-button">Click for Quotation &#x1F4AC;</a>
    </div>
       <div class="content-container">
        <div>
            <p class="welcome-message">Airtel Welcomes You to
             the 5G World!</p>
             <p class="nourish-message">Let's nourish the new technology.</p><div class="buttons-container">
                <a href="#services" class="services-button">Services</a>
                <a href="#contactus" class="contact-button">Contact Us</a>
            </div>
        </div>
        <div class="image-container">
            <img src="C:\Users\ameen\Downloads\images.jpg" alt="Airtel 5G" class="airtel-5g-image"> <!-- Replace with your image URL -->
        </div>
    </div>
</body>
</html>

