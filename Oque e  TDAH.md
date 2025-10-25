<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>TDAH – Entenda e Saiba Como Amenizar</title>
    <style>
        /* ======== ESTILO GERAL ======== */
        :root {
            --bg-color: #f5f7fa;
            --text-color: #333;
            --primary: #4f46e5;
            --secondary: #06b6d4;
            --card-bg: #fff;
        }

        body.dark-mode {
            --bg-color: #111827;
            --text-color: #e5e7eb;
            --primary: #818cf8;
            --secondary: #22d3ee;
            --card-bg: #1f2937;
        }

        body {
            font-family: "Poppins", Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: var(--bg-color);
            color: var(--text-color);
            transition: 0.4s;
        }

        /* ======== MENU ======== */
        nav {
            position: fixed;
            top: 0;
            width: 100%;
            background-color: var(--card-bg);
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 15px 30px;
            box-shadow: 0 2px 8px rgba(0,0,0,0.1);
            z-index: 1000;
        }

        nav a {
            color: var(--text-color);
            margin: 0 15px;
            text-decoration: none;
            font-weight: 500;
        }

        nav a:hover {
            color: var(--secondary);
        }

        .toggle-btn {
            background-color: var(--secondary);
            border: none;
            color: white;
            padding: 8px 14px;
            border-radius: 6px;
            cursor: pointer;
            font-weight: 600;
        }

        header {
            text-align: center;
            padding: 120px 20px 60px;
            background: linear-gradient(135deg, var(--primary), var(--secondary));
            color: white;
        }

        header h1 {
            font-size: 2.8em;
        }

        header p {
            font-size: 1.2em;
            opacity: 0.9;
        }

        section {
            max-width: 900px;
            margin: 40px auto;
            background: var(--card-bg);
            padding: 40px;
            border-radius: 12px;
            box-shadow: 0 4px 12px rgba(0,0,0,0.08);
        }

        h2 {
            color: var(--primary);
            border-left: 6px solid var(--primary);
            padding-left: 10px;
            margin-top: 40px;
        }

        h3 {
            color: var(--secondary);
        }

        img {
            width: 100%;
            border-radius: 12px;
            margin: 20px 0;
            box-shadow: 0 2px 8px rgba(0,0,0,0.1);
        }

        ul {
            margin-left: 20px;
        }

        footer {
            text-align: center;
            padding: 30px;
            background-color: var(--card-bg);
            color: var(--text-color);
            border-top: 1px solid rgba(0,0,0,0.1);
        }

        footer p {
            margin: 0;
            font-size: 0.95em;
        }

        @media (max-width: 700px) {
            nav {
                flex-direction: column;
                gap: 10px;
            }
        }
    </style>
