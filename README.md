<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>klem@sys:~$</title>
  <style>
    :root {
      --bg: #0f0f17;
      --card-bg: #161622;
      --text: #cdd6f4;
      --accent-pink: #f5c2e7;
      --accent-lavender: #cba6f7;
      --accent-blue: #89b4fa;
      --accent-green: #a6e3a1;
      --dim: #6c7086;
    }

    * { margin: 0; padding: 0; box-sizing: border-box; }

    body {
      background-color: var(--bg);
      color: var(--text);
      font-family: 'Fira Code', 'Courier New', Courier, monospace;
      min-height: 100vh;
      display: flex;
      justify-content: center;
      align-items: center;
      padding: 20px;
    }

    .terminal {
      background-color: var(--card-bg);
      border: 1px solid #313244;
      border-radius: 10px;
      width: 100%;
      max-width: 800px;
      box-shadow: 0 10px 30px rgba(0, 0, 0, 0.5);
      overflow: hidden;
    }

    .terminal-header {
      background-color: #1e1e2e;
      padding: 10px 15px;
      display: flex;
      align-items: center;
      border-bottom: 1px solid #313244;
    }

    .buttons {
      display: flex;
      gap: 8px;
    }

    .dot {
      width: 12px;
      height: 12px;
      border-radius: 50%;
    }
    .red { background-color: #f38ba8; }
    .yellow { background-color: #f9e2af; }
    .green { background-color: #a6e3a1; }

    .title {
      margin-left: 15px;
      font-size: 0.85rem;
      color: var(--dim);
    }

    .terminal-body {
      padding: 25px;
      line-height: 1.6;
      font-size: 0.95rem;
      white-space: pre-wrap;
    }

    .prompt { color: var(--accent-lavender); font-weight: bold; }
    .cmd { color: var(--accent-pink); }
    .string { color: var(--accent-green); }
    .keyword { color: var(--accent-blue); }
    .comment { color: var(--dim); italic: true; }

    a {
      color: var(--accent-pink);
      text-decoration: none;
      border-bottom: 1px dashed var(--accent-pink);
    }
    a:hover {
      color: var(--accent-lavender);
      border-bottom-style: solid;
    }

    .ascii-art {
      color: var(--accent-lavender);
      font-weight: bold;
      margin-bottom: 15px;
    }

    .divider {
      border: 0;
      border-top: 1px solid #313244;
      margin: 15px 0;
    }
  </style>
</head>
<body>

  <div class="terminal">
    <div class="terminal-header">
      <div class="buttons">
        <div class="dot red"></div>
        <div class="dot yellow"></div>
        <div class="dot green"></div>
      </div>
      <div class="title">klem@sys: ~/.mooncodec.github.io</div>
    </div>

    <div class="terminal-body">
<div class="ascii-art">
  __  __                  ____            _             
 |  \/  | ___   ___  _ __/ ___|___   __| | ___  ___ 
 | |\/| |/ _ \ / _ \| '_ \ |   / _ \ / _` |/ _ \/ __|
 | |  | | (_) | (_) | | | | |__| (_) | (_| |  __/ (__ 
 |_|  |_|\___/ \___/|_| |_|\____\___/ \__,_|\___|\___|
</div>
<span class="prompt">klem@sys:~$</span> <span class="cmd">whoami</span>
> Software Developer & System Enthusiast

<hr class="divider">

<span class="comment"># ~/.bashrc - User Configuration</span>
<span class="keyword">export</span> USER=<span class="string">"klem"</span>
<span class="keyword">export</span> ROLE=<span class="string">"Software Developer"</span>
<span class="keyword">export</span> STACK=<span class="string">"Java, Kotlin, PHP, JS, Linux"</span>
<span class="keyword">export</span> VIBE=<span class="string">"cozy code, lofi, quiet nights"</span>

<span class="comment"># Background jobs</span>
[1]  Running    mc-project (bg)

<hr class="divider">

<span class="prompt">klem@terminal:~$</span> <span class="cmd">cat skills.conf</span>
[LANGUAGES]    Java | Kotlin | PHP | JavaScript
[SYSTEMS]      Linux | Bash | Git
[WORKFLOW]     IntelliJ IDEA | Neovim | Terminal

<hr class="divider">

<span class="prompt">klem@terminal:~$</span> <span class="cmd">curl -L /links</span>
+-----------------------------------------------------------------------+
|  [GitHub]    <a href="https://github.com/MoonCodec" target="_blank">github.com/MoonCodec</a>
|  [Discord]   <span class="string">klem</span>
|  [Website]   <a href="https://mooncodec.github.io">mooncodec.github.io</a>
+-----------------------------------------------------------------------+

                     (\__/)
                    ( =^.^=)
                    c(")(")  — thanks for stopping by...
    </div>
  </div>

</body>
</html>
