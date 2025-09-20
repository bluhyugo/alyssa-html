<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <meta name="description" content="Academic services, verified account offerings, and portfolio by [Your Name/Business]" />
  <title>[Your Business Name] — Academic Help • Verified Accounts • Portfolio</title>

  <!-- Simple, clean CSS (feel free to replace with your own) -->
  <style>
    :root{
      --accent:#0b74de;
      --muted:#666;
      --bg:#f6f8fb;
      --card:#ffffff;
      --radius:14px;
      font-family: Inter, system-ui, -apple-system, "Segoe UI", Roboto, "Helvetica Neue", Arial;
    }
    *{box-sizing:border-box}
    body{
      margin:0;
      background:linear-gradient(180deg,#f6f8fb 0%, #ffffff 100%);
      color:#111;
      line-height:1.5;
      -webkit-font-smoothing:antialiased;
    }
    .container{max-width:1100px;margin:32px auto;padding:0 20px;}
    header{display:flex;align-items:center;justify-content:space-between;gap:16px}
    .brand{display:flex;align-items:center;gap:12px}
    .logo{width:56px;height:56px;border-radius:12px;background:var(--accent);display:inline-grid;place-items:center;color:#fff;font-weight:700;}
    nav a{margin-left:14px;color:var(--muted);text-decoration:none;font-weight:600}
    nav a:hover{color:var(--accent)}
    main{margin-top:28px}
    .hero{display:grid;grid-template-columns:1fr 420px;gap:28px;align-items:center}
    .hero .badge{display:inline-block;background:rgba(11,116,222,0.12);color:var(--accent);padding:8px 12px;border-radius:999px;font-weight:700;margin-bottom:12px}
    h1{font-size:28px;margin:0 0 12px}
    p.lead{color:var(--muted);margin:0 0 18px}
    .cta{display:flex;gap:10px;flex-wrap:wrap}
    .btn{display:inline-block;padding:10px 16px;border-radius:10px;text-decoration:none;font-weight:700}
    .btn-primary{background:var(--accent);color:#fff}
    .btn-ghost{border:1px solid #e6e9ef;background:transparent;color:var(--accent)}
    .card{background:var(--card);padding:20px;border-radius:var(--radius);box-shadow:0 6px 20px rgba(20,30,80,0.06)}
    .services{display:grid;grid-template-columns:repeat(auto-fit,minmax(240px,1fr));gap:16px;margin-top:20px}
    .service-title{margin:0 0 8px}
    .portfolio-grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(220px,1fr));gap:14px;margin-top:14px}
    .project{border-radius:10px;overflow:hidden;display:block;text-decoration:none;color:inherit;background:#fafbff}
    .project img{width:100%;height:140px;object-fit:cover;display:block}
    .project .meta{padding:10px}
    footer{margin-top:34px;padding:20px 0;color:var(--muted);font-size:14px;border-top:1px solid #edf0f7}
    .grid-2{display:grid;grid-template-columns:1fr 320px;gap:18px}
    @media (max-width:900px){
      .hero{grid-template-columns:1fr}
      .grid-2{grid-template-columns:1fr}
    }

    /* accessibility helpers */
    .sr-only{position:absolute;width:1px;height:1px;padding:0;margin:-1px;overflow:hidden;clip:rect(0,0,0,0);white-space:nowrap;border:0}
    .note{font-size:13px;color:var(--muted)}
    .pill{display:inline-block;padding:6px 8px;border-radius:999px;background:#eef6ff;color:var(--accent);font-weight:700}
    .tag{font-size:12px;padding:6px 8px;border-radius:8px;background:#f2f5fb;color:var(--muted);display:inline-block;margin-right:8px}
    form input, form textarea{width:100%;padding:10px;border-radius:8px;border:1px solid #e6e9ef;margin-top:8px}
    .small{font-size:13px;color:var(--muted)}
  </style>
</head>
<body>
  <div class="container" role="document">
    <header>
      <div class="brand" role="banner">
        <div class="logo" aria-hidden="true">AB</div>
        <div>
          <div style="font-weight:800">[Your Business Name]</div>
          <div class="note">Academic Services • Verified Accounts • Portfolio</div>
        </div>
      </div>

      <nav aria-label="Primary">
        <a href="#services">Services</a>
        <a href="#accounts">Accounts</a>
        <a href="#portfolio">Portfolio</a>
        <a href="#contact">Contact</a>
      </nav>
    </header>

    <main>
      <section class="hero" aria-labelledby="hero-heading">
        <div>
          <span class="badge">Trusted • Verified</span>
          <h1 id="hero-heading">Academic help, verified accounts, and creative portfolio — all in one place</h1>
          <p class="lead">We provide tutoring, assignments review, research guidance, plus ethically sourced/verified accounts for specific services (with proof). See our portfolio and testimonials below.</p>

          <div class="cta">
            <a class="btn btn-primary" href="#contact">Get Started</a>
            <a class="btn btn-ghost" href="#portfolio">See Portfolio</a>
          </div>

          <div style="margin-top:16px" aria-hidden="false">
            <span class="tag">Tutoring</span><span class="tag">Proofreading</span><span class="tag">Account Verification</span>
          </div>

          <div style="margin-top:16px" class="note">
            <strong>Important:</strong> Accounts are only offered when legally transferable and with documented proof. Read our <a href="#terms">Verification & Terms</a>.
          </div>
        </div>

        <aside class="card" aria-label="Quick contact">
          <h3 style="margin-top:0">Quick Contact</h3>
          <p class="small">Email: <a href="mailto:youremail@example.com">youremail@example.com</a></p>
          <p class="small">Phone/Telegram: <a href="tel:+639xxxxxxxxx">+63 9XXXXXXXXX</a></p>
          <p class="small">Social: <a href="https://facebook.com/yourprofile" target="_blank" rel="noopener">Facebook</a> • <a href="#" target="_blank" rel="noopener">Instagram</a></p>
          <p style="margin-top:10px" class="pill">Open for bookings</p>
        </aside>
      </section>

      <!-- Services -->
      <section id="services" style="margin-top:28px">
        <h2>Our Academic Services</h2>
        <p class="note">Personalized help for high school and college: tutoring, paper editing, research assistance, and presentation coaching.</p>

        <div class="services" role="list">
          <article class="card" role="listitem">
            <h3 class="service-title">One-on-One Tutoring</h3>
            <p class="small">Subject-focused tutoring (IT, Math, English, Research Methods). Flexible scheduling and progress tracking.</p>
          </article>

          <article class="card" role="listitem">
            <h3 class="service-title">Assignment & Paper Editing</h3>
            <p class="small">Grammar, structure, citations (APA/MLA/Chicago), and coach feedback to improve clarity and grade potential.</p>
          </article>

          <article class="card" role="listitem">
            <h3 class="service-title">Presentation & Defense Prep</h3>
            <p class="small">Slide design, script polishing, mock Q&A, and confidence coaching for viva/defense or class presentations.</p>
          </article>

          <article class="card" role="listitem">
            <h3 class="service-title">Research & Data Help</h3>
            <p class="small">Topic selection, literature review help, basic data analysis guidance, and citation management support.</p>
          </article>
        </div>
      </section>

      <!-- Accounts -->
      <section id="accounts" style="margin-top:28px">
        <h2>Verified / Legit Account Offerings</h2>
        <p class="note">We list only accounts that are explicitly transferable and compliant with the originating service's policies. Every account sold includes verification proof and a transfer receipt.</p>

        <div class="grid-2" style="margin-top:12px;gap:18px;">
          <div>
            <div class="card">
              <h3 style="margin-top:0">How verification works</h3>
              <ol>
                <li class="small">Proof screenshots showing account age and access (no sensitive passwords in public view).</li>
                <li class="small">Delivery via secure handover process (change of registered email / two-factor transfer as required).</li>
                <li class="small">Buyer signs a short receipt acknowledging transfer and terms.</li>
              </ol>
              <p class="small"><strong>Note:</strong> We refuse accounts that were obtained through hacking, stolen credentials, or in violation of law.</p>
            </div>

            <div class="card" style="margin-top:12px">
              <h4 style="margin:0 0 8px">Sample offerings</h4>
              <ul class="small">
                <li>Verified streaming account — includes original email transfer</li>
                <li>Educational software subscription — transferable institutional license (if allowed)</li>
                <li>Specialty service accounts — proof of ownership provided</li>
              </ul>
            </div>
          </div>

          <aside class="card">
            <h4 style="margin-top:0">Verification & Terms <a href="#terms" style="font-size:12px;margin-left:8px;text-decoration:none">(read)</a></h4>
            <p class="small">All sales include a terms document and at least one form of verification (screenshot or recorded video). Refunds considered only if proof is falsified or transfer fails due to seller fault.</p>
            <p class="small">By purchasing you confirm you understand platform transfer rules and local regulations.</p>
          </aside>
        </div>
      </section>

      <!-- Portfolio -->
      <section id="portfolio" style="margin-top:28px">
        <h2>Portfolio</h2>
        <p class="note">Selected projects, tutoring success stories, and verified account handovers (redacted for privacy).</p>

        <div class="portfolio-grid" aria-live="polite">
          <!-- Example project 1 -->
          <a class="project" href="#" aria-label="Project: Research paper editing sample">
            <img src="https://images.unsplash.com/photo-1526378729407-1e6bc1e5d7a6?q=80&w=1200&auto=format&fit=crop&ixlib=rb-4.0.3&s=example" alt="Student working on laptop">
            <div class="meta">
              <strong>Research paper editing — Communication</strong>
              <div class="small">Result: Improved clarity and citation formatting. Client grade: A-</div>
            </div>
          </a>

          <!-- Example project 2 -->
          <a class="project" href="#" aria-label="Project: Tutoring success story">
            <img src="https://images.unsplash.com/photo-1522202176988-66273c2fd55f?q=80&w=1200&auto=format&fit=crop&ixlib=rb-4.0.3&s=example" alt="Tutor explaining on a whiteboard">
            <div class="meta">
              <strong>Tutoring — Calculus</strong>
              <div class="small">Result: Student went from 65% to 88% in 6 weeks.</div>
            </div>
          </a>

          <!-- Example project 3 -->
          <a class="project" href="#" aria-label="Project: Account handover (redacted)">
            <img src="https://images.unsplash.com/photo-1515879218367-8466d910aaa4?q=80&w=1200&auto=format&fit=crop&ixlib=rb-4.0.3&s=example" alt="Secure handshake">
            <div class="meta">
              <strong>Account Transfer (redacted)</strong>
              <div class="small">Proof-of-transfer provided; buyer confirmed successful handover.</div>
            </div>
          </a>
        </div>
      </section>

      <!-- Contact & form -->
      <section id="contact" style="margin-top:28px">
        <h2>Contact & Booking</h2>
        <div style="display:grid;grid-template-columns:1fr 320px;gap:18px">
          <div class="card" aria-labelledby="contact-form-heading">
            <h3 id="contact-form-heading" style="margin-top:0">Send us a message</h3>
            <!-- Simple contact form (mailto fallback). Replace action with your server endpoint if you have one. -->
            <form action="mailto:youremail@example.com" method="post" enctype="text/plain" aria-label="Contact form">
              <label for="name">Your name</label>
              <input id="name" name="name" required placeholder="Juan dela Cruz" />

              <label for="email">Email</label>
              <input id="email" name="email" type="email" required placeholder="you@example.com" />

              <label for="service">Service interested in</label>
              <input id="service" name="service" placeholder="Tutoring / Account verification / Portfolio inquiry" />

              <label for="message">Message</label>
              <textarea id="message" name="message" rows="5" placeholder="Tell us what you need..."></textarea>

              <div style="margin-top:10px">
                <button class="btn btn-primary" type="submit">Send message</button>
                <a class="btn btn-ghost" href="mailto:youremail@example.com">Or email directly</a>
              </div>
            </form>
          </div>

          <aside class="card" aria-label="Booking info">
            <h4 style="margin-top:0">Booking & Payments</h4>
            <p class="small">We accept bank transfers, GCash/PayMaya, and cash on meet (when safe). For account purchases, full payment is required after verification and before transfer.</p>
            <h4 style="margin:10px 0 6px">Business hours</h4>
            <p class="small">Mon–Sat: 9:00 AM — 7:00 PM (Philippine Time)</p>
            <p class="small">Response time: Usually within 24 hours.</p>
          </aside>
        </div>
      </section>

      <!-- Terms (short) -->
      <section id="terms" style="margin-top:28px">
        <h2>Verification & Terms (short)</h2>
        <div class="card">
          <h4 style="margin-top:0">Seller guarantees</h4>
          <ul class="small">
            <li>Accounts sold are claimed by seller to be their property; buyer receives documented proof.</li>
            <li>Transfers are completed using the appropriate official transfer methods wherever possible.</li>
            <li>Refunds are considered if proof is proven false or transfer cannot be completed due to seller negligence.</li>
          </ul>

          <h4 style="margin-top:10px">Buyer responsibilities</h4>
          <ul class="small">
            <li>Confirm with the originating platform whether account transfer is allowed.</li>
            <li>Complete payments only after a satisfactory verification step defined in the listing.</li>
            <li>Report any suspicious listings; we reserve the right to refuse any sale.</li>
          </ul>
        </div>
      </section>
    </main>

    <footer>
      <div style="display:flex;justify-content:space-between;align-items:center;flex-wrap:wrap;gap:12px">
        <div>
          <strong>[Your Business Name]</strong> — Academic help • Verified accounts • Portfolio<br>
          <span class="small">© <span id="year"></span> All rights reserved</span>
        </div>

        <div class="small">
          <a href="#terms">Terms</a> • <a href="#contact">Contact</a>
        </div>
      </div>
    </footer>
  </div>

  <script>
    // Accessibility: focus visible outline for keyboard users
    (function(){
      function handleFirstTab(e){
        if(e.key === 'Tab'){
          document.documentElement.classList.add('show-focus');
          window.removeEventListener('keydown', handleFirstTab);
        }
      }
      window.addEventListener('keydown', handleFirstTab);
      // fill year
      document.getElementById('year').textContent = new Date().getFullYear();
    })();
  </script>
</body>
</html>

