# PVI_WStand_faz-tudo
Página para oferecer trabalho de "faz tudo_marido de aluguel"

<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Marido de Aluguel - Faz Tudo</title>
  <link rel="stylesheet" href="styles.css">
</head>

<body>
<header>
  <h1>Ricardão Marido de Aluguel</h1>
    <p>Bem-vindo à página do seu parceiro ideal Ricardão Serviços de Manutenção e Reparos domiciliar</p>
</header>

<section id="sobre">
  <h2>Sobre Nós</h2>
    <p>Somos uma empresa dedicada a oferecer serviços de qualidade em reparos e manutenção domiciliar. Com profissionais experientes, garantimos eficiência e confiança em cada tarefa!</p>
</section>

<section id="servicos">
  <h2>Serviços Oferecidos</h2>
  <div class="flexbox-container">
    <div class="service-card">
      <h3>Reparos Gerais</h3>
      <p>Oferecemos serviços para consertos de alvenaria em geral na sua casa.</p>
    </div>
    <div class="service-card">
      <h3>Pintura</h3>
      <p>Pintura de interiores e exteriores com organização e acabamento impecáveis.</p>
    </div>
    <div class="service-card">
      <h3>Montagem de Móveis</h3>
      <p>Montamos seus móveis de forma rápida e segura.</p>
    </div>
    <div class="service-card">
      <h3>Instalações Elétricas</h3>
      <p>Manutenção e reparos nas instalações elétricas para sua segurança e economia.</p>
    </div>
    <div class="service-card">
      <h3>Instalações Hidráulicas</h3>
      <p>Manutenção e reparos nas instalações hidráulicas para seu conforto e economia.</p>
    </div>
    <div class="service-card">
      <h3>Serviços de Jardinagem</h3>
      <p>Cuidados e manutenção do seu jardim, com muito carinho, para que ele fique sempre bonito.</p>
    </div>
  </div>
</section>

<section id="vantagens">
  <h2>Vantagens e Benefícios</h2>
  <ul>
    <li>Tenha sua casa sempre linda e funcional.</li>
    <li>Atendimento personalizado e confiável.</li>
    <li>Profissionais experientes e qualificados.</li>
    <li>Tarefas realizadas com qualidade, agilidade e limpeza.</li>
    <li>Oferecemos 3 meses de garantia dos serviços realizados.</li>
  </ul>
</section>

<section id="depoimentos"
  <h2>O que nossos cliente dizem sobre nós...</h2>
  <blockquote>
    <p>"Serviço de qualidade! O marido de aluguel resolveu todos os nossos problemas em casa!"</p>
    <cite>- Ana Paula</cite>
  </blockquote>
  <blockquote>
    <p>"Muito profissional e atencioso. Recomendado!"</p>
    <cite>- Carlos Eduardo</cite>
  </blockquote>
</section>

<section id="contato">
  <h2>Entre em Contato</h2>
    <p><strong>Email:</strong> contato@ricardaoreparos.com</p>
    <p><strong>Telefone/WhatsApp:</strong> (11) 91234-5678</p>
  
  <form>
    <label for="nome">Nome:</label>
    <input type="text" id="nome" name="nome" required>
    <label for="email">Email:</label>
    <input type="email" id="email" name="email" required>
    <label for="mensagem">Mensagem:</label>
    <textarea id="mensagem" name="mensagem" required></textarea>
    <button type="submit">Enviar</button>
  </form>
</section>

<footer>
  <p>© 2025 Ricardão Marido de Aluguel. Todos os direitos reservados.</p>
</footer>

</body>
</html>


styles.css

body {
  font-family: Arial, sans-serif;
  margin: 0;
  padding: 0;
  line-height: 1.6;
}

header {
  text-align: center;
  background-color: #4CAF50; /* Cor Verde */
  color: white;
  padding: 1rem;
}

h2 {
  text-align: center;
}

.flexbox-container {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
}

.service-card {
  border: 1px solid #ddd;
  border-radius: 5px;
  margin: 10px;
  padding: 10px;
  width: calc(20% - 20px); /* Ajuste a largura para se adaptar */
}

ul {
  list-style-type: none;
  padding: 0;
}

form {
  display: flex;
  flex-direction: column;
  width: 300px;
  margin: auto;
}

footer {
  text-align: center;
  background-color: #f1f1f1;
  padding: 1rem;
  position: relative;
  bottom: 0;
  width: 100%;
}

@media (max-width: 768px) {
  .service-card {
      width: calc(45% - 20px); /* Dois cards por linha em telas menores */
  }
}

@media (max-width: 480px) {
  .service-card {
      width: 100%; /* Um card por linha em telas pequenas */
  }
}





