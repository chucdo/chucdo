---
title: "CV"
permalink: /cv/
layout: single
classes: wide
---

<style>
/* ===== One-file CV style (no extra files) ===== */
:root{
  --cv-bg: rgba(255,255,255,.06);
  --cv-bd: rgba(140,140,140,.22);
  --cv-tx: rgba(255,255,255,.88);
  --cv-dim: rgba(255,255,255,.72);
  --cv-shadow: 0 12px 28px rgba(0,0,0,.18);
  --cv-radius: 18px;
}
.page__content { font-size: 1rem; line-height: 1.65; }
.cv-wrap{ max-width: 980px; margin: 0 auto; }

.cv-hero{
  position: relative;
  padding: 22px 18px 16px;
  border: 1px solid var(--cv-bd);
  border-radius: var(--cv-radius);
  background: linear-gradient(135deg, rgba(120,120,120,.10), rgba(120,120,120,.03));
  box-shadow: var(--cv-shadow);
  overflow: hidden;
}
.cv-hero:before{
  content:"";
  position:absolute; inset:-140px -120px auto auto;
  width: 280px; height: 280px;
  background: radial-gradient(circle, rgba(160,160,160,.18), transparent 65%);
  filter: blur(0px);
  transform: rotate(12deg);
}
.cv-name{
  margin: 0;
  font-size: clamp(1.8rem, 3vw, 2.35rem);
  font-weight: 900;
  letter-spacing: -0.02em;
}
.cv-role{
  margin: 6px 0 10px;
  font-size: 1.05rem;
  opacity: .85;
}
.cv-summary{
  margin: 10px 0 0;
  opacity: .92;
}
.cv-cta{
  display:flex; flex-wrap: wrap; gap: 10px;
  margin-top: 14px;
}
.cv-btn{
  display:inline-flex; align-items:center; gap:10px;
  padding: 10px 12px;
  border-radius: 999px;
  border: 1px solid var(--cv-bd);
  background: rgba(120,120,120,.08);
  text-decoration: none !important;
  font-weight: 700;
}
.cv-btn:hover{ transform: translateY(-1px); box-shadow: 0 10px 22px rgba(0,0,0,.16); }

.cv-chips{
  display:flex; flex-wrap:wrap; gap:10px;
  margin: 14px 0 0;
}
.cv-chip{
  display:inline-flex; align-items:center; gap:10px;
  padding: 9px 12px;
  border-radius: 999px;
  border: 1px solid var(--cv-bd);
  background: rgba(120,120,120,.06);
  text-decoration: none !important;
  max-width: 100%;
}
.cv-chip small{ opacity:.8; }
.cv-ico{
  width: 30px; height: 30px; min-width: 30px;
  display:grid; place-items:center;
  border-radius: 12px;
  background: rgba(120,120,120,.10);
  border: 1px solid rgba(140,140,140,.22);
  transform-origin:center;
  animation: cv-float 2.4s ease-in-out infinite;
}
.cv-chip:hover .cv-ico{ animation: cv-pulse .55s ease-in-out 1; }

@keyframes cv-float{ 0%{transform:translateY(0)} 50%{transform:translateY(-3px)} 100%{transform:translateY(0)} }
@keyframes cv-pulse{ 0%{transform:scale(1)} 50%{transform:scale(1.12)} 100%{transform:scale(1)} }

.cv-section{
  margin-top: 18px;
}
.cv-h2{
  display:flex; align-items:center; gap:10px;
  margin: 22px 2px 10px;
  font-size: 1.15rem;
  font-weight: 900;
}
.cv-dot{
  width: 10px; height: 10px; border-radius: 999px;
  background: rgba(160,160,160,.65);
  box-shadow: 0 0 0 6px rgba(160,160,160,.10);
}

.cv-grid{
  display:grid;
  grid-template-columns: 1fr;
  gap: 12px;
}
@media (min-width: 900px){
  .cv-grid.two{ grid-template-columns: 1.1fr .9fr; }
}

