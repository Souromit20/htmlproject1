<!-- Project: Student Registration Form (Beautified) -->
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Student Registration Form</title>
  <style>
    :root{
      --bg-start:#0f172a; /* slate-900 */
      --bg-end:#1e293b;   /* slate-800 */
      --card:#0b1224cc;   /* translucent */
      --primary:#7c3aed;  /* violet-600 */
      --primary-600:#6d28d9; /* violet-700 */
      --accent:#22d3ee;   /* cyan-400 */
      --text:#e5e7eb;     /* gray-200 */
      --muted:#94a3b8;    /* slate-400 */
      --error:#ef4444;    /* red-500 */
      --ring: 0 0 0 3px rgba(124,58,237,.35);
      --radius: 18px;
      --shadow-lg: 0 10px 25px rgba(0,0,0,.35), 0 6px 10px rgba(0,0,0,.25);
      --shadow-sm: 0 6px 16px rgba(0,0,0,.25);
    }

    * { box-sizing: border-box; }
    html, body { height: 100%; }
    body{
      margin:0; font-family: ui-sans-serif, system-ui, -apple-system, Segoe UI, Roboto, Helvetica, Arial, "Apple Color Emoji", "Segoe UI Emoji";
      color:var(--text);
      background: radial-gradient(1200px 600px at 20% 10%, rgba(124,58,237,.25), transparent 60%),
                  radial-gradient(1000px 500px at 90% 80%, rgba(34,211,238,.18), transparent 60%),
                  linear-gradient(135deg, var(--bg-start), var(--bg-end));
      display:grid; place-items:center; padding: 28px;
    }

    .card{
      width:min(960px, 96vw);
      background: linear-gradient(180deg, rgba(255,255,255,.06), rgba(255,255,255,.03));
      backdrop-filter: blur(12px);
      border:1px solid rgba(255,255,255,.08);
      border-radius: var(--radius);
      box-shadow: var(--shadow-lg);
      overflow:hidden;
      position:relative;
    }

    .header{
      padding: 28px 28px 16px;
      border-bottom:1px solid rgba(255,255,255,.08);
      display:flex; align-items:center; gap:14px;
    }

    .logo{
      width:42px; height:42px; border-radius:12px;
      background: conic-gradient(from 180deg, var(--primary), var(--accent), var(--primary));
      box-shadow: inset 0 0 24px rgba(255,255,255,.25), 0 6px 18px rgba(124,58,237,.35);
    }

    h1{ font-size: clamp(22px, 3vw, 30px); margin:0; letter-spacing:.3px; }
    .subtitle{ color: var(--muted); margin:4px 0 0; font-size: 14px; }

    form{ padding: 26px; display:grid; gap: 22px; }

    .grid{ display:grid; gap: 18px; grid-template-columns: 1fr; }
    @media (min-width: 720px){
      .grid{ grid-template-columns: repeat(2, 1fr); }
    }

    .field{
      display:grid; gap:10px; padding:16px; border:1px solid rgba(255,255,255,.08);
      border-radius: 14px; background: rgba(12,18,36,.35);
    }

    label.title{ font-weight:600; letter-spacing:.2px; }
    .hint{ color:var(--muted); font-size: 12.5px; }

    input[type="text"],
    input[type="password"],
    select, textarea{
      width:100%; padding:12px 14px; border-radius:12px;
      border:1px solid rgba(255,255,255,.16);
      background: rgba(8,12,26,.55);
      color:var(--text);
      outline:none; transition: .18s ease;
      box-shadow: var(--shadow-sm);
    }
    input::placeholder, textarea::placeholder{ color:#9aa3b2; }

    input:focus, select:focus, textarea:focus{
      border-color: var(--primary);
      box-shadow: var(--shadow-sm), var(--ring);
    }

    /* Radios & Checkboxes - pretty */
    .choices{ display:flex; flex-wrap:wrap; gap:12px; }
    .chip{
      position:relative; display:inline-flex; align-items:center; gap:10px;
      padding:10px 12px; border-radius: 999px; cursor:pointer;
      border:1px solid rgba(255,255,255,.13);
      background: rgba(10,16,32,.45);
      transition:.18s ease; user-select:none;
    }
    .chip:hover{ transform: translateY(-1px); border-color: rgba(255,255,255,.25); }
    .chip input{ position:absolute; inset:0; opacity:0; pointer-events:none; }
    .dot, .check{
      width:16px; height:16px; border-radius:50%;
      border:2px solid rgba(255,255,255,.45); display:inline-flex; align-items:center; justify-content:center;
    }
    .check{ border-radius:6px; }
    .chip input[type="radio"]:checked ~ .dot{ border-color:var(--primary); box-shadow: 0 0 0 3px rgba(124,58,237,.35) inset; }
    .chip input[type="checkbox"]:checked ~ .check{ border-color:var(--accent); box-shadow: 0 0 0 3px rgba(34,211,238,.35) inset; }

    /* Actions */
    .actions{ display:flex; flex-wrap:wrap; gap:12px; justify-content:flex-end; padding: 0 4px; }
    .btn{
      appearance:none; border:none; cursor:pointer; font-weight:600; letter-spacing:.2px;
      padding:12px 18px; border-radius: 12px; transition:.18s ease; box-shadow: var(--shadow-sm);
    }
    .btn-primary{ background: linear-gradient(180deg, var(--primary), var(--primary-600)); color:white; }
    .btn-primary:hover{ transform: translateY(-1px); filter: brightness(1.05); }
    .btn-ghost{ background: transparent; color: var(--text); border:1px solid rgba(255,255,255,.18); }
    .btn-ghost:hover{ background: rgba(255,255,255,.06); }

    /* Footer */
    .footer{ padding: 0 26px 26px; color:var(--muted); font-size: 12.5px; }

    /* Validation hints */
    input:required:invalid, textarea:required:invalid{ border-color: rgba(239,68,68,.6); }
    .error{ color: var(--error); font-size: 12.5px; display:none; }
    input:required:invalid ~ .error,
    textarea:required:invalid ~ .error{ display:block; }
  </style>
</head>
<body>
  <main class="card" aria-labelledby="title">
    <header class="header">
      <div class="logo" aria-hidden="true"></div>
      <div>
        <h1 id="title">Student Registration Form</h1>
        <p class="subtitle">Fill in your details and preferences below. Fields marked with * are required.</p>
      </div>
    </header>

    <form action="/action.php" method="post" novalidate>
      <section class="grid" aria-label="Account information">
        <div class="field">
          <label class="title" for="username">Username *</label>
          <input id="username" name="username" type="text" inputmode="text" placeholder="Enter your username" autocomplete="username" required minlength="3" />
          <p class="hint">Use 3–20 characters. Letters and numbers only.</p>
          <p class="error">Please enter a valid username (min 3 characters).</p>
        </div>

        <div class="field">
          <label class="title" for="password">Password *</label>
          <input id="password" name="password" type="password" placeholder="Create a strong password" autocomplete="new-password" required minlength="6" />
          <p class="hint">At least 6 characters recommended.</p>
          <p class="error">Password is required (min 6 characters).</p>
        </div>
      </section>

      <section class="field" aria-label="Stream selection">
        <label class="title">Choose your Stream *</label>
        <div class="choices" role="radiogroup" aria-label="Stream">
          <label class="chip">
            <input type="radio" name="stream" value="CSE" required />
            <span class="dot" aria-hidden="true"></span>
            <span>CSE</span>
          </label>
          <label class="chip">
            <input type="radio" name="stream" value="AI" />
            <span class="dot" aria-hidden="true"></span>
            <span>AI</span>
          </label>
        </div>
        <p class="hint">Tap the text or the dot to select.</p>
      </section>

      <section class="field" aria-label="Subject preferences">
        <label class="title">Choose your Subjects</label>
        <p class="hint">You can select multiple.</p>
        <div class="choices">
          <label class="chip">
            <input type="checkbox" name="subjects" value="Math" />
            <span class="check" aria-hidden="true"></span>
            <span>Math</span>
          </label>
          <label class="chip">
            <input type="checkbox" name="subjects" value="Physics" />
            <span class="check" aria-hidden="true"></span>
            <span>Physics</span>
          </label>
          <label class="chip">
            <input type="checkbox" name="subjects" value="Chemistry" />
            <span class="check" aria-hidden="true"></span>
            <span>Chemistry</span>
          </label>
          <label class="chip">
            <input type="checkbox" name="subjects" value="Computer Science" />
            <span class="check" aria-hidden="true"></span>
            <span>Computer Science</span>
          </label>
        </div>
      </section>

      <section class="grid" aria-label="Location & feedback">
        <div class="field">
          <label class="title" for="city">Select your City (in India)</label>
          <select id="city" name="city">
            <option value="" selected disabled>Choose a city…</option>
            <option>Delhi</option>
            <option>Mumbai</option>
            <option>Kolkata</option>
            <option>Bangalore</option>
            <option>Chennai</option>
            <option>Hyderabad</option>
            <option>Pune</option>
            <option>Ahmedabad</option>
            <option>Jaipur</option>
            <option>Others</option>
          </select>
        </div>

        <div class="field">
          <label class="title" for="feedback">Feedback</label>
          <textarea id="feedback" name="feedback" placeholder="Please give your valuable feedback here" rows="5"></textarea>
          <p class="hint">Tell us anything that will help us improve.</p>
        </div>
      </section>

      <div class="actions">
        <button class="btn btn-ghost" type="reset">Reset</button>
        <button class="btn btn-primary" type="submit">Submit</button>
      </div>
    </form>

    <div class="footer">
      <small>Built with accessible HTML5 controls • Smooth focus states • Responsive design</small>
    </div>
  </main>
</body>
</html>
