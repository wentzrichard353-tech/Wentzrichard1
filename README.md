<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>All Roads Towing Accident Recovery Specialists | Wisconsin Dells, WI</title>
<meta name="description" content="Fast, reliable towing and accident recovery services in Wisconsin Dells, WI. Available 24/7. Call +1 (262) 844-7838 for emergency towing, roadside assistance, and accident recovery.">
<meta name="keywords" content="towing Wisconsin Dells, accident recovery, roadside assistance, emergency towing, 24/7 towing WI">
<link rel="preconnect" href="https://fonts.googleapis.com">
<link href="https://fonts.googleapis.com/css2?family=Barlow+Condensed:wght@400;600;700;800;900&family=Barlow:wght@300;400;500;600&display=swap" rel="stylesheet">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css">
<style>
:root {
  --navy: #0a1628;
  --navy2: #0d1f3c;
  --navy3: #152a4e;
  --blue: #1a3a6b;
  --blue2: #1e4890;
  --red: #d42b2b;
  --red2: #b02020;
  --yellow: #f5c518;
  --yellow2: #e0b010;
  --white: #ffffff;
  --off-white: #f0f4f8;
  --gray: #8a9ab0;
  --gray2: #c8d4e0;
  --dark: #050d1a;
  --text: #e8eef5;
  --text-muted: #8a9ab0;
  --font-head: 'Barlow Condensed', sans-serif;
  --font-body: 'Barlow', sans-serif;
  --transition: 0.3s ease;
  --shadow: 0 8px 32px rgba(0,0,0,0.4);
  --shadow-sm: 0 2px 12px rgba(0,0,0,0.25);
}

*, *::before, *::after { box-sizing: border-box; margin: 0; padding: 0; }

html { scroll-behavior: smooth; font-size: 16px; }

body {
  font-family: var(--font-body);
  background: var(--navy);
  color: var(--text);
  line-height: 1.6;
  overflow-x: hidden;
}

/* ── SCROLLBAR ── */
::-webkit-scrollbar { width: 8px; }
::-webkit-scrollbar-track { background: var(--dark); }
::-webkit-scrollbar-thumb { background: var(--blue2); border-radius: 4px; }

/* ── NAV ── */
#navbar {
  position: fixed;
  top: 0; left: 0; right: 0;
  z-index: 1000;
  background: rgba(5,13,26,0.95);
  backdrop-filter: blur(16px);
  border-bottom: 2px solid var(--blue);
  transition: var(--transition);
}
#navbar.scrolled { box-shadow: 0 4px 24px rgba(0,0,0,0.5); }

.nav-inner {
  max-width: 1300px;
  margin: 0 auto;
  padding: 0 24px;
  display: flex;
  align-items: center;
  justify-content: space-between;
  height: 72px;
}

.nav-logo {
  display: flex;
  align-items: center;
  gap: 12px;
  text-decoration: none;
  cursor: pointer;
}
.nav-logo-icon {
  width: 48px; height: 48px;
  background: var(--red);
  border-radius: 8px;
  display: flex; align-items: center; justify-content: center;
  font-size: 22px;
  color: white;
  flex-shrink: 0;
}
.nav-logo-text { display: flex; flex-direction: column; line-height: 1.1; }
.nav-logo-text .brand { font-family: var(--font-head); font-size: 18px; font-weight: 800; color: var(--white); letter-spacing: 0.5px; }
.nav-logo-text .tagline { font-size: 10px; color: var(--yellow); font-weight: 600; letter-spacing: 1.5px; text-transform: uppercase; }

.nav-links {
  display: flex;
  align-items: center;
  gap: 4px;
  list-style: none;
}
.nav-links a {
  display: block;
  padding: 8px 14px;
  color: var(--gray2);
  text-decoration: none;
  font-family: var(--font-head);
  font-size: 15px;
  font-weight: 600;
  letter-spacing: 0.5px;
  border-radius: 6px;
  transition: var(--transition);
  text-transform: uppercase;
  cursor: pointer;
}
.nav-links a:hover, .nav-links a.active { color: var(--white); background: var(--blue); }

.nav-cta {
  display: flex; align-items: center; gap: 10px;
}
.btn-call {
  display: flex; align-items: center; gap: 8px;
  background: var(--red);
  color: white;
  padding: 10px 18px;
  border-radius: 6px;
  font-family: var(--font-head);
  font-size: 15px;
  font-weight: 700;
  letter-spacing: 0.5px;
  text-decoration: none;
  transition: var(--transition);
  border: none; cursor: pointer;
  animation: pulse-red 2.5s infinite;
}
.btn-call:hover { background: var(--red2); transform: translateY(-1px); }

@keyframes pulse-red {
  0%, 100% { box-shadow: 0 0 0 0 rgba(212,43,43,0.4); }
  50% { box-shadow: 0 0 0 8px rgba(212,43,43,0); }
}

.hamburger {
  display: none;
  flex-direction: column;
  gap: 5px;
  cursor: pointer;
  padding: 8px;
  background: none;
  border: none;
}
.hamburger span { display: block; width: 26px; height: 2px; background: var(--white); transition: var(--transition); }
.hamburger.open span:nth-child(1) { transform: rotate(45deg) translate(5px, 5px); }
.hamburger.open span:nth-child(2) { opacity: 0; }
.hamburger.open span:nth-child(3) { transform: rotate(-45deg) translate(5px, -5px); }

.mobile-menu {
  display: none;
  position: fixed;
  top: 72px; left: 0; right: 0;
  background: rgba(5,13,26,0.98);
  backdrop-filter: blur(16px);
  border-bottom: 2px solid var(--blue);
  z-index: 999;
  padding: 20px 24px;
  flex-direction: column;
  gap: 4px;
}
.mobile-menu.open { display: flex; }
.mobile-menu a {
  display: block;
  padding: 12px 16px;
  color: var(--gray2);
  text-decoration: none;
  font-family: var(--font-head);
  font-size: 17px;
  font-weight: 600;
  letter-spacing: 0.5px;
  border-radius: 6px;
  text-transform: uppercase;
  cursor: pointer;
  transition: var(--transition);
}
.mobile-menu a:hover { color: var(--white); background: var(--blue); }
.mobile-menu .m-call {
  margin-top: 12px;
  background: var(--red);
  color: white;
  text-align: center;
  padding: 14px;
  border-radius: 6px;
  font-size: 18px;
}

/* ── PAGE SYSTEM ── */
.page { display: none; }
.page.active { display: block; }

/* ── HERO ── */
.hero {
  position: relative;
  min-height: 100vh;
  display: flex;
  align-items: center;
  overflow: hidden;
  padding-top: 72px;
}

.hero-bg {
  position: absolute;
  inset: 0;
  background:
    linear-gradient(135deg, rgba(5,13,26,0.92) 0%, rgba(10,22,40,0.8) 50%, rgba(21,42,78,0.7) 100%),
    url('https://images.unsplash.com/photo-1558618666-fcd25c85cd64?w=1600&q=80') center/cover no-repeat;
}

.hero-pattern {
  position: absolute;
  inset: 0;
  background-image:
    repeating-linear-gradient(90deg, transparent, transparent 80px, rgba(255,197,24,0.03) 80px, rgba(255,197,24,0.03) 82px);
  pointer-events: none;
}

.hero-stripe {
  position: absolute;
  bottom: 0; left: 0; right: 0;
  height: 8px;
  background: repeating-linear-gradient(90deg, var(--yellow) 0, var(--yellow) 40px, var(--dark) 40px, var(--dark) 80px);
}

.hero-content {
  position: relative;
  max-width: 1300px;
  margin: 0 auto;
  padding: 80px 24px 120px;
  display: grid;
  grid-template-columns: 1fr 380px;
  gap: 60px;
  align-items: center;
  width: 100%;
}

.hero-badge {
  display: inline-flex;
  align-items: center;
  gap: 8px;
  background: var(--red);
  color: white;
  padding: 6px 16px;
  border-radius: 40px;
  font-family: var(--font-head);
  font-size: 13px;
  font-weight: 700;
  letter-spacing: 2px;
  text-transform: uppercase;
  margin-bottom: 20px;
  animation: badge-pulse 2s infinite;
}
.hero-badge .dot { width: 8px; height: 8px; background: white; border-radius: 50%; animation: blink 1s infinite; }
@keyframes blink { 0%,100% { opacity: 1; } 50% { opacity: 0; } }
@keyframes badge-pulse { 0%,100% { box-shadow: 0 0 0 0 rgba(212,43,43,0.5); } 50% { box-shadow: 0 0 0 10px rgba(212,43,43,0); } }

.hero h1 {
  font-family: var(--font-head);
  font-size: clamp(42px, 6vw, 76px);
  font-weight: 900;
  line-height: 0.95;
  color: var(--white);
  letter-spacing: -1px;
  margin-bottom: 24px;
}
.hero h1 em { color: var(--yellow); font-style: normal; }
.hero h1 span { color: var(--red); }

.hero-sub {
  font-size: 18px;
  color: var(--gray2);
  max-width: 560px;
  margin-bottom: 40px;
  line-height: 1.7;
}

.hero-btns {
  display: flex;
  flex-wrap: wrap;
  gap: 14px;
  margin-bottom: 48px;
}

.btn-primary {
  display: inline-flex; align-items: center; gap: 10px;
  background: var(--red);
  color: white;
  padding: 16px 28px;
  border-radius: 6px;
  font-family: var(--font-head);
  font-size: 17px;
  font-weight: 700;
  letter-spacing: 0.5px;
  text-decoration: none;
  transition: var(--transition);
  cursor: pointer;
  border: none;
}
.btn-primary:hover { background: var(--red2); transform: translateY(-2px); box-shadow: 0 8px 24px rgba(212,43,43,0.4); }

.btn-secondary {
  display: inline-flex; align-items: center; gap: 10px;
  background: rgba(255,255,255,0.1);
  border: 2px solid rgba(255,255,255,0.3);
  color: white;
  padding: 14px 26px;
  border-radius: 6px;
  font-family: var(--font-head);
  font-size: 17px;
  font-weight: 700;
  letter-spacing: 0.5px;
  text-decoration: none;
  transition: var(--transition);
  cursor: pointer;
}
.btn-secondary:hover { background: var(--blue2); border-color: var(--blue2); transform: translateY(-2px); }

