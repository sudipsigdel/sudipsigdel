<!DOCTYPE html>
<html>
<head>
  <title>Welcome to my GitHub profile</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
    }

    h1 {
      text-align: center;
      margin-bottom: 10px;
    }

    h3 {
      text-align: center;
      margin-top: 10px;
    }

    .container {
      display: flex;
      flex-direction: column;
      align-items: center;
    }

    .gif-container {
      max-width: 100%;
      height: auto;
      margin-top: 20px;
    }

    .social-media {
      display: flex;
      justify-content: space-evenly;
      margin-top: 20px;
    }

    .social-media img {
      width: 50px;
      height: 60px;
    }

    @media only screen and (min-width: 768px) {
      .container {
        flex-direction: row;
      }

      .gif-container {
        flex: 1;
        padding-right: 20px;
        max-width: 50%;
      }

      .social-media {
        flex: 1;
        justify-content: flex-start;
      }
    }
  </style>
</head>
<body>
  <div class="container">
    <div class="profile-info">
      <h1>Welcome to my GitHub profile <img src="https://media.giphy.com/media/Qilx8dKjHI7FP3Mn5K/giphy.gif" width="50px" height="50px"></h1>
      <h3>An IT enthusiast from Nepal.</h3>
      <p>I’m currently learning <strong>Web Development</strong>.</p>
      <p>Visit my website <a href="https://sudipsigdel.com.np" target="_blank"><strong>sudipsigdel.com.np</strong></a>.</p>
      <p>Drop your queries at <strong>hello@sudipsigdel.com.np</strong>.</p>
    </div>
    <div class="gif-container">
      <img alt="GIF" src="https://media.giphy.com/media/f3iwJFOVOwuy7K6FFw/giphy.gif" width="100%" height="auto" />
    </div>
  </div>
  <h3>My Social Media handles</h3>
  <div class="social-media">
    <a href="https://facebook.com/sudipsigdel2059" target="_blank"> <img src="https://media.giphy.com/media/SKFsUhe9jUwrRtNPlq/giphy.gif" height="60" width="50" /></a>
    <a href="https://instagram.com/sudipsigdel2059" target="_blank"> <img src="https://media.giphy.com/media/c3u4lpyl64h1scLnko/giphy.gif" height="60" width="50" /></a>
    <a href="https://twitter.com/sudipsigdel2059" target="_blank"> <img src="https://media.giphy.com/media/e6YbWDajUKSzebFVuB/giphy.gif" height="60" width="50" /></a>
    <a href="https://linkedin.com/in/sudipsigdel2059" target="_blank"> <img src="https://media.giphy.com/media/QhPL2mdDVzeuHiRcIw/giphy.gif" height="60" width="50" /></a>
  </div>
</body>
</html>
