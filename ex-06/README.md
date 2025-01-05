# Exercício 6 - Landing Page Responsiva
Utilize a página HTML abaixo para recriar o site de acordo com as imagens de referência. Garanta que a estilização ficará tão próxima quanto possível do resultado esperado nas imagens de referência e se atente para os seguintes pontos:

- O site deverá possuir um modo claro e um modo escuro, e deverá aplicá-los de acordo com a preferência do sistema do usuário;
- O site deverá ser responsivo, se adaptando aos diferentes tamanhos de tela (priorize dispositivos móveis e computadores de mesa);
- A estilização deverá seguir a abordagem *mobile-first*, ou seja, os estilos devem ser implementados a partir do ponto de vista de dispositivos móveis e adaptado para telas maiores;

**Arquivo HTML:**
```html
<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Future Tech Conference 2024</title>
  <link rel="stylesheet" href="style.css">
</head>

<body>
  <!-- Hero Section -->
  <section class="hero">
    <div class="hero-content">
      <h1>Future Tech Conference 2024</h1>
      <p>Join the leading voices in AI, Cloud Computing, and Web Development</p>
      <a href="#register" class="btn">Register Now</a>
    </div>
  </section>

  <!-- Speakers Section -->
  <section class="speakers">
    <h2>Our Speakers</h2>
    <div class="speakers-grid">
      <div class="speaker-card">
        <img src="images/speaker-1.jpg" alt="Speaker 1">
        <h3>Dr. Jane Doe</h3>
        <p>AI Specialist at TechCorp</p>
      </div>
      <div class="speaker-card">
        <img src="images/speaker-2.jpg" alt="Speaker 2">
        <h3>John Smith</h3>
        <p>Cloud Architect at CloudNet</p>
      </div>
      <div class="speaker-card">
        <img src="images/speaker-3.jpg" alt="Speaker 3">
        <h3>Sara Lee</h3>
        <p>Full Stack Developer at WebWorks</p>
      </div>
    </div>
  </section>

  <!-- Schedule Section -->
  <section class="schedule">
    <h2>Event Schedule</h2>
    <div class="schedule-grid">
      <div class="schedule-item">
        <h3>09:00 AM - Opening Keynote</h3>
        <p>Dr. Jane Doe: "The Future of AI"</p>
      </div>
      <div class="schedule-item">
        <h3>11:00 AM - Cloud Computing Trends</h3>
        <p>John Smith & Panelists</p>
      </div>
      <div class="schedule-item">
        <h3>02:00 PM - Building Scalable Web Apps</h3>
        <p>Sara Lee</p>
      </div>
      <div class="schedule-item">
        <h3>04:00 PM - Closing Remarks</h3>
        <p>Tech Innovations Beyond 2024</p>
      </div>
    </div>
  </section>

  <!-- Newsletter Subscription Section -->
  <section class="newsletter">
    <div class="newsletter-grid">
      <div class="newsletter-image">
        <img src="images/undraw_subscribe_vspl.svg" alt="Newsletter illustration">
      </div>
      <div class="newsletter-text">
        <h2>Subscribe to Our Newsletter</h2>
        <p>Stay updated with the latest event news, speaker announcements, and more!</p>
        <form action="#" method="post" class="newsletter-form">
          <div class="form-group">
            <label for="name">Full Name</label>
            <input type="text" id="name" name="name" placeholder="Enter your full name" required>
          </div>
          <div class="form-group">
            <label for="email">Email Address</label>
            <input type="email" id="email" name="email" placeholder="Enter your email" required>
          </div>
          <button type="submit" class="btn">Subscribe</button>
        </form>
      </div>
    </div>
  </section>

  <!-- Footer and Call to Action -->
  <footer class="footer">
    <p>&copy; 2024 Future Tech Conference. All rights reserved.</p>
    <a href="#register" class="btn">Register Now</a>
  </footer>
</body>

</html>
``` 

**Imagens utilizadas na página:**
<img src="https://onebitcode.notion.site/image/https%3A%2F%2Fprod-files-secure.s3.us-west-2.amazonaws.com%2F6e5271d8-2f68-42f5-aa75-5978bbff47fa%2F72e87185-d71b-4b60-a5dd-c0277152a82a%2Fpexels-bertellifotografia-3321797.jpg?table=block&id=364f7d97-8ea2-42a2-b8c3-4543f50e1a80&spaceId=6e5271d8-2f68-42f5-aa75-5978bbff47fa&width=1360&userId=&cache=v2">

