<!DOCTYPE html>
<html lang="ko">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>바이브 코딩(Vibe Coding) 성공 가이드 & 웹앱</title>
    <!-- Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- FontAwesome Icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <!-- Google Fonts (Noto Sans KR) -->
    <link href="https://fonts.googleapis.com/css2?family=Noto+Sans+KR:wght@300;400;600;700;900&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Noto Sans KR', sans-serif;
        }
        .gradient-bg {
            background: linear-gradient(135deg, #6366f1 0%, #a855f7 50%, #ec4899 100%);
        }
        .glass-card {
            background: rgba(255, 255, 255, 0.9);
            backdrop-filter: blur(10px);
            border: 1px solid rgba(255, 255, 255, 0.2);
        }
    </style>
</head>
<body class="bg-slate-50 text-slate-800 min-h-screen flex flex-col justify-between">

    <!-- Header / Hero Section -->
    <header class="gradient-bg text-white py-12 px-4 sm:px-6 lg:px-8 text-center shadow-lg relative overflow-hidden">
        <div class="absolute inset-0 opacity-10 bg-[radial-gradient(#fff_1px,transparent_1px)] [background-size:16px_16px]"></div>
        <div class="max-w-4xl mx-auto relative z-10">
            <span class="inline-block px-3 py-1 bg-white/20 backdrop-blur-md rounded-full text-xs font-semibold uppercase tracking-wider mb-3">
                <i class="fa-solid => fa-bolt mr-1"></i> Future of Coding
            </span>
            <h1 class="text-4xl sm:text-5xl font-extrabold tracking-tight mb-4">
                🚀 바이브 코딩(Vibe Coding) 성공법
            </h1>
            <p class="text-lg sm:text-xl text-indigo-100 font-light max-w-2xl mx-auto">
                AI와 직관적으로 소통하며 아이디어를 빠르고 완벽하게 현실로 만드는 현대적인 개발 패러다임
            </p>
        </div>
    </header>

    <!-- Main Content Container -->
    <main class="max-w-5xl mx-auto px-4 sm:px-6 lg:px-8 py-10 flex-grow w-full space-y-12">

        <!-- Section 1: 성공 원칙 카드 Grid -->
        <section>
            <h2 class="text-2xl font-bold text-slate-900 mb-6 flex items-center gap-2">
                <i class="fa-solid fa-key text-indigo-600"></i> 바이브 코딩 5대 성공 법칙
            </h2>
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-6">
                
                <!-- Rule 1 -->
                <div class="glass-card rounded-2xl p-6 shadow-sm hover:shadow-md transition-all duration-300 border border-slate-100 flex flex-col justify-between">
                    <div>
                        <div class="w-12 h-12 rounded-xl bg-indigo-100 text-indigo-600 flex items-center justify-center text-xl font-bold mb-4">
                            01
                        </div>
                        <h3 class="text-lg font-bold text-slate-900 mb-2">명확한 인텐트 설정</h3>
                        <p class="text-sm text-slate-600 leading-relaxed">
                            복잡한 코드 대신 원하는 결과물의 목적과 UI/UX 흐름을 명확하고 구체적으로 설명하세요.
                        </p>
                    </div>
                    <div class="mt-4 pt-3 border-t border-slate-100 text-xs text-indigo-600 font-semibold">
                        #목표중심 #직관적대화
                    </div>
                </div>

                <!-- Rule 2 -->
                <div class="glass-card rounded-2xl p-6 shadow-sm hover:shadow-md transition-all duration-300 border border-slate-100 flex flex-col justify-between">
                    <div>
                        <div class="w-12 h-12 rounded-xl bg-purple-100 text-purple-600 flex items-center justify-center text-xl font-bold mb-4">
                            02
                        </div>
                        <h3 class="text-lg font-bold text-slate-900 mb-2">점진적 점프 (MVP)</h3>
                        <p class="text-sm text-slate-600 leading-relaxed">
                            처음부터 거대하게 만들지 말고 핵심 기능(MVP)부터 시작해 기능을 하나씩 덧붙이세요.
                        </p>
                    </div>
                    <div class="mt-4 pt-3 border-t border-slate-100 text-xs text-purple-600 font-semibold">
                        #작게시작하기 #빠른피드백
                    </div>
                </div>

                <!-- Rule 3 -->
                <div class="glass-card rounded-2xl p-6 shadow-sm hover:shadow-md transition-all duration-300 border border-slate-100 flex flex-col justify-between">
                    <div>
                        <div class="w-12 h-12 rounded-xl bg-pink-100 text-pink-600 flex items-center justify-center text-xl font-bold mb-4">
                            03
                        </div>
                        <h3 class="text-lg font-bold text-slate-900 mb-2">실시간 바이브 검증</h3>
                        <p class="text-sm text-slate-600 leading-relaxed">
                            AI가 생성한 결과물을 바로 렌더링하고 시각적/기능적 '바이브'가 맞는지 실시간 수정하세요.
                        </p>
                    </div>
                    <div class="mt-4 pt-3 border-t border-slate-100 text-xs text-pink-600 font-semibold">
                        #실시간테스트 #디버깅
                    </div>
                </div>

                <!-- Rule 4 -->
                <div class="glass-card rounded-2xl p-6 shadow-sm hover:shadow-md transition-all duration-300 border border-slate-100 flex flex-col justify-between">
                    <div>
                        <div class="w-12 h-12 rounded-xl bg-amber-100 text-amber-600 flex items-center justify-center text-xl font-bold mb-4">
                            04
                        </div>
                        <h3 class="text-lg font-bold text-slate-900 mb-2">단일 파일/모듈화 지향</h3>
                        <p class="text-sm text-slate-600 leading-relaxed">
                            독립적으로 실행 가능한 자기완결적(Self-contained) 구조로 작성하도록 프롬프트를 구성하세요.
                        </p>
                    </div>
                    <div class="mt-4 pt-3 border-t border-slate-100 text-xs text-amber-600 font-semibold">
                        #자기완결성 #모듈화
                    </div>
                </div>

                <!-- Rule 5 -->
                <div class="glass-card rounded-2xl p-6 shadow-sm hover:shadow-md transition-all duration-300 border border-slate-100 flex flex-col justify-between md:col-span-2 lg:col-span-2">
                    <div>
                        <div class="w-12 h-12 rounded-xl bg-emerald-100 text-emerald-600 flex items-center justify-center text-xl font-bold mb-4">
                            05
                        </div>
                        <h3 class="text-lg font-bold text-slate-900 mb-2">AI 페어 프로그래밍 서포트</h3>
                        <p class="text-sm text-slate-600 leading-relaxed">
                            AI를 주도적인 개발 주체로 활용하되, 방향성과 윤리적 책임은 개발자가 쥐는 완벽한 파트너십을 형성하세요.
                        </p>
                    </div>
                    <div class="mt-4 pt-3 border-t border-slate-100 text-xs text-emerald-600 font-semibold">
                        #AI협업 #올바른사용
                    </div>
                </div>

            </div>
        </section>

        <!-- Section 2: Interactive Vibe Coding Studio (동적 앱 체험) -->
        <section class="bg-white rounded-3xl p-6 sm:p-8 shadow-xl border border-slate-100">
            <div class="max-w-3xl mx-auto text-center mb-8">
                <span class="text-xs font-bold text-indigo-600 bg-indigo-50 px-3 py-1 rounded-full uppercase">Interactive Tool</span>
                <h2 class="text-2xl sm:text-3xl font-bold text-slate-900 mt-2">✨ 나만의 바이브 아이디어 노트</h2>
                <p class="text-sm text-slate-500 mt-1">아이디어를 적고 AI 프롬프트 스타일로 변환해보세요.</p>
            </div>

            <div class="space-y-4 max-w-2xl mx-auto">
                <div>
                    <label for="ideaInput" class="block text-sm font-semibold text-slate-700 mb-1">
                        만들고 싶은 앱 아이디어
                    </label>
                    <input type="text" id="ideaInput" placeholder="예: 오늘 할 일을 뽀모도로 타이머와 결합한 앱" 
                           class="w-full px-4 py-3 rounded-xl border border-slate-200 focus:outline-none focus:ring-2 focus:ring-indigo-500 transition-all text-sm">
                </div>

                <div>
                    <label for="vibeSelect" class="block text-sm font-semibold text-slate-700 mb-1">
                        원하는 디자인 바이브 (Style Vibe)
                    </label>
                    <select id="vibeSelect" class="w-full px-4 py-3 rounded-xl border border-slate-200 focus:outline-none focus:ring-2 focus:ring-indigo-500 transition-all text-sm bg-white">
                        <option value="모던하고 깔끔한 파스텔 톤 앤 네온">🎨 모던 & 파스텔 앤 네온</option>
                        <option value="사이버펑크 다크 모드 스타일">🌙 다크 모드 & 사이버펑크</option>
                        <option value="미니멀하고 세련된 미드센추리"> minimalist 세련된 미니멀리즘</option>
                        <option value="친근하고 귀여운 레트로 게임 픽셀 스타일">🎮 레트로 게임 스타일</option>
                    </select>
                </div>

                <button onclick="generatePrompt()" 
                        class="w-full py-3.5 bg-indigo-600 hover:bg-indigo-700 text-white font-semibold rounded-xl shadow-lg hover:shadow-indigo-200 transition-all duration-200 flex items-center justify-center gap-2">
                    <i class="fa-solid fa-wand-magic-sparkles"></i> 바이브 프롬프트 생성하기
                </button>
            </div>

            <!-- Result Box -->
            <div id="resultBox" class="hidden mt-8 max-w-2xl mx-auto p-5 bg-slate-900 text-slate-100 rounded-2xl shadow-inner relative">
                <div class="flex justify-between items-center mb-2">
                    <span class="text-xs font-mono text-indigo-400 font-semibold"><i class="fa-solid fa-code"></i> Generated AI Prompt</span>
                    <button onclick="copyPrompt()" class="text-xs bg-slate-800 hover:bg-slate-700 text-slate-300 px-3 py-1 rounded-md transition-all">
                        <i class="fa-regular fa-copy"></i> 복사하기
                    </button>
                </div>
                <p id="promptText" class="text-sm font-mono leading-relaxed text-slate-200 whitespace-pre-wrap"></p>
            </div>
        </section>

    </main>

    <!-- Footer Section -->
    <footer class="bg-slate-900 text-slate-400 py-8 px-4 text-center border-t border-slate-800">
        <div class="max-w-4xl mx-auto space-y-3">
            <p class="text-lg font-bold text-transparent bg-clip-text bg-gradient-to-r from-indigo-400 via-purple-400 to-pink-400">
                " AI디지털을 All바르게 쓰자 "
            </p>
            <p class="text-sm text-slate-500 font-medium">
                ©고은찬
            </p>
        </div>
    </footer>

    <!-- JavaScript logic -->
    <script>
        function generatePrompt() {
            const idea = document.getElementById('ideaInput').value.trim();
            const vibe = document.getElementById('vibeSelect').value;
            const resultBox = document.getElementById('resultBox');
            const promptText = document.getElementById('promptText');

            if (!idea) {
                alert('아이디어를 입력해주세요!');
                return;
            }

            const generated = `[바이브 코딩 요청]\n` +
                `역할: 웹 프론트엔드 전문 개발자\n` +
                `목표: '${idea}' 기능이 완벽하게 동작하는 싱글 페이지 웹앱을 제작해줘.\n` +
                `디자인 바이브: ${vibe}\n` +
                `조건:\n` +
                `- 단일 HTML 파일 내에 CSS(Tailwind CSS)와 JS를 모두 포함해줘.\n` +
                `- 사용자가 사용하기 편리하도록 반응형 디자인과 감각적인 애니메이션을 적용해줘.\n` +
                `- 모든 기능은 실행 가능하고 오류가 없어야 해.`;

            promptText.textContent = generated;
            resultBox.classList.remove('hidden');
        }

        function copyPrompt() {
            const promptText = document.getElementById('promptText').textContent;
            
            // Clipboard copy fall-back handling
            const tempTextArea = document.createElement("textarea");
            tempTextArea.value = promptText;
            document.body.appendChild(tempTextArea);
            tempTextArea.select();
            document.execCommand("copy");
            document.body.removeChild(tempTextArea);

            alert('프롬프트가 클립보드에 복사되었습니다!');
        }
    </script>
</body>
</html># Vibe-coding
