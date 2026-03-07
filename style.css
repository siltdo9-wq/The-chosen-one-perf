<!DOCTYPE html>
<html lang="fr">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>SHŌRI — Streetwear</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link href="https://fonts.googleapis.com/css2?family=Bebas+Neue&family=Barlow+Condensed:ital,wght@0,300;0,400;0,600;0,700;0,900;1,700&family=Barlow:ital,wght@0,300;0,400;0,600;1,300&display=swap" rel="stylesheet">
<style>
  :root {
    --black: #080808;
    --white: #f5f5f0;
    --gold: #c8a96e;
    --gray: #141414;
    --gray2: #1e1e1e;
    --gray3: #2a2a2a;
    --muted: #666;
  }

*, *::before, *::after { box-sizing: border-box; margin: 0; padding: 0; }
html { scroll-behavior: smooth; }

body {
background: var(--black);
color: var(--white);
font-family: 'Barlow', sans-serif;
font-weight: 300;
overflow-x: hidden;
}

/* NOISE */
body::before {
content: '';
position: fixed;
inset: 0;
background-image: url("data:image/svg+xml,%3Csvg viewBox='0 0 200 200' xmlns='http://www.w3.org/2000/svg'%3E%3Cfilter id='n'%3E%3CfeTurbulence type='fractalNoise' baseFrequency='0.85' numOctaves='4' stitchTiles='stitch'/%3E%3C/filter%3E%3Crect width='100%25' height='100%25' filter='url(%23n)' opacity='0.035'/%3E%3C/svg%3E");
pointer-events: none;
z-index: 9999;
opacity: 0.5;
}

/* ANNOUNCEMENT */
.announcement {
background: var(--gold);
color: var(--black);
text-align: center;
padding: 11px;
font-family: 'Barlow Condensed', sans-serif;
font-size: 11px;
font-weight: 700;
letter-spacing: 5px;
text-transform: uppercase;
animation: shimmer 3s ease-in-out infinite;
}

@keyframes shimmer {
  0%, 100% { opacity: 1; }
  50% { opacity: 0.8; }
}

/* NAV */
nav {
position: sticky;
top: 0;
z-index: 100;
display: flex;
justify-content: space-between;
align-items: center;
padding: 18px 40px;
background: rgba(8,8,8,0.97);
backdrop-filter: blur(16px);
border-bottom: 1px solid rgba(255,255,255,0.07);
transition: all 0.4s ease;
}

nav.scrolled {
  padding: 12px 40px;
  background: rgba(8,8,8,0.98);
}

.nav-logo {
font-family: 'Bebas Neue', sans-serif;
font-size: 30px;
letter-spacing: 10px;
color: var(--white);
text-decoration: none;
position: relative;
overflow: hidden;
}

.nav-logo::after {
  content: '';
  position: absolute;
  bottom: 0;
  left: 0;
  width: 0;
  height: 2px;
  background: var(--gold);
  transition: width 0.3s ease;
}

.nav-logo:hover::after {
  width: 100%;
}

.nav-tagline {
font-family: 'Barlow Condensed', sans-serif;
font-size: 10px;
letter-spacing: 5px;
color: var(--muted);
text-transform: uppercase;
font-weight: 400;
opacity: 0;
animation: fadeIn 1s ease 0.5s forwards;
}

@keyframes fadeIn {
  to { opacity: 1; }
}

.nav-actions {
display: flex;
align-items: center;
gap: 28px;
}

.nav-actions a {
color: var(--white);
text-decoration: none;
font-family: 'Barlow Condensed', sans-serif;
font-size: 11px;
font-weight: 600;
letter-spacing: 4px;
text-transform: uppercase;
opacity: 0.5;
transition: all 0.3s ease;
position: relative;
}
.nav-actions a:hover { opacity: 1; }

.nav-actions a::after {
  content: '';
  position: absolute;
  bottom: -4px;
  left: 0;
  width: 0;
  height: 1px;
  background: var(--gold);
  transition: width 0.3s ease;
}

.nav-actions a:hover::after {
  width: 100%;
}

.cart-btn {
background: var(--white);
color: var(--black) !important;
opacity: 1 !important;
padding: 9px 22px;
font-weight: 700 !important;
transition: all 0.3s ease;
}

.cart-btn:hover {
  background: var(--gold) !important;
  transform: translateY(-2px);
  box-shadow: 0 4px 20px rgba(200,169,110,0.3);
}

.cart-btn::after {
  display: none !important;
}

/* HERO */
.hero {
min-height: 100vh;
display: flex;
flex-direction: column;
align-items: center;
justify-content: center;
position: relative;
overflow: hidden;
background: var(--black);
}

.hero-bg {
position: absolute;
inset: 0;
background: radial-gradient(ellipse 70% 50% at 50% 50%, rgba(200,169,110,0.05) 0%, transparent 65%);
animation: pulse 8s ease-in-out infinite;
}

@keyframes pulse {
  0%, 100% { transform: scale(1); opacity: 0.05; }
  50% { transform: scale(1.1); opacity: 0.08; }
}

.hero-globe {
position: absolute;
width: 560px;
height: 560px;
opacity: 0.07;
animation: rotate 60s linear infinite;
}

@keyframes rotate {
  from { transform: rotate(0deg); }
  to { transform: rotate(360deg); }
}

.hero-content {
position: relative;
text-align: center;
z-index: 2;
padding: 0 20px;
opacity: 0;
transform: translateY(30px);
animation: slideUp 1s ease 0.2s forwards;
}

