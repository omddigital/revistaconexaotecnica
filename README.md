
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Conexão Técnica - Valorizando quem faz a obra acontecer</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Montserrat:wght@400;700;900&display=swap');
        
        body {
            font-family: 'Montserrat', sans-serif;
            background-color: #f8f9fa;
        }
        
        .hero-gradient {
            background: linear-gradient(135deg, #f59e0b 0%, #ef4444 100%);
        }
        
        .section-divider {
            border-bottom: 3px solid #f59e0b;
            width: 100px;
            margin: 1rem auto;
        }
        
        .floating-card {
            box-shadow: 0 10px 25px -5px rgba(0, 0, 0, 0.1), 0 10px 10px -5px rgba(0, 0, 0, 0.04);
            transition: all 0.3s ease;
        }
        
        .floating-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 20px 25px -5px rgba(0, 0, 0, 0.1), 0 10px 10px -5px rgba(0, 0, 0, 0.04);
        }
        
        .carousel-slide {
            transition: opacity 1s ease;
            opacity: 0;
        }
        
        .carousel-slide img {
            width: 100%;
            height: 100%;
            object-fit: cover;
        }
    </style>
</head>
<body class="bg-gray-50">
    <!-- Header -->
    <header class="hero-gradient text-white py-6">
        <div class="container mx-auto px-4">
            <div class="flex flex-col md:flex-row justify-between items-center">
                <div class="mb-4 md:mb-0">
                    <h1 class="text-3xl md:text-4xl font-bold">CONEXÃO TÉCNICA</h1>
                    <p class="text-lg md:text-xl mt-2">Valorizando quem faz a obra acontecer</p>
                </div>
                <div class="flex items-center space-x-4">
                    <span class="hidden md:block">Edição Especial - 2025</span>
                    <button class="bg-white text-orange-600 font-bold py-2 px-6 rounded-full hover:bg-gray-100 transition">
                        Assine já
                    </button>
                </div>
            </div>
        </div>
    </header>

    <!-- Cover Section -->
    <section class="relative">
        <div class="carousel relative w-full h-[80vh] overflow-hidden">
            <!-- Slide 1 -->
            <div class="carousel-slide absolute inset-0 w-full h-full">
                <div class="absolute inset-0 bg-black/50"></div>
                <img src="https://images.unsplash.com/photo-1581094794329-c8112a89af12?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=2070&q=80" 
                     alt="Técnicos em plataforma offshore" 
                     class="w-full h-full object-cover">
                <div class="container mx-auto px-4 text-center absolute inset-0 flex flex-col justify-center items-center text-white">
                    <h2 class="text-4xl md:text-6xl font-bold mb-6">O TÉCNICO NO CENTRO DA RETOMADA ECONÔMICA NACIONAL</h2>
                    <p class="text-xl md:text-2xl max-w-3xl mx-auto mb-8">Um mergulho profundo nas forças que estão reerguendo a economia: energia, saneamento, transporte, construção civil.</p>
                    <div class="flex flex-col md:flex-row justify-center gap-4">
                        <button class="bg-orange-500 hover:bg-orange-600 text-white font-bold py-3 px-8 rounded-full transition">
                            Leia a matéria completa
                        </button>
                        <button class="bg-transparent border-2 border-white hover:bg-white hover:text-black text-white font-bold py-3 px-8 rounded-full transition">
                            Veja o vídeo exclusivo
                        </button>
                    </div>
                </div>
            </div>
            
            <!-- Slide 2 -->
            <div class="carousel-slide absolute inset-0 w-full h-full">
                <div class="absolute inset-0 bg-black/50"></div>
                <img src="https://images.unsplash.com/photo-1581094794329-c8112a89af12?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=2070&q=80" 
                     alt="Equipe técnica trabalhando" 
                     class="w-full h-full object-cover">
                <div class="container mx-auto px-4 text-center absolute inset-0 flex flex-col justify-center items-center text-white">
                    <h2 class="text-4xl md:text-6xl font-bold mb-6">VALORIZANDO QUEM FAZ A OBRA ACONTECER</h2>
                    <p class="text-xl md:text-2xl max-w-3xl mx-auto mb-8">Técnicos em macacão amarelo, capacete e EPIs completos garantindo segurança e qualidade nas operações.</p>
                </div>
            </div>
            
            <!-- Slide 3 -->
            <div class="carousel-slide absolute inset-0 w-full h-full">
                <div class="absolute inset-0 bg-black/50"></div>
                <img src="https://images.unsplash.com/photo-1581094794329-c8112a89af12?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=2070&q=80" 
                     alt="Plataforma Petrobras ao pôr do sol" 
                     class="w-full h-full object-cover">
                <div class="container mx-auto px-4 text-center absolute inset-0 flex flex-col justify-center items-center text-white">
                    <h2 class="text-4xl md:text-6xl font-bold mb-6">TECNOLOGIA E SEGURANÇA OFFSHORE</h2>
                    <p class="text-xl md:text-2xl max-w-3xl mx-auto mb-8">A excelência técnica brasileira em águas profundas, construindo o futuro energético do país.</p>
                </div>
            </div>
        </div>
        
        <!-- Carousel Controls -->
        <button class="carousel-prev absolute left-4 top-1/2 -translate-y-1/2 bg-white/30 hover:bg-white/50 text-white p-3 rounded-full z-10 transition">
            <i class="fas fa-chevron-left"></i>
        </button>
        <button class="carousel-next absolute right-4 top-1/2 -translate-y-1/2 bg-white/30 hover:bg-white/50 text-white p-3 rounded-full z-10 transition">
            <i class="fas fa-chevron-right"></i>
        </button>
        
        <!-- Carousel Indicators -->
        <div class="absolute bottom-8 left-0 right-0 flex justify-center gap-2">
            <button class="carousel-indicator w-3 h-3 rounded-full bg-white/50 hover:bg-white transition"></button>
            <button class="carousel-indicator w-3 h-3 rounded-full bg-white/50 hover:bg-white transition"></button>
            <button class="carousel-indicator w-3 h-3 rounded-full bg-white/50 hover:bg-white transition"></button>
        </div>
    </section>

    <!-- Carousel Script -->
    <script>
        document.addEventListener('DOMContentLoaded', function() {
            const slides = document.querySelectorAll('.carousel-slide');
            const prevBtn = document.querySelector('.carousel-prev');
            const nextBtn = document.querySelector('.carousel-next');
            const indicators = document.querySelectorAll('.carousel-indicator');
            let currentSlide = 0;
            
            function showSlide(index) {
                slides.forEach((slide, i) => {
                    slide.style.opacity = i === index ? '1' : '0';
                    slide.style.zIndex = i === index ? '10' : '0';
                });
                
                indicators.forEach((indicator, i) => {
                    indicator.classList.toggle('bg-white', i === index);
                    indicator.classList.toggle('bg-white/50', i !== index);
                });
            }
            
            function nextSlide() {
                currentSlide = (currentSlide + 1) % slides.length;
                showSlide(currentSlide);
            }
            
            function prevSlide() {
                currentSlide = (currentSlide - 1 + slides.length) % slides.length;
                showSlide(currentSlide);
            }
            
            // Initialize
            showSlide(currentSlide);
            
            // Event Listeners
            nextBtn.addEventListener('click', nextSlide);
            prevBtn.addEventListener('click', prevSlide);
            
            indicators.forEach((indicator, index) => {
                indicator.addEventListener('click', () => {
                    currentSlide = index;
                    showSlide(currentSlide);
                });
            });
            
            // Auto-advance
            setInterval(nextSlide, 5000);
        });
    </script>

    <!-- Editorial Section -->
    <section class="py-16 bg-white">
        <div class="container mx-auto px-4">
            <div class="max-w-4xl mx-auto">
                <h2 class="text-3xl font-bold text-center mb-2">EDITORIAL</h2>
                <div class="section-divider"></div>
                <p class="text-gray-600 text-center mb-8">Por Vicente Carneiro</p>
                
                <div class="bg-gray-50 p-8 rounded-lg">
                    <p class="text-lg mb-6">
                        Neste editorial, não apenas escrevo, mas convoco. Um chamado à sociedade para enxergar os técnicos como gigantes silenciosos que sustentam, com talento e suor, os pilares da infraestrutura nacional. Na edição especial de 2025, destacamos os técnicos em macacão amarelo da Petrobras, verdadeiros heróis da engenharia offshore.
                    </p>
                    <p class="text-lg mb-6">
                        Explico que por trás de cada obra há decisões complexas, ajustes finos e inspeções rigorosas conduzidas por técnicos que garantem segurança, eficiência e qualidade. Mostro como, das plataformas do pré-sal aos corredores de hospitais, o toque técnico é invisível, mas absolutamente vital. Nossas reportagens revelam:
                    </p>
                    <ul class="text-lg mb-6 list-disc pl-6 space-y-2">
                        <li><strong>O dia a dia dos técnicos em plataformas de petróleo:</strong> Rotinas de 12h em turnos alternados, inspeções meticulosas em equipamentos críticos, manutenção preventiva que evita paradas milionárias</li>
                        <li><strong>Os desafios da segurança industrial:</strong> Operações em ambientes com temperaturas extremas (+50°C a -20°C), pressões equivalentes a 300m submersos, atmosferas potencialmente explosivas</li>
                        <li><strong>Inovações tecnológicas:</strong> Desenvolvimento brasileiro de robôs submarinos para inspeção em águas profundas, sistemas de monitoramento contínuo via IoT</li>
                        <li><strong>Protocolos de emergência:</strong> Treinamentos mensais em combate a incêndio, abandono de plataforma em 90 segundos, resgate em helicóptero (HUET)</li>
                    </ul>
                    
                    <h3 class="text-xl font-bold mb-4 mt-8">QUALIFICAÇÃO E FUTURO</h3>
                    <p class="text-lg mb-4">
                        Em parceria exclusiva com a FOX Brasil, lançamos o programa "Técnicos do Amanhã" - 15 mil bolsas integrais em cursos técnicos reconhecidos pelo MEC. Destaque para:
                    </p>
                    <ul class="text-lg mb-6 list-disc pl-6 space-y-2">
                        <li><strong>Ensino Superior Sequencial:</strong> Cursos de 2 anos com titulação equivalente à graduação, focados em petróleo/gás e energias renováveis</li>
                        <li><strong>Carreiras de liderança:</strong> Depoimentos de ex-alunos técnicos que hoje ocupam cargos de supervisão e gerência em multinacionais</li>
                        <li><strong>Mentorias:</strong> Programa que conecta aprendizes a veteranos com 20+ anos de experiência offshore</li>
                    </ul>

                    <h3 class="text-xl font-bold mb-4 mt-8">TECNOLOGIA E SUSTENTABILIDADE</h3>
                    <p class="text-lg mb-4">
                        O Projeto Hidroenergia está formando 5 mil técnicos especializados até 2026 para liderar a transição energética nacional:
                    </p>
                    <ul class="text-lg mb-6 list-disc pl-6 space-y-2">
                        <li><strong>Casos de sucesso:</strong> Fazenda eólica no RN que reduziu custos em 40% com manutenção preditiva feita por técnicos locais</li>
                        <li><strong>Eficiência energética:</strong> Sistemas de cogeração em refinarias que reaproveitam 85% do calor residual</li>
                        <li><strong>Hidrogênio verde:</strong> Primeiro laboratório offshore para produção piloto, totalmente operado por técnicos brasileiros</li>
                    </ul>

                    <p class="text-lg font-bold mt-8">
                        "É hora do Brasil conhecer, respeitar e celebrar quem, com coragem e conhecimento, constrói o presente e abre caminhos para o futuro. Os técnicos não são apenas peças fundamentais - são os arquitetos da nova revolução industrial verde que colocará nosso país na vanguarda mundial. Esta edição especial de 2025 é nossa homenagem aos homens e mulheres que vestem o macacão amarelo com orgulho e transformam desafios em conquistas diárias."
                    </p>
                    <p class="text-right mt-4 font-bold">Vicente Carneiro<br>Editor-Chefe</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Main Content -->
    <section class="py-16 bg-gray-50">
        <div class="container mx-auto px-4">
            <h2 class="text-3xl font-bold text-center mb-12">DESTAQUES DA EDIÇÃO</h2>
            
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
                <!-- Card 1 -->
                <div class="bg-white rounded-xl overflow-hidden floating-card">
                    <div class="h-48 bg-blue-800 flex items-center justify-center">
                        <i class="fas fa-oil-rig text-white text-6xl"></i>
                    </div>
                    <div class="p-6">
                        <h3 class="text-xl font-bold mb-3">Painel Offshore</h3>
                        <p class="text-gray-600 mb-4">Profundidade técnica sobre operações em alto mar:
                            <ul class="mt-2 space-y-1 text-gray-600 text-sm list-disc pl-4">
                                <li><strong>Rotinas diárias:</strong> Turnos de 12h, inspeções de equipamentos críticos, manutenção preventiva</li>
                                <li><strong>Segurança:</strong> EPIs específicos para ambientes explosivos, treinamentos obrigatórios NRs 10, 12 e 35</li>
                                <li><strong>Tecnologia:</strong> Sensores IoT para monitoramento contínuo, drones para inspeção de estruturas</li>
                                <li><strong>Pré-sal:</strong> Desafios técnicos em águas ultra-profundas (até 3.000m), soluções brasileiras inovadoras</li>
                                <li><strong>Energia limpa:</strong> Projetos pioneiros de hidrogênio verde offshore e captura de carbono</li>
                            </ul>
                        </p>
                        <div class="flex items-center text-orange-500 font-medium">
                            <a href="https://wa.me/5522988273669" class="flex items-center">
                                <span>Saiba mais</span>
                                <i class="fas fa-arrow-right ml-2"></i>
                            </a>
                        </div>
                    </div>
                </div>
                
                <!-- Card 2 -->
                <div class="bg-white rounded-xl overflow-hidden floating-card">
                    <div class="h-48 bg-green-700 flex items-center justify-center">
                        <i class="fas fa-city text-white text-6xl"></i>
                    </div>
                    <div class="p-6">
                        <h3 class="text-xl font-bold mb-3">Mercado Nacional</h3>
                        <p class="text-gray-600 mb-4">Panorama completo do setor técnico brasileiro:
                            <ul class="mt-2 space-y-1 text-gray-600 text-sm list-disc pl-4">
                                <li><strong>Infraestrutura:</strong> Demandas por técnicos em usinas (5.000 vagas), ferrovias (3.200 vagas) e portos</li>
                                <li><strong>Certificações:</strong> NRs obrigatórias, cursos SENAI/SENAC, especializações internacionais</li>
                                <li><strong>EPIs:</strong> Evolução tecnológica - capacetes com realidade aumentada, macacões anti-chama</li>
                                <li><strong>Transporte:</strong> Técnicos especializados em sistemas metroviários (sinalização, eletrônica)</li>
                                <li><strong>Saneamento:</strong> Novo marco legal exigindo 15.000 técnicos para universalização até 2033</li>
                            </ul>
                        </p>
                        <div class="flex items-center text-orange-500 font-medium">
                            <span>Saiba mais</span>
                            <i class="fas fa-arrow-right ml-2"></i>
                        </div>
                    </div>
                </div>
                
                <!-- Card 3 -->
                <div class="bg-white rounded-xl overflow-hidden floating-card">
                    <div class="h-48 bg-purple-700 flex items-center justify-center">
                        <i class="fas fa-globe-americas text-white text-6xl"></i>
                    </div>
                    <div class="p-6">
                        <h3 class="text-xl font-bold mb-3">Internacional</h3>
                        <p class="text-gray-600 mb-4">Expansão global da expertise brasileira:
                            <ul class="mt-2 space-y-1 text-gray-600 text-sm list-disc pl-4">
                                <li><strong>África:</strong> Contratos de técnicos brasileiros em projetos de petróleo em Angola e Moçambique</li>
                                <li><strong>América Latina:</strong> Transferência de know-how em pré-sal para Colômbia e Argentina</li>
                                <li><strong>Oriente Médio:</strong> Técnicos brasileiros liderando equipes em Dubai e Qatar</li>
                                <li><strong>Europa:</strong> Demandas por especialistas em energia eólica offshore</li>
                                <li><strong>Certificações:</strong> Como validar diplomas técnicos para trabalhar no exterior</li>
                            </ul>
                        </p>
                        <div class="flex items-center text-orange-500 font-medium">
                            <span>Saiba mais</span>
                            <i class="fas fa-arrow-right ml-2"></i>
                        </div>
                    </div>
                </div>
                
                <!-- Card 4 -->
                <div class="bg-white rounded-xl overflow-hidden floating-card">
                    <div class="h-48 bg-yellow-600 flex items-center justify-center">
                        <i class="fas fa-graduation-cap text-white text-6xl"></i>
                    </div>
                    <div class="p-6">
                        <h3 class="text-xl font-bold mb-3">Qualificação</h3>
                        <p class="text-gray-600 mb-4">Caminhos para capacitação técnica:
                            <ul class="mt-2 space-y-1 text-gray-600 text-sm list-disc pl-4">
                                <li><strong>Offshore:</strong> Cursos de sobrevivência no mar (HUET), combate a incêndio, primeiros socorros</li>
                                <li><strong>EPIs:</strong> Treinamentos práticos com equipamentos reais em ambientes simulados</li>
                                <li><strong>Emergência:</strong> Simulações de abandono de plataforma, controle de vazamentos, resgate</li>
                                <li><strong>Normas:</strong> Especialização em normas técnicas da Petrobras (SGSO) e ANP</li>
                                <li><strong>Internacional:</strong> Cursos de inglês técnico, certificações OPITO e IWCF</li>
                                <li><strong>Remuneração:</strong> Técnicos certificados podem ganhar até 3x mais</li>
                            </ul>
                        </p>
                        <div class="flex items-center text-orange-500 font-medium">
                            <span>Saiba mais</span>
                            <i class="fas fa-arrow-right ml-2"></i>
                        </div>
                    </div>
                </div>
                
                <!-- Card 5 -->
                <div class="bg-white rounded-xl overflow-hidden floating-card">
                    <div class="h-48 bg-teal-600 flex items-center justify-center">
                        <i class="fas fa-solar-panel text-white text-6xl"></i>
                    </div>
                    <div class="p-6">
                        <h3 class="text-xl font-bold mb-3">Tecnologia</h3>
                        <p class="text-gray-600 mb-4">Inovações transformando o setor:
                            <ul class="mt-2 space-y-1 text-gray-600 text-sm list-disc pl-4">
                                <li><strong>Hidroenergia:</strong> Novas turbinas subaquáticas para geração limpa (potencial de 15GW)</li>
                                <li><strong>Digitalização:</strong> Uso de BIM, realidade aumentada e digital twins em obras</li>
                                <li><strong>Robótica:</strong> Drones e ROVs para inspeção em áreas de risco</li>
                                <li><strong>Treinamento:</strong> Simuladores virtuais para capacitação em emergências</li>
                                <li><strong>Energias:</strong> Transição para hidrogênio verde e CCUS (captura de carbono)</li>
                                <li><strong>Carreiras:</strong> Novas funções técnicas em energias renováveis</li>
                            </ul>
                        </p>
                        <div class="flex items-center text-orange-500 font-medium">
                            <span>Saiba mais</span>
                            <i class="fas fa-arrow-right ml-2"></i>
                        </div>
                    </div>
                </div>
                
                <!-- Card 6 -->
                <div class="bg-white rounded-xl overflow-hidden floating-card">
                    <div class="h-48 bg-red-600 flex items-center justify-center">
                        <i class="fas fa-heartbeat text-white text-6xl"></i>
                    </div>
                    <div class="p-6">
                        <h3 class="text-xl font-bold mb-3">Benefícios</h3>
                        <p class="text-gray-600 mb-4">Vantagens exclusivas para técnicos:
                            <ul class="mt-2 space-y-1 text-gray-600 text-sm list-disc pl-4">
                                <li><strong>Saúde:</strong> Telemedicina 24h com especialistas em medicina ocupacional</li>
                                <li><strong>Utilidades:</strong> Até 30% de desconto em contas de luz e água</li>
                                <li><strong>Cartão Técnico+:</strong> Vantagens em 5.000 estabelecimentos nacionais</li>
                                <li><strong>Educação:</strong> Bolsas de estudo em cursos técnicos e idiomas</li>
                                <li><strong>Seguros:</strong> Planos de vida e acidentes pessoais diferenciados</li>
                                <li><strong>Carreira:</strong> Programas de desenvolvimento profissional contínuo</li>
                            </ul>
                        </p>
                        <div class="flex items-center text-orange-500 font-medium">
                            <span>Saiba mais</span>
                            <i class="fas fa-arrow-right ml-2"></i>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Stats Section -->
    <section class="py-16 bg-orange-600 text-white">
        <div class="container mx-auto px-4">
            <h2 class="text-3xl font-bold text-center mb-12">EM NÚMEROS</h2>
            
            <div class="grid grid-cols-1 md:grid-cols-3 gap-8 text-center">
                <div>
                    <div class="text-5xl font-bold mb-2">85%</div>
                    <p class="text-xl">das obras de infraestrutura dependem diretamente de técnicos qualificados</p>
                </div>
                <div>
                    <div class="text-5xl font-bold mb-2">2030</div>
                    <p class="text-xl">previsão de crescimento acima da média nacional no setor técnico</p>
                </div>
                <div>
                    <div class="text-5xl font-bold mb-2">10.000+</div>
                    <p class="text-xl">vagas técnicas abertas apenas no setor offshore</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Testimonials -->
    <section class="py-16 bg-white">
        <div class="container mx-auto px-4">
            <h2 class="text-3xl font-bold text-center mb-12">QUEM FAZ ACONTECER</h2>
            
            <div class="grid grid-cols-1 md:grid-cols-2 gap-8">
                <div class="bg-gray-50 p-8 rounded-lg">
                    <div class="flex items-center mb-4">
                        <div class="w-16 h-16 bg-orange-500 rounded-full flex items-center justify-center text-white text-2xl font-bold mr-4">JC</div>
                        <div>
                            <h4 class="font-bold">João Carlos</h4>
                            <p class="text-gray-600">Técnico em Plataformas Offshore</p>
                        </div>
                    </div>
                    <p class="text-lg italic">
                        "Comecei carregando ferramentas e hoje comando uma equipe de 15 técnicos na plataforma P-75. Cada dia no macacão amarelo é um desafio - desde inspeções de segurança até manutenção preventiva. A educação técnica mudou minha vida e da minha família. Esta edição especial de 2025 captura exatamente nosso orgulho profissional."
                    </p>
                </div>
                
                <div class="bg-gray-50 p-8 rounded-lg">
                    <div class="flex items-center mb-4">
                        <div class="w-16 h-16 bg-orange-500 rounded-full flex items-center justify-center text-white text-2xl font-bold mr-4">AM</div>
                        <div>
                            <h4 class="font-bold">Ana Maria</h4>
                            <p class="text-gray-600">Inspetora de Qualidade</p>
                        </div>
                    </div>
                    <p class="text-lg italic">
                        "Como inspetora de qualidade, meu trabalho vai além de checklists. Garantir que cada parafuso, cada conexão esteja perfeita pode salvar vidas offshore. Ver uma obra que fiscalizei operando com segurança por anos é minha maior recompensa. Esta edição especial mostra porque técnico não é só profissão - é missão, especialmente quando vestimos o macacão amarelo da Petrobras."
                    </p>
                </div>
            </div>
        </div>
    </section>

    <!-- Call to Action -->
    <section class="py-16 bg-gray-800 text-white">
        <div class="container mx-auto px-4 text-center">
            <h2 class="text-3xl font-bold mb-6">TÉCNICO É VALOR</h2>
            <p class="text-xl max-w-3xl mx-auto mb-8">
                "Eles não estão só construindo pontes, plataformas e hospitais. Estão construindo esperança, progresso e futuro. Técnico é mais que valor: técnico é essencial."
            </p>
            <button class="bg-orange-500 hover:bg-orange-600 text-white font-bold py-3 px-8 rounded-full transition">
                Junte-se ao movimento
            </button>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-gray-900 text-white py-12">
        <div class="container mx-auto px-4">
            <div class="grid grid-cols-1 md:grid-cols-4 gap-8">
                <div>
                    <h3 class="text-xl font-bold mb-4">CONEXÃO TÉCNICA</h3>
                    <p>Valorizando quem faz a obra acontecer</p>
                </div>
                <div>
                    <h4 class="font-bold mb-4">Edições</h4>
                    <ul class="space-y-2">
                        <li><a href="#" class="hover:text-orange-500 transition">Última edição</a></li>
                        <li><a href="#" class="hover:text-orange-500 transition">Arquivo</a></li>
                        <li><a href="#" class="hover:text-orange-500 transition">Especiais</a></li>
                    </ul>
                </div>
                <div>
                    <h4 class="font-bold mb-4">Links</h4>
                    <ul class="space-y-2">
                        <li><a href="#" class="hover:text-orange-500 transition">Assinaturas</a></li>
                        <li><a href="#" class="hover:text-orange-500 transition">Anuncie</a></li>
                        <li><a href="#" class="hover:text-orange-500 transition">Contato</a></li>
                    </ul>
                </div>
                <div>
                    <h4 class="font-bold mb-4">Siga-nos</h4>
                    <div class="flex space-x-4">
                        <a href="#" class="w-10 h-10 bg-gray-700 rounded-full flex items-center justify-center hover:bg-orange-500 transition">
                            <i class="fab fa-facebook-f"></i>
                        </a>
                        <a href="#" class="w-10 h-10 bg-gray-700 rounded-full flex items-center justify-center hover:bg-orange-500 transition">
                            <i class="fab fa-instagram"></i>
                        </a>
                        <a href="#" class="w-10 h-10 bg-gray-700 rounded-full flex items-center justify-center hover:bg-orange-500 transition">
                            <i class="fab fa-linkedin-in"></i>
                        </a>
                        <a href="#" class="w-10 h-10 bg-gray-700 rounded-full flex items-center justify-center hover:bg-orange-500 transition">
                            <i class="fab fa-youtube"></i>
                        </a>
                    </div>
                </div>
            </div>
            <div class="border-t border-gray-700 mt-8 pt-8 text-center text-gray-400">
                <p>© 2023 Conexão Técnica. Todos os direitos reservados.</p>
            </div>
        </div>
    </footer>

    <script>
        // Simple animation for cards on scroll
        document.addEventListener('DOMContentLoaded', function() {
            const cards = document.querySelectorAll('.floating-card');
            
            const observer = new IntersectionObserver((entries) => {
                entries.forEach(entry => {
                    if (entry.isIntersecting) {
                        entry.target.style.opacity = '1';
                        entry.target.style.transform = 'translateY(0)';
                    }
                });
            }, { threshold: 0.1 });
            
            cards.forEach(card => {
                card.style.opacity = '0';
                card.style.transform = 'translateY(20px)';
                card.style.transition = 'all 0.6s ease';
                observer.observe(card);
            });
        });
    </script>
</body>
</html>
