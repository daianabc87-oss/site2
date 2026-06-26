<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Daiana Cardoso | Mapa da Alma & Terapias Integrativas</title>
    <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@400;700&family=Inter:wght@300;400;500&display=swap" rel="stylesheet">
    <style>
        :root {
            --gold: #C9A56B;
            --creme: #F8F1E9;
            --brown: #3F2A1E;
            --dark: #1C140F;
        }
        * { margin: 0; padding: 0; box-sizing: border-box; }
        body {
            font-family: 'Inter', sans-serif;
            color: var(--brown);
            background: #fff;
            line-height: 1.7;
        }
        h1, h2, h3 { font-family: 'Playfair Display', serif; }

        /* NAV */
        nav {
            position: fixed;
            top: 0;
            width: 100%;
            background: rgba(255,255,255,0.95);
            backdrop-filter: blur(10px);
            z-index: 100;
            padding: 20px 5%;
            border-bottom: 1px solid #eee;
        }
        .nav-inner {
            max-width: 1200px;
            margin: 0 auto;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }
        .logo { font-family: 'Playfair Display', serif; font-size: 28px; color: var(--brown); }
        .nav-links a {
            margin-left: 40px;
            text-decoration: none;
            color: var(--brown);
            font-weight: 500;
        }

        /* HERO */
        .hero {
            height: 100vh;
            background: linear-gradient(rgba(0,0,0,0.4), rgba(0,0,0,0.4)), url('https://via.placeholder.com/1920x1080/3F2A1E/ F8F1E9?text=Daiana+Cardoso') center/cover no-repeat;
            display: flex;
            align-items: center;
            text-align: center;
            color: white;
        }
        .hero-content {
            max-width: 800px;
            margin: 0 auto;
            padding: 0 20px;
        }
        .hero h1 {
            font-size: 4.5rem;
            margin-bottom: 20px;
        }
        .hero p {
            font-size: 1.4rem;
            margin-bottom: 40px;
        }
        .btn {
            background: var(--gold);
            color: white;
            padding: 16px 40px;
            border-radius: 50px;
            text-decoration: none;
            font-weight: 600;
            display: inline-block;
        }

        /* SEÇÕES */
        section { padding: 120px 5%; max-width: 1200px; margin: 0 auto; }
        .section-title {
            text-align: center;
            font-size: 3rem;
            margin-bottom: 60px;
            color: var(--brown);
        }

        .sobre { background: var(--creme); }
        .servicos { background: white; }
        .card {
            background: white;
            padding: 40px;
            border-radius: 20px;
            box-shadow: 0 10px 30px rgba(0,0,0,0.08);
            text-align: center;
            transition: all 0.3s;
        }
        .card:hover { transform: translateY(-10px); }

        footer {
            background: var(--dark);
            color: #ddd;
            text-align: center;
            padding: 80px 20px;
        }
    </style>
</head>
<body>

    <!-- NAV -->
    <nav>
        <div class="nav-inner">
            <div class="logo">Daiana Cardoso</div>
            <div class="nav-links">
                <a href="#sobre">Sobre mim</a>
                <a href="#servicos">Trabalhos</a>
                <a href="#contato">Contato</a>
            </div>
        </div>
    </nav>

    <!-- HERO -->
    <section class="hero">
        <div class="hero-content">
            <h1>Desperte sua Alma</h1>
            <p>Leitura de Mapa da Alma + Terapias Integrativas para mulheres que desejam viver com mais clareza, propósito e leveza.</p>
            <a href="#contato" class="btn">Agendar Leitura</a>
        </div>
    </section>

    <!-- SOBRE -->
    <section id="sobre" class="sobre">
        <h2 class="section-title">Bem-vinda ao seu novo ciclo</h2>
        <p style="font-size:1.3rem; text-align:center; max-width:700px; margin:0 auto;">
            Sou Daiana Cardoso, terapeuta integrativa e facilitadora de processos de autoconhecimento. 
            Ajudar mulheres a reconectarem-se com sua essência, liberarem o que não pertence mais e 
            caminharem com coragem em direção à vida que realmente desejam viver.
        </p>
    </section>

    <!-- SERVIÇOS -->
    <section id="servicos" class="servicos">
        <h2 class="section-title">Como posso te ajudar</h2>
        
        <div style="display:grid; grid-template-columns: repeat(auto-fit, minmax(320px, 1fr)); gap:40px;">
            
            <div class="card">
                <h3>Mapa da Alma</h3>
                <p>Uma leitura profunda que revela seus padrões, talentos, ciclos e o caminho de alma para esta vida. Ideal para quem busca clareza e direção.</p>
                <strong>Investimento: Sob consulta</strong><br><br>
                <a href="#" class="btn">Agendar</a>
            </div>

            <div class="card">
                <h3>Terapia Integrativa</h3>
                <p>Combinação de Tarot Terapêutico, Constelação Familiar, Cura Energética e práticas de Sagrado Feminino.</p>
                <strong>Investimento: Sob consulta</strong><br><br>
                <a href="#" class="btn">Agendar</a>
            </div>

            <div class="card">
                <h3>Acompanhamento 1:1</h3>
                <p>Processo de 3 ou 6 sessões para uma transformação mais profunda e sustentada.</p>
                <strong>Investimento: Sob consulta</strong><br><br>
                <a href="#" class="btn">Saiba mais</a>
            </div>
        </div>
    </section>

    <footer id="contato">
        <p style="font-size:1.5rem; margin-bottom:20px;">Pronto para reencontrar seu caminho?</p>
        <a href="https://wa.me/5551SEUNUMERO" class="btn" style="background:#25D366;">Falar no WhatsApp</a>
        <p style="margin-top:60px; opacity:0.7;">© 2026 Daiana Cardoso — Porto Alegre, RS</p>
    </footer>

</body>
</html># site2
