<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Electromecánica Murillo - Ingeniería Eléctromecánica Costa Rica</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;700&display=swap" rel="stylesheet">
    <script src="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/js/all.min.js"></script>
    <style>
        body { font-family: 'Inter', sans-serif; scroll-behavior: smooth; }
        .glass { background: rgba(255, 255, 255, 0.98); backdrop-filter: blur(10px); }
        .tech-gradient { background: linear-gradient(135deg, #0f172a 0%, #1e293b 100%); }
        .accent-gradient { background: linear-gradient(135deg, #f59e0b 0%, #d97706 100%); }
        
        .service-card { transition: all 0.3s cubic-bezier(0.4, 0, 0.2, 1); }
        .service-card:hover { transform: translateY(-10px); box-shadow: 0 20px 25px -5px rgba(0, 0, 0, 0.1); }

        .loader {
            border: 3px solid #f3f3f3;
            border-top: 3px solid #f59e0b;
            border-radius: 50%;
            width: 20px;
            height: 20px;
            animation: spin 1s linear infinite;
        }
        @keyframes spin { 0% { transform: rotate(0deg); } 100% { transform: rotate(360deg); } }

        .chat-bubble { animation: slideIn 0.3s ease-out; }
        @keyframes slideIn { from { transform: translateY(20px); opacity: 0; } to { transform: translateY(0); opacity: 1; } }
    </style>
</head>
<body class="bg-slate-50 text-slate-900">

    <nav class="fixed w-full z-[100] glass border-b border-slate-200">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex justify-between h-20 items-center">
                <div class="flex items-center space-x-2">
                    <div class="p-2 accent-gradient rounded-lg text-white shadow-lg">
                        <i class="fas fa-bolt-lightning text-xl"></i>
                    </div>
                    <div class="flex flex-col">
                        <span class="text-lg md:text-xl font-bold tracking-tight text-slate-800 leading-none">Electromecánica <span class="text-amber-600">Murillo</span></span>
                        <span class="text-[10px] text-slate-500 font-semibold tracking-wider uppercase">www.electromecanicamurillo.com</span>
                    </div>
                </div>
                <div class="hidden lg:flex space-x-8 font-semibold text-slate-600 text-sm">
                    <a href="#inicio" class="hover:text-amber-600 transition">Inicio</a>
                    <a href="#servicios" class="hover:text-amber-600 transition">Servicios</a>
                    <a href="#analizador" class="hover:text-amber-600 transition">Análisis Técnico</a>
                    <a href="#contacto" class="hover:text-amber-600 transition">Contacto</a>
                </div>
                <div class="flex items-center space-x-4">
                    <a href="tel:85723218" class="bg-red-600 hover:bg-red-700 text-white px-5 py-2 rounded-full font-bold flex items-center space-x-2 transition shadow-lg text-sm">
                        <i class="fas fa-phone-volume"></i>
                        <span class="hidden sm:inline">8572-3218</span>
                    </a>
                </div>
            </div>
        </div>
    </nav>

    <section id="inicio" class="pt-32 pb-20 tech-gradient text-white relative overflow-hidden">
        <div class="absolute inset-0 opacity-10 pointer-events-none">
            <div class="absolute inset-0" style="background-image: radial-gradient(#ffffff 1px, transparent 1px); background-size: 40px 40px;"></div>
        </div>
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 relative z-10">
            <div class="grid lg:grid-cols-2 gap-12 items-center">
                <div class="text-left">
                    <div class="inline-flex items-center space-x-2 bg-amber-500/20 text-amber-400 border border-amber-500/30 px-4 py-1 rounded-full text-xs font-bold mb-6 tracking-widest uppercase">
                        <i class="fas fa-certificate"></i>
                        <span>Ingeniería Eléctrica Bajo Normativa Vigente</span>
                    </div>
                    <h1 class="text-4xl md:text-6xl font-extrabold leading-tight mb-6">
                        Soluciones en <br>
                        <span class="text-amber-500">Electromecánica</span>
                    </h1>
                    <p class="text-lg text-slate-300 mb-8 max-w-lg">
                        Especialistas en cumplimiento de normativa nacional, diseño de planos ante el CFIA y legalización de servicios eléctricos en toda Costa Rica.
                    </p>
                    <div class="flex flex-wrap gap-4">
                        <a href="#contacto" class="accent-gradient px-8 py-4 rounded-xl font-bold text-white shadow-xl hover:shadow-amber-500/20 transition transform hover:-translate-y-1">
                            Solicitar Cotización
                        </a>
                        <a href="https://wa.me/50685723218" class="bg-slate-700 hover:bg-slate-600 px-8 py-4 rounded-xl font-bold text-white transition flex items-center space-x-2">
                            <i class="fab fa-whatsapp"></i>
                            <span>WhatsApp Directo</span>
                        </a>
                    </div>
                </div>
                <div class="relative hidden lg:block">
                    <img src="https://images.unsplash.com/photo-1581092160562-40aa08e78837?auto=format&fit=crop&w=800&q=80" alt="Ingeniería Electromecánica Costa Rica" class="rounded-3xl shadow-2xl border-4 border-slate-700/50 grayscale hover:grayscale-0 transition duration-700">
                    <div class="absolute -bottom-6 -right-6 bg-white p-6 rounded-2xl shadow-xl text-slate-900 border border-slate-100">
                        <div class="flex items-center space-x-4">
                            <div class="w-12 h-12 bg-amber-100 rounded-full flex items-center justify-center text-amber-600 text-xl">
                                <i class="fas fa-user-tie"></i>
                            </div>
                            <div>
                                <p class="text-sm font-bold">Inscrito en CFIA</p>
                                <p class="text-xs text-slate-500">Ing. Alban Murillo</p>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <section id="servicios" class="py-24 bg-white">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center mb-16">
                <h2 class="text-3xl md:text-4xl font-bold text-slate-800 mb-4">Servicios Especializados</h2>
                <div class="h-1.5 w-24 accent-gradient mx-auto rounded-full"></div>
                <p class="mt-4 text-slate-500">Compromiso con la seguridad y la legalidad eléctrica en Costa Rica</p>
            </div>

            <div class="grid md:grid-cols-2 lg:grid-cols-4 gap-8">
                <!-- Mantenimientos -->
                <div class="service-card p-8 bg-slate-50 rounded-3xl border border-slate-100">
                    <div class="w-14 h-14 bg-white shadow-md rounded-2xl flex items-center justify-center text-amber-600 text-2xl mb-6">
                        <i class="fas fa-screwdriver-wrench"></i>
                    </div>
                    <h3 class="text-xl font-bold mb-3">Mantenimientos</h3>
                    <p class="text-slate-600 text-sm leading-relaxed">Preventivo y correctivo para industria y comercio, asegurando la continuidad operativa bajo estándares nacionales.</p>
                </div>
                <!-- Boletas -->
                <div class="service-card p-8 bg-slate-50 rounded-3xl border border-slate-100">
                    <div class="w-14 h-14 bg-white shadow-md rounded-2xl flex items-center justify-center text-amber-600 text-2xl mb-6">
                        <i class="fas fa-file-contract"></i>
                    </div>
                    <h3 class="text-xl font-bold mb-3">Boletas Eléctricas</h3>
                    <p class="text-slate-600 text-sm leading-relaxed">Certificación técnica para solicitud de medidores o aumentos de carga ante CNFL, ICE, ESPH y COOPELESCA.</p>
                </div>
                <!-- Diseño Planos -->
                <div class="service-card p-8 bg-slate-50 rounded-3xl border border-slate-100">
                    <div class="w-14 h-14 bg-white shadow-md rounded-2xl flex items-center justify-center text-amber-600 text-2xl mb-6">
                        <i class="fas fa-pencil-ruler"></i>
                    </div>
                    <h3 class="text-xl font-bold mb-3">Diseño de Planos</h3>
                    <p class="text-slate-600 text-sm leading-relaxed">Elaboración de planos electromecánicos de alta precisión para proyectos residenciales, comerciales e industriales.</p>
                </div>
                <!-- Tramites CFIA -->
                <div class="service-card p-8 bg-slate-50 rounded-3xl border border-slate-100">
                    <div class="w-14 h-14 bg-white shadow-md rounded-2xl flex items-center justify-center text-amber-600 text-2xl mb-6">
                        <i class="fas fa-landmark"></i>
                    </div>
                    <h3 class="text-xl font-bold mb-3">Trámites CFIA</h3>
                    <p class="text-slate-600 text-sm leading-relaxed">Gestión completa en plataforma APC, sellado de planos y trámites de responsabilidad profesional ante el Colegio.</p>
                </div>
            </div>
        </div>
    </section>

    <section id="analizador" class="py-24 bg-slate-900 text-white">
        <div class="max-w-5xl mx-auto px-4">
            <div class="text-center mb-12">
                <span class="text-amber-500 font-bold uppercase tracking-widest text-xs">Evaluación Preliminar</span>
                <h2 class="text-3xl md:text-4xl font-bold mt-2">Asistente Técnico de Ingeniería</h2>
                <p class="text-slate-400 mt-4">Analice su requerimiento técnico de forma inmediata mediante nuestra herramienta de diagnóstico.</p>
            </div>

            <div class="bg-slate-800 rounded-3xl p-8 border border-slate-700 shadow-2xl">
                <div class="grid lg:grid-cols-2 gap-10">
                    <div>
                        <h4 class="font-bold text-lg mb-4 flex items-center gap-2">
                            <i class="fas fa-clipboard-list text-amber-500"></i>
                            Descripción de la Necesidad
                        </h4>
                        <textarea id="ai-input" rows="5" class="w-full bg-slate-900 border border-slate-700 rounded-2xl p-4 text-slate-200 outline-none focus:ring-2 focus:ring-amber-500 transition" placeholder="Ej: Requiero diseño de planos para una nave industrial en Alajuela..."></textarea>
                        
                        <div class="mt-6">
                            <h4 class="font-bold text-sm mb-3 text-slate-400">Adjuntar Referencia Visual (Opcional)</h4>
                            <div class="flex items-center justify-center w-full">
                                <label class="flex flex-col items-center justify-center w-full h-28 border-2 border-slate-700 border-dashed rounded-2xl cursor-pointer hover:bg-slate-700/50 transition">
                                    <div class="flex flex-col items-center justify-center pt-2 pb-2" id="upload-ui">
                                        <i class="fas fa-camera text-xl text-slate-500 mb-2"></i>
                                        <p class="text-xs text-slate-400 text-center px-4">Suba foto de tablero o sitio de proyecto para análisis visual</p>
                                    </div>
                                    <input id="image-upload" type="file" class="hidden" accept="image/*" onchange="handleImageUpload(event)" />
                                    <div id="image-preview" class="hidden w-full h-full p-2">
                                        <img src="" id="preview-img" class="w-full h-full object-cover rounded-xl" />
                                    </div>
                                </label>
                            </div>
                        </div>

                        <button onclick="runTechnicalAnalysis()" id="analyze-btn" class="w-full mt-6 accent-gradient py-4 rounded-xl font-bold flex items-center justify-center gap-3 hover:scale-[1.02] transition">
                            <i class="fas fa-microchip"></i>
                            Generar Reporte Técnico
                        </button>
                    </div>

                    <div id="ai-output-container" class="bg-slate-900 rounded-2xl p-6 border border-slate-700 relative min-h-[300px]">
                        <div id="ai-placeholder" class="h-full flex flex-col items-center justify-center text-slate-500 text-center">
                            <i class="fas fa-file-invoice text-4xl mb-4 opacity-20"></i>
                            <p class="text-sm italic">Describa su proyecto o adjunte una imagen para recibir un análisis preliminar basado en estándares profesionales.</p>
                        </div>
                        <div id="ai-loader" class="hidden absolute inset-0 flex flex-col items-center justify-center bg-slate-900/80 rounded-2xl">
                            <div class="loader mb-4"></div>
                            <p class="text-xs font-bold text-amber-500 animate-pulse">Consultando Normativa y Estándares Nacionales...</p>
                        </div>
                        <div id="ai-result" class="hidden text-sm leading-relaxed prose prose-invert max-w-none">
                            <!-- Resultado de Gemini -->
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <section id="contacto" class="py-24 bg-white">
        <div class="max-w-4xl mx-auto px-4">
            <div class="text-center mb-12">
                <h2 class="text-3xl md:text-4xl font-bold mb-4">Solicitud de Ingeniería</h2>
                <p class="text-slate-500">Atención directa por el Ing. Alban Murillo para todos sus trámites y proyectos.</p>
                <p class="text-amber-600 font-bold mt-2 text-sm tracking-widest uppercase">www.electromecanicamurillo.com</p>
            </div>

            <div class="bg-slate-50 rounded-3xl shadow-xl p-8 md:p-12 border border-slate-100">
                <form onsubmit="handleContact(event)" class="space-y-6">
                    <div class="grid md:grid-cols-2 gap-6">
                        <div>
                            <label class="block text-sm font-bold text-slate-700 mb-2">Nombre / Empresa</label>
                            <input type="text" id="contact-name" required class="w-full px-4 py-3 rounded-xl border border-slate-200 focus:ring-2 focus:ring-amber-500 outline-none transition" placeholder="Su nombre o razón social">
                        </div>
                        <div>
                            <label class="block text-sm font-bold text-slate-700 mb-2">Teléfono</label>
                            <input type="tel" id="contact-phone" required class="w-full px-4 py-3 rounded-xl border border-slate-200 focus:ring-2 focus:ring-amber-500 outline-none transition" placeholder="8888-8888">
                        </div>
                    </div>
                    <div>
                        <label class="block text-sm font-bold text-slate-700 mb-2">Servicio Requerido</label>
                        <select id="contact-service" required class="w-full px-4 py-3 rounded-xl border border-slate-200 focus:ring-2 focus:ring-amber-500 outline-none transition bg-white">
                            <option value="">Seleccione una opción</option>
                            <option value="Boletas Eléctricas (ICE/CNFL/COOPELESCA)">Boletas Eléctricas (ICE/CNFL/COOPELESCA)</option>
                            <option value="Diseño de Planos Eléctricos">Diseño de Planos Eléctricos</option>
                            <option value="Mantenimiento Industrial">Mantenimiento Industrial</option>
                            <option value="Trámites CFIA / APC">Trámites CFIA / APC</option>
                            <option value="Otro">Otro requerimiento técnico</option>
                        </select>
                    </div>
                    <div>
                        <label class="block text-sm font-bold text-slate-700 mb-2">Detalle de Solicitud</label>
                        <textarea id="contact-msg" rows="4" required class="w-full px-4 py-3 rounded-xl border border-slate-200 focus:ring-2 focus:ring-amber-500 outline-none transition" placeholder="Describa su necesidad de ingeniería..."></textarea>
                    </div>
                    <button type="submit" class="w-full accent-gradient text-white py-4 rounded-xl font-bold shadow-lg hover:shadow-amber-500/30 transition transform flex items-center justify-center gap-3">
                        <i class="fas fa-paper-plane"></i>
                        Enviar Correo a Electromecánica Murillo
                    </button>
                </form>
            </div>
        </div>
    </section>

    <footer class="bg-slate-900 text-slate-400 py-12 border-t border-slate-800">
        <div class="max-w-7xl mx-auto px-4 text-center">
            <div class="flex items-center justify-center space-x-2 mb-4">
                <div class="p-1.5 bg-amber-500 rounded text-white">
                    <i class="fas fa-bolt-lightning text-sm"></i>
                </div>
                <span class="text-xl font-bold text-white tracking-tight">Electromecánica Murillo</span>
            </div>
            <p class="text-amber-500 font-semibold mb-6 text-sm tracking-widest uppercase">www.electromecanicamurillo.com</p>
            <p class="text-sm max-w-md mx-auto mb-8 leading-relaxed">
                Ingeniería electromecánica con respaldo profesional en Costa Rica. <br>
                Seguridad garantizada bajo normativa nacional vigente.
            </p>
            <div class="flex justify-center gap-6 mb-8 text-xl">
                <a href="tel:85723218" class="hover:text-amber-500 transition"><i class="fas fa-phone"></i></a>
                <a href="https://wa.me/50685723218" class="hover:text-amber-500 transition"><i class="fab fa-whatsapp"></i></a>
                <a href="mailto:albanmurillo4@hotmail.com" class="hover:text-amber-500 transition"><i class="fas fa-envelope"></i></a>
            </div>
            <p class="text-xs uppercase tracking-widest font-bold">Ing. Alban Murillo &copy; 2024 - Costa Rica</p>
        </div>
    </footer>

    <!-- Botón Flotante Chat Inteligente -->
    <div class="fixed bottom-6 right-6 z-[200]">
        <button onclick="toggleChat()" class="w-16 h-16 accent-gradient rounded-full shadow-2xl flex items-center justify-center text-white text-2xl hover:scale-110 transition relative group">
            <i class="fas fa-user-gear"></i>
            <span class="absolute -top-1 -right-1 flex h-4 w-4">
                <span class="animate-ping absolute inline-flex h-full w-full rounded-full bg-amber-400 opacity-75"></span>
                <span class="relative inline-flex rounded-full h-4 w-4 bg-amber-500"></span>
            </span>
        </button>
    </div>

    <div id="chat-window" class="hidden fixed bottom-24 right-6 w-80 md:w-96 bg-white rounded-3xl shadow-2xl z-[200] flex flex-col border border-slate-100 overflow-hidden chat-bubble">
        <div class="p-4 bg-slate-900 text-white flex justify-between items-center">
            <div class="flex items-center gap-3">
                <div class="w-10 h-10 bg-amber-500 rounded-full flex items-center justify-center">
                    <i class="fas fa-bolt text-lg"></i>
                </div>
                <div>
                    <p class="font-bold text-sm">Soporte Técnico</p>
                    <p class="text-[10px] text-amber-500 uppercase font-bold">Electromecánica Murillo</p>
                </div>
            </div>
            <button onclick="toggleChat()" class="hover:bg-white/10 p-2 rounded-lg transition"><i class="fas fa-times"></i></button>
        </div>
        <div id="chat-content" class="h-80 overflow-y-auto p-4 space-y-4 bg-slate-50 flex flex-col">
            <div class="bg-white p-3 rounded-2xl rounded-tl-none shadow-sm border border-slate-100 text-sm max-w-[85%]">
                Hola, bienvenido a <strong>Electromecánica Murillo</strong>. ¿En qué servicio de ingeniería podemos asesorarle hoy?
            </div>
        </div>
        <div class="p-4 bg-white border-t border-slate-100 flex gap-2">
            <input id="chat-input" type="text" placeholder="Escriba su consulta técnica..." class="flex-1 bg-slate-100 rounded-xl px-4 py-2 text-sm outline-none focus:ring-1 focus:ring-amber-500" onkeypress="if(event.key==='Enter') sendMessage()">
            <button onclick="sendMessage()" class="p-2 text-amber-600 hover:text-amber-700 transition"><i class="fas fa-paper-plane text-xl"></i></button>
        </div>
    </div>

    <script>
        const apiKey = ""; // La API Key se inyectará automáticamente
        const model = "gemini-3-flash-preview";
        let base64Image = null;

        function toggleChat() {
            document.getElementById('chat-window').classList.toggle('hidden');
        }

        // Manejo de carga de imagen
        function handleImageUpload(event) {
            const file = event.target.files[0];
            if (file) {
                const reader = new FileReader();
                reader.onload = function(e) {
                    document.getElementById('upload-ui').classList.add('hidden');
                    document.getElementById('image-preview').classList.remove('hidden');
                    document.getElementById('preview-img').src = e.target.result;
                    base64Image = e.target.result.split(',')[1];
                }
                reader.readAsDataURL(file);
            }
        }

        // Función central para llamar a la API de Gemini
        async function callGemini(prompt, isMultimodal = false) {
            const url = `https://generativelanguage.googleapis.com/v1beta/models/${model}:generateContent?key=${apiKey}`;
            
            const contentParts = [{ text: prompt }];
            if (isMultimodal && base64Image) {
                contentParts.push({
                    inlineData: {
                        mimeType: "image/jpeg",
                        data: base64Image
                    }
                });
            }

            const payload = {
                contents: [{ parts: contentParts }],
                systemInstruction: {
                    parts: [{ 
                        text: `Eres el Asistente Técnico Profesional de Electromecánica Murillo en Costa Rica. 
                        TU OBJETIVO: Asesorar sobre mantenimientos, boletas eléctricas, diseño de planos y trámites CFIA.
                        REGLAS CRÍTICAS:
                        1. Basa tus respuestas ÚNICAMENTE en la normativa vigente en Costa Rica (basada en el NEC) y estándares del CFIA.
                        2. SI DETECTAS PELIGRO (humo, chispas, cables expuestos, agua cerca de tableros): Ordena desconexión inmediata y contactar al Ing. Alban Murillo al 85723218.
                        3. NO menciones que eres una IA o modelo de lenguaje. Actúa como un experto de la empresa.
                        4. Usa terminología técnica costarricense: medidor, acometida, sellado APC, breker, caja de registro, COOPELESCA, CNFL, ICE, ESPH.
                        5. Sé serio, técnico, conciso y profesional.` 
                    }]
                }
            };

            try {
                const response = await fetch(url, {
                    method: 'POST',
                    headers: { 'Content-Type': 'application/json' },
                    body: JSON.stringify(payload)
                });
                
                const data = await response.json();
                if (data.candidates && data.candidates[0].content.parts[0].text) {
                    return data.candidates[0].content.parts[0].text;
                } else {
                    throw new Error("Respuesta inválida");
                }
            } catch (error) {
                console.error("Error API Gemini:", error);
                return "Disculpe, tenemos una alta demanda en las consultas técnicas. Por favor, comuníquese directamente al 8572-3218 para asistencia inmediata por parte del Ing. Alban Murillo.";
            }
        }

        // Función para enviar mensajes en el chat
        async function sendMessage() {
            const input = document.getElementById('chat-input');
            const content = document.getElementById('chat-content');
            const text = input.value.trim();
            if (!text) return;

            // Mensaje usuario
            const userMsg = document.createElement('div');
            userMsg.className = "bg-amber-100 p-3 rounded-2xl rounded-tr-none shadow-sm self-end text-sm max-w-[85%]";
            userMsg.textContent = text;
            content.appendChild(userMsg);
            input.value = "";
            content.scrollTop = content.scrollHeight;

            // Indicador de carga
            const typing = document.createElement('div');
            typing.className = "bg-white p-3 rounded-2xl rounded-tl-none shadow-sm border border-slate-100 text-xs italic text-slate-400";
            typing.textContent = "Consultando estándares técnicos...";
            content.appendChild(typing);

            const responseText = await callGemini(text);
            content.removeChild(typing);

            // Respuesta asistente
            const assistantMsg = document.createElement('div');
            assistantMsg.className = "bg-white p-3 rounded-2xl rounded-tl-none shadow-sm border border-slate-100 text-sm max-w-[85%]";
            assistantMsg.innerHTML = responseText.replace(/\n/g, '<br>');
            content.appendChild(assistantMsg);
            content.scrollTop = content.scrollHeight;
        }

        // Función para análisis técnico profundo
        async function runTechnicalAnalysis() {
            const input = document.getElementById('ai-input').value;
            const resContainer = document.getElementById('ai-result');
            const placeholder = document.getElementById('ai-placeholder');
            const loader = document.getElementById('ai-loader');

            if (!input && !base64Image) {
                alert("Por favor, ingrese una descripción o adjunte una imagen para el análisis.");
                return;
            }

            placeholder.classList.add('hidden');
            loader.classList.remove('hidden');
            resContainer.classList.add('hidden');

            let prompt = `Realice un análisis técnico profesional exhaustivo para el siguiente requerimiento en Costa Rica: "${input}". 
            Detalle:
            1. Cumplimiento de normativa vigente.
            2. Necesidad de trámites específicos ante el CFIA o instituciones (ICE/COOPELESCA/CNFL).
            3. Evaluación de posibles riesgos eléctricos.
            4. Recomendaciones de ingeniería inmediata.`;
            
            if (base64Image) {
                prompt = "Analice visualmente esta imagen bajo estándares técnicos de Costa Rica y el contexto de la descripción: " + input + ". Identifique fallos visibles, cumplimiento de normativa y recomendaciones críticas.";
            }

            const analysis = await callGemini(prompt, !!base64Image);
            
            loader.classList.add('hidden');
            resContainer.classList.remove('hidden');
            resContainer.innerHTML = `
                <div class="mb-4 p-2 bg-amber-500/10 border border-amber-500/30 rounded-lg text-amber-500 font-bold text-[10px] uppercase tracking-widest">
                    Evaluación Técnica de Ingeniería - Reporte Preliminar
                </div>
                <div class="text-slate-300">
                    ${analysis.replace(/\*\*(.*?)\*\*/g, '<strong class="text-amber-500">$1</strong>').replace(/\n/g, '<br>')}
                </div>
                <div class="mt-6 flex flex-wrap gap-2">
                    <button onclick="copyReport('${analysis.replace(/'/g, "\\'")}')" class="bg-slate-700 hover:bg-slate-600 px-3 py-1.5 rounded-lg text-xs font-bold transition">Copiar Reporte</button>
                    <a href="#contacto" class="bg-amber-600 hover:bg-amber-700 px-3 py-1.5 rounded-lg text-xs font-bold transition text-white">Contactar con Alban Murillo</a>
                </div>
            `;
        }

        // Manejo de formulario de contacto
        function handleContact(e) {
            e.preventDefault();
            const name = document.getElementById('contact-name').value;
            const phone = document.getElementById('contact-phone').value;
            const service = document.getElementById('contact-service').value;
            const msg = document.getElementById('contact-msg').value;

            const subject = encodeURIComponent(`Nuevo Proyecto CR: ${service} - ${name}`);
            const body = encodeURIComponent(`Hola Ing. Alban Murillo,\n\nSolicito información técnica para el siguiente requerimiento:\n\nNombre: ${name}\nTeléfono: ${phone}\nServicio: ${service}\n\nDetalles del proyecto:\n${msg}\n\nEnviado desde el portal www.electromecanicamurillo.com.`);
            
            window.location.href = `mailto:albanmurillo4@hotmail.com?subject=${subject}&body=${body}`;
        }

        function copyReport(text) {
            const temp = document.createElement("textarea");
            temp.value = text;
            document.body.appendChild(temp);
            temp.select();
            document.execCommand("copy");
            document.body.removeChild(temp);
            alert("El reporte técnico ha sido copiado al portapapeles.");
        }
    </script>
</body>
</html>
