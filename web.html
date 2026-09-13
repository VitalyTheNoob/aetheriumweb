<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Aetherium</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            background-color: #0a0a0a;
            color: #ffffff;
            font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;
            min-height: 100vh;
            position: relative;
            overflow-x: hidden;
            scroll-behavior: smooth;
        }

        /* Top left corner label */
        .top-left-label {
            position: fixed;
            top: 30px;
            left: 40px;
            font-size: 1.2rem;
            font-weight: 700;
            letter-spacing: 0.15em;
            text-transform: uppercase;
            color: #ffffff;
            z-index: 100;
        }

        /* Buttons container */
        .buttons-container {
            position: fixed;
            top: 30px;
            right: 40px;
            display: flex;
            gap: 16px;
            z-index: 100;
        }

        .btn {
            padding: 12px 28px;
            border-radius: 40px;
            font-size: 0.85rem;
            font-weight: 600;
            letter-spacing: 0.08em;
            text-transform: uppercase;
            text-decoration: none;
            cursor: pointer;
            transition: all 0.3s ease;
            border: 1.5px solid transparent;
            white-space: nowrap;
        }

        .btn-primary,
        .btn-outline {
            background-color: transparent;
            color: #ffffff;
            border-color: #ffffff;
        }

        .btn-primary:hover,
        .btn-outline:hover {
            background-color: #ffffff;
            color: #0a0a0a;
        }

        /* Hero */
        .hero-section {
            min-height: 100vh;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            padding: 120px 20px 60px;
            position: relative;
        }

        .main-content {
            display: flex;
            flex-direction: column;
            align-items: center;
            gap: 20px;
            width: 100%;
            max-width: 900px;
        }

        .main-heading {
            font-size: clamp(3rem, 12vw, 10rem);
            font-weight: 800;
            letter-spacing: -0.03em;
            text-transform: uppercase;
            text-align: center;
            line-height: 1;
            animation: fadeIn 1.2s ease-out;
        }

        .subtitle-wrapper {
            display: flex;
            justify-content: center;
            align-items: center;
            height: 1.8em;
            margin-bottom: 18px;
            animation: fadeIn 1.3s ease-out;
        }

        .subtitle {
            font-size: 1rem;
            font-weight: 500;
            letter-spacing: 0.24em;
            text-transform: uppercase;
            color: #999;
            text-align: center;
            white-space: nowrap;
            transition: opacity 0.5s ease, transform 0.5s ease;
            opacity: 1;
            transform: translateY(0);
        }

        .subtitle.fade-out {
            opacity: 0;
            transform: translateY(-10px);
        }

        .subtitle.fade-in {
            opacity: 0;
            transform: translateY(10px);
        }

        @keyframes fadeIn {
            from { opacity: 0; transform: translateY(30px); }
            to { opacity: 1; transform: translateY(0); }
        }

        /* Loadstring row */
        .loadstring-row {
            display: flex;
            align-items: center;
            gap: 16px;
            width: 100%;
            max-width: 580px;
            animation: fadeIn 1.4s ease-out;
        }

        .loadstring-box {
            flex: 1;
            background-color: #1a1a1a;
            border: 1.5px solid #2e2e2e;
            border-radius: 12px;
            padding: 13px 18px;
            font-family: 'SF Mono', 'Fira Code', 'Consolas', 'Monaco', monospace;
            font-size: 0.88rem;
            color: #e0e0e0;
            transition: border-color 0.3s ease, box-shadow 0.3s ease;
            display: flex;
            align-items: center;
            gap: 10px;
            min-width: 0;
            box-shadow: 0 6px 20px rgba(0, 0, 0, 0.4);
        }

        .loadstring-box:hover,
        .loadstring-box:focus-within {
            border-color: #555;
            box-shadow: 0 6px 26px rgba(0, 0, 0, 0.6);
        }

        .prompt {
            color: #6a9955;
            font-weight: 600;
            user-select: none;
            flex-shrink: 0;
            font-size: 0.88rem;
        }

        /* Read-only loadstring display */
        .loadstring-input {
            background: transparent;
            border: none;
            outline: none;
            color: #e0e0e0;
            font-family: inherit;
            font-size: inherit;
            width: 100%;
            letter-spacing: 0.01em;
            min-width: 0;
            cursor: text;
            user-select: all;
            overflow: hidden;
            text-overflow: ellipsis;
            white-space: nowrap;
        }

        /* Icon buttons */
        .icon-btn {
            width: 44px;
            height: 44px;
            flex-shrink: 0;
            border-radius: 12px;
            border: 1.5px solid #2e2e2e;
            background-color: #1a1a1a;
            color: #e0e0e0;
            display: flex;
            align-items: center;
            justify-content: center;
            cursor: pointer;
            transition: all 0.25s ease;
            text-decoration: none;
            box-shadow: 0 6px 20px rgba(0, 0, 0, 0.4);
            padding: 0;
        }

        .icon-btn svg {
            width: 20px;
            height: 20px;
            fill: currentColor;
            transition: fill 0.25s ease;
        }

        .icon-btn:hover {
            border-color: #555;
            background-color: #222;
            transform: translateY(-2px);
        }

        .icon-btn:active {
            transform: translateY(0) scale(0.94);
        }

        .copy-btn:hover { color: #4fc3f7; border-color: #4fc3f7; }
        .discord-btn:hover { color: #5865F2; border-color: #5865F2; }
        .copy-btn.copied { color: #6a9955; border-color: #6a9955; }

        .status-msg {
            font-size: 0.8rem;
            color: #6a9955;
            font-family: 'SF Mono', 'Fira Code', 'Consolas', monospace;
            letter-spacing: 0.02em;
            min-height: 1.2em;
            text-align: center;
            animation: fadeIn 0.4s ease-out;
        }

        /* ---- Thin horizontal dividers ---- */
        .thin-divider {
            height: 1px;
            width: 100%;
            max-width: 1100px;
            margin: 0 auto;
            background-color: #1e1e1e;
        }

        .thin-divider-top {
            height: 1px;
            width: 100%;
            max-width: 1100px;
            margin: 100px auto 0;
            background-color: #1e1e1e;
        }

        .divider-under-loadstring {
            height: 1px;
            width: 100%;
            max-width: 580px;
            margin: 60px auto 0;
            background-color: #1e1e1e;
            animation: fadeIn 1.5s ease-out;
        }

        .divider-above-games {
            height: 1px;
            width: 100%;
            max-width: 580px;
            margin: 0 auto 40px;
            background-color: #1e1e1e;
            animation: fadeIn 1.6s ease-out;
        }

        /* ---- Executors block ---- */
        .executors-block {
            width: 100%;
            max-width: 700px;
            margin: 40px auto 0;
            display: flex;
            flex-direction: column;
            align-items: center;
            gap: 32px;
            animation: fadeIn 1.5s ease-out;
        }

        .executors-label {
            font-size: 1rem;
            font-weight: 500;
            letter-spacing: 0.24em;
            text-transform: uppercase;
            color: #666;
            text-align: center;
        }

        .executors-row {
            display: flex;
            align-items: center;
            justify-content: center;
            gap: 44px;
            flex-wrap: wrap;
        }

        .executor {
            display: flex;
            align-items: center;
            gap: 12px;
            color: #ccc;
            font-size: 1.4rem;
            font-weight: 700;
            letter-spacing: -0.01em;
            transition: color 0.25s ease, transform 0.25s ease;
            text-decoration: none;
            cursor: pointer;
        }

        .executor:hover {
            color: #ffffff;
            transform: translateY(-2px);
        }

        .executor:active {
            transform: translateY(0) scale(0.97);
        }

        .executor-icon {
            width: 34px;
            height: 34px;
            display: flex;
            align-items: center;
            justify-content: center;
            flex-shrink: 0;
        }

        .executor-icon img {
            width: 100%;
            height: 100%;
            object-fit: contain;
            display: block;
        }

        /* Madium icon — a tiny bit bigger */
        .executor.madium .executor-icon {
            width: 37px;
            height: 37px;
        }

        /* "and more" text */
        .and-more {
            font-size: 0.85rem;
            font-weight: 400;
            letter-spacing: 0.18em;
            text-transform: lowercase;
            color: #555;
            text-align: center;
            margin-top: 4px;
            animation: fadeIn 1.6s ease-out;
        }

        /* Games section */
        .games-section {
            padding: 80px 20px 100px;
            max-width: 1100px;
            margin: 0 auto;
            display: flex;
            flex-direction: column;
            align-items: center;
            gap: 60px;
        }

        .games-heading {
            font-size: clamp(2rem, 6vw, 4.5rem);
            font-weight: 800;
            letter-spacing: -0.02em;
            text-transform: uppercase;
            text-align: center;
            line-height: 1.1;
        }

        .games-sub {
            font-size: clamp(0.9rem, 1.5vw, 1.15rem);
            font-weight: 500;
            letter-spacing: 0.22em;
            text-transform: uppercase;
            color: #777;
            text-align: center;
            margin-top: -40px;
        }

        .game-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
            gap: 32px;
            width: 100%;
        }

        .game-card {
            display: flex;
            flex-direction: column;
            gap: 16px;
            background-color: #141414;
            border: 1.5px solid #2a2a2a;
            border-radius: 18px;
            padding: 18px;
            transition: all 0.3s ease;
        }

        .game-card:hover {
            border-color: #444;
            background-color: #1a1a1a;
            transform: translateY(-6px);
        }

        .game-image {
            width: 100%;
            aspect-ratio: 16 / 9;
            border-radius: 12px;
            overflow: hidden;
            background-color: #0f0f0f;
            position: relative;
        }

        .game-image img {
            width: 100%;
            height: 100%;
            object-fit: cover;
            display: block;
            transition: transform 0.4s ease;
        }

        .game-card:hover .game-image img {
            transform: scale(1.05);
        }

        .game-title-row {
            display: flex;
            align-items: center;
            justify-content: space-between;
            gap: 12px;
            padding: 0 4px;
        }

        .game-name {
            font-size: 1.15rem;
            font-weight: 700;
            letter-spacing: -0.01em;
        }

        .status-dot {
            width: 12px;
            height: 12px;
            border-radius: 50%;
            flex-shrink: 0;
        }

        .dot-green {
            background-color: #22c55e;
            box-shadow: 0 0 10px rgba(34, 197, 94, 0.7);
        }

        .dot-orange {
            background-color: #f59e0b;
            box-shadow: 0 0 10px rgba(245, 158, 11, 0.7);
        }

        .dot-red {
            background-color: #ef4444;
            box-shadow: 0 0 10px rgba(239, 68, 68, 0.7);
        }

        .footer {
            padding: 60px 20px;
            text-align: center;
            color: #555;
            font-size: 0.78rem;
            letter-spacing: 0.15em;
            text-transform: uppercase;
        }

        /* Responsive */
        @media (max-width: 768px) {
            .top-left-label { top: 20px; left: 20px; font-size: 0.9rem; }
            .buttons-container { top: 20px; right: 20px; gap: 10px; }
            .btn { padding: 10px 18px; font-size: 0.72rem; }
            .main-heading { font-size: clamp(2.5rem, 15vw, 6rem); }
            .subtitle { font-size: 0.82rem; letter-spacing: 0.2em; }
            .loadstring-box { padding: 11px 14px; font-size: 0.78rem; }
            .icon-btn { width: 40px; height: 40px; border-radius: 10px; }
            .icon-btn svg { width: 18px; height: 18px; }
            .loadstring-row { gap: 12px; }
            .thin-divider-top { margin-top: 80px; }
            .divider-under-loadstring { margin-top: 40px; }
            .divider-above-games { margin-bottom: 30px; }
            .executors-row { gap: 30px; }
            .executor { font-size: 1.15rem; }
            .executor-icon { width: 28px; height: 28px; }
            .executor.madium .executor-icon { width: 31px; height: 31px; }
            .and-more { font-size: 0.78rem; }
            .games-section { padding: 60px 20px 80px; gap: 40px; }
            .game-grid { gap: 22px; }
        }

        @media (max-width: 480px) {
            .buttons-container { flex-direction: column; gap: 8px; }
            .btn { padding: 8px 16px; font-size: 0.68rem; }
            .loadstring-row { gap: 10px; }
            .loadstring-box { padding: 9px 12px; font-size: 0.72rem; }
            .icon-btn { width: 36px; height: 36px; border-radius: 10px; }
            .icon-btn svg { width: 16px; height: 16px; }
            .subtitle { font-size: 0.68rem; letter-spacing: 0.16em; white-space: normal; }
            .thin-divider-top { margin-top: 60px; }
            .divider-under-loadstring { margin-top: 30px; }
            .divider-above-games { margin-bottom: 20px; }
            .executors-row { gap: 22px; }
            .executor { font-size: 1rem; }
            .executor-icon { width: 24px; height: 24px; }
            .executor.madium .executor-icon { width: 27px; height: 27px; }
            .and-more { font-size: 0.72rem; }
        }
    </style>
</head>
<body>

    <div class="top-left-label">Aetherium</div>

    <div class="buttons-container">
        <a href="#" class="btn btn-primary">Get a Key</a>
        <a href="#" class="btn btn-outline">Shop</a>
    </div>

    <!-- Top thin divider (full width) -->
    <div class="thin-divider-top"></div>

    <!-- Hero -->
    <section class="hero-section">
        <div class="main-content">
            <h1 class="main-heading">Aetherium</h1>

            <div class="subtitle-wrapper">
                <p class="subtitle" id="subtitle">The #1 Roblox utility for Doors</p>
            </div>

            <div class="loadstring-row">
                <div class="loadstring-box">
                    <span class="prompt">&gt;</span>
                    <span
                        class="loadstring-input"
                        id="loadstringValue"
                        title="Click to select, use the copy button to copy"
                    >loadstring(game:HttpGet("https://raw.githubusercontent.com/VitalyTheNoob/Aetherium/refs/heads/main/full"))()</span>
                </div>

                <button class="icon-btn copy-btn" id="copyBtn" title="Copy loadstring" onclick="copyLoadstring()">
                    <svg viewBox="0 0 24 24"><path d="M16 4h2a2 2 0 0 1 2 2v14a2 2 0 0 1-2 2H6a2 2 0 0 1-2-2V6a2 2 0 0 1 2-2h2a2 2 0 0 1 2-2h4a2 2 0 0 1 2 2zM9 4v2h6V4H9zm-1 4a1 1 0 0 0-1 1v10a1 1 0 0 0 1 1h8a1 1 0 0 0 1-1V9a1 1 0 0 0-1-1H8z"/></svg>
                </button>

                <a class="icon-btn discord-btn" href="https://discord.gg/3xtWKJ2kmg" target="_blank" rel="noopener noreferrer" title="Join our Discord">
                    <svg viewBox="0 0 24 24"><path d="M20.317 4.369A19.79 19.79 0 0 0 16.558 3c-.2.357-.43.838-.59 1.222a18.27 18.27 0 0 0-5.936 0A12.4 12.4 0 0 0 9.44 3 19.74 19.74 0 0 0 5.68 4.37C2.905 8.484 2.15 12.5 2.53 16.457a19.9 19.9 0 0 0 6.03 3.043c.487-.667.923-1.375 1.297-2.12a12.9 12.9 0 0 1-2.042-.98c.171-.126.339-.257.5-.393a14.2 14.2 0 0 0 12.19 0c.163.138.33.268.5.393-.65.386-1.335.716-2.045.983.375.744.81 1.45 1.298 2.117a19.86 19.86 0 0 0 6.03-3.043c.447-4.579-.766-8.56-3.17-12.088zM8.68 14.075c-1.184 0-2.157-1.086-2.157-2.42 0-1.334.955-2.42 2.157-2.42 1.21 0 2.176 1.095 2.157 2.42 0 1.334-.955 2.42-2.157 2.42zm6.64 0c-1.184 0-2.157-1.086-2.157-2.42 0-1.334.955-2.42 2.157-2.42 1.21 0 2.176 1.095 2.157 2.42 0 1.334-.947 2.42-2.157 2.42z"/></svg>
                </a>
            </div>

            <div class="status-msg" id="statusMsg"></div>

            <!-- Small divider under the loadstring row -->
            <div class="divider-under-loadstring"></div>

            <!-- Executors block -->
            <div class="executors-block">
                <div class="executors-label">Supporting the Best Executors</div>

                <div class="executors-row">
                    <!-- Madium -->
                    <a class="executor madium" href="https://getmadium.net" target="_blank" rel="noopener noreferrer">
                        <div class="executor-icon">
                            <img src="https://www.msdoors.xyz/_next/image?url=%2Fexecutors%2Fmadium.png&w=64&q=75" alt="Madium" />
                        </div>
                        <span>Madium</span>
                    </a>

                    <!-- Real -->
                    <a class="executor" href="https://projectreal.gg" target="_blank" rel="noopener noreferrer">
                        <div class="executor-icon">
                            <img src="https://www.msdoors.xyz/_next/image?url=%2Fexecutors%2Freal.png&w=64&q=75" alt="Real" />
                        </div>
                        <span>Real</span>
                    </a>

                    <!-- Wave -->
                    <a class="executor" href="https://getwave.gg" target="_blank" rel="noopener noreferrer">
                        <div class="executor-icon">
                            <img src="https://www.msdoors.xyz/_next/image?url=%2Fexecutors%2Fwave.png&w=32&q=75" alt="Wave" />
                        </div>
                        <span>Wave</span>
                    </a>

                    <!-- Delta -->
                    <a class="executor" href="https://deltaexploits.gg" target="_blank" rel="noopener noreferrer">
                        <div class="executor-icon">
                            <img src="https://q2p0njok3b.ufs.sh/f/Z155p1jPvLAslPmgsgFtT6a830HkYDKeuAh9RwMGsqd24CQZ" alt="Delta" />
                        </div>
                        <span>Delta</span>
                    </a>
                </div>

                <!-- "and more" small text -->
                <div class="and-more">and more</div>
            </div>
        </div>
    </section>

    <!-- Games -->
    <section class="games-section">
        <!-- Small divider above the games heading -->
        <div class="divider-above-games"></div>

        <h2 class="games-heading">Aetherium Supports 3 Games!</h2>
        <p class="games-sub">But we're still expanding!</p>

        <div class="game-grid">
            <!-- Doors -->
            <div class="game-card">
                <div class="game-image">
                    <img src="https://i.imgur.com/fkx4J4d.png" alt="Roblox Doors" loading="lazy" />
                </div>
                <div class="game-title-row">
                    <span class="game-name">Doors</span>
                    <span class="status-dot dot-orange" title="Partial support"></span>
                </div>
            </div>

            <!-- Jujutsu Shenanigans -->
            <div class="game-card">
                <div class="game-image">
                    <img src="https://i.imgur.com/yq3VCo5.png" alt="Jujutsu Shenanigans" loading="lazy" />
                </div>
                <div class="game-title-row">
                    <span class="game-name">Jujutsu Shenanigans</span>
                    <span class="status-dot dot-green" title="Supported"></span>
                </div>
            </div>

            <!-- Deagle Duels -->
            <div class="game-card">
                <div class="game-image">
                    <img src="https://i.imgur.com/4XnSidw.png" alt="Deagle Duels" loading="lazy" />
                </div>
                <div class="game-title-row">
                    <span class="game-name">Deagle Duels</span>
                    <span class="status-dot dot-green" title="Supported"></span>
                </div>
            </div>
        </div>
    </section>

    <div class="thin-divider"></div>

    <footer class="footer">
        © 2026 Aetherium - Not Affiliated with Roblox
    </footer>

    <script>
        // Rotating subtitle
        const subtitleEl = document.getElementById('subtitle');
        const subtitles = [
            'The #1 Roblox utility for Doors',
            'The #1 Roblox utility for Jujutsu Shenanigans',
            'The #1 Roblox utility for Deagle Duels'
        ];
        let currentIndex = 0;

        function rotateSubtitle() {
            subtitleEl.classList.add('fade-out');
            subtitleEl.classList.remove('fade-in');
            setTimeout(() => {
                currentIndex = (currentIndex + 1) % subtitles.length;
                subtitleEl.textContent = subtitles[currentIndex];
                subtitleEl.classList.remove('fade-out');
                subtitleEl.classList.add('fade-in');
                void subtitleEl.offsetWidth;
                subtitleEl.classList.remove('fade-in');
            }, 500);
        }
        setInterval(rotateSubtitle, 3000);

        // Fixed loadstring (cannot be edited by user)
        const FIXED_LOADSTRING = 'loadstring(game:HttpGet("https://raw.githubusercontent.com/VitalyTheNoob/Aetherium/refs/heads/main/full"))()';

        // Copy loadstring
        function copyLoadstring() {
            const copyBtn = document.getElementById('copyBtn');
            const status = document.getElementById('statusMsg');

            navigator.clipboard.writeText(FIXED_LOADSTRING).then(() => {
                copyBtn.classList.add('copied');
                status.style.color = '#6a9955';
                status.textContent = '✓ Loadstring copied!';
                setTimeout(() => {
                    copyBtn.classList.remove('copied');
                    status.textContent = '';
                }, 1800);
            }).catch(() => {
                // Fallback
                const temp = document.createElement('textarea');
                temp.value = FIXED_LOADSTRING;
                document.body.appendChild(temp);
                temp.select();
                document.execCommand('copy');
                document.body.removeChild(temp);

                copyBtn.classList.add('copied');
                status.style.color = '#6a9955';
                status.textContent = '✓ Loadstring copied!';
                setTimeout(() => {
                    copyBtn.classList.remove('copied');
                    status.textContent = '';
                }, 1800);
            });
        }
    </script>

</body>
</html>
