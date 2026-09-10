<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Jack Dogle | Portfolio & AI Assistant</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css" rel="stylesheet">
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Inter', sans-serif;
            background-color: #0d1117; /* GitHub Dark Theme Background */
            color: #c9d1d9;
        }
        /* Custom scrollbar for chat */
        .chat-scroll::-webkit-scrollbar {
            width: 6px;
        }
        .chat-scroll::-webkit-scrollbar-thumb {
            background-color: #4b5563;
            border-radius: 10px;
        }
        .typing-indicator span {
            animation: blink 1.4s infinite both;
            height: 6px;
            width: 6px;
            background: #cbd5e1;
            border-radius: 50%;
            display: inline-block;
            margin: 0 1px;
        }
        .typing-indicator span:nth-child(2) { animation-delay: 0.2s; }
        .typing-indicator span:nth-child(3) { animation-delay: 0.4s; }
        @keyframes blink {
            0% { opacity: 0.2; }
            20% { opacity: 1; }
            100% { opacity: 0.2; }
        }
    </style>
</head>
<body class="antialiased min-h-screen flex flex-col items-center pb-20">

    <header class="w-full max-w-4xl mx-auto p-6 mt-10 text-center">
        <div class="relative inline-block">
            <img src="https://github.com/jackdogle.png" alt="Jack Dogle" class="w-40 h-40 rounded-full mx-auto border-4 border-blue-500 shadow-[0_0_20px_rgba(59,130,246,0.5)] z-10 relative">
            <div class="absolute -bottom-2 -right-2 bg-gray-800 rounded-full p-2 text-2xl border-4 border-[#0d1117] z-20">
                🚀
            </div>
        </div>
        <h1 class="text-4xl font-bold mt-6 text-white tracking-tight">Jack Dogle</h1>
        <p class="text-xl text-blue-400 mt-2 font-medium">Network Automation | Bot Developer | DevOps</p>
        
        <div class="mt-6 flex justify-center gap-4">
            <a href="https://github.com/jackdogle" target="_blank" class="text-gray-400 hover:text-white transition duration-300 text-2xl"><i class="fab fa-github"></i></a>
            <a href="https://linkedin.com/in/jack-dogle-4981943b" target="_blank" class="text-gray-400 hover:text-blue-500 transition duration-300 text-2xl"><i class="fab fa-linkedin"></i></a>
            <a href="mailto:jackdogle@example.com" class="text-gray-400 hover:text-red-500 transition duration-300 text-2xl"><i class="fas fa-envelope"></i></a>
        </div>
    </header>

    <main class="w-full max-w-4xl mx-auto p-6 space-y-12">
        
        <!-- About Section -->
        <section class="bg-[#161b22] border border-gray-700 rounded-2xl p-8 shadow-lg">
            <h2 class="text-2xl font-bold text-white mb-4 border-b border-gray-700 pb-2"><i class="fas fa-user-astronaut mr-2 text-blue-400"></i> Di Balik Layar</h2>
            <p class="text-gray-300 leading-relaxed mb-6">
                Halo! Saya <b>Jack Dogle</b>, seorang pengembang yang berdedikasi pada <b>Server Automation</b> dan <b>Bot Development</b>. Saya memiliki ketertarikan mendalam dalam mengoptimalkan protokol jaringan dan menciptakan alat bantu yang efisien bagi komunitas.
            </p>
            <ul class="space-y-3 text-gray-300">
                <li><i class="fas fa-telescope w-6 text-blue-400"></i> <b>Fokus Saat Ini:</b> Mengembangkan Discord Bots canggih & solusi Tunneling aman.</li>
                <li><i class="fas fa-seedling w-6 text-green-400"></i> <b>Sedang Belajar:</b> Pterodactyl Eggs & keamanan jaringan tingkat lanjut.</li>
                <li><i class="fas fa-handshake w-6 text-yellow-400"></i> <b>Kolaborasi:</b> Proyek SAMP & integrasi API kompleks.</li>
                <li><i class="fas fa-bolt w-6 text-purple-400"></i> <b>Fakta Unik:</b> Menikmati tantangan mencari celah konfigurasi server.</li>
            </ul>
        </section>

        <!-- Skills Section -->
        <section>
            <h2 class="text-2xl font-bold text-white mb-6 text-center">🛠️ Keahlian & Tools</h2>
            <div class="flex flex-wrap justify-center gap-4">
                <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" alt="TS" class="rounded-md hover:scale-105 transition-transform"/>
                <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JS" class="rounded-md hover:scale-105 transition-transform"/>
                <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" class="rounded-md hover:scale-105 transition-transform"/>
                <img src="https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnu-bash&logoColor=white" alt="Bash" class="rounded-md hover:scale-105 transition-transform"/>
                <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white" alt="NodeJS" class="rounded-md hover:scale-105 transition-transform"/>
                <img src="https://img.shields.io/badge/Discord.js-5865F2?style=for-the-badge&logo=discord&logoColor=white" alt="DiscordJS" class="rounded-md hover:scale-105 transition-transform"/>
                <img src="https://img.shields.io/badge/Cloudflare-F38020?style=for-the-badge&logo=cloudflare&logoColor=white" alt="Cloudflare" class="rounded-md hover:scale-105 transition-transform"/>
                <img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black" alt="Linux" class="rounded-md hover:scale-105 transition-transform"/>
                <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker" class="rounded-md hover:scale-105 transition-transform"/>
            </div>
        </section>

        <!-- Projects Section -->
        <section>
            <h2 class="text-2xl font-bold text-white mb-6 text-center">🧩 Proyek Unggulan</h2>
            <div class="grid grid-cols-1 md:grid-cols-3 gap-6">
                <!-- Project 1 -->
                <a href="https://github.com/jackdogle/Discord-Bot-Samp" target="_blank" class="block bg-[#161b22] border border-gray-700 rounded-xl p-6 hover:border-blue-500 transition duration-300 group">
                    <div class="text-4xl text-blue-500 mb-4 group-hover:scale-110 transition-transform"><i class="fab fa-discord"></i></div>
                    <h3 class="text-lg font-bold text-white mb-2">Discord Bot SAMP</h3>
                    <p class="text-sm text-gray-400">Bot Discord canggih yang terintegrasi dengan server SAMP (San Andreas Multiplayer).</p>
                </a>
                <!-- Project 2 -->
                <a href="https://github.com/jackdogle/Cloudflared-RDP-Tutorial-Free" target="_blank" class="block bg-[#161b22] border border-gray-700 rounded-xl p-6 hover:border-orange-500 transition duration-300 group">
                    <div class="text-4xl text-orange-500 mb-4 group-hover:scale-110 transition-transform"><i class="fas fa-cloud"></i></div>
                    <h3 class="text-lg font-bold text-white mb-2">Cloudflare RDP</h3>
                    <p class="text-sm text-gray-400">Panduan komprehensif setup RDP & SSH aman menggunakan Cloudflare Tunnels.</p>
                </a>
                <!-- Project 3 -->
                <a href="https://github.com/jackdogle/python-pterodactyl-tunnel" target="_blank" class="block bg-[#161b22] border border-gray-700 rounded-xl p-6 hover:border-green-500 transition duration-300 group">
                    <div class="text-4xl text-green-500 mb-4 group-hover:scale-110 transition-transform"><i class="fab fa-python"></i></div>
                    <h3 class="text-lg font-bold text-white mb-2">Pterodactyl Tunnel</h3>
                    <p class="text-sm text-gray-400">Egg Pterodactyl berbasis Python dengan dukungan proxy Cloudflare untuk performa maksimal.</p>
                </a>
            </div>
        </section>
    </main>

    <!-- AI Assistant Floating UI -->
    <div id="chatbot-container" class="fixed bottom-6 right-6 z-50 flex flex-col items-end">
        <!-- Chat Window -->
        <div id="chat-window" class="hidden bg-[#161b22] border border-gray-700 rounded-2xl shadow-2xl w-80 sm:w-96 mb-4 overflow-hidden flex-col h-[450px] transition-all duration-300 transform origin-bottom-right">
            <!-- Chat Header -->
            <div class="bg-blue-600 text-white px-4 py-3 flex justify-between items-center rounded-t-2xl">
                <div class="flex items-center gap-2">
                    <i class="fas fa-robot text-xl"></i>
                    <span class="font-bold">Jack's AI Assistant</span>
                </div>
                <button id="close-chat-btn" class="hover:text-gray-300 transition-colors focus:outline-none">
                    <i class="fas fa-times"></i>
                </button>
            </div>
            
            <!-- Chat History -->
            <div id="chat-history" class="flex-1 p-4 overflow-y-auto chat-scroll flex flex-col gap-3 bg-[#0d1117]">
                <div class="bg-gray-800 text-gray-200 rounded-tl-xl rounded-tr-xl rounded-br-xl p-3 text-sm self-start max-w-[85%] border border-gray-700">
                    Halo! Saya AI asisten dari Jack Dogle. Ada yang ingin Anda tanyakan tentang proyek, keahlian, atau pengalaman Jack?
                </div>
            </div>

            <!-- Chat Input -->
            <div class="p-3 bg-[#161b22] border-t border-gray-700 flex gap-2">
                <input type="text" id="chat-input" placeholder="Tanya sesuatu..." class="flex-1 bg-[#0d1117] border border-gray-600 text-white text-sm rounded-full px-4 py-2 focus:outline-none focus:border-blue-500 transition-colors" autocomplete="off" />
                <button id="send-btn" class="bg-blue-600 hover:bg-blue-700 text-white rounded-full w-10 h-10 flex items-center justify-center transition-colors focus:outline-none">
                    <i class="fas fa-paper-plane text-sm -ml-1"></i>
                </button>
            </div>
        </div>

        <!-- Floating Action Button -->
        <button id="fab-btn" class="bg-blue-600 hover:bg-blue-500 text-white w-14 h-14 rounded-full shadow-[0_0_15px_rgba(37,99,235,0.5)] flex items-center justify-center text-2xl transition-all duration-300 transform hover:scale-110 focus:outline-none">
            <i class="fas fa-comment-dots"></i>
        </button>
    </div>

    <script>
        document.addEventListener('DOMContentLoaded', () => {
            const fabBtn = document.getElementById('fab-btn');
            const chatWindow = document.getElementById('chat-window');
            const closeChatBtn = document.getElementById('close-chat-btn');
            const chatInput = document.getElementById('chat-input');
            const sendBtn = document.getElementById('send-btn');
            const chatHistory = document.getElementById('chat-history');

            // --- UI Interactions ---
            fabBtn.addEventListener('click', () => {
                chatWindow.classList.toggle('hidden');
                chatWindow.classList.toggle('flex');
                if (!chatWindow.classList.contains('hidden')) {
                    chatInput.focus();
                }
            });

            closeChatBtn.addEventListener('click', () => {
                chatWindow.classList.add('hidden');
                chatWindow.classList.remove('flex');
            });

            // --- Gemini API Configuration ---
            // System prompt to set the persona of the AI
            const systemPrompt = `Kamu adalah AI Asisten Virtual resmi untuk Jack Dogle.
Tugasmu adalah menjawab pertanyaan pengunjung tentang Jack dengan sopan, ramah, dan profesional dalam bahasa Indonesia.
Informasi tentang Jack Dogle:
- Fokus Utama: Server Automation, Discord Bots, DevOps, dan Tunneling aman.
- Keahlian Teknis: TypeScript, JavaScript, Python, Bash, Node.js, Discord.js, Pterodactyl, Cloudflare Tunnels, Linux, Git, Docker.
- Proyek Unggulan: 
  1. Discord Bot SAMP (Bot discord yang terintegrasi dengan server San Andreas Multiplayer).
  2. Cloudflare RDP (Panduan setup RDP/SSH aman via CF Tunnels).
  3. Python Pterodactyl Tunnel (Egg Pterodactyl dengan dukungan proxy Cloudflare).
- Sedang belajar: Keamanan jaringan tingkat lanjut.
- Fakta Unik: Suka mencari celah unik konfigurasi server untuk optimasi performa.

Jawablah dengan ringkas (maksimal 2 paragraf pendek). Jangan memberikan janji palsu atau informasi di luar konteks yang diberikan.`;

            // Conversation history to maintain context
            let conversationHistory = [
                { role: "user", parts: [{ text: "Halo, siapa kamu?" }] },
                { role: "model", parts: [{ text: "Halo! Saya AI asisten dari Jack Dogle. Ada yang ingin Anda tanyakan tentang proyek, keahlian, atau pengalaman Jack?" }] }
            ];

            // --- Chat Logic ---
            function appendMessage(text, sender) {
                const msgDiv = document.createElement('div');
                msgDiv.className = `p-3 text-sm max-w-[85%] rounded-2xl border ${
                    sender === 'user' 
                    ? 'bg-blue-600 text-white self-end border-blue-500 rounded-tr-none' 
                    : 'bg-gray-800 text-gray-200 self-start border-gray-700 rounded-tl-none'
                }`;
                msgDiv.textContent = text;
                chatHistory.appendChild(msgDiv);
                chatHistory.scrollTop = chatHistory.scrollHeight;
            }

            function showTypingIndicator() {
                const indicator = document.createElement('div');
                indicator.id = 'typing-indicator';
                indicator.className = 'bg-gray-800 text-gray-200 p-3 text-sm max-w-[50%] self-start rounded-2xl rounded-tl-none border border-gray-700 typing-indicator';
                indicator.innerHTML = '<span></span><span></span><span></span>';
                chatHistory.appendChild(indicator);
                chatHistory.scrollTop = chatHistory.scrollHeight;
            }

            function removeTypingIndicator() {
                const indicator = document.getElementById('typing-indicator');
                if (indicator) indicator.remove();
            }

            async function callGeminiAPI(userMessage) {
                // Add user message to history
                conversationHistory.push({ role: "user", parts: [{ text: userMessage }] });

                // The Canvas environment automatically injects the API key when left empty
                const apiKey = ""; 
                const apiUrl = `https://generativelanguage.googleapis.com/v1beta/models/gemini-3-flash-preview:generateContent?key=${apiKey}`;

                const payload = {
                    systemInstruction: {
                        parts: [{ text: systemPrompt }]
                    },
                    contents: conversationHistory,
                };

                let attempt = 0;
                const maxAttempts = 3;
                let delay = 1000;

                while (attempt < maxAttempts) {
                    try {
                        const response = await fetch(apiUrl, {
                            method: 'POST',
                            headers: { 'Content-Type': 'application/json' },
                            body: JSON.stringify(payload)
                        });

                        if (!response.ok) {
                            if (response.status === 429) {
                                // Rate limited, apply exponential backoff
                                attempt++;
                                await new Promise(res => setTimeout(res, delay));
                                delay *= 2;
                                continue;
                            }
                            throw new Error(`HTTP error! status: ${response.status}`);
                        }

                        const result = await response.json();
                        const aiText = result.candidates?.[0]?.content?.parts?.[0]?.text;

                        if (aiText) {
                            // Update history with model response
                            conversationHistory.push({ role: "model", parts: [{ text: aiText }] });
                            return aiText;
                        } else {
                            throw new Error("Invalid response format");
                        }

                    } catch (error) {
                        attempt++;
                        if (attempt >= maxAttempts) {
                            console.error("Gemini API Error:", error);
                            return "Maaf, sistem AI sedang mengalami gangguan. Silakan coba beberapa saat lagi atau hubungi Jack langsung via Email/LinkedIn.";
                        }
                        await new Promise(res => setTimeout(res, delay));
                        delay *= 2;
                    }
                }
            }

            async function handleSend() {
                const text = chatInput.value.trim();
                if (!text) return;

                // 1. Show user message
                appendMessage(text, 'user');
                chatInput.value = '';
                
                // 2. Show typing indicator
                showTypingIndicator();

                // 3. Call AI
                const aiResponse = await callGeminiAPI(text);

                // 4. Remove typing and show AI message
                removeTypingIndicator();
                appendMessage(aiResponse, 'model');
            }

            // Event Listeners
            sendBtn.addEventListener('click', handleSend);
            chatInput.addEventListener('keypress', (e) => {
                if (e.key === 'Enter') handleSend();
            });
        });
    </script>
</body>
</html>