.cv-card{
  border: 1px solid var(--cv-bd);
  border-radius: var(--cv-radius);
  background: rgba(120,120,120,.05);
  box-shadow: 0 10px 22px rgba(0,0,0,.12);
  padding: 14px 14px 10px;
}
.cv-card h3{ margin: 0 0 6px; font-size: 1.05rem; }
.cv-meta{
  display:flex; flex-wrap:wrap; gap:10px;
  opacity: .86;
  font-size: .93rem;
  margin-bottom: 10px;
}
.cv-tags{
  display:flex; flex-wrap:wrap; gap:8px;
  margin-top: 10px;
}
.cv-tag{
  padding: 6px 10px;
  border-radius: 999px;
  border: 1px solid rgba(140,140,140,.22);
  background: rgba(120,120,120,.06);
  font-size: .9rem;
}
.cv-list{ margin: 10px 0 0 18px; }
.cv-list li{ margin: 6px 0; }

.cv-timeline{
  position: relative;
  padding-left: 16px;
}
.cv-timeline:before{
  content:"";
  position:absolute; left: 7px; top: 6px; bottom: 6px;
  width: 2px;
  background: rgba(150,150,150,.28);
}
.cv-item{
  position: relative;
  margin: 12px 0;
  padding-left: 14px;
}
.cv-item:before{
  content:"";
  position:absolute; left: -2px; top: 14px;
  width: 18px; height: 18px;
  border-radius: 999px;
  background: rgba(150,150,150,.25);
  border: 1px solid rgba(150,150,150,.35);
  box-shadow: 0 0 0 6px rgba(150,150,150,.10);
}
.cv-item .cv-card{ margin-left: 6px; }

.cv-link{
  text-decoration: none !important;
  border-bottom: 1px dashed rgba(160,160,160,.55);
}
.cv-link:hover{ border-bottom-style: solid; }

.cv-reveal{ opacity: 0; transform: translateY(10px); transition: .55s ease; }
.cv-reveal.is-in{ opacity: 1; transform: translateY(0); }

@media (prefers-reduced-motion: reduce){
  .cv-ico{ animation: none !important; }
  .cv-reveal{ transition: none !important; }
  .cv-btn:hover{ transform:none; }
}
</style>

<div class="cv-wrap">

<!-- HERO -->
<section class="cv-hero cv-reveal">
  <h1 class="cv-name">Đỗ Công Chức</h1>
  <div class="cv-role">Lập trình viên Flutter • BLoC / GetX • Clean Architecture</div>

  <p class="cv-summary">
    <strong>Mục tiêu hiện tại:</strong> tìm môi trường học hỏi và làm việc để tích lũy kinh nghiệm chuyên môn, phát triển bền vững. <br/>
    <strong>Mục tiêu tương lai:</strong> trở thành Flutter developer xuất sắc và hướng tới vị trí lead/mentor cho team.
  </p>

  <div class="cv-cta">
    <a class="cv-btn" href="https://github.com/chucdo" target="_blank" rel="noopener">
      <span class="cv-ico">🐙</span> GitHub
    </a>
    <a class="cv-btn" href="mailto:chucdo298@gmail.com">
      <span class="cv-ico">✉️</span> Email
    </a>
    <a class="cv-btn" href="tel:+84971856081">
      <span class="cv-ico">📞</span> Gọi
    </a>
  </div>

  <div class="cv-chips">
    <a class="cv-chip" href="tel:+84971856081"><span class="cv-ico">📱</span><span>0971 856 081</span></a>
    <a class="cv-chip" href="mailto:chucdo298@gmail.com"><span class="cv-ico">✉️</span><span>chucdo298@gmail.com</span></a>
    <a class="cv-chip" href="https://www.facebook.com/tlukirito/" target="_blank" rel="noopener"><span class="cv-ico">🌐</span><span>facebook.com/tlukirito</span></a>
    <span class="cv-chip"><span class="cv-ico">🎂</span><span>29/08/2000</span></span>
    <span class="cv-chip"><span class="cv-ico">📍</span><span>Đại Thành, Quốc Oai, Hà Nội</span></span>
  </div>
</section>

