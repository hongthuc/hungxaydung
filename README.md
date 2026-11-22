<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HÙNG XÂY DỰNG - Thiết Kế & Thi Công Xây Dựng Trọn Gói Tại TP. Đà Nẵng | hungxaydung.com</title>
    <meta name="description" content="Hùng Xây Dựng (hungxaydung.com) chuyên thiết kế kiến trúc, thi công phần thô, hoàn thiện và xây nhà trọn gói uy tín tại TP. Đà Nẵng. Hotline: 0903.609.581.">

    <!-- =========================================================
         THẺ META THUMBNAIL CHIA SẺ LINK (ẢNH LOGO THƯƠNG HIỆU)
         Lưu ý khi đưa lên WordPress/Hosting: thay đường dẫn og:image
         bằng link file logo PNG kích thước 1200x630 trên hungxaydung.com
         ========================================================= -->
    <meta property="og:type" content="website">
    <meta property="og:url" content="https://hungxaydung.com/">
    <meta property="og:site_name" content="HÙNG XÂY DỰNG">
    <meta property="og:title" content="HÙNG XÂY DỰNG - Xây Dựng Trọn Gói Chuyên Nghiệp TP. Đà Nẵng">
    <meta property="og:description" content="Thiết kế kiến trúc - Thi công phần thô - Hoàn thiện nội thất - Xây nhà trọn gói uy tín tại TP. Đà Nẵng. Hotline: 0903.609.581.">
    <meta property="og:image" content="https://hungxaydung.com/wp-content/uploads/logo-hung-xay-dung-thumbnail.png">
    <meta property="og:image:width" content="1200">
    <meta property="og:image:height" content="630">
    <meta property="og:image:alt" content="Logo Hùng Xây Dựng - hungxaydung.com">
    <meta name="twitter:card" content="summary_large_image">
    <meta name="twitter:title" content="HÙNG XÂY DỰNG - hungxaydung.com">
    <meta name="twitter:description" content="Thiết kế & Thi công xây dựng trọn gói tại TP. Đà Nẵng. Hotline: 0903.609.581.">
    <meta name="twitter:image" content="https://hungxaydung.com/wp-content/uploads/logo-hung-xay-dung-thumbnail.png">

    <!-- Favicon biểu tượng Logo Hùng Xây Dựng -->
    <link rel="icon" type="image/svg+xml" href="data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 64 64'%3E%3Crect width='64' height='64' rx='10' fill='%230F2B46'/%3E%3Cpath d='M14 28L32 13L50 28' fill='none' stroke='%23E58A00' stroke-width='4.5' stroke-linecap='round' stroke-linejoin='round'/%3E%3Cpath d='M20 27V50H27V39H37V50H44V27' fill='none' stroke='%23FFFFFF' stroke-width='4.5' stroke-linecap='round' stroke-linejoin='round'/%3E%3C/svg%3E">

    <!-- Font Inter Google Fonts -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&display=swap" rel="stylesheet">

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
                        // Bảng màu đồng bộ theo Logo HÙNG XÂY DỰNG
                        brand: {
                            navy: '#0F2B46',       // Xanh Navy kiến trúc chủ đạo
                            navyDark: '#0A1E33',   // Xanh đậm cho Topbar/Footer
                            navyLight: '#18426B',  // Xanh sáng cho hover
                            amber: '#E58A00',      // Vàng cam xây dựng tạo điểm nhấn
                            amberDark: '#C67400',  // Hover vàng cam
                            surface: '#F6F8FA',    // Nền xám sáng thanh lịch
                        }
                    }
                }
            }
        }
    </script>

    <style>
        /* Chống tràn viền ngang tuyệt đối trên mọi thiết bị */
        html, body {
            max-width: 100%;
            overflow-x: hidden;
            scroll-behavior: smooth;
            box-sizing: border-box;
        }
        *, *::before, *::after {
            box-sizing: border-box;
        }

        /* Khung rộng chuẩn 95% màn hình trên máy tính theo yêu cầu */
        .hxd-container {
            width: 100%;
            margin-left: auto;
            margin-right: auto;
            padding-left: 12px;
            padding-right: 12px;
        }
        @media (min-width: 1024px) {
            .hxd-container {
                width: 95%;
                max-width: 95%;
                padding-left: 0;
                padding-right: 0;
            }
        }

        /* Tiêu đề Section chuẩn Flatsome UX Builder */
        .flatsome-section-title {
            display: flex;
            align-items: center;
            justify-content: center;
            gap: 14px;
            width: 100%;
        }
        .flatsome-section-title::before,
        .flatsome-section-title::after {
            content: "";
            height: 2px;
            flex: 1;
            max-width: 90px;
            background-color: #CBD5E1;
        }

        /* Hiệu ứng sóng lan tỏa cho nút Hotline nổi */
        @keyframes hxd-pulse {
            0% { transform: scale(1); opacity: 0.75; }
            70% { transform: scale(1.45); opacity: 0; }
            100% { transform: scale(1.45); opacity: 0; }
        }
        .hotline-ring::before {
            content: "";
            position: absolute;
            inset: 0;
            border-radius: 9999px;
            background-color: #DC2626;
            animation: hxd-pulse 2s infinite;
            z-index: -1;
        }

        /* Thanh cuộn ngang mượt cho tab danh mục trên mobile nếu cần */
        .no-scrollbar::-webkit-scrollbar {
            display: none;
        }
        .no-scrollbar {
            -ms-overflow-style: none;
            scrollbar-width: none;
        }

        /* Đảm bảo 2 banner có kích thước bằng nhau tuyệt đối và không bao giờ cắt chữ */
        .banner-stack {
            display: grid;
            grid-template-columns: 1fr;
            grid-template-rows: 1fr;
        }
        .banner-slide-item {
            grid-column: 1 / 2;
            grid-row: 1 / 2;
            transition: opacity 0.65s ease-in-out, visibility 0.65s ease-in-out;
        }
    </style>
