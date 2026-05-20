<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Yorran Personal - Links</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Roboto, Helvetica, Arial, sans-serif;
        }

        body {
            background-color: #0D0D0D;
            color: #FFFFFF;
            display: flex;
            justify-content: center;
            align-items: flex-start;
            min-height: 100vh;
            padding: 40px 20px;
        }

        .container {
            width: 100%;
            max-width: 450px;
            text-align: center;
        }

        /* Cabeçalho */
        .profile-area {
            margin-bottom: 35px;
        }

        .profile-pic {
            width: 110px;
            height: 110px;
            border-radius: 50%;
            border: 3px solid #39FF14;
            object-fit: cover;
            margin-bottom: 15px;
            box-shadow: 0 0 15px rgba(57, 255, 20, 0.4);
        }

        h1 {
            font-size: 22px;
            font-weight: 700;
            letter-spacing: 0.5px;
            margin-bottom: 8px;
            color: #FFFFFF;
        }

        .subtitle {
            font-size: 14px;
            color: #A0A0A0;
            line-height: 1.5;
            padding: 0 10px;
        }

        /* Links / Botões */
        .links-area {
            display: flex;
            flex-direction: column;
            gap: 18px;
        }

        .btn {
            display: block;
            text-decoration: none;
            padding: 18px 20px;
            border-radius: 12px;
            transition: all 0.3s ease;
            text-align: center;
        }

        /* Botão Consultoria (Roxo - 10%) */
        .btn-consultoria {
            background-color: #8A2BE2;
            color: #FFFFFF;
            box-shadow: 0 4px 20px rgba(138, 43, 226, 0.4);
        }

        .btn-consultoria:hover {
            transform: translateY(-3px);
            box-shadow: 0 6px 25px rgba(138, 43, 226, 0.6);
        }

        /* Botão Personal (Verde - 30%) */
        .btn-personal {
            background: transparent;
            border: 2px solid #39FF14;
            color: #39FF14;
            box-shadow: 0 0 10px rgba(57, 255, 20, 0.1);
        }

        .btn-personal:hover {
            background-color: #39FF14;
            color: #0D0D0D;
            transform: translateY(-3px);
            box-shadow: 0 5px 20px rgba(57, 255, 20, 0.4);
            font-weight: bold;
        }

        .btn-title {
            font-size: 16px;
            font-weight: 700;
            text-transform: uppercase;
            letter-spacing: 1px;
            margin-bottom: 4px;
            display: block;
        }

        .btn-desc {
            font-size: 12px;
            display: block;
            opacity: 0.9;
        }

        .btn-personal .btn-desc {
            color: #FFFFFF;
        }
        .btn-personal:hover .btn-desc {
            color: #0D0D0D;
        }

        /* Rodapé */
        footer {
            margin-top: 50px;
            font-size: 11px;
            color: #404040;
            letter-spacing: 1px;
        }
    </style>
</head>
<body>

    <div class="container">
        <!-- Cabeçalho -->
        <div class="profile-area">
            <!-- Caso queira usar uma foto, substitua o src pelo link da sua foto (ex: do imgur ou instagram) -->
            <img class="profile-pic" src="https://www.facebook.com/photo/?fbid=3172223659627630&set=a.110881542428539" alt="Yorran Personal">
            <h1>Yorran Personal</h1>
            <p class="subtitle">Treino inteligente e estratégias validadas para transformar o seu corpo.</p>
        </div>

        <!-- Links Principais -->
        <div class="links-area">
            
            <!-- Botão Consultoria (Roxo Elétrico - Foco 10%) -->
            <a href="https://api.whatsapp.com/send?phone=5517981507581&text=Ol%C3%A1%2C%20Yorran%21%20Vim%20pelo%20seu%20site%20e%20quero%20entender%20como%20funciona%20a%20sua%20Consultoria%20Online%20para%20come%C3%A7ar%20os%20meus%20treinos." target="_blank" class="btn btn-consultoria">
                <span class="btn-title">🚀 Consultoria Online</span>
                <span class="btn-desc">Vagas limitadas. Treine onde e quando quiser com o meu método.</span>
            </a>

            <!-- Botão Personal Presencial (Verde Neon - Estrutura 30%) -->
            <a href="https://api.whatsapp.com/send?phone=5517981507581&text=Ol%C3%A1%2C%20Yorran%21%20Vi%20seu%20link%20na%20bio%20e%20gostaria%20de%20consultar%20sua%20disponibilidade%20de%20hor%C3%A1rios%20para%20Personal%20Presencial." target="_blank" class="btn btn-personal">
                <span class="btn-title">💪 Personal Presencial</span>
                <span class="btn-desc">Consulte disponibilidade. Atendimento exclusivo e focado em alta performance.</span>
            </a>

        </div>

        <!-- Rodapé discreto -->
        <footer>
            &copy; 2026 YORRAN PERSONAL. TODOS OS DIREITOS RESERVADOS.
        </footer>
    </div>

</body>
</html>
