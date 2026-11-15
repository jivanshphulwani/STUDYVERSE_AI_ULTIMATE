
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<meta name="theme-color" content="#635bff">
<title>STUDYVERSE AI — Your Learning Space</title>
<style>
:root{--bg:#f5f6fc;--panel:#fff;--text:#20223a;--muted:#777b93;--line:#e9eaf2;--primary:#635bff;--primary2:#817bff;--soft:#efefff;--green:#159b72;--shadow:0 12px 34px rgba(31,35,90,.07)}
*{box-sizing:border-box}body{margin:0;background:var(--bg);color:var(--text);font:15px/1.5 Inter,ui-sans-serif,system-ui,-apple-system,Segoe UI,Arial,sans-serif;transition:.2s}
body.dark{--bg:#111321;--panel:#1b1e30;--text:#f2f3ff;--muted:#a1a5bd;--line:#30344b;--soft:#29284c;--shadow:0 12px 34px rgba(0,0,0,.2)}
button,input,select,textarea{font:inherit}button{cursor:pointer;border:0}.app{display:grid;grid-template-columns:250px 1fr;min-height:100vh}
aside{background:var(--panel);border-right:1px solid var(--line);padding:26px 17px;position:sticky;top:0;height:100vh}
.brand{display:flex;align-items:center;gap:10px;padding:0 10px 30px;font-weight:850;font-size:19px;letter-spacing:-.5px}.brand-mark{width:36px;height:36px;border-radius:12px;background:linear-gradient(135deg,#635bff,#a36cff);display:grid;place-items:center;color:white;font-size:20px}
.nav-label{color:var(--muted);font-size:10px;font-weight:800;letter-spacing:1.5px;padding:12px 12px 8px}.nav{display:grid;gap:5px}.nav button{background:transparent;color:var(--muted);text-align:left;padding:11px 13px;border-radius:11px;font-weight:650;display:flex;align-items:center;gap:12px}.nav button span{width:20px;text-align:center;font-size:17px}.nav button.active,.nav button:hover{background:var(--soft);color:var(--primary)}
.sidebar-bottom{position:absolute;bottom:20px;left:17px;right:17px;background:var(--soft);border-radius:15px;padding:15px}.sidebar-bottom strong{display:block;font-size:13px}.sidebar-bottom small{color:var(--muted)}
main{padding:28px clamp(18px,4vw,52px);max-width:1500px;width:100%;margin:auto}.topbar{display:flex;justify-content:space-between;align-items:center;gap:16px;margin-bottom:30px}.welcome small{color:var(--muted)}h1{font-size:27px;line-height:1.2;margin:3px 0 0;letter-spacing:-.8px}.top-actions{display:flex;align-items:center;gap:10px}.pill{border:1px solid var(--line);background:var(--panel);color:var(--text);border-radius:12px;padding:9px 12px}.avatar{width:39px;height:39px;border-radius:50%;display:grid;place-items:center;background:#e5e3ff;color:#5148db;font-weight:800}
.page{display:none}.page.active{display:block}.hero{background:linear-gradient(115deg,#5148e8,#8277ff 65%,#a28bff);border-radius:22px;padding:28px 30px;color:white;display:flex;justify-content:space-between;align-items:center;gap:20px;overflow:hidden;position:relative;box-shadow:var(--shadow)}.hero:after{content:"✦";position:absolute;font-size:170px;right:10%;top:-62px;color:#ffffff18}.hero h2{font-size:25px;margin:0 0 7px}.hero p{margin:0 0 18px;color:#eeedff;max-width:500px}.hero .btn{background:white;color:#554ce6}.hero-art{font-size:78px;z-index:1;padding:0 28px}
.btn{background:var(--primary);color:white;padding:10px 15px;border-radius:10px;font-weight:700;transition:.2s}.btn:hover{filter:brightness(1.08);transform:translateY(-1px)}.btn.secondary{background:var(--soft);color:var(--primary)}.btn.ghost{background:transparent;color:var(--muted);border:1px solid var(--line)}.btn.danger{background:#fff0f0;color:#d34d59}
.section-head{display:flex;justify-content:space-between;align-items:center;margin:27px 0 14px;gap:12px}.section-head h2{font-size:17px;margin:0}.section-head p{color:var(--muted);margin:3px 0 0;font-size:13px}
.stats{display:grid;grid-template-columns:repeat(4,1fr);gap:14px;margin-top:20px}.stat,.card{background:var(--panel);border:1px solid var(--line);border-radius:16px;padding:18px;box-shadow:var(--shadow)}.stat-top{display:flex;justify-content:space-between;color:var(--muted);font-size:12px;font-weight:650}.stat-icon{width:34px;height:34px;border-radius:10px;background:var(--soft);display:grid;place-items:center;font-size:17px}.stat strong{font-size:26px;display:block;margin-top:8px}.stat small{color:var(--muted)}
.grid2{display:grid;grid-template-columns:1.3fr 1fr;gap:16px}.grid3{display:grid;grid-template-columns:repeat(3,1fr);gap:14px}.task-row{display:flex;align-items:center;gap:11px;padding:11px 0;border-bottom:1px solid var(--line)}.task-row:last-child{border:0}.task-row input{accent-color:var(--primary);width:17px;height:17px}.task-row .task-name{flex:1}.task-row.done .task-name{text-decoration:line-through;color:var(--muted)}.tag{font-size:11px;padding:4px 8px;border-radius:20px;background:var(--soft);color:var(--primary);font-weight:700}
.progress{height:8px;background:var(--line);border-radius:20px;overflow:hidden;margin:12px 0}.progress span{height:100%;display:block;background:linear-gradient(90deg,#635bff,#a38cff);border-radius:20px}
.feature{padding:18px;border:1px solid var(--line);background:var(--panel);border-radius:16px;cursor:pointer;transition:.2s}.feature:hover{transform:translateY(-3px);box-shadow:var(--shadow);border-color:#c8c4ff}.feature .emoji{font-size:25px}.feature h3{margin:10px 0 4px;font-size:15px}.feature p{margin:0;color:var(--muted);font-size:12px}
.panel{background:var(--panel);border:1px solid var(--line);border-radius:16px;padding:20px;box-shadow:var(--shadow)}.panel h3{margin:0 0 5px;font-size:16px}.muted{color:var(--muted)}.form-row{display:flex;gap:10px;flex-wrap:wrap}.field{width:100%;background:var(--bg);color:var(--text);border:1px solid var(--line);padding:11px 12px;border-radius:10px;outline:none}.field:focus{border-color:var(--primary)}.form-row .field{flex:1;min-width:140px}.stack{display:grid;gap:12px}.empty{text-align:center;color:var(--muted);padding:25px 10px}
.chat-box{height:310px;overflow:auto;background:var(--bg);border:1px solid var(--line);border-radius:13px;padding:14px;display:flex;flex-direction:column;gap:12px;margin:14px 0}.bubble{max-width:85%;padding:11px 13px;border-radius:13px;background:var(--panel);border:1px solid var(--line)}.bubble.me{align-self:flex-end;background:var(--soft);border-color:transparent}.bubble strong{font-size:11px;color:var(--primary);display:block;margin-bottom:3px}.notice{background:#fff8e6;color:#795b16;border:1px solid #f3e4b6;padding:11px 13px;border-radius:10px;font-size:12px;margin-top:12px}
.quiz-option{display:block;width:100%;text-align:left;background:var(--bg);border:1px solid var(--line);color:var(--text);padding:12px;border-radius:10px;margin:8px 0}.quiz-option:hover{border-color:var(--primary)}.quiz-option.selected{border-color:var(--primary);background:var(--soft)}.flashcard{min-height:190px;display:grid;place-items:center;text-align:center;background:linear-gradient(135deg,var(--soft),var(--panel));border:1px solid var(--line);border-radius:18px;padding:25px;cursor:pointer}.flashcard strong{font-size:22px}.flashcard small{display:block;color:var(--muted);margin-top:10px}
ul.clean{padding-left:19px;color:var(--muted)}.hidden{display:none!important}.footer{text-align:center;color:var(--muted);font-size:11px;padding:30px 0 10px}

.login-screen{min-height:100vh;display:grid;grid-template-columns:1.05fr .95fr;background:var(--bg)}
.login-visual{padding:clamp(30px,7vw,90px);display:flex;flex-direction:column;justify-content:space-between;color:white;background:radial-gradient(circle at 80% 15%,#a79cff 0,transparent 28%),linear-gradient(145deg,#4840d9,#7167f5 58%,#9a83ff);position:relative;overflow:hidden}
.login-visual:after{content:"✦";position:absolute;font-size:330px;right:-40px;bottom:-135px;color:#ffffff16}
.login-brand{font-size:20px;font-weight:900;letter-spacing:.5px;z-index:1}.login-copy{max-width:540px;z-index:1}.login-copy h1{font-size:clamp(36px,5vw,60px);line-height:1.05;letter-spacing:-2px;margin:0 0 18px}.login-copy p{color:#efedff;font-size:17px;max-width:430px}.login-foot{font-size:12px;color:#e4e0ff;z-index:1}
.login-side{display:grid;place-items:center;padding:28px}.login-card{width:min(100%,420px);background:var(--panel);border:1px solid var(--line);border-radius:22px;padding:clamp(24px,4vw,38px);box-shadow:var(--shadow)}.login-card h2{font-size:27px;margin:0 0 5px}.login-card>p{color:var(--muted);margin:0 0 25px;font-size:14px}.login-card label{font-size:13px;font-weight:700}.login-card .field{margin-top:6px}.login-error{color:#d34d59;font-size:12px;min-height:18px}.login-note{font-size:11px;color:var(--muted);margin-top:16px;line-height:1.5}.login-submit{width:100%;padding:13px;margin-top:7px}.login-mini{display:flex;align-items:center;gap:8px;color:var(--muted);font-size:12px;margin-top:18px}.login-mini:before,.login-mini:after{content:"";height:1px;background:var(--line);flex:1}
@media(max-width:760px){.login-screen{grid-template-columns:1fr}.login-visual{min-height:260px;padding:25px}.login-copy h1{font-size:36px}.login-copy p{font-size:14px}.login-foot{display:none}.login-side{padding:22px 16px}.login-card{padding:25px}}
@media(max-width:900px){.app{grid-template-columns:1fr}aside{height:auto;position:relative;padding:12px;border-right:0;border-bottom:1px solid var(--line)}.brand{padding:4px 8px 12px}.nav-label,.sidebar-bottom{display:none}.nav{display:flex;overflow:auto}.nav button{white-space:nowrap;padding:9px 11px}.nav button span{display:none}main{padding-top:20px}.stats{grid-template-columns:repeat(2,1fr)}}
@media(max-width:620px){.topbar{align-items:flex-start}.welcome h1{font-size:22px}.top-actions .pill{display:none}.hero{padding:22px}.hero-art{font-size:48px;padding:0}.hero h2{font-size:21px}.grid2,.grid3{grid-template-columns:1fr}.stats{gap:9px}.stat{padding:13px}.stat strong{font-size:22px}}

.focus-panel{text-align:center;padding:clamp(24px,5vw,48px)}
.focus-mode{font-size:12px;font-weight:850;letter-spacing:2px;color:var(--primary)}
.focus-clock{font-size:clamp(64px,12vw,104px);font-weight:850;letter-spacing:-5px;line-height:1.2;margin:12px 0;font-variant-numeric:tabular-nums}
.focus-progress{max-width:520px;margin:22px auto;height:10px}
.focus-buttons{justify-content:center;margin-top:20px}
.focus-buttons button{min-width:125px}
@media(max-width:620px){.focus-buttons button{flex:1}.focus-clock{letter-spacing:-3px}}

</style>
</head>
<body>
<section class="login-screen" id="loginScreen">
  <div class="login-visual">
    <div class="login-brand">✦ STUDYVERSE AI</div>
    <div class="login-copy"><h1>Make learning your superpower.</h1><p>Your personal space to study smarter, organise homework, practise concepts and reach your goals.</p></div>
    <div class="login-foot">A brighter way to learn · Classes 6–12</div>
  </div>
  <div class="login-side">
    <form class="login-card" id="loginForm">
      <div style="font-size:30px;margin-bottom:12px">👋</div>
      <h2>Welcome back!</h2><p>Sign in to enter your learning space.</p>
      <div class="stack">
        <div><label for="loginName">Your name</label><input class="field" id="loginName" placeholder="Enter your name" autocomplete="name" required></div>
        <div><label for="loginEmail">Email address</label><input class="field" id="loginEmail" type="email" placeholder="you@example.com" autocomplete="email" required></div>
        <div><label for="loginPassword">Password</label><input class="field" id="loginPassword" type="password" placeholder="Enter any password" minlength="4" autocomplete="current-password" required></div>
        <div class="login-error" id="loginError" aria-live="polite"></div>
        <button class="btn login-submit" type="submit">Sign in to Studyverse →</button>
      </div>
      <div class="login-mini">Your learning journey starts here</div>
      <div class="login-note">Demo login: enter your name, email and any password (at least 4 characters). This is a local demo sign-in for this browser, not secure account authentication. Do not use a real password or private information.</div>
    </form>
  </div>
</section>
<div class="app">
<aside>
  <div class="brand"><div class="brand-mark">✦</div> STUDYVERSE <span style="color:var(--primary)">AI</span></div>
  <div class="nav-label">WORKSPACE</div>
  <nav class="nav" id="nav">
    <button class="active" data-page="dashboard"><span>⌂</span>Dashboard</button>
    <button data-page="tutor"><span>✧</span>AI Tutor</button>
    <button data-page="homework"><span>▤</span>Homework</button>
    <button data-page="notes"><span>▧</span>Smart Notes</button>
    <button data-page="quiz"><span>◈</span>Practice Quiz</button>
    <button data-page="flashcards"><span>▣</span>Flashcards</button>
    <button data-page="planner"><span>◷</span>Study Planner</button>
    <button data-page="focus"><span>⏳</span>Focus Timer</button>
  </nav>
  <div class="sidebar-bottom"><strong>Small steps. Big results. 🚀</strong><small>Keep learning, one day at a time.</small></div>
</aside>
<main>
  <header class="topbar">
    <div class="welcome"><small id="dateText">YOUR LEARNING SPACE</small><h1 id="greeting">Welcome back, Student! 👋</h1></div>
    <div class="top-actions">
      <select class="pill" id="classSelect" aria-label="Choose class"><option>Class 6</option><option>Class 7</option><option selected>Class 8</option><option>Class 9</option><option>Class 10</option><option>Class 11</option><option>Class 12</option></select>
      <button class="pill" id="themeBtn" title="Toggle dark mode">☾</button><button class="pill" id="exportBtn" title="Download a backup">↓ Backup</button><button class="pill" id="logoutBtn" title="Sign out">↪ Sign out</button><div class="avatar" id="userAvatar">S</div>
    </div>
  </header>

  <section class="page active" id="dashboard">
    <div class="hero"><div><h2>Your goals are within reach.</h2><p>Learn smarter, stay organised, and make every study session count.</p><button class="btn" onclick="showPage('tutor')">Ask your AI Tutor ↗</button></div><div class="hero-art">📚</div></div>
    <div class="stats">
      <div class="stat"><div class="stat-top">Homework tasks <span class="stat-icon">📝</span></div><strong id="statTasks">0</strong><small>Tasks still to complete</small></div>
      <div class="stat"><div class="stat-top">Completed <span class="stat-icon">✅</span></div><strong id="statDone">0</strong><small>Homework finished</small></div>
      <div class="stat"><div class="stat-top">Study sessions <span class="stat-icon">⏱️</span></div><strong id="statSessions">0</strong><small>Sessions recorded</small></div>
      <div class="stat"><div class="stat-top">Flashcards <span class="stat-icon">🧠</span></div><strong id="statCards">0</strong><small>Cards in your collection</small></div>
    </div>
    <div class="section-head"><div><h2>Your learning tools</h2><p>Everything you need, in one place.</p></div></div>
    <div class="grid3">
      <div class="feature" onclick="showPage('tutor')"><div class="emoji">✨</div><h3>AI Study Tutor</h3><p>Ask questions and explore concepts.</p></div>
      <div class="feature" onclick="showPage('notes')"><div class="emoji">📒</div><h3>Smart Notes</h3><p>Organise your notes into clear points.</p></div>
      <div class="feature" onclick="showPage('quiz')"><div class="emoji">🎯</div><h3>Practice Quiz</h3><p>Test your knowledge with a quick quiz.</p></div>
      <div class="feature" onclick="showPage('homework')"><div class="emoji">📋</div><h3>Homework Tracker</h3><p>Keep track of tasks and deadlines.</p></div>
      <div class="feature" onclick="showPage('flashcards')"><div class="emoji">🗂️</div><h3>Flashcards</h3><p>Review important terms and definitions.</p></div>
      <div class="feature" onclick="showPage('planner')"><div class="emoji">🗓️</div><h3>Study Planner</h3><p>Record focused study sessions.</p></div>
      <div class="feature" onclick="showPage('focus')"><div class="emoji">⏳</div><h3>Focus Timer</h3><p>Use focused study and short breaks.</p></div>
    </div>
    <div class="section-head"><h2>Homework overview</h2><button class="btn secondary" onclick="showPage('homework')">View all</button></div>
    <div class="panel" id="dashboardTasks"><div class="empty">No homework added yet. Add your first task in Homework Tracker.</div></div>
    <div class="footer">STUDYVERSE AI · Learn at your own pace</div>
  </section>

  <section class="page" id="tutor">
    <div class="section-head"><div><h2>✨ AI Study Tutor</h2><p>Ask a question and get a helpful starting point.</p></div></div>
    <div class="panel">
      <h3>What would you like to understand?</h3><p class="muted" style="font-size:13px">Try a school topic, ask for an example, or request a simpler explanation.</p>
      <div class="chat-box" id="chatBox"><div class="bubble"><strong>STUDYVERSE</strong>Hi! I’m your study assistant. Ask me a question to get started. This offline demo gives sample guidance; connect an AI service to enable real AI answers.</div></div>
      <form class="form-row" id="chatForm"><input class="field" id="chatInput" placeholder="E.g. Explain photosynthesis in simple words..." required><button class="btn">Send ↑</button></form>
      <div class="notice">Demo mode: this standalone HTML file does not send your questions to an AI service. Never enter private information here.</div>
    </div>
  </section>

  <section class="page" id="homework">
    <div class="section-head"><div><h2>📝 Homework Tracker</h2><p>Add tasks and tick them off when you finish.</p></div></div>
    <div class="panel">
      <form id="taskForm" class="form-row">
        <input class="field" id="taskInput" placeholder="What homework do you need to do?" required>
        <select class="field" id="subjectInput" style="max-width:160px"><option>Science</option><option>Maths</option><option>English</option><option>Hindi</option><option>SST</option><option>Other</option></select>
        <input class="field" id="dueInput" type="date" aria-label="Due date" style="max-width:165px">
        <button class="btn">+ Add task</button>
      </form>
    </div>
    <div class="section-head"><h2>Your tasks</h2><span class="tag" id="taskCount">0 tasks</span></div>
    <div class="panel" id="taskList"><div class="empty">Your task list is empty. Add a homework task above.</div></div>
  </section>

  <section class="page" id="notes">
    <div class="section-head"><div><h2>📒 Smart Notes</h2><p>Turn rough notes into a neat, readable outline.</p></div></div>
    <div class="panel stack">
      <label for="notesInput"><strong>Paste or type your study notes</strong></label>
      <textarea class="field" id="notesInput" rows="9" placeholder="Paste your chapter notes here..."></textarea>
      <div class="form-row"><button class="btn" id="formatNotes">Organise my notes ✨</button><button class="btn secondary" id="clearNotes">Clear</button></div>
      <div id="notesOutput" class="hidden"><h3>Organised notes</h3><div class="panel" id="notesResult" style="background:var(--bg);white-space:pre-wrap"></div><button class="btn secondary" id="copyNotes" style="margin-top:12px">Copy notes</button></div>
      <div class="notice">This tool organises text locally into headings and bullet points. It does not generate AI summaries or verify facts.</div>
    </div>
  </section>

  <section class="page" id="quiz">
    <div class="section-head"><div><h2>🎯 Practice Quiz</h2><p>Try this quick general science quiz.</p></div><span class="tag" id="quizProgress">Question 1 of 5</span></div>
    <div class="panel" id="quizPanel"><h3 id="questionText"></h3><div id="options"></div><p class="muted" id="quizFeedback"></p><button class="btn" id="nextQuestion" disabled>Next question →</button></div>
    <div class="panel hidden" id="quizResult" style="text-align:center"><div style="font-size:42px">🏆</div><h2>Quiz completed!</h2><p id="scoreText" class="muted"></p><button class="btn" id="restartQuiz">Try again</button></div>
  </section>

  <section class="page" id="flashcards">
    <div class="section-head"><div><h2>🗂️ Flashcards</h2><p>Create cards to revise definitions and key ideas.</p></div></div>
    <div class="panel">
      <form id="cardForm" class="stack"><input class="field" id="cardFront" placeholder="Term or question" required><textarea class="field" id="cardBack" rows="2" placeholder="Definition or answer" required></textarea><button class="btn">+ Create flashcard</button></form>
    </div>
    <div class="section-head"><h2>Revision deck</h2><span class="tag" id="cardCount">0 cards</span></div>
    <div id="cardArea" class="panel"><div class="empty">No flashcards yet. Create your first card above.</div></div>
  </section>

  <section class="page" id="planner">
    <div class="section-head"><div><h2>🗓️ Study Planner</h2><p>Record your focused study sessions and build a steady routine.</p></div></div>
    <div class="grid2">
      <div class="panel"><h3>Log a study session</h3><form id="sessionForm" class="stack" style="margin-top:15px"><input class="field" id="sessionSubject" placeholder="Subject or topic" required><input class="field" id="sessionMinutes" type="number" min="1" max="600" placeholder="Duration in minutes" required><button class="btn">Save session</button></form></div>
      <div class="panel"><h3>Your study progress</h3><div style="font-size:34px;font-weight:800;margin-top:12px" id="totalMinutes">0 min</div><p class="muted">Total recorded study time</p><div class="progress"><span id="studyProgress" style="width:0%"></span></div><small class="muted">Daily goal: 120 minutes</small></div>
    </div>
    <div class="section-head"><h2>Recent sessions</h2></div><div class="panel" id="sessionList"><div class="empty">No sessions recorded yet.</div></div>
  </section>

  <section class="page" id="focus">
    <div class="section-head"><div><h2>⏳ Focus Timer</h2><p>Work in focused blocks, then take a refreshing break.</p></div><span class="tag">Pomodoro</span></div>
    <div class="panel focus-panel">
      <div class="focus-mode" id="focusMode">FOCUS SESSION</div>
      <div class="focus-clock" id="focusClock">25:00</div>
      <p class="muted" id="focusHint">One task at a time. You’ve got this.</p>
      <div class="progress focus-progress"><span id="focusBar" style="width:100%"></span></div>
      <div class="form-row focus-buttons">
        <button class="btn" id="focusStart">Start focus</button>
        <button class="btn secondary" id="focusPause" disabled>Pause</button>
        <button class="btn ghost" id="focusReset">Reset</button>
        <button class="btn ghost" id="focusModeSwitch">Switch to 5-min break</button>
      </div>
      <div class="notice">Tip: Choose one small task before starting. The timer runs only while this page is open.</div>
    </div>
    <div class="grid2" style="margin-top:16px">
      <div class="panel"><h3>How to use focus sessions</h3><ul class="clean"><li>Choose one subject or assignment.</li><li>Focus for 25 minutes without switching tasks.</li><li>Take a 5-minute break.</li><li>Repeat when you feel ready.</li></ul></div>
      <div class="panel"><h3>Today's focus tip</h3><p class="muted">Keep your books, notebook and water ready before you begin. Put distracting tabs away and decide exactly what you want to finish.</p></div>
    </div>
  </section>

</main>
</div>
<script>
const $=id=>document.getElementById(id);
const authUser=()=>{try{return JSON.parse(localStorage.getItem('sv_user')||'null')}catch{return null}};
function enterApp(user){localStorage.setItem('sv_user',JSON.stringify(user));$('loginScreen').classList.add('hidden');document.querySelector('.app').classList.remove('hidden');$('greeting').textContent='Welcome back, '+user.name+'! 👋';$('userAvatar').textContent=(user.name||'S').trim().charAt(0).toUpperCase()}
function signOut(){localStorage.removeItem('sv_user');$('loginForm').reset();$('loginError').textContent='';document.querySelector('.app').classList.add('hidden');$('loginScreen').classList.remove('hidden')}
$('loginForm').addEventListener('submit',e=>{e.preventDefault();const name=$('loginName').value.trim(),email=$('loginEmail').value.trim(),password=$('loginPassword').value;if(!name||!email||password.length<4){$('loginError').textContent='Please enter your name, a valid email and a password of at least 4 characters.';return}enterApp({name,email})});
$('logoutBtn').addEventListener('click',signOut);
$('exportBtn').addEventListener('click',()=>exportStudyData());
const savedUser=authUser();if(savedUser){enterApp(savedUser)}else{document.querySelector('.app').classList.add('hidden')}
const get=(key, fallback=[])=>{try{return JSON.parse(localStorage.getItem('sv_'+key))??fallback}catch{return fallback}};
const save=(key,value)=>localStorage.setItem('sv_'+key,JSON.stringify(value));
let tasks=get('tasks'),cards=get('cards'),sessions=get('sessions');
function showPage(name){if(!authUser()){document.querySelector('.app').classList.add('hidden');$('loginScreen').classList.remove('hidden');return}document.querySelectorAll('.page').forEach(p=>p.classList.toggle('active',p.id===name));document.querySelectorAll('#nav button').forEach(b=>b.classList.toggle('active',b.dataset.page===name));window.scrollTo({top:0,behavior:'smooth'});if(name==='quiz'&&!quizStarted)startQuiz();}
$('nav').addEventListener('click',e=>{const b=e.target.closest('button[data-page]');if(b)showPage(b.dataset.page)});
$('themeBtn').onclick=()=>{document.body.classList.toggle('dark');localStorage.setItem('sv_dark',document.body.classList.contains('dark'))};
if(localStorage.getItem('sv_dark')==='true')document.body.classList.add('dark');
$('classSelect').value=get('class','Class 8');$('classSelect').onchange=e=>save('class',e.target.value);
const now=new Date();$('dateText').textContent=now.toLocaleDateString(undefined,{weekday:'long',month:'long',day:'numeric'}).toUpperCase();
function renderTasks(){
 const pending=tasks.filter(t=>!t.done).length,done=tasks.length-pending;
 $('statTasks').textContent=pending;$('statDone').textContent=done;$('taskCount').textContent=tasks.length+' tasks';
 const html=tasks.length?tasks.map((t,i)=>`<div class="task-row ${t.done?'done':''}"><input type="checkbox" ${t.done?'checked':''} onchange="toggleTask(${i})"><span class="task-name"><strong>${esc(t.name)}</strong><br><small class="muted">${esc(t.subject)}${t.due?' · Due '+esc(t.due):''}</small></span><button class="btn ghost" onclick="deleteTask(${i})" aria-label="Delete task">✕</button></div>`).join(''):'<div class="empty">Your task list is empty. Add a homework task above.</div>';
 $('taskList').innerHTML=html;
 $('dashboardTasks').innerHTML=tasks.length?tasks.slice(0,4).map((t,i)=>`<div class="task-row ${t.done?'done':''}"><input type="checkbox" ${t.done?'checked':''} onchange="toggleTask(${i})"><span class="task-name">${esc(t.name)}</span><span class="tag">${esc(t.subject)}</span></div>`).join(''):'<div class="empty">No homework added yet. Add your first task in Homework Tracker.</div>';
}
function toggleTask(i){tasks[i].done=!tasks[i].done;save('tasks',tasks);renderTasks()}
function deleteTask(i){tasks.splice(i,1);save('tasks',tasks);renderTasks()}
$('taskForm').onsubmit=e=>{e.preventDefault();tasks.unshift({name:$('taskInput').value.trim(),subject:$('subjectInput').value,due:$('dueInput').value,done:false});save('tasks',tasks);$('taskInput').value='';$('dueInput').value='';renderTasks()};
function esc(s){return String(s).replace(/[&<>"']/g,c=>({'&':'&amp;','<':'&lt;','>':'&gt;','"':'&quot;',"'":'&#39;'}[c]))}
function renderCards(){ $('statCards').textContent=cards.length;$('cardCount').textContent=cards.length+' cards';$('cardArea').innerHTML=cards.length?`<div class="flashcard" id="flashcard" onclick="flipCard()"><div><strong id="flashText"></strong><small id="flashHint">Click to reveal answer</small></div></div><div class="form-row" style="justify-content:space-between;margin-top:13px"><button class="btn secondary" onclick="prevCard()">← Previous</button><span class="muted" id="cardPosition" style="align-self:center"></span><button class="btn secondary" onclick="nextCard()">Next →</button></div><button class="btn danger" onclick="deleteCard()" style="margin-top:13px">Delete this card</button>`:'<div class="empty">No flashcards yet. Create your first card above.</div>';if(cards.length)showCard()}
let cardIndex=0,flipped=false;
function showCard(){if(!cards.length)return;flipped=false;$('flashText').textContent=cards[cardIndex].front;$('flashHint').textContent='Click to reveal answer';$('cardPosition').textContent=(cardIndex+1)+' / '+cards.length}
function flipCard(){if(!cards.length)return;flipped=!flipped;$('flashText').textContent=flipped?cards[cardIndex].back:cards[cardIndex].front;$('flashHint').textContent=flipped?'Click to see question':'Click to reveal answer'}
function nextCard(){cardIndex=(cardIndex+1)%cards.length;showCard()}function prevCard(){cardIndex=(cardIndex-1+cards.length)%cards.length;showCard()}
function deleteCard(){cards.splice(cardIndex,1);cardIndex=Math.max(0,cardIndex-1);save('cards',cards);renderCards()}
$('cardForm').onsubmit=e=>{e.preventDefault();cards.push({front:$('cardFront').value.trim(),back:$('cardBack').value.trim()});save('cards',cards);$('cardForm').reset();renderCards()};
$('formatNotes').onclick=()=>{const raw=$('notesInput').value.trim();if(!raw){alert('Please enter some notes first.');return}const lines=raw.split(/\n+/).map(x=>x.trim()).filter(Boolean);const formatted=lines.map((line,i)=>{let clean=line.replace(/^[-*•]\s*/,'');return (i===0?'📌 ':'• ')+clean}).join('\n');$('notesResult').textContent='STUDY NOTES\n\n'+formatted;$('notesOutput').classList.remove('hidden')};
$('clearNotes').onclick=()=>{$('notesInput').value='';$('notesOutput').classList.add('hidden')};
$('copyNotes').onclick=async()=>{try{await navigator.clipboard.writeText($('notesResult').textContent);$('copyNotes').textContent='Copied! ✓'}catch{alert('Copy is not available in this browser.')}};
const quiz=[{q:'Which part of a plant mainly absorbs water from the soil?',o:['Flower','Roots','Leaves','Stem'],a:1,e:'Roots absorb water and minerals from the soil.'},{q:'What is the SI unit of force?',o:['Joule','Watt','Newton','Pascal'],a:2,e:'Force is measured in newtons (N).'}, {q:'Which gas do plants take in during photosynthesis?',o:['Oxygen','Nitrogen','Carbon dioxide','Hydrogen'],a:2,e:'Plants use carbon dioxide and water to make food.'},{q:'How many sides does a hexagon have?',o:['Five','Six','Seven','Eight'],a:1,e:'A hexagon has six sides.'},{q:'Which organ pumps blood around the human body?',o:['Lungs','Brain','Heart','Kidney'],a:2,e:'The heart pumps blood through the circulatory system.'}];
let qi=0,score=0,answered=false,quizStarted=false;
function startQuiz(){quizStarted=true;qi=0;score=0;$('quizPanel').classList.remove('hidden');$('quizResult').classList.add('hidden');renderQuestion()}
function renderQuestion(){answered=false;$('quizProgress').textContent=`Question ${qi+1} of ${quiz.length}`;$('questionText').textContent=quiz[qi].q;$('quizFeedback').textContent='';$('nextQuestion').disabled=true;$('nextQuestion').textContent=qi===quiz.length-1?'See results':'Next question →';$('options').innerHTML=quiz[qi].o.map((o,i)=>`<button class="quiz-option" onclick="answerQuiz(${i})">${String.fromCharCode(65+i)}. ${o}</button>`).join('')}
function answerQuiz(i){if(answered)return;answered=true;const correct=i===quiz[qi].a;if(correct)score++;document.querySelectorAll('.quiz-option')[i].classList.add('selected');$('quizFeedback').textContent=(correct?'Correct! ✓ ':'Not quite. ')+quiz[qi].e;$('nextQuestion').disabled=false}
$('nextQuestion').onclick=()=>{if(qi<quiz.length-1){qi++;renderQuestion()}else{$('quizPanel').classList.add('hidden');$('quizResult').classList.remove('hidden');$('scoreText').textContent=`You scored ${score} out of ${quiz.length}. Keep practising!`}};
$('restartQuiz').onclick=startQuiz;
$('sessionForm').onsubmit=e=>{e.preventDefault();sessions.unshift({subject:$('sessionSubject').value.trim(),minutes:Number($('sessionMinutes').value),date:new Date().toLocaleDateString()});save('sessions',sessions);$('sessionForm').reset();renderSessions()};
function renderSessions(){const total=sessions.reduce((a,s)=>a+s.minutes,0);$('statSessions').textContent=sessions.length;$('totalMinutes').textContent=total+' min';$('studyProgress').style.width=Math.min(100,total/120*100)+'%';$('sessionList').innerHTML=sessions.length?sessions.slice(0,10).map(s=>`<div class="task-row"><span class="task-name"><strong>${esc(s.subject)}</strong><br><small class="muted">${esc(s.date)}</small></span><span class="tag">${s.minutes} min</span></div>`).join(''):'<div class="empty">No sessions recorded yet.</div>'}
function tutorReply(q){const s=q.toLowerCase();if(s.includes('photosynthesis'))return 'Photosynthesis is the process by which green plants make their own food. They use sunlight, water and carbon dioxide to produce glucose and release oxygen. Think of leaves as tiny food-making factories!';if(s.includes('force'))return 'A force is a push or a pull acting on an object. It can change an object’s speed, direction or shape. The SI unit of force is the newton (N).';if(s.includes('fraction'))return 'A fraction represents a part of a whole. The top number is the numerator and the bottom number is the denominator. For example, 3/4 means 3 out of 4 equal parts.';if(s.includes('water cycle'))return 'The water cycle is the continuous movement of water. Its main stages are evaporation, condensation, precipitation and collection.';return 'Good question! To study this topic, first identify its key definition, then learn the main points and one example. Try writing the concept in your own words. This offline demo has a few sample explanations; connect an AI service for answers to other questions.'}
$('chatForm').onsubmit=e=>{e.preventDefault();const q=$('chatInput').value.trim();if(!q)return;const box=$('chatBox');box.insertAdjacentHTML('beforeend',`<div class="bubble me"><strong>YOU</strong>${esc(q)}</div>`);box.insertAdjacentHTML('beforeend',`<div class="bubble"><strong>STUDYVERSE</strong>${esc(tutorReply(q))}</div>`);$('chatInput').value='';box.scrollTop=box.scrollHeight};
function renderAll(){renderTasks();renderCards();renderSessions()}
renderAll();

// Pomodoro focus timer
let focusMode='focus', focusDuration=25*60, focusRemaining=25*60, focusInterval=null;
function paintFocus(){
  const m=String(Math.floor(focusRemaining/60)).padStart(2,'0');
  const s=String(focusRemaining%60).padStart(2,'0');
  $('focusClock').textContent=m+':'+s;
  $('focusMode').textContent=focusMode==='focus'?'FOCUS SESSION':'SHORT BREAK';
  $('focusHint').textContent=focusMode==='focus'?'One task at a time. You’ve got this.':'Take a breath, stretch and rest your eyes.';
  $('focusBar').style.width=(focusRemaining/focusDuration*100)+'%';
  $('focusStart').textContent=focusInterval?'Running…':'Resume timer';
}
function stopFocus(){if(focusInterval){clearInterval(focusInterval);focusInterval=null} $('focusPause').disabled=true;$('focusStart').disabled=false;paintFocus()}
function startFocus(){if(focusInterval)return;$('focusPause').disabled=false;$('focusStart').disabled=true;focusInterval=setInterval(()=>{
  focusRemaining=Math.max(0,focusRemaining-1);paintFocus();
  if(focusRemaining===0){stopFocus();$('focusHint').textContent=focusMode==='focus'?'Focus session complete! Take a short break.':'Break complete! Ready for another focus session?';$('focusStart').textContent='Start next session';try{if('Notification'in window&&Notification.permission==='granted')new Notification('STUDYVERSE AI',{body:focusMode==='focus'?'Great work! Time for a short break.':'Break finished. Ready to focus again?'})}catch{}}
},1000)}
$('focusStart').addEventListener('click',startFocus);
$('focusPause').addEventListener('click',stopFocus);
$('focusReset').addEventListener('click',()=>{stopFocus();focusRemaining=focusDuration;paintFocus()});
$('focusModeSwitch').addEventListener('click',()=>{stopFocus();focusMode=focusMode==='focus'?'break':'focus';focusDuration=focusMode==='focus'?25*60:5*60;focusRemaining=focusDuration;$('focusModeSwitch').textContent=focusMode==='focus'?'Switch to 5-min break':'Switch to 25-min focus';paintFocus()});
paintFocus();

// Export a backup of the student's locally saved study data.
function exportStudyData(){
  const keys=['sv_user','sv_class','sv_tasks','sv_cards','sv_sessions','sv_dark'];
  const backup={product:'STUDYVERSE AI',exportedAt:new Date().toISOString(),data:{}};
  keys.forEach(k=>{const v=localStorage.getItem(k);if(v!==null)backup.data[k]=v});
  const blob=new Blob([JSON.stringify(backup,null,2)],{type:'application/json'});
  const url=URL.createObjectURL(blob);const a=document.createElement('a');a.href=url;a.download='studyverse-backup.json';a.click();URL.revokeObjectURL(url);
}

</script>
</body>
</html>
