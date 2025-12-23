---
# Only the main Sass file needs front matter (the dashes are enough)
---

@import "minimal-mistakes/skins/{{ site.minimal_mistakes_skin | default: 'default' }}";
@import "minimal-mistakes";

/* ===== CUSTOM CV STYLES ===== */

.cv-hero {
  padding: 1.25rem 0 0.25rem;
}

.cv-title {
  font-size: 2.0rem;
  font-weight: 800;
  letter-spacing: -0.02em;
  margin: 0;
}

.cv-subtitle {
  font-size: 1.05rem;
  opacity: 0.85;
  margin-top: 0.25rem;
}

.cv-badges {
  display: flex;
  flex-wrap: wrap;
  gap: .5rem;
  margin: .9rem 0 0;
}

.cv-badge {
  display: inline-flex;
  align-items: center;
  gap: .5rem;
  padding: .45rem .75rem;
  border-radius: 999px;
  border: 1px solid rgba(120,120,120,.25);
  background: rgba(120,120,120,.06);
  text-decoration: none !important;
}

.cv-badge i {
  width: 1.1rem;
}

/* Icon animations */
@keyframes cv-float {
  0% { transform: translateY(0); }
  50% { transform: translateY(-3px); }
  100% { transform: translateY(0); }
}

@keyframes cv-pulse {
  0% { transform: scale(1); }
  50% { transform: scale(1.08); }
  100% { transform: scale(1); }
}

.cv-badge i {
  animation: cv-float 2.4s ease-in-out infinite;
  transform-origin: center;
}

.cv-badge:hover i {
  animation: cv-pulse .55s ease-in-out 1;
}

.cv-section-title {
  display: flex;
  align-items: center;
  gap: .6rem;
  margin-top: 1.8rem;
}

.cv-section-title i {
  width: 1.2rem;
}

.cv-card {
  border: 1px solid rgba(120,120,120,.18);
  border-radius: 16px;
  padding: 1rem 1rem .75rem;
  margin: .8rem 0;
  background: rgba(120,120,120,.03);
}

.cv-meta {
  display: flex;
  flex-wrap: wrap;
  gap: .5rem .8rem;
  opacity: .85;
  font-size: .95rem;
  margin-top: .25rem;
}

.cv-meta span i {
  width: 1.1rem;
}

.cv-list {
  margin: .65rem 0 .25rem;
}

.cv-list li {
  margin: .28rem 0;
}
