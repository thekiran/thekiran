<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <style>
    body {
      margin: 0;
      padding: 0;
      font-family: Arial, sans-serif;
      background: linear-gradient(45deg, #ff00ff, #00ffff);
      height: 100vh;
      display: flex;
      justify-content: center;
      align-items: center;
      color: white;
      overflow: hidden;
    }

    .content-container {
      display: flex;
      flex-direction: column;
      align-items: center;
      text-align: center;
      background-color: rgba(0, 0, 0, 0.7);
      border-radius: 10px;
      padding: 40px;
      box-shadow: 0 0 20px 10px rgba(255, 0, 255, 0.7);
      backdrop-filter: blur(5px);
      width: 80%;
    }

    .neon-text {
      font-size: 32px;
      font-weight: bold;
      color: #fff;
      text-shadow: 0 0 10px rgba(255, 0, 255, 0.7), 0 0 20px rgba(0, 255, 255, 0.7);
    }

    .badge-container {
      display: flex;
      justify-content: center;
      gap: 20px;
      margin-top: 20px;
    }

    .badge-container img {
      width: 100px;
      filter: drop-shadow(0 0 5px rgba(255, 0, 255, 0.8));
    }

    .stats-container {
      display: flex;
      justify-content: space-around;
      width: 100%;
      margin-top: 20px;
    }

    .stats-container img {
      width: 45%;
      border-radius: 10px;
      box-shadow: 0 0 10px 5px rgba(0, 255, 255, 0.6);
    }

    .neon-gif {
      margin-top: 30px;
      width: 70%;
      border-radius: 10px;
      box-shadow: 0 0 15px 5px rgba(0, 255, 255, 0.6);
    }
  </style>
</head>
<body>

  <div class="content-container">
    <div class="neon-text">
      #Hello! 👋 <br>
      I'm Muhammed Emin Kıran. 🌟 <br> 
      I’m passionate about software development and cybersecurity.
    </div>

    <div class="badge-container">
      <a href="https://wakatime.com/@cef45e7a-ee97-4a47-a568-86349b210b0d">
        <img src="https://wakatime.com/badge/user/cef45e7a-ee97-4a47-a568-86349b210b0d.svg" alt="Wakatime">
      </a>
      <img src="https://profile-counter.glitch.me/888KIRAN/count.svg" alt="Visitor Count">
    </div>

    <div class="stats-container">
      <img src="https://github-readme-stats.vercel.app/api?username=888KIRAN&show_icons=true&theme=radical&count_private=true" alt="GitHub Stats">
      <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=888KIRAN&layout=compact&theme=radical" alt="Top Languages">
    </div>

    <img src="https://github-readme-activity-graph.vercel.app/graph?username=888KIRAN&theme=radical" alt="Activity Graph">

    <div style="display: flex; align-items: center; justify-content: center; margin-top: 20px;">
      <img src="https://github-readme-stats.vercel.app/api/wakatime?username=888KIRAN&apikey=waka_24e9ea78-a54c-47be-8523-65f01926dbf6&theme=radical" alt="Wakatime Stats" style="margin-right: 20px;"/>
      <img src="https://media.giphy.com/media/kg9fAQryp5fMY/giphy.gif?cid=ecf05e470wh12s9k2i5i4cih23b1749b85cx2yq7bk4hx9yg&ep=v1_gifs_related&rid=giphy.gif&ct=g" alt="3D Animation" />
    </div>
  </div>

</body>
</html>
