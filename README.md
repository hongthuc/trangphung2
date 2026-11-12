<html lang="vi">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=5.0">
  <title>Nhà Phân Phối Trang Phụng - Vật Tư Kim Khí & Thiết Bị Công Nghiệp Đà Nẵng | trangphung.com</title>
  <meta name="description" content="Nhà Phân Phối Trang Phụng (trangphung.com) chuyên cung ứng vật tư kim khí công nghiệp, bulong ốc vít, dụng cụ cầm tay, đá mài, keo dán, sơn công nghiệp, thiết bị khí nén tại 338-340 Bùi Thiện Ngộ, Hòa Xuân, Đà Nẵng.">

  <!-- Open Graph / Zalo / Facebook Share Thumbnail là Logo trang web -->
  <meta property="og:type" content="website">
  <meta property="og:url" content="https://trangphung.com/">
  <meta property="og:title" content="Nhà Phân Phối Trang Phụng - Kim Khí & Vật Tư Công Nghiệp | trangphung.com">
  <meta property="og:description" content="Chuyên phân phối Bulong Ốc Vít, Dầu Mỡ Hóa Chất, Keo Dán, Sơn PU/NC, Dụng Cụ Cầm Tay, Đồ Mài, Thiết Bị Khí Nén. Đ/c: 338-340 Bùi Thiện Ngộ, Hòa Xuân, Đà Nẵng.">
  <meta property="og:image" content="https://drive.google.com/thumbnail?id=10KscawaPXgqAAjwNXC6srgtzYC8sREWN&sz=w1200">
  <meta property="og:image:alt" content="Logo Nhà Phân Phối Trang Phụng">
  <meta name="twitter:card" content="summary_large_image">
  <meta name="twitter:image" content="https://drive.google.com/thumbnail?id=10KscawaPXgqAAjwNXC6srgtzYC8sREWN&sz=w1200">
  <link rel="icon" href="https://drive.google.com/thumbnail?id=10KscawaPXgqAAjwNXC6srgtzYC8sREWN&sz=w200">

  <!-- Google Fonts: Inter -->
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&display=swap" rel="stylesheet">

  <!-- Font Awesome 6 Icons -->
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">

  <!-- Tailwind CSS CDN -->
  <script src="https://cdn.tailwindcss.com"></script>
  <script>
    tailwind.config = {
      theme: {
        extend: {
          fontFamily: {
            sans: ['Inter', 'sans-serif'],
          },
          colors: {
            brand: {
              DEFAULT: '#0f4c81',
              dark: '#09355c',
              light: '#e6f0f9',
              accent: '#d9251d',
              gold: '#f59e0b'
            }
          }
        }
      }
    }
  </script>

  <!-- Trình xử lý tải ảnh Google Drive đa luồng đảm bảo hiển thị 100% -->
  <script>
    function handleDriveImgError(img) {
      const fileId = img.getAttribute('data-drive-id');
      const fallbackLabel = encodeURIComponent(img.getAttribute('data-label') || 'Trang Phung');
      const step = parseInt(img.getAttribute('data-retry-step') || '0', 10);

      if (!fileId) return;

      if (step === 0) {
        img.setAttribute('data-retry-step', '1');
        img.src = 'https://lh3.googleusercontent.com/d/' + fileId + '=w1000';
      } else if (step === 1) {
        img.setAttribute('data-retry-step', '2');
        img.src = 'https://drive.google.com/uc?export=view&id=' + fileId;
      } else if (step === 2) {
        img.setAttribute('data-retry-step', '3');
        img.src = 'https://drive.google.com/thumbnail?id=' + fileId + '&sz=w800';
      } else {
        img.onerror = null;
        img.src = 'https://placehold.co/600x600/f1f5f9/0f4c81?text=' + fallbackLabel;
      }
    }
  </script>

  <style>
    /* Reset chuẩn tránh tràn viền hoặc lệch phải trên mọi thiết bị & tương thích hoàn toàn khi nhúng vào Flatsome/WordPress */
    *, *::before, *::after {
      box-sizing: border-box;
    }
    html, body {
      width: 100% !important;
      max-width: 100% !important;
      overflow-x: hidden !important;
      margin: 0 !important;
      padding: 0 !important;
      font-family: 'Inter', sans-serif;
      background-color: #f4f6f9;
      color: #1e293b;
      -webkit-text-size-adjust: 100%;
    }

    /* Tự động xóa toàn bộ margin/padding/shadow của mọi thẻ cha bao ngoài trên WordPress / Flatsome gây đẩy lệch sang phải */
    html:has(#tp-site-wrapper),
    body:has(#tp-site-wrapper),
    *:has(#tp-site-wrapper) {
      margin-left: 0 !important;
      margin-right: 0 !important;
      padding-left: 0 !important;
      padding-right: 0 !important;
      left: 0 !important;
      right: 0 !important;
      width: 100% !important;
      max-width: 100% !important;
      min-width: 0 !important;
      box-sizing: border-box !important;
      transform: none !important;
    }

    #main, #content, #wrapper, .page-wrapper, .entry-content, .page-inner, .col-inner, .container, .row, .col, article, section {
      max-width: 100% !important;
      box-sizing: border-box !important;
    }

    @media (max-width: 1023px) {
      .entry-header, .page-title, h1.entry-title, header.entry-header {
        display: none !important;
      }
      *:has(#tp-site-wrapper) {
        display: block !important;
        margin: 0 !important;
        padding: 0 !important;
        border: 0 !important;
        box-shadow: none !important;
        width: 100% !important;
        max-width: 100% !important;
      }
      #wrapper, #main, #content, .page-wrapper, .entry-content, .page-inner, .container, .row, .col, .col-inner {
        padding-left: 0 !important;
        padding-right: 0 !important;
        margin-left: 0 !important;
        margin-right: 0 !important;
        width: 100% !important;
        max-width: 100% !important;
        box-shadow: none !important;
      }
    }

    /* Khung bao tổng chống tràn ngang tuyệt đối */
    #tp-site-wrapper {
      width: 100% !important;
      max-width: 100% !important;
      overflow-x: hidden !important;
      margin: 0 auto !important;
      padding: 0 !important;
      position: relative;
      left: 0 !important;
      right: 0 !important;
    }

    /* Ngăn CSS mặc định của Flatsome tự cộng thêm margin vào button, input, form, heading gây lệch phải */
    #tp-site-wrapper h1,
    #tp-site-wrapper h2,
    #tp-site-wrapper h3,
    #tp-site-wrapper p,
    #tp-site-wrapper form,
    #tp-site-wrapper input,
    #tp-site-wrapper select,
    #tp-site-wrapper textarea,
    #tp-site-wrapper button,
    #tp-site-wrapper a {
      margin-top: 0;
      margin-bottom: 0;
      margin-left: 0;
      margin-right: 0;
    }

    /* Chiều ngang giao diện trên máy tính bằng 95% kích thước màn hình máy tính, trên điện thoại vừa khít 100% căn giữa */
    .flatsome-container {
      width: 100% !important;
      max-width: 100% !important;
      margin-left: auto !important;
      margin-right: auto !important;
      padding-left: 10px !important;
      padding-right: 10px !important;
      box-sizing: border-box !important;
    }
    @media (min-width: 1024px) {
      .flatsome-container {
        width: 95% !important;
        max-width: 95% !important;
        padding-left: 0 !important;
        padding-right: 0 !important;
      }
    }

    /* Ép các ô trong Grid (danh mục, sản phẩm) co giãn vừa khít cột trên điện thoại, không đẩy khung sang phải */
    .cat-card {
      min-width: 0 !important;
      width: 100% !important;
      max-width: 100% !important;
      overflow: hidden !important;
    }

    /* Tối ưu tên danh mục trên máy tính: viết liền trên 1 hàng, không xuống dòng chữ bên trong */
    .desktop-cat-pill {
      white-space: nowrap;
      display: inline-flex;
      align-items: center;
      gap: 5px;
      font-size: 12px;
      line-height: 1.2;
      padding: 7px 11px;
      border-radius: 6px;
      font-weight: 600;
      transition: all 0.2s ease;
    }

    /* Tên sản phẩm đầy đủ, không bị cắt chữ hay tràn ra ngoài */
    .product-title-full {
      word-break: break-word;
      overflow-wrap: break-word;
      white-space: normal;
      line-height: 1.38;
    }

    /* Nhãn % giảm giá góc trên bên trái chuẩn Flatsome */
    .flatsome-sale-badge {
      position: absolute;
      top: 8px;
      left: 8px;
      z-index: 10;
      background: linear-gradient(135deg, #d9251d 0%, #b91c1c 100%);
      color: #ffffff;
      font-weight: 700;
      font-size: 11px;
      line-height: 1;
      padding: 5px 7px;
      border-radius: 9999px;
      box-shadow: 0 2px 6px rgba(217, 37, 29, 0.35);
    }

    /* Hiệu ứng nổi cho nút liên hệ */
    @keyframes pulseRing {
      0% { transform: scale(0.95); box-shadow: 0 0 0 0 rgba(217, 37, 29, 0.6); }
      70% { transform: scale(1); box-shadow: 0 0 0 10px rgba(217, 37, 29, 0); }
      100% { transform: scale(0.95); box-shadow: 0 0 0 0 rgba(217, 37, 29, 0); }
    }
    .pulse-btn {
      animation: pulseRing 2s infinite;
    }
  </style>
</head>
<body class="min-h-screen flex flex-col">
  <div id="tp-site-wrapper" class="min-h-screen flex flex-col w-full max-w-full overflow-x-hidden">

  <!-- ================= TOP BAR (Đơn giản, chuẩn Flatsome, không có thanh công cụ UX Builder) ================= -->
  <div class="bg-[#09355c] text-white text-[11px] sm:text-xs py-1.5 border-b border-white/10 w-full">
    <div class="flatsome-container flex flex-wrap items-center justify-between gap-2">
      <div class="flex items-center gap-2 min-w-0 max-w-full overflow-hidden">
        <span class="font-semibold tracking-wide uppercase text-amber-300 truncate block">CHÀO MỪNG BẠN ĐẾN VỚI NHÀ PHÂN PHỐI TRANG PHỤNG</span>
        <span class="hidden md:inline text-white/60">|</span>
        <span class="hidden md:inline text-white/90">Website chính thức: <strong>trangphung.com</strong></span>
      </div>
      <div class="hidden sm:flex items-center gap-4 text-white/90">
        <span><i class="fa-solid fa-location-dot text-amber-400 mr-1"></i>338-340 Bùi Thiện Ngộ, P. Hòa Xuân, TP. Đà Nẵng</span>
        <span><i class="fa-regular fa-clock text-amber-400 mr-1"></i>7:00 - 18:00 (T2 - CN)</span>
      </div>
    </div>
  </div>

  <!-- ================= HEADER MAIN (Logo gọn nhỏ, Không để nút Gọi ngay trên Header tránh tràn viền) ================= -->
  <header class="bg-white shadow-sm sticky top-0 z-40 border-b border-slate-200 w-full">
    <div class="flatsome-container py-2.5">
      <div class="flex items-center justify-between gap-1.5 sm:gap-4 w-full min-w-0">
        
        <!-- Nút mở menu danh mục trên điện thoại -->
        <button type="button" onclick="toggleMobileDrawer()" aria-label="Mở danh mục" class="lg:hidden inline-flex items-center justify-center w-9 h-9 rounded-lg bg-slate-100 text-[#0f4c81] hover:bg-slate-200 shrink-0">
          <i class="fa-solid fa-bars text-base"></i>
        </button>

        <!-- Logo chỉnh gọn nhỏ lại (cho phép co giãn min-w-0 flex-1 trên điện thoại để không đẩy tràn lề phải) -->
        <a href="#top" class="flex items-center gap-2 flex-1 lg:flex-initial min-w-0 overflow-hidden">
          <div class="w-9 h-9 sm:w-11 sm:h-11 rounded-lg bg-white border border-slate-200 p-1 flex items-center justify-center overflow-hidden shrink-0 shadow-xs">
            <img 
              src="https://drive.google.com/thumbnail?id=10KscawaPXgqAAjwNXC6srgtzYC8sREWN&sz=w400" 
              data-drive-id="10KscawaPXgqAAjwNXC6srgtzYC8sREWN"
              data-label="LOGO"
              onerror="handleDriveImgError(this)"
              alt="Logo Nhà Phân Phối Trang Phụng" 
              class="max-h-7 sm:max-h-9 w-auto object-contain"
            >
          </div>
          <div class="leading-tight min-w-0 flex-1 overflow-hidden">
            <div class="text-[11px] sm:text-sm md:text-base font-extrabold text-[#0f4c81] uppercase tracking-tight truncate">NHÀ PHÂN PHỐI TRANG PHỤNG</div>
            <div class="text-[10px] sm:text-[11px] text-slate-500 font-medium truncate">Kim Khí • Vật Tư Công Nghiệp • trangphung.com</div>
          </div>
        </a>

        <!-- Thanh tìm kiếm chuẩn Flatsome giống kimkhithanhthang.com -->
        <div class="hidden md:flex flex-1 max-w-2xl mx-2">
          <form onsubmit="handleSearchSubmit(event)" class="w-full flex items-center border-2 border-[#0f4c81] rounded-lg overflow-hidden bg-white">
            <select id="desktopSearchCat" aria-label="Chọn danh mục" class="bg-slate-50 text-slate-700 text-xs font-medium px-2.5 py-2.5 border-r border-slate-200 focus:outline-none max-w-[155px]">
              <option value="all">Tất cả danh mục</option>
              <option value="Bulong – Ốc Vít">Bulong – Ốc Vít</option>
              <option value="Dầu Mỡ – Hóa Chất">Dầu Mỡ – Hóa Chất</option>
              <option value="Dụng Cụ Cầm Tay">Dụng Cụ Cầm Tay</option>
              <option value="Dụng Cụ Đồ Mài">Dụng Cụ Đồ Mài</option>
              <option value="Dụng Cụ Tiêu Hao">Dụng Cụ Tiêu Hao</option>
              <option value="Dụng Cụ Phòng Khuôn">Dụng Cụ Phòng Khuôn</option>
              <option value="Thiết Bị Khí Nén">Thiết Bị Khí Nén</option>
              <option value="Thiết Bị Máy Móc">Thiết Bị Máy Móc</option>
              <option value="Đồ Bảo Hộ Lao Động">Đồ Bảo Hộ Lao Động</option>
              <option value="Vòng Bi – Nam Châm">Vòng Bi – Nam Châm</option>
            </select>
            <input 
              id="desktopSearchInput"
              type="text" 
              placeholder="Tìm kiếm bulong, đá mài, keo silicon, sơn, dụng cụ cầm tay..." 
              class="flex-1 px-3 py-2 text-xs sm:text-sm text-slate-800 focus:outline-none min-w-0"
            >
            <button type="submit" class="bg-[#0f4c81] hover:bg-[#09355c] text-white px-4 py-2.5 text-xs font-semibold transition shrink-0">
              <i class="fa-solid fa-magnifying-glass mr-1"></i>Tìm
            </button>
          </form>
        </div>

        <!-- Cụm điều hướng nhanh gọn (Không để nút Gọi ngay để tránh tràn viền) -->
        <div class="flex items-center gap-1.5 sm:gap-2 shrink-0">
          <a href="#form-bao-gia" class="inline-flex items-center gap-1.5 px-2.5 py-2 rounded-lg bg-amber-50 hover:bg-amber-100 text-[#0f4c81] border border-amber-200 text-xs font-bold transition">
            <i class="fa-solid fa-file-invoice text-[#d9251d]"></i>
            <span class="hidden sm:inline">Nhận Báo Giá</span>
          </a>
          <button type="button" onclick="openCartModal()" class="relative inline-flex items-center gap-1.5 px-2.5 py-2 rounded-lg bg-[#0f4c81] hover:bg-[#09355c] text-white text-xs font-semibold transition">
            <i class="fa-solid fa-cart-shopping"></i>
            <span class="hidden xl:inline">Giỏ hàng</span>
            <span id="cartCountBadge" class="inline-flex items-center justify-center min-w-[18px] h-[18px] px-1 rounded-full bg-[#d9251d] text-white text-[10px] font-bold">0</span>
          </button>
        </div>

      </div>

      <!-- Thanh tìm kiếm trên điện thoại -->
      <div class="mt-2 md:hidden">
        <form onsubmit="handleMobileSearchSubmit(event)" class="flex items-center border border-[#0f4c81] rounded-lg overflow-hidden bg-white">
          <input 
            id="mobileSearchInput"
            type="text" 
            placeholder="Tìm sản phẩm: bulong, keo, đá mài, dụng cụ..." 
            class="flex-1 px-3 py-2 text-xs text-slate-800 focus:outline-none min-w-0"
          >
          <button type="submit" class="bg-[#0f4c81] text-white px-3.5 py-2 text-xs font-semibold shrink-0">
            <i class="fa-solid fa-magnifying-glass"></i>
          </button>
        </form>
      </div>
    </div>

    <!-- ================= THANH DANH MỤC TRÊN MÁY TÍNH (Chữ nhỏ gọn, viết liền 1 hàng, không xuống dòng tên danh mục) ================= -->
    <nav class="hidden lg:block bg-[#0f4c81] border-t border-white/15">
      <div class="flatsome-container py-1.5">
        <div class="flex flex-wrap items-center justify-start gap-1.5">
          <a href="#danh-muc-san-pham" onclick="filterByCategory('all')" class="desktop-cat-pill bg-[#d9251d] text-white hover:bg-red-700">
            <i class="fa-solid fa-bars-staggered"></i>
            <span>Tất Cả Danh Mục</span>
          </a>
          <a href="#san-pham-thuc-te" onclick="filterByCategory('Bulong – Ốc Vít')" class="desktop-cat-pill text-white hover:bg-white/15">
            <i class="fa-solid fa-screwdriver-wrench text-amber-300"></i>
            <span>Bulong – Ốc Vít</span>
          </a>
          <a href="#san-pham-thuc-te" onclick="filterByCategory('Dầu Mỡ – Hóa Chất')" class="desktop-cat-pill text-white hover:bg-white/15">
            <i class="fa-solid fa-fill-drip text-amber-300"></i>
            <span>Dầu Mỡ – Hóa Chất</span>
          </a>
          <a href="#san-pham-thuc-te" onclick="filterByCategory('Dụng Cụ Cầm Tay')" class="desktop-cat-pill text-white hover:bg-white/15">
            <i class="fa-solid fa-hammer text-amber-300"></i>
            <span>Dụng Cụ Cầm Tay</span>
          </a>
          <a href="#san-pham-thuc-te" onclick="filterByCategory('Dụng Cụ Đồ Mài')" class="desktop-cat-pill text-white hover:bg-white/15">
            <i class="fa-solid fa-compact-disc text-amber-300"></i>
            <span>Dụng Cụ Đồ Mài</span>
          </a>
          <a href="#san-pham-thuc-te" onclick="filterByCategory('Dụng Cụ Tiêu Hao')" class="desktop-cat-pill text-white hover:bg-white/15">
            <i class="fa-solid fa-tape text-amber-300"></i>
            <span>Dụng Cụ Tiêu Hao</span>
          </a>
          <a href="#san-pham-thuc-te" onclick="filterByCategory('Dụng Cụ Phòng Khuôn')" class="desktop-cat-pill text-white hover:bg-white/15">
            <i class="fa-solid fa-cubes text-amber-300"></i>
            <span>Dụng Cụ Phòng Khuôn</span>
          </a>
          <a href="#san-pham-thuc-te" onclick="filterByCategory('Thiết Bị Khí Nén')" class="desktop-cat-pill text-white hover:bg-white/15">
            <i class="fa-solid fa-gauge-high text-amber-300"></i>
            <span>Thiết Bị Khí Nén</span>
          </a>
          <a href="#san-pham-thuc-te" onclick="filterByCategory('Thiết Bị Máy Móc')" class="desktop-cat-pill text-white hover:bg-white/15">
            <i class="fa-solid fa-gears text-amber-300"></i>
            <span>Thiết Bị Máy Móc</span>
          </a>
          <a href="#san-pham-thuc-te" onclick="filterByCategory('Đồ Bảo Hộ Lao Động')" class="desktop-cat-pill text-white hover:bg-white/15">
            <i class="fa-solid fa-helmet-safety text-amber-300"></i>
            <span>Đồ Bảo Hộ Lao Động</span>
          </a>
          <a href="#san-pham-thuc-te" onclick="filterByCategory('Vòng Bi – Nam Châm')" class="desktop-cat-pill text-white hover:bg-white/15">
            <i class="fa-solid fa-ring text-amber-300"></i>
            <span>Vòng Bi – Nam Châm</span>
          </a>
          <a href="#tin-tuc" class="desktop-cat-pill text-amber-200 hover:bg-white/15">
            <i class="fa-regular fa-newspaper"></i>
            <span>Kinh Nghiệm Hay</span>
          </a>
          <a href="#doi-tac" class="desktop-cat-pill text-amber-200 hover:bg-white/15">
            <i class="fa-solid fa-handshake"></i>
            <span>Đối Tác</span>
          </a>
          <a href="#lien-he-map" class="desktop-cat-pill text-amber-200 hover:bg-white/15">
            <i class="fa-solid fa-map-location-dot"></i>
            <span>Bản Đồ & Liên Hệ</span>
          </a>
        </div>
      </div>
    </nav>
  </header>

  <!-- ================= MENU DRAWER TRÊN ĐIỆN THOẠI ================= -->
  <div id="mobileDrawerBackdrop" onclick="toggleMobileDrawer()" class="fixed inset-0 bg-slate-900/60 z-50 hidden"></div>
  <aside id="mobileDrawer" class="fixed top-0 left-0 bottom-0 w-[280px] max-w-[85vw] bg-white z-50 shadow-2xl transform -translate-x-full transition-transform duration-300 flex flex-col">
    <div class="p-3.5 bg-[#0f4c81] text-white flex items-center justify-between">
      <span class="font-bold text-xs uppercase tracking-wider">DANH MỤC SẢN PHẨM</span>
      <button type="button" onclick="toggleMobileDrawer()" class="w-7 h-7 rounded bg-white/10 flex items-center justify-center text-white">
        <i class="fa-solid fa-xmark"></i>
      </button>
    </div>
    <div class="flex-1 overflow-y-auto divide-y divide-slate-100 text-xs font-semibold text-slate-700">
      <a href="#san-pham-thuc-te" onclick="filterByCategory('all'); toggleMobileDrawer();" class="flex items-center justify-between px-4 py-3 hover:bg-slate-50 text-[#0f4c81]">
        <span><i class="fa-solid fa-border-all w-5 text-[#d9251d]"></i>Tất Cả Sản Phẩm</span>
        <i class="fa-solid fa-chevron-right text-[10px] text-slate-400"></i>
      </a>
      <a href="#san-pham-thuc-te" onclick="filterByCategory('Bulong – Ốc Vít'); toggleMobileDrawer();" class="flex items-center justify-between px-4 py-3 hover:bg-slate-50">
        <span><i class="fa-solid fa-screwdriver-wrench w-5 text-[#0f4c81]"></i>Bulong – Ốc Vít</span>
        <i class="fa-solid fa-chevron-right text-[10px] text-slate-400"></i>
      </a>
      <a href="#san-pham-thuc-te" onclick="filterByCategory('Dầu Mỡ – Hóa Chất'); toggleMobileDrawer();" class="flex items-center justify-between px-4 py-3 hover:bg-slate-50">
        <span><i class="fa-solid fa-fill-drip w-5 text-[#0f4c81]"></i>Dầu Mỡ – Hóa Chất – Sơn</span>
        <i class="fa-solid fa-chevron-right text-[10px] text-slate-400"></i>
      </a>
      <a href="#san-pham-thuc-te" onclick="filterByCategory('Dụng Cụ Cầm Tay'); toggleMobileDrawer();" class="flex items-center justify-between px-4 py-3 hover:bg-slate-50">
        <span><i class="fa-solid fa-hammer w-5 text-[#0f4c81]"></i>Dụng Cụ Cầm Tay</span>
        <i class="fa-solid fa-chevron-right text-[10px] text-slate-400"></i>
      </a>
      <a href="#san-pham-thuc-te" onclick="filterByCategory('Dụng Cụ Đồ Mài'); toggleMobileDrawer();" class="flex items-center justify-between px-4 py-3 hover:bg-slate-50">
        <span><i class="fa-solid fa-compact-disc w-5 text-[#0f4c81]"></i>Dụng Cụ Đồ Mài</span>
        <i class="fa-solid fa-chevron-right text-[10px] text-slate-400"></i>
      </a>
      <a href="#san-pham-thuc-te" onclick="filterByCategory('Dụng Cụ Tiêu Hao'); toggleMobileDrawer();" class="flex items-center justify-between px-4 py-3 hover:bg-slate-50">
        <span><i class="fa-solid fa-tape w-5 text-[#0f4c81]"></i>Dụng Cụ Tiêu Hao</span>
        <i class="fa-solid fa-chevron-right text-[10px] text-slate-400"></i>
      </a>
      <a href="#san-pham-thuc-te" onclick="filterByCategory('Dụng Cụ Phòng Khuôn'); toggleMobileDrawer();" class="flex items-center justify-between px-4 py-3 hover:bg-slate-50">
        <span><i class="fa-solid fa-cubes w-5 text-[#0f4c81]"></i>Dụng Cụ Phòng Khuôn</span>
        <i class="fa-solid fa-chevron-right text-[10px] text-slate-400"></i>
      </a>
      <a href="#san-pham-thuc-te" onclick="filterByCategory('Thiết Bị Khí Nén'); toggleMobileDrawer();" class="flex items-center justify-between px-4 py-3 hover:bg-slate-50">
        <span><i class="fa-solid fa-gauge-high w-5 text-[#0f4c81]"></i>Thiết Bị Khí Nén</span>
        <i class="fa-solid fa-chevron-right text-[10px] text-slate-400"></i>
      </a>
      <a href="#san-pham-thuc-te" onclick="filterByCategory('Thiết Bị Máy Móc'); toggleMobileDrawer();" class="flex items-center justify-between px-4 py-3 hover:bg-slate-50">
        <span><i class="fa-solid fa-gears w-5 text-[#0f4c81]"></i>Thiết Bị Máy Móc</span>
        <i class="fa-solid fa-chevron-right text-[10px] text-slate-400"></i>
      </a>
      <a href="#san-pham-thuc-te" onclick="filterByCategory('Đồ Bảo Hộ Lao Động'); toggleMobileDrawer();" class="flex items-center justify-between px-4 py-3 hover:bg-slate-50">
        <span><i class="fa-solid fa-helmet-safety w-5 text-[#0f4c81]"></i>Đồ Bảo Hộ Lao Động</span>
        <i class="fa-solid fa-chevron-right text-[10px] text-slate-400"></i>
      </a>
      <a href="#san-pham-thuc-te" onclick="filterByCategory('Vòng Bi – Nam Châm'); toggleMobileDrawer();" class="flex items-center justify-between px-4 py-3 hover:bg-slate-50">
        <span><i class="fa-solid fa-ring w-5 text-[#0f4c81]"></i>Vòng Bi – Nam Châm</span>
        <i class="fa-solid fa-chevron-right text-[10px] text-slate-400"></i>
      </a>
      <a href="#form-bao-gia" onclick="toggleMobileDrawer()" class="flex items-center justify-between px-4 py-3 bg-amber-50 text-[#d9251d]">
        <span><i class="fa-solid fa-file-signature w-5"></i>Yêu Cầu Báo Giá Nhanh</span>
        <i class="fa-solid fa-chevron-right text-[10px]"></i>
      </a>
    </div>
    <div class="p-3 bg-slate-50 border-t border-slate-200 text-[11px] text-slate-600">
      <div class="font-bold text-[#0f4c81]">NHÀ PHÂN PHỐI TRANG PHỤNG</div>
      <div class="mt-0.5">Đ/c: 338-340 Bùi Thiện Ngộ, Hòa Xuân, Đà Nẵng</div>
      <div class="mt-0.5 font-semibold text-[#d9251d]">SĐT: 0905.576.733 - 0935.249.951</div>
    </div>
  </aside>

  <!-- ================= MAIN CONTENT ================= -->
  <main id="top" class="flex-1">

    <!-- ================= 2 ẢNH BANNER TỰ TRƯỢT CHUYÊN NGHIỆP KÍCH THƯỚC BẰNG NHAU ================= -->
    <!-- Thiết kế riêng Banner Máy Tính (md:block) và Banner Điện Thoại (md:hidden) để chữ gọn nhỏ nằm trọn trong khung, không tràn viền -->
    <section class="flatsome-container mt-3">
      <div class="relative rounded-xl overflow-hidden shadow-md bg-[#09355c]">

        <!-- ===== PHIÊN BẢN BANNER MÁY TÍNH (Desktop >= 768px): 2 Slide kích thước bằng nhau (h-[340px] lg:h-[370px]) ===== -->
        <div class="hidden md:block relative w-full h-[340px] lg:h-[370px]">
          
          <!-- Desktop Slide 1 -->
          <div data-desktop-slide="0" class="desktop-slide absolute inset-0 transition-opacity duration-700 opacity-100 z-10 bg-gradient-to-r from-[#072948] via-[#0f4c81] to-[#165b96] flex items-center">
            <div class="w-full h-full grid grid-cols-12 items-center px-10 lg:px-14 gap-6">
              <div class="col-span-7 text-white space-y-3 pr-4">
                <div class="inline-flex items-center gap-2 px-3 py-1 rounded-full bg-amber-400/20 border border-amber-300/40 text-amber-300 text-xs font-bold uppercase tracking-wider">
                  <i class="fa-solid fa-certificate"></i> NHÀ PHÂN PHỐI TRANG PHỤNG - TRANGPHUNG.COM
                </div>
                <h1 class="text-xl lg:text-2xl xl:text-3xl font-extrabold leading-snug text-white">
                  TỔNG KHO VẬT TƯ KIM KHÍ, BULONG ỐC VÍT & DỤNG CỤ CÔNG NGHIỆP ĐÀ NẴNG
                </h1>
                <p class="text-xs lg:text-sm text-slate-200 leading-relaxed max-w-xl">
                  Chuyên phân phối sỉ & lẻ Bulong Inox 304, Đá cắt - Đá mài, Dụng cụ cầm tay, Keo Silicon - Keo công nghiệp, Sơn PU/NC/Mạ kẽm, Thiết bị khí nén chính hãng giá gốc.
                </p>
                <div class="pt-1 flex flex-wrap items-center gap-3 text-xs">
                  <a href="#san-pham-thuc-te" class="px-4 py-2.5 rounded-lg bg-[#d9251d] hover:bg-red-700 text-white font-bold shadow transition">
                    <i class="fa-solid fa-box-open mr-1.5"></i>XEM SẢN PHẨM
                  </a>
                  <a href="#form-bao-gia" class="px-4 py-2.5 rounded-lg bg-white text-[#0f4c81] hover:bg-slate-100 font-bold shadow transition">
                    <i class="fa-solid fa-paper-plane mr-1.5"></i>NHẬN BÁO GIÁ SỈ
                  </a>
                  <span class="text-amber-300 font-semibold"><i class="fa-solid fa-phone-volume mr-1"></i>0905.576.733 - 0935.249.951</span>
                </div>
              </div>
              <div class="col-span-5 h-full py-5 flex items-center justify-center">
                <div class="grid grid-cols-2 gap-2.5 w-full max-w-[360px] bg-white/10 p-3 rounded-xl border border-white/20 backdrop-blur-xs">
                  <div class="bg-white rounded-lg p-1.5 h-32 flex items-center justify-center overflow-hidden">
                    <img src="https://drive.google.com/thumbnail?id=1ODt-OrWa3gCTXJhnexmv9aN-EbolZy4B&sz=w600" data-drive-id="1ODt-OrWa3gCTXJhnexmv9aN-EbolZy4B" data-label="Bulong" onerror="handleDriveImgError(this)" alt="Sản phẩm thực tế 1" class="max-h-full max-w-full object-contain">
                  </div>
                  <div class="bg-white rounded-lg p-1.5 h-32 flex items-center justify-center overflow-hidden">
                    <img src="https://drive.google.com/thumbnail?id=1nJELgF4XaQfTQSlczJSWLZQQ166reIbe&sz=w600" data-drive-id="1nJELgF4XaQfTQSlczJSWLZQQ166reIbe" data-label="Hoa Chat" onerror="handleDriveImgError(this)" alt="Sản phẩm thực tế 2" class="max-h-full max-w-full object-contain">
                  </div>
                  <div class="bg-white rounded-lg p-1.5 h-32 flex items-center justify-center overflow-hidden">
                    <img src="https://drive.google.com/thumbnail?id=1lUsNiRG1UGUWjThuQM7uKKjYypMKI7mw&sz=w600" data-drive-id="1lUsNiRG1UGUWjThuQM7uKKjYypMKI7mw" data-label="Do Mai" onerror="handleDriveImgError(this)" alt="Sản phẩm thực tế 3" class="max-h-full max-w-full object-contain">
                  </div>
                  <div class="bg-white rounded-lg p-1.5 h-32 flex items-center justify-center overflow-hidden">
                    <img src="https://drive.google.com/thumbnail?id=1apNof0fiboG58EAA566Ei9ww1GoWJuUo&sz=w600" data-drive-id="1apNof0fiboG58EAA566Ei9ww1GoWJuUo" data-label="Dung Cu" onerror="handleDriveImgError(this)" alt="Sản phẩm thực tế 4" class="max-h-full max-w-full object-contain">
                  </div>
                </div>
              </div>
            </div>
          </div>

          <!-- Desktop Slide 2 (Kích thước bằng đúng Slide 1) -->
          <div data-desktop-slide="1" class="desktop-slide absolute inset-0 transition-opacity duration-700 opacity-0 z-0 bg-gradient-to-r from-[#112233] via-[#0f4c81] to-[#09355c] flex items-center">
            <div class="w-full h-full grid grid-cols-12 items-center px-10 lg:px-14 gap-6">
              <div class="col-span-7 text-white space-y-3 pr-4">
                <div class="inline-flex items-center gap-2 px-3 py-1 rounded-full bg-red-500/20 border border-red-400/40 text-amber-300 text-xs font-bold uppercase tracking-wider">
                  <i class="fa-solid fa-truck-fast"></i> GIAO HÀNG NHANH TẠI ĐÀ NẴNG & MIỀN TRUNG
                </div>
                <h2 class="text-xl lg:text-2xl xl:text-3xl font-extrabold leading-snug text-white">
                  ĐỐI TÁC CUNG ỨNG KIM KHÍ – HÓA CHẤT – SƠN – KEO DÁN – THIẾT BỊ CƠ KHÍ UY TÍN
                </h2>
                <p class="text-xs lg:text-sm text-slate-200 leading-relaxed max-w-xl">
                  Địa chỉ: <strong>338-340 Bùi Thiện Ngộ, Phường Hòa Xuân, TP. Đà Nẵng</strong>. Nguồn hàng sẵn kho số lượng lớn, chiết khấu cao cho đại lý, nhà thầu xây dựng và xưởng sản xuất.
                </p>
                <div class="pt-1 flex flex-wrap items-center gap-3 text-xs">
                  <a href="#gioi-thieu" class="px-4 py-2.5 rounded-lg bg-amber-500 hover:bg-amber-600 text-slate-950 font-bold shadow transition">
                    <i class="fa-solid fa-building mr-1.5"></i>VỀ TRANG PHỤNG
                  </a>
                  <a href="#lien-he-map" class="px-4 py-2.5 rounded-lg bg-white/15 hover:bg-white/25 text-white border border-white/30 font-bold transition">
                    <i class="fa-solid fa-location-dot mr-1.5"></i>XEM BẢN ĐỒ CHỈ ĐƯỜNG
                  </a>
                </div>
              </div>
              <div class="col-span-5 h-full py-5 flex items-center justify-center">
                <div class="w-full max-w-[360px] h-[275px] bg-white/10 p-2.5 rounded-xl border border-white/20 overflow-hidden flex items-center justify-center">
                  <img 
                    src="https://drive.google.com/thumbnail?id=1m6NnkLWgwaopsKblzRvWbB9bdqh2Nsae&sz=w1000" 
                    data-drive-id="1m6NnkLWgwaopsKblzRvWbB9bdqh2Nsae"
                    data-label="Nha Phan Phoi Trang Phung"
                    onerror="handleDriveImgError(this)"
                    alt="Ảnh Công Ty Nhà Phân Phối Trang Phụng" 
                    class="w-full h-full object-cover rounded-lg"
                  >
                </div>
              </div>
            </div>
          </div>

        </div>

        <!-- ===== PHIÊN BẢN BANNER ĐIỆN THOẠI (Mobile < 768px): Thiết kế riêng cho màn hình nhỏ, chữ nhỏ gọn nằm trọn bên trong, không tràn viền ===== -->
        <div class="block md:hidden relative w-full h-[230px] overflow-hidden">
          
          <!-- Mobile Slide 1 -->
          <div data-mobile-slide="0" class="mobile-slide absolute inset-0 transition-opacity duration-700 opacity-100 z-10 bg-gradient-to-br from-[#072948] via-[#0f4c81] to-[#155e95] p-3 flex flex-col justify-between overflow-hidden">
            <div class="flex items-center justify-between gap-2 min-w-0">
              <span class="px-2 py-0.5 rounded bg-amber-400/20 border border-amber-300/40 text-amber-300 !text-[10px] font-bold uppercase truncate">
                TRANGPHUNG.COM
              </span>
              <span class="!text-[10px] text-white/90 font-semibold shrink-0">0905.576.733</span>
            </div>

            <div class="grid grid-cols-12 gap-2 items-center my-auto py-1 min-w-0">
              <div class="col-span-8 space-y-1 pr-1 min-w-0">
                <h2 class="!text-[12.5px] !leading-[1.32] font-extrabold text-white break-words">
                  NHÀ PHÂN PHỐI TRANG PHỤNG – KIM KHÍ & VẬT TƯ CÔNG NGHIỆP
                </h2>
                <p class="!text-[10.5px] !leading-[1.35] text-slate-200 break-words">
                  Chuyên Bulong Ốc Vít, Đá Mài, Dụng Cụ Cầm Tay, Keo Silicon, Sơn PU/NC, Khí Nén chính hãng tại Đà Nẵng.
                </p>
              </div>
              <div class="col-span-4 bg-white rounded-lg p-1.5 h-20 flex items-center justify-center overflow-hidden shadow shrink-0">
                <img src="https://drive.google.com/thumbnail?id=1ODt-OrWa3gCTXJhnexmv9aN-EbolZy4B&sz=w400" data-drive-id="1ODt-OrWa3gCTXJhnexmv9aN-EbolZy4B" data-label="SP" onerror="handleDriveImgError(this)" alt="Sản phẩm Trang Phụng" class="max-h-full max-w-full object-contain">
              </div>
            </div>

            <div class="flex items-center justify-between gap-2 pt-1.5 border-t border-white/15 !text-[10px] text-amber-200 min-w-0">
              <span class="truncate"><i class="fa-solid fa-location-dot mr-1"></i>338-340 Bùi Thiện Ngộ, Hòa Xuân, ĐN</span>
              <a href="#san-pham-thuc-te" class="px-2.5 py-1 rounded bg-[#d9251d] text-white font-bold shrink-0 !text-[10px]">Xem ngay</a>
            </div>
          </div>

          <!-- Mobile Slide 2 (Kích thước bằng đúng Mobile Slide 1: h-[230px]) -->
          <div data-mobile-slide="1" class="mobile-slide absolute inset-0 transition-opacity duration-700 opacity-0 z-0 bg-gradient-to-br from-[#0f172a] via-[#0f4c81] to-[#09355c] p-3 flex flex-col justify-between overflow-hidden">
            <div class="flex items-center justify-between gap-2 min-w-0">
              <span class="px-2 py-0.5 rounded bg-red-500/25 border border-red-300/40 text-amber-300 !text-[10px] font-bold uppercase truncate">
                CHIẾT KHẤU ĐẠI LÝ TỐT NHẤT
              </span>
              <span class="!text-[10px] text-white/90 font-semibold shrink-0">0935.249.951</span>
            </div>

            <div class="grid grid-cols-12 gap-2 items-center my-auto py-1 min-w-0">
              <div class="col-span-8 space-y-1 pr-1 min-w-0">
                <h2 class="!text-[12.5px] !leading-[1.32] font-extrabold text-white break-words">
                  CUNG ỨNG SỈ & LẺ VẬT TƯ CƠ KHÍ, HÓA CHẤT, KEO DÁN, SƠN MẠ KẼM
                </h2>
                <p class="!text-[10.5px] !leading-[1.35] text-slate-200 break-words">
                  Sẵn kho số lượng lớn cho xưởng cơ khí, nhà máy & công trình. Giao nhanh tận nơi tại TP. Đà Nẵng.
                </p>
              </div>
              <div class="col-span-4 bg-white rounded-lg p-1 h-20 flex items-center justify-center overflow-hidden shadow shrink-0">
                <img src="https://drive.google.com/thumbnail?id=1m6NnkLWgwaopsKblzRvWbB9bdqh2Nsae&sz=w400" data-drive-id="1m6NnkLWgwaopsKblzRvWbB9bdqh2Nsae" data-label="Cong Ty" onerror="handleDriveImgError(this)" alt="Nhà Phân Phối Trang Phụng" class="w-full h-full object-cover rounded">
              </div>
            </div>

            <div class="flex items-center justify-between gap-2 pt-1.5 border-t border-white/15 !text-[10px] text-amber-200 min-w-0">
              <span class="truncate"><i class="fa-solid fa-phone mr-1"></i>0905.576.733 - 0935.249.951</span>
              <a href="#form-bao-gia" class="px-2.5 py-1 rounded bg-amber-500 text-slate-950 font-bold shrink-0 !text-[10px]">Báo giá</a>
            </div>
          </div>

        </div>

        <!-- Nút điều hướng Slide & Chấm chỉ báo -->
        <button type="button" onclick="prevBannerSlide()" aria-label="Slide trước" class=" hidden sm:flex absolute left-2.5 top-1/2 -translate-y-1/2 z-20 w-8 h-8 rounded-full bg-black/35 hover:bg-black/60 text-white items-center justify-center transition">
          <i class="fa-solid fa-chevron-left text-xs"></i>
        </button>
        <button type="button" onclick="nextBannerSlide()" aria-label="Slide tiếp" class="hidden sm:flex absolute right-2.5 top-1/2 -translate-y-1/2 z-20 w-8 h-8 rounded-full bg-black/35 hover:bg-black/60 text-white items-center justify-center transition">
          <i class="fa-solid fa-chevron-right text-xs"></i>
        </button>
        <div class="absolute bottom-2 left-1/2 -translate-x-1/2 z-20 flex items-center gap-2">
          <button type="button" onclick="goToBannerSlide(0)" id="bannerDot0" aria-label="Slide 1" class="w-5 h-1.5 rounded-full bg-amber-400 transition-all"></button>
          <button type="button" onclick="goToBannerSlide(1)" id="bannerDot1" aria-label="Slide 2" class="w-2 h-1.5 rounded-full bg-white/50 transition-all"></button>
        </div>

      </div>
    </section>

    <!-- ================= DANH MỤC SẢN PHẨM TRANG CHỦ (Tối ưu cho cả Máy Tính & Điện Thoại, chữ nhỏ gọn, không xuống dòng tên danh mục) ================= -->
    <section id="danh-muc-san-pham" class="flatsome-container mt-5">
      <div class="bg-white rounded-xl shadow-xs border border-slate-200 p-3 sm:p-4">
        <div class="flex items-center justify-between border-b border-slate-200 pb-2.5 mb-3">
          <div class="flex items-center gap-2">
            <span class="w-1.5 h-5 rounded-full bg-[#d9251d]"></span>
            <h2 class="text-sm sm:text-base font-extrabold text-[#0f4c81] uppercase tracking-tight">DANH MỤC SẢN PHẨM</h2>
          </div>
          <span class="text-[11px] text-slate-500 hidden sm:inline">Chọn danh mục để lọc nhanh sản phẩm</span>
        </div>

        <!-- Grid Danh Mục: 2 cột trên điện thoại, 5 cột trên máy tính, chữ nhỏ gọn trên 1 hàng -->
        <div class="grid grid-cols-2 sm:grid-cols-3 md:grid-cols-5 gap-2 sm:gap-2.5">
          
          <button type="button" onclick="filterByCategory('Bulong – Ốc Vít')" class="cat-card group flex items-center gap-2.5 p-2.5 rounded-lg border border-slate-200 hover:border-[#0f4c81] hover:bg-blue-50/50 transition text-left">
            <div class="w-9 h-9 rounded-lg bg-[#0f4c81]/10 text-[#0f4c81] group-hover:bg-[#0f4c81] group-hover:text-white flex items-center justify-center shrink-0 transition">
              <i class="fa-solid fa-screwdriver-wrench text-sm"></i>
            </div>
            <div class="min-w-0">
              <div class="text-[11px] sm:text-xs font-bold text-slate-800 group-hover:text-[#0f4c81] whitespace-nowrap overflow-hidden text-ellipsis">Bulong – Ốc Vít</div>
              <div class="text-[10px] text-slate-500 whitespace-nowrap overflow-hidden text-ellipsis">Inox 304, Thép đen, Titan</div>
            </div>
          </button>

          <button type="button" onclick="filterByCategory('Dầu Mỡ – Hóa Chất')" class="cat-card group flex items-center gap-2.5 p-2.5 rounded-lg border border-slate-200 hover:border-[#0f4c81] hover:bg-blue-50/50 transition text-left">
            <div class="w-9 h-9 rounded-lg bg-[#0f4c81]/10 text-[#0f4c81] group-hover:bg-[#0f4c81] group-hover:text-white flex items-center justify-center shrink-0 transition">
              <i class="fa-solid fa-fill-drip text-sm"></i>
            </div>
            <div class="min-w-0">
              <div class="text-[11px] sm:text-xs font-bold text-slate-800 group-hover:text-[#0f4c81] whitespace-nowrap overflow-hidden text-ellipsis">Dầu Mỡ – Hóa Chất</div>
              <div class="text-[10px] text-slate-500 whitespace-nowrap overflow-hidden text-ellipsis">Keo dán, Silicon, Sơn PU</div>
            </div>
          </button>

          <button type="button" onclick="filterByCategory('Dụng Cụ Cầm Tay')" class="cat-card group flex items-center gap-2.5 p-2.5 rounded-lg border border-slate-200 hover:border-[#0f4c81] hover:bg-blue-50/50 transition text-left">
            <div class="w-9 h-9 rounded-lg bg-[#0f4c81]/10 text-[#0f4c81] group-hover:bg-[#0f4c81] group-hover:text-white flex items-center justify-center shrink-0 transition">
              <i class="fa-solid fa-hammer text-sm"></i>
            </div>
            <div class="min-w-0">
              <div class="text-[11px] sm:text-xs font-bold text-slate-800 group-hover:text-[#0f4c81] whitespace-nowrap overflow-hidden text-ellipsis">Dụng Cụ Cầm Tay</div>
              <div class="text-[10px] text-slate-500 whitespace-nowrap overflow-hidden text-ellipsis">Kìm, Cờ lê, Đồ nghề</div>
            </div>
          </button>

          <button type="button" onclick="filterByCategory('Dụng Cụ Đồ Mài')" class="cat-card group flex items-center gap-2.5 p-2.5 rounded-lg border border-slate-200 hover:border-[#0f4c81] hover:bg-blue-50/50 transition text-left">
            <div class="w-9 h-9 rounded-lg bg-[#0f4c81]/10 text-[#0f4c81] group-hover:bg-[#0f4c81] group-hover:text-white flex items-center justify-center shrink-0 transition">
              <i class="fa-solid fa-compact-disc text-sm"></i>
            </div>
            <div class="min-w-0">
              <div class="text-[11px] sm:text-xs font-bold text-slate-800 group-hover:text-[#0f4c81] whitespace-nowrap overflow-hidden text-ellipsis">Dụng Cụ Đồ Mài</div>
              <div class="text-[10px] text-slate-500 whitespace-nowrap overflow-hidden text-ellipsis">Đá mài, Đá cắt, Nhám</div>
            </div>
          </button>

          <button type="button" onclick="filterByCategory('Dụng Cụ Tiêu Hao')" class="cat-card group flex items-center gap-2.5 p-2.5 rounded-lg border border-slate-200 hover:border-[#0f4c81] hover:bg-blue-50/50 transition text-left">
            <div class="w-9 h-9 rounded-lg bg-[#0f4c81]/10 text-[#0f4c81] group-hover:bg-[#0f4c81] group-hover:text-white flex items-center justify-center shrink-0 transition">
              <i class="fa-solid fa-tape text-sm"></i>
            </div>
            <div class="min-w-0">
              <div class="text-[11px] sm:text-xs font-bold text-slate-800 group-hover:text-[#0f4c81] whitespace-nowrap overflow-hidden text-ellipsis">Dụng Cụ Tiêu Hao</div>
              <div class="text-[10px] text-slate-500 whitespace-nowrap overflow-hidden text-ellipsis">Băng keo nhiệt, Lõi lọc</div>
            </div>
          </button>

          <button type="button" onclick="filterByCategory('Dụng Cụ Phòng Khuôn')" class="cat-card group flex items-center gap-2.5 p-2.5 rounded-lg border border-slate-200 hover:border-[#0f4c81] hover:bg-blue-50/50 transition text-left">
            <div class="w-9 h-9 rounded-lg bg-[#0f4c81]/10 text-[#0f4c81] group-hover:bg-[#0f4c81] group-hover:text-white flex items-center justify-center shrink-0 transition">
              <i class="fa-solid fa-cubes text-sm"></i>
            </div>
            <div class="min-w-0">
              <div class="text-[11px] sm:text-xs font-bold text-slate-800 group-hover:text-[#0f4c81] whitespace-nowrap overflow-hidden text-ellipsis">Dụng Cụ Phòng Khuôn</div>
              <div class="text-[10px] text-slate-500 whitespace-nowrap overflow-hidden text-ellipsis">Chốt định vị, Áo chốt</div>
            </div>
          </button>

          <button type="button" onclick="filterByCategory('Thiết Bị Khí Nén')" class="cat-card group flex items-center gap-2.5 p-2.5 rounded-lg border border-slate-200 hover:border-[#0f4c81] hover:bg-blue-50/50 transition text-left">
            <div class="w-9 h-9 rounded-lg bg-[#0f4c81]/10 text-[#0f4c81] group-hover:bg-[#0f4c81] group-hover:text-white flex items-center justify-center shrink-0 transition">
              <i class="fa-solid fa-gauge-high text-sm"></i>
            </div>
            <div class="min-w-0">
              <div class="text-[11px] sm:text-xs font-bold text-slate-800 group-hover:text-[#0f4c81] whitespace-nowrap overflow-hidden text-ellipsis">Thiết Bị Khí Nén</div>
              <div class="text-[10px] text-slate-500 whitespace-nowrap overflow-hidden text-ellipsis">Dây khí, Nối khí, Xi lanh</div>
            </div>
          </button>

          <button type="button" onclick="filterByCategory('Thiết Bị Máy Móc')" class="cat-card group flex items-center gap-2.5 p-2.5 rounded-lg border border-slate-200 hover:border-[#0f4c81] hover:bg-blue-50/50 transition text-left">
            <div class="w-9 h-9 rounded-lg bg-[#0f4c81]/10 text-[#0f4c81] group-hover:bg-[#0f4c81] group-hover:text-white flex items-center justify-center shrink-0 transition">
              <i class="fa-solid fa-gears text-sm"></i>
            </div>
            <div class="min-w-0">
              <div class="text-[11px] sm:text-xs font-bold text-slate-800 group-hover:text-[#0f4c81] whitespace-nowrap overflow-hidden text-ellipsis">Thiết Bị Máy Móc</div>
              <div class="text-[10px] text-slate-500 whitespace-nowrap overflow-hidden text-ellipsis">Thiết bị điện, Cân, Máy</div>
            </div>
          </button>

          <button type="button" onclick="filterByCategory('Đồ Bảo Hộ Lao Động')" class="cat-card group flex items-center gap-2.5 p-2.5 rounded-lg border border-slate-200 hover:border-[#0f4c81] hover:bg-blue-50/50 transition text-left">
            <div class="w-9 h-9 rounded-lg bg-[#0f4c81]/10 text-[#0f4c81] group-hover:bg-[#0f4c81] group-hover:text-white flex items-center justify-center shrink-0 transition">
              <i class="fa-solid fa-helmet-safety text-sm"></i>
            </div>
            <div class="min-w-0">
              <div class="text-[11px] sm:text-xs font-bold text-slate-800 group-hover:text-[#0f4c81] whitespace-nowrap overflow-hidden text-ellipsis">Đồ Bảo Hộ Lao Động</div>
              <div class="text-[10px] text-slate-500 whitespace-nowrap overflow-hidden text-ellipsis">Găng tay, Kính, Giày</div>
            </div>
          </button>

          <button type="button" onclick="filterByCategory('Vòng Bi – Nam Châm')" class="cat-card group flex items-center gap-2.5 p-2.5 rounded-lg border border-slate-200 hover:border-[#0f4c81] hover:bg-blue-50/50 transition text-left">
            <div class="w-9 h-9 rounded-lg bg-[#0f4c81]/10 text-[#0f4c81] group-hover:bg-[#0f4c81] group-hover:text-white flex items-center justify-center shrink-0 transition">
              <i class="fa-solid fa-ring text-sm"></i>
            </div>
            <div class="min-w-0">
              <div class="text-[11px] sm:text-xs font-bold text-slate-800 group-hover:text-[#0f4c81] whitespace-nowrap overflow-hidden text-ellipsis">Vòng Bi – Nam Châm</div>
              <div class="text-[10px] text-slate-500 whitespace-nowrap overflow-hidden text-ellipsis">Vòng bi, Lò xo, Thủy lực</div>
            </div>
          </button>

        </div>
      </div>
    </section>

    <!-- ================= 14 SẢN PHẨM THỰC TẾ TỪ FILE GOOGLE DRIVE (Chia 2 cột trên điện thoại, 4-5 cột trên máy tính, % giảm giá góc trên bên trái chuẩn Flatsome, tên không bị cắt chữ) ================= -->
    <section id="san-pham-thuc-te" class="flatsome-container mt-5">
      <div class="bg-white rounded-xl shadow-xs border border-slate-200 p-3 sm:p-4">
        
        <!-- Tiêu đề khối + Bộ lọc nhanh -->
        <div class="flex flex-col md:flex-row md:items-center justify-between gap-2 border-b border-slate-200 pb-3 mb-3.5">
          <div class="flex items-center justify-between sm:justify-start gap-2 min-w-0">
            <div class="flex items-center gap-2 min-w-0">
              <span class="w-1.5 h-5 rounded-full bg-[#0f4c81] shrink-0"></span>
              <h2 class="text-xs sm:text-base font-extrabold text-[#0f4c81] uppercase tracking-tight leading-snug">
                SẢN PHẨM THỰC TẾ TẠI NHÀ PHÂN PHỐI TRANG PHỤNG
              </h2>
            </div>
            <span id="activeCategoryLabel" class="text-[11px] font-semibold px-2 py-0.5 rounded bg-blue-50 text-[#0f4c81] border border-blue-200 shrink-0 whitespace-nowrap">Tất cả (14)</span>
          </div>

          <div class="flex flex-wrap items-center gap-1.5">
            <button type="button" onclick="filterByCategory('all')" class="filter-tab px-2.5 py-1 rounded text-[11px] font-semibold bg-[#0f4c81] text-white" data-cat="all">Tất cả</button>
            <button type="button" onclick="filterByCategory('Bulong – Ốc Vít')" class="filter-tab px-2.5 py-1 rounded text-[11px] font-semibold bg-slate-100 text-slate-700 hover:bg-slate-200" data-cat="Bulong – Ốc Vít">Bulong – Ốc Vít</button>
            <button type="button" onclick="filterByCategory('Dầu Mỡ – Hóa Chất')" class="filter-tab px-2.5 py-1 rounded text-[11px] font-semibold bg-slate-100 text-slate-700 hover:bg-slate-200" data-cat="Dầu Mỡ – Hóa Chất">Dầu Mỡ – Hóa Chất</button>
            <button type="button" onclick="filterByCategory('Dụng Cụ Cầm Tay')" class="filter-tab px-2.5 py-1 rounded text-[11px] font-semibold bg-slate-100 text-slate-700 hover:bg-slate-200" data-cat="Dụng Cụ Cầm Tay">Dụng Cụ Cầm Tay</button>
            <button type="button" onclick="filterByCategory('Dụng Cụ Đồ Mài')" class="filter-tab px-2.5 py-1 rounded text-[11px] font-semibold bg-slate-100 text-slate-700 hover:bg-slate-200" data-cat="Dụng Cụ Đồ Mài">Dụng Cụ Đồ Mài</button>
            <button type="button" onclick="filterByCategory('Thiết Bị Khí Nén')" class="filter-tab px-2.5 py-1 rounded text-[11px] font-semibold bg-slate-100 text-slate-700 hover:bg-slate-200" data-cat="Thiết Bị Khí Nén">Thiết Bị Khí Nén</button>
          </div>
        </div>

        <!-- Lưới sản phẩm: Điện thoại 2 cột (grid-cols-2), Máy tính 4-5 cột -->
        <div id="realProductsGrid" class="grid grid-cols-2 sm:grid-cols-3 md:grid-cols-4 lg:grid-cols-5 gap-2.5 sm:gap-3.5">
          <!-- Được render tự động bằng JS từ 14 link ảnh thực tế Google Drive -->
        </div>

      </div>
    </section>

    <!-- ================= CÁC KHỐI DANH MỤC SẢN PHẨM GIỐNG WEB MẪU KIMKHITHANHTHANG.COM ================= -->
    
    <!-- KHỐI 1: BULONG – ỐC VÍT & DỤNG CỤ PHÒNG KHUÔN -->
    <section class="flatsome-container mt-5">
      <div class="bg-white rounded-xl shadow-xs border border-slate-200 p-3 sm:p-4">
        <div class="flex flex-wrap items-center justify-between gap-2 border-b-2 border-[#0f4c81] pb-2.5 mb-3.5">
          <div class="flex items-center gap-2">
            <span class="bg-[#0f4c81] text-white px-3 py-1 rounded-t-md text-xs sm:text-sm font-extrabold uppercase">
              BULONG – ỐC VÍT & DỤNG CỤ PHÒNG KHUÔN
            </span>
          </div>
          <div class="flex flex-wrap items-center gap-2 text-[11px] font-semibold text-slate-600">
            <button type="button" onclick="filterByCategory('Bulong – Ốc Vít')" class="hover:text-[#0f4c81]">Bulong Inox 304</button>
            <span>•</span>
            <button type="button" onclick="filterByCategory('Bulong – Ốc Vít')" class="hover:text-[#0f4c81]">Bulong Thép Đen</button>
            <span>•</span>
            <button type="button" onclick="filterByCategory('Bulong – Ốc Vít')" class="hover:text-[#0f4c81]">Bulong Titan</button>
            <span>•</span>
            <button type="button" onclick="filterByCategory('Dụng Cụ Phòng Khuôn')" class="hover:text-[#0f4c81]">Chốt Định Vị Inox 304</button>
          </div>
        </div>

        <div id="sectionGridBulong" class="grid grid-cols-2 sm:grid-cols-3 md:grid-cols-4 lg:grid-cols-5 gap-2.5 sm:gap-3.5"></div>
      </div>
    </section>

    <!-- KHỐI 2: DẦU MỠ – HÓA CHẤT – KEO DÁN – SƠN CÔNG NGHIỆP -->
    <section class="flatsome-container mt-5">
      <div class="bg-white rounded-xl shadow-xs border border-slate-200 p-3 sm:p-4">
        <div class="flex flex-wrap items-center justify-between gap-2 border-b-2 border-[#0f4c81] pb-2.5 mb-3.5">
          <div class="flex items-center gap-2">
            <span class="bg-[#0f4c81] text-white px-3 py-1 rounded-t-md text-xs sm:text-sm font-extrabold uppercase">
              DẦU MỠ – HÓA CHẤT – KEO DÁN & SƠN PU/NC
            </span>
          </div>
          <div class="flex flex-wrap items-center gap-2 text-[11px] font-semibold text-slate-600">
            <button type="button" onclick="filterByCategory('Dầu Mỡ – Hóa Chất')" class="hover:text-[#0f4c81]">Keo Silicon & Keo Dán</button>
            <span>•</span>
            <button type="button" onclick="filterByCategory('Dầu Mỡ – Hóa Chất')" class="hover:text-[#0f4c81]">Mỡ Bôi Trơn MOLYKOTE</button>
            <span>•</span>
            <button type="button" onclick="filterByCategory('Dầu Mỡ – Hóa Chất')" class="hover:text-[#0f4c81]">Sơn PU / NC / Mạ Kẽm</button>
          </div>
        </div>

        <div id="sectionGridHoaChat" class="grid grid-cols-2 sm:grid-cols-3 md:grid-cols-4 lg:grid-cols-5 gap-2.5 sm:gap-3.5"></div>
      </div>
    </section>

    <!-- KHỐI 3: DỤNG CỤ CẦM TAY – DỤNG CỤ ĐỒ MÀI – DỤNG CỤ TIÊU HAO -->
    <section class="flatsome-container mt-5">
      <div class="bg-white rounded-xl shadow-xs border border-slate-200 p-3 sm:p-4">
        <div class="flex flex-wrap items-center justify-between gap-2 border-b-2 border-[#0f4c81] pb-2.5 mb-3.5">
          <div class="flex items-center gap-2">
            <span class="bg-[#0f4c81] text-white px-3 py-1 rounded-t-md text-xs sm:text-sm font-extrabold uppercase">
              DỤNG CỤ CẦM TAY – ĐỒ MÀI & VẬT TƯ TIÊU HAO
            </span>
          </div>
          <div class="flex flex-wrap items-center gap-2 text-[11px] font-semibold text-slate-600">
            <button type="button" onclick="filterByCategory('Dụng Cụ Cầm Tay')" class="hover:text-[#0f4c81]">Dụng Cụ Cầm Tay</button>
            <span>•</span>
            <button type="button" onclick="filterByCategory('Dụng Cụ Đồ Mài')" class="hover:text-[#0f4c81]">Đá Mài – Đá Cắt – Bàn Chải</button>
            <span>•</span>
            <button type="button" onclick="filterByCategory('Dụng Cụ Tiêu Hao')" class="hover:text-[#0f4c81]">Băng Keo Chịu Nhiệt – Lõi Lọc</button>
          </div>
        </div>

        <div id="sectionGridDungCu" class="grid grid-cols-2 sm:grid-cols-3 md:grid-cols-4 lg:grid-cols-5 gap-2.5 sm:gap-3.5"></div>
      </div>
    </section>

    <!-- KHỐI 4: THIẾT BỊ KHÍ NÉN – MÁY MÓC – BẢO HỘ LAO ĐỘNG -->
    <section class="flatsome-container mt-5">
      <div class="bg-white rounded-xl shadow-xs border border-slate-200 p-3 sm:p-4">
        <div class="flex flex-wrap items-center justify-between gap-2 border-b-2 border-[#0f4c81] pb-2.5 mb-3.5">
          <div class="flex items-center gap-2">
            <span class="bg-[#0f4c81] text-white px-3 py-1 rounded-t-md text-xs sm:text-sm font-extrabold uppercase">
              THIẾT BỊ KHÍ NÉN – MÁY MÓC & ĐỒ BẢO HỘ
            </span>
          </div>
          <div class="flex flex-wrap items-center gap-2 text-[11px] font-semibold text-slate-600">
            <button type="button" onclick="filterByCategory('Thiết Bị Khí Nén')" class="hover:text-[#0f4c81]">Dây Khí – Nối Khí SMC</button>
            <span>•</span>
            <button type="button" onclick="filterByCategory('Thiết Bị Máy Móc')" class="hover:text-[#0f4c81]">Thiết Bị Điện – Cơ Khí</button>
            <span>•</span>
            <button type="button" onclick="filterByCategory('Đồ Bảo Hộ Lao Động')" class="hover:text-[#0f4c81]">Bảo Hộ Lao Động</button>
          </div>
        </div>

        <div id="sectionGridThietBi" class="grid grid-cols-2 sm:grid-cols-3 md:grid-cols-4 lg:grid-cols-5 gap-2.5 sm:gap-3.5"></div>
      </div>
    </section>

    <!-- ================= GIỚI THIỆU CÔNG TY & FORM YÊU CẦU BÁO GIÁ TRANG CHỦ ================= -->
    <section id="gioi-thieu" class="flatsome-container mt-5">
      <div class="grid grid-cols-1 lg:grid-cols-12 gap-4">
        
        <!-- Cột trái: Hình ảnh thực tế Công ty & Giới thiệu Nhà Phân Phối Trang Phụng -->
        <div class="lg:col-span-6 bg-white rounded-xl shadow-xs border border-slate-200 p-4 flex flex-col justify-between">
          <div>
            <div class="flex items-center gap-2 border-b border-slate-200 pb-2.5 mb-3">
              <span class="w-1.5 h-5 rounded-full bg-[#0f4c81]"></span>
              <h2 class="text-sm sm:text-base font-extrabold text-[#0f4c81] uppercase">
                VỀ NHÀ PHÂN PHỐI TRANG PHỤNG
              </h2>
            </div>

            <div class="rounded-lg overflow-hidden border border-slate-200 bg-slate-100 h-56 sm:h-64 mb-3">
              <img 
                src="https://drive.google.com/thumbnail?id=1m6NnkLWgwaopsKblzRvWbB9bdqh2Nsae&sz=w1000" 
                data-drive-id="1m6NnkLWgwaopsKblzRvWbB9bdqh2Nsae"
                data-label="Anh Cong Ty Trang Phung"
                onerror="handleDriveImgError(this)"
                alt="Hình ảnh thực tế Nhà Phân Phối Trang Phụng" 
                class="w-full h-full object-cover"
              >
            </div>

            <h3 class="text-sm sm:text-base font-bold text-slate-800 mb-1.5">
              Nhà Cung Ứng Vật Tư Kim Khí, Cơ Khí, Hóa Chất & Dụng Cụ Cầm Tay Uy Tín Tại Đà Nẵng
            </h3>
            <p class="text-xs sm:text-sm text-slate-600 leading-relaxed mb-3">
              <strong>Nhà Phân Phối Trang Phụng (trangphung.com)</strong> tọa lạc tại <strong>338-340 Bùi Thiện Ngộ, Phường Hòa Xuân, TP. Đà Nẵng</strong>. Chúng tôi chuyên phân phối sỉ và lẻ các dòng sản phẩm: Bulong – Ốc vít, dụng cụ đồ nghề cầm tay, đá cắt – đá mài, keo silicon, keo dán công nghiệp, sơn PU/NC, dung môi, sơn mạ kẽm, thiết bị khí nén và vật tư tiêu hao nhà xưởng.
            </p>
          </div>

          <div class="grid grid-cols-2 gap-2.5 pt-2 border-t border-slate-100 text-xs">
            <div class="p-2.5 rounded-lg bg-slate-50 border border-slate-200">
              <div class="font-bold text-[#0f4c81]"><i class="fa-solid fa-check-circle text-[#d9251d] mr-1"></i>Hàng Chính Hãng 100%</div>
              <div class="text-[11px] text-slate-500 mt-0.5">Đầy đủ quy cách, tiêu chuẩn kỹ thuật</div>
            </div>
            <div class="p-2.5 rounded-lg bg-slate-50 border border-slate-200">
              <div class="font-bold text-[#0f4c81]"><i class="fa-solid fa-bolt text-[#d9251d] mr-1"></i>Giao Nhanh Trong Ngày</div>
              <div class="text-[11px] text-slate-500 mt-0.5">Hỗ trợ công trình & nhà xưởng Đà Nẵng</div>
            </div>
          </div>
        </div>

        <!-- Cột phải: FORM YÊU CẦU VÀ BÁO GIÁ TRANG CHỦ -->
        <div id="form-bao-gia" class="lg:col-span-6 bg-white rounded-xl shadow-xs border border-slate-200 p-4">
          <div class="flex items-center gap-2 border-b border-slate-200 pb-2.5 mb-3">
            <span class="w-1.5 h-5 rounded-full bg-[#d9251d]"></span>
            <h2 class="text-sm sm:text-base font-extrabold text-[#0f4c81] uppercase">
              ĐĂNG KÝ YÊU CẦU TƯ VẤN & NHẬN BÁO GIÁ SỈ
            </h2>
          </div>

          <p class="text-xs text-slate-600 mb-3">
            Quý khách hàng, đại lý, nhà thầu cần báo giá nhanh danh mục vật tư kim khí, vui lòng điền thông tin bên dưới. Bộ phận kinh doanh Trang Phụng sẽ liên hệ ngay trong 15 phút!
          </p>

          <form id="quoteRequestForm" onsubmit="handleQuoteFormSubmit(event)" class="space-y-3 text-xs sm:text-sm">
            <div class="grid grid-cols-1 sm:grid-cols-2 gap-3">
              <div>
                <label class="block font-semibold text-slate-700 mb-1">Họ và tên / Tên đơn vị *</label>
                <input type="text" id="quoteName" required placeholder="Nhập họ tên hoặc tên công ty" class="w-full px-3 py-2 rounded-lg border border-slate-300 focus:border-[#0f4c81] focus:outline-none">
              </div>
              <div>
                <label class="block font-semibold text-slate-700 mb-1">Số điện thoại / Zalo *</label>
                <input type="tel" id="quotePhone" required placeholder="Ví dụ: 0905576733" class="w-full px-3 py-2 rounded-lg border border-slate-300 focus:border-[#0f4c81] focus:outline-none">
              </div>
            </div>

            <div class="grid grid-cols-1 sm:grid-cols-2 gap-3">
              <div>
                <label class="block font-semibold text-slate-700 mb-1">Danh mục quan tâm</label>
                <select id="quoteCategory" class="w-full px-3 py-2 rounded-lg border border-slate-300 focus:border-[#0f4c81] focus:outline-none bg-white">
                  <option value="Báo giá tổng hợp vật tư kim khí">Báo giá tổng hợp vật tư kim khí</option>
                  <option value="Bulong – Ốc Vít các loại">Bulong – Ốc Vít các loại</option>
                  <option value="Keo Silicon – Keo Dán – Sơn PU/NC">Keo Silicon – Keo Dán – Sơn PU/NC</option>
                  <option value="Dụng Cụ Cầm Tay – Đá Mài – Đá Cắt">Dụng Cụ Cầm Tay – Đá Mài – Đá Cắt</option>
                  <option value="Thiết Bị Khí Nén – Máy Móc – Điện">Thiết Bị Khí Nén – Máy Móc – Điện</option>
                  <option value="Dụng Cụ Phòng Khuôn – Tiêu Hao">Dụng Cụ Phòng Khuôn – Tiêu Hao</option>
                </select>
              </div>
              <div>
                <label class="block font-semibold text-slate-700 mb-1">Địa chỉ nhận hàng</label>
                <input type="text" id="quoteAddress" placeholder="Quận/Huyện, Tỉnh/Thành phố" class="w-full px-3 py-2 rounded-lg border border-slate-300 focus:border-[#0f4c81] focus:outline-none">
              </div>
            </div>

            <div>
              <label class="block font-semibold text-slate-700 mb-1">Nội dung yêu cầu / Quy cách & Số lượng cần báo giá *</label>
              <textarea id="quoteContent" rows="3" required placeholder="Nhập tên sản phẩm, quy cách (VD: Bulong Inox 304 M8x30, Keo Silicon, Đá cắt 107mm...) và số lượng cần mua..." class="w-full px-3 py-2 rounded-lg border border-slate-300 focus:border-[#0f4c81] focus:outline-none"></textarea>
            </div>

            <div class="flex flex-wrap items-center justify-between gap-2 pt-1">
              <div class="text-[11px] text-slate-500">
                <i class="fa-solid fa-headset text-[#0f4c81] mr-1"></i>Hotline trực tiếp: <strong class="text-[#d9251d]">0905.576.733 - 0935.249.951</strong>
              </div>
              <button type="submit" class="px-5 py-2.5 rounded-lg bg-[#d9251d] hover:bg-red-700 text-white font-bold shadow transition">
                <i class="fa-solid fa-paper-plane mr-1.5"></i>GỬI YÊU CẦU BÁO GIÁ
              </button>
            </div>
          </form>
        </div>

      </div>
    </section>

    <!-- ================= DANH MỤC CÁC BÀI VIẾT TRANG CHỦ (KINH NGHIỆM HAY) ================= -->
    <section id="tin-tuc" class="flatsome-container mt-5">
      <div class="bg-white rounded-xl shadow-xs border border-slate-200 p-3 sm:p-4">
        <div class="flex items-center justify-between border-b border-slate-200 pb-2.5 mb-3.5">
          <div class="flex items-center gap-2">
            <span class="w-1.5 h-5 rounded-full bg-[#0f4c81]"></span>
            <h2 class="text-sm sm:text-base font-extrabold text-[#0f4c81] uppercase">
              DANH MỤC BÀI VIẾT – KINH NGHIỆM HAY
            </h2>
          </div>
          <span class="text-[11px] text-slate-500">Kiến thức kim khí & vật tư công nghiệp</span>
        </div>

        <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-3.5">
          
          <!-- Bài viết 1 -->
          <article class="border border-slate-200 rounded-lg overflow-hidden flex flex-col justify-between bg-white hover:shadow-md transition">
            <div>
              <div class="h-36 bg-slate-100 overflow-hidden relative">
                <img src="https://drive.google.com/thumbnail?id=1ODt-OrWa3gCTXJhnexmv9aN-EbolZy4B&sz=w600" data-drive-id="1ODt-OrWa3gCTXJhnexmv9aN-EbolZy4B" data-label="Bai Viet 1" onerror="handleDriveImgError(this)" alt="Bulong Inox 201 304 316" class="w-full h-full object-contain p-2 bg-white">
                <span class="absolute top-2 left-2 bg-[#0f4c81] text-white text-[10px] font-bold px-2 py-0.5 rounded">Kinh Nghiệm Hay</span>
              </div>
              <div class="p-3">
                <h3 class="text-xs sm:text-sm font-bold text-slate-800 leading-snug mb-1.5">
                  Phân biệt Bulong Inox 201, 304, 316 chuẩn DIN 933 & DIN 912 trong cơ khí
                </h3>
                <p class="text-[11px] text-slate-600 leading-relaxed">
                  Hướng dẫn chi tiết cách chọn bulong inox chống ăn mòn, chịu lực cao phù hợp cho công trình xây dựng và lắp máy tại Đà Nẵng...
                </p>
              </div>
            </div>
            <div class="px-3 pb-3 pt-1 flex items-center justify-between text-[11px] text-slate-500 border-t border-slate-100">
              <span><i class="fa-regular fa-calendar mr-1"></i>Chuyên mục Kim Khí</span>
              <button type="button" onclick="openArticleModal(0)" class="text-[#0f4c81] font-bold hover:underline">Đọc tiếp →</button>
            </div>
          </article>

          <!-- Bài viết 2 -->
          <article class="border border-slate-200 rounded-lg overflow-hidden flex flex-col justify-between bg-white hover:shadow-md transition">
            <div>
              <div class="h-36 bg-slate-100 overflow-hidden relative">
                <img src="https://drive.google.com/thumbnail?id=1nJELgF4XaQfTQSlczJSWLZQQ166reIbe&sz=w600" data-drive-id="1nJELgF4XaQfTQSlczJSWLZQQ166reIbe" data-label="Bai Viet 2" onerror="handleDriveImgError(this)" alt="Keo dán công nghiệp" class="w-full h-full object-contain p-2 bg-white">
                <span class="absolute top-2 left-2 bg-[#0f4c81] text-white text-[10px] font-bold px-2 py-0.5 rounded">Hóa Chất & Keo</span>
              </div>
              <div class="p-3">
                <h3 class="text-xs sm:text-sm font-bold text-slate-800 leading-snug mb-1.5">
                  Top các loại keo dán công nghiệp, keo Silicon và sơn mạ kẽm thông dụng nhất
                </h3>
                <p class="text-[11px] text-slate-600 leading-relaxed">
                  Tìm hiểu ứng dụng thực tế của keo Silicon, keo khóa ren Loctite, keo dán nhanh AXIA và sơn xịt mạ kẽm chống gỉ sét mối hàn...
                </p>
              </div>
            </div>
            <div class="px-3 pb-3 pt-1 flex items-center justify-between text-[11px] text-slate-500 border-t border-slate-100">
              <span><i class="fa-regular fa-calendar mr-1"></i>Chuyên mục Hóa Chất</span>
              <button type="button" onclick="openArticleModal(1)" class="text-[#0f4c81] font-bold hover:underline">Đọc tiếp →</button>
            </div>
          </article>

          <!-- Bài viết 3 -->
          <article class="border border-slate-200 rounded-lg overflow-hidden flex flex-col justify-between bg-white hover:shadow-md transition">
            <div>
              <div class="h-36 bg-slate-100 overflow-hidden relative">
                <img src="https://drive.google.com/thumbnail?id=1lUsNiRG1UGUWjThuQM7uKKjYypMKI7mw&sz=w600" data-drive-id="1lUsNiRG1UGUWjThuQM7uKKjYypMKI7mw" data-label="Bai Viet 3" onerror="handleDriveImgError(this)" alt="Dụng cụ đồ mài" class="w-full h-full object-contain p-2 bg-white">
                <span class="absolute top-2 left-2 bg-[#0f4c81] text-white text-[10px] font-bold px-2 py-0.5 rounded">Dụng Cụ Đồ Mài</span>
              </div>
              <div class="p-3">
                <h3 class="text-xs sm:text-sm font-bold text-slate-800 leading-snug mb-1.5">
                  Kinh nghiệm lựa chọn đá cắt, đá mài và đầu mài đánh bóng kim loại an toàn
                </h3>
                <p class="text-[11px] text-slate-600 leading-relaxed">
                  Các thông số tốc độ vòng quay, độ hạt nhám và tiêu chuẩn an toàn khi sử dụng đá cắt inox, bàn chải đánh gỉ sợi thép...
                </p>
              </div>
            </div>
            <div class="px-3 pb-3 pt-1 flex items-center justify-between text-[11px] text-slate-500 border-t border-slate-100">
              <span><i class="fa-regular fa-calendar mr-1"></i>Chuyên mục Cơ Khí</span>
              <button type="button" onclick="openArticleModal(2)" class="text-[#0f4c81] font-bold hover:underline">Đọc tiếp →</button>
            </div>
          </article>

          <!-- Bài viết 4 -->
          <article class="border border-slate-200 rounded-lg overflow-hidden flex flex-col justify-between bg-white hover:shadow-md transition">
            <div>
              <div class="h-36 bg-slate-100 overflow-hidden relative">
                <img src="https://drive.google.com/thumbnail?id=15e_IE2GO_SyjwKn-ID8GMvdHEpJouDRm&sz=w600" data-drive-id="15e_IE2GO_SyjwKn-ID8GMvdHEpJouDRm" data-label="Bai Viet 4" onerror="handleDriveImgError(this)" alt="Thiết bị khí nén" class="w-full h-full object-contain p-2 bg-white">
                <span class="absolute top-2 left-2 bg-[#0f4c81] text-white text-[10px] font-bold px-2 py-0.5 rounded">Thiết Bị Công Nghiệp</span>
              </div>
              <div class="p-3">
                <h3 class="text-xs sm:text-sm font-bold text-slate-800 leading-snug mb-1.5">
                  Hướng dẫn chọn đầu nối nhanh khí nén, dây hơi PU và mỡ bôi trơn chịu nhiệt
                </h3>
                <p class="text-[11px] text-slate-600 leading-relaxed">
                  Giải pháp tối ưu hệ thống khí nén nhà xưởng không rò rỉ áp suất và quy trình tra mỡ bảo dưỡng vòng bi, khuôn mẫu...
                </p>
              </div>
            </div>
            <div class="px-3 pb-3 pt-1 flex items-center justify-between text-[11px] text-slate-500 border-t border-slate-100">
              <span><i class="fa-regular fa-calendar mr-1"></i>Kỹ thuật Nhà Xưởng</span>
              <button type="button" onclick="openArticleModal(3)" class="text-[#0f4c81] font-bold hover:underline">Đọc tiếp →</button>
            </div>
          </article>

        </div>
      </div>
    </section>

    <!-- ================= DANH MỤC CÁC ĐỐI TÁC ================= -->
    <section id="doi-tac" class="flatsome-container mt-5">
      <div class="bg-white rounded-xl shadow-xs border border-slate-200 p-3 sm:p-4">
        <div class="flex items-center justify-between border-b border-slate-200 pb-2.5 mb-3.5">
          <div class="flex items-center gap-2">
            <span class="w-1.5 h-5 rounded-full bg-[#d9251d]"></span>
            <h2 class="text-sm sm:text-base font-extrabold text-[#0f4c81] uppercase">
              ĐỐI TÁC & THƯƠNG HIỆU PHÂN PHỐI
            </h2>
          </div>
          <span class="text-[11px] text-slate-500">Hợp tác cùng các thương hiệu uy tín hàng đầu</span>
        </div>

        <div class="grid grid-cols-2 sm:grid-cols-3 md:grid-cols-6 gap-2.5">
          <div class="p-3 rounded-lg border border-slate-200 bg-slate-50 flex flex-col items-center justify-center text-center hover:border-[#0f4c81] transition">
            <span class="text-sm font-black tracking-wider text-[#0f4c81]">MOLYKOTE®</span>
            <span class="text-[10px] text-slate-500 mt-0.5">Mỡ Bôi Trơn Công Nghiệp</span>
          </div>
          <div class="p-3 rounded-lg border border-slate-200 bg-slate-50 flex flex-col items-center justify-center text-center hover:border-[#0f4c81] transition">
            <span class="text-sm font-black tracking-wider text-[#d9251d]">LOCTITE®</span>
            <span class="text-[10px] text-slate-500 mt-0.5">Keo Công Nghiệp & Khóa Ren</span>
          </div>
          <div class="p-3 rounded-lg border border-slate-200 bg-slate-50 flex flex-col items-center justify-center text-center hover:border-[#0f4c81] transition">
            <span class="text-sm font-black tracking-wider text-sky-700">SMC PNEUMATICS</span>
            <span class="text-[10px] text-slate-500 mt-0.5">Thiết Bị & Đầu Nối Khí Nén</span>
          </div>
          <div class="p-3 rounded-lg border border-slate-200 bg-slate-50 flex flex-col items-center justify-center text-center hover:border-[#0f4c81] transition">
            <span class="text-sm font-black tracking-wider text-emerald-700">SHIN-ETSU / AXIA</span>
            <span class="text-[10px] text-slate-500 mt-0.5">Keo Dán & Silicone</span>
          </div>
          <div class="p-3 rounded-lg border border-slate-200 bg-slate-50 flex flex-col items-center justify-center text-center hover:border-[#0f4c81] transition">
            <span class="text-sm font-black tracking-wider text-amber-600">TOTAL / MAKITA</span>
            <span class="text-[10px] text-slate-500 mt-0.5">Dụng Cụ Cầm Tay & Đồ Nghề</span>
          </div>
          <div class="p-3 rounded-lg border border-slate-200 bg-slate-50 flex flex-col items-center justify-center text-center hover:border-[#0f4c81] transition">
            <span class="text-sm font-black tracking-wider text-slate-800">INOX 304 DIN</span>
            <span class="text-[10px] text-slate-500 mt-0.5">Bulong Ốc Vít Chuẩn Quốc Tế</span>
          </div>
        </div>
      </div>
    </section>

    <!-- ================= ĐƯA GOOGLE MAP & FANPAGE RA NGOÀI TRANG CHỦ ================= -->
    <section id="lien-he-map" class="flatsome-container mt-5 mb-6">
      <div class="grid grid-cols-1 lg:grid-cols-12 gap-4">
        
        <!-- GOOGLE MAP TRANG CHỦ (7 cột trên máy tính) -->
        <div class="lg:col-span-7 bg-white rounded-xl shadow-xs border border-slate-200 p-3 sm:p-4 flex flex-col justify-between">
          <div>
            <div class="flex flex-wrap items-center justify-between gap-2 border-b border-slate-200 pb-2.5 mb-3">
              <div class="flex items-center gap-2">
                <span class="w-1.5 h-5 rounded-full bg-[#d9251d]"></span>
                <h2 class="text-sm sm:text-base font-extrabold text-[#0f4c81] uppercase">
                  BẢN ĐỒ GOOGLE MAPS – NHÀ PHÂN PHỐI TRANG PHỤNG
                </h2>
              </div>
              <a 
                href="https://www.google.com/maps/search/?api=1&query=338-340+B%C3%B9i+Thi%E1%BB%87n+Ng%E1%BB%99,+H%C3%B2a+Xu%C3%A2n,+%C4%90%C3%A0+N%E1%BA%B5ng" 
                target="_blank" 
                rel="noopener noreferrer"
                class="text-xs font-bold text-[#d9251d] hover:underline"
              >
                <i class="fa-solid fa-diamond-turn-right mr-1"></i>Mở Google Maps lớn
              </a>
            </div>

            <div class="text-xs text-slate-700 mb-2.5 flex flex-wrap items-center gap-x-4 gap-y-1">
              <span><i class="fa-solid fa-location-dot text-[#d9251d] mr-1"></i><strong>Địa chỉ:</strong> 338-340 Bùi Thiện Ngộ, Phường Hòa Xuân, Tp.Đà Nẵng</span>
              <span><i class="fa-solid fa-phone text-[#0f4c81] mr-1"></i><strong>Hotline:</strong> 0905.576.733 - 0935.249.951</span>
            </div>

            <!-- Khung Google Maps trực tiếp ngoài trang chủ -->
            <div class="w-full h-64 sm:h-72 rounded-lg overflow-hidden border border-slate-300 bg-slate-100 relative">
              <iframe 
                title="Bản đồ Nhà Phân Phối Trang Phụng 338-340 Bùi Thiện Ngộ, Phường Hòa Xuân, Đà Nẵng"
                src="https://maps.google.com/maps?q=338%20B%C3%B9i%20Thi%E1%BB%87n%20Ng%E1%BB%99,%20H%C3%B2a%20Xu%C3%A2n,%20C%E1%BA%A9m%20L%E1%BB%87,%20%C4%90%C3%A0%20N%E1%BA%B5ng&t=&z=16&ie=UTF8&iwloc=&output=embed" 
                class="w-full h-full border-0" 
                loading="lazy" 
                referrerpolicy="no-referrer-when-downgrade"
              ></iframe>
            </div>
          </div>

          <!-- Thẻ dẫn đường nhanh -->
          <div class="mt-3 pt-2.5 border-t border-slate-100 flex flex-wrap items-center justify-between gap-2 text-xs">
            <span class="text-slate-600"><i class="fa-solid fa-Warehouse text-[#0f4c81] mr-1"></i>Kho hàng mặt tiền đường Bùi Thiện Ngộ, xe tải đỗ tận nơi</span>
            <a 
              href="https://www.google.com/maps/search/?api=1&query=338-340+B%C3%B9i+Thi%E1%BB%87n+Ng%E1%BB%99,+Ph%C6%B0%E1%BB%9Dng+H%C3%B2a+Xu%C3%A2n,+%C4%90%C3%A0+N%E1%BA%B5ng" 
              target="_blank" 
              rel="noopener noreferrer"
              class="px-3 py-1.5 rounded-lg bg-[#0f4c81] hover:bg-[#09355c] text-white font-semibold transition"
            >
              <i class="fa-solid fa-location-arrow mr-1"></i>Chỉ đường đến Trang Phụng
            </a>
          </div>
        </div>

        <!-- FANPAGE FACEBOOK RA NGOÀI TRANG CHỦ (5 cột trên máy tính) -->
        <div class="lg:col-span-5 bg-white rounded-xl shadow-xs border border-slate-200 p-3 sm:p-4 flex flex-col justify-between">
          <div>
            <div class="flex items-center justify-between border-b border-slate-200 pb-2.5 mb-3">
              <div class="flex items-center gap-2">
                <span class="w-1.5 h-5 rounded-full bg-[#1877f2]"></span>
                <h2 class="text-sm sm:text-base font-extrabold text-[#0f4c81] uppercase">
                  FANPAGE NHÀ PHÂN PHỐI TRANG PHỤNG
                </h2>
              </div>
              <span class="text-xs font-semibold text-[#1877f2]"><i class="fa-brands fa-facebook mr-1"></i>Facebook</span>
            </div>

            <!-- Giao diện Fanpage trực quan ngay ngoài trang chủ -->
            <div class="rounded-xl border border-slate-200 overflow-hidden bg-slate-50">
              <!-- Ảnh bìa Fanpage lấy từ ảnh thực tế công ty -->
              <div class="relative h-36 bg-[#09355c] overflow-hidden">
                <img 
                  src="https://drive.google.com/thumbnail?id=1m6NnkLWgwaopsKblzRvWbB9bdqh2Nsae&sz=w800" 
                  data-drive-id="1m6NnkLWgwaopsKblzRvWbB9bdqh2Nsae"
                  data-label="Fanpage Trang Phung"
                  onerror="handleDriveImgError(this)"
                  alt="Bìa Fanpage Nhà Phân Phối Trang Phụng" 
                  class="w-full h-full object-cover opacity-85"
                >
                <div class="absolute inset-0 bg-gradient-to-t from-black/80 via-black/30 to-transparent"></div>
                <div class="absolute bottom-3 left-3 right-3 flex items-center gap-3">
                  <div class="w-12 h-12 rounded-lg bg-white p-1 shadow border border-white shrink-0 flex items-center justify-center overflow-hidden">
                    <img 
                      src="https://drive.google.com/thumbnail?id=10KscawaPXgqAAjwNXC6srgtzYC8sREWN&sz=w300" 
                      data-drive-id="10KscawaPXgqAAjwNXC6srgtzYC8sREWN"
                      data-label="Logo"
                      onerror="handleDriveImgError(this)"
                      alt="Logo Fanpage" 
                      class="max-h-full max-w-full object-contain"
                    >
                  </div>
                  <div class="text-white min-w-0">
                    <div class="font-bold text-xs sm:text-sm truncate flex items-center gap-1">
                      <span>Nhà Phân Phối Trang Phụng</span>
                      <i class="fa-solid fa-circle-check text-sky-400 text-xs"></i>
                    </div>
                    <div class="text-[11px] text-slate-200">Kim Khí • Vật Tư Công Nghiệp • 3.8K người theo dõi</div>
                  </div>
                </div>
              </div>

              <!-- Các nút tương tác Fanpage -->
              <div class="p-3 bg-white border-b border-slate-200 flex items-center justify-between gap-2">
                <a href="https://www.facebook.com" target="_blank" rel="noopener noreferrer" class="flex-1 py-1.5 px-3 rounded bg-[#1877f2] hover:bg-blue-700 text-white text-xs font-bold text-center transition">
                  <i class="fa-brands fa-facebook mr-1"></i>Theo dõi Trang
                </a>
                <a href="https://zalo.me/0905576733" target="_blank" rel="noopener noreferrer" class="flex-1 py-1.5 px-3 rounded bg-slate-100 hover:bg-slate-200 text-slate-800 text-xs font-bold text-center transition">
                  <i class="fa-brands fa-facebook-messenger text-[#1877f2] mr-1"></i>Gửi tin nhắn
                </a>
              </div>

              <!-- Bài đăng tiêu biểu trên Fanpage -->
              <div class="p-3 text-xs space-y-2">
                <div class="text-slate-700 leading-relaxed">
                  <strong>Nhà Phân Phối Trang Phụng (trangphung.com)</strong> chuyên phân phối sỉ & lẻ Bulong Ốc Vít, Keo Silicon, Sơn Công Nghiệp, Đá Cắt - Đá Mài, Dụng Cụ Cầm Tay chính hãng tại Đà Nẵng.
                </div>
                <div class="grid grid-cols-3 gap-1.5 pt-1">
                  <img src="https://drive.google.com/thumbnail?id=1G5NBdtRylR2M44sgRCBd7fsyPDK1EDq_&sz=w300" data-drive-id="1G5NBdtRylR2M44sgRCBd7fsyPDK1EDq_" data-label="SP5" onerror="handleDriveImgError(this)" alt="Ảnh SP Fanpage 1" class="h-16 w-full object-contain bg-white rounded border border-slate-200 p-1">
                  <img src="https://drive.google.com/thumbnail?id=1nBl0UB8r77ho39NyonEjtllptTkEutph&sz=w300" data-drive-id="1nBl0UB8r77ho39NyonEjtllptTkEutph" data-label="SP6" onerror="handleDriveImgError(this)" alt="Ảnh SP Fanpage 2" class="h-16 w-full object-contain bg-white rounded border border-slate-200 p-1">
                  <img src="https://drive.google.com/thumbnail?id=1eTo9z5y66H5o0Vy53MVTqoayZtDLXSfb&sz=w300" data-drive-id="1eTo9z5y66H5o0Vy53MVTqoayZtDLXSfb" data-label="SP8" onerror="handleDriveImgError(this)" alt="Ảnh SP Fanpage 3" class="h-16 w-full object-contain bg-white rounded border border-slate-200 p-1">
                </div>
              </div>
            </div>
          </div>

          <div class="mt-3 pt-2 border-t border-slate-100 text-[11px] text-slate-500 flex items-center justify-between">
            <span>Kết nối trực tiếp qua Fanpage & Zalo OA</span>
            <span class="font-bold text-[#0f4c81]">trangphung.com</span>
          </div>
        </div>

      </div>
    </section>

  </main>

  <!-- ================= FOOTER CHUẨN FLATSOME GIỐNG WEB MẪU ================= -->
  <footer class="bg-[#082b49] text-slate-200 pt-8 pb-20 md:pb-8 border-t-4 border-[#d9251d]">
    <div class="flatsome-container">
      <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-12 gap-6 pb-6 border-b border-white/15">
        
        <!-- Cột 1: Thông tin Nhà Phân Phối Trang Phụng -->
        <div class="lg:col-span-5 space-y-2.5">
          <div class="flex items-center gap-2.5">
            <div class="w-10 h-10 rounded-lg bg-white p-1 flex items-center justify-center shrink-0">
              <img 
                src="https://drive.google.com/thumbnail?id=10KscawaPXgqAAjwNXC6srgtzYC8sREWN&sz=w300" 
                data-drive-id="10KscawaPXgqAAjwNXC6srgtzYC8sREWN"
                data-label="Logo"
                onerror="handleDriveImgError(this)"
                alt="Logo Nhà Phân Phối Trang Phụng" 
                class="max-h-8 w-auto object-contain"
              >
            </div>
            <div>
              <div class="text-sm sm:text-base font-extrabold text-white uppercase">NHÀ PHÂN PHỐI TRANG PHỤNG</div>
              <div class="text-[11px] text-amber-300 font-semibold">Website: https://trangphung.com</div>
            </div>
          </div>

          <p class="text-xs text-slate-300 leading-relaxed">
            Nhà Phân Phối Trang Phụng tự hào là đơn vị cung ứng các loại vật tư kim khí công nghiệp, bulong ốc vít, dụng cụ cầm tay, đồ mài, keo silicon, sơn PU/NC, hóa chất và thiết bị khí nén hàng đầu tại Đà Nẵng.
          </p>

          <ul class="space-y-1.5 text-xs text-slate-200 pt-1">
            <li><i class="fa-solid fa-location-dot text-amber-400 w-5"></i><strong>Địa chỉ:</strong> 338-340 Bùi Thiện Ngộ, Phường Hòa Xuân, Tp.Đà Nẵng</li>
            <li><i class="fa-solid fa-phone-volume text-amber-400 w-5"></i><strong>Điện thoại:</strong> <a href="tel:0905576733" class="hover:text-amber-300 font-bold">0905.576.733</a> - <a href="tel:0935249951" class="hover:text-amber-300 font-bold">0935.249.951</a></li>
            <li><i class="fa-solid fa-globe text-amber-400 w-5"></i><strong>Website:</strong> trangphung.com</li>
          </ul>
        </div>

        <!-- Cột 2: Danh mục sản phẩm chính -->
        <div class="lg:col-span-4 space-y-2">
          <h3 class="text-xs sm:text-sm font-extrabold text-white uppercase tracking-wider border-b border-white/15 pb-1.5">
            DANH MỤC SẢN PHẨM
          </h3>
          <div class="grid grid-cols-2 gap-1.5 text-xs text-slate-300">
            <a href="#san-pham-thuc-te" onclick="filterByCategory('Bulong – Ốc Vít')" class="hover:text-amber-300 whitespace-nowrap">• Bulong – Ốc Vít</a>
            <a href="#san-pham-thuc-te" onclick="filterByCategory('Dầu Mỡ – Hóa Chất')" class="hover:text-amber-300 whitespace-nowrap">• Dầu Mỡ – Hóa Chất</a>
            <a href="#san-pham-thuc-te" onclick="filterByCategory('Dụng Cụ Cầm Tay')" class="hover:text-amber-300 whitespace-nowrap">• Dụng Cụ Cầm Tay</a>
            <a href="#san-pham-thuc-te" onclick="filterByCategory('Dụng Cụ Đồ Mài')" class="hover:text-amber-300 whitespace-nowrap">• Dụng Cụ Đồ Mài</a>
            <a href="#san-pham-thuc-te" onclick="filterByCategory('Dụng Cụ Tiêu Hao')" class="hover:text-amber-300 whitespace-nowrap">• Dụng Cụ Tiêu Hao</a>
            <a href="#san-pham-thuc-te" onclick="filterByCategory('Dụng Cụ Phòng Khuôn')" class="hover:text-amber-300 whitespace-nowrap">• Dụng Cụ Phòng Khuôn</a>
            <a href="#san-pham-thuc-te" onclick="filterByCategory('Thiết Bị Khí Nén')" class="hover:text-amber-300 whitespace-nowrap">• Thiết Bị Khí Nén</a>
            <a href="#san-pham-thuc-te" onclick="filterByCategory('Thiết Bị Máy Móc')" class="hover:text-amber-300 whitespace-nowrap">• Thiết Bị Máy Móc</a>
            <a href="#san-pham-thuc-te" onclick="filterByCategory('Đồ Bảo Hộ Lao Động')" class="hover:text-amber-300 whitespace-nowrap">• Đồ Bảo Hộ Lao Động</a>
            <a href="#san-pham-thuc-te" onclick="filterByCategory('Vòng Bi – Nam Châm')" class="hover:text-amber-300 whitespace-nowrap">• Vòng Bi – Nam Châm</a>
          </div>
        </div>

        <!-- Cột 3: Chính sách & Hỗ trợ khách hàng -->
        <div class="lg:col-span-3 space-y-2">
          <h3 class="text-xs sm:text-sm font-extrabold text-white uppercase tracking-wider border-b border-white/15 pb-1.5">
            CHÍNH SÁCH & HỖ TRỢ
          </h3>
          <ul class="space-y-1.5 text-xs text-slate-300">
            <li><a href="#gioi-thieu" class="hover:text-amber-300">Giới thiệu Nhà Phân Phối Trang Phụng</a></li>
            <li><a href="#form-bao-gia" class="hover:text-amber-300">Chính sách báo giá sỉ & đại lý</a></li>
            <li><a href="#form-bao-gia" class="hover:text-amber-300">Chính sách vận chuyển & giao nhận</a></li>
            <li><a href="#form-bao-gia" class="hover:text-amber-300">Chính sách đổi trả & bảo hành</a></li>
            <li><a href="#lien-he-map" class="hover:text-amber-300">Bản đồ đường đi (338-340 Bùi Thiện Ngộ)</a></li>
          </ul>
        </div>

      </div>

      <div class="pt-4 flex flex-col sm:flex-row items-center justify-between gap-2 text-[11px] text-slate-400">
        <div>© Bản quyền thuộc về <strong class="text-white">Nhà Phân Phối Trang Phụng (trangphung.com)</strong>. Thiết kế chuẩn giao diện Flatsome.</div>
        <div>Địa chỉ: 338-340 Bùi Thiện Ngộ, P. Hòa Xuân, TP. Đà Nẵng</div>
      </div>
    </div>
  </footer>

  <!-- ================= CÁC NÚT LIÊN HỆ NỔI BẬT ZALO, FACEBOOK, HOTLINE (Tương thích trên cả Máy Tính & Điện Thoại, gọn đẹp không che nội dung) ================= -->
  <div class="fixed left-2.5 bottom-3 z-40 flex flex-col items-start gap-2">
    
    <!-- Nút Zalo nổi bật -->
    <a 
      href="https://zalo.me/0905576733" 
      target="_blank" 
      rel="noopener noreferrer"
      class="inline-flex items-center gap-1.5 bg-[#0068ff] hover:bg-blue-700 text-white p-1.5 sm:px-3 sm:py-2 rounded-full shadow-lg transition w-auto"
      title="Chat Zalo 0905.576.733"
    >
      <span class="w-7 h-7 sm:w-6 sm:h-6 rounded-full bg-white text-[#0068ff] font-black text-[10px] flex items-center justify-center shrink-0">Zalo</span>
      <span class="text-xs font-bold pr-1 hidden sm:inline">Chat Zalo</span>
    </a>

    <!-- Nút Facebook nổi bật -->
    <a 
      href="#lien-he-map" 
      class="inline-flex items-center gap-1.5 bg-[#1877f2] hover:bg-blue-800 text-white p-1.5 sm:px-3 sm:py-2 rounded-full shadow-lg transition w-auto"
      title="Fanpage Facebook Nhà Phân Phối Trang Phụng"
    >
      <span class="w-7 h-7 sm:w-6 sm:h-6 rounded-full bg-white text-[#1877f2] flex items-center justify-center shrink-0">
        <i class="fa-brands fa-facebook-f text-xs"></i>
      </span>
      <span class="text-xs font-bold pr-1 hidden sm:inline">Facebook</span>
    </a>

    <!-- Nút Hotline 1 nổi bật -->
    <a 
      href="tel:0905576733" 
      class="pulse-btn inline-flex items-center gap-1.5 bg-[#d9251d] hover:bg-red-700 text-white px-2.5 py-1.5 sm:px-3 sm:py-2 rounded-full shadow-lg transition w-auto"
      title="Gọi 0905.576.733"
    >
      <span class="w-6 h-6 rounded-full bg-white text-[#d9251d] flex items-center justify-center shrink-0">
        <i class="fa-solid fa-phone-volume text-xs"></i>
      </span>
      <span class="text-[11px] sm:text-xs font-extrabold pr-1">0905.576.733</span>
    </a>

    <!-- Nút Hotline 2 nổi bật -->
    <a 
      href="tel:0935249951" 
      class="inline-flex items-center gap-1.5 bg-[#0f4c81] hover:bg-[#09355c] text-white px-2.5 py-1.5 sm:px-3 sm:py-1.5 rounded-full shadow-lg transition border border-white/20 w-auto"
      title="Gọi 0935.249.951"
    >
      <span class="w-5 h-5 rounded-full bg-amber-400 text-slate-900 flex items-center justify-center shrink-0">
        <i class="fa-solid fa-phone text-[10px]"></i>
      </span>
      <span class="text-[11px] font-bold pr-1">0935.249.951</span>
    </a>

  </div>

  <!-- ================= MODAL XEM NHANH / ĐẶT HÀNG & GIỎ BÁO GIÁ (Không dùng alert) ================= -->
  <div id="customModal" class="fixed inset-0 bg-slate-900/60 z-50 hidden items-center justify-center p-3">
    <div class="bg-white rounded-xl max-w-lg w-full p-4 sm:p-5 shadow-2xl border border-slate-200 max-h-[90vh] overflow-y-auto">
      <div class="flex items-center justify-between border-b border-slate-200 pb-2.5 mb-3">
        <h3 id="modalTitle" class="text-sm sm:text-base font-extrabold text-[#0f4c81] uppercase">THÔNG BÁO</h3>
        <button type="button" onclick="closeCustomModal()" class="w-7 h-7 rounded-lg bg-slate-100 hover:bg-slate-200 text-slate-600 flex items-center justify-center">
          <i class="fa-solid fa-xmark"></i>
        </button>
      </div>
      <div id="modalBody" class="text-xs sm:text-sm text-slate-700 space-y-3"></div>
    </div>
  </div>

  <!-- ================= JAVASCRIPT XỬ LÝ DỮ LIỆU SẢN PHẨM, SLIDER & TƯƠNG TÁC ================= -->
  <script>
    // Danh sách 14 sản phẩm thực tế lấy trực tiếp từ 14 file Google Drive của Nhà Phân Phối Trang Phụng
    const REAL_PRODUCTS = [
      {
        id: 'tp-01',
        driveId: '1ODt-OrWa3gCTXJhnexmv9aN-EbolZy4B',
        name: 'Bulong Lục Giác Chìm Inox 304 Tiêu Chuẩn DIN 912 (Đủ Quy Cách M4 - M24)',
        category: 'Bulong – Ốc Vít',
        oldPrice: 185000,
        salePrice: 150000,
        discountPercent: 19,
        unit: 'Hộp / Bịch'
      },
      {
        id: 'tp-02',
        driveId: '1nJELgF4XaQfTQSlczJSWLZQQ166reIbe',
        name: 'Keo Dán Công Nghiệp & Keo Silicon Kết Dính Đa Năng Chịu Nhiệt Cao',
        category: 'Dầu Mỡ – Hóa Chất',
        oldPrice: 95000,
        salePrice: 78000,
        discountPercent: 18,
        unit: 'Chai / Tuýp'
      },
      {
        id: 'tp-03',
        driveId: '1lUsNiRG1UGUWjThuQM7uKKjYypMKI7mw',
        name: 'Đá Cắt Sắt Inox & Đá Mài Hợp Kim Công Nghiệp Siêu Bén Chính Hãng',
        category: 'Dụng Cụ Đồ Mài',
        oldPrice: 145000,
        salePrice: 118000,
        discountPercent: 19,
        unit: 'Hộp 25 viên'
      },
      {
        id: 'tp-04',
        driveId: '1apNof0fiboG58EAA566Ei9ww1GoWJuUo',
        name: 'Bộ Dụng Cụ Cầm Tay & Đồ Nghề Cơ Khí Sửa Chữa Chuyên Dụng',
        category: 'Dụng Cụ Cầm Tay',
        oldPrice: 320000,
        salePrice: 265000,
        discountPercent: 17,
        unit: 'Bộ'
      },
      {
        id: 'tp-05',
        driveId: '1G5NBdtRylR2M44sgRCBd7fsyPDK1EDq_',
        name: 'Sơn Xịt Mạ Kẽm Lạnh & Sơn Công Nghiệp PU / NC Chống Gỉ Sét Cao Cấp',
        category: 'Dầu Mỡ – Hóa Chất',
        oldPrice: 135000,
        salePrice: 110000,
        discountPercent: 19,
        unit: 'Bình / Lon'
      },
      {
        id: 'tp-06',
        driveId: '1nBl0UB8r77ho39NyonEjtllptTkEutph',
        name: 'Mỡ Bôi Trơn Chịu Nhiệt Công Nghiệp MOLYKOTE & Dầu Bảo Dưỡng Máy',
        category: 'Dầu Mỡ – Hóa Chất',
        oldPrice: 290000,
        salePrice: 245000,
        discountPercent: 16,
        unit: 'Hộp'
      },
      {
        id: 'tp-07',
        driveId: '15e_IE2GO_SyjwKn-ID8GMvdHEpJouDRm',
        name: 'Đầu Nối Nhanh Khí Nén PC/PE/PEG & Phụ Kiện Dây Hơi Áp Lực Cao SMC',
        category: 'Thiết Bị Khí Nén',
        oldPrice: 160000,
        salePrice: 132000,
        discountPercent: 18,
        unit: 'Túi 10 cái'
      },
      {
        id: 'tp-08',
        driveId: '1eTo9z5y66H5o0Vy53MVTqoayZtDLXSfb',
        name: 'Băng Keo Chịu Nhiệt Teflon / PET & Băng Dính Cách Điện Công Nghiệp',
        category: 'Dụng Cụ Tiêu Hao',
        oldPrice: 110000,
        salePrice: 89000,
        discountPercent: 19,
        unit: 'Cuộn'
      },
      {
        id: 'tp-09',
        driveId: '1AblxnH01SuL6vTa-aZuCJis-9xaZdl3T',
        name: 'Bàn Chải Cước Sắt, Chổi Đánh Gỉ Sợi Đồng & Đầu Mài Đánh Bóng Kim Loại',
        category: 'Dụng Cụ Đồ Mài',
        oldPrice: 85000,
        salePrice: 68000,
        discountPercent: 20,
        unit: 'Cái'
      },
      {
        id: 'tp-10',
        driveId: '1Cp0gOblBVAq_5D69elaxSTkUFpC_uRtd',
        name: 'Chốt Định Vị Khuôn Mẫu Inox 304 (M2 - M10) & Áo Chốt Pin Phòng Khuôn',
        category: 'Dụng Cụ Phòng Khuôn',
        oldPrice: 210000,
        salePrice: 175000,
        discountPercent: 17,
        unit: 'Bộ / Hộp'
      },
      {
        id: 'tp-11',
        driveId: '1DxwC3sdES-rwzgGAFqV2aOeRP3fPQFGQ',
        name: 'Bulong Thép Đen Cường Độ Cao 8.8 / 10.9, Đai Ốc & Vòng Đệm Phẳng - Vênh',
        category: 'Bulong – Ốc Vít',
        oldPrice: 195000,
        salePrice: 162000,
        discountPercent: 17,
        unit: 'Kg / Hộp'
      },
      {
        id: 'tp-12',
        driveId: '1RF6rWKynhGj4pWiRhsj-NomE6lddw_EV',
        name: 'Lõi Lọc Công Nghiệp Đa Cấp Độ & Vật Tư Lọc Nước - Lọc Khí Nhà Xưởng',
        category: 'Dụng Cụ Tiêu Hao',
        oldPrice: 175000,
        salePrice: 142000,
        discountPercent: 19,
        unit: 'Lõi'
      },
      {
        id: 'tp-13',
        driveId: '1q1R-0OSp3kgpgDlJ6zdbn8dcBe5D1_SA',
        name: 'Công Tắc Hành Trình, Rơ Le Thời Gian & Thiết Bị Điện Máy Móc Công Nghiệp',
        category: 'Thiết Bị Máy Móc',
        oldPrice: 240000,
        salePrice: 198000,
        discountPercent: 18,
        unit: 'Cái'
      },
      {
        id: 'tp-14',
        driveId: '16_vnu3sGDDVxT08hoOfr92m2Qy-ubZpx',
        name: 'Găng Tay Bảo Hộ Lao Động Phủ PU Chống Cắt & Vật Tư An Toàn Nhà Xưởng',
        category: 'Đồ Bảo Hộ Lao Động',
        oldPrice: 120000,
        salePrice: 96000,
        discountPercent: 20,
        unit: 'Bịch 10 đôi'
      }
    ];

    let cartItems = [];

    function formatVND(amount) {
      return amount.toString().replace(/\B(?=(\d{3})+(?!\d))/g, '.') + ' ₫';
    }

    // Tạo thẻ sản phẩm chuẩn Flatsome:
    // - % giảm giá góc trên bên trái (.flatsome-sale-badge)
    // - Giá gốc gạch ngang + Giá giảm nổi bật
    // - Tên sản phẩm đầy đủ (.product-title-full), không bị cắt chữ hay tràn ra ngoài
    function createProductCardHTML(product) {
      return `
        <div class="bg-white rounded-lg border border-slate-200 hover:border-[#0f4c81] hover:shadow-md transition flex flex-col justify-between overflow-hidden group min-w-0 w-full max-w-full">
          <div>
            <div class="relative w-full h-36 sm:h-44 bg-white border-b border-slate-100 p-2 flex items-center justify-center overflow-hidden">
              <span class="flatsome-sale-badge">-${product.discountPercent}%</span>
              <img 
                src="https://drive.google.com/thumbnail?id=${product.driveId}&sz=w600" 
                data-drive-id="${product.driveId}"
                data-label="${product.category}"
                onerror="handleDriveImgError(this)"
                alt="${product.name}" 
                class="max-h-full max-w-full object-contain group-hover:scale-105 transition-transform duration-300"
              >
            </div>
            <div class="p-2.5 sm:p-3">
              <div class="text-[10px] font-semibold text-[#0f4c81] uppercase mb-1">
                ${product.category}
              </div>
              <h3 class="product-title-full text-xs sm:text-[13px] font-bold text-slate-800 group-hover:text-[#0f4c81] transition">
                ${product.name}
              </h3>
            </div>
          </div>

          <div class="px-2.5 pb-2.5 sm:px-3 sm:pb-3 pt-1 border-t border-slate-100">
            <div class="flex flex-wrap items-baseline gap-1.5 mb-2">
              <del class="text-[11px] text-slate-400 font-medium">${formatVND(product.oldPrice)}</del>
              <span class="text-xs sm:text-sm font-extrabold text-[#d9251d]">${formatVND(product.salePrice)}</span>
            </div>
            <div class="grid grid-cols-2 gap-1.5">
              <button 
                type="button" 
                onclick="addToCart('${product.id}')" 
                class="py-1.5 px-2 rounded bg-[#0f4c81] hover:bg-[#09355c] text-white text-[11px] font-bold transition text-center"
              >
                + Giỏ hàng
              </button>
              <button 
                type="button" 
                onclick="quickQuoteProduct('${product.id}')" 
                class="py-1.5 px-2 rounded bg-amber-50 hover:bg-amber-100 text-[#d9251d] border border-amber-200 text-[11px] font-bold transition text-center"
              >
                Báo giá sỉ
              </button>
            </div>
          </div>
        </div>
      `;
    }

    function renderAllProductSections(filterCat = 'all', searchKeyword = '') {
      const mainGrid = document.getElementById('realProductsGrid');
      const activeLabel = document.getElementById('activeCategoryLabel');

      let filtered = REAL_PRODUCTS.filter(p => {
        const matchCat = (filterCat === 'all') || (p.category === filterCat);
        const matchSearch = !searchKeyword || p.name.toLowerCase().includes(searchKeyword.toLowerCase()) || p.category.toLowerCase().includes(searchKeyword.toLowerCase());
        return matchCat && matchSearch;
      });

      if (activeLabel) {
        activeLabel.textContent = filterCat === 'all'
          ? `Tất cả (${filtered.length})`
          : `${filterCat} (${filtered.length})`;
      }

      if (mainGrid) {
        if (filtered.length === 0) {
          mainGrid.innerHTML = `
            <div class="col-span-full py-8 text-center text-xs sm:text-sm text-slate-500">
              Không tìm thấy sản phẩm phù hợp. <button type="button" onclick="filterByCategory('all')" class="text-[#0f4c81] font-bold underline ml-1">Xem tất cả 14 sản phẩm</button>
            </div>
          `;
        } else {
          mainGrid.innerHTML = filtered.map(createProductCardHTML).join('');
        }
      }

      // Render 4 khối danh mục chuyên biệt giống web mẫu kimkhithanhthang.com
      const bulongList = REAL_PRODUCTS.filter(p => ['Bulong – Ốc Vít', 'Dụng Cụ Phòng Khuôn'].includes(p.category));
      const hoaChatList = REAL_PRODUCTS.filter(p => ['Dầu Mỡ – Hóa Chất'].includes(p.category));
      const dungCuList = REAL_PRODUCTS.filter(p => ['Dụng Cụ Cầm Tay', 'Dụng Cụ Đồ Mài', 'Dụng Cụ Tiêu Hao'].includes(p.category));
      const thietBiList = REAL_PRODUCTS.filter(p => ['Thiết Bị Khí Nén', 'Thiết Bị Máy Móc', 'Đồ Bảo Hộ Lao Động'].includes(p.category));

      document.getElementById('sectionGridBulong').innerHTML = bulongList.map(createProductCardHTML).join('');
      document.getElementById('sectionGridHoaChat').innerHTML = hoaChatList.map(createProductCardHTML).join('');
      document.getElementById('sectionGridDungCu').innerHTML = dungCuList.map(createProductCardHTML).join('');
      document.getElementById('sectionGridThietBi').innerHTML = thietBiList.map(createProductCardHTML).join('');
    }

    function filterByCategory(category) {
      document.querySelectorAll('.filter-tab').forEach(btn => {
        if (btn.getAttribute('data-cat') === category) {
          btn.className = 'filter-tab px-2.5 py-1 rounded text-[11px] font-semibold bg-[#0f4c81] text-white';
        } else {
          btn.className = 'filter-tab px-2.5 py-1 rounded text-[11px] font-semibold bg-slate-100 text-slate-700 hover:bg-slate-200';
        }
      });

      renderAllProductSections(category, '');
      const el = document.getElementById('san-pham-thuc-te');
      if (el) el.scrollIntoView({ behavior: 'smooth', block: 'start' });
    }

    function handleSearchSubmit(e) {
      e.preventDefault();
      const cat = document.getElementById('desktopSearchCat').value;
      const kw = document.getElementById('desktopSearchInput').value.trim();
      renderAllProductSections(cat, kw);
      document.getElementById('san-pham-thuc-te').scrollIntoView({ behavior: 'smooth' });
    }

    function handleMobileSearchSubmit(e) {
      e.preventDefault();
      const kw = document.getElementById('mobileSearchInput').value.trim();
      renderAllProductSections('all', kw);
      document.getElementById('san-pham-thuc-te').scrollIntoView({ behavior: 'smooth' });
    }

    // ================= SLIDER 2 BANNER TỰ TRƯỢT =================
    let currentBannerIndex = 0;
    const totalBanners = 2;

    function updateBannerSlides() {
      const desktopSlides = document.querySelectorAll('.desktop-slide');
      const mobileSlides = document.querySelectorAll('.mobile-slide');
      const dot0 = document.getElementById('bannerDot0');
      const dot1 = document.getElementById('bannerDot1');

      desktopSlides.forEach((s, idx) => {
        if (idx === currentBannerIndex) {
          s.classList.remove('opacity-0', 'z-0');
          s.classList.add('opacity-100', 'z-10');
        } else {
          s.classList.remove('opacity-100', 'z-10');
          s.classList.add('opacity-0', 'z-0');
        }
      });

      mobileSlides.forEach((s, idx) => {
        if (idx === currentBannerIndex) {
          s.classList.remove('opacity-0', 'z-0');
          s.classList.add('opacity-100', 'z-10');
        } else {
          s.classList.remove('opacity-100', 'z-10');
          s.classList.add('opacity-0', 'z-0');
        }
      });

      if (dot0 && dot1) {
        dot0.className = currentBannerIndex === 0
          ? 'w-5 h-1.5 rounded-full bg-amber-400 transition-all'
          : 'w-2 h-1.5 rounded-full bg-white/50 transition-all';
        dot1.className = currentBannerIndex === 1
          ? 'w-5 h-1.5 rounded-full bg-amber-400 transition-all'
          : 'w-2 h-1.5 rounded-full bg-white/50 transition-all';
      }
    }

    function nextBannerSlide() {
      currentBannerIndex = (currentBannerIndex + 1) % totalBanners;
      updateBannerSlides();
    }

    function prevBannerSlide() {
      currentBannerIndex = (currentBannerIndex - 1 + totalBanners) % totalBanners;
      updateBannerSlides();
    }

    function goToBannerSlide(index) {
      currentBannerIndex = index;
      updateBannerSlides();
    }

    setInterval(nextBannerSlide, 4800);

    // ================= MENU ĐIỆN THOẠI =================
    function toggleMobileDrawer() {
      const drawer = document.getElementById('mobileDrawer');
      const backdrop = document.getElementById('mobileDrawerBackdrop');
      const isHidden = drawer.classList.contains('-translate-x-full');

      if (isHidden) {
        drawer.classList.remove('-translate-x-full');
        backdrop.classList.remove('hidden');
      } else {
        drawer.classList.add('-translate-x-full');
        backdrop.classList.add('hidden');
      }
    }

    // ================= GIỎ HÀNG & BÁO GIÁ (Không dùng alert) =================
    function openCustomModal(title, htmlContent) {
      document.getElementById('modalTitle').textContent = title;
      document.getElementById('modalBody').innerHTML = htmlContent;
      const modal = document.getElementById('customModal');
      modal.classList.remove('hidden');
      modal.classList.add('flex');
    }

    function closeCustomModal() {
      const modal = document.getElementById('customModal');
      modal.classList.add('hidden');
      modal.classList.remove('flex');
    }

    function addToCart(productId) {
      const product = REAL_PRODUCTS.find(p => p.id === productId);
      if (!product) return;

      const existing = cartItems.find(item => item.id === productId);
      if (existing) {
        existing.qty += 1;
      } else {
        cartItems.push({ ...product, qty: 1 });
      }

      const totalCount = cartItems.reduce((sum, i) => sum + i.qty, 0);
      document.getElementById('cartCountBadge').textContent = totalCount;

      openCustomModal('ĐÃ THÊM VÀO DANH SÁCH ĐẶT HÀNG', `
        <div class="flex items-center gap-3 p-2.5 rounded-lg bg-slate-50 border border-slate-200">
          <img src="https://drive.google.com/thumbnail?id=${product.driveId}&sz=w200" class="w-14 h-14 object-contain bg-white rounded border p-1">
          <div>
            <div class="font-bold text-slate-800">${product.name}</div>
            <div class="text-[#d9251d] font-bold mt-0.5">${formatVND(product.salePrice)} <span class="text-slate-400 font-normal text-xs">(Giảm ${product.discountPercent}%)</span></div>
          </div>
        </div>
        <div class="flex items-center justify-end gap-2 pt-2">
          <button type="button" onclick="closeCustomModal()" class="px-3 py-1.5 rounded bg-slate-200 text-slate-700 font-semibold text-xs">Tiếp tục xem</button>
          <button type="button" onclick="openCartModal()" class="px-3 py-1.5 rounded bg-[#0f4c81] text-white font-semibold text-xs">Xem giỏ hàng (${totalCount})</button>
        </div>
      `);
    }

    function openCartModal() {
      if (cartItems.length === 0) {
        openCustomModal('GIỎ HÀNG CỦA BẠN', `
          <div class="py-4 text-center text-slate-500">
            Hiện chưa có sản phẩm nào trong giỏ hàng. Hãy chọn sản phẩm để nhận báo giá ưu đãi!
          </div>
        `);
        return;
      }

      let total = 0;
      const rows = cartItems.map(item => {
        const sub = item.salePrice * item.qty;
        total += sub;
        return `
          <div class="flex items-center justify-between gap-2 py-2 border-b border-slate-100">
            <div class="min-w-0">
              <div class="font-bold text-xs text-slate-800">${item.name}</div>
              <div class="text-[11px] text-slate-500">${formatVND(item.salePrice)} x ${item.qty}</div>
            </div>
            <div class="font-bold text-xs text-[#d9251d] shrink-0">${formatVND(sub)}</div>
          </div>
        `;
      }).join('');

      openCustomModal('GIỎ HÀNG & GỬI YÊU CẦU ĐẶT HÀNG', `
        <div class="max-h-60 overflow-y-auto">${rows}</div>
        <div class="flex items-center justify-between pt-2 font-extrabold text-sm text-[#0f4c81]">
          <span>Tạm tính:</span>
          <span class="text-[#d9251d]">${formatVND(total)}</span>
        </div>
        <div class="pt-3 flex flex-wrap items-center justify-end gap-2">
          <a href="https://zalo.me/0905576733" target="_blank" rel="noopener noreferrer" class="px-3.5 py-2 rounded bg-[#0068ff] text-white text-xs font-bold">Gửi đơn qua Zalo 0905.576.733</a>
          <button type="button" onclick="transferCartToQuoteForm()" class="px-3.5 py-2 rounded bg-[#d9251d] text-white text-xs font-bold">Điền Form Báo Giá</button>
        </div>
      `);
    }

    function quickQuoteProduct(productId) {
      const product = REAL_PRODUCTS.find(p => p.id === productId);
      if (!product) return;
      const contentBox = document.getElementById('quoteContent');
      if (contentBox) {
        contentBox.value = `Yêu cầu báo giá sỉ sản phẩm: ${product.name} - Số lượng cần mua: ...`;
      }
      document.getElementById('form-bao-gia').scrollIntoView({ behavior: 'smooth' });
    }

    function transferCartToQuoteForm() {
      const summary = cartItems.map(i => `- ${i.name} (SL: ${i.qty})`).join('\n');
      document.getElementById('quoteContent').value = `Báo giá đơn hàng gồm:\n${summary}`;
      closeCustomModal();
      document.getElementById('form-bao-gia').scrollIntoView({ behavior: 'smooth' });
    }

    function handleQuoteFormSubmit(e) {
      e.preventDefault();
      const name = document.getElementById('quoteName').value;
      const phone = document.getElementById('quotePhone').value;
      const cat = document.getElementById('quoteCategory').value;
      const content = document.getElementById('quoteContent').value;

      openCustomModal('ĐÃ GỬI YÊU CẦU BÁO GIÁ THÀNH CÔNG', `
        <div class="p-3 rounded-lg bg-emerald-50 border border-emerald-200 text-emerald-800 text-xs leading-relaxed">
          Cảm ơn <strong>${name}</strong> (SĐT: <strong>${phone}</strong>)! Yêu cầu báo giá danh mục <strong>${cat}</strong> của quý khách đã được ghi nhận tại hệ thống <strong>trangphung.com</strong>.
        </div>
        <div class="text-xs text-slate-600">
          <strong>Nội dung yêu cầu:</strong><br>${content}
        </div>
        <div class="text-xs text-slate-700 pt-1">
          Để nhận bảng giá chiết khấu ngay lập tức qua Zalo, quý khách có thể bấm nút bên dưới hoặc gọi trực tiếp <strong>0905.576.733 - 0935.249.951</strong>.
        </div>
        <div class="flex justify-end gap-2 pt-2">
          <a href="https://zalo.me/0905576733" target="_blank" rel="noopener noreferrer" class="px-4 py-2 rounded bg-[#0068ff] text-white text-xs font-bold">Mở Zalo 0905.576.733</a>
          <button type="button" onclick="closeCustomModal()" class="px-4 py-2 rounded bg-[#0f4c81] text-white text-xs font-bold">Đóng</button>
        </div>
      `);
      e.target.reset();
    }

    const ARTICLES_DATA = [
      {
        title: 'Phân biệt Bulong Inox 201, 304, 316 chuẩn DIN 933 & DIN 912 trong cơ khí',
        body: 'Bulong Inox 304 có khả năng chống gỉ sét vượt trội trong môi trường ẩm và ngoài trời tại khu vực ven biển miền Trung. Tại Nhà Phân Phối Trang Phụng (338-340 Bùi Thiện Ngộ, Hòa Xuân, Đà Nẵng), chúng tôi cung cấp đầy đủ các cấp bền và quy cách từ M3 đến M30.'
      },
      {
        title: 'Top các loại keo dán công nghiệp, keo Silicon và sơn mạ kẽm thông dụng nhất',
        body: 'Trong lắp ráp cơ khí và xây dựng, keo Silicon trung tính, keo khóa ren Loctite, keo dán nhanh AXIA và sơn xịt mạ kẽm lạnh giúp bảo vệ mối hàn và cố định chi tiết máy bền bỉ.'
      },
      {
        title: 'Kinh nghiệm lựa chọn đá cắt, đá mài và đầu mài đánh bóng kim loại an toàn',
        body: 'Khi gia công inox và thép hợp kim, việc chọn đúng đá cắt mỏng chính hãng và đầu mài hợp kim giúp đường cắt ngọt, không cháy phôi và đảm bảo an toàn lao động.'
      },
      {
        title: 'Hướng dẫn chọn đầu nối nhanh khí nén, dây hơi PU và mỡ bôi trơn chịu nhiệt',
        body: 'Hệ thống khí nén SMC kết hợp cùng mỡ bôi trơn chịu nhiệt MOLYKOTE giúp dây chuyền máy móc vận hành êm ái, giảm hao mòn vòng bi và xi lanh.'
      }
    ];

    function openArticleModal(idx) {
      const art = ARTICLES_DATA[idx];
      if (!art) return;
      openCustomModal(art.title, `
        <p class="leading-relaxed text-slate-700">${art.body}</p>
        <div class="p-2.5 rounded bg-slate-50 border border-slate-200 text-xs">
          <strong>Nhà Phân Phối Trang Phụng (trangphung.com)</strong><br>
          Địa chỉ: 338-340 Bùi Thiện Ngộ, Phường Hòa Xuân, Tp.Đà Nẵng<br>
          Hotline tư vấn kỹ thuật & báo giá: <strong>0905.576.733 - 0935.249.951</strong>
        </div>
      `);
    }

    // Tự động khử khoảng lệch trái của mọi khung bao ngoài (WordPress / Flatsome / Webview) và căn chuẩn sát mép màn hình
    function fixMobileAlignment() {
      const wrapper = document.getElementById('tp-site-wrapper');
      if (!wrapper) return;

      // Reset margin/padding trước khi đo
      wrapper.style.setProperty('margin-left', '0px', 'important');
      wrapper.style.setProperty('margin-right', '0px', 'important');
      wrapper.style.setProperty('width', '100%', 'important');
      wrapper.style.setProperty('max-width', '100%', 'important');

      // Đi ngược lên tất cả các thẻ cha bao ngoài và xóa sạch lề trái/phải + bóng đổ thừa
      let parent = wrapper.parentElement;
      while (parent && parent !== document.documentElement) {
        parent.style.setProperty('margin-left', '0px', 'important');
        parent.style.setProperty('margin-right', '0px', 'important');
        parent.style.setProperty('padding-left', '0px', 'important');
        parent.style.setProperty('padding-right', '0px', 'important');
        parent.style.setProperty('border-left', '0px', 'important');
        parent.style.setProperty('border-right', '0px', 'important');
        parent.style.setProperty('box-shadow', 'none', 'important');
        parent.style.setProperty('left', '0px', 'important');
        parent.style.setProperty('right', '0px', 'important');
        parent.style.setProperty('width', '100%', 'important');
        parent.style.setProperty('max-width', '100%', 'important');
        parent.style.setProperty('min-width', '0px', 'important');
        parent.style.setProperty('box-sizing', 'border-box', 'important');
        parent.style.setProperty('transform', 'none', 'important');
        parent = parent.parentElement;
      }

      // Kiểm tra tọa độ thực tế trên màn hình và bù trừ chính xác nếu khung ngoài vẫn đẩy lệch
      const vw = document.documentElement.clientWidth || window.innerWidth;
      const rect = wrapper.getBoundingClientRect();
      if (Math.abs(rect.left) > 0.5) {
        wrapper.style.setProperty('margin-left', (-rect.left) + 'px', 'important');
      }
      if (vw < 1024) {
        wrapper.style.setProperty('width', vw + 'px', 'important');
        wrapper.style.setProperty('max-width', vw + 'px', 'important');
      }
    }

    fixMobileAlignment();
    window.addEventListener('DOMContentLoaded', () => {
      fixMobileAlignment();
      renderAllProductSections('all', '');
    });
    window.addEventListener('load', fixMobileAlignment);
    window.addEventListener('resize', fixMobileAlignment);
  </script>
  </div>
</body>
</html>
