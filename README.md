# Meu-portif-lio-css
Esqueleto de um portifólio simples 
<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Portfólio - Júlia Bomfonti de Oliveira</title>
  <style>
     {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }
    body {
      font-family: Arial, Helvetica, sans-serif;
      line-height: 1.6;
      background: #f5f7fa;
      color: #333;
    }
    header {
      background: #4a90e2;
      color: #fff;
      padding: 20px 0;
      text-align: center;
    }
    header h1 {
      margin-bottom: 10px;
    }
    nav ul {
      list-style: none;
      display: flex;
      justify-content: center;
      gap: 20px;
    }
    nav a {
      text-decoration: none;
      color: #fff;
      font-weight: bold;
      transition: color 0.3s;
    }
    nav a:hover {
      color: #ffd700;
    }
    section {
      padding: 40px 20px;
      max-width: 900px;
      margin: auto;
    }
    h2 {
      margin-bottom: 15px;
      color: #4a90e2;
    }
    ul {
      list-style: none;
      margin-top: 15px;
    }
    li {
      margin-bottom: 20px;
      background: #fff;
      padding: 15px;
      border-radius: 8px;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
    }
    footer {
      background: #4a90e2;
      color: #fff;
      text-align: center;
      padding: 15px;
      margin-top: 30px;
    }
    footer a {
      color: #ffd700;
      text-decoration: none;
      margin: 0 5px;
    }
    footer a:hover {
      text-decoration: underline;
    }
    @media (max-width: 600px) {
      nav ul {
        flex-direction: column;
        gap: 10px;
      }
    }
  </style>
</head>
<body>

  <header>
    <h1>Júlia Bomfonti de Oliveira</h1>
    <nav>
      <ul>
        <li><a href="#sobre">Sobre</a></li>
        <li><a href="#projetos">Projetos</a></li>
        <li><a href="#contato">Contato</a></li>
      </ul>
    </nav>
  </header>

  <section id="apresentacao">
    <h2>Apresentação</h2>
    <p>Estudante de Análise e Desenvolvimento de Sistemas interessada em tecnologia, design e inovação.</p>
  </section>

  <section id="sobre">
    <h2>Sobre Mim</h2>
    <p>Gosto de aprender coisas novas e aplicar meus conhecimentos em projetos práticos.
    Tenho interesse em programação, design digital e soluções criativas que possam ajudar no dia a dia.</p>
    <p>Minhas principais habilidades incluem: lógica de programação, HTML, trabalho em equipe e vontade de aprender sempre.</p>
  </section>

  <section id="projetos">
    <h2>Projetos</h2>
    <ul>
      <li>
        <h3>Site Pessoal</h3>
        <p>Criação de uma página simples em HTML para apresentar meu perfil.</p>
      </li>
      <li>
        <h3>Trabalho em Grupo</h3>
        <p>Participação em projeto acadêmico focado em sustentabilidade e tecnologia.</p>
      </li>
    </ul>
  </section>

  <section id="contato">
    <h2>Contato</h2>
    <p>Email: <a href="mailto:julia.bomfonti2004@gmail.com">julia.bomfonti2004@gmail.com</a></p>
    <p>LinkedIn: <a href="https://www.linkedin.com/in/j%C3%BAlia-bomfonti-de-oliveira-bbb83b309/" target="_blank">JuliaBomfonti</a></p>
  </section>

  <footer>
    <p>Redes sociais:
      <a href="https://www.instagram.com/juliabomf/" target="_blank">Instagram</a> |
      <a href="[def]" target="_blank">GitHub</a>
    </p>
  </footer>

</body>
</html>


[def]: ttps://github.com/jbomfont
</body>
</html>