</head>
<body class="bg-white text-slate-800 font-sans antialiased">

    <!-- =========================================================
         FLATSOME TOP BAR (Thanh thông tin liên hệ phía trên)
         ========================================================= -->
    <div class="bg-brand-navyDark text-slate-200 text-xs py-2 border-b border-white/10">
        <div class="hxd-container flex flex-wrap items-center justify-between gap-2">
            <div class="flex items-center gap-3 sm:gap-5">
                <a href="tel:0903609581" class="inline-flex items-center gap-1.5 hover:text-brand-amber transition-colors font-medium">
                    <svg class="w-3.5 h-3.5 text-brand-amber shrink-0" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M3 5a2 2 0 012-2h3.28a1 1 0 01.948.684l1.498 4.493a1 1 0 01-.502 1.21l-2.257 1.13a11.042 11.042 0 005.516 5.516l1.13-2.257a1 1 0 011.21-.502l4.493 1.498a1 1 0 01.684.949V19a2 2 0 01-2 2h-1C9.716 21 3 14.284 3 6V5z"/></svg>
                    <span>0903.609.581</span>
                </a>
                <span class="hidden sm:inline text-white/30">|</span>
                <span class="hidden sm:inline-flex items-center gap-1.5">
                    <svg class="w-3.5 h-3.5 text-brand-amber shrink-0" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M17.657 16.657L13.414 20.9a1.998 1.998 0 01-2.827 0l-4.244-4.243a8 8 0 1111.314 0z"/><path stroke-linecap="round" stroke-linejoin="round" d="M15 11a3 3 0 11-6 0 3 3 0 016 0z"/></svg>
                    <span>TP. Đà Nẵng</span>
                </span>
            </div>
            <div class="flex items-center gap-3 text-[11px] sm:text-xs">
                <span class="text-slate-300">hungxaydung.com</span>
            </div>
        </div>
    </div>

    <!-- =========================================================
         FLATSOME HEADER CHÍNH (Logo gọn nhỏ + Menu 1 hàng chuẩn)
         Không đặt nút Gọi ngay trên Header để tránh tràn viền
         ========================================================= -->
    <header class="sticky top-0 z-40 bg-white/95 backdrop-blur-md shadow-sm border-b border-slate-200">
        <div class="hxd-container h-16 lg:h-[72px] flex items-center justify-between gap-4">
            <!-- Logo HÙNG XÂY DỰNG thiết kế gọn, nhỏ, chuyên nghiệp -->
            <a href="#trang-chu" class="flex items-center gap-2.5 shrink-0 group" aria-label="Hùng Xây Dựng Trang Chủ">
                <svg class="w-9 h-9 sm:w-10 sm:h-10 shrink-0" viewBox="0 0 64 64" fill="none" xmlns="http://www.w3.org/2000/svg">
                    <rect width="64" height="64" rx="10" fill="#0F2B46"/>
                    <path d="M13 27.5L32 12L51 27.5" stroke="#E58A00" stroke-width="4.5" stroke-linecap="round" stroke-linejoin="round"/>
                    <path d="M21 26V50H27.5V39H36.5V50H43V26" stroke="#FFFFFF" stroke-width="4.5" stroke-linecap="round" stroke-linejoin="round"/>
                    <rect x="29.5" y="23" width="5" height="5" rx="1" fill="#E58A00"/>
                </svg>
                <div class="leading-tight">
                    <div class="text-[15px] sm:text-[17px] font-extrabold tracking-tight text-brand-navy group-hover:text-brand-amber transition-colors whitespace-nowrap">
                        HÙNG <span class="text-brand-amber">XÂY DỰNG</span>
                    </div>
                    <div class="text-[10px] font-semibold tracking-wider text-slate-500 uppercase whitespace-nowrap">
                        hungxaydung.com
                    </div>
                </div>
            </a>

            <!-- Menu Desktop: Chữ nhỏ gọn, viết liền 1 hàng, không bao giờ xuống dòng tên danh mục -->
            <nav class="hidden lg:flex items-center justify-end flex-nowrap gap-3.5 xl:gap-5 overflow-hidden" aria-label="Menu chính">
                <a href="#trang-chu" class="text-[12px] xl:text-[13px] font-semibold text-brand-navy hover:text-brand-amber transition-colors whitespace-nowrap py-2">Trang chủ</a>
                <a href="#gioi-thieu" class="text-[12px] xl:text-[13px] font-semibold text-slate-700 hover:text-brand-amber transition-colors whitespace-nowrap py-2">Giới thiệu</a>
                <a href="#dich-vu-thi-cong" class="text-[12px] xl:text-[13px] font-semibold text-slate-700 hover:text-brand-amber transition-colors whitespace-nowrap py-2">Lĩnh vực hoạt động</a>
                <a href="#san-pham-thi-cong" class="text-[12px] xl:text-[13px] font-semibold text-slate-700 hover:text-brand-amber transition-colors whitespace-nowrap py-2">Thi công thực tế</a>
                <a href="#du-an-da-nang" class="text-[12px] xl:text-[13px] font-semibold text-slate-700 hover:text-brand-amber transition-colors whitespace-nowrap py-2">Dự án Đà Nẵng</a>
                <a href="#doi-tac" class="text-[12px] xl:text-[13px] font-semibold text-slate-700 hover:text-brand-amber transition-colors whitespace-nowrap py-2">Đối tác</a>
                <a href="#bao-gia" class="text-[12px] xl:text-[13px] font-semibold text-slate-700 hover:text-brand-amber transition-colors whitespace-nowrap py-2">Báo giá</a>
                <a href="#tin-tuc" class="text-[12px] xl:text-[13px] font-semibold text-slate-700 hover:text-brand-amber transition-colors whitespace-nowrap py-2">Tin tức</a>
                <a href="#lien-he" class="text-[12px] xl:text-[13px] font-semibold text-slate-700 hover:text-brand-amber transition-colors whitespace-nowrap py-2">Liên hệ</a>
            </nav>

            <!-- Nút Menu Mobile -->
            <button id="mobileMenuBtn" type="button" class="lg:hidden p-2.5 rounded-lg text-brand-navy hover:bg-slate-100 focus:outline-none" aria-label="Mở menu">
                <svg class="w-6 h-6" fill="none" stroke="currentColor" stroke-width="2.2" viewBox="0 0 24 24">
                    <path stroke-linecap="round" stroke-linejoin="round" d="M4 6h16M4 12h16M4 18h16"/>
                </svg>
            </button>
        </div>
    </header>

    <!-- =========================================================
         FLATSOME MOBILE OFF-CANVAS DRAWER MENU
         ========================================================= -->
    <div id="mobileMenuOverlay" class="fixed inset-0 bg-black/50 z-50 hidden transition-opacity"></div>
    <aside id="mobileMenuDrawer" class="fixed top-0 left-0 h-full w-72 max-w-[85vw] bg-white z-50 shadow-2xl transform -translate-x-full transition-transform duration-300 flex flex-col">
        <div class="p-4 bg-brand-navy text-white flex items-center justify-between">
            <div class="flex items-center gap-2">
                <svg class="w-8 h-8 shrink-0" viewBox="0 0 64 64" fill="none">
                    <rect width="64" height="64" rx="10" fill="#18426B"/>
                    <path d="M13 27.5L32 12L51 27.5" stroke="#E58A00" stroke-width="4.5" stroke-linecap="round" stroke-linejoin="round"/>
                    <path d="M21 26V50H27.5V39H36.5V50H43V26" stroke="#FFFFFF" stroke-width="4.5" stroke-linecap="round" stroke-linejoin="round"/>
                </svg>
                <span class="font-bold text-sm tracking-wide">HÙNG XÂY DỰNG</span>
            </div>
            <button id="closeMobileMenuBtn" type="button" class="p-2 rounded-lg text-white/80 hover:text-white hover:bg-white/10" aria-label="Đóng menu">
                <svg class="w-5 h-5" fill="none" stroke="currentColor" stroke-width="2.2" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M6 18L18 6M6 6l12 12"/></svg>
            </button>
        </div>
        <nav class="flex-1 overflow-y-auto py-3 px-4 flex flex-col divide-y divide-slate-100">
            <a href="#trang-chu" class="mobile-nav-link py-3 text-sm font-semibold text-brand-navy hover:text-brand-amber">Trang chủ</a>
            <a href="#gioi-thieu" class="mobile-nav-link py-3 text-sm font-semibold text-slate-700 hover:text-brand-amber">Giới thiệu</a>
            <a href="#dich-vu-thi-cong" class="mobile-nav-link py-3 text-sm font-semibold text-slate-700 hover:text-brand-amber">Lĩnh vực hoạt động</a>
            <a href="#san-pham-thi-cong" class="mobile-nav-link py-3 text-sm font-semibold text-slate-700 hover:text-brand-amber">Thi công thực tế</a>
            <a href="#du-an-da-nang" class="mobile-nav-link py-3 text-sm font-semibold text-slate-700 hover:text-brand-amber">Dự án Đà Nẵng</a>
            <a href="#doi-tac" class="mobile-nav-link py-3 text-sm font-semibold text-slate-700 hover:text-brand-amber">Đối tác</a>
            <a href="#bao-gia" class="mobile-nav-link py-3 text-sm font-semibold text-slate-700 hover:text-brand-amber">Yêu cầu báo giá</a>
            <a href="#tin-tuc" class="mobile-nav-link py-3 text-sm font-semibold text-slate-700 hover:text-brand-amber">Tin tức xây dựng</a>
            <a href="#lien-he" class="mobile-nav-link py-3 text-sm font-semibold text-slate-700 hover:text-brand-amber">Liên hệ & Bản đồ</a>
        </nav>
        <div class="p-4 bg-brand-surface border-t border-slate-200 text-xs text-slate-600 space-y-1.5">
            <div class="font-bold text-brand-navy">HÙNG XÂY DỰNG - ĐÀ NẴNG</div>
            <div>Hotline: <a href="tel:0903609581" class="font-bold text-brand-amber">0903.609.581</a></div>
            <div>Website: hungxaydung.com</div>
        </div>
    </aside>

    <!-- =========================================================
         FLATSOME SECTION 1: 2 ẢNH BANNER TỰ TRƯỢT CHUYÊN NGHIỆP
         - Kích thước 2 banner bằng nhau tuyệt đối (CSS Grid Stack)
         - Hình ảnh & chữ nằm trọn trong banner, chữ cách xa viền
         - Không bao giờ mất chữ trên điện thoại và máy tính
         ========================================================= -->
    <section id="trang-chu" class="w-full bg-brand-navyDark pt-3 pb-4 lg:py-4">
        <div class="hxd-container">
            <div id="heroSlider" class="relative w-full rounded-xl overflow-hidden shadow-lg bg-brand-navy">
                <div class="banner-stack w-full">

                    <!-- BANNER 1 -->
                    <div class="banner-slide-item relative w-full opacity-100 z-10" data-slide="0">
                        <img
                            src="https://lh3.googleusercontent.com/d/13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz=w1600"
                            data-fallback="https://drive.google.com/thumbnail?id=13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz&sz=w1400"
                            alt="Hùng Xây Dựng - Thiết kế và thi công nhà trọn gói tại Đà Nẵng"
                            class="hxd-drive-img absolute inset-0 w-full h-full object-cover object-center"
                        >
                        <!-- Lớp phủ màu Navy theo màu logo giúp chữ nổi bật sắc nét -->
                        <div class="absolute inset-0 bg-gradient-to-r from-brand-navyDark/90 via-brand-navy/75 to-brand-navyDark/55"></div>

                        <!-- Vùng chữ có khoảng cách an toàn rộng rãi cách xa 4 viền ảnh -->
                        <div class="relative z-10 w-full h-full flex items-center justify-center px-8 sm:px-14 md:px-20 lg:px-24 py-12 sm:py-16 md:py-24 lg:py-28">
                            <div class="w-full max-w-3xl mx-auto text-center text-white space-y-3 sm:space-y-4">
                                <div class="text-[11px] sm:text-xs md:text-sm font-bold uppercase tracking-[0.18em] text-brand-amber">
                                    HÙNG XÂY DỰNG • TP. ĐÀ NẴNG
                                </div>
                                <h1 class="text-xl sm:text-3xl md:text-4xl lg:text-[42px] font-extrabold leading-snug tracking-tight">
                                    THIẾT KẾ &amp; THI CÔNG NHÀ TRỌN GÓI CHUYÊN NGHIỆP
                                </h1>
                                <p class="text-xs sm:text-sm md:text-base text-slate-200 leading-relaxed max-w-2xl mx-auto">
                                    Kiến tạo không gian sống bền vững với tiêu chuẩn kỹ thuật cao, báo giá minh bạch, cam kết đúng tiến độ và bảo hành dài hạn tại khu vực Đà Nẵng.
                                </p>
                                <div class="pt-2 sm:pt-3 flex flex-wrap items-center justify-center gap-2.5 sm:gap-4">
                                    <a href="#bao-gia" class="px-5 sm:px-7 py-2.5 sm:py-3 rounded-lg bg-brand-amber hover:bg-brand-amberDark text-white font-bold text-xs sm:text-sm transition-colors shadow-md">
                                        Nhận Báo Giá Miễn Phí
                                    </a>
                                    <a href="#du-an-da-nang" class="px-5 sm:px-7 py-2.5 sm:py-3 rounded-lg bg-white/15 hover:bg-white/25 border border-white/40 text-white font-semibold text-xs sm:text-sm transition-colors">
                                        Xem Dự Án Đà Nẵng
                                    </a>
                                </div>
                            </div>
                        </div>
                    </div>

                    <!-- BANNER 2 -->
                    <div class="banner-slide-item relative w-full opacity-0 invisible z-0" data-slide="1">
                        <img
                            src="https://lh3.googleusercontent.com/d/157Suq0BLEh2zFs3X-uaNTN-ARDWhfjfT=w1600"
                            data-fallback="https://drive.google.com/thumbnail?id=157Suq0BLEh2zFs3X-uaNTN-ARDWhfjfT&sz=w1400"
                            alt="Hùng Xây Dựng - Thi công phần thô và hoàn thiện công trình thực tế"
                            class="hxd-drive-img absolute inset-0 w-full h-full object-cover object-center"
                        >
                        <div class="absolute inset-0 bg-gradient-to-r from-brand-navyDark/90 via-brand-navy/75 to-brand-navyDark/55"></div>

                        <!-- Vùng chữ có khoảng cách an toàn y hệt Banner 1 -->
                        <div class="relative z-10 w-full h-full flex items-center justify-center px-8 sm:px-14 md:px-20 lg:px-24 py-12 sm:py-16 md:py-24 lg:py-28">
                            <div class="w-full max-w-3xl mx-auto text-center text-white space-y-3 sm:space-y-4">
                                <div class="text-[11px] sm:text-xs md:text-sm font-bold uppercase tracking-[0.18em] text-brand-amber">
                                    UY TÍN TẠO NIỀM TIN • HUNGXAYDUNG.COM
                                </div>
                                <h2 class="text-xl sm:text-3xl md:text-4xl lg:text-[42px] font-extrabold leading-snug tracking-tight">
                                    THI CÔNG PHẦN THÔ &amp; HOÀN THIỆN CHUẨN KỸ THUẬT
                                </h2>
                                <p class="text-xs sm:text-sm md:text-base text-slate-200 leading-relaxed max-w-2xl mx-auto">
                                    Đội ngũ kỹ sư và thợ lành nghề trực tiếp thi công nhà phố, biệt thự, căn hộ, khách sạn. Vật tư chính hãng, giám sát chặt chẽ từng công đoạn.
                                </p>
                                <div class="pt-2 sm:pt-3 flex flex-wrap items-center justify-center gap-2.5 sm:gap-4">
                                    <a href="#san-pham-thi-cong" class="px-5 sm:px-7 py-2.5 sm:py-3 rounded-lg bg-brand-amber hover:bg-brand-amberDark text-white font-bold text-xs sm:text-sm transition-colors shadow-md">
                                        Xem Thi Công Thực Tế
                                    </a>
                                    <a href="tel:0903609581" class="px-5 sm:px-7 py-2.5 sm:py-3 rounded-lg bg-white/15 hover:bg-white/25 border border-white/40 text-white font-semibold text-xs sm:text-sm transition-colors">
                                        Hotline: 0903.609.581
                                    </a>
                                </div>
                            </div>
                        </div>
                    </div>

                </div>

                <!-- Nút chuyển Banner Trái / Phải đặt gọn sát mép an toàn -->
                <button id="prevBannerBtn" type="button" aria-label="Banner trước" class="absolute left-2 sm:left-4 top-1/2 -translate-y-1/2 z-20 w-8 h-8 sm:w-10 sm:h-10 rounded-full bg-black/35 hover:bg-brand-amber text-white flex items-center justify-center transition-colors">
                    <svg class="w-4 h-4 sm:w-5 sm:h-5" fill="none" stroke="currentColor" stroke-width="2.5" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M15 19l-7-7 7-7"/></svg>
                </button>
                <button id="nextBannerBtn" type="button" aria-label="Banner tiếp theo" class="absolute right-2 sm:right-4 top-1/2 -translate-y-1/2 z-20 w-8 h-8 sm:w-10 sm:h-10 rounded-full bg-black/35 hover:bg-brand-amber text-white flex items-center justify-center transition-colors">
                    <svg class="w-4 h-4 sm:w-5 sm:h-5" fill="none" stroke="currentColor" stroke-width="2.5" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M9 5l7 7-7 7"/></svg>
                </button>

                <!-- Dấu chấm chỉ báo 2 Banner -->
                <div class="absolute bottom-3 sm:bottom-4 left-1/2 -translate-x-1/2 z-20 flex items-center gap-2.5">
                    <button type="button" class="banner-dot w-7 h-2 rounded-full bg-brand-amber transition-all" data-index="0" aria-label="Chọn banner 1"></button>
                    <button type="button" class="banner-dot w-2.5 h-2 rounded-full bg-white/60 hover:bg-white transition-all" data-index="1" aria-label="Chọn banner 2"></button>
                </div>
            </div>
        </div>
    </section>

    <!-- =========================================================
         FLATSOME SECTION 2: DỊCH VỤ TIÊU BIỂU (Giống mẫu Tín Trường Thịnh)
         3 cột: THIẾT KẾ - THI CÔNG - NỘI THẤT
         ========================================================= -->
    <section id="dich-vu-thi-cong" class="py-10 sm:py-14 bg-white">
        <div class="hxd-container">
            <div class="text-center mb-7 sm:mb-9">
                <h2 class="flatsome-section-title text-lg sm:text-2xl font-extrabold text-brand-navy uppercase tracking-wide">
                    Dịch Vụ Tiêu Biểu
                </h2>
            </div>

            <div class="grid grid-cols-1 md:grid-cols-3 gap-4 sm:gap-6">
                <!-- Cột 1: Thiết kế -->
                <a href="#san-pham-thi-cong" class="group block rounded-xl overflow-hidden border border-slate-200 bg-white shadow-sm hover:shadow-md transition-shadow">
                    <div class="relative aspect-[16/10] overflow-hidden bg-slate-100">
                        <img
                            src="https://lh3.googleusercontent.com/d/1_0OVVXoqQgYvoVEaZSC5iZh_SKGBbr-t=w900"
                            data-fallback="https://drive.google.com/thumbnail?id=1_0OVVXoqQgYvoVEaZSC5iZh_SKGBbr-t&sz=w900"
                            alt="Thiết kế kiến trúc Hùng Xây Dựng"
                            class="hxd-drive-img w-full h-full object-cover group-hover:scale-105 transition-transform duration-500"
                        >
                        <div class="absolute inset-0 bg-gradient-to-t from-brand-navyDark/80 via-transparent to-transparent"></div>
                        <div class="absolute bottom-3 left-4 right-4 text-white font-extrabold text-base sm:text-lg tracking-wide">
                            THIẾT KẾ KIẾN TRÚC
                        </div>
                    </div>
                    <div class="p-4 text-xs sm:text-sm text-slate-600 leading-relaxed">
                        Tư vấn phương án mặt bằng, phối cảnh 3D nhà phố, biệt thự, khách sạn, căn hộ tối ưu công năng và thẩm mỹ hiện đại.
                    </div>
                </a>

                <!-- Cột 2: Thi công -->
                <a href="#san-pham-thi-cong" class="group block rounded-xl overflow-hidden border border-slate-200 bg-white shadow-sm hover:shadow-md transition-shadow">
                    <div class="relative aspect-[16/10] overflow-hidden bg-slate-100">
                        <img
                            src="https://lh3.googleusercontent.com/d/1taZEEvo_cWqkQxBcCPhpoDRIIMQ-50eR=w900"
                            data-fallback="https://drive.google.com/thumbnail?id=1taZEEvo_cWqkQxBcCPhpoDRIIMQ-50eR&sz=w900"
                            alt="Thi công phần thô và trọn gói Hùng Xây Dựng"
                            class="hxd-drive-img w-full h-full object-cover group-hover:scale-105 transition-transform duration-500"
                        >
                        <div class="absolute inset-0 bg-gradient-to-t from-brand-navyDark/80 via-transparent to-transparent"></div>
                        <div class="absolute bottom-3 left-4 right-4 text-white font-extrabold text-base sm:text-lg tracking-wide">
                            THI CÔNG XÂY DỰNG
                        </div>
                    </div>
                    <div class="p-4 text-xs sm:text-sm text-slate-600 leading-relaxed">
                        Thi công phần thô, hoàn thiện và xây nhà trọn gói chìa khóa trao tay. Cam kết kết cấu vững chắc, không phát sinh chi phí.
                    </div>
                </a>

                <!-- Cột 3: Nội thất -->
                <a href="#san-pham-thi-cong" class="group block rounded-xl overflow-hidden border border-slate-200 bg-white shadow-sm hover:shadow-md transition-shadow">
                    <div class="relative aspect-[16/10] overflow-hidden bg-slate-100">
                        <img
                            src="https://lh3.googleusercontent.com/d/1UB12E_spzIvo7TNREjBJXUV9o_HVWOv_=w900"
                            data-fallback="https://drive.google.com/thumbnail?id=1UB12E_spzIvo7TNREjBJXUV9o_HVWOv_&sz=w900"
                            alt="Hoàn thiện nội thất Hùng Xây Dựng"
                            class="hxd-drive-img w-full h-full object-cover group-hover:scale-105 transition-transform duration-500"
                        >
                        <div class="absolute inset-0 bg-gradient-to-t from-brand-navyDark/80 via-transparent to-transparent"></div>
                        <div class="absolute bottom-3 left-4 right-4 text-white font-extrabold text-base sm:text-lg tracking-wide">
                            HOÀN THIỆN NỘI THẤT
                        </div>
                    </div>
                    <div class="p-4 text-xs sm:text-sm text-slate-600 leading-relaxed">
                        Sản xuất và lắp đặt nội thất nhà ở, văn phòng, căn hộ cho thuê đồng bộ theo bản vẽ, tinh tế trong từng đường nét.
                    </div>
                </a>
            </div>
        </div>
    </section>

    <!-- =========================================================
         FLATSOME SECTION 3: GIỚI THIỆU & THẾ MẠNH CỦA CHÚNG TÔI
         (Bố cục 2 phần chuẩn theo web mẫu tintruongthinh.com)
         ========================================================= -->
    <section id="gioi-thieu" class="py-10 sm:py-14 bg-brand-surface border-y border-slate-200">
        <div class="hxd-container space-y-10">
            <!-- Giới thiệu ngắn gọn về HÙNG XÂY DỰNG -->
            <div class="grid grid-cols-1 lg:grid-cols-12 gap-6 lg:gap-10 items-center bg-white rounded-xl p-5 sm:p-8 border border-slate-200 shadow-sm">
                <div class="lg:col-span-5">
                    <div class="rounded-xl overflow-hidden aspect-[4/3] bg-slate-100">
                        <img
                            src="https://lh3.googleusercontent.com/d/1Wlhms5ZB_mL9OptenKvrBS-rGCP2xU1_=w900"
                            data-fallback="https://drive.google.com/thumbnail?id=1Wlhms5ZB_mL9OptenKvrBS-rGCP2xU1_&sz=w900"
                            alt="Đội ngũ thi công công trình Hùng Xây Dựng Đà Nẵng"
                            class="hxd-drive-img w-full h-full object-cover"
                        >
                    </div>
                </div>
                <div class="lg:col-span-7 space-y-4">
                    <div class="text-xs font-bold uppercase tracking-widest text-brand-amber">Về Chúng Tôi</div>
                    <h2 class="text-xl sm:text-2xl lg:text-3xl font-extrabold text-brand-navy leading-snug">
                        HÙNG XÂY DỰNG – ĐỒNG HÀNH XÂY DỰNG TỔ ẤM BỀN VỮNG TẠI ĐÀ NẴNG
                    </h2>
                    <p class="text-sm text-slate-600 leading-relaxed">
                        <strong>HÙNG XÂY DỰNG (hungxaydung.com)</strong> chuyên Thiết kế – Thi công phần thô – Hoàn thiện – Xây nhà trọn gói các công trình Nhà phố, Biệt thự, Căn hộ cho thuê, Khách sạn và Văn phòng tại khu vực TP. Đà Nẵng và lân cận.
                    </p>
                    <p class="text-sm text-slate-600 leading-relaxed">
                        Đặt tiêu chí <strong>“AN TOÀN – CHẤT LƯỢNG – ĐÚNG TIẾN ĐỘ – CHI PHÍ HỢP LÝ”</strong> lên hàng đầu, đội ngũ kỹ sư và thợ thi công giàu kinh nghiệm của chúng tôi luôn tận tâm giám sát từng hạng mục để mỗi công trình bàn giao đều đạt sự hài lòng cao nhất từ Quý khách hàng.
                    </p>
                    <div class="grid grid-cols-3 gap-3 pt-2">
                        <div class="p-3 rounded-lg bg-brand-surface border border-slate-200 text-center">
                            <div class="text-lg sm:text-2xl font-extrabold text-brand-navy">10+</div>
                            <div class="text-[11px] sm:text-xs text-slate-600 mt-0.5">Năm kinh nghiệm</div>
                        </div>
                        <div class="p-3 rounded-lg bg-brand-surface border border-slate-200 text-center">
                            <div class="text-lg sm:text-2xl font-extrabold text-brand-amber">120+</div>
                            <div class="text-[11px] sm:text-xs text-slate-600 mt-0.5">Công trình hoàn thiện</div>
                        </div>
                        <div class="p-3 rounded-lg bg-brand-surface border border-slate-200 text-center">
                            <div class="text-lg sm:text-2xl font-extrabold text-brand-navy">100%</div>
                            <div class="text-[11px] sm:text-xs text-slate-600 mt-0.5">Vật tư chuẩn cam kết</div>
                        </div>
                    </div>
                </div>
            </div>

            <!-- 6 Thế mạnh của HÙNG XÂY DỰNG (Flatsome 3x2 Icon Box) -->
            <div>
                <div class="text-center mb-7">
                    <h2 class="flatsome-section-title text-lg sm:text-2xl font-extrabold text-brand-navy uppercase tracking-wide">
                        Thế Mạnh Của Chúng Tôi
                    </h2>
                </div>
                <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-4 sm:gap-5">
                    <div class="bg-white p-5 rounded-xl border border-slate-200 shadow-sm flex items-start gap-4">
                        <div class="w-11 h-11 rounded-lg bg-brand-navy text-brand-amber flex items-center justify-center shrink-0">
                            <svg class="w-6 h-6" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M17 20h5v-2a3 3 0 00-5.356-1.857M17 20H7m10 0v-2c0-.656-.126-1.283-.356-1.857M7 20H2v-2a3 3 0 015.356-1.857M7 20v-2c0-.656.126-1.283.356-1.857m0 0a5.002 5.002 0 019.288 0M15 7a3 3 0 11-6 0 3 3 0 016 0z"/></svg>
                        </div>
                        <div>
                            <h3 class="font-bold text-brand-navy text-sm sm:text-base mb-1">Kỹ sư &amp; thợ tay nghề cao</h3>
                            <p class="text-xs sm:text-sm text-slate-600 leading-relaxed">Đội ngũ kiến trúc sư sáng tạo cùng kỹ sư giám sát và công nhân lành nghề, trực tiếp thi công không bán thầu.</p>
                        </div>
                    </div>
                    <div class="bg-white p-5 rounded-xl border border-slate-200 shadow-sm flex items-start gap-4">
                        <div class="w-11 h-11 rounded-lg bg-brand-navy text-brand-amber flex items-center justify-center shrink-0">
                            <svg class="w-6 h-6" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M19 21V5a2 2 0 00-2-2H7a2 2 0 00-2 2v16m14 0h2m-2 0h-5m-9 0H3m2 0h5M9 7h1m-1 4h1m4-4h1m-1 4h1m-5 10v-5a1 1 0 011-1h2a1 1 0 011 1v5m-4 0h4"/></svg>
                        </div>
                        <div>
                            <h3 class="font-bold text-brand-navy text-sm sm:text-base mb-1">Xu hướng thiết kế hiện đại</h3>
                            <p class="text-xs sm:text-sm text-slate-600 leading-relaxed">Cập nhật liên tục vật liệu mới và giải pháp thi công tối ưu không gian, thông thoáng và tiết kiệm năng lượng.</p>
                        </div>
                    </div>
                    <div class="bg-white p-5 rounded-xl border border-slate-200 shadow-sm flex items-start gap-4">
                        <div class="w-11 h-11 rounded-lg bg-brand-navy text-brand-amber flex items-center justify-center shrink-0">
                            <svg class="w-6 h-6" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M12 8v4l3 3m6-3a9 9 0 11-18 0 9 9 0 0118 0z"/></svg>
                        </div>
                        <div>
                            <h3 class="font-bold text-brand-navy text-sm sm:text-base mb-1">Giám sát tiến độ chuẩn xác</h3>
                            <p class="text-xs sm:text-sm text-slate-600 leading-relaxed">Cập nhật hình ảnh thực tế tại công trường thường xuyên giúp chủ đầu tư dễ dàng theo dõi tiến độ mỗi ngày.</p>
                        </div>
                    </div>
                    <div class="bg-white p-5 rounded-xl border border-slate-200 shadow-sm flex items-start gap-4">
                        <div class="w-11 h-11 rounded-lg bg-brand-navy text-brand-amber flex items-center justify-center shrink-0">
                            <svg class="w-6 h-6" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M9 12l2 2 4-4m5.618-4.016A11.955 11.955 0 0112 2.944a11.955 11.955 0 01-8.618 3.04A12.02 12.02 0 003 9c0 5.591 3.824 10.29 9 11.622 5.176-1.332 9-6.03 9-11.622 0-1.042-.133-2.052-.382-3.016z"/></svg>
                        </div>
                        <div>
                            <h3 class="font-bold text-brand-navy text-sm sm:text-base mb-1">Bảo hành công trình dài hạn</h3>
                            <p class="text-xs sm:text-sm text-slate-600 leading-relaxed">Chế độ bảo hành kết cấu lên đến 5 năm, hỗ trợ bảo trì nhanh chóng giúp gia chủ luôn an tâm sử dụng.</p>
                        </div>
                    </div>
                    <div class="bg-white p-5 rounded-xl border border-slate-200 shadow-sm flex items-start gap-4">
                        <div class="w-11 h-11 rounded-lg bg-brand-navy text-brand-amber flex items-center justify-center shrink-0">
                            <svg class="w-6 h-6" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M12 8c-1.657 0-3 .895-3 2s1.343 2 3 2 3 .895 3 2-1.343 2-3 2m0-8c1.11 0 2.08.402 2.599 1M12 8V7m0 1v8m0 0v1m0-1c-1.11 0-2.08-.402-2.599-1M21 12a9 9 0 11-18 0 9 9 0 0118 0z"/></svg>
                        </div>
                        <div>
                            <h3 class="font-bold text-brand-navy text-sm sm:text-base mb-1">Báo giá minh bạch, hợp lý</h3>
                            <p class="text-xs sm:text-sm text-slate-600 leading-relaxed">Dự toán chi tiết từng hạng mục vật tư, tối ưu ngân sách hợp lý nhất mà vẫn đảm bảo chất lượng thi công bền bỉ.</p>
                        </div>
                    </div>
                    <div class="bg-white p-5 rounded-xl border border-slate-200 shadow-sm flex items-start gap-4">
                        <div class="w-11 h-11 rounded-lg bg-brand-navy text-brand-amber flex items-center justify-center shrink-0">
                            <svg class="w-6 h-6" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M18.364 5.636l-3.536 3.536m0 5.656l3.536 3.536M9.172 9.172L5.636 5.636m3.536 9.192l-3.536 3.536M21 12a9 9 0 11-18 0 9 9 0 0118 0zm-5 0a4 4 0 11-8 0 4 4 0 018 0z"/></svg>
                        </div>
                        <div>
                            <h3 class="font-bold text-brand-navy text-sm sm:text-base mb-1">Hỗ trợ tư vấn miễn phí 24/7</h3>
                            <p class="text-xs sm:text-sm text-slate-600 leading-relaxed">Tư vấn pháp lý, xin phép xây dựng, thiết kế sơ bộ và dự toán chi phí hoàn toàn miễn phí qua Hotline &amp; Zalo.</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- =========================================================
         FLATSOME SECTION 4: DANH MỤC SẢN PHẨM & THI CÔNG THỰC TẾ
         - Sử dụng toàn bộ 9 ảnh thực tế thi công từ Google Drive
         - Danh mục gọn đẹp trên máy tính & điện thoại, không xuống dòng tên danh mục
         - Lưới 2 cột trên điện thoại, 4 cột trên máy tính
         - Không nhãn dán, tên sản phẩm đầy đủ không cắt chữ
         ========================================================= -->
    <section id="san-pham-thi-cong" class="py-10 sm:py-14 bg-white">
        <div class="hxd-container">
            <div class="text-center mb-5 sm:mb-7">
                <h2 class="flatsome-section-title text-lg sm:text-2xl font-extrabold text-brand-navy uppercase tracking-wide">
                    Danh Mục Thi Công Thực Tế
                </h2>
                <p class="text-xs sm:text-sm text-slate-500 mt-2">
                    Hình ảnh thực tế thi công xây dựng do đội ngũ Hùng Xây Dựng trực tiếp thực hiện
                </p>
            </div>

            <!-- Thanh danh mục sản phẩm gọn gàng, tên danh mục không bao giờ bị ngắt dòng -->
            <div class="flex flex-wrap items-center justify-center gap-1.5 sm:gap-2 mb-6 sm:mb-8" id="serviceFilterBar">
                <button type="button" data-filter="all" class="service-tab active px-3 sm:px-4 py-1.5 sm:py-2 rounded-lg text-[11px] sm:text-xs font-semibold whitespace-nowrap bg-brand-navy text-white transition-colors">
                    Tất cả
                </button>
                <button type="button" data-filter="phan-tho" class="service-tab px-3 sm:px-4 py-1.5 sm:py-2 rounded-lg text-[11px] sm:text-xs font-semibold whitespace-nowrap bg-slate-100 text-slate-700 hover:bg-brand-amber hover:text-white transition-colors">
                    Thi công phần thô
                </button>
                <button type="button" data-filter="tron-goi" class="service-tab px-3 sm:px-4 py-1.5 sm:py-2 rounded-lg text-[11px] sm:text-xs font-semibold whitespace-nowrap bg-slate-100 text-slate-700 hover:bg-brand-amber hover:text-white transition-colors">
                    Thi công trọn gói
                </button>
                <button type="button" data-filter="hoan-thien" class="service-tab px-3 sm:px-4 py-1.5 sm:py-2 rounded-lg text-[11px] sm:text-xs font-semibold whitespace-nowrap bg-slate-100 text-slate-700 hover:bg-brand-amber hover:text-white transition-colors">
                    Thi công hoàn thiện
                </button>
                <button type="button" data-filter="thiet-ke" class="service-tab px-3 sm:px-4 py-1.5 sm:py-2 rounded-lg text-[11px] sm:text-xs font-semibold whitespace-nowrap bg-slate-100 text-slate-700 hover:bg-brand-amber hover:text-white transition-colors">
                    Thiết kế kiến trúc – Nội thất
                </button>
                <button type="button" data-filter="cai-tao" class="service-tab px-3 sm:px-4 py-1.5 sm:py-2 rounded-lg text-[11px] sm:text-xs font-semibold whitespace-nowrap bg-slate-100 text-slate-700 hover:bg-brand-amber hover:text-white transition-colors">
                    Cải tạo – Sửa chữa
                </button>
            </div>

            <!-- Lưới sản phẩm/dịch vụ: 2 cột trên điện thoại, 3 cột tablet, 4 cột desktop -->
            <div id="serviceGrid" class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-3 sm:gap-5">
                <!-- Dữ liệu được render sạch qua JS để dễ dàng lọc & mở xem chi tiết -->
            </div>
        </div>
    </section>

    <!-- =========================================================
         FLATSOME SECTION 5: CÁC DỰ ÁN TIÊU BIỂU TẠI ĐÀ NẴNG
         - Sử dụng toàn bộ 10 ảnh dự án Đà Nẵng từ Google Drive
         - Chia danh mục chuẩn web mẫu: Nhà phố, Biệt thự, Khách sạn - Căn hộ, Văn phòng
         - Lưới 2 cột trên điện thoại, không nhãn dán, tên hiển thị trọn vẹn
         ========================================================= -->
    <section id="du-an-da-nang" class="py-10 sm:py-14 bg-brand-surface border-y border-slate-200">
        <div class="hxd-container">
            <div class="text-center mb-5 sm:mb-7">
                <h2 class="flatsome-section-title text-lg sm:text-2xl font-extrabold text-brand-navy uppercase tracking-wide">
                    Các Dự Án Tại Đà Nẵng
                </h2>
                <p class="text-xs sm:text-sm text-slate-500 mt-2">
                    Tổng hợp các công trình nhà ở, biệt thự, căn hộ và văn phòng đã bàn giao tại TP. Đà Nẵng
                </p>
            </div>

            <!-- Thanh lọc dự án Đà Nẵng gọn 1 dòng từng danh mục -->
            <div class="flex flex-wrap items-center justify-center gap-1.5 sm:gap-2 mb-6 sm:mb-8" id="projectFilterBar">
                <button type="button" data-filter="all" class="project-tab active px-3 sm:px-4 py-1.5 sm:py-2 rounded-lg text-[11px] sm:text-xs font-semibold whitespace-nowrap bg-brand-navy text-white transition-colors">
                    Tất cả
                </button>
                <button type="button" data-filter="nha-pho" class="project-tab px-3 sm:px-4 py-1.5 sm:py-2 rounded-lg text-[11px] sm:text-xs font-semibold whitespace-nowrap bg-white border border-slate-200 text-slate-700 hover:bg-brand-amber hover:text-white hover:border-brand-amber transition-colors">
                    Nhà phố
                </button>
                <button type="button" data-filter="biet-thu" class="project-tab px-3 sm:px-4 py-1.5 sm:py-2 rounded-lg text-[11px] sm:text-xs font-semibold whitespace-nowrap bg-white border border-slate-200 text-slate-700 hover:bg-brand-amber hover:text-white hover:border-brand-amber transition-colors">
                    Biệt thự
                </button>
                <button type="button" data-filter="khach-san" class="project-tab px-3 sm:px-4 py-1.5 sm:py-2 rounded-lg text-[11px] sm:text-xs font-semibold whitespace-nowrap bg-white border border-slate-200 text-slate-700 hover:bg-brand-amber hover:text-white hover:border-brand-amber transition-colors">
                    Khách sạn – Căn hộ
                </button>
                <button type="button" data-filter="van-phong" class="project-tab px-3 sm:px-4 py-1.5 sm:py-2 rounded-lg text-[11px] sm:text-xs font-semibold whitespace-nowrap bg-white border border-slate-200 text-slate-700 hover:bg-brand-amber hover:text-white hover:border-brand-amber transition-colors">
                    Văn phòng
                </button>
            </div>

            <!-- Lưới 10 dự án Đà Nẵng: 2 cột mobile, 3 cột tablet, 4 cột desktop -->
            <div id="projectGrid" class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-3 sm:gap-5">
                <!-- Render qua JS -->
            </div>
        </div>
    </section>

    <!-- =========================================================
         FLATSOME SECTION 6: DANH MỤC CÁC ĐỐI TÁC CUNG ỨNG VẬT TƯ
         ========================================================= -->
    <section id="doi-tac" class="py-10 sm:py-14 bg-white">
        <div class="hxd-container">
            <div class="text-center mb-7 sm:mb-9">
                <h2 class="flatsome-section-title text-lg sm:text-2xl font-extrabold text-brand-navy uppercase tracking-wide">
                    Đối Tác Đồng Hành
                </h2>
                <p class="text-xs sm:text-sm text-slate-500 mt-2">
                    Cam kết sử dụng 100% vật tư xây dựng chính hãng từ các thương hiệu uy tín hàng đầu
                </p>
            </div>

            <div class="grid grid-cols-2 sm:grid-cols-4 gap-3 sm:gap-5">
                <!-- Đối tác 1 -->
                <div class="h-20 sm:h-24 rounded-xl border border-slate-200 bg-brand-surface flex flex-col items-center justify-center px-3 text-center hover:border-brand-amber transition-colors">
                    <div class="text-sm sm:text-base font-extrabold tracking-wide text-brand-navy">THÉP HÒA PHÁT</div>
                    <div class="text-[10px] sm:text-xs text-slate-500 mt-0.5">Sắt thép kết cấu</div>
                </div>
                <!-- Đối tác 2 -->
                <div class="h-20 sm:h-24 rounded-xl border border-slate-200 bg-brand-surface flex flex-col items-center justify-center px-3 text-center hover:border-brand-amber transition-colors">
                    <div class="text-sm sm:text-base font-extrabold tracking-wide text-brand-navy">XI MĂNG SÔNG GIANH</div>
                    <div class="text-[10px] sm:text-xs text-slate-500 mt-0.5">Xi măng công trình</div>
                </div>
                <!-- Đối tác 3 -->
                <div class="h-20 sm:h-24 rounded-xl border border-slate-200 bg-brand-surface flex flex-col items-center justify-center px-3 text-center hover:border-brand-amber transition-colors">
                    <div class="text-sm sm:text-base font-extrabold tracking-wide text-brand-navy">SƠN DULUX</div>
                    <div class="text-[10px] sm:text-xs text-slate-500 mt-0.5">Sơn nội ngoại thất</div>
                </div>
                <!-- Đối tác 4 -->
                <div class="h-20 sm:h-24 rounded-xl border border-slate-200 bg-brand-surface flex flex-col items-center justify-center px-3 text-center hover:border-brand-amber transition-colors">
                    <div class="text-sm sm:text-base font-extrabold tracking-wide text-brand-navy">CADIVI</div>
                    <div class="text-[10px] sm:text-xs text-slate-500 mt-0.5">Dây cáp điện âm tường</div>
                </div>
                <!-- Đối tác 5 -->
                <div class="h-20 sm:h-24 rounded-xl border border-slate-200 bg-brand-surface flex flex-col items-center justify-center px-3 text-center hover:border-brand-amber transition-colors">
                    <div class="text-sm sm:text-base font-extrabold tracking-wide text-brand-navy">NHỰA BÌNH MINH</div>
                    <div class="text-[10px] sm:text-xs text-slate-500 mt-0.5">Hệ thống cấp thoát nước</div>
                </div>
                <!-- Đối tác 6 -->
                <div class="h-20 sm:h-24 rounded-xl border border-slate-200 bg-brand-surface flex flex-col items-center justify-center px-3 text-center hover:border-brand-amber transition-colors">
                    <div class="text-sm sm:text-base font-extrabold tracking-wide text-brand-navy">NHÔM XINGFA</div>
                    <div class="text-[10px] sm:text-xs text-slate-500 mt-0.5">Cửa nhôm kính cao cấp</div>
                </div>
                <!-- Đối tác 7 -->
                <div class="h-20 sm:h-24 rounded-xl border border-slate-200 bg-brand-surface flex flex-col items-center justify-center px-3 text-center hover:border-brand-amber transition-colors">
                    <div class="text-sm sm:text-base font-extrabold tracking-wide text-brand-navy">ĐỒNG TÂM GROUP</div>
                    <div class="text-[10px] sm:text-xs text-slate-500 mt-0.5">Gạch ốp lát &amp; ngói</div>
                </div>
                <!-- Đối tác 8 -->
                <div class="h-20 sm:h-24 rounded-xl border border-slate-200 bg-brand-surface flex flex-col items-center justify-center px-3 text-center hover:border-brand-amber transition-colors">
                    <div class="text-sm sm:text-base font-extrabold tracking-wide text-brand-navy">GỖ AN CƯỜNG</div>
                    <div class="text-[10px] sm:text-xs text-slate-500 mt-0.5">Vật liệu nội thất</div>
                </div>
            </div>
        </div>
    </section>

    <!-- =========================================================
         FLATSOME SECTION 7: FORM YÊU CẦU TƯ VẤN & BÁO GIÁ TRANG CHỦ
         (Giống mẫu Miễn Phí Tư Vấn trên tintruongthinh.com)
         ========================================================= -->
    <section id="bao-gia" class="py-10 sm:py-14 bg-brand-navy text-white">
        <div class="hxd-container">
            <div class="grid grid-cols-1 lg:grid-cols-12 gap-8 items-center">
                <!-- Cột thông tin cam kết -->
                <div class="lg:col-span-5 space-y-4">
                    <div class="text-xs font-bold uppercase tracking-widest text-brand-amber">Miễn Phí Tư Vấn &amp; Khảo Sát</div>
                    <h2 class="text-2xl sm:text-3xl font-extrabold leading-snug">
                        YÊU CẦU TƯ VẤN &amp; BÁO GIÁ THI CÔNG TRỌN GÓI
                    </h2>
                    <p class="text-sm text-slate-300 leading-relaxed">
                        Để lại thông tin công trình dự kiến của bạn, kỹ sư <strong>HÙNG XÂY DỰNG</strong> sẽ liên hệ tư vấn phương án thiết kế và gửi bảng dự toán chi tiết hoàn toàn miễn phí trong vòng 30 phút.
                    </p>
                    <ul class="space-y-2.5 text-sm text-slate-200 pt-1">
                        <li class="flex items-center gap-2.5">
                            <span class="w-5 h-5 rounded-full bg-brand-amber text-white flex items-center justify-center text-xs font-bold shrink-0">✓</span>
                            <span>Khảo sát thực tế mặt bằng miễn phí tại TP. Đà Nẵng</span>
                        </li>
                        <li class="flex items-center gap-2.5">
                            <span class="w-5 h-5 rounded-full bg-brand-amber text-white flex items-center justify-center text-xs font-bold shrink-0">✓</span>
                            <span>Bóc tách dự toán vật tư rõ ràng, không phát sinh</span>
                        </li>
                        <li class="flex items-center gap-2.5">
                            <span class="w-5 h-5 rounded-full bg-brand-amber text-white flex items-center justify-center text-xs font-bold shrink-0">✓</span>
                            <span>Hỗ trợ hồ sơ xin giấy phép xây dựng nhanh chóng</span>
                        </li>
                    </ul>
                    <div class="pt-2">
                        <a href="tel:0903609581" class="inline-flex items-center gap-2 text-brand-amber font-extrabold text-lg hover:underline">
                            <svg class="w-5 h-5" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M3 5a2 2 0 012-2h3.28a1 1 0 01.948.684l1.498 4.493a1 1 0 01-.502 1.21l-2.257 1.13a11.042 11.042 0 005.516 5.516l1.13-2.257a1 1 0 011.21-.502l4.493 1.498a1 1 0 01.684.949V19a2 2 0 01-2 2h-1C9.716 21 3 14.284 3 6V5z"/></svg>
                            <span>Hotline tư vấn trực tiếp: 0903.609.581</span>
                        </a>
                    </div>
                </div>

                <!-- Cột Form điền thông tin -->
                <div class="lg:col-span-7 bg-white text-slate-800 rounded-xl p-5 sm:p-7 shadow-xl">
                    <form id="quoteForm" class="space-y-4">
                        <div class="grid grid-cols-1 sm:grid-cols-2 gap-4">
                            <div>
                                <label for="qName" class="block text-xs font-bold text-brand-navy mb-1.5">Họ và tên *</label>
                                <input id="qName" type="text" required placeholder="Nhập họ tên của bạn" class="w-full px-3.5 py-2.5 rounded-lg border border-slate-300 text-sm focus:outline-none focus:border-brand-amber focus:ring-2 focus:ring-brand-amber/20">
                            </div>
                            <div>
                                <label for="qPhone" class="block text-xs font-bold text-brand-navy mb-1.5">Số điện thoại *</label>
                                <input id="qPhone" type="tel" required placeholder="Nhập số điện thoại / Zalo" class="w-full px-3.5 py-2.5 rounded-lg border border-slate-300 text-sm focus:outline-none focus:border-brand-amber focus:ring-2 focus:ring-brand-amber/20">
                            </div>
                        </div>

                        <div class="grid grid-cols-1 sm:grid-cols-2 gap-4">
                            <div>
                                <label for="qType" class="block text-xs font-bold text-brand-navy mb-1.5">Loại công trình</label>
                                <select id="qType" class="w-full px-3.5 py-2.5 rounded-lg border border-slate-300 text-sm bg-white focus:outline-none focus:border-brand-amber focus:ring-2 focus:ring-brand-amber/20">
                                    <option value="Nhà phố">Nhà phố</option>
                                    <option value="Biệt thự">Biệt thự</option>
                                    <option value="Khách sạn - Căn hộ - Phòng trọ">Khách sạn – Căn hộ cho thuê – Phòng trọ</option>
                                    <option value="Văn phòng">Văn phòng / Showroom</option>
                                    <option value="Cải tạo sửa chữa">Cải tạo – Sửa chữa nhà ở</option>
                                </select>
                            </div>
                            <div>
                                <label for="qBudget" class="block text-xs font-bold text-brand-navy mb-1.5">Mức đầu tư dự kiến</label>
                                <select id="qBudget" class="w-full px-3.5 py-2.5 rounded-lg border border-slate-300 text-sm bg-white focus:outline-none focus:border-brand-amber focus:ring-2 focus:ring-brand-amber/20">
                                    <option value="Chưa xác định">Chưa xác định</option>
                                    <option value="Dưới 500 triệu">Dưới 500 triệu</option>
                                    <option value="500 triệu - 1 tỷ">500 triệu – 1 tỷ</option>
                                    <option value="1 tỷ - 2 tỷ">1 tỷ – 2 tỷ</option>
                                    <option value="2 tỷ - 3 tỷ">2 tỷ – 3 tỷ</option>
                                    <option value="Trên 3 tỷ">Trên 3 tỷ</option>
                                </select>
                            </div>
                        </div>

                        <div>
                            <label for="qNote" class="block text-xs font-bold text-brand-navy mb-1.5">Mô tả diện tích &amp; yêu cầu thi công</label>
                            <textarea id="qNote" rows="3" placeholder="Ví dụ: Xây nhà phố 3 tầng diện tích 5x20m tại Hòa Xuân, Đà Nẵng..." class="w-full px-3.5 py-2.5 rounded-lg border border-slate-300 text-sm focus:outline-none focus:border-brand-amber focus:ring-2 focus:ring-brand-amber/20"></textarea>
                        </div>

                        <button type="submit" class="w-full py-3 rounded-lg bg-brand-amber hover:bg-brand-amberDark text-white font-extrabold text-sm uppercase tracking-wider transition-colors shadow-md">
                            Gửi Yêu Cầu Nhận Báo Giá Ngay
                        </button>
                    </form>

                    <!-- Thông báo gửi thành công trực tiếp (không dùng alert) -->
                    <div id="quoteSuccessBox" class="hidden mt-4 p-4 rounded-lg bg-emerald-50 border border-emerald-200 text-emerald-800 text-sm">
                        <div class="font-bold mb-1">Đã tiếp nhận yêu cầu báo giá thành công!</div>
                        <div id="quoteSuccessText" class="text-xs sm:text-sm"></div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- =========================================================
         FLATSOME SECTION 8: DANH MỤC CÁC BÀI VIẾT TRANG CHỦ (TIN TỨC)
         ========================================================= -->
    <section id="tin-tuc" class="py-10 sm:py-14 bg-white">
        <div class="hxd-container">
            <div class="text-center mb-7 sm:mb-9">
                <h2 class="flatsome-section-title text-lg sm:text-2xl font-extrabold text-brand-navy uppercase tracking-wide">
                    Tin Tức &amp; Kinh Nghiệm Xây Dựng
                </h2>
                <p class="text-xs sm:text-sm text-slate-500 mt-2">
                    Cẩm nang kỹ thuật thi công, kinh nghiệm chuẩn bị xây nhà và cập nhật đơn giá tại Đà Nẵng
                </p>
            </div>

            <div id="newsGrid" class="grid grid-cols-2 lg:grid-cols-4 gap-3 sm:gap-5">
                <!-- Render danh sách bài viết qua JS để mở đọc nhanh trong modal -->
            </div>
        </div>
    </section>

    <!-- =========================================================
         FLATSOME SECTION 9: FANPAGE & BẢN ĐỒ GOOGLE MAP ĐÀ NẴNG
         Đưa cả Fanpage và Google Map trực tiếp ra ngoài trang chủ
         ========================================================= -->
    <section id="lien-he" class="py-10 sm:py-14 bg-brand-surface border-t border-slate-200">
        <div class="hxd-container">
            <div class="text-center mb-7 sm:mb-9">
                <h2 class="flatsome-section-title text-lg sm:text-2xl font-extrabold text-brand-navy uppercase tracking-wide">
                    Kết Nối Fanpage &amp; Bản Đồ Chỉ Đường
                </h2>
            </div>

            <div class="grid grid-cols-1 lg:grid-cols-12 gap-5 sm:gap-6 items-stretch">
                <!-- Cột Trái: Khung Fanpage Hùng Xây Dựng đưa ra ngoài trang chủ -->
                <div class="lg:col-span-5 bg-white rounded-xl border border-slate-200 shadow-sm overflow-hidden flex flex-col">
                    <div class="px-4 py-3 bg-brand-navy text-white flex items-center justify-between">
                        <div class="flex items-center gap-2 font-bold text-sm">
                            <svg class="w-4 h-4 text-brand-amber" fill="currentColor" viewBox="0 0 24 24"><path d="M22 12c0-5.523-4.477-10-10-10S2 6.477 2 12c0 4.991 3.657 9.128 8.438 9.878v-6.987h-2.54V12h2.54V9.797c0-2.506 1.492-3.89 3.777-3.89 1.094 0 2.238.195 2.238.195v2.46h-1.26c-1.243 0-1.63.771-1.63 1.562V12h2.773l-.443 2.89h-2.33v6.988C18.343 21.128 22 16.991 22 12z"/></svg>
                            <span>Fanpage Chính Thức</span>
                        </div>
                        <span class="text-[11px] text-slate-300">Facebook</span>
                    </div>

                    <!-- Giao diện Page Plugin Fanpage hiển thị đẹp & ổn định mọi trình duyệt -->
                    <div class="p-4 flex-1 flex flex-col justify-between gap-4">
                        <div class="rounded-xl overflow-hidden border border-slate-200">
                            <div class="relative h-32 bg-brand-navy">
                                <img
                                    src="https://lh3.googleusercontent.com/d/1FVfIU7HJM8cAb-lO7wnjGvji6ZEvl7ff=w800"
                                    data-fallback="https://drive.google.com/thumbnail?id=1FVfIU7HJM8cAb-lO7wnjGvji6ZEvl7ff&sz=w800"
                                    alt="Ảnh bìa Fanpage Hùng Xây Dựng"
                                    class="hxd-drive-img w-full h-full object-cover opacity-80"
                                >
                                <div class="absolute inset-0 bg-gradient-to-t from-black/80 via-black/30 to-transparent"></div>
                                <div class="absolute bottom-3 left-3 right-3 flex items-center gap-3">
                                    <div class="w-12 h-12 rounded-lg bg-white p-1 shadow-md shrink-0 flex items-center justify-center">
                                        <svg class="w-full h-full" viewBox="0 0 64 64" fill="none">
                                            <rect width="64" height="64" rx="10" fill="#0F2B46"/>
                                            <path d="M13 27.5L32 12L51 27.5" stroke="#E58A00" stroke-width="4.5" stroke-linecap="round" stroke-linejoin="round"/>
                                            <path d="M21 26V50H27.5V39H36.5V50H43V26" stroke="#FFFFFF" stroke-width="4.5" stroke-linecap="round" stroke-linejoin="round"/>
                                        </svg>
                                    </div>
                                    <div class="text-white min-w-0">
                                        <div class="font-bold text-sm leading-tight">HÙNG XÂY DỰNG - TP. Đà Nẵng</div>
                                        <div class="text-[11px] text-slate-200 mt-0.5">Thiết kế &amp; Thi công xây dựng trọn gói</div>
                                    </div>
                                </div>
                            </div>
                            <div class="p-3.5 bg-slate-50 space-y-2.5">
                                <p class="text-xs text-slate-600 leading-relaxed">
                                    Cập nhật hình ảnh tiến độ công trình hàng ngày tại Hòa Xuân, Sơn Trà, Hải Châu, Liên Chiểu... Theo dõi Fanpage để nhận mẫu nhà đẹp và ưu đãi miễn phí thiết kế khi ký hợp đồng thi công.
                                </p>
                                <div class="flex items-center gap-2 pt-1">
                                    <a href="https://www.facebook.com/" target="_blank" rel="noopener noreferrer" class="flex-1 py-2 px-3 rounded-lg bg-[#1877F2] hover:bg-[#1465D0] text-white text-xs font-bold text-center transition-colors">
                                        Theo Dõi Fanpage
                                    </a>
                                    <a href="https://zalo.me/0903609581" target="_blank" rel="noopener noreferrer" class="flex-1 py-2 px-3 rounded-lg bg-brand-navy hover:bg-brand-navyLight text-white text-xs font-bold text-center transition-colors">
                                        Nhắn Tin Tư Vấn
                                    </a>
                                </div>
                            </div>
                        </div>

                        <div class="rounded-xl bg-brand-surface p-3.5 border border-slate-200 text-xs space-y-1.5 text-slate-700">
                            <div><strong class="text-brand-navy">Địa chỉ:</strong> TP. Đà Nẵng</div>
                            <div><strong class="text-brand-navy">Hotline / Zalo:</strong> <a href="tel:0903609581" class="text-brand-amber font-bold">0903.609.581</a></div>
                            <div><strong class="text-brand-navy">Website:</strong> hungxaydung.com</div>
                        </div>
                    </div>
                </div>

                <!-- Cột Phải: Bản đồ Google Map TP. Đà Nẵng đưa trực tiếp ra trang chủ -->
                <div class="lg:col-span-7 bg-white rounded-xl border border-slate-200 shadow-sm overflow-hidden flex flex-col">
                    <div class="px-4 py-3 bg-brand-navy text-white flex items-center justify-between gap-2">
                        <div class="flex items-center gap-2 font-bold text-sm">
                            <svg class="w-4 h-4 text-brand-amber shrink-0" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M17.657 16.657L13.414 20.9a1.998 1.998 0 01-2.827 0l-4.244-4.243a8 8 0 1111.314 0z"/><path stroke-linecap="round" stroke-linejoin="round" d="M15 11a3 3 0 11-6 0 3 3 0 016 0z"/></svg>
                            <span>Bản Đồ Google Map – TP. Đà Nẵng</span>
                        </div>
                        <a href="https://www.google.com/maps/search/?api=1&query=TP+Da+Nang+Vietnam" target="_blank" rel="noopener noreferrer" class="text-[11px] font-semibold text-brand-amber hover:underline whitespace-nowrap">
                            Mở chỉ đường &rarr;
                        </a>
                    </div>
                    <div class="w-full flex-1 min-h-[280px] sm:min-h-[340px] bg-slate-100">
                        <iframe
                            title="Bản đồ Google Map Hùng Xây Dựng TP Đà Nẵng"
                            src="https://maps.google.com/maps?q=Da%20Nang%2C%20Vietnam&t=&z=13&ie=UTF8&iwloc=&output=embed"
                            class="w-full h-full min-h-[280px] sm:min-h-[340px] border-0"
                            loading="lazy"
                            referrerpolicy="no-referrer-when-downgrade"
                            allowfullscreen>
                        </iframe>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- =========================================================
         FLATSOME FOOTER (Chân trang chuẩn 4 cột gọn đẹp)
         ========================================================= -->
    <footer class="bg-brand-navyDark text-slate-300 pt-10 pb-6 border-t-4 border-brand-amber">
        <div class="hxd-container">
            <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-7 pb-8 border-b border-white/10">
                <!-- Cột 1: Thông tin thương hiệu -->
                <div class="space-y-3">
                    <div class="flex items-center gap-2.5">
                        <svg class="w-9 h-9 shrink-0" viewBox="0 0 64 64" fill="none">
                            <rect width="64" height="64" rx="10" fill="#18426B"/>
                            <path d="M13 27.5L32 12L51 27.5" stroke="#E58A00" stroke-width="4.5" stroke-linecap="round" stroke-linejoin="round"/>
                            <path d="M21 26V50H27.5V39H36.5V50H43V26" stroke="#FFFFFF" stroke-width="4.5" stroke-linecap="round" stroke-linejoin="round"/>
                        </svg>
                        <div class="leading-tight">
                            <div class="text-base font-extrabold text-white">HÙNG <span class="text-brand-amber">XÂY DỰNG</span></div>
                            <div class="text-[10px] uppercase tracking-wider text-slate-400">hungxaydung.com</div>
                        </div>
                    </div>
                    <p class="text-xs leading-relaxed text-slate-400">
                        Đơn vị thiết kế kiến trúc, thi công phần thô, hoàn thiện và xây nhà trọn gói chuyên nghiệp tại TP. Đà Nẵng.
                    </p>
                </div>

                <!-- Cột 2: Thông tin liên hệ -->
                <div class="space-y-2.5 text-xs">
                    <h3 class="text-sm font-bold text-white uppercase tracking-wide mb-2">Thông Tin Liên Hệ</h3>
                    <div><strong>Đơn vị:</strong> HÙNG XÂY DỰNG</div>
                    <div><strong>Địa chỉ:</strong> TP. Đà Nẵng</div>
                    <div><strong>Hotline / Zalo:</strong> <a href="tel:0903609581" class="text-brand-amber font-bold">0903.609.581</a></div>
                    <div><strong>Website:</strong> hungxaydung.com</div>
                </div>

                <!-- Cột 3: Lĩnh vực hoạt động -->
                <div class="space-y-2 text-xs">
                    <h3 class="text-sm font-bold text-white uppercase tracking-wide mb-2">Lĩnh Vực Hoạt Động</h3>
                    <ul class="space-y-1.5">
                        <li><a href="#san-pham-thi-cong" class="hover:text-brand-amber transition-colors">Thiết kế kiến trúc – Nội thất</a></li>
                        <li><a href="#san-pham-thi-cong" class="hover:text-brand-amber transition-colors">Thi công phần thô</a></li>
                        <li><a href="#san-pham-thi-cong" class="hover:text-brand-amber transition-colors">Thi công hoàn thiện</a></li>
                        <li><a href="#san-pham-thi-cong" class="hover:text-brand-amber transition-colors">Xây nhà trọn gói Đà Nẵng</a></li>
                        <li><a href="#san-pham-thi-cong" class="hover:text-brand-amber transition-colors">Cải tạo &amp; sửa chữa nhà ở</a></li>
                    </ul>
                </div>

                <!-- Cột 4: Liên kết nhanh -->
                <div class="space-y-2 text-xs">
                    <h3 class="text-sm font-bold text-white uppercase tracking-wide mb-2">Danh Mục Trang</h3>
                    <ul class="space-y-1.5">
                        <li><a href="#gioi-thieu" class="hover:text-brand-amber transition-colors">Giới thiệu công ty</a></li>
                        <li><a href="#du-an-da-nang" class="hover:text-brand-amber transition-colors">Các dự án tại Đà Nẵng</a></li>
                        <li><a href="#doi-tac" class="hover:text-brand-amber transition-colors">Đối tác cung ứng vật tư</a></li>
                        <li><a href="#bao-gia" class="hover:text-brand-amber transition-colors">Yêu cầu báo giá</a></li>
                        <li><a href="#tin-tuc" class="hover:text-brand-amber transition-colors">Tin tức &amp; kinh nghiệm</a></li>
                    </ul>
                </div>
            </div>

            <div class="pt-5 flex flex-col sm:flex-row items-center justify-between gap-2 text-xs text-slate-400 text-center sm:text-left">
                <div>Copyright © 2026 <strong class="text-white">HÙNG XÂY DỰNG</strong> (hungxaydung.com). All rights reserved.</div>
                <div>Thiết kế tối ưu theo chuẩn Flatsome UX Builder</div>
            </div>
        </div>
    </footer>

    <!-- =========================================================
         CÁC NÚT LIÊN HỆ NỔI BẬT: ZALO, FACEBOOK, HOTLINE
         Tương thích hoàn hảo trên cả máy tính và điện thoại, không tràn viền
         ========================================================= -->
    <div class="fixed right-3 sm:right-5 bottom-4 sm:bottom-6 z-40 flex flex-col items-end gap-2.5 sm:gap-3">
        <!-- Nút Facebook -->
        <a href="https://www.facebook.com/" target="_blank" rel="noopener noreferrer" aria-label="Nhắn tin Facebook Hùng Xây Dựng"
           class="group flex items-center gap-2 bg-[#1877F2] hover:bg-[#1465D0] text-white rounded-full shadow-lg p-2.5 sm:px-4 sm:py-2.5 transition-all">
            <svg class="w-5 h-5 shrink-0" fill="currentColor" viewBox="0 0 24 24"><path d="M22 12c0-5.523-4.477-10-10-10S2 6.477 2 12c0 4.991 3.657 9.128 8.438 9.878v-6.987h-2.54V12h2.54V9.797c0-2.506 1.492-3.89 3.777-3.89 1.094 0 2.238.195 2.238.195v2.46h-1.26c-1.243 0-1.63.771-1.63 1.562V12h2.773l-.443 2.89h-2.33v6.988C18.343 21.128 22 16.991 22 12z"/></svg>
            <span class="hidden sm:inline text-xs font-bold whitespace-nowrap">Facebook</span>
        </a>

        <!-- Nút Zalo -->
        <a href="https://zalo.me/0903609581" target="_blank" rel="noopener noreferrer" aria-label="Chat Zalo Hùng Xây Dựng"
           class="group flex items-center gap-2 bg-[#0068FF] hover:bg-[#0055D4] text-white rounded-full shadow-lg p-2.5 sm:px-4 sm:py-2.5 transition-all">
            <span class="w-5 h-5 rounded-full bg-white text-[#0068FF] font-extrabold text-[10px] flex items-center justify-center shrink-0">Zalo</span>
            <span class="hidden sm:inline text-xs font-bold whitespace-nowrap">Chat Zalo</span>
        </a>

        <!-- Nút Hotline nổi bật có hiệu ứng sóng -->
        <a href="tel:0903609581" aria-label="Gọi Hotline 0903.609.581"
           class="hotline-ring relative flex items-center gap-2 bg-[#DC2626] hover:bg-[#B91C1C] text-white rounded-full shadow-xl p-3 sm:px-4 sm:py-2.5 transition-all">
            <svg class="w-5 h-5 shrink-0" fill="none" stroke="currentColor" stroke-width="2.2" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M3 5a2 2 0 012-2h3.28a1 1 0 01.948.684l1.498 4.493a1 1 0 01-.502 1.21l-2.257 1.13a11.042 11.042 0 005.516 5.516l1.13-2.257a1 1 0 011.21-.502l4.493 1.498a1 1 0 01.684.949V19a2 2 0 01-2 2h-1C9.716 21 3 14.284 3 6V5z"/></svg>
            <span class="hidden sm:inline text-xs font-extrabold whitespace-nowrap">0903.609.581</span>
        </a>
    </div>

    <!-- =========================================================
         MODAL XEM CHI TIẾT SẢN PHẨM / DỰ ÁN / BÀI VIẾT
         ========================================================= -->
    <div id="detailModal" class="fixed inset-0 z-50 hidden items-center justify-center p-3 sm:p-5 bg-black/70 backdrop-blur-sm">
        <div class="bg-white rounded-xl max-w-2xl w-full max-h-[90vh] overflow-y-auto shadow-2xl relative">
            <button id="closeModalBtn" type="button" aria-label="Đóng cửa sổ" class="sticky top-3 float-right mr-3 mt-3 z-10 w-9 h-9 rounded-full bg-brand-navy/90 hover:bg-brand-amber text-white flex items-center justify-center transition-colors">
                <svg class="w-5 h-5" fill="none" stroke="currentColor" stroke-width="2.5" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M6 18L18 6M6 6l12 12"/></svg>
            </button>
            <div class="p-4 sm:p-6 clear-both space-y-4">
                <div class="rounded-lg overflow-hidden bg-slate-100 aspect-[16/10]">
                    <img id="modalImage" src="" alt="" class="w-full h-full object-cover">
                </div>
                <div id="modalSubtitle" class="text-xs font-bold uppercase tracking-wider text-brand-amber"></div>
                <h3 id="modalTitle" class="text-lg sm:text-xl font-extrabold text-brand-navy leading-snug"></h3>
                <p id="modalDesc" class="text-sm text-slate-600 leading-relaxed whitespace-pre-line"></p>
                <div class="pt-3 border-t border-slate-200 flex flex-wrap gap-2.5">
                    <a href="tel:0903609581" class="flex-1 min-w-[140px] py-2.5 px-4 rounded-lg bg-brand-amber hover:bg-brand-amberDark text-white font-bold text-xs sm:text-sm text-center transition-colors">
                        Gọi Tư Vấn: 0903.609.581
                    </a>
                    <a href="https://zalo.me/0903609581" target="_blank" rel="noopener noreferrer" class="flex-1 min-w-[140px] py-2.5 px-4 rounded-lg bg-brand-navy hover:bg-brand-navyLight text-white font-bold text-xs sm:text-sm text-center transition-colors">
                        Nhận Báo Giá Qua Zalo
                    </a>
                </div>
            </div>
        </div>
    </div>

    <!-- =========================================================
         JAVASCRIPT ĐIỀU KHIỂN SLIDER, DỮ LIỆU ẢNH GOOGLE DRIVE & LỌC DANH MỤC
         ========================================================= -->
    <script>
        (function () {
            "use strict";

            // Hàm tạo đường dẫn ảnh Google Drive chuẩn + dự phòng tự động
            function getDriveUrl(id, size) {
                return `https://lh3.googleusercontent.com/d/${id}=w${size || 900}`;
            }
            function getDriveFallback(id, size) {
                return `https://drive.google.com/thumbnail?id=${id}&sz=w${size || 900}`;
            }
            function attachImgFallback(imgEl, id, label) {
                imgEl.addEventListener("error", function handleErr() {
                    if (!imgEl.dataset.triedThumb) {
                        imgEl.dataset.triedThumb = "1";
                        imgEl.src = getDriveFallback(id, 900);
                    } else {
                        imgEl.removeEventListener("error", handleErr);
                        const safeText = encodeURIComponent(label || "HÙNG XÂY DỰNG");
                        imgEl.src = `https://placehold.co/800x600/0F2B46/FFFFFF?text=${safeText}`;
                    }
                });
            }

            // Gắn fallback cho toàn bộ ảnh tĩnh trên trang
            document.querySelectorAll(".hxd-drive-img").forEach(function (img) {
                const match = img.src.match(/\/d\/([^=/?]+)/);
                if (match && match[1]) {
                    attachImgFallback(img, match[1], img.alt);
                }
            });

            // =========================================================
            // 1. DỮ LIỆU 9 ẢNH THỰC TẾ THI CÔNG XÂY DỰNG (GROUP A)
            // =========================================================
            const constructionItems = [
                {
                    id: "13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz",
                    category: "phan-tho",
                    categoryName: "Thi công phần thô",
                    title: "Thi Công Phần Thô Nhà Phố Kết Cấu Bê Tông Cốt Thép",
                    desc: "Thi công khung kết cấu cột, dầm, sàn và xây tường gạch chuẩn kỹ thuật cho nhà phố tại Đà Nẵng. Sử dụng sắt thép Hòa Phát và xi măng chính hãng, đảm bảo độ bền vững lâu dài cho toàn bộ công trình."
                },
                {
                    id: "1taZEEvo_cWqkQxBcCPhpoDRIIMQ-50eR",
                    category: "phan-tho",
                    categoryName: "Thi công phần thô",
                    title: "Thi Công Đổ Bê Tông Sàn Mái & Bảo Dưỡng Đúng Quy Trình",
                    desc: "Công tác ghép cốp pha, đan sắt sàn 2 lớp và đổ bê tông thương phẩm được kỹ sư Hùng Xây Dựng nghiệm thu chặt chẽ trước khi thi công, chống nứt và chống thấm hiệu quả."
                },
                {
                    id: "1Y1HUmEwHLU9YbOhwPzHpFwKQecXvLhUv",
                    category: "phan-tho",
                    categoryName: "Thi công phần thô",
                    title: "Thi Công Móng Băng, Đà Kiềng & Hệ Thống Cột Trụ",
                    desc: "Xử lý nền móng vững chắc phù hợp địa chất TP. Đà Nẵng, thi công thép móng đúng bản vẽ kết cấu và kiểm tra độ thẳng đứng của hệ cột trụ."
                },
                {
                    id: "1Wlhms5ZB_mL9OptenKvrBS-rGCP2xU1_",
                    category: "tron-goi",
                    categoryName: "Thi công trọn gói",
                    title: "Xây Nhà Trọn Gói Chìa Khóa Trao Tay 3 Tầng Hiện Đại",
                    desc: "Dịch vụ xây dựng trọn gói từ khâu thiết kế kiến trúc, xin phép xây dựng, thi công phần thô đến hoàn thiện bàn giao vào ở ngay. Cam kết không phát sinh chi phí ngoài hợp đồng."
                },
                {
                    id: "1bRJmtvTDnszz8dMG3_a3Z8hoL5igG-hO",
                    category: "hoan-thien",
                    categoryName: "Thi công hoàn thiện",
                    title: "Thi Công Tô Trát, Sơn Nước & Ốp Lát Hoàn Thiện Mặt Tiền",
                    desc: "Hạng mục hoàn thiện mặt tiền, xử lý chống thấm ngoài trời, ốp đá trang trí và lắp đặt hệ cửa nhôm kính đảm bảo thẩm mỹ sắc nét và bền màu trước thời tiết miền Trung."
                },
                {
                    id: "1_0OVVXoqQgYvoVEaZSC5iZh_SKGBbr-t",
                    category: "thiet-ke",
                    categoryName: "Thiết kế kiến trúc – Nội thất",
                    title: "Thiết Kế Kiến Trúc & Thi Công Biệt Thự Không Gian Mở",
                    desc: "Tư vấn thiết kế bản vẽ kiến trúc 3D, kết cấu, điện nước và triển khai thi công thực tế chuẩn theo phối cảnh, tối ưu ánh sáng tự nhiên và thông gió."
                },
                {
                    id: "1UB12E_spzIvo7TNREjBJXUV9o_HVWOv_",
                    category: "hoan-thien",
                    categoryName: "Thi công hoàn thiện",
                    title: "Thi Công Hoàn Thiện Trần Thạch Cao & Nội Thất Nhà Ở",
                    desc: "Hoàn thiện đồng bộ hệ thống điện chiếu sáng, trần thạch cao giật cấp, ốp lát sàn gỗ, gạch men và thiết bị vệ sinh chính hãng."
                },
                {
                    id: "1wHGqk7znpnGmrOjz4_EdpHnHK8xKyxkT",
                    category: "tron-goi",
                    categoryName: "Thi công trọn gói",
                    title: "Thi Công Trọn Gói Căn Hộ Cho Thuê & Nhà Phố Kinh Doanh",
                    desc: "Giải pháp xây dựng tối ưu chi phí đầu tư cho các chủ đầu tư căn hộ dịch vụ, nhà nghỉ, mặt bằng kinh doanh tại TP. Đà Nẵng."
                },
                {
                    id: "1-eBgG9wF3I6_gyPir2CmCnwJg4sP7Bnn",
                    category: "cai-tao",
                    categoryName: "Cải tạo – Sửa chữa",
                    title: "Cải Tạo, Nâng Tầng & Sửa Chữa Trọn Gói Nhà Ở Dân Dụng",
                    desc: "Khảo sát hiện trạng kết cấu, gia cố móng cột, cải tạo mặt tiền, chống thấm dột và làm mới toàn bộ không gian sống tiết kiệm chi phí."
                }
            ];

            // =========================================================
            // 2. DỮ LIỆU 10 DỰ ÁN TIÊU BIỂU TẠI ĐÀ NẴNG (GROUP B)
            // =========================================================
            const daNangProjects = [
                {
                    id: "157Suq0BLEh2zFs3X-uaNTN-ARDWhfjfT",
                    category: "nha-pho",
                    categoryName: "Nhà phố",
                    title: "Nhà Phố 3 Tầng Khu Đô Thị Hòa Xuân, Cẩm Lệ, Đà Nẵng",
                    desc: "Quy mô: 3 tầng hiện đại (100m²). Hạng mục: Thiết kế & thi công trọn gói chìa khóa trao tay tại KĐT Sinh Thái Hòa Xuân, TP. Đà Nẵng."
                },
                {
                    id: "1FVfIU7HJM8cAb-lO7wnjGvji6ZEvl7ff",
                    category: "biet-thu",
                    categoryName: "Biệt thự",
                    title: "Biệt Thự Hiện Đại Khu Nam Việt Á, Ngũ Hành Sơn, Đà Nẵng",
                    desc: "Quy mô: Biệt thự 2 tầng sân vườn rộng thoáng. Hạng mục: Thi công phần thô, hoàn thiện ngoại thất và nội thất cao cấp tại Quận Ngũ Hành Sơn."
                },
                {
                    id: "1wkzckXZhRrWh3V2GIOfdqBmOwQTBVFhz",
                    category: "khach-san",
                    categoryName: "Khách sạn – Căn hộ",
                    title: "Căn Hộ Cho Thuê Đường Võ Nguyên Giáp, Sơn Trà, Đà Nẵng",
                    desc: "Quy mô: 5 tầng gồm 14 căn hộ khép kín. Hạng mục: Thi công trọn gói đảm bảo tiêu chuẩn PCCC và thẩm mỹ thu hút khách du lịch."
                },
                {
                    id: "1I7lc3ghS0tyqh6Pq3xsZTidKsr0oT-8k",
                    category: "nha-pho",
                    categoryName: "Nhà phố",
                    title: "Nhà Phố 2 Mặt Tiền Đường Nguyễn Chánh, Liên Chiểu, Đà Nẵng",
                    desc: "Quy mô: 3 tầng 1 tum phong cách tối giản. Hạng mục: Thiết kế kiến trúc và thi công hoàn thiện trọn gói tại Quận Liên Chiểu."
                },
                {
                    id: "1Q8VoCbT7s09UNaoI8GNcYdvKpJ2wz78N",
                    category: "khach-san",
                    categoryName: "Khách sạn – Căn hộ",
                    title: "Khách Sạn Mini Ven Biển Mỹ Khê, Ngũ Hành Sơn, Đà Nẵng",
                    desc: "Quy mô: 6 tầng tiêu chuẩn lưu trú hiện đại. Hạng mục: Thi công phần thô, chống thấm toàn diện và hoàn thiện mặt đứng kiến trúc."
                },
                {
                    id: "1tkQlfZJTkaSunwOIMhfnzkEG2YHwxhML",
                    category: "biet-thu",
                    categoryName: "Biệt thự",
                    title: "Biệt Thự Vườn Khu Sinh Thái Hòa Quý, Ngũ Hành Sơn, Đà Nẵng",
                    desc: "Quy mô: Biệt thự mái Nhật 2 tầng thoáng mát. Hạng mục: Thi công xây dựng trọn gói, tiểu cảnh sân vườn và hệ thống hàng rào."
                },
                {
                    id: "1An7LyMVwj3rhKZlsVnYQ2UrLe48IeTBF",
                    category: "van-phong",
                    categoryName: "Văn phòng",
                    title: "Thi Công Trụ Sở Văn Phòng Quận Hải Châu, TP. Đà Nẵng",
                    desc: "Quy mô: Tòa nhà văn phòng 4 tầng mặt tiền kính hiện đại. Hạng mục: Thi công kết cấu, hoàn thiện không gian làm việc mở."
                },
                {
                    id: "1R1Da04pAYI9-NJz1IsAfa7pVKkuK7J-A",
                    category: "nha-pho",
                    categoryName: "Nhà phố",
                    title: "Nhà Phố Liền Kề Khu Đô Thị Phước Lý, Cẩm Lệ, Đà Nẵng",
                    desc: "Quy mô: Nhà phố 2 tầng 1 lửng tối ưu công năng cho gia đình trẻ. Hạng mục: Xây nhà trọn gói đúng tiến độ bàn giao."
                },
                {
                    id: "1FdQEsiEBrIW5TiN22dvzV5g6amDPp-80",
                    category: "khach-san",
                    categoryName: "Khách sạn – Căn hộ",
                    title: "Căn Hộ Dịch Vụ Đường Tiểu La, Quận Hải Châu, Đà Nẵng",
                    desc: "Quy mô: 4 tầng 1 tum gồm phòng studio full nội thất. Hạng mục: Thi công phần thô và hoàn thiện chìa khóa trao tay."
                },
                {
                    id: "1So_3V4rw1y7lHegiIkYmh2Z9UIdozAL4",
                    category: "van-phong",
                    categoryName: "Văn phòng",
                    title: "Thiết Kế & Thi Công Văn Phòng Quận Thanh Khê, Đà Nẵng",
                    desc: "Quy mô: 3 tầng kết hợp showroom trưng bày. Hạng mục: Cải tạo kết cấu, thi công mặt tiền và hoàn thiện nội thất đồng bộ."
                }
            ];

            // =========================================================
            // 3. DỮ LIỆU 4 BÀI VIẾT TIN TỨC TRANG CHỦ
            // =========================================================
            const newsItems = [
                {
                    id: "1taZEEvo_cWqkQxBcCPhpoDRIIMQ-50eR",
                    date: "Kinh nghiệm thi công",
                    title: "Hướng Dẫn Bảo Dưỡng Bê Tông Móng & Sàn Đúng Kỹ Thuật",
                    excerpt: "Bảo dưỡng bê tông đúng cách trong 7 ngày đầu giúp tăng cường độ chịu lực và hạn chế tối đa tình trạng rạn nứt chân chim.",
                    content: "Trong quá trình thi công phần thô, công đoạn bảo dưỡng bê tông sau khi đổ đóng vai trò quyết định đến tuổi thọ công trình.\n\n1. Giữ ẩm liên tục sau khi bê tông bắt đầu ninh kết (khoảng 4-6 giờ sau đổ).\n2. Che phủ bạt hoặc bao tải ẩm khi thời tiết nắng gắt tại Đà Nẵng để tránh mất nước đột ngột.\n3. Không đặt tải trọng nặng lên sàn mới đổ trong 7 ngày đầu tiên.\n\nLiên hệ Hùng Xây Dựng (0903.609.581) để được kỹ sư tư vấn quy trình thi công chuẩn xác nhất."
                },
                {
                    id: "1Wlhms5ZB_mL9OptenKvrBS-rGCP2xU1_",
                    date: "Cẩm nang xây nhà",
                    title: "03 Nỗi Lo Lớn Nhất Khi Xây Nhà Tại Đà Nẵng Và Cách Phòng Tránh",
                    excerpt: "Phát sinh chi phí, chậm tiến độ và chất lượng vật tư là 3 vấn đề chủ nhà cần kiểm soát ngay từ khi ký hợp đồng.",
                    content: "Khi chuẩn bị xây dựng tổ ấm, hầu hết gia chủ đều gặp 3 nỗi lo phổ biến:\n\n1. Phát sinh chi phí vượt ngân sách: Giải pháp là lập bản vẽ chi tiết và bảng bóc tách vật tư rõ ràng trước khi khởi công.\n2. Chậm tiến độ bàn giao: Hợp đồng cần ghi rõ từng mốc giai đoạn thi công và cam kết trách nhiệm nhà thầu.\n3. Vật tư không đúng chủng loại: Chủ đầu tư nên chọn nhà thầu minh bạch thương hiệu vật tư như Hòa Phát, Sông Gianh, Cadivi, Bình Minh...\n\nHùng Xây Dựng luôn đồng hành minh bạch cùng khách hàng từ ngày khởi công đến lúc bàn giao."
                },
                {
                    id: "1_0OVVXoqQgYvoVEaZSC5iZh_SKGBbr-t",
                    date: "Báo giá tham khảo",
                    title: "Kinh Nghiệm Chọn Gói Thi Công Phần Thô Hay Xây Nhà Trọn Gói",
                    excerpt: "So sánh ưu nhược điểm giữa hai hình thức xây dựng phổ biến giúp gia chủ tiết kiệm thời gian và tối ưu ngân sách.",
                    content: "Tùy vào quỹ thời gian và kinh nghiệm quản lý vật tư, gia chủ có thể cân nhắc:\n\n• Thi công phần thô & nhân công hoàn thiện: Phù hợp với gia chủ có thời gian tự đi chọn gạch ốp lát, thiết bị vệ sinh, sơn nước theo sở thích cá nhân.\n• Xây nhà trọn gói (Chìa khóa trao tay): Phù hợp với gia đình bận rộn, muốn đồng bộ thiết kế – thi công, quản lý trọn ngân sách không lo phát sinh và được bảo hành tổng thể từ một đầu mối duy nhất."
                },
                {
                    id: "1bRJmtvTDnszz8dMG3_a3Z8hoL5igG-hO",
                    date: "Kỹ thuật chống thấm",
                    title: "Giải Pháp Chống Thấm Tường & Sân Thượng Bền Bỉ Mùa Mưa Đà Nẵng",
                    excerpt: "Đặc thù mưa bão miền Trung đòi hỏi quy trình chống thấm cổ ống, sàn mái và tường ngoài phải được thi công bài bản.",
                    content: "Khí hậu mưa bão đặc trưng tại TP. Đà Nẵng dễ khiến tường ngoài và sân thượng bị thấm nếu xử lý sơ sài.\n\nTại Hùng Xây Dựng, mọi công trình đều áp dụng quy trình chống thấm 3 lớp: xử lý vệ sinh bề mặt bê tông, quét màng chống thấm đàn hồi cao tại cổ ống xuyên sàn – chân tường – sàn mái, và ngâm nước thử tải 48 giờ nghiệm thu trước khi lát gạch hoàn thiện."
                }
            ];

            // =========================================================
            // HÀM RENDER THẺ SẢN PHẨM / DỰ ÁN (KHÔNG NHÃN DÁN, 2 CỘT MOBILE, ĐỦ CHỮ)
            // =========================================================
            function renderCardGrid(containerId, items, filterKey) {
                const container = document.getElementById(containerId);
                if (!container) return;

                const filtered = filterKey === "all"
                    ? items
                    : items.filter(item => item.category === filterKey);

                container.innerHTML = "";
                filtered.forEach(function (item) {
                    const card = document.createElement("article");
                    card.className = "group bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition-all cursor-pointer flex flex-col";

                    card.innerHTML = `
                        <div class="w-full aspect-[4/3] bg-slate-100 overflow-hidden">
                            <img src="${getDriveUrl(item.id, 800)}" alt="${item.title}" loading="lazy" class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-500">
                        </div>
                        <div class="p-2.5 sm:p-4 flex-1 flex flex-col justify-between gap-1.5">
                            <div class="text-[10px] sm:text-[11px] font-semibold text-brand-amber leading-tight">
                                ${item.categoryName}
                            </div>
                            <h3 class="text-[12px] sm:text-sm font-bold text-brand-navy group-hover:text-brand-amber transition-colors leading-snug break-words">
                                ${item.title}
                            </h3>
                        </div>
                    `;

                    const imgEl = card.querySelector("img");
                    attachImgFallback(imgEl, item.id, item.title);

                    card.addEventListener("click", function () {
                        openModal(item.id, item.categoryName, item.title, item.desc);
                    });

                    container.appendChild(card);
                });
            }

            // Render tin tức trang chủ
            function renderNews() {
                const container = document.getElementById("newsGrid");
                if (!container) return;
                container.innerHTML = "";
                newsItems.forEach(function (post) {
                    const card = document.createElement("article");
                    card.className = "group bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition-all cursor-pointer flex flex-col";
                    card.innerHTML = `
                        <div class="w-full aspect-[16/10] bg-slate-100 overflow-hidden">
                            <img src="${getDriveUrl(post.id, 700)}" alt="${post.title}" loading="lazy" class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-500">
                        </div>
                        <div class="p-2.5 sm:p-4 flex-1 flex flex-col gap-1.5">
                            <div class="text-[10px] sm:text-[11px] font-semibold text-brand-amber">${post.date}</div>
                            <h3 class="text-[12px] sm:text-sm font-bold text-brand-navy group-hover:text-brand-amber transition-colors leading-snug break-words">
                                ${post.title}
                            </h3>
                            <p class="hidden sm:block text-xs text-slate-600 leading-relaxed mt-1">
                                ${post.excerpt}
                            </p>
                        </div>
                    `;
                    const imgEl = card.querySelector("img");
                    attachImgFallback(imgEl, post.id, post.title);

                    card.addEventListener("click", function () {
                        openModal(post.id, post.date, post.title, post.content);
                    });
                    container.appendChild(card);
                });
            }

            // Khởi tạo hiển thị ban đầu
            renderCardGrid("serviceGrid", constructionItems, "all");
            renderCardGrid("projectGrid", daNangProjects, "all");
            renderNews();

            // Xử lý lọc tab Danh mục thi công thực tế
            document.querySelectorAll(".service-tab").forEach(function (btn) {
                btn.addEventListener("click", function () {
                    document.querySelectorAll(".service-tab").forEach(function (b) {
                        b.classList.remove("bg-brand-navy", "text-white");
                        b.classList.add("bg-slate-100", "text-slate-700");
                    });
                    btn.classList.remove("bg-slate-100", "text-slate-700");
                    btn.classList.add("bg-brand-navy", "text-white");
                    renderCardGrid("serviceGrid", constructionItems, btn.dataset.filter);
                });
            });

            // Xử lý lọc tab Dự án tại Đà Nẵng
            document.querySelectorAll(".project-tab").forEach(function (btn) {
                btn.addEventListener("click", function () {
                    document.querySelectorAll(".project-tab").forEach(function (b) {
                        b.classList.remove("bg-brand-navy", "text-white", "border-brand-navy");
                        b.classList.add("bg-white", "text-slate-700", "border-slate-200");
                    });
                    btn.classList.remove("bg-white", "text-slate-700", "border-slate-200");
                    btn.classList.add("bg-brand-navy", "text-white", "border-brand-navy");
                    renderCardGrid("projectGrid", daNangProjects, btn.dataset.filter);
                });
            });

            // =========================================================
            // 4. ĐIỀU KHIỂN 2 BANNER TỰ TRƯỢT CHUYÊN NGHIỆP (Hỗ trợ vuốt cảm ứng)
            // =========================================================
            const slides = document.querySelectorAll(".banner-slide-item");
            const dots = document.querySelectorAll(".banner-dot");
            let currentSlide = 0;
            let sliderTimer = null;

            function showSlide(index) {
                currentSlide = (index + slides.length) % slides.length;
                slides.forEach(function (slide, idx) {
                    if (idx === currentSlide) {
                        slide.classList.remove("opacity-0", "invisible", "z-0");
                        slide.classList.add("opacity-100", "visible", "z-10");
                    } else {
                        slide.classList.remove("opacity-100", "visible", "z-10");
                        slide.classList.add("opacity-0", "invisible", "z-0");
                    }
                });
                dots.forEach(function (dot, idx) {
                    if (idx === currentSlide) {
                        dot.classList.remove("w-2.5", "bg-white/60");
                        dot.classList.add("w-7", "bg-brand-amber");
                    } else {
                        dot.classList.remove("w-7", "bg-brand-amber");
                        dot.classList.add("w-2.5", "bg-white/60");
                    }
                });
            }

            function startSlider() {
                stopSlider();
                sliderTimer = setInterval(function () {
                    showSlide(currentSlide + 1);
                }, 5000);
            }
            function stopSlider() {
                if (sliderTimer) clearInterval(sliderTimer);
            }

            document.getElementById("prevBannerBtn").addEventListener("click", function () {
                showSlide(currentSlide - 1);
                startSlider();
            });
            document.getElementById("nextBannerBtn").addEventListener("click", function () {
                showSlide(currentSlide + 1);
                startSlider();
            });
            dots.forEach(function (dot) {
                dot.addEventListener("click", function () {
                    showSlide(parseInt(dot.dataset.index, 10));
                    startSlider();
                });
            });

            // Hỗ trợ vuốt trái/phải trên điện thoại cho Banner
            const heroSlider = document.getElementById("heroSlider");
            let touchStartX = 0;
            heroSlider.addEventListener("touchstart", function (e) {
                touchStartX = e.changedTouches[0].screenX;
                stopSlider();
            }, { passive: true });
            heroSlider.addEventListener("touchend", function (e) {
                const diff = e.changedTouches[0].screenX - touchStartX;
                if (Math.abs(diff) > 40) {
                    showSlide(diff > 0 ? currentSlide - 1 : currentSlide + 1);
                }
                startSlider();
            }, { passive: true });
            heroSlider.addEventListener("mouseenter", stopSlider);
            heroSlider.addEventListener("mouseleave", startSlider);

            startSlider();

            // =========================================================
            // 5. MENU MOBILE OFF-CANVAS
            // =========================================================
            const mobileMenuBtn = document.getElementById("mobileMenuBtn");
            const closeMobileMenuBtn = document.getElementById("closeMobileMenuBtn");
            const mobileMenuOverlay = document.getElementById("mobileMenuOverlay");
            const mobileMenuDrawer = document.getElementById("mobileMenuDrawer");

            function openMobileMenu() {
                mobileMenuOverlay.classList.remove("hidden");
                mobileMenuDrawer.classList.remove("-translate-x-full");
            }
            function closeMobileMenu() {
                mobileMenuOverlay.classList.add("hidden");
                mobileMenuDrawer.classList.add("-translate-x-full");
            }

            mobileMenuBtn.addEventListener("click", openMobileMenu);
            closeMobileMenuBtn.addEventListener("click", closeMobileMenu);
            mobileMenuOverlay.addEventListener("click", closeMobileMenu);
            document.querySelectorAll(".mobile-nav-link").forEach(function (link) {
                link.addEventListener("click", closeMobileMenu);
            });

            // =========================================================
            // 6. MODAL CHI TIẾT CÔNG TRÌNH / DỰ ÁN / BÀI VIẾT
            // =========================================================
            const detailModal = document.getElementById("detailModal");
            const modalImage = document.getElementById("modalImage");
            const modalSubtitle = document.getElementById("modalSubtitle");
            const modalTitle = document.getElementById("modalTitle");
            const modalDesc = document.getElementById("modalDesc");
            const closeModalBtn = document.getElementById("closeModalBtn");

            function openModal(imgId, subtitle, title, desc) {
                modalImage.dataset.triedThumb = "";
                modalImage.src = getDriveUrl(imgId, 1200);
                modalImage.alt = title;
                attachImgFallback(modalImage, imgId, title);
                modalSubtitle.textContent = subtitle;
                modalTitle.textContent = title;
                modalDesc.textContent = desc;
                detailModal.classList.remove("hidden");
                detailModal.classList.add("flex");
                document.body.style.overflow = "hidden";
            }

            function closeModal() {
                detailModal.classList.add("hidden");
                detailModal.classList.remove("flex");
                document.body.style.overflow = "";
            }

            closeModalBtn.addEventListener("click", closeModal);
            detailModal.addEventListener("click", function (e) {
                if (e.target === detailModal) closeModal();
            });
            document.addEventListener("keydown", function (e) {
                if (e.key === "Escape") closeModal();
            });

            // =========================================================
            // 7. XỬ LÝ FORM YÊU CẦU TƯ VẤN & BÁO GIÁ (KHÔNG DÙNG ALERT)
            // =========================================================
            const quoteForm = document.getElementById("quoteForm");
            const quoteSuccessBox = document.getElementById("quoteSuccessBox");
            const quoteSuccessText = document.getElementById("quoteSuccessText");

            quoteForm.addEventListener("submit", function (e) {
                e.preventDefault();
                const name = document.getElementById("qName").value.trim();
                const phone = document.getElementById("qPhone").value.trim();
                const type = document.getElementById("qType").value;
                const budget = document.getElementById("qBudget").value;

                if (!name || !phone) return;

                quoteSuccessText.textContent = `Cảm ơn ${name} (${phone}) đã gửi yêu cầu báo giá hạng mục "${type}" (${budget}). Kỹ sư Hùng Xây Dựng sẽ liên hệ tư vấn sớm nhất hoặc bạn có thể gọi trực tiếp 0903.609.581.`;
                quoteSuccessBox.classList.remove("hidden");
                quoteForm.reset();
            });
        })();
    </script>
</body>
</html>