@keyframes slideUp {
  to {
    opacity: 1;
    transform: translateY(0);
  }
}

.hero-eyebrow {
font-family: 'Barlow Condensed', sans-serif;
font-size: 11px;
font-weight: 700;
letter-spacing: 10px;
color: var(--gold);
text-transform: uppercase;
margin-bottom: 12px;
display: block;
opacity: 0;
animation: fadeIn 1s ease 0.4s forwards;
}

.hero-title {
font-family: 'Bebas Neue', sans-serif;
font-size: clamp(110px, 24vw, 240px);
line-height: 0.88;
letter-spacing: 4px;
color: var(--white);
display: block;
position: relative;
}

.hero-title::after {
  content: 'SHŌRI';
  position: absolute;
  left: 2px;
  top: 2px;
  color: transparent;
  -webkit-text-stroke: 1px rgba(200,169,110,0.2);
  z-index: -1;
}

.hero-rule {
display: flex;
align-items: center;
justify-content: center;
gap: 20px;
margin: 28px 0;
opacity: 0;
animation: fadeIn 1s ease 0.6s forwards;
}

.hero-rule::before,
.hero-rule::after {
content: '';
width: 100px;
height: 1px;
background: rgba(255,255,255,0.15);
transition: width 0.5s ease;
}

.hero:hover .hero-rule::before,
.hero:hover .hero-rule::after {
  width: 150px;
}

.hero-rule span {
font-family: 'Barlow Condensed', sans-serif;
font-size: 10px;
font-weight: 600;
letter-spacing: 7px;
text-transform: uppercase;
color: rgba(255,255,255,0.3);
}

.hero-pillars {
font-family: 'Barlow Condensed', sans-serif;
font-size: 12px;
font-weight: 600;
letter-spacing: 7px;
text-transform: uppercase;
color: var(--muted);
margin-bottom: 52px;
display: block;
opacity: 0;
animation: fadeIn 1s ease 0.8s forwards;
}

.hero-cta {
display: inline-flex;
gap: 14px;
flex-wrap: wrap;
justify-content: center;
opacity: 0;
animation: fadeIn 1s ease 1s forwards;
}

/* BUTTONS */
.btn {
font-family: 'Barlow Condensed', sans-serif;
font-size: 11px;
font-weight: 700;
letter-spacing: 5px;
text-transform: uppercase;
padding: 15px 38px;
text-decoration: none;
border: 1px solid;
cursor: pointer;
display: inline-block;
background: none;
transition: all 0.3s ease;
position: relative;
overflow: hidden;
}

.btn::before {
  content: '';
  position: absolute;
  top: 0;
  left: -100%;
  width: 100%;
  height: 100%;
  background: linear-gradient(90deg, transparent, rgba(255,255,255,0.2), transparent);
  transition: left 0.5s ease;
}

.btn:hover::before {
  left: 100%;
}

.btn-primary {
background: var(--white);
color: var(--black);
border-color: var(--white);
}
.btn-primary:hover { 
  background: var(--gold); 
  border-color: var(--gold);
  transform: translateY(-2px);
  box-shadow: 0 10px 30px rgba(200,169,110,0.3);
}

.btn-ghost {
background: transparent;
color: var(--white);
border-color: rgba(255,255,255,0.25);
}
.btn-ghost:hover { 
  border-color: var(--white);
  background: rgba(255,255,255,0.05);
  transform: translateY(-2px);
}

/* MARQUEE */
.marquee-wrap {
border-top: 1px solid rgba(255,255,255,0.07);
border-bottom: 1px solid rgba(255,255,255,0.07);
overflow: hidden;
padding: 14px 0;
background: var(--gray);
}

.marquee-track {
display: flex;
white-space: nowrap;
animation: marquee-scroll 22s linear infinite;
}

@keyframes marquee-scroll { 
  from { transform: translateX(0); } 
  to { transform: translateX(-50%); } 
}

.marquee-inner {
display: flex;
flex-shrink: 0;
min-width: 100%;
}

.marquee-inner span {
font-family: 'Bebas Neue', sans-serif;
font-size: 13px;
letter-spacing: 7px;
color: var(--muted);
padding: 0 36px;
transition: color 0.3s ease;
}

.marquee-inner span:hover {
  color: var(--gold);
}

.marquee-inner span.accent { 
  color: var(--gold);
  animation: pulse-gold 2s ease-in-out infinite;
}

@keyframes pulse-gold {
  0%, 100% { opacity: 1; }
  50% { opacity: 0.5; }
}

/* SECTION BASE */
section { padding: 110px 40px; }

.label {
font-family: 'Barlow Condensed', sans-serif;
font-size: 10px;
font-weight: 700;
letter-spacing: 7px;
text-transform: uppercase;
color: var(--gold);
display: block;
margin-bottom: 14px;
}

.display-title {
font-family: 'Bebas Neue', sans-serif;
font-size: clamp(52px, 9vw, 108px);
line-height: 0.88;
letter-spacing: 3px;
display: block;
}

/* ABOUT */
.about-grid {
display: grid;
grid-template-columns: 1fr 1fr;
gap: 100px;
align-items: center;
max-width: 1200px;
margin: 0 auto;
}

.about-visual {
border: 1px solid rgba(255,255,255,0.06);
aspect-ratio: 1;
display: flex;
align-items: center;
justify-content: center;
background: var(--gray);
position: relative;
overflow: hidden;
transition: border-color 0.3s ease;
}

