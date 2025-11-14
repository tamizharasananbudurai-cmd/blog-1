

<html lang="en">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width,initial-scale=1">
  <title>A Game of Thrones — Book Review</title>
  <style>
    :root{--bg:#0f1724;--card:#0b1220;--accent:#f59e0b;--muted:#94a3b8;--glass: rgba(255,255,255,0.03)}
    html,body{height:100%;margin:0;font-family:Inter, system-ui, -apple-system, 'Segoe UI', Roboto, 'Helvetica Neue', Arial; background:linear-gradient(180deg,#071025 0%, #081224 60%);color:#e6eef8}
    .container{max-width:900px;margin:40px auto;padding:24px}
    .card{background:linear-gradient(180deg, rgba(255,255,255,0.02), rgba(255,255,255,0.01)); border-radius:14px;padding:26px;box-shadow:0 8px 30px rgba(2,6,23,0.6);border:1px solid rgba(255,255,255,0.03)}
    h1{font-size:28px;margin:0 0 8px}
    .subtitle{color:var(--muted);margin:0 0 18px}
    .meta{display:flex;gap:12px;align-items:center;margin-bottom:18px}
    .badge{background:var(--glass);padding:8px 12px;border-radius:999px;font-weight:600}
    .btn{background:transparent;border:1px solid rgba(255,255,255,0.06);padding:8px 12px;border-radius:8px;color:inherit;cursor:pointer}
    .controls{display:flex;gap:8px;flex-wrap:wrap;margin-bottom:18px}
    .review p{line-height:1.6;margin:0 0 12px}
    .hidden{display:none}
    .section-title{margin:18px 0 8px;color:var(--accent);font-weight:700}
    .grid{display:grid;grid-template-columns:1fr 1fr;gap:12px}
    .panel{background:rgba(255,255,255,0.02);padding:12px;border-radius:10px;border:1px solid rgba(255,255,255,0.02)}
    ul{margin:8px 0 0 20px;color:var(--muted)}
    .rating{font-size:18px;font-weight:700;color:var(--accent)}
    footer{color:var(--muted);font-size:13px;margin-top:18px}
    @media (max-width:720px){.grid{grid-template-columns:1fr}}
    .print-only{display:none}
    @media print{body{background:white;color:black} .card{box-shadow:none;border:none;background:transparent} .no-print{display:none} .print-only{display:block}}
  </style>
</head>
<body>
  <div class="container">
    <div class="card" role="article" aria-labelledby="title">
      <header>
        <h1 id="title">A Game of Thrones — Book Review</h1>
        <p class="subtitle">George R. R. Martin — <em>A Song of Ice and Fire, Book 1</em></p>
        <div class="meta">
          <div class="badge">Epic Fantasy</div>
          <div class="badge">Published: 1996</div>
          <div style="margin-left:auto" class="no-print">
            <button class="btn" onclick="window.print()">Print / Save as PDF</button>
          </div>
        </div>
      </header><div class="controls no-print">
    <button class="btn" onclick="showVariant('concise')">Concise</button>
    <button class="btn" onclick="showVariant('full')">Full (6-paragraph)</button>
    <button class="btn" onclick="toggleSection('rating')">Rating</button>
    <button class="btn" onclick="toggleSection('characters')">Character Analysis</button>
    <button class="btn" onclick="toggleSection('themes')">Themes & Symbols</button>
  </div>

  <main class="review">
    <!-- Concise / Full texts -->
    <div id="concise" class="variant">
      <p><strong>George R. R. Martin’s <em>A Game of Thrones</em></strong> is a masterclass in epic fantasy storytelling. Set in the turbulent land of Westeros, the book blends political intrigue, medieval warfare, moral ambiguity, and subtle magic to create a deeply immersive world that feels almost alive. Martin challenges fantasy conventions by killing major characters and dismantling heroic tropes.</p>
      <p>The novel’s strength lies in its richly drawn characters and shifting point-of-view structure, which makes the narrative layered and unpredictable. Martin’s world-building — rival houses, scheming courts, and ancient dangers beyond the Wall — keeps political tension high and alliances fragile.</p>
      <p>Accessible yet vivid prose, moral complexity, and emotional stakes make the book rewarding for readers who enjoy political drama and deep characterization. It’s a landmark novel that redefined modern fantasy.</p>
    </div>

    <div id="full" class="variant hidden">
      <p>George R. R. Martin’s <em>A Game of Thrones</em>, the first novel in the <em>A Song of Ice and Fire</em> series, is a masterclass in epic fantasy storytelling. Set in the turbulent land of Westeros, the book blends political intrigue, medieval warfare, moral ambiguity, and subtle magic to create a deeply immersive world that feels almost alive. Unlike traditional fantasy, Martin isn’t afraid to challenge readers’ expectations, killing major characters and dismantling familiar heroic tropes.</p>

      <p>The novel’s strength lies in its richly drawn characters. From Eddard Stark’s unwavering honor to Tyrion Lannister’s sharp wit and Daenerys Targaryen’s transformation from timid girl to future queen, every point-of-view character offers a unique lens into the world. The shifting perspectives make the narrative layered and unpredictable, highlighting the personal stakes behind political decisions.</p>

      <p>Martin’s political world-building stands out. The rivalries between noble houses, the scheming in King’s Landing, and the ancient threats beyond the Wall create a multi-directional tension where every alliance feels fragile. The famous motto “When you play the game of thrones, you win or you die” captures the brutal reality of power dynamics in Westeros.</p>

      <p>The prose is accessible yet vivid, filled with atmospheric descriptions that bring castles, snowscapes, and battlefields to life. Martin avoids excessive exposition and instead reveals history through dialogue, stories, and character memory, making the world feel lived-in and natural.</p>

      <p>One of the book’s defining features is its moral complexity. There are no pure heroes or villains—only people with motives shaped by duty, desire, fear, or ambition. This realism, combined with the high emotional stakes, makes the plot gripping and often heart-wrenching.</p>

      <p>Overall, <em>A Game of Thrones</em> is a landmark fantasy novel that redefined the genre. It’s ideal for readers who enjoy political drama, deep characterization, and unpredictable storytelling. The book demands attention but rewards it with unforgettable moments and a world that stays with you long after closing the final page.</p>
    </div>

    <!-- Optional sections -->
    <div id="rating" class="hidden">
      <h3 class="section-title">⭐ Rating breakdown</h3>
      <div class="grid">
        <div class="panel">
          <div class="rating">Overall: 4.5 / 5</div>
          <ul>
            <li>Plot & Pacing: 4 / 5 — complex, slow at times</li>
            <li>Characters: 5 / 5 — deeply drawn and memorable</li>
            <li>World-building: 5 / 5 — immersive and detailed</li>
            <li>Prose: 4 / 5 — vivid, occasionally dense</li>
          </ul>
        </div>
        <div class="panel">
          <strong>Best for:</strong>
          <ul>
            <li>Readers who like political intrigue</li>
            <li>Fans of morally complex characters</li>
            <li>Those who enjoy long, layered series</li>
          </ul>
        </div>
      </div>
    </div>

    <div id="characters" class="hidden">
      <h3 class="section-title">🔥 Character analysis</h3>
      <ul>
        <li><strong>Eddard (Ned) Stark</strong>: Honor-bound but politically naive; a moral anchor whose choices set major events in motion.</li>
        <li><strong>Tyrion Lannister</strong>: Sharp-witted outsider; intellect and empathy make him one of the most compelling figures.</li>
        <li><strong>Daenerys Targaryen</strong>: Begins as vulnerable and grows toward leadership — the seeds of a revolutionary arc.</li>
        <li><strong>Own observations</strong>: Martin spreads empathy across viewpoints, so even antagonists feel human and motivated.</li>
      </ul>
    </div>

    <div id="themes" class="hidden">
      <h3 class="section-title">⚔️ Themes & symbols</h3>
      <ul>
        <li><strong>Power and its cost</strong> — the brutal calculus of politics and survival.</li>
        <li><strong>Honor vs. pragmatism</strong> — when idealism clashes with realpolitik.</li>
        <li><strong>Identity and legacy</strong> — bloodlines, honor, and what we inherit.</li>
        <li><strong>The Wall & the North</strong> — the unknown beyond civilization; slow-burn threat.</li>
      </ul>
    </div>

    <footer>
      <div class="no-print">Use the buttons above to toggle sections. Click <em>Print / Save as PDF</em> to export a clean copy for school or sharing.</div>
      <div class="print-only">This review: A Game of Thrones — George R. R. Martin.</div>
    </footer>

  </main>
</div>

  </div>  <script>
    function showVariant(id){
      document.querySelectorAll('.variant').forEach(el=>el.classList.add('hidden'));
      document.getElementById(id).classList.remove('hidden');
      // hide optional sections when switching
      ['rating','characters','themes'].forEach(s=>document.getElementById(s).classList.add('hidden'));
    }
    function toggleSection(id){
      const el = document.getElementById(id);
      if(!el) return;
      el.classList.toggle('hidden');
      // ensure full variant is visible when showing details
      if(!el.classList.contains('hidden')){
        document.getElementById('concise').classList.add('hidden');
        document.getElementById('full').classList.remove('hidden');
      }
    }
    // default view
    showVariant('concise');
  </script></body>
</html>
