
<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Portfólio - Tereza Silva</title>
  <link href="https://fonts.googleapis.com/css2?family=Lora:wght@400;600;700&display=swap" rel="stylesheet">
  <link rel="stylesheet" href="style.css"> <!-- seu CSS externo -->
</head>
<body>
  <!-- Menu -->
  <header>
    <div class="logo-nome">
      <img src="https://github.com/terearaujo/meu-site-/raw/main/imagens/logotipo.png" alt="Logo" class="logo">
      <h1>Tereza Silva</h1>
    </div>

    <nav class="menu">
      <a href="#sobre">Sobre</a>
      <a href="#formacao">Formação</a>
      <a href="#habilidades">Habilidades</a>
      <a href="#projetos">Projetos</a>
      <a href="#contato">Contatos</a>
    </nav>

    <div class="social">
      <a href="https://github.com/terearaujo" target="_blank">
        <i class="fab fa-github"></i>
      </a>
      <a href="https://www.linkedin.com/in/tereza-romana-a2a6071ba/" target="_blank">
        <i class="fab fa-linkedin"></i>
      </a>
    </div>
  </header>

  <!-- Sobre -->
 <section id="sobre" class="sessao">
  <h2>Sobre mim</h2>
  <p>
    Olá! Meu nome é <strong>Tereza Romana</strong>, tenho 27 anos e sou apaixonada pelo mundo do design e da tecnologia. 
    Possuo conhecimentos básicos em <strong>HTML, CSS, Python e SQL</strong>, adquiridos em cursos de plataformas como 
    <em>Formação Meu Curso</em>, <em>Curso Guanabara</em> e <em>Teo</em>.
  </p>
  <p>
    Além da área de programação, também desenvolvo trabalhos em <strong>artes visuais para redes sociais</strong>, explorando criatividade e comunicação visual. 
    Meus aprendizados em design vêm de estudos pela plataforma <em>Coisas de Designer</em>, onde aprimorei meu olhar estético e minhas habilidades gráficas.
  </p>
  <p>
    Busco unir tecnologia e design para criar experiências digitais criativas, funcionais e visualmente atraentes.
  </p>
</section>


  <!-- Formação -->
  <section id="formacao" class="sessao">
    <h2>Formação</h2>
    <ul>
      <li>Cursando Graduação em Ciência da Computação</li>
      <li>Cursos e certificações em áreas de tecnologia e design</li>
    </ul>
  </section>

  <!-- Habilidades -->
  <section id="habilidades" class="sessao">
    <h2>Habilidades</h2>
    <div class="skills">
      <span>HTML</span>
      <span>CSS</span>
      <span>Design Gráfico</span>
      <span>Python</span>
      <span>SQL</span>
    </div>
  </section>

  <!-- Projetos -->
  <section id="projetos" class="sessao">
    <h2>Projetos</h2>
    <div class="grid-projetos">
      <div class="card">Projeto 1</div>
      <div class="card">Projeto 2</div>
    </div>
  </section>

  <!-- Contato -->
  <footer id="contato">
    <p>© 2025 - Desenvolvido por Tereza Silva</p>
  </footer>
</body>
</html>

/* Fonte suave */
body {
  margin: 0;
  font-family: 'Arial', sans-serif;
  background-color: #fff;
  color: #333;
}

/* Header / Navbar */
header {
  display: flex;
  align-items: center;
  justify-content: space-between;
  background-color: #f8cdda; /* rosa pastel suave */
  padding: 15px 40px;
  position: sticky;
  top: 0;
  z-index: 1000;
}

/* Logo + nome */
.logo-nome {
  display: flex;
  align-items: center;
}

.logo {
  height: 70px;
  width: auto;
  margin-right: 12px;
}

.logo-nome h1 {
  font-size: 1.5rem;
  color: #333;
}

/* Menu central */
.menu {
  display: flex;
  gap: 25px;
}

.menu a {
  text-decoration: none;
  color: #333;
  font-weight: 500;
  transition: color 0.3s;
}

.menu a:hover {
  color: #c2185b; /* rosa mais escuro */
}

/* Ícones sociais à direita */
.social a {
  margin-left: 15px;
  font-size: 22px;
  color: #333;
  transition: color 0.3s;
}

.social a:hover {
  color: #c2185b;
}

/* Sessões */
.sessao {
  padding: 60px 20px;
  text-align: center;
}

.sessao h2 {
  color: #c2185b;
  margin-bottom: 20px;
}

/* Habilidades */
.skills {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  gap: 15px;
}

.skills span {
  background: #fce4ec;
  padding: 10px 20px;
  border-radius: 20px;
  font-weight: bold;
  color: #c2185b;
}

/* Projetos */
.grid-projetos {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
  gap: 20px;
}

.card {
  background: #f8cdda;
  padding: 30px;
  border-radius: 15px;
  box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
  transition: transform 0.3s;
}

.card:hover {
  transform: scale(1.05);
}

/* Rodapé */
footer {
  background-color: #f8cdda;
  text-align: center;
  padding: 20px;
  font-size: 14px;
  color: #333;
}

