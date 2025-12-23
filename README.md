---
title: "CV"
permalink: /README/
layout: single
classes: wide
---

<style>
/* ===== One-file CV style (only this .md) ===== */
:root{
  --bd: rgba(140,140,140,.22);
  --bg: rgba(120,120,120,.06);
  --bg2: rgba(120,120,120,.03);
  --shadow: 0 14px 34px rgba(0,0,0,.16);
  --r: 18px;
}
.page__content{ font-size: 1rem; line-height: 1.68; }
.cv-wrap{ max-width: 1020px; margin: 0 auto; }

.cv-hero{
  position: relative;
  padding: 22px 18px 16px;
  border: 1px solid var(--bd);
  border-radius: var(--r);
  background: linear-gradient(135deg, var(--bg), var(--bg2));
  box-shadow: var(--shadow);
  overflow: hidden;
}
.cv-hero:before{
  content:"";
  position:absolute; inset:-160px -130px auto auto;
  width: 330px; height: 330px;
  background: radial-gradient(circle, rgba(170,170,170,.18), transparent 60%);
  transform: rotate(12deg);
}
.cv-name{
  margin: 0;
  font-size: clamp(1.85rem, 3vw, 2.45rem);
  font-weight: 900;
  letter-spacing: -0.02em;
}
.cv-role{
  margin: 6px 0 10px;
  font-size: 1.05rem;
  opacity: .86;
}
.cv-summary{ margin: 10px 0 0; opacity: .92; }

.cv-row{
  display: grid;
  grid-template-columns: 1fr;
  gap: 12px;
  margin-top: 14px;
}
@media (min-width: 920px){
  .cv-row.two{ grid-template-columns: 1.1fr .9fr; }
}

.cv-chips{ display:flex; flex-wrap:wrap; gap:10px; margin: 12px 0 0; }
.cv-chip, .cv-btn{
  display:inline-flex; align-items:center; gap:10px;
  padding: 9px 12px;
  border-radius: 999px;
  border: 1px solid var(--bd);
  background: rgba(120,120,120,.07);
  text-decoration: none !important;
  max-width: 100%;
  color: inherit !important;
  font-weight: 700;
}
.cv-btn{ padding: 10px 12px; }
.cv-btn:hover, .cv-chip:hover{
  transform: translateY(-1px);
  box-shadow: 0 12px 26px rgba(0,0,0,.14);
}

.cv-ico{
  width: 30px; height: 30px; min-width: 30px;
  display:grid; place-items:center;
  border-radius: 12px;
  background: rgba(120,120,120,.10);
  border: 1px solid rgba(140,140,140,.22);
  transform-origin:center;
  animation: cv-float 2.4s ease-in-out infinite;
}
.cv-chip:hover .cv-ico, .cv-btn:hover .cv-ico{ animation: cv-pulse .55s ease-in-out 1; }

@keyframes cv-float{ 0%{transform:translateY(0)} 50%{transform:translateY(-3px)} 100%{transform:translateY(0)} }
@keyframes cv-pulse{ 0%{transform:scale(1)} 50%{transform:scale(1.12)} 100%{transform:scale(1)} }

.cv-h2{
  display:flex; align-items:center; gap:10px;
  margin: 22px 2px 10px;
  font-size: 1.15rem;
  font-weight: 900;
}
.cv-dot{
  width: 10px; height: 10px; border-radius: 999px;
  background: rgba(160,160,160,.65);
  box-shadow: 0 0 0 6px rgba(160,160,160,.10