.about-visual:hover {
  border-color: rgba(200,169,110,0.3);
}

.about-visual::before {
content: '';
position: absolute;
inset: 0;
background: radial-gradient(ellipse at center, rgba(200,169,110,0.06) 0%, transparent 70%);
animation: pulse 6s ease-in-out infinite;
}

.about-monogram {
font-family: 'Bebas Neue', sans-serif;
font-size: 100px;
letter-spacing: 6px;
color: rgba(255,255,255,0.05);
position: absolute;
animation: float 6s ease-in-out infinite;
}

@keyframes float {
  0%, 100% { transform: translateY(0); }
  50% { transform: translateY(-10px); }
}

.about-rings {
position: relative;
display: flex;
align-items: center;
justify-content: center;
}

.ring {
position: absolute;
border-radius: 50%;
border: 1px solid rgba(200,169,110,0.15);
animation: ripple 4s ease-out infinite;
}

.ring-1 { width: 160px; height: 160px; animation-delay: 0s; }
.ring-2 { width: 220px; height: 220px; animation-delay: 1s; }
.ring-3 { width: 280px; height: 280px; animation-delay: 2s; }

@keyframes ripple {
  0% { transform: scale(0.8); opacity: 0.5; }
  100% { transform: scale(1.2); opacity: 0; }
}

.about-center-text {
position: relative;
text-align: center;
z-index: 2;
}

.about-center-text strong {
font-family: 'Bebas Neue', sans-serif;
font-size: 52px;
letter-spacing: 5px;
display: block;
line-height: 1;
}

.about-center-text span {
font-family: 'Barlow Condensed', sans-serif;
font-size: 10px;
font-weight: 600;
letter-spacing: 8px;
color: var(--gold);
text-transform: uppercase;
display: block;
margin-top: 10px;
}

.about-text .display-title { margin-bottom: 36px; }

.about-text p {
font-family: 'Barlow', sans-serif;
font-size: 15px;
font-weight: 300;
line-height: 2;
color: rgba(245,245,240,0.5);
margin-bottom: 18px;
transition: color 0.3s ease;
}

.about-text p:hover {
  color: rgba(245,245,240,0.8);
}

.about-text p strong {
font-weight: 600;
color: var(--white);
font-style: italic;
}

/* MANIFESTO */
.manifesto {
background: var(--gray);
border-top: 1px solid rgba(255,255,255,0.06);
border-bottom: 1px solid rgba(255,255,255,0.06);
padding: 130px 40px;
text-align: center;
position: relative;
overflow: hidden;
}

.manifesto::before {
content: 'SHŌRI';
position: absolute;
font-family: 'Bebas Neue', sans-serif;
font-size: 38vw;
color: rgba(255,255,255,0.018);
top: 50%;
left: 50%;
transform: translate(-50%, -50%);
pointer-events: none;
letter-spacing: -4px;
white-space: nowrap;
animation: drift 20s ease-in-out infinite;
}

@keyframes drift {
  0%, 100% { transform: translate(-50%, -50%) translateX(0); }
  50% { transform: translate(-50%, -50%) translateX(-20px); }
}

.manifesto-inner {
position: relative;
max-width: 800px;
margin: 0 auto;
}

.manifesto-quote {
font-family: 'Bebas Neue', sans-serif;
font-size: clamp(42px, 7vw, 84px);
line-height: 1;
letter-spacing: 3px;
margin-bottom: 36px;
}

.manifesto-quote em {
color: var(--gold);
font-style: normal;
position: relative;
}

.manifesto-quote em::after {
  content: '';
  position: absolute;
  bottom: -5px;
  left: 0;
  width: 100%;
  height: 3px;
  background: var(--gold);
  transform: scaleX(0);
  transition: transform 0.5s ease;
}

.manifesto-inner:hover .manifesto-quote em::after {
  transform: scaleX(1);
}

.manifesto-body {
font-family: 'Barlow', sans-serif;
font-size: 14px;
font-weight: 300;
font-style: italic;
line-height: 2.1;
color: rgba(245,245,240,0.4);
max-width: 480px;
margin: 0 auto;
letter-spacing: 0.5px;
transition: color 0.3s ease;
}

.manifesto-inner:hover .manifesto-body {
  color: rgba(245,245,240,0.7);
}

/* PRODUCTS */
.products-section { max-width: 1200px; margin: 0 auto; }

.products-header {
display: flex;
justify-content: space-between;
align-items: flex-end;
margin-bottom: 48px;
border-bottom: 1px solid rgba(255,255,255,0.07);
padding-bottom: 32px;
}

.products-grid {
display: grid;
grid-template-columns: repeat(3, 1fr);
gap: 2px;
}

.product-card {
background: var(--gray);
position: relative;
transition: all 0.4s ease;
overflow: hidden;
}

.product-card:hover {
  transform: translateY(-10px);
  box-shadow: 0 20px 40px rgba(0,0,0,0.4);
  z-index: 10;
}

.product-img-placeholder {
width: 100%;
aspect-ratio: 3/4;
display: flex;
flex-direction: column;
align-items: center;
justify-content: center;
gap: 20px;
background: var(--gray2);
border-bottom: 1px solid rgba(255,255,255,0.05);
position: relative;
overflow: hidden;
}

.product-img-placeholder::before {
  content: '';
  position: absolute;
  inset: 0;
  background: radial-gradient(circle at center, rgba(200,169,110,0.1) 0%, transparent 70%);
  opacity: 0;
  transition: opacity 0.3s ease;
}

