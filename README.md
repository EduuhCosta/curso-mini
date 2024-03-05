#DyW Host 

<!DOCTYPE html>
<html lang="PT-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>DyW HOST</title>
    <!-- ESTILOS -->
    <link rel="stylesheet" href="CSS/Style.css">
    <!-- ICONES -->
    <link rel="stylesheet" 
        href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css" 
        integrity="sha512-DTOQO9RWCH3ppGqcWaEA1BIZOC6xxalwEsw9c2QQeAIftl+Vegovlnee1c9QX4TctnWMn13TZye+giMm8e2LwA==" 
        crossorigin="anonymous" 
        referrerpolicy="no-referrer" 
    />
</head>
<body>
    <div class="container">
        <div class="navbar-container">
            <nav>
                <a href="#">
                    <img src="IMG/DYW.png" alt="DYW host" class="logo">
                </a>
                <ul class="navbar-items">
                    <li>
                        <a href="#">HOME</a>
                    </li>
                    <li>
                        <a href="#">Preços</a>
                    </li>
                    <li>
                        <a href="#">Contato</a>
                    </li>
                    <li>
                        <a href="#" class="default-btn">Entrar</a>
                    </li>
                </ul>
            </nav>
        </div>
        <main>
            <div class="main-banner">
                <h1>DyW Host</h1>
                <h4>Discovery Your World</h4>
                <h5>Seu dominio é com a gente !</h5>
                <p>A Discovery Your World é uma empresa que descomplica a hospedagem de sites e aplicações PHP para você focar no seu negócio.</p>

                <section class="service-container">
                    <ul>
                        <li>
                            <i class="fas fa-shield-alt">
                                <h3>Segurança</h3>
                                <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Laudantium labore maiores alias asperiores suscipit corporis repellat cumque, assumenda libero tempore sed! Eius vero est voluptatem voluptas libero architecto, eveniet praesentium.
                                </p>
                            </i>
                        </li>
                        <li>
                            <i class="fas fa-rocket">
                                <h3>Perfomance</h3>
                                <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Laudantium labore maiores alias asperiores suscipit corporis repellat cumque, assumenda libero tempore sed! Eius vero est voluptatem voluptas libero architecto, eveniet praesentium.
                                  
                                </p>
                            </i>
                        </li>
                        <li>
                            <i class="fas fa-comments">
                                <h3>Suporte 24/7</h3>
                                <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Laudantium labore maiores alias asperiores suscipit corporis repellat cumque, assumenda libero tempore sed! Eius vero est voluptatem voluptas libero architecto, eveniet praesentium.
                                </p>
                            </i>
                        </li>
                    </ul>
                </section>

                <section class="pricing-container">
                    <h2>Planos e preços</h2>
                    <p>Selecione o Plano que atende as suas necessidades</p>
                    <div class="plans-container">
                        <div class="plan">
                            <ul>
                                <li class="price">R$14,99/Mês</li>
                                <li class="plan-name" style="color: #38B6FF;">Básico</li>
                                <li>2Gb de Espaço</li>
                                <li>1 Subdomínio</li>
                                <li>25 contas de Email</li>
                                <li>C-panel</li>
                                <li>Atendimento 24/7</li>
                                <li class="price-btn">Saber Mais</li>
                            </ul>
                        </div>
                        <div class="plan">
                            <ul>
                                <li class="price">R$29,99/Mês</li>
                                <li class="plan-name" style="color: #cd7f32;">Bronze</li>
                                <li>5Gb de Espaço</li>
                                <li>5 Subdomínio</li>
                                <li>50 contas de Email</li>
                                <li>C-panel</li>
                                <li>Atendimento 24/7</li>
                                <li class="price-btn">Saber Mais</li>
                            </ul>
                        </div>
                        <div class="plan">
                            <ul>
                                <li class="price recommended">R$49,99/Mês</li>
                                <li class="plan-name" style="color: #d1d1d1;">Silver</li>
                                <li>10Gb de Espaço</li>
                                <li>10 Subdomínio</li>
                                <li>75 contas de Email</li>
                                <li>C-panel</li>
                                <li>Atendimento 24/7</li>
                                <li class="price-btn recommended">Saber Mais</li>
                            </ul>
                        </div>
                        <div class="plan">
                            <ul>
                                <li class="price">R$100,00/Mês</li>
                                <li class="plan-name" style="color: #daa520;">Gold</li>
                                <li>20Gb de Espaço</li>
                                <li>20 Subdomínio</li>
                                <li>150 contas de Email</li>
                                <li>C-panel</li>
                                <li>Atendimento 24/7</li>
                                <li class="price-btn">Saber Mais</li>
                            </ul>
                        </div>
                    </div>
                </section>
               
                <section class="searchdomain-container">
                    <h2>Qual Dominio você quer para seu site?</h2>
                    <p>Verifique se o seu dominio está Disponível no site!</p>
                    <form>
                        <input type="text" name="domain" id="domain" placeholder="Digíte o Dominio Desejado">
                        <input type="submit" value="Procurar Dominio">
                    </form>
                </section>
                <section class="contact-container">
                    <h2>Fale com a nossa central!</h2>
                    <h3>Está com Duvidas?</h3>
                    <p>Mande a sua mensagem e em um prazo de 4 horas um profissional entrará em contato!</p>
                    <form>
                        <input type="text" id="name" placeholder="Digite o seu nome!" required>
                        <input type="email" id="email" placeholder="digite o seu Email!" required>
                        <textarea name="message" id="message" placeholder="Descreva o que você precisa ou o seu projeto..."></textarea>
                        <input type="submit" value="enviar">
                    </form>
                </section>
            </div>
        </main>
        <p class="select">DyW Host @ 2024</p>

    </div>
    
</body>
</html>