.btn-whatsapp {
  display: inline-flex; align-items: center; gap: 10px;
  background: #25D366;
  color: white;
  padding: 16px 28px;
  border-radius: 6px;
  font-family: var(--font-head);
  font-size: 17px;
  font-weight: 700;
  text-decoration: none;
  transition: var(--transition);
}
.btn-whatsapp:hover { background: #1da851; transform: translateY(-2px); box-shadow: 0 8px 24px rgba(37,211,102,0.3); }

.hero-stats {
  display: flex;
  gap: 32px;
  flex-wrap: wrap;
}
.hero-stat { text-align: center; }
.hero-stat .num {
  font-family: var(--font-head);
  font-size: 36px;
  font-weight: 900;
  color: var(--yellow);
  line-height: 1;
}
.hero-stat .lbl { font-size: 12px; color: var(--gray); letter-spacing: 1px; text-transform: uppercase; margin-top: 4px; }

/* Hero card */
.hero-card {
  background: rgba(10,22,40,0.85);
  border: 1px solid rgba(255,255,255,0.1);
  border-radius: 16px;
  padding: 36px;
  backdrop-filter: blur(12px);
  box-shadow: var(--shadow);
}
.hero-card-title {
  font-family: var(--font-head);
  font-size: 22px;
  font-weight: 800;
  color: var(--white);
  margin-bottom: 24px;
  display: flex; align-items: center; gap: 10px;
}
.hero-card-title i { color: var(--red); }
.contact-item {
  display: flex;
  align-items: center;
  gap: 14px;
  padding: 14px 0;
  border-bottom: 1px solid rgba(255,255,255,0.08);
}
.contact-item:last-child { border-bottom: none; }
.contact-icon {
  width: 42px; height: 42px;
  border-radius: 8px;
  display: flex; align-items: center; justify-content: center;
  font-size: 16px;
  flex-shrink: 0;
}
.contact-icon.phone { background: rgba(212,43,43,0.2); color: var(--red); }
.contact-icon.wa { background: rgba(37,211,102,0.2); color: #25D366; }
.contact-icon.mail { background: rgba(26,58,107,0.4); color: var(--blue2); }
.contact-icon.clock { background: rgba(245,197,24,0.2); color: var(--yellow); }
.contact-info strong { display: block; font-size: 13px; color: var(--gray); font-weight: 400; }
.contact-info a, .contact-info span { color: var(--white); font-weight: 600; text-decoration: none; font-size: 15px; }
.contact-info a:hover { color: var(--yellow); }

/* ── SECTION COMMON ── */
.section {
  padding: 100px 0;
}
.section-alt { background: var(--navy2); }
.section-dark { background: var(--dark); }

.container {
  max-width: 1300px;
  margin: 0 auto;
  padding: 0 24px;
}

.section-label {
  display: inline-flex;
  align-items: center;
  gap: 8px;
  font-family: var(--font-head);
  font-size: 12px;
  font-weight: 700;
  color: var(--yellow);
  letter-spacing: 3px;
  text-transform: uppercase;
  margin-bottom: 16px;
}
.section-label::before {
  content: '';
  display: block;
  width: 30px; height: 2px;
  background: var(--yellow);
}

.section-title {
  font-family: var(--font-head);
  font-size: clamp(32px, 5vw, 56px);
  font-weight: 900;
  color: var(--white);
  line-height: 1;
  margin-bottom: 16px;
  letter-spacing: -0.5px;
}
.section-title em { color: var(--yellow); font-style: normal; }
.section-title span { color: var(--red); }

.section-sub {
  font-size: 17px;
  color: var(--gray);
  max-width: 600px;
  line-height: 1.7;
}

/* ── WHY CHOOSE US ── */
.why-grid {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 24px;
  margin-top: 60px;
}
.why-card {
  background: var(--navy2);
  border: 1px solid rgba(255,255,255,0.07);
  border-radius: 12px;
  padding: 32px;
  transition: var(--transition);
  position: relative;
  overflow: hidden;
}
.why-card::after {
  content: '';
  position: absolute;
  bottom: 0; left: 0;
  width: 100%; height: 3px;
  background: var(--red);
  transform: scaleX(0);
  transform-origin: left;
  transition: var(--transition);
}
.why-card:hover { transform: translateY(-4px); border-color: rgba(212,43,43,0.3); }
.why-card:hover::after { transform: scaleX(1); }
.why-icon {
  width: 56px; height: 56px;
  background: rgba(212,43,43,0.15);
  border-radius: 12px;
  display: flex; align-items: center; justify-content: center;
  font-size: 22px;
  color: var(--red);
  margin-bottom: 20px;
}
.why-card h3 {
  font-family: var(--font-head);
  font-size: 20px;
  font-weight: 800;
  color: var(--white);
  margin-bottom: 10px;
}
.why-card p { color: var(--gray); font-size: 15px; line-height: 1.6; }

/* ── FOUNDER ── */
.founder-section {
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 80px;
  align-items: center;
  padding: 100px 0;
}
.founder-img-wrap {
  position: relative;
}
.founder-img-wrap img {
  width: 100%;
  border-radius: 16px;
  object-fit: cover;
  height: 480px;
  filter: grayscale(20%) contrast(1.05);
}
.founder-badge {
  position: absolute;
  bottom: -20px; right: -20px;
  background: var(--red);
  color: white;
  border-radius: 12px;
  padding: 20px 24px;
  font-family: var(--font-head);
  font-size: 14px;
  font-weight: 700;
  letter-spacing: 1px;
  text-align: center;
  box-shadow: var(--shadow);
}
.founder-badge .big { font-size: 40px; display: block; line-height: 1; }

.founder-content .section-label { margin-bottom: 12px; }
.founder-name {
  font-family: var(--font-head);
  font-size: 48px;
  font-weight: 900;
  color: var(--white);
  line-height: 1;
  margin-bottom: 8px;
}
.founder-title { color: var(--yellow); font-weight: 600; font-size: 15px; letter-spacing: 1px; text-transform: uppercase; margin-bottom: 24px; }
.founder-content p { color: var(--gray); line-height: 1.8; margin-bottom: 20px; font-size: 16px; }

/* ── SERVICES ── */
.services-grid {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 24px;
  margin-top: 60px;
}
.service-card {
  background: var(--navy);
  border: 1px solid rgba(255,255,255,0.07);
  border-radius: 12px;
  padding: 32px;
  transition: var(--transition);
  display: flex;
  flex-direction: column;
  gap: 16px;
  cursor: default;
}
.service-card:hover { transform: translateY(-6px); border-color: rgba(245,197,24,0.3); box-shadow: 0 16px 40px rgba(0,0,0,0.4); }
.service-icon {
  width: 64px; height: 64px;
  background: linear-gradient(135deg, var(--blue), var(--blue2));
  border-radius: 14px;
  display: flex; align-items: center; justify-content: center;
  font-size: 24px;
  color: var(--yellow);
  flex-shrink: 0;
}
.service-card h3 {
  font-family: var(--font-head);
  font-size: 22px;
  font-weight: 800;
  color: var(--white);
}
.service-card p { color: var(--gray); font-size: 15px; line-height: 1.65; flex: 1; }
.service-benefits {
  list-style: none;
  margin: 4px 0;
}
.service-benefits li {
  display: flex;
  align-items: center;
  gap: 8px;
  font-size: 14px;
  color: var(--gray2);
  padding: 3px 0;
}
.service-benefits li::before { content: '✓'; color: var(--yellow); font-weight: 700; }
.btn-sm {
  display: inline-flex; align-items: center; gap: 8px;
  background: var(--red);
  color: white;
  padding: 10px 20px;
  border-radius: 6px;
  font-family: var(--font-head);
  font-size: 14px;
  font-weight: 700;
  text-decoration: none;
  transition: var(--transition);
  border: none; cursor: pointer;
  letter-spacing: 0.5px;
  align-self: flex-start;
}
.btn-sm:hover { background: var(--red2); transform: translateY(-1px); }

/* ── ABOUT ── */
.about-hero {
  background: linear-gradient(135deg, var(--dark) 0%, var(--navy2) 100%);
  padding: 120px 0 80px;
  position: relative;
  overflow: hidden;
}
.about-hero::before {
  content: '';
  position: absolute;
  top: -50%; right: -10%;
  width: 600px; height: 600px;
  background: radial-gradient(circle, rgba(26,58,107,0.3) 0%, transparent 70%);
  pointer-events: none;
}

.values-grid {
  display: grid;
  grid-template-columns: repeat(5, 1fr);
  gap: 20px;
  margin-top: 60px;
}
.value-card {
  text-align: center;
  padding: 32px 20px;
  background: var(--navy2);
  border-radius: 12px;
  border: 1px solid rgba(255,255,255,0.07);
  transition: var(--transition);
}
.value-card:hover { transform: translateY(-4px); border-color: rgba(245,197,24,0.3); }
.value-icon {
  width: 60px; height: 60px;
  background: linear-gradient(135deg, var(--yellow2), var(--yellow));
  border-radius: 50%;
  display: flex; align-items: center; justify-content: center;
  font-size: 22px;
  color: var(--dark);
  margin: 0 auto 16px;
}
.value-card h3 {
  font-family: var(--font-head);
  font-size: 18px;
  font-weight: 800;
  color: var(--white);
  margin-bottom: 8px;
}
.value-card p { font-size: 13px; color: var(--gray); line-height: 1.5; }

.mission-vision {
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 32px;
  margin-top: 60px;
}
.mv-card {
  padding: 40px;
  border-radius: 16px;
  border-left: 4px solid;
  background: var(--navy2);
}
.mv-card.mission { border-color: var(--red); }
.mv-card.vision { border-color: var(--yellow); }
.mv-card h3 {
  font-family: var(--font-head);
  font-size: 28px;
  font-weight: 800;
  margin-bottom: 16px;
}
.mv-card.mission h3 { color: var(--red); }
.mv-card.vision h3 { color: var(--yellow); }
.mv-card p { color: var(--gray); line-height: 1.8; font-size: 16px; }

/* ── CONTACT ── */
.contact-grid {
  display: grid;
  grid-template-columns: 1fr 1.2fr;
  gap: 60px;
  margin-top: 60px;
}
.contact-info-side { display: flex; flex-direction: column; gap: 20px; }
.info-card {
  background: var(--navy2);
  border: 1px solid rgba(255,255,255,0.07);
  border-radius: 12px;
  padding: 24px;
  display: flex;
  align-items: flex-start;
  gap: 16px;
  transition: var(--transition);
}
.info-card:hover { border-color: rgba(245,197,24,0.3); transform: translateX(4px); }
.info-card-icon {
  width: 50px; height: 50px;
  border-radius: 10px;
  display: flex; align-items: center; justify-content: center;
  font-size: 20px;
  flex-shrink: 0;
}
.info-card-icon.r { background: rgba(212,43,43,0.2); color: var(--red); }
.info-card-icon.g { background: rgba(37,211,102,0.2); color: #25D366; }
.info-card-icon.b { background: rgba(26,58,107,0.3); color: var(--blue2); }
.info-card-icon.y { background: rgba(245,197,24,0.2); color: var(--yellow); }
.info-card h4 { font-family: var(--font-head); font-size: 14px; font-weight: 700; color: var(--gray); letter-spacing: 1px; text-transform: uppercase; margin-bottom: 4px; }
.info-card a, .info-card span { color: var(--white); text-decoration: none; font-weight: 600; font-size: 16px; }
.info-card a:hover { color: var(--yellow); }

.map-container {
  border-radius: 12px;
  overflow: hidden;
  border: 1px solid rgba(255,255,255,0.1);
  margin-top: 20px;
}
.map-container iframe {
  width: 100%;
  height: 250px;
  border: none;
  display: block;
}

/* ── FORM ── */
.form-card {
  background: var(--navy2);
  border: 1px solid rgba(255,255,255,0.07);
  border-radius: 16px;
  padding: 40px;
}
.form-title {
  font-family: var(--font-head);
  font-size: 28px;
  font-weight: 800;
  color: var(--white);
  margin-bottom: 28px;
  display: flex; align-items: center; gap: 10px;
}
.form-title i { color: var(--red); }

.form-group { margin-bottom: 20px; }
.form-group label {
  display: block;
  font-size: 13px;
  font-weight: 600;
  color: var(--gray2);
  letter-spacing: 0.5px;
  margin-bottom: 8px;
  text-transform: uppercase;
}
.form-control {
  width: 100%;
  background: rgba(255,255,255,0.05);
  border: 1px solid rgba(255,255,255,0.12);
  border-radius: 8px;
  padding: 12px 16px;
  color: var(--white);
  font-family: var(--font-body);
  font-size: 15px;
  transition: var(--transition);
  outline: none;
  -webkit-appearance: none;
}
.form-control:focus { border-color: var(--blue2); background: rgba(30,72,144,0.1); }
.form-control::placeholder { color: var(--gray); }
select.form-control option { background: var(--navy); }
textarea.form-control { resize: vertical; min-height: 120px; }
.form-row { display: grid; grid-template-columns: 1fr 1fr; gap: 16px; }

.form-success {
  display: none;
  text-align: center;
  padding: 40px;
}
.form-success i { font-size: 56px; color: #25D366; margin-bottom: 16px; }
.form-success h3 { font-family: var(--font-head); font-size: 26px; font-weight: 800; color: var(--white); margin-bottom: 10px; }
.form-success p { color: var(--gray); }

/* ── CAREERS ── */
.careers-hero {
  background: linear-gradient(135deg, var(--dark) 0%, var(--navy3) 100%);
  padding: 120px 0 80px;
  text-align: center;
  position: relative;
  overflow: hidden;
}
.careers-hero::before {
  content: 'HIRING';
  position: absolute;
  font-family: var(--font-head);
  font-size: 200px;
  font-weight: 900;
  color: rgba(255,255,255,0.03);
  top: 50%;
  left: 50%;
  transform: translate(-50%,-50%);
  letter-spacing: 20px;
  pointer-events: none;
}

.positions-grid {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 20px;
  margin: 60px 0 40px;
}
.position-card {
  background: var(--navy2);
  border: 1px solid rgba(255,255,255,0.07);
  border-radius: 12px;
  padding: 24px;
  transition: var(--transition);
  cursor: pointer;
}
.position-card:hover, .position-card.selected { border-color: var(--red); background: rgba(212,43,43,0.05); }
.position-card h4 { font-family: var(--font-head); font-size: 18px; font-weight: 800; color: var(--white); margin-bottom: 8px; }
.position-card p { font-size: 13px; color: var(--gray); }
.position-tag {
  display: inline-block;
  background: var(--red);
  color: white;
  padding: 3px 10px;
  border-radius: 4px;
  font-size: 11px;
  font-weight: 700;
  letter-spacing: 1px;
  text-transform: uppercase;
  margin-bottom: 10px;
}

.upload-area {
  border: 2px dashed rgba(255,255,255,0.15);
  border-radius: 8px;
  padding: 32px;
  text-align: center;
  cursor: pointer;
  transition: var(--transition);
}
.upload-area:hover { border-color: var(--blue2); background: rgba(30,72,144,0.05); }
.upload-area i { font-size: 32px; color: var(--gray); margin-bottom: 12px; display: block; }
.upload-area p { color: var(--gray); font-size: 14px; }
.upload-area strong { color: var(--blue2); }
.upload-area input { display: none; }

/* ── TESTIMONIALS ── */
.testimonials-grid {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 24px;
  margin-top: 60px;
}
.testimonial-card {
  background: var(--navy2);
  border: 1px solid rgba(255,255,255,0.07);
  border-radius: 16px;
  padding: 32px;
  transition: var(--transition);
  position: relative;
}
.testimonial-card:hover { transform: translateY(-4px); border-color: rgba(245,197,24,0.2); }
.testimonial-card::before {
  content: '"';
  font-family: var(--font-head);
  font-size: 80px;
  color: rgba(245,197,24,0.15);
  position: absolute;
  top: 10px; left: 24px;
  line-height: 1;
}
.stars { color: var(--yellow); font-size: 14px; margin-bottom: 16px; }
.testimonial-text { color: var(--gray2); font-size: 15px; line-height: 1.7; margin-bottom: 24px; position: relative; }
.testimonial-author { display: flex; align-items: center; gap: 14px; }
.author-avatar {
  width: 48px; height: 48px;
  border-radius: 50%;
  background: linear-gradient(135deg, var(--blue), var(--blue2));
  display: flex; align-items: center; justify-content: center;
  font-family: var(--font-head);
  font-size: 18px;
  font-weight: 800;
  color: white;
  flex-shrink: 0;
}
.author-name { font-weight: 700; color: var(--white); font-size: 15px; }
.author-loc { font-size: 12px; color: var(--gray); }

/* ── FAQ ── */
.faq-list { margin-top: 60px; max-width: 900px; }
.faq-item {
  border-bottom: 1px solid rgba(255,255,255,0.08);
}
.faq-question {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 24px 0;
  cursor: pointer;
  gap: 20px;
}
.faq-question h3 {
  font-family: var(--font-head);
  font-size: 20px;
  font-weight: 700;
  color: var(--white);
  flex: 1;
}
.faq-question .icon {
  width: 32px; height: 32px;
  background: var(--blue);
  border-radius: 50%;
  display: flex; align-items: center; justify-content: center;
  color: var(--white);
  font-size: 14px;
  flex-shrink: 0;
  transition: var(--transition);
}
.faq-item.open .faq-question .icon { background: var(--red); transform: rotate(45deg); }
.faq-answer {
  max-height: 0;
  overflow: hidden;
  transition: max-height 0.4s ease;
}
.faq-answer-inner {
  padding: 0 0 24px;
  color: var(--gray);
  font-size: 16px;
  line-height: 1.8;
}
.faq-item.open .faq-answer { max-height: 300px; }

/* ── CTA BAND ── */
.cta-band {
  background: linear-gradient(135deg, var(--red) 0%, var(--red2) 100%);
  padding: 80px 0;
  text-align: center;
  position: relative;
  overflow: hidden;
}
.cta-band::before {
  content: '';
  position: absolute;
  inset: 0;
  background: repeating-linear-gradient(90deg, transparent, transparent 60px, rgba(255,255,255,0.04) 60px, rgba(255,255,255,0.04) 62px);
}
.cta-band h2 {
  font-family: var(--font-head);
  font-size: clamp(32px, 5vw, 56px);
  font-weight: 900;
  color: white;
  margin-bottom: 16px;
  position: relative;
}
.cta-band p { color: rgba(255,255,255,0.8); font-size: 18px; margin-bottom: 32px; position: relative; }
.cta-band .btn-white {
  display: inline-flex; align-items: center; gap: 10px;
  background: white;
  color: var(--red);
  padding: 16px 32px;
  border-radius: 6px;
  font-family: var(--font-head);
  font-size: 18px;
  font-weight: 800;
  text-decoration: none;
  transition: var(--transition);
  margin: 8px;
  position: relative;
}
.cta-band .btn-white:hover { transform: translateY(-2px); box-shadow: 0 8px 24px rgba(0,0,0,0.2); }
.cta-band .btn-dark {
  display: inline-flex; align-items: center; gap: 10px;
  background: rgba(0,0,0,0.3);
  border: 2px solid rgba(255,255,255,0.5);
  color: white;
  padding: 14px 30px;
  border-radius: 6px;
  font-family: var(--font-head);
  font-size: 18px;
  font-weight: 800;
  text-decoration: none;
  transition: var(--transition);
  margin: 8px;
  position: relative;
}
.cta-band .btn-dark:hover { background: rgba(0,0,0,0.5); transform: translateY(-2px); }

/* ── FOOTER ── */
footer {
  background: var(--dark);
  border-top: 3px solid var(--blue);
  padding: 80px 0 0;
}
.footer-grid {
  display: grid;
  grid-template-columns: 2fr 1fr 1fr 1.5fr;
  gap: 48px;
  padding-bottom: 60px;
}
.footer-brand .logo { display: flex; align-items: center; gap: 12px; margin-bottom: 20px; }
.footer-brand .logo-icon {
  width: 48px; height: 48px;
  background: var(--red);
  border-radius: 8px;
  display: flex; align-items: center; justify-content: center;
  font-size: 22px;
  color: white;
}
.footer-brand .logo-text .b { font-family: var(--font-head); font-size: 16px; font-weight: 800; color: var(--white); }
.footer-brand .logo-text .t { font-size: 10px; color: var(--yellow); letter-spacing: 1.5px; text-transform: uppercase; font-weight: 600; }
.footer-brand p { color: var(--gray); font-size: 14px; line-height: 1.7; margin-bottom: 20px; max-width: 300px; }
.social-links { display: flex; gap: 10px; }
.social-link {
  width: 38px; height: 38px;
  background: rgba(255,255,255,0.07);
  border-radius: 8px;
  display: flex; align-items: center; justify-content: center;
  color: var(--gray);
  text-decoration: none;
  font-size: 15px;
  transition: var(--transition);
}
.social-link:hover { background: var(--blue2); color: white; }

.footer-col h4 {
  font-family: var(--font-head);
  font-size: 16px;
  font-weight: 800;
  color: var(--white);
  letter-spacing: 0.5px;
  margin-bottom: 20px;
  padding-bottom: 10px;
  border-bottom: 2px solid var(--red);
  display: inline-block;
}
.footer-links { list-style: none; display: flex; flex-direction: column; gap: 10px; }
.footer-links a {
  color: var(--gray);
  text-decoration: none;
  font-size: 14px;
  transition: var(--transition);
  display: flex;
  align-items: center;
  gap: 8px;
  cursor: pointer;
}
.footer-links a:hover { color: var(--yellow); padding-left: 4px; }
.footer-links a::before { content: '→'; font-size: 12px; }

.footer-contact-item { display: flex; align-items: flex-start; gap: 12px; margin-bottom: 16px; }
.footer-contact-item i { color: var(--red); margin-top: 3px; width: 16px; }
.footer-contact-item a, .footer-contact-item span { color: var(--gray); text-decoration: none; font-size: 14px; }
.footer-contact-item a:hover { color: var(--yellow); }

.footer-bottom {
  border-top: 1px solid rgba(255,255,255,0.07);
  padding: 24px 0;
  display: flex;
  justify-content: space-between;
  align-items: center;
  flex-wrap: wrap;
  gap: 12px;
}
.footer-bottom p { color: var(--gray); font-size: 13px; }
.footer-bottom .emergency-badge {
  display: flex; align-items: center; gap: 8px;
  background: var(--red);
  color: white;
  padding: 6px 14px;
  border-radius: 40px;
  font-size: 13px;
  font-weight: 700;
  text-decoration: none;
}
.footer-stripe {
  height: 6px;
  background: repeating-linear-gradient(90deg, var(--yellow) 0, var(--yellow) 30px, var(--dark) 30px, var(--dark) 60px);
}

/* ── FLOATING BTN ── */
.float-btns {
  position: fixed;
  bottom: 30px;
  right: 24px;
  display: flex;
  flex-direction: column;
  gap: 12px;
  z-index: 900;
}
.float-btn {
  width: 54px; height: 54px;
  border-radius: 50%;
  display: flex; align-items: center; justify-content: center;
  font-size: 22px;
  text-decoration: none;
  color: white;
  box-shadow: 0 4px 16px rgba(0,0,0,0.4);
  transition: var(--transition);
}
.float-btn:hover { transform: scale(1.1) translateY(-2px); }
.float-btn.wa { background: #25D366; }
.float-btn.call { background: var(--red); animation: pulse-red 2s infinite; }

/* ── PAGE BANNER ── */
.page-banner {
  background: linear-gradient(135deg, var(--dark) 0%, var(--navy2) 100%);
  padding: 140px 0 70px;
  text-align: center;
  position: relative;
  overflow: hidden;
  border-bottom: 3px solid var(--blue);
}
.page-banner::before {
  content: '';
  position: absolute;
  inset: 0;
  background: repeating-linear-gradient(135deg, transparent, transparent 40px, rgba(255,255,255,0.01) 40px, rgba(255,255,255,0.01) 41px);
}
.page-banner h1 {
  font-family: var(--font-head);
  font-size: clamp(40px, 6vw, 72px);
  font-weight: 900;
  color: var(--white);
  position: relative;
  margin-bottom: 12px;
}
.page-banner p { color: var(--gray2); font-size: 18px; position: relative; max-width: 600px; margin: 0 auto; }
.breadcrumb {
  display: flex; justify-content: center; align-items: center; gap: 8px;
  margin-bottom: 20px;
  position: relative;
}
.breadcrumb span { color: var(--gray); font-size: 13px; cursor: pointer; transition: var(--transition); }
.breadcrumb span:hover { color: var(--yellow); }
.breadcrumb .sep { color: var(--gray); font-size: 13px; }
.breadcrumb .current { color: var(--yellow); font-weight: 600; }

/* ── SCROLL ANIMATIONS ── */
.reveal {
  opacity: 0;
  transform: translateY(30px);
  transition: opacity 0.6s ease, transform 0.6s ease;
}
.reveal.visible {
  opacity: 1;
  transform: translateY(0);
}
.reveal-left { opacity: 0; transform: translateX(-30px); transition: opacity 0.6s ease, transform 0.6s ease; }
.reveal-left.visible { opacity: 1; transform: translateX(0); }
.reveal-right { opacity: 0; transform: translateX(30px); transition: opacity 0.6s ease, transform 0.6s ease; }
.reveal-right.visible { opacity: 1; transform: translateX(0); }

/* ── RESPONSIVE ── */
@media (max-width: 1024px) {
  .hero-content { grid-template-columns: 1fr; }
  .hero-card { max-width: 500px; }
  .why-grid { grid-template-columns: repeat(2, 1fr); }
  .services-grid { grid-template-columns: repeat(2, 1fr); }
  .founder-section { grid-template-columns: 1fr; }
  .founder-img-wrap { display: none; }
  .values-grid { grid-template-columns: repeat(3, 1fr); }
  .footer-grid { grid-template-columns: 1fr 1fr; }
  .positions-grid { grid-template-columns: repeat(2, 1fr); }
}

@media (max-width: 768px) {
  .nav-links, .nav-cta { display: none; }
  .hamburger { display: flex; }
  .hero-content { gap: 40px; padding: 60px 24px 80px; }
  .why-grid { grid-template-columns: 1fr; }
  .services-grid { grid-template-columns: 1fr; }
  .contact-grid { grid-template-columns: 1fr; }
  .mission-vision { grid-template-columns: 1fr; }
  .values-grid { grid-template-columns: repeat(2, 1fr); }
  .testimonials-grid { grid-template-columns: 1fr; }
  .footer-grid { grid-template-columns: 1fr; }
  .footer-bottom { flex-direction: column; text-align: center; }
  .form-row { grid-template-columns: 1fr; }
  .positions-grid { grid-template-columns: 1fr; }
  .section { padding: 70px 0; }
}

@media (max-width: 480px) {
  .hero-btns { flex-direction: column; }
  .hero-btns a, .hero-btns button { width: 100%; justify-content: center; }
  .values-grid { grid-template-columns: 1fr 1fr; }
}
</style>
</head>
<body>

<!-- ══ NAVBAR ══ -->
<nav id="navbar">
  <div class="nav-inner">
    <a class="nav-logo" onclick="showPage('home')">
      <div class="nav-logo-icon"><i class="fas fa-truck-tow"></i></div>
      <div class="nav-logo-text">
        <span class="brand">All Roads Towing</span>
        <span class="tagline">Accident Recovery Specialists</span>
      </div>
    </a>
    <ul class="nav-links">
      <li><a onclick="showPage('home')" id="nav-home">Home</a></li>
      <li><a onclick="showPage('services')" id="nav-services">Services</a></li>
      <li><a onclick="showPage('about')" id="nav-about">About</a></li>
      <li><a onclick="showPage('testimonials')" id="nav-testimonials">Reviews</a></li>
      <li><a onclick="showPage('faq')" id="nav-faq">FAQ</a></li>
      <li><a onclick="showPage('careers')" id="nav-careers">Careers</a></li>
      <li><a onclick="showPage('contact')" id="nav-contact">Contact</a></li>
    </ul>
    <div class="nav-cta">
      <a class="btn-call" href="tel:+12628447838"><i class="fas fa-phone"></i> Call Now</a>
    </div>
    <button class="hamburger" id="hamburger" onclick="toggleMenu()">
      <span></span><span></span><span></span>
    </button>
  </div>
</nav>

<!-- Mobile Menu -->
<div class="mobile-menu" id="mobileMenu">
  <a onclick="showPage('home');closeMenu()">Home</a>
  <a onclick="showPage('services');closeMenu()">Services</a>
  <a onclick="showPage('about');closeMenu()">About Us</a>
  <a onclick="showPage('testimonials');closeMenu()">Reviews</a>
  <a onclick="showPage('faq');closeMenu()">FAQ</a>
  <a onclick="showPage('careers');closeMenu()">Careers</a>
  <a onclick="showPage('contact');closeMenu()">Contact</a>
  <a class="m-call" href="tel:+12628447838"><i class="fas fa-phone"></i> +1 (262) 844-7838</a>
</div>

<!-- ══════════════════════════════
     PAGE: HOME
══════════════════════════════ -->
<div class="page active" id="page-home">

  <!-- HERO -->
  <section class="hero">
    <div class="hero-bg"></div>
    <div class="hero-pattern"></div>
    <div class="hero-content container">
      <div>
        <div class="hero-badge"><span class="dot"></span> 24/7 Emergency Service Available</div>
        <h1>Fast, Reliable<br><em>Towing</em> &<br><span>Accident Recovery</span></h1>
        <p class="hero-sub">Serving Wisconsin Dells and surrounding communities with professional towing, roadside assistance, and emergency accident recovery services.</p>
        <div class="hero-btns">
          <a class="btn-primary" href="tel:+12628447838"><i class="fas fa-phone"></i> Call Now</a>
          <a class="btn-whatsapp" href="https://wa.me/12628447838" target="_blank"><i class="fab fa-whatsapp"></i> WhatsApp Us</a>
          <button class="btn-secondary" onclick="showPage('contact')"><i class="fas fa-location-dot"></i> Request Assistance</button>
        </div>
        <div class="hero-stats">
          <div class="hero-stat"><div class="num">24/7</div><div class="lbl">Always Available</div></div>
          <div class="hero-stat"><div class="num">30<small style="font-size:20px">min</small></div><div class="lbl">Avg Response</div></div>
          <div class="hero-stat"><div class="num">100%</div><div class="lbl">Licensed & Insured</div></div>
          <div class="hero-stat"><div class="num">500+</div><div class="lbl">Happy Customers</div></div>
        </div>
      </div>
      <div class="hero-card">
        <div class="hero-card-title"><i class="fas fa-headset"></i> Get Help Now</div>
        <div class="contact-item">
          <div class="contact-icon phone"><i class="fas fa-phone"></i></div>
          <div class="contact-info">
            <strong>Emergency Line</strong>
            <a href="tel:+12628447838">+1 (262) 844-7838</a>
          </div>
        </div>
        <div class="contact-item">
          <div class="contact-icon wa"><i class="fab fa-whatsapp"></i></div>
          <div class="contact-info">
            <strong>WhatsApp</strong>
            <a href="https://wa.me/12628447838" target="_blank">+1 (262) 844-7838</a>
          </div>
        </div>
        <div class="contact-item">
          <div class="contact-icon mail"><i class="fas fa-envelope"></i></div>
          <div class="contact-info">
            <strong>Email Us</strong>
            <a href="mailto:wentzrichard353@gmail.com">wentzrichard353@gmail.com</a>
          </div>
        </div>
        <div class="contact-item">
          <div class="contact-icon clock"><i class="fas fa-clock"></i></div>
          <div class="contact-info">
            <strong>Business Hours</strong>
            <span>24 Hours / 7 Days a Week</span>
          </div>
        </div>
        <button class="btn-primary" style="width:100%;margin-top:16px;justify-content:center;" onclick="showPage('contact')">
          <i class="fas fa-location-dot"></i> Request Assistance
        </button>
      </div>
    </div>
    <div class="hero-stripe"></div>
  </section>

  <!-- WHY CHOOSE US -->
  <section class="section">
    <div class="container">
      <div class="reveal">
        <div class="section-label">Why Choose Us</div>
        <h2 class="section-title">Wisconsin Dells' Most <em>Trusted</em> Towing Company</h2>
        <p class="section-sub">When you're stranded on the side of the road, you need a team you can count on. Here's what sets All Roads Towing apart.</p>
      </div>
      <div class="why-grid">
        <div class="why-card reveal"><div class="why-icon"><i class="fas fa-bolt"></i></div><h3>Lightning Fast Response</h3><p>Our strategically positioned fleet means we reach you faster. Average response time under 30 minutes throughout Wisconsin Dells and surrounding areas.</p></div>
        <div class="why-card reveal"><div class="why-icon"><i class="fas fa-clock"></i></div><h3>24/7 Emergency Support</h3><p>Accidents and breakdowns don't follow business hours. We're available around the clock, every single day including holidays.</p></div>
        <div class="why-card reveal"><div class="why-icon"><i class="fas fa-user-tie"></i></div><h3>Professional Operators</h3><p>Our certified drivers and technicians bring years of experience to every job, handling your vehicle with care and professionalism.</p></div>
        <div class="why-card reveal"><div class="why-icon"><i class="fas fa-shield-halved"></i></div><h3>Licensed & Insured</h3><p>Fully licensed and comprehensively insured, giving you complete peace of mind that your vehicle is in safe, protected hands.</p></div>
        <div class="why-card reveal"><div class="why-icon"><i class="fas fa-car-burst"></i></div><h3>Reliable Accident Recovery</h3><p>From minor fender benders to major multi-vehicle accidents, our specialized recovery equipment handles any situation safely and efficiently.</p></div>
        <div class="why-card reveal"><div class="why-icon"><i class="fas fa-heart"></i></div><h3>Customer-First Approach</h3><p>We understand you're in a stressful situation. Our team goes the extra mile to make the experience as smooth and stress-free as possible.</p></div>
      </div>
    </div>
  </section>

  <!-- FOUNDER -->
  <section class="section section-dark">
    <div class="container">
      <div class="founder-section">
        <div class="founder-img-wrap reveal-left">
          <img src="https://images.unsplash.com/photo-1507003211169-0a1dd7228f2d?w=600&q=80" alt="Rick Wentz - Founder">
          <div class="founder-badge">
            <span class="big">15+</span>
            Years of Experience
          </div>
        </div>
        <div class="founder-content reveal-right">
          <div class="section-label">Meet the Founder</div>
          <h2 class="founder-name">Rick Wentz</h2>
          <p class="founder-title">Founder & Lead Recovery Specialist</p>
          <p>Founded by Rick Wentz, All Roads Towing Accident Recovery Specialists is dedicated to helping drivers get back on the road quickly and safely. Rick built this company on the belief that every stranded motorist deserves a fast, professional, and compassionate response.</p>
          <p>With over 15 years in the towing and recovery industry, Rick has personally responded to thousands of calls across Wisconsin. His hands-on experience, combined with a deep commitment to his community, drives the culture of excellence at All Roads Towing.</p>
          <p>Under Rick's leadership, All Roads Towing has grown into Wisconsin Dells' most trusted emergency response team, handling everything from simple lockouts to complex multi-vehicle accident recoveries.</p>
          <div style="display:flex;gap:16px;flex-wrap:wrap;margin-top:8px;">
            <a class="btn-primary" href="tel:+12628447838"><i class="fas fa-phone"></i> Call Rick's Team</a>
            <button class="btn-secondary" onclick="showPage('about')"><i class="fas fa-arrow-right"></i> Our Full Story</button>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- SERVICES PREVIEW -->
  <section class="section section-alt">
    <div class="container">
      <div class="reveal" style="text-align:center;margin-bottom:0;">
        <div class="section-label" style="justify-content:center;">Our Services</div>
        <h2 class="section-title">Complete Towing & <em>Recovery</em> Solutions</h2>
        <p class="section-sub" style="margin:0 auto 0;">From basic roadside assistance to complex accident recovery — we handle it all.</p>
      </div>
      <div class="services-grid">
        <div class="service-card reveal"><div class="service-icon"><i class="fas fa-truck-tow"></i></div><h3>Emergency Towing</h3><p>24/7 emergency towing for all vehicle types. Fast dispatch, professional handling.</p><button class="btn-sm" onclick="showPage('services')">Learn More <i class="fas fa-arrow-right"></i></button></div>
        <div class="service-card reveal"><div class="service-icon"><i class="fas fa-car-burst"></i></div><h3>Accident Recovery</h3><p>Specialized equipment for safe, efficient vehicle recovery after accidents.</p><button class="btn-sm" onclick="showPage('services')">Learn More <i class="fas fa-arrow-right"></i></button></div>
        <div class="service-card reveal"><div class="service-icon"><i class="fas fa-road"></i></div><h3>Roadside Assistance</h3><p>Flat tires, jump starts, fuel delivery, lockouts — we've got you covered.</p><button class="btn-sm" onclick="showPage('services')">Learn More <i class="fas fa-arrow-right"></i></button></div>
      </div>
      <div style="text-align:center;margin-top:40px;">
        <button class="btn-primary" onclick="showPage('services')"><i class="fas fa-list"></i> View All 12 Services</button>
      </div>
    </div>
  </section>

  <!-- CTA -->
  <div class="cta-band">
    <div class="container">
      <h2>Stranded? We're On Our Way.</h2>
      <p>Available 24 hours a day, 7 days a week — including holidays. Don't wait, call now.</p>
      <a class="btn-white" href="tel:+12628447838"><i class="fas fa-phone"></i> +1 (262) 844-7838</a>
      <a class="btn-dark" href="https://wa.me/12628447838" target="_blank"><i class="fab fa-whatsapp"></i> WhatsApp Us</a>
    </div>
  </div>

</div><!-- /home -->


<!-- ══════════════════════════════
     PAGE: SERVICES
══════════════════════════════ -->
<div class="page" id="page-services">
  <div class="page-banner">
    <div class="container">
      <div class="breadcrumb"><span onclick="showPage('home')">Home</span><span class="sep">/</span><span class="current">Services</span></div>
      <h1>Our <span style="color:var(--yellow)">Services</span></h1>
      <p>Professional towing, roadside assistance, and accident recovery services available 24/7 across Wisconsin Dells and surrounding areas.</p>
    </div>
  </div>
  <section class="section">
    <div class="container">
      <div class="services-grid">
        <div class="service-card reveal">
          <div class="service-icon"><i class="fas fa-truck-tow"></i></div>
          <h3>Emergency Towing</h3>
          <p>When your vehicle breaks down unexpectedly, our emergency towing service dispatches immediately. We tow all makes and models safely to your preferred location.</p>
          <ul class="service-benefits"><li>Fast 24/7 dispatch</li><li>All vehicle types</li><li>Safe & secure transport</li><li>Competitive flat rates</li></ul>
          <a class="btn-sm" href="tel:+12628447838"><i class="fas fa-phone"></i> Call for Emergency Tow</a>
        </div>
        <div class="service-card reveal">
          <div class="service-icon"><i class="fas fa-car-burst"></i></div>
          <h3>Accident Recovery</h3>
          <p>Specialized accident recovery operations using heavy-duty equipment. We work efficiently to clear scenes safely and recover vehicles from all crash scenarios.</p>
          <ul class="service-benefits"><li>Multi-vehicle recovery</li><li>Heavy-duty equipment</li><li>Scene safety first</li><li>Insurance coordination</li></ul>
          <a class="btn-sm" href="tel:+12628447838"><i class="fas fa-phone"></i> Emergency Recovery</a>
        </div>
        <div class="service-card reveal">
          <div class="service-icon"><i class="fas fa-road"></i></div>
          <h3>Roadside Assistance</h3>
          <p>Comprehensive roadside support including tire changes, jump starts, fuel delivery, and more. We come to you so you don't have to be stranded for long.</p>
          <ul class="service-benefits"><li>Quick on-site service</li><li>Multiple services offered</li><li>Affordable pricing</li><li>Professional technicians</li></ul>
          <a class="btn-sm" href="tel:+12628447838"><i class="fas fa-phone"></i> Get Roadside Help</a>
        </div>
        <div class="service-card reveal">
          <div class="service-icon"><i class="fas fa-circle-dot"></i></div>
          <h3>Flat Tire Assistance</h3>
          <p>Got a flat? Our technicians arrive quickly to mount your spare or arrange transport to the nearest tire shop. Safe and efficient tire change service.</p>
          <ul class="service-benefits"><li>Spare tire mounting</li><li>Tire repair assessment</li><li>Transport to tire shop</li><li>All terrain vehicles</li></ul>
          <a class="btn-sm" href="tel:+12628447838"><i class="fas fa-phone"></i> Flat Tire Help</a>
        </div>
        <div class="service-card reveal">
          <div class="service-icon"><i class="fas fa-battery-full"></i></div>
          <h3>Jump-Start Service</h3>
          <p>Dead battery? We provide professional jump-start service with professional-grade equipment. If needed, we can transport your vehicle to the nearest service center.</p>
          <ul class="service-benefits"><li>Professional jump packs</li><li>Battery testing on-site</li><li>Safe for modern vehicles</li><li>Quick arrival times</li></ul>
          <a class="btn-sm" href="tel:+12628447838"><i class="fas fa-phone"></i> Jump Start Now</a>
        </div>
        <div class="service-card reveal">
          <div class="service-icon"><i class="fas fa-gas-pump"></i></div>
          <h3>Fuel Delivery</h3>
          <p>Ran out of gas? We deliver the fuel you need directly to your location. Available 24/7 so you can get back on the road without delay.</p>
          <ul class="service-benefits"><li>Gas & diesel available</li><li>Delivered to your location</li><li>24/7 availability</li><li>Fast response</li></ul>
          <a class="btn-sm" href="tel:+12628447838"><i class="fas fa-phone"></i> Request Fuel Delivery</a>
        </div>
        <div class="service-card reveal">
          <div class="service-icon"><i class="fas fa-key"></i></div>
          <h3>Vehicle Lockout Service</h3>
          <p>Locked your keys in your car? Our professionals arrive fast and use proper tools to get you back in your vehicle without damage.</p>
          <ul class="service-benefits"><li>All vehicle types</li><li>No-damage methods</li><li>Fast response</li><li>Available 24/7</li></ul>
          <a class="btn-sm" href="tel:+12628447838"><i class="fas fa-phone"></i> Lockout Help</a>
        </div>
        <div class="service-card reveal">
          <div class="service-icon"><i class="fas fa-anchor"></i></div>
          <h3>Winch-Out Services</h3>
          <p>Vehicle stuck in mud, snow, or a ditch? Our winch-out service uses heavy-duty equipment to safely extract your vehicle from any difficult situation.</p>
          <ul class="service-benefits"><li>Mud & ditch recovery</li><li>Snow extraction</li><li>Off-road recovery</li><li>Heavy-duty winches</li></ul>
          <a class="btn-sm" href="tel:+12628447838"><i class="fas fa-phone"></i> Get Winch-Out</a>
        </div>
        <div class="service-card reveal">
          <div class="service-icon"><i class="fas fa-map-location-dot"></i></div>
          <h3>Long-Distance Towing</h3>
          <p>Need your vehicle transported across state or long distances? We provide safe, reliable long-distance towing with tracking and communication throughout.</p>
          <ul class="service-benefits"><li>Multi-state capability</li><li>Enclosed transport option</li><li>Real-time updates</li><li>Safe vehicle handling</li></ul>
          <a class="btn-sm" href="tel:+12628447838"><i class="fas fa-phone"></i> Long-Distance Quote</a>
        </div>
        <div class="service-card reveal">
          <div class="service-icon"><i class="fas fa-truck-monster"></i></div>
          <h3>Heavy-Duty Towing</h3>
          <p>Specialized heavy-duty towing for commercial trucks, buses, RVs, and construction equipment. Our heavy-duty rigs handle the big jobs professionally.</p>
          <ul class="service-benefits"><li>Semi-trucks & RVs</li><li>Construction equipment</li><li>Specialized rigging</li><li>Commercial vehicles</li></ul>
          <a class="btn-sm" href="tel:+12628447838"><i class="fas fa-phone"></i> Heavy-Duty Tow</a>
        </div>
        <div class="service-card reveal">
          <div class="service-icon"><i class="fas fa-motorcycle"></i></div>
          <h3>Motorcycle Towing</h3>
          <p>Specialized motorcycle towing with proper tie-down and cradle systems to ensure your bike is transported safely without damage to fairings or frame.</p>
          <ul class="service-benefits"><li>Proper cradle systems</li><li>No damage guarantee</li><li>All motorcycle types</li><li>Short & long distance</li></ul>
          <a class="btn-sm" href="tel:+12628447838"><i class="fas fa-phone"></i> Moto Towing</a>
        </div>
        <div class="service-card reveal">
          <div class="service-icon"><i class="fas fa-truck-front"></i></div>
          <h3>Vehicle Transport</h3>
          <p>Need to move a non-running or classic vehicle? Our vehicle transport service provides safe, enclosed or open transport for any vehicle type.</p>
          <ul class="service-benefits"><li>Classic car transport</li><li>Non-running vehicles</li><li>Dealer to dealer</li><li>Auction transport</li></ul>
          <a class="btn-sm" href="tel:+12628447838"><i class="fas fa-phone"></i> Transport Quote</a>
        </div>
      </div>
    </div>
  </section>
  <div class="cta-band">
    <div class="container">
      <h2>Need a Service Right Now?</h2>
      <p>Our team is standing by 24/7. One call is all it takes.</p>
      <a class="btn-white" href="tel:+12628447838"><i class="fas fa-phone"></i> +1 (262) 844-7838</a>
      <a class="btn-dark" href="https://wa.me/12628447838" target="_blank"><i class="fab fa-whatsapp"></i> WhatsApp</a>
    </div>
  </div>
</div><!-- /services -->


<!-- ══════════════════════════════
     PAGE: ABOUT
══════════════════════════════ -->
<div class="page" id="page-about">
  <div class="page-banner">
    <div class="container">
      <div class="breadcrumb"><span onclick="showPage('home')">Home</span><span class="sep">/</span><span class="current">About Us</span></div>
      <h1>About <span style="color:var(--yellow)">All Roads</span> Towing</h1>
      <p>Wisconsin Dells' trusted towing and accident recovery specialists — built on integrity, powered by purpose.</p>
    </div>
  </div>

  <section class="section">
    <div class="container">
      <div style="display:grid;grid-template-columns:1fr 1fr;gap:60px;align-items:center;">
        <div class="reveal-left">
          <div class="section-label">Our Story</div>
          <h2 class="section-title">Built on <em>Trust</em> and <span>Dedication</span></h2>
          <p style="color:var(--gray);line-height:1.8;margin-bottom:16px;">All Roads Towing Accident Recovery Specialists was founded with a single mission: to provide the people of Wisconsin Dells and surrounding communities with the fastest, most professional, and most reliable towing and recovery service available.</p>
          <p style="color:var(--gray);line-height:1.8;margin-bottom:16px;">What began as a one-truck operation has grown into a full-service towing and recovery company equipped to handle everything from simple lockouts to complex heavy-duty accident recoveries. Through every job, small or large, our commitment to quality and customer care has remained constant.</p>
          <p style="color:var(--gray);line-height:1.8;">We've built our reputation one rescue at a time — arriving quickly, treating every driver with respect, and handling every vehicle as if it were our own.</p>
        </div>
        <div class="reveal-right">
          <img src="https://images.unsplash.com/photo-1558618666-fcd25c85cd64?w=700&q=80" alt="All Roads Towing" style="width:100%;border-radius:16px;height:380px;object-fit:cover;">
        </div>
      </div>
    </div>
  </section>

  <!-- FOUNDER -->
  <section class="section section-dark">
    <div class="container">
      <div style="display:grid;grid-template-columns:1fr 1fr;gap:60px;align-items:center;">
        <div class="reveal-left">
          <div class="section-label">Founder</div>
          <h2 class="section-title">Meet <em>Rick</em> Wentz</h2>
          <p class="founder-title" style="color:var(--yellow);font-size:15px;letter-spacing:1px;text-transform:uppercase;font-weight:600;margin-bottom:20px;">Founder & Lead Recovery Specialist</p>
          <p style="color:var(--gray);line-height:1.8;margin-bottom:16px;">Rick Wentz has been in the towing and recovery industry for over 15 years. A Wisconsin native, Rick understands the unique challenges of driving in the Midwest — from harsh winters to rural highway emergencies.</p>
          <p style="color:var(--gray);line-height:1.8;margin-bottom:16px;">Rick founded All Roads Towing after seeing firsthand how poorly many stranded drivers were treated by impersonal, slow-responding towing services. He set out to build something different: a company where every driver is treated with urgency, respect, and genuine care.</p>
          <p style="color:var(--gray);line-height:1.8;">Today, Rick leads a team of certified professionals who share his passion for service and his commitment to the community of Wisconsin Dells.</p>
          <a class="btn-primary" style="margin-top:20px;display:inline-flex;" href="tel:+12628447838"><i class="fas fa-phone"></i> Speak with Rick's Team</a>
        </div>
        <div class="reveal-right" style="background:var(--navy2);border-radius:16px;padding:40px;border:1px solid rgba(255,255,255,0.07);">
          <h3 style="font-family:var(--font-head);font-size:22px;font-weight:800;color:var(--white);margin-bottom:24px;"><i class="fas fa-quote-left" style="color:var(--yellow);margin-right:10px;"></i>Rick's Personal Commitment</h3>
          <p style="color:var(--gray);font-size:17px;line-height:1.9;font-style:italic;margin-bottom:24px;">"When someone calls us, they're usually scared, stressed, or upset. My promise to every customer is that when we arrive, that feeling goes away. We take it from there. That's what All Roads Towing is all about."</p>
          <p style="font-family:var(--font-head);font-size:20px;font-weight:800;color:var(--yellow);">— Rick Wentz, Founder</p>
        </div>
      </div>
    </div>
  </section>

  <!-- MISSION & VISION -->
  <section class="section">
    <div class="container">
      <div style="text-align:center;" class="reveal">
        <div class="section-label" style="justify-content:center;">Our Purpose</div>
        <h2 class="section-title">Mission & <em>Vision</em></h2>
      </div>
      <div class="mission-vision reveal">
        <div class="mv-card mission">
          <h3><i class="fas fa-bullseye" style="margin-right:12px;"></i>Our Mission</h3>
          <p>To provide Wisconsin Dells and surrounding communities with the fastest, most reliable, and most professional towing and accident recovery services available — treating every customer with the urgency and respect they deserve during their most stressful moments on the road.</p>
        </div>
        <div class="mv-card vision">
          <h3><i class="fas fa-eye" style="margin-right:12px;"></i>Our Vision</h3>
          <p>To be recognized as Wisconsin's leading towing and accident recovery specialists — known for our rapid response, exceptional professionalism, and unwavering commitment to keeping drivers and communities safe on every road.</p>
        </div>
      </div>
    </div>
  </section>

  <!-- VALUES -->
  <section class="section section-alt">
    <div class="container">
      <div style="text-align:center;" class="reveal">
        <div class="section-label" style="justify-content:center;">What Drives Us</div>
        <h2 class="section-title">Our Core <em>Values</em></h2>
      </div>
      <div class="values-grid">
        <div class="value-card reveal"><div class="value-icon"><i class="fas fa-handshake"></i></div><h3>Reliability</h3><p>When we say we're coming, we're coming. Fast and on time, every time.</p></div>
        <div class="value-card reveal"><div class="value-icon"><i class="fas fa-shield-halved"></i></div><h3>Safety</h3><p>Safety of our customers, our team, and your vehicle is always the top priority.</p></div>
        <div class="value-card reveal"><div class="value-icon"><i class="fas fa-scale-balanced"></i></div><h3>Integrity</h3><p>Honest pricing, honest communication, and honest service — always.</p></div>
        <div class="value-card reveal"><div class="value-icon"><i class="fas fa-star"></i></div><h3>Professionalism</h3><p>Trained, certified operators who treat every job with expertise and care.</p></div>
        <div class="value-card reveal"><div class="value-icon"><i class="fas fa-heart"></i></div><h3>Customer Service</h3><p>We don't just tow cars — we support people in their most stressful moments.</p></div>
      </div>
    </div>
  </section>

  <div class="cta-band">
    <div class="container">
      <h2>Ready to Experience the Difference?</h2>
      <p>Join hundreds of satisfied customers across Wisconsin Dells.</p>
      <a class="btn-white" href="tel:+12628447838"><i class="fas fa-phone"></i> Call Now</a>
      <button class="btn-dark" onclick="showPage('contact')"><i class="fas fa-envelope"></i> Contact Us</button>
    </div>
  </div>
</div><!-- /about -->


<!-- ══════════════════════════════
     PAGE: CONTACT
══════════════════════════════ -->
<div class="page" id="page-contact">
  <div class="page-banner">
    <div class="container">
      <div class="breadcrumb"><span onclick="showPage('home')">Home</span><span class="sep">/</span><span class="current">Contact</span></div>
      <h1>Contact <span style="color:var(--yellow)">Us</span></h1>
      <p>Reach us any time — we're available 24/7 for all your towing and roadside assistance needs.</p>
    </div>
  </div>
  <section class="section">
    <div class="container">
      <div class="contact-grid">
        <div class="contact-info-side">
          <div class="info-card reveal"><div class="info-card-icon r"><i class="fas fa-phone"></i></div><div><h4>Emergency Line</h4><a href="tel:+12628447838">+1 (262) 844-7838</a></div></div>
          <div class="info-card reveal"><div class="info-card-icon g"><i class="fab fa-whatsapp"></i></div><div><h4>WhatsApp</h4><a href="https://wa.me/12628447838" target="_blank">+1 (262) 844-7838</a></div></div>
          <div class="info-card reveal"><div class="info-card-icon b"><i class="fas fa-envelope"></i></div><div><h4>Email</h4><a href="mailto:wentzrichard353@gmail.com">wentzrichard353@gmail.com</a></div></div>
          <div class="info-card reveal"><div class="info-card-icon y"><i class="fas fa-clock"></i></div><div><h4>Hours</h4><span>24 Hours / 7 Days a Week</span></div></div>
          <div class="info-card reveal"><div class="info-card-icon r"><i class="fas fa-location-dot"></i></div><div><h4>Location</h4><span>Wisconsin Dells, Wisconsin, USA</span></div></div>
          <div class="map-container reveal">
            <iframe src="https://maps.google.com/maps?q=Wisconsin+Dells,+Wisconsin&output=embed" allowfullscreen loading="lazy"></iframe>
          </div>
        </div>
        <div class="form-card reveal">
          <div class="form-title"><i class="fas fa-location-dot"></i> Request Assistance</div>
          <div id="contactSuccess" class="form-success">
            <i class="fas fa-circle-check"></i>
            <h3>Message Sent!</h3>
            <p>Thank you for contacting All Roads Towing. Our team will respond as soon as possible. For emergencies, please call <a href="tel:+12628447838" style="color:var(--yellow);">+1 (262) 844-7838</a> immediately.</p>
          </div>
          <form id="contactForm" onsubmit="submitContact(event)">
            <div class="form-row">
              <div class="form-group"><label>Full Name *</label><input type="text" class="form-control" placeholder="Your full name" required></div>
              <div class="form-group"><label>Email *</label><input type="email" class="form-control" placeholder="your@email.com" required></div>
            </div>
            <div class="form-row">
              <div class="form-group"><label>Phone Number *</label><input type="tel" class="form-control" placeholder="+1 (000) 000-0000" required></div>
              <div class="form-group"><label>Vehicle Type</label><input type="text" class="form-control" placeholder="e.g. 2019 Honda Civic"></div>
            </div>
            <div class="form-group"><label>Service Needed</label>
              <select class="form-control">
                <option value="">Select a service...</option>
                <option>Emergency Towing</option>
                <option>Accident Recovery</option>
                <option>Roadside Assistance</option>
                <option>Flat Tire Assistance</option>
                <option>Jump-Start Service</option>
                <option>Fuel Delivery</option>
                <option>Vehicle Lockout</option>
                <option>Winch-Out Service</option>
                <option>Long-Distance Towing</option>
                <option>Heavy-Duty Towing</option>
                <option>Motorcycle Towing</option>
                <option>Vehicle Transport</option>
              </select>
            </div>
            <div class="form-group"><label>Current Location *</label><input type="text" class="form-control" placeholder="Street address, highway, or landmark" required></div>
            <div class="form-group"><label>Message / Additional Details</label><textarea class="form-control" placeholder="Describe your situation or any additional details that may help us assist you better..."></textarea></div>
            <button type="submit" class="btn-primary" style="width:100%;justify-content:center;font-size:17px;padding:16px;"><i class="fas fa-paper-plane"></i> Send Request</button>
          </form>
        </div>
      </div>
    </div>
  </section>
</div><!-- /contact -->


<!-- ══════════════════════════════
     PAGE: CAREERS
══════════════════════════════ -->
<div class="page" id="page-careers">
  <div class="careers-hero">
    <div class="container">
      <div class="section-label" style="justify-content:center;margin-bottom:12px;">Join Our Team</div>
      <h1 style="font-family:var(--font-head);font-size:clamp(40px,6vw,72px);font-weight:900;color:var(--white);margin-bottom:16px;">Drive Your <span style="color:var(--yellow)">Career</span> Forward</h1>
      <p style="font-size:18px;color:var(--gray2);max-width:600px;margin:0 auto;">Be part of Wisconsin Dells' most trusted towing and recovery team. We're looking for dedicated professionals who are passionate about helping people.</p>
    </div>
  </div>

  <section class="section">
    <div class="container">
      <div style="text-align:center;" class="reveal">
        <div class="section-label" style="justify-content:center;">Open Positions</div>
        <h2 class="section-title">Current <em>Openings</em></h2>
      </div>
      <div class="positions-grid">
        <div class="position-card reveal"><span class="position-tag">Full-Time</span><h4>Tow Truck Driver</h4><p>CDL preferred. Minimum 2 years driving experience. Clean record required.</p></div>
        <div class="position-card reveal"><span class="position-tag">Full-Time</span><h4>Recovery Specialist</h4><p>Experience in accident recovery and heavy-duty extraction. Certified preferred.</p></div>
        <div class="position-card reveal"><span class="position-tag">Full/Part-Time</span><h4>Roadside Technician</h4><p>Provide roadside assistance services. Mechanical background helpful.</p></div>
        <div class="position-card reveal"><span class="position-tag">Part-Time</span><h4>Dispatcher</h4><p>Coordinate service calls and communicate with field teams. Strong communication skills required.</p></div>
        <div class="position-card reveal"><span class="position-tag">Full-Time</span><h4>Heavy Equipment Operator</h4><p>Operate heavy-duty towing and recovery equipment. CDL required.</p></div>
        <div class="position-card reveal"><span class="position-tag">Open</span><h4>General Application</h4><p>Don't see your position? Submit a general application and we'll keep it on file.</p></div>
      </div>

      <div class="form-card reveal" style="margin-top:20px;">
        <div class="form-title"><i class="fas fa-file-alt"></i> Employment Application</div>

        <div id="careerSuccess" class="form-success">
          <i class="fas fa-circle-check"></i>
          <h3>Application Received!</h3>
          <p>Thank you for applying to All Roads Towing Accident Recovery Specialists. Our team will review your application and contact you soon.</p>
        </div>

        <form id="careerForm" onsubmit="submitCareer(event)">
          <h4 style="font-family:var(--font-head);font-size:18px;color:var(--yellow);margin-bottom:20px;padding-bottom:10px;border-bottom:1px solid rgba(255,255,255,0.08);">Personal Information</h4>
          <div class="form-row">
            <div class="form-group"><label>Full Name *</label><input type="text" class="form-control" placeholder="First and last name" required></div>
            <div class="form-group"><label>Email Address *</label><input type="email" class="form-control" placeholder="your@email.com" required></div>
          </div>
          <div class="form-row">
            <div class="form-group"><label>Phone Number *</label><input type="tel" class="form-control" placeholder="+1 (000) 000-0000" required></div>
            <div class="form-group"><label>Home Address</label><input type="text" class="form-control" placeholder="Street address"></div>
          </div>
          <div class="form-row">
            <div class="form-group"><label>City</label><input type="text" class="form-control" placeholder="City"></div>
            <div class="form-group"><label>State</label><input type="text" class="form-control" placeholder="State"></div>
          </div>
          <div class="form-group"><label>Zip Code</label><input type="text" class="form-control" placeholder="ZIP code" style="max-width:200px;"></div>

          <h4 style="font-family:var(--font-head);font-size:18px;color:var(--yellow);margin:32px 0 20px;padding-bottom:10px;border-bottom:1px solid rgba(255,255,255,0.08);">Employment Information</h4>
          <div class="form-row">
            <div class="form-group"><label>Desired Position *</label>
              <select class="form-control" required>
                <option value="">Select position...</option>
                <option>Tow Truck Driver</option>
                <option>Recovery Specialist</option>
                <option>Roadside Technician</option>
                <option>Dispatcher</option>
                <option>Heavy Equipment Operator</option>
                <option>General Application</option>
              </select>
            </div>
            <div class="form-group"><label>Years of Experience</label>
              <select class="form-control">
                <option>Less than 1 year</option>
                <option>1–2 years</option>
                <option>3–5 years</option>
                <option>5–10 years</option>
                <option>10+ years</option>
              </select>
            </div>
          </div>
          <div class="form-row">
            <div class="form-group"><label>Driver License Number</label><input type="text" class="form-control" placeholder="License number"></div>
            <div class="form-group"><label>CDL License</label>
              <select class="form-control">
                <option value="">Select...</option>
                <option>Yes — Class A CDL</option>
                <option>Yes — Class B CDL</option>
                <option>No CDL</option>
                <option>In Progress</option>
              </select>
            </div>
          </div>
          <div class="form-group"><label>Previous Employer</label><input type="text" class="form-control" placeholder="Most recent employer name"></div>
          <div class="form-group"><label>Skills</label><input type="text" class="form-control" placeholder="e.g. Heavy equipment operation, winching, roadside assistance..."></div>
          <div class="form-group"><label>Certifications</label><input type="text" class="form-control" placeholder="e.g. WreckMaster, TRAA, OSHA..."></div>
          <div class="form-group"><label>Availability</label>
            <select class="form-control">
              <option>Full-Time (Days)</option>
              <option>Full-Time (Nights)</option>
              <option>Full-Time (Any Shift)</option>
              <option>Part-Time</option>
              <option>Weekends Only</option>
              <option>Flexible</option>
            </select>
          </div>

          <h4 style="font-family:var(--font-head);font-size:18px;color:var(--yellow);margin:32px 0 20px;padding-bottom:10px;border-bottom:1px solid rgba(255,255,255,0.08);">Documents & Files</h4>
          <div class="form-group">
            <label>Resume / CV</label>
            <div class="upload-area" onclick="document.getElementById('resumeUpload').click()">
              <input type="file" id="resumeUpload" accept=".pdf,.doc,.docx" onchange="showFileName(this,'resumeLabel')">
              <i class="fas fa-file-alt"></i>
              <p id="resumeLabel">Click to upload your <strong>Resume</strong><br><small>PDF, DOC, DOCX — max 10MB</small></p>
            </div>
          </div>
          <div class="form-row">
            <div class="form-group">
              <label>Driver's License Image</label>
              <div class="upload-area" onclick="document.getElementById('licenseUpload').click()">
                <input type="file" id="licenseUpload" accept="image/*,.pdf" onchange="showFileName(this,'licenseLabel')">
                <i class="fas fa-id-card"></i>
                <p id="licenseLabel">Upload <strong>License</strong><br><small>JPG, PNG, PDF</small></p>
              </div>
            </div>
            <div class="form-group">
              <label>Certifications</label>
              <div class="upload-area" onclick="document.getElementById('certsUpload').click()">
                <input type="file" id="certsUpload" accept=".pdf,image/*" multiple onchange="showFileName(this,'certsLabel')">
                <i class="fas fa-certificate"></i>
                <p id="certsLabel">Upload <strong>Certificates</strong><br><small>Multiple files OK</small></p>
              </div>
            </div>
          </div>
          <div class="form-group">
            <label>Cover Letter (Optional)</label>
            <div class="upload-area" onclick="document.getElementById('coverUpload').click()">
              <input type="file" id="coverUpload" accept=".pdf,.doc,.docx" onchange="showFileName(this,'coverLabel')">
              <i class="fas fa-envelope-open-text"></i>
              <p id="coverLabel">Upload <strong>Cover Letter</strong><br><small>PDF, DOC, DOCX</small></p>
            </div>
          </div>

          <h4 style="font-family:var(--font-head);font-size:18px;color:var(--yellow);margin:32px 0 20px;padding-bottom:10px;border-bottom:1px solid rgba(255,255,255,0.08);">Additional Questions</h4>
          <div class="form-group"><label>Why do you want to work with All Roads Towing? *</label><textarea class="form-control" placeholder="Tell us what motivates you to join our team..." required></textarea></div>
          <div class="form-group"><label>Describe your relevant experience</label><textarea class="form-control" placeholder="Detail your towing, recovery, or related experience..."></textarea></div>
          <div class="form-group"><label>Weekly Availability Schedule</label><textarea class="form-control" placeholder="e.g. Monday–Friday 7am–7pm, available weekends..."></textarea></div>

          <div style="display:flex;gap:16px;flex-wrap:wrap;margin-top:8px;">
            <button type="submit" class="btn-primary" style="flex:1;justify-content:center;padding:16px;font-size:17px;"><i class="fas fa-paper-plane"></i> Submit Application</button>
            <button type="button" class="btn-secondary" style="flex:1;justify-content:center;padding:14px;font-size:16px;" onclick="alert('Draft saved locally.')"><i class="fas fa-save"></i> Save Draft</button>
          </div>
        </form>
      </div>
    </div>
  </section>
</div><!-- /careers -->


<!-- ══════════════════════════════
     PAGE: TESTIMONIALS
══════════════════════════════ -->
<div class="page" id="page-testimonials">
  <div class="page-banner">
    <div class="container">
      <div class="breadcrumb"><span onclick="showPage('home')">Home</span><span class="sep">/</span><span class="current">Reviews</span></div>
      <h1>Customer <span style="color:var(--yellow)">Reviews</span></h1>
      <p>Don't take our word for it — hear from the hundreds of drivers we've helped across Wisconsin Dells.</p>
    </div>
  </div>
  <section class="section">
    <div class="container">
      <div style="text-align:center;margin-bottom:20px;" class="reveal">
        <div style="font-family:var(--font-head);font-size:72px;font-weight:900;color:var(--yellow);line-height:1;">4.9</div>
        <div class="stars" style="font-size:24px;margin-bottom:8px;">★★★★★</div>
        <p style="color:var(--gray);">Based on 500+ customer reviews across Google, Facebook & Yelp</p>
      </div>
      <div class="testimonials-grid">
        <div class="testimonial-card reveal">
          <div class="stars">★★★★★</div>
          <p class="testimonial-text">I had a blowout on I-90 at 11pm and was terrified. Rick's team arrived within 20 minutes, changed my spare, and made sure I got home safe. Absolutely incredible service. These guys are the real deal.</p>
          <div class="testimonial-author"><div class="author-avatar">SJ</div><div><div class="author-name">Sarah Johnson</div><div class="author-loc">Wisconsin Dells, WI</div></div></div>
        </div>
        <div class="testimonial-card reveal">
          <div class="stars">★★★★★</div>
          <p class="testimonial-text">Got into an accident on Hwy 12 and All Roads Towing was there before the police even finished their report. Professional, calm, and efficient. They handled everything perfectly. Cannot recommend enough.</p>
          <div class="testimonial-author"><div class="author-avatar">MT</div><div><div class="author-name">Mike Thompson</div><div class="author-loc">Baraboo, WI</div></div></div>
        </div>
        <div class="testimonial-card reveal">
          <div class="stars">★★★★★</div>
          <p class="testimonial-text">Locked my keys in my truck during a snowstorm. Called All Roads and the driver was there in under 25 minutes. Friendly, professional, and had me back in my truck in no time. 10/10 service.</p>
          <div class="testimonial-author"><div class="author-avatar">DL</div><div><div class="author-name">Dave Larson</div><div class="author-loc">Portage, WI</div></div></div>
        </div>
        <div class="testimonial-card reveal">
          <div class="stars">★★★★★</div>
          <p class="testimonial-text">Used them for a long-distance tow from Wisconsin Dells to Milwaukee. Fair price, my car arrived without a scratch, and the driver kept me updated the whole time. Will use again without hesitation.</p>
          <div class="testimonial-author"><div class="author-avatar">JR</div><div><div class="author-name">Jennifer Rodriguez</div><div class="author-loc">Milwaukee, WI</div></div></div>
        </div>
        <div class="testimonial-card reveal">
          <div class="stars">★★★★★</div>
          <p class="testimonial-text">My RV got stuck in soft ground at a campsite. The winch-out crew was amazing — careful, efficient, and they didn't damage anything. These guys know what they're doing. Very impressed.</p>
          <div class="testimonial-author"><div class="author-avatar">BC</div><div><div class="author-name">Brian Carter</div><div class="author-loc">Reedsburg, WI</div></div></div>
        </div>
        <div class="testimonial-card reveal">
          <div class="stars">★★★★★</div>
          <p class="testimonial-text">Rick himself showed up when my car died on the interstate. He was kind, quick, and went above and beyond by following me to the mechanic to make sure I got there safely. Outstanding human being and business.</p>
          <div class="testimonial-author"><div class="author-avatar">AM</div><div><div class="author-name">Amanda Mitchell</div><div class="author-loc">Wisconsin Dells, WI</div></div></div>
        </div>
        <div class="testimonial-card reveal">
          <div class="stars">★★★★★</div>
          <p class="testimonial-text">Had my motorcycle towed after a minor tip-over. The driver used proper cradles and straps and treated my bike with so much care. No scratches, no damage. I was impressed by the professionalism.</p>
          <div class="testimonial-author"><div class="author-avatar">KP</div><div><div class="author-name">Kevin Park</div><div class="author-loc">Wisconsin Dells, WI</div></div></div>
        </div>
        <div class="testimonial-card reveal">
          <div class="stars">★★★★★</div>
          <p class="testimonial-text">Ran out of gas on a back road at 2am. All Roads sent someone out within 30 minutes with exactly what I needed. I couldn't believe how fast they were at that hour. Incredible 24/7 service.</p>
          <div class="testimonial-author"><div class="author-avatar">TW</div><div><div class="author-name">Tanya Williams</div><div class="author-loc">Merrimac, WI</div></div></div>
        </div>
        <div class="testimonial-card reveal">
          <div class="stars">★★★★★</div>
          <p class="testimonial-text">Our semi broke down on I-90 during a delivery. All Roads' heavy-duty team handled it professionally and got us moving again in record time. We've made them our company's go-to towing service.</p>
          <div class="testimonial-author"><div class="author-avatar">FL</div><div><div class="author-name">Frank Lombardi</div><div class="author-loc">Madison, WI</div></div></div>
        </div>
      </div>
    </div>
  </section>
  <div class="cta-band">
    <div class="container">
      <h2>Join Hundreds of Satisfied Customers</h2>
      <p>Experience the All Roads Towing difference. Available 24/7.</p>
      <a class="btn-white" href="tel:+12628447838"><i class="fas fa-phone"></i> Call Now</a>
    </div>
  </div>
</div><!-- /testimonials -->


<!-- ══════════════════════════════
     PAGE: FAQ
══════════════════════════════ -->
<div class="page" id="page-faq">
  <div class="page-banner">
    <div class="container">
      <div class="breadcrumb"><span onclick="showPage('home')">Home</span><span class="sep">/</span><span class="current">FAQ</span></div>
      <h1>Frequently Asked <span style="color:var(--yellow)">Questions</span></h1>
      <p>Answers to the questions we hear most often from our customers.</p>
    </div>
  </div>
  <section class="section">
    <div class="container">
      <div style="display:grid;grid-template-columns:1fr 1.5fr;gap:60px;align-items:start;">
        <div class="reveal">
          <div class="section-label">Still Have Questions?</div>
          <h2 class="section-title">We're Here <em>24/7</em></h2>
          <p style="color:var(--gray);margin-bottom:24px;line-height:1.7;">Can't find the answer you're looking for? Our team is available around the clock to assist you.</p>
          <a class="btn-primary" href="tel:+12628447838" style="display:inline-flex;margin-bottom:12px;"><i class="fas fa-phone"></i> +1 (262) 844-7838</a><br>
          <a class="btn-whatsapp" href="https://wa.me/12628447838" target="_blank" style="display:inline-flex;margin-top:8px;"><i class="fab fa-whatsapp"></i> WhatsApp Us</a>
          <div style="margin-top:40px;background:var(--navy2);border-radius:12px;padding:28px;border:1px solid rgba(255,255,255,0.07);">
            <h4 style="font-family:var(--font-head);font-size:18px;color:var(--white);margin-bottom:16px;"><i class="fas fa-location-dot" style="color:var(--red);margin-right:8px;"></i>Service Area</h4>
            <p style="color:var(--gray);font-size:14px;line-height:1.7;">We primarily serve Wisconsin Dells and all surrounding communities including Baraboo, Portage, Reedsburg, Lake Delton, Merrimac, and beyond. Long-distance towing available statewide.</p>
          </div>
        </div>
        <div class="faq-list reveal">
          <div class="faq-item">
            <div class="faq-question" onclick="toggleFaq(this)"><h3>Do you operate 24/7?</h3><span class="icon"><i class="fas fa-plus"></i></span></div>
            <div class="faq-answer"><div class="faq-answer-inner">Yes, absolutely! All Roads Towing Accident Recovery Specialists operates 24 hours a day, 7 days a week, 365 days a year — including all holidays. Emergencies don't wait, and neither do we. You can call us any time, day or night, and a dispatcher will answer immediately.</div></div>
          </div>
          <div class="faq-item">
            <div class="faq-question" onclick="toggleFaq(this)"><h3>How quickly do you respond?</h3><span class="icon"><i class="fas fa-plus"></i></span></div>
            <div class="faq-answer"><div class="faq-answer-inner">Our average response time is under 30 minutes in Wisconsin Dells and immediate surrounding areas. Response times may vary for more rural locations or during extremely high-demand periods such as major storms. We always give you an estimated arrival time when you call, and we keep you updated if anything changes.</div></div>
          </div>
          <div class="faq-item">
            <div class="faq-question" onclick="toggleFaq(this)"><h3>What areas do you serve?</h3><span class="icon"><i class="fas fa-plus"></i></span></div>
            <div class="faq-answer"><div class="faq-answer-inner">We primarily serve Wisconsin Dells and surrounding communities including Baraboo, Portage, Lake Delton, Reedsburg, Merrimac, Sauk City, Prairie du Sac, and surrounding areas. We also provide long-distance and statewide towing services throughout Wisconsin. Call us and we'll let you know if we can reach your location.</div></div>
          </div>
          <div class="faq-item">
            <div class="faq-question" onclick="toggleFaq(this)"><h3>Do you provide accident recovery?</h3><span class="icon"><i class="fas fa-plus"></i></span></div>
            <div class="faq-answer"><div class="faq-answer-inner">Yes — accident recovery is one of our core specialties. We have specialized equipment and trained operators for everything from minor accidents to major multi-vehicle crash recoveries. We work alongside law enforcement to clear scenes safely and efficiently, and we can coordinate with your insurance company.</div></div>
          </div>
          <div class="faq-item">
            <div class="faq-question" onclick="toggleFaq(this)"><h3>Do you offer roadside assistance?</h3><span class="icon"><i class="fas fa-plus"></i></span></div>
            <div class="faq-answer"><div class="faq-answer-inner">Yes! Our comprehensive roadside assistance services include flat tire changes, battery jump-starts, fuel delivery, vehicle lockout service, and more. We come to you wherever you are so you can get back on the road without needing a full tow in many situations.</div></div>
          </div>
          <div class="faq-item">
            <div class="faq-question" onclick="toggleFaq(this)"><h3>Do you tow motorcycles?</h3><span class="icon"><i class="fas fa-plus"></i></span></div>
            <div class="faq-answer"><div class="faq-answer-inner">Yes! We offer specialized motorcycle towing using proper cradle systems and tie-down equipment designed specifically for bikes. We take great care to ensure your motorcycle is transported safely without damage to the frame, fairings, or finish. We tow all types of motorcycles, sport bikes, cruisers, and more.</div></div>
          </div>
          <div class="faq-item">
            <div class="faq-question" onclick="toggleFaq(this)"><h3>Do you offer long-distance towing?</h3><span class="icon"><i class="fas fa-plus"></i></span></div>
            <div class="faq-answer"><div class="faq-answer-inner">Absolutely. We provide long-distance towing throughout Wisconsin and beyond. Whether you need your vehicle moved across the state or out of state entirely, we can accommodate. We'll provide a quote based on distance and vehicle type. Call us at +1 (262) 844-7838 to discuss your long-distance towing needs.</div></div>
          </div>
          <div class="faq-item">
            <div class="faq-question" onclick="toggleFaq(this)"><h3>Are you licensed and insured?</h3><span class="icon"><i class="fas fa-plus"></i></span></div>
            <div class="faq-answer"><div class="faq-answer-inner">Yes, All Roads Towing Accident Recovery Specialists is fully licensed and insured in the state of Wisconsin. All of our operators are trained professionals, and our fleet meets all state and federal safety requirements. Your vehicle is in safe, protected hands from pickup to drop-off.</div></div>
          </div>
          <div class="faq-item">
            <div class="faq-question" onclick="toggleFaq(this)"><h3>How do I get a price quote?</h3><span class="icon"><i class="fas fa-plus"></i></span></div>
            <div class="faq-answer"><div class="faq-answer-inner">Simply call us at +1 (262) 844-7838 or send us a message via WhatsApp. We'll gather some basic information about your vehicle, location, and the service you need, and we'll provide you with a transparent, upfront quote. We believe in honest pricing with no hidden fees or surprise charges.</div></div>
          </div>
        </div>
      </div>
    </div>
  </section>
</div><!-- /faq -->


<!-- ══ FLOATING BUTTONS ══ -->
<div class="float-btns">
  <a class="float-btn wa" href="https://wa.me/12628447838" target="_blank" title="WhatsApp"><i class="fab fa-whatsapp"></i></a>
  <a class="float-btn call" href="tel:+12628447838" title="Call Now"><i class="fas fa-phone"></i></a>
</div>

<!-- ══ FOOTER ══ -->
<footer>
  <div class="container">
    <div class="footer-grid">
      <div class="footer-brand">
        <div class="logo">
          <div class="logo-icon"><i class="fas fa-truck-tow"></i></div>
          <div class="logo-text"><div class="b">All Roads Towing</div><div class="t">Accident Recovery Specialists</div></div>
        </div>
        <p>Fast, reliable towing and accident recovery services in Wisconsin Dells, WI. Available 24/7 — because emergencies don't wait for business hours.</p>
        <div class="social-links">
          <a class="social-link" href="#" title="Facebook"><i class="fab fa-facebook-f"></i></a>
          <a class="social-link" href="#" title="Instagram"><i class="fab fa-instagram"></i></a>
          <a class="social-link" href="#" title="Twitter"><i class="fab fa-x-twitter"></i></a>
          <a class="social-link" href="https://wa.me/12628447838" target="_blank" title="WhatsApp"><i class="fab fa-whatsapp"></i></a>
          <a class="social-link" href="https://google.com" title="Google"><i class="fab fa-google"></i></a>
        </div>
      </div>
      <div class="footer-col">
        <h4>Quick Links</h4>
        <ul class="footer-links">
          <li><a onclick="showPage('home')">Home</a></li>
          <li><a onclick="showPage('about')">About Us</a></li>
          <li><a onclick="showPage('testimonials')">Customer Reviews</a></li>
          <li><a onclick="showPage('faq')">FAQ</a></li>
          <li><a onclick="showPage('careers')">Careers</a></li>
          <li><a onclick="showPage('contact')">Contact Us</a></li>
        </ul>
      </div>
      <div class="footer-col">
        <h4>Services</h4>
        <ul class="footer-links">
          <li><a onclick="showPage('services')">Emergency Towing</a></li>
          <li><a onclick="showPage('services')">Accident Recovery</a></li>
          <li><a onclick="showPage('services')">Roadside Assistance</a></li>
          <li><a onclick="showPage('services')">Jump-Start Service</a></li>
          <li><a onclick="showPage('services')">Fuel Delivery</a></li>
          <li><a onclick="showPage('services')">Vehicle Lockout</a></li>
          <li><a onclick="showPage('services')">Long-Distance Towing</a></li>
          <li><a onclick="showPage('services')">Motorcycle Towing</a></li>
        </ul>
      </div>
      <div class="footer-col">
        <h4>Contact</h4>
        <div class="footer-contact-item"><i class="fas fa-phone"></i><a href="tel:+12628447838">+1 (262) 844-7838</a></div>
        <div class="footer-contact-item"><i class="fab fa-whatsapp"></i><a href="https://wa.me/12628447838" target="_blank">WhatsApp: +1 (262) 844-7838</a></div>
        <div class="footer-contact-item"><i class="fas fa-envelope"></i><a href="mailto:wentzrichard353@gmail.com">wentzrichard353@gmail.com</a></div>
        <div class="footer-contact-item"><i class="fas fa-location-dot"></i><span>Wisconsin Dells, Wisconsin, USA</span></div>
        <div class="footer-contact-item"><i class="fas fa-clock"></i><span>24 Hours / 7 Days a Week</span></div>
      </div>
    </div>
    <div class="footer-bottom">
      <p>© 2026 All Roads Towing Accident Recovery Specialists. All Rights Reserved. | Founded by Rick Wentz</p>
      <a class="emergency-badge" href="tel:+12628447838"><span class="dot" style="width:8px;height:8px;background:white;border-radius:50%;display:inline-block;animation:blink 1s infinite;"></span> Emergency: +1 (262) 844-7838</a>
    </div>
  </div>
  <div class="footer-stripe"></div>
</footer>

<script>
// ── PAGE ROUTING ──
function showPage(id) {
  document.querySelectorAll('.page').forEach(p => p.classList.remove('active'));
  document.querySelectorAll('.nav-links a').forEach(a => a.classList.remove('active'));
  const page = document.getElementById('page-' + id);
  if (page) { page.classList.add('active'); }
  const navLink = document.getElementById('nav-' + id);
  if (navLink) { navLink.classList.add('active'); }
  window.scrollTo({ top: 0, behavior: 'smooth' });
  setTimeout(initReveal, 100);
}

// ── MOBILE MENU ──
function toggleMenu() {
  const ham = document.getElementById('hamburger');
  const menu = document.getElementById('mobileMenu');
  ham.classList.toggle('open');
  menu.classList.toggle('open');
}
function closeMenu() {
  document.getElementById('hamburger').classList.remove('open');
  document.getElementById('mobileMenu').classList.remove('open');
}

// ── NAVBAR SCROLL ──
window.addEventListener('scroll', () => {
  const nb = document.getElementById('navbar');
  nb.classList.toggle('scrolled', window.scrollY > 50);
});

// ── SCROLL REVEAL ──
function initReveal() {
  const observer = new IntersectionObserver((entries) => {
    entries.forEach(e => { if (e.isIntersecting) { e.target.classList.add('visible'); } });
  }, { threshold: 0.1 });
  document.querySelectorAll('.page.active .reveal, .page.active .reveal-left, .page.active .reveal-right').forEach(el => {
    el.classList.remove('visible');
    observer.observe(el);
  });
}
window.addEventListener('load', () => { setTimeout(initReveal, 200); });

// ── FAQ TOGGLE ──
function toggleFaq(btn) {
  const item = btn.closest('.faq-item');
  const wasOpen = item.classList.contains('open');
  document.querySelectorAll('.faq-item').forEach(i => i.classList.remove('open'));
  if (!wasOpen) item.classList.add('open');
}

// ── FORMS ──
function submitContact(e) {
  e.preventDefault();
  document.getElementById('contactForm').style.display = 'none';
  document.getElementById('contactSuccess').style.display = 'block';
}
function submitCareer(e) {
  e.preventDefault();
  document.getElementById('careerForm').style.display = 'none';
  document.getElementById('careerSuccess').style.display = 'block';
}

// ── FILE UPLOAD LABELS ──
function showFileName(input, labelId) {
  const label = document.getElementById(labelId);
  if (input.files.length > 0) {
    const names = Array.from(input.files).map(f => f.name).join(', ');
    label.innerHTML = '<strong style="color:var(--yellow)"><i class="fas fa-check"></i> ' + names + '</strong>';
  }
}

// ── STAGGER DELAYS ──
document.querySelectorAll('.why-grid .why-card, .services-grid .service-card, .testimonials-grid .testimonial-card, .values-grid .value-card').forEach((el, i) => {
  el.style.transitionDelay = (i * 80) + 'ms';
});

// Init home active
document.getElementById('nav-home').classList.add('active');
</script>
</body>
</html>