.product-card:hover .product-img-placeholder::before {
  opacity: 1;
}

.placeholder-icon { 
  opacity: 0.12;
  transition: all 0.3s ease;
}
.placeholder-icon svg { width: 64px; height: 64px; }

.product-card:hover .placeholder-icon {
  opacity: 0.3;
  transform: scale(1.1);
}

.placeholder-label {
font-family: 'Barlow Condensed', sans-serif;
font-size: 10px;
font-weight: 700;
letter-spacing: 6px;
text-transform: uppercase;
color: rgba(255,255,255,0.15);
transition: color 0.3s ease;
}

.product-card:hover .placeholder-label {
  color: var(--gold);
}

.product-info {
padding: 22px 24px 26px;
}

.product-edition {
font-family: 'Barlow Condensed', sans-serif;
font-size: 10px;
font-weight: 700;
letter-spacing: 5px;
text-transform: uppercase;
color: var(--gold);
display: block;
margin-bottom: 6px;
}

.product-name {
font-family: 'Bebas Neue', sans-serif;
font-size: 32px;
letter-spacing: 3px;
display: block;
margin-bottom: 18px;
line-height: 1;
transition: color 0.3s ease;
}

.product-card:hover .product-name {
  color: var(--gold);
}

.product-bottom {
display: flex;
justify-content: space-between;
align-items: flex-end;
margin-bottom: 16px;
}

.product-price {
font-family: 'Bebas Neue', sans-serif;
font-size: 36px;
letter-spacing: 2px;
line-height: 1;
transition: transform 0.3s ease;
}

.product-card:hover .product-price {
  transform: scale(1.05);
}

.product-sizes {
display: flex;
gap: 5px;
}

.size-dot {
width: 30px;
height: 30px;
border: 1px solid rgba(255,255,255,0.18);
display: flex;
align-items: center;
justify-content: center;
font-family: 'Barlow Condensed', sans-serif;
font-size: 10px;
font-weight: 700;
cursor: pointer;
color: rgba(255,255,255,0.5);
transition: all 0.2s ease;
}

.size-dot:hover, .size-dot.active {
border-color: var(--white);
background: var(--white);
color: var(--black);
transform: scale(1.1);
}

.add-cart-btn {
width: 100%;
background: none;
border: 1px solid rgba(255,255,255,0.2);
color: var(--white);
font-family: 'Barlow Condensed', sans-serif;
font-size: 11px;
font-weight: 700;
letter-spacing: 5px;
text-transform: uppercase;
padding: 12px;
cursor: pointer;
transition: all 0.3s ease;
position: relative;
overflow: hidden;
}

.add-cart-btn:hover { 
  background: var(--white); 
  color: var(--black); 
  border-color: var(--white);
  transform: translateY(-2px);
  box-shadow: 0 5px 15px rgba(255,255,255,0.1);
}

.add-cart-btn.added { 
  background: var(--gold); 
  border-color: var(--gold); 
  color: var(--black);
  animation: addedPulse 0.5s ease;
}

@keyframes addedPulse {
  0% { transform: scale(1); }
  50% { transform: scale(1.05); }
  100% { transform: scale(1); }
}

.saving-badge {
font-family: 'Barlow Condensed', sans-serif;
font-size: 10px;
font-weight: 700;
letter-spacing: 3px;
color: var(--gold);
text-transform: uppercase;
display: block;
margin-top: 4px;
animation: shimmer 2s ease-in-out infinite;
}

/* PILLARS */
.pillars-section { max-width: 1200px; margin: 0 auto; }

.pillars-grid {
display: grid;
grid-template-columns: repeat(3, 1fr);
gap: 2px;
margin-top: 56px;
}

.pillar {
background: var(--gray2);
padding: 50px 38px;
border: 1px solid rgba(255,255,255,0.05);
position: relative;
overflow: hidden;
transition: all 0.4s ease;
}

.pillar:hover {
  background: var(--gray3);
  border-color: rgba(200,169,110,0.2);
  transform: translateY(-5px);
}

.pillar-bg-num {
font-family: 'Bebas Neue', sans-serif;
font-size: 140px;
color: rgba(255,255,255,0.03);
position: absolute;
top: -16px;
right: -8px;
line-height: 1;
pointer-events: none;
letter-spacing: -4px;
transition: all 0.3s ease;
}

.pillar:hover .pillar-bg-num {
  color: rgba(200,169,110,0.08);
  transform: scale(1.1);
}

.pillar-bar {
width: 32px;
height: 2px;
background: var(--gold);
margin-bottom: 28px;
transition: width 0.3s ease;
}

.pillar:hover .pillar-bar {
  width: 60px;
}

.pillar-title {
font-family: 'Bebas Neue', sans-serif;
font-size: 42px;
letter-spacing: 4px;
margin-bottom: 16px;
display: block;
transition: color 0.3s ease;
}

.pillar:hover .pillar-title {
  color: var(--gold);
}

.pillar-text {
font-family: 'Barlow', sans-serif;
font-size: 13px;
font-weight: 300;
line-height: 1.9;
color: rgba(245,245,240,0.45);
transition: color 0.3s ease;
}

.pillar:hover .pillar-text {
  color: rgba(245,245,240,0.7);
}

/* NEWSLETTER */
.newsletter {
background: var(--white);
color: var(--black);
text-align: center;
padding: 110px 40px;
position: relative;
overflow: hidden;
}

