<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8"/>
<meta name="viewport" content="width=device-width, initial-scale=1.0"/>
<title>Nam An – Nâng Tầm Vẻ Đẹp Với Phẫu Thuật Thẩm Mỹ</title>
<link href="https://fonts.googleapis.com/css2?family=Cormorant+Garamond:ital,wght@0,500;0,600;0,700;1,500;1,600&family=Plus+Jakarta+Sans:wght@300;400;500;600&display=swap" rel="stylesheet"/>
<style>
*,*::before,*::after{box-sizing:border-box;margin:0;padding:0}

:root{
  --cream:#f6f1e8;
  --cream2:#ede8df;
  --terra:#d9664a;
  --terra2:#e07d60;
  --dark:#1e1510;
  --mid:#6b5c50;
  --light:#c0a898;
  --gold:#c9a96e;
  --white:#ffffff;
}

html{height:100%}
body{
  font-family:'Plus Jakarta Sans',sans-serif;
  
  /* Ảnh nền độc lập cho toàn bộ giao diện */
  background-image: url('https://benhvienthammynaman.com/wp-content/uploads/2026/05/Trang-mua-hang-1.png');
  background-size: cover;
  background-position: center center;
  background-repeat: no-repeat;
  background-attachment: fixed;
  
  color: var(--dark);
  overflow-y:auto;
}

/* ─── NAVBAR ────────────────────────────────────────── */
nav{
  position:fixed;top:0;left:0;right:0;z-index:200;
  display:flex;align-items:center;justify-content:space-between;
  padding:0 56px;
  height:70px;
  background:rgba(246,241,232,0.92);
  backdrop-filter:blur(16px);
  -webkit-backdrop-filter:blur(16px);
  border-bottom:1px solid rgba(201,169,110,.12);
  animation:navIn .65s cubic-bezier(.22,1,.36,1) both;
  will-change:auto;
}
@keyframes navIn{from{opacity:0;top:-70px}to{opacity:1;top:0}}

.logo{
  display:flex;align-items:center;
  text-decoration:none;
}

.nav-links{
  display:flex;align-items:center;gap:8px;
  list-style:none;
}
.nav-links li a{
  display:inline-block;
  padding:5px 14px;
  font-size:.85rem;font-weight:500;
  color:var(--mid);
  text-decoration:none;
  border-radius:20px;
  transition:all .25s;
}
.nav-links li a:hover{color:var(--dark);background:rgba(0,0,0,.05)}
.nav-links li a.active{
  background:var(--terra);
  color:#fff;
  box-shadow:0 3px 12px rgba(217,102,74,.3);
}

