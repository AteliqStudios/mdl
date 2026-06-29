<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Malelane Draft League — Season 1</title>
<meta name="description" content="Malelane Draft League — Register, get rated, get drafted.">
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Bebas+Neue&family=DM+Sans:ital,opsz,wght@0,9..40,300;0,9..40,400;0,9..40,500;0,9..40,600;0,9..40,700;1,9..40,400&family=DM+Mono:wght@400;500&display=swap" rel="stylesheet">

<!-- Supabase already configured. Your project: https://xlrzfpxejghlcvldxqmz.supabase.co -->
<script>
  window.SUPABASE_URL      = 'https://xlrzfpxejghlcvldxqmz.supabase.co';
  window.SUPABASE_ANON_KEY = 'eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJzdXBhYmFzZSIsInJlZiI6InhscnpmcHhlamdobGN2bGR4cW16Iiwicm9sZSI6ImFub24iLCJpYXQiOjE3ODEwMjQyODUsImV4cCI6MjA5NjYwMDI4NX0.a3jvigutg4jNP_4wjL2BFQqotdckzeha6jjdI8eVT2c';
</script>
<script src="https://cdn.jsdelivr.net/npm/@supabase/supabase-js@2"></script>

<style>
/* ── RESET ─────────────────────────────────────────────── */
*,*::before,*::after{margin:0;padding:0;box-sizing:border-box;}
html{scroll-behavior:smooth;}
img{max-width:100%;display:block;}
button{font-family:inherit;cursor:pointer;}
input,select,textarea{font-family:inherit;}

/* ── TOKENS ────────────────────────────────────────────── */
:root{
  --green:#1a7a3c;--green-light:#22a050;--green-dark:#0f4f25;--green-glow:rgba(26,122,60,0.25);
  --gold:#c9a84c;--gold-light:#e8c96a;--gold-dim:#8a7333;--gold-glow:rgba(201,168,76,0.2);
  --bg:#080c08;--bg2:#0e120e;--bg3:#141a14;--bg4:#1c231c;
  --border:rgba(255,255,255,0.06);--border-gold:rgba(201,168,76,0.2);
  --txt:#f0f4f0;--txt2:rgba(240,244,240,0.6);--txt3:rgba(240,244,240,0.35);
  --red:#e03c3c;--blue:#3c7de0;--orange:#e08c3c;
  --font-display:'Bebas Neue',sans-serif;
  --font-body:'DM Sans',sans-serif;
  --font-mono:'DM Mono',monospace;
  --radius:6px;--radius-lg:12px;
  --shadow:0 8px 32px rgba(0,0,0,0.5);
  --shadow-gold:0 8px 32px rgba(201,168,76,0.15);
}

/* ── BASE ──────────────────────────────────────────────── */
body{font-family:var(--font-body);background:var(--bg);color:var(--txt);min-height:100vh;overflow-x:hidden;line-height:1.6;}
body::before{content:'';position:fixed;inset:0;pointer-events:none;z-index:0;background-image:url("data:image/svg+xml,%3Csvg viewBox='0 0 256 256' xmlns='http://www.w3.org/2000/svg'%3E%3Cfilter id='n'%3E%3CfeTurbulence type='fractalNoise' baseFrequency='0.9' numOctaves='4' stitchTiles='stitch'/%3E%3C/filter%3E%3Crect width='100%25' height='100%25' filter='url(%23n)' opacity='0.04'/%3E%3C/svg%3E");opacity:0.35;}

/* ── TICKER ────────────────────────────────────────────── */
.ticker-bar{position:fixed;top:0;left:0;right:0;z-index:200;height:30px;background:var(--gold);overflow:hidden;display:flex;align-items:center;}
.ticker-track{display:flex;align-items:center;white-space:nowrap;animation:ticker 36s linear infinite;}
.ticker-item{font-family:var(--font-mono);font-size:0.58rem;font-weight:600;letter-spacing:0.14em;text-transform:uppercase;color:var(--bg);padding:0 1.5rem;}
.ticker-sep{color:rgba(0,0,0,0.25);font-weight:700;font-size:0.7rem;}
@keyframes ticker{from{transform:translateX(0);}to{transform:translateX(-50%);}}

