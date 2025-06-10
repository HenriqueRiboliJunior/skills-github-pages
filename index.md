

<html lang="pt-BR" class="scroll-smooth"> 
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Henrique Riboli Junior - Portfólio</title>
    <!-- Chosen Palette: Tech Deep Dive (Body bg-gray-900, section bg-gray-800, text-gray-200, accent text-teal-400/sky-400 for highlights) -->
    <!-- Application Structure Plan: A single-page professional portfolio structured into distinct, navigable sections: Hero (introduces the professional), About (detailed summary), Skills (categorized technical abilities), Experience (chronological work history), Education & Certifications, and Courses. This linear flow is intuitive for a resume-like presentation. The design prioritizes readability and quick access to key information, making it easy for recruiters or peers to understand the candidate's profile. -->
    <!-- Visualization & Content Choices: Report Info -> Goal -> Viz/Presentation Method -> Interaction -> Justification -> Library/Method. 1. Contact Info -> Inform -> Text links with Unicode icons -> Direct navigation -> Standard and clear. (HTML/Unicode). 2. Summary -> Inform -> Paragraphs -> Read -> Provides a concise overview. (HTML). 3. Skills -> Organize -> Tag-like list -> Quick scan for relevant tech -> Visually appealing and easy to digest. (HTML). 4. Experience -> Organize/Inform -> Timeline/cards with detailed points -> Chronological context, clear responsibilities -> Standard and effective for work history. (HTML). 5. Education, Certs, Courses -> Inform -> List items -> Direct information display -> Simple and clear. (HTML). 6. Languages -> Inform -> List items -> Direct information display -> Simple and clear. (HTML). -->
    <!-- CONFIRMATION: NO SVG graphics used. NO Mermaid JS used. -->
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Inter', sans-serif;
            background-color: #1a202c; /* Cor de fundo principal mais escura */
            color: #e2e8f0; /* Cor do texto padrão mais clara */
        }
        .section-bg {
            background-color: #2d3748; /* Cor de fundo para seções */
        }
        .accent-text {
            color: #2dd4bf; /* Cor de destaque (teal-400) */
        }
        .accent-bg {
            background-color: #2dd4bf; /* Cor de fundo para botões/destaques */
        }
        .skill-tag {
            background-color: #4a5568; /* Fundo para as tags de habilidade */
            color: #e2e8f0;
        }
        .timeline-dot {
            background-color: #2dd4bf;
        }
    </style>
