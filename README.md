<!DOCTYPE html>
<html lang="vi">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>12C2 - THPT Gio Linh</title>
<link rel="stylesheet" href="style.css">
</head>

<body>

<!-- Popup -->
<div class="welcome">
  💙 Chào mừng đến với website lớp 12C2 💙
</div>

<!-- Header -->
<header>
  <h1>TRƯỜNG THPT GIO LINH</h1>
  <h2>TẬP THỂ LỚP 12C2</h2>
  <h3>👩‍🏫 GVCN: TRẦN MAI LY 💖</h3>
</header>

<!-- Menu -->
<nav>
  <button onclick="show('home')">Trang chủ</button>
  <button onclick="show('about')">Giới thiệu</button>
  <button onclick="show('members')">Thành viên</button>
  <button onclick="show('gallery')">Kỷ niệm</button>
  <button onclick="show('contact')">Liên hệ</button>
</nav>

<!-- Trang chủ -->
<section id="home" class="active">
  <h2>Thanh Xuân 12C2 💙</h2>
  <p>
    Ba năm cấp ba dưới mái trường THPT Gio Linh là hành trình
    đẹp nhất của tuổi trẻ. Có áp lực, có mệt mỏi,
    nhưng luôn có nhau.
  </p>

  <div class="countdown">
    ⏳ Đếm ngược thi THPT:
    <h3 id="time"></h3>
  </div>
</section>

<!-- Giới thiệu -->
<section id="about">
  <h2>Giới thiệu tập thể 12C2</h2>
  <p>
    12C2 không chỉ là một lớp học,
    mà là một gia đình đúng nghĩa.
    Ở đó có tiếng cười giòn tan,
    có những giờ học nghiêm túc,
    có sự cố gắng không ai bỏ lại ai phía sau.
  </p>
  <p>
    Dưới sự dẫn dắt của cô giáo chủ nhiệm
    TRẦN MAI LY – tận tâm và yêu thương học sinh,
    tập thể 12C2 đã trưởng thành từng ngày.
  </p>
</section>

<!-- Thành viên -->
<section id="members">
  <h2>Tập thể 12C2</h2>

  <div class="card">
    <h3>Lớp trưởng</h3>
    <p>Thông tin đang cập nhật...</p>
  </div>

  <div class="card">
    <h3>Bí thư</h3>
    <p>Thông tin đang cập nhật...</p>
  </div>

  <div class="card">
    <h3>Đoàn viên</h3>
    <p>Chúng tôi là một tập thể đoàn kết và năng động.</p>
  </div>
</section>

<!-- Kỷ niệm -->
<section id="gallery">
  <h2>Kỷ niệm 3 năm</h2>
  <div class="gallery">
    <img src="https://picsum.photos/300?1">
    <img src="https://picsum.photos/300?2">
    <img src="https://picsum.photos/300?3">
    <img src="https://picsum.photos/300?4">
  </div>
</section>

<!-- Liên hệ -->
<section id="contact">
  <h2>Liên hệ</h2>
  <p>Email: nguyenlamvy09@gmail.com</p>
  <p>Địa chỉ: Lớp 12C2 – THPT Gio Linh</p>
</section>

<footer>
  🌸 Website kỷ niệm tập thể lớp 12C2 🌸
</footer>

<script src="script.js"></script>
</body>
</html>
