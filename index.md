<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Document</title>
    <style>
      /* .css-selector {
        background: linear-gradient(324deg, #00ffbd, #f5924f);
        background-size: 400% 400%;
        height: 500px;
        animation: AnimationName 3s ease infinite;
      }

      @keyframes AnimationName {
        0% {
          background-position: 51% 0%;
        }
        50% {
          background-position: 50% 100%;
        }
        100% {
          background-position: 51% 0%;
        }
      } */
      .hinh {
        transition: all 2s;
        border-radius: 50%;
        margin-right: 60px;
      }
      .hinh:hover {
        width: 128px;
      }
      .hinh2 {
        transition: all 2s;
        opacity: 0.1;
      }
      .hinh2:hover {
        opacity: 1;
      }
    </style>
  </head>
  <body>
    <div class="wrapper">
      <h1 style="color: purple;">Đây là công chúa Linh Leo, một nàng công chúa cực kì cute phô mai que, hover vào cô ấy để thấy điều kì diệu nhé</h1>
      <img class="hinh" src="em.jpg" width="64px">
      <img class="hinh2" src="em2.jpg" width="256px">
    </div>
  </body>
</html>
