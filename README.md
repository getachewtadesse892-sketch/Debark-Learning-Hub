# Debark-Learning-Hub
<!DOCTYPE html>
<html lang="am">
<head>
    <meta charset="UTF-8">
    <title>ደባርቅ ዩኒቨርሲቲ - Resource Hub</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <div class="header-content">
            <h1>Debark University Resource Hub</h1>
            <nav>
                <a href="login.html" class="teacher-link">ለመምህራን (Teachers)</a>
            </nav>
        </div>
    </header>

    <main class="container">
        <h2>የመማሪያ ማቴሪያሎች</h2>
        <div class="course-grid">
            <div class="course-card">
                <h3>Linear Algebra</h3>
                <p>Chapter 1: Matrices</p>
                <a href="#" class="btn">Download PDF</a>
            </div>
            <div class="course-card">
                <h3>Automata Theory</h3>
                <p>Chapter 2: DFA</p>
                <a href="#" class="btn">Download PDF</a>
            </div>
        </div>
    </main>
</body>
</html>
2. login.html (የመምህራን መግቢያ)
ይህ ገጽ መምህራን ስማቸውንና ፓስወርዳቸውን የሚያስገቡበት ነው።

HTML
<!DOCTYPE html>
<html lang="am">
<head>
    <meta charset="UTF-8">
    <title>መምህራን መግቢያ</title>
    <link rel="stylesheet" href="style.css">
</head>
<body class="login-page">
    <div class="login-box">
        <h2>መምህራን መግቢያ</h2>
        <form id="loginForm">
            <input type="text" id="username" placeholder="የተጠቃሚ ስም" required>
            <input type="password" id="password" placeholder="የይለፍ ቃል" required>
            <button type="button" onclick="checkLogin()">ግባ (Login)</button>
        </form>
        <p><a href="index.html">ወደ ዋናው ገጽ ተመለስ</a></p>
    </div>
    <script src="script.js"></script>
</body>
</html>
