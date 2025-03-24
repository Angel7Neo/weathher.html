<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Weather Forecast</title>
    <style>
      body {
        font-family: Arial, sans-serif;
        text-align: center;
        background-color: #ffffff;
        margin: 0;
        padding: 20px;
      }

      h1 {
        font-size: 28px;
        font-weight: bold;
        color: #1a73e8;
      }

      h2 {
        font-size: 22px;
        color: #333;
      }

      ul {
        list-style: none;
        padding: 0;
      }

      li {
        margin: 15px 0;
        padding: 10px;
        border-radius: 8px;
        transition: box-shadow 0.3s ease-in-out;
      }

      li:hover {
        box-shadow: 0 4px 10px rgba(255, 192, 203, 0.6);
      }

      h3 {
        margin: 0;
        font-weight: bold;
        display: flex;
        align-items: center;
        justify-content: center;
        gap: 8px;
      }

      p {
        margin: 5px 0;
        font-size: 18px;
      }

      .weather-icon {
        font-size: 24px;
      }

      button {
        margin-top: 20px;
        padding: 10px 20px;
        font-size: 16px;
        background-color: #1a73e8;
        color: white;
        border: none;
        border-radius: 20px;
        cursor: pointer;
        transition: 0.3s ease-in-out;
        box-shadow: 0px 4px 8px rgba(0, 0, 0, 0.2);
      }

      button:hover {
        background-color: #0056b3;
        box-shadow: 0px 6px 12px rgba(0, 0, 0, 0.3);
      }

      .footer {
        margin-top: 20px;
        font-size: 14px;
        color: #777;
      }
    </style>
  </head>
  <body>
    <h1>🌤 Currently 21° in Pretoria</h1>
    <h2>13° / <strong>23°</strong></h2>

    <ul>
      <li>
        <h3>🌧 Tomorrow</h3>
        <p>10° / <strong>22°</strong></p>
      </li>
      <li>
        <h3>☁️ Saturday</h3>
        <p>15° / <strong>17°</strong></p>
      </li>
      <li>
        <h3>☀️ Sunday</h3>
        <p>25° / <strong>28°</strong></p>
      </li>
    </ul>

    <button>Change city</button>

    <p class="footer">Coded by Angel Dineo Masonganye</p>
  </body>
</html>
