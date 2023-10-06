# Portfolio-elasnatech

Projeto para finalizar o curso Elas Na Tech

<!DOCTYPE html>
<html lang="pt-br">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Alice Bispo</title>
  <link rel="stylesheet" href="index.css">
  <script src="Javascript.js"></script>
  <link rel="shortcut icon" href="./img/foto-perfil.png">
  <script src="https://use.fontawesome.com/releases/v5.15.3/js/all.js" data-auto-replace-svg="nest"></script>
</head>

<body>
  <header class="header-menu">
    <nav>
      <ul class="lista-menu">
        <li><a href="#principal">Texto sobre</a> </li>
        <li><a href="#trabalhos">Trabalhos feitos</a></li>
        <li><a href="#contato">Contatos</a></li>
      </ul>
    </nav>
  </header>

  <main>
    <section id="principal" class="principal">
      <article class="subcontainer-principal container">
          <div>
            <h1 class="nome-completo">Alice Bispo dos Santos</h1>
            <h2 class="profissao">Estudante</h2>
          </div>
          <div class="texto-sobre"> 
            <p>
              Graduanda em Engenharia de Produção, com foco na área de tecnologia e inovação, pela Universidade Federal do Recôncavo da Bahia e com conhecimento básico em programação, c#, python, javascript, html e css.
              Sou secretaria do WIE, Organização que tem como principal objetivo defender a permanência das mulheres nas areas de exatas e tecnologias.
            </p>
          </div>
      </article>
    </section>

    <section id="trabalhos">
      <article class="container article-lista">
        <div>
          <h3 class="topico-principal">Trabalhos realizados</h3>
        </div>

        <div class="lista-item">
            <ul>
              <li>
                <p class="lista-titulo">Site da ODS</p>
                <a href=" https://alicebispo.github.io/Site-sobre-ODS/" target="_blank" class="lista-local">Site ODS</a>
              </li>
  
              <li>
                <p class="lista-titulo">Currículo</p>
                <a href="https://alicebispo.github.io/curriculo-elasnatech/" target="_blank" class="lista-local">currículo</a>
              </li>
            </ul>
          </div>

      </article>
    </section>
  </main>

  <form name="meu_form">

    <h1>Entre em contato!!!!</h1>
  
    <input type="text" id="nome" placeholder="Alice Bispo" required="required" name="nome" />
    <label for="nome">Nome</label>
  
    <input type="tel" id="celular" placeholder="(xx)x-xxxx-xxxx" name="fone" />
    <label for="fone">Número</label>
  
    <input type="email" id="emailid" placeholder="fulano@mail.com" name="email" />
    <label for="email">Email</label>
  
    <textarea placeholder="Comentarios"></textarea>
  
    <input type="submit" class="enviar" onclick="Enviar();" value="Enviar" />
  </form>

  <footer class="rodape">
    <div class="container">
      <ul id="contato" class="lista-rodape">
        <li><i class="fas fa-envelope-square estilo-icone"></i>alicebispotmi@gmail.com</li>
        <li><a href="https://www.linkedin.com/in/alice-bispo-498a461a3/" target="_blank"><i class="fab fa-linkedin estilo-icone"></i>Alice-Bispo</a></li>
        <li><a href="https://github.com/AliceBispo" target="_blank"><i class="fab fa-github-square estilo-icone"></i>AliceBispo</a></li>
      </ul>
    </div>
  </footer>

</body>

</html>