.newsletter::before {
  content: '';
  position: absolute;
  top: -50%;
  left: -50%;
  width: 200%;
  height: 200%;
  background: radial-gradient(circle, rgba(200,169,110,0.1) 0%, transparent 70%);
  animation: rotate 30s linear infinite;
}

.newsletter .label { color: rgba(0,0,0,0.35); }
.newsletter .display-title { color: var(--black); position: relative; z-index: 1; }

.newsletter-sub {
font-family: 'Barlow', sans-serif;
font-size: 13px;
font-weight: 300;
font-style: italic;
letter-spacing: 1px;
color: rgba(0,0,0,0.4);
margin: 16px 0 40px;
position: relative;
z-index: 1;
}

.newsletter-form {
display: flex;
max-width: 460px;
margin: 0 auto;
border: 1px solid rgba(0,0,0,0.18);
position: relative;
z-index: 1;
transition: all 0.3s ease;
}

.newsletter-form:focus-within {
  border-color: var(--gold);
  box-shadow: 0 5px 20px rgba(200,169,110,0.2);
}

.newsletter-input {
flex: 1;
background: transparent;
border: none;
outline: none;
padding: 15px 20px;
font-family: 'Barlow', sans-serif;
font-size: 13px;
font-weight: 300;
color: var(--black);
letter-spacing: 1px;
}

.newsletter-input::placeholder { color: rgba(0,0,0,0.28); }

.newsletter-submit {
background: var(--black);
color: var(--white);
border: none;
padding: 15px 28px;
font-family: 'Barlow Condensed', sans-serif;
font-size: 10px;
font-weight: 700;
letter-spacing: 5px;
text-transform: uppercase;
cursor: pointer;
transition: all 0.3s ease;
}

.newsletter-submit:hover { 
  background: var(--gold);
  transform: translateX(2px);
}

/* FOOTER */
footer {
background: var(--black);
padding: 64px 40px 36px;
border-top: 1px solid rgba(255,255,255,0.06);
}

.footer-top {
display: grid;
grid-template-columns: 2fr 1fr 1fr;
gap: 72px;
margin-bottom: 64px;
}

.footer-brand-logo {
font-family: 'Bebas Neue', sans-serif;
font-size: 52px;
letter-spacing: 8px;
color: var(--white);
text-decoration: none;
display: block;
margin-bottom: 16px;
transition: color 0.3s ease;
}

.footer-brand-logo:hover {
  color: var(--gold);
}

.footer-brand p {
font-family: 'Barlow', sans-serif;
font-size: 13px;
font-weight: 300;
line-height: 1.8;
color: var(--muted);
max-width: 260px;
}

.social-link {
display: inline-flex;
align-items: center;
gap: 9px;
font-family: 'Barlow Condensed', sans-serif;
font-size: 10px;
font-weight: 700;
letter-spacing: 4px;
text-transform: uppercase;
color: var(--muted);
text-decoration: none;
margin-top: 24px;
transition: all 0.3s ease;
}
.social-link:hover { 
  color: var(--gold);
  transform: translateX(5px);
}
.social-link svg { width: 14px; height: 14px; flex-shrink: 0; }

.footer-col h4 {
font-family: 'Barlow Condensed', sans-serif;
font-size: 10px;
font-weight: 700;
letter-spacing: 6px;
text-transform: uppercase;
color: var(--gold);
margin-bottom: 24px;
}

.footer-col ul { list-style: none; }
.footer-col li { margin-bottom: 12px; }
.footer-col a {
text-decoration: none;
color: var(--muted);
font-family: 'Barlow', sans-serif;
font-size: 13px;
font-weight: 300;
letter-spacing: 0.5px;
transition: all 0.3s ease;
display: inline-block;
}
.footer-col a:hover { 
  color: var(--white);
  transform: translateX(3px);
}

.footer-bottom {
display: flex;
justify-content: space-between;
align-items: center;
padding-top: 28px;
border-top: 1px solid rgba(255,255,255,0.06);
}

.footer-copy {
font-family: 'Barlow Condensed', sans-serif;
font-size: 10px;
font-weight: 400;
letter-spacing: 3px;
text-transform: uppercase;
color: rgba(102,102,102,0.5);
}

.payment-icons { display: flex; gap: 6px; }

.payment-icon {
padding: 4px 9px;
background: rgba(255,255,255,0.05);
font-family: 'Barlow Condensed', sans-serif;
font-size: 9px;
font-weight: 700;
letter-spacing: 1px;
color: rgba(255,255,255,0.25);
text-transform: uppercase;
transition: all 0.3s ease;
cursor: pointer;
}

.payment-icon:hover {
  background: var(--gold);
  color: var(--black);
  transform: translateY(-2px);
}

/* SCROLL HINT */
.scroll-hint {
position: absolute;
bottom: 32px;
left: 50%;
transform: translateX(-50%);
display: flex;
flex-direction: column;
align-items: center;
gap: 10px;
opacity: 0.28;
animation: bounce 2s ease-in-out infinite;
}

@keyframes bounce {
  0%, 100% { transform: translateX(-50%) translateY(0); }
  50% { transform: translateX(-50%) translateY(10px); }
}

.scroll-hint span {
font-family: 'Barlow Condensed', sans-serif;
font-size: 9px;
font-weight: 700;
letter-spacing: 5px;
text-transform: uppercase;
}

