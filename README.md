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
  box-shadow: 0 0 0 6px rgba(160,160,160,.10);
}

.cv-card{
  border: 1px solid var(--bd);
  border-radius: var(--r);
  background: rgba(120,120,120,.05);
  box-shadow: 0 10px 22px rgba(0,0,0,.12);
  padding: 14px 14px 10px;
}
.cv-card h3{ margin: 0 0 6px; font-size: 1.05rem; }
.cv-meta{ display:flex; flex-wrap:wrap; gap:10px; opacity: .86; font-size: .93rem; margin-bottom: 10px; }
.cv-tags{ display:flex; flex-wrap:wrap; gap:8px; margin-top: 10px; }
.cv-tag{
  padding: 6px 10px; border-radius: 999px;
  border: 1px solid rgba(140,140,140,.22);
  background: rgba(120,120,120,.06);
  font-size: .9rem;
}
.cv-list{ margin: 10px 0 0 18px; }
.cv-list li{ margin: 6px 0; }

.cv-timeline{ position: relative; padding-left: 16px; }
.cv-timeline:before{
  content:""; position:absolute; left: 7px; top: 6px; bottom: 6px;
  width: 2px; background: rgba(150,150,150,.28);
}
.cv-item{ position: relative; margin: 12px 0; padding-left: 14px; }
.cv-item:before{
  content:""; position:absolute; left: -2px; top: 14px;
  width: 18px; height: 18px; border-radius: 999px;
  background: rgba(150,150,150,.25);
  border: 1px solid rgba(150,150,150,.35);
  box-shadow: 0 0 0 6px rgba(150,150,150,.10);
}
.cv-item .cv-card{ margin-left: 6px; }

.cv-link{
  text-decoration: none !important;
  border-bottom: 1px dashed rgba(160,160,160,.55);
  color: inherit !important;
}
.cv-link:hover{ border-bottom-style: solid; }

.cv-reveal{ opacity: 0; transform: translateY(10px); transition: .55s ease; }
.cv-reveal.is-in{ opacity: 1; transform: translateY(0); }

@media (prefers-reduced-motion: reduce){
  .cv-ico{ animation: none !important; }
  .cv-reveal{ transition: none !important; }
  .cv-btn:hover, .cv-chip:hover{ transform:none; }
}
</style>

<div class="cv-wrap">

<!-- HERO -->
<section class="cv-hero cv-reveal">
  <h1 class="cv-name">Đỗ Công Chức</h1>
  <div class="cv-role">Lập trình viên Flutter • BLoC / GetX • Clean Architecture</div>

  <p class="cv-summary">
    <strong>Mục tiêu hiện tại:</strong> Muốn tìm một nơi để học tập và làm việc để tích lũy kinh nghiệm chuyên môn, phát triển bản thân ngày càng tốt hơn.<br/>
    <strong>Mục tiêu tương lai:</strong> Trở thành một lập trình viên Flutter xuất sắc, đóng góp hết sức mình cho công ty và hướng tới dẫn dắt team/nhóm của riêng mình trong ~12 năm tới.
  </p>

  <div class="cv-chips" style="margin-top:14px;">
    <a class="cv-btn" href="https://github.com/chucdo" target="_blank" rel="noopener"><span class="cv-ico">🐙</span>GitHub</a>
    <a class="cv-btn" href="mailto:chucdo298@gmail.com"><span class="cv-ico">✉️</span>Email</a>
    <a class="cv-btn" href="tel:+84971856081"><span class="cv-ico">📞</span>Gọi</a>
  </div>

  <div class="cv-chips">
    <a class="cv-chip" href="tel:+84971856081"><span class="cv-ico">📱</span><span>0971 856 081</span></a>
    <a class="cv-chip" href="mailto:chucdo298@gmail.com"><span class="cv-ico">✉️</span><span>chucdo298@gmail.com</span></a>
    <a class="cv-chip" href="https://www.facebook.com/tlukirito/" target="_blank" rel="noopener"><span class="cv-ico">🌐</span><span>facebook.com/tlukirito</span></a>
    <span class="cv-chip"><span class="cv-ico">🎂</span><span>29/08/2000</span></span>
    <span class="cv-chip"><span class="cv-ico">📍</span><span>Đại Thành, Quốc Oai, Hà Nội</span></span>
  </div>
