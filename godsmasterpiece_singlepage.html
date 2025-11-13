<!--
GodsMasterpiece Single-Page Website
File: godsmasterpiece_singlepage.html

INCLUDED IN THIS FILE:
- Complete single-file HTML/CSS/JS site (hero, daily verse, blog samples, about, contact/prayer requests)

DEPLOYMENT INSTRUCTIONS (short -- also included here so you don't need to leave the file):

Option A — GitHub Pages (free)
1. Create a GitHub account if you don't have one: https://github.com
2. Create a new repository named: <your-username>.github.io  OR any repo for a project site.
3. Add this HTML file as `index.html` in the repository (upload via web UI or commit).
4. If your repo is named <your-username>.github.io, the site will be available at:
   https://<your-username>.github.io/
   Otherwise, enable Pages in Settings -> Pages -> select branch `main` and folder `/ (root)`.
5. To use a custom domain later (godsmasterpiece.com), buy the domain at Namecheap/Google Domains/GoDaddy and follow GitHub Pages -> Custom domain settings.

Option B — Netlify (free + continuous deploy)
1. Create a Netlify account.
2. Drag & drop this `index.html` into "Sites" or connect to a GitHub repo.
3. Netlify provides a free subdomain; add a custom domain in Site Settings when ready.

Free domain (temporary) with Freenom:
- If you want a free domain now, register a .tk/.ml/.ga/.cf/.gq domain at https://www.freenom.com then point its DNS to GitHub Pages or Netlify according to their guides (use CNAME or A records).

Notes:
- This site uses a simple mailto form for contact (no backend). For prayer requests to persist on the visitor's browser, we store them in localStorage.
- To add or edit blog posts, edit the `posts` array in the JavaScript section.

--------------------
END COMMENT -- HTML CONTENT STARTS BELOW
-->

<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width,initial-scale=1">
  <title>God's Masterpiece — Faith, Hope & Daily Verses</title>
  <meta name="description" content="Daily verses, reflections and encouragement. You are God\'s masterpiece.">
  <style>
    :root{
      --warm-1:#fffaf0; /* very light cream */
      --warm-2:#f5e6d3; /* soft beige */
      --accent:#c79a5e; /* soft gold */
      --muted:#6b5b4a; /* coffee */
      --card:#fff; 
      --radius:16px;
      --maxw:980px;
      font-family: 'Georgia', 'Times New Roman', serif;
    }
    *{box-sizing:border-box}
    body{margin:0;background:linear-gradient(180deg,var(--warm-1),#fff);color:var(--muted);-webkit-font-smoothing:antialiased}
    header{background-image:linear-gradient(rgba(255,250,240,0.6),rgba(255,250,240,0.6)), url('https://images.unsplash.com/photo-1500530855697-b586d89ba3ee?q=80&w=1800&auto=format&fit=crop&ixlib=rb-4.0.3&s=6b3dede814d75b6db5c2f041d9bbf7b3');background-size:cover;background-position:center;padding:88px 24px 48px;border-bottom-left-radius:40px;border-bottom-right-radius:40px;}
    .container{max-width:var(--maxw);margin:0 auto;padding:24px}
    .hero{display:flex;gap:24px;align-items:center}
    .hero-left{flex:1}
    h1{font-size:36px;margin:0 0 12px;color:#52392a}
    p.lead{margin:0 0 18px;font-size:18px;color:#5b4536}
    .btn{display:inline-block;padding:10px 18px;border-radius:999px;background:var(--accent);color:white;text-decoration:none;font-weight:600;box-shadow:0 6px 18px rgba(199,154,94,0.18)}
    .verse-card{background:rgba(255,255,255,0.92);padding:16px;border-radius:12px;max-width:420px;box-shadow:0 8px 30px rgba(91,69,54,0.06)}
    .verse-text{font-style:italic;font-size:18px;color:#3e2e26;margin-bottom:8px}
    .verse-ref{font-size:14px;color:#7a6859}

    /* Sections */
    section{padding:48px 0}
    .grid{display:grid;grid-template-columns:1fr 320px;gap:28px}
    @media (max-width:880px){.grid{grid-template-columns:1fr}header{padding:56px 16px}h1{font-size:28px}}

    /* Blog */
    .posts{display:grid;grid-template-columns:repeat(auto-fit,minmax(220px,1fr));gap:18px}
    .post{background:var(--card);padding:18px;border-radius:12px;box-shadow:0 6px 18px rgba(91,69,54,0.06)}
    .post h3{margin:0 0 10px;color:#4a392e}
    .post p{margin:0 0 12px;color:#6e5749}
    .meta{font-size:13px;color:#a18567}

    /* About & Contact */
    .about{background:linear-gradient(180deg, rgba(255,250,240,0.7), rgba(255,250,240,0.95));padding:18px;border-radius:12px}
    .contact form{display:grid;gap:8px}
    input,textarea{padding:10px;border-radius:8px;border:1px solid #e8d9c9}
    input::placeholder,textarea::placeholder{color:#b59f8f}
    .small{font-size:13px;color:#7e6a5a}

    footer{padding:24px 0;text-align:center;color:#8b7766}

    /* subtle animations */
    .fade-up{transform:translateY(6px);opacity:0;animation:fadeUp .9s ease forwards}
    @keyframes fadeUp{to{transform:none;opacity:1}}

    /* prayer list */
    .prayer-list{max-height:160px;overflow:auto;padding:8px;background:#fff;border-radius:8px}
    .prayer-item{padding:8px;border-bottom:1px solid #f4ece3}

  </style>
</head>
<body>
  <header>
    <div class="container hero">
      <div class="hero-left fade-up">
        <h1>You are <span style="color:var(--accent);">God's Masterpiece</span></h1>
        <p class="lead">Daily verses, encouraging reflections, and gentle reminders of God's love. Find rest here — short readings to lift your heart and renew your spirit.</p>
        <a class="btn" href="#reflections">Read Today's Reflection</a>
        <div style="height:12px"></div>
        <div class="verse-card">
          <div id="verseText" class="verse-text">Loading today's verse...</div>
          <div id="verseRef" class="verse-ref">—</div>
        </div>
      </div>
      <div class="hero-right" style="min-width:300px;">
        <!-- reserved for image / quote -->
      </div>
    </div>
  </header>

  <main class="container">
    <section id="reflections">
      <div class="grid">
        <div>
          <h2 style="color:#4a392e">Reflections & Inspirations</h2>
          <p class="small">Short, practical reflections to help you live each day with hope.</p>

          <div class="posts" id="postsContainer">
            <!-- posts inserted by JS -->
          </div>
        </div>

        <aside>
          <div class="about">
            <h3>About God's Masterpiece</h3>
            <p>We believe every person is lovingly crafted by God. This site shares daily verses and reflections to remind you of your worth and the gentle work of the Spirit in your life.</p>
            <p class="small">Ephesians 2:10 — "For we are God's workmanship, created in Christ Jesus..."</p>
          </div>

          <div style="height:18px"></div>

          <div class="about">
            <h4>Verse of the Day</h4>
            <div style="margin-top:8px">
              <button class="btn" onclick="newVerse()">Another verse</button>
            </div>
          </div>

        </aside>
      </div>
    </section>

    <section id="contact">
      <div style="display:grid;gap:18px">
        <h2 style="color:#4a392e">Contact & Prayer Requests</h2>
        <div class="grid">
          <div class="about contact">
            <form id="contactForm" onsubmit="submitContact(event)">
              <input type="text" id="name" placeholder="Your name (optional)">
              <input type="email" id="email" placeholder="Your email (optional)">
              <textarea id="message" placeholder="Your prayer request or message" rows="4"></textarea>
              <div style="display:flex;gap:8px;align-items:center">
                <button class="btn" type="submit">Send Prayer Request</button>
                <a class="small" href="mailto:your-email@example.com?subject=Prayer Request">Or email us</a>
              </div>
              <div id="contactNote" class="small" style="margin-top:8px;color:#7a6859"></div>
            </form>
          </div>

          <div class="about">
            <h4>Prayer Wall</h4>
            <div class="prayer-list" id="prayerList">
              <!-- saved prayers -->
            </div>
            <div style="margin-top:8px" class="small">Prayers are saved locally to your browser for privacy. To share publicly, email us.</div>
          </div>
        </div>
      </div>
    </section>
  </main>

  <footer>
    <div class="container">
      <div class="small">&copy; <span id="year"></span> God's Masterpiece — created to remind you of God's love.</div>
    </div>
  </footer>

  <script>
    // ------------------------
    // Content (edit these arrays to change posts or verses)
    // ------------------------
    const verses = [
      {text:"But because of his great love for us, God, who is rich in mercy, made us alive with Christ even when we were dead in transgressions — it is by grace you have been saved.",ref:"Ephesians 2:4-5"},
      {text:"I praise you because I am fearfully and wonderfully made; your works are wonderful, I know that full well.",ref:"Psalm 139:14"},
      {text:"For I know the plans I have for you, declares the LORD, plans for welfare and not for evil, to give you a future and a hope.",ref:"Jeremiah 29:11"},
      {text:"He heals the brokenhearted and binds up their wounds.",ref:"Psalm 147:3"},
      {text:"The LORD is near to the brokenhearted and saves the crushed in spirit.",ref:"Psalm 34:18"},
      {text:"Cast all your anxiety on him because he cares for you.",ref:"1 Peter 5:7"},
      {text:"The steadfast love of the LORD never ceases; his mercies never come to an end.",ref:"Lamentations 3:22"},
      {text:"Be still, and know that I am God.",ref:"Psalm 46:10"},
      {text:"You are God\'s workmanship, created in Christ Jesus to do good works.",ref:"Ephesians 2:10"},
      {text:"I can do all things through him who strengthens me.",ref:"Philippians 4:13"}
    ];

    const posts = [
      {title:"Trusting God in Uncertain Seasons",excerpt:"How to find peace when life feels unstable. Practical ways to rest in prayer and scripture.",date:"Nov 10, 2025"},
      {title:"You Are Wonderfully Made",excerpt:"A short reflection on identity and worth in Christ.",date:"Nov 3, 2025"},
      {title:"Small Habits that Grow Faith",excerpt:"Daily rhythms that help you notice God in ordinary moments.",date:"Oct 28, 2025"}
    ];

    // ------------------------
    // Verse of the day logic: chooses based on date so it's consistent per day
    // ------------------------
    function getIndexFromDate(){
      const d = new Date();
      const key = d.getFullYear()*10000 + (d.getMonth()+1)*100 + d.getDate();
      return key % verses.length;
    }

    function showVerse(i){
      const v = verses[i % verses.length];
      document.getElementById('verseText').textContent = '"' + v.text + '"';
      document.getElementById('verseRef').textContent = v.ref;
    }

    function newVerse(){
      const i = Math.floor(Math.random()*verses.length);
      showVerse(i);
    }

    // ------------------------
    // Render posts
    // ------------------------
    function renderPosts(){
      const c = document.getElementById('postsContainer');
      c.innerHTML = '';
      posts.forEach(p=>{
        const el = document.createElement('article');
        el.className = 'post';
        el.innerHTML = `<h3>${p.title}</h3><p>${p.excerpt}</p><div class="meta">${p.date}</div><div style="height:8px"></div><a class="small" href="#" onclick="openPost('${escapeHtml(p.title)}')">Read more</a>`;
        c.appendChild(el);
      })
    }

    function escapeHtml(s){return s.replace(/'/g,"\\'").replace(/"/g,'\"');}

    function openPost(title){
      alert(title + "\n\n(Full post content can be added by editing the posts array in the site's code.)");
    }

    // ------------------------
    // Contact / Prayer Requests (stored locally)
    // ------------------------
    function submitContact(e){
      e.preventDefault();
      const name = document.getElementById('name').value.trim();
      const msg = document.getElementById('message').value.trim();
      if(!msg){document.getElementById('contactNote').textContent = 'Please write a short prayer request or message.';return}
      const prayers = JSON.parse(localStorage.getItem('gmp_prayers')||'[]');
      prayers.unshift({name:name||'Anonymous',message:msg,date:new Date().toLocaleString()});
      localStorage.setItem('gmp_prayers',JSON.stringify(prayers.slice(0,100)));
      document.getElementById('contactNote').textContent = 'Thank you — your prayer has been saved locally.';
      document.getElementById('contactForm').reset();
      renderPrayers();
    }

    function renderPrayers(){
      const prayers = JSON.parse(localStorage.getItem('gmp_prayers')||'[]');
      const c = document.getElementById('prayerList');
      c.innerHTML = '';
      if(prayers.length===0){c.innerHTML = '<div class="small">No prayers yet — be the first to share.</div>';return}
      prayers.forEach(p=>{
        const d = document.createElement('div');d.className='prayer-item';
        d.innerHTML = `<strong>${escapeHtml(p.name)}</strong><div style="font-size:14px;margin-top:6px;color:#5d4b3f">${escapeHtml(p.message)}</div><div class="small" style="margin-top:8px;color:#9a8570">${p.date}</div>`;
        c.appendChild(d);
      })
    }

    // ------------------------
    // Init
    // ------------------------
    document.getElementById('year').textContent = new Date().getFullYear();
    showVerse(getIndexFromDate());
    renderPosts();
    renderPrayers();

  </script>
</body>
</html>
