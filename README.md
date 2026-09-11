<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Asesmen Sumatif Tengah Semester - Fikih Kelas 8 | SMP Islam Maryam Muraith</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css" rel="stylesheet">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Lora:ital,wght@0,400;0,600;0,700;1,400&family=Inter:wght@300;400;600;700&display=swap" rel="stylesheet">
    
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        tosca: '#14b8a6',
                        toscaDark: '#0f766e',
                        navy: '#1e3a8a',
                        gold: '#eab308',
                        goldLight: '#fde047',
                        silver: '#cbd5e1',
                        greenIslamic: '#065f46',
                        duskDark: '#090d16',
                        duskOrange: '#ea580c',
                        duskPurple: '#31103f',
                    },
                    fontFamily: {
                        serif: ['"Lora"', '"High Tower Text"', 'serif'],
                        sans: ['"Inter"', 'sans-serif'],
                    }
                }
            }
        }
    </script>
    <style>
        :root {
            --bg-pattern: url("data:image/svg+xml,%3Csvg width='60' height='60' viewBox='0 0 60 60' xmlns='http://www.w3.org/2000/svg'%3E%3Cg fill='none' fill-rule='evenodd'%3E%3Cg fill='%23fde047' fill-opacity='0.04'%3E%3Cpath d='M36 34v-4h-2v4h-4v2h4v4h2v-4h4v-2h-4zm0-30V0h-2v4h-4v2h4v4h2V6h4V4h-4zM6 34v-4H4v4H0v2h4v4h2v-4h4v-2H6zM6 4V0H4v4H0v2h4v4h2V6h4V4H6z'/%3E%3C/g%3E%3C/g%3E%3C/svg%3E");
        }
        body {
            font-family: 'Inter', sans-serif;
            background: linear-gradient(to top, #1c0a00 0%, #31103f 35%, #0d1b2a 80%, #090d16 100%);
            background-image: var(--bg-pattern), linear-gradient(to top, #1c0a00 0%, #31103f 35%, #0d1b2a 80%, #090d16 100%);
            background-attachment: fixed;
            overflow-x: hidden;
            -webkit-touch-callout: none;
            -webkit-user-select: none;
            user-select: none;
            color: #f8fafc;
        }
        
        /* Twinkling Stars */
        .star {
            position: absolute;
            background: #fde047;
            border-radius: 50%;
            animation: twinkle 3s infinite ease-in-out;
            pointer-events: none;
        }
        @keyframes twinkle {
            0%, 100% { opacity: 0.15; transform: scale(0.8); }
            50% { opacity: 1; transform: scale(1.3); box-shadow: 0 0 8px #fde047; }
        }

        .font-theme { font-family: 'Lora', 'High Tower Text', serif; }
        
        .fade-in { animation: fadeIn 0.4s ease-in-out; }
        .slide-in-right { animation: slideInRight 0.4s cubic-bezier(0.25, 0.46, 0.45, 0.94); }
        .zoom-in { animation: zoomIn 0.5s cubic-bezier(0.175, 0.885, 0.32, 1.275); }
        .flip-card { animation: flipIn 0.6s ease-out; }
        .pulse-glow { animation: pulseGlow 2s infinite; }

        @keyframes fadeIn { from { opacity: 0; } to { opacity: 1; } }
        @keyframes slideInRight { from { transform: translateX(40px); opacity: 0; } to { transform: translateX(0); opacity: 1; } }
        @keyframes zoomIn { from { transform: scale(0.85); opacity: 0; } to { transform: scale(1); opacity: 1; } }
        @keyframes flipIn { from { transform: perspective(400px) rotateY(90deg); opacity: 0; } to { transform: perspective(400px) rotateY(0deg); opacity: 1; } }
        @keyframes pulseGlow { 0% { box-shadow: 0 0 0 0 rgba(234, 179, 8, 0.7); } 70% { box-shadow: 0 0 15px 10px rgba(234, 179, 8, 0); } 100% { box-shadow: 0 0 0 0 rgba(234, 179, 8, 0); } }

        textarea::-webkit-scrollbar { width: 8px; }
        textarea::-webkit-scrollbar-track { background: #f1f1f1; border-radius: 4px; }
        textarea::-webkit-scrollbar-thumb { background: #cbd5e1; border-radius: 4px; }
        
        .no-select { user-select: none; -webkit-user-select: none; }
        
        .glass-panel {
            background: rgba(13, 27, 42, 0.88);
            backdrop-filter: blur(14px);
            border: 1px solid rgba(253, 224, 71, 0.25);
            box-shadow: 0 20px 40px 0 rgba(0, 0, 0, 0.6);
        }

        .custom-radio input[type="radio"] { display: none; }
        .custom-radio label {
            display: flex;
            align-items: center;
            padding: 1rem;
            border-radius: 0.75rem;
            border: 2px solid rgba(255, 255, 255, 0.15);
            background: rgba(255, 255, 255, 0.04);
            cursor: pointer;
            transition: all 0.2s;
            color: #f8fafc;
        }
        .custom-radio input[type="radio"]:checked + label {
            border-color: #14b8a6;
            background-color: rgba(20, 184, 166, 0.2);
            box-shadow: 0 4px 12px rgba(20, 184, 166, 0.3);
        }
        .custom-radio input[type="radio"]:disabled + label {
            cursor: not-allowed;
            opacity: 0.7;
        }
        .custom-radio input[type="radio"]:disabled:checked + label {
            border-color: #64748b;
            background-color: rgba(100, 116, 139, 0.2);
            color: #cbd5e1;
        }

        .loader-spin {
            border: 4px solid rgba(234, 179, 8, 0.3);
            border-radius: 50%;
            border-top: 4px solid #eab308;
            width: 44px;
            height: 44px;
            animation: spin 1s linear infinite;
        }
        @keyframes spin { 0% { transform: rotate(0deg); } 100% { transform: rotate(360deg); } }

        #confetti-canvas {
            position: fixed;
            top: 0; left: 0;
            width: 100%; height: 100%;
            pointer-events: none;
            z-index: 9999;
        }
    </style>
</head>
<body class="h-screen w-screen overflow-hidden flex flex-col" oncontextmenu="return false;">

    <div id="stars-container" class="absolute inset-0 overflow-hidden pointer-events-none z-0"></div>

    <div id="app-container" class="w-full h-full relative flex flex-col z-10">
        
        <!-- Global Audio & Teacher Portal Toggle -->
        <div class="absolute top-4 right-4 z-50 flex gap-3">
            <button id="btn-audio-toggle" class="bg-slate-900/80 backdrop-blur border border-amber-500/30 rounded-full px-4 py-2 shadow-lg text-gold hover:text-white transition-colors flex items-center gap-2 font-semibold text-sm" onclick="toggleAudio()">
                <i class="fas fa-volume-up text-lg" id="audio-icon"></i>
                <span id="audio-text" class="hidden sm:inline">SOUND ON</span>
            </button>
            <button id="btn-teacher-portal-link" class="bg-slate-900/80 backdrop-blur border border-amber-500/30 rounded-full px-4 py-2 shadow-lg text-slate-200 hover:text-gold transition-colors flex items-center gap-2 font-semibold text-sm" onclick="switchView('teacher-login')" title="Panel Guru">
                <i class="fas fa-chalkboard-teacher text-lg"></i>
                <span class="hidden sm:inline">Panel Guru</span>
            </button>
        </div>

        <!-- Loading View -->
        <div id="view-loading" class="view-section w-full h-full flex flex-col items-center justify-center text-white z-40 absolute inset-0 bg-gradient-to-t from-[#1c0a00] via-[#31103f] to-[#090d16]">
            <img src="https://iili.io/FvHPaku.png" alt="Logo SMP Islam Maryam Muraith" class="w-28 h-28 md:w-36 md:h-36 mb-6 zoom-in drop-shadow-[0_10px_20px_rgba(234,179,8,0.4)]" onerror="this.src='https://placehold.co/150x150/1e3a8a/ffffff?text=Logo'">
            <h2 class="text-sm md:text-base uppercase tracking-widest text-amber-300 mb-1 font-semibold">SMP ISLAM MARYAM MURAITH</h2>
            <h1 class="font-theme text-4xl md:text-6xl font-bold mb-2 text-center text-gold drop-shadow-md">FIKIH</h1>
            <p class="text-xs md:text-sm text-silver mb-8 text-center px-4">Asesmen Sumatif Tengah Semester – Kelas 8</p>
            <div class="loader-spin mb-4"></div>
            <p class="text-sm text-amber-200 animate-pulse">Menyiapkan suasana senja ujian interaktif...</p>
        </div>

        <!-- Student Login View -->
        <div id="view-login" class="view-section w-full h-full hidden flex-col items-center justify-center p-4 relative overflow-y-auto">
            <div class="absolute inset-0 bg-[url('https://www.transparenttextures.com/patterns/arabesque.png')] opacity-10 pointer-events-none"></div>
            <div class="glass-panel w-full max-w-md p-8 rounded-2xl shadow-2xl relative z-10 fade-in my-auto border border-amber-500/30">
                <div class="text-center mb-6">
                    <div class="w-16 h-16 mx-auto bg-amber-500/20 rounded-2xl flex items-center justify-center text-gold text-3xl mb-3 shadow-inner border border-amber-500/30">
                        <i class="fas fa-mosque"></i>
                    </div>
                    <h2 class="font-theme text-2xl md:text-3xl font-bold text-gold mb-1">Login Siswa</h2>
                    <p class="text-slate-300 text-sm">Pilih kelas dan namamu untuk memulai asesmen.</p>
                </div>
                
                <div class="space-y-5">
                    <div>
                        <label class="block text-sm font-semibold text-amber-200 mb-1.5"><i class="fas fa-school mr-1 text-gold"></i> Pilih Kelas</label>
                        <select id="login-class" class="w-full p-3.5 rounded-xl border-2 border-slate-700 focus:border-gold focus:ring-0 transition-colors bg-slate-900 font-medium text-white" onchange="populateStudents()">
                            <option value="">-- Pilih Kelas --</option>
                            <option value="8.1">Kelas 8.1</option>
                            <option value="8.2">Kelas 8.2</option>
                            <option value="8.3">Kelas 8.3</option>
                        </select>
                    </div>
                    <div>
                        <label class="block text-sm font-semibold text-amber-200 mb-1.5"><i class="fas fa-id-card mr-1 text-gold"></i> Nama Lengkap</label>
                        <select id="login-name" class="w-full p-3.5 rounded-xl border-2 border-slate-700 focus:border-gold focus:ring-0 transition-colors bg-slate-900 font-medium text-white disabled:bg-slate-800 disabled:cursor-not-allowed" disabled>
                            <option value="">-- Pilih Kelas Terlebih Dahulu --</option>
                        </select>
                        <p id="login-error" class="text-red-400 text-xs mt-2 font-medium hidden"><i class="fas fa-exclamation-circle mr-1"></i> Data tidak valid atau Anda telah menyelesaikan ujian.</p>
                    </div>
                    
                    <button onclick="attemptLogin()" class="w-full py-4 bg-gradient-to-r from-gold to-amber-600 hover:from-amber-600 hover:to-gold text-slate-950 font-bold rounded-xl shadow-lg transform hover:scale-[1.02] active:scale-95 transition-all flex items-center justify-center gap-2 pulse-glow text-base">
                        <i class="fas fa-rocket text-lg"></i> MULAI PETUALANGAN UJIAN
                    </button>
                </div>
            </div>
        </div>

        <!-- Teacher Login View -->
        <div id="view-teacher-login" class="view-section w-full h-full hidden flex-col items-center justify-center p-4 relative overflow-y-auto">
            <div class="glass-panel w-full max-w-md p-8 rounded-2xl shadow-2xl relative z-10 fade-in my-auto border border-amber-500/30">
                <div class="text-center mb-6">
                    <div class="w-16 h-16 mx-auto bg-amber-500/20 rounded-2xl flex items-center justify-center text-gold text-3xl mb-3 shadow-inner border border-amber-500/30">
                        <i class="fas fa-chalkboard-teacher"></i>
                    </div>
                    <h2 class="font-theme text-2xl md:text-3xl font-bold text-gold mb-1">Panel Guru Fikih</h2>
                    <p class="text-slate-300 text-sm">Autentikasi Pengawas / Guru Pengampu</p>
                </div>
                <div class="space-y-4">
                    <div>
                        <label class="block text-sm font-semibold text-amber-200 mb-1">Username</label>
                        <input type="text" id="t-username" class="w-full p-3.5 border-2 border-slate-700 bg-slate-900 text-white rounded-xl focus:border-gold" placeholder="Masukkan username...">
                    </div>
                    <div>
                        <label class="block text-sm font-semibold text-amber-200 mb-1">Password</label>
                        <input type="password" id="t-password" class="w-full p-3.5 border-2 border-slate-700 bg-slate-900 text-white rounded-xl focus:border-gold" placeholder="Masukkan password...">
                        <p id="t-login-error" class="text-red-400 text-xs mt-2 font-medium hidden"><i class="fas fa-times-circle"></i> Username atau Password salah!</p>
                    </div>
                    <button onclick="attemptTeacherLogin()" class="w-full py-3.5 bg-gradient-to-r from-amber-600 to-yellow-600 hover:from-yellow-600 hover:to-amber-600 text-slate-950 font-bold rounded-xl shadow-lg transition-all flex items-center justify-center gap-2">
                        <i class="fas fa-lock"></i> 🔐 MASUK KE PANEL GURU
                    </button>
                    <button onclick="switchView('login')" class="w-full py-3 bg-slate-800 hover:bg-slate-700 text-slate-200 font-semibold rounded-xl transition-all flex items-center justify-center gap-2 text-sm">
                        <i class="fas fa-home"></i> Kembali ke Halaman Utama
                    </button>
                </div>
            </div>
        </div>

        <!-- Exam Briefing View -->
        <div id="view-briefing" class="view-section w-full h-full hidden flex-col items-center justify-center p-4 relative overflow-y-auto">
            <div class="glass-panel w-full max-w-2xl p-6 md:p-8 rounded-2xl shadow-xl zoom-in my-auto border border-amber-500/30">
                <div class="flex items-center gap-4 mb-6 border-b pb-4 border-slate-700">
                    <div class="w-14 h-14 rounded-2xl bg-amber-500/20 flex items-center justify-center text-gold text-3xl shrink-0 border border-amber-500/30">
                        <i class="fas fa-bullseye"></i>
                    </div>
                    <div>
                        <h2 class="font-theme text-2xl font-bold text-gold">🎯 PETUNJUK & MISI UJIAN</h2>
                        <p class="text-amber-200 text-sm font-semibold" id="briefing-student-name">Nama Siswa</p>
                    </div>
                </div>
                
                <div class="space-y-4 text-slate-200 mb-8 text-sm md:text-base">
                    <div class="grid grid-cols-2 gap-3">
                        <div class="bg-slate-900/60 p-3.5 rounded-xl border border-slate-700 flex items-center gap-3">
                            <i class="fas fa-list-ol text-gold text-xl"></i>
                            <div><p class="text-xs text-slate-400 font-semibold">Total Soal</p><p class="font-bold text-white">30 Soal (25 PG, 5 Esai)</p></div>
                        </div>
                        <div class="bg-slate-900/60 p-3.5 rounded-xl border border-slate-700 flex items-center gap-3">
                            <i class="fas fa-stopwatch text-gold text-xl"></i>
                            <div><p class="text-xs text-slate-400 font-semibold">Durasi Misi</p><p class="font-bold text-white">60 Menit</p></div>
                        </div>
                    </div>
                    
                    <ul class="space-y-2.5 bg-slate-900/80 p-4 rounded-xl border border-amber-500/20 text-xs md:text-sm">
                        <li class="flex gap-2.5 items-start"><i class="fas fa-check-circle text-gold mt-0.5"></i> <span>Pilihan ganda yang telah dijawab <b>tidak dapat diubah</b> setelah berpindah dari soal tersebut.</span></li>
                        <li class="flex gap-2.5 items-start"><i class="fas fa-check-circle text-gold mt-0.5"></i> <span>Jawaban esai (26-30) dapat diedit dan diubah sewaktu-waktu sampai Anda menekan tombol <b>Submit Akhir</b>.</span></li>
                        <li class="flex gap-2.5 items-start"><i class="fas fa-shield-alt text-red-400 mt-0.5"></i> <span><b>Sistem Anti-Cheating Aktif:</b> Dilarang pindah tab, keluar halaman, membuka inspect element, atau melakukan copy-paste.</span></li>
                        <li class="flex gap-2.5 items-start"><i class="fas fa-exclamation-triangle text-red-400 mt-0.5"></i> <span>Maksimal toleransi pelanggaran: <b>3 kali</b>. Pelanggaran batas akan langsung mendiskualifikasi ujian.</span></li>
                    </ul>
                </div>
                
                <div class="space-y-3">
                    <button onclick="startExam()" class="w-full py-4 bg-gradient-to-r from-gold to-amber-600 hover:from-amber-600 hover:to-gold text-slate-950 font-bold rounded-xl shadow-lg transform hover:-translate-y-0.5 transition-all flex items-center justify-center gap-2 text-base">
                        <i class="fas fa-lock-open"></i> 🔐 SAYA SIAP, MULAI UJIAN
                    </button>
                    <button onclick="switchView('login')" class="w-full py-3 bg-slate-800 hover:bg-slate-700 text-slate-200 font-semibold rounded-xl transition-all flex items-center justify-center gap-2 text-sm">
                        <i class="fas fa-home"></i> Kembali ke Halaman Utama
                    </button>
                </div>
            </div>
        </div>

        <!-- Exam Active View -->
        <div id="view-exam" class="view-section w-full h-full hidden flex-col bg-slate-950 overflow-hidden">
            <!-- Exam Header -->
            <header class="bg-slate-900 text-white p-3 md:p-4 shadow-lg flex justify-between items-center z-20 shrink-0 border-b border-amber-500/20">
                <div class="flex items-center gap-3">
                    <div class="w-10 h-10 rounded-xl bg-amber-500/20 flex items-center justify-center text-gold text-lg shadow-inner border border-amber-500/30">
                        <i class="fas fa-mosque"></i>
                    </div>
                    <div>
                        <h1 class="font-theme font-bold text-base md:text-lg leading-tight text-gold">FIKIH KELAS 8</h1>
                        <p class="text-xs text-slate-300 truncate max-w-[140px] md:max-w-xs font-medium" id="exam-header-name">Nama Siswa - Kelas</p>
                    </div>
                </div>
                
                <div class="flex items-center gap-4">
                    <div class="flex items-center gap-2 text-gold font-bold text-base md:text-xl bg-black/40 px-3.5 py-1.5 rounded-xl border border-gold/30">
                        <i class="fas fa-stopwatch animate-pulse"></i>
                        <span id="exam-timer">59:59</span>
                    </div>
                    <div class="hidden sm:flex flex-col text-right text-xs text-slate-400">
                        <span>Peringatan:</span>
                        <span class="font-bold text-red-400" id="exam-violation-count">0 / 3</span>
                    </div>
                </div>
            </header>

            <!-- Progress Bar -->
            <div class="w-full bg-slate-800 h-2 shrink-0">
                <div id="exam-progress-bar" class="bg-gradient-to-r from-amber-500 to-gold h-2 transition-all duration-300" style="width: 0%"></div>
            </div>

            <!-- Main Question & Sidebar Container -->
            <div class="flex-1 overflow-hidden flex flex-col md:flex-row relative">
                
                <!-- Question Area -->
                <div class="flex-1 h-full overflow-y-auto p-4 md:p-8" id="question-scroll-area">
                    <div class="max-w-3xl mx-auto">
                        <div class="flex justify-between items-end mb-4">
                            <span class="bg-amber-500/10 text-amber-300 font-bold px-3.5 py-1 rounded-full text-xs md:text-sm flex items-center gap-2 border border-amber-500/30">
                                <i class="fas fa-flag"></i> <span id="question-indicator">SOAL 01/30</span>
                            </span>
                            <span class="text-xs font-bold text-slate-400 uppercase tracking-wider" id="question-type-badge">Pilihan Ganda</span>
                        </div>

                        <!-- Question Box with Animations -->
                        <div id="question-container" class="glass-panel p-5 md:p-8 rounded-2xl shadow-xl mb-6 min-h-[320px] slide-in-right relative border border-amber-500/20">
                            <div class="flex items-start gap-3 mb-6">
                                <button onclick="readQuestionAudio()" class="mt-1 w-10 h-10 rounded-xl bg-slate-800 hover:bg-gold hover:text-slate-950 text-amber-300 transition-colors flex items-center justify-center shrink-0 shadow-sm border border-amber-500/30" title="Bacakan Soal">
                                    <i class="fas fa-volume-up text-lg"></i>
                                </button>
                                <h3 id="question-text" class="text-base md:text-xl font-medium text-slate-100 leading-relaxed no-select">
                                    Memuat soal...
                                </h3>
                            </div>
                            
                            <!-- Options Container for MCQ -->
                            <div id="options-container" class="space-y-3 mt-6"></div>
                            
                            <!-- Essay Container for Esai (26-30) -->
                            <div id="essay-container" class="hidden mt-6">
                                <label class="block text-xs font-semibold text-amber-300 mb-2">JAWABAN ESAI (Otomatis tersimpan saat Anda mengetik):</label>
                                <textarea id="essay-input" class="w-full h-44 p-4 border-2 border-slate-700 rounded-xl focus:border-gold focus:ring-0 resize-none transition-colors text-white bg-slate-900" placeholder="Ketik jawaban esai Anda di sini..." oninput="debouncedSaveEssay()"></textarea>
                            </div>
                            
                            <!-- Locked Answer Warning -->
                            <div id="locked-warning" class="hidden mt-4 bg-amber-950/60 border border-amber-500/40 text-amber-200 p-3.5 rounded-xl text-xs md:text-sm flex items-center gap-2">
                                <i class="fas fa-lock text-gold"></i> Jawaban pilihan ganda ini telah dikunci dan tidak dapat diubah kembali.
                            </div>
                        </div>

                        <!-- Navigation Buttons -->
                        <div class="flex flex-wrap justify-between gap-3 mb-12">
                            <button onclick="navigateQuestion('prev')" id="btn-prev" class="px-5 py-3 bg-slate-900 border border-slate-700 text-slate-200 rounded-xl hover:bg-slate-800 font-semibold transition-colors flex items-center gap-2 disabled:opacity-40 disabled:cursor-not-allowed shadow-sm">
                                <i class="fas fa-chevron-left"></i> SEBELUMNYA
                            </button>
                            
                            <div class="flex gap-2">
                                <button onclick="skipQuestion()" id="btn-skip" class="px-5 py-3 bg-slate-800 text-slate-300 rounded-xl hover:bg-slate-700 font-semibold transition-colors text-sm">
                                    LEWATI
                                </button>
                                <button onclick="navigateQuestion('next')" id="btn-next" class="px-6 py-3 bg-gradient-to-r from-amber-600 to-gold hover:from-gold hover:to-amber-600 text-slate-950 rounded-xl shadow-md font-bold transition-colors flex items-center gap-2">
                                    BERIKUTNYA <i class="fas fa-chevron-right"></i>
                                </button>
                            </div>
                            
                            <button onclick="checkUnansweredAndSubmit()" id="btn-submit-exam" class="hidden px-8 py-3 bg-gradient-to-r from-gold to-yellow-500 hover:from-yellow-600 hover:to-gold text-slate-950 rounded-xl shadow-lg font-bold transition-all items-center gap-2">
                                <i class="fas fa-check-circle"></i> SUBMIT AKHIR
                            </button>
                        </div>
                    </div>
                </div>

                <!-- Question Navigation Palette Sidebar -->
                <div class="w-full md:w-80 bg-slate-900 border-l border-slate-800 flex flex-col shrink-0 absolute md:relative z-30 h-full transform translate-x-full md:translate-x-0 transition-transform duration-300 shadow-2xl md:shadow-none" id="palette-sidebar">
                    <div class="p-4 bg-slate-950 border-b border-slate-800 flex justify-between items-center">
                        <h3 class="font-bold text-amber-300 flex items-center gap-2"><i class="fas fa-th-large text-gold"></i> Peta Misi Soal</h3>
                        <button class="md:hidden text-slate-400 hover:text-white" onclick="togglePalette()"><i class="fas fa-times text-xl"></i></button>
                    </div>
                    <div class="p-4 overflow-y-auto flex-1 space-y-4">
                        <div>
                            <div class="mb-2 text-xs font-bold text-slate-400 uppercase tracking-wider">Pilihan Ganda (1 - 25)</div>
                            <div class="grid grid-cols-5 gap-2" id="palette-grid-pg"></div>
                        </div>
                        <div>
                            <div class="mb-2 text-xs font-bold text-slate-400 uppercase tracking-wider">Esai Final Mission (26 - 30)</div>
                            <div class="grid grid-cols-5 gap-2" id="palette-grid-essay"></div>
                        </div>
                        
                        <div class="mt-6 bg-slate-950/80 p-3.5 rounded-xl border border-slate-800 text-xs space-y-2 text-slate-300">
                            <div class="flex items-center gap-2"><div class="w-3.5 h-3.5 rounded-md bg-slate-800 border border-slate-700"></div> Kosong / Belum Dijawab</div>
                            <div class="flex items-center gap-2"><div class="w-3.5 h-3.5 rounded-md bg-amber-600"></div> Terjawab & Terkunci (PG)</div>
                            <div class="flex items-center gap-2"><div class="w-3.5 h-3.5 rounded-md bg-gold"></div> Terisi (Esai)</div>
                            <div class="flex items-center gap-2"><div class="w-3.5 h-3.5 rounded-md bg-indigo-600"></div> Soal Aktif Saat Ini</div>
                        </div>
                    </div>
                </div>
            </div>
            
            <button class="md:hidden absolute bottom-5 right-5 bg-gradient-to-r from-amber-600 to-gold text-slate-950 w-14 h-14 rounded-full shadow-2xl flex items-center justify-center z-20 text-2xl border-2 border-gold font-bold" onclick="togglePalette()">
                <i class="fas fa-layer-group"></i>
            </button>
        </div>

        <!-- Result View -->
        <div id="view-result" class="view-section w-full h-full hidden flex-col items-center justify-center p-4 relative overflow-y-auto">
            <canvas id="confetti-canvas"></canvas>
            <div class="glass-panel w-full max-w-lg p-6 md:p-8 rounded-2xl shadow-2xl relative z-10 text-center zoom-in my-auto border border-amber-500/30">
                <div class="w-20 h-20 mx-auto bg-amber-500/20 text-gold rounded-full flex items-center justify-center text-4xl mb-4 shadow-inner border border-amber-500/40">
                    <i class="fas fa-award"></i>
                </div>
                <h2 class="font-theme text-3xl font-bold text-gold mb-1">🎉 MISI SELESAI!</h2>
                <p class="text-amber-200 text-sm mb-6 font-semibold" id="result-name">Nama Siswa - Kelas</p>
                
                <div class="bg-slate-900/90 rounded-2xl p-6 shadow-sm mb-6 border border-slate-800 text-left">
                    <div class="text-center mb-4">
                        <div class="text-5xl font-bold text-gold mb-1" id="result-score">0</div>
                        <p class="text-xs text-slate-400 uppercase tracking-widest font-bold">NILAI AKHIR</p>
                    </div>
                    
                    <div class="grid grid-cols-2 gap-3 pt-4 border-t border-slate-800">
                        <div class="bg-slate-950 p-3 rounded-xl border border-slate-800"><p class="text-xs text-slate-400 font-medium">Nilai PG (Max 75)</p><p class="font-bold text-white text-base" id="result-pg-score">0</p></div>
                        <div class="bg-slate-950 p-3 rounded-xl border border-slate-800"><p class="text-xs text-slate-400 font-medium">Nilai Esai (Max 25)</p><p class="font-bold text-white text-base" id="result-essay-score">0</p></div>
                        <div class="bg-green-950/60 p-3 rounded-xl border border-green-800/50 text-green-300"><p class="text-xs opacity-80 font-medium">Jawaban Benar</p><p class="font-bold text-base" id="result-correct">0</p></div>
                        <div class="bg-red-950/60 p-3 rounded-xl border border-red-800/50 text-red-300"><p class="text-xs opacity-80 font-medium">Jawaban Salah</p><p class="font-bold text-base" id="result-wrong">0</p></div>
                    </div>
                </div>
                
                <div class="mb-6 p-4 rounded-xl font-bold text-base shadow-sm" id="result-status-banner"></div>
                
                <p class="text-xs md:text-sm text-slate-300 italic mb-6 bg-slate-900/80 p-3 rounded-xl border border-slate-800" id="result-feedback">Feedback edukatif...</p>
                
                <div class="text-xs text-amber-200 font-medium flex items-center justify-center gap-1 mb-6">
                    <i class="fas fa-stopwatch text-gold"></i> Durasi Pengerjaan: <span id="result-duration">0 menit</span>
                </div>

                <div class="space-y-3">
                    <button onclick="switchView('login')" class="w-full py-3.5 bg-gradient-to-r from-amber-600 to-gold hover:from-gold hover:to-amber-600 text-slate-950 font-bold rounded-xl shadow-md transition-all flex items-center justify-center gap-2 text-sm">
                        <i class="fas fa-home"></i> Kembali ke Halaman Utama
                    </button>
                </div>
            </div>
        </div>

        <!-- Teacher Panel View -->
        <div id="view-teacher-panel" class="view-section w-full h-full hidden flex-col bg-slate-950 overflow-hidden">
            <!-- Navbar Guru -->
            <nav class="bg-slate-900 text-white p-4 flex justify-between items-center shadow-md z-10 shrink-0 border-b border-amber-500/20">
                <div class="flex items-center gap-3">
                    <i class="fas fa-chalkboard-teacher text-2xl text-gold"></i>
                    <h1 class="font-theme font-bold text-lg md:text-xl text-gold">DASHBOARD GURU - FIKIH</h1>
                </div>
                <div class="flex items-center gap-2 md:gap-3">
                    <button onclick="openKkmModal()" class="text-xs md:text-sm bg-slate-800 hover:bg-slate-700 border border-amber-500/30 px-3 py-2 rounded-xl transition-colors flex items-center gap-1.5" title="Atur KKM">
                        <i class="fas fa-cog text-gold"></i> KKM: <span id="display-kkm" class="font-bold text-gold">73</span>
                    </button>
                    <button onclick="openSheetsModal()" class="text-xs md:text-sm bg-purple-700 hover:bg-purple-600 px-3 py-2 rounded-xl transition-colors shadow flex items-center gap-1.5 font-medium text-white" title="Google Sheets Sync">
                        <i class="fas fa-link"></i> <span class="hidden md:inline">Google Sheets Sync</span>
                    </button>
                    <button onclick="exportToCSV()" class="text-xs md:text-sm bg-emerald-700 hover:bg-emerald-600 px-3 py-2 rounded-xl transition-colors shadow flex items-center gap-1.5 font-medium text-white">
                        <i class="fas fa-file-excel"></i> <span class="hidden md:inline">Export CSV</span>
                    </button>
                    <a href="https://docs.google.com/spreadsheets/d/1oBuh_hKvedWdiVDB6a4pwk9oFRIAihcmYD6bCa1xjyM/edit?usp=sharing" target="_blank" class="text-xs md:text-sm bg-blue-700 hover:bg-blue-600 px-3 py-2 rounded-xl transition-colors shadow flex items-center gap-1.5 font-medium text-white" title="Buka Spreadsheet">
                        <i class="fas fa-external-link-alt"></i> <span class="hidden md:inline">Buka Sheet</span>
                    </a>
                    <button onclick="logoutTeacher()" class="text-red-400 hover:text-red-300 p-2" title="Keluar">
                        <i class="fas fa-sign-out-alt text-xl"></i>
                    </button>
                </div>
            </nav>

            <div class="flex-1 overflow-y-auto p-4 md:p-6 flex flex-col gap-6 bg-slate-950">
                <!-- Stat Cards -->
                <div class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-6 gap-3 md:gap-4">
                    <div class="bg-slate-900 p-4 rounded-2xl shadow-sm border-l-4 border-blue-500 border-y border-r border-slate-800"><p class="text-xs text-slate-400 font-semibold">Total Peserta</p><p class="text-2xl font-bold text-white" id="stat-total">0</p></div>
                    <div class="bg-slate-900 p-4 rounded-2xl shadow-sm border-l-4 border-amber-500 border-y border-r border-slate-800"><p class="text-xs text-slate-400 font-semibold">Rata-rata Nilai</p><p class="text-2xl font-bold text-white" id="stat-avg">0</p></div>
                    <div class="bg-slate-900 p-4 rounded-2xl shadow-sm border-l-4 border-green-500 border-y border-r border-slate-800"><p class="text-xs text-slate-400 font-semibold">Nilai Tertinggi</p><p class="text-2xl font-bold text-white" id="stat-max">0</p></div>
                    <div class="bg-slate-900 p-4 rounded-2xl shadow-sm border-l-4 border-red-500 border-y border-r border-slate-800"><p class="text-xs text-slate-400 font-semibold">Nilai Terendah</p><p class="text-2xl font-bold text-white" id="stat-min">0</p></div>
                    <div class="bg-slate-900 p-4 rounded-2xl shadow-sm border-l-4 border-gold border-y border-r border-slate-800"><p class="text-xs text-slate-400 font-semibold">Ketuntasan</p><p class="text-2xl font-bold text-white" id="stat-pass">0%</p></div>
                    <div class="bg-slate-900 p-4 rounded-2xl shadow-sm border-l-4 border-orange-500 border-y border-r border-slate-800"><p class="text-xs text-slate-400 font-semibold">Terindikasi Pelanggaran</p><p class="text-2xl font-bold text-white" id="stat-viol">0</p></div>
                </div>

                <!-- Automated Analysis Summary Box -->
                <div class="bg-amber-950/40 border border-amber-500/30 rounded-2xl p-4 text-sm text-amber-200 shadow-sm flex items-start gap-3">
                    <i class="fas fa-lightbulb text-gold text-2xl mt-0.5 shrink-0"></i>
                    <div>
                        <h4 class="font-bold mb-1 text-gold">Analisis Hasil Otomatis & Rekomendasi Guru</h4>
                        <p id="system-analysis-text" class="text-xs md:text-sm leading-relaxed text-slate-300">Mengumpulkan data hasil ujian secara real-time untuk analisis komprehensif...</p>
                    </div>
                </div>

                <!-- Filters & Table Container -->
                <div class="bg-slate-900 rounded-2xl shadow-sm flex-1 flex flex-col overflow-hidden border border-slate-800">
                    <div class="p-4 border-b border-slate-800 bg-slate-950 flex flex-wrap gap-3 items-end">
                        <div>
                            <label class="block text-xs font-semibold text-slate-400 mb-1">Kelas</label>
                            <select id="filter-class" class="p-2 text-sm border border-slate-700 rounded-xl bg-slate-900 text-white w-28 font-medium" onchange="applyFilters()">
                                <option value="all">Semua</option><option value="8.1">8.1</option><option value="8.2">8.2</option><option value="8.3">8.3</option>
                            </select>
                        </div>
                        <div>
                            <label class="block text-xs font-semibold text-slate-400 mb-1">Status</label>
                            <select id="filter-status" class="p-2 text-sm border border-slate-700 rounded-xl bg-slate-900 text-white w-36 font-medium" onchange="applyFilters()">
                                <option value="all">Semua</option><option value="TUNTAS">Tuntas</option><option value="BELUM TUNTAS">Belum Tuntas</option><option value="DISKUALIFIKASI">Diskualifikasi</option>
                            </select>
                        </div>
                        <div>
                            <label class="block text-xs font-semibold text-slate-400 mb-1">Cari Nama Siswa</label>
                            <input type="text" id="filter-name" placeholder="Ketik nama..." class="p-2 text-sm border border-slate-700 rounded-xl bg-slate-900 text-white w-52 font-medium" onkeyup="applyFilters()">
                        </div>
                        <div class="flex-1 flex justify-end gap-2">
                            <button onclick="sortData('score')" class="px-3.5 py-2 bg-slate-800 border border-slate-700 rounded-xl text-sm text-slate-200 hover:bg-slate-700 font-medium shadow-sm flex items-center gap-1.5"><i class="fas fa-sort-numeric-down text-gold"></i> Urutkan Nilai</button>
                            <button onclick="fetchResults()" class="px-3.5 py-2 bg-amber-600 text-slate-950 font-bold rounded-xl text-sm hover:bg-amber-500 shadow-sm flex items-center gap-1.5"><i class="fas fa-sync-alt"></i> Refresh</button>
                        </div>
                    </div>
                    
                    <div class="flex-1 overflow-auto">
                        <table class="w-full text-left text-sm whitespace-nowrap">
                            <thead class="bg-slate-950 text-slate-400 uppercase text-xs sticky top-0 font-bold border-b border-slate-800">
                                <tr>
                                    <th class="p-3.5">No</th>
                                    <th class="p-3.5">Nama</th>
                                    <th class="p-3.5">Kelas</th>
                                    <th class="p-3.5">Tanggal</th>
                                    <th class="p-3.5 text-center">Nilai</th>
                                    <th class="p-3.5 text-center">Waktu</th>
                                    <th class="p-3.5 text-center">Status</th>
                                    <th class="p-3.5 text-center">Aksi</th>
                                </tr>
                            </thead>
                            <tbody id="results-table-body" class="divide-y divide-slate-800/60 text-slate-200"></tbody>
                        </table>
                    </div>
                </div>
            </div>
        </div>

        <!-- Google Sheets Sync Modal -->
        <div id="sheets-modal-overlay" class="fixed inset-0 bg-slate-950/80 backdrop-blur-sm z-50 hidden flex items-center justify-center p-4">
            <div class="glass-panel rounded-2xl p-6 md:p-8 max-w-xl w-full shadow-2xl zoom-in max-h-[90vh] overflow-y-auto border border-amber-500/30">
                <h3 class="text-xl font-bold text-gold mb-3 flex items-center gap-2"><i class="fas fa-link text-purple-400"></i> Integrasi Google Sheets & Apps Script</h3>
                <p class="text-xs text-slate-300 mb-4 leading-relaxed">
                    Data siswa secara otomatis tersimpan di database cloud real-time. Untuk mencatat baris baru secara otomatis langsung ke spreadsheet resmi <b>SMP Islam Maryam Muraith</b>, Anda dapat memasukkan URL Web App Google Apps Script di bawah ini:
                </p>
                <div class="mb-4">
                    <label class="block text-xs font-semibold text-amber-200 mb-1">Link Google Spreadsheet Resmi</label>
                    <input type="text" readonly value="https://docs.google.com/spreadsheets/d/1oBuh_hKvedWdiVDB6a4pwk9oFRIAihcmYD6bCa1xjyM/edit?usp=sharing" class="w-full p-3 bg-slate-900 border border-slate-700 rounded-xl text-xs text-amber-300 font-mono select-all">
                </div>
                <div class="mb-4">
                    <label class="block text-xs font-semibold text-amber-200 mb-1">Google Apps Script Web App URL</label>
                    <input type="text" id="input-script-url" placeholder="https://script.google.com/macros/s/.../exec" class="w-full p-3 bg-slate-900 border-2 border-slate-700 rounded-xl text-xs font-mono text-white focus:border-purple-500">
                    <p class="text-[11px] text-slate-400 mt-1">Kosongkan jika hanya menggunakan sinkronisasi database cloud utama dan ekspor CSV.</p>
                </div>
                <div class="flex gap-3 justify-end">
                    <button onclick="closeSheetsModal()" class="px-4 py-2.5 bg-slate-800 text-slate-300 rounded-xl font-semibold hover:bg-slate-700 text-sm">Tutup</button>
                    <button onclick="syncToSheets()" class="px-4 py-2.5 bg-purple-600 text-white rounded-xl font-semibold hover:bg-purple-500 text-sm flex items-center gap-2"><i class="fas fa-save"></i> Simpan & Buka Spreadsheet</button>
                </div>
            </div>
        </div>

        <!-- Custom Modal Overlay -->
        <div id="custom-modal-overlay" class="fixed inset-0 bg-slate-950/80 backdrop-blur-sm z-50 hidden flex items-center justify-center p-4">
            <div id="custom-modal" class="glass-panel rounded-2xl p-6 md:p-8 max-w-md w-full shadow-2xl transform scale-95 transition-transform duration-200 border border-amber-500/30">
                <div id="modal-icon" class="w-16 h-16 mx-auto rounded-full bg-red-950/80 text-red-400 flex items-center justify-center text-3xl mb-4 border border-red-800/50">
                    <i class="fas fa-exclamation-triangle"></i>
                </div>
                <h3 id="modal-title" class="text-xl font-bold text-center text-gold mb-2">Peringatan!</h3>
                <p id="modal-message" class="text-slate-300 text-center mb-6 text-sm leading-relaxed">Pesan modal disini.</p>
                
                <div id="modal-pin-area" class="hidden mb-6">
                    <label class="block text-xs font-bold text-amber-300 mb-2 text-center">MASUKKAN PIN PENGAWAS</label>
                    <input type="password" id="modal-pin-input" class="w-full text-center p-3 text-2xl tracking-widest border-2 border-slate-700 bg-slate-900 rounded-xl text-white focus:border-red-500 focus:outline-none font-bold" maxlength="4" placeholder="••••">
                    <p id="modal-pin-error" class="text-red-400 text-xs text-center mt-2 font-semibold hidden"><i class="fas fa-times-circle"></i> PIN Pengawas Salah! (Gunakan 1414)</p>
                </div>

                <div id="modal-buttons" class="flex gap-3 justify-center"></div>
            </div>
        </div>
        
        <!-- KKM Setting Modal -->
        <div id="kkm-modal-overlay" class="fixed inset-0 bg-slate-950/80 backdrop-blur-sm z-50 hidden flex items-center justify-center p-4">
            <div class="glass-panel rounded-2xl p-6 max-w-sm w-full shadow-2xl zoom-in border border-amber-500/30">
                <h3 class="text-lg font-bold text-gold mb-4 border-b border-slate-800 pb-3 flex items-center gap-2"><i class="fas fa-cog text-gold"></i> Pengaturan KKM</h3>
                <div class="mb-6">
                    <label class="block text-sm font-semibold text-amber-200 mb-2">Batas Nilai Tuntas (0 - 100)</label>
                    <input type="number" id="input-kkm-setting" class="w-full p-3.5 border-2 border-slate-700 bg-slate-900 text-white rounded-xl text-xl font-bold text-center focus:border-gold" min="0" max="100">
                    <p class="text-xs text-slate-400 mt-2">Nilai peserta ≥ batas ini akan otomatis berstatus <b>TUNTAS</b>.</p>
                </div>
                <div class="flex gap-3 justify-end">
                    <button onclick="closeKkmModal()" class="px-4 py-2.5 bg-slate-800 text-slate-300 rounded-xl font-semibold hover:bg-slate-700 text-sm">Batal</button>
                    <button onclick="saveKkmSetting()" class="px-4 py-2.5 bg-gradient-to-r from-amber-600 to-gold text-slate-950 font-bold rounded-xl shadow-sm text-sm">Simpan</button>
                </div>
            </div>
        </div>
        
        <!-- Student Detail Modal for Teacher -->
        <div id="detail-modal-overlay" class="fixed inset-0 bg-slate-950/80 backdrop-blur-sm z-50 hidden flex items-center justify-center p-4">
            <div class="glass-panel rounded-2xl p-6 md:p-8 max-w-2xl w-full max-h-[90vh] overflow-y-auto shadow-2xl zoom-in relative border border-amber-500/30 text-slate-200">
                <button onclick="closeDetailModal()" class="absolute top-4 right-4 text-slate-400 hover:text-red-400 text-2xl"><i class="fas fa-times"></i></button>
                <h3 class="text-xl font-bold text-gold mb-4 border-b border-slate-800 pb-3 flex items-center gap-2"><i class="fas fa-user-graduate text-gold"></i> Detail Hasil Ujian Siswa</h3>
                <div id="detail-content" class="space-y-4"></div>
            </div>
        </div>

    </div>

    <script type="module">
        import { initializeApp } from "https://www.gstatic.com/firebasejs/11.6.1/firebase-app.js";
        import { getAuth, signInAnonymously, signInWithCustomToken } from "https://www.gstatic.com/firebasejs/11.6.1/firebase-auth.js";
        import { getFirestore, doc, setDoc, getDoc, collection, onSnapshot, serverTimestamp } from "https://www.gstatic.com/firebasejs/11.6.1/firebase-firestore.js";

        // Generate Twinkling Stars dynamically
        function createStars() {
            const container = document.getElementById('stars-container');
            if(!container) return;
            for(let i = 0; i < 70; i++) {
                const star = document.createElement('div');
                star.className = 'star';
                star.style.width = Math.random() * 3 + 1 + 'px';
                star.style.height = star.style.width;
                star.style.top = Math.random() * 70 + '%';
                star.style.left = Math.random() * 100 + '%';
                star.style.animationDelay = (Math.random() * 3) + 's';
                container.appendChild(star);
            }
        }
        createStars();

        const appId = typeof __app_id !== 'undefined' ? __app_id : 'smp-maryam-fiqih-sts-01';
        let firebaseConfig = {};
        try {
            firebaseConfig = typeof __firebase_config !== 'undefined' ? JSON.parse(__firebase_config) : { projectId: "dummy" };
        } catch(e) { console.warn("Using offline mock storage."); }

        let app, db, auth, userId;
        const resultsCollectionPath = `artifacts/${appId}/public/data/exam_results`;
        const settingsCollectionPath = `artifacts/${appId}/public/data/exam_settings`;
        let isFirebaseActive = false;

        async function initFirebase() {
            try {
                if(!firebaseConfig.projectId || firebaseConfig.projectId === "dummy") return;
                app = initializeApp(firebaseConfig);
                db = getFirestore(app);
                auth = getAuth(app);
                
                const token = typeof __initial_auth_token !== 'undefined' ? __initial_auth_token : null;
                if (token) {
                    await signInWithCustomToken(auth, token);
                } else {
                    await signInAnonymously(auth);
                }
                userId = auth.currentUser.uid;
                isFirebaseActive = true;
                console.log("Firebase initialized successfully. UID:", userId);
            } catch (error) {
                console.warn("Running in robust local storage mode:", error);
            }
        }

        // --- STUDENTS DATA LIST (65 Students) ---
        const STUDENTS = {
            "8.1": [
                "Abid Aqila Pranaja", "Adib Naufal Abiyyu", "Agung Kurniawan Syahputra", "Aidil Arif", 
                "Andi Firmansyah", "Aqilla Sadewa Yudistira", "Bima Dwi Cahya", "Cakra Andika", 
                "Dhafin Tito Abdillah", "Dheren Abdul Rahman", "Faezya Hamiz Khan", "Hafiz Tristan Alvaro", 
                "Hendra Saputra", "M Galih Wicaksono", "M Zimi Al Saputra", "Muhammad Farid", 
                "Nichzar Bagus Kusuma", "Zaki Al Musyafik"
            ],
            "8.2": [
                "Abyan Nandana", "Afif Ibnu Ansyori", "Assani Ramadhan Wijaya", "Azzam Benzema", 
                "Chandra Ulil Rasyido", "Dyandra Ramadhanish Tauladani", "Dzacky nayotama", "Fakhri Maulana", 
                "Hanan Nafi", "Khaisan alfariza", "M Fathan Kartula", "M.Allbi Galang Alamsyah", 
                "M.Rizky Fadhillah", "Muhamad Farid", "Muhammad Nur Fahmi Ramadhan", "Muhammad Zoando Alhafiz", 
                "Rafif Qais Adikara", "Ramdhani Koswara"
            ],
            "8.3": [
                "ACHILA ANATSYA INDRIYANI", "AFILA FATIN ARISTA", "AFIQA CLARESTA Q", "ALIA SYIFA HUMAIRO", 
                "Altanovela Yuriezha Brilliansyah", "AMANNATUZ ZAHRA", "Amiirah Izdihaar", "Aqila Putri Sharapova", 
                "ARBELTA ALESHA FAJRI", "Atifa Raykhatul Jannah", "AULIA AZKA ANNASYABILA", "AZAHRA SHILLA SOLEHA", 
                "DINDA FIONALIA", "Esa Adhwa Roselani", "FAJRA NADA NADIFA", "Fiorenzha Syaza Dhiskara Putri", 
                "ICA OKTAVIA MARTA", "Ismiyati Nuridah", "KHANZA ZARRA NABILA", "MIKHAYLA AFYA ZAFARANI", 
                "MUTIA SARAH AZ ZAHRAH", "Najwa Zahra Artalaou", "NATASHA ALYA DISTHI", "NAYLA ROSA MIRANDA", 
                "NEISYA MIKHAYLA FADRI", "Nisrina Zahirah Putri Al Kamal", "PAMELA ELYSIA MASHUMI", "RAHMAH HUMAIRA", 
                "YOLLA ZAHRA KINANTI"
            ]
        };

        // --- COMPLETE FIQH QUESTION BANK (25 MCQ + 5 Essay) ---
        const QUESTIONS = [
            { type: 'pg', text: "Sujud sahwi dilakukan karena …", options: ["Lupa makan", "Lupa jumlah rakaat shalat", "Lupa membaca doa makan", "Lupa membaca hamdalah setelah bersin"], answer: 1 },
            { type: 'pg', text: "Jumlah sujud sahwi adalah …", options: ["1 kali", "2 kali", "3 kali", "4 kali"], answer: 1 },
            { type: 'pg', text: "Sujud sahwi dilakukan pada …", options: ["Awal shalat", "Tengah shalat", "Akhir shalat sebelum salam", "Setelah membaca Al-Fatihah"], answer: 2 },
            { type: 'pg', text: "Jika seseorang shalat lupa membaca tahiyat awal, maka ia harus …", options: ["Mengulang shalat dari awal", "Membaca tahiyat awal di rakaat berikutnya", "Mengganti dengan doa lain", "Melakukan sujud sahwi"], answer: 3 },
            { type: 'pg', text: "Zakat fitrah dibayarkan pada …", options: ["Bulan Ramadhan hingga sebelum shalat Id", "Setiap hari Jumat", "Awal Muharram", "Setiap bulan sekali"], answer: 0 },
            { type: 'pg', text: "Besarnya zakat fitrah adalah …", options: ["1 sha’ makanan pokok (± 2,5 kg beras)", "1 kg beras", "3 liter minyak", "½ dinar emas"], answer: 0 },
            { type: 'pg', text: "Orang yang wajib mengeluarkan zakat disebut …", options: ["Mustahik", "Muzakki", "Fakir", "Gharim"], answer: 1 },
            { type: 'pg', text: "Sujud yang dilakukan sebagai tanda terimakasih kepada Allah swt. atas karunia-Nya disebut sujud....", options: ["Sahwi", "Tilawah", "Syukur", "Salat"], answer: 2 },
            { type: 'pg', text: "Sujud yang dilakukan ketika membaca atau mendengar ayat sajdah dilakukan sebanyak…", options: ["1 kali", "3 kali", "2 kali", "4 kali"], answer: 0 },
            { type: 'pg', text: "Di salah satu wilayah terjadi musibah banjir. Kebetulan saudara Bu Anita selamat dari musibah tersebut. Bu Anita kemudian melakukan sujud...", options: ["Rukun", "Sahwi", "Tilawah", "Syukur"], answer: 3 },
            { type: 'pg', text: "Berikut ini yang bukan termasuk syarat melakukan sujud tilawah adalah...", options: ["Niat melakukan sujud tilawah", "Setelah membaca ayat sajdah", "Setelah mendengar ayat sajdah", "Suci dari hadats dan najis"], answer: 3 },
            { type: 'pg', text: "Pernyataan penyebab untuk melaksanakan sujud sahwi: 1) Lupa kelebihan rakaat śalat, 2) Mendapatkan nikmat, 3) Mendengarkan ayat sajdah, 4) Lupa rukun śalat, 5) Lupa kekurangan rakaat. Manakah penyebab sujud sahwi?", options: ["1, 2 dan 3", "2, 3 dan 4", "1, 4 dan 5", "4, 5 dan 6"], answer: 2 },
            { type: 'pg', text: "Ahmad sedang mengerjakan salat asar, tiba-tiba ia teringat bilangan rakaatnya berlebih, maka sebaiknya Ahmad melaksanakan sujud sahwi...", options: ["Sebelum salam", "Setelah salam", "Sebelum takbir", "Setelah takbir"], answer: 0 },
            { type: 'pg', text: "Apabila seorang imam yang membaca ayat-ayat sajadah melakukan sujud, maka yang mendengarkan sebagai makmum hendaknya....", options: ["Membiarkan saja", "Ikut melakukan sujud", "Berpura-pura tidak tahu", "Melihat dan memperhatikan"], answer: 1 },
            { type: 'pg', text: "\"Maha Suci Allah yang tidak pernah tidur dan tidak pernah lupa\", adalah arti bacaan ....", options: ["Sujud Sahwi", "Sujud Syukur", "Sujud tilawah", "Sujud sajdah"], answer: 0 },
            { type: 'pg', text: "Perintah mengeluarkan zakat terdapat dalam Al-Qur`an surat ....", options: ["Q.S At-Taubah ayat 101", "Q.S At-Taubah ayat 102", "Q.S At-Taubah ayat 103", "Q.S At-Taubah ayat 104"], answer: 2 },
            { type: 'pg', text: "Arti dari ibnu sabil adalah ....", options: ["Orang yang kehabisan bekal", "Orang yang dalam perjalanan", "Orang yang tidak punya tempat tinggal", "Orang yang tidak punya pekerjaan"], answer: 1 },
            { type: 'pg', text: "Harga beras Rp14.000/kg. Berapa zakat fitrah (2,5 kg) yang harus dibayar oleh Keluarga Loid Forger jika menggunakan uang untuk 3 jiwa?", options: ["Rp 95.000", "Rp 100.000", "Rp 105.000", "Rp 110.000"], answer: 2 },
            { type: 'pg', text: "Orang yang berhak menerima zakat (mustahik) terdiri dari . . . golongan.", options: ["Lima", "Enam", "Tujuh", "Delapan"], answer: 3 },
            { type: 'pg', text: "Stefani orang USA yang memeluk Islam, Beni kehabisan bekal, Ivan terjerat rentenir, Igan menjadi amil. Manakah yang termasuk golongan Mu’allaf?", options: ["Stefani (1)", "Beni (2)", "Ivan (3)", "Igan (4)"], answer: 0 },
            { type: 'pg', text: "Orang yang mengurus dan memungut zakat disebut....", options: ["Amil", "Mustahik", "Muzakki", "Mualaf"], answer: 0 },
            { type: 'pg', text: "Yang termasuk syarat wajib zakat harta ialah....", options: ["Islam - balig - merdeka - barang dagangan", "Islam - balig - berakal - merdeka - milik sempurna", "Balig - binatang ternak - merdeka", "Islam - balig - merdeka - berakal"], answer: 3 },
            { type: 'pg', text: "Harta yang tidak dipersyaratkan haul (tahun) dalam ketentuan zakat adalah...", options: ["Emas dan perak", "Harta temuan (rikaz)", "Harta perdagangan", "Binatang ternak"], answer: 1 },
            { type: 'pg', text: "Nisab harta perdagangan yang wajib dizakati ukurannya setara dengan nisab...", options: ["Hasil pertanian", "Binatang ternak", "Emas", "Perak"], answer: 2 },
            { type: 'pg', text: "Seseorang yang mempunyai 10 ekor unta, ia wajib mengeluarkan zakatnya berupa....", options: ["Satu ekor kambing", "Dua ekor kambing", "Satu ekor unta", "Dua ekor unta"], answer: 1 },
            // Essay (26-30)
            { type: 'essay', text: "Jelaskan pengertian sujud sahwi!" },
            { type: 'essay', text: "Kapan waktu pelaksanaan sujud sahwi yang benar?" },
            { type: 'essay', text: "Sebutkan 3 (tiga) sebab seseorang harus melakukan sujud sahwi!" },
            { type: 'essay', text: "Sebutkan syarat-syarat wajib zakat secara lengkap!" },
            { type: 'essay', text: "Sebutkan 8 asnaf (golongan) yang berhak menerima zakat sesuai surah At-Taubah ayat 60!" }
        ];

        // --- APP STATE ---
        let appState = {
            view: 'loading',
            studentName: '',
            studentClass: '',
            answers: new Array(30).fill(null),
            lockedAnswers: new Array(25).fill(false),
            currentIndex: 0,
            timer: 3600,
            timerInterval: null,
            violationCount: 0,
            isAudioOn: true,
            status: 'PENDING',
            docId: null,
            kkm: 73
        };

        let audioCtx = null;

        window.switchView = (viewName) => {
            document.querySelectorAll('.view-section').forEach(el => el.classList.add('hidden'));
            document.getElementById(`view-${viewName}`).classList.remove('hidden');
            document.getElementById(`view-${viewName}`).classList.add('fade-in');
            appState.view = viewName;
            
            const teacherLink = document.getElementById('btn-teacher-portal-link');
            if(viewName === 'login') {
                populateStudents();
                teacherLink.classList.remove('hidden');
            } else {
                teacherLink.classList.add('hidden');
            }
        }

        window.onload = async () => {
            await initFirebase();
            if(isFirebaseActive) {
                try {
                    const kkmDoc = await getDoc(doc(db, settingsCollectionPath, 'global'));
                    if(kkmDoc.exists() && kkmDoc.data().kkm) {
                        appState.kkm = kkmDoc.data().kkm;
                        document.getElementById('display-kkm').innerText = appState.kkm;
                    }
                } catch(e) { console.log("KKM sync fallback used."); }
            }
            setTimeout(() => { switchView('login'); }, 1800);
        };

        // --- AUDIO SYSTEM ---
        window.toggleAudio = () => {
            appState.isAudioOn = !appState.isAudioOn;
            const icon = document.getElementById('audio-icon');
            const txt = document.getElementById('audio-text');
            if(appState.isAudioOn) {
                icon.className = "fas fa-volume-up text-lg";
                if(txt) txt.textContent = "SOUND ON";
            } else {
                icon.className = "fas fa-volume-mute text-lg text-red-400";
                if(txt) txt.textContent = "SOUND OFF";
            }
        }

        function playSound(type) {
            if (!appState.isAudioOn) return;
            if (!audioCtx) audioCtx = new (window.AudioContext || window.webkitAudioContext)();
            if (audioCtx.state === 'suspended') audioCtx.resume();
            
            const osc = audioCtx.createOscillator();
            const gainNode = audioCtx.createGain();
            osc.connect(gainNode);
            gainNode.connect(audioCtx.destination);
            const now = audioCtx.currentTime;
            
            if (type === 'swipe') {
                osc.type = 'sine';
                osc.frequency.setValueAtTime(350, now);
                osc.frequency.exponentialRampToValueAtTime(550, now + 0.08);
                gainNode.gain.setValueAtTime(0.08, now);
                gainNode.gain.exponentialRampToValueAtTime(0.001, now + 0.08);
                osc.start(now); osc.stop(now + 0.08);
            } else if (type === 'beep') {
                osc.type = 'square';
                osc.frequency.setValueAtTime(440, now);
                gainNode.gain.setValueAtTime(0.15, now);
                gainNode.gain.linearRampToValueAtTime(0, now + 0.3);
                osc.start(now); osc.stop(now + 0.3);
            } else if (type === 'success') {
                osc.type = 'triangle';
                osc.frequency.setValueAtTime(523.25, now);
                osc.frequency.setValueAtTime(659.25, now + 0.1);
                osc.frequency.setValueAtTime(783.99, now + 0.2);
                gainNode.gain.setValueAtTime(0.15, now);
                gainNode.gain.linearRampToValueAtTime(0, now + 0.4);
                osc.start(now); osc.stop(now + 0.4);
            } else if (type === 'error') {
                osc.type = 'sawtooth';
                osc.frequency.setValueAtTime(140, now);
                gainNode.gain.setValueAtTime(0.2, now);
                gainNode.gain.exponentialRampToValueAtTime(0.01, now + 0.35);
                osc.start(now); osc.stop(now + 0.35);
            }
        }

        window.readQuestionAudio = () => {
            if (!appState.isAudioOn || !window.speechSynthesis) return;
            window.speechSynthesis.cancel();
            const q = QUESTIONS[appState.currentIndex];
            let txt = `Soal nomor ${appState.currentIndex + 1}. ${q.text}`;
            if(q.type === 'pg') {
                txt += ` Pilihan A: ${q.options[0]}. Pilihan B: ${q.options[1]}. Pilihan C: ${q.options[2]}. Pilihan D: ${q.options[3]}`;
            }
            const utterance = new SpeechSynthesisUtterance(txt);
            utterance.lang = 'id-ID';
            utterance.rate = 0.95;
            window.speechSynthesis.speak(utterance);
        }

        // --- STUDENT LOGIN & SESSION ---
        window.populateStudents = () => {
            const cls = document.getElementById('login-class').value;
            const nameSel = document.getElementById('login-name');
            nameSel.innerHTML = '<option value="">-- Pilih Nama Siswa --</option>';
            if (cls && STUDENTS[cls]) {
                STUDENTS[cls].forEach(name => {
                    const opt = document.createElement('option');
                    opt.value = name; opt.textContent = name;
                    nameSel.appendChild(opt);
                });
                nameSel.disabled = false;
            } else {
                nameSel.disabled = true;
            }
        }

        window.attemptLogin = async () => {
            const cls = document.getElementById('login-class').value;
            const name = document.getElementById('login-name').value;
            const err = document.getElementById('login-error');
            
            if (!cls || !name) {
                err.textContent = "Silakan pilih kelas dan nama lengkap Anda.";
                err.classList.remove('hidden');
                playSound('error');
                return;
            }

            const docId = `${cls.replace('.','-')}_${name.replace(/\s+/g, '_')}`;
            appState.docId = docId;

            if (isFirebaseActive) {
                try {
                    const docSnap = await getDoc(doc(db, resultsCollectionPath, docId));
                    if (docSnap.exists()) {
                        const dat = docSnap.data();
                        if (dat.status === 'TUNTAS' || dat.status === 'BELUM TUNTAS' || dat.status === 'DISKUALIFIKASI') {
                            err.innerHTML = `<i class="fas fa-ban"></i> Anda sudah menyelesaikan ujian ini (Status: ${dat.status}). Hubungi guru jika perbaikan diperlukan.`;
                            err.classList.remove('hidden');
                            playSound('error');
                            return;
                        }
                    }
                } catch(e) { console.log("Check student status online error, allowing offline."); }
            }

            appState.studentName = name;
            appState.studentClass = cls;
            document.getElementById('briefing-student-name').textContent = `${name} (${cls})`;
            document.getElementById('exam-header-name').textContent = `${name} - ${cls}`;
            
            playSound('success');
            switchView('briefing');
        }

        window.startExam = () => {
            if(audioCtx && audioCtx.state === 'suspended') audioCtx.resume();
            else if(!audioCtx) audioCtx = new (window.AudioContext || window.webkitAudioContext)();
            
            appState.timer = 3600;
            switchView('exam');
            buildPalette();
            renderQuestion();
            startTimer();
            setupAntiCheat();
            
            document.documentElement.requestFullscreen().catch(e => console.log("Fullscreen mode ready"));
        }

        function formatTime(secs) {
            const m = Math.floor(secs / 60).toString().padStart(2, '0');
            const s = (secs % 60).toString().padStart(2, '0');
            return `${m}:${s}`;
        }

        function startTimer() {
            const timerEl = document.getElementById('exam-timer');
            appState.timerInterval = setInterval(() => {
                appState.timer--;
                timerEl.textContent = formatTime(appState.timer);
                if (appState.timer <= 300) timerEl.classList.add('text-red-400');
                if (appState.timer <= 0) {
                    clearInterval(appState.timerInterval);
                    autoSubmitExam("Waktu Ujian Habis (00:00)");
                }
            }, 1000);
        }

        // --- QUESTION & TRANSITION LOGIC ---
        function renderQuestion() {
            const idx = appState.currentIndex;
            const q = QUESTIONS[idx];
            const qContainer = document.getElementById('question-container');
            
            qContainer.classList.remove('slide-in-right', 'flip-card', 'zoom-in');
            void qContainer.offsetWidth;
            
            if (idx === 10 || idx === 21) {
                qContainer.classList.add('flip-card');
            } else if (idx === 25) {
                qContainer.classList.add('zoom-in');
            } else {
                qContainer.classList.add('slide-in-right');
            }

            document.getElementById('question-indicator').textContent = `SOAL ${(idx + 1).toString().padStart(2, '0')}/30`;
            document.getElementById('question-type-badge').textContent = q.type === 'pg' ? "Pilihan Ganda" : "⚔️ Final Mission (Esai)";
            document.getElementById('exam-progress-bar').style.width = `${((idx + 1) / 30) * 100}%`;
            
            document.getElementById('question-text').textContent = q.text;
            
            const optContainer = document.getElementById('options-container');
            const essayContainer = document.getElementById('essay-container');
            const lockWarning = document.getElementById('locked-warning');
            
            if (q.type === 'pg') {
                essayContainer.classList.add('hidden');
                optContainer.classList.remove('hidden');
                optContainer.innerHTML = '';
                
                const isLocked = appState.lockedAnswers[idx];
                const savedAns = appState.answers[idx];
                
                if (isLocked) lockWarning.classList.remove('hidden');
                else lockWarning.classList.add('hidden');

                q.options.forEach((opt, i) => {
                    const html = `
                        <div class="custom-radio">
                            <input type="radio" name="pg_${idx}" id="opt_${idx}_${i}" value="${i}" 
                                ${savedAns === i ? 'checked' : ''} 
                                ${isLocked ? 'disabled' : ''}
                                onchange="selectAnswer(${idx}, ${i})">
                            <label for="opt_${idx}_${i}">
                                <span class="w-8 h-8 rounded-xl border border-slate-700 flex items-center justify-center mr-3 font-bold bg-slate-900 text-amber-300 shadow-sm">${String.fromCharCode(65+i)}</span>
                                <span class="text-slate-200 font-medium">${opt}</span>
                            </label>
                        </div>
                    `;
                    optContainer.insertAdjacentHTML('beforeend', html);
                });
            } else {
                optContainer.classList.add('hidden');
                essayContainer.classList.remove('hidden');
                lockWarning.classList.add('hidden');
                document.getElementById('essay-input').value = appState.answers[idx] || '';
            }

            document.getElementById('btn-prev').disabled = (idx === 0);
            
            if (idx === QUESTIONS.length - 1) {
                document.getElementById('btn-next').classList.add('hidden');
                document.getElementById('btn-skip').classList.add('hidden');
                document.getElementById('btn-submit-exam').classList.remove('hidden');
            } else {
                document.getElementById('btn-next').classList.remove('hidden');
                document.getElementById('btn-skip').classList.remove('hidden');
                document.getElementById('btn-submit-exam').classList.add('hidden');
            }

            updatePaletteVisuals();
            if (window.speechSynthesis) window.speechSynthesis.cancel();
        }

        window.selectAnswer = (qIndex, ansIndex) => {
            appState.answers[qIndex] = ansIndex;
            playSound('beep');
            updatePaletteVisuals();
            
            if (!appState.lockedAnswers[qIndex]) {
                setTimeout(() => {
                    if (appState.currentIndex === qIndex && appState.answers[qIndex] !== null) {
                        navigateQuestion('next');
                    }
                }, 1200);
            }
        }

        let essayTimeout;
        window.debouncedSaveEssay = () => {
            clearTimeout(essayTimeout);
            essayTimeout = setTimeout(() => {
                appState.answers[appState.currentIndex] = document.getElementById('essay-input').value;
                updatePaletteVisuals();
            }, 400);
        }

        window.navigateQuestion = (dir) => {
            if (dir === 'next' && appState.currentIndex < 29) {
                if (QUESTIONS[appState.currentIndex].type === 'pg' && appState.answers[appState.currentIndex] !== null) {
                    appState.lockedAnswers[appState.currentIndex] = true;
                }
                appState.currentIndex++;
                playSound('swipe');
                renderQuestion();
            } else if (dir === 'prev' && appState.currentIndex > 0) {
                appState.currentIndex--;
                playSound('swipe');
                renderQuestion();
            }
        }
        
        window.skipQuestion = () => {
            if (QUESTIONS[appState.currentIndex].type === 'pg' && appState.answers[appState.currentIndex] !== null) {
                appState.lockedAnswers[appState.currentIndex] = true;
            }
            if (appState.currentIndex < 29) {
                appState.currentIndex++;
                playSound('swipe');
                renderQuestion();
            }
        }

        window.jumpToQuestion = (idx) => {
            appState.currentIndex = idx;
            playSound('swipe');
            renderQuestion();
            if(window.innerWidth < 768) togglePalette();
        }

        function buildPalette() {
            const gridPg = document.getElementById('palette-grid-pg');
            const gridEssay = document.getElementById('palette-grid-essay');
            gridPg.innerHTML = ''; gridEssay.innerHTML = '';
            
            QUESTIONS.forEach((q, i) => {
                const btn = document.createElement('button');
                btn.id = `pal-btn-${i}`;
                btn.className = `w-full aspect-square rounded-xl font-bold text-xs flex items-center justify-center transition-all border-2 bg-slate-900 border-slate-800 text-slate-300 hover:border-gold shadow-sm`;
                btn.textContent = i + 1;
                btn.onclick = () => jumpToQuestion(i);
                
                if (q.type === 'pg') gridPg.appendChild(btn);
                else gridEssay.appendChild(btn);
            });
        }

        function updatePaletteVisuals() {
            QUESTIONS.forEach((q, i) => {
                const btn = document.getElementById(`pal-btn-${i}`);
                if (!btn) return;
                
                btn.className = `w-full aspect-square rounded-xl font-bold text-xs flex items-center justify-center transition-all border-2 shadow-sm`;
                
                if (i === appState.currentIndex) {
                    btn.classList.add('bg-indigo-600', 'border-indigo-400', 'text-white', 'scale-105');
                } else if (appState.answers[i] !== null && appState.answers[i] !== '') {
                    if (q.type === 'pg' && appState.lockedAnswers[i]) {
                        btn.classList.add('bg-amber-600', 'border-amber-400', 'text-white');
                    } else if (q.type === 'essay') {
                        btn.classList.add('bg-gold', 'border-yellow-600', 'text-slate-950');
                    } else {
                        btn.classList.add('bg-amber-900/50', 'border-amber-600', 'text-amber-200');
                    }
                } else {
                    btn.classList.add('bg-slate-900', 'border-slate-800', 'text-slate-400');
                }
            });
        }

        window.togglePalette = () => {
            const pal = document.getElementById('palette-sidebar');
            pal.classList.toggle('translate-x-full');
        }

        // --- CHECK UNANSWERED & SUBMIT CONFIRMATION ---
        window.checkUnansweredAndSubmit = () => {
            const unanswered = [];
            QUESTIONS.forEach((q, i) => {
                const ans = appState.answers[i];
                if (ans === null || ans === '' || (typeof ans === 'string' && ans.trim() === '')) {
                    unanswered.push(i + 1);
                }
            });

            if (unanswered.length > 0) {
                showModal({
                    title: "⚠️ MASIH ADA SOAL KOSONG",
                    message: `Terdapat <b>${unanswered.length} soal</b> yang belum terjawab:<br><span class="text-red-400 font-bold">${unanswered.join(', ')}</span><br><br>Apakah Anda ingin kembali memeriksa soal tersebut atau tetap mengirimkan?`,
                    icon: 'fa-exclamation-triangle',
                    type: 'warning',
                    confirmText: "Kembali Memeriksa",
                    cancelText: "Tetap Submit",
                    onCancel: () => { confirmFinalSubmit(); },
                    onConfirm: () => { jumpToQuestion(unanswered[0] - 1); }
                });
            } else {
                confirmFinalSubmit();
            }
        }

        function confirmFinalSubmit() {
            showModal({
                title: "🏁 SELESAIKAN MISI?",
                message: "Pastikan seluruh jawaban sudah diperiksa. Setelah dikirim, jawaban tidak dapat diubah.",
                icon: 'fa-flag-checkered',
                type: 'confirm',
                confirmText: "KIRIM JAWABAN",
                cancelText: "KEMBALI",
                onConfirm: () => { processSubmit('NORMAL'); }
            });
        }

        function autoSubmitExam(reason) {
            showModal({
                title: "OTOMATIS SUBMIT",
                message: `Alasan: <b>${reason}</b><br>Sistem sedang merekam dan mengirim jawaban Anda...`,
                icon: 'fa-clock',
                type: 'warning'
            });
            setTimeout(() => { hideModal(); processSubmit('AUTO_SUBMIT'); }, 2000);
        }

        // --- ANTI-CHEATING SYSTEM ---
        function setupAntiCheat() {
            document.addEventListener('visibilitychange', handleVisibilityChange);
            window.addEventListener('blur', handleBlur);
            document.addEventListener('keydown', (e) => {
                if (appState.view === 'exam' && ((e.ctrlKey && ['c','v','p','s','a','u'].includes(e.key.toLowerCase())) || e.key === 'F12')) {
                    e.preventDefault();
                }
            });
        }

        function handleVisibilityChange() {
            if (document.hidden && appState.view === 'exam') {
                triggerViolation("Pindah Tab / Minimize Browser Terdeteksi");
            }
        }

        function handleBlur() {
            if (appState.view === 'exam' && !document.getElementById('custom-modal-overlay').classList.contains('hidden')) return;
            if (appState.view === 'exam') {
                triggerViolation("Kehilangan Fokus Halaman Ujian");
            }
        }

        function triggerViolation(reason) {
            appState.violationCount++;
            document.getElementById('exam-violation-count').textContent = `${appState.violationCount} / 3`;
            playSound('error');
            
            const appEl = document.getElementById('app-container');
            appEl.style.backgroundColor = 'rgba(239, 68, 68, 0.25)';
            setTimeout(() => appEl.style.backgroundColor = '', 400);

            if (appState.violationCount === 1) {
                showModal({
                    title: "⚠️ PERINGATAN! (Pelanggaran 1/3)",
                    message: `Sistem mendeteksi aktivitas yang tidak diperbolehkan:<br><b>${reason}</b><br><br>Tetap jujur dalam mengerjakan ujian. Masukkan PIN Pengawas (1414) untuk melanjutkan.`,
                    icon: 'fa-shield-alt',
                    type: 'warning',
                    showPin: true,
                    confirmText: "Buka Ujian",
                    onConfirm: () => { console.log("PIN Accepted."); }
                });
            } else if (appState.violationCount === 2) {
                showModal({
                    title: "🚨 PERINGATAN TERAKHIR! (Pelanggaran 2/3)",
                    message: `Aktivitas terlarang terdeteksi kembali:<br><b>${reason}</b><br><br>Jika Anda melakukan pelanggaran sekali lagi, ujian akan otomatis dihentikan dan didiskualifikasi!`,
                    icon: 'fa-radiation',
                    type: 'warning',
                    confirmText: "Saya Mengerti & Lanjutkan",
                    onConfirm: () => { console.log("Warning 2 acknowledged."); }
                });
            } else if (appState.violationCount >= 3) {
                clearInterval(appState.timerInterval);
                document.removeEventListener('visibilitychange', handleVisibilityChange);
                window.removeEventListener('blur', handleBlur);
                processSubmit('DISKUALIFIKASI');
            }
        }

        // --- SUBMISSION & SCORING ---
        async function processSubmit(triggerType) {
            clearInterval(appState.timerInterval);
            if (window.speechSynthesis) window.speechSynthesis.cancel();
            
            let correctPG = 0;
            let wrongPG = 0;
            
            QUESTIONS.forEach((q, i) => {
                if (q.type === 'pg') {
                    if (appState.answers[i] === q.answer) correctPG++;
                    else if (appState.answers[i] !== null) wrongPG++;
                }
            });

            const scorePG = correctPG * 3; // 25 * 3 = 75 max
            
            let scoreEssay = 0;
            QUESTIONS.forEach((q, i) => {
                if (q.type === 'essay' && appState.answers[i] && appState.answers[i].trim().length > 8) {
                    scoreEssay += 5; // 5 * 5 = 25 max
                }
            });

            const totalScore = Math.min(100, scorePG + scoreEssay);
            
            let finalStatus = 'BELUM TUNTAS';
            if (triggerType === 'DISKUALIFIKASI') finalStatus = 'DISKUALIFIKASI';
            else if (totalScore >= appState.kkm) finalStatus = 'TUNTAS';

            appState.status = finalStatus;
            const duration = 3600 - appState.timer;

            const record = {
                studentName: appState.studentName,
                studentClass: appState.studentClass,
                scorePG: scorePG,
                scoreEssay: scoreEssay,
                totalScore: totalScore,
                correctPG: correctPG,
                wrongPG: wrongPG,
                durationSeconds: duration,
                status: finalStatus,
                violationCount: appState.violationCount,
                triggerType: triggerType,
                timestampStr: new Date().toLocaleString('id-ID'),
                timestamp: isFirebaseActive ? serverTimestamp() : new Date().toISOString(),
                answers: appState.answers
            };

            if (isFirebaseActive) {
                try {
                    await setDoc(doc(db, resultsCollectionPath, appState.docId), record);
                    console.log("Exam result successfully saved to Firestore.");
                } catch(e) { console.error("Firestore save error:", e); }
            }

            // Push to Google Sheets Web App if configured
            const scriptUrl = localStorage.getItem('smp_script_url');
            if (scriptUrl) {
                fetch(scriptUrl, {
                    method: 'POST',
                    mode: 'no-cors',
                    headers: { 'Content-Type': 'application/json' },
                    body: JSON.stringify(record)
                }).catch(err => console.log("Apps Script push note:", err));
            }

            // Render Result Page
            document.getElementById('result-name').textContent = `${appState.studentName} — Kelas ${appState.studentClass}`;
            document.getElementById('result-score').textContent = totalScore;
            document.getElementById('result-pg-score').textContent = `${scorePG} / 75`;
            document.getElementById('result-essay-score').textContent = `${scoreEssay} / 25`;
            document.getElementById('result-correct').textContent = correctPG;
            document.getElementById('result-wrong').textContent = wrongPG;
            document.getElementById('result-duration').textContent = formatTime(duration) + " menit";
            
            const banner = document.getElementById('result-status-banner');
            if (finalStatus === 'TUNTAS') {
                banner.className = "mb-6 p-4 rounded-xl font-bold text-base bg-emerald-950/80 text-emerald-200 border-2 border-emerald-600 shadow-sm";
                banner.textContent = "ALHAMDULILLAH, TUNTAS!";
                document.getElementById('result-feedback').textContent = "Hebat! Pemahaman fikih Anda sangat baik. Pertahankan prestasimu!";
                shootConfetti();
                playSound('success');
            } else if (finalStatus === 'DISKUALIFIKASI') {
                banner.className = "mb-6 p-4 rounded-xl font-bold text-base bg-red-950/80 text-red-200 border-2 border-red-600 shadow-sm";
                banner.textContent = "UJIAN DIHENTIKAN / DISKUALIFIKASI";
                document.getElementById('result-feedback').textContent = "Terdeteksi pelanggaran aturan ujian melebihi batas toleransi. Silakan melapor kepada pengawas.";
                playSound('error');
            } else {
                banner.className = "mb-6 p-4 rounded-xl font-bold text-base bg-amber-950/80 text-amber-200 border-2 border-amber-600 shadow-sm";
                banner.textContent = "BELUM TUNTAS (DI BAWAH KKM)";
                document.getElementById('result-feedback').textContent = "Tetap semangat! Pelajari kembali materi Fikih yang belum dikuasai dan ikuti program remedial.";
                playSound('beep');
            }

            switchView('result');
        }

        function shootConfetti() {
            const canvas = document.getElementById('confetti-canvas');
            const ctx = canvas.getContext('2d');
            canvas.width = window.innerWidth;
            canvas.height = window.innerHeight;
            
            const pieces = [];
            const colors = ['#eab308', '#f59e0b', '#14b8a6', '#ffffff', '#fbbf24'];
            for(let i=0; i<120; i++) {
                pieces.push({
                    x: canvas.width/2, y: canvas.height/2 + 150,
                    vx: (Math.random() - 0.5) * 22, vy: (Math.random() - 1) * 22 - 12,
                    size: Math.random() * 10 + 6,
                    color: colors[Math.floor(Math.random() * colors.length)],
                    rot: Math.random() * 360, rotSpeed: (Math.random() - 0.5) * 12
                });
            }
            
            function animate() {
                ctx.clearRect(0, 0, canvas.width, canvas.height);
                let active = false;
                pieces.forEach(p => {
                    p.x += p.vx; p.y += p.vy; p.vy += 0.55;
                    p.rot += p.rotSpeed;
                    if(p.y < canvas.height) active = true;
                    
                    ctx.save();
                    ctx.translate(p.x, p.y);
                    ctx.rotate(p.rot * Math.PI / 180);
                    ctx.fillStyle = p.color;
                    ctx.fillRect(-p.size/2, -p.size/2, p.size, p.size);
                    ctx.restore();
                });
                if(active) requestAnimationFrame(animate);
                else ctx.clearRect(0, 0, canvas.width, canvas.height);
            }
            animate();
        }

        // --- CUSTOM MODAL SYSTEM ---
        function showModal({ title, message, icon, type, showPin = false, confirmText = "Konfirmasi", cancelText = "Batal", onConfirm, onCancel }) {
            const overlay = document.getElementById('custom-modal-overlay');
            const modal = document.getElementById('custom-modal');
            
            document.getElementById('modal-title').textContent = title;
            document.getElementById('modal-message').innerHTML = message;
            
            const iconEl = document.getElementById('modal-icon');
            iconEl.innerHTML = `<i class="fas ${icon}"></i>`;
            iconEl.className = `w-16 h-16 mx-auto rounded-full flex items-center justify-center text-3xl mb-4 ${
                type === 'warning' ? 'bg-red-950/80 text-red-400 border border-red-800' : 'bg-amber-950/80 text-gold border border-amber-800'
            }`;

            const pinArea = document.getElementById('modal-pin-area');
            const pinInput = document.getElementById('modal-pin-input');
            const pinErr = document.getElementById('modal-pin-error');
            
            if (showPin) {
                pinArea.classList.remove('hidden');
                pinInput.value = '';
                pinErr.classList.add('hidden');
            } else {
                pinArea.classList.add('hidden');
            }

            const btnContainer = document.getElementById('modal-buttons');
            btnContainer.innerHTML = '';
            
            if (onCancel || cancelText) {
                const btnCancel = document.createElement('button');
                btnCancel.className = "px-5 py-2.5 rounded-xl font-bold text-slate-300 bg-slate-800 hover:bg-slate-700 text-sm transition-colors";
                btnCancel.textContent = cancelText;
                btnCancel.onclick = () => { hideModal(); if(onCancel) onCancel(); };
                btnContainer.appendChild(btnCancel);
            }
            
            if (onConfirm) {
                const btnConfirm = document.createElement('button');
                btnConfirm.className = `px-6 py-2.5 rounded-xl font-bold text-slate-950 text-sm transition-colors shadow-md ${
                    type === 'warning' ? 'bg-red-500 hover:bg-red-400 text-white' : 'bg-gradient-to-r from-amber-600 to-gold hover:from-gold hover:to-amber-600'
                }`;
                btnConfirm.textContent = confirmText;
                btnConfirm.onclick = () => {
                    if (showPin) {
                        if (pinInput.value === '1414') {
                            hideModal();
                            onConfirm();
                        } else {
                            pinErr.classList.remove('hidden');
                            playSound('error');
                        }
                    } else {
                        hideModal();
                        onConfirm();
                    }
                };
                btnContainer.appendChild(btnConfirm);
            }

            overlay.classList.remove('hidden');
            setTimeout(() => modal.classList.remove('scale-95'), 10);
        }

        window.hideModal = () => {
            const overlay = document.getElementById('custom-modal-overlay');
            const modal = document.getElementById('custom-modal');
            modal.classList.add('scale-95');
            setTimeout(() => overlay.classList.add('hidden'), 200);
        }

        // --- TEACHER PANEL LOGIC ---
        let teacherData = [];
        let unsubscribeResults = null;

        window.attemptTeacherLogin = () => {
            const user = document.getElementById('t-username').value;
            const pass = document.getElementById('t-password').value;
            const err = document.getElementById('t-login-error');
            
            if (user === 'riia' && pass === 'ujian2026') {
                err.classList.add('hidden');
                switchView('teacher-panel');
                fetchResults();
            } else {
                err.classList.remove('hidden');
                playSound('error');
            }
        }

        window.logoutTeacher = () => {
            if(unsubscribeResults) unsubscribeResults();
            document.getElementById('t-username').value = '';
            document.getElementById('t-password').value = '';
            switchView('login');
        }

        window.fetchResults = async () => {
            if (!isFirebaseActive) {
                teacherData = [
                    { id: '1', studentName: 'Adib Naufal Abiyyu', studentClass: '8.1', totalScore: 88, scorePG: 66, scoreEssay: 22, correctPG: 22, wrongPG: 3, status: 'TUNTAS', durationSeconds: 2100, violationCount: 0, timestampStr: '11/09/2026 21:00' },
                    { id: '2', studentName: 'Fakhri Maulana', studentClass: '8.2', totalScore: 68, scorePG: 51, scoreEssay: 17, correctPG: 17, wrongPG: 8, status: 'BELUM TUNTAS', durationSeconds: 2900, violationCount: 1, timestampStr: '11/09/2026 21:15' },
                    { id: '3', studentName: 'ACHILA ANATSYA INDRIYANI', studentClass: '8.3', totalScore: 94, scorePG: 72, scoreEssay: 22, correctPG: 24, wrongPG: 1, status: 'TUNTAS', durationSeconds: 1950, violationCount: 0, timestampStr: '11/09/2026 21:20' }
                ];
                applyFilters();
                analyzeTeacherData();
                return;
            }

            const q = collection(db, resultsCollectionPath);
            unsubscribeResults = onSnapshot(q, (snapshot) => {
                teacherData = [];
                snapshot.forEach((doc) => {
                    teacherData.push({ id: doc.id, ...doc.data() });
                });
                recalculateStatus();
                applyFilters();
                analyzeTeacherData();
            }, (error) => { console.error("Error fetching teacher snapshot:", error); });
        }

        function recalculateStatus() {
            teacherData.forEach(d => {
                if (d.status !== 'DISKUALIFIKASI') {
                    if (d.totalScore >= appState.kkm) d.status = 'TUNTAS';
                    else d.status = 'BELUM TUNTAS';
                }
            });
        }

        window.openSheetsModal = () => {
            const savedUrl = localStorage.getItem('smp_script_url') || '';
            document.getElementById('input-script-url').value = savedUrl;
            document.getElementById('sheets-modal-overlay').classList.remove('hidden');
        }
        window.closeSheetsModal = () => document.getElementById('sheets-modal-overlay').classList.add('hidden');
        window.syncToSheets = () => {
            const url = document.getElementById('input-script-url').value.trim();
            if(url) {
                localStorage.setItem('smp_script_url', url);
            }
            window.open('https://docs.google.com/spreadsheets/d/1oBuh_hKvedWdiVDB6a4pwk9oFRIAihcmYD6bCa1xjyM/edit?usp=sharing', '_blank');
            closeSheetsModal();
        }

        window.applyFilters = () => {
            const fClass = document.getElementById('filter-class').value;
            const fStatus = document.getElementById('filter-status').value;
            const fName = document.getElementById('filter-name').value.toLowerCase();
            
            let filtered = teacherData.filter(d => {
                let matchClass = (fClass === 'all' || d.studentClass === fClass);
                let matchStatus = (fStatus === 'all' || d.status === fStatus);
                let matchName = d.studentName.toLowerCase().includes(fName);
                return matchClass && matchStatus && matchName;
            });
            
            renderTable(filtered);
            updateDashboardStats(filtered);
        }

        let sortDesc = true;
        window.sortData = (key) => {
            sortDesc = !sortDesc;
            const fClass = document.getElementById('filter-class').value;
            const fStatus = document.getElementById('filter-status').value;
            const fName = document.getElementById('filter-name').value.toLowerCase();
            
            let filtered = teacherData.filter(d => {
                return (fClass === 'all' || d.studentClass === fClass) &&
                       (fStatus === 'all' || d.status === fStatus) &&
                       (d.studentName.toLowerCase().includes(fName));
            });

            filtered.sort((a, b) => {
                if(key === 'score') return sortDesc ? b.totalScore - a.totalScore : a.totalScore - b.totalScore;
                return 0;
            });
            renderTable(filtered);
        }

        function renderTable(data) {
            const tbody = document.getElementById('results-table-body');
            tbody.innerHTML = '';
            
            if (data.length === 0) {
                tbody.innerHTML = '<tr><td colspan="8" class="p-8 text-center text-slate-500">Tidak ada data rekapitulasi ujian yang sesuai filter.</td></tr>';
                return;
            }

            data.forEach((d, index) => {
                const tr = document.createElement('tr');
                tr.className = "hover:bg-slate-900/80 transition-colors cursor-pointer border-b border-slate-800/40";
                tr.onclick = () => showStudentDetail(d);
                
                let statusBadge = '';
                if(d.status === 'TUNTAS') statusBadge = '<span class="px-2.5 py-1 bg-emerald-950 text-emerald-300 border border-emerald-800 rounded-lg text-xs font-bold">TUNTAS</span>';
                else if(d.status === 'DISKUALIFIKASI') statusBadge = '<span class="px-2.5 py-1 bg-red-950 text-red-300 border border-red-800 rounded-lg text-xs font-bold">DISKUALIFIKASI</span>';
                else statusBadge = '<span class="px-2.5 py-1 bg-amber-950 text-amber-300 border border-amber-800 rounded-lg text-xs font-bold">BELUM TUNTAS</span>';

                tr.innerHTML = `
                    <td class="p-3.5">${index + 1}</td>
                    <td class="p-3.5 font-bold text-white">${d.studentName}</td>
                    <td class="p-3.5 font-medium">${d.studentClass}</td>
                    <td class="p-3.5 text-xs text-slate-400">${d.timestampStr || '-'}</td>
                    <td class="p-3.5 text-center font-bold text-base text-gold">${d.totalScore}</td>
                    <td class="p-3.5 text-center text-xs text-slate-400">${formatTime(d.durationSeconds || 0)}</td>
                    <td class="p-3.5 text-center">${statusBadge}</td>
                    <td class="p-3.5 text-center text-gold hover:text-white"><i class="fas fa-search-plus text-base"></i></td>
                `;
                tbody.appendChild(tr);
            });
        }

        function updateDashboardStats(data) {
            if(data.length === 0) {
                ['stat-total','stat-avg','stat-max','stat-min','stat-pass','stat-viol'].forEach(id => document.getElementById(id).textContent = '0');
                return;
            }

            document.getElementById('stat-total').textContent = data.length;
            const sum = data.reduce((acc, curr) => acc + curr.totalScore, 0);
            document.getElementById('stat-avg').textContent = (sum / data.length).toFixed(1);
            document.getElementById('stat-max').textContent = Math.max(...data.map(d => d.totalScore));
            document.getElementById('stat-min').textContent = Math.min(...data.map(d => d.totalScore));
            
            const passCount = data.filter(d => d.status === 'TUNTAS').length;
            document.getElementById('stat-pass').textContent = Math.round((passCount / data.length) * 100) + '%';
            
            const violCount = data.filter(d => d.violationCount > 0).length;
            document.getElementById('stat-viol').textContent = violCount;
        }

        function analyzeTeacherData() {
            if (teacherData.length === 0) return;
            const avg = teacherData.reduce((acc, curr) => acc + curr.totalScore, 0) / teacherData.length;
            let text = `Rata-rata kelas saat ini adalah <b>${avg.toFixed(1)}</b>. `;
            if (avg >= appState.kkm) {
                text += `Secara umum pencapaian siswa melampaui batas KKM (${appState.kkm}). `;
            } else {
                text += `Rata-rata berada di bawah KKM (${appState.kkm}). <b>Rekomendasi:</b> Perlu diadakan penguatan materi ibadah sunnah dan zakat mal.`;
            }
            document.getElementById('system-analysis-text').innerHTML = text;
        }

        window.openKkmModal = () => {
            document.getElementById('input-kkm-setting').value = appState.kkm;
            document.getElementById('kkm-modal-overlay').classList.remove('hidden');
        }
        window.closeKkmModal = () => document.getElementById('kkm-modal-overlay').classList.add('hidden');
        window.saveKkmSetting = async () => {
            const val = parseInt(document.getElementById('input-kkm-setting').value);
            if (val >= 0 && val <= 100) {
                appState.kkm = val;
                document.getElementById('display-kkm').textContent = val;
                if (isFirebaseActive) {
                    try { await setDoc(doc(db, settingsCollectionPath, 'global'), { kkm: val }, { merge: true }); } catch(e) {}
                }
                recalculateStatus();
                applyFilters();
                closeKkmModal();
            }
        }

        window.showStudentDetail = (d) => {
            const content = document.getElementById('detail-content');
            let badge = d.status === 'TUNTAS' ? '<span class="bg-emerald-950 text-emerald-300 border border-emerald-800 px-3 py-1 rounded-full text-xs font-bold">TUNTAS</span>' : '<span class="bg-amber-950 text-amber-300 border border-amber-800 px-3 py-1 rounded-full text-xs font-bold">BELUM TUNTAS</span>';
            
            let essayHTML = '<div class="mt-4"><h5 class="font-bold text-gold mb-2 text-sm">Jawaban Esai (Soal 26 - 30):</h5><div class="space-y-2">';
            if (d.answers) {
                for (let i = 25; i < 30; i++) {
                    let ans = d.answers[i] || '<span class="text-slate-500 italic">Tidak dijawab</span>';
                    essayHTML += `<div class="bg-slate-900 p-3 rounded-xl border border-slate-800 text-xs"><p class="font-semibold text-amber-300 mb-1">Soal ${i+1}:</p><p class="text-slate-300">${ans}</p></div>`;
                }
            }
            essayHTML += '</div></div>';

            content.innerHTML = `
                <div class="flex justify-between items-start mb-4 border-b border-slate-800 pb-3">
                    <div>
                        <h4 class="text-xl font-bold text-white">${d.studentName}</h4>
                        <p class="text-slate-400 text-sm">Kelas: ${d.studentClass}</p>
                    </div>
                    <div class="text-right">
                        <div class="text-3xl font-bold text-gold">${d.totalScore}</div>
                        ${badge}
                    </div>
                </div>
                <div class="grid grid-cols-2 md:grid-cols-4 gap-3 text-center mb-4">
                    <div class="bg-slate-900 p-3 rounded-xl border border-slate-800"><p class="text-xs text-slate-400 font-medium">Nilai PG</p><p class="font-bold text-base text-white">${d.scorePG || 0}</p></div>
                    <div class="bg-slate-900 p-3 rounded-xl border border-slate-800"><p class="text-xs text-slate-400 font-medium">Nilai Esai</p><p class="font-bold text-base text-white">${d.scoreEssay || 0}</p></div>
                    <div class="bg-slate-900 p-3 rounded-xl border border-slate-800"><p class="text-xs text-slate-400 font-medium">Durasi</p><p class="font-bold text-base text-white">${formatTime(d.durationSeconds || 0)}</p></div>
                    <div class="bg-slate-900 p-3 rounded-xl border border-slate-800"><p class="text-xs text-slate-400 font-medium">Pelanggaran</p><p class="font-bold text-base text-red-400">${d.violationCount || 0}</p></div>
                </div>
                ${d.violationCount > 0 ? `<div class="bg-red-950/60 border border-red-800/60 text-red-300 p-3 rounded-xl text-xs mb-4"><i class="fas fa-exclamation-triangle mr-1"></i> Terindikasi aktivitas tidak diperbolehkan sebanyak ${d.violationCount} kali.</div>` : ''}
                ${essayHTML}
            `;
            document.getElementById('detail-modal-overlay').classList.remove('hidden');
        }

        window.closeDetailModal = () => document.getElementById('detail-modal-overlay').classList.add('hidden');

        window.exportToCSV = () => {
            if (teacherData.length === 0) return;
            let csv = "No,Nama Siswa,Kelas,Nilai Total,Nilai PG,Nilai Esai,Status,Durasi (detik),Jumlah Pelanggaran,Waktu Submit\n";
            teacherData.forEach((d, idx) => {
                csv += `${idx+1},"${d.studentName}",${d.studentClass},${d.totalScore},${d.scorePG||0},${d.scoreEssay||0},${d.status},${d.durationSeconds||0},${d.violationCount||0},"${d.timestampStr||''}"\n`;
            });
            const blob = new Blob([csv], { type: 'text/csv;charset=utf-8;' });
            const url = URL.createObjectURL(blob);
            const a = document.createElement('a');
            a.href = url;
            a.download = `Rekap_Ujian_Fikih_Kelas_8_${new Date().toISOString().split('T')[0]}.csv`;
            a.click();
        }
    </script>
</body>
</html># game-ujian-sumatif-fikih-ganjil