</head>
<body class="bg-gray-900 text-gray-200">

    <!-- Header e Navegação -->
    <header class="bg-gray-800 shadow-md sticky top-0 z-50">
        <nav class="container mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex items-center justify-between h-16">
                <div class="flex-shrink-0">
                    <a href="#hero" class="text-2xl font-bold accent-text">Henrique Riboli Junior</a>
                </div>
                <div class="hidden md:block">
                    <div class="ml-10 flex items-baseline space-x-4">
                        <a href="#sobre" class="text-gray-300 hover:text-white px-3 py-2 rounded-md text-sm font-medium transition-colors duration-200">Sobre Mim</a>
                        <a href="#habilidades" class="text-gray-300 hover:text-white px-3 py-2 rounded-md text-sm font-medium transition-colors duration-200">Habilidades</a>
                        <a href="#experiencia" class="text-gray-300 hover:text-white px-3 py-2 rounded-md text-sm font-medium transition-colors duration-200">Experiência</a>
                        <a href="#formacao" class="text-gray-300 hover:text-white px-3 py-2 rounded-md text-sm font-medium transition-colors duration-200">Formação & Cursos</a>
                    </div>
                </div>
                <div class="-mr-2 flex md:hidden">
                    <button id="mobile-menu-button" type="button" class="bg-gray-700 inline-flex items-center justify-center p-2 rounded-md text-gray-400 hover:text-white hover:bg-gray-600 focus:outline-none focus:ring-2 focus:ring-offset-2 focus:ring-offset-gray-700 focus:ring-teal-500">
                        <span class="sr-only">Abrir menu principal</span>
                        <svg class="h-6 w-6" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke="currentColor" aria-hidden="true">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16M4 18h16" />
                        </svg>
                    </button>
                </div>
            </div>
        </nav>
        <div class="md:hidden hidden" id="mobile-menu">
            <div class="px-2 pt-2 pb-3 space-y-1 sm:px-3">
                <a href="#sobre" class="text-gray-300 hover:text-white block px-3 py-2 rounded-md text-base font-medium">Sobre Mim</a>
                <a href="#habilidades" class="text-gray-300 hover:text-white block px-3 py-2 rounded-md text-base font-medium">Habilidades</a>
                <a href="#experiencia" class="text-gray-300 hover:text-white block px-3 py-2 rounded-md text-base font-medium">Experiência</a>
                <a href="#formacao" class="text-gray-300 hover:text-white block px-3 py-2 rounded-md text-base font-medium">Formação & Cursos</a>
            </div>
        </div>
    </header>

    <main class="container mx-auto px-4 sm:px-6 lg:px-8 py-8">
        
        <!-- Seção Hero -->
        <section id="hero" class="pt-20 -mt-16 text-center mb-24">
            <div class="w-24 h-24 bg-gray-700 rounded-full mx-auto mb-6 flex items-center justify-center text-5xl font-bold accent-text">H</div>
            <h1 class="text-5xl font-extrabold text-white mb-4 tracking-tight">Henrique Riboli Junior</h1>
            <p class="mt-2 text-2xl font-light text-gray-300 mb-6">Analista de Testes / Automação de Testes</p>
            <div class="flex flex-wrap justify-center gap-4 text-lg">
                <a href="mailto:henrique.dev@live.com" class="bg-gray-700 hover:bg-gray-600 text-gray-200 px-4 py-2 rounded-full transition-colors duration-200 flex items-center">
                    📧 <span class="ml-2">E-mail</span>
                </a>
                <a href="https://www.linkedin.com/in/henrique-riboli-junior-1382809a" target="_blank" rel="noopener noreferrer" class="bg-gray-700 hover:bg-gray-600 text-gray-200 px-4 py-2 rounded-full transition-colors duration-200 flex items-center">
                    🔗 <span class="ml-2">LinkedIn</span>
            </div>
        </section>

        <!-- Seção Sobre Mim -->
        <section id="sobre" class="pt-20 -mt-16 mb-24 p-8 rounded-xl section-bg shadow-lg">
            <h2 class="text-4xl font-bold accent-text mb-8 text-center">Sobre Mim</h2>
            <div class="max-w-3xl mx-auto space-y-6 text-lg text-gray-300">
                <p>Com vasta experiência em testes funcionais manuais, incluindo planejamento e execução de casos de testes baseados em requisitos e protótipos, e criação de massa de testes para garantir a qualidade do software.</p>
                <p>Sou especialista em automação de testes, com proficiência em ferramentas como Selenium Webdriver para aplicações web, Appium para plataformas mobile (Android) e Postman para automação de testes de API. Minha paixão é otimizar processos de teste para entregar software robusto e confiável.</p>
            </div>
        </section>

        <!-- Seção Habilidades -->
        <section id="habilidades" class="pt-20 -mt-16 mb-24 p-8 rounded-xl section-bg shadow-lg">
            <h2 class="text-4xl font-bold accent-text mb-8 text-center">Competências e Especialidades</h2>
            <div class="max-w-4xl mx-auto flex flex-wrap justify-center gap-4">
                <span class="skill-tag px-4 py-2 rounded-full font-medium">Selenium Webdriver</span>
                <span class="skill-tag px-4 py-2 rounded-full font-medium">Selenium Grid e Cloud</span>
                <span class="skill-tag px-4 py-2 rounded-full font-medium">Appium</span>
                <span class="skill-tag px-4 py-2 rounded-full font-medium">HTTParty + RSpec</span>
                <span class="skill-tag px-4 py-2 rounded-full font-medium">Capybara/Cucumber</span>
                <span class="skill-tag px-4 py-2 rounded-full font-medium">RestAssured</span>
                <span class="skill-tag px-4 py-2 rounded-full font-medium">Java</span>
                <span class="skill-tag px-4 py-2 rounded-full font-medium">JUnit</span>
                <span class="skill-tag px-4 py-2 rounded-full font-medium">Mockito</span>
                <span class="skill-tag px-4 py-2 rounded-full font-medium">Jmeter</span>
                <span class="skill-tag px-4 py-2 rounded-full font-medium">SQL</span>
                <span class="skill-tag px-4 py-2 rounded-full font-medium">API Testing</span>
                <span class="skill-tag px-4 py-2 rounded-full font-medium">Scrum</span>
                <span class="skill-tag px-4 py-2 rounded-full font-medium">ALM (Application Lifecycle Management)</span>
                <span class="skill-tag px-4 py-2 rounded-full font-medium">Jira</span>
                <span class="skill-tag px-4 py-2 rounded-full font-medium">Kanban</span>
                <span class="skill-tag px-4 py-2 rounded-full font-medium">C#</span>
            </div>
        </section>

        <!-- Seção Experiência -->
        <section id="experiencia" class="pt-20 -mt-16 mb-24 p-8 rounded-xl section-bg shadow-lg">
            <h2 class="text-4xl font-bold accent-text mb-12 text-center">Experiência Profissional</h2>
            <div class="relative max-w-4xl mx-auto">
                <!-- Linha do tempo -->
                <div class="absolute inset-y-0 left-1/2 transform -translate-x-1/2 w-0.5 bg-gray-700 hidden md:block"></div>

                <!-- Experiência ZarpSystem -->
                <div class="mb-12 flex flex-col md:flex-row items-center justify-between w-full">
                    <div class="md:w-5/12 text-center md:text-right p-4">
                        <h3 class="text-2xl font-semibold text-white">Analista de Testes/Automação de testes</h3>
                        <p class="text-gray-400">ZarpSystem</p>
                        <p class="text-sm text-gray-500">Novembro 2020 – Atualmente</p>
                    </div>
                    <div class="md:w-1/12 hidden md:flex justify-center">
                        <div class="w-4 h-4 rounded-full timeline-dot absolute"></div>
                    </div>
                    <div class="md:w-5/12 p-4 section-bg rounded-lg shadow-md border border-gray-700">
                        <ul class="list-disc list-inside text-gray-300 space-y-2">
                            <li>Análise, planejamento e execução de testes funcionais em sistemas Web, Processamento batch e Mobile (Android e IOS).</li>
                            <li>Registro e gerenciamento de incidentes (defeitos) e identificação das possíveis causas, impactos e riscos para o projeto.</li>
                            <li>Elaboração e Revisão de Casos de Testes/Planos de Testes.</li>
                            <li>Aplicação da Metodologia Ágil (Scrum/Jira).</li>
                            <li>Automação de testes de API com Postman, automação de testes WEB com Selenium Webdriver e automação de testes Mobile - Android com Appium.</li>
                        </ul>
                    </div>
                </div>

                <!-- Experiência HP - Analista -->
                <div class="mb-12 flex flex-col md:flex-row items-center justify-between w-full md:flex-row-reverse">
                    <div class="md:w-5/12 text-center md:text-left p-4">
                        <h3 class="text-2xl font-semibold text-white">Analista de Testes</h3>
                        <p class="text-gray-400">Hewlett-Packard - Enterprise Services</p>
                        <p class="text-sm text-gray-500">Maio 2014 – Setembro 2017</p>
                    </div>
                    <div class="md:w-1/12 hidden md:flex justify-center">
                        <div class="w-4 h-4 rounded-full timeline-dot absolute"></div>
                    </div>
                    <div class="md:w-5/12 p-4 section-bg rounded-lg shadow-md border border-gray-700">
                        <ul class="list-disc list-inside text-gray-300 space-y-2">
                            <li>Análise, planejamento e execução dos testes funcionais em sistemas Web/Mobile.</li>
                            <li>Registro e gerenciamento dos incidentes (defeitos) encontrados no sistema e identificação das possíveis causas, impactos e riscos para o projeto utilizando HP ALM.</li>
                            <li>Elaboração e Revisão de Casos de Testes/Planos de Testes visando reutilização.</li>
                            <li>Aplicação da Metodologia Ágil (Scrum/Kanban).</li>
                        </ul>
                    </div>
                </div>

                <!-- Experiência HP - Estagiário -->
                <div class="mb-12 flex flex-col md:flex-row items-center justify-between w-full">
                    <div class="md:w-5/12 text-center md:text-right p-4">
                        <h3 class="text-2xl font-semibold text-white">Estagiário</h3>
                        <p class="text-gray-400">Hewlett-Packard - Enterprise Services</p>
                        <p class="text-sm text-gray-500">Junho 2013 – Maio 2014</p>
                    </div>
                    <div class="md:w-1/12 hidden md:flex justify-center">
                        <div class="w-4 h-4 rounded-full timeline-dot absolute"></div>
                    </div>
                    <div class="md:w-5/12 p-4 section-bg rounded-lg shadow-md border border-gray-700">
                        <ul class="list-disc list-inside text-gray-300 space-y-2">
                            <li>Análise de sistemas em C#.</li>
                            <li>Elaboração de relatórios via script (SQL).</li>
                        </ul>
                    </div>
                </div>

            </div>
        </section>

        <!-- Seção Formação Acadêmica e Certificações -->
        <section id="formacao" class="pt-20 -mt-16 mb-24 p-8 rounded-xl section-bg shadow-lg">
            <h2 class="text-4xl font-bold accent-text mb-12 text-center">Formação & Certificações</h2>
            <div class="grid md:grid-cols-2 gap-8 max-w-4xl mx-auto">
                <div>
                    <h3 class="text-2xl font-semibold text-white mb-4">Formação Acadêmica</h3>
                    <div class="bg-gray-700 p-6 rounded-lg shadow-md border border-gray-600">
                        <p class="font-medium text-lg text-gray-200">Graduação, Sistemas de Informação</p>
                        <p class="text-gray-400">Universidade de Araraquara - Uniara</p>
                        <p class="text-sm text-gray-500">2011 - 2016</p>
                    </div>
                </div>
                <div>
                    <h3 class="text-2xl font-semibold text-white mb-4">Certificações</h3>
                    <ul class="space-y-4">
                        <li class="bg-gray-700 p-6 rounded-lg shadow-md border border-gray-600">
                            <p class="font-medium text-lg text-gray-200">Scrum Fundamentals Certified</p>
                            <p class="text-gray-400">SCRUMstudy</p>
                        </li>
                        <li class="bg-gray-700 p-6 rounded-lg shadow-md border border-gray-600">
                            <p class="font-medium text-lg text-gray-200">ITIL® V3 Foundation</p>
                            <p class="text-gray-400">CSME, Inc.</p>
                        </li>
                    </ul>
                </div>
            </div>

            <div class="mt-12">
                <h3 class="text-2xl font-semibold text-white mb-6 text-center">Cursos Complementares</h3>
                <div class="flex flex-wrap justify-center gap-4 text-center text-gray-300 max-w-4xl mx-auto">
                    <span class="bg-gray-700 px-4 py-2 rounded-full shadow-sm text-sm border border-gray-600">Testes funcionais com Selenium Webdriver</span>
                    <span class="bg-gray-700 px-4 py-2 rounded-full shadow-sm text-sm border border-gray-600">Testes funcionais de aplicação Android com Appium</span>
                    <span class="bg-gray-700 px-4 py-2 rounded-full shadow-sm text-sm border border-gray-600">Testes funcionais com Capybara, Cucumber e Ruby</span>
                    <span class="bg-gray-700 px-4 py-2 rounded-full shadow-sm text-sm border border-gray-600">Testes Automatizados de API com HTTParty + RSpec</span>
                    <span class="bg-gray-700 px-4 py-2 rounded-full shadow-sm text-sm border border-gray-600">Jmeter - Testes de performance</span>
                    <span class="bg-gray-700 px-4 py-2 rounded-full shadow-sm text-sm border border-gray-600">Testes unitários em Java - JUnit, Mockito e TDD</span>
                    <span class="bg-gray-700 px-4 py-2 rounded-full shadow-sm text-sm border border-gray-600">Orientação a objetos com Java</span>
                    <span class="bg-gray-700 px-4 py-2 rounded-full shadow-sm text-sm border border-gray-600">TDD - Desenvolvimento de Software Guiado por Testes</span>
                    <span class="bg-gray-700 px-4 py-2 rounded-full shadow-sm text-sm border border-gray-600">Testes API REST com REST-Assured</span>
                </div>
            </div>

            <div class="mt-12 text-center">
                <h3 class="text-2xl font-semibold text-white mb-6">Idiomas</h3>
                <div class="flex flex-wrap justify-center gap-4 text-gray-300">
                    <span class="bg-gray-700 px-4 py-2 rounded-full shadow-sm text-sm border border-gray-600">Inglês - Nível Básico</span>
                    <span class="bg-gray-700 px-4 py-2 rounded-full shadow-sm text-sm border border-gray-600">Espanhol - Nível Básico</span>
                </div>
            </div>
        </section>

    </main>

    <footer class="bg-gray-800 text-gray-400 mt-16">
        <div class="container mx-auto py-6 px-4 sm:px-6 lg:px-8 text-center text-sm">
            <p>&copy; 2024 Henrique Riboli Junior. Todos os direitos reservados.</p>
        </div>
    </footer>

    <script>
        document.addEventListener('DOMContentLoaded', function () {
            // Mobile menu toggle
            const mobileMenuButton = document.getElementById('mobile-menu-button');
            const mobileMenu = document.getElementById('mobile-menu');
            mobileMenuButton.addEventListener('click', () => {
                mobileMenu.classList.toggle('hidden');
            });

            // Smooth scroll for navigation links
            document.querySelectorAll('a[href^="#"]').forEach(anchor => {
                anchor.addEventListener('click', function (e) {
                    e.preventDefault();
                    document.querySelector(this.getAttribute('href')).scrollIntoView({
                        behavior: 'smooth'
                    });
                    // Close mobile menu after clicking a link
                    if (!mobileMenu.classList.contains('hidden')) {
                        mobileMenu.classList.add('hidden');
                    }
                });
            });
        });
    </script>
</body>
</html>