.scroll-line {
width: 1px;
height: 36px;
background: linear-gradient(to bottom, var(--white), transparent);
animation: linePulse 2s ease-in-out infinite;
}

@keyframes linePulse {
  0%, 100% { opacity: 0.3; }
  50% { opacity: 1; }
}

/* REVEAL ANIMATIONS */
.reveal {
  opacity: 0;
  transform: translateY(30px);
  transition: all 0.8s ease;
}

.reveal.active {
  opacity: 1;
  transform: translateY(0);
}

/* MOBILE */
@media (max-width: 768px) {
nav { padding: 16px 20px; }
.nav-tagline { display: none; }
.nav-actions a:not(.cart-btn) { display: none; }
section { padding: 80px 20px; }
.about-grid { grid-template-columns: 1fr; gap: 48px; }
.about-visual { display: none; }
.products-grid { grid-template-columns: 1fr; gap: 20px; }
.products-header { flex-direction: column; align-items: flex-start; gap: 20px; }
.pillars-grid { grid-template-columns: 1fr; }
.footer-top { grid-template-columns: 1fr; gap: 40px; }
.footer-bottom { flex-direction: column; gap: 16px; text-align: center; }
.newsletter-form { flex-direction: column; }
.newsletter-submit { padding: 14px; }
.manifesto { padding: 80px 20px; }
footer { padding: 64px 20px 36px; }
.hero-globe { width: 300px; height: 300px; }
}
</style>

</head>
<body>

<div class="announcement">BLACK EDITION — DISPONIBLE MAINTENANT &nbsp;✦&nbsp; BELGIQUE & FRANCE</div>

<nav id="navbar">
  <a href="#" class="nav-logo">SHŌRI</a>
  <span class="nav-tagline">Ambition · Hard Work · Faith</span>
  <div class="nav-actions">
    <a href="#collection">Collection</a>
    <a href="#about">Histoire</a>
    <a href="#" class="cart-btn" id="cartBtn">Panier (0)</a>
  </div>
</nav>

<!-- HERO -->

<section class="hero">
  <div class="hero-bg"></div>

  <svg class="hero-globe" viewBox="0 0 400 400" fill="none" xmlns="http://www.w3.org/2000/svg">
    <circle cx="200" cy="200" r="190" stroke="white" stroke-width="0.6"/>
    <ellipse cx="200" cy="200" rx="190" ry="68" stroke="white" stroke-width="0.6"/>
    <ellipse cx="200" cy="200" rx="190" ry="128" stroke="white" stroke-width="0.6"/>
    <ellipse cx="200" cy="200" rx="68" ry="190" stroke="white" stroke-width="0.6"/>
    <ellipse cx="200" cy="200" rx="128" ry="190" stroke="white" stroke-width="0.6"/>
    <line x1="10" y1="200" x2="390" y2="200" stroke="white" stroke-width="0.6"/>
    <line x1="200" y1="10" x2="200" y2="390" stroke="white" stroke-width="0.6"/>
  </svg>

  <div class="hero-content">
    <span class="hero-eyebrow">Hustle.</span>
    <span class="hero-title">SHŌRI</span>
    <div class="hero-rule"><span>Streetwear</span></div>
    <span class="hero-pillars">Ambition &nbsp;·&nbsp; Hard Work &nbsp;·&nbsp; Faith</span>
    <div class="hero-cta">
      <a href="#collection" class="btn btn-primary">Voir la collection</a>
      <a href="#about" class="btn btn-ghost">Notre histoire</a>
    </div>
  </div>

  <div class="scroll-hint">
    <span>Scroll</span>
    <div class="scroll-line"></div>
  </div>
</section>

<!-- MARQUEE -->

<div class="marquee-wrap">
  <div class="marquee-track">
    <div class="marquee-inner">
      <span>SHŌRI</span><span class="accent">✦</span>
      <span>STREETWEAR</span><span class="accent">✦</span>
      <span>AMBITION</span><span class="accent">✦</span>
      <span>HARD WORK</span><span class="accent">✦</span>
      <span>FAITH</span><span class="accent">✦</span>
      <span>BLACK EDITION</span><span class="accent">✦</span>
      <span>HUSTLE</span><span class="accent">✦</span>
    </div>
    <div class="marquee-inner" aria-hidden="true">
      <span>SHŌRI</span><span class="accent">✦</span>
      <span>STREETWEAR</span><span class="accent">✦</span>
      <span>AMBITION</span><span class="accent">✦</span>
      <span>HARD WORK</span><span class="accent">✦</span>
      <span>FAITH</span><span class="accent">✦</span>
      <span>BLACK EDITION</span><span class="accent">✦</span>
      <span>HUSTLE</span><span class="accent">✦</span>
    </div>
  </div>
</div>

<!-- ABOUT -->

<section id="about">
  <div class="about-grid">
    <div class="about-visual reveal">
      <div class="about-monogram">SH</div>
      <div class="about-rings">
        <div class="ring ring-1"></div>
        <div class="ring ring-2"></div>
        <div class="ring ring-3"></div>
        <div class="about-center-text">
          <strong>SHŌRI</strong>
          <span>Streetwear</span>
        </div>
      </div>
    </div>
    <div class="about-text reveal">
      <span class="label">Qui sommes-nous</span>
      <span class="display-title">NOTRE<br>HISTOIRE</span>
      <p>Des pièces simples, confortables, avec des détails qui font la différence.</p>
      <p>Derrière chaque vêtement, il y a un travail, de l'ambition et une envie de créer quelque chose qui dure.</p>
      <p><strong>Shōri, c'est du streetwear qui raconte une histoire.</strong></p>
      <a href="#collection" class="btn btn-ghost" style="margin-top: 36px;">Voir la collection</a>
    </div>
  </div>
