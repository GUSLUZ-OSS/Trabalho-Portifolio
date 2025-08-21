<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.7/dist/css/bootstrap.min.css" rel="stylesheet">
  <link rel="stylesheet" href="style.css">
  <title>Meu portfólio</title>
</head>

<body>
  <header class="container text-center py-5"> 
    <img src="img/WhatsApp Image 2025-08-21 at 20.15.07.jpeg" alt="foto do gustavo" class="rounded-0 mb-3" width="200">
    <p class="lead">Eu sou Gustavo</p>
    <h1>Quero entrar no rumo de programação</h1>
    <p>Sou Gustavo Luz de Souza, atualmente tenho 16 anos, gosto de programação. Meu desejo é um dia programar um jogo de sucesso, sou bom com números e gosto de escrever. Tenho alguns certificados que ganhei fazendo cursos na Alura.</p>
    <p>Minhas habilidades:</p>
    <div>
      <span class="badge text-bg-secondary m-1">Lógica de programação</span>
      <span class="badge text-bg-secondary m-1">Prestativo</span>
      <span class="badge text-bg-secondary m-1">Bom com contas</span>
      <span class="badge text-bg-secondary m-1">Trabalho em equipe</span>
    </div>
  </header>

  <main class="container mt-3">
    <h2 class="mb-4">Meus projetos</h2>
    <div class="row justify-content-center">
      <!-- PROJETO 1 -->
      <div class="col-md-6 mb-4">
        <div class="card">
          <img src="img/undefined- (1).jpeg" class="card-img-top" alt="imagem do certificado do projeto">
          <div class="card-body">
            <h5 class="card-title">Projeto corrida parte 1</h5>
            <p class="card-text">Esse foi um projeto em Java sobre corrida. Um projeto simples, porém com cuidado e empenho no desenvolvimento.</p>
            <button type="button" data-bs-toggle="modal" data-bs-target="#modal1" class="btn btn-info">Olhar projeto</button>
          </div>
        </div>
      </div>

      <!-- PROJETO 2 -->
      <div class="col-md-6 mb-4">
        <div class="card">
          <img src="img/undefined- (2).jpeg" class="card-img-top" alt="imagem do certificado do projeto">
          <div class="card-body">
            <h5 class="card-title">Projeto corrida parte 2</h5>
            <p class="card-text">Segunda parte do projeto de corrida, aprimorando o conhecimento e simplificando o código para melhor desempenho e resultado visual.</p>
            <button type="button" data-bs-toggle="modal" data-bs-target="#modal2" class="btn btn-info">Olhar projeto</button>
          </div>
        </div>
      </div>

      <!-- PROJETO 3 -->
      <div class="col-md-6 mb-4">
        <div class="card">
          <img src="img/undefined-.jpeg" class="card-img-top" alt="imagem do certificado do projeto">
          <div class="card-body">
            <h5 class="card-title">Projeto Rosto</h5>
            <p class="card-text">Primeiro projeto do ano, simples mas com resultado interessante. Observando os projetos percebo melhora no desempenho.</p>
            <button type="button" data-bs-toggle="modal" data-bs-target="#modal3" class="btn btn-info">Olhar projeto</button>
          </div>
        </div>
      </div>
    </div>
  </main>

  <!-- MODAIS -->
  <!-- Modal 1 -->
  <div class="modal fade" id="modal1" tabindex="-1" aria-hidden="true">
    <div class="modal-dialog">
      <div class="modal-content">
        <div class="modal-header">
          <h5 class="modal-title">Projeto Corrida Parte 1</h5>
          <button type="button" class="btn-close" data-bs-dismiss="modal" aria-label="Fechar"></button>
        </div>
        <div class="modal-body">
          <p>Projeto de programação Java. Primeira vez lidando com Java, desafiador, mas com aprendizado progressivo e resultado satisfatório.</p>
          <img src="img/Captura de tela 2025-08-21 185648.png" alt="imagem do projeto" class="img-fluid">
        </div>
        <div class="modal-footer">
          <a href="mailto:gusluz2931@gmail.com" class="btn btn-primary">Entrar em contato</a>
        </div>
      </div>
    </div>
  </div>

  <!-- Modal 2 -->
  <div class="modal fade" id="modal2" tabindex="-1" aria-hidden="true">
    <div class="modal-dialog">
      <div class="modal-content">
        <div class="modal-header">
          <h5 class="modal-title">Projeto Corrida Parte 2</h5>
          <button type="button" class="btn-close" data-bs-dismiss="modal" aria-label="Fechar"></button>
        </div>
        <div class="modal-body">
          <p>Projeto parte 2, aprimorando o código e tornando-o mais eficiente e compreensível.</p>
          <img src="img/Captura de tela 2025-08-21 194948.png" alt="imagem do projeto" class="img-fluid">
        </div>
        <div class="modal-footer">
          <a href="mailto:gusluz2931@gmail.com" class="btn btn-primary">Entrar em contato</a>
        </div>
      </div>
    </div>
  </div>

  <!-- Modal 3 -->
  <div class="modal fade" id="modal3" tabindex="-1" aria-hidden="true">
    <div class="modal-dialog">
      <div class="modal-content">
        <div class="modal-header">
          <h5 class="modal-title">Projeto Rosto</h5>
          <button type="button" class="btn-close" data-bs-dismiss="modal" aria-label="Fechar"></button>
        </div>
        <div class="modal-body">
          <p>Projeto sobre rostos, melhorando técnica e desempenho.</p>
          <img src="img/Captura de tela 2025-08-21 195017.png" alt="imagem do projeto" class="img-fluid">
        </div>
        <div class="modal-footer">
          <a href="mailto:gusluz2931@gmail.com" class="btn btn-primary">Entrar em contato</a>
        </div>
      </div>
    </div>
  </div>

  <!-- Footer -->
  <footer class="container py-5 text-center">
    <h2>Entre em contato</h2>
    <div class="mb-3">
      <a href="mailto:gusluz2931@gmail.com" class="me-3">EMAIL</a>
      <a href="tel:+5511941159018">TELEFONE</a>
    </div>
    <p class="my-3">&copy; 2025. Produzido por Gustavo Luz</p>
  </footer>

  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.7/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
w
