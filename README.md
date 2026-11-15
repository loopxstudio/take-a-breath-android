<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>Take a Breath: a calm pause before social media</title>
<meta name="description" content="Take a Breath is a free, no-ads, fully on-device app for Android that adds a mindful breathing pause before social media. For adults and for parents guiding a child's phone use. Nothing is collected.">
<meta name="theme-color" content="#0b1d2a">
<meta property="og:title" content="Take a Breath">
<meta property="og:description" content="A calm pause before social media. Free, no ads, nothing collected.">
<meta property="og:type" content="website">
<meta property="og:url" content="https://takeabreath.loopxstudio.ca/">
<link rel="canonical" href="https://takeabreath.loopxstudio.ca/">
<link rel="icon" href="data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 120 120'%3E%3Crect width='120' height='120' rx='28' fill='%230b1d2a'/%3E%3Cg fill='none' stroke='%237fe3d4' stroke-width='4'%3E%3Ccircle cx='60' cy='60' r='14'/%3E%3Ccircle cx='60' cy='60' r='25' opacity='.8'/%3E%3Ccircle cx='60' cy='60' r='36' opacity='.6'/%3E%3C/g%3E%3C/svg%3E">
<style>
:root{
  --bg:#fbfbfd; --card:#ffffff; --ink:#1d1d1f; --muted:#6e6e73; --line:#e6e6ea;
  --navy:#0b1d2a; --navy2:#12334a; --teal:#7fe3d4; --accent:#0f8f86; --accent-soft:#e8f6f4;
}
*{box-sizing:border-box;margin:0;padding:0}
html{scroll-behavior:smooth}
body{font-family:-apple-system,BlinkMacSystemFont,"SF Pro Display","Segoe UI",Roboto,Helvetica,Arial,sans-serif;background:var(--bg);color:var(--ink);line-height:1.55;-webkit-font-smoothing:antialiased}
a{color:var(--accent);text-decoration:none}
a:hover{text-decoration:underline}
.wrap{max-width:1080px;margin:0 auto;padding:0 24px}