<img src="https://onebitcode.notion.site/image/https%3A%2F%2Fprod-files-secure.s3.us-west-2.amazonaws.com%2F6e5271d8-2f68-42f5-aa75-5978bbff47fa%2F6cba3e1e-9b14-45ea-b682-c52add0a7222%2Fspeaker-1.jpg?table=block&id=b2f7141f-cef3-40ed-aab8-0fbc2060dedc&spaceId=6e5271d8-2f68-42f5-aa75-5978bbff47fa&width=300&userId=&cache=v2">

<img src="https://onebitcode.notion.site/image/https%3A%2F%2Fprod-files-secure.s3.us-west-2.amazonaws.com%2F6e5271d8-2f68-42f5-aa75-5978bbff47fa%2F5549d267-f35e-4379-8818-a21869a4df62%2Fspeaker-2.jpg?table=block&id=e04ee1dd-cea5-4447-a58b-86f4716baa24&spaceId=6e5271d8-2f68-42f5-aa75-5978bbff47fa&width=300&userId=&cache=v2">

<img src="https://onebitcode.notion.site/image/https%3A%2F%2Fprod-files-secure.s3.us-west-2.amazonaws.com%2F6e5271d8-2f68-42f5-aa75-5978bbff47fa%2F975cb6b7-220a-4946-8bf3-76a6d43d136e%2Fspeaker-3.jpg?table=block&id=c034b66c-6ed9-4020-9de0-e861e5cf5d71&spaceId=6e5271d8-2f68-42f5-aa75-5978bbff47fa&width=300&userId=&cache=v2">

<img src="https://onebitcode.notion.site/image/https%3A%2F%2Fprod-files-secure.s3.us-west-2.amazonaws.com%2F6e5271d8-2f68-42f5-aa75-5978bbff47fa%2Fc9905796-baa4-48e1-93bf-658e3bcaf014%2Fundraw_subscribe_vspl.svg?table=block&id=0f33ec1d-7cd0-4f24-9e48-c693ee25b9b2&spaceId=6e5271d8-2f68-42f5-aa75-5978bbff47fa&userId=&cache=v2">

**Cores utilizadas na página:**
```css
--fundo-branco:  #ffffff
--fundo-claro:   #e0e0e0
--cor-principal: #6c63ff
--fundo-escuro:  #2c2c2e
--fundo-preto:   #070707
```

## Imagens de Referência:
Visualização desktop (claro e escuro)

<img src="https://onebitcode.notion.site/image/https%3A%2F%2Fprod-files-secure.s3.us-west-2.amazonaws.com%2F6e5271d8-2f68-42f5-aa75-5978bbff47fa%2F10c3e949-2d29-4ecb-80d0-0a716bf0a03d%2FFireShot_Capture_008_-_Future_Tech_Conference_2024_-_127.0.0.1.png?table=block&id=982a56da-8cba-4fad-8240-4ae44672ac18&spaceId=6e5271d8-2f68-42f5-aa75-5978bbff47fa&width=660&userId=&cache=v2">

<img src="https://onebitcode.notion.site/image/https%3A%2F%2Fprod-files-secure.s3.us-west-2.amazonaws.com%2F6e5271d8-2f68-42f5-aa75-5978bbff47fa%2Fb39c1b29-147f-4388-9020-c303fbf186cf%2FFireShot_Capture_007_-_Future_Tech_Conference_2024_-_127.0.0.1.png?table=block&id=85355c6b-a91b-4150-be35-1c1676c9a570&spaceId=6e5271d8-2f68-42f5-aa75-5978bbff47fa&width=660&userId=&cache=v2">

Visualização mobile (claro e escuro)

<img src="https://onebitcode.notion.site/image/https%3A%2F%2Fprod-files-secure.s3.us-west-2.amazonaws.com%2F6e5271d8-2f68-42f5-aa75-5978bbff47fa%2Fef78db90-6936-4901-8b33-a3cd9c14c4fa%2FFireShot_Capture_009_-_Future_Tech_Conference_2024_-_127.0.0.1.png?table=block&id=86c43ef7-658c-4a48-bb67-32ad50034512&spaceId=6e5271d8-2f68-42f5-aa75-5978bbff47fa&width=660&userId=&cache=v2">

<img src="https://onebitcode.notion.site/image/https%3A%2F%2Fprod-files-secure.s3.us-west-2.amazonaws.com%2F6e5271d8-2f68-42f5-aa75-5978bbff47fa%2F98e80c7f-f07e-4397-a243-1372d53aa15d%2FFireShot_Capture_010_-_Future_Tech_Conference_2024_-_127.0.0.1.png?table=block&id=c51848b7-6831-49d9-95d2-5cfb141fa6ee&spaceId=6e5271d8-2f68-42f5-aa75-5978bbff47fa&width=660&userId=&cache=v2">