.nav-right{display:flex;align-items:center;gap:14px}
.btn-icon{
  width:38px;height:38px;border-radius:50%;
  border:1.5px solid rgba(107,92,80,.2);
  background:transparent;cursor:pointer;
  display:flex;align-items:center;justify-content:center;
  color:var(--mid);
  transition:all .28s;
}
.btn-icon:hover{background:var(--terra);border-color:var(--terra);color:#fff;transform:scale(1.07)}

.btn-appt{
  padding:9px 20px;border-radius:50px;border:none;cursor:pointer;
  background:var(--terra);color:#fff;
  font-family:'Plus Jakarta Sans',sans-serif;
  font-size:.82rem;font-weight:600;letter-spacing:.02em;
  box-shadow:0 4px 16px rgba(217,102,74,.32);
  transition:all .3s cubic-bezier(.22,1,.36,1);
  position:relative;overflow:hidden;
}
.btn-appt::after{
  content:'';position:absolute;inset:0;
  background:linear-gradient(90deg,transparent 0%,rgba(255,255,255,.18) 50%,transparent 100%);
  transform:translateX(-100%);
}
.btn-appt:hover{transform:translateY(-2px);box-shadow:0 8px 24px rgba(217,102,74,.4)}
.btn-appt:hover::after{animation:shimmer .6s ease forwards}
@keyframes shimmer{to{transform:translateX(200%)}}

/* ─── HERO SECTION ───────────────────────────────────── */
.hero{
  min-height:100vh;
  display:grid;
  grid-template-columns:1fr 1fr;
  padding:70px 0 0;
  position:relative;
  overflow:hidden;
}

.hero::before{
  content:'';position:absolute;inset:0;
  background: 
    radial-gradient(ellipse 60% 60% at 15% 50%, rgba(255,255,255,.4) 0%, transparent 80%),
    radial-gradient(ellipse 40% 40% at 85% 80%, rgba(217,102,74,.05) 0%, transparent 60%);
  pointer-events:none;
}

/* ── LEFT PANEL ── */
.hero-left{
  display:flex;flex-direction:column;justify-content:center;
  padding:0 56px 60px 56px;
  position:relative;z-index:2;
}

.headline{
  font-family:'Cormorant Garamond',serif;
  font-size:clamp(2rem,3.2vw,3.1rem);
  line-height:1.15;
  font-weight:700;
  color:var(--dark);
  position:relative;
  margin-bottom:20px;
  opacity:0;animation:upIn .8s .4s cubic-bezier(.22,1,.36,1) forwards;
}
.headline em{
  font-style:italic;color:var(--terra);
  position:relative;display:inline-block;
}
.headline em::after{
  content:'';position:absolute;
  left:0;bottom:-2px;right:0;height:2.5px;
  background:currentColor;border-radius:2px;
  transform:scaleX(0);transform-origin:left;
  animation:scaleX 1s 1.3s cubic-bezier(.22,1,.36,1) forwards;
}

.chip-face{
  display:inline-flex;align-items:center;justify-content:center;
  width:62px;height:34px;border-radius:30px;
  border:3px solid var(--white);
  box-shadow:0 6px 20px rgba(0,0,0,.15);
  overflow:hidden;
  vertical-align:top;
  position:relative;top:5px;
  margin:0 6px;
  flex-shrink:0;
  animation:chipPop .7s .9s cubic-bezier(.22,1,.36,1) both, floatY 4s 1.6s ease-in-out infinite;
}
.chip-face img{width:100%;height:100%;object-fit:cover}

.chip-syringe{
  display:inline-flex;align-items:center;justify-content:center;
  width:54px;height:28px;border-radius:30px;
  border:3px solid var(--white);
  box-shadow:0 6px 20px rgba(0,0,0,.12);
  overflow:hidden;
  vertical-align:middle;
  margin:0 4px;
  flex-shrink:0;
  animation:chipPop .7s 1s cubic-bezier(.22,1,.36,1) both, floatY 5s 1.8s ease-in-out infinite reverse;
}
.chip-syringe img{width:100%;height:100%;object-fit:cover}

@keyframes chipPop{from{opacity:0;transform:scale(.5)}to{opacity:1;transform:scale(1)}}
@keyframes floatY{0%,100%{transform:translateY(0)}50%{transform:translateY(-8px)}}

.desc{
  font-size:.92rem;line-height:1.78;
  color:#3d2d26;
  font-weight: 500;
  max-width:400px;margin-bottom:36px;
  opacity:0;animation:upIn .8s .55s cubic-bezier(.22,1,.36,1) forwards;
}

.actions{
  display:flex;align-items:center;gap:18px;
  margin-bottom:44px;
  opacity:0;animation:upIn .8s .65s cubic-bezier(.22,1,.36,1) forwards;
}

.btn-start{
  padding:13px 28px;border-radius:50px;border:none;cursor:pointer;
  background:var(--terra);color:#fff;
  font-family:'Plus Jakarta Sans',sans-serif;
  font-size:.9rem;font-weight:600;
  box-shadow:0 5px 20px rgba(217,102,74,.36);
  transition:all .3s cubic-bezier(.22,1,.36,1);
  position:relative;overflow:hidden;
}
.btn-start:hover{background:var(--dark);transform:translateY(-2px);box-shadow:0 10px 28px rgba(0,0,0,.2)}

.btn-how{
  display:flex;align-items:center;gap:12px;
  background:none;border:none;cursor:pointer;
  font-family:'Plus Jakarta Sans',sans-serif;
  font-size:.88rem;font-weight:600;color:var(--dark);
  transition:gap .3s;
}
.btn-how:hover{gap:16px}
.play-wrap{
  width:44px;height:44px;border-radius:50%;
  border:1.5px solid rgba(61,41,30,.4);
  display:flex;align-items:center;justify-content:center;
  color:var(--dark);position:relative;
  transition:all .3s;
}
.play-wrap::before{
  content:'';position:absolute;inset:-6px;
  border-radius:50%;border:1.5px solid rgba(217,102,74,.25);
  opacity:0;transform:scale(.85);
  transition:all .35s;
}
.btn-how:hover .play-wrap{background:var(--terra);border-color:var(--terra);color:#fff}
.btn-how:hover .play-wrap::before{opacity:1;transform:scale(1)}

/* ── RATING & STATS ── */
.rating-row{
  display:flex;align-items:center;gap:22px;
  padding-top:28px;
  border-top:1px solid rgba(61,41,30,.18);
  opacity:0;animation:upIn .8s .8s cubic-bezier(.22,1,.36,1) forwards;
}

.stars{display:flex;gap:2px}
.star{font-size:1.05rem;color:var(--gold)}

.rating-num{
  font-family:'Cormorant Garamond',serif;
  font-size:1.6rem;font-weight:700;color:var(--dark);
}
.rating-label{font-size:.78rem;color:#3d2d26;font-weight:600;}

.av-stack{display:flex}
.av{
  width:38px;height:38px;border-radius:50%;
  border:2.5px solid #eae2d5;
  overflow:hidden;margin-left:-10px;
  transition:transform .25s,z-index 0s;
  cursor:pointer;
}
.av:first-child{margin-left:0}
.av:hover{transform:translateY(-6px) scale(1.12);z-index:10}
.av img{width:100%;height:100%;object-fit:cover}

.client-count{font-size:.8rem;color:#3d2d26;line-height:1.4;font-weight:500;}
.client-count strong{display:block;font-size:1rem;color:var(--dark);font-weight:700}

/* ── RIGHT PANEL ── */
.hero-right{
  position:relative;
  display:flex;align-items:center;justify-content:center;
  overflow:hidden;
  opacity:0;animation:rightIn .9s .5s cubic-bezier(.22,1,.36,1) forwards;
}

.blob-wrap{
  position:relative;
  width:420px;height:520px;
  margin-right:40px;
  margin-top:20px;
}

.blob{
  position:absolute;
  top:0;right:0;
  width:400px;height:500px;
  border-radius:200px 200px 170px 170px;
  background:var(--terra);
  overflow:hidden;
  box-shadow:0 30px 80px rgba(217,102,74,.25);
}

.blob img.hero-photo{
  width:100%;height:100%;
  object-fit:cover;object-position:center top;
  display:block;
}

.ring{
  position:absolute;
  top:-24px;right:-24px;
  width:110px;height:110px;
  border-radius:50%;
  border:1.5px dashed rgba(217,102,74,.455);
  animation:spin 18s linear infinite;
  pointer-events:none;
}
.ring::before{
  content:'';position:absolute;inset:12px;
  border-radius:50%;border:1.5px dashed rgba(217,102,74,.3);
}
@keyframes spin{to{transform:rotate(360deg)}}

.wave-bottom{
  position:absolute;bottom:0;left:0;right:0;height:70px;
  pointer-events:none;z-index:1;
}
.wave-bottom svg{width:100%;height:100%}

/* ── ANIMATIONS ── */
@keyframes upIn{from{opacity:0;transform:translateY(28px)}to{opacity:1;transform:translateY(0)}}
@keyframes rightIn{from{opacity:0;transform:translateX(50px)}to{opacity:1;transform:translateX(0)}}
</style>
</head>
<body>

<nav>
  <a class="logo" href="#">
    <img src="https://benhvienthammynaman.com/wp-content/uploads/2023/04/footer-logo-home.svg" alt="Nam An Logo" style="height:44px;width:auto;display:block;"/>
  </a>

  <ul class="nav-links">
    <li><a href="#" class="active">Trang Chủ</a></li>
    <li><a href="#">Giới Thiệu</a></li>
    <li><a href="#">Dịch Vụ</a></li>
    <li><a href="#">Bác Sĩ</a></li>
    <li><a href="#">Liên Hệ</a></li>
  </ul>

  <div class="nav-right">
    <button class="btn-icon" aria-label="Tìm kiếm">
      <svg width="15" height="15" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.2"><circle cx="11" cy="11" r="8"/><line x1="21" y1="21" x2="16.65" y2="16.65"/></svg>
    </button>
    <button class="btn-appt">ĐẶT LỊCH</button>
  </div>
</nav>

<section class="hero">
  <div class="hero-left">
    <h1 class="headline">
      Nâng Tầm Vẻ Đẹp <span class="chip-face"><img src="https://images.unsplash.com/photo-1508214751196-bcfd4ca60f91?w=120&h=120&fit=crop&crop=face" alt="" onerror="this.src='https://randomuser.me/api/portraits/women/44.jpg'"/></span><br>
      <span class="chip-syringe" style="position:relative;top:2px">
        <img src="https://images.unsplash.com/photo-1612349317150-e413f6a5b16d?w=120&h=60&fit=crop" alt="" onerror="this.style.display='none'"/>
      </span>
      Với <em>Điêu Khắc Thẩm Mỹ</em>
    </h1>

    <p class="desc">
      Các giải pháp phẫu thuật thẩm mỹ được thiết kế để nâng cao, trẻ hóa hoặc tái tạo
      nhiều bộ phận trên cơ thể, giải quyết các vấn đề thẩm mỹ cá nhân một cách an toàn và hiệu quả.
    </p>

    <div class="actions">
      <button class="btn-start">Bác Sĩ</button>
      <button class="btn-how">
        <span class="play-wrap">
          <svg width="13" height="13" viewBox="0 0 24 24" fill="currentColor"><polygon points="5 3 19 12 5 21 5 3"/></svg>
        </span>
        Giới Thiệu Bệnh Viện Nam An
      </button>
    </div>

    <div class="rating-row">
      <div>
        <div class="stars">
          <span class="star">★</span><span class="star">★</span><span class="star">★</span>
          <span class="star">★</span><span class="star">★</span>
        </div>
        <div style="display:flex;align-items:baseline;gap:4px;margin-top:4px">
          <span class="rating-num">4.9</span>
          <span style="font-size:.82rem;color:var(--mid)">/ 5</span>
          <span class="rating-label">&nbsp;Đánh Giá</span>
        </div>
      </div>

      <div class="av-stack">
        <div class="av"><img src="https://images.unsplash.com/photo-1494790108377-be9c29b29330?w=80&h=80&fit=crop&crop=face" alt=""/></div>
        <div class="av"><img src="https://images.unsplash.com/photo-1517841905240-472988babdf9?w=80&h=80&fit=crop&crop=face" alt=""/></div>
        <div class="av"><img src="https://images.unsplash.com/photo-1534528741775-53994a69daeb?w=80&h=80&fit=crop&crop=face" alt=""/></div>
        <div class="av"><img src="https://images.unsplash.com/photo-1524504388940-b1c1722653e1?w=80&h=80&fit=crop&crop=face" alt=""/></div>
        <div class="av"><img src="https://images.unsplash.com/photo-1502767089025-6572583495d4?w=80&h=80&fit=crop&crop=face" alt=""/></div>
      </div>

      <div class="client-count">
        <strong>2.400+</strong>
        Khách Hàng Hài Lòng
      </div>
    </div>
  </div>

  <div class="hero-right">
    <div class="blob-wrap">
      <div class="ring"></div>
      <div class="blob">
        <img class="hero-photo"
          src="https://images.unsplash.com/photo-1594824476967-48c8b964273f?w=800&h=1000&fit=crop&crop=top"
          alt="Phụ nữ đang được điều trị thẩm mỹ"
          onerror="this.src='https://images.unsplash.com/photo-1559757148-5c350d0d3c56?w=800&h=1000&fit=crop'"/>
      </div>
    </div>
  </div>

  <div class="wave-bottom">
    <svg viewBox="0 0 1440 70" preserveAspectRatio="none" xmlns="http://www.w3.org/2000/svg">
      <path d="M0,35 C360,70 1080,0 1440,35 L1440,70 L0,70 Z" fill="rgba(255,255,255,.2)"/>
    </svg>
  </div>
</section>

<script>
/* ── Parallax on mouse move ── */
const blob = document.querySelector('.blob');
const ring = document.querySelector('.ring');
document.addEventListener('mousemove', e => {
  const x = (e.clientX / window.innerWidth - .5) * 18;
  const y = (e.clientY / window.innerHeight - .5) * 12;
  if(blob) blob.style.transform = `translate(${x*.4}px,${y*.4}px)`;
  if(ring) ring.style.marginTop  = `${y*.3}px`;
});

/* ── Button ripple ── */
document.querySelectorAll('.btn-start, .btn-appt').forEach(btn => {
  btn.addEventListener('click', function(e){
    const s = document.createElement('span');
    const rect = this.getBoundingClientRect();
    const sz = Math.max(rect.width, rect.height) * 2;
    Object.assign(s.style, {
      position:'absolute', borderRadius:'50%',
      background:'rgba(255,255,255,.3)',
      width: sz + 'px', height: sz + 'px',
      left: (e.clientX - rect.left - sz/2) + 'px',
      top:  (e.clientY - rect.top  - sz/2) + 'px',
      transform:'scale(0)', animation:'rpl .6s linear',
      pointerEvents:'none'
    });
    this.style.position = 'relative';
    this.style.overflow = 'hidden';
    this.appendChild(s);
    s.addEventListener('animationend', () => s.remove());
  });
});

/* inject ripple keyframe */
const st = document.createElement('style');
st.textContent = '@keyframes rpl{to{transform:scale(1);opacity:0}}';
document.head.appendChild(st);

/* ── Avatar z-index stagger ── */
document.querySelectorAll('.av').forEach((a,i) => a.style.zIndex = i + 1);

/* ── Staggered star colour animation ── */
document.querySelectorAll('.star').forEach((s,i) => {
  s.style.animationDelay = (i * .08 + .9) + 's';
  s.style.opacity = '0';
  s.style.animation = `upIn .5s ${(i * .08 + .9)}s cubic-bezier(.22,1,.36,1) forwards`;
});
</script>
</body>
</html>













<!-- BẮT ĐẦU VÙNG CÔ LẬP LAYOUT TUYỆT ĐỐI -->

<iframe srcdoc="
<!DOCTYPE html>
<html lang='vi'>
<head>
<meta charset='UTF-8'>
<meta name='viewport' content='width=device-width, initial-scale=1.0'>
<title>Vẻ Đẹp Vượt Trội</title>
<link href='https://fonts.googleapis.com/css2?family=Cormorant+Infant:ital,wght@0,400;0,600;1,400&family=Be+Vietnam+Pro:wght@300;400;500&display=swap' rel='stylesheet'>
<style>
  *,*::before,*::after{box-sizing:border-box;margin:0;padding:0}

  html, body {
    height: 100%;
  }

  body {
    background: #ffffff;
    font-family: 'Be Vietnam Pro', sans-serif;
    height: 100vh;
    display: flex;
    align-items: center;
    justify-content: center;
    padding: 0;
    overflow: hidden;
  }

  .wrapper {
    max-width: 980px;
    width: 100%;
    background: #fff;
    border-radius: 0;
    box-shadow: none;
    display: grid;
    grid-template-columns: 340px 1fr;
    gap: 0;
  }

  /* ────────── TRÁI: ảnh grid ────────── */
  .pane-left {
    background: #ffffff;
    padding: 44px 32px 44px 40px;
    display: flex;
    align-items: center;
  }

  .anh-grid {
    width: 100%;
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 10px;
  }

  .anh {
    overflow: hidden;
    position: relative;
    opacity: 0;
    transform: scale(0.82) translateY(8px);
    animation: hienAnh 0.7s cubic-bezier(0.34,1.56,0.64,1) forwards;
  }
  .anh:nth-child(1){animation-delay:0.08s}
  .anh:nth-child(2){animation-delay:0.22s}
  .anh:nth-child(3){animation-delay:0.36s}
  .anh:nth-child(4){animation-delay:0.50s}

  @keyframes hienAnh {
    to { opacity:1; transform:scale(1) translateY(0) }
  }

  .anh img {
    width:100%; height:100%;
    object-fit:cover;
    display:block;
    transition: transform 0.55s ease;
  }
  .anh:hover img { transform: scale(1.07) }

  .anh-tl { border-radius: 64px 64px 0 64px;   height: 220px }
  .anh-tr { border-radius: 64px 64px 64px 0;   height: 180px; margin-top: 40px }
  .anh-bl { border-radius: 64px 0 64px 64px;   height: 180px }
  .anh-br { border-radius: 0 64px 64px 64px;   height: 220px }
.anh::after {
  content: '';
  position: absolute;
  inset: 0;
  background: rgba(196, 113, 74, 0);
  transition: background 0.4s ease;
  border-radius: inherit;
}
.anh:hover::after {
  background: rgba(196, 113, 74, 0.22);
}
  /* ────────── PHẢI: nội dung ────────── */
  .pane-right {
    padding: 48px 44px 44px 40px;
    display: flex;
    flex-direction: column;
    justify-content: center;
  }

  .tag {
    display: inline-block;
    font-size: 10px;
    font-weight: 500;
    letter-spacing: 2.5px;
    text-transform: uppercase;
    color: #c4714a;
    background: #fde8de;
    padding: 4px 12px;
    border-radius: 20px;
    margin-bottom: 14px;
    opacity: 0;
    animation: truotLen 0.5s ease 0.3s forwards;
  }

  .tieu-de {
    font-family: 'Cormorant Infant', serif;
    font-size: 30px;
    font-weight: 600;
    color: #1c1c1c;
    line-height: 1.25;
    margin-bottom: 22px;
    opacity: 0;
    animation: truotLen 0.6s ease 0.42s forwards;
  }

  .tieu-de em {
    font-style: italic;
    color: #c4714a;
  }

  @keyframes truotLen {
    from { opacity:0; transform:translateY(16px) }
    to   { opacity:1; transform:translateY(0) }
  }

  /* 6 tính năng */
  .tinh-nang {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 13px 22px;
    margin-bottom: 26px;
  }

  .tn {
    display: flex;
    gap: 10px;
    align-items: flex-start;
    opacity: 0;
    transform: translateX(-10px);
    animation: truotPhai 0.4s ease forwards;
  }
  .tn:nth-child(1){animation-delay:0.62s}
  .tn:nth-child(2){animation-delay:0.72s}
  .tn:nth-child(3){animation-delay:0.82s}
  .tn:nth-child(4){animation-delay:0.92s}
  .tn:nth-child(5){animation-delay:1.02s}
  .tn:nth-child(6){animation-delay:1.12s}

  @keyframes truotPhai {
    to { opacity:1; transform:translateX(0) }
  }

  .tn-bieu-tuong {
    width: 34px; height: 34px;
    border-radius: 50%;
    background: #fdeee7;
    display: flex; align-items: center; justify-content: center;
    flex-shrink: 0;
    transition: background 0.3s;
  }
  .tn:hover .tn-bieu-tuong { background: #f8d8cb }

  .tn-bieu-tuong svg {
    width: 16px; height: 16px;
    stroke: #c4714a;
    fill: none;
    stroke-width: 1.9;
    stroke-linecap: round;
    stroke-linejoin: round;
  }

  .tn-ten {
    font-size: 11.5px;
    font-weight: 500;
    color: #c4714a;
    margin-bottom: 2px;
  }

  .tn-chu {
    font-size: 10px;
    color: #cdc5bc;
    line-height: 1.45;
    font-weight: 300;
  }

  /* Đường kẻ phân tách */
  .duong-ke {
    height: 1px;
    background: linear-gradient(to right, #f0e8df, transparent);
    margin-bottom: 20px;
    opacity: 0;
    animation: hienDan 0.5s ease 1.2s forwards;
  }

  /* Thống kê */
  .thong-ke {
    display: flex;
    gap: 28px;
    opacity: 0;
    animation: hienDan 0.6s ease 1.28s forwards;
  }

  @keyframes hienDan { to { opacity:1 } }

  .tk-so {
    font-family: 'Cormorant Infant', serif;
    font-size: 30px;
    font-weight: 600;
    color: #1c1c1c;
    line-height: 1;
    display: flex;
    align-items: flex-start;
  }

  .tk-ky-hieu {
    font-size: 13px;
    color: #c4714a;
    font-family: 'Be Vietnam Pro', sans-serif;
    font-weight: 500;
    margin-top: 5px;
    margin-left: 1px;
  }

  .tk-nhan {
    font-size: 10px;
    color: #c0b8b0;
    margin-top: 4px;
    font-weight: 300;
    letter-spacing: 0.3px;
  }
</style>
</head>
<body>

<div class='wrapper'>

  <!-- TRÁI -->
  <div class='pane-left'>
    <div class='anh-grid'>
      <div class='anh anh-tl'>
        <img src='https://images.unsplash.com/photo-1515377905703-c4788e51af15?q=80&w=600&auto=format&fit=crop' alt='Tư vấn bác sĩ'>
      </div>
      <div class='anh anh-tr'>
        <img src='https://images.unsplash.com/photo-1524504388940-b1c1722653e1?q=80&w=600&auto=format&fit=crop' alt='Chăm sóc da'>
      </div>
      <div class='anh anh-bl'>
        <img src='https://images.unsplash.com/photo-1515886657613-9f3515b0c78f?q=80&w=600&auto=format&fit=crop' alt='Điều trị thẩm mỹ'>
      </div>
      <div class='anh anh-br'>
        <img src='https://images.unsplash.com/photo-1487412720507-e7ab37603c6f?q=80&w=600&auto=format&fit=crop' alt='Kết quả phẫu thuật'>
      </div>
    </div>
  </div>

  <!-- PHẢI -->
  <div class='pane-right'>

    <span class='tag'>Vì sao khách hàng chọn Bệnh Viện Nam An</span>

    <h1 class='tieu-de'>Vẻ Đẹp Vượt Trội — Khám Phá<br><em>Phiên Bản</em> Tốt Nhất Của Bạn</h1>

    <div class='tinh-nang'>
      <div class='tn'>
        <div class='tn-bieu-tuong'>
          <svg viewBox='0 0 24 24'><circle cx='12' cy='8' r='4'/><path d='M4 20c0-4 3.6-7 8-7s8 3 8 7'/></svg>
        </div>
        <div>
          <div class='tn-ten'>Bác Sĩ Giỏi</div>
          <div class='tn-chu'>Chứng nhận quốc tế</div>
        </div>
      </div>
      <div class='tn'>
        <div class='tn-bieu-tuong'>
          <svg viewBox='0 0 24 24'><rect x='4' y='3' width='16' height='18' rx='2'/><line x1='9' y1='9' x2='15' y2='9'/><line x1='9' y1='13' x2='15' y2='13'/><line x1='9' y1='17' x2='12' y2='17'/></svg>
        </div>
        <div>
          <div class='tn-ten'>Chuyên Gia Cấp Cao</div>
          <div class='tn-chu'>Được cấp phép chính thức</div>
        </div>
      </div>
      <div class='tn'>
        <div class='tn-bieu-tuong'>
          <svg viewBox='0 0 24 24'><circle cx='12' cy='12' r='3'/><path d='M12 2v2M12 20v2M2 12h2M20 12h2M4.93 4.93l1.41 1.41M17.66 17.66l1.41 1.41M4.93 19.07l1.41-1.41M17.66 6.34l1.41-1.41'/></svg>
        </div>
        <div>
          <div class='tn-ten'>Công Nghệ Hiện Đại</div>
          <div class='tn-chu'>Thiết bị thế hệ mới</div>
        </div>
      </div>
      <div class='tn'>
        <div class='tn-bieu-tuong'>
          <svg viewBox='0 0 24 24'><line x1='12' y1='1' x2='12' y2='23'/><path d='M17 5H9.5a3.5 3.5 0 0 0 0 7h5a3.5 3.5 0 0 1 0 7H6'/></svg>
        </div>
        <div>
          <div class='tn-ten'>Giá Cả Hợp Lý</div>
          <div class='tn-chu'>Minh bạch, linh hoạt</div>
        </div>
      </div>
      <div class='tn'>
        <div class='tn-bieu-tuong'>
          <svg viewBox='0 0 24 24'><path d='M3 9l9-7 9 7v11a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2z'/><polyline points='9 22 9 12 15 12 15 22'/></svg>
        </div>
        <div>
          <div class='tn-ten'>Bệnh Viện Uy Tín</div>
          <div class='tn-chu'>Chuẩn vệ sinh tuyệt đối</div>
        </div>
      </div>
      <div class='tn'>
        <div class='tn-bieu-tuong'>
          <svg viewBox='0 0 24 24'><path d='M22 16.92v3a2 2 0 0 1-2.18 2 19.79 19.79 0 0 1-8.63-3.07A19.5 19.5 0 0 1 4.69 12a19.79 19.79 0 0 1-3.07-8.67A2 2 0 0 1 3.6 1.26h3a2 2 0 0 1 2 1.72 12.84 12.84 0 0 0 .7 2.81 2 2 0 0 1-.45 2.11L8.09 8.91a16 16 0 0 0 6 6l1.27-1.27a2 2 0 0 1 2.11-.45 12.84 12.84 0 0 0 2.81.7A2 2 0 0 1 22 16.92z'/></svg>
        </div>
        <div>
          <div class='tn-ten'>Hỗ Trợ 24/7</div>
          <div class='tn-chu'>Luôn sẵn sàng bên bạn</div>
        </div>
      </div>
    </div>

    <div class='duong-ke'></div>

    <div class='thong-ke'>
      <div>
        <div class='tk-so'><span id='s1'>0</span><span class='tk-ky-hieu'>+</span></div>
        <div class='tk-nhan'>Năm Kinh Nghiệm</div>
      </div>
      <div>
        <div class='tk-so'><span id='s2'>0</span><span class='tk-ky-hieu'>+</span></div>
        <div class='tk-nhan'>Bác Sĩ Chuyên Khoa</div>
      </div>
      <div>
        <div class='tk-so'><span id='s3'>0</span><span class='tk-ky-hieu'>%</span></div>
        <div class='tk-nhan'>Khách Hàng Hài Lòng</div>
      </div>
    </div>

  </div>
</div>

<script>
  function demSo(el, dich, thoiGian, treCho) {
    setTimeout(function() {
      var hienTai = 0;
      var laThapPhan = dich % 1 !== 0;
      var buoc = dich / (thoiGian / 16);
      var dem = setInterval(function() {
        hienTai = Math.min(hienTai + buoc, dich);
        el.textContent = laThapPhan ? hienTai.toFixed(1) : Math.round(hienTai);
        if (hienTai >= dich) clearInterval(dem);
      }, 16);
    }, treCho);
  }
  demSo(document.getElementById('s1'), 49,   1400, 1350);
  demSo(document.getElementById('s2'), 26,   1400, 1450);
  demSo(document.getElementById('s3'), 97.8, 1400, 1550);
</script>

</body>
</html>
" style="width: 100%; height: 100vh; border: none; overflow: hidden; display: block; background: #ffffff;"></iframe>
<!-- KẾT THÚC VÙNG CÔ LẬP LAYOUT -->

















<!-- BẮT ĐẦU VÙNG CÔ LẬP LAYOUT TUYỆT ĐỐI -->
<iframe srcdoc="
<!DOCTYPE html>
<html lang='en'>
<head>
  <meta charset='UTF-8'>
  <meta name='viewport' content='width=device-width, initial-scale=1.0'>
  <title>Butterfly Divider</title>

  <style>
    * { margin: 0; padding: 0; box-sizing: border-box; }

    body{
      background:#ffffff;
      padding: 0px;
      font-family:Arial, sans-serif;
      display: flex;
      align-items: center;
      justify-content: center;
      min-height: 0vh;
      overflow: hidden;
    }

    .divider{
      display:flex;
      align-items:center;
      justify-content:center;
      gap:20px;
      width:100%;
      max-width: 800px;
    }

    .divider::before,
    .divider::after{
      content:'';
      flex:1;
      height:1px;
      background:linear-gradient(
        to right,
        transparent,
        #d8c7c0,
        transparent
      );
    }

    .butterfly{
      font-size:28px;
      color:#c79b8b;
      transform:rotate(-8deg);
      display: inline-block;
    }
  </style>
</head>
<body>

  <div class='divider'>
    <span class='butterfly'>🦋</span>
  </div>

</body>
</html>
" style="width: 100%; height: 60px; border: none; overflow: hidden; display: block; background: transparent;"></iframe>
<!-- KẾT THÚC VÙNG CÔ LẬP LAYOUT -->













<!-- BẮT ĐẦU VÙNG CÔ LẬP LAYOUT GRID 3 CỘT -->
<iframe srcdoc="
<!DOCTYPE html>
<html lang='vi'>
<head>
  <meta charset='UTF-8' />
  <meta name='viewport' content='width=device-width, initial-scale=1.0'/>
  <title>Dịch Vụ Điêu Khắc</title>
  <style>
    *{ margin:0; padding:0; box-sizing:border-box; font-family:Arial,Helvetica,sans-serif }
    
    body{ 
      background:#fff; 
      padding:25px 10px; 
      display:flex; 
      justify-content:center; 
      align-items:center; 
      min-height:180px;
    }
    
    .services{ 
      display:flex; 
      gap:20px; 
      flex-wrap:wrap; 
      justify-content:center; 
      max-width:1100px; 
      width:100%;
    }
    
    .card{    
      width:320px; 
      height:160px; 
      background:#f1eeeb;    
      border-radius:0 80px 80px 0;    
      display:flex; 
      align-items:center; 
      padding:18px;    
      position:relative; 
      overflow:hidden; 
      cursor:pointer;    
      opacity:0; 
      transform:translateY(36px);    
      animation:hienMem 0.8s cubic-bezier(0.16,1,0.3,1) forwards;    
      transition:background 0.5s cubic-bezier(0.16,1,0.3,1);  
    }
    
    .card:nth-child(1){animation-delay:0.1s}  
    .card:nth-child(2){animation-delay:0.25s}  
    .card:nth-child(3){animation-delay:0.4s}  
    
    @keyframes hienMem{ to{opacity:1;transform:translateY(0)} }  
    
    .card:hover{background:#f5a97a;}  
    
    .card::before{    
      content:''; 
      position:absolute; 
      inset:0;    
      background:radial-gradient(circle at 60% 50%, #e8804a 0%, transparent 72%);    
      opacity:0; 
      transform:scale(0.4);    
      transition:opacity 0.55s ease, transform 0.55s cubic-bezier(0.16,1,0.3,1);    
      pointer-events:none; 
      border-radius:inherit;  
    }  
    
    .card:hover::before{opacity:0.35;transform:scale(1);}  
    
    .card-image{    
      width:95px; 
      height:120px; 
      border-radius:0 30px; 
      overflow:hidden;    
      flex-shrink:0; 
      margin-right:18px;    
      transition:transform 0.55s cubic-bezier(0.16,1,0.3,1);    
      position:relative; 
      z-index:1;  
    }  
    
    .card:hover .card-image{transform:scale(1.06) translateY(-2px);}  
    
    .card-image img{
      width:100%; 
      height:100%; 
      object-fit:cover; 
      object-position:top center; 
      transition:transform 0.6s cubic-bezier(0.16,1,0.3,1);
    }  
    
    .card:hover .card-image img{transform:scale(1.1);}  
    
    .card-content{position:relative;z-index:1;}  
    
    .card-content h3{
      font-size:16px; 
      color:#4b3b35; 
      margin-bottom:8px; 
      line-height:1.3; 
      transition:color 0.4s ease;
    }  
    
    .card:hover .card-content h3{color:#fff;}  
    
    .card-content p{
      font-size:11.5px; 
      color:#7c706a; 
      line-height:1.6; 
      margin-bottom:14px; 
      transition:color 0.4s ease;
    }  
    
    .card:hover .card-content p{color:rgba(255,255,255,0.85);}  
    
    .card-content a{
      text-decoration:none; 
      color:#c4714a; 
      font-size:12px; 
      font-weight:600; 
      display:inline-flex; 
      align-items:center; 
      gap:5px; 
      transition:color 0.4s ease, gap 0.4s ease;
    }  
    
    .card:hover .card-content a{color:#fff;gap:10px;}  
    
    .card-content a span{display:inline-block;transition:transform 0.4s cubic-bezier(0.16,1,0.3,1);}  
    
    .card:hover .card-content a span{transform:translateX(5px);}
  </style>
</head>
<body>

  <div class='services'>  
    <div class='card'>    
      <div class='card-image'>      
        <img src='https://images.unsplash.com/photo-1512290923902-8a9f81dc236c?q=80&w=600&auto=format&fit=crop&crop=top' alt='Điêu Khắc Gương Mặt'>    
      </div>    
      <div class='card-content'>      
        <h3>Điêu Khắc<br>Gương Mặt</h3>      
        <p>Tạo đường nét thanh tú, cân đối — vẻ đẹp hài hòa tự nhiên cho khuôn mặt.</p>      
        <a href='#'>Tìm hiểu thêm <span>➜</span></a>    
      </div>  
    </div>  
    
    <div class='card'>    
      <div class='card-image'>      
        <img src='https://images.unsplash.com/photo-1515377905703-c4788e51af15?q=80&w=600&auto=format&fit=crop&crop=top' alt='Điêu Khắc Vóc Dáng'>    
      </div>    
      <div class='card-content'>      
        <h3>Điêu Khắc<br>Vóc Dáng</h3>      
        <p>Phác họa đường cong lý tưởng — tự tin với vóc dáng chuẩn, săn chắc.</p>      
        <a href='#'>Tìm hiểu thêm <span>➜</span></a>    
      </div>  
    </div>  
    
    <div class='card'>    
      <div class='card-image'>      
        <img src='https://images.unsplash.com/photo-1487412720507-e7ab37603c6f?q=80&w=600&auto=format&fit=crop&crop=top' alt='Chăm Sóc Da Toàn Diện'>    
      </div>    
      <div class='card-content'>      
        <h3>Chăm Sóc Da<br>Toàn Diện</h3>      
        <p>Phục hồi, nuôi dưỡng làn da — căng bóng, rạng rỡ từ sâu bên trong.</p>      
        <a href='#'>Tìm hiểu thêm <span>➜</span></a>    
      </div>  
    </div>
  </div>

</body>
</html>
" style="width: 100%; min-height: 230px; border: none; overflow: visible; display: block; background: transparent;"></iframe>
<!-- KẾT THÚC VÙNG CÔ LẬP LAYOUT GRID 3 CỘT -->































<!-- BẮT ĐẦU VÙNG CÔ LẬP LAYOUT GRID 4 SẢN PHẨM -->
<iframe srcdoc="
<!DOCTYPE html>
<html lang='vi'>
<head>
  <meta charset='UTF-8' />
  <meta name='viewport' content='width=device-width, initial-scale=1.0'/>
  <title>Dịch Vụ Điêu Khắc Cao Cấp</title>
  <link href='https://fonts.googleapis.com/css2?family=Be+Vietnam+Pro:wght@400;500;600&display=swap' rel='stylesheet'>
  <style>
    *{ margin:0; padding:0; box-sizing:border-box; }  
    body{ font-family: Georgia, serif; background:#fff; color:#3f2f2b; padding:25px 10px; }
    .services-section{ width:1000px; margin:0 auto; }
    .services-grid{ display:grid; grid-template-columns:repeat(2,1fr); gap:45px 30px; }
    .service-card{    background:#fff;    border:1px solid #f0e8e0;    display:flex;    align-items:center;    gap:20px;    padding:20px;    min-height:260px;    overflow:visible;    position:relative;    opacity:0;    transform:translateY(40px);    animation:hienLen 0.75s cubic-bezier(0.16,1,0.3,1) forwards;  }  
    .service-card:nth-child(1){ animation-delay:0.2s }  
    .service-card:nth-child(2){ animation-delay:0.35s }  
    .service-card:nth-child(3){ animation-delay:0.5s }  
    .service-card:nth-child(4){ animation-delay:0.65s }
    @keyframes hienLen{ to{ opacity:1; transform:translateY(0) } }
    .service-card::before{    content:'';    position:absolute;    inset:0;    background:linear-gradient(135deg, #fde8d8 0%, #fdf0e8 100%);    opacity:0;    transition:opacity 0.45s ease;    pointer-events:none;  }  
    .service-card:hover::before{ opacity:1; }  
    .service-card:hover{    transform:translateY(-7px);    box-shadow:0 18px 42px rgba(200,120,70,0.13);    border-color:#f0c9a8;    transition: transform 0.4s cubic-bezier(0.16,1,0.3,1), box-shadow 0.4s ease, border-color 0.4s ease;  }
    
    /* ── BADGE MINI ── */  
    .mini-badge {    position: absolute;    top: -13px;    right: 16px;    z-index: 10;    display: inline-flex;    align-items: center;    gap: 5px;    background: #ffffff;    border: 1px solid rgba(228,129,91,0.4);    border-radius: 30px;    padding: 3px 10px 3px 7px;    box-shadow: 0 2px 10px rgba(228,129,91,0.15);    animation: floatBadge 3.5s ease-in-out infinite;  }  
    @keyframes floatBadge {    0%,100%{ transform: translateY(0); }    50%{ transform: translateY(-3px); }  }  
    .mini-badge-diamond {    width: 5px; height: 5px;    background: #e4815b;    transform: rotate(45deg);    border-radius: 1px;    flex-shrink: 0;    animation: pulseBadge 2.5s ease-in-out infinite;  }  
    @keyframes pulseBadge {    0%,100%{ box-shadow: 0 0 3px rgba(228,129,91,0.3); }    50%{ box-shadow: 0 0 7px rgba(228,129,91,0.7); }  }  
    .mini-badge-text {    font-family: 'Be Vietnam Pro', sans-serif;    font-size: 9px;    font-weight: 600;    letter-spacing: 1.2px;    text-transform: uppercase;    background: linear-gradient(135deg, #e4815b, #c96840, #e4815b);    background-size: 200% auto;    -webkit-background-clip: text;    -webkit-text-fill-color: transparent;    background-clip: text;    animation: shimmer 3s linear infinite;    white-space: nowrap;  }  
    @keyframes shimmer {    0%{ background-position: 0% center; }    100%{ background-position: 200% center; }  }
    
    /* ── ẢNH ── */  
    .service-image{    width:180px; height:310px;    overflow:hidden;    border-radius:10px 90px 90px 90px;    flex-shrink:0;    margin-bottom:-45px;    position:relative; z-index:1;    transition:transform 0.5s cubic-bezier(0.16,1,0.3,1), box-shadow 0.4s ease;  }  
    .service-card:hover .service-image{ transform:translateY(-6px) scale(1.02); box-shadow:0 12px 32px rgba(0,0,0,0.14); }  
    .service-image img{ width:100%; height:100%; object-fit:cover; display:block; transition:transform 0.6s cubic-bezier(0.16,1,0.3,1); }  
    .service-card:hover .service-image img{ transform:scale(1.07); }
    
    /* ── NỘI DUNG ── */  
    .service-content{ position:relative; z-index:1; }  
    .service-content h3{ font-size:18px; color:#c97b4b; margin-bottom:6px; line-height:1.3; font-weight:600; transition:color 0.35s ease; }  
    .service-card:hover .service-content h3{ color:#a85c30; }  
    .service-content p{ color:#9a8880; font-size:13px; line-height:1.6; margin-bottom:14px; transition:color 0.35s ease; }  
    .service-card:hover .service-content p{ color:#7a6860; }  
    .service-content ul{ list-style:none; margin-bottom:16px; }  
    .service-content ul li{ position:relative; padding-left:22px; margin-bottom:8px; color:#6e6060; font-size:13px; transition:color 0.35s ease, transform 0.35s ease; }  
    .service-card:hover .service-content ul li{ color:#5a4040; }  
    .service-card:hover .service-content ul li:nth-child(1){ transition-delay:0.03s; transform:translateX(3px) }  
    .service-card:hover .service-content ul li:nth-child(2){ transition-delay:0.06s; transform:translateX(3px) }  
    .service-card:hover .service-content ul li:nth-child(3){ transition-delay:0.09s; transform:translateX(3px) }  
    .service-card:hover .service-content ul li:nth-child(4){ transition-delay:0.12s; transform:translateX(3px) }  
    .service-content ul li::before{ content:'✓'; position:absolute; left:0; top:0; color:#d8916a; font-weight:bold; font-size:13px; transition:color 0.35s ease; }  
    .service-card:hover .service-content ul li::before{ color:#c06030; }  
    .learn-more{ text-decoration:none; color:#c97b4b; font-size:13.5px; font-weight:600; display:inline-flex; align-items:center; gap:6px; transition:gap 0.4s ease, color 0.35s ease; }  
    .service-card:hover .learn-more{ gap:10px; color:#a85c30; }  
    .learn-more span{ display:inline-block; transition:transform 0.4s cubic-bezier(0.16,1,0.3,1); }  
    .service-card:hover .learn-more span{ transform:translateX(5px); }
    
    @media(max-width:1000px){ .services-section{ width:92% } }  
    @media(max-width:900px){ .services-grid{ grid-template-columns:1fr } }  
    @media(max-width:768px){    
      .service-card{ flex-direction:column; text-align:center; padding:24px 20px 45px }    
      .service-image{ width:100%; height:280px; margin-bottom:-35px }    
      .service-content ul li{ text-align:left }  
    }
  </style>
</head>
<body>

  <section class='services-section'>  
    <div class='services-grid'>
      <!-- Sản phẩm 1 -->
      <div class='service-card'>      
        <div class='mini-badge'><div class='mini-badge-diamond'></div><span class='mini-badge-text'>Công Nghệ Điêu Khắc</span></div>      
        <div class='service-image'><img src='https://images.unsplash.com/photo-1588776814546-1ffcf47267a5?q=80&w=1200&auto=format&fit=crop' alt='Công nghệ RF'></div>      
        <div class='service-content'>        
          <h3>Công Nghệ RF</h3>        
          <p>Căng da toàn diện — kích thích collagen tái tạo, trả lại làn da săn chắc và đàn hồi tự nhiên.</p>        
          <ul>          
            <li>Căng da mặt & cổ</li>          
            <li>Kích thích collagen sâu</li>          
            <li>Không xâm lấn, không phục hồi</li>          
            <li>Hiệu quả sau 1–3 lần điều trị</li>        
          </ul>        
          <a href='#' class='learn-more'>Tìm hiểu thêm <span>➜</span></a>      
        </div>    
      </div>

      <!-- Sản phẩm 2 -->
      <div class='service-card'>      
        <div class='mini-badge'><div class='mini-badge-diamond'></div><span class='mini-badge-text'>Công Nghệ Điêu Khắc</span></div>      
        <div class='service-image'><img src='https://images.unsplash.com/photo-1515377905703-c4788e51af15?q=80&w=1200&auto=format&fit=crop' alt='Công nghệ QuantumRF'></div>      
        <div class='service-content'>        
          <h3>Công Nghệ QuantumRF</h3>        
          <p>Hút mỡ & tạo cơ — phá hủy tế bào mỡ bướng bỉnh, đồng thời điêu khắc cơ bắp chuẩn dáng.</p>        
          <ul>          
            <li>Hút mỡ không phẫu thuật</li>          
            <li>Tạo cơ & định hình vóc dáng</li>          
            <li>Giảm mỡ vùng bụng, đùi, tay</li>          
            <li>An toàn, không đau, không nghỉ dưỡng</li>        
          </ul>        
          <a href='#' class='learn-more'>Tìm hiểu thêm <span>➜</span></a>      
        </div>    
      </div>

      <!-- Sản phẩm 3 -->
      <div class='service-card'>      
        <div class='mini-badge'><div class='mini-badge-diamond'></div><span class='mini-badge-text'>Công Nghệ Điêu Khắc</span></div>      
        <div class='service-image'><img src='https://images.unsplash.com/photo-1559839734-2b71ea197ec2?q=80&w=1200&auto=format&fit=crop' alt='Thermage & Ultherapy Prime'></div>      
        <div class='service-content'>        
          <h3>THERMAGE &<br>ULTHERAPY PRIME</h3>        
          <p>THERMAGE xóa nhăn sâu — ULTHERAPY PRIME nâng cơ, định hình gương mặt thon gọn, trẻ trung.</p>        
          <ul>          
            <li>Xóa nếp nhăn toàn mặt</li>          
            <li>Nâng cơ, săn chắc da</li>          
            <li>Định hình đường V-line</li>          
            <li>Kết hợp 2 công nghệ trong 1 liệu trình</li>        
          </ul>        
          <a href='#' class='learn-more'>Tìm hiểu thêm <span>➜</span></a>      
        </div>    
      </div>

      <!-- Sản phẩm 4 -->
      <div class='service-card'>      
        <div class='mini-badge'><div class='mini-badge-diamond'></div><span class='mini-badge-text'>Công Nghệ Điêu Khắc</span></div>      
        <div class='service-image'><img src='https://images.unsplash.com/photo-1609840114035-3c981b782dfe?q=80&w=1200&auto=format&fit=crop' alt='Công nghệ Forma V'></div>      
        <div class='service-content'>        
          <h3>Công Nghệ Forma V</h3>        
          <p>Trẻ hóa vùng kín — phục hồi độ đàn hồi, tăng cảm giác và cải thiện chất lượng cuộc sống cho phụ nữ.</p>        
          <ul>          
            <li>Trẻ hóa mô vùng kín không xâm lấn</li>          
            <li>Tăng độ đàn hồi & cảm giác</li>          
            <li>Cải thiện sau sinh & mãn kinh</li>          
            <li>Thủ thuật nhanh, riêng tư, an toàn</li>        
          </ul>        
          <a href='#' class='learn-more'>Tìm hiểu thêm <span>➜</span></a>      
        </div>    
      </div>
    </div>
  </section>

</body>
</html>
" style="width: 100%; min-height: 740px; border: none; overflow: hidden; display: block; background: #ffffff;"></iframe>
<!-- KẾT THÚC VÙNG CÔ LẬP LAYOUT GRID 4 SẢN PHẨM -->





























<div style="all: initial; display: block;">
  <style>
    #banner-root { all: initial; display: flex; justify-content: center; background: #ffffff; padding: 32px 0; overflow-x: auto; box-sizing: border-box; width: 100%; }
    #banner-root .bw { width: 1000px; min-width: 1000px; border-radius: 0px; overflow: hidden; position: relative; display: flex; align-items: center; font-family: 'Inter', sans-serif; min-height: 200px; }
    #banner-root .bbg { position: absolute; inset: 0; background-image: url('https://images.unsplash.com/photo-1512290923902-8a9f81dc236c?q=80&w=1400&auto=format&fit=crop&crop=right'); background-size: cover; background-position: center right; z-index: 0; }
    #banner-root .bov { position: absolute; inset: 0; background: linear-gradient(to right, rgba(75,45,35,0.88) 0%, rgba(75,45,35,0.75) 35%, rgba(75,45,35,0.3) 60%, rgba(75,45,35,0.0) 100%); z-index: 1; }
    #banner-root .bc { position: relative; z-index: 2; padding: 40px 44px; max-width: 520px; opacity: 0; transform: translateY(16px); animation: bFadeUp 0.9s cubic-bezier(0.16,1,0.3,1) 0.2s forwards; box-sizing: border-box; }
    @keyframes bFadeUp { to { opacity: 1; transform: translateY(0); } }
    #banner-root .bt { font-family: 'Playfair Display', serif; font-size: 26px; font-weight: 500; color: #ffffff; line-height: 1.35; margin: 0 0 10px 0; padding: 0; }
    #banner-root .bd { font-size: 12px; color: rgba(255,255,255,0.72); line-height: 1.65; margin: 0 0 20px 0; max-width: 360px; font-weight: 300; padding: 0; }
    #banner-root .bb { display: inline-block; background: #d97b52; color: #ffffff; font-size: 13px; font-weight: 400; letter-spacing: 0.3px; padding: 10px 24px; border-radius: 30px; text-decoration: none; border: none; cursor: pointer; transition: background 0.3s ease, transform 0.3s ease; font-family: 'Inter', sans-serif; }
    #banner-root .bb:hover { background: #c96840; transform: translateY(-2px); }
  </style>
  <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@400;500&family=Inter:wght@300;400&display=swap" rel="stylesheet">
  <div id="banner-root">
    <div class="bw">
      <div class="bbg"></div>
      <div class="bov"></div>
      <div class="bc">
        <h2 class="bt">Ưu Đãi Đặc Biệt Dành Cho<br>Khách Hàng Đầu Tiên</h2>
        <p class="bd">Nhận ngay ưu đãi độc quyền khi trải nghiệm dịch vụ lần đầu — cam kết chất lượng, hiệu quả thấy rõ sau mỗi liệu trình.</p>
        <a href="#" class="bb">Nhận Ưu Đãi Ngay</a>
      </div>
    </div>
  </div>
</div>





















<style>
  @import url('https://fonts.googleapis.com/css2?family=Playfair+Display:wght@400;500&family=DM+Sans:wght@300;400;500&display=swap');

  #appt-root {
    all: initial;
    display: flex;
    justify-content: center;
    background: #ffffff;
    width: 100%;
    box-sizing: border-box;
    padding: 0px 0px 30px 0px;
  }

  #appt-root * { box-sizing: border-box; }

  #appt-root .appt-section {
    display: flex;
    gap: 40px;
    align-items: flex-start;
    width: 1000px;
    min-width: 1000px;
    font-family: 'DM Sans', sans-serif;
  }

  #appt-root .appt-form-box {
    width: 480px;
    flex-shrink: 0;
    background: #f5f1ed;
    border-radius: 0px;
    padding: 22px 20px 20px;
  }

  #appt-root .appt-row {
    display: flex;
    gap: 10px;
    margin-bottom: 10px;
  }

  #appt-root .appt-input,
  #appt-root .appt-select,
  #appt-root .appt-textarea {
    flex: 1;
    background: #ffffff;
    border: 1px solid #ece6e0;
    border-radius: 30px;
    padding: 9px 14px;
    font-size: 12px;
    color: #a09088;
    font-family: 'DM Sans', sans-serif;
    outline: none;
    appearance: none;
    -webkit-appearance: none;
    transition: border-color 0.25s ease;
    width: 100%;
  }

  #appt-root .appt-input:focus,
  #appt-root .appt-select:focus { border-color: #d97b52; color: #5a4a42; }

  #appt-root .appt-select-wrap { flex: 1; position: relative; }
  #appt-root .appt-select-wrap::after {
    content: '∨';
    position: absolute;
    right: 14px;
    top: 50%;
    transform: translateY(-50%);
    font-size: 10px;
    color: #b0a09a;
    pointer-events: none;
  }
  #appt-root .appt-select { width: 100%; }

  #appt-root .appt-textarea {
    border-radius: 10px;
    resize: vertical;
    min-height: 85px;
    padding: 10px 14px;
    display: block;
    width: 100%;
    margin-bottom: 14px;
  }
  #appt-root .appt-textarea:focus { border-color: #d97b52; color: #5a4a42; }

  #appt-root .appt-submit-row { display: flex; justify-content: flex-end; }

  #appt-root .appt-btn {
    background: #d97b52;
    color: #ffffff;
    border: none;
    border-radius: 30px;
    padding: 10px 22px;
    font-size: 12.5px;
    font-weight: 500;
    font-family: 'DM Sans', sans-serif;
    cursor: pointer;
    transition: background 0.3s ease, transform 0.25s ease;
  }
  #appt-root .appt-btn:hover { background: #c96840; transform: translateY(-2px); }

  #appt-root .appt-info {
    width: 300px;
    flex-shrink: 0;
    padding-top: 4px;
  }

  #appt-root .appt-info-title {
    font-family: 'Playfair Display', serif;
    font-size: 26px;
    font-weight: 400;
    color: #3a2a22;
    line-height: 1.3;
    margin: 0 0 22px 0;
  }

  #appt-root .appt-schedule-title {
    font-size: 13px;
    font-weight: 600;
    color: #3a2a22;
    margin: 0 0 12px 0;
  }

  #appt-root .appt-schedule-table { width: 100%; border-collapse: collapse; }
  #appt-root .appt-schedule-table tr { border-top: 1px solid #ece6e0; }
  #appt-root .appt-schedule-table td {
    padding: 9px 0;
    font-size: 12.5px;
    color: #7a6a62;
  }
  #appt-root .appt-schedule-table td:last-child {
    text-align: right;
    color: #5a4a42;
    font-weight: 500;
  }
  #appt-root .appt-closed { color: #c96840 !important; font-weight: 600 !important; }
</style>

<div id="appt-root">
  <div class="appt-section">
    <div class="appt-form-box">
      <div class="appt-row">
        <input class="appt-input" type="text" placeholder="Họ và Tên">
        <input class="appt-input" type="tel" placeholder="Số Điện Thoại">
      </div>
      <div class="appt-row">
        <div class="appt-select-wrap">
          <select class="appt-select">
            <option value="" disabled selected>Chọn Dịch Vụ</option>
            <option>Điêu Khắc Gương Mặt</option>
            <option>Điêu Khắc Vóc Dáng</option>
            <option>Chăm Sóc Da Toàn Diện</option>
          </select>
        </div>
      </div>
      <textarea class="appt-textarea" placeholder="Yêu Cầu Của Bạn"></textarea>
      <div class="appt-submit-row">
        <button class="appt-btn">Đặt Lịch Hẹn Ngay</button>
      </div>
    </div>

    <div class="appt-info">
      <h2 class="appt-info-title">Lịch Làm Việc</h2>
      <p class="appt-schedule-title">Lịch Hàng Tuần</p>
      <table class="appt-schedule-table">
        <tr><td>Thứ Hai – Thứ Bảy</td><td>7:00 SA – 5:00 CH</td></tr>
        <tr><td>Chủ Nhật</td><td class="appt-closed">ĐÓNG CỬA</td></tr>
      </table>
    </div>
  </div>
</div>








<div id="vr-root">
<style>
  @import url('https://fonts.googleapis.com/css2?family=Playfair+Display:wght@400;500&family=DM+Sans:wght@300;400;500&display=swap');
  #vr-root { all: initial; display: flex; justify-content: center; width: 100%; box-sizing: border-box; padding: 60px 0; position: relative; background-color: #f5f0eb; background-size: cover; background-position: center; }
  #vr-root * { box-sizing: border-box; }
  #vr-root .vr-wrap { position: relative; z-index: 1; width: 1000px; min-width: 1000px; font-family: 'DM Sans', sans-serif; }
  #vr-root .vr-header { text-align: center; margin-bottom: 36px; }
  #vr-root .vr-stars { display: flex; gap: 4px; justify-content: center; margin-bottom: 12px; }
  #vr-root .vr-star { color: #d97b52; font-size: 16px; }
  #vr-root .vr-title { font-family: 'Playfair Display', serif; font-size: 32px; font-weight: 400; color: #2a1a12; margin: 0 0 8px 0; line-height: 1.2; white-space: nowrap; }
  #vr-root .vr-sub { font-size: 13px; color: #7a6258; font-weight: 300; margin: 0; }
  #vr-root .vr-track-outer { overflow: hidden; background: transparent; border: none; outline: none; box-shadow: none; }
  #vr-root .vr-track { display: flex; transition: transform 0.45s cubic-bezier(0.16,1,0.3,1); background: transparent; border: none; }
  #vr-root .vr-slide { flex: 0 0 100%; width: 100%; display: flex; gap: 20px; padding: 0 4px; background: transparent; }
  #vr-root .vr-video-wrap { flex: 1; border-radius: 0px; overflow: hidden; background: transparent; border: none; }
  #vr-root .vr-video-wrap iframe { display: block; width: 100%; height: 420px; border: 0px; outline: none; margin: 0; padding: 0; }
  #vr-root .vr-nav { display: flex; align-items: center; justify-content: center; gap: 16px; margin-top: 28px; }
  #vr-root .vr-btn { width: 40px; height: 40px; border-radius: 50%; border: 1.5px solid rgba(180,150,130,0.5); background: rgba(255,255,255,0.6); display: flex; align-items: center; justify-content: center; cursor: pointer; font-size: 15px; color: #5a3a2a; transition: border-color 0.2s, color 0.2s, background 0.2s; }
  #vr-root .vr-btn:hover { border-color: #d97b52; color: #d97b52; background: rgba(255,255,255,0.9); }
  #vr-root .vr-dots { display: flex; gap: 8px; }
  #vr-root .vr-dot { width: 7px; height: 7px; border-radius: 50%; background: rgba(90,58,42,0.25); cursor: pointer; transition: background 0.2s, transform 0.2s; }
  #vr-root .vr-dot.active { background: #d97b52; transform: scale(1.25); }
</style>

  <div style="position:absolute;inset:0;z-index:0;overflow:hidden;">
    <img src="https://i.pinimg.com/736x/9f/57/40/9f57405a1e7640773a528671669b846f.jpg" style="width:100%;height:100%;object-fit:cover;display:block;" alt="">
  </div>

  <div class="vr-wrap">
    <div class="vr-header">
      <div class="vr-stars">
        <span class="vr-star">★</span><span class="vr-star">★</span><span class="vr-star">★</span><span class="vr-star">★</span><span class="vr-star">★</span>
      </div>
      <h2 class="vr-title">Khách Hàng Nói Gì Về Chúng Tôi</h2>
      <p class="vr-sub">Trải nghiệm thực tế từ khách hàng tại Bệnh viện Thẩm mỹ Nam An</p>
    </div>

    <div class="vr-track-outer">
      <div class="vr-track" id="vrTrack">
        <div class="vr-slide">
          <div class="vr-video-wrap">
            <iframe src="https://www.youtube.com/embed/eDMEAHi-2YI" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
          </div>
          <div class="vr-video-wrap">
            <iframe src="https://www.youtube.com/embed/sekU53WSOsY" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
          </div>
        </div>
        <div class="vr-slide">
          <div class="vr-video-wrap">
            <iframe src="https://www.youtube.com/embed/tG-2vEQvMd0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
          </div>
          <div class="vr-video-wrap">
            <iframe src="https://www.youtube.com/embed/w_KhcgEJHgo" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
          </div>
        </div>
      </div>
    </div>

    <div class="vr-nav">
      <button class="vr-btn" id="vrPrev">←</button>
      <div class="vr-dots">
        <div class="vr-dot active" data-i="0"></div>
        <div class="vr-dot" data-i="1"></div>
      </div>
      <button class="vr-btn" id="vrNext">→</button>
    </div>
  </div>
</div>

<script>
(function() {
  const track = document.getElementById('vrTrack');
  const dots = document.querySelectorAll('#vr-root .vr-dot');
  let cur = 0;
  const total = 2;
  function go(n) {
    cur = (n + total) % total;
    track.style.transform = 'translateX(-' + (cur * 100) + '%)';
    dots.forEach((d, i) => d.classList.toggle('active', i === cur));
  }
  document.getElementById('vrPrev').addEventListener('click', () => go(cur - 1));
  document.getElementById('vrNext').addEventListener('click', () => go(cur + 1));
  dots.forEach(d => d.addEventListener('click', () => go(+d.dataset.i)));
})();
</script>












<iframe srcdoc="
<!DOCTYPE html>
<html lang='vi'>
<head>
  <meta charset='UTF-8'>
  <meta name='viewport' content='width=device-width, initial-scale=1.0'>
  <title>Blog Thẩm Mỹ</title>
  <link href='https://fonts.googleapis.com/css2?family=Playfair+Display:wght@400;500;600&family=DM+Sans:wght@300;400;500&display=swap' rel='stylesheet'>
  <style>
    * { margin:0; padding:0; box-sizing:border-box; }
    html, body { background:; font-family:'DM Sans',sans-serif; color:#3d2d26; overflow:hidden; } /* Triệt tiêu khả năng tạo scroll nội bộ */
    
    /* ĐÃ THÊM PADDING BOTTOM 50PX THEO YÊU CẦU */
    .blog-section { width:100%; max-width:1000px; margin:auto; padding:35px 20px 50px 20px; }
    
    .top-header { display:flex; justify-content:space-between; align-items:flex-start; margin-bottom:30px; }
    .title-wrap h2 { font-size:42px; font-family:'Playfair Display',serif; font-weight:500; line-height:1.1; margin-bottom:8px; color:#3c2a24; }
    .title-wrap p { color:#9b918a; font-size:13px; font-weight:300; line-height:1.6; }
    .load-btn { border:none; background:#f28a57; color:#fff; padding:13px 28px; border-radius:50px; font-size:13px; font-family:'DM Sans',sans-serif; cursor:pointer; transition:0.3s; white-space:nowrap; }
    .load-btn:hover { background:#df7543; }
    .blog-grid { display:grid; grid-template-columns:1fr 1fr; gap:35px 55px; }
    .blog-card { display:flex; align-items:center; gap:22px; }
    .blog-image { width:230px; height:135px; border-radius:0 90px 90px 0; overflow:hidden; flex-shrink:0; }
    .blog-image img { width:100%; height:100%; object-fit:cover; display:block; }
    .blog-content { flex:1; }
    .category { display:inline-block; background:#f8ddd1; color:#d07a55; padding:6px 12px; border-radius:30px; font-size:11px; margin-bottom:12px; font-weight:500; }
    .blog-content h3 { font-size:22px; line-height:1.3; font-family:'Playfair Display',serif; font-weight:500; color:#3a2a23; margin-bottom:12px; }
    .date { font-size:12px; color:#a79d95; display:flex; align-items:center; gap:7px; font-weight:300; }
    .date::before { content:'◉'; font-size:7px; }
    
    @media(max-width:1024px){ 
        .blog-grid { grid-template-columns:1fr; gap:30px; } 
    }
    @media(max-width:768px){
        .blog-section { padding:20px 15px 50px 15px; } /* Giữ padding bottom 50px trên mobile */
        .top-header { flex-direction:column; gap:20px; }
        .blog-card { flex-direction:column; align-items:flex-start; gap:15px; }
        .blog-image { width:100%; height:220px; border-radius:0 40px 40px 0; }
        .title-wrap h2 { font-size:34px; }
        .blog-content h3 { font-size:20px; }
    }
  </style>
</head>
<body>
  <section class='blog-section'>
      <div class='top-header'>
          <div class='title-wrap'>
              <h2>Bài Viết Mới Nhất</h2>
              <p>Khám phá kiến thức làm đẹp và chăm sóc sức khỏe từ các chuyên gia hàng đầu.</p>
          </div>
          <button class='load-btn'>Xem Thêm Bài Viết</button>
      </div>
      <div class='blog-grid'>
          <div class='blog-card'>
              <div class='blog-image'>
                  <img src='https://images.unsplash.com/photo-1515377905703-c4788e51af15?q=80&w=1200&auto=format&fit=crop'>
              </div>
              <div class='blog-content'>
                  <span class='category'>Thẩm Mỹ</span>
                  <h3>Xu Hướng Phẫu Thuật Thẩm Mỹ Hiện Đại Bạn Nên Biết</h3>
                  <div class='date'>05 Tháng 12, 2023</div>
              </div>
          </div>
          <div class='blog-card'>
              <div class='blog-image'>
                  <img src='https://images.unsplash.com/photo-1559599101-f09722fb4948?q=80&w=1200&auto=format&fit=crop'>
              </div>
              <div class='blog-content'>
                  <span class='category'>Làm Đẹp</span>
                  <h3>Hành Trình Thay Đổi Ngoại Hình Của Những Khách Hàng Thật</h3>
                  <div class='date'>05 Tháng 12, 2023</div>
              </div>
          </div>
          <div class='blog-card'>
              <div class='blog-image'>
                  <img src='https://images.unsplash.com/photo-1570172619644-dfd03ed5d881?q=80&w=1200&auto=format&fit=crop'>
              </div>
              <div class='blog-content'>
                  <span class='category'>Chăm Sóc Da</span>
                  <h3>Khám Phá Công Nghệ Làm Đẹp Mới Nhất Trong Thẩm Mỹ</h3>
                  <div class='date'>05 Tháng 12, 2023</div>
              </div>
          </div>
          <div class='blog-card'>
              <div class='blog-image'>
                  <img src='https://images.unsplash.com/photo-1616391182219-e080b4d1043a?q=80&w=1200&auto=format&fit=crop'>
              </div>
              <div class='blog-content'>
                  <span class='category'>Điêu Khắc</span>
                  <h3>Quy Trình Và Khoa Học Đằng Sau Phẫu Thuật Tạo Hình Cơ Thể</h3>
                  <div class='date'>05 Tháng 12, 2023</div>
              </div>
          </div>
      </div>
  </section>
</body>
</html>
" scrolling="no" style="width: 100%; height: 580px; border: none; overflow: hidden; display: block; background: #ffffff;"></iframe>















<iframe srcdoc="
<!DOCTYPE html>
<html lang='vi'>
<head>
  <meta charset='UTF-8'>
  <meta name='viewport' content='width=device-width, initial-scale=1.0'>
  <title>Footer Premium</title>
  <link rel='stylesheet' href='https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css'>
  <link href='https://fonts.googleapis.com/css2?family=Fahkwang:wght@700;800&family=Be+Vietnam+Pro:wght@300;400;600;700&display=swap' rel='stylesheet'>
  <style>
    * { margin:0; padding:0; box-sizing:border-box !important; }
    body { background:#fff; padding:0; overflow-x:hidden; }

    .na-footer-premium {
        background-image: url('https://benhvienthammynaman.com/wp-content/uploads/2026/05/Trang-mua-hang.png');
        background-size: cover;
        background-position: center center;
        background-repeat: no-repeat;
        color: #733F2E !important;
        padding: 60px !important;
        position: relative;
        overflow: hidden;
        font-family: 'Be Vietnam Pro', sans-serif !important;
        line-height: 1.5 !important;
        text-align: left !important;
    }

    .na-footer-wrapper {
        max-width: 1200px !important;
        margin: 0 auto !important;
        padding: 0 20px !important;
        display: grid !important;
        grid-template-columns: 1fr 1fr 1fr !important;
        gap: 40px !important;
        position: relative;
        z-index: 2;
        align-items: start;
    }

    /* Cột 1 */
    .na-info-col { display: flex; flex-direction: column; }

    .na-brand-logo {
        font-family: 'Fahkwang', sans-serif;
        font-size: 18px;
        font-weight: 800;
        margin-bottom: 20px;
        display: block;
        color: #733F2E;
        white-space: nowrap;
        overflow: hidden;
        text-overflow: ellipsis;
    }

    .na-hotline-highlight {
        background: #F37043;
        color: #fff !important;
        padding: 12px 20px;
        border-radius: 50px;
        display: inline-flex;
        align-items: center;
        gap: 12px;
        text-decoration: none !important;
        margin-bottom: 24px;
        transition: 0.4s cubic-bezier(0.175, 0.885, 0.32, 1.275);
        box-shadow: 0 10px 25px rgba(243,112,67,0.4);
    }

    .na-hotline-highlight:hover { transform: scale(1.05); background: #E65A28; }

    .na-hotline-highlight i {
        font-size: 20px;
        background: rgba(255,255,255,0.25);
        color: white !important;
        width: 38px;
        height: 38px;
        display: flex;
        align-items: center;
        justify-content: center;
        border-radius: 50%;
        flex-shrink: 0;
    }

    .na-hotline-text span {
        display: block;
        font-size: 11px;
        font-weight: 600;
        text-transform: uppercase;
        opacity: 0.9;
        color: #fff;
        white-space: nowrap;
    }

    .na-hotline-text b { font-size: 20px; letter-spacing: 1px; color: #fff; white-space: nowrap; }

    .na-contact-details p {
        margin: 10px 0 !important;
        font-size: 13.5px;
        display: flex;
        align-items: flex-start;
        color: #733F2E !important;
    }

    /* Cột 2 */
    .na-links-col { display: flex; flex-direction: column; }

    .na-footer-title {
        font-family: 'Fahkwang', sans-serif;
        font-size: 17px;
        font-weight: 700;
        margin-bottom: 22px;
        position: relative;
        display: inline-block;
        color: #733F2E;
    }

    .na-footer-title::after {
        content: '';
        position: absolute;
        width: 30px;
        height: 2px;
        background: #F37043;
        bottom: -8px;
        left: 0;
    }

    .na-footer-links { list-style: none !important; padding: 0 !important; margin: 0 !important; }
    .na-footer-links li { margin-bottom: 11px !important; background: none !important; }
    .na-footer-links a {
        color: #733F2E !important;
        text-decoration: none !important;
        transition: 0.3s;
        font-size: 13.5px;
        opacity: 0.85;
    }
    .na-footer-links a:hover { color: #F37043 !important; padding-left: 8px; opacity: 1; }

    /* Mã số thuế + DMCA nằm dưới list, cạnh nhau */
    .na-links-bottom {
        margin-top: 20px;
        padding-top: 16px;
        border-top: 1px solid rgba(115,63,46,0.25);
        display: flex;
        align-items: center;
        gap: 16px;
        flex-wrap: wrap;
    }

    .na-tax-text {
        font-size: 13px;
        color: #733F2E;
        white-space: nowrap;
        font-weight: 600;
    }

    .na-dmca-badge {
        display: inline-block;
        border-radius: 8px;
        overflow: hidden;
        border: 1px solid rgba(115,63,46,0.2);
        transition: 0.3s;
        background: #fff;
        padding: 5px 8px;
        flex-shrink: 0;
    }

    .na-dmca-badge img {
        width: 90px;
        height: auto;
        display: block;
        object-fit: contain;
    }

    .na-dmca-badge:hover {
        transform: translateY(-2px);
        border-color: #F37043;
        box-shadow: 0 4px 12px rgba(243,112,67,0.2);
    }

    /* Cột 3 */
    .na-form-col {
        background: rgba(255,255,255,0.55);
        padding: 22px 26px 18px;
        border-radius: 20px;
        border: 1px solid rgba(115,63,46,0.2);
        backdrop-filter: blur(10px);
        -webkit-backdrop-filter: blur(10px);
    }

    .na-form-col h3 {
        font-family: 'Fahkwang', sans-serif;
        margin-top: 0;
        font-size: 17px;
        margin-bottom: 14px;
        color: #733F2E;
    }

    .na-footer-form input,
    .na-footer-form textarea {
        width: 100%;
        padding: 9px 13px;
        margin-bottom: 10px;
        border-radius: 8px;
        border: 1px solid rgba(115,63,46,0.25) !important;
        background: rgba(255,255,255,0.95) !important;
        font-family: 'Be Vietnam Pro', sans-serif !important;
        font-size: 13.5px;
        color: #733F2E;
    }

    .na-footer-form input::placeholder,
    .na-footer-form textarea::placeholder { color: #a07060; }

    .na-footer-form textarea { height: 65px; resize: none; }

    .na-footer-form button {
        width: 100%;
        padding: 11px;
        border-radius: 8px;
        border: none;
        background: #F37043 !important;
        color: white !important;
        font-weight: 700;
        cursor: pointer;
        transition: 0.3s;
        text-transform: uppercase;
        font-family: 'Fahkwang', sans-serif;
        margin-top: 4px;
        letter-spacing: 1px;
        font-size: 13px;
    }

    .na-footer-form button:hover {
        background: #E65A28 !important;
        transform: translateY(-2px);
    }

    /* License row */
    .na-license-row {
        max-width: 1200px !important;
        margin: 36px auto 0 !important;
        padding: 0 20px !important;
        display: grid !important;
        grid-template-columns: repeat(4, 1fr) !important;
        gap: 16px !important;
        position: relative;
        z-index: 2;
    }

    .na-license-box {
        border-radius: 10px;
        overflow: hidden;
        border: 1px solid rgba(115,63,46,0.3);
        background: rgba(255,255,255,0.1);
        transition: 0.4s;
    }

    .na-license-box img {
        width: 100%;
        height: 160px;
        object-fit: cover;
        display: block;
    }

    .na-license-box:hover {
        transform: translateY(-4px);
        background: rgba(255,255,255,0.25);
        border-color: #733F2E;
    }

    @media (max-width: 992px) {
        .na-footer-wrapper { grid-template-columns: 1fr !important; gap: 32px !important; }
        .na-license-row { grid-template-columns: repeat(2, 1fr) !important; }
    }
    @media (max-width: 767px) {
        .na-license-row { grid-template-columns: 1fr !important; }
    }
  </style>
</head>
<body>

<footer class='na-footer-premium'>
    <div class='na-footer-wrapper'>

        <!-- Cột 1 -->
        <div class='na-info-col'>
            <span class='na-brand-logo'>BỆNH VIỆN THẨM MỸ NAM AN</span>
            <a href='tel:0901939229' class='na-hotline-highlight'>
                <i class='fa fa-phone'></i>
                <div class='na-hotline-text'>
                    <span>Tổng đài tư vấn 24/7</span>
                    <b>0901 939 229</b>
                </div>
            </a>
            <div class='na-contact-details'>
                <p><i class='fa-solid fa-location-dot' style='width:18px; margin-right:9px; flex-shrink:0'></i> 45A, Ba Tháng Hai, P. Vườn Lài, TP.HCM</p>
                <p><i class='fa-solid fa-envelope' style='width:18px; margin-right:9px; flex-shrink:0'></i> contact@bvnaman.com</p>
                <p><i class='fa-solid fa-clock' style='width:18px; margin-right:9px; flex-shrink:0'></i> 08:00 - 20:00 (Thứ 2 - CN)</p>
            </div>
        </div>

        <!-- Cột 2 -->
        <div class='na-links-col'>
            <h3 class='na-footer-title'>VỀ CHÚNG TÔI</h3>
            <ul class='na-footer-links'>
                <li><a href='#'><i class='fa fa-chevron-right' style='font-size:10px; margin-right:7px'></i> Giới thiệu bệnh viện</a></li>
                <li><a href='#'><i class='fa fa-chevron-right' style='font-size:10px; margin-right:7px'></i> Đội ngũ chuyên gia</a></li>
                <li><a href='#'><i class='fa fa-chevron-right' style='font-size:10px; margin-right:7px'></i> Cơ sở vật chất</a></li>
                <li><a href='#'><i class='fa fa-chevron-right' style='font-size:10px; margin-right:7px'></i> Chính sách bảo mật</a></li>
                <li><a href='#'><i class='fa fa-chevron-right' style='font-size:10px; margin-right:7px'></i> Quy chế hoạt động</a></li>
            </ul>
            <div class='na-links-bottom'>
                <span class='na-tax-text'>Mã số thuế: 0315700968</span>
                <a href='https://www.dmca.com' target='_blank' class='na-dmca-badge'>
                    <img src='https://www.dmca.com/img/dmca-website-logo-2022.png' alt='DMCA Protected'>
                </a>
            </div>
        </div>

        <!-- Cột 3 -->
        <div class='na-form-col'>
            <h3>NHẬN TƯ VẤN MIỄN PHÍ</h3>
            <form class='na-footer-form'>
                <input type='text' placeholder='Họ và tên của bạn' required>
                <input type='tel' placeholder='Số điện thoại' required>
                <textarea placeholder='Nhu cầu tư vấn của bạn'></textarea>
                <button type='submit'>Gửi yêu cầu ngay</button>
            </form>
        </div>

    </div>

    <div class='na-license-row'>
        <div class='na-license-box'><img src='https://cdn.accgroup.vn/wp-content/uploads/2023/06/giay-phep-chua-benh.jpg' alt='Giấy phép 1'></div>
        <div class='na-license-box'><img src='https://cdn.accgroup.vn/wp-content/uploads/2023/06/giay-phep-chua-benh.jpg' alt='Giấy phép 2'></div>
        <div class='na-license-box'><img src='https://cdn.accgroup.vn/wp-content/uploads/2023/06/giay-phep-chua-benh.jpg' alt='Giấy phép 3'></div>
        <div class='na-license-box'><img src='https://cdn.accgroup.vn/wp-content/uploads/2023/06/giay-phep-chua-benh.jpg' alt='Giấy phép 4'></div>
    </div>
</footer>

</body>
</html>
" style="width:100%; min-height:660px; border:none; overflow:visible; display:block; background:#ffffff;"></iframe>