<!-- SKILLS -->
<section class="cv-section">
  <div class="cv-h2 cv-reveal"><span class="cv-dot"></span> Kỹ năng</div>

  <div class="cv-grid two">
    <div class="cv-card cv-reveal">
      <h3>State management</h3>
      <ul class="cv-list">
        <li><strong>BLoC</strong> (chính), GetX, Provider</li>
      </ul>

      <h3 style="margin-top:12px;">Architecture & Engineering</h3>
      <ul class="cv-list">
        <li>Clean Architecture, SOLID, Design Patterns</li>
        <li>Dependency Injection: <code>get_it</code>, <code>injectable</code></li>
        <li>Performance: rasterization, batching, profiler</li>
        <li>Memory optimization</li>
        <li>Codegen: <code>build_runner</code>, <code>json_serializable</code>, <code>freezed</code></li>
      </ul>
    </div>

    <div class="cv-card cv-reveal">
      <h3>Tools & Collaboration</h3>
      <ul class="cv-list">
        <li>Git / GitFlow</li>
        <li>Jira, Trello</li>
        <li>Figma</li>
        <li>Postman, Swagger</li>
        <li>VS Code, Android Studio</li>
      </ul>

      <div class="cv-tags">
        <span class="cv-tag">🚀 Clean Code</span>
        <span class="cv-tag">🧩 DI</span>
        <span class="cv-tag">⚡ Performance</span>
        <span class="cv-tag">🧠 Memory</span>
      </div>
    </div>
  </div>
</section>

<!-- EXPERIENCE TIMELINE -->
<section class="cv-section">
  <div class="cv-h2 cv-reveal"><span class="cv-dot"></span> Kinh nghiệm</div>

  <div class="cv-timeline">

    <div class="cv-item cv-reveal">
      <div class="cv-card">
        <h3>Kztek (03/2024 – Hiện tại) — Flutter Developer</h3>
        <div class="cv-meta">
          <span>👤 Thường 1 dev chính</span>
          <span>🧠 BLoC</span>
          <span>🏗️ Clean Architecture</span>
        </div>
        <ul class="cv-list">
          <li><strong>Kz-ERP</strong>: chấm công theo vị trí, lịch sử, đơn nghỉ phép/đi muộn, lịch làm việc.</li>
          <li><strong>KParking</strong>: quản lý lượt xe ra/vào; vào/ra bằng LPR camera, NFC/UHF, QR; in vé; dashboard doanh thu tuần/tháng.</li>
          <li><strong>Meeting Master</strong>: quản lý phòng họp cho cơ quan (Hà Tĩnh) — BLoC + Clean Architecture.</li>
        </ul>
        <div class="cv-tags">
          <a class="cv-tag cv-link" href="https://github.com/chucdo/Urovo_scan" target="_blank" rel="noopener">🔧 RFID lib (Repo)</a>
          <a class="cv-tag cv-link" href="https://github.com/chucdo/flutter_clean_base" target="_blank" rel="noopener">🏗️ Clean Base (Repo)</a>
        </div>
      </div>
    </div>

    <div class="cv-item cv-reveal">
      <div class="cv-card">
        <h3>Volio Group (01/2023 – 03/2024) — Flutter Developer</h3>
        <div class="cv-meta">
          <span>🎯 GetX</span>
          <span>📈 Ads / bidding / tracking</span>
          <span>🛒 IAP</span>
        </div>
        <ul class="cv-list">
          <li><strong>Floralwhisper</strong>: tạo wallpaper từ sticker, quay video chèn sticker, share MXH; iOS app.
            <a class="cv-link" href="https://apps.apple.com/vn/app/floralwhisper-lovely-language/id6504385346?l=vi" target="_blank" rel="noopener">App Store</a>
          </li>
          <li><strong>Zumee</strong>: vẽ trong room, QR scan, ads & IAP.
            <a class="cv-link" href="https://apps.apple.com/vn/app/zumee-lockscreen-drawing/id6502684901" target="_blank" rel="noopener">App Store</a>
          </li>
          <li><strong>Skizz</strong>: vẽ cùng nhau (1 dev), ads & IAP.
            <a class="cv-link" href="https://apps.apple.com/vn/app/skizz-drawing-together/id6505097805" target="_blank" rel="noopener">App Store</a>
          </li>
          <li><strong>Winx</strong>: effect video — SwiftUI tách nền/chủ thể rồi bridge sang Flutter.
            <a class="cv-link" href="https://apps.apple.com/vn/app/winx-live-butterfly-efftect/id6612029564" target="_blank" rel="noopener">App Store</a>
          </li>
          <li><strong>Dựng base cho team</strong>: mediation + revenue impression + Appsflyer + IAP connector + uninstall event...</li>
        </ul>
      </div>
    </div>

    <div class="cv-item cv-reveal">
      <div class="cv-card">
        <h3>SoftDreams (03/2022 – 01/2023) — Flutter Developer</h3>
        <div class="cv-meta">
          <span>👥 1–3 dev</span>
          <span>🧠 GetX / BLoC</span>
          <span>🗺️ Maps</span>
        </div>
        <ul class="cv-list">
          <li><strong>Speed</strong>: Google Maps; tính quãng đường/thời gian; tìm tài xế trong bán kính ~5km (không public theo yêu cầu khách hàng).</li>
          <li><strong>Live218</strong>: bảo trì & nâng cấp web app; quản lý state bằng BLoC.</li>
          <li><strong>EasyHrm</strong>: điểm danh (face/wifi/gps), chữ ký số, lịch sử công, tính lương...
            <a class="cv-link" href="https://apps.apple.com/vn/app/easyhrm/id1666225914?l=vi" target="_blank" rel="noopener">App Store</a> •
            <a class="cv-link" href="https://play.google.com/store/search?q=easyHrm&c=apps&hl=en-VN" target="_blank" rel="noopener">Google Play</a>
          </li>
        </ul>
      </div>
    </div>

    <div class="cv-item cv-reveal">
      <div class="cv-card">
        <h3>Intes-Tech (Part-time 01/2024) — Flutter Developer</h3>
        <div class="cv-meta">
          <span>👤 1 dev chính</span>
          <span>🎯 GetX</span>
          <span>📱 Native Android</span>
        </div>
        <ul class="cv-list">
          <li><strong>SmartLight</strong>: blue filter/relax/music —
            <a class="cv-link" href="https://play.google.com/store/apps/details?id=com.abi.booklight&hl=vi&gl=US" target="_blank" rel="noopener">Google Play</a>
          </li>
          <li><strong>Al-plancha</strong>: order + realtime location + PayPal —
            <a class="cv-link" href="https://play.google.com/store/apps/details?id=com.cfi.la_plancha" target="_blank" rel="noopener">Google Play</a>
          </li>
          <li><strong>ISticker</strong>: sticker maker + IAP + ads/tracking/bidding —
            <a class="cv-link" href="https://play.google.com/store/apps/details?id=com.isticker.sticker.maker&hl=en-VN" target="_blank" rel="noopener">Google Play</a>
          </li>
        </ul>
      </div>
    </div>

    <div class="cv-item cv-reveal">
      <div class="cv-card">
        <h3>Team cá nhân (07/2023 – 12/2023) — Dự án cá nhân</h3>
        <div class="cv-meta">
          <span>🧠 BLoC</span>
          <span>📹 Video call</span>
        </div>
        <ul class="cv-list">
          <li><strong>Hello Job</strong>: kết nối XKLĐ, video call/chat, bài đăng & bình luận, quản lý hồ sơ —
            <a class="cv-link" href="https://play.google.com/store/apps/details?id=org.nativescript.HelloJob" target="_blank" rel="noopener">Google Play</a>
          </li>
        </ul>
      </div>
    </div>

  </div>
