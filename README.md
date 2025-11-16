
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Khwaja Owesh Choudhary — CV</title>
  <meta name="description" content="CV / Resume — Khwaja Owesh Choudhary: Sales & Service Engineer" />
  <link rel="icon" href="data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 100 100'%3E%3Crect width='100' height='100' rx='20' fill='%23333'/%3E%3Ctext x='50' y='57' font-size='48' text-anchor='middle' fill='white' font-family='Arial'%3EO%3C/text%3E%3C/svg%3E">
  <style>
    :root{
      --bg:#0f1724; /* dark */
      --card:#0b1220;
      --muted:#94a3b8;
      --accent:#06b6d4;
      --glass: rgba(255,255,255,0.04);
      --text:#e6eef8;
      --maxw:1000px;
    }
    *{box-sizing:border-box}
    html,body{height:100%;margin:0;font-family:Inter,ui-sans-serif,system-ui,-apple-system,"Segoe UI",Roboto,"Helvetica Neue",Arial;color:var(--text);background:linear-gradient(180deg,#071025 0%, #041021 100%);}    
    .wrap{max-width:var(--maxw);margin:28px auto;padding:28px}

    .card{background:linear-gradient(180deg, rgba(255,255,255,0.02), rgba(255,255,255,0.01));border-radius:14px;padding:26px;display:grid;grid-template-columns:320px 1fr;gap:26px;box-shadow:0 8px 30px rgba(2,6,23,0.6);backdrop-filter: blur(6px)}

    /* header / left column */
    .left{padding:6px}
    .photo{width:160px;height:160px;border-radius:50%;object-fit:cover;border:6px solid var(--glass);box-shadow:0 6px 20px rgba(2,6,23,0.6);display:block;margin:auto}
    h1{font-size:22px;margin:10px 0 4px;text-align:center}
    .role{text-align:center;color:var(--muted);font-size:13px;margin-bottom:12px}

    .contact-card{background:linear-gradient(180deg, rgba(255,255,255,0.02), rgba(255,255,255,0.01));padding:12px;border-radius:10px;}
    .contact-card p{margin:7px 0;font-size:14px;color:var(--muted)}

    /* right column */
    .right{padding:6px}
    .section{margin-bottom:18px}
    .section h2{font-size:16px;margin:0 0 8px}
    p.lead{color:var(--muted);margin:0 0 8px;line-height:1.5}

    ul.skills{list-style:none;padding:0;margin:8px 0 0;display:flex;flex-wrap:wrap;gap:8px}
    ul.skills li{background:rgba(255,255,255,0.03);padding:6px 10px;border-radius:999px;font-size:13px;color:var(--muted)}

    .timeline{list-style:none;padding:0;margin:8px 0}
    .timeline li{background:rgba(255,255,255,0.02);padding:12px;border-radius:8px;margin-bottom:8px}
    .meta{font-size:12px;color:var(--muted)}

    /* buttons */
    .controls{display:flex;gap:10px;flex-wrap:wrap;justify-content:center;margin-top:12px}
    .btn{background:linear-gradient(90deg,var(--accent),#0ea5b3);border:none;color:#042022;padding:10px 14px;border-radius:10px;font-weight:600;cursor:pointer;box-shadow:0 6px 18px rgba(6,182,212,0.12)}
    .btn.ghost{background:transparent;border:1px solid rgba(255,255,255,0.06);color:var(--text)}

    /* QR + utility */
    .qr{display:flex;align-items:center;gap:12px}
    .qr img{width:84px;height:84px;border-radius:10px}

    /* projects grid */
    .grid{display:grid;grid-template-columns:repeat(2,1fr);gap:12px}
    .card-mini{background:rgba(255,255,255,0.02);padding:10px;border-radius:10px}

    /* responsive */
    @media (max-width:880px){
      .card{grid-template-columns:1fr;}
      .grid{grid-template-columns:1fr}
      .photo{width:140px;height:140px}
    }

    /* subtle animations */
    .fade-in{animation:fadeIn .6s ease both}
    @keyframes fadeIn{from{opacity:0;transform:translateY(6px)}to{opacity:1;transform:none}}

    /* dark/light toggle */
    .topbar{display:flex;justify-content:space-between;align-items:center;margin-bottom:10px}
    .toggle{background:transparent;border:1px solid rgba(255,255,255,0.06);padding:8px;border-radius:8px;color:var(--muted);cursor:pointer}

    /* print styles */
    @media print{
      body{background:white;color:black}
      .card{box-shadow:none;background:white}
      .controls, .toggle, .qr{display:none}
    }
  </style>
</head>
<body>
  <div class="wrap fade-in">
    <div class="topbar">
      <div style="color:var(--muted)">Curriculum Vitae — <strong>Khwaja Owesh Choudhary</strong></div>
      <div>
        <button class="toggle" id="themeToggle">Toggle Dark/Light</button>
      </div>
    </div>

    <div class="card">
      <div class="left">
        <!-- replace profile.jpg with your actual image file or embedded base64 -->
        <img src="data:image/jpeg;base64,/9j/4AAQSkZJRgABAQAAAQABAAD/...your_base64_photo_data_here..." alt="Profile Photo" class="photo" id="profilePhoto" src="profile.jpg" onerror="this.style.display='none'" />
        <h1>Khwaja Owesh Choudhary</h1>
        <div class="role">Sales & Service Engineer • Biomedical Engineer</div>

        <div class="contact-card">
          <p><strong>Email:</strong> <a href="mailto:Khwaja.owesh@gmail.com" style="color:var(--accent);text-decoration:none">Khwaja.owesh@gmail.com</a></p>
          <p><strong>Phone:</strong> <a href="tel:+971583027876" style="color:var(--accent);text-decoration:none">+971 58 302 7876</a></p>
          <p><strong>Location:</strong> Dubai, United Arab Emirates</p>
          <p><strong>Nationality:</strong> Indian</p>
          <p><strong>Visa:</strong> Visit Visa — Valid till 08 Dec 2025</p>
        </div>

        <div style="margin-top:12px;text-align:center">
          <div class="controls">
            <button class="btn" id="whatsappBtn">WhatsApp</button>
            <button class="btn ghost" id="linkedinBtn">LinkedIn</button>
            <button class="btn ghost" id="downloadPdf">Download PDF</button>
            <button class="btn ghost" id="printBtn">Print</button>
          </div>
        </div>

        <div style="margin-top:14px;text-align:center" class="qr">
          <img id="qrImg" alt="QR code" src="" />
          <div style="text-align:left;color:var(--muted);font-size:13px">Scan to open<br/><strong id="publicUrl">yourusername.github.io</strong></div>
        </div>
      </div>

      <div class="right">
        <div class="section">
          <h2>Professional Summary</h2>
          <p class="lead">Biomedical Engineering graduate with over 2 years of experience in medical device maintenance and technical support specialising in endoscopic systems. Experienced in calibration, troubleshooting, staff training, and quality assurance to maintain high standards of device performance and patient safety.</p>
          <ul class="skills">
            <li>Endoscopic Maintenance</li>
            <li>Calibration & Troubleshooting</li>
            <li>Imaging Systems</li>
            <li>Technical Training</li>
            <li>Quality Assurance</li>
          </ul>
        </div>

        <div class="section">
          <h2>Experience</h2>
          <ul class="timeline">
            <li>
              <div style="display:flex;justify-content:space-between"><strong>Sales & Service Engineer — Mitra Industries Pvt. Ltd.</strong><span class="meta">08/2022 — Present • Mumbai, India</span></div>
              <div class="meta">• Maintenance & calibration of endoscopic systems • Technical support & training • Quality assurance & compliance</div>
            </li>
            <li>
              <div style="display:flex;justify-content:space-between"><strong>Biomedical Intern — SL Raheja Fortis Hospital</strong><span class="meta">01/2022 — 04/2022 • Mumbai, India</span></div>
              <div class="meta">• Assisted with equipment maintenance • Troubleshooting & inventory support</div>
            </li>
          </ul>
        </div>

        <div class="section">
          <h2>Education</h2>
          <div class="card-mini">
            <strong>B.E. — Biomedical Engineering</strong><br/>Vidyalankar Institute of Technology, Mumbai (2019 — 2022)
          </div>
          <div style="height:8px"></div>
          <div class="card-mini">
            <strong>Diploma — Medical Electronics</strong><br/>VPM's Polytechnic, Mumbai (2017 — 2019)
          </div>
        </div>

        <div class="section">
          <h2>Projects & Achievements</h2>
          <div class="grid">
            <div class="card-mini"><strong>Endoscope Calibration Workflow</strong><div class="meta">Developed SOP for optical calibration & imaging validation.</div></div>
            <div class="card-mini"><strong>Training Program</strong><div class="meta">Conducted hands-on training for hospital staff on device handling.</div></div>
            <div class="card-mini"><strong>Quality Initiative</strong><div class="meta">Participated in corrective action planning to reduce device downtime.</div></div>
            <div class="card-mini"><strong>Internship Recognition</strong><div class="meta">Acknowledged for proactive troubleshooting at SL Raheja Fortis.</div></div>
          </div>
        </div>

        <div class="section">
          <h2>Certificates</h2>
          <div class="grid">
            <div class="card-mini">Diploma: Medical Electronics</div>
            <div class="card-mini">B.E. Biomedical Engineering</div>
          </div>
        </div>

        <div class="section">
          <h2>Languages</h2>
          <p class="meta">English • Hindi • Arabic</p>
        </div>

        <div class="section">
          <h2>Contact / Message</h2>
          <!-- Form uses Formspree placeholder; replace ACTION with your Formspree endpoint or use mailto fallback -->
          <form id="contactForm" action="https://formspree.io/f/your-id" method="POST">
            <div style="display:flex;gap:8px;flex-wrap:wrap">
              <input name="name" placeholder="Your name" required style="flex:1;padding:10px;border-radius:8px;border:1px solid rgba(255,255,255,0.04);background:transparent;color:var(--text)">
              <input name="email" type="email" placeholder="Your email" required style="flex:1;padding:10px;border-radius:8px;border:1px solid rgba(255,255,255,0.04);background:transparent;color:var(--text)">
            </div>
            <textarea name="message" placeholder="Message" required style="width:100%;margin-top:8px;padding:10px;border-radius:8px;border:1px solid rgba(255,255,255,0.04);background:transparent;color:var(--text)"></textarea>
            <div style="margin-top:8px;display:flex;gap:8px">
              <button class="btn" type="submit">Send Message</button>
              <button class="btn ghost" type="button" id="mailtoFallback">Email Me</button>
            </div>
          </form>
        </div>

      </div>
    </div>
  </div>

  <script>
    // --- Utilities ---
    const usernamePlaceholder = 'yourusername.github.io';
    document.getElementById('publicUrl').textContent = usernamePlaceholder;

    // Theme toggle (simple light mode)
    const themeToggle = document.getElementById('themeToggle');
    themeToggle.addEventListener('click', ()=>{
      if(document.documentElement.style.getPropertyValue('--bg') === ''){
        // already default
      }
      // quick light toggle by swapping CSS vars
      const isLight = document.documentElement.style.getPropertyValue('--bg') === '#ffffff';
      if(!isLight){
        document.documentElement.style.setProperty('--bg','#ffffff');
        document.documentElement.style.setProperty('--card','#f8fafc');
        document.documentElement.style.setProperty('--muted','#475569');
        document.documentElement.style.setProperty('--accent','#0ea5a3');
        document.documentElement.style.setProperty('--glass','rgba(0,0,0,0.04)');
        document.documentElement.style.setProperty('--text','#082032');
        document.body.style.background = 'linear-gradient(180deg,#ffffff 0%, #f3f4f6 100%)';
      } else {
        document.documentElement.style.setProperty('--bg','#0f1724');
        document.documentElement.style.setProperty('--card','#0b1220');
        document.documentElement.style.setProperty('--muted','#94a3b8');
        document.documentElement.style.setProperty('--accent','#06b6d4');
        document.documentElement.style.setProperty('--glass','rgba(255,255,255,0.04)');
        document.documentElement.style.setProperty('--text','#e6eef8');
        document.body.style.background = 'linear-gradient(180deg,#071025 0%, #041021 100%)';
      }
    });

    // WhatsApp button behavior (opens chat)
    document.getElementById('whatsappBtn').addEventListener('click', ()=>{
      const phone = '+971583027876';
      const text = encodeURIComponent('Hello Khwaja, I saw your CV and would like to get in touch.');
      window.open(`https://wa.me/${phone.replace(/[^\\d]/g,'')}?text=${text}`,'_blank');
    });

    // LinkedIn button (placeholder)
    document.getElementById('linkedinBtn').addEventListener('click', ()=>{
      const url = prompt('Paste your LinkedIn profile URL (full):','https://www.linkedin.com/in/');
      if(url) window.open(url,'_blank');
    });

    // Print & Download PDF
    document.getElementById('printBtn').addEventListener('click', ()=>window.print());
    document.getElementById('downloadPdf').addEventListener('click', ()=>window.print());

    // Mailto fallback for contact form
    document.getElementById('mailtoFallback').addEventListener('click', ()=>{
      const name = document.querySelector('[name="name"]').value || 'New contact';
      const email = document.querySelector('[name="email"]').value || '';
      const message = document.querySelector('[name="message"]').value || '';
      const subject = encodeURIComponent('Contact from CV — ' + name);
      const body = encodeURIComponent('From: '+name+" (%22+email+" )\n\n"+message);
      window.location.href = `mailto:Khwaja.owesh@gmail.com?subject=${subject}&body=${body}`;
    });

    // QR code generation (using chart.googleapis.com)
    const publicUrl = 'https://' + usernamePlaceholder;
    const qrSrc = 'https://chart.googleapis.com/chart?cht=qr&chs=200x200&chl=' + encodeURIComponent(publicUrl);
    document.getElementById('qrImg').src = qrSrc;

    // If profile.jpg isn't provided, optionally embed base64 if available (we keep src=profile.jpg)

    // Form: graceful message on submit (if using Formspree replace action with your endpoint)
    document.getElementById('contactForm').addEventListener('submit', (e)=>{
      // Allow default submit only if user replaced action
      const form = e.target;
      if(form.action.includes('formspree.io') && form.action.includes('your-id')){
        e.preventDefault();
        alert('Replace the form ACTION with your Formspree endpoint or the form will not submit. Alternatively use the Email button.');
      } else {
        // let it submit (Formspree or other will handle)
      }
    });

    // small accessibility: focus outline
    document.addEventListener('keydown',(e)=>{if(e.key==='Tab')document.body.classList.add('show-focus')})
  </script>
</body>
</html>

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Khwaja Owesh Choudhary — CV</title>
  <meta name="description" content="CV / Resume — Khwaja Owesh Choudhary: Sales & Service Engineer" />
  <link rel="icon" href="data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 100 100'%3E%3Crect width='100' height='100' rx='20' fill='%23333'/%3E%3Ctext x='50' y='57' font-size='48' text-anchor='middle' fill='white' font-family='Arial'%3EO%3C/text%3E%3C/svg%3E">
  <style>
    :root{
      --bg:#0f1724; /* dark */
      --card:#0b1220;
      --muted:#94a3b8;
      --accent:#06b6d4;
      --glass: rgba(255,255,255,0.04);
      --text:#e6eef8;
      --maxw:1000px;
    }
    *{box-sizing:border-box}
    html,body{height:100%;margin:0;font-family:Inter,ui-sans-serif,system-ui,-apple-system,"Segoe UI",Roboto,"Helvetica Neue",Arial;color:var(--text);background:linear-gradient(180deg,#071025 0%, #041021 100%);}    
    .wrap{max-width:var(--maxw);margin:28px auto;padding:28px}

    .card{background:linear-gradient(180deg, rgba(255,255,255,0.02), rgba(255,255,255,0.01));border-radius:14px;padding:26px;display:grid;grid-template-columns:320px 1fr;gap:26px;box-shadow:0 8px 30px rgba(2,6,23,0.6);backdrop-filter: blur(6px)}

    /* header / left column */
    .left{padding:6px}
    .photo{width:160px;height:160px;border-radius:50%;object-fit:cover;border:6px solid var(--glass);box-shadow:0 6px 20px rgba(2,6,23,0.6);display:block;margin:auto}
    h1{font-size:22px;margin:10px 0 4px;text-align:center}
    .role{text-align:center;color:var(--muted);font-size:13px;margin-bottom:12px}

    .contact-card{background:linear-gradient(180deg, rgba(255,255,255,0.02), rgba(255,255,255,0.01));padding:12px;border-radius:10px;}
    .contact-card p{margin:7px 0;font-size:14px;color:var(--muted)}

    /* right column */
    .right{padding:6px}
    .section{margin-bottom:18px}
    .section h2{font-size:16px;margin:0 0 8px}
    p.lead{color:var(--muted);margin:0 0 8px;line-height:1.5}

    ul.skills{list-style:none;padding:0;margin:8px 0 0;display:flex;flex-wrap:wrap;gap:8px}
    ul.skills li{background:rgba(255,255,255,0.03);padding:6px 10px;border-radius:999px;font-size:13px;color:var(--muted)}

    .timeline{list-style:none;padding:0;margin:8px 0}
    .timeline li{background:rgba(255,255,255,0.02);padding:12px;border-radius:8px;margin-bottom:8px}
    .meta{font-size:12px;color:var(--muted)}

    /* buttons */
    .controls{display:flex;gap:10px;flex-wrap:wrap;justify-content:center;margin-top:12px}
    .btn{background:linear-gradient(90deg,var(--accent),#0ea5b3);border:none;color:#042022;padding:10px 14px;border-radius:10px;font-weight:600;cursor:pointer;box-shadow:0 6px 18px rgba(6,182,212,0.12)}
    .btn.ghost{background:transparent;border:1px solid rgba(255,255,255,0.06);color:var(--text)}

    /* QR + utility */
    .qr{display:flex;align-items:center;gap:12px}
    .qr img{width:84px;height:84px;border-radius:10px}

    /* projects grid */
    .grid{display:grid;grid-template-columns:repeat(2,1fr);gap:12px}
    .card-mini{background:rgba(255,255,255,0.02);padding:10px;border-radius:10px}

    /* responsive */
    @media (max-width:880px){
      .card{grid-template-columns:1fr;}
      .grid{grid-template-columns:1fr}
      .photo{width:140px;height:140px}
    }

    /* subtle animations */
    .fade-in{animation:fadeIn .6s ease both}
    @keyframes fadeIn{from{opacity:0;transform:translateY(6px)}to{opacity:1;transform:none}}

    /* dark/light toggle */
    .topbar{display:flex;justify-content:space-between;align-items:center;margin-bottom:10px}
    .toggle{background:transparent;border:1px solid rgba(255,255,255,0.06);padding:8px;border-radius:8px;color:var(--muted);cursor:pointer}

    /* print styles */
    @media print{
      body{background:white;color:black}
      .card{box-shadow:none;background:white}
      .controls, .toggle, .qr{display:none}
    }
  </style>
</head>
<body>
  <div class="wrap fade-in">
    <div class="topbar">
      <div style="color:var(--muted)">Curriculum Vitae — <strong>Khwaja Owesh Choudhary</strong></div>
      <div>
        <button class="toggle" id="themeToggle">Toggle Dark/Light</button>
      </div>
    </div>

    <div class="card">
      <div class="left">
        <!-- replace profile.jpg with your actual image file or embedded base64 -->
        <img src="data:image/jpeg;base64,/9j/4AAQSkZJRgABAQAAAQABAAD/...your_base64_photo_data_here..." alt="Profile Photo" class="photo" id="profilePhoto" src="profile.jpg" onerror="this.style.display='none'" />
        <h1>Khwaja Owesh Choudhary</h1>
        <div class="role">Sales & Service Engineer • Biomedical Engineer</div>

        <div class="contact-card">
          <p><strong>Email:</strong> <a href="mailto:Khwaja.owesh@gmail.com" style="color:var(--accent);text-decoration:none">Khwaja.owesh@gmail.com</a></p>
          <p><strong>Phone:</strong> <a href="tel:+971583027876" style="color:var(--accent);text-decoration:none">+971 58 302 7876</a></p>
          <p><strong>Location:</strong> Dubai, United Arab Emirates</p>
          <p><strong>Nationality:</strong> Indian</p>
          <p><strong>Visa:</strong> Visit Visa — Valid till 08 Dec 2025</p>
        </div>

        <div style="margin-top:12px;text-align:center">
          <div class="controls">
            <button class="btn" id="whatsappBtn">WhatsApp</button>
            <button class="btn ghost" id="linkedinBtn">LinkedIn</button>
            <button class="btn ghost" id="downloadPdf">Download PDF</button>
            <button class="btn ghost" id="printBtn">Print</button>
          </div>
        </div>

        <div style="margin-top:14px;text-align:center" class="qr">
          <img id="qrImg" alt="QR code" src="" />
          <div style="text-align:left;color:var(--muted);font-size:13px">Scan to open<br/><strong id="publicUrl">yourusername.github.io</strong></div>
        </div>
      </div>

      <div class="right">
        <div class="section">
          <h2>Professional Summary</h2>
          <p class="lead">Biomedical Engineering graduate with over 2 years of experience in medical device maintenance and technical support specialising in endoscopic systems. Experienced in calibration, troubleshooting, staff training, and quality assurance to maintain high standards of device performance and patient safety.</p>
          <ul class="skills">
            <li>Endoscopic Maintenance</li>
            <li>Calibration & Troubleshooting</li>
            <li>Imaging Systems</li>
            <li>Technical Training</li>
            <li>Quality Assurance</li>
          </ul>
        </div>

        <div class="section">
          <h2>Experience</h2>
          <ul class="timeline">
            <li>
              <div style="display:flex;justify-content:space-between"><strong>Sales & Service Engineer — Mitra Industries Pvt. Ltd.</strong><span class="meta">08/2022 — Present • Mumbai, India</span></div>
              <div class="meta">• Maintenance & calibration of endoscopic systems • Technical support & training • Quality assurance & compliance</div>
            </li>
            <li>
              <div style="display:flex;justify-content:space-between"><strong>Biomedical Intern — SL Raheja Fortis Hospital</strong><span class="meta">01/2022 — 04/2022 • Mumbai, India</span></div>
              <div class="meta">• Assisted with equipment maintenance • Troubleshooting & inventory support</div>
            </li>
          </ul>
        </div>

        <div class="section">
          <h2>Education</h2>
          <div class="card-mini">
            <strong>B.E. — Biomedical Engineering</strong><br/>Vidyalankar Institute of Technology, Mumbai (2019 — 2022)
          </div>
          <div style="height:8px"></div>
          <div class="card-mini">
            <strong>Diploma — Medical Electronics</strong><br/>VPM's Polytechnic, Mumbai (2017 — 2019)
          </div>
        </div>

        <div class="section">
          <h2>Projects & Achievements</h2>
          <div class="grid">
            <div class="card-mini"><strong>Endoscope Calibration Workflow</strong><div class="meta">Developed SOP for optical calibration & imaging validation.</div></div>
            <div class="card-mini"><strong>Training Program</strong><div class="meta">Conducted hands-on training for hospital staff on device handling.</div></div>
            <div class="card-mini"><strong>Quality Initiative</strong><div class="meta">Participated in corrective action planning to reduce device downtime.</div></div>
            <div class="card-mini"><strong>Internship Recognition</strong><div class="meta">Acknowledged for proactive troubleshooting at SL Raheja Fortis.</div></div>
          </div>
        </div>

        <div class="section">
          <h2>Certificates</h2>
          <div class="grid">
            <div class="card-mini">Diploma: Medical Electronics</div>
            <div class="card-mini">B.E. Biomedical Engineering</div>
          </div>
        </div>

        <div class="section">
          <h2>Languages</h2>
          <p class="meta">English • Hindi • Arabic</p>
        </div>

        <div class="section">
          <h2>Contact / Message</h2>
          <!-- Form uses Formspree placeholder; replace ACTION with your Formspree endpoint or use mailto fallback -->
          <form id="contactForm" action="https://formspree.io/f/your-id" method="POST">
            <div style="display:flex;gap:8px;flex-wrap:wrap">
              <input name="name" placeholder="Your name" required style="flex:1;padding:10px;border-radius:8px;border:1px solid rgba(255,255,255,0.04);background:transparent;color:var(--text)">
              <input name="email" type="email" placeholder="Your email" required style="flex:1;padding:10px;border-radius:8px;border:1px solid rgba(255,255,255,0.04);background:transparent;color:var(--text)">
            </div>
            <textarea name="message" placeholder="Message" required style="width:100%;margin-top:8px;padding:10px;border-radius:8px;border:1px solid rgba(255,255,255,0.04);background:transparent;color:var(--text)"></textarea>
            <div style="margin-top:8px;display:flex;gap:8px">
              <button class="btn" type="submit">Send Message</button>
              <button class="btn ghost" type="button" id="mailtoFallback">Email Me</button>
            </div>
          </form>
        </div>

      </div>
    </div>
  </div>

  <script>
    // --- Utilities ---
    const usernamePlaceholder = 'yourusername.github.io';
    document.getElementById('publicUrl').textContent = usernamePlaceholder;

    // Theme toggle (simple light mode)
    const themeToggle = document.getElementById('themeToggle');
    themeToggle.addEventListener('click', ()=>{
      if(document.documentElement.style.getPropertyValue('--bg') === ''){
        // already default
      }
      // quick light toggle by swapping CSS vars
      const isLight = document.documentElement.style.getPropertyValue('--bg') === '#ffffff';
      if(!isLight){
        document.documentElement.style.setProperty('--bg','#ffffff');
        document.documentElement.style.setProperty('--card','#f8fafc');
        document.documentElement.style.setProperty('--muted','#475569');
        document.documentElement.style.setProperty('--accent','#0ea5a3');
        document.documentElement.style.setProperty('--glass','rgba(0,0,0,0.04)');
        document.documentElement.style.setProperty('--text','#082032');
        document.body.style.background = 'linear-gradient(180deg,#ffffff 0%, #f3f4f6 100%)';
      } else {
        document.documentElement.style.setProperty('--bg','#0f1724');
        document.documentElement.style.setProperty('--card','#0b1220');
        document.documentElement.style.setProperty('--muted','#94a3b8');
        document.documentElement.style.setProperty('--accent','#06b6d4');
        document.documentElement.style.setProperty('--glass','rgba(255,255,255,0.04)');
        document.documentElement.style.setProperty('--text','#e6eef8');
        document.body.style.background = 'linear-gradient(180deg,#071025 0%, #041021 100%)';
      }
    });

    // WhatsApp button behavior (opens chat)
    document.getElementById('whatsappBtn').addEventListener('click', ()=>{
      const phone = '+971583027876';
      const text = encodeURIComponent('Hello Khwaja, I saw your CV and would like to get in touch.');
      window.open(`https://wa.me/${phone.replace(/[^\\d]/g,'')}?text=${text}`,'_blank');
    });

    // LinkedIn button (placeholder)
    document.getElementById('linkedinBtn').addEventListener('click', ()=>{
      const url = prompt('Paste your LinkedIn profile URL (full):','https://www.linkedin.com/in/');
      if(url) window.open(url,'_blank');
    });

    // Print & Download PDF
    document.getElementById('printBtn').addEventListener('click', ()=>window.print());
    document.getElementById('downloadPdf').addEventListener('click', ()=>window.print());

    // Mailto fallback for contact form
    document.getElementById('mailtoFallback').addEventListener('click', ()=>{
      const name = document.querySelector('[name="name"]').value || 'New contact';
      const email = document.querySelector('[name="email"]').value || '';
      const message = document.querySelector('[name="message"]').value || '';
      const subject = encodeURIComponent('Contact from CV — ' + name);
      const body = encodeURIComponent('From: '+name+" (%22+email+" )\n\n"+message);
      window.location.href = `mailto:Khwaja.owesh@gmail.com?subject=${subject}&body=${body}`;
    });

    // QR code generation (using chart.googleapis.com)
    const publicUrl = 'https://' + usernamePlaceholder;
    const qrSrc = 'https://chart.googleapis.com/chart?cht=qr&chs=200x200&chl=' + encodeURIComponent(publicUrl);
    document.getElementById('qrImg').src = qrSrc;

    // If profile.jpg isn't provided, optionally embed base64 if available (we keep src=profile.jpg)

    // Form: graceful message on submit (if using Formspree replace action with your endpoint)
    document.getElementById('contactForm').addEventListener('submit', (e)=>{
      // Allow default submit only if user replaced action
      const form = e.target;
      if(form.action.includes('formspree.io') && form.action.includes('your-id')){
        e.preventDefault();
        alert('Replace the form ACTION with your Formspree endpoint or the form will not submit. Alternatively use the Email button.');
      } else {
        // let it submit (Formspree or other will handle)
      }
    });

    // small accessibility: focus outline
    document.addEventListener('keydown',(e)=>{if(e.key==='Tab')document.body.classList.add('show-focus')})
  </script>
</body>
</html>
