
<style>
*{box-sizing:border-box;margin:0;padding:0}
body{background:transparent}
.htf-root{background:#020817;color:#fff;font-family:var(--font-sans);min-height:100vh}
.htf-root a{color:inherit;text-decoration:none}
.btn-blue{background:#3b82f6;color:#fff;border:none;border-radius:12px;padding:10px 20px;font-weight:700;font-size:14px;cursor:pointer;display:inline-flex;align-items:center;gap:6px}
.btn-blue:hover{background:#60a5fa}
.btn-outline{background:rgba(255,255,255,0.05);color:#fff;border:1px solid rgba(255,255,255,0.2);border-radius:12px;padding:10px 20px;font-weight:700;font-size:14px;cursor:pointer}
.btn-outline:hover{background:rgba(255,255,255,0.1)}
header{position:sticky;top:0;z-index:50;border-bottom:1px solid rgba(255,255,255,0.1);background:rgba(2,8,23,0.9);backdrop-filter:blur(8px)}
.header-inner{max-width:1120px;margin:0 auto;display:flex;align-items:center;justify-content:space-between;padding:14px 24px}
.logo{font-size:18px;font-weight:900;letter-spacing:-0.5px}.logo span{color:#60a5fa}
nav{display:flex;gap:28px;font-size:14px;color:#cbd5e1}
nav a:hover{color:#fff}
.hero{padding:80px 24px;position:relative;overflow:hidden}
.hero-bg{position:absolute;inset:0;background:radial-gradient(circle at 80% 20%,rgba(59,130,246,0.2),transparent 40%),radial-gradient(circle at 10% 80%,rgba(14,165,233,0.12),transparent 35%);pointer-events:none}
.hero-inner{max-width:1120px;margin:0 auto;display:grid;grid-template-columns:1fr 1fr;gap:48px;align-items:center;position:relative}
.hero-badge{display:inline-block;border:1px solid rgba(96,165,250,0.3);background:rgba(96,165,250,0.1);border-radius:999px;padding:6px 16px;font-size:13px;color:#bfdbfe;margin-bottom:20px}
.hero-h1{font-size:clamp(36px,5vw,60px);font-weight:900;line-height:1.1;letter-spacing:-1px}
.hero-p{margin-top:20px;font-size:16px;line-height:1.7;color:#cbd5e1;max-width:500px}
.hero-btns{display:flex;flex-wrap:wrap;gap:12px;margin-top:28px}
.hero-card{border:1px solid rgba(255,255,255,0.1);background:rgba(255,255,255,0.04);border-radius:28px;padding:24px;box-shadow:0 20px 60px rgba(0,0,0,0.4)}
.hero-card-inner{background:#0f172a;border-radius:20px;padding:24px}
.hero-card-header{display:flex;justify-content:space-between;align-items:flex-start;margin-bottom:20px}
.hero-card-header p{font-size:13px;color:#94a3b8}
.hero-card-header h3{font-size:20px;font-weight:700}
.metric-row{display:flex;align-items:flex-start;gap:10px;background:rgba(30,41,59,0.7);border:1px solid rgba(255,255,255,0.08);border-radius:14px;padding:14px;margin-bottom:10px}
.metric-row:last-child{margin-bottom:0}
.metric-check{color:#60a5fa;font-size:18px;margin-top:1px;flex-shrink:0}
.metric-title{font-weight:600;font-size:14px}
.metric-sub{font-size:12px;color:#94a3b8;margin-top:2px}
.section{padding:72px 24px}
.section-inner{max-width:1120px;margin:0 auto}
.section-center{text-align:center;max-width:700px;margin:0 auto 40px}
.s-h2{font-size:clamp(28px,4vw,44px);font-weight:900;letter-spacing:-0.5px;line-height:1.15}
.s-p{margin-top:16px;font-size:16px;line-height:1.7;color:#cbd5e1}
.grid3{display:grid;grid-template-columns:repeat(3,1fr);gap:20px;margin-top:40px}
.grid2{display:grid;grid-template-columns:repeat(2,1fr);gap:20px;margin-top:40px}
.grid4{display:grid;grid-template-columns:repeat(4,1fr);gap:20px;margin-top:40px}
.card{border:1px solid rgba(255,255,255,0.1);border-radius:24px;padding:28px}
.card-dark{background:#020817}
.card-mid{background:rgba(255,255,255,0.04)}
.card-icon{width:44px;height:44px;border-radius:12px;background:rgba(59,130,246,0.12);display:flex;align-items:center;justify-content:center;margin-bottom:18px;font-size:20px;color:#60a5fa}
.card h3{font-size:20px;font-weight:700}
.card p{margin-top:10px;font-size:14px;line-height:1.7;color:#94a3b8}
.bg-alt{background:rgba(15,23,42,0.7)}
.step-num{font-size:12px;font-weight:900;color:#60a5fa;letter-spacing:1px}
.about-grid{display:grid;grid-template-columns:0.9fr 1.1fr;gap:40px;align-items:center;max-width:1120px;margin:0 auto}
.about-left{border:1px solid rgba(255,255,255,0.1);background:#020817;border-radius:28px;padding:32px}
.htf-logo{width:72px;height:72px;border-radius:20px;background:#3b82f6;display:flex;align-items:center;justify-content:center;font-size:20px;font-weight:900}
.about-left h3{margin-top:28px;font-size:26px;font-weight:900}
.about-left p{margin-top:12px;font-size:14px;line-height:1.7;color:#94a3b8}
.stats{display:grid;grid-template-columns:repeat(3,1fr);gap:14px;margin-top:28px}
.stat{border:1px solid rgba(255,255,255,0.1);background:rgba(255,255,255,0.04);border-radius:14px;padding:18px}
.stat-num{font-size:28px;font-weight:900;color:#60a5fa}
.stat-lbl{margin-top:6px;font-size:12px;color:#94a3b8}
.cta{border:1px solid rgba(96,165,250,0.2);background:rgba(59,130,246,0.08);border-radius:28px;padding:56px 40px;text-align:center;max-width:860px;margin:0 auto}
.cta-icon{font-size:40px;color:#60a5fa;margin-bottom:20px}
footer{border-top:1px solid rgba(255,255,255,0.1);padding:28px 24px}
.footer-inner{max-width:1120px;margin:0 auto;display:flex;justify-content:space-between;font-size:13px;color:#64748b;flex-wrap:wrap;gap:12px}
@media(max-width:700px){
  nav{display:none}
  .hero-inner,.grid3,.grid2,.grid4,.about-grid,.stats{grid-template-columns:1fr}
}
</style>

<h2 class="sr-only">High Ticket Force — high-ticket sales consultancy website</h2>

<div class="htf-root">
  <header>
    <div class="header-inner">
      <div class="logo">High Ticket <span>Force</span></div>
      <nav>
        <a href="#services">Services</a>
        <a href="#process">Process</a>
        <a href="#about">About</a>
        <a href="#contact">Book a Call</a>
      </nav>
      <button class="btn-blue">Book a Call</button>
    </div>
  </header>

  <main>
    <!-- Hero -->
    <section class="hero">
      <div class="hero-bg"></div>
      <div class="hero-inner">
        <div>
          <div class="hero-badge">High-ticket sales consultancy for online businesses</div>
          <h1 class="hero-h1">Build a sales team that actually converts.</h1>
          <p class="hero-p">High Ticket Force helps coaches, influencers, consultants and online education brands recruit, train and manage high-ticket closers and appointment setters so they can scale with structure, confidence and consistency.</p>
          <div class="hero-btns">
            <button class="btn-blue" style="padding:14px 24px;font-size:15px">Book a Free Strategy Call <i class="ti ti-arrow-right" aria-hidden="true"></i></button>
            <button class="btn-outline" style="padding:14px 24px;font-size:15px">See How It Works</button>
          </div>
        </div>
        <div class="hero-card">
          <div class="hero-card-inner">
            <div class="hero-card-header">
              <div>
                <p>Sales Engine</p>
                <h3>Growth Dashboard</h3>
              </div>
              <i class="ti ti-chart-bar" style="font-size:28px;color:#60a5fa" aria-hidden="true"></i>
            </div>
            <div class="metric-row"><span class="metric-check"><i class="ti ti-circle-check" aria-hidden="true"></i></span><div><div class="metric-title">Setter show-up rate</div><div class="metric-sub">Improved follow-up &amp; qualification</div></div></div>
            <div class="metric-row"><span class="metric-check"><i class="ti ti-circle-check" aria-hidden="true"></i></span><div><div class="metric-title">Closer conversion</div><div class="metric-sub">Sharper discovery &amp; objection handling</div></div></div>
            <div class="metric-row"><span class="metric-check"><i class="ti ti-circle-check" aria-hidden="true"></i></span><div><div class="metric-title">Team accountability</div><div class="metric-sub">Scorecards, coaching and reviews</div></div></div>
            <div class="metric-row"><span class="metric-check"><i class="ti ti-circle-check" aria-hidden="true"></i></span><div><div class="metric-title">Founder time</div><div class="metric-sub">Less dependency on owner-led sales</div></div></div>
          </div>
        </div>
      </div>
    </section>

    <!-- Problem -->
    <section class="section">
      <div class="section-inner">
        <div class="section-center">
          <h2 class="s-h2">Your offer is not the problem. Your sales system might be.</h2>
          <p class="s-p">If your leads are inconsistent, your closers lack structure, or you are still handling every sales call yourself, you do not need more chaos. You need a sales engine.</p>
        </div>
        <div class="grid3">
          <div class="card card-mid">
            <div class="card-icon"><i class="ti ti-target" aria-hidden="true"></i></div>
            <h3>Weak qualification</h3>
            <p>Setters book calls, but the wrong people end up on the calendar.</p>
          </div>
          <div class="card card-mid">
            <div class="card-icon"><i class="ti ti-phone" aria-hidden="true"></i></div>
            <h3>Inconsistent closing</h3>
            <p>Closers sound good, but lack a repeatable process that drives decisions.</p>
          </div>
          <div class="card card-mid">
            <div class="card-icon"><i class="ti ti-users" aria-hidden="true"></i></div>
            <h3>No team rhythm</h3>
            <p>No scorecards, no call reviews, no accountability and no clear coaching structure.</p>
          </div>
        </div>
      </div>
    </section>

    <!-- Services -->
    <section id="services" class="section bg-alt">
      <div class="section-inner">
        <div style="max-width:600px">
          <h2 class="s-h2">What we help you build</h2>
          <p class="s-p">From hiring the right people to training the team and managing performance, we help you build the backend sales structure behind your high-ticket offer.</p>
        </div>
        <div class="grid2">
          <div class="card card-dark">
            <div class="card-icon"><i class="ti ti-shield-check" aria-hidden="true"></i></div>
            <h3>Closer &amp; Setter Recruitment</h3>
            <p>Find, screen and filter sales talent that fits your offer, audience and business model.</p>
          </div>
          <div class="card card-dark">
            <div class="card-icon"><i class="ti ti-shield-check" aria-hidden="true"></i></div>
            <h3>Sales Team Training</h3>
            <p>Train your team on discovery, rapport, objection handling, follow-up and closing conversations.</p>
          </div>
          <div class="card card-dark">
            <div class="card-icon"><i class="ti ti-shield-check" aria-hidden="true"></i></div>
            <h3>Sales Process Consulting</h3>
            <p>Build scripts, pipeline stages, CRM habits, follow-up systems and performance expectations.</p>
          </div>
          <div class="card card-dark">
            <div class="card-icon"><i class="ti ti-shield-check" aria-hidden="true"></i></div>
            <h3>Performance Management</h3>
            <p>Create coaching rhythms, scorecards and weekly reviews so the team stays accountable.</p>
          </div>
        </div>
      </div>
    </section>

    <!-- Process -->
    <section id="process" class="section">
      <div class="section-inner">
        <div class="section-center">
          <h2 class="s-h2">The High Ticket Force Method</h2>
          <p class="s-p">A simple, practical system to move from random sales activity to consistent team execution.</p>
        </div>
        <div class="grid4">
          <div class="card card-mid">
            <div class="step-num">01</div>
            <h3 style="margin-top:14px">Audit</h3>
            <p>We review your offer, funnel, team, scripts and current sales process.</p>
          </div>
          <div class="card card-mid">
            <div class="step-num">02</div>
            <h3 style="margin-top:14px">Build</h3>
            <p>We design the sales structure, roles, KPIs, scripts and management rhythm.</p>
          </div>
          <div class="card card-mid">
            <div class="step-num">03</div>
            <h3 style="margin-top:14px">Train</h3>
            <p>We coach your setters and closers to sharpen conversations and conversion.</p>
          </div>
          <div class="card card-mid">
            <div class="step-num">04</div>
            <h3 style="margin-top:14px">Scale</h3>
            <p>We create accountability so performance improves without constant founder chasing.</p>
          </div>
        </div>
      </div>
    </section>

    <!-- About -->
    <section id="about" class="section bg-alt">
      <div class="about-grid">
        <div class="about-left">
          <div class="htf-logo">HTF</div>
          <h3>Built by sales leadership experience, not theory.</h3>
          <p>High Ticket Force is built for business owners who want real sales structure, not motivational fluff.</p>
        </div>
        <div>
          <h2 class="s-h2">Led by Humza Khan</h2>
          <p class="s-p">With 7+ years across sales, leadership, coaching, customer experience, compliance and operations, Humza brings practical frontline and leadership experience to high-ticket sales teams.</p>
          <p class="s-p" style="margin-top:16px">He currently leads a sales team of 25+ direct reports and has experience managing performance, coaching conversations, improving team accountability and building sales habits that can be repeated across a team.</p>
          <div class="stats">
            <div class="stat"><div class="stat-num">7+</div><div class="stat-lbl">Years sales experience</div></div>
            <div class="stat"><div class="stat-num">25+</div><div class="stat-lbl">Team members led</div></div>
            <div class="stat"><div class="stat-num">$7.3M</div><div class="stat-lbl">Business performance exposure</div></div>
          </div>
        </div>
      </div>
    </section>

    <!-- CTA -->
    <section id="contact" class="section">
      <div class="section-inner">
        <div class="cta">
          <div class="cta-icon"><i class="ti ti-trending-up" aria-hidden="true"></i></div>
          <h2 class="s-h2">Ready to build your sales force?</h2>
          <p class="s-p" style="max-width:560px;margin:16px auto 0">Book a free strategy call and we will look at your offer, current sales process and where your team is leaking opportunities.</p>
          <div style="margin-top:28px">
            <button class="btn-blue" style="padding:14px 28px;font-size:15px">Book a Free Strategy Call <i class="ti ti-arrow-right" aria-hidden="true"></i></button>
          </div>
        </div>
      </div>
    </section>
  </main>

  <footer>
    <div class="footer-inner">
      <p>© 2026 High Ticket Force. All rights reserved.</p>
      <p>Recruitment. Training. Sales Systems. Performance.</p>
    </div>
  </footer>
</div>
