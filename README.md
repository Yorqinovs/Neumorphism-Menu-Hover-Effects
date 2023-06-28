# Neumorphism-Menu-Hover-Effects
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <link
      rel="stylesheet"
      href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css"
    />
    <!--<link rel="stylesheet" href="style.css" />-->
    <title>Neumorphism Navigation bar| Yorqinovs</title>
    <style>
      @import url("https://fonts.googleapis.com/css2?family=Baloo+Bhai+2&display=swap");
      * {
        padding: 0;
        margin: 0;
        box-sizing: border-box;
        list-style: none;
        text-decoration: none;
        font-family: "Baloo Bhai 2", cursive;
      }
      body {
        height: 100vh;
        display: grid;
        place-items: center;
        background: #d1d8ec;
      }
      .card {
        height: 40px;
        width: 180px;
        border-radius: 5px;
        background: #d1d8ec;
        box-shadow: 3px 3px 5px #54565e, -3px -3px 15px #ffffff;
      }
      .card ul {
        display: flex;
        justify-content: space-between;
        margin: 8px 5px;
      }
      .card ul li {
        height: 25px;
        width: 20px;
        overflow: hidden;
        border-radius: 3px;
        padding: 4px;
        line-height: 1;
        transition: all 0.3s ease;
      }
      .card ul li a {
        color: rgba(0, 0, 0, 0.397);
      }
      .card ul li a i {
        margin-bottom: 15px;
      }
      .card ul li a span {
        font-size: 14px;
        transition: 0.5s;
      }
      .card ul li:hover {
        width: 90px;
        background: linear-gradient(
          90deg,
          rgba(153, 59, 215, 1) 0%,
          rgba(227, 99, 221, 1) 83%,
          rgba(255, 133, 133, 1) 100%
        );
        box-shadow: -5px -5px 10px #cacaca, 5px 5px 10px #f6f6f6;
      }
      .card ul li:hover a {
        color: #fff;
      }
      .card ul li:hover a i {
        padding-right: 5px;
        margin-right: 5px;
        border-right: 1px solid rgba(0, 0, 0, 0.096);
      }
    </style>
  </head>
  <body>
    <div class="card">
      <ul>
        <li class="">
          <a href=""><i class="fa fa-home"></i><span>Home</span></a>
        </li>
        <li>
          <a href=""><i class="fa fa-user"></i><span>Profile</span></a>
        </li>
        <li>
          <a href=""><i class="fa fa-cog"></i><span>Setting</span></a>
        </li>
        <li>
          <a href=""><i class="fa fa-bookmark"></i><span>Save</span></a>
        </li>
      </ul>
    </div>
  </body>
</html>