/* nav */
nav{position:sticky;top:0;z-index:20;background:rgba(251,251,253,.8);backdrop-filter:saturate(180%) blur(18px);-webkit-backdrop-filter:saturate(180%) blur(18px);border-bottom:1px solid var(--line)}
nav .wrap{display:flex;align-items:center;justify-content:space-between;height:56px}
.brand{display:flex;align-items:center;gap:10px;font-weight:600;color:var(--ink);font-size:17px}
.brand:hover{text-decoration:none}
nav ul{display:flex;gap:26px;list-style:none;font-size:14px}
nav ul a{color:#424245}
@media(max-width:720px){nav ul{display:none}}

/* logo */
.logo{display:block}
.logo .ring{fill:none;stroke:var(--teal);stroke-linecap:round;transform-box:fill-box;transform-origin:center;animation:tremble 1s ease-in-out infinite alternate}
.logo .r1{stroke-width:3.2;animation-duration:.6s}
.logo .r2{stroke-width:3;opacity:.85;animation-duration:.74s}
.logo .r3{stroke-width:2.8;opacity:.7;animation-duration:.9s}
.logo .r4{stroke-width:2.6;opacity:.55;animation-duration:1.05s}
.logo .all{transform-box:fill-box;transform-origin:center;animation:breathe 4s ease-in-out infinite}
@keyframes breathe{0%,100%{transform:scale(.88)}50%{transform:scale(1.06)}}
@keyframes tremble{from{transform:rotate(-2.2deg)}to{transform:rotate(2.2deg)}}
@media(prefers-reduced-motion:reduce){.logo .ring,.logo .all,.pulse{animation:none!important}}

/* hero */
.hero{background:radial-gradient(1200px 600px at 50% -10%,var(--navy2) 0%,var(--navy) 60%);color:#fff;text-align:center;padding:84px 0 96px}
.hero .logo{margin:0 auto 28px;filter:drop-shadow(0 18px 40px rgba(127,227,212,.25))}
.eyebrow{display:inline-block;font-size:13px;letter-spacing:.08em;text-transform:uppercase;color:var(--teal);font-weight:600;margin-bottom:14px}
.hero h1{font-size:clamp(38px,6vw,64px);line-height:1.05;font-weight:700;letter-spacing:-.02em;max-width:820px;margin:0 auto 18px}
.hero p.lead{font-size:clamp(18px,2.2vw,22px);color:#c9d6df;max-width:680px;margin:0 auto 34px}
.badges{display:flex;flex-wrap:wrap;gap:10px;justify-content:center;margin-bottom:34px}
.badge{font-size:13px;padding:7px 14px;border-radius:999px;border:1px solid rgba(255,255,255,.2);color:#e8f1f6;background:rgba(255,255,255,.06)}
.cta{display:inline-flex;align-items:center;gap:10px;background:#fff;color:var(--navy);padding:14px 26px;border-radius:999px;font-weight:600;font-size:16px}
.cta:hover{text-decoration:none;transform:translateY(-1px)}
.soon{display:block;margin-top:14px;font-size:13px;color:#9fb3c1}

/* sections */
section{padding:88px 0}
section.alt{background:#fff;border-top:1px solid var(--line);border-bottom:1px solid var(--line)}
.kicker{font-size:13px;letter-spacing:.08em;text-transform:uppercase;color:var(--accent);font-weight:600;margin-bottom:10px}
h2{font-size:clamp(28px,4vw,44px);line-height:1.1;letter-spacing:-.02em;font-weight:700;margin-bottom:14px}
.sub{font-size:19px;color:var(--muted);max-width:720px;margin-bottom:44px}
.center{text-align:center}.center .sub{margin-left:auto;margin-right:auto}
.grid{display:grid;gap:20px}
.g3{grid-template-columns:repeat(3,1fr)}
.g2{grid-template-columns:repeat(2,1fr)}
@media(max-width:860px){.g3,.g2{grid-template-columns:1fr}}
.card{background:var(--card);border:1px solid var(--line);border-radius:22px;padding:30px}
section.alt .card{background:var(--bg)}
.card h3{font-size:20px;margin-bottom:8px;letter-spacing:-.01em}
.card p{color:var(--muted);font-size:16px}
.ico{width:44px;height:44px;border-radius:12px;background:var(--accent-soft);display:flex;align-items:center;justify-content:center;margin-bottom:18px}
.ico svg{width:24px;height:24px;stroke:var(--accent);fill:none;stroke-width:1.8;stroke-linecap:round;stroke-linejoin:round}
.step{counter-increment:s}
.num{font-size:14px;font-weight:700;color:var(--accent);margin-bottom:12px}

/* breathing demo */
.demo{display:flex;align-items:center;justify-content:center}
.phone{width:260px;height:520px;border-radius:44px;background:linear-gradient(160deg,var(--navy2),var(--navy));border:8px solid #1d1d1f;display:flex;flex-direction:column;align-items:center;justify-content:center;color:#fff;box-shadow:0 30px 60px rgba(0,0,0,.18);text-align:center;padding:24px}
.pulse{width:150px;height:150px;border-radius:50%;border:3px dashed var(--teal);animation:pulse 8s ease-in-out infinite;margin-bottom:26px}
@keyframes pulse{0%,100%{transform:scale(.7);opacity:.6}50%{transform:scale(1.1);opacity:1}}
.phone b{font-size:20px;display:block;margin-bottom:6px}
.phone span{font-size:14px;color:#a9bcc9}
.split{display:grid;grid-template-columns:1.1fr .9fr;gap:56px;align-items:center}
@media(max-width:860px){.split{grid-template-columns:1fr}}
.ticks{list-style:none;margin-top:18px}
.ticks li{padding:10px 0 10px 34px;position:relative;font-size:17px;border-bottom:1px solid var(--line)}
.ticks li:last-child{border:none}
.ticks li:before{content:"";position:absolute;left:0;top:15px;width:20px;height:20px;border-radius:50%;background:var(--accent-soft) url("data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 20 20'%3E%3Cpath d='M5.5 10.5l3 3 6-7' fill='none' stroke='%230f8f86' stroke-width='2' stroke-linecap='round' stroke-linejoin='round'/%3E%3C/svg%3E") center/20px no-repeat}

/* privacy band */
.band{background:var(--navy);color:#fff;border-radius:28px;padding:56px 44px}
.band h2{color:#fff}.band .sub{color:#b8c8d3;margin-bottom:32px}
.stats{display:grid;grid-template-columns:repeat(4,1fr);gap:20px}
@media(max-width:860px){.stats{grid-template-columns:repeat(2,1fr)}.band{padding:40px 24px}}
.stat b{display:block;font-size:30px;color:var(--teal);letter-spacing:-.02em}
.stat span{font-size:14px;color:#b8c8d3}

/* permissions table */
table{width:100%;border-collapse:collapse;background:#fff;border:1px solid var(--line);border-radius:18px;overflow:hidden;font-size:15.5px}
th,td{text-align:left;padding:16px 20px;border-bottom:1px solid var(--line);vertical-align:top}
th{background:#f5f5f7;font-size:13px;text-transform:uppercase;letter-spacing:.06em;color:var(--muted)}
tr:last-child td{border-bottom:none}
@media(max-width:640px){th:nth-child(1),td:nth-child(1){width:38%}}

/* faq */
details{background:#fff;border:1px solid var(--line);border-radius:16px;padding:20px 24px;margin-bottom:12px}
summary{font-weight:600;font-size:17px;cursor:pointer;list-style:none;display:flex;justify-content:space-between;gap:20px}
summary::-webkit-details-marker{display:none}
summary:after{content:"+";font-size:22px;color:var(--accent);line-height:1}
details[open] summary:after{content:"−"}
details p{color:var(--muted);margin-top:12px}

.note{font-size:14px;color:var(--muted);max-width:760px;margin:26px auto 0;text-align:center}

/* footer */
footer{background:#f5f5f7;border-top:1px solid var(--line);padding:44px 0;font-size:14px;color:var(--muted)}
footer .row{display:flex;flex-wrap:wrap;gap:20px;justify-content:space-between;align-items:center}
footer .links{display:flex;gap:22px;flex-wrap:wrap}
footer .links a{color:#424245}
.fine{margin-top:22px;font-size:13px}
</style>
</head>
<body>

<nav>
  <div class="wrap">
    <a class="brand" href="#top" aria-label="Take a Breath home">
      <svg class="logo" width="30" height="30" viewBox="0 0 120 120" aria-hidden="true"><rect width="120" height="120" rx="28" fill="#0b1d2a"/><g class="all"><circle class="ring r1" cx="60" cy="60" r="12.4" stroke-dasharray="15 7"/><circle class="ring r2" cx="60" cy="60" r="19.8" stroke-dasharray="19 9"/><circle class="ring r3" cx="60" cy="60" r="27.3" stroke-dasharray="22 10"/><circle class="ring r4" cx="60" cy="60" r="34.7" stroke-dasharray="27 11"/></g></svg>
      Take a Breath
    </a>
    <ul>
      <li><a href="#how">How it works</a></li>
      <li><a href="#who">Who it's for</a></li>
      <li><a href="#wellbeing">Wellbeing</a></li>
      <li><a href="#privacy">Privacy</a></li>
      <li><a href="#faq">FAQ</a></li>
    </ul>
  </div>
</nav>

<header class="hero" id="top">
  <div class="wrap">
    <svg class="logo" width="132" height="132" viewBox="0 0 120 120" role="img" aria-label="Take a Breath logo"><rect width="120" height="120" rx="28" fill="#0b1d2a" stroke="rgba(255,255,255,.12)"/><g class="all"><circle class="ring r1" cx="60" cy="60" r="12.4" stroke-dasharray="15 7"/><circle class="ring r2" cx="60" cy="60" r="19.8" stroke-dasharray="19 9"/><circle class="ring r3" cx="60" cy="60" r="27.3" stroke-dasharray="22 10"/><circle class="ring r4" cx="60" cy="60" r="34.7" stroke-dasharray="27 11"/></g></svg>
    <span class="eyebrow">For Android</span>
    <h1>Pause. Breathe.<br>Then decide.</h1>
    <p class="lead">Take a Breath adds a calm, mindful pause before the apps that pull you in, so scrolling becomes a choice instead of a habit. For you, and for the family.</p>
    <div class="badges">
      <span class="badge">Free</span>
      <span class="badge">No ads</span>
      <span class="badge">No account</span>
      <span class="badge">Works offline</span>
      <span class="badge">Nothing collected</span>
    </div>
    <a class="cta" href="#how">See how it works</a>
    <span class="soon">Coming soon to Google Play</span>
  </div>
</header>

<section id="why">
  <div class="wrap center">
    <div class="kicker">Why Take a Breath</div>
    <h2>Most of us reach for the phone without deciding to.</h2>
    <p class="sub">Endless feeds are designed to keep you in. Take a Breath puts a short, gentle moment between the tap and the scroll, which is often enough to remember what you actually wanted to do.</p>
    <div class="grid g3" style="text-align:left">
      <div class="card"><div class="ico"><svg viewBox="0 0 24 24"><circle cx="12" cy="12" r="9"/><path d="M12 7v5l3 2"/></svg></div><h3>Time back</h3><p>Fewer automatic opens and shorter sessions leave more hours for sleep, study, work, movement and people.</p></div>
      <div class="card"><div class="ico"><svg viewBox="0 0 24 24"><path d="M12 21s-7-4.5-7-10a4 4 0 0 1 7-2.6A4 4 0 0 1 19 11c0 5.5-7 10-7 10z"/></svg></div><h3>A calmer mind</h3><p>A few slow breaths before a feed can settle the pace of your day, rather than starting it with a rush.</p></div>
      <div class="card"><div class="ico"><svg viewBox="0 0 24 24"><circle cx="9" cy="8" r="3"/><circle cx="17" cy="9" r="2.5"/><path d="M3 20c0-3.3 2.7-6 6-6s6 2.7 6 6M15 14.5c3 0 6 1.5 6 5.5"/></svg></div><h3>Healthy family habits</h3><p>Parents can set clear, predictable limits on a child's phone without surveillance, screenshots or tracking.</p></div>
    </div>
  </div>
</section>

<section class="alt" id="how">
  <div class="wrap">
    <div class="split">
      <div>
        <div class="kicker">How it works</div>
        <h2>Three simple steps. No learning curve.</h2>
        <p class="sub" style="margin-bottom:24px">Choose the apps you want to be mindful about. Take a Breath does the rest, quietly in the background.</p>
        <ul class="ticks">
          <li><b>1. Choose guarded apps.</b> Pick social media or any app you'd like to open more deliberately.</li>
          <li><b>2. Breathe first.</b> When you open one, a guided breathing ring leads you through inhale, hold and release.</li>
          <li><b>3. Enjoy a timed session.</b> Use the app for the time you set. When it ends, a cooldown rest begins before the next session.</li>
        </ul>
      </div>
      <div class="demo">
        <div class="phone" role="img" aria-label="Illustration of the breathing screen">
          <div class="pulse"></div>
          <b>Breathe in…</b>
          <span>Take a moment before you scroll</span>
        </div>
      </div>
    </div>
  </div>
</section>

<section id="features">
  <div class="wrap">
    <div class="kicker">Features</div>
    <h2>Thoughtful controls. Nothing you don't need.</h2>
    <p class="sub">Everything is designed to be understood in seconds by an adult, and to be easy to set up on a child's phone.</p>
    <div class="grid g3">
      <div class="card"><h3>Guided breathing</h3><p>An animated ring paces your inhale, hold and release with adjustable timing.</p></div>
      <div class="card"><h3>Session and cooldown</h3><p>Set how long you can use a guarded app, then a mandatory rest before you can return.</p></div>
      <div class="card"><h3>Active windows</h3><p>Limit guarding to certain hours, or create named profiles such as Work, Study, Family time, Workout or your own.</p></div>
      <div class="card"><h3>Parent lock</h3><p>Protect settings with a numeric PIN and a one-time recovery code, so a child can't turn guarding off.</p></div>
      <div class="card"><h3>Calm by design</h3><p>Quiet notification, gentle visuals, and media is paused while the breathing screen is showing.</p></div>
      <div class="card"><h3>Fully on your device</h3><p>No internet access, no account, no servers. Your settings never leave your phone.</p></div>
    </div>
  </div>
</section>

<section class="alt" id="who">
  <div class="wrap">
    <div class="kicker">Who it's for</div>
    <h2>One app, for every kind of screen habit.</h2>
    <p class="sub">Whether you want to reclaim your own attention or guide a child's, the same calm pause applies.</p>
    <div class="grid g2">
      <div class="card"><h3>For yourself</h3><p>Cut down on mindless scrolling while working, studying, or winding down for bed. Build a rhythm of intention: breathe, use, rest.</p></div>
      <div class="card"><h3>For parents and families</h3><p>Set up Take a Breath on your child's phone, lock the settings with your PIN, and create a simple routine around homework, meals and bedtime. Pair it with Google Family Link to also control app installs and removal.</p></div>
      <div class="card"><h3>For students</h3><p>Use study profiles so guarded apps are gently held back during focus hours, without blocking everything.</p></div>
      <div class="card"><h3>For work and focus</h3><p>Create a Work profile for the hours you need your attention, and let the rest of the day stay flexible.</p></div>
    </div>
  </div>
</section>

<section id="wellbeing">
  <div class="wrap">
    <div class="kicker">Wellbeing</div>
    <h2>Small pauses, felt across daily life.</h2>
    <p class="sub">Healthy habits are built from many small moments. Here is how a calmer relationship with your phone can support everyday wellbeing for you and your family.</p>
    <div class="grid g3">
      <div class="card"><div class="ico"><svg viewBox="0 0 24 24"><path d="M9 4a4 4 0 0 0-4 4v1a3 3 0 0 0 0 6v1a4 4 0 0 0 4 4M15 4a4 4 0 0 1 4 4v1a3 3 0 0 1 0 6v1a4 4 0 0 1-4 4M12 4v16"/></svg></div><h3>Mental wellbeing</h3><p>Slow, deliberate breathing is a widely used relaxation practice. Fewer automatic checks may also mean less comparison, less noise, and more space to focus and feel present.</p></div>
      <div class="card"><div class="ico"><svg viewBox="0 0 24 24"><path d="M6 20l3-9 3 4 3-8 3 13"/></svg></div><h3>Physical wellbeing</h3><p>Less time looking down at a screen leaves more room for movement, posture breaks, outdoor time, meals without a phone, and earlier, calmer bedtimes.</p></div>
      <div class="card"><div class="ico"><svg viewBox="0 0 24 24"><path d="M3 11l9-7 9 7v9a1 1 0 0 1-1 1h-5v-6H9v6H4a1 1 0 0 1-1-1z"/></svg></div><h3>Family connection</h3><p>Shared limits make screen time a household routine rather than an argument. More attention for conversations, play, homework and time together.</p></div>
    </div>
    <p class="note">Take a Breath is a self-care and digital-habits tool. It is not a medical device and does not diagnose, treat or prevent any condition. If you are struggling with your health or wellbeing, please speak with a qualified professional.</p>
  </div>
</section>

<section class="alt" id="privacy">
  <div class="wrap">
    <div class="band">
      <div class="kicker" style="color:var(--teal)">Privacy first</div>
      <h2>We collect nothing. Really.</h2>
      <p class="sub">Take a Breath runs entirely on your device. It has no internet permission, no accounts, no analytics, no advertising and no third-party code that sends data anywhere.</p>
      <div class="stats">
        <div class="stat"><b>0</b><span>ads or trackers</span></div>
        <div class="stat"><b>0</b><span>accounts or sign-ups</span></div>
        <div class="stat"><b>0</b><span>bytes sent to servers</span></div>
        <div class="stat"><b>100%</b><span>stored on your phone</span></div>
      </div>
    </div>
  </div>
</section>

<section id="permissions">
  <div class="wrap">
    <div class="kicker">Transparency</div>
    <h2>Why the app asks for each permission.</h2>
    <p class="sub">Take a Breath only requests what it needs to show the breathing pause. You are shown a clear explanation before any permission is requested.</p>
    <table>
      <tr><th>Permission</th><th>What it's used for</th></tr>
      <tr><td><b>Usage access</b></td><td>To notice when one of your chosen apps comes to the foreground, so the breathing pause can appear. The app does not read or store what you do inside any app.</td></tr>
      <tr><td><b>Display over other apps</b></td><td>To show the breathing and rest screens on top of a guarded app.</td></tr>
      <tr><td><b>Notification (foreground service)</b></td><td>To keep the protection running reliably. The notification is silent, minimal and hidden on the lock screen.</td></tr>
    </table>
    <p class="note">Usage data is processed on the device only and is never recorded, shared or transmitted. The app has no internet permission at all.</p>
  </div>
</section>

<section class="alt" id="faq">
  <div class="wrap" style="max-width:780px">
    <div class="kicker">FAQ</div>
    <h2>Good questions</h2>
    <p class="sub" style="margin-bottom:28px">Quick answers about how Take a Breath works.</p>
    <details><summary>Is Take a Breath really free?</summary><p>Yes. It is free to use and has no advertising and no in-app tracking.</p></details>
    <details><summary>Does it collect or share any data?</summary><p>No. Settings stay on your device and the app cannot access the internet. Read the full <a href="privacy.html">Privacy Policy</a>.</p></details>
    <details><summary>Can I use it on my child's phone?</summary><p>Yes. Turn on the Parent lock with a numeric PIN so only you can change settings. For preventing uninstall or controlling app installs, use Google Family Link alongside Take a Breath.</p></details>
    <details><summary>What if I forget the parent PIN?</summary><p>When you set the PIN you receive a one-time recovery code. Keep it somewhere safe, since it is the only way to reset the PIN.</p></details>
    <details><summary>Which apps can I guard?</summary><p>You choose. Social media is the common use, but any installed app can be guarded.</p></details>
    <details><summary>How do I get in touch?</summary><p>Email <a href="mailto:support.takeabreath@loopxstudio.ca">support.takeabreath@loopxstudio.ca</a>.</p></details>
  </div>
</section>

<footer>
  <div class="wrap">
    <div class="row">
      <div class="brand">
        <svg class="logo" width="26" height="26" viewBox="0 0 120 120" aria-hidden="true"><rect width="120" height="120" rx="28" fill="#0b1d2a"/><g class="all"><circle class="ring r1" cx="60" cy="60" r="12.4" stroke-dasharray="15 7"/><circle class="ring r2" cx="60" cy="60" r="19.8" stroke-dasharray="19 9"/><circle class="ring r3" cx="60" cy="60" r="27.3" stroke-dasharray="22 10"/><circle class="ring r4" cx="60" cy="60" r="34.7" stroke-dasharray="27 11"/></g></svg>
        Take a Breath
      </div>
      <div class="links">
        <a href="privacy.html">Privacy Policy</a>
        <a href="terms.html">Terms of Service</a>
        <a href="mailto:support.takeabreath@loopxstudio.ca">Contact support</a>
      </div>
    </div>
    <p class="fine">Take a Breath is made by LoopX Studio, Toronto, Canada. © 2026 LoopX Studio. Google Play and Android are trademarks of Google LLC. Take a Breath is not affiliated with or endorsed by any social media company.</p>
  </div>
</footer>

</body>
</html>