</head>
<body>

    <!-- MENU DE NAVEGAÇÃO -->
    <nav>
        <div>
            <a href="#sobre">O que é</a>
            <a href="#causas">Causas</a>
            <a href="#sintomas">Sintomas</a>
            <a href="#tratamento">Tratamento</a>
            <a href="#convivencia">Convivência</a>
        </div>
        <button class="toggle-btn" onclick="toggleMode()">🌙 Modo Escuro</button>
    </nav>

    <header>
        <h1>Transtorno de Déficit de Atenção e Hiperatividade (TDAH)</h1>
        <p>Compreenda o transtorno, suas causas, sintomas e formas de lidar com empatia.</p>
    </header>

    <section id="sobre">
        <h2>O que é TDAH?</h2>
        <img src="https://images.unsplash.com/photo-1601582582061-7a61b8a0c7b2?auto=format&fit=crop&w=900&q=60" alt="Concentração e foco">
        <p>
            O <strong>TDAH</strong> é um transtorno neurobiológico que afeta a atenção, o controle de impulsos e o comportamento. 
            Ele costuma aparecer na infância e pode acompanhar a pessoa por toda a vida.
        </p>
        <p>
            Não se trata de preguiça ou falta de disciplina, mas sim de uma condição reconhecida pela <strong>Organização Mundial da Saúde (OMS)</strong>, com causas genéticas e biológicas.
        </p>
    </section>

    <section id="causas">
        <h2>Causas do TDAH</h2>
        <img src="https://images.unsplash.com/photo-1553531384-cc64ac80f931?auto=format&fit=crop&w=900&q=60" alt="Cérebro humano em ilustração">
        <ul>
            <li><strong>Genéticas:</strong> histórico familiar é um dos principais fatores de risco.</li>
            <li><strong>Alterações neuroquímicas:</strong> diferenças na produção de dopamina e noradrenalina.</li>
            <li><strong>Fatores ambientais:</strong> exposição a toxinas, álcool ou tabaco durante a gestação.</li>
            <li><strong>Ambiente social:</strong> estresse e falta de rotina podem agravar os sintomas.</li>
        </ul>
    </section>

    <section id="sintomas">
        <h2>Principais Sintomas</h2>
        <img src="https://images.unsplash.com/photo-1554774853-b414d2b3d3cd?auto=format&fit=crop&w=900&q=60" alt="Criança estudando com dificuldade de foco">
        <h3>1. Tipo Desatento</h3>
        <ul>
            <li>Dificuldade em manter o foco.</li>
            <li>Esquecimento frequente.</li>
            <li>Perda de objetos.</li>
            <li>Dificuldade em seguir instruções.</li>
        </ul>

        <h3>2. Tipo Hiperativo/Impulsivo</h3>
        <ul>
            <li>Inquietação constante.</li>
            <li>Fala excessiva.</li>
            <li>Impaciência e impulsividade.</li>
            <li>Age antes de pensar.</li>
        </ul>

        <h3>3. Tipo Combinado</h3>
        <p>Reúne sintomas de desatenção e hiperatividade, sendo o tipo mais comum.</p>
    </section>

    <section id="tratamento">
        <h2>Tratamento e Manejo</h2>
        <img src="https://images.unsplash.com/photo-1601933470628-3e4e5b63b66b?auto=format&fit=crop&w=900&q=60" alt="Terapia e apoio psicológico">
        <p>Embora o TDAH não tenha cura, o tratamento adequado pode transformar a qualidade de vida da pessoa.</p>

        <h3>1. Intervenção Médica</h3>
        <p>Medicamentos como metilfenidato ou lisdexanfetamina ajudam na concentração e no controle de impulsos, sempre com prescrição médica.</p>

        <h3>2. Psicoterapia</h3>
        <p>A <strong>Terapia Cognitivo-Comportamental (TCC)</strong> auxilia na organização e na criação de estratégias emocionais.</p>

        <h3>3. Rotina Estruturada</h3>
        <ul>
            <li>Use agendas e lembretes.</li>
            <li>Divida grandes tarefas em partes pequenas.</li>
            <li>Mantenha horários fixos.</li>
        </ul>

        <h3>4. Apoio Familiar e Escolar</h3>
        <p>Compreensão e empatia fazem toda a diferença no progresso do tratamento.</p>

        <h3>5. Alimentação, Sono e Exercício</h3>
        <p>Hábitos saudáveis ajudam a equilibrar o humor e aumentar a concentração.</p>
    </section>

    <section id="convivencia">
        <h2>Convivendo com o TDAH</h2>
        <img src="https://images.unsplash.com/photo-1531379410502-63bfe8cdaf6f?auto=format&fit=crop&w=900&q=60" alt="Pessoa confiante e produtiva">
        <p>
            O TDAH não define quem a pessoa é. Com o tratamento certo e apoio, é possível desenvolver todo o potencial, transformando desafios em conquistas.
        </p>

        <blockquote style="font-style: italic; color: var(--primary); border-left:4px solid var(--primary); padding-left:15px;">
            "Informação e empatia são os primeiros passos para transformar o desafio em superação."
        </blockquote>
    </section>

    <footer>
        <p>© 2025 - Página informativa sobre TDAH | Desenvolvido com empatia 💙</p>
    </footer>

    <script>
        // Função para alternar o modo escuro
        function toggleMode() {
            document.body.classList.toggle('dark-mode');
            const btn = document.querySelector('.toggle-btn');
            btn.textContent = document.body.classList.contains('dark-mode') ? '☀️ Modo Claro' : '🌙 Modo Escuro';
        }
    </script>
</body>
</html>
