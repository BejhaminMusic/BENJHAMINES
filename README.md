<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Benjhamin Music ®  Landing Page</title>
  <link href="https://fonts.googleapis.com/css2?family=UnifrakturCook:wght@700&display=swap" rel="stylesheet" />
  <style>
    body {
      background-color: #000;
      color: #d4af37;
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
    }
    header {
      background-color: #000;
      color: #d4af37;
      text-align: center;
      padding: 40px 20px;
      font-family: 'UnifrakturCook', cursive;
    }
    header h1 {
      font-size: 4rem;
    }
    .gallery {
      display: flex;
      justify-content: center;
      align-items: center;
      gap: 22px;
      padding: 24px 12px;
      background-color: #000;
      flex-wrap: wrap;
    }
    .photo-container {
      position: relative;
      display: flex;
      flex-direction: column;
      align-items: center;
    }
    .photo-number {
      position: absolute;
      top: 5px;
      left: 8px;
      background: rgba(212, 175, 55, 0.85);
      color: #000;
      padding: 3px 9px;
      font-weight: bold;
      border-radius: 5px;
      font-size: 0.95em;
      pointer-events: none;
      z-index: 2;
    }
    .gallery a {
      display: inline-block;
      cursor: pointer;
      text-decoration: none;
      position: relative;
      z-index: 1;
    }
    .gallery svg {
      width: 68px;
      height: 68px;
      fill: #d4af37;
      stroke: #d4af37;
      transition: transform 0.3s, filter 0.3s;
    }
    .gallery a:hover svg {
      transform: scale(1.12);
      filter: drop-shadow(0 0 8px #d4af37);
    }
    .links {
      text-align: center;
      padding: 24px 12px 16px 12px;
      background-color: #000;
    }
    .links a {
      margin: 0 15px;
      font-size: 1.25em;
      text-decoration: none;
      padding: 12px 32px;
      border-radius: 8px;
      background: transparent;
      font-weight: bold;
      transition: background-color 0.3s, color 0.3s;
      border: none;
      box-shadow: 0 0 8px rgba(212,175,55,0.1);
      display: inline-block;
      letter-spacing: 1px;
    }
    .btn-youtube {
      color: #fff !important;
      background-color: #FF0000;
    }
    .btn-youtube:hover {
      background-color: #b70000;
      color: #fff !important;
    }
    .btn-beatstars {
      color: #fff !important;
      background-color: #006aff;
    }
    .btn-beatstars:hover {
      background-color: #024eab;
      color: #fff !important;
    }
    .btn-instagram {
      color: #fff !important;
      background: linear-gradient(90deg, #fd5949 0%, #d6249f 50%, #285AEB 100%);
      border: none;
    }
    .btn-instagram:hover {
      background: linear-gradient(90deg, #d6249f 0%, #fd5949 50%, #285AEB 100%);
      color: #fff !important;
    }
    footer {
      text-align: center;
      padding: 15px;
      background-color: #000;
      color: #d4af37;
      font-size: 0.9em;
    }
  </style>
</head>
<body>

  <header>
    <h1>Benjhamin Music <sup>®</sup></h1>
  </header>

  <section class="gallery">
    <div class="photo-container" title="YouTube">
      <span class="photo-number">1</span>
      <a href="https://l.instagram.com/?u=https%3A%2F%2Fyoutu.be%2Fbc6jeLO5vu8%3Fsi%3DSKC5OyGl3rFyRDOh%26fbclid%3DPAZXh0bgNhZW0CMTEAAaeaB9s8BejD4dIHwlQ1GpvqPemQOj6ISw7qFayZnGhml2ENNPNJQNAbRubhuA_aem_QndeJppohZE0GC_R-O1Mfw&e=AT0gyabne1TLSOZmPpXeivy_gmYZBjfFsYKC2kjexdw3ui-5Ues4tHNBvT5t9ldSQM9tOiVUkMnBvq9XVghef3Vdby4tlwdIzXuYGA" target="_blank" rel="noopener noreferrer">
        <svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg" fill="#d4af37" stroke="#d4af37" stroke-width="1">
          <path d="M10 15l5.19-3L10 9v6z" />
          <rect x="3" y="6" width="18" height="12" rx="3" ry="3" fill="none" stroke="#d4af37" stroke-width="2"/>
        </svg>
      </a>
    </div>
    <div class="photo-container" title="BeatStars">
      <span class="photo-number">2</span>
      <a href="https://l.instagram.com/?u=https%3A%2F%2Fbeatstars.com%2Fbenjhamindale%3Ffbclid%3DPAZXh0bgNhZW0CMTEAAafTTMVBbLfo2qfdaXn2658E7U4UIWDpp7slip5Stmy-fTt_2pQV9dT0B6dNYQ_aem_ljlaYQvcSAs4L3n3EZJhPQ&e=AT3pu1g3pACvahmXeNNCldZsneKLsdTayW9MC8XGw9CxBRA0qr8yM_DGM0t7X1FbNkfC8dRFaG2LMQQIxd_Awe78fmyhQ-ugyENsog" target="_blank" rel="noopener noreferrer">
        <svg viewBox="0 0 64 64" xmlns="http://www.w3.org/2000/svg" >
          <rect x="28" y="8" width="8" height="40" fill="#d4af37"/>
          <circle cx="32" cy="52" r="10" fill="none" stroke="#d4af37" stroke-width="3"/>
        </svg>
      </a>
    </div>
    <div class="photo-container" title="Instagram">
      <span class="photo-number">3</span>
      <a href="https://www.instagram.com/benjhamines/" target="_blank" rel="noopener noreferrer">
        <svg role="img" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg" fill="#d4af37" stroke="#d4af37" stroke-width="1">
          <rect x="2" y="2" width="20" height="20" rx="5" ry="5" fill="none" stroke="#d4af37" stroke-width="2"/>
          <circle cx="12" cy="12" r="5" fill="none" stroke="#d4af37" stroke-width="2"/>
          <circle cx="17.5" cy="6.5" r="1.5" fill="#d4af37"/>
        </svg>
      </a>
    </div>
  </section>

  <section class="links">
    <a href="https://l.instagram.com/?u=https%3A%2F%2Fyoutu.be%2Fbc6jeLO5vu8%3Fsi%3DSKC5OyGl3rFyRDOh%26fbclid%3DPAZXh0bgNhZW0CMTEAAaeaB9s8BejD4dIHwlQ1GpvqPemQOj6ISw7qFayZnGhml2ENNPNJQNAbRubhuA_aem_QndeJppohZE0GC_R-O1Mfw&e=AT0gyabne1TLSOZmPpXeivy_gmYZBjfFsYKC2kjexdw3ui-5Ues4tHNBvT5t9ldSQM9tOiVUkMnBvq9XVghef3Vdby4tlwdIzXuYGA" target="_blank" rel="noopener noreferrer" class="btn-youtube">YouTube</a>
    <a href="https://l.instagram.com/?u=https%3A%2F%2Fbeatstars.com%2Fbenjhamindale%3Ffbclid%3DPAZXh0bgNhZW0CMTEAAafTTMVBbLfo2qfdaXn2658E7U4UIWDpp7slip5Stmy-fTt_2pQV9dT0B6dNYQ_aem_ljlaYQvcSAs4L3n3EZJhPQ&e=AT3pu1g3pACvahmXeNNCldZsneKLsdTayW9MC8XGw9CxBRA0qr8yM_DGM0t7X1FbNkfC8dRFaG2LMQQIxd_Awe78fmyhQ-ugyENsog" target="_blank" rel="noopener noreferrer" class="btn-beatstars">BeatStars</a>
    <a href="https://www.instagram.com/benjhamines/" target="_blank" rel="noopener noreferrer" class="btn-instagram">Instagram</a>
  </section>

  <footer>
    &copy; 2025 Benjhamin Music ® . Todos los derechos reservados.
  </footer>

</body>
</html>
