# RK-Iphones
<!DOCTYPE html>
<html lang="pt-br">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Minha Loja de Celulares</title>
<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&display=swap" rel="stylesheet">
<style>
  * { margin:0; padding:0; box-sizing:border-box; font-family: 'Poppins', sans-serif; }
  body { background:#f5f5f5; color:#333; }
  a { text-decoration:none; color: inherit; }

  /* Header */
  header { display:flex; justify-content:space-between; align-items:center; padding:15px 20px; background:#fff; position:sticky; top:0; z-index:1000; box-shadow:0 2px 5px rgba(0,0,0,0.1); }
  .logo { font-weight:700; font-size:1.2rem; color:#007bff; }
  .menu { font-size:1.5rem; cursor:pointer; }

  /* Banner */
  .banner { background:#007bff; color:#fff; text-align:center; padding:40px 20px; font-size:1.2rem; }
  .banner button { margin-top:20px; padding:10px 20px; background:#ffdd00; border:none; border-radius:5px; font-weight:600; cursor:pointer; }

  /* Seções */
  section { padding:20px; }
  h2 { margin-bottom:15px; font-size:1.1rem; }

  /* Carrossel de produtos */
  .products { display:flex; overflow-x:auto; gap:15px; padding-bottom:10px; }
  .product { background:#fff; border-radius:10px; min-width:150px; padding:10px; flex-shrink:0; text-align:center; box-shadow:0 2px 5px rgba(0,0,0,0.1); }
  .product img { width:100%; border-radius:10px; margin-bottom:10px; }
  .product h3 { font-size:0.95rem; margin-bottom:5px; }
  .price { font-weight:600; color:#007bff; }
  .old-price { text-decoration: line-through; color:#999; font-size:0.8rem; }
  .buy-btn { display:block; margin-top:10px; background:#ffdd00; padding:8px 0; border-radius:5px; font-weight:600; cursor:pointer; }

  /* Bloco de explicações */
  .conditions { display:flex; flex-direction:column; gap:10px; }
  .condition { background:#fff; padding:15px; border-radius:10px; box-shadow:0 2px 5px rgba(0,0,0,0.1); display:flex; gap:10px; align-items:center; }
  .condition img { width:40px; height:40px; }

  /* Depoimentos */
  .testimonials { display:flex; flex-direction:column; gap:10px; }
  .testimonial { background:#fff; padding:15px; border-radius:10px; box-shadow:0 2px 5px rgba(0,0,0,0.1); }

  /* Newsletter */
  .newsletter { background:#007bff; color:#fff; padding:20px; border-radius:10px; text-align:center; }
  .newsletter input[type="email"] { padding:10px; width:70%; border:none; border-radius:5px; margin-bottom:10px; }
  .newsletter button { padding:10px 20px; background:#ffdd00; border:none; border-radius:5px; font-weight:600; cursor:pointer; }

  /* Rodapé */
  footer { background:#333; color:#fff; padding:20px; text-align:center; font-size:0.85rem; }
  footer a { color:#ffdd00; }

  /* WhatsApp flutuante */
  .whatsapp { position:fixed; bottom:20px; right:20px; background:#25d366; width:50px; height:50px; border-radius:50%; display:flex; justify-content:center; align-items:center; color:#fff; font-size:1.5rem; box-shadow:0 2px 5px rgba(0,0,0,0.2); cursor:pointer; }
</style>
</head>
<body>

<header>
  <div class="logo">LojaCelular</div>
  <div class="menu">&#9776;</div>
</header>

<div class="banner">
  Celulares seminovos com garantia e frete grátis!  
  <button>Confira as Ofertas</button>
</div>

<section>
  <h2>Mais Vendidos</h2>
  <div class="products">
    <div class="product">
      <img src="https://via.placeholder.com/150x200" alt="iPhone 13">
      <h3>iPhone 13</h3>
      <div class="old-price">R$ 4.500</div>
      <div class="price">R$ 3.999</div>
      <button class="buy-btn">Comprar</button>
    </div>
    <div class="product">
      <img src="https://via.placeholder.com/150x200" alt="Samsung S21">
      <h3>Samsung S21</h3>
      <div class="old-price">R$ 3.200</div>
      <div class="price">R$ 2.799</div>
      <button class="buy-btn">Comprar</button>
    </div>
    <div class="product">
      <img src="https://via.placeholder.com/150x200" alt="Motorola G100">
      <h3>Motorola G100</h3>
      <div class="old-price">R$ 2.200</div>
      <div class="price">R$ 1.899</div>
      <button class="buy-btn">Comprar</button>
    </div>
  </div>
</section>

<section>
  <h2>Condições dos Aparelhos</h2>
  <div class="conditions">
    <div class="condition">
      <img src="https://via.placeholder.com/40" alt="Como Novo">
      <span>Como Novo – Sem marcas de uso, funcionando perfeitamente</span>
    </div>
    <div class="condition">
      <img src="https://via.placeholder.com/40" alt="Usado com Cuidado">
      <span>Usado com Cuidado – Pequenos sinais de uso, 100% funcional</span>
    </div>
    <div class="condition">
      <img src="https://via.placeholder.com/40" alt="Garantia">
      <span>Garantia de 6 meses para todos os produtos</span>
    </div>
  </div>
</section>

<section>
  <h2>Depoimentos de Clientes</h2>
  <div class="testimonials">
    <div class="testimonial">"Excelente atendimento e celular chegou rápido!" – Maria S.</div>
    <div class="testimonial">"Produto em ótimo estado e preço justo." – João P.</div>
  </div>
</section>

<section class="newsletter">
  <h2>Assine nossa Newsletter</h2>
  <input type="email" placeholder="Seu e-mail">
  <br>
  <button>Assinar</button>
</section>

<footer>
  &copy; 2026 LojaCelular | <a href="#">Sobre</a> | <a href="#">Termos e Condições</a> | <a href="#">Contato</a><br>
  WhatsApp: <a href="https://wa.me/5511953425162" target="_blank">11 95342-5162</a>
</footer>

<div class="whatsapp">
  <a href="https://wa.me/5511953425162" target="_blank" style="color:#fff;">&#9990;</a>
</div>

</body>
</html>