<!DOCTYPE html>
<html lang="sw">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Video UI Style</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', sans-serif;
      background: white;
      color: red;
      padding: 20px;
    }

    h2 {
      margin-left: 10px;
      font-size: 22px;
    }

    .video-grid {
      display: grid;
      grid-template-columns: repeat(auto-fill, minmax(110px, 1fr));
      gap: 15px;
      margin-top: 10px;
    }

    .video-card {
      background: #222;
      border-radius: 12px;
      overflow: hidden;
      box-shadow: 0 4px 10px rgba(0,0,0,0.4);
      transition: transform 0.2s ease;
    }

    .video-card:hover {
      transform: scale(1.03);
    }

    .video-card img {
      width: 100%;
      height: 90px;
      object-fit: cover;
      display: block;
    }

    .video-caption {
      padding: 6px 8px;
      font-size: 13px;
      text-align: left;
      color: white;
      white-space: nowrap;
      overflow: hidden;
      text-overflow: ellipsis;
    }

    a {
      text-decoration: none;
      color: inherit;
    }
  </style>
</head>
<body>

  <h2>FROM RAHA TUPU</h2>
  <div class="video-grid">
    <a href="https://example.com/v1" target="_blank">
      <div class="video-card">
        <img src="https://tse4.mm.bing.net/th/id/OIP.SKzXIuxFbIrxZbSlyH5U0AHaD4?rs=1&pid=ImgDetMain&o=7&rm=3" alt="With You">
        <div class="video-caption">With You</div>
      </div>
    </a>
    <a href="https://example.com/v2" target="_blank">
      <div class="video-card">
        <img src="https://tse4.mm.bing.net/th/id/OIP.SKzXIuxFbIrxZbSlyH5U0AHaD4?rs=1&pid=ImgDetMain&o=7&rm=3" alt="Venus">
        <div class="video-caption">Venus</div>
      </div>
    </a>
    <a href="https://example.com/v3" target="_blank">
      <div class="video-card">
        <img src="https://tse4.mm.bing.net/th/id/OIP.SKzXIuxFbIrxZbSlyH5U0AHaD4?rs=1&pid=ImgDetMain&o=7&rm=3" alt="Ye">
        <div class="video-caption">Ye</div>
      </div>
    </a>
    <a href="https://example.com/v4" target="_blank">
      <div class="video-card">
        <img src="https://tse4.mm.bing.net/th/id/OIP.SKzXIuxFbIrxZbSlyH5U0AHaD4?rs=1&pid=ImgDetMain&o=7&rm=3" alt="Ubuyu">
        <div class="video-caption">Ubuyu</div>
      </div>
    </a>
    <a href="https://example.com/v5" target="_blank">
      <div class="video-card">
        <img src="https://tse4.mm.bing.net/th/id/OIP.SKzXIuxFbIrxZbSlyH5U0AHaD4?rs=1&pid=ImgDetMain&o=7&rm=3" alt="Copy Paste">
        <div class="video-caption">Copy & Paste</div>
      </div>
    </a>
    <a href="https://example.com/v6" target="_blank">
      <div class="video-card">
        <img src="https://via.placeholder.com/150x90?text=Dogo+Mallo" alt="Dogo Mallo">
        <div class="video-caption">Dogo Mallo</div>
      </div>
    </a>
    <a href="https://example.com/v7" target="_blank">
      <div class="video-card">
        <img src="https://via.placeholder.com/150x90?text=Ordinary" alt="Ordinary">
        <div class="video-caption">Ordinary</div>
      </div>
    </a>
    <a href="https://example.com/v8" target="_blank">
      <div class="video-card">
        <img src="https://via.placeholder.com/150x90?text=One+Of+Your" alt="One Of Your...">
        <div class="video-caption">One Of Your...</div>
      </div>
    </a>
    <a href="https://example.com/v9" target="_blank">
      <div class="video-card">
        <img src="https://via.placeholder.com/150x90?text=Arike" alt="Arike">
        <div class="video-caption">Arike</div>
      </div>
    </a>
  </div>

</body>
</html>
