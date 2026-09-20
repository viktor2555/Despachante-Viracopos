<!DOCTYPE html>
<html lang="pt-BR" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Victor Luis Sanches | Despachante Aduaneiro em Viracopos</title>
    <!-- Tailwind CSS CDN -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- FontAwesome for Icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <!-- Google Fonts Inter -->
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700;800&display=swap" rel="stylesheet">
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        navy: {
                            900: '#0A192F',
                            800: '#112240',
                            700: '#1D3557',
                        },
                        accent: {
                            green: '#10B981',
                            greenHover: '#059669',
                            blue: '#3B82F6'
                        }
                    },
                    fontFamily: {
                        sans: ['Inter', 'sans-serif'],
                    }
                }
            }
        }
    </script>
    <style>
        @keyframes fadeIn {
            from { opacity: 0; transform: translateY(20px); }
            to { opacity: 1; transform: translateY(0); }
        }
        .animate-fade-in {
            animation: fadeIn 1s ease-out forwards;
        }
        .glass-panel {
            background: rgba(17, 34, 64, 0.75);
            backdrop-filter: blur(12px);
            -webkit-backdrop-filter: blur(12px);
            border: 1px solid rgba(255, 255, 255, 0.1);
        }
    </style>
</head>
<body class="bg-slate-900 text-slate-100 font-sans antialiased selection:bg-accent-green selection:text-white">

    <!-- Navbar -->
    <header class="fixed top-0 left-0 right-0 z-50 bg-navy-900/90 backdrop-blur-md border-b border-slate-800 transition-all duration-300">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 h-20 flex items-center justify-between">
            <a href="#" class="flex items-center space-x-3 group">
                <div class="w-10 h-10 rounded-lg bg-accent-green flex items-center justify-center text-navy-900 font-black text-xl shadow-lg shadow-accent-green/20 group-hover:scale-105 transition-transform">
                    VS
                </div>
                <div>
                    <span class="block font-bold text-lg tracking-tight text-white leading-tight">Victor Luis Sanches</span>
                    <span class="block text-xs text-slate-400 font-medium">Despachante Aduaneiro • Viracopos</span>
                </div>
            </a>

            <nav class="hidden md:flex items-center space-x-8 text-sm font-medium">
                <a href="#inicio" class="text-slate-300 hover:text-accent-green transition-colors">Início</a>
                <a href="#servicos" class="text-slate-300 hover:text-accent-green transition-colors">Serviços</a>
                <a href="#viracopos" class="text-slate-300 hover:text-accent-green transition-colors">Viracopos</a>
                <a href="#sobre" class="text-slate-300 hover:text-accent-green transition-colors">Sobre Mim</a>
                <a href="#contato" class="text-slate-300 hover:text-accent-green transition-colors">Contato</a>
            </nav>

            <div class="hidden md:flex items-center space-x-4">
                <a href="https://wa.me/5519974090051?text=Olá%20Victor,%20gostaria%20de%20uma%20cotação%20para%20desembaraço%20aduaneiro%20em%20Viracopos." target="_blank" rel="noopener noreferrer" class="bg-accent-green hover:bg-accent-greenHover text-navy-900 font-bold px-5 py-2.5 rounded-xl shadow-lg shadow-accent-green/20 transition-all transform hover:-translate-y-0.5 flex items-center space-x-2">
                    <i class="fa-brands fa-whatsapp text-lg"></i>
                    <span>(19) 97409-0051</span>
                </a>
            </div>

            <!-- Mobile menu button -->
            <button id="menu-btn" class="md:hidden text-slate-300 hover:text-white focus:outline-none p-2">
                <i class="fa-solid fa-bars text-2xl"></i>
            </button>
        </div>

        <!-- Mobile menu dropdown -->
        <div id="mobile-menu" class="hidden md:hidden bg-navy-900 border-b border-slate-800 px-4 pt-2 pb-6 space-y-3">
            <a href="#inicio" class="block py-2 text-slate-300 hover:text-accent-green font-medium">Início</a>
            <a href="#servicos" class="block py-2 text-slate-300 hover:text-accent-green font-medium">Serviços</a>
            <a href="#viracopos" class="block py-2 text-slate-300 hover:text-accent-green font-medium">Viracopos</a>
            <a href="#sobre" class="block py-2 text-slate-300 hover:text-accent-green font-medium">Sobre Mim</a>
            <a href="#contato" class="block py-2 text-slate-300 hover:text-accent-green font-medium">Contato</a>
            <a href="https://wa.me/5519974090051?text=Olá%20Victor,%20gostaria%20de%20uma%20cotação%20para%20desembaraço%20aduaneiro%20em%20Viracopos." target="_blank" rel="noopener noreferrer" class="w-full mt-2 bg-accent-green text-navy-900 font-bold px-4 py-3 rounded-xl flex items-center justify-center space-x-2">
                <i class="fa-brands fa-whatsapp text-lg"></i>
                <span>Falar no WhatsApp</span>
            </a>
        </div>
    </header>

    <!-- Hero Section -->
    <section id="inicio" class="relative min-h-screen flex items-center justify-center pt-20 overflow-hidden">
        <!-- Video Background with Fallback Image -->
        <div class="absolute inset-0 z-0 overflow-hidden">
            <video autoplay muted loop playsinline class="absolute w-full h-full object-cover filter brightness-50">
                <source src="https://assets.mixkit.co/videos/preview/mixkit-aerial-view-of-cargo-port-at-sunset-41656-large.mp4" type="video/mp4">
            </video>
            <!-- Fallback background image if video fails or on mobile data savers -->
            <div class="absolute inset-0 bg-cover bg-center" style="background-image: url('https://images.unsplash.com/photo-1586528116311-ad8dd3c8310d?q=80&w=1920&auto=format&fit=crop'); z-index: -1;"></div>
            <!-- Dark Gradient Overlay -->
            <div class="absolute inset-0 bg-gradient-to-r from-navy-950/95 via-navy-900/80 to-navy-950/90"></div>
        </div>

        <div class="relative z-10 max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 py-24 md:py-32 text-center md:text-left w-full">
            <div class="grid grid-cols-1 md:grid-cols-12 gap-12 items-center">
                <div class="md:col-span-8 space-y-6 animate-fade-in">
                    <div class="inline-flex items-center space-x-2 bg-accent-green/10 border border-accent-green/30 px-3.5 py-1.5 rounded-full text-accent-green text-sm font-semibold tracking-wide">
                        <i class="fa-solid fa-plane-arrival"></i>
                        <span>Aeroporto Internacional de Viracopos • Campinas/SP</span>
                    </div>
                    <h1 class="text-4xl sm:text-5xl lg:text-6xl font-extrabold text-white tracking-tight leading-none">
                        Agilidade e Segurança no <span class="text-transparent bg-clip-text bg-gradient-to-r from-accent-green to-blue-400">Desembaraço Aduaneiro</span>
                    </h1>
                    <p class="text-lg sm:text-xl text-slate-300 font-normal max-w-2xl leading-relaxed">
                        Experiência sólida em comércio exterior para desburocratizar, acelerar liberações e otimizar custos logísticos da sua carga com atendimento consultivo e personalizado.
                    </p>
                    <div class="flex flex-col sm:flex-row items-center justify-center md:justify-start gap-4 pt-4">
                        <a href="https://wa.me/5519974090051?text=Olá%20Victor,%20preciso%20de%20suporte%20aduaneiro%20em%20Viracopos." target="_blank" rel="noopener noreferrer" class="w-full sm:w-auto bg-accent-green hover:bg-accent-greenHover text-navy-900 font-bold px-8 py-4 rounded-xl shadow-xl shadow-accent-green/20 transition-all transform hover:-translate-y-1 flex items-center justify-center space-x-3 text-base">
                            <i class="fa-brands fa-whatsapp text-2xl"></i>
                            <span>Falar Direto no WhatsApp</span>
                        </a>
                        <a href="#servicos" class="w-full sm:w-auto bg-slate-800/80 hover:bg-slate-800 text-white font-semibold px-8 py-4 rounded-xl border border-slate-700 backdrop-blur transition-all flex items-center justify-center space-x-2 text-base">
                            <span>Conhecer Serviços</span>
                            <i class="fa-solid fa-arrow-down text-sm"></i>
                        </a>
                    </div>
                    
                    <div class="grid grid-cols-3 gap-6 pt-8 border-t border-slate-800/80 max-w-lg">
                        <div>
                            <span class="block text-2xl font-bold text-white">+10 Anos</span>
                            <span class="block text-xs text-slate-400">Comércio Exterior</span>
                        </div>
                        <div>
                            <span class="block text-2xl font-bold text-accent-green">Viracopos</span>
                            <span class="block text-xs text-slate-400">Atuação Exclusiva</span>
                        </div>
                        <div>
                            <span class="block text-2xl font-bold text-white">Ágil</span>
                            <span class="block text-xs text-slate-400">Liberação sem Atrasos</span>
                        </div>
                    </div>
                </div>

                <div class="md:col-span-4 hidden md:block">
                    <div class="glass-panel p-6 rounded-2xl shadow-2xl space-y-6 border border-slate-700/50">
                        <div class="flex items-center space-x-4">
                            <div class="w-14 h-14 rounded-full bg-accent-green/20 flex items-center justify-center text-accent-green font-bold text-2xl">
                                <i class="fa-solid fa-user-tie"></i>
                            </div>
                            <div>
                                <h3 class="font-bold text-lg text-white">Victor Luis Sanches</h3>
                                <p class="text-xs text-accent-green font-medium">Despachante Aduaneiro</p>
                            </div>
                        </div>
                        <div class="space-y-3 text-sm text-slate-300">
                            <div class="flex items-start space-x-3">
                                <i class="fa-solid fa-check text-accent-green mt-1"></i>
                                <span>Atendimento personalizado para PMEs e Grandes Empresas.</span>
                            </div>
                            <div class="flex items-start space-x-3">
                                <i class="fa-solid fa-check text-accent-green mt-1"></i>
                                <span>Redução de custos com armazenagem alfandegária.</span>
                            </div>
                            <div class="flex items-start space-x-3">
                                <i class="fa-solid fa-check text-accent-green mt-1"></i>
                                <span>Presença física ativa no complexo aeroportuário.</span>
                            </div>
                        </div>
                        <a href="https://www.linkedin.com/in/victor-luis-sanches" target="_blank" rel="noopener noreferrer" class="block w-full text-center bg-blue-600 hover:bg-blue-700 text-white font-semibold py-3 rounded-xl transition-all shadow-md">
                            <i class="fa-brands fa-linkedin mr-2"></i> Ver Perfil no LinkedIn
                        </a>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Services Section -->
    <section id="servicos" class="py-24 bg-slate-950 relative">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center max-w-3xl mx-auto mb-16 space-y-4">
                <span class="text-accent-green font-semibold text-sm tracking-widest uppercase bg-accent-green/10 px-3 py-1 rounded-full">Soluções Especializadas</span>
                <h2 class="text-3xl sm:text-4xl font-extrabold text-white tracking-tight">Serviços em Assessoria e Desembaraço Aduaneiro</h2>
                <p class="text-slate-400 text-base sm:text-lg">Eficiência operacional e conformidade legal em cada etapa do seu processo de importação e exportação em Viracopos.</p>
            </div>

            <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
                <!-- Card 1 -->
                <div class="bg-navy-900/80 rounded-2xl overflow-hidden border border-slate-800 hover:border-accent-green/50 transition-all duration-300 group shadow-xl flex flex-col">
                    <div class="h-48 overflow-hidden relative">
                        <img src="https://images.unsplash.com/photo-1578575437130-527eed3abbec?q=80&w=800&auto=format&fit=crop" alt="Desembaraço Aduaneiro" class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-500">
                        <div class="absolute inset-0 bg-gradient-to-t from-navy-900 via-transparent to-transparent"></div>
                        <div class="absolute bottom-3 left-4 bg-accent-green text-navy-900 font-bold px-3 py-1 rounded-lg text-xs">
                            Principal Serviço
                        </div>
                    </div>
                    <div class="p-6 sm:p-8 flex-1 flex flex-col justify-between space-y-6">
                        <div class="space-y-3">
                            <h3 class="text-xl font-bold text-white group-hover:text-accent-green transition-colors">Desembaraço de Importação e Exportação</h3>
                            <p class="text-slate-400 text-sm leading-relaxed">
                                Liberação aduaneira ágil e sem complicações para cargas aéreas no aeroporto de Viracopos, garantindo conformidade com a Receita Federal e órgãos intervenientes.
                            </p>
                        </div>
                        <a href="https://wa.me/5519974090051?text=Olá%20Victor,%20gostaria%20de%20saber%20mais%20sobre%20Desembaraço%20de%20Importação%20e%20Exportação." target="_blank" rel="noopener noreferrer" class="inline-flex items-center space-x-2 text-accent-green hover:text-accent-greenHover font-semibold text-sm">
                            <span>Solicitar Cotação</span>
                            <i class="fa-solid fa-arrow-right text-xs"></i>
                        </a>
                    </div>
                </div>

                <!-- Card 2 -->
                <div class="bg-navy-900/80 rounded-2xl overflow-hidden border border-slate-800 hover:border-accent-green/50 transition-all duration-300 group shadow-xl flex flex-col">
                    <div class="h-48 overflow-hidden relative">
                        <img src="https://images.unsplash.com/photo-1454165804606-c3d57bc86b40?q=80&w=800&auto=format&fit=crop" alt="Consultoria Comércio Exterior" class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-500">
                        <div class="absolute inset-0 bg-gradient-to-t from-navy-900 via-transparent to-transparent"></div>
                        <div class="absolute bottom-3 left-4 bg-blue-600 text-white font-bold px-3 py-1 rounded-lg text-xs">
                            Estratégico
                        </div>
                    </div>
                    <div class="p-6 sm:p-8 flex-1 flex flex-col justify-between space-y-6">
                        <div class="space-y-3">
                            <h3 class="text-xl font-bold text-white group-hover:text-accent-green transition-colors">Assessoria e Consultoria Aduaneira</h3>
                            <p class="text-slate-400 text-sm leading-relaxed">
                                Análise prévia de documentos, classificação fiscal (NCM), verificação de licenças de importação (LI) e planejamento tributário para redução de custos.
                            </p>
                        </div>
                        <a href="https://wa.me/5519974090051?text=Olá%20Victor,%20gostaria%20de%20consultoria%20em%20comércio%20exterior." target="_blank" rel="noopener noreferrer" class="inline-flex items-center space-x-2 text-accent-green hover:text-accent-greenHover font-semibold text-sm">
                            <span>Falar com Consultor</span>
                            <i class="fa-solid fa-arrow-right text-xs"></i>
                        </a>
                    </div>
                </div>

                <!-- Card 3 -->
                <div class="bg-navy-900/80 rounded-2xl overflow-hidden border border-slate-800 hover:border-accent-green/50 transition-all duration-300 group shadow-xl flex flex-col">
                    <div class="h-48 overflow-hidden relative">
                        <img src="https://images.unsplash.com/photo-1586528116493-a02532555cae?q=80&w=800&auto=format&fit=crop" alt="Vistoria e Conferência Física" class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-500">
                        <div class="absolute inset-0 bg-gradient-to-t from-navy-900 via-transparent to-transparent"></div>
                        <div class="absolute bottom-3 left-4 bg-purple-600 text-white font-bold px-3 py-1 rounded-lg text-xs">
                            Presencial
                        </div>
                    </div>
                    <div class="p-6 sm:p-8 flex-1 flex flex-col justify-between space-y-6">
                        <div class="space-y-3">
                            <h3 class="text-xl font-bold text-white group-hover:text-accent-green transition-colors">Acompanhamento de Vistoria e Conferência</h3>
                            <p class="text-slate-400 text-sm leading-relaxed">
                                Presença ativa e dedicada no terminal alfandegário de Viracopos durante vistorias físicas da Receita Federal e ANVISA, garantindo integridade e rapidez.
                            </p>
                        </div>
                        <a href="https://wa.me/5519974090051?text=Olá%20Victor,%20preciso%20de%20acompanhamento%20de%20vistoria%20em%20Viracopos." target="_blank" rel="noopener noreferrer" class="inline-flex items-center space-x-2 text-accent-green hover:text-accent-greenHover font-semibold text-sm">
                            <span>Agendar Acompanhamento</span>
                            <i class="fa-solid fa-arrow-right text-xs"></i>
                        </a>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Viracopos Operations Spotlight Section -->
    <section id="viracopos" class="py-24 bg-navy-900 relative overflow-hidden">
        <div class="absolute inset-0 opacity-10 bg-[radial-gradient(#3B82F6_1px,transparent_1px)] [background-size:16px_16px]"></div>
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 relative z-10">
            <div class="grid grid-cols-1 lg:grid-cols-2 gap-12 items-center">
                <div class="space-y-6">
                    <span class="text-accent-green font-semibold text-sm tracking-widest uppercase bg-accent-green/10 px-3 py-1 rounded-full">Foco Geográfico Estratégico</span>
                    <h2 class="text-3xl sm:text-4xl font-extrabold text-white tracking-tight">Atuação Direta no Terminal Alfandegário de Viracopos</h2>
                    <p class="text-slate-300 leading-relaxed text-base sm:text-lg">
                        O Aeroporto Internacional de Viracopos (Campinas) é um dos principais hubs logísticos e de cargas do Brasil. Contar com um despachante autônomo especialista no local garante decisões rápidas e desburocratização.
                    </p>
                    <div class="space-y-4 pt-2">
                        <div class="flex items-start space-x-4">
                            <div class="w-10 h-10 rounded-xl bg-accent-green/20 text-accent-green flex items-center justify-center font-bold flex-shrink-0 mt-1">
                                <i class="fa-solid fa-clock"></i>
                            </div>
                            <div>
                                <h4 class="font-bold text-white text-lg">Redução de Custos de Armazenagem</h4>
                                <p class="text-slate-400 text-sm">Liberação ágil evita taxas elevadas de permanência de carga nos terminais do aeroporto.</p>
                            </div>
                        </div>
                        <div class="flex items-start space-x-4">
                            <div class="w-10 h-10 rounded-xl bg-accent-green/20 text-accent-green flex items-center justify-center font-bold flex-shrink-0 mt-1">
                                <i class="fa-solid fa-shield-halved"></i>
                            </div>
                            <div>
                                <h4 class="font-bold text-white text-lg">Segurança Regulatória</h4>
                                <p class="text-slate-400 text-sm">Conformidade total com exigências aduaneiras e órgãos anuentes (ANVISA, Vigiagro, Receita Federal).</p>
                            </div>
                        </div>
                    </div>
                </div>

                <div class="relative">
                    <div class="absolute -inset-2 bg-gradient-to-r from-accent-green to-blue-600 rounded-3xl blur-lg opacity-30"></div>
                    <div class="relative rounded-2xl overflow-hidden border border-slate-700 shadow-2xl">
                        <img src="https://images.unsplash.com/photo-1542296332-2e4473faf563?q=80&w=1000&auto=format&fit=crop" alt="Aeroporto de Viracopos Cargas" class="w-full h-[400px] object-cover">
                        <div class="absolute inset-0 bg-gradient-to-t from-navy-950 via-transparent to-transparent opacity-80"></div>
                        <div class="absolute bottom-6 left-6 right-6 p-4 glass-panel rounded-xl">
                            <p class="text-sm font-semibold text-white flex items-center">
                                <i class="fa-solid fa-location-dot text-accent-green mr-2"></i>
                                Aeroporto Internacional de Viracopos - Campinas/SP
                            </p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- About Me Section -->
    <section id="sobre" class="py-24 bg-slate-950 relative">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="bg-navy-900 border border-slate-800 rounded-3xl p-8 sm:p-12 lg:p-16 shadow-2xl">
                <div class="grid grid-cols-1 lg:grid-cols-12 gap-12 items-center">
                    <div class="lg:col-span-5 flex justify-center">
                        <div class="relative">
                            <div class="w-64 h-64 sm:w-80 sm:h-80 rounded-2xl overflow-hidden border-2 border-accent-green/50 shadow-2xl relative">
                                <img src="https://images.unsplash.com/photo-1507003211169-0a1dd7228f2d?q=80&w=600&auto=format&fit=crop" alt="Victor Luis Sanches" class="w-full h-full object-cover">
                            </div>
                            <div class="absolute -bottom-6 -right-6 bg-accent-green text-navy-900 p-4 rounded-2xl shadow-xl font-bold flex items-center space-x-2">
                                <i class="fa-solid fa-award text-2xl"></i>
                                <div>
                                    <span class="block text-xs uppercase tracking-wider">Especialista</span>
                                    <span class="block text-sm">Comércio Exterior</span>
                                </div>
                            </div>
                        </div>
                    </div>

                    <div class="lg:col-span-7 space-y-6">
                        <span class="text-accent-green font-semibold text-sm tracking-widest uppercase bg-accent-green/10 px-3 py-1 rounded-full">Profissional Autônomo</span>
                        <h2 class="text-3xl sm:text-4xl font-extrabold text-white tracking-tight">Victor Luis Sanches</h2>
                        <p class="text-slate-300 leading-relaxed text-base">
                            Com sólida experiência e atuação direta no comércio exterior, atuo como despachante aduaneiro autônomo com foco total em excelência, agilidade e transparência nas operações em Viracopos.
                        </p>
                        <p class="text-slate-400 text-sm leading-relaxed">
                            Meu compromisso é descomplicar a burocracia alfandegária para empresas que importam e exportam, oferecendo suporte técnico especializado desde a preparação documental até a liberação final da mercadoria.
                        </p>
                        <div class="pt-4 flex flex-wrap gap-4">
                            <a href="https://www.linkedin.com/in/victor-luis-sanches" target="_blank" rel="noopener noreferrer" class="bg-blue-600 hover:bg-blue-700 text-white font-semibold px-6 py-3 rounded-xl transition-all shadow-lg flex items-center space-x-2">
                                <i class="fa-brands fa-linkedin text-lg"></i>
                                <span>Conectar no LinkedIn</span>
                            </a>
                            <a href="https://wa.me/5519974090051?text=Olá%20Victor,%20gostaria%20de%20agendar%20uma%20conversa%20sobre%20sua%20assessoria%20aduaneira." target="_blank" rel="noopener noreferrer" class="bg-accent-green hover:bg-accent-greenHover text-navy-900 font-bold px-6 py-3 rounded-xl shadow-lg transition-all flex items-center space-x-2">
                                <i class="fa-brands fa-whatsapp text-lg"></i>
                                <span>Conversar pelo WhatsApp</span>
                            </a>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Contact & Footer Section -->
    <section id="contato" class="py-24 bg-navy-900 relative">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center max-w-3xl mx-auto mb-16 space-y-4">
                <span class="text-accent-green font-semibold text-sm tracking-widest uppercase bg-accent-green/10 px-3 py-1 rounded-full">Atendimento Imediato</span>
                <h2 class="text-3xl sm:text-4xl font-extrabold text-white tracking-tight">Entre em Contato com Victor Luis Sanches</h2>
                <p class="text-slate-400 text-base sm:text-lg">Precisa de liberação urgente ou consultoria aduaneira em Viracopos? Fale diretamente agora mesmo.</p>
            </div>

            <div class="grid grid-cols-1 lg:grid-cols-2 gap-12 items-start">
                <!-- Info Column -->
                <div class="space-y-8 bg-navy-800 p-8 sm:p-10 rounded-3xl border border-slate-700 shadow-2xl">
                    <h3 class="text-2xl font-bold text-white">Canais Oficiais</h3>
                    
                    <div class="space-y-6">
                        <a href="https://wa.me/5519974090051?text=Olá%20Victor,%20vim%20pelo%20site%20e%20gostaria%20de%20falar%20sobre%20desembaraço%20aduaneiro." target="_blank" rel="noopener noreferrer" class="flex items-center space-x-4 p-4 rounded-2xl bg-slate-900/60 hover:bg-slate-900 border border-slate-700/60 transition-all group">
                            <div class="w-12 h-12 rounded-xl bg-accent-green/20 text-accent-green flex items-center justify-center text-xl font-bold group-hover:scale-110 transition-transform">
                                <i class="fa-brands fa-whatsapp"></i>
                            </div>
                            <div>
                                <span class="block text-xs text-slate-400 font-medium uppercase tracking-wider">Telefone / WhatsApp</span>
                                <span class="block text-lg font-bold text-white group-hover:text-accent-green transition-colors">(19) 97409-0051</span>
                            </div>
                        </a>

                        <div class="flex items-center space-x-4 p-4 rounded-2xl bg-slate-900/60 border border-slate-700/60">
                            <div class="w-12 h-12 rounded-xl bg-blue-500/20 text-blue-400 flex items-center justify-center text-xl font-bold">
                                <i class="fa-solid fa-location-dot"></i>
                            </div>
                            <div>
                                <span class="block text-xs text-slate-400 font-medium uppercase tracking-wider">Local de Atuação</span>
                                <span class="block text-base font-bold text-white">Aeroporto Internacional de Viracopos - Campinas/SP</span>
                            </div>
                        </div>

                        <a href="https://www.linkedin.com/in/victor-luis-sanches" target="_blank" rel="noopener noreferrer" class="flex items-center space-x-4 p-4 rounded-2xl bg-slate-900/60 hover:bg-slate-900 border border-slate-700/60 transition-all group">
                            <div class="w-12 h-12 rounded-xl bg-blue-600/20 text-blue-400 flex items-center justify-center text-xl font-bold group-hover:scale-110 transition-transform">
                                <i class="fa-brands fa-linkedin"></i>
                            </div>
                            <div>
                                <span class="block text-xs text-slate-400 font-medium uppercase tracking-wider">Rede Social Profissional</span>
                                <span class="block text-base font-bold text-white group-hover:text-blue-400 transition-colors">victor-luis-sanches | LinkedIn</span>
                            </div>
                        </a>
                    </div>
                </div>

                <!-- Fast WhatsApp Trigger Card -->
                <div class="bg-gradient-to-br from-navy-800 to-navy-950 p-8 sm:p-10 rounded-3xl border border-accent-green/30 shadow-2xl flex flex-col justify-between space-y-6">
                    <div class="space-y-4">
                        <span class="inline-block bg-accent-green/10 text-accent-green text-xs font-semibold px-3 py-1 rounded-full uppercase tracking-wider">Atendimento Rápido</span>
                        <h3 class="text-2xl font-bold text-white">Envie uma Mensagem Instantânea</h3>
                        <p class="text-slate-300 text-sm">
                            Clique no botão abaixo para abrir diretamente uma conversa com o Victor no WhatsApp com mensagem pré-formatada.
                        </p>
                    </div>

                    <div class="space-y-4 pt-4">
                        <div class="bg-slate-900/80 p-4 rounded-xl border border-slate-800 text-sm text-slate-300">
                            <p class="font-medium text-white mb-1"><i class="fa-solid fa-circle-info text-accent-green mr-2"></i>Dica para importadores:</p>
                            Tenha em mãos o Conhecimento de Carga (AWB) e a Fatura Comercial (Invoice) para agilizar o primeiro atendimento.
                        </div>

                        <a href="https://wa.me/5519974090051?text=Olá%20Victor,%20gostaria%20de%20solicitar%20uma%20cotação%20para%20desembaraço%20aduaneiro%20em%20Viracopos." target="_blank" rel="noopener noreferrer" class="w-full bg-accent-green hover:bg-accent-greenHover text-navy-900 font-bold py-4 rounded-xl shadow-xl shadow-accent-green/20 transition-all flex items-center justify-center space-x-3 text-lg">
                            <i class="fa-brands fa-whatsapp text-2xl"></i>
                            <span>Abrir Conversa no WhatsApp</span>
                        </a>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-slate-950 py-12 border-t border-slate-900 text-center text-slate-500 text-sm">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 space-y-4">
            <p class="font-semibold text-slate-300">Victor Luis Sanches • Despachante Aduaneiro & Consultoria em Comércio Exterior</p>
            <p>Aeroporto Internacional de Viracopos - Campinas/SP | Telefone: (19) 97409-0051</p>
            <p class="text-xs pt-4 border-t border-slate-900/80">&copy; 2026 Victor Luis Sanches. Todos os direitos reservados.</p>
        </div>
    </footer>

    <script>
        // Toggle Mobile Menu
        const menuBtn = document.getElementById('menu-btn');
        const mobileMenu = document.getElementById('mobile-menu');

        menuBtn.addEventListener('click', () => {
            mobileMenu.classList.toggle('hidden');
        });

        // Close mobile menu when clicking nav links
        const mobileLinks = mobileMenu.querySelectorAll('a');
        mobileLinks.forEach(link => {
            link.addEventListener('click', () => {
                mobileMenu.classList.add('hidden');
            });
        });
    </script>
</body>
</html>