/* ── NAV ───────────────────────────────────────────────── */
nav{position:fixed;top:30px;left:0;right:0;z-index:199;height:60px;display:flex;align-items:center;justify-content:space-between;padding:0 2rem;background:rgba(8,12,8,0.9);backdrop-filter:blur(16px);border-bottom:1px solid var(--border-gold);}
.nav-logo{font-family:var(--font-display);font-size:1.35rem;letter-spacing:0.12em;cursor:pointer;background:linear-gradient(90deg,var(--gold),var(--gold-light),#fff8d0,var(--gold-light),var(--gold));background-size:200% auto;-webkit-background-clip:text;-webkit-text-fill-color:transparent;background-clip:text;animation:shimmer 3s linear infinite;}
@keyframes shimmer{to{background-position:200% center;}}
.nav-links{display:flex;gap:0.15rem;list-style:none;}
.nav-links a{font-family:var(--font-mono);font-size:0.65rem;letter-spacing:0.1em;text-transform:uppercase;color:var(--txt3);text-decoration:none;padding:0.4rem 0.7rem;border-radius:4px;transition:all 0.2s;border:none;background:none;cursor:pointer;}
.nav-links a:hover,.nav-links a.active{color:var(--gold);background:var(--gold-glow);}
.hamburger{display:none;flex-direction:column;gap:5px;cursor:pointer;padding:4px;}
.hamburger span{display:block;width:22px;height:2px;background:var(--txt);border-radius:2px;transition:all 0.3s;}

/* ── PAGES ─────────────────────────────────────────────── */
.page{display:none;padding-top:90px;min-height:100vh;}
.page.active{display:block;animation:pageIn 0.3s ease both;}
@keyframes pageIn{from{opacity:0;transform:translateY(8px);}to{opacity:1;transform:translateY(0);}}

/* ── HERO ──────────────────────────────────────────────── */
.hero{position:relative;min-height:calc(100vh - 90px);display:flex;flex-direction:column;align-items:center;justify-content:center;text-align:center;padding:4rem 2rem;overflow:hidden;}
.hero-bg{position:absolute;inset:0;background:radial-gradient(ellipse 60% 50% at 50% 10%,rgba(26,122,60,0.2) 0%,transparent 65%),radial-gradient(ellipse 40% 30% at 85% 80%,rgba(201,168,76,0.1) 0%,transparent 60%),radial-gradient(ellipse 30% 25% at 10% 70%,rgba(26,122,60,0.08) 0%,transparent 55%),linear-gradient(180deg,#060a06 0%,#0e120e 100%);}
.pitch-lines{position:absolute;inset:0;opacity:0.045;background-image:repeating-linear-gradient(90deg,rgba(255,255,255,0.8) 0,rgba(255,255,255,0.8) 1px,transparent 1px,transparent 80px),repeating-linear-gradient(0deg,rgba(255,255,255,0.8) 0,rgba(255,255,255,0.8) 1px,transparent 1px,transparent 80px);}
.pitch-circle{position:absolute;left:50%;top:50%;transform:translate(-50%,-50%);width:280px;height:280px;border-radius:50%;border:1px solid rgba(255,255,255,0.06);pointer-events:none;}
.pitch-dot{position:absolute;left:50%;top:50%;transform:translate(-50%,-50%);width:6px;height:6px;border-radius:50%;background:rgba(255,255,255,0.08);pointer-events:none;}
.hero-content{position:relative;z-index:2;}
.hero-badge{display:inline-flex;align-items:center;gap:0.5rem;font-family:var(--font-mono);font-size:0.62rem;letter-spacing:0.2em;text-transform:uppercase;color:var(--gold);border:1px solid var(--border-gold);padding:0.4rem 1.2rem;border-radius:2px;margin-bottom:2rem;background:rgba(201,168,76,0.05);backdrop-filter:blur(4px);animation:fadeUp 0.8s ease both;}
.badge-dot{width:6px;height:6px;border-radius:50%;background:var(--green-light);flex-shrink:0;animation:pulseDot 2s ease infinite;}
@keyframes pulseDot{0%,100%{box-shadow:0 0 0 0 rgba(34,160,80,0.5);}50%{box-shadow:0 0 0 5px rgba(34,160,80,0);}}
.hero-title{font-family:var(--font-display);font-size:clamp(3.5rem,11vw,9rem);line-height:0.9;letter-spacing:0.02em;animation:fadeUp 0.8s 0.1s ease both;}
.hero-title .outline{-webkit-text-stroke:1px rgba(255,255,255,0.25);color:transparent;display:block;}
.hero-title .accent{color:var(--gold);display:block;}
.hero-sub{font-size:1rem;color:var(--txt2);margin-top:1.5rem;letter-spacing:0.04em;animation:fadeUp 0.8s 0.2s ease both;}
.hero-cta{display:flex;gap:1rem;justify-content:center;margin-top:2.5rem;flex-wrap:wrap;animation:fadeUp 0.8s 0.3s ease both;}
.hero-stats{display:flex;justify-content:center;margin-top:4rem;animation:fadeUp 0.8s 0.4s ease both;border:1px solid var(--border);border-radius:var(--radius);background:rgba(255,255,255,0.02);backdrop-filter:blur(6px);overflow:hidden;flex-wrap:wrap;}
.hstat{text-align:center;padding:1.25rem 2rem;border-right:1px solid var(--border);flex:1;min-width:90px;}
.hstat:last-child{border-right:none;}
.hstat-num{font-family:var(--font-display);font-size:2.25rem;color:var(--gold);line-height:1;}
.hstat-label{font-family:var(--font-mono);font-size:0.55rem;letter-spacing:0.14em;text-transform:uppercase;color:var(--txt3);margin-top:0.2rem;}
.scroll-cue{position:absolute;bottom:2rem;left:50%;transform:translateX(-50%);display:flex;flex-direction:column;align-items:center;gap:0.4rem;opacity:0.3;animation:fadeUp 1s 1s ease both;}
.scroll-line{width:1px;height:36px;background:linear-gradient(to bottom,transparent,var(--gold));animation:scrollAnim 2s ease infinite;}
.scroll-txt{font-family:var(--font-mono);font-size:0.5rem;letter-spacing:0.2em;text-transform:uppercase;color:var(--gold);}
@keyframes scrollAnim{0%{transform:scaleY(0);transform-origin:top;}50%{transform:scaleY(1);transform-origin:top;}51%{transform:scaleY(1);transform-origin:bottom;}100%{transform:scaleY(0);transform-origin:bottom;}}
@keyframes fadeUp{from{opacity:0;transform:translateY(20px);}to{opacity:1;transform:translateY(0);}}

/* ── CONTACT STRIP ─────────────────────────────────────── */
.contact-strip{background:var(--bg2);border-top:1px solid var(--border);border-bottom:1px solid var(--border);padding:1rem 2rem;text-align:center;display:flex;align-items:center;justify-content:center;gap:2rem;flex-wrap:wrap;}
.contact-strip-item{display:flex;align-items:center;gap:0.5rem;font-family:var(--font-mono);font-size:0.65rem;letter-spacing:0.08em;color:var(--txt2);text-decoration:none;transition:color 0.2s;}
.contact-strip-item:hover{color:var(--gold);}
.ci-icon{font-size:0.9rem;}
.contact-org-label{font-family:var(--font-mono);font-size:0.6rem;letter-spacing:0.14em;text-transform:uppercase;color:var(--txt3);}

/* ── BUTTONS ───────────────────────────────────────────── */
.btn-primary{font-family:var(--font-mono);font-size:0.72rem;letter-spacing:0.12em;text-transform:uppercase;background:var(--gold);color:var(--bg);border:none;padding:0.85rem 2rem;border-radius:3px;cursor:pointer;font-weight:600;transition:all 0.2s cubic-bezier(0.16,1,0.3,1);}
.btn-primary:hover{background:var(--gold-light);transform:translateY(-2px);box-shadow:var(--shadow-gold);}
.btn-secondary{font-family:var(--font-mono);font-size:0.72rem;letter-spacing:0.12em;text-transform:uppercase;background:transparent;color:var(--txt);border:1px solid var(--border);padding:0.85rem 2rem;border-radius:3px;cursor:pointer;transition:all 0.2s;}
.btn-secondary:hover{border-color:var(--gold);color:var(--gold);transform:translateY(-2px);}
.btn-sm{font-family:var(--font-mono);font-size:0.6rem;letter-spacing:0.08em;text-transform:uppercase;background:var(--gold-glow);color:var(--gold);border:1px solid var(--border-gold);padding:0.35rem 0.8rem;border-radius:3px;cursor:pointer;transition:all 0.2s;white-space:nowrap;}
.btn-sm:hover{background:rgba(201,168,76,0.2);}
.btn-danger{background:rgba(224,60,60,0.1);color:var(--red);border-color:rgba(224,60,60,0.3);}
.btn-danger:hover{background:rgba(224,60,60,0.2);}
.btn-green{background:rgba(26,122,60,0.15);color:#4ecb71;border-color:rgba(26,122,60,0.4);}
.btn-green:hover{background:rgba(26,122,60,0.25);}
.btn-wa{font-family:var(--font-mono);font-size:0.72rem;letter-spacing:0.1em;text-transform:uppercase;background:rgba(37,211,102,0.12);color:#25d366;border:1px solid rgba(37,211,102,0.3);padding:0.85rem 2rem;border-radius:3px;cursor:pointer;transition:all 0.2s;display:inline-flex;align-items:center;gap:0.5rem;}
.btn-wa:hover{background:rgba(37,211,102,0.2);transform:translateY(-2px);}
.btn-full{width:100%;margin-top:0.5rem;}
button:disabled{opacity:0.45;cursor:not-allowed;transform:none !important;}

/* ── SECTION ───────────────────────────────────────────── */
.section{max-width:1200px;margin:0 auto;padding:4rem 2rem;}
.section-header{display:flex;align-items:baseline;gap:1.5rem;margin-bottom:2.5rem;padding-bottom:1.25rem;position:relative;}
.section-header::before{content:'';position:absolute;bottom:0;left:0;right:0;height:1px;background:var(--border);}
.section-header::after{content:'';position:absolute;bottom:0;left:0;width:48px;height:2px;background:var(--gold);border-radius:1px;}
.section-title{font-family:var(--font-display);font-size:2.4rem;letter-spacing:0.05em;}
.section-count{font-family:var(--font-mono);font-size:0.68rem;color:var(--gold);letter-spacing:0.1em;}

/* ── FORMS ─────────────────────────────────────────────── */
.form-group{margin-bottom:1.25rem;}
label{display:block;font-family:var(--font-mono);font-size:0.62rem;letter-spacing:0.12em;text-transform:uppercase;color:var(--txt2);margin-bottom:0.5rem;}
input[type=text],input[type=tel],input[type=password],input[type=number],input[type=url],select,textarea{width:100%;background:var(--bg3);border:1px solid var(--border);border-radius:var(--radius);color:var(--txt);padding:0.75rem 1rem;font-family:var(--font-body);font-size:0.9rem;outline:none;transition:border-color 0.2s,box-shadow 0.2s;appearance:none;}
input:focus,select:focus,textarea:focus{border-color:var(--gold);box-shadow:0 0 0 3px var(--gold-glow);}
select option{background:var(--bg3);color:var(--txt);}
.form-row{display:grid;grid-template-columns:1fr 1fr;gap:1rem;}
.form-note{font-family:var(--font-mono);font-size:0.6rem;letter-spacing:0.08em;color:var(--txt3);margin-top:0.75rem;text-align:center;}
.form-note.warn{color:rgba(224,140,60,0.8);}
.form-divider{height:1px;background:var(--border);margin:2rem 0;}

/* ── PLAYER CARDS ──────────────────────────────────────── */
.players-grid{display:grid;grid-template-columns:repeat(auto-fill,minmax(190px,1fr));gap:1rem;}
.player-card{background:var(--bg3);border:1px solid var(--border);border-radius:var(--radius-lg);overflow:hidden;transition:all 0.25s cubic-bezier(0.16,1,0.3,1);cursor:default;position:relative;}
.player-card:hover{transform:translateY(-4px);box-shadow:var(--shadow);border-color:var(--border-gold);}
.card-strip{height:3px;}
.strip-GK{background:linear-gradient(90deg,#ffa500,#ffcc55);}
.strip-DEF{background:linear-gradient(90deg,#3c7de0,#6fa8f5);}
.strip-MID{background:linear-gradient(90deg,#1a7a3c,#4ecb71);}
.strip-FWD{background:linear-gradient(90deg,#e03c3c,#f57070);}
.strip-pending{background:var(--border);}
.card-top{padding:1.25rem 1.25rem 0.75rem;position:relative;}
.card-pos{position:absolute;top:1rem;right:1rem;font-family:var(--font-mono);font-size:0.58rem;letter-spacing:0.1em;padding:0.2rem 0.5rem;border-radius:2px;}
.pos-GK{background:rgba(255,165,0,0.15);color:#ffa500;border:1px solid rgba(255,165,0,0.3);}
.pos-DEF{background:rgba(60,125,224,0.15);color:#6fa8f5;border:1px solid rgba(60,125,224,0.3);}
.pos-MID{background:rgba(26,122,60,0.2);color:#4ecb71;border:1px solid rgba(26,122,60,0.4);}
.pos-FWD{background:rgba(224,60,60,0.15);color:#f57070;border:1px solid rgba(224,60,60,0.3);}
.card-avatar{width:50px;height:50px;border-radius:50%;background:linear-gradient(135deg,var(--bg4),var(--bg3));border:2px solid var(--border);display:flex;align-items:center;justify-content:center;font-family:var(--font-display);font-size:1.35rem;color:var(--gold);margin-bottom:0.75rem;}
.card-name{font-weight:600;font-size:0.92rem;white-space:nowrap;overflow:hidden;text-overflow:ellipsis;}
.card-price-row{display:flex;align-items:center;justify-content:space-between;margin-top:0.35rem;}
.card-price{font-family:var(--font-display);font-size:1.5rem;color:var(--gold);line-height:1;}
.card-price-cr{font-family:var(--font-mono);font-size:0.6rem;color:rgba(201,168,76,0.5);}
.card-price-pending{font-family:var(--font-mono);font-size:0.58rem;color:var(--txt3);letter-spacing:0.08em;}
.tier-badge{display:inline-flex;align-items:center;gap:0.25rem;font-family:var(--font-mono);font-size:0.55rem;letter-spacing:0.1em;text-transform:uppercase;padding:0.15rem 0.45rem;border-radius:2px;margin-top:0.3rem;}
.tier-elite{background:rgba(201,168,76,0.15);color:var(--gold);border:1px solid rgba(201,168,76,0.35);}
.tier-solid{background:rgba(60,125,224,0.12);color:#6fa8f5;border:1px solid rgba(60,125,224,0.3);}
.tier-budget{background:rgba(255,255,255,0.05);color:var(--txt3);border:1px solid var(--border);}
.card-divider{height:1px;background:var(--border);margin:0 1.25rem;}
.card-pending-body{padding:1rem 1.25rem 1.25rem;text-align:center;}
.pending-label{font-family:var(--font-mono);font-size:0.58rem;letter-spacing:0.12em;text-transform:uppercase;color:var(--txt3);background:rgba(255,255,255,0.03);padding:0.5rem;border-radius:4px;border:1px dashed var(--border);}
.card-sold-tag{position:absolute;top:0;left:0;right:0;z-index:2;background:rgba(26,122,60,0.88);backdrop-filter:blur(4px);text-align:center;padding:0.25rem;font-family:var(--font-mono);font-size:0.55rem;letter-spacing:0.12em;text-transform:uppercase;color:#fff;}

/* ── FILTER BAR ────────────────────────────────────────── */
.filter-bar{display:flex;gap:0.4rem;margin-bottom:2rem;flex-wrap:wrap;}
.filter-btn{font-family:var(--font-mono);font-size:0.6rem;letter-spacing:0.1em;text-transform:uppercase;padding:0.38rem 0.85rem;border-radius:3px;border:1px solid var(--border);background:transparent;color:var(--txt3);cursor:pointer;transition:all 0.2s;}
.filter-btn.active,.filter-btn:hover{border-color:var(--gold);color:var(--gold);background:var(--gold-glow);}

/* ── AUCTION / TIERS ───────────────────────────────────── */
.tier-section{margin-bottom:3rem;}
.tier-header{display:flex;align-items:center;gap:1rem;padding:1rem 1.25rem;border-radius:var(--radius);cursor:pointer;user-select:none;border:1px solid var(--border);background:var(--bg2);transition:all 0.2s;margin-bottom:1rem;}
.tier-header:hover{border-color:var(--border-gold);}
.tier-header-left{display:flex;align-items:center;gap:1rem;flex:1;}
.tier-crown{font-size:1.4rem;}
.tier-name{font-family:var(--font-display);font-size:1.5rem;letter-spacing:0.05em;}
.tier-sub{font-family:var(--font-mono);font-size:0.6rem;letter-spacing:0.1em;color:var(--txt3);margin-top:0.1rem;}
.tier-count-badge{font-family:var(--font-mono);font-size:0.6rem;letter-spacing:0.1em;padding:0.25rem 0.65rem;border-radius:2px;}
.tier-chevron{font-size:1rem;color:var(--txt3);transition:transform 0.3s;margin-left:auto;}
.tier-header.open .tier-chevron{transform:rotate(180deg);}
.tier-body{display:none;}
.tier-body.open{display:block;animation:fadeUp 0.25s ease both;}
.tier-elite-hdr{border-color:rgba(201,168,76,0.25);background:linear-gradient(90deg,rgba(201,168,76,0.06),var(--bg2));}
.tier-solid-hdr{border-color:rgba(60,125,224,0.2);background:linear-gradient(90deg,rgba(60,125,224,0.06),var(--bg2));}
.tier-elite-hdr .tier-name{color:var(--gold);}
.tier-solid-hdr .tier-name{color:#6fa8f5;}
.tier-elite-badge{background:rgba(201,168,76,0.15);color:var(--gold);border:1px solid rgba(201,168,76,0.3);}
.tier-solid-badge{background:rgba(60,125,224,0.12);color:#6fa8f5;border:1px solid rgba(60,125,224,0.3);}
.tier-budget-badge{background:rgba(255,255,255,0.05);color:var(--txt2);border:1px solid var(--border);}

/* ── CAPTAIN CARDS ─────────────────────────────────────── */
.captains-grid{display:grid;grid-template-columns:repeat(auto-fill,minmax(300px,1fr));gap:1.25rem;margin-bottom:3rem;}
.captain-card{background:var(--bg3);border:1px solid var(--border);border-radius:var(--radius-lg);overflow:hidden;transition:all 0.25s;}
.captain-card:hover{border-color:var(--border-gold);transform:translateY(-2px);box-shadow:var(--shadow);}
.cap-strip{height:4px;background:linear-gradient(90deg,var(--green-dark),var(--green),var(--gold));}
.cap-inner{padding:1.5rem;}
.cap-header{display:flex;align-items:center;gap:1rem;margin-bottom:1.25rem;}
.cap-avatar{width:44px;height:44px;border-radius:50%;flex-shrink:0;display:flex;align-items:center;justify-content:center;font-family:var(--font-display);font-size:1.15rem;color:var(--gold);}
.cap-name{font-weight:600;font-size:1rem;}
.cap-team{font-family:var(--font-mono);font-size:0.58rem;letter-spacing:0.1em;color:var(--txt3);margin-top:0.1rem;}
.budget-lbl{display:flex;justify-content:space-between;margin-bottom:0.4rem;}
.budget-lbl span{font-family:var(--font-mono);font-size:0.58rem;letter-spacing:0.08em;color:var(--txt3);}
.budget-lbl .brem{color:var(--gold);}
.budget-bar{height:4px;background:rgba(255,255,255,0.07);border-radius:2px;overflow:hidden;}
.budget-fill{height:100%;background:linear-gradient(90deg,var(--green),var(--gold));border-radius:2px;transition:width 0.5s ease;}
.budget-fill.warn{background:linear-gradient(90deg,#e08c3c,#ffcc55);}
.budget-fill.danger{background:linear-gradient(90deg,var(--red),#f57070);}
.squad-meta{font-family:var(--font-mono);font-size:0.58rem;color:var(--txt3);margin-top:0.5rem;letter-spacing:0.07em;}

/* ── SQUAD NEEDS ───────────────────────────────────────── */
.squad-needs{display:flex;gap:0.35rem;flex-wrap:wrap;margin-top:0.75rem;}
.need-badge{font-family:var(--font-mono);font-size:0.52rem;letter-spacing:0.08em;padding:0.18rem 0.5rem;border-radius:2px;display:flex;align-items:center;gap:0.3rem;}
.need-GK{background:rgba(255,165,0,0.1);color:#ffa500;border:1px solid rgba(255,165,0,0.25);}
.need-DEF{background:rgba(60,125,224,0.1);color:#6fa8f5;border:1px solid rgba(60,125,224,0.25);}
.need-MID{background:rgba(26,122,60,0.12);color:#4ecb71;border:1px solid rgba(26,122,60,0.3);}
.need-FWD{background:rgba(224,60,60,0.1);color:#f57070;border:1px solid rgba(224,60,60,0.25);}

/* ── PITCH VIEW ────────────────────────────────────────── */
.pitch-view{background:linear-gradient(180deg,rgba(26,122,60,0.12) 0%,rgba(15,79,37,0.08) 100%);border:1px solid rgba(26,122,60,0.2);border-radius:var(--radius-lg);padding:1.5rem 1rem 1rem;margin-top:1rem;position:relative;overflow:hidden;}
.pitch-view::before{content:'';position:absolute;inset:0;opacity:0.04;background-image:repeating-linear-gradient(0deg,rgba(255,255,255,0.8) 0,rgba(255,255,255,0.8) 1px,transparent 1px,transparent 40px),repeating-linear-gradient(90deg,rgba(255,255,255,0.8) 0,rgba(255,255,255,0.8) 1px,transparent 1px,transparent 40px);}
.pitch-title{font-family:var(--font-mono);font-size:0.58rem;letter-spacing:0.12em;text-transform:uppercase;color:var(--txt3);text-align:center;margin-bottom:1rem;}
.pitch-row{display:flex;justify-content:center;gap:0.5rem;margin-bottom:0.75rem;flex-wrap:wrap;}
.pitch-player{display:flex;flex-direction:column;align-items:center;gap:0.25rem;min-width:60px;max-width:70px;}
.pitch-player-circle{width:42px;height:42px;border-radius:50%;display:flex;align-items:center;justify-content:center;font-family:var(--font-display);font-size:0.95rem;border:2px solid rgba(255,255,255,0.15);background:var(--bg3);color:var(--txt);position:relative;}
.pitch-player-name{font-family:var(--font-mono);font-size:0.48rem;letter-spacing:0.06em;text-transform:uppercase;color:var(--txt2);text-align:center;white-space:nowrap;overflow:hidden;text-overflow:ellipsis;width:100%;}
.pitch-empty .pitch-player-circle{border-style:dashed;border-color:rgba(255,255,255,0.08);background:transparent;}
.pitch-subs-row{border-top:1px solid var(--border);margin-top:0.75rem;padding-top:0.75rem;display:flex;justify-content:center;gap:0.5rem;flex-wrap:wrap;}
.pitch-subs-label{font-family:var(--font-mono);font-size:0.52rem;letter-spacing:0.1em;text-transform:uppercase;color:var(--txt3);text-align:center;width:100%;margin-bottom:0.4rem;}

/* ── REGISTER PAGE ─────────────────────────────────────── */
.reg-hero{background:linear-gradient(180deg,rgba(26,122,60,0.07) 0%,transparent 100%);border-bottom:1px solid var(--border);padding:3rem 2rem 2rem;text-align:center;}
.reg-hero-title{font-family:var(--font-display);font-size:clamp(2.5rem,8vw,5rem);letter-spacing:0.05em;line-height:1;}
.reg-hero-sub{color:var(--txt2);font-size:0.85rem;margin-top:0.75rem;}
.reg-wrap{max-width:580px;margin:0 auto;padding:2.5rem 2rem 5rem;}
.self-rating-wrap{margin-bottom:1.25rem;}
.self-rating-track{display:flex;align-items:center;gap:1rem;margin-top:0.5rem;}
.self-rating-track input[type=range]{flex:1;appearance:auto;background:transparent;padding:0;height:auto;border:none;box-shadow:none;}
.self-rating-track input[type=range]:focus{box-shadow:none;border:none;}
.self-rating-val{font-family:var(--font-display);font-size:2rem;color:var(--gold);min-width:32px;text-align:center;line-height:1;}
.self-rating-desc{font-family:var(--font-mono);font-size:0.6rem;letter-spacing:0.08em;color:var(--txt3);margin-top:0.25rem;}
.warn-box{background:rgba(224,140,60,0.08);border:1px solid rgba(224,140,60,0.3);border-radius:var(--radius);padding:0.85rem 1rem;margin-bottom:1.25rem;display:flex;gap:0.75rem;align-items:flex-start;}
.warn-box-icon{font-size:1rem;flex-shrink:0;margin-top:0.05rem;}
.warn-box-txt{font-family:var(--font-mono);font-size:0.62rem;letter-spacing:0.07em;color:rgba(224,140,60,0.9);line-height:1.5;}

/* ── TEAMS PAGE ────────────────────────────────────────── */
.teams-search-wrap{max-width:480px;margin:0 auto 3rem;display:flex;gap:0.75rem;align-items:flex-end;}
.teams-search-wrap .form-group{flex:1;margin-bottom:0;}
.teams-grid{display:grid;grid-template-columns:repeat(auto-fill,minmax(320px,1fr));gap:1.5rem;}
.team-card{background:var(--bg3);border:1px solid var(--border);border-radius:var(--radius-lg);overflow:hidden;transition:all 0.25s;}
.team-card:hover{border-color:var(--border-gold);box-shadow:var(--shadow);}
.team-banner{height:6px;}
.team-banner-inner{height:100%;background:linear-gradient(90deg,var(--green-dark),var(--green),var(--gold));}
.team-info{padding:1.5rem;}
.team-name-row{display:flex;align-items:center;gap:1rem;margin-bottom:1.25rem;}
.team-crest{width:48px;height:48px;border-radius:50%;display:flex;align-items:center;justify-content:center;font-family:var(--font-display);font-size:1.25rem;color:var(--gold);flex-shrink:0;}
.team-fullname{font-family:var(--font-display);font-size:1.5rem;letter-spacing:0.05em;color:var(--txt);}
.team-captain-name{font-family:var(--font-mono);font-size:0.6rem;letter-spacing:0.1em;color:var(--txt3);}
.team-roster{border-top:1px solid var(--border);padding-top:1rem;margin-top:0.5rem;}
.roster-pos-group{margin-bottom:0.75rem;}
.roster-pos-label{font-family:var(--font-mono);font-size:0.55rem;letter-spacing:0.14em;text-transform:uppercase;color:var(--txt3);margin-bottom:0.35rem;}
.roster-player-row{display:flex;align-items:center;justify-content:space-between;padding:0.35rem 0.6rem;border-radius:4px;transition:background 0.15s;margin-bottom:0.2rem;}
.roster-player-row:hover{background:rgba(255,255,255,0.03);}
.roster-player-row.highlight{background:rgba(201,168,76,0.08);border:1px solid rgba(201,168,76,0.2);}
.roster-player-name{font-size:0.85rem;font-weight:500;}
.roster-player-price{font-family:var(--font-mono);font-size:0.58rem;color:var(--gold);}
.roster-player-you{font-family:var(--font-mono);font-size:0.52rem;letter-spacing:0.1em;text-transform:uppercase;color:var(--gold);background:rgba(201,168,76,0.12);padding:0.15rem 0.4rem;border-radius:2px;border:1px solid rgba(201,168,76,0.3);}
.team-empty{text-align:center;padding:2rem;color:var(--txt3);font-family:var(--font-mono);font-size:0.65rem;letter-spacing:0.1em;}
.player-search-result{background:var(--bg2);border:1px solid var(--border-gold);border-radius:var(--radius-lg);padding:1.5rem;margin-bottom:2rem;display:flex;align-items:center;gap:1.25rem;flex-wrap:wrap;}
.psr-avatar{width:56px;height:56px;border-radius:50%;background:linear-gradient(135deg,var(--green-dark),var(--green));display:flex;align-items:center;justify-content:center;font-family:var(--font-display);font-size:1.4rem;color:var(--gold);flex-shrink:0;}
.psr-info{flex:1;}
.psr-name{font-family:var(--font-display);font-size:1.5rem;letter-spacing:0.04em;}
.psr-team{color:var(--gold);font-size:0.9rem;margin-top:0.15rem;}
.psr-pos{font-family:var(--font-mono);font-size:0.6rem;color:var(--txt3);letter-spacing:0.1em;margin-top:0.1rem;}
.psr-not-found{font-family:var(--font-mono);font-size:0.68rem;color:var(--txt3);letter-spacing:0.08em;text-align:center;padding:1.5rem;background:var(--bg2);border:1px dashed var(--border);border-radius:var(--radius);}

/* ── ADMIN ─────────────────────────────────────────────── */
.login-wrap{max-width:360px;margin:0 auto;padding:5rem 2rem;}
.login-title{font-family:var(--font-display);font-size:2.4rem;letter-spacing:0.05em;margin-bottom:0.4rem;}
.login-sub{color:var(--txt3);font-size:0.85rem;margin-bottom:2rem;}
.admin-wrap{max-width:920px;margin:0 auto;padding:3rem 2rem;}
.admin-header{display:flex;align-items:center;justify-content:space-between;margin-bottom:2rem;padding-bottom:1.5rem;border-bottom:1px solid var(--border);}
.admin-title{font-family:var(--font-display);font-size:2rem;letter-spacing:0.05em;}
.admin-badge{font-family:var(--font-mono);font-size:0.58rem;letter-spacing:0.12em;text-transform:uppercase;color:var(--gold);background:var(--gold-glow);border:1px solid var(--border-gold);padding:0.3rem 0.75rem;border-radius:2px;}
.admin-tabs{display:flex;gap:0.15rem;margin-bottom:2rem;border-bottom:1px solid var(--border);flex-wrap:wrap;}
.admin-tab{font-family:var(--font-mono);font-size:0.62rem;letter-spacing:0.1em;text-transform:uppercase;padding:0.6rem 1rem;border:none;background:none;color:var(--txt3);cursor:pointer;border-bottom:2px solid transparent;margin-bottom:-1px;transition:all 0.2s;}
.admin-tab.active{color:var(--gold);border-bottom-color:var(--gold);}
.admin-panel{display:none;}
.admin-panel.active{display:block;}
.admin-row{display:flex;align-items:center;gap:0.75rem;padding:0.9rem 1.1rem;background:var(--bg3);border:1px solid var(--border);border-radius:var(--radius);margin-bottom:0.5rem;transition:border-color 0.2s;position:relative;overflow:hidden;flex-wrap:wrap;}
.admin-row:hover{border-color:rgba(255,255,255,0.1);}
.admin-row::before{content:'';position:absolute;left:0;top:0;bottom:0;width:3px;background:var(--gold);transform:scaleY(0);transition:transform 0.2s;border-radius:0 2px 2px 0;}
.admin-row:hover::before{transform:scaleY(1);}
.arow-name{flex:1;font-weight:500;font-size:0.88rem;min-width:120px;}
.arow-pos{font-family:var(--font-mono);font-size:0.58rem;letter-spacing:0.08em;padding:0.2rem 0.45rem;border-radius:2px;}
.arow-price{font-family:var(--font-display);font-size:1.2rem;color:var(--gold);min-width:55px;text-align:right;}
.arow-price.unrated{font-family:var(--font-mono);font-size:0.58rem;color:var(--txt3);letter-spacing:0.08em;}
.arow-self{font-family:var(--font-mono);font-size:0.58rem;color:var(--txt2);letter-spacing:0.07em;}

/* Pricing guide */
.pricing-guide{display:grid;grid-template-columns:repeat(auto-fill,minmax(200px,1fr));gap:0.75rem;margin-bottom:1.5rem;}
.pg-card{background:var(--bg3);border:1px solid var(--border);border-radius:var(--radius);padding:1rem;}
.pg-pos{font-family:var(--font-display);font-size:1.2rem;letter-spacing:0.06em;margin-bottom:0.5rem;}
.pg-row{display:flex;justify-content:space-between;font-family:var(--font-mono);font-size:0.58rem;letter-spacing:0.07em;color:var(--txt3);margin-bottom:0.2rem;}
.pg-row span:last-child{color:var(--txt2);}

/* ── MODAL ─────────────────────────────────────────────── */
.modal-overlay{display:none;position:fixed;inset:0;background:rgba(0,0,0,0.8);z-index:500;align-items:center;justify-content:center;padding:2rem;backdrop-filter:blur(4px);}
.modal-overlay.open{display:flex;}
.modal-overlay.open .modal{animation:modalIn 0.3s cubic-bezier(0.34,1.56,0.64,1) both;}
@keyframes modalIn{from{opacity:0;transform:scale(0.9) translateY(12px);}to{opacity:1;transform:scale(1) translateY(0);}}
.modal{background:var(--bg2);border:1px solid rgba(255,255,255,0.1);border-radius:var(--radius-lg);padding:2rem;width:100%;max-width:500px;max-height:90vh;overflow-y:auto;}
.modal-title{font-family:var(--font-display);font-size:1.7rem;letter-spacing:0.05em;margin-bottom:0.5rem;color:var(--gold);}
.modal-sub{font-family:var(--font-mono);font-size:0.6rem;letter-spacing:0.1em;color:var(--txt3);margin-bottom:1.5rem;}
.stats-grid{display:grid;grid-template-columns:1fr 1fr;gap:0.75rem;margin-bottom:1.25rem;}
.stat-ig label{font-size:0.6rem;margin-bottom:0.3rem;}
.stat-ig input{padding:0.5rem 0.75rem;font-size:0.85rem;}
.price-preview{background:var(--gold-glow);border:1px solid var(--border-gold);border-radius:var(--radius);padding:1rem;text-align:center;margin-bottom:1rem;}
.pp-label{font-family:var(--font-mono);font-size:0.58rem;letter-spacing:0.12em;text-transform:uppercase;color:var(--txt3);margin-bottom:0.25rem;}
.pp-val{font-family:var(--font-display);font-size:2.4rem;color:var(--gold);line-height:1;}
.pp-range{font-family:var(--font-mono);font-size:0.58rem;color:var(--txt3);margin-top:0.25rem;}
.modal-actions{display:flex;gap:0.75rem;justify-content:flex-end;}

/* ── TOAST ─────────────────────────────────────────────── */
.toast{position:fixed;bottom:2rem;right:2rem;background:var(--bg3);border:1px solid var(--border);border-radius:var(--radius);padding:0.85rem 1.25rem;font-family:var(--font-mono);font-size:0.68rem;letter-spacing:0.07em;color:var(--txt);z-index:9999;transform:translateY(100px);opacity:0;transition:all 0.3s ease;max-width:300px;}
.toast.show{transform:translateY(0);opacity:1;}
.toast.success{border-color:rgba(26,122,60,0.5);color:#4ecb71;}
.toast.error{border-color:rgba(224,60,60,0.5);color:#f57070;}

/* ── LOADING ────────────────────────────────────────────── */
.loading-state{text-align:center;padding:3rem 2rem;color:var(--txt3);}
.loading-spinner{width:28px;height:28px;border:2px solid var(--border);border-top-color:var(--gold);border-radius:50%;animation:spin 0.7s linear infinite;margin:0 auto 1rem;}
@keyframes spin{to{transform:rotate(360deg);}}
.loading-txt{font-family:var(--font-mono);font-size:0.62rem;letter-spacing:0.1em;text-transform:uppercase;}

/* ── SUPABASE CONFIG WARNING ───────────────────────────── */
.config-warning{background:rgba(224,60,60,0.08);border:1px solid rgba(224,60,60,0.3);border-radius:var(--radius-lg);padding:1.25rem 1.5rem;margin:1rem 2rem;display:flex;gap:0.75rem;align-items:flex-start;}
.config-warning-icon{font-size:1.1rem;flex-shrink:0;}
.config-warning-txt{font-family:var(--font-mono);font-size:0.62rem;letter-spacing:0.07em;color:rgba(224,100,100,0.95);line-height:1.6;}
.config-warning-txt code{background:rgba(255,255,255,0.07);padding:0.1rem 0.35rem;border-radius:3px;font-size:0.6rem;}

/* ── EMPTY STATE ───────────────────────────────────────── */
.empty-state{text-align:center;padding:4rem 2rem;color:var(--txt3);}
.empty-icon{font-size:2.5rem;margin-bottom:1rem;opacity:0.3;}
.empty-text{font-family:var(--font-mono);font-size:0.68rem;letter-spacing:0.1em;text-transform:uppercase;}

/* ── RESPONSIVE ────────────────────────────────────────── */
@media(max-width:768px){
  .nav-links{display:none;position:fixed;top:90px;left:0;right:0;background:var(--bg2);padding:1rem;flex-direction:column;border-bottom:1px solid var(--border);gap:0;z-index:198;}
  .nav-links.open{display:flex;}
  .nav-links a{padding:0.75rem 1rem;border-radius:var(--radius);font-size:0.75rem;}
  .hamburger{display:flex;}
  .form-row{grid-template-columns:1fr;}
  .captains-grid{grid-template-columns:1fr;}
  .teams-grid{grid-template-columns:1fr;}
  .stats-grid{grid-template-columns:1fr;}
  .hstat{padding:1rem 1.25rem;}
  .admin-row{gap:0.5rem;}
  .arow-name{width:100%;}
  .modal{padding:1.5rem;}
  .contact-strip{flex-direction:column;gap:0.75rem;}
  .hero-cta{flex-direction:column;align-items:center;}
  .teams-search-wrap{flex-direction:column;}
  .config-warning{margin:1rem;}
}
@media(max-width:480px){
  .section{padding:3rem 1.25rem;}
  .hero{padding:3rem 1.25rem;}
  nav{padding:0 1.25rem;}
}
</style>
</head>
<body>

<!-- TICKER -->
<div class="ticker-bar">
  <div class="ticker-track" id="ticker-track">
    <span class="ticker-item">&#9917; Malelane Draft League</span><span class="ticker-sep">·</span>
    <span class="ticker-item" id="tick-players">— Players Registered</span><span class="ticker-sep">·</span>
    <span class="ticker-item" id="tick-rated">— Rated</span><span class="ticker-sep">·</span>
    <span class="ticker-item" id="tick-caps">— Captains</span><span class="ticker-sep">·</span>
    <span class="ticker-item">100 Credits Per Squad</span><span class="ticker-sep">·</span>
    <span class="ticker-item">8 Players &middot; 6-A-Side</span><span class="ticker-sep">·</span>
    <span class="ticker-item">Season 1 — Register Now</span><span class="ticker-sep">·</span>
    <span class="ticker-item">&#9917; Malelane Draft League</span><span class="ticker-sep">·</span>
    <span class="ticker-item" id="tick-players2">— Players Registered</span><span class="ticker-sep">·</span>
    <span class="ticker-item" id="tick-rated2">— Rated</span><span class="ticker-sep">·</span>
    <span class="ticker-item" id="tick-caps2">— Captains</span><span class="ticker-sep">·</span>
    <span class="ticker-item">100 Credits Per Squad</span><span class="ticker-sep">·</span>
    <span class="ticker-item">8 Players &middot; 6-A-Side</span><span class="ticker-sep">·</span>
    <span class="ticker-item">Season 1 — Register Now</span><span class="ticker-sep">·</span>
  </div>
</div>

<!-- NAV -->
<nav>
  <div class="nav-logo" onclick="navigate('home')">MDL</div>
  <ul class="nav-links" id="nav-links">
    <li><a onclick="navigate('home')" id="nav-home" class="active">Home</a></li>
    <li><a onclick="navigate('players')" id="nav-players">Players</a></li>
    <li><a onclick="navigate('auction')" id="nav-auction">Auction</a></li>
    <li><a onclick="navigate('teams')" id="nav-teams">Teams</a></li>
    <li><a onclick="navigate('register')" id="nav-register">Register</a></li>
    <li><a onclick="navigate('admin')" id="nav-admin">Admin</a></li>
  </ul>
  <div class="hamburger" onclick="toggleMobileNav()" id="hamburger">
    <span></span><span></span><span></span>
  </div>
</nav>

<div class="toast" id="toast"></div>

<!-- ════════════════ HOME PAGE -->
<div class="page active" id="page-home">
  <div class="hero">
    <div class="hero-bg"></div>
    <div class="pitch-lines"></div>
    <div class="pitch-circle"></div>
    <div class="pitch-dot"></div>
    <div class="hero-content">
      <div class="hero-badge"><span class="badge-dot"></span>Malelane &middot; Season 1 &middot; Live</div>
      <h1 class="hero-title">
        <span class="outline">Malelane</span>
        <span class="accent">Draft</span>
        League
      </h1>
      <p class="hero-sub">Register. Get Rated. Get Drafted. Dominate.</p>
      <div class="hero-cta">
        <button type="button" class="btn-primary" onclick="navigate('register')">Register as Player</button>
        <button type="button" class="btn-secondary" onclick="navigate('teams')">Find My Team</button>
        <button type="button" class="btn-secondary" onclick="navigate('players')">View Player Pool</button>
      </div>
      <div class="hero-stats">
        <div class="hstat"><div class="hstat-num" id="stat-players">—</div><div class="hstat-label">Registered</div></div>
        <div class="hstat"><div class="hstat-num" id="stat-rated">—</div><div class="hstat-label">Rated</div></div>
        <div class="hstat"><div class="hstat-num" id="stat-captains">—</div><div class="hstat-label">Captains</div></div>
        <div class="hstat"><div class="hstat-num">100</div><div class="hstat-label">Credits</div></div>
        <div class="hstat"><div class="hstat-num">8</div><div class="hstat-label">Per Squad</div></div>
        <div class="hstat"><div class="hstat-num">6</div><div class="hstat-label">A-Side</div></div>
      </div>
    </div>
    <div class="scroll-cue"><div class="scroll-txt">Scroll</div><div class="scroll-line"></div></div>
  </div>
  <div class="contact-strip">
    <div class="contact-org-label">Organiser</div>
    <a class="contact-strip-item" href="https://wa.me/27780120351" target="_blank" rel="noopener"><span class="ci-icon">&#128241;</span>+27 78 012 0351</a>
    <a class="contact-strip-item" href="mailto:1abdullahpatel0@gmail.com"><span class="ci-icon">&#9993;</span>1abdullahpatel0@gmail.com</a>
  </div>
</div>

<!-- ════════════════ PLAYERS PAGE -->
<div class="page" id="page-players">
  <div class="section">
    <div class="section-header">
      <div class="section-title">Player Pool</div>
      <div class="section-count" id="players-count">Loading...</div>
    </div>
    <div class="filter-bar">
      <button class="filter-btn active" onclick="filterPlayers('ALL',this)">All</button>
      <button class="filter-btn" onclick="filterPlayers('GK',this)">GK</button>
      <button class="filter-btn" onclick="filterPlayers('DEF',this)">DEF</button>
      <button class="filter-btn" onclick="filterPlayers('MID',this)">MID</button>
      <button class="filter-btn" onclick="filterPlayers('FWD',this)">FWD</button>
      <button class="filter-btn" onclick="filterPlayers('RATED',this)">Rated Only</button>
      <button class="filter-btn" onclick="filterPlayers('AVAILABLE',this)">Available</button>
    </div>
    <div class="players-grid" id="players-grid">
      <div class="loading-state" style="grid-column:1/-1"><div class="loading-spinner"></div><div class="loading-txt">Loading players...</div></div>
    </div>
  </div>
</div>

<!-- ════════════════ AUCTION PAGE -->
<div class="page" id="page-auction">
  <div class="section">
    <div class="section-header">
      <div class="section-title">Auction Board</div>
      <div class="section-count" id="auction-count">Loading...</div>
    </div>
    <div class="captains-grid" id="captains-grid"></div>
    <div id="tier-sections"></div>
  </div>
</div>

<!-- ════════════════ TEAMS PAGE -->
<div class="page" id="page-teams">
  <div class="section">
    <div class="section-header">
      <div class="section-title">Teams</div>
      <div class="section-count" id="teams-count">Season 1</div>
    </div>
    <div style="background:rgba(201,168,76,0.04);border:1px solid var(--border-gold);border-radius:var(--radius-lg);padding:1.5rem;margin-bottom:2.5rem;">
      <div style="font-family:var(--font-display);font-size:1.4rem;letter-spacing:0.05em;margin-bottom:0.25rem;">&#128269; Find My Team</div>
      <div style="font-family:var(--font-mono);font-size:0.62rem;color:var(--txt3);letter-spacing:0.08em;margin-bottom:1rem;">Search your name to see which team drafted you</div>
      <div class="teams-search-wrap">
        <div class="form-group">
          <input type="text" id="team-search" placeholder="Type your name..." oninput="searchPlayerTeam()">
        </div>
      </div>
      <div id="team-search-result"></div>
    </div>
    <div class="teams-grid" id="teams-grid">
      <div class="loading-state" style="grid-column:1/-1"><div class="loading-spinner"></div><div class="loading-txt">Loading teams...</div></div>
    </div>
  </div>
</div>

<!-- ════════════════ REGISTER PAGE -->
<div class="page" id="page-register">
  <div class="reg-hero">
    <div class="reg-hero-title">Register<br><span style="color:var(--gold);">to Play</span></div>
    <div class="reg-hero-sub">Enter the player pool. Get rated. Get drafted.</div>
  </div>
  <div class="reg-wrap">
    <div class="form-group">
      <label>Full Name *</label>
      <input type="text" id="reg-name" placeholder="Your full name">
    </div>
    <div class="form-row">
      <div class="form-group">
        <label>WhatsApp Number *</label>
        <input type="tel" id="reg-phone" placeholder="+27 ...">
      </div>
      <div class="form-group">
        <label>Preferred Position *</label>
        <select id="reg-position" onchange="updateSelfRatingStats()">
          <option value="">Select position</option>
          <option value="GK">Goalkeeper (GK)</option>
          <option value="DEF">Defender (DEF)</option>
          <option value="MID">Midfielder (MID)</option>
          <option value="FWD">Forward (FWD)</option>
        </select>
      </div>
    </div>
    <div class="form-group">
      <label>Secondary Position (optional)</label>
      <select id="reg-position2">
        <option value="">None</option>
        <option value="GK">Goalkeeper (GK)</option>
        <option value="DEF">Defender (DEF)</option>
        <option value="MID">Midfielder (MID)</option>
        <option value="FWD">Forward (FWD)</option>
      </select>
    </div>
    <div class="form-group">
      <label>Anything else we should know?</label>
      <textarea id="reg-note" rows="3" placeholder="e.g. injury history, availability, preferred foot..." style="resize:vertical;"></textarea>
    </div>
    <div class="form-divider"></div>
    <div style="margin-bottom:1.5rem;">
      <div style="font-family:var(--font-display);font-size:1.4rem;letter-spacing:0.05em;margin-bottom:0.25rem;">Rate Yourself</div>
      <div style="font-family:var(--font-mono);font-size:0.62rem;color:var(--txt3);letter-spacing:0.08em;">Optional — give us an idea of your ability</div>
    </div>
    <div class="warn-box">
      <div class="warn-box-icon">&#9888;&#65039;</div>
      <div class="warn-box-txt">Your self-rating is <strong>not your final price</strong>. It's just a guide for the organiser. Your official rating and auction price will be set by the organiser based on what they know about your ability.</div>
    </div>
    <div class="self-rating-wrap">
      <label>Overall Self-Rating (1–10)</label>
      <div class="self-rating-track">
        <input type="range" id="self-rating-slider" min="1" max="10" value="5" oninput="updateSelfRatingDisplay()">
        <div class="self-rating-val" id="self-rating-val">5</div>
      </div>
      <div class="self-rating-desc" id="self-rating-desc">Decent — holds their own in most games</div>
    </div>
    <div class="form-group">
      <label>Why do you rate yourself that? (optional)</label>
      <textarea id="self-rating-reason" rows="2" placeholder="e.g. I score most weeks, strong in the air, good engine..." style="resize:vertical;"></textarea>
    </div>
    <div class="form-divider"></div>
    <div style="margin-bottom:1.5rem;">
      <div style="font-family:var(--font-display);font-size:1.4rem;letter-spacing:0.05em;margin-bottom:0.25rem;">Submit Footage</div>
      <div style="font-family:var(--font-mono);font-size:0.62rem;color:var(--txt3);letter-spacing:0.08em;">Help the organiser rate you accurately</div>
    </div>
    <div class="form-group">
      <label>Video Link (YouTube, Google Drive, etc.)</label>
      <input type="url" id="reg-video" placeholder="https://...">
    </div>
    <div class="form-note" style="margin-bottom:1.5rem;text-align:left;">Paste a link to any footage of you playing — highlights, full match, training clips.</div>
    <button type="button" class="btn-primary btn-full" id="reg-submit-btn" onclick="registerPlayer()">Submit Registration</button>
    <div style="margin-top:1rem;">
      <button type="button" class="btn-wa btn-full" onclick="sendWAConfirmation()">&#128241; Send via WhatsApp Instead</button>
    </div>
    <p class="form-note warn" style="margin-top:1rem;">&#9888; Your final price is set by the organiser — self-rating is a guide only.</p>
  </div>
</div>

<!-- ════════════════ ADMIN PAGE -->
<div class="page" id="page-admin">
  <div id="admin-login">
    <div class="login-wrap">
      <div class="login-title">Admin Panel</div>
      <div class="login-sub">Organiser access only.</div>
      <div class="form-group">
        <label>Password</label>
        <input type="password" id="admin-pw" placeholder="••••••••" onkeydown="if(event.key==='Enter')adminLogin()">
      </div>
      <button type="button" class="btn-primary btn-full" onclick="adminLogin()">Login</button>
    </div>
  </div>

  <div id="admin-dashboard" style="display:none;">
    <div class="admin-wrap">
      <div class="admin-header">
        <div class="admin-title">Admin Panel</div>
        <div style="display:flex;gap:0.5rem;align-items:center;">
          <span class="admin-badge">Organiser</span>
          <button type="button" class="btn-sm btn-danger" onclick="adminLogout()">Logout</button>
        </div>
      </div>
      <div class="admin-tabs">
        <button class="admin-tab active" onclick="switchAdminTab('players',this)">Players</button>
        <button class="admin-tab" onclick="switchAdminTab('captains',this)">Captains</button>
        <button class="admin-tab" onclick="switchAdminTab('assign',this)">Assign</button>
        <button class="admin-tab" onclick="switchAdminTab('pricing',this)">Pricing Guide</button>
        <button class="admin-tab" onclick="switchAdminTab('settings',this)">Settings</button>
      </div>

      <div class="admin-panel active" id="tab-players">
        <div id="admin-players-list"></div>
      </div>

      <div class="admin-panel" id="tab-captains">
        <div class="form-row" style="margin-bottom:1rem;">
          <div class="form-group"><label>Captain Name</label><input type="text" id="cap-name" placeholder="Name"></div>
          <div class="form-group"><label>Team Name</label><input type="text" id="cap-team" placeholder="e.g. Lowveld Lions"></div>
        </div>
        <button type="button" class="btn-primary" onclick="addCaptain()" style="margin-bottom:2rem;">Add Captain</button>
        <div id="admin-captains-list"></div>
      </div>

      <div class="admin-panel" id="tab-assign">
        <p style="color:var(--txt3);font-size:0.85rem;margin-bottom:1rem;">Assign rated players to a captain's squad. Squad limits: 1 GK, 2 DEF, 2 MID, 1 FWD starters + 3 flexible subs = 8 total.</p>
        <div id="assign-captain-needs" style="margin-bottom:1.5rem;"></div>
        <div class="form-row" style="margin-bottom:1rem;">
          <div class="form-group"><label>Select Player</label><select id="assign-player" onchange="updateAssignPreview()"></select></div>
          <div class="form-group"><label>Assign to Captain</label><select id="assign-captain" onchange="updateAssignPreview()"></select></div>
        </div>
        <div class="form-group" style="max-width:220px;">
          <label>Winning Bid (credits)</label>
          <input type="number" id="assign-bid" placeholder="e.g. 8.5" min="0.5" max="100" step="0.5" oninput="updateAssignPreview()">
        </div>
        <div id="assign-preview" style="margin-bottom:1rem;"></div>
        <button type="button" class="btn-primary" onclick="assignPlayer()">Confirm Assignment</button>
      </div>

      <div class="admin-panel" id="tab-pricing">
        <p style="color:var(--txt2);font-size:0.85rem;margin-bottom:1.5rem;">Price ranges by position. Each position has a unique formula — an elite FWD costs more than an elite GK, reflecting real auction scarcity and positional value.</p>
        <div class="pricing-guide" id="pricing-guide-content"></div>
        <div style="background:var(--bg3);border:1px solid var(--border);border-radius:var(--radius);padding:1.25rem;margin-top:1rem;">
          <div style="font-family:var(--font-mono);font-size:0.62rem;letter-spacing:0.1em;text-transform:uppercase;color:var(--txt3);margin-bottom:0.75rem;">Tier Thresholds</div>
          <div style="display:flex;gap:1.5rem;flex-wrap:wrap;">
            <div><span style="color:var(--gold);font-family:var(--font-display);">Elite</span> <span style="font-family:var(--font-mono);font-size:0.65rem;color:var(--txt3);">≥ 10 cr</span></div>
            <div><span style="color:#6fa8f5;font-family:var(--font-display);">Solid</span> <span style="font-family:var(--font-mono);font-size:0.65rem;color:var(--txt3);">6 – 9.5 cr</span></div>
            <div><span style="color:var(--txt3);font-family:var(--font-display);">Budget</span> <span style="font-family:var(--font-mono);font-size:0.65rem;color:var(--txt3);">&lt; 6 cr</span></div>
          </div>
        </div>
      </div>

      <div class="admin-panel" id="tab-settings">
        <div class="form-group" style="max-width:300px;">
          <label>Change Admin Password</label>
          <input type="password" id="new-pw" placeholder="New password">
        </div>
        <button type="button" class="btn-sm" onclick="changePassword()" style="margin-bottom:2rem;">Update Password</button>
        <br>
        <button type="button" class="btn-sm btn-danger" onclick="clearAllData()" style="margin-top:1rem;">&#9888; Clear All Data</button>
        <p style="color:var(--txt3);font-size:0.75rem;margin-top:0.5rem;">Deletes all players and captains from Supabase. Cannot be undone.</p>
      </div>
    </div>
  </div>
</div>

<!-- RATING MODAL -->
<div class="modal-overlay" id="rating-modal" onclick="closeRatingModalOverlay(event)">
  <div class="modal" onclick="event.stopPropagation()">
    <div class="modal-title" id="rating-modal-title">Rate Player</div>
    <div class="modal-sub" id="rating-modal-sub"></div>
    <input type="hidden" id="rating-player-id">
    <div id="stat-inputs" class="stats-grid"></div>
    <div class="price-preview">
      <div class="pp-label">Calculated Price</div>
      <div class="pp-val" id="price-preview">—</div>
      <div class="pp-range" id="price-range-hint"></div>
    </div>
    <div class="modal-actions">
      <button type="button" class="btn-sm" onclick="closeRatingModal()">Cancel</button>
      <button type="button" class="btn-sm btn-green" id="save-rating-btn" onclick="saveRating()">Save Rating</button>
    </div>
  </div>
</div>

<script>
"use strict";

/* ════════════════════════════════════════
   SUPABASE INIT
════════════════════════════════════════ */
var sb = null;
var SUPABASE_CONFIGURED = false;

function initSupabase(){
  var url = window.SUPABASE_URL;
  var key = window.SUPABASE_ANON_KEY;
  if(!url || url.includes('YOUR_PROJECT_ID') || !key || key.includes('YOUR_ANON_KEY')){
    showConfigWarning();
    return false;
  }
  try{
    sb = window.supabase.createClient(url, key);
    SUPABASE_CONFIGURED = true;
    return true;
  } catch(e){
    console.error('Supabase init failed:', e);
    showConfigWarning();
    return false;
  }
}

function showConfigWarning(){
  // Only show if not already shown
  if(document.getElementById('config-warn-banner')) return;
  var banner = document.createElement('div');
  banner.id = 'config-warn-banner';
  banner.className = 'config-warning';
  banner.style.cssText = 'position:fixed;top:90px;left:0;right:0;z-index:198;margin:0;border-radius:0;border-left:none;border-right:none;';
  banner.innerHTML = '<div class="config-warning-icon">⚠️</div>'
    +'<div class="config-warning-txt">'
    +'<strong>Supabase not configured.</strong> Open this HTML file, find the two lines near the top and replace them:<br><br>'
    +'<code>window.SUPABASE_URL = \'https://YOUR_PROJECT_ID.supabase.co\';</code><br>'
    +'<code>window.SUPABASE_ANON_KEY = \'YOUR_ANON_KEY_HERE\';</code><br><br>'
    +'Get these from your Supabase project → Settings → API. Also run the SQL in the comment at the top of this file to create the tables.'
    +'</div>';
  document.body.insertBefore(banner, document.body.firstChild);
  // push content down
  document.querySelectorAll('.page').forEach(function(p){ p.style.paddingTop = '150px'; });
}

/* ════════════════════════════════════════
   DATA LAYER — all reads/writes go through Supabase
════════════════════════════════════════ */
async function dbGetPlayers(){
  if(!sb) return [];
  var { data, error } = await sb.from('players').select('*').order('created_at', {ascending:true});
  if(error){ console.error('getPlayers:', error); return []; }
  return (data||[]).map(normalizePlayer);
}

async function dbGetCaptains(){
  if(!sb) return [];
  var { data, error } = await sb.from('captains').select('*').order('created_at', {ascending:true});
  if(error){ console.error('getCaptains:', error); return []; }
  return data||[];
}

async function dbGetAll(){
  var [players, captains] = await Promise.all([dbGetPlayers(), dbGetCaptains()]);
  return { players, captains };
}

async function dbInsertPlayer(player){
  if(!sb) return false;
  var row = playerToRow(player);
  var { error } = await sb.from('players').insert(row);
  if(error){ console.error('insertPlayer:', error); return false; }
  return true;
}

async function dbUpdatePlayer(id, fields){
  if(!sb) return false;
  var row = {};
  // Map camelCase to snake_case for Supabase
  if(fields.stats       !== undefined) row.stats        = fields.stats;
  if(fields.price       !== undefined) row.price        = fields.price;
  if(fields.captainId   !== undefined) row.captain_id   = fields.captainId;
  if(fields.bidPrice    !== undefined) row.bid_price     = fields.bidPrice;
  var { error } = await sb.from('players').update(row).eq('id', id);
  if(error){ console.error('updatePlayer:', error); return false; }
  return true;
}

async function dbDeletePlayer(id){
  if(!sb) return false;
  var { error } = await sb.from('players').delete().eq('id', id);
  if(error){ console.error('deletePlayer:', error); return false; }
  return true;
}

async function dbInsertCaptain(captain){
  if(!sb) return false;
  var { error } = await sb.from('captains').insert({
    id: captain.id, name: captain.name, team: captain.team||'', budget: captain.budget||100
  });
  if(error){ console.error('insertCaptain:', error); return false; }
  return true;
}

async function dbDeleteCaptain(id){
  if(!sb) return false;
  // Unassign players first
  await sb.from('players').update({captain_id: null, bid_price: null}).eq('captain_id', id);
  var { error } = await sb.from('captains').delete().eq('id', id);
  if(error){ console.error('deleteCaptain:', error); return false; }
  return true;
}

async function dbClearAll(){
  if(!sb) return false;
  await sb.from('players').delete().neq('id','__never__');
  await sb.from('captains').delete().neq('id','__never__');
  return true;
}

// Normalize snake_case from Supabase → camelCase for the app
function normalizePlayer(row){
  return {
    id:               row.id,
    name:             row.name,
    phone:            row.phone,
    pos:              row.pos,
    pos2:             row.pos2||'',
    note:             row.note||'',
    selfRating:       row.self_rating||5,
    selfRatingReason: row.self_rating_reason||'',
    video:            row.video||'',
    stats:            row.stats||null,
    price:            row.price!=null ? Number(row.price) : null,
    captainId:        row.captain_id||null,
    bidPrice:         row.bid_price!=null ? Number(row.bid_price) : null,
  };
}

function playerToRow(p){
  return {
    id:                  p.id,
    name:                p.name,
    phone:               p.phone,
    pos:                 p.pos,
    pos2:                p.pos2||null,
    note:                p.note||null,
    self_rating:         p.selfRating||5,
    self_rating_reason:  p.selfRatingReason||null,
    video:               p.video||null,
    stats:               p.stats||null,
    price:               p.price!=null ? p.price : null,
    captain_id:          p.captainId||null,
    bid_price:           p.bidPrice!=null ? p.bidPrice : null,
  };
}

/* ════════════════════════════════════════
   CONSTANTS & PASSWORD (still localStorage for admin PW only)
════════════════════════════════════════ */
var ADMIN_PW_KEY = 'mdl_admin_pw';
var DEFAULT_PW   = 'mdl2024';
function getAdminPw(){ return localStorage.getItem(ADMIN_PW_KEY)||DEFAULT_PW; }

/* ════════════════════════════════════════
   PRICING ENGINE
════════════════════════════════════════ */
var POS_STATS = {
  GK:  ['Reflexes','Shot Stopping','Distribution','Aerial','Positioning'],
  DEF: ['Tackling','Pace','Aerial','Passing','Positioning'],
  MID: ['Passing','Vision','Stamina','Dribbling','Shooting'],
  FWD: ['Finishing','Pace','Dribbling','Hold-up Play','Off the Ball'],
};
var STAT_WEIGHTS = {
  GK:  {'Reflexes':2.5,'Shot Stopping':2.5,'Distribution':0.75,'Aerial':0.75,'Positioning':1.5},
  DEF: {'Tackling':2,'Pace':1.5,'Aerial':1.25,'Passing':0.75,'Positioning':1.5},
  MID: {'Passing':1.5,'Vision':1.25,'Stamina':1,'Dribbling':1.5,'Shooting':1.75},
  FWD: {'Finishing':3,'Pace':2,'Dribbling':1.5,'Hold-up Play':0.75,'Off the Ball':1.75},
};
var POS_PRICE = {
  GK:  {base:3.5, ceil:9.0},
  DEF: {base:4.0, ceil:13.0},
  MID: {base:4.5, ceil:14.0},
  FWD: {base:6.0, ceil:18.0},
};

function calcPrice(stats, pos){
  var weights=STAT_WEIGHTS[pos]||{};
  var totalW=0, totalWV=0;
  Object.keys(stats).forEach(function(s){
    var w=weights[s]||1; totalW+=w; totalWV+=(Number(stats[s])||0)*w;
  });
  if(!totalW) return null;
  var wavg=totalWV/totalW;
  var pp=POS_PRICE[pos]||{base:4,ceil:12};
  var price=pp.base+((wavg-1)/9)*(pp.ceil-pp.base);
  return Math.round(price*2)/2;
}
function getTier(price){
  if(price===null||price===undefined) return null;
  if(price>=10) return 'ELITE';
  if(price>=6)  return 'SOLID';
  return 'BUDGET';
}
function posColor(pos){
  return {GK:'#ffa500',DEF:'#6fa8f5',MID:'#4ecb71',FWD:'#f57070'}[pos]||'#fff';
}

var STARTER_SLOTS={GK:1,DEF:2,MID:2,FWD:1};
var SQUAD_MAX=8;
function getSquadNeeds(squad){
  var counts={GK:0,DEF:0,MID:0,FWD:0};
  squad.forEach(function(p){if(counts[p.pos]!==undefined) counts[p.pos]++;});
  var needs={};
  Object.keys(STARTER_SLOTS).forEach(function(pos){
    var need=STARTER_SLOTS[pos]-counts[pos];
    if(need>0) needs[pos]=need;
  });
  return needs;
}

/* ════════════════════════════════════════
   NAVIGATION
════════════════════════════════════════ */
function navigate(page){
  document.querySelectorAll('.page').forEach(function(p){p.classList.remove('active');});
  var t=document.getElementById('page-'+page);
  if(!t) return;
  t.classList.add('active');
  document.querySelectorAll('.nav-links a').forEach(function(a){a.classList.remove('active');});
  var n=document.getElementById('nav-'+page);
  if(n) n.classList.add('active');
  window.scrollTo(0,0);
  closeMobileNav();
  if(page==='players') renderPlayers();
  if(page==='auction') renderAuction();
  if(page==='teams')   renderTeams();
  if(page==='home')    updateHeroStats();
  if(page==='admin'&&adminLoggedIn){ renderAdminPlayers(); renderAdminCaptains(); }
}
function toggleMobileNav(){ document.getElementById('nav-links').classList.toggle('open'); }
function closeMobileNav(){ document.getElementById('nav-links').classList.remove('open'); }
document.addEventListener('keydown',function(e){if(e.key==='Escape') closeRatingModal();});

/* ════════════════════════════════════════
   SELF RATING
════════════════════════════════════════ */
var RATING_DESCS=['','Struggling — still learning the game','Beginner — occasional bright moments','Below average — getting there','Average — holds their own','Decent — solid in most games','Good — makes a difference regularly','Very good — one of the better players','Excellent — a real threat every game','Elite — dominates most matches','World class — unstoppable on their day'];
function updateSelfRatingDisplay(){
  var v=document.getElementById('self-rating-slider').value;
  document.getElementById('self-rating-val').textContent=v;
  document.getElementById('self-rating-desc').textContent=RATING_DESCS[v]||'';
}
function updateSelfRatingStats(){}

/* ════════════════════════════════════════
   REGISTRATION
════════════════════════════════════════ */
async function registerPlayer(){
  if(!SUPABASE_CONFIGURED){ showToast('Supabase not configured. Use the WhatsApp option instead.','error'); return; }

  var name   = document.getElementById('reg-name').value.trim();
  var phone  = document.getElementById('reg-phone').value.trim();
  var pos    = document.getElementById('reg-position').value;
  var pos2   = document.getElementById('reg-position2').value;
  var note   = document.getElementById('reg-note').value.trim();
  var selfR  = document.getElementById('self-rating-slider').value;
  var selfTxt= document.getElementById('self-rating-reason').value.trim();
  var video  = document.getElementById('reg-video').value.trim();

  if(!name||!phone||!pos){ showToast('Please fill in all required fields.','error'); return; }
  var digits=phone.replace(/\D/g,'');
  if(digits.length<10){ showToast('Please enter a valid phone number.','error'); return; }

  // Check for duplicate phone
  var { data: existing } = await sb.from('players').select('id').eq('phone', phone).maybeSingle();
  if(existing){ showToast('A player with this number is already registered.','error'); return; }

  var btn = document.getElementById('reg-submit-btn');
  btn.disabled = true;
  btn.textContent = 'Submitting...';

  var player = {
    id: Date.now().toString()+Math.random().toString(36).substr(2,5),
    name, phone, pos, pos2, note,
    selfRating: Number(selfR), selfRatingReason: selfTxt, video,
    stats: null, price: null, captainId: null, bidPrice: null,
  };

  var ok = await dbInsertPlayer(player);
  btn.disabled = false;
  btn.textContent = 'Submit Registration';

  if(!ok){ showToast('Registration failed. Try the WhatsApp option instead.','error'); return; }

  sendOrgNotification(player);
  ['reg-name','reg-phone','reg-note','self-rating-reason','reg-video'].forEach(function(id){document.getElementById(id).value='';});
  document.getElementById('reg-position').value='';
  document.getElementById('reg-position2').value='';
  document.getElementById('self-rating-slider').value=5;
  updateSelfRatingDisplay();
  showToast(name+' registered! Organiser notified.','success');
  updateHeroStats();
}

function sendOrgNotification(player){
  var msg='🏆 *New MDL Registration*\n\n'
    +'*Name:* '+player.name+'\n'
    +'*Phone:* '+player.phone+'\n'
    +'*Position:* '+player.pos+(player.pos2?' / '+player.pos2:'')+'\n'
    +'*Self-Rating:* '+player.selfRating+'/10\n'
    +(player.selfRatingReason?'*Why:* '+player.selfRatingReason+'\n':'')
    +(player.video?'*Video:* '+player.video+'\n':'')
    +(player.note?'*Notes:* '+player.note+'\n':'')
    +'\n_Malelane Draft League — Season 1_';
  window.open('https://wa.me/27780120351?text='+encodeURIComponent(msg),'_blank');
}

function sendWAConfirmation(){
  var name  =document.getElementById('reg-name').value.trim();
  var phone =document.getElementById('reg-phone').value.trim();
  var pos   =document.getElementById('reg-position').value;
  if(!name||!phone||!pos){ showToast('Fill in your name, number and position first.','error'); return; }
  var selfR =document.getElementById('self-rating-slider').value;
  var selfTxt=document.getElementById('self-rating-reason').value.trim();
  var video =document.getElementById('reg-video').value.trim();
  var note  =document.getElementById('reg-note').value.trim();
  var msg='🏆 *MDL Registration — '+name+'*\n\n'
    +'*Position:* '+pos+'\n'
    +'*My Number:* '+phone+'\n'
    +'*Self-Rating:* '+selfR+'/10\n'
    +(selfTxt?'*Why:* '+selfTxt+'\n':'')
    +(video?'*Video:* '+video+'\n':'')
    +(note?'*Notes:* '+note+'\n':'')
    +'\n⚠️ _I understand my self-rating is not my final price._\n_Malelane Draft League — Season 1_';
  window.open('https://wa.me/27780120351?text='+encodeURIComponent(msg),'_blank');
  showToast('WhatsApp opened — send the message to complete registration.','success');
}

/* ════════════════════════════════════════
   PLAYERS PAGE
════════════════════════════════════════ */
var currentFilter='ALL';
function filterPlayers(f,btn){
  currentFilter=f;
  document.querySelectorAll('.filter-btn').forEach(function(b){b.classList.remove('active');});
  if(btn) btn.classList.add('active');
  renderPlayers();
}

async function renderPlayers(){
  var grid=document.getElementById('players-grid');
  grid.innerHTML='<div class="loading-state" style="grid-column:1/-1"><div class="loading-spinner"></div><div class="loading-txt">Loading players...</div></div>';

  var d = await dbGetAll();
  var players=d.players.slice();
  if(currentFilter==='RATED')     players=players.filter(function(p){return p.stats;});
  else if(currentFilter==='AVAILABLE') players=players.filter(function(p){return p.stats&&!p.captainId;});
  else if(currentFilter!=='ALL')  players=players.filter(function(p){return p.pos===currentFilter;});
  document.getElementById('players-count').textContent=players.length+' player'+(players.length!==1?'s':'');

  if(!players.length){
    grid.innerHTML='<div class="empty-state" style="grid-column:1/-1"><div class="empty-icon">⚽</div><div class="empty-text">No players in this category yet</div></div>';
    return;
  }
  grid.innerHTML=players.map(function(p){return playerCardHTML(p,d.captains);}).join('');
}

function playerCardHTML(p, captains){
  var initials=p.name.split(' ').map(function(w){return w[0]||'';}).join('').slice(0,2).toUpperCase();
  var captain=(captains||[]).find(function(c){return c.id===p.captainId;});
  var stripClass=p.stats?'strip-'+p.pos:'strip-pending';
  var tier=p.price!=null?getTier(p.price):null;
  var priceHTML, bottomHTML='';
  if(p.stats&&p.price!=null){
    var tierLabel=tier==='ELITE'?'<span class="tier-badge tier-elite">★ Elite</span>'
                 :tier==='SOLID'?'<span class="tier-badge tier-solid">● Solid</span>'
                 :'<span class="tier-badge tier-budget">Budget</span>';
    priceHTML='<div><div class="card-price-row"><span><span class="card-price">'+p.price.toFixed(1)+'</span> <span class="card-price-cr">cr</span></span></div>'+tierLabel+'</div>';
  } else {
    priceHTML='<span class="card-price-pending">Pending rating</span>';
    bottomHTML='<div class="card-divider"></div><div class="card-pending-body"><div class="pending-label">Awaiting organiser rating</div></div>';
  }
  var soldTag=captain?'<div class="card-sold-tag">📋 '+(captain.team||captain.name)+'</div>':'';
  var topPad=captain?'padding-top:2rem;':'';
  return '<div class="player-card">'
    +'<div class="card-strip '+stripClass+'"></div>'
    +soldTag
    +'<div class="card-top" style="'+topPad+'">'
      +'<div class="card-pos pos-'+p.pos+'">'+p.pos+'</div>'
      +'<div class="card-avatar">'+initials+'</div>'
      +'<div class="card-name">'+esc(p.name)+'</div>'
      +priceHTML
    +'</div>'
    +bottomHTML
  +'</div>';
}

/* ════════════════════════════════════════
   AUCTION PAGE
════════════════════════════════════════ */
async function renderAuction(){
  document.getElementById('auction-count').textContent='Loading...';
  document.getElementById('captains-grid').innerHTML='<div class="loading-state" style="grid-column:1/-1"><div class="loading-spinner"></div><div class="loading-txt">Loading...</div></div>';

  var d = await dbGetAll();
  document.getElementById('auction-count').textContent=d.captains.length+' captain'+(d.captains.length!==1?'s':'');
  var capGrid=document.getElementById('captains-grid');
  if(!d.captains.length){
    capGrid.innerHTML='<div class="empty-state" style="grid-column:1/-1"><div class="empty-icon">🏆</div><div class="empty-text">No captains added yet</div></div>';
  } else {
    capGrid.innerHTML=d.captains.map(function(c){return captainCardHTML(c,d.players);}).join('');
  }
  renderTierSections(d);
}

function captainCardHTML(c, players){
  var squad=players.filter(function(p){return p.captainId===c.id;});
  var spent=squad.reduce(function(a,p){return a+(p.bidPrice||0);},0);
  var rem=(c.budget||100)-spent;
  var pct=Math.max(0,(rem/(c.budget||100))*100);
  var fillClass=rem<20?'danger':rem<40?'warn':'';
  var initials=c.name.split(' ').map(function(w){return w[0]||'';}).join('').slice(0,2).toUpperCase();
  var needs=getSquadNeeds(squad);
  var needsHTML='';
  Object.keys(needs).forEach(function(pos){needsHTML+='<span class="need-badge need-'+pos+'">Need '+needs[pos]+' '+pos+'</span>';});
  if(squad.length>=SQUAD_MAX) needsHTML='<span class="need-badge" style="background:rgba(26,122,60,0.12);color:#4ecb71;border:1px solid rgba(26,122,60,0.3);">✓ Squad Full</span>';

  var byPos={GK:[],DEF:[],MID:[],FWD:[]};
  squad.forEach(function(p){if(byPos[p.pos]) byPos[p.pos].push(p);});
  var formation=[
    {slots:1,players:byPos.GK.slice(0,1)},
    {slots:2,players:byPos.DEF.slice(0,2)},
    {slots:2,players:byPos.MID.slice(0,2)},
    {slots:1,players:byPos.FWD.slice(0,1)},
  ];
  var pitchRows=formation.map(function(row){
    var slots='';
    for(var i=0;i<row.slots;i++){
      var pl=row.players[i];
      if(pl){
        var ini=pl.name.split(' ').map(function(w){return w[0]||'';}).join('').slice(0,2).toUpperCase();
        var col=posColor(pl.pos);
        slots+='<div class="pitch-player"><div class="pitch-player-circle" style="border-color:'+col+'40;background:'+col+'15;color:'+col+';">'+ini+'</div><div class="pitch-player-name">'+pl.name.split(' ')[0]+'</div></div>';
      } else {
        slots+='<div class="pitch-player pitch-empty"><div class="pitch-player-circle"></div><div class="pitch-player-name" style="color:var(--txt3);">—</div></div>';
      }
    }
    return '<div class="pitch-row">'+slots+'</div>';
  }).join('');

  var starterSet=[];
  formation.forEach(function(row){row.players.forEach(function(p){starterSet.push(p.id);});});
  var subs=squad.filter(function(p){return !starterSet.includes(p.id);}).slice(0,3);
  var subSlots='';
  for(var i=0;i<3;i++){
    var sub=subs[i];
    if(sub){
      var ini=sub.name.split(' ').map(function(w){return w[0]||'';}).join('').slice(0,2).toUpperCase();
      var col=posColor(sub.pos);
      subSlots+='<div class="pitch-player"><div class="pitch-player-circle" style="font-size:0.8rem;border-color:'+col+'40;background:'+col+'0d;color:'+col+';">'+ini+'</div><div class="pitch-player-name">'+sub.name.split(' ')[0]+'</div></div>';
    } else {
      subSlots+='<div class="pitch-player pitch-empty"><div class="pitch-player-circle"></div><div class="pitch-player-name" style="color:var(--txt3);">—</div></div>';
    }
  }
  var avatarGrad='background:linear-gradient(135deg,'+['#1a7a3c','#c9a84c','#3c7de0','#e03c3c','#8b3ce0'][c.name.charCodeAt(0)%5]+','+['#4ecb71','#e8c96a','#6fa8f5','#f57070','#c17cf0'][c.name.charCodeAt(1)%5]+');';
  return '<div class="captain-card">'
    +'<div class="cap-strip"></div>'
    +'<div class="cap-inner">'
      +'<div class="cap-header"><div class="cap-avatar" style="'+avatarGrad+'">'+initials+'</div><div><div class="cap-name">'+esc(c.name)+'</div><div class="cap-team">'+(c.team||'No team name')+'</div></div></div>'
      +'<div class="budget-lbl"><span>Budget</span><span class="brem">'+rem.toFixed(1)+' cr left</span></div>'
      +'<div class="budget-bar"><div class="budget-fill '+fillClass+'" style="width:'+pct+'%"></div></div>'
      +'<div class="squad-meta">'+squad.length+'/8 players · '+spent.toFixed(1)+' cr spent</div>'
      +'<div class="squad-needs">'+needsHTML+'</div>'
      +'<div class="pitch-view"><div class="
