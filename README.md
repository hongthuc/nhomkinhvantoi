<html lang="vi">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Nhôm Kính Văn Tới | Cửa Nhôm Xingfa & Kính Cường Lực Tại TP. Đà Nẵng</title>
  <meta name="description" content="Nhôm kính Văn Tới (nhomkinhvantoi.com) chuyên thiết kế, gia công và thi công cửa nhôm Xingfa nhập khẩu, cửa kính cường lực, cầu thang kính, kính ốp bếp, phòng tắm kính uy tín tại TP. Đà Nẵng. Hotline: 0905.579.197." />

  <!-- Meta Open Graph & Twitter Thumbnail (Ảnh logo khi chia sẻ đường link website) -->
  <meta property="og:type" content="website" />
  <meta property="og:url" content="https://nhomkinhvantoi.com/" />
  <meta property="og:site_name" content="Nhôm Kính Văn Tới" />
  <meta property="og:title" content="Nhôm Kính Văn Tới - Cửa Nhôm Xingfa & Kính Cường Lực Đà Nẵng" />
  <meta property="og:description" content="Chuyên thi công Cửa nhôm Xingfa, Cửa kính cường lực, Cửa nhựa lõi thép, Cầu thang kính, Kính ốp bếp, Phòng tắm kính tại TP. Đà Nẵng. Hotline: 0905.579.197." />
  <meta property="og:image" content="https://nhomkinhvantoi.com/logo-nhom-kinh-van-toi.png" />
  <meta property="og:image:width" content="1200" />
  <meta property="og:image:height" content="630" />
  <meta name="twitter:card" content="summary_large_image" />
  <meta name="twitter:title" content="Nhôm Kính Văn Tới - nhomkinhvantoi.com" />
  <meta name="twitter:description" content="Thi công cửa nhôm Xingfa & kính cường lực uy tín tại TP. Đà Nẵng - Hotline: 0905.579.197" />
  <meta name="twitter:image" content="https://nhomkinhvantoi.com/logo-nhom-kinh-van-toi.png" />

  <!-- Favicon Logo SVG -->
  <link rel="icon" type="image/svg+xml" href="data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 64 64'%3E%3Crect width='64' height='64' rx='12' fill='%230B3C68'/%3E%3Crect x='10' y='10' width='44' height='44' rx='6' fill='none' stroke='%23E59A1A' stroke-width='3.5'/%3E%3Cpath d='M19 20L27 44L35 20M37 22H48M42.5 22V44' stroke='%23FFFFFF' stroke-width='4' stroke-linecap='round' stroke-linejoin='round' fill='none'/%3E%3C/svg%3E" />

  <!-- Font Inter & Tailwind CSS -->
  <link rel="preconnect" href="https://fonts.googleapis.com" />
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&display=swap" rel="stylesheet" />
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
              DEFAULT: '#0B3C68',
              dark: '#072847',
              light: '#145894',
              soft: '#EEF5FC',
            },
            accent: {
              DEFAULT: '#D98A0C',
              light: '#F3A829',
              dark: '#B57106',
            }
          }
        }
      }
    };
  </script>

  <style>
    /* Đảm bảo tuyệt đối không tràn viền ngang và không lệch sang phải trên mọi thiết bị */
    *, *::before, *::after {
      box-sizing: border-box;
    }
    html, body {
      margin: 0;
      padding: 0;
      width: 100%;
      max-width: 100%;
      overflow-x: hidden;
      font-family: 'Inter', sans-serif;
      scroll-behavior: smooth;
      background-color: #ffffff;
      color: #1e293b;
    }

    /* Chiều ngang giao diện trên máy tính đúng bằng 95% màn hình */
    .vt-container {
      width: 94%;
      max-width: 100%;
      margin-left: auto;
      margin-right: auto;
    }
    @media (min-width: 1024px) {
      .vt-container {
        width: 95%;
        max-width: 95vw;
      }
    }

    /* Thanh menu máy tính: chữ nhỏ gọn, viết liền không xuống dòng tên danh mục */
    .desktop-nav-item {
      white-space: nowrap;
      flex-shrink: 0;
    }
    .desktop-nav-dropdown {
      opacity: 0;
      visibility: hidden;
      transform: translateY(8px);
      transition: all 0.2s ease;
    }
    .group:hover .desktop-nav-dropdown,
    .group:focus-within .desktop-nav-dropdown {
      opacity: 1;
      visibility: visible;
      transform: translateY(0);
    }

    /* Slider 2 banner tự trượt kích thước bằng nhau tuyệt đối trên cả mobile & desktop */
    .hero-slider-grid {
      display: grid;
      grid-template-columns: 1fr;
    }
    .hero-slide {
      grid-area: 1 / 1;
      opacity: 0;
      visibility: hidden;
      pointer-events: none;
      transition: opacity 0.65s ease-in-out, visibility 0.65s ease-in-out;
    }
    .hero-slide.is-active {
      opacity: 1;
      visibility: visible;
      pointer-events: auto;
      z-index: 2;
    }

    /* Tiêu đề chuẩn Flatsome có gạch nhấn theo màu logo */
    .flatsome-heading {
      position: relative;
      display: inline-block;
      padding-bottom: 10px;
    }
    .flatsome-heading::after {
      content: '';
      position: absolute;
      left: 50%;
      bottom: 0;
      transform: translateX(-50%);
      width: 64px;
      height: 3px;
      background: linear-gradient(90deg, #0B3C68, #D98A0C);
      border-radius: 999px;
    }
    .flatsome-heading-left::after {
      left: 0;
      transform: none;
    }

    /* Hiệu ứng rung nhẹ cho nút Hotline nổi */
    @keyframes softPulse {
      0% { box-shadow: 0 0 0 0 rgba(217, 138, 12, 0.55); }
      70% { box-shadow: 0 0 0 12px rgba(217, 138, 12, 0); }
      100% { box-shadow: 0 0 0 0 rgba(217, 138, 12, 0); }
    }
    .pulse-hotline {
      animation: softPulse 2s infinite;
    }
  </style>
</head>
<body class="bg-white text-slate-800 antialiased">

  <!-- ===================================================================== -->
  <!-- UX BUILDER SECTION: TOP BAR & HEADER (KHÔNG NÚT GỌI NGAY ĐỂ KHÔNG TRÀN) -->
  <!-- ===================================================================== -->
  <div class="bg-brand-dark text-slate-200 text-xs py-1.5 border-b border-brand-light/30">
    <div class="vt-container flex items-center justify-between gap-2">
      <div class="flex items-center gap-3 min-w-0 truncate">
        <span class="inline-flex items-center gap-1.5 truncate">
          <svg class="w-3.5 h-3.5 text-accent-light shrink-0" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M17.657 16.657L13.414 20.9a1.998 1.998 0 01-2.827 0l-4.244-4.243a8 8 0 1111.314 0z"/><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M15 11a3 3 0 11-6 0 3 3 0 016 0z"/></svg>
          <span class="truncate">TP. Đà Nẵng</span>
        </span>
        <span class="hidden sm:inline text-slate-500">|</span>
        <span class="hidden sm:inline text-slate-300">Làm việc 24/7</span>
      </div>
      <div class="flex items-center gap-3 shrink-0">
        <span class="hidden md:inline text-slate-300">Website: nhomkinhvantoi.com</span>
        <a href="tel:0905579197" class="font-semibold text-accent-light hover:text-white transition">0905.579.197</a>
      </div>
    </div>
  </div>

  <!-- Main Sticky Header -->
  <header id="trang-chu" class="sticky top-0 z-40 bg-white shadow-sm border-b border-slate-200 w-full">
    <!-- Hàng 1: Logo nhỏ gọn + Thanh tìm kiếm sản phẩm (Không nút Gọi Ngay) -->
    <div class="vt-container py-2.5 flex items-center justify-between gap-3">
      <!-- Logo Nhôm Kính Văn Tới thiết kế gọn nhỏ, sắc nét -->
      <a href="#trang-chu" class="flex items-center gap-2.5 shrink-0 group focus:outline-none" aria-label="Nhôm Kính Văn Tới">
        <svg class="w-9 h-9 sm:w-10 sm:h-10 shrink-0" viewBox="0 0 64 64" fill="none" xmlns="http://www.w3.org/2000/svg">
          <rect width="64" height="64" rx="12" fill="#0B3C68"/>
          <rect x="6" y="6" width="52" height="52" rx="8" stroke="#E59A1A" stroke-width="2.5"/>
          <!-- Khung cửa kính cách điệu chữ VT -->
          <path d="M15 18L24.5 46L34 18" stroke="#FFFFFF" stroke-width="4.2" stroke-linecap="round" stroke-linejoin="round"/>
          <path d="M35.5 20H49.5" stroke="#F3A829" stroke-width="4.2" stroke-linecap="round"/>
          <path d="M42.5 20V46" stroke="#F3A829" stroke-width="4.2" stroke-linecap="round"/>
          <line x1="15" y1="51" x2="49" y2="51" stroke="#FFFFFF" stroke-opacity="0.35" stroke-width="1.5"/>
        </svg>
        <div class="leading-tight">
          <div class="text-sm sm:text-base font-extrabold tracking-tight text-brand uppercase">
            NHÔM KÍNH <span class="text-accent">VĂN TỚI</span>
          </div>
          <div class="text-[10px] sm:text-[11px] font-medium text-slate-500 tracking-wide">
            nhomkinhvantoi.com
          </div>
        </div>
      </a>

      <!-- Ô tìm kiếm gọn nhẹ trên máy tính & máy tính bảng -->
      <div class="hidden md:flex items-center flex-1 max-w-md mx-4">
        <div class="relative w-full">
          <input
            id="desktop-search-input"
            type="text"
            placeholder="Tìm cửa nhôm Xingfa, cầu thang kính, phòng tắm kính..."
            class="w-full bg-slate-50 border border-slate-300 rounded-lg pl-3.5 pr-10 py-1.5 text-xs sm:text-sm text-slate-700 focus:outline-none focus:border-brand focus:ring-2 focus:ring-brand/15 transition"
          />
          <button
            id="desktop-search-btn"
            type="button"
            aria-label="Tìm kiếm"
            class="absolute right-1.5 top-1/2 -translate-y-1/2 p-1.5 rounded-md text-brand hover:bg-brand-soft transition"
          >
            <svg class="w-4 h-4" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M21 21l-6-6m2-5a7 7 0 11-14 0 7 7 0 0114 0z"/></svg>
          </button>
        </div>
      </div>

      <!-- Thông tin địa chỉ ngắn bên phải trên màn hình lớn + Nút mở menu trên điện thoại -->
      <div class="flex items-center gap-2 shrink-0">
        <div class="hidden lg:flex items-center gap-2 text-right pr-1">
          <div class="w-8 h-8 rounded-lg bg-brand-soft text-brand flex items-center justify-center shrink-0">
            <svg class="w-4 h-4" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 12l2 2 4-4m5.618-4.016A11.955 11.955 0 0112 2.944a11.955 11.955 0 01-8.618 3.04A12.02 12.02 0 003 9c0 5.591 3.824 10.29 9 11.622 5.176-1.332 9-6.03 9-11.622 0-1.042-.133-2.052-.382-3.016z"/></svg>
          </div>
          <div class="leading-tight">
            <div class="text-[11px] font-bold text-brand uppercase">Chính hãng 100%</div>
            <div class="text-[10px] text-slate-500">Bảo hành dài hạn Đà Nẵng</div>
          </div>
        </div>

        <!-- Nút Menu Mobile -->
        <button
          id="mobile-menu-open"
          type="button"
          aria-label="Mở danh mục"
          class="lg:hidden inline-flex items-center justify-center gap-1.5 px-3 py-2 rounded-lg bg-brand text-white text-xs font-semibold hover:bg-brand-dark transition"
        >
          <svg class="w-5 h-5" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16M4 18h16"/></svg>
          <span>Danh mục</span>
        </button>
      </div>
    </div>

    <!-- Hàng 2: Thanh Danh Mục Máy Tính (Viết liền 1 hàng, chữ nhỏ gọn, không bao giờ xuống dòng tên danh mục) -->
    <nav class="hidden lg:block bg-brand text-white border-t border-brand-light/40" aria-label="Danh mục chính">
      <div class="vt-container">
        <ul class="flex flex-wrap items-center justify-between gap-x-1 gap-y-0.5 py-0">
          <li class="desktop-nav-item">
            <a href="#trang-chu" class="block px-2.5 xl:px-3.5 py-2.5 text-[12px] xl:text-[13px] font-semibold uppercase tracking-tight hover:bg-brand-light hover:text-accent-light transition rounded-t-sm">
              Trang chủ
            </a>
          </li>
          <li class="desktop-nav-item">
            <a href="#gioi-thieu" class="block px-2.5 xl:px-3.5 py-2.5 text-[12px] xl:text-[13px] font-semibold uppercase tracking-tight hover:bg-brand-light hover:text-accent-light transition">
              Giới thiệu
            </a>
          </li>

          <!-- Dropdown: Cửa nhôm xingfa -->
          <li class="desktop-nav-item relative group">
            <a href="#san-pham-xingfa" class="flex items-center gap-1 px-2.5 xl:px-3.5 py-2.5 text-[12px] xl:text-[13px] font-semibold uppercase tracking-tight hover:bg-brand-light hover:text-accent-light transition">
              <span>Cửa nhôm xingfa</span>
              <svg class="w-3.5 h-3.5 opacity-80" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 9l-7 7-7-7"/></svg>
            </a>
            <ul class="desktop-nav-dropdown absolute left-0 top-full w-56 bg-white text-slate-700 rounded-b-lg shadow-xl border border-slate-200 py-1.5 z-50">
              <li><a href="#san-pham-xingfa" onclick="filterProductsByKeyword('1 cánh')" class="block px-4 py-2 text-xs font-medium hover:bg-brand-soft hover:text-brand transition">Cửa nhôm xingfa 1 cánh</a></li>
              <li><a href="#san-pham-xingfa" onclick="filterProductsByKeyword('2 cánh')" class="block px-4 py-2 text-xs font-medium hover:bg-brand-soft hover:text-brand transition">Cửa nhôm xingfa 2 cánh</a></li>
              <li><a href="#san-pham-xingfa" onclick="filterProductsByKeyword('3 cánh')" class="block px-4 py-2 text-xs font-medium hover:bg-brand-soft hover:text-brand transition">Cửa nhôm xingfa 3 cánh</a></li>
              <li><a href="#san-pham-xingfa" onclick="filterProductsByKeyword('4 cánh')" class="block px-4 py-2 text-xs font-medium hover:bg-brand-soft hover:text-brand transition">Cửa nhôm xingfa 4 cánh</a></li>
              <li><a href="#san-pham-xingfa" onclick="filterProductsByKeyword('Xếp Trượt')" class="block px-4 py-2 text-xs font-medium hover:bg-brand-soft hover:text-brand transition">Cửa nhôm xingfa 5 cánh</a></li>
            </ul>
          </li>

          <li class="desktop-nav-item">
            <a href="#danh-muc-san-pham" class="block px-2.5 xl:px-3.5 py-2.5 text-[12px] xl:text-[13px] font-semibold uppercase tracking-tight hover:bg-brand-light hover:text-accent-light transition">
              Cửa kính cường lực
            </a>
          </li>

          <!-- Dropdown: Sản phẩm -->
          <li class="desktop-nav-item relative group">
            <a href="#danh-muc-san-pham" class="flex items-center gap-1 px-2.5 xl:px-3.5 py-2.5 text-[12px] xl:text-[13px] font-semibold uppercase tracking-tight hover:bg-brand-light hover:text-accent-light transition">
              <span>Sản phẩm</span>
              <svg class="w-3.5 h-3.5 opacity-80" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 9l-7 7-7-7"/></svg>
            </a>
            <ul class="desktop-nav-dropdown absolute left-0 top-full w-56 bg-white text-slate-700 rounded-b-lg shadow-xl border border-slate-200 py-1.5 z-50">
              <li><a href="#san-pham-xingfa" class="block px-4 py-2 text-xs font-medium hover:bg-brand-soft hover:text-brand transition">Cửa nhôm xingfa</a></li>
              <li><a href="#danh-muc-san-pham" class="block px-4 py-2 text-xs font-medium hover:bg-brand-soft hover:text-brand transition">Cửa nhựa lõi thép</a></li>
              <li><a href="#danh-muc-san-pham" class="block px-4 py-2 text-xs font-medium hover:bg-brand-soft hover:text-brand transition">Cửa kính tự động</a></li>
              <li><a href="#danh-muc-san-pham" class="block px-4 py-2 text-xs font-medium hover:bg-brand-soft hover:text-brand transition">Cầu thang kính</a></li>
              <li><a href="#danh-muc-san-pham" class="block px-4 py-2 text-xs font-medium hover:bg-brand-soft hover:text-brand transition">Kính ốp bếp</a></li>
              <li><a href="#danh-muc-san-pham" class="block px-4 py-2 text-xs font-medium hover:bg-brand-soft hover:text-brand transition">Phòng tắm kính</a></li>
            </ul>
          </li>

          <li class="desktop-nav-item">
            <a href="#cong-trinh" class="block px-2.5 xl:px-3.5 py-2.5 text-[12px] xl:text-[13px] font-semibold uppercase tracking-tight hover:bg-brand-light hover:text-accent-light transition">
              Công trình
            </a>
          </li>
          <li class="desktop-nav-item">
            <a href="#bao-gia" class="block px-2.5 xl:px-3.5 py-2.5 text-[12px] xl:text-[13px] font-semibold uppercase tracking-tight hover:bg-brand-light hover:text-accent-light transition">
              Báo giá
            </a>
          </li>
          <li class="desktop-nav-item">
            <a href="#tin-tuc" class="block px-2.5 xl:px-3.5 py-2.5 text-[12px] xl:text-[13px] font-semibold uppercase tracking-tight hover:bg-brand-light hover:text-accent-light transition">
              Tin tức
            </a>
          </li>
          <li class="desktop-nav-item">
            <a href="#lien-he" class="block px-2.5 xl:px-3.5 py-2.5 text-[12px] xl:text-[13px] font-semibold uppercase tracking-tight hover:bg-brand-light hover:text-accent-light transition">
              Liên hệ
            </a>
          </li>
        </ul>
      </div>
    </nav>
  </header>

  <!-- Mobile Drawer Navigation -->
  <div id="mobile-drawer" class="fixed inset-0 z-50 hidden">
    <div id="mobile-drawer-backdrop" class="absolute inset-0 bg-slate-900/60 backdrop-blur-xs"></div>
    <aside class="relative w-[84%] max-w-xs h-full bg-white shadow-2xl flex flex-col overflow-y-auto">
      <div class="bg-brand text-white px-4 py-3.5 flex items-center justify-between">
        <div class="font-bold text-sm uppercase tracking-wide">Nhôm Kính Văn Tới</div>
        <button id="mobile-menu-close" type="button" aria-label="Đóng menu" class="p-1.5 rounded-lg bg-white/15 hover:bg-white/25 transition">
          <svg class="w-5 h-5" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M6 18L18 6M6 6l12 12"/></svg>
        </button>
      </div>

      <!-- Tìm kiếm mobile -->
      <div class="p-3 border-b border-slate-100">
        <div class="relative">
          <input id="mobile-search-input" type="text" placeholder="Tìm sản phẩm..." class="w-full bg-slate-50 border border-slate-200 rounded-lg pl-3 pr-9 py-2 text-xs focus:outline-none focus:border-brand" />
          <button id="mobile-search-btn" type="button" class="absolute right-2 top-1/2 -translate-y-1/2 text-brand p-1">
            <svg class="w-4 h-4" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M21 21l-6-6m2-5a7 7 0 11-14 0 7 7 0 0114 0z"/></svg>
          </button>
        </div>
      </div>

      <ul class="divide-y divide-slate-100 text-sm font-medium text-slate-700 flex-1">
        <li><a href="#trang-chu" class="mobile-nav-link block px-4 py-3 hover:bg-brand-soft hover:text-brand">Trang chủ</a></li>
        <li><a href="#gioi-thieu" class="mobile-nav-link block px-4 py-3 hover:bg-brand-soft hover:text-brand">Giới thiệu</a></li>

        <!-- Accordion: Cửa nhôm xingfa -->
        <li>
          <div class="flex items-center justify-between">
            <a href="#san-pham-xingfa" class="mobile-nav-link flex-1 px-4 py-3 hover:text-brand">Cửa nhôm xingfa</a>
            <button type="button" onclick="toggleMobileSub('sub-xingfa', this)" class="px-4 py-3 text-slate-500 hover:text-brand" aria-label="Mở rộng Cửa nhôm xingfa">
              <svg class="w-4 h-4 transition-transform duration-200" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 9l-7 7-7-7"/></svg>
            </button>
          </div>
          <ul id="sub-xingfa" class="hidden bg-slate-50 pl-6 pr-4 py-1 text-xs space-y-1 border-t border-slate-100">
            <li><a href="#san-pham-xingfa" onclick="filterProductsByKeyword('1 cánh')" class="mobile-nav-link block py-2 text-slate-600 hover:text-brand">+ Cửa nhôm xingfa 1 cánh</a></li>
            <li><a href="#san-pham-xingfa" onclick="filterProductsByKeyword('2 cánh')" class="mobile-nav-link block py-2 text-slate-600 hover:text-brand">+ Cửa nhôm xingfa 2 cánh</a></li>
            <li><a href="#san-pham-xingfa" onclick="filterProductsByKeyword('3 cánh')" class="mobile-nav-link block py-2 text-slate-600 hover:text-brand">+ Cửa nhôm xingfa 3 cánh</a></li>
            <li><a href="#san-pham-xingfa" onclick="filterProductsByKeyword('4 cánh')" class="mobile-nav-link block py-2 text-slate-600 hover:text-brand">+ Cửa nhôm xingfa 4 cánh</a></li>
            <li><a href="#san-pham-xingfa" onclick="filterProductsByKeyword('Xếp Trượt')" class="mobile-nav-link block py-2 text-slate-600 hover:text-brand">+ Cửa nhôm xingfa 5 cánh</a></li>
          </ul>
        </li>

        <li><a href="#danh-muc-san-pham" class="mobile-nav-link block px-4 py-3 hover:bg-brand-soft hover:text-brand">Cửa kính cường lực</a></li>

        <!-- Accordion: Sản phẩm -->
        <li>
          <div class="flex items-center justify-between">
            <a href="#danh-muc-san-pham" class="mobile-nav-link flex-1 px-4 py-3 hover:text-brand">Sản phẩm</a>
            <button type="button" onclick="toggleMobileSub('sub-sanpham', this)" class="px-4 py-3 text-slate-500 hover:text-brand" aria-label="Mở rộng Sản phẩm">
              <svg class="w-4 h-4 transition-transform duration-200" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 9l-7 7-7-7"/></svg>
            </button>
          </div>
          <ul id="sub-sanpham" class="hidden bg-slate-50 pl-6 pr-4 py-1 text-xs space-y-1 border-t border-slate-100">
            <li><a href="#san-pham-xingfa" class="mobile-nav-link block py-2 text-slate-600 hover:text-brand">+ Cửa nhôm xingfa</a></li>
            <li><a href="#danh-muc-san-pham" class="mobile-nav-link block py-2 text-slate-600 hover:text-brand">+ Cửa nhựa lõi thép</a></li>
            <li><a href="#danh-muc-san-pham" class="mobile-nav-link block py-2 text-slate-600 hover:text-brand">+ Cửa kính tự động</a></li>
            <li><a href="#danh-muc-san-pham" class="mobile-nav-link block py-2 text-slate-600 hover:text-brand">+ Cầu thang kính</a></li>
            <li><a href="#danh-muc-san-pham" class="mobile-nav-link block py-2 text-slate-600 hover:text-brand">+ Kính ốp bếp</a></li>
            <li><a href="#danh-muc-san-pham" class="mobile-nav-link block py-2 text-slate-600 hover:text-brand">+ Phòng tắm kính</a></li>
          </ul>
        </li>

        <li><a href="#cong-trinh" class="mobile-nav-link block px-4 py-3 hover:bg-brand-soft hover:text-brand">Công trình</a></li>
        <li><a href="#bao-gia" class="mobile-nav-link block px-4 py-3 hover:bg-brand-soft hover:text-brand">Báo giá</a></li>
        <li><a href="#tin-tuc" class="mobile-nav-link block px-4 py-3 hover:bg-brand-soft hover:text-brand">Tin tức</a></li>
        <li><a href="#lien-he" class="mobile-nav-link block px-4 py-3 hover:bg-brand-soft hover:text-brand">Liên hệ</a></li>
      </ul>

      <div class="p-4 bg-brand-soft border-t border-slate-200 text-xs text-slate-600 space-y-1">
        <div class="font-bold text-brand">Hotline tư vấn: 0905.579.197</div>
        <div>Địa chỉ: TP. Đà Nẵng</div>
      </div>
    </aside>
  </div>

  <!-- ===================================================================== -->
  <!-- UX BUILDER SECTION: 2 BANNER TỰ TRƯỢT CHUYÊN NGHIỆP KÍCH THƯỚC BẰNG NHAU -->
  <!-- Hình ảnh & chữ nằm trọn trong banner, cách xa viền, không mất chữ mobile/PC -->
  <!-- ===================================================================== -->
  <section class="py-3 sm:py-4 bg-slate-50 border-b border-slate-200">
    <div class="vt-container">
      <div id="hero-slider" class="relative rounded-2xl overflow-hidden shadow-md bg-brand-dark">
        <div class="hero-slider-grid">

          <!-- BANNER 1 -->
          <div class="hero-slide is-active bg-gradient-to-br from-brand-dark via-brand to-[#145894] text-white">
            <div class="px-6 py-8 sm:px-12 sm:py-11 md:px-14 md:py-12 lg:px-16 lg:py-14 grid grid-cols-1 lg:grid-cols-12 gap-6 lg:gap-8 items-center h-full">
              <!-- Nội dung chữ cách xa viền ảnh banner -->
              <div class="lg:col-span-7 space-y-3 sm:space-y-4">
                <div class="text-[11px] sm:text-xs font-semibold uppercase tracking-widest text-accent-light">
                  Nhôm Kính Văn Tới • TP. Đà Nẵng
                </div>
                <h1 class="text-xl sm:text-3xl lg:text-4xl font-extrabold leading-snug text-white">
                  Cửa Nhôm Xingfa Nhập Khẩu Chính Hãng Tại Đà Nẵng
                </h1>
                <p class="text-xs sm:text-sm md:text-base text-slate-200 leading-relaxed max-w-xl">
                  Thiết kế, gia công và thi công trọn gói cửa nhôm Xingfa tem đỏ, phụ kiện Kinlong đồng bộ. Khảo sát tận nơi miễn phí, bảo hành uy tín dài hạn.
                </p>
                <div class="pt-1 flex flex-wrap items-center gap-3">
                  <a href="#form-bao-gia" class="inline-flex items-center justify-center px-4 py-2.5 sm:px-5 sm:py-2.5 rounded-lg bg-accent hover:bg-accent-dark text-white text-xs sm:text-sm font-bold shadow transition">
                    Nhận Báo Giá Ngay
                  </a>
                  <a href="#san-pham-xingfa" class="inline-flex items-center justify-center px-4 py-2.5 sm:px-5 sm:py-2.5 rounded-lg bg-white/15 hover:bg-white/25 border border-white/30 text-white text-xs sm:text-sm font-semibold transition">
                    Xem Mẫu Cửa
                  </a>
                </div>
              </div>
              <!-- Khung hình ảnh sản phẩm nằm gọn bên trong banner -->
              <div class="lg:col-span-5">
                <div class="rounded-xl overflow-hidden border-2 border-white/20 shadow-lg bg-white/10 aspect-[16/10]">
                  <img
                    data-drive-id="1lxzMKWX3e_HJn7UELFZDOURuxh-NYZg-"
                    alt="Cửa đi quay mở 4 cánh nhôm Xingfa Văn Tới"
                    class="drive-img w-full h-full object-cover"
                  />
                </div>
              </div>
            </div>
          </div>

          <!-- BANNER 2 -->
          <div class="hero-slide bg-gradient-to-br from-[#082B4B] via-[#0F497C] to-[#0B3C68] text-white">
            <div class="px-6 py-8 sm:px-12 sm:py-11 md:px-14 md:py-12 lg:px-16 lg:py-14 grid grid-cols-1 lg:grid-cols-12 gap-6 lg:gap-8 items-center h-full">
              <!-- Nội dung chữ cách xa viền ảnh banner -->
              <div class="lg:col-span-7 space-y-3 sm:space-y-4">
                <div class="text-[11px] sm:text-xs font-semibold uppercase tracking-widest text-accent-light">
                  Thi Công Chuyên Nghiệp • Giá Tận Xưởng
                </div>
                <h2 class="text-xl sm:text-3xl lg:text-4xl font-extrabold leading-snug text-white">
                  Cửa Kính Cường Lực, Cầu Thang & Phòng Tắm Kính
                </h2>
                <p class="text-xs sm:text-sm md:text-base text-slate-200 leading-relaxed max-w-xl">
                  Giải pháp không gian hiện đại cho nhà phố, biệt thự, khách sạn & resort tại Đà Nẵng. Kính cường lực đạt chuẩn an toàn, thi công đúng tiến độ.
                </p>
                <div class="pt-1 flex flex-wrap items-center gap-3">
                  <a href="#cong-trinh" class="inline-flex items-center justify-center px-4 py-2.5 sm:px-5 sm:py-2.5 rounded-lg bg-accent hover:bg-accent-dark text-white text-xs sm:text-sm font-bold shadow transition">
                    Xem Công Trình Thực Tế
                  </a>
                  <a href="tel:0905579197" class="inline-flex items-center justify-center px-4 py-2.5 sm:px-5 sm:py-2.5 rounded-lg bg-white/15 hover:bg-white/25 border border-white/30 text-white text-xs sm:text-sm font-semibold transition">
                    Hotline: 0905.579.197
                  </a>
                </div>
              </div>
              <!-- Khung hình ảnh công trình nằm gọn bên trong banner -->
              <div class="lg:col-span-5">
                <div class="rounded-xl overflow-hidden border-2 border-white/20 shadow-lg bg-white/10 aspect-[16/10]">
                  <img
                    data-drive-id="1MmAfsyp3s3YCaEMymrkk8TZbD38jCsAQ"
                    alt="Dự án thi công nhôm kính cao cấp tại Đà Nẵng"
                    class="drive-img w-full h-full object-cover"
                  />
                </div>
              </div>
            </div>
          </div>

        </div>

        <!-- Nút điều hướng slider trái/phải gọn sát mép không đè chữ -->
        <button id="hero-prev" type="button" aria-label="Banner trước" class="hidden sm:flex absolute left-2.5 top-1/2 -translate-y-1/2 z-10 w-8 h-8 rounded-full bg-black/30 hover:bg-black/55 text-white items-center justify-center transition">
          <svg class="w-4 h-4" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2.5" d="M15 19l-7-7 7-7"/></svg>
        </button>
        <button id="hero-next" type="button" aria-label="Banner tiếp theo" class="hidden sm:flex absolute right-2.5 top-1/2 -translate-y-1/2 z-10 w-8 h-8 rounded-full bg-black/30 hover:bg-black/55 text-white items-center justify-center transition">
          <svg class="w-4 h-4" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2.5" d="M9 5l7 7-7 7"/></svg>
        </button>

        <!-- Chấm tròn chỉ báo slide -->
        <div class="absolute bottom-2.5 left-1/2 -translate-x-1/2 z-10 flex items-center gap-2">
          <button type="button" data-slide-dot="0" aria-label="Slide 1" class="hero-dot w-6 h-2 rounded-full bg-accent-light transition-all"></button>
          <button type="button" data-slide-dot="1" aria-label="Slide 2" class="hero-dot w-2 h-2 rounded-full bg-white/50 hover:bg-white transition-all"></button>
        </div>
      </div>
    </div>
  </section>

  <!-- ===================================================================== -->
  <!-- UX BUILDER SECTION: DANH MỤC SẢN PHẨM NỔI BẬT (THEO MẪU NGOCHANWINDOW) -->
  <!-- ===================================================================== -->
  <section id="danh-muc-san-pham" class="py-10 sm:py-12 bg-white">
    <div class="vt-container">
      <div class="text-center mb-7">
        <h2 class="flatsome-heading text-lg sm:text-2xl font-extrabold uppercase text-brand tracking-tight">
          Danh Mục Sản Phẩm Nổi Bật
        </h2>
        <p class="text-xs sm:text-sm text-slate-500 mt-2.5">
          Đa dạng giải pháp nhôm kính kiến trúc cho nhà ở, văn phòng và khách sạn tại TP. Đà Nẵng
        </p>
      </div>

      <!-- Grid 2 cột trên điện thoại, 3 cột trên máy tính -->
      <div id="category-grid" class="grid grid-cols-2 md:grid-cols-3 gap-3 sm:gap-5">
        <!-- Render tự động bằng JS từ dữ liệu ảnh Drive -->
      </div>
    </div>
  </section>

  <!-- ===================================================================== -->
  <!-- UX BUILDER SECTION: SẢN PHẨM CỬA NHÔM XINGFA (2 CỘT MOBILE, GIÁ & -%) -->
  <!-- ===================================================================== -->
  <section id="san-pham-xingfa" class="py-10 sm:py-12 bg-slate-50 border-y border-slate-200/80">
    <div class="vt-container">
      <div class="flex flex-col md:flex-row md:items-end justify-between gap-4 mb-7">
        <div class="text-center md:text-left">
          <h2 class="flatsome-heading md:flatsome-heading-left text-lg sm:text-2xl font-extrabold uppercase text-brand tracking-tight">
            Cửa Nhôm Xingfa Bán Chạy
          </h2>
          <p class="text-xs sm:text-sm text-slate-500 mt-2.5">
            Giá gốc tại xưởng gia công Nhôm Kính Văn Tới — Phụ kiện đồng bộ chính hãng
          </p>
        </div>

        <!-- Bộ lọc nhanh đơn giản -->
        <div class="flex flex-wrap items-center justify-center md:justify-end gap-1.5" id="product-filter-bar">
          <button type="button" data-filter="all" class="product-filter-btn px-3 py-1.5 rounded-lg text-xs font-semibold bg-brand text-white transition">Tất cả</button>
          <button type="button" data-filter="1 cánh" class="product-filter-btn px-3 py-1.5 rounded-lg text-xs font-semibold bg-white border border-slate-200 text-slate-700 hover:border-brand hover:text-brand transition">1 cánh</button>
          <button type="button" data-filter="2 cánh" class="product-filter-btn px-3 py-1.5 rounded-lg text-xs font-semibold bg-white border border-slate-200 text-slate-700 hover:border-brand hover:text-brand transition">2 cánh</button>
          <button type="button" data-filter="3 cánh" class="product-filter-btn px-3 py-1.5 rounded-lg text-xs font-semibold bg-white border border-slate-200 text-slate-700 hover:border-brand hover:text-brand transition">3 cánh</button>
          <button type="button" data-filter="4 cánh" class="product-filter-btn px-3 py-1.5 rounded-lg text-xs font-semibold bg-white border border-slate-200 text-slate-700 hover:border-brand hover:text-brand transition">4 cánh</button>
          <button type="button" data-filter="Xếp Trượt" class="product-filter-btn px-3 py-1.5 rounded-lg text-xs font-semibold bg-white border border-slate-200 text-slate-700 hover:border-brand hover:text-brand transition">Xếp trượt</button>
        </div>
      </div>

      <!-- Grid sản phẩm: 2 cột trên điện thoại, 3 cột trên máy tính -->
      <div id="product-grid" class="grid grid-cols-2 md:grid-cols-3 gap-3 sm:gap-5">
        <!-- Render tự động bằng JS -->
      </div>
    </div>
  </section>

  <!-- ===================================================================== -->
  <!-- UX BUILDER SECTION: GIỚI THIỆU & CHỈ SỐ NĂNG LỰC (FLATSOME STYLE)     -->
  <!-- ===================================================================== -->
  <section id="gioi-thieu" class="py-10 sm:py-12 bg-white">
    <div class="vt-container">
      <div class="grid grid-cols-1 lg:grid-cols-12 gap-6 lg:gap-10 items-center">
        <div class="lg:col-span-7 space-y-4">
          <h2 class="flatsome-heading flatsome-heading-left text-lg sm:text-2xl font-extrabold uppercase text-brand tracking-tight">
            Nhôm Kính Văn Tới — Đà Nẵng
          </h2>
          <p class="text-sm text-slate-600 leading-relaxed">
            <strong>Nhôm Kính Văn Tới</strong> là đơn vị uy tín hàng đầu chuyên tư vấn thiết kế, sản xuất và thi công lắp đặt các hạng mục nhôm kính cao cấp tại TP. Đà Nẵng và khu vực Miền Trung. Với phương châm <em>“Chất lượng tạo dựng niềm tin — Cửa đẹp cho mọi công trình”</em>, chúng tôi mang đến không gian hiện đại, cách âm, cách nhiệt và bền vững theo thời gian.
          </p>
          <p class="text-sm text-slate-600 leading-relaxed">
            Các dòng sản phẩm chủ lực bao gồm: <strong>Cửa nhôm Xingfa nhập khẩu tem đỏ</strong> (hệ 55, 63, 65, 93), <strong>Cửa kính cường lực</strong>, <strong>Cửa nhựa lõi thép</strong>, <strong>Cửa kính tự động</strong>, <strong>Cầu thang kính</strong>, <strong>Kính ốp bếp</strong> và <strong>Phòng tắm kính</strong>.
          </p>

          <!-- Bảng cam kết dịch vụ (như web mẫu) -->
          <div class="rounded-xl border border-slate-200 overflow-hidden text-xs sm:text-sm">
            <div class="grid grid-cols-2 bg-brand text-white font-semibold px-4 py-2.5">
              <div>Hạng mục cam kết</div>
              <div>Chính sách tại Văn Tới</div>
            </div>
            <div class="divide-y divide-slate-200 bg-white">
              <div class="grid grid-cols-2 px-4 py-2.5">
                <div class="font-medium text-slate-700">Hotline tư vấn 24/7</div>
                <div class="font-bold text-brand">0905.579.197</div>
              </div>
              <div class="grid grid-cols-2 px-4 py-2.5 bg-slate-50/70">
                <div class="font-medium text-slate-700">Khảo sát & vận chuyển</div>
                <div class="text-slate-700">Miễn phí nội thành Đà Nẵng</div>
              </div>
              <div class="grid grid-cols-2 px-4 py-2.5">
                <div class="font-medium text-slate-700">Chính sách ưu đãi</div>
                <div class="text-accent-dark font-semibold">Chiết khấu trực tiếp theo khối lượng</div>
              </div>
              <div class="grid grid-cols-2 px-4 py-2.5 bg-slate-50/70">
                <div class="font-medium text-slate-700">Bảo hành chính hãng</div>
                <div class="text-slate-700">Lên đến 5 năm thanh nhôm & 2 năm phụ kiện</div>
              </div>
            </div>
          </div>
        </div>

        <!-- Khối 4 số liệu thống kê Flatsome -->
        <div class="lg:col-span-5">
          <div class="grid grid-cols-2 gap-3 sm:gap-4">
            <div class="rounded-xl bg-brand-soft border border-brand/10 p-5 text-center">
              <div class="text-2xl sm:text-3xl font-extrabold text-brand">150+</div>
              <div class="text-xs sm:text-sm font-medium text-slate-600 mt-1">Dự án hoàn thành</div>
            </div>
            <div class="rounded-xl bg-amber-50 border border-accent/20 p-5 text-center">
              <div class="text-2xl sm:text-3xl font-extrabold text-accent-dark">50+</div>
              <div class="text-xs sm:text-sm font-medium text-slate-600 mt-1">Kỹ thuật viên lành nghề</div>
            </div>
            <div class="rounded-xl bg-amber-50 border border-accent/20 p-5 text-center">
              <div class="text-2xl sm:text-3xl font-extrabold text-accent-dark">100+</div>
              <div class="text-xs sm:text-sm font-medium text-slate-600 mt-1">Mẫu sản phẩm chuẩn</div>
            </div>
            <div class="rounded-xl bg-brand-soft border border-brand/10 p-5 text-center">
              <div class="text-2xl sm:text-3xl font-extrabold text-brand">100%</div>
              <div class="text-xs sm:text-sm font-medium text-slate-600 mt-1">Khách hàng hài lòng</div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- ===================================================================== -->
  <!-- UX BUILDER SECTION: CÁC DỰ ÁN CÔNG TRÌNH NỔI BẬT TẠI ĐÀ NẴNG          -->
  <!-- ===================================================================== -->
  <section id="cong-trinh" class="py-10 sm:py-12 bg-slate-50 border-y border-slate-200/80">
    <div class="vt-container">
      <div class="text-center mb-7">
        <h2 class="flatsome-heading text-lg sm:text-2xl font-extrabold uppercase text-brand tracking-tight">
          Các Dự Án Nổi Bật Tại Đà Nẵng
        </h2>
        <p class="text-xs sm:text-sm text-slate-500 mt-2.5">
          Những công trình khách sạn, resort và nhà phố tiêu biểu được thi công bởi đội ngũ kỹ thuật của chúng tôi
        </p>
      </div>

      <!-- 6 dự án thực tế tại Đà Nẵng -->
      <div id="project-grid" class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-4 sm:gap-5">
        <!-- Render tự động bằng JS -->
      </div>
    </div>
  </section>

  <!-- ===================================================================== -->
  <!-- UX BUILDER SECTION: BẢNG BÁO GIÁ THAM KHẢO & FORM YÊU CẦU BÁO GIÁ     -->
  <!-- ===================================================================== -->
  <section id="bao-gia" class="py-10 sm:py-12 bg-white">
    <div class="vt-container">
      <div class="text-center mb-8">
        <h2 class="flatsome-heading text-lg sm:text-2xl font-extrabold uppercase text-brand tracking-tight">
          Báo Giá & Đăng Ký Tư Vấn Trực Tuyến
        </h2>
        <p class="text-xs sm:text-sm text-slate-500 mt-2.5">
          Bảng giá tham khảo minh bạch — Gửi yêu cầu để nhận báo giá chi tiết theo kích thước thực tế
        </p>
      </div>

      <div class="grid grid-cols-1 lg:grid-cols-12 gap-6 items-start">
        <!-- Cột trái: Bảng báo giá cửa nhôm Xingfa tham khảo -->
        <div class="lg:col-span-7 rounded-xl border border-slate-200 overflow-hidden shadow-xs">
          <div class="bg-brand text-white px-4 py-3 font-bold text-xs sm:text-sm uppercase tracking-wide flex items-center justify-between">
            <span>Bảng Báo Giá Cửa Nhôm Xingfa Đà Nẵng</span>
            <span class="text-accent-light font-semibold">Đơn vị: VNĐ/m²</span>
          </div>
          <div class="overflow-x-auto">
            <table class="w-full text-left border-collapse text-xs sm:text-sm">
              <thead>
                <tr class="bg-slate-100 text-slate-700 border-b border-slate-200">
                  <th class="py-2.5 px-3 font-bold">Hạng mục sản phẩm</th>
                  <th class="py-2.5 px-3 font-bold">Hệ nhôm</th>
                  <th class="py-2.5 px-3 font-bold text-right">Đơn giá ưu đãi</th>
                </tr>
              </thead>
              <tbody class="divide-y divide-slate-200 bg-white">
                <tr class="hover:bg-slate-50">
                  <td class="py-2.5 px-3 font-medium text-slate-800">Cửa sổ mở hất / mở quay nhôm Xingfa</td>
                  <td class="py-2.5 px-3 text-slate-600">Hệ 55 (1.4mm)</td>
                  <td class="py-2.5 px-3 text-right font-bold text-accent-dark">1.890.000 ₫</td>
                </tr>
                <tr class="hover:bg-slate-50">
                  <td class="py-2.5 px-3 font-medium text-slate-800">Cửa đi quay mở 1 cánh nhôm Xingfa</td>
                  <td class="py-2.5 px-3 text-slate-600">Hệ 55 (2.0mm)</td>
                  <td class="py-2.5 px-3 text-right font-bold text-accent-dark">2.100.000 ₫</td>
                </tr>
                <tr class="hover:bg-slate-50">
                  <td class="py-2.5 px-3 font-medium text-slate-800">Cửa đi quay mở 2 cánh nhôm Xingfa</td>
                  <td class="py-2.5 px-3 text-slate-600">Hệ 55 (2.0mm)</td>
                  <td class="py-2.5 px-3 text-right font-bold text-accent-dark">2.100.000 ₫</td>
                </tr>
                <tr class="hover:bg-slate-50">
                  <td class="py-2.5 px-3 font-medium text-slate-800">Cửa đi quay mở 3 cánh nhôm Xingfa</td>
                  <td class="py-2.5 px-3 text-slate-600">Hệ 55 (2.0mm)</td>
                  <td class="py-2.5 px-3 text-right font-bold text-accent-dark">2.150.000 ₫</td>
                </tr>
                <tr class="hover:bg-slate-50">
                  <td class="py-2.5 px-3 font-medium text-slate-800">Cửa đi quay mở 4 cánh nhôm Xingfa</td>
                  <td class="py-2.5 px-3 text-slate-600">Hệ 55 (2.0mm)</td>
                  <td class="py-2.5 px-3 text-right font-bold text-accent-dark">2.200.000 ₫</td>
                </tr>
                <tr class="hover:bg-slate-50">
                  <td class="py-2.5 px-3 font-medium text-slate-800">Cửa đi xếp trượt nhôm Xingfa</td>
                  <td class="py-2.5 px-3 text-slate-600">Hệ 63 (2.0mm)</td>
                  <td class="py-2.5 px-3 text-right font-bold text-accent-dark">2.350.000 ₫</td>
                </tr>
                <tr class="hover:bg-slate-50">
                  <td class="py-2.5 px-3 font-medium text-slate-800">Cửa kính cường lực 10mm - 12mm</td>
                  <td class="py-2.5 px-3 text-slate-600">Kính Việt Nhật</td>
                  <td class="py-2.5 px-3 text-right font-bold text-accent-dark">750.000 ₫</td>
                </tr>
              </tbody>
            </table>
          </div>
          <div class="px-4 py-2.5 bg-brand-soft text-[11px] sm:text-xs text-slate-600">
            * Đơn giá trên đã bao gồm kính an toàn tiêu chuẩn, gioăng EPDM, keo silicon và lắp đặt hoàn thiện tại TP. Đà Nẵng.
          </div>
        </div>

        <!-- Cột phải: Form yêu cầu và báo giá ngay trang chủ -->
        <div id="form-bao-gia" class="lg:col-span-5 rounded-xl border border-brand/20 bg-brand-soft/60 p-5 sm:p-6 shadow-xs">
          <h3 class="text-base sm:text-lg font-extrabold text-brand uppercase mb-1">
            Form Yêu Cầu & Nhận Báo Giá
          </h3>
          <p class="text-xs text-slate-600 mb-4">
            Để lại thông tin, kỹ thuật viên Nhôm Kính Văn Tới sẽ liên hệ tư vấn và gửi báo giá trong 15 phút.
          </p>

          <form id="quote-form" class="space-y-3">
            <div>
              <label for="q-name" class="block text-xs font-semibold text-slate-700 mb-1">Họ và tên *</label>
              <input id="q-name" type="text" required placeholder="Nhập họ tên của bạn" class="w-full rounded-lg border border-slate-300 bg-white px-3.5 py-2 text-sm focus:outline-none focus:border-brand focus:ring-2 focus:ring-brand/15" />
            </div>

            <div class="grid grid-cols-1 sm:grid-cols-2 gap-3">
              <div>
                <label for="q-phone" class="block text-xs font-semibold text-slate-700 mb-1">Số điện thoại / Zalo *</label>
                <input id="q-phone" type="tel" required placeholder="0905 xxx xxx" class="w-full rounded-lg border border-slate-300 bg-white px-3.5 py-2 text-sm focus:outline-none focus:border-brand focus:ring-2 focus:ring-brand/15" />
              </div>
              <div>
                <label for="q-category" class="block text-xs font-semibold text-slate-700 mb-1">Hạng mục quan tâm</label>
                <select id="q-category" class="w-full rounded-lg border border-slate-300 bg-white px-3 py-2 text-sm focus:outline-none focus:border-brand focus:ring-2 focus:ring-brand/15">
                  <option value="Cửa nhôm Xingfa">Cửa nhôm Xingfa</option>
                  <option value="Cửa kính cường lực">Cửa kính cường lực</option>
                  <option value="Cửa nhựa lõi thép">Cửa nhựa lõi thép</option>
                  <option value="Cửa kính tự động">Cửa kính tự động</option>
                  <option value="Cầu thang kính">Cầu thang kính</option>
                  <option value="Kính ốp bếp">Kính ốp bếp</option>
                  <option value="Phòng tắm kính">Phòng tắm kính</option>
                </select>
              </div>
            </div>

            <div>
              <label for="q-note" class="block text-xs font-semibold text-slate-700 mb-1">Kích thước dự kiến / Địa chỉ công trình</label>
              <textarea id="q-note" rows="3" placeholder="Ví dụ: Làm 2 bộ cửa đi 4 cánh nhôm Xingfa màu xám ghi tại quận Hải Châu, Đà Nẵng..." class="w-full rounded-lg border border-slate-300 bg-white px-3.5 py-2 text-sm focus:outline-none focus:border-brand focus:ring-2 focus:ring-brand/15"></textarea>
            </div>

            <button type="submit" class="w-full py-2.5 px-4 rounded-lg bg-brand hover:bg-brand-dark text-white font-bold text-sm shadow transition flex items-center justify-center gap-2">
              <svg class="w-4 h-4" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 19l9 2-9-18-9 18 9-2zm0 0v-8"/></svg>
              <span>Gửi Yêu Cầu Báo Giá Miễn Phí</span>
            </button>
          </form>
        </div>
      </div>
    </div>
  </section>

  <!-- ===================================================================== -->
  <!-- UX BUILDER SECTION: DANH MỤC CÁC BÀI VIẾT / TIN TỨC TRANG CHỦ         -->
  <!-- ===================================================================== -->
  <section id="tin-tuc" class="py-10 sm:py-12 bg-slate-50 border-y border-slate-200/80">
    <div class="vt-container">
      <div class="text-center mb-7">
        <h2 class="flatsome-heading text-lg sm:text-2xl font-extrabold uppercase text-brand tracking-tight">
          Tin Tức & Kinh Nghiệm Chọn Cửa
        </h2>
        <p class="text-xs sm:text-sm text-slate-500 mt-2.5">
          Chia sẻ kiến thức thực tế về cửa nhôm Xingfa, kính cường lực và bảo dưỡng cửa bền đẹp
        </p>
      </div>

      <div id="news-grid" class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-4 sm:gap-5">
        <!-- Render tự động bằng JS -->
      </div>
    </div>
  </section>

  <!-- ===================================================================== -->
  <!-- UX BUILDER SECTION: ĐỐI TÁC CỦA CHÚNG TÔI (6 ẢNH ĐỐI TÁC DRIVE)        -->
  <!-- ===================================================================== -->
  <section class="py-9 sm:py-10 bg-white border-b border-slate-200/80">
    <div class="vt-container">
      <div class="text-center mb-6">
        <h2 class="flatsome-heading text-base sm:text-xl font-extrabold uppercase text-brand tracking-tight">
          Đối Tác Của Chúng Tôi
        </h2>
      </div>
      <div id="partner-grid" class="grid grid-cols-3 md:grid-cols-6 gap-3 sm:gap-4 items-center">
        <!-- Render tự động 6 ảnh đối tác từ Google Drive -->
      </div>
    </div>
  </section>

  <!-- ===================================================================== -->
  <!-- UX BUILDER SECTION: GOOGLE MAP & FANPAGE FACEBOOK NGOÀI TRANG CHỦ      -->
  <!-- ===================================================================== -->
  <section id="lien-he" class="py-10 sm:py-12 bg-slate-50">
    <div class="vt-container">
      <div class="text-center mb-7">
        <h2 class="flatsome-heading text-lg sm:text-2xl font-extrabold uppercase text-brand tracking-tight">
          Bản Đồ Chỉ Đường & Fanpage Chính Thức
        </h2>
        <p class="text-xs sm:text-sm text-slate-500 mt-2.5">
          Kết nối trực tiếp với Nhôm Kính Văn Tới tại TP. Đà Nẵng để xem mẫu thực tế
        </p>
      </div>

      <div class="grid grid-cols-1 lg:grid-cols-12 gap-5 items-stretch">
        <!-- Bản đồ Google Map ngoài trang chủ -->
        <div class="lg:col-span-7 bg-white rounded-xl border border-slate-200 shadow-xs overflow-hidden flex flex-col">
          <div class="px-4 py-3 bg-brand text-white flex items-center justify-between gap-2">
            <div class="flex items-center gap-2 text-xs sm:text-sm font-bold">
              <svg class="w-4 h-4 text-accent-light shrink-0" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M17.657 16.657L13.414 20.9a1.998 1.998 0 01-2.827 0l-4.244-4.243a8 8 0 1111.314 0z"/><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M15 11a3 3 0 11-6 0 3 3 0 016 0z"/></svg>
              <span>Bản Đồ Google Map — TP. Đà Nẵng</span>
            </div>
            <a href="https://maps.google.com/?q=Da+Nang,Vietnam" target="_blank" rel="noopener noreferrer" class="text-[11px] font-semibold text-accent-light hover:underline shrink-0">
              Mở rộng bản đồ
            </a>
          </div>
          <div class="w-full flex-1 min-h-[280px] sm:min-h-[320px] bg-slate-100">
            <iframe
              title="Bản đồ Nhôm Kính Văn Tới - TP. Đà Nẵng"
              src="https://www.google.com/maps?q=Da+Nang,+Vietnam&output=embed"
              class="w-full h-full min-h-[280px] sm:min-h-[320px] border-0"
              loading="lazy"
              referrerpolicy="no-referrer-when-downgrade"
            ></iframe>
          </div>
        </div>

        <!-- Fanpage Facebook ngoài trang chủ -->
        <div class="lg:col-span-5 bg-white rounded-xl border border-slate-200 shadow-xs overflow-hidden flex flex-col">
          <div class="px-4 py-3 bg-[#1877F2] text-white flex items-center justify-between gap-2">
            <div class="flex items-center gap-2 text-xs sm:text-sm font-bold">
              <svg class="w-4 h-4 shrink-0" fill="currentColor" viewBox="0 0 24 24"><path d="M22.675 0h-21.35C.597 0 0 .597 0 1.326v21.348C0 23.403.597 24 1.326 24h11.495v-9.294H9.691v-3.622h3.13V8.413c0-3.1 1.893-4.788 4.659-4.788 1.325 0 2.463.099 2.795.143v3.24l-1.918.001c-1.504 0-1.795.715-1.795 1.763v2.313h3.587l-.467 3.622h-3.12V24h6.116C23.403 24 24 23.403 24 22.674V1.326C24 .597 23.403 0 22.675 0z"/></svg>
              <span>Fanpage Facebook Chính Thức</span>
            </div>
            <span class="text-[11px] opacity-90">Hoạt động 24/7</span>
          </div>

          <!-- Khung giao diện Fanpage Facebook chuẩn nhúng trang chủ -->
          <div class="p-4 flex-1 flex flex-col justify-between gap-4">
            <div class="rounded-lg border border-slate-200 overflow-hidden bg-slate-50">
              <!-- Ảnh bìa Fanpage -->
              <div class="relative h-32 bg-gradient-to-r from-brand-dark via-brand to-brand-light p-3.5 flex items-end">
                <div class="flex items-center gap-3">
                  <div class="w-12 h-12 rounded-lg bg-white p-1 shadow-md shrink-0 flex items-center justify-center">
                    <svg class="w-10 h-10" viewBox="0 0 64 64" fill="none" xmlns="http://www.w3.org/2000/svg">
                      <rect width="64" height="64" rx="10" fill="#0B3C68"/>
                      <rect x="6" y="6" width="52" height="52" rx="7" stroke="#E59A1A" stroke-width="2.5"/>
                      <path d="M15 18L24.5 46L34 18" stroke="#FFFFFF" stroke-width="4.2" stroke-linecap="round" stroke-linejoin="round"/>
                      <path d="M35.5 20H49.5" stroke="#F3A829" stroke-width="4.2" stroke-linecap="round"/>
                      <path d="M42.5 20V46" stroke="#F3A829" stroke-width="4.2" stroke-linecap="round"/>
                    </svg>
                  </div>
                  <div class="text-white leading-tight">
                    <div class="font-bold text-sm sm:text-base">Nhôm Kính Văn Tới - Đà Nẵng</div>
                    <div class="text-[11px] text-slate-200 mt-0.5">4.850 lượt thích • 5.120 người theo dõi</div>
                  </div>
                </div>
              </div>

              <!-- Nội dung bài ghim mới nhất trên Fanpage -->
              <div class="p-3.5 bg-white space-y-2.5 text-xs text-slate-600">
                <p class="leading-relaxed">
                  <strong>Nhôm Kính Văn Tới</strong> cập nhật liên tục hình ảnh công trình bàn giao thực tế tại TP. Đà Nẵng: Cửa nhôm Xingfa 1–5 cánh, cầu thang kính, phòng tắm kính, kính ốp bếp.
                </p>
                <div class="flex flex-wrap items-center gap-2 pt-1">
                  <a href="https://www.facebook.com/" target="_blank" rel="noopener noreferrer" class="flex-1 inline-flex items-center justify-center gap-1.5 px-3 py-2 rounded-lg bg-[#1877F2] hover:bg-[#1465D1] text-white font-semibold transition">
                    <svg class="w-3.5 h-3.5" fill="currentColor" viewBox="0 0 24 24"><path d="M14 9V5a3 3 0 00-3-3l-4 9v11h11.28a2 2 0 002-1.7l1.38-9a2 2 0 00-2-2.3H14zM7 22H4a2 2 0 01-2-2v-7a2 2 0 012-2h3"/></svg>
                    <span>Thích Trang</span>
                  </a>
                  <a href="https://zalo.me/0905579197" target="_blank" rel="noopener noreferrer" class="flex-1 inline-flex items-center justify-center gap-1.5 px-3 py-2 rounded-lg bg-slate-100 hover:bg-slate-200 text-slate-800 font-semibold transition">
                    <svg class="w-3.5 h-3.5 text-brand" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M8 10h.01M12 10h.01M16 10h.01M9 16H5a2 2 0 01-2-2V6a2 2 0 012-2h14a2 2 0 012 2v8a2 2 0 01-2 2h-5l-5 5v-5z"/></svg>
                    <span>Nhắn Tin Tư Vấn</span>
                  </a>
                </div>
              </div>
            </div>

            <!-- Thông tin liên hệ nhanh bên dưới -->
            <div class="rounded-lg bg-brand-soft p-3.5 text-xs space-y-1.5 text-slate-700 border border-brand/10">
              <div class="font-bold text-brand uppercase">Thông tin liên hệ trực tiếp</div>
              <div><strong>Địa chỉ:</strong> TP. Đà Nẵng</div>
              <div><strong>Hotline / Zalo:</strong> <a href="tel:0905579197" class="font-bold text-accent-dark hover:underline">0905.579.197</a></div>
              <div><strong>Website:</strong> <span class="font-semibold text-brand">nhomkinhvantoi.com</span></div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- ===================================================================== -->
  <!-- UX BUILDER SECTION: FOOTER 4 CỘT CHUẨN FLATSOME                       -->
  <!-- ===================================================================== -->
  <footer class="bg-brand-dark text-slate-300 pt-10 pb-6 border-t-4 border-accent">
    <div class="vt-container">
      <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-7 pb-8 border-b border-white/10">
        <!-- Cột 1: Giới thiệu & Liên hệ -->
        <div class="space-y-3">
          <div class="flex items-center gap-2.5">
            <svg class="w-9 h-9 shrink-0" viewBox="0 0 64 64" fill="none" xmlns="http://www.w3.org/2000/svg">
              <rect width="64" height="64" rx="12" fill="#145894"/>
              <rect x="6" y="6" width="52" height="52" rx="8" stroke="#E59A1A" stroke-width="2.5"/>
              <path d="M15 18L24.5 46L34 18" stroke="#FFFFFF" stroke-width="4.2" stroke-linecap="round" stroke-linejoin="round"/>
              <path d="M35.5 20H49.5" stroke="#F3A829" stroke-width="4.2" stroke-linecap="round"/>
              <path d="M42.5 20V46" stroke="#F3A829" stroke-width="4.2" stroke-linecap="round"/>
            </svg>
            <div>
              <div class="text-sm font-extrabold text-white uppercase">NHÔM KÍNH VĂN TỚI</div>
              <div class="text-[11px] text-accent-light">nhomkinhvantoi.com</div>
            </div>
          </div>
          <p class="text-xs leading-relaxed text-slate-300">
            Chuyên gia công & thi công cửa nhôm Xingfa nhập khẩu, cửa kính cường lực, cầu thang kính, phòng tắm kính, kính ốp bếp tại TP. Đà Nẵng.
          </p>
          <ul class="text-xs space-y-1.5">
            <li><strong class="text-white">Địa chỉ:</strong> TP. Đà Nẵng</li>
            <li><strong class="text-white">Hotline:</strong> <a href="tel:0905579197" class="text-accent-light font-bold hover:underline">0905.579.197</a></li>
            <li><strong class="text-white">Website:</strong> nhomkinhvantoi.com</li>
          </ul>
        </div>

        <!-- Cột 2: Cửa nhôm Xingfa -->
        <div>
          <h4 class="text-xs font-bold uppercase text-white tracking-wider mb-3 pb-1.5 border-b border-white/15">
            Cửa Nhôm Xingfa
          </h4>
          <ul class="space-y-2 text-xs">
            <li><a href="#san-pham-xingfa" onclick="filterProductsByKeyword('1 cánh')" class="hover:text-accent-light transition">Cửa nhôm xingfa 1 cánh</a></li>
            <li><a href="#san-pham-xingfa" onclick="filterProductsByKeyword('2 cánh')" class="hover:text-accent-light transition">Cửa nhôm xingfa 2 cánh</a></li>
            <li><a href="#san-pham-xingfa" onclick="filterProductsByKeyword('3 cánh')" class="hover:text-accent-light transition">Cửa nhôm xingfa 3 cánh</a></li>
            <li><a href="#san-pham-xingfa" onclick="filterProductsByKeyword('4 cánh')" class="hover:text-accent-light transition">Cửa nhôm xingfa 4 cánh</a></li>
            <li><a href="#san-pham-xingfa" onclick="filterProductsByKeyword('Xếp Trượt')" class="hover:text-accent-light transition">Cửa nhôm xingfa 5 cánh</a></li>
            <li><a href="#danh-muc-san-pham" class="hover:text-accent-light transition">Cửa kính cường lực</a></li>
          </ul>
        </div>

        <!-- Cột 3: Danh mục sản phẩm -->
        <div>
          <h4 class="text-xs font-bold uppercase text-white tracking-wider mb-3 pb-1.5 border-b border-white/15">
            Danh Mục Sản Phẩm
          </h4>
          <ul class="space-y-2 text-xs">
            <li><a href="#danh-muc-san-pham" class="hover:text-accent-light transition">Cửa nhôm xingfa</a></li>
            <li><a href="#danh-muc-san-pham" class="hover:text-accent-light transition">Cửa nhựa lõi thép</a></li>
            <li><a href="#danh-muc-san-pham" class="hover:text-accent-light transition">Cửa kính tự động</a></li>
            <li><a href="#danh-muc-san-pham" class="hover:text-accent-light transition">Cầu thang kính</a></li>
            <li><a href="#danh-muc-san-pham" class="hover:text-accent-light transition">Kính ốp bếp</a></li>
            <li><a href="#danh-muc-san-pham" class="hover:text-accent-light transition">Phòng tắm kính</a></li>
          </ul>
        </div>

        <!-- Cột 4: Liên kết nhanh -->
        <div>
          <h4 class="text-xs font-bold uppercase text-white tracking-wider mb-3 pb-1.5 border-b border-white/15">
            Hỗ Trợ Khách Hàng
          </h4>
          <ul class="space-y-2 text-xs">
            <li><a href="#gioi-thieu" class="hover:text-accent-light transition">Giới thiệu Nhôm Kính Văn Tới</a></li>
            <li><a href="#cong-trinh" class="hover:text-accent-light transition">Công trình đã thi công</a></li>
            <li><a href="#bao-gia" class="hover:text-accent-light transition">Bảng báo giá mới nhất</a></li>
            <li><a href="#tin-tuc" class="hover:text-accent-light transition">Tin tức & tư vấn kỹ thuật</a></li>
            <li><a href="#form-bao-gia" class="hover:text-accent-light transition">Đăng ký khảo sát miễn phí</a></li>
          </ul>
        </div>
      </div>

      <div class="pt-5 flex flex-col sm:flex-row items-center justify-between gap-2 text-xs text-slate-400 text-center sm:text-left">
        <div>Copyright © 2026 <strong>Nhôm Kính Văn Tới</strong> (nhomkinhvantoi.com). All rights reserved.</div>
        <div>Thiết kế tối ưu chuẩn Flatsome UX Builder • TP. Đà Nẵng</div>
      </div>
    </div>
  </footer>

  <!-- ===================================================================== -->
  <!-- CÁC NÚT LIÊN HỆ NỔI BẬT: ZALO, FACEBOOK, HOTLINE (TƯƠNG THÍCH MOBILE/PC) -->
  <!-- ===================================================================== -->
  <div class="fixed bottom-4 right-3 sm:bottom-6 sm:right-5 z-40 flex flex-col items-end gap-2.5">
    <!-- Nút Zalo -->
    <a
      href="https://zalo.me/0905579197"
      target="_blank"
      rel="noopener noreferrer"
      aria-label="Chat Zalo Nhôm Kính Văn Tới"
      class="group flex items-center gap-2 bg-[#0068FF] hover:bg-[#0055D4] text-white rounded-full shadow-lg p-2.5 sm:px-3.5 sm:py-2.5 transition"
    >
      <span class="w-6 h-6 rounded-full bg-white text-[#0068FF] font-extrabold text-[10px] flex items-center justify-center shrink-0">Zalo</span>
      <span class="hidden sm:inline text-xs font-bold pr-1">Chat Zalo</span>
    </a>

    <!-- Nút Facebook -->
    <a
      href="https://www.facebook.com/"
      target="_blank"
      rel="noopener noreferrer"
      aria-label="Fanpage Facebook Nhôm Kính Văn Tới"
      class="group flex items-center gap-2 bg-[#1877F2] hover:bg-[#1362C7] text-white rounded-full shadow-lg p-2.5 sm:px-3.5 sm:py-2.5 transition"
    >
      <svg class="w-6 h-6 shrink-0" fill="currentColor" viewBox="0 0 24 24"><path d="M22.675 0h-21.35C.597 0 0 .597 0 1.326v21.348C0 23.403.597 24 1.326 24h11.495v-9.294H9.691v-3.622h3.13V8.413c0-3.1 1.893-4.788 4.659-4.788 1.325 0 2.463.099 2.795.143v3.24l-1.918.001c-1.504 0-1.795.715-1.795 1.763v2.313h3.587l-.467 3.622h-3.12V24h6.116C23.403 24 24 23.403 24 22.674V1.326C24 .597 23.403 0 22.675 0z"/></svg>
      <span class="hidden sm:inline text-xs font-bold pr-1">Facebook</span>
    </a>

    <!-- Nút Hotline -->
    <a
      href="tel:0905579197"
      aria-label="Gọi Hotline 0905.579.197"
      class="pulse-hotline flex items-center gap-2 bg-accent hover:bg-accent-dark text-white rounded-full shadow-xl p-2.5 sm:px-4 sm:py-2.5 transition"
    >
      <svg class="w-6 h-6 shrink-0" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2.2" d="M3 5a2 2 0 012-2h3.28a1 1 0 01.948.684l1.498 4.493a1 1 0 01-.502 1.21l-2.257 1.13a11.042 11.042 0 005.516 5.516l1.13-2.257a1 1 0 011.21-.502l4.493 1.498a1 1 0 01.684.949V19a2 2 0 01-2 2h-1C9.716 21 3 14.284 3 6V5z"/></svg>
      <span class="hidden sm:inline text-xs font-extrabold tracking-wide">0905.579.197</span>
    </a>
  </div>

  <!-- ===================================================================== -->
  <!-- MODAL CHI TIẾT (XEM NHANH SẢN PHẨM / DỰ ÁN / BÀI VIẾT)                -->
  <!-- ===================================================================== -->
  <div id="detail-modal" class="fixed inset-0 z-50 hidden items-center justify-center p-4 bg-slate-900/70 backdrop-blur-xs">
    <div class="bg-white rounded-2xl max-w-2xl w-full max-h-[90vh] overflow-y-auto shadow-2xl border border-slate-200">
      <div class="sticky top-0 bg-white px-5 py-3.5 border-b border-slate-200 flex items-center justify-between gap-3 z-10">
        <h3 id="modal-title" class="text-sm sm:text-base font-extrabold text-brand">Chi tiết</h3>
        <button id="modal-close" type="button" class="p-1.5 rounded-lg bg-slate-100 hover:bg-slate-200 text-slate-600 transition" aria-label="Đóng">
          <svg class="w-5 h-5" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M6 18L18 6M6 6l12 12"/></svg>
        </button>
      </div>
      <div id="modal-body" class="p-5"></div>
    </div>
  </div>

  <!-- Thông báo Toast (Thay thế hoàn toàn cho alert) -->
  <div id="toast-box" class="fixed top-20 left-1/2 -translate-x-1/2 z-50 hidden max-w-md w-[90%] bg-brand-dark text-white px-4 py-3 rounded-xl shadow-2xl border border-accent/50 text-xs sm:text-sm font-medium text-center"></div>

  <!-- ===================================================================== -->
  <!-- JAVASCRIPT: DỮ LIỆU ẢNH GOOGLE DRIVE, SLIDER, BỘ LỌC & TƯƠNG TÁC      -->
  <!-- ===================================================================== -->
  <script>
    // Chuyển đổi Google Drive File ID sang URL hiển thị trực tiếp ổn định kèm fallback dự phòng
    function getDriveUrlPrimary(id) {
      return `https://lh3.googleusercontent.com/d/${id}=w1000`;
    }
    function getDriveUrlFallback(id) {
      return `https://drive.google.com/thumbnail?id=${id}&sz=w1000`;
    }
    function handleImgError(img, label) {
      const step = parseInt(img.dataset.errStep || '0', 10);
      const id = img.dataset.driveId;
      if (step === 0 && id) {
        img.dataset.errStep = '1';
        img.src = getDriveUrlFallback(id);
      } else {
        img.onerror = null;
        const safeText = encodeURIComponent(label || 'Nhôm Kính Văn Tới');
        img.src = `https://placehold.co/600x420/0B3C68/FFFFFF?text=${safeText}`;
      }
    }

    // 1. DỮ LIỆU 6 DANH MỤC SẢN PHẨM CHÍNH (ẢNH GOOGLE DRIVE ĐÚNG DANH MỤC)
    const CATEGORIES = [
      {
        name: 'Cửa Nhôm Xingfa',
        driveId: '1zRlHJBAneXS7EQ1jdT__hVRCTf2mzOiX',
        desc: 'Nhôm thanh định hình nhập khẩu tem đỏ, hệ 55, 63, 93.',
        target: '#san-pham-xingfa'
      },
      {
        name: 'Cửa Nhựa Lõi Thép',
        driveId: '1jiHBW-2MoWUHjQUicSe-rO6NlmfNuZNA',
        desc: 'Thanh nhựa uPVC lõi thép gia cường cách âm, cách nhiệt.',
        target: '#form-bao-gia'
      },
      {
        name: 'Cửa Kính Tự Động',
        driveId: '1PIFP1UCQs_FIaKCgGwcJWt-5wTnST9iJ',
        desc: 'Cảm biến mắt thần đóng mở êm ái cho showroom, khách sạn.',
        target: '#form-bao-gia'
      },
      {
        name: 'Cầu Thang Kính',
        driveId: '1FnuITlKMjk-xTxkIV96ABv43S1PG--Ul',
        desc: 'Kính cường lực 10mm - 12mm tay vịn gỗ hoặc inox 304.',
        target: '#form-bao-gia'
      },
      {
        name: 'Kính Ốp Bếp',
        driveId: '1ilanOshTrs9llnMXWl5iZ8DtgptJ0hCb',
        desc: 'Kính màu cường lực chịu nhiệt, dễ lau chùi, màu sắc sang trọng.',
        target: '#form-bao-gia'
      },
      {
        name: 'Phòng Tắm Kính',
        driveId: '1MhCILHQ5goD1cAPTt1hZsY_ajeOMs-qH',
        desc: 'Cabin vách kính tắm chống tràn nước, phụ kiện inox chống gỉ.',
        target: '#form-bao-gia'
      }
    ];

    // 2. DỮ LIỆU 6 SẢN PHẨM CỬA NHÔM XINGFA (GIÁ + GIẢM GIÁ % GÓC TRÊN BÊN TRÁI)
    const PRODUCTS = [
      {
        id: 'sp-1',
        name: 'Cửa đi quay mở 1 cánh nhôm xingfa',
        driveId: '1-0eBWGjPwzQ-C9c1Wjws9wt0gbsulkPm',
        oldPrice: '2.450.000 ₫',
        price: '2.100.000 ₫',
        discount: '-14%',
        specs: 'Nhôm Xingfa hệ 55 dày 2.0mm, kính an toàn 6.38mm hoặc kính cường lực 8mm, phụ kiện Kinlong đồng bộ.'
      },
      {
        id: 'sp-2',
        name: 'Cửa đi quay mở 2 cánh nhôm xingfa',
        driveId: '1h2r2rbPrEL7dgLE-MiE5lBBuE8gFNehb',
        oldPrice: '2.500.000 ₫',
        price: '2.100.000 ₫',
        discount: '-16%',
        specs: 'Thiết kế cân đối cho cửa chính nhà phố, độ kín khít cao, chống nước mưa tuyệt đối tại khí hậu Đà Nẵng.'
      },
      {
        id: 'sp-3',
        name: 'Cửa đi quay mở 3 cánh nhôm xingfa',
        driveId: '17Qi2D8ntACnVrTeRPZ2V7rC0FmI8ecaR',
        oldPrice: '2.550.000 ₫',
        price: '2.150.000 ₫',
        discount: '-16%',
        specs: 'Mở rộng tối đa không gian mặt tiền, sử dụng bản lề 3D chịu lực và khóa đa điểm chống trộm cao cấp.'
      },
      {
        id: 'sp-4',
        name: 'Cửa đi quay mở 4 cánh nhôm xingfa',
        driveId: '1lxzMKWX3e_HJn7UELFZDOURuxh-NYZg-',
        oldPrice: '2.600.000 ₫',
        price: '2.200.000 ₫',
        discount: '-15%',
        specs: 'Dòng cửa mặt tiền sang trọng nhất, màu xám ghi / đen tuyền / vân gỗ sơn tĩnh điện bảo hành 5 năm.'
      },
      {
        id: 'sp-5',
        name: 'Cửa Nhôm Xingfa Cửa Đi Xếp Trượt',
        driveId: '1lJpUJBpR_cJp8mIaZ4FnRTynQ_-paNwZ',
        oldPrice: '2.850.000 ₫',
        price: '2.350.000 ₫',
        discount: '-18%',
        specs: 'Nhôm Xingfa hệ 63 chuyên dụng xếp gấp 3-5 cánh gọn gàng, tối ưu tầm nhìn sân vườn, hồ bơi và ban công.'
      },
      {
        id: 'sp-6',
        name: 'Cửa sổ mở hất 2 cánh nhôm Xingfa',
        driveId: '11fS_oEeJtnDICQZ77fJlYl6GhHf-GOhA',
        oldPrice: '2.250.000 ₫',
        price: '1.890.000 ₫',
        discount: '-16%',
        specs: 'Nhôm Xingfa hệ 55 dày 1.4mm, thanh định vị chống gió đập mạnh, lấy gió thoáng kể cả khi trời mưa nhỏ.'
      }
    ];

    // 3. DỮ LIỆU 6 DỰ ÁN TIÊU BIỂU TẠI ĐÀ NẴNG
    const PROJECTS = [
      {
        title: 'DỰ ÁN RESORT MỸ SƠN 4 SAO “MY SON HERITAGE RESORT & SPA”',
        driveId: '1MmAfsyp3s3YCaEMymrkk8TZbD38jCsAQ',
        location: 'Quảng Nam - Đà Nẵng',
        scope: 'Thi công hệ thống cửa nhôm Xingfa nhập khẩu, vách kính mặt dựng và phòng tắm kính cao cấp chuẩn resort 4 sao.'
      },
      {
        title: 'THI CÔNG DỰ ÁN KHÁCH SẠN GODEN LINE',
        driveId: '1YeuDLiSXUK_Epupq9QiGzM90_EGW3Kfy',
        location: 'TP. Đà Nẵng',
        scope: 'Lắp đặt trọn gói cửa đi ban công, cửa sổ cách âm chống bão và vách kính cường lực mặt tiền khách sạn.'
      },
      {
        title: 'DỰ ÁN KHÁCH SẠN RUBY LIGHT',
        driveId: '1wH-JJ2rOYRmDGsNapl3bIBjfiG3Qm6zZ',
        location: 'TP. Đà Nẵng',
        scope: 'Gia công cửa nhôm kính Xingfa màu xám ghi, cửa kính tự động sảnh chính và cabin tắm kính toàn bộ phòng lưu trú.'
      },
      {
        title: 'THI CÔNG DỰ ÁN RAON ĐÀ NẴNG BEACH HOTEL',
        driveId: '1za_IJpAm850uulT6IuhBsk1THb3LuPuc',
        location: 'Ven biển TP. Đà Nẵng',
        scope: 'Giải pháp nhôm kính chịu gió biển, chống ăn mòn muối biển kết hợp kính hộp cách âm hiệu quả.'
      },
      {
        title: 'THI CÔNG DỰ ÁN KHÁCH SẠN JOLIA',
        driveId: '1WRgx-EUIrn8IKFZdpmdv6Z2Xyb7L8_64',
        location: 'TP. Đà Nẵng',
        scope: 'Hoàn thiện toàn bộ hệ thống cửa nhôm Xingfa, lan can kính cường lực và cầu thang kính hiện đại.'
      },
      {
        title: 'THI CÔNG DỰ ÁN KHÁCH SẠN SOHO',
        driveId: '1-C5bdt4K-PpLX_KqSN6QAR5ULo1WnNzt',
        location: 'TP. Đà Nẵng',
        scope: 'Thiết kế và lắp đặt hệ cửa nhôm kính thẩm mỹ cao, tối ưu ánh sáng tự nhiên và tiết kiệm điện năng.'
      }
    ];

    // 4. DỮ LIỆU 6 ĐỐI TÁC (ẢNH DRIVE THỰC TẾ)
    const PARTNERS = [
      { name: 'Đối tác nhôm kính 1', driveId: '13il4TeS8ZnrK0CD4VDPMdNX3EKxY8AFk' },
      { name: 'Đối tác nhôm kính 2', driveId: '1QRcPtjWfg5PEQXw6UMg6ZylQhg8BpzUq' },
      { name: 'Đối tác nhôm kính 3', driveId: '1-Ka-zScPzx653Tg2oWE9-qmFtTdn3Svn' },
      { name: 'Đối tác nhôm kính 4', driveId: '1Oy52Wdfy5x6DKF1lyfYxpZTD5fvGH5vT' },
      { name: 'Đối tác nhôm kính 5', driveId: '1SDcarhnX0yypmqdbawICjYBRtFnKngn-' },
      { name: 'Đối tác nhôm kính 6', driveId: '1Ua4C1iiZqrjkWx-3h2quvqM0w_Xj33fg' }
    ];

    // 5. DỮ LIỆU CÁC BÀI VIẾT TIN TỨC NỔI BẬT TRANG CHỦ
    const ARTICLES = [
      {
        title: 'Cửa nhôm Xingfa có phù hợp với khí hậu biển Đà Nẵng không?',
        date: '18/11/2026',
        driveId: '1zRlHJBAneXS7EQ1jdT__hVRCTf2mzOiX',
        excerpt: 'Khí hậu ven biển Đà Nẵng có độ ẩm và hơi muối cao. Nhôm Xingfa sơn tĩnh điện ngoài trời giúp chống oxy hóa, kín nước tuyệt đối khi mưa bão.',
        content: 'Nhôm Xingfa nhập khẩu chính hãng sở hữu bề mặt sơn tĩnh điện cao cấp theo tiêu chuẩn quốc tế, chống bám muối biển và không cong vênh dưới nắng gắt Miền Trung. Kết hợp gioăng kép EPDM và keo silicon chuyên dụng giúp ngăn nước tràn vào nhà ngay cả trong mùa mưa bão tại Đà Nẵng.'
      },
      {
        title: 'Cửa nhôm Xingfa có tiết kiệm điện năng và cách âm tốt không?',
        date: '12/11/2026',
        driveId: '1h2r2rbPrEL7dgLE-MiE5lBBuE8gFNehb',
        excerpt: 'Cấu trúc khoang rỗng kết hợp gân gia cường và kính hộp giúp giảm thất thoát nhiệt điều hòa lên đến 30% cho nhà phố và khách sạn.',
        content: 'Nhờ cấu tạo thanh profile có nhiều khoang trống cùng hệ phụ kiện khóa đa điểm ép chặt cánh cửa vào khung bao, cửa nhôm Xingfa hạn chế tối đa thất thoát hơi lạnh máy điều hòa và giảm tiếng ồn giao thông đô thị rõ rệt.'
      },
      {
        title: 'Kinh nghiệm chọn phòng tắm kính & kính ốp bếp bền đẹp theo năm tháng',
        date: '05/11/2026',
        driveId: '1MhCILHQ5goD1cAPTt1hZsY_ajeOMs-qH',
        excerpt: 'Nên dùng kính cường lực độ dày 8mm hay 10mm? Phụ kiện inox 304 nào chống hoen gỉ tốt nhất trong môi trường ẩm ướt?',
        content: 'Đối với phòng tắm kính, nên sử dụng kính cường lực 10mm kết hợp bản lề và kẹp định vị inox 304 chuẩn để tránh xệ cánh và chống rỉ sét. Đối với kính ốp bếp, kính cường lực 8mm sơn màu chịu nhiệt đảm bảo dễ vệ sinh dầu mỡ và giữ màu sáng bóng lâu dài.'
      },
      {
        title: 'So sánh cửa nhôm Xingfa và cửa nhựa lõi thép: Nên chọn loại nào?',
        date: '29/10/2026',
        driveId: '1jiHBW-2MoWUHjQUicSe-rO6NlmfNuZNA',
        excerpt: 'Phân tích ưu nhược điểm về độ bền, khả năng chịu lực, tính thẩm mỹ và chi phí đầu tư giữa hai dòng cửa phổ biến nhất hiện nay.',
        content: 'Cửa nhôm Xingfa nổi bật về độ cứng vững, khung thanh mảnh hiện đại và độ bền màu vượt trội ở vị trí mặt tiền chịu nắng gió trực tiếp. Trong khi đó, cửa nhựa lõi thép uPVC có chi phí kinh tế và cách âm tốt cho không gian phòng ngủ hoặc văn phòng bên trong.'
      }
    ];

    // Render Danh mục sản phẩm nổi bật
    function renderCategories() {
      const container = document.getElementById('category-grid');
      if (!container) return;
      container.innerHTML = CATEGORIES.map(cat => `
        <a href="${cat.target}" onclick="selectQuoteCategory('${cat.name}')" class="group bg-white rounded-xl border border-slate-200 overflow-hidden shadow-xs hover:shadow-md hover:border-brand/40 transition flex flex-col">
          <div class="aspect-[4/3] w-full overflow-hidden bg-slate-100">
            <img
              src="${getDriveUrlPrimary(cat.driveId)}"
              data-drive-id="${cat.driveId}"
              alt="${cat.name}"
              loading="lazy"
              onerror="handleImgError(this, '${cat.name}')"
              class="w-full h-full object-cover group-hover:scale-105 transition duration-500"
            />
          </div>
          <div class="p-3 sm:p-4 text-center flex-1 flex flex-col justify-between">
            <h3 class="text-xs sm:text-sm font-extrabold uppercase text-brand group-hover:text-accent-dark transition leading-snug">
              ${cat.name}
            </h3>
            <p class="hidden sm:block text-xs text-slate-500 mt-1.5 leading-relaxed">
              ${cat.desc}
            </p>
          </div>
        </a>
      `).join('');
    }

    // Render Sản phẩm (2 cột trên điện thoại, giá & giảm giá % góc trên bên trái, không cắt thiếu chữ tên sản phẩm)
    function renderProducts(list) {
      const container = document.getElementById('product-grid');
      if (!container) return;
      if (!list.length) {
        container.innerHTML = `
          <div class="col-span-full text-center py-8 bg-white rounded-xl border border-slate-200 text-sm text-slate-500">
            Không tìm thấy sản phẩm phù hợp. <button type="button" onclick="filterProductsByKeyword('all')" class="text-brand font-bold underline ml-1">Xem tất cả sản phẩm</button>
          </div>
        `;
        return;
      }
      container.innerHTML = list.map(sp => `
        <article class="bg-white rounded-xl border border-slate-200 overflow-hidden shadow-xs hover:shadow-md transition flex flex-col">
          <div class="relative aspect-[4/3] w-full overflow-hidden bg-slate-100">
            <!-- Giảm giá % góc trên bên trái -->
            <span class="absolute top-2 left-2 z-10 bg-red-600 text-white text-[11px] sm:text-xs font-extrabold px-2 py-0.5 rounded-md shadow">
              ${sp.discount}
            </span>
            <img
              src="${getDriveUrlPrimary(sp.driveId)}"
              data-drive-id="${sp.driveId}"
              alt="${sp.name}"
              loading="lazy"
              onerror="handleImgError(this, '${sp.name}')"
              class="w-full h-full object-cover hover:scale-105 transition duration-500 cursor-pointer"
              onclick="openProductModal('${sp.id}')"
            />
          </div>
          <div class="p-2.5 sm:p-4 flex-1 flex flex-col justify-between gap-2">
            <!-- Tên sản phẩm hiển thị đầy đủ, không bị tràn hoặc cắt chữ -->
            <h3
              onclick="openProductModal('${sp.id}')"
              class="text-[12px] sm:text-sm font-bold text-slate-800 hover:text-brand cursor-pointer leading-snug break-words"
            >
              ${sp.name}
            </h3>

            <div class="space-y-2 pt-1">
              <!-- Giá bán và giá gốc -->
              <div class="flex flex-wrap items-baseline gap-x-2 gap-y-0.5">
                <span class="text-[13px] sm:text-base font-extrabold text-red-600">${sp.price}</span>
                <span class="text-[11px] sm:text-xs text-slate-400 line-through">${sp.oldPrice}</span>
              </div>

              <div class="grid grid-cols-1 sm:grid-cols-2 gap-1.5">
                <button
                  type="button"
                  onclick="openProductModal('${sp.id}')"
                  class="w-full py-1.5 px-2 rounded-lg bg-brand-soft hover:bg-brand text-brand hover:text-white text-[11px] sm:text-xs font-bold transition"
                >
                  Xem chi tiết
                </button>
                <a
                  href="#form-bao-gia"
                  onclick="selectQuoteProduct('${sp.name}')"
                  class="w-full py-1.5 px-2 rounded-lg bg-brand hover:bg-brand-dark text-white text-[11px] sm:text-xs font-bold text-center transition"
                >
                  Báo giá
                </a>
              </div>
            </div>
          </div>
        </article>
      `).join('');
    }

    // Render 6 Dự án tại Đà Nẵng
    function renderProjects() {
      const container = document.getElementById('project-grid');
      if (!container) return;
      container.innerHTML = PROJECTS.map((proj, idx) => `
        <article onclick="openProjectModal(${idx})" class="group bg-white rounded-xl border border-slate-200 overflow-hidden shadow-xs hover:shadow-md transition cursor-pointer flex flex-col">
          <div class="aspect-[16/10] w-full overflow-hidden bg-slate-100">
            <img
              src="${getDriveUrlPrimary(proj.driveId)}"
              data-drive-id="${proj.driveId}"
              alt="${proj.title}"
              loading="lazy"
              onerror="handleImgError(this, 'Dự án Đà Nẵng')"
              class="w-full h-full object-cover group-hover:scale-105 transition duration-500"
            />
          </div>
          <div class="p-3.5 sm:p-4 flex-1 flex flex-col justify-between gap-2">
            <h3 class="text-xs sm:text-sm font-bold text-brand group-hover:text-accent-dark transition leading-snug">
              ${proj.title}
            </h3>
            <div class="flex items-center justify-between text-[11px] text-slate-500 pt-1 border-t border-slate-100">
              <span>${proj.location}</span>
              <span class="font-semibold text-brand">Xem chi tiết →</span>
            </div>
          </div>
        </article>
      `).join('');
    }

    // Render Tin tức nổi bật
    function renderNews() {
      const container = document.getElementById('news-grid');
      if (!container) return;
      container.innerHTML = ARTICLES.map((art, idx) => `
        <article onclick="openArticleModal(${idx})" class="group bg-white rounded-xl border border-slate-200 overflow-hidden shadow-xs hover:shadow-md transition cursor-pointer flex flex-col">
          <div class="aspect-[16/10] w-full overflow-hidden bg-slate-100">
            <img
              src="${getDriveUrlPrimary(art.driveId)}"
              data-drive-id="${art.driveId}"
              alt="${art.title}"
              loading="lazy"
              onerror="handleImgError(this, 'Tin tức nhôm kính')"
              class="w-full h-full object-cover group-hover:scale-105 transition duration-500"
            />
          </div>
          <div class="p-3.5 flex-1 flex flex-col justify-between gap-2">
            <div>
              <div class="text-[11px] text-slate-400 mb-1">${art.date}</div>
              <h3 class="text-xs sm:text-sm font-bold text-slate-800 group-hover:text-brand transition leading-snug">
                ${art.title}
              </h3>
              <p class="text-xs text-slate-500 mt-1.5 leading-relaxed">
                ${art.excerpt}
              </p>
            </div>
            <div class="text-xs font-bold text-brand pt-1">Đọc tiếp →</div>
          </div>
        </article>
      `).join('');
    }

    // Render 6 Đối tác
    function renderPartners() {
      const container = document.getElementById('partner-grid');
      if (!container) return;
      container.innerHTML = PARTNERS.map((p, idx) => `
        <div class="bg-white rounded-lg border border-slate-200 p-2.5 sm:p-3 h-20 sm:h-24 flex items-center justify-center shadow-2xs hover:border-brand/40 transition">
          <img
            src="${getDriveUrlPrimary(p.driveId)}"
            data-drive-id="${p.driveId}"
            alt="${p.name}"
            loading="lazy"
            onerror="handleImgError(this, 'Đối tác ${idx + 1}')"
            class="max-h-full max-w-full object-contain"
          />
        </div>
      `).join('');
    }

    // Khởi tạo hình ảnh Banner sử dụng Drive URL
    function initHeroDriveImages() {
      document.querySelectorAll('.drive-img').forEach(img => {
        const id = img.dataset.driveId;
        if (id) {
          img.src = getDriveUrlPrimary(id);
          img.onerror = function() {
            handleImgError(this, 'Nhôm Kính Văn Tới');
          };
        }
      });
    }

    // Lọc sản phẩm theo từ khóa / nút bộ lọc
    function filterProductsByKeyword(keyword) {
      const btns = document.querySelectorAll('.product-filter-btn');
      btns.forEach(btn => {
        const isMatch = btn.dataset.filter.toLowerCase() === keyword.toLowerCase();
        btn.className = isMatch
          ? 'product-filter-btn px-3 py-1.5 rounded-lg text-xs font-semibold bg-brand text-white transition'
          : 'product-filter-btn px-3 py-1.5 rounded-lg text-xs font-semibold bg-white border border-slate-200 text-slate-700 hover:border-brand hover:text-brand transition';
      });

      if (!keyword || keyword === 'all') {
        renderProducts(PRODUCTS);
        return;
      }
      const q = keyword.toLowerCase();
      const filtered = PRODUCTS.filter(p => p.name.toLowerCase().includes(q));
      renderProducts(filtered);
    }

    // Tự điền hạng mục vào Form Báo Giá khi người dùng nhấn chọn sản phẩm/danh mục
    function selectQuoteCategory(catName) {
      const selectEl = document.getElementById('q-category');
      if (!selectEl) return;
      for (let i = 0; i < selectEl.options.length; i++) {
        if (selectEl.options[i].value.toLowerCase() === catName.toLowerCase()) {
          selectEl.selectedIndex = i;
          break;
        }
      }
    }
    function selectQuoteProduct(productName) {
      const noteEl = document.getElementById('q-note');
      if (noteEl) {
        noteEl.value = `Tôi cần tư vấn và báo giá mẫu: ${productName}`;
      }
    }

    // Modal xem chi tiết Sản phẩm / Dự án / Bài viết
    function openModal(title, htmlContent) {
      const modal = document.getElementById('detail-modal');
      document.getElementById('modal-title').textContent = title;
      document.getElementById('modal-body').innerHTML = htmlContent;
      modal.classList.remove('hidden');
      modal.classList.add('flex');
      document.body.style.overflow = 'hidden';
    }
    function closeModal() {
      const modal = document.getElementById('detail-modal');
      modal.classList.add('hidden');
      modal.classList.remove('flex');
      document.body.style.overflow = '';
    }

    function openProductModal(id) {
      const sp = PRODUCTS.find(p => p.id === id);
      if (!sp) return;
      openModal(sp.name, `
        <div class="grid grid-cols-1 sm:grid-cols-2 gap-5 items-start">
          <div class="relative rounded-xl overflow-hidden border border-slate-200 bg-slate-100 aspect-[4/3]">
            <span class="absolute top-2.5 left-2.5 bg-red-600 text-white text-xs font-extrabold px-2.5 py-0.5 rounded-md shadow">${sp.discount}</span>
            <img src="${getDriveUrlPrimary(sp.driveId)}" data-drive-id="${sp.driveId}" alt="${sp.name}" onerror="handleImgError(this, '${sp.name}')" class="w-full h-full object-cover" />
          </div>
          <div class="space-y-3">
            <div class="flex items-baseline gap-2.5">
              <span class="text-xl font-extrabold text-red-600">${sp.price}</span>
              <span class="text-sm text-slate-400 line-through">${sp.oldPrice}</span>
            </div>
            <p class="text-xs sm:text-sm text-slate-600 leading-relaxed">${sp.specs}</p>
            <ul class="text-xs text-slate-600 space-y-1.5 bg-brand-soft p-3 rounded-lg">
              <li>• Gia công trực tiếp tại xưởng TP. Đà Nẵng</li>
              <li>• Khảo sát đo đạc & lên bản vẽ miễn phí</li>
              <li>• Bảo hành chính hãng dài hạn</li>
            </ul>
            <div class="flex flex-wrap gap-2 pt-1">
              <a href="tel:0905579197" class="flex-1 py-2.5 px-3 rounded-lg bg-accent hover:bg-accent-dark text-white text-xs font-bold text-center transition">Gọi 0905.579.197</a>
              <a href="#form-bao-gia" onclick="closeModal(); selectQuoteProduct('${sp.name}')" class="flex-1 py-2.5 px-3 rounded-lg bg-brand hover:bg-brand-dark text-white text-xs font-bold text-center transition">Nhận Báo Giá</a>
            </div>
          </div>
        </div>
      `);
    }

    function openProjectModal(idx) {
      const proj = PROJECTS[idx];
      if (!proj) return;
      openModal(proj.title, `
        <div class="space-y-4">
          <div class="rounded-xl overflow-hidden border border-slate-200 aspect-[16/10] bg-slate-100">
            <img src="${getDriveUrlPrimary(proj.driveId)}" data-drive-id="${proj.driveId}" alt="${proj.title}" onerror="handleImgError(this, 'Dự án Đà Nẵng')" class="w-full h-full object-cover" />
          </div>
          <div class="text-xs sm:text-sm text-slate-600 space-y-2 leading-relaxed">
            <div><strong class="text-brand">Khu vực:</strong> ${proj.location}</div>
            <div><strong class="text-brand">Hạng mục thi công:</strong> ${proj.scope}</div>
          </div>
          <div class="pt-2 flex justify-end">
            <a href="#form-bao-gia" onclick="closeModal()" class="px-4 py-2 rounded-lg bg-brand hover:bg-brand-dark text-white text-xs font-bold transition">Tư vấn thi công công trình tương tự</a>
          </div>
        </div>
      `);
    }

    function openArticleModal(idx) {
      const art = ARTICLES[idx];
      if (!art) return;
      openModal(art.title, `
        <div class="space-y-4">
          <div class="rounded-xl overflow-hidden border border-slate-200 aspect-[16/9] bg-slate-100">
            <img src="${getDriveUrlPrimary(art.driveId)}" data-drive-id="${art.driveId}" alt="${art.title}" onerror="handleImgError(this, 'Tin tức')" class="w-full h-full object-cover" />
          </div>
          <div class="text-xs text-slate-400">Đăng ngày ${art.date} • Nhôm Kính Văn Tới</div>
          <p class="text-sm text-slate-700 leading-relaxed">${art.excerpt}</p>
          <p class="text-sm text-slate-700 leading-relaxed">${art.content}</p>
          <div class="p-3.5 rounded-xl bg-brand-soft text-xs text-slate-700">
            Cần tư vấn kỹ thuật chi tiết tại TP. Đà Nẵng? Liên hệ ngay Hotline/Zalo: <a href="tel:0905579197" class="font-bold text-brand underline">0905.579.197</a>.
          </div>
        </div>
      `);
    }

    // Hiển thị thông báo Toast
    let toastTimer = null;
    function showToast(msg) {
      const box = document.getElementById('toast-box');
      if (!box) return;
      box.textContent = msg;
      box.classList.remove('hidden');
      clearTimeout(toastTimer);
      toastTimer = setTimeout(() => {
        box.classList.add('hidden');
      }, 4200);
    }

    // Accordion menu mobile
    function toggleMobileSub(subId, btn) {
      const sub = document.getElementById(subId);
      const icon = btn.querySelector('svg');
      if (!sub) return;
      sub.classList.toggle('hidden');
      if (icon) icon.classList.toggle('rotate-180');
    }

    // Logic 2 Banner tự trượt chuyên nghiệp (hỗ trợ vuốt cảm ứng trên điện thoại)
    function initHeroSlider() {
      const slides = document.querySelectorAll('.hero-slide');
      const dots = document.querySelectorAll('.hero-dot');
      const sliderEl = document.getElementById('hero-slider');
      let current = 0;
      let autoPlay = null;

      function goToSlide(index) {
        current = (index + slides.length) % slides.length;
        slides.forEach((s, i) => s.classList.toggle('is-active', i === current));
        dots.forEach((d, i) => {
          if (i === current) {
            d.classList.add('w-6', 'bg-accent-light');
            d.classList.remove('w-2', 'bg-white/50');
          } else {
            d.classList.remove('w-6', 'bg-accent-light');
            d.classList.add('w-2', 'bg-white/50');
          }
        });
      }

      function startAuto() {
        stopAuto();
        autoPlay = setInterval(() => goToSlide(current + 1), 5000);
      }
      function stopAuto() {
        if (autoPlay) clearInterval(autoPlay);
      }

      document.getElementById('hero-prev')?.addEventListener('click', () => { goToSlide(current - 1); startAuto(); });
      document.getElementById('hero-next')?.addEventListener('click', () => { goToSlide(current + 1); startAuto(); });
      dots.forEach(dot => {
        dot.addEventListener('click', () => {
          goToSlide(parseInt(dot.dataset.slideDot, 10));
          startAuto();
        });
      });

      // Hỗ trợ vuốt ngang trên điện thoại
      let touchStartX = 0;
      sliderEl?.addEventListener('touchstart', (e) => {
        touchStartX = e.changedTouches[0].screenX;
        stopAuto();
      }, { passive: true });
      sliderEl?.addEventListener('touchend', (e) => {
        const diff = touchStartX - e.changedTouches[0].screenX;
        if (Math.abs(diff) > 40) {
          goToSlide(diff > 0 ? current + 1 : current - 1);
        }
        startAuto();
      }, { passive: true });

      startAuto();
    }

    // Khởi chạy toàn bộ chức năng khi trang tải xong
    document.addEventListener('DOMContentLoaded', () => {
      try {
        initHeroDriveImages();
        renderCategories();
        renderProducts(PRODUCTS);
        renderProjects();
        renderNews();
        renderPartners();
        initHeroSlider();

        // Sự kiện nút lọc sản phẩm
        document.querySelectorAll('.product-filter-btn').forEach(btn => {
          btn.addEventListener('click', () => filterProductsByKeyword(btn.dataset.filter));
        });

        // Tìm kiếm sản phẩm
        const runSearch = (inputEl) => {
          const val = (inputEl?.value || '').trim();
          filterProductsByKeyword(val || 'all');
          document.getElementById('san-pham-xingfa')?.scrollIntoView({ behavior: 'smooth' });
        };
        document.getElementById('desktop-search-btn')?.addEventListener('click', () => runSearch(document.getElementById('desktop-search-input')));
        document.getElementById('desktop-search-input')?.addEventListener('keydown', (e) => {
          if (e.key === 'Enter') runSearch(e.target);
        });
        document.getElementById('mobile-search-btn')?.addEventListener('click', () => {
          runSearch(document.getElementById('mobile-search-input'));
          closeMobileDrawer();
        });

        // Mobile Drawer
        const drawer = document.getElementById('mobile-drawer');
        const openMobileDrawer = () => {
          drawer.classList.remove('hidden');
          document.body.style.overflow = 'hidden';
        };
        const closeMobileDrawer = () => {
          drawer.classList.add('hidden');
          document.body.style.overflow = '';
        };
        document.getElementById('mobile-menu-open')?.addEventListener('click', openMobileDrawer);
        document.getElementById('mobile-menu-close')?.addEventListener('click', closeMobileDrawer);
        document.getElementById('mobile-drawer-backdrop')?.addEventListener('click', closeMobileDrawer);
        document.querySelectorAll('.mobile-nav-link').forEach(link => {
          link.addEventListener('click', closeMobileDrawer);
        });

        // Modal close
        document.getElementById('modal-close')?.addEventListener('click', closeModal);
        document.getElementById('detail-modal')?.addEventListener('click', (e) => {
          if (e.target.id === 'detail-modal') closeModal();
        });

        // Form yêu cầu & báo giá
        document.getElementById('quote-form')?.addEventListener('submit', (e) => {
          e.preventDefault();
          const name = document.getElementById('q-name').value.trim();
          const phone = document.getElementById('q-phone').value.trim();
          if (!name || !phone) {
            showToast('Vui lòng nhập đầy đủ Họ tên và Số điện thoại để nhận báo giá.');
            return;
          }
          showToast(`Cảm ơn ${name}! Nhôm Kính Văn Tới đã nhận yêu cầu và sẽ gọi lại số ${phone} trong 15 phút.`);
          e.target.reset();
        });
      } catch (err) {
        console.error('Lỗi khởi tạo giao diện:', err);
      }
    });
  </script>
</body>
</html>
