<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Innocent | Portfolio</title>
  <style>
    @import url('https://fonts.googleapis.com/css2?family=Pacifico&family=Poppins:wght@400;600&display=swap');

    * { margin: 0; padding: 0; box-sizing: border-box; font-family: 'Poppins', sans-serif; }

    body {
      background: linear-gradient(135deg, #ff4b2b, #ff416c, #ff6a00, #f9d423, #24c6dc, #514a9d);
      background-size: 600% 600%;
      animation: gradientBG 12s ease infinite;
      color: white;
    }
    @keyframes gradientBG {
      0% { background-position: 0% 50%; }
      50% { background-position: 100% 50%; }
      100% { background-position: 0% 50%; }
    }

    header {
      height: 100vh;
      display: flex; flex-direction: column;
      justify-content: center; align-items: center;
      text-align: center; padding: 0 16px;
    }

    header img {
      width: 130px; height: 130px; border-radius: 50%;
      border: 3px solid white; margin-bottom: 20px; object-fit: cover;
      background: rgba(255,255,255,0.3);
    }

    header h1 {
      font-size: 3.2rem; font-family: 'Pacifico', cursive;
      margin-bottom: 10px; text-shadow: 2px 2px 10px rgba(0,0,0,0.4);
    }

    header p { font-size: 1.2rem; color: #fffdd0; margin-bottom: 25px; }

    .contact a {
      display: inline-block; margin: 10px; text-decoration: none; color: white;
      border: none; padding: 12px 25px; border-radius: 30px; font-weight: 600;
      transition: 0.3s;
    }
    .contact a.insta {
      background: linear-gradient(45deg, #feda75, #fa7e1e, #d62976, #962fbf, #4f5bd5);
    }
    .contact a:hover { opacity: 0.85; transform: scale(1.08); }

    footer {
      text-align: center; padding: 20px; background: rgba(0,0,0,0.35);
      border-radius: 15px 15px 0 0; font-size: 0.9rem;
    }

    /* 👀 Visitor counter badge */
    .visit-badge {
      position: fixed; left: 16px; bottom: 16px;
      background: rgba(255,255,255,0.2);
      backdrop-filter: blur(6px);
      border: 1px solid rgba(255,255,255,0.4);
      border-radius: 14px; padding: 10px 14px;
      display: flex; align-items: center; gap: 8px;
      box-shadow: 0 8px 20px rgba(0,0,0,0.25);
      user-select: none;
    }
    .visit-dot {
      width: 10px; height: 10px; border-radius: 50%;
      background: #00ffcc; box-shadow: 0 0 10px #00ffcc;
    }
    .visit-text { font-weight: 600; font-size: 0.95rem; }
    .visit-num { font-variant-numeric: tabular-nums; font-weight: 700; }
  </style>
</head>
<body>
  <header>
    <img src="https://via.placeholder.com/150" alt="Profile Picture"/>
    <h1>Innocent</h1>
    <p>Creative Mind ✨ Exploring Colors, Tech & Ideas 🌈</p>
    <div class="contact">
      <a href="https://www.instagram.com/innocent_txt?igsh=b2s2dzljbDZqcmxy" target="_blank" class="insta">Instagram</a>
    </div>
  </header>

  <!-- 👀 Global visitor counter badge -->
  <div class="visit-badge" aria-live="polite" title="Unique visitors">
    <div class="visit-dot"></div>
    <span class="visit-text">Visitors:</span>
    <span class="visit-num" id="visitCount">—</span>
  </div>

  <footer>
    <p>© 2025 Innocent | Made with ❤️ & Colors</p>
  </footer>

  <!-- Counter Logic -->
  <script>
    /*
      Simple global counter using a public key-value counter API.
      - Uses a namespace/key unique to your site.
      - Adds a 24h cooldown per device so refresh spam na ho.
    */
    (async function() {
      const NAMESPACE = 'innocent-portfolio';
      const KEY = 'home';
      const API_BASE = 'https://api.countapi.xyz';
      const COUNT_EL = document.getElementById('visitCount');

      // 24h cooldown per browser to avoid double count spam
      const COOL_HOURS = 24;
      const lsKey = 'visit_last_increment';
      const last = localStorage.getItem(lsKey);
      const now = Date.now();
      const shouldIncrement = !last || (now - Number(last)) > COOL_HOURS * 60 * 60 * 1000;

      try {
        // ensure key exists
        await fetch(`${API_BASE}/create?namespace=${encodeURIComponent(NAMESPACE)}&key=${encodeURIComponent(KEY)}&value=0`)
          .catch(()=>{});

        // increment once per 24h per device, else just get current
        const endpoint = shouldIncrement
          ? `${API_BASE}/hit/${encodeURIComponent(NAMESPACE)}/${encodeURIComponent(KEY)}`
          : `${API_BASE}/get/${encodeURIComponent(NAMESPACE)}/${encodeURIComponent(KEY)}`;

        const res = await fetch(endpoint);
        const data = await res.json();
        const value = data && (data.value ?? data.count ?? data.value);
        if (typeof value === 'number') {
          COUNT_EL.textContent = value.toLocaleString();
        } else {
          COUNT_EL.textContent = '—';
        }

        if (shouldIncrement) {
          localStorage.setItem(lsKey, String(now));
        }
      } catch (e) {
        COUNT_EL.textContent = '—';
        console.error('Visitor counter failed:', e);
      }
    })();
  </script>
</body>
</html>￼Enter
