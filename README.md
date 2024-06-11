# DL-REFRIGERA-OES <!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Site Pessoal - Montagem e Manutenção</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        header {
            background-color: #4CAF50;
            color: white;
            padding: 10px 0;
            text-align: center;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: #333;
        }
        nav a {
            color: white;
            padding: 14px 20px;
            text-decoration: none;
            text-align: center;
        }
        nav a:hover {
            background-color: #ddd;
            color: black;
        }
        section {
            padding: 20px;
        }
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 10px 0;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
        .container {
            width: 80%;
            margin: auto;
            overflow: hidden;
        }
        .testimonials, .services {
            display: flex;
            justify-content: space-around;
        }
        .testimonial, .service {
            background: #fff;
            padding: 20px;
            margin: 10px;
            border-radius: 5px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            flex-basis: 45%;
        }
    </style>
</head>
<body>
    <header>
        <h1>Excelência em Montagem e Manutenção</h1>
        <p>Montagem e manutenção de câmaras frias | Instalação de ar condicionado</p>
    </header>
    <nav>
        <a href="#home">Home</a>
        <a href="#about">Sobre Mim</a>
        <a href="#portfolio">Portfólio</a>
        <a href="#blog">Blog</a>
        <a href="#contact">Contato</a>
        <a href="#testimonials">Testemunhos</a>
        <a href="#services">Serviços</a>
    </nav>
    <section id="home" class="container">
        <h2>Bem-vindo!</h2>
        <p>Bem-vindo ao meu site pessoal, onde você pode conhecer mais sobre meus serviços de montagem e manutenção de câmaras frias, além da instalação de ar condicionado.</p>
    </section>
    <section id="about" class="container">
        <h2>Sobre Mim</h2>
        <p>Olá! Meu nome é [Seu Nome]. Sou um especialista em montagem e manutenção de câmaras frias e instalação de ar condicionado. Com [X] anos de experiência na área, tenho ajudado diversos clientes a manterem seus sistemas de refrigeração e climatização funcionando perfeitamente. Sou apaixonado por tecnologia e inovação, e estou sempre em busca de novas soluções para melhorar a eficiência e durabilidade dos sistemas que instalo e mantenho.</p>
    </section>
    <section id="portfolio" class="container">
        <h2>Portfólio</h2>
        <div>
            <h3>Projeto 1: Instalação de Câmara Fria para Armazém de Alimentos</h3>
            <p>Instalação completa de uma câmara fria para armazenamento de alimentos em um armazém. O projeto incluiu desde o planejamento até a implementação e testes finais.</p>
            <!-- Adicionar imagem aqui -->
        </div>
        <div>
            <h3>Projeto 2: Manutenção de Sistema de Ar Condicionado em Edifício Comercial</h3>
            <p>Realização de manutenção preventiva e corretiva em sistemas de ar condicionado de um edifício comercial, garantindo o funcionamento contínuo e eficiente.</p>
            <!-- Adicionar imagem aqui -->
        </div>
    </section>
    <section id="blog" class="container">
        <h2>Blog</h2>
        <article>
            <h3>Como Manter sua Câmara Fria Funcionando Eficientemente</h3>
            <p>Manter uma câmara fria funcionando de maneira eficiente é crucial para a conservação de produtos perecíveis. Neste artigo, discutimos dicas e melhores práticas para a manutenção regular e preventiva de câmaras frias.</p>
            <a href="#">Leia mais...</a>
        </article>
    </section>
    <section id="contact" class="container">
        <h2>Contato</h2>
        <p>Email: seuemail@exemplo.com</p>
        <p>Telefone: (00) 12345-6789</p>
        <p>LinkedIn: <a href="https://www.linkedin.com">Seu LinkedIn</a></p>
        <p>Twitter: <a href="https://www.twitter.com">Seu Twitter</a></p>
        <h3>Formulário de Contato</h3>
        <form>
            <label for="name">Nome:</label><br>
            <input type="text" id="name" name="name"><br><br>
            <label for="email">Email:</label><br>
            <input type="email" id="email" name="email"><br><br>
            <label for="message">Mensagem:</label><br>
            <textarea id="message" name="message" rows="4" cols="50"></textarea><br><br>
            <input type="submit" value="Enviar">
        </form>
    </section>
    <section id="testimonials" class="container">
        <h2>Testemunhos</h2>
        <div class="testimonials">
            <div class="testimonial">
                <p><strong>João Silva:</strong> "Excelente profissional! A instalação da nossa câmara fria foi rápida e eficiente. Recomendo a todos."</p>
            </div>
            <div class="testimonial">
                <p><strong>Maria Oliveira:</strong> "Profissional dedicado e atento aos detalhes. A manutenção do nosso sistema de ar condicionado nunca foi tão boa."</p>
            </div>
        </div>
    </section>
    <section id="services" class="container">
        <h2>Serviços</h2>
        <div class="services">
            <div class="service">
                <h3>Montagem e Manutenção de Câmara Fria</h3>
                <p>Oferecemos serviços completos de montagem e manutenção de câmaras frias, garantindo a conservação ideal dos seus produtos.</p>
            </div>
            <div class="service">
                <h3>Instalação de Ar Condicionado</h3>
                <p>Serviços de instalação de ar condicionado para residências e empresas, assegurando um ambiente climatizado e confortável.</p>
            </div>
        </div>
    </section>
    <footer>
        <p>&copy; 2024 [Seu Nome]. Todos os direitos reservados.</p>
    </footer>
</body>
</html>