</section>

<!-- EDUCATION + HOBBIES -->
<section class="cv-section">
  <div class="cv-grid two">
    <div class="cv-card cv-reveal">
      <div class="cv-h2" style="margin-top:0;"><span class="cv-dot"></span> Học vấn</div>
      <p style="margin:0;"><strong>ĐH Thủy Lợi</strong> (08/2018 – 01/2023) — CNTT</p>
      <ul class="cv-list">
        <li>Thường làm lead nhóm nhỏ: chia task & đảm nhiệm phần code chính.</li>
      </ul>
    </div>

    <div class="cv-card cv-reveal">
      <div class="cv-h2" style="margin-top:0;"><span class="cv-dot"></span> Sở thích</div>
      <ul class="cv-list">
        <li>Thể thao, game & nghiên cứu cơ chế vận hành</li>
        <li>Thử nghiệm dự án video/audio</li>
        <li>Học công nghệ mới: Flutter, Swift, backend (.NET, Go, Python)</li>
      </ul>
    </div>
  </div>
</section>

</div>

<script>
/* reveal on scroll – all inside this md */
(function(){
  const els = document.querySelectorAll('.cv-reveal');
  if(!('IntersectionObserver' in window) || !els.length){
    els.forEach(e=>e.classList.add('is-in'));
    return;
  }
  const io = new IntersectionObserver((entries)=>{
    entries.forEach(en=>{
      if(en.isIntersecting){
        en.target.classList.add('is-in');
        io.unobserve(en.target);
      }
    });
  }, { threshold: 0.12 });
  els.forEach(el=>io.observe(el));
})();
</script>
