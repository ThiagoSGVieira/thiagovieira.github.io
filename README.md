<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Thiago Vieira | Psicólogo Perito Judicial</title>
    <meta name="description" content="Psicólogo Perito Judicial - CRP 06/204224. Produção de laudos e pareceres psicológicos, leitura crítica de documentos, assistência técnica e consultoria para advogados, famílias e instituições.">
    <meta name="keywords" content="psicólogo perito judicial, laudo psicológico, parecer psicológico, assistência técnica, leitura de laudo, psicologia forense, consultoria jurídica psicologia, CRP 06/204224, ética, humano, acolhimento">
    <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@700&family=Roboto:wght@400;700&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">
    <style>
        :root {
            --primary: #f59e0b;
            --primary-dark: #c47c00;
            --bg: #18181b;
            --bg-light: #23232b;
            --text: #f4f4f5;
            --text-muted: #bdbdbd;
            --border: #32323e;
            --transition: 0.3s cubic-bezier(.4,0,.2,1);
        }
        * { box-sizing: border-box; margin: 0; padding: 0; }
        body {
            background: var(--bg);
            color: var(--text);
            font-family: 'Roboto', Arial, sans-serif;
            line-height: 1.6;
        }
        header {
            background: var(--bg-light);
            border-bottom: 1px solid var(--border);
            position: sticky;
            top: 0;
            z-index: 100;
        }
        .container {
            max-width: 1100px;
            margin: 0 auto;
            padding: 0 1.2rem;
        }
        nav {
            display: flex;
            justify-content: flex-start;
            align-items: center;
            height: 70px;
        }
        .logo {
            font-family: 'Playfair Display', serif;
            font-size: 1.5rem;
            color: var(--primary);
            letter-spacing: 1px;
            font-weight: 700;
            text-decoration: none;
            display: flex;
            align-items: center;
            gap: 0.7rem;
        }
        .logo img {
            height: 52px;
            width: auto;
            margin-right: 10px;
            border-radius: 0;
            box-shadow: none;
            background: transparent;
            display: block;
        }
        .crp {
            font-size: 1.05rem;
            color: var(--primary);
            margin-top: 0.2rem;
            font-weight: 500;
            letter-spacing: 1px;
        }
        .hero {
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            min-height: 75vh;
            text-align: center;
            background: linear-gradient(120deg, #23232b 80%, #f59e0b22 100%);
            padding: 3rem 0 2rem 0;
        }
        .hero-img {
            width: 210px;
            height: 210px;
            border-radius: 50%;
            border: 5px solid var(--primary);
            box-shadow: 0 8px 24px #0008;
            margin-bottom: 2rem;
            object-fit: cover;
            object-position: center;
            background: #fff;
        }
        .hero h1 {
            font-family: 'Playfair Display', serif;
            font-size: 2.4rem;
            color: var(--primary);
            margin-bottom: 0.5rem;
            font-weight: 700;
        }
        .hero .crp {margin-bottom: 1.2rem;}
        .hero p {
            font-size: 1.18rem;
            color: var(--text-muted);
            max-width: 650px;
            margin: 0 auto 1.5rem;
        }
        .hero .welcome {
            background: var(--bg-light);
            border-radius: 12px;
            padding: 1.8rem 2rem;
            margin: 1.5rem auto 0;
            max-width: 700px;
            border: 1px solid var(--border);
            box-shadow: 0 4px 16px #0003;
        }
        .hero .welcome p {
            font-size: 1.13rem;
            color: var(--text);
            margin-bottom: 1rem;
        }
        .hero .welcome .cta {
            color: var(--primary);
            font-weight: 700;
            font-size: 1.08rem;
        }
        section { padding: 4rem 0; }
        .section-title {
            font-family: 'Playfair Display', serif;
            font-size: 2rem;
            color: var(--primary);
            text-align: center;
            margin-bottom: 0.5rem;
            font-weight: 700;
            letter-spacing: 0.5px;
        }
        .section-desc {
            color: var(--text-muted);
            text-align: center;
            margin-bottom: 2.5rem;
            font-size: 1.13rem;
            max-width: 800px;
            margin-left: auto;
            margin-right: auto;
        }
        .grid {
            display: grid;
            gap: 2rem;
        }
        @media (min-width: 900px) {
            .grid-3 { grid-template-columns: repeat(3, 1fr); }
            .grid-2 { grid-template-columns: repeat(2, 1fr); }
        }
        @media (max-width: 900px) {
            .grid-3, .grid-2 { grid-template-columns: 1fr; }
        }
        .card {
            background: var(--bg-light);
            border-radius: 12px;
            padding: 2rem;
            border: 1px solid var(--border);
            box-shadow: 0 2px 12px #0003;
            transition: transform var(--transition), box-shadow var(--transition);
        }
        .card:hover { transform: translateY(-4px) scale(1.01); box-shadow: 0 8px 24px #0004;}
        .card .icon {
            font-size: 2.3rem;
            color: var(--primary);
            margin-bottom: 0.8rem;
        }
        .card h3 {
            font-size: 1.22rem;
            margin-bottom: 0.7rem;
            color: var(--primary);
            font-weight: 700;
        }
        .card p, .card ul { color: var(--text-muted);}
        .card ul { padding-left: 1.2rem; margin-top: 0.7rem;}
        .card ul li { margin-bottom: 0.5rem;}
        .target-audience {
            background: linear-gradient(135deg, #23232b 0%, #2a2a35 100%);
            border-radius: 16px;
            padding: 2.5rem;
            margin: 2rem 0;
            border: 1px solid var(--border);
        }
        .target-audience h3 {
            color: var(--primary);
            font-size: 1.4rem;
            margin-bottom: 1.2rem;
            text-align: center;
            font-family: 'Playfair Display', serif;
        }
        .target-list {
            display: grid;
            gap: 1rem;
            margin-top: 1.5rem;
        }
        @media (min-width: 600px) {
            .target-list { grid-template-columns: repeat(2, 1fr); }
        }
        .target-item {
            display: flex;
            align-items: center;
            gap: 0.8rem;
            padding: 0.8rem;
            background: var(--bg);
            border-radius: 8px;
            border: 1px solid var(--border);
        }
        .target-item i {
            color: var(--primary);
            font-size: 1.2rem;
            width: 20px;
            text-align: center;
        }
        .article-list .card { min-height: 200px; }
        .article-link {
            font-weight: 700;
            color: var(--primary);
            margin-top: 1rem;
            display: inline-block;
            text-decoration: none;
            transition: color var(--transition);
            position: relative;
            padding-right: 1.2rem;
            cursor: pointer;
        }
        .article-link::after {
            content: '→';
            position: absolute;
            right: 0; top: 0;
            transition: right var(--transition);
        }
        .article-link:hover::after { right: -6px; }
        .article-content {
            display: none;
            background: var(--bg-light);
            border-radius: 12px;
            margin: 2rem auto;
            max-width: 700px;
            padding: 2.5rem 2rem;
            box-shadow: 0 2px 12px #0002;
        }
        .article-content.active { display: block; animation: fadeIn 0.7s;}
        .article-content h3 {
            color: var(--primary);
            font-size: 1.5rem;
            margin-bottom: 1.2rem;
            font-family: 'Playfair Display', serif;
        }
        .article-content h4 {
            font-size: 1.13rem;
            color: var(--primary);
            margin: 1.7rem 0 0.7rem 0;
            border-left: 4px solid var(--primary);
            padding-left: 0.9rem;
        }
        .article-content blockquote {
            margin: 1.5rem 0;
            padding: 1rem 1.5rem;
            background: #23232b;
            border-left: 4px solid var(--primary);
            color: var(--text-muted);
            font-style: italic;
        }
        .article-content ul { margin-bottom: 1.5rem;}
        .close-article {
            display: inline-block;
            margin-top: 2rem;
            background: var(--bg);
            color: var(--primary);
            font-weight: 700;
            padding: 0.5rem 1.2rem;
            border-radius: 8px;
            text-decoration: none;
            transition: background var(--transition), color var(--transition);
            cursor: pointer;
        }
        .close-article:hover { background: var(--primary); color: var(--bg); }
        .faq-item {
            border-bottom: 1px solid var(--border);
            padding: 1.5rem 0;
        }
        .faq-item:last-child { border-bottom: none; }
        .faq-item h4 { 
            color: var(--primary); 
            font-size: 1.15rem; 
            margin-bottom: 0.7rem;
            font-weight: 700;
        }
        .faq-item p {
            color: var(--text-muted);
            line-height: 1.7;
        }
        .contact-section {
            background: linear-gradient(120deg, #f59e0b 80%, #23232b 100%);
            color: #18181b;
            padding: 3.5rem 0;
            position: relative;
            text-align: center;
        }
        .contact-section h2, .contact-section p { color: #18181b;}
        .contact-links {
            display: flex;
            flex-direction: column;
            align-items: center;
            gap: 1.2rem;
            margin-top: 2rem;
        }
        .contact-links a {
            background: #fff6;
            color: #18181b;
            font-weight: 700;
            padding: 0.8rem 1.7rem;
            border-radius: 8px;
            text-decoration: none;
            display: flex;
            align-items: center;
            gap: 0.7rem;
            transition: background var(--transition), color var(--transition);
            font-size: 1.08rem;
            word-break: break-all;
        }
        .contact-links a:hover { background: #fff; color: var(--primary-dark);}
        @media (min-width: 600px) {
            .contact-links { flex-direction: row; flex-wrap: wrap; justify-content: center;}
        }
        footer {
            background: var(--bg-light);
            padding: 2rem 0;
            color: var(--text-muted);
            border-top: 1px solid var(--border);
            text-align: center;
            font-size: 1rem;
        }
        .footer-socials {
            margin: 1rem 0 0.5rem 0;
            display: flex;
            justify-content: center;
            gap: 1.3rem;
        }
        .footer-socials a {
            color: var(--text-muted);
            font-size: 1.5rem;
            transition: color var(--transition);
        }
        .footer-socials a:hover { color: var(--primary);}
        .footer-crp {
            color: var(--primary);
            font-size: 1.05rem;
            margin-top: 0.2rem;
            letter-spacing: 1px;
            font-weight: 600;
        }
        @keyframes fadeIn {
            from { opacity: 0; transform: translateY(20px);}
            to { opacity: 1; transform: translateY(0);}
        }
    </style>
</head>
<body>
    <header>
        <div class="container">
            <nav>
                <a href="#" class="logo" aria-label="Logo Thiago Vieira">
                    <img src="https://d41chssnpqdne.cloudfront.net/user_upload_by_module/chat_bot/files/6608603/k1oIon1rVfvXrYSC.png?Expires=1753049975&Signature=eHZxGqUdpeae50~s09VEdNfBcFhM8AEJlQhhuSBaQJBNwbzM6~02kaEsmIsyAep4pdvVgOLr~v~4o~djcwcuM2ehgUiS3rus~lbsZtJuI5hZo~CAbRXPe07wcZxc1N0Vb-JvsijViJvv4F~mqm7hbMunwmcY6ExbiLSFiMJrxMwICZI2irUU5ZCgOiaIuHTo9AyfKCfRcIZJsz-~2lXVr-qZjFY9qmJkXbZpzalot0bQIGosSp~pkwMcmdNNeYGyO7Q6zsICQ-ioqDT6vXI9zsd4I0047iV-y9gszsen2RXknAP4yPCTLYmk7yAt7pUHrrRpfvXrGRLLERa3T5Tfgw__&Key-Pair-Id=K3USGZIKWMDCSX" alt="Logo Caduceu Justiça Psicologia Thiago Vieira" />
                    Thiago Vieira
                </a>
            </nav>
        </div>
    </header>
    <main>
        <section class="hero" id="home">
            <img class="hero-img" src="https://d41chssnpqdne.cloudfront.net/user_upload_by_module/chat_bot/files/6608603/8JwM8VaQO32FxM20.png?Expires=1752935105&Signature=pV6KaleFASGdxdxbuDnaF1WQgsN0CdWzXQx17TNDZX4Mxn5Bpjsm4kyEVBylpGmkvkpRLrJdkktMAkGMRPV0lSXQa5SnDJvNl7amc2WY0QGIsHeDHv4AYbDT~YwnMCjPWgsMyqiLh5FITP27g1Tbq2SQn6EBIDsoGxmDD8MdnDlonAtdBqTzEsoxDs5VcKlxY086Qt44g0-qMbBUfH7z1xmN9e4IUoZzvlRvwGPCmddFOLEsXPXJoRqQSZbG6mfdOagrI5-2WQ9MH653gfXdD435B-EbtGUC499A-YIAaBglVNC62MUWlFVAKGeO7dwZAJDcgT5wZKpOmaCuf47xew__&Key-Pair-Id=K3USGZIKWMDCSX" alt="Thiago Vieira - Psicólogo Perito Judicial especializado em laudos, pareceres e assistência técnica">
            <h1>Psicólogo Perito Judicial</h1>
            <div class="crp">CRP 06/204224</div>
            <p>
                Atuação ética, técnica e acolhedora em Psicologia Jurídica. Produção de laudos psicológicos, pareceres técnicos e leitura crítica de documentos já existentes para advogados, famílias e instituições. Meu compromisso é contribuir para decisões mais justas e fundamentadas, oferecendo suporte completo em demandas judiciais e administrativas.
            </p>
            <div class="welcome">
                <p>
                    <strong>Bem-vindo ao meu espaço profissional.</strong> Cada demanda é tratada com respeito, escuta qualificada e compromisso com a justiça. Produzo laudos e pareceres psicológicos, além de analisar criticamente documentos já existentes, oferecendo suporte técnico para advogados, partes e instituições.
                </p>
                <p>
                    Com sólida formação e experiência em Psicologia Jurídica, atuo na elaboração, revisão e orientação técnica de documentos, sempre com ética e responsabilidade.
                </p>
                <p class="cta">
                    Precisa de um laudo psicológico para processo judicial ou administrativo? Busca um parecer técnico detalhado? Tem dúvidas sobre um documento já existente? Conte com minha experiência para esclarecer, orientar e fortalecer sua demanda, promovendo o contraditório, a ampla defesa e a proteção de direitos.
                </p>
            </div>
        </section>
        <!-- SERVIÇOS -->
        <section id="servicos">
            <div class="container">
                <h2 class="section-title">Serviços</h2>
                <p class="section-desc">
                    Atendo demandas relacionadas à produção de laudos psicológicos, elaboração de pareceres técnicos, análise e revisão de documentos já existentes, impugnações, auxílio na formulação de quesitos e consultoria estratégica para advogados, famílias e instituições. Minha atuação é pautada pela ética, rigor científico e compromisso com a justiça.
                </p>
                <div class="grid grid-3">
                    <div class="card">
                        <div class="icon"><i class="fas fa-file-alt"></i></div>
                        <h3>Laudos Psicológicos</h3>
                        <p>
                            Elaboração de laudos psicológicos para processos judiciais e administrativos, seguindo rigorosamente as normas do CFP e os princípios éticos da profissão. Os laudos são instrumentos fundamentais para subsidiar decisões em questões de guarda, interdição, avaliação de capacidade, entre outros.
                        </p>
                        <ul>
                            <li>Laudos em processos cíveis, criminais e de família</li>
                            <li>Laudos para concursos, sindicâncias e demandas administrativas</li>
                            <li>Metodologia clara, objetiva e fundamentada</li>
                        </ul>
                    </div>
                    <div class="card">
                        <div class="icon"><i class="fas fa-user-shield"></i></div>
                        <h3>Pareceres Técnicos e Impugnações</h3>
                        <p>
                            Produção de pareceres técnicos detalhados sobre documentos psicológicos, análise crítica de laudos já existentes, impugnações fundamentadas e auxílio na elaboração de quesitos para o processo. O objetivo é garantir a defesa de direitos e a justiça processual.
                        </p>
                        <ul>
                            <li>Pareceres para subsidiar estratégias jurídicas</li>
                            <li>Impugnação de laudos e manifestações técnicas</li>
                            <li>Auxílio na elaboração de quesitos e esclarecimentos</li>
                        </ul>
                    </div>
                    <div class="card">
                        <div class="icon"><i class="fas fa-comments"></i></div>
                        <h3>Consultoria Especializada</h3>
                        <p>
                            Orientação técnica para advogados(as), famílias e instituições sobre produção, leitura e compreensão de laudos e pareceres psicológicos. Consultoria estratégica para audiências, manifestações e esclarecimento de dúvidas sobre a atuação do psicólogo no Judiciário.
                        </p>
                        <ul>
                            <li>Reuniões explicativas e tira-dúvidas</li>
                            <li>Relatórios e pareceres complementares</li>
                            <li>Atualização sobre normativas e jurisprudência</li>
                        </ul>
                    </div>
                </div>
            </div>
        </section>
        <!-- PÚBLICO-ALVO -->
        <section id="publico">
            <div class="container">
                <div class="target-audience">
                    <h3>Público-Alvo</h3>
                    <div class="target-list">
                        <div class="target-item"><i class="fas fa-balance-scale"></i>
                            <span>
                                <strong>Advogados(as) e Operadores do Direito:</strong> profissionais que necessitam de laudos psicológicos, pareceres técnicos, análise de documentos já existentes, impugnações ou esclarecimentos para processos judiciais e administrativos.
                            </span>
                        </div>
                        <div class="target-item"><i class="fas fa-users"></i>
                            <span>
                                <strong>Famílias e Partes em Processo:</strong> pessoas envolvidas em disputas judiciais (guarda, interdição, alienação parental, etc.) que precisam de laudo psicológico, parecer técnico ou desejam entender e questionar documentos já produzidos.
                            </span>
                        </div>
                        <div class="target-item"><i class="fas fa-building"></i>
                            <span>
                                <strong>Instituições Públicas e Privadas:</strong> órgãos, empresas e entidades que necessitam de laudos, pareceres ou análise técnica de documentos apresentados em sindicâncias, processos internos, concursos ou demandas administrativas.
                            </span>
                        </div>
                        <div class="target-item"><i class="fas fa-handshake"></i>
                            <span>
                                <strong>Organizações e ONGs:</strong> entidades do terceiro setor que atuam em interface com o Judiciário e precisam de laudos, pareceres ou orientação técnica sobre documentos psicológicos.
                            </span>
                        </div>
                    </div>
                </div>
            </div>
        </section>
        <!-- ARTIGOS -->
        <section id="artigos">
            <div class="container">
                <h2 class="section-title">Artigos & Conteúdo</h2>
                <p class="section-desc">
                    Conheça em detalhes o escopo, os limites e a importância da produção de laudos, pareceres psicológicos e da leitura crítica de documentos, assistência técnica e consultoria em Psicologia Jurídica. Estes artigos visam esclarecer dúvidas frequentes e apresentar, de forma transparente, como posso contribuir para seu caso.
                </p>
                <div class="grid grid-3 article-list">
                    <div class="card">
                        <h3>O que faz um psicólogo perito e assistente técnico judicial?</h3>
                        <p>
                            Entenda como o psicólogo pode atuar tanto na produção de laudos e pareceres quanto na análise crítica de documentos já existentes, orientando advogados e partes. Saiba por que a atuação técnica é fundamental para o contraditório e a justiça.
                        </p>
                        <a href="#" class="article-link" data-article="art1">Ler artigo completo</a>
                    </div>
                    <div class="card">
                        <h3>Quando solicitar um laudo, parecer ou leitura crítica?</h3>
                        <p>
                            Veja em quais situações é recomendável buscar a produção de um laudo psicológico, um parecer técnico ou uma segunda opinião sobre documentos já existentes, e como isso pode impactar seu processo.
                        </p>
                        <a href="#" class="article-link" data-article="art2">Ler artigo completo</a>
                    </div>
                    <div class="card">
                        <h3>Como posso ajudar: meu trabalho em laudos, pareceres e leitura crítica</h3>
                        <p>
                            Entenda o que faço, como atuo e de que forma posso contribuir tecnicamente para sua demanda judicial ou administrativa, seja produzindo laudos, pareceres ou revisando documentos já existentes.
                        </p>
                        <a href="#" class="article-link" data-article="art3">Ler artigo completo</a>
                    </div>
                </div>
                <!-- Artigos completos -->
                <div class="article-content" id="art1">
                    <h3>O que faz um psicólogo perito e assistente técnico judicial?</h3>
                    <p>
                        O psicólogo perito judicial é nomeado pelo juiz para produzir laudos psicológicos em processos judiciais, respondendo aos quesitos formulados pelas partes e pelo magistrado. Já o psicólogo assistente técnico pode ser contratado por uma das partes para elaborar pareceres técnicos, analisar criticamente laudos já existentes, impugnar documentos e orientar a estratégia jurídica.
                    </p>
                    <h4>Principais funções:</h4>
                    <ul>
                        <li>
                            <strong>Produção de laudos psicológicos:</strong> avaliação e elaboração de laudos para processos cíveis, criminais, de família, concursos, sindicâncias e demandas administrativas.
                        </li>
                        <li>
                            <strong>Parecer técnico:</strong> elaboração de documento técnico que pode ser anexado ao processo, subsidiando a defesa ou contestação da parte contratante.
                        </li>
                        <li>
                            <strong>Análise crítica de documentos:</strong> leitura detalhada de laudos já existentes, verificando metodologia, fundamentação e clareza das conclusões.
                        </li>
                        <li>
                            <strong>Auxílio ao advogado(a):</strong> orientação sobre quesitos, estratégias de impugnação e esclarecimento de dúvidas técnicas.
                        </li>
                        <li>
                            <strong>Participação em audiências:</strong> quando necessário, o psicólogo pode participar de audiências, prestando esclarecimentos técnicos ao juiz e às partes.
                        </li>
                    </ul>
                    <blockquote>
                        O psicólogo pode ser fundamental tanto na produção de documentos inéditos quanto na análise, revisão e impugnação de laudos já existentes, sempre com ética e fundamentação científica.
                    </blockquote>
                    <a href="#" class="close-article">Voltar</a>
                </div>
                <div class="article-content" id="art2">
                    <h3>Quando solicitar um laudo, parecer ou leitura crítica?</h3>
                    <p>
                        A produção de laudo psicológico é indicada quando o processo exige avaliação técnica inédita sobre aspectos psicológicos relevantes, como guarda, interdição, avaliação de capacidade, entre outros. O parecer técnico é útil para embasar estratégias jurídicas, esclarecer dúvidas ou complementar informações já existentes. Já a leitura crítica é recomendada quando há dúvidas sobre a metodologia, fundamentação ou conclusões de laudos já produzidos.
                    </p>
                    <h4>Exemplos de situações:</h4>
                    <ul>
                        <li>
                            <strong>Necessidade de laudo inédito:</strong> quando não há documento anterior ou quando há solicitação judicial para avaliação psicológica.
                        </li>
                        <li>
                            <strong>Necessidade de parecer técnico:</strong> para subsidiar manifestações, recursos, defesas ou para complementar documentos.
                        </li>
                        <li>
                            <strong>Dúvidas sobre laudo existente:</strong> quando o laudo apresenta inconsistências, omissões, ou quando se busca uma segunda opinião técnica.
                        </li>
                        <li>
                            <strong>Impugnação de documentos:</strong> para contestar laudos, apontar fragilidades técnicas ou esclarecer eventuais vieses.
                        </li>
                    </ul>
                    <blockquote>
                        O psicólogo pode atuar tanto produzindo novos documentos quanto revisando e questionando laudos já existentes, colaborando para a justiça e a defesa de direitos.
                    </blockquote>
                    <a href="#" class="close-article">Voltar</a>
                </div>
                <div class="article-content" id="art3">
                    <h3>Como posso ajudar: meu trabalho em laudos, pareceres e leitura crítica</h3>
                    <p>
                        Minha atuação contempla a produção de laudos psicológicos, pareceres técnicos e a leitura crítica de documentos já existentes. Em todos os casos, aplico metodologia rigorosa, respeito às normas do CFP e total compromisso ético.
                    </p>
                    <h4>Etapas do meu trabalho:</h4>
                    <ul>
                        <li>
                            <strong>Produção de laudos:</strong> realizo avaliações psicológicas, entrevistas, análise documental e elaboração de laudo claro, objetivo e fundamentado, de acordo com a demanda judicial ou administrativa.
                        </li>
                        <li>
                            <strong>Parecer técnico:</strong> elaboro parecer detalhado sobre questões específicas do processo, podendo complementar ou esclarecer pontos de laudos já existentes.
                        </li>
                        <li>
                            <strong>Leitura crítica:</strong> analiso laudos psicológicos já produzidos, identificando inconsistências, omissões ou fragilidades técnicas, e produzo relatório para subsidiar estratégias jurídicas.
                        </li>
                        <li>
                            <strong>Orientação técnica:</strong> ofereço reuniões para discussão de estratégias, esclarecimento de dúvidas e apoio à elaboração de quesitos ou impugnações.
                        </li>
                        <li>
                            <strong>Sigilo e ética:</strong> todo o serviço é realizado com total sigilo, respeito à legislação vigente e compromisso com a ética profissional.
                        </li>
                    </ul>
                    <blockquote>
                        Seja para produzir um novo laudo, elaborar um parecer técnico ou revisar documentos já existentes, estou à disposição para contribuir com conhecimento, responsabilidade e dedicação.
                    </blockquote>
                    <a href="#" class="close-article">Voltar</a>
                </div>
            </div>
        </section>
        <!-- FAQ -->
        <section id="faq">
            <div class="container">
                <h2 class="section-title">Perguntas Frequentes (FAQ)</h2>
                <div class="faq-item">
                    <h4>Você faz laudos psicológicos ou apenas pareceres?</h4>
                    <p>
                        Sim, produzo laudos psicológicos e pareceres técnicos, conforme a necessidade do processo judicial ou administrativo. Também realizo leitura crítica e revisão de documentos já existentes, sempre respeitando os limites éticos e legais da profissão.
                    </p>
                </div>
                <div class="faq-item">
                    <h4>Quem pode solicitar seus serviços?</h4>
                    <p>
                        Advogados(as), famílias, instituições públicas ou privadas, organizações do terceiro setor e qualquer parte interessada em obter um laudo, parecer ou análise qualificada de documentos psicológicos para processos judiciais ou administrativos.
                    </p>
                </div>
                <div class="faq-item">
                    <h4>Como funciona a produção de laudos e pareceres?</h4>
                    <p>
                        Após análise da demanda, realizo entrevistas, avaliações, análise documental e elaboro o laudo ou parecer solicitado, sempre com fundamentação científica, clareza e objetividade. O serviço pode incluir reuniões, orientações e acompanhamento técnico durante o processo.
                    </p>
                </div>
                <div class="faq-item">
                    <h4>Você também revisa e impugna laudos já existentes?</h4>
                    <p>
                        Sim. Realizo leitura crítica, revisão e impugnação de laudos psicológicos já produzidos, elaborando pareceres técnicos detalhados para subsidiar estratégias jurídicas, recursos ou manifestações das partes.
                    </p>
                </div>
                <div class="faq-item">
                    <h4>O atendimento é sigiloso?</h4>
                    <p>
                        Sim. Todo o trabalho segue o Código de Ética Profissional do Psicólogo e as normas do CFP, garantindo sigilo, respeito, proteção de dados e compromisso com a confidencialidade das informações.
                    </p>
                </div>
                <div class="faq-item">
                    <h4>Quais documentos são necessários para iniciar o serviço?</h4>
                    <p>
                        Para laudos inéditos, são necessárias informações detalhadas sobre a demanda, documentos do processo e, quando pertinente, autorização judicial. Para pareceres ou leitura crítica, é essencial o acesso ao documento a ser analisado e, se possível, aos autos do processo.
                    </p>
                </div>
            </div>
        </section>
        <!-- CONTATO -->
        <section class="contact-section" id="contato">
            <div class="container">
                <h2>Contato</h2>
                <p>
                    Entre em contato para agendar uma conversa, tirar dúvidas ou solicitar orçamento. Garanto resposta rápida, atendimento humanizado e total sigilo sobre sua demanda. Sua questão será acolhida com seriedade, ética e compromisso com a justiça.
                </p>
                <div class="contact-links">
                    <a href="mailto:thiagovieira.psi@gmail.com"><i class="fas fa-envelope"></i> thiagovieira.psi@gmail.com</a>
                    <a href="https://wa.me/5512999999999" target="_blank"><i class="fab fa-whatsapp"></i> WhatsApp (12) 99999-9999</a>
                    <a href="https://www.linkedin.com/in/thiago-vieira-ab2046167" target="_blank"><i class="fab fa-linkedin"></i> LinkedIn</a>
                    <a href="https://www.instagram.com/psi_thiagovieira/" target="_blank"><i class="fab fa-instagram"></i> Instagram</a>
                </div>
            </div>
        </section>
    </main>
    <footer>
        <div class="container">
            <div>&copy; 2025 Thiago Vieira | Psicólogo Perito Judicial</div>
            <div class="footer-crp">CRP 06/204224</div>
            <div class="footer-socials">
                <a href="https://www.linkedin.com/in/thiago-vieira-ab2046167" target="_blank" title="LinkedIn"><i class="fab fa-linkedin"></i></a>
                <a href="https://www.instagram.com/psi_thiagovieira/" target="_blank" title="Instagram"><i class="fab fa-instagram"></i></a>
            </div>
            <div style="font-size:0.98rem;">Site desenvolvido por Monica</div>
        </div>
    </footer>
    <script>
    // Script para abrir e fechar artigos SEM recarregar a página
    document.addEventListener('DOMContentLoaded', function() {
        // Ao clicar em "Ler artigo completo"
        document.querySelectorAll('.article-link').forEach(function(link) {
            link.addEventListener('click', function(e) {
                e.preventDefault();
                // Esconde todos os artigos
                document.querySelectorAll('.article-content').forEach(function(art) {
                    art.classList.remove('active');
                });
                // Mostra o artigo correspondente
                const artId = link.getAttribute('data-article');
                const article = document.getElementById(artId);
                if(article) {
                    article.classList.add('active');
                    article.scrollIntoView({behavior:'smooth', block:'center'});
                }
            });
        });
        // Ao clicar em "Voltar"
        document.query