</section>

<!-- HIGHLIGHTS + SKILLS -->
<section>
  <div class="cv-h2 cv-reveal"><span class="cv-dot"></span> Tổng quan</div>

  <div class="cv-row two">
    <div class="cv-card cv-reveal">
      <h3>Điểm mạnh</h3>
      <ul class="cv-list">
        <li>State management: <strong>BLoC (chính)</strong>, GetX, Provider.</li>
        <li>Clean Architecture, SOLID, Design Patterns, Dependency Injection (<code>get_it</code>, <code>injectable</code>).</li>
        <li>Tối ưu hiệu năng: rasterization/batching/profiler; tối ưu bộ nhớ.</li>
        <li>Code generation: <code>build_runner</code>, <code>json_serializable</code>, <code>freezed</code>.</li>
        <li>Làm được cả phần “khó”: ads bidding/tracking, IAP, bridge native (Android / iOS SwiftUI/UIView).</li>
      </ul>
      <div class="cv-tags">
        <span class="cv-tag">⚡ Performance</span>
        <span class="cv-tag">🏗️ Clean Architecture</span>
        <span class="cv-tag">🧩 DI</span>
        <span class="cv-tag">🛒 IAP</span>
        <span class="cv-tag">📈 Ads / Bidding</span>
      </div>
    </div>

    <div class="cv-card cv-reveal">
      <h3>Tools & Collaboration</h3>
      <ul class="cv-list">
        <li>Git / GitFlow</li>
        <li>Jira, Trello</li>
        <li>Figma</li>
        <li>Postman, Swagger</li>
        <li>Visual Studio Code, Android Studio</li>
      </ul>
      <div class="cv-tags">
        <span class="cv-tag">✅ Review code</span>
        <span class="cv-tag">🤝 Mentor fresher</span>
      </div>
    </div>
  </div>
</section>