</section>

<!-- MANIFESTO -->

<div class="manifesto">
  <div class="manifesto-inner reveal">
    <span class="label" style="display:block; text-align:center;">Manifeste</span>
    <h2 class="manifesto-quote">CHAQUE PIÈCE EST<br>UN <em>ÉTAT D'ESPRIT</em></h2>
    <p class="manifesto-body">Ce n'est pas juste du tissu. C'est la représentation physique de tout ce que tu traverses, de tout ce que tu construis. Porter SHŌRI, c'est choisir d'avancer.</p>
  </div>
</div>

<!-- COLLECTION -->

<section id="collection">
  <div class="products-section">
    <div class="products-header reveal">
      <div>
        <span class="label">Collection</span>
        <span class="display-title">BLACK<br>EDITION</span>
      </div>
      <a href="#" class="btn btn-ghost">Tout voir</a>
    </div>

<div class="products-grid">

  <div class="product-card reveal">
    <div class="product-img-placeholder">
      <div class="placeholder-icon">
        <svg viewBox="0 0 100 100" fill="none" xmlns="http://www.w3.org/2000/svg">
          <path d="M30 20 L15 40 L25 45 L20 80 L80 80 L75 45 L85 40 L70 20 C65 28 55 32 50 32 C45 32 35 28 30 20Z" stroke="white" stroke-width="2" fill="none"/>
          <path d="M45 20 L50 32 L55 20" stroke="white" stroke-width="1.5" fill="none"/>
        </svg>
      </div>
      <span class="placeholder-label">Photo à venir</span>
    </div>
    <div class="product-info">
      <span class="product-edition">Black Edition</span>
      <span class="product-name">Hoodie</span>
      <div class="product-bottom">
        <span class="product-price">€60</span>
        <div class="product-sizes">
          <div class="size-dot">S</div><div class="size-dot">M</div><div class="size-dot">L</div><div class="size-dot">XL</div>
        </div>
      </div>
      <button class="add-cart-btn" data-product="Hoodie" data-price="60">Ajouter au panier</button>
    </div>
  </div>

  <div class="product-card reveal">
    <div class="product-img-placeholder">
      <div class="placeholder-icon">
        <svg viewBox="0 0 100 100" fill="none" xmlns="http://www.w3.org/2000/svg">
          <path d="M30 20 L25 50 L20 80 L45 80 L50 55 L55 80 L80 80 L75 50 L70 20 Z" stroke="white" stroke-width="2" fill="none"/>
          <path d="M30 34 L70 34" stroke="white" stroke-width="1" stroke-dasharray="4 3"/>
        </svg>
      </div>
      <span class="placeholder-label">Photo à venir</span>
    </div>
    <div class="product-info">
      <span class="product-edition">Black Edition</span>
      <span class="product-name">Jogger</span>
      <div class="product-bottom">
        <span class="product-price">€55</span>
        <div class="product-sizes">
          <div class="size-dot">S</div><div class="size-dot">M</div><div class="size-dot">L</div><div class="size-dot">XL</div>
        </div>
      </div>
      <button class="add-cart-btn" data-product="Jogger" data-price="55">Ajouter au panier</button>
    </div>
  </div>

  <div class="product-card reveal">
    <div class="product-img-placeholder">
      <div class="placeholder-icon">
        <svg viewBox="0 0 100 100" fill="none" xmlns="http://www.w3.org/2000/svg">
          <path d="M20 50 L50 20 L80 50 L50 80 Z" stroke="white" stroke-width="1.5" fill="none"/>
          <circle cx="50" cy="50" r="15" stroke="white" stroke-width="1.5" fill="none"/>
        </svg>
      </div>
      <span class="placeholder-label">Photo à venir</span>
    </div>
    <div class="product-info">
      <span class="product-edition">Offre Exclusive</span>
      <span class="product-name">Pack Black</span>
      <div class="product-bottom">
        <div>
          <span class="product-price">€105</span>
          <span class="saving-badge">−12€ d'économie</span>
        </div>
      </div>
      <button class="add-cart-btn" data-product="Pack Black" data-price="105">Ajouter au panier</button>
    </div>
  </div>

</div>

  </div>
</section>

<!-- PILLARS -->

<section style="background: var(--gray); border-top: 1px solid rgba(255,255,255,0.06); border-bottom: 1px solid rgba(255,255,255,0.06);">
  <div class="pillars-section">
    <span class="label reveal">Ce que nous portons</span>
    <span class="display-title reveal">NOS<br>VALEURS</span>
    <div class="pillars-grid">
      <div class="pillar reveal">
        <div class="pillar-bg-num">1</div>
        <div class="pillar-bar"></div>
        <span class="pillar-title">Ambition</span>
        <p class="pillar-text">Viser plus haut, toujours. Chaque jour est une opportunité de construire quelque chose de plus grand.</p>
      </div>
      <div class="pillar reveal">
        <div class="pillar-bg-num">2</div>
        <div class="pillar-bar"></div>
        <span class="pillar-title">Hard Work</span>
        <p class="pillar-text">Le travail ne ment pas. Ce qui est construit à la sueur du front a une valeur que personne ne peut effacer.</p>
      </div>
      <div class="pillar reveal">
        <div class="pillar-bg-num">3</div>
        <div class="pillar-bar"></div>
        <span class="pillar-title">Faith</span>
        <p class="pillar-text">Croire en quelque chose de plus grand. La foi comme fondation de chaque décision, de chaque mouvement.</p>
      </div>
    </div>
  </div>
