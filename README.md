# SiteModas
<!DOCTYPE html>
<html lang="pt-BR">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Claudio Almeida - Moda Masculina</title>
    <link rel="stylesheet" href="style.css">
    <link rel="stylesheet" href="java.js">
    <link href="https://fonts.googleapis.com/css2?family=Mea+Culpa&display=swap" rel="style.css">

</head>


<body>

    <header>

        <h1>Claudio Almeida</h1>

        <nav>
            <ul class="UL">

                <ul>
                    <li><a href="#home" class="menu-link">Início</a></li>
                    <li><a href="#Produtos" class="menu-link">Produtos</a></li>
                    <li><a href="#sobre" class="menu-link">Sobre</a></li>
                    <li><a href="#contato" class="menu-link">Contato</a></li>
                </ul>


            </ul>

        </nav>

        <nav class="navbar">
            <ul class="menu">
                
                <li class="menu-item">
                    <a href="#">Camisetas</a>
                </li>
                <li class="menu-item">
                    <a href="#">Blazer</a>
                    <ul class="submenu">
                        <li><a href="#">Marca 1</a></li>
                        <li><a href="#">Marca 2</a></li>
                        <li><a href="#">Marca 3</a></li>
                        <li><a href="#">Marca 4</a></li>
                    </ul>
                </li>
                <li class="menu-item">
                    <a href="#">Camisetas</a>
                    <ul class="submenu">
                        <li><a href="#">Produto 1</a></li>
                        <li><a href="#">Produto 2</a></li>
                        <li><a href="#">Produto 3</a></li>
                    </ul>
                </li>
                <li class="menu-item">
                    <a href="#">Ternos</a>
                    <ul class="submenu">
                        <li><a href="#">Desconto 1</a></li>
                        <li><a href="#">Desconto 2</a></li>
                    </ul>
                </li>
                <li class="menu-item">
                    <a href="#">Looks</a>
                </li>
            </ul>
        </nav>



        <div class="search-container">
            <form action="#" method="get">
                <div class="Procurar">
                    <input type="text" name="search" placeholder="Buscar...">

                    <div class="Lupabaixo"> <img
                            src="Leonardo_Phoenix_A_stylized_illustration_of_a_magnifying_glass_1-removebg-preview.png"
                            alt="" class="Lupa"> </div>
                </div>

            </form>
        </div>

    </header>


    <section class="js-adbar section-adbar section-adbar-animated section-adbar-colors adbar-with-messages">
        <div class="js-adbar-animated adbar-animated">
            <div class="js-adbar-text-container adbar-text-container align-items-center">
                <span class="adbar-message mr-4">
                    <a href="https://wa.me/5511992426616">PRÉ BLACK FRIDAY GARBO - ATÉ 40% OFF</a>
                </span>
                <span class="adbar-message mr-4">
                    <a href="https://wa.me/5511992426616">FALE CONOSCO PELO WHATS</a>
                </span>
                <span class="adbar-message mr-4">
                    <a href="https://wa.me/5511992426616">PRÉ BLACK FRIDAY GARBO - ATÉ 40% OFF</a>
                </span>
                <span class="adbar-message mr-4">
                    <a href="https://wa.me/5511992426616">FALE CONOSCO PELO WHATS</a>
                </span>
                <!-- Adicione mais mensagens conforme necessário -->
            </div>
        </div>
    </section>

    <!DOCTYPE html>
    <html>

    <head>
        <meta name="viewport" content="width=device-width, initial-scale=1">
        <style>
            * {
                box-sizing: border-box
            }

            body {
                font-family: Verdana, sans-serif;
                margin: 0
            }

            .mySlides {
                display: none
            }

            img {
                vertical-align: middle;
            }

            /* Slideshow container */
            .slideshow-container {
                max-width: 1000px;
                position: relative;
                margin: auto;
            }

            /* Next & previous buttons */
            .prev,
            .next {
                cursor: pointer;
                position: absolute;
                top: 50%;
                width: auto;
                padding: 16px;
                margin-top: -22px;
                color: rgb(0, 0, 0);
                font-weight: bold;
                font-size: 18px;
                transition: 10s ease;
                border-radius: 0 3px 3px 0;
                user-select: none;
            }

            /* Position the "next button" to the right */
            .next {
                right: 0;
                border-radius: 3px 0 0 3px;
            }

            /* On hover, add a black background color with a little bit see-through */
            .prev:hover,
            .next:hover {
                background-color: rgba(0, 0, 0, 0.8);
                color: black 2px solid;
            }

            /* Caption text */
            .text {
                color: #f2f2f2;
                font-size: 15px;
                padding: 8px 12px;
                position: absolute;
                bottom: 8px;
                width: 100%;
                text-align: center;
            }

            /* Number text (1/3 etc) */
            .numbertext {
                color: #f2f2f2;
                font-size: 12px;
                padding: 8px 12px;
                position: absolute;
                top: 0;
            }

            /* The dots/bullets/indicators */
            .dot {
                cursor: pointer;
                height: 15px;
                width: 15px;
                margin: 0 2px;
                background-color: #bbb;
                border-radius: 50%;
                display: inline-block;
                transition: background-color 0.6s ease;
            }

            .active,
            .dot:hover {
                background-color: #717171;
            }

            /* Fading animation */
            .fade {
                animation-name: fade;
                animation-duration: 0.5s;
            }

            @keyframes fade {
                from {
                    opacity: .4
                }

                to {
                    opacity: 1
                }
            }

            /* On smaller screens, decrease text size */
            @media only screen and (max-width: 300px) {

                .prev,
                .next,
                .text {
                    font-size: 11px
                }
            }
        </style>
    </head>

    <body>
        <section class="sec-1">
            <div class="slideshow-container">

                <div class="mySlides fade">
                    <div class="numbertext">1 / 3</div>
                    <img src="Loja de Roupas Claudio Almeida Patos de Minas.jpg" style="width:100%">
                    <div class="text">Caption Text</div>
                </div>

                <div class="mySlides fade">
                    <div class="numbertext">2 / 3</div>
                    <img src="Leonardo_Phoenix_A_stylized_illustration_of_a_magnifying_glass_1-removebg-preview.png"
                        style="width:100%">
                    <div class="text">Caption Two</div>
                </div>

                <div class="mySlides fade">
                    <div class="numbertext">3 / 4</div>
                    <img src="Leonardo_Phoenix_A_stylized_illustration_of_a_magnifying_glass_2-removebg-preview.png"
                        style="width:100%">
                    <div class="text">Caption Three</div>
                </div>

                <div class="mySlides fade">
                    <div class="numbertext">4 / 4</div>
                    <img src="Leonardo_Phoenix_A_stylized_illustration_of_a_magnifying_glass_2-removebg-preview.png"
                        style="width:100%">
                    <div class="text">Caption Three</div>
                </div>

                <div class="mySlides fade">
                    <div class="numbertext">5 / 5</div>
                    <img src="Leonardo_Phoenix_A_stylized_illustration_of_a_magnifying_glass_2-removebg-preview.png"
                        style="width:100%">
                    <div class="text">Caption Three</div>
                </div>

                <a class="prev" onclick="plusSlides(-1)">❮</a>
                <a class="next" onclick="plusSlides(1)">❯</a>

            </div>
            <br>

            <div style="text-align:center">
                <span class="dot" onclick="currentSlide(1)"></span>
                <span class="dot" onclick="currentSlide(2)"></span>
                <span class="dot" onclick="currentSlide(3)"></span>
                <span class="dot" onclick="currentSlide(4)"></span>
                <span class="dot" onclick="currentSlide(5)"></span>
            </div>
        </section>
        <script>

            // Navegação manual (botões)
            function plusSlides(n) {
                showSlides(slideIndex += n);
            }

            // Navegação manual (indicadores)
            function currentSlide(n) {
                showSlides(slideIndex = n);
            }

            // Exibe os slides
            function showSlides(n) {
                let i;
                let slides = document.getElementsByClassName("mySlides");
                let dots = document.getElementsByClassName("dot");
                if (n > slides.length) { slideIndex = 1 }
                if (n < 1) { slideIndex = slides.length }
                for (i = 0; i < slides.length; i++) {
                    slides[i].style.display = "none";
                }
                for (i = 0; i < dots.length; i++) {
                    dots[i].className = dots[i].className.replace(" active", "");
                }
                slides[slideIndex - 1].style.display = "block";
                dots[slideIndex - 1].className += " active";
            }

            // Navegação automática
            setInterval(() => {
                plusSlides(1); // Avança um slide automaticamente
            }, 5000); // Troca a cada 5 segundos

            // Inicializa o slideIndex
            let: slideIndex = 1;
            showSlides(slideIndex);
        </script>
        <Section></Section>



        </script>
        </section>

        <section class="sec-2">

            <h2>BLACK FRIDAY</h2>
            <p>PROMOÇAO IMPERDIVEL</p>
            <div class="carrossel-container">
                <div class="carrossel">
                    <div class="carrossel-item">
                        <img src="Loja de Roupas Claudio Almeida Patos de Minas.jpg" alt="Imagem 1">
                    </div>
                    <div class="carrossel-item">
                        <img src="Leonardo_Phoenix_A_stylized_illustration_of_a_magnifying_glass_1-removebg-preview.png"
                            alt="Imagem 2">
                    </div>
                    <div class="carrossel-item">
                        <img src="image03.jpg" alt="Imagem 3">
                    </div>
                </div>

                <button class="prev" onclick="moveSlide(-1)">&#10094;</button>
                <button class="next" onclick="moveSlide(1)">&#10095;</button>
            </div>

            <script src="script.js"></script>


        </section>

        <section class="sec-3">
            <h2>Conheça Nossa Loja</h2>

            <div class="Video">
                <video width="800" autoplay loop muted>
                    <source
                        src="Snapinsta.app_video_AQOORdKz_jWQ4leCtMaCP8swE2r-xv81vAEWVaLcch7G1nn7X5LelIXhJN0QKtwpBAqqtXC3E4Z3KcwAp2uREGck.mp4"
                        type="video/mp4">
                    <source src="videos/nomedovideo.webm" type="video/webm">
                    <source src="videos/nomedovideo.ogv" type="video/ogg">
                    Seu navegador não suporta a tag de vídeo.
                </video>
            </div>
        </section>

        <section class="sec-4">
            <h2 class="Produtos">Produtos</h2>





            <img src="camisa,blazer.jpg" alt="" class="camisabranca">
            <img src="camisa,blazer.jpg" alt="" class="camisabranca">
            <img src="camisa,blazer.jpg" alt="" class="camisabranca">
            <img src="camisa,blazer.jpg" alt="" class="camisabranca">
            <img src="Camisa branca,jeans.jpg" alt="" class="camisabranca">
            <img src="Camisa branca,jeans.jpg" alt="" class="camisabranca">
            <img src="Camisa branca,jeans.jpg" alt="" class="camisabranca">
            <img src="Camisa branca,jeans.jpg" alt="" class="camisabranca">
            <img src="Camisa branca,jeans.jpg" alt="" class="camisabranca">
            <img src="Camisa branca,jeans.jpg" alt="" class="camisabranca">
            <img src="Camisa branca,jeans.jpg" alt="" class="camisabranca">
        </section>

        <section class="sec-5">
            <h2>Looks</h2>


            <img src="camisa,blazer.jpg" alt="" class="camisabranca2">
            <img src="camisa,blazer.jpg" alt="" class="camisabranca2">
            <img src="camisa,blazer.jpg" alt="" class="camisabranca2">
            <img src="camisa,blazer.jpg" alt="" class="camisabranca2">
            <img src="Camisa branca,jeans.jpg" alt="" class="camisabranca2">
            <img src="Camisa branca,jeans.jpg" alt="" class="camisabranca2">
            <img src="Camisa branca,jeans.jpg" alt="" class="camisabranca2">
            <img src="Camisa branca,jeans.jpg" alt="" class="camisabranca2">
            <img src="Camisa branca,jeans.jpg" alt="" class="camisabranca2">
            <img src="Camisa branca,jeans.jpg" alt="" class="camisabranca2">
            <img src="Camisa branca,jeans.jpg" alt="" class="camisabranca2">

        </section>



    </body>

    </html>






    <script src="java.js"></script>
    <main>
        <section id="home">
            <h2>Bem-vindo à Claudio Almeida</h2>
            <p>Moda masculina de alta qualidade.</p>
        </section>



        </section>

        <section id="sobre">
            <h2>Sobre Nós</h2>
            <p>Conheça nossa história e missão.</p>
        </section>

        <section id="contato">
            <h2>Contato</h2>
            <p>Entre em contato conosco!</p>
            <p>Entre em contato conosco!</p>
            <p>Entre em contato conosco!</p>
       
            <div class="social-icons">
                <a href="https://www.facebook.com" target="_blank" class="icon">
                  <img src="facebook.png" alt="Facebook">
                </a>
                <a href="https://www.instagram.com" target="_blank" class="icon">
                  <img src="" alt="Instagram">
                </a>
                <a href="https://www.twitter.com" target="_blank" class="icon">
                  <img src="twitter-icon.png" alt="Twitter">
                </a>
                <a href="https://www.linkedin.com" target="_blank" class="icon">
                  <img src="linkedin-icon.png" alt="LinkedIn">
                </a>
                <a href="https://www.youtube.com" target="_blank" class="icon">
                  <img src="youtube-icon.png" alt="YouTube">
                </a>
              </div>
              
         
        </section>
        <!-- START Widget WhastApp hospedagemwordpresspro -->

    </main>
    <a href="https://api.whatsapp.com/send?phone=55NUMEROTELEFONE&text=Olá, preciso de mais informações!" id="waurlsite"
        class="bt-whatsApp" target="_blank">
        <img src="https://upload.wikimedia.org/wikipedia/commons/6/6b/WhatsApp.svg" alt="WhatsApp" width="60px">
    </a>

    <!-- Alerta de notificação -->
    <span id="alertWapp"
        style="right:30px; visibility: hidden; position:fixed;width:17px;height:17px;bottom:90px;background:red;z-index:101;font-size:11px;color:#fff;text-align:center;border-radius: 50%;font-weight:bold;line-height: normal;">
        1 </span>

    <!-- Caixa de mensagem que aparece após alguns segundos -->
    <div id="msg1"
        style="right: 90px; visibility: hidden; background: #fff;color: #000;position: fixed;width: 100px;bottom: 55px;font-size: 12px;line-height: 13px;padding: 3px; border-radius: 10px; border:1px solid #e2e2e2; box-shadow: 2px 2px 3px #999;z-index:100;">
        Olá, como podemos ajudar?
    </div>

    <script type="text/javascript">
        // Funções para exibir a caixa de mensagem
        function showIt2() {
            document.getElementById("msg1").style.visibility = "visible";
        }
        setTimeout("showIt2()", 5000);  // Exibe após 5 segundos

        function hiddenIt() {
            document.getElementById("msg1").style.visibility = "hidden";
        }
        setTimeout("hiddenIt()", 15000);  // Esconde após 15 segundos

        function showIt3() {
            document.getElementById("msg1").style.visibility = "visible";
        }
        setTimeout("showIt3()", 25000);  // Exibe novamente após 25 segundos

        // Função para mostrar o alerta de notificação
        function alertW() {
            document.getElementById("alertWapp").style.visibility = "visible";
        }
        setTimeout("alertW()", 15000);  // Exibe após 15 segundos
    </script>







    <footer>
        <p>&copy; 2024 Claudio Almeida. Todos os direitos reservados.</p>
        <p>R. Olegário Maciel, 332 - Centro, Patos de Minas - MG, 38700-543</p>
        <a class="WhatsApp"
            href="https://api.whatsapp.com/send?phone=55NUMEROTELEFONE&text=Olá, preciso de mais informações!"
            id="waurlsite" class="bt-whatsApp" target="_blank"
            style="right:25px; position:fixed;width:60px;height:60px;bottom:40px;z-index:100;">

    </footer>

    <script src="script.js"></script>




</body>

</html>