<!-- EXPERIENCE -->
<section>
  <div class="cv-h2 cv-reveal"><span class="cv-dot"></span> Kinh nghiệm làm việc</div>

  <div class="cv-timeline">

    <div class="cv-item cv-reveal">
      <div class="cv-card">
        <h3>Công ty cổ phần đầu tư và phát triển Kztek (03/2024 – Hiện tại) — Flutter Developer</h3>
        <div class="cv-meta">
          <span>👤 1 dev chính</span>
          <span>🧠 BLoC</span>
          <span>🏗️ Clean Architecture</span>
        </div>

        <ul class="cv-list">
          <li><strong>Kz-ERP</strong>: chấm công theo vị trí, lịch sử chấm công, tạo/duyệt đơn nghỉ phép & đi muộn, quản lý lịch làm việc.</li>
          <li><strong>KParking</strong>: quản lý bãi đỗ xe; vào/ra bằng nhận dạng biển số (camera), quẹt thẻ NFC/UHF, QR; in vé; dashboard doanh thu & biểu đồ tuần/tháng.</li>
          <li><strong>Meeting Master</strong>: quản lý phòng họp cho cơ quan (Hà Tĩnh) — BLoC + Clean Architecture.</li>
          <li><strong>Build thư viện RFID</strong>: <a class="cv-link" href="https://github.com/chucdo/Urovo_scan" target="_blank" rel="noopener">github.com/chucdo/Urovo_scan</a></li>
          <li><strong>Base Clean Architecture</strong>: <a class="cv-link" href="https://github.com/chucdo/flutter_clean_base" target="_blank" rel="noopener">github.com/chucdo/flutter_clean_base</a></li>
        </ul>
      </div>
    </div>

    <div class="cv-item cv-reveal">
      <div class="cv-card">
        <h3>Volio Group (01/2023 – 03/2024) — Flutter Developer</h3>
        <div class="cv-meta">
          <span>🎯 GetX</span>
          <span>📈 Ads / Tracking / Bidding</span>
          <span>🛒 In-App Purchase</span>
        </div>

        <ul class="cv-list">
          <li><strong>Sudoku App</strong>: 3 chế độ (solo / vs AI / 1v1), kết bạn – mời bạn bè, animation, AdMob.</li>

          <li>
            <strong>Floralwhisper – Lovely language</strong> (2 dev):
            tạo wallpaper từ sticker, quay video chèn sticker, trend filter, lưu & chia sẻ (TikTok/Facebook/Instagram…),
            bridge iOS (nhúng UIKit vào Flutter view), Ads + tracking + bidding + IAP.
            <br/>
            App Store:
            <a class="cv-link" href="https://apps.apple.com/vn/app/floralwhisper-lovely-language/id6504385346?l=vi" target="_blank" rel="noopener">link</a>
            <br/>
            (Đỉnh điểm: ~30k users dùng đồng thời theo ghi nhận nội bộ.)
          </li>

          <li>
            <strong>Zumee – lockscreen drawing</strong> (2 dev):
            kết nối bạn bè để vẽ trong Room, QR scan, Ads + tracking + bidding + IAP.
            App Store:
            <a class="cv-link" href="https://apps.apple.com/vn/app/zumee-lockscreen-drawing/id6502684901" target="_blank" rel="noopener">link</a>
          </li>

          <li>
            <strong>Skizz – Drawing Together</strong> (1 dev):
            vẽ sáng tạo trong Room (người lạ/bạn bè), QR, tuỳ biến nét bút & sticker, Ads + tracking + bidding + IAP.
            App Store:
            <a class="cv-link" href="https://apps.apple.com/vn/app/skizz-drawing-together/id6505097805" target="_blank" rel="noopener">link</a>
          </li>

          <li>
            <strong>Winx: Live Butterfly Effect</strong> (1 dev):
            quay video với hiệu ứng bướm; cần code <strong>SwiftUI</strong> để tách nền/chủ thể rồi bridge sang Flutter; thêm/cắt nhạc, lưu & chia sẻ.
            App Store:
            <a class="cv-link" href="https://apps.apple.com/vn/app/winx-live-butterfly-efftect/id6612029564" target="_blank" rel="noopener">link</a>
          </li>

          <li>
            <strong>Dựng base cho team</strong>:
            bidding Ads (Applovin, Mintegral, Pangle, DTExchange, Liftoff, Meta…), Appsflyer SDK,
            impression-level revenue, IAP connector, uninstall event, promoted IAP, share Facebook/IG…
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
          <li>
            <strong>SmartLight: Blue filter, Relax</strong>:
            bộ lọc màn hình, kindle light, selfie light, nghe nhạc thư giãn; nhiều custom UI & đụng native Android.
            Google Play:
            <a class="cv-link" href="https://play.google.com/store/apps/details?id=com.abi.booklight&hl=vi&gl=US" target="_blank" rel="noopener">link</a>
          </li>

          <li>
            <strong>Al-plancha</strong>:
            đặt sản phẩm, cập nhật vị trí realtime, theo dõi đơn hàng, thanh toán PayPal.
            Google Play:
            <a class="cv-link" href="https://play.google.com/store/apps/details?id=com.cfi.la_plancha" target="_blank" rel="noopener">link</a>
          </li>

          <li>
            <strong>ISticker - Sticker Maker</strong>:
            tạo sticker (scale/remove/flip/rotate/drag), IAP, ads + tracking + bidding;
            hỗ trợ kỹ thuật & code các tính năng khó cho app.
            Google Play:
            <a class="cv-link" href="https://play.google.com/store/apps/details?id=com.isticker.sticker.maker&hl=en-VN" target="_blank" rel="noopener">link</a>
          </li>
        </ul>
      </div>
    </div>

    <div class="cv-item cv-reveal">
      <div class="cv-card">
        <h3>Team cá nhân (07/2023 – 12/2023) — Dự án cá nhân</h3>
        <div class="cv-meta">
          <span>🧠 BLoC</span>
          <span>📹 Chat / Video call</span>
        </div>

        <ul class="cv-list">
          <li>
            <strong>Hello Job</strong>:
            kết nối giữa người cần xuất khẩu lao động và người tuyển dụng, chat/video call,
            bài đăng tuyển dụng & bình luận, quản lý hồ sơ người lao động.
            Google Play:
            <a class="cv-link" href="https://play.google.com/store/apps/details?id=org.nativescript.HelloJob" target="_blank" rel="noopener">link</a>
          </li>
        </ul>
      </div>
    </div>

    <div class="cv-item cv-reveal">
      <div class="cv-card">
        <h3>SoftDreams (03/2022 – 01/2023) — Flutter Developer</h3>
        <div class="cv-meta">
          <span>👥 2–3 thành viên</span>
          <span>🎯 GetX / BLoC</span>
          <span>🗺️ Google Maps</span>
        </div>

        <ul class="cv-list">
          <li>
            <strong>Speed</strong> (2 dev / ~2 tháng):
            tích hợp Google Maps, tính quãng đường/thời gian A→B, tìm tài xế xung quanh trong bán kính ~5km
            (không public theo yêu cầu khách hàng).
          </li>
          <li>
            <strong>Live218</strong> (2 dev):
            bảo trì & nâng cấp chức năng/UI theo yêu cầu; dùng BLoC cho state management.
          </li>
          <li>
            <strong>App theo dõi chu kì kinh</strong> (3 dev / ~2 tháng):
            phát triển tính năng & UI, quản lý state bằng GetX.
          </li>
          <li>
            <strong>EasyHrm</strong>:
            điểm danh (khuôn mặt, WiFi, GPS), chữ ký số, lịch sử công, tính lương, ngày nghỉ,
            quản lý đơn nghỉ ca/ngày/dài hạn/công tác; hỗ trợ thực tập sinh & fresher (mentor/review code).
            <br/>
            App Store: <a class="cv-link" href="https://apps.apple.com/vn/app/easyhrm/id1666225914?l=vi" target="_blank" rel="noopener">link</a> •
            Google Play: <a class="cv-link" href="https://play.google.com/store/search?q=easyHrm&c=apps&hl=en-VN" target="_blank" rel="noopener">link</a>
          </li>
        </ul>
      </div>
    </div>

  </div>
</section>

<!-- EDUCATION + HOBBIES -->
<section>
  <div class="cv-row two">
    <div class="cv-card cv-reveal">
      <div class="cv-h2" style="margin-top:0;"><span class="cv-dot"></span> Học vấn</div>
      <p style="margin:0;">
        <strong>Đại học Thủy Lợi</strong> (08/2018 – 01/2023) — Công nghệ thông tin
      </p>
      <ul class="cv-list">
        <li>Thường làm lead nhóm nhỏ: phân chia nhiệm vụ & đảm nhiệm phần code chính trong bài tập/dự án môn học.</li>
      </ul>
    </div>

    <div class="cv-card cv-reveal">
      <div class="cv-h2" style="margin-top:0;"><span class="cv-dot"></span> Sở thích</div>
      <ul class="cv-list">
        <li>Chơi thể thao (tăng sức bền, giảm stress)</li>
        <li>Chơi game & nghiên cứu cơ chế vận hành</li>
        <li>Lập trình thử nghiệm dự án nhỏ liên quan video/audio</li>
        <li>Xem phim & lên ý tưởng sáng tạo cho TikTok/YouTube</li>
        <li>Tìm hiểu công nghệ mới: Flutter, Swift, backend (.NET, Go, Python)</li>
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