</section>

<!-- NEWSLETTER -->

<section class="newsletter">
  <span class="label reveal">Restez connectés</span>
  <span class="display-title reveal">NEWSLETTER</span>
  <p class="newsletter-sub reveal">Ne manquez rien : nouvelles collections & offres exclusives en avant-première.</p>
  <div class="newsletter-form reveal">
    <input type="email" class="newsletter-input" placeholder="Votre adresse e-mail" required>
    <button class="newsletter-submit" type="submit">S'inscrire</button>
  </div>
</section>

<!-- FOOTER -->

<footer>
  <div class="footer-top">
    <div class="footer-brand reveal">
      <a href="#" class="footer-brand-logo">SHŌRI</a>
      <p>Du streetwear qui raconte une histoire. Ambition, Hard Work, Faith — pas juste des mots, un mode de vie.</p>
      <a href="https://instagram.com/shori.hustle" class="social-link" target="_blank">
        <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.5">
          <rect x="2" y="2" width="20" height="20" rx="5"/>
          <circle cx="12" cy="12" r="5"/>
          <circle cx="17.5" cy="6.5" r="1" fill="currentColor" stroke="none"/>
        </svg>
        @shori.hustle
      </a>
    </div>
    <div class="footer-col reveal">
      <h4>Boutique</h4>
      <ul>
        <li><a href="#">Black Edition</a></li>
        <li><a href="#">Hoodie</a></li>
        <li><a href="#">Jogger</a></li>
        <li><a href="#">Packs</a></li>
      </ul>
    </div>
    <div class="footer-col reveal">
      <h4>Infos</h4>
      <ul>
        <li><a href="#">Notre histoire</a></li>
        <li><a href="#">Contact</a></li>
        <li><a href="#">Livraison</a></li>
        <li><a href="#">Confidentialité</a></li>
        <li><a href="#">Cookies</a></li>
      </ul>
    </div>
  </div>
  <div class="footer-bottom">
    <span class="footer-copy">© 2026, SHŌRI — Tous droits réservés</span>
    <div class="payment-icons">
      <div class="payment-icon">Visa</div>
      <div class="payment-icon">MC</div>
      <div class="payment-icon">Amex</div>
      <div class="payment-icon">Apple Pay</div>
      <div class="payment-icon">Bancontact</div>
    </div>
  </div>
</footer>

<script>
  // Cart functionality
  let cartCount = 0;
  const cartBtn = document.getElementById('cartBtn');
  
  // Add to cart buttons
  document.querySelectorAll('.add-cart-btn').forEach(btn => {
    btn.addEventListener('click', function() {
      const original = this.textContent;
      this.textContent = '✓ Ajouté';
      this.classList.add('added');
      
      // Update cart count
      cartCount++;
      cartBtn.textContent = `Panier (${cartCount})`;
      
      // Animate cart button
      cartBtn.style.transform = 'scale(1.1)';
      setTimeout(() => {
        cartBtn.style.transform = 'scale(1)';
      }, 200);
      
      setTimeout(() => {
        this.textContent = original;
        this.classList.remove('added');
      }, 1800);
    });
  });

  // Size selection
  document.querySelectorAll('.product-card').forEach(card => {
    card.querySelectorAll('.size-dot').forEach(dot => {
      dot.addEventListener('click', function() {
        card.querySelectorAll('.size-dot').forEach(s => s.classList.remove('active'));
        this.classList.add('active');
      });
    });
  });

  // Navbar scroll effect
  const navbar = document.getElementById('navbar');
  window.addEventListener('scroll', () => {
    if (window.scrollY > 50) {
      navbar.classList.add('scrolled');
    } else {
      navbar.classList.remove('scrolled');
    }
  });

  // Intersection Observer for reveal animations
  const observerOptions = {
    threshold: 0.1,
    rootMargin: '0px 0px -50px 0px'
  };

  const observer = new IntersectionObserver((entries) => {
    entries.forEach(entry => {
      if (entry.isIntersecting) {
        entry.target.classList.add('active');
      }
    });
  }, observerOptions);

  document.querySelectorAll('.reveal').forEach(el => {
    observer.observe(el);
  });

  // Smooth scroll for anchor links
  document.querySelectorAll('a[href^="#"]').forEach(anchor => {
    anchor.addEventListener('click', function(e) {
      e.preventDefault();
      const target = document.querySelector(this.getAttribute('href'));
      if (target) {
        target.scrollIntoView({
          behavior: 'smooth',
          block: 'start'
        });
      }
    });
  });

  // Newsletter form
  document.querySelector('.newsletter-form').addEventListener('submit', function(e) {
    e.preventDefault();
    const input = this.querySelector('.newsletter-input');
    const btn = this.querySelector('.newsletter-submit');
    
    if (input.value) {
      const originalText = btn.textContent;
      btn.textContent = '✓ Inscrit';
      btn.style.background = 'var(--gold)';
      input.value = '';
      
      setTimeout(() => {
        btn.textContent = originalText;
        btn.style.background = '';
      }, 2000);
    }
  });
</script>

</body>
</html>
