<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
    <title>CÔNG TY TNHH TM-DV MINH CHÂU STONE - Thi Công & Đánh Bóng Đá Đà Nẵng</title>
    <meta name="description" content="CÔNG TY TNHH TM-DV MINH CHÂU STONE chuyên đánh bóng sàn đá Marble, Granite, mài sàn bê tông, thi công đá mài Terrazzo, Sơn Epoxy và Microcement uy tín tại Đà Nẵng.">
    
    <!-- Open Graph Thumbnail là Logo trang web khi gửi link chia sẻ -->
    <meta property="og:type" content="website">
    <meta property="og:url" content="https://minhchaustone.com/">
    <meta property="og:title" content="CÔNG TY TNHH TM-DV MINH CHÂU STONE - minhchaustone.com">
    <meta property="og:description" content="Đơn vị chuyên đánh bóng sàn đá, mài sàn bê tông, thi công đá mài Terrazzo, Sơn Epoxy, Microcement chuyên nghiệp tại Đà Nẵng.">
    <meta property="og:image" content="https://drive.google.com/thumbnail?id=11N1b7m-M43TQlNNmNUDPbXiDRWtZwVYB&sz=w1200">
    <link rel="icon" href="https://drive.google.com/thumbnail?id=11N1b7m-M43TQlNNmNUDPbXiDRWtZwVYB&sz=w200">

    <!-- Thư viện Tailwind CSS & Font Awesome & Google Fonts -->
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&display=swap" rel="stylesheet">

    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        mc: {
                            dark: '#0c2340',     /* Xanh Navy đậm theo tông màu Logo Stone */
                            primary: '#163e6c',  /* Xanh chủ đạo */
                            accent: '#c59b27',   /* Vàng đồng/kim sang trọng */
                            light: '#f4f7fa'
                        }
                    },
                    maxWidth: {
                        '1500': '1500px'
                    }
                }
            }
        }
    </script>

    <style>
        /* CẤU HÌNH CHỐNG TRÀN VIỀN & LỆCH PHẢI TUYỆT ĐỐI */
        *, *::before, *::after {
            box-sizing: border-box;
        }
        html, body {
            width: 100%;
            max-width: 100vw;
            overflow-x: hidden !important;
            margin: 0;
            padding: 0;
            font-family: 'Inter', sans-serif;
            background-color: #f8fafc;
            color: #1e293b;
            scroll-behavior: smooth;
        }

        /* KHUNG GIAO DIỆN CHUẨN FLATSOME 1500PX TRÊN MÁY TÍNH */
        .flatsome-container {
            width: 100%;
            max-width: 1500px;
            margin-left: auto;
            margin-right: auto;
            padding-left: 15px;
            padding-right: 15px;
        }

        /* TỐI ƯU MENU DANH MỤC TRÊN MÁY TÍNH: NẰM TRÊN 1 HÀNG HOẶC HÀNG 2, KHÔNG NGẮT TỪ */
        .desktop-nav-list {
            display: flex;
            flex-wrap: wrap;
            align-items: center;
            justify-content: center;
            gap: 4px 14px;
        }
        .desktop-nav-item {
            white-space: nowrap !important;
            font-size: 13px;
            font-weight: 700;
            text-transform: uppercase;
            letter-spacing: 0.01em;
            padding: 8px 10px;
            border-radius: 6px;
            transition: all 0.2s ease;
            color: #0c2340;
            display: inline-flex;
            align-items: center;
            gap: 5px;
        }
        .desktop-nav-item:hover, .desktop-nav-item.active {
            background-color: #163e6c;
            color: #ffffff;
        }

        /* TỐI ƯU CHIP DANH MỤC Ở TRANG CHỦ: CHỮ NHỎ GỌN, LIỀN 1 HÀNG TRÊN TỪNG MỤC */
        .category-pill {
            white-space: nowrap !important;
            font-size: 12.5px;
            font-weight: 600;
            padding: 7px 14px;
            border-radius: 6px;
            border: 1px solid #cbd5e1;
            background: #ffffff;
            color: #0c2340;
            transition: all 0.2s ease;
            cursor: pointer;
            display: inline-flex;
            align-items: center;
            gap: 6px;
        }
        .category-pill:hover, .category-pill.active {
            background: #0c2340;
            color: #ffffff;
            border-color: #0c2340;
        }

        /* TIÊU ĐỀ SECTION PHONG CÁCH FLATSOME (SECTION-TITLE-CENTER) */
        .ux-section-title {
            display: flex;
            align-items: center;
            justify-content: center;
            margin-bottom: 1.5rem;
            width: 100%;
        }
        .ux-section-title b {
            flex: 1;
            height: 2px;
            background-color: #cbd5e1;
        }
        .ux-section-title span {
            padding: 0 18px;
            font-weight: 800;
            text-transform: uppercase;
            color: #0c2340;
            text-align: center;
            font-size: 1.15rem;
            letter-spacing: 0.03em;
        }
        @media (min-width: 768px) {
            .ux-section-title span {
                font-size: 1.4rem;
            }
        }

        /* TÊN SẢN PHẨM ĐẦY ĐỦ KHÔNG BỊ CẮT CHỮ HAY TRÀN RA NGOÀI */
        .product-title-full {
            white-space: normal !important;
            overflow: visible !important;
            text-overflow: unset !important;
            word-break: break-word;
            line-height: 1.38;
        }

        /* NÚT LIÊN HỆ NỔI BẬT CÓ HIỆU ỨNG SÓNG */
        @keyframes pulse-ring {
            0% { transform: scale(0.95); box-shadow: 0 0 0 0 rgba(22, 62, 108, 0.6); }
            70% { transform: scale(1); box-shadow: 0 0 0 10px rgba(22, 62, 108, 0); }
            100% { transform: scale(0.95); box-shadow: 0 0 0 0 rgba(22, 62, 108, 0); }
        }
        .pulse-btn {
            animation: pulse-ring 2s infinite;
        }
    </style>
</head>
<body class="flex flex-col min-h-screen">

    <!-- ===================================================================== -->
    <!-- TOP BAR ĐƠN GIẢN CHUẨN FLATSOME (KHÔNG CÓ THANH CÔNG CỤ UX BUILDER) -->
    <!-- ===================================================================== -->
    <div class="bg-mc-dark text-white text-xs py-2 border-b border-slate-700 w-full">
        <div class="flatsome-container flex flex-wrap justify-between items-center gap-2">
            <div class="flex items-center gap-2 truncate max-w-full">
                <i class="fa-solid fa-location-dot text-mc-accent shrink-0"></i>
                <span class="truncate">Thửa đất số 217, Tờ bản đồ số 159, Lô 46-B2.21, TĐC Tân Trà, P. Ngũ Hành Sơn, TP Đà Nẵng</span>
            </div>
            <div class="hidden md:flex items-center gap-5 shrink-0 font-medium">
                <span><i class="fa-solid fa-globe text-mc-accent mr-1.5"></i>minhchaustone.com</span>
                <span><i class="fa-solid fa-phone-volume text-mc-accent mr-1.5"></i>0975.796.543 - 0355.698.490</span>
            </div>
        </div>
    </div>

    <!-- ===================================================================== -->
    <!-- HEADER CHÍNH (LOGO NHỎ GỌN, MENU 1 HÀNG, KHÔNG ĐỂ NÚT GỌI NGAY)      -->
    <!-- ===================================================================== -->
    <header class="bg-white shadow-sm sticky top-0 z-40 w-full border-b border-slate-200">
        <div class="flatsome-container py-2.5 flex items-center justify-between gap-3">
            
            <!-- Logo chỉnh gọn nhỏ lại + Tên công ty -->
            <a href="#top" class="flex items-center gap-2.5 shrink-0 group max-w-[82%] sm:max-w-none">
                <div class="w-11 h-11 md:w-12 md:h-12 rounded-lg border border-slate-200 bg-white p-1 flex items-center justify-center overflow-hidden shrink-0 shadow-sm">
                    <img src="https://drive.google.com/thumbnail?id=11N1b7m-M43TQlNNmNUDPbXiDRWtZwVYB&sz=w400" 
                         alt="Logo Minh Châu Stone" 
                         class="max-h-9 md:max-h-10 w-auto object-contain"
                         onerror="this.onerror=null;this.src='https://placehold.co/120x120/0c2340/c59b27?text=MC+STONE';">
                </div>
                <div class="leading-tight overflow-hidden">
                    <span class="block font-extrabold text-mc-dark text-sm sm:text-base md:text-lg tracking-tight truncate">MINH CHÂU STONE</span>
                    <span class="block text-[10.5px] sm:text-xs text-slate-500 font-medium truncate">CÔNG TY TNHH TM-DV MINH CHÂU STONE</span>
                </div>
            </a>

            <!-- Danh mục trên máy tính: Viết liền trên 1 hàng chữ nhỏ gọn, không xuống dòng từng mục -->
            <nav class="hidden lg:block flex-1 px-2">
                <ul class="desktop-nav-list">
                    <li><a href="#top" class="desktop-nav-item active"><i class="fa-solid fa-house text-[11px]"></i>Trang chủ</a></li>
                    <li><a href="#san-pham-dich-vu" onclick="filterCategory('danh-bong-da')" class="desktop-nav-item">Đánh bóng sàn đá</a></li>
                    <li><a href="#san-pham-dich-vu" onclick="filterCategory('son-epoxy')" class="desktop-nav-item">Sơn Epoxy</a></li>
                    <li><a href="#san-pham-dich-vu" onclick="filterCategory('mai-be-tong')" class="desktop-nav-item">Mài bê tông</a></li>
                    <li><a href="#san-pham-dich-vu" onclick="filterCategory('terrazzo')" class="desktop-nav-item">Đá mài Terrazzo</a></li>
                    <li><a href="#san-pham-dich-vu" onclick="filterCategory('microcement')" class="desktop-nav-item">Thi công Microcement</a></li>
                    <li><a href="#du-an-da-nang" class="desktop-nav-item">Dự án Đà Nẵng</a></li>
                    <li><a href="#tin-tuc" class="desktop-nav-item">Tin tức</a></li>
                    <li><a href="#bao-gia-lien-he" class="desktop-nav-item">Liên hệ</a></li>
                </ul>
            </nav>

            <!-- Nút mở Menu trên Điện thoại & Máy tính bảng (Không để nút Gọi ngay trên Header) -->
            <button id="mobileMenuBtn" onclick="toggleMobileMenu()" aria-label="Mở danh mục" class="lg:hidden p-2.5 rounded-lg bg-slate-100 text-mc-dark hover:bg-mc-dark hover:text-white transition shrink-0">
                <i class="fa-solid fa-bars text-lg"></i>
            </button>
        </div>

        <!-- Menu danh mục thả xuống cho Điện thoại (Thiết kế đẹp, chia 2 cột gọn gàng) -->
        <div id="mobileMenuDrawer" class="hidden lg:hidden bg-white border-t border-slate-200 px-4 py-3 shadow-lg">
            <div class="grid grid-cols-2 gap-2 text-xs font-bold text-mc-dark">
                <a href="#top" onclick="toggleMobileMenu()" class="p-2.5 rounded bg-slate-100 hover:bg-mc-primary hover:text-white flex items-center gap-2">
                    <i class="fa-solid fa-house text-mc-accent"></i> Trang chủ
                </a>
                <a href="#san-pham-dich-vu" onclick="filterCategory('danh-bong-da'); toggleMobileMenu()" class="p-2.5 rounded bg-slate-100 hover:bg-mc-primary hover:text-white flex items-center gap-2">
                    <i class="fa-solid fa-gem text-mc-accent"></i> Đánh bóng sàn đá
                </a>
                <a href="#san-pham-dich-vu" onclick="filterCategory('son-epoxy'); toggleMobileMenu()" class="p-2.5 rounded bg-slate-100 hover:bg-mc-primary hover:text-white flex items-center gap-2">
                    <i class="fa-solid fa-fill-drip text-mc-accent"></i> Sơn Epoxy
                </a>
                <a href="#san-pham-dich-vu" onclick="filterCategory('mai-be-tong'); toggleMobileMenu()" class="p-2.5 rounded bg-slate-100 hover:bg-mc-primary hover:text-white flex items-center gap-2">
                    <i class="fa-solid fa-layer-group text-mc-accent"></i> Mài bê tông
                </a>
                <a href="#san-pham-dich-vu" onclick="filterCategory('terrazzo'); toggleMobileMenu()" class="p-2.5 rounded bg-slate-100 hover:bg-mc-primary hover:text-white flex items-center gap-2">
                    <i class="fa-solid fa-cubes text-mc-accent"></i> Đá mài Terrazzo
                </a>
                <a href="#san-pham-dich-vu" onclick="filterCategory('microcement'); toggleMobileMenu()" class="p-2.5 rounded bg-slate-100 hover:bg-mc-primary hover:text-white flex items-center gap-2">
                    <i class="fa-solid fa-trowel-bricks text-mc-accent"></i> Thi công Microcement
                </a>
                <a href="#du-an-da-nang" onclick="toggleMobileMenu()" class="p-2.5 rounded bg-slate-100 hover:bg-mc-primary hover:text-white flex items-center gap-2">
                    <i class="fa-solid fa-building-circle-check text-mc-accent"></i> Dự án Đà Nẵng
                </a>
                <a href="#tin-tuc" onclick="toggleMobileMenu()" class="p-2.5 rounded bg-slate-100 hover:bg-mc-primary hover:text-white flex items-center gap-2">
                    <i class="fa-solid fa-newspaper text-mc-accent"></i> Bài viết & Tin tức
                </a>
                <a href="#bao-gia-lien-he" onclick="toggleMobileMenu()" class="col-span-2 p-2.5 rounded bg-mc-dark text-white text-center flex items-center justify-center gap-2">
                    <i class="fa-solid fa-file-signature text-mc-accent"></i> Nhận Báo Giá & Liên Hệ Ngay
                </a>
            </div>
        </div>
    </header>

    <!-- ===================================================================== -->
    <!-- SLIDER 2 BANNER TỰ TRƯỢT KÍCH THƯỚC BẰNG NHAU                         -->
    <!-- TÁCH RIÊNG ẢNH BANNER MÁY TÍNH & ẢNH BANNER ĐIỆN THOẠI                -->
    <!-- CHỮ NHỎ GỌN NẰM HẾT BÊN TRONG ẢNH, KHÔNG TRÀN VIỀN                    -->
    <!-- ===================================================================== -->
    <section id="top" class="w-full bg-slate-900 relative overflow-hidden">
        <div class="flatsome-container px-0 sm:px-4 py-0 sm:py-3">
            <div class="relative w-full overflow-hidden sm:rounded-xl shadow-md">
                
                <!-- ================= SLIDE 1 ================= -->
                <div class="banner-slide block w-full transition-opacity duration-700" data-slide="0">
                    
                    <!-- Bản Máy tính (Desktop Banner 1 - Kích thước chuẩn 1500x460 bằng nhau) -->
                    <div class="hidden md:flex relative w-full h-[420px] lg:h-[460px] items-center justify-between px-12 lg:px-16 overflow-hidden bg-gradient-to-r from-[#07162c] via-[#0f2c52] to-[#163e6c]">
                        <img src="https://drive.google.com/thumbnail?id=1QDZrsMiETa0VeHn5PFd8DgXq8nowxxT3&sz=w1600" 
                             alt="Banner Minh Châu Stone 1" 
                             class="absolute inset-0 w-full h-full object-cover opacity-30 mix-blend-luminosity">
                        
                        <!-- Nội dung chữ thu gọn nằm hoàn toàn bên trong khung an toàn của ảnh -->
                        <div class="relative z-10 max-w-[58%] text-white space-y-3 bg-slate-950/45 p-6 rounded-xl backdrop-blur-sm border border-white/15">
                            <div class="inline-flex items-center gap-2 text-mc-accent text-xs font-bold uppercase tracking-widest">
                                <i class="fa-solid fa-certificate"></i> CÔNG TY TNHH TM-DV MINH CHÂU STONE
                            </div>
                            <h1 class="text-xl lg:text-2xl xl:text-3xl font-extrabold leading-snug text-white">
                                CHUYÊN ĐÁNH BÓNG SÀN ĐÁ MARBLE, GRANITE & THI CÔNG ĐÁ MÀI TERRAZZO ĐÀ NẴNG
                            </h1>
                            <p class="text-xs lg:text-sm text-slate-200 leading-relaxed">
                                Giải pháp phục hồi sàn đá tự nhiên, mài đánh bóng sàn bê tông, thi công sơn sàn Epoxy và hoàn thiện Microcement chuẩn chất lượng ISO cho khách sạn, resort, biệt thự.
                            </p>
                            <div class="pt-1 flex flex-wrap items-center gap-3 text-xs font-semibold">
                                <span class="bg-mc-accent text-slate-950 px-3 py-1.5 rounded font-bold"><i class="fa-solid fa-phone mr-1"></i>0975.796.543 - 0355.698.490</span>
                                <span class="bg-white/10 text-white px-3 py-1.5 rounded border border-white/20">Website: minhchaustone.com</span>
                            </div>
                        </div>

                        <!-- Khung ảnh thực tế bên phải trên Banner Desktop -->
                        <div class="relative z-10 w-[38%] h-[320px] rounded-xl overflow-hidden border-2 border-mc-accent/70 shadow-2xl">
                            <img src="https://drive.google.com/thumbnail?id=1PsUMnTiNF0vzi9P834jOPQcQ9inXCHSm&sz=w900" 
                                 alt="Thi công đánh bóng đá thực tế" 
                                 class="w-full h-full object-cover"
                                 onerror="this.onerror=null;this.src='https://placehold.co/600x400/163e6c/ffffff?text=Minh+Chau+Stone';">
                        </div>
                    </div>

                    <!-- Bản Điện thoại (Mobile Banner 1 thiết kế riêng biệt, chữ nhỏ gọn nằm trọn bên trong ảnh) -->
                    <div class="flex md:hidden relative w-full h-[250px] sm:h-[280px] items-center justify-center p-4 overflow-hidden bg-gradient-to-b from-[#091e3a] to-[#12345b]">
                        <img src="https://drive.google.com/thumbnail?id=1QDZrsMiETa0VeHn5PFd8DgXq8nowxxT3&sz=w800" 
                             alt="Mobile Banner 1" 
                             class="absolute inset-0 w-full h-full object-cover opacity-25">
                        <div class="relative z-10 w-full max-w-[94%] bg-slate-950/65 border border-white/15 rounded-lg p-3.5 text-center text-white space-y-1.5">
                            <p class="text-[10px] font-bold uppercase tracking-wider text-mc-accent">MINH CHÂU STONE - MINHCHAUSTONE.COM</p>
                            <h2 class="text-sm sm:text-base font-extrabold leading-snug text-white">
                                ĐÁNH BÓNG SÀN ĐÁ MARBLE - GRANITE & ĐÁ MÀI TERRAZZO ĐÀ NẴNG
                            </h2>
                            <p class="text-[11px] text-slate-200 leading-tight">
                                Chuyên mài phục hồi sàn đá, mài sàn bê tông, sơn Epoxy & Microcement uy tín, tiết kiệm 20% chi phí.
                            </p>
                            <div class="pt-1">
                                <span class="inline-block bg-mc-accent text-slate-950 text-[11px] font-extrabold px-2.5 py-1 rounded">
                                    Hotline: 0975.796.543 - 0355.698.490
                                </span>
                            </div>
                        </div>
                    </div>
                </div>

                <!-- ================= SLIDE 2 ================= -->
                <div class="banner-slide hidden w-full transition-opacity duration-700" data-slide="1">
                    
                    <!-- Bản Máy tính (Desktop Banner 2 - Kích thước chuẩn 1500x460 bằng nhau) -->
                    <div class="hidden md:flex relative w-full h-[420px] lg:h-[460px] items-center justify-between px-12 lg:px-16 overflow-hidden bg-gradient-to-r from-[#0f2942] via-[#173f66] to-[#0c2340]">
                        <img src="https://drive.google.com/thumbnail?id=1YSE0tN0WSfjeA0AYbRweC_pUP58nP02e&sz=w1600" 
                             alt="Banner Minh Châu Stone 2" 
                             class="absolute inset-0 w-full h-full object-cover opacity-30 mix-blend-luminosity">
                        
                        <div class="relative z-10 max-w-[58%] text-white space-y-3 bg-slate-950/45 p-6 rounded-xl backdrop-blur-sm border border-white/15">
                            <div class="inline-flex items-center gap-2 text-mc-accent text-xs font-bold uppercase tracking-widest">
                                <i class="fa-solid fa-award"></i> CÔNG NGHỆ MÀI BÓNG & PHỦ SÀN HIỆN ĐẠI
                            </div>
                            <h2 class="text-xl lg:text-2xl xl:text-3xl font-extrabold leading-snug text-white">
                                THI CÔNG SƠN SÀN EPOXY, MÀI BÊ TÔNG LỘ CỐT LIỆU & SÀN MICROCEMENT CAO CẤP
                            </h2>
                            <p class="text-xs lg:text-sm text-slate-200 leading-relaxed">
                                Đội ngũ kỹ thuật viên lành nghề cùng hệ thống máy mài công suất lớn, hóa chất nhập khẩu chính hãng. Khảo sát tận nơi tại Ngũ Hành Sơn và toàn TP Đà Nẵng.
                            </p>
                            <div class="pt-1 flex flex-wrap items-center gap-3 text-xs font-semibold">
                                <span class="bg-mc-accent text-slate-950 px-3 py-1.5 rounded font-bold"><i class="fa-solid fa-location-dot mr-1"></i>TĐC Tân Trà, P. Ngũ Hành Sơn, Đà Nẵng</span>
                                <span class="bg-white/10 text-white px-3 py-1.5 rounded border border-white/20">Tư vấn 24/7: 0975.796.543</span>
                            </div>
                        </div>

                        <div class="relative z-10 w-[38%] h-[320px] rounded-xl overflow-hidden border-2 border-mc-accent/70 shadow-2xl">
                            <img src="https://drive.google.com/thumbnail?id=1RfQNvz0pxQNUMwzSYgFimrwg34O16VYV&sz=w900" 
                                 alt="Thi công mài bê tông và đá tự nhiên" 
                                 class="w-full h-full object-cover"
                                 onerror="this.onerror=null;this.src='https://placehold.co/600x400/0c2340/ffffff?text=Minh+Chau+Stone';">
                        </div>
                    </div>

                    <!-- Bản Điện thoại (Mobile Banner 2 thiết kế riêng biệt, kích thước bằng Mobile Banner 1) -->
                    <div class="flex md:hidden relative w-full h-[250px] sm:h-[280px] items-center justify-center p-4 overflow-hidden bg-gradient-to-b from-[#102a49] to-[#0a1d33]">
                        <img src="https://drive.google.com/thumbnail?id=1YSE0tN0WSfjeA0AYbRweC_pUP58nP02e&sz=w800" 
                             alt="Mobile Banner 2" 
                             class="absolute inset-0 w-full h-full object-cover opacity-25">
                        <div class="relative z-10 w-full max-w-[94%] bg-slate-950/65 border border-white/15 rounded-lg p-3.5 text-center text-white space-y-1.5">
                            <p class="text-[10px] font-bold uppercase tracking-wider text-mc-accent">CÔNG NGHỆ ĐÁNH BÓNG & PHỦ SÀN</p>
                            <h2 class="text-sm sm:text-base font-extrabold leading-snug text-white">
                                THI CÔNG SƠN EPOXY, MÀI SÀN BÊ TÔNG & MICROCEMENT ĐÀ NẴNG
                            </h2>
                            <p class="text-[11px] text-slate-200 leading-tight">
                                Địa chỉ: Lô 46-B2.21, TĐC Tân Trà, P. Ngũ Hành Sơn, TP Đà Nẵng. Khảo sát & báo giá miễn phí.
                            </p>
                            <div class="pt-1">
                                <span class="inline-block bg-mc-accent text-slate-950 text-[11px] font-extrabold px-2.5 py-1 rounded">
                                    Gọi ngay: 0975.796.543 - 0355.698.490
                                </span>
                            </div>
                        </div>
                    </div>
                </div>

                <!-- Nút điều hướng 2 Banner -->
                <button onclick="changeSlide(-1)" aria-label="Slide trước" class="absolute left-2.5 top-1/2 -translate-y-1/2 w-8 h-8 md:w-10 md:h-10 rounded-full bg-black/45 text-white hover:bg-mc-accent hover:text-slate-900 flex items-center justify-center transition z-20">
                    <i class="fa-solid fa-chevron-left text-xs md:text-sm"></i>
                </button>
                <button onclick="changeSlide(1)" aria-label="Slide tiếp" class="absolute right-2.5 top-1/2 -translate-y-1/2 w-8 h-8 md:w-10 md:h-10 rounded-full bg-black/45 text-white hover:bg-mc-accent hover:text-slate-900 flex items-center justify-center transition z-20">
                    <i class="fa-solid fa-chevron-right text-xs md:text-sm"></i>
                </button>

                <!-- Chấm chỉ báo Slide -->
                <div class="absolute bottom-2.5 left-1/2 -translate-x-1/2 flex items-center gap-2 z-20">
                    <button onclick="goToSlide(0)" id="dot-0" class="w-6 h-2 rounded-full bg-mc-accent transition-all"></button>
                    <button onclick="goToSlide(1)" id="dot-1" class="w-2.5 h-2 rounded-full bg-white/60 transition-all"></button>
                </div>

            </div>
        </div>
    </section>

    <!-- ===================================================================== -->
    <!-- THANH KẾT NỐI NHANH GIỐNG BACTRUNG.COM (FACEBOOK - ZALO - HOTLINE)    -->
    <!-- ===================================================================== -->
    <section class="w-full py-4 bg-white border-b border-slate-200">
        <div class="flatsome-container">
            <div class="bg-mc-light border border-slate-200 rounded-xl p-4 flex flex-col lg:flex-row items-center justify-between gap-4">
                <div class="text-center lg:text-left">
                    <h2 class="text-sm sm:text-base font-extrabold text-mc-dark">
                        Bạn cần tư vấn & báo giá nhanh dịch vụ đá và sàn tại Đà Nẵng?
                    </h2>
                    <p class="text-xs text-slate-600 mt-0.5">
                        Liên hệ trực tiếp CÔNG TY TNHH TM-DV MINH CHÂU STONE qua các kênh hỗ trợ 24/7:
                    </p>
                </div>
                <div class="grid grid-cols-3 gap-2 sm:gap-3 w-full lg:w-auto shrink-0">
                    <a href="https://www.facebook.com" target="_blank" rel="noopener" class="bg-[#1877F2] hover:opacity-95 text-white font-bold text-xs sm:text-sm py-2.5 px-3 sm:px-5 rounded-lg flex items-center justify-center gap-1.5 shadow-sm">
                        <i class="fa-brands fa-facebook-f"></i> <span>FACEBOOK</span>
                    </a>
                    <a href="https://zalo.me/0975796543" target="_blank" rel="noopener" class="bg-[#0068FF] hover:opacity-95 text-white font-bold text-xs sm:text-sm py-2.5 px-3 sm:px-5 rounded-lg flex items-center justify-center gap-1.5 shadow-sm">
                        <i class="fa-solid fa-comment-dots"></i> <span>ZALO</span>
                    </a>
                    <a href="tel:0975796543" class="bg-red-600 hover:bg-red-700 text-white font-bold text-xs sm:text-sm py-2.5 px-3 sm:px-5 rounded-lg flex items-center justify-center gap-1.5 shadow-sm">
                        <i class="fa-solid fa-phone"></i> <span>HOTLINE</span>
                    </a>
                </div>
            </div>
        </div>
    </section>

    <!-- ===================================================================== -->
    <!-- GIỚI THIỆU MINH CHÂU STONE (THEO BỐ CỤC MẪU BACTRUNG.COM)             -->
    <!-- ===================================================================== -->
    <section class="w-full py-8 bg-white">
        <div class="flatsome-container">
            <div class="grid grid-cols-1 lg:grid-cols-12 gap-6 items-center">
                <div class="lg:col-span-7 space-y-3">
                    <div class="text-xs font-bold uppercase text-mc-primary tracking-wider">GIỚI THIỆU DOANH NGHIỆP</div>
                    <h2 class="text-lg sm:text-2xl font-extrabold text-mc-dark">
                        CÔNG TY TNHH TM-DV MINH CHÂU STONE
                    </h2>
                    <p class="text-sm text-slate-700 leading-relaxed">
                        <strong>Công ty TNHH TM-DV Minh Châu Stone</strong> (<a href="https://minhchaustone.com" class="text-mc-primary font-semibold underline">minhchaustone.com</a>) là đơn vị chuyên cung cấp, thi công đá tự nhiên và dịch vụ mài đánh bóng sàn bê tông, xử lý phục hồi đánh bóng sàn đá Marble – Granite, đá mài Terrazzo, sơn sàn Epoxy và thi công Microcement tại Đà Nẵng uy tín, chất lượng với mức giá hợp lý nhất.
                    </p>
                    <p class="text-sm text-slate-700 leading-relaxed">
                        Đá tự nhiên, đá Marble, đá Granite và đá mài Terrazzo được ứng dụng rộng rãi tại các công trình biệt thự, khách sạn, khu nghỉ dưỡng và tòa nhà thương mại. Sau một thời gian khai thác hoặc mới lắp đặt, bề mặt sàn cần được xử lý mài phẳng, đánh bóng gương và phủ chống thấm chuyên sâu. Minh Châu Stone cam kết mang lại mặt sàn sáng bóng bền bỉ như mới.
                    </p>
                    <div class="grid grid-cols-2 sm:grid-cols-3 gap-2.5 pt-2 text-xs font-semibold text-mc-dark">
                        <div class="p-2.5 rounded-lg bg-slate-50 border border-slate-200 flex items-center gap-2">
                            <i class="fa-solid fa-circle-check text-mc-accent"></i> Máy móc công nghiệp hiện đại
                        </div>
                        <div class="p-2.5 rounded-lg bg-slate-50 border border-slate-200 flex items-center gap-2">
                            <i class="fa-solid fa-circle-check text-mc-accent"></i> Hóa chất nhập khẩu Ý, Anh
                        </div>
                        <div class="col-span-2 sm:col-span-1 p-2.5 rounded-lg bg-slate-50 border border-slate-200 flex items-center gap-2">
                            <i class="fa-solid fa-circle-check text-mc-accent"></i> Bảo hành dài hạn, đúng tiến độ
                        </div>
                    </div>
                </div>
                <div class="lg:col-span-5 grid grid-cols-2 gap-3">
                    <div class="rounded-xl overflow-hidden border border-slate-200 shadow-sm h-44 sm:h-52">
                        <img src="https://drive.google.com/thumbnail?id=1QDZrsMiETa0VeHn5PFd8DgXq8nowxxT3&sz=w800" 
                             alt="Hình ảnh thực tế Minh Châu Stone 1" 
                             class="w-full h-full object-cover"
                             onerror="this.onerror=null;this.src='https://placehold.co/500x400/0c2340/ffffff?text=Minh+Chau+Stone';">
                    </div>
                    <div class="rounded-xl overflow-hidden border border-slate-200 shadow-sm h-44 sm:h-52">
                        <img src="https://drive.google.com/thumbnail?id=1AXKSFrWkWGV_CIOqbGGYecZREk0VzU1k&sz=w800" 
                             alt="Hình ảnh thực tế Minh Châu Stone 2" 
                             class="w-full h-full object-cover"
                             onerror="this.onerror=null;this.src='https://placehold.co/500x400/163e6c/ffffff?text=Thi+Cong+Da';">
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- ===================================================================== -->
    <!-- DANH MỤC & SẢN PHẨM / DỊCH VỤ (LẤY TỪ WEB MẪU + 10 ẢNH GOOGLE DRIVE)  -->
    <!-- - Chữ danh mục ở trang chủ nhỏ gọn, viết liền trên 1 hàng             -->
    <!-- - Điện thoại chia đúng 2 cột (grid-cols-2)                            -->
    <!-- - Không để nhãn dán (badge/sticker) trên ảnh                          -->
    <!-- - Tên sản phẩm hiển thị đầy đủ không bị tràn hay thiếu chữ            -->
    <!-- ===================================================================== -->
    <section id="san-pham-dich-vu" class="w-full py-8 bg-slate-50 border-t border-slate-200">
        <div class="flatsome-container">
            
            <!-- Tiêu đề chuẩn Flatsome -->
            <div class="ux-section-title">
                <b></b>
                <span>DANH MỤC SẢN PHẨM & DỊCH VỤ THI CÔNG</span>
                <b></b>
            </div>

            <!-- Thanh Danh Mục Trang Chủ: Chữ nhỏ gọn, viết liền không xuống dòng trong từng nút -->
            <div class="flex flex-wrap items-center justify-center gap-2 mb-6">
                <button onclick="filterCategory('all')" data-cat-btn="all" class="category-pill active">
                    <i class="fa-solid fa-border-all"></i> Tất cả danh mục
                </button>
                <button onclick="filterCategory('danh-bong-da')" data-cat-btn="danh-bong-da" class="category-pill">
                    <i class="fa-solid fa-gem"></i> Đánh bóng sàn đá
                </button>
                <button onclick="filterCategory('son-epoxy')" data-cat-btn="son-epoxy" class="category-pill">
                    <i class="fa-solid fa-fill-drip"></i> Sơn Epoxy
                </button>
                <button onclick="filterCategory('mai-be-tong')" data-cat-btn="mai-be-tong" class="category-pill">
                    <i class="fa-solid fa-layer-group"></i> Mài bê tông
                </button>
                <button onclick="filterCategory('terrazzo')" data-cat-btn="terrazzo" class="category-pill">
                    <i class="fa-solid fa-cubes"></i> Thi công đá mài Terrazzo
                </button>
                <button onclick="filterCategory('microcement')" data-cat-btn="microcement" class="category-pill">
                    <i class="fa-solid fa-trowel-bricks"></i> Thi công Microcement
                </button>
            </div>

            <!-- Lưới 10 Sản phẩm/Dịch vụ từ 10 file ảnh thực tế Google Drive -->
            <!-- Trên điện thoại chia 2 cột (grid-cols-2), trên máy tính chia 5 cột (lg:grid-cols-5) -->
            <div id="productGrid" class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-5 gap-3 sm:gap-4">

                <!-- Sản phẩm 1 (File Drive 1: 1QDZrsMiETa0VeHn5PFd8DgXq8nowxxT3) -->
                <div class="product-card bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col" data-category="danh-bong-da">
                    <div class="aspect-[4/3] w-full bg-slate-100 overflow-hidden">
                        <img src="https://drive.google.com/thumbnail?id=1QDZrsMiETa0VeHn5PFd8DgXq8nowxxT3&sz=w700" 
                             alt="Đánh bóng sàn đá Marble Cẩm Thạch tự nhiên tại Đà Nẵng" 
                             class="w-full h-full object-cover hover:scale-105 transition duration-300"
                             onerror="this.onerror=null;this.src='https://placehold.co/600x450/0c2340/ffffff?text=Da+Marble';">
                    </div>
                    <div class="p-3 flex flex-col flex-1 justify-between gap-2">
                        <div>
                            <div class="text-[11px] font-semibold text-slate-500">Đánh bóng sàn đá</div>
                            <h3 class="product-title-full font-bold text-mc-dark text-xs sm:text-sm mt-0.5">
                                Dịch vụ mài phục hồi và đánh bóng sàn đá Marble (Đá Cẩm Thạch) tại Đà Nẵng
                            </h3>
                        </div>
                        <div class="pt-2 border-t border-slate-100 flex items-center justify-between gap-1">
                            <span class="text-[11px] sm:text-xs font-extrabold text-red-600">170.000đ - 250.000đ/m²</span>
                            <a href="#bao-gia-lien-he" class="text-[11px] font-bold text-mc-primary hover:underline shrink-0">Báo giá</a>
                        </div>
                    </div>
                </div>

                <!-- Sản phẩm 2 (File Drive 2: 1PsUMnTiNF0vzi9P834jOPQcQ9inXCHSm) -->
                <div class="product-card bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col" data-category="danh-bong-da">
                    <div class="aspect-[4/3] w-full bg-slate-100 overflow-hidden">
                        <img src="https://drive.google.com/thumbnail?id=1PsUMnTiNF0vzi9P834jOPQcQ9inXCHSm&sz=w700" 
                             alt="Thi công mài phục hồi đánh bóng đá Granite Hoa Cương" 
                             class="w-full h-full object-cover hover:scale-105 transition duration-300"
                             onerror="this.onerror=null;this.src='https://placehold.co/600x450/0c2340/ffffff?text=Da+Granite';">
                    </div>
                    <div class="p-3 flex flex-col flex-1 justify-between gap-2">
                        <div>
                            <div class="text-[11px] font-semibold text-slate-500">Đánh bóng sàn đá</div>
                            <h3 class="product-title-full font-bold text-mc-dark text-xs sm:text-sm mt-0.5">
                                Dịch vụ mài phục hồi, đánh bóng sàn đá Granite (Đá Hoa Cương) chuyên nghiệp
                            </h3>
                        </div>
                        <div class="pt-2 border-t border-slate-100 flex items-center justify-between gap-1">
                            <span class="text-[11px] sm:text-xs font-extrabold text-red-600">150.000đ - 250.000đ/m²</span>
                            <a href="#bao-gia-lien-he" class="text-[11px] font-bold text-mc-primary hover:underline shrink-0">Báo giá</a>
                        </div>
                    </div>
                </div>

                <!-- Sản phẩm 3 (File Drive 3: 1YSE0tN0WSfjeA0AYbRweC_pUP58nP02e) -->
                <div class="product-card bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col" data-category="terrazzo">
                    <div class="aspect-[4/3] w-full bg-slate-100 overflow-hidden">
                        <img src="https://drive.google.com/thumbnail?id=1YSE0tN0WSfjeA0AYbRweC_pUP58nP02e&sz=w700" 
                             alt="Thi công đá mài Terrazzo nội ngoại thất Đà Nẵng" 
                             class="w-full h-full object-cover hover:scale-105 transition duration-300"
                             onerror="this.onerror=null;this.src='https://placehold.co/600x450/0c2340/ffffff?text=Da+Terrazzo';">
                    </div>
                    <div class="p-3 flex flex-col flex-1 justify-between gap-2">
                        <div>
                            <div class="text-[11px] font-semibold text-slate-500">Thi công đá mài Terrazzo</div>
                            <h3 class="product-title-full font-bold text-mc-dark text-xs sm:text-sm mt-0.5">
                                Thi công sàn đá mài Terrazzo cao cấp cho biệt thự, khách sạn và showroom
                            </h3>
                        </div>
                        <div class="pt-2 border-t border-slate-100 flex items-center justify-between gap-1">
                            <span class="text-[11px] sm:text-xs font-extrabold text-red-600">Liên hệ báo giá</span>
                            <a href="#bao-gia-lien-he" class="text-[11px] font-bold text-mc-primary hover:underline shrink-0">Báo giá</a>
                        </div>
                    </div>
                </div>

                <!-- Sản phẩm 4 (File Drive 4: 1RfQNvz0pxQNUMwzSYgFimrwg34O16VYV) -->
                <div class="product-card bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col" data-category="terrazzo">
                    <div class="aspect-[4/3] w-full bg-slate-100 overflow-hidden">
                        <img src="https://drive.google.com/thumbnail?id=1RfQNvz0pxQNUMwzSYgFimrwg34O16VYV&sz=w700" 
                             alt="Thi công hồ bơi cầu thang và bồn cây đá Terrazzo" 
                             class="w-full h-full object-cover hover:scale-105 transition duration-300"
                             onerror="this.onerror=null;this.src='https://placehold.co/600x450/0c2340/ffffff?text=Ho+Boi+Terrazzo';">
                    </div>
                    <div class="p-3 flex flex-col flex-1 justify-between gap-2">
                        <div>
                            <div class="text-[11px] font-semibold text-slate-500">Thi công đá mài Terrazzo</div>
                            <h3 class="product-title-full font-bold text-mc-dark text-xs sm:text-sm mt-0.5">
                                Thi công hồ bơi đá mài Terrazzo, cầu thang và bồn cây cảnh Terrazzo nguyên khối
                            </h3>
                        </div>
                        <div class="pt-2 border-t border-slate-100 flex items-center justify-between gap-1">
                            <span class="text-[11px] sm:text-xs font-extrabold text-red-600">120.000đ - 150.000đ/m²</span>
                            <a href="#bao-gia-lien-he" class="text-[11px] font-bold text-mc-primary hover:underline shrink-0">Báo giá</a>
                        </div>
                    </div>
                </div>

                <!-- Sản phẩm 5 (File Drive 5: 1AXKSFrWkWGV_CIOqbGGYecZREk0VzU1k) -->
                <div class="product-card bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col" data-category="mai-be-tong">
                    <div class="aspect-[4/3] w-full bg-slate-100 overflow-hidden">
                        <img src="https://drive.google.com/thumbnail?id=1AXKSFrWkWGV_CIOqbGGYecZREk0VzU1k&sz=w700" 
                             alt="Mài đánh bóng sàn bê tông lộ cát lộ đá tại Đà Nẵng" 
                             class="w-full h-full object-cover hover:scale-105 transition duration-300"
                             onerror="this.onerror=null;this.src='https://placehold.co/600x450/0c2340/ffffff?text=Mai+Be+Tong';">
                    </div>
                    <div class="p-3 flex flex-col flex-1 justify-between gap-2">
                        <div>
                            <div class="text-[11px] font-semibold text-slate-500">Mài bê tông</div>
                            <h3 class="product-title-full font-bold text-mc-dark text-xs sm:text-sm mt-0.5">
                                Dịch vụ mài đánh bóng sàn bê tông lộ cát, lộ cốt liệu đá hạt tiêu tại Đà Nẵng
                            </h3>
                        </div>
                        <div class="pt-2 border-t border-slate-100 flex items-center justify-between gap-1">
                            <span class="text-[11px] sm:text-xs font-extrabold text-red-600">110.000đ - 120.000đ/m²</span>
                            <a href="#bao-gia-lien-he" class="text-[11px] font-bold text-mc-primary hover:underline shrink-0">Báo giá</a>
                        </div>
                    </div>
                </div>

                <!-- Sản phẩm 6 (File Drive 6: 1tX9FDCFD64EgV2UM0c_P40ylsnGb4MP1) -->
                <div class="product-card bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col" data-category="mai-be-tong">
                    <div class="aspect-[4/3] w-full bg-slate-100 overflow-hidden">
                        <img src="https://drive.google.com/thumbnail?id=1tX9FDCFD64EgV2UM0c_P40ylsnGb4MP1&sz=w700" 
                             alt="Mài sàn bê tông tăng cứng Liquid Hardener nhà xưởng" 
                             class="w-full h-full object-cover hover:scale-105 transition duration-300"
                             onerror="this.onerror=null;this.src='https://placehold.co/600x450/0c2340/ffffff?text=San+Be+Tong';">
                    </div>
                    <div class="p-3 flex flex-col flex-1 justify-between gap-2">
                        <div>
                            <div class="text-[11px] font-semibold text-slate-500">Mài bê tông</div>
                            <h3 class="product-title-full font-bold text-mc-dark text-xs sm:text-sm mt-0.5">
                                Thi công mài phẳng và phủ hóa chất tăng cứng sàn bê tông nhà xưởng, tầng hầm
                            </h3>
                        </div>
                        <div class="pt-2 border-t border-slate-100 flex items-center justify-between gap-1">
                            <span class="text-[11px] sm:text-xs font-extrabold text-red-600">Báo giá theo diện tích</span>
                            <a href="#bao-gia-lien-he" class="text-[11px] font-bold text-mc-primary hover:underline shrink-0">Báo giá</a>
                        </div>
                    </div>
                </div>

                <!-- Sản phẩm 7 (File Drive 7: 1TXR9-xdfBuhNTGh1VVouv-qgJ4071leV) -->
                <div class="product-card bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col" data-category="son-epoxy">
                    <div class="aspect-[4/3] w-full bg-slate-100 overflow-hidden">
                        <img src="https://drive.google.com/thumbnail?id=1TXR9-xdfBuhNTGh1VVouv-qgJ4071leV&sz=w700" 
                             alt="Thi công sơn sàn Epoxy hệ lăn và tự san phẳng Đà Nẵng" 
                             class="w-full h-full object-cover hover:scale-105 transition duration-300"
                             onerror="this.onerror=null;this.src='https://placehold.co/600x450/0c2340/ffffff?text=Son+Epoxy';">
                    </div>
                    <div class="p-3 flex flex-col flex-1 justify-between gap-2">
                        <div>
                            <div class="text-[11px] font-semibold text-slate-500">Sơn Epoxy</div>
                            <h3 class="product-title-full font-bold text-mc-dark text-xs sm:text-sm mt-0.5">
                                Thi công sơn sàn Epoxy tự san phẳng kháng khuẩn cho showroom, bệnh viện, nhà máy
                            </h3>
                        </div>
                        <div class="pt-2 border-t border-slate-100 flex items-center justify-between gap-1">
                            <span class="text-[11px] sm:text-xs font-extrabold text-red-600">Liên hệ báo giá</span>
                            <a href="#bao-gia-lien-he" class="text-[11px] font-bold text-mc-primary hover:underline shrink-0">Báo giá</a>
                        </div>
                    </div>
                </div>

                <!-- Sản phẩm 8 (File Drive 8: 1CDzDZ3Em_reh2GBq9vU_28L4KRaZ6Ay2) -->
                <div class="product-card bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col" data-category="son-epoxy">
                    <div class="aspect-[4/3] w-full bg-slate-100 overflow-hidden">
                        <img src="https://drive.google.com/thumbnail?id=1CDzDZ3Em_reh2GBq9vU_28L4KRaZ6Ay2&sz=w700" 
                             alt="Thi công sơn sàn Epoxy hệ lăn kẻ vạch nhà kho gara" 
                             class="w-full h-full object-cover hover:scale-105 transition duration-300"
                             onerror="this.onerror=null;this.src='https://placehold.co/600x450/0c2340/ffffff?text=Epoxy+He+Lan';">
                    </div>
                    <div class="p-3 flex flex-col flex-1 justify-between gap-2">
                        <div>
                            <div class="text-[11px] font-semibold text-slate-500">Sơn Epoxy</div>
                            <h3 class="product-title-full font-bold text-mc-dark text-xs sm:text-sm mt-0.5">
                                Dịch vụ sơn sàn Epoxy hệ lăn 3 lớp chống thấm, kẻ vạch tầng hầm và gara ô tô
                            </h3>
                        </div>
                        <div class="pt-2 border-t border-slate-100 flex items-center justify-between gap-1">
                            <span class="text-[11px] sm:text-xs font-extrabold text-red-600">Liên hệ báo giá</span>
                            <a href="#bao-gia-lien-he" class="text-[11px] font-bold text-mc-primary hover:underline shrink-0">Báo giá</a>
                        </div>
                    </div>
                </div>

                <!-- Sản phẩm 9 (File Drive 9: 1g_-n827VKRmoUoQOfMVu6lJj4U7hmoc2) -->
                <div class="product-card bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col" data-category="microcement">
                    <div class="aspect-[4/3] w-full bg-slate-100 overflow-hidden">
                        <img src="https://drive.google.com/thumbnail?id=1g_-n827VKRmoUoQOfMVu6lJj4U7hmoc2&sz=w700" 
                             alt="Thi công sàn và tường hiệu ứng Microcement Đà Nẵng" 
                             class="w-full h-full object-cover hover:scale-105 transition duration-300"
                             onerror="this.onerror=null;this.src='https://placehold.co/600x450/0c2340/ffffff?text=Microcement';">
                    </div>
                    <div class="p-3 flex flex-col flex-1 justify-between gap-2">
                        <div>
                            <div class="text-[11px] font-semibold text-slate-500">Thi công Microcement</div>
                            <h3 class="product-title-full font-bold text-mc-dark text-xs sm:text-sm mt-0.5">
                                Thi công sàn và tường Microcement liền mạch không đường ron hiện đại tại Đà Nẵng
                            </h3>
                        </div>
                        <div class="pt-2 border-t border-slate-100 flex items-center justify-between gap-1">
                            <span class="text-[11px] sm:text-xs font-extrabold text-red-600">500.000đ - 900.000đ/m²</span>
                            <a href="#bao-gia-lien-he" class="text-[11px] font-bold text-mc-primary hover:underline shrink-0">Báo giá</a>
                        </div>
                    </div>
                </div>

                <!-- Sản phẩm 10 (File Drive 10: 1S_YaA0IhlBeHsUxLKUaAoe00gV1ZD519) -->
                <div class="product-card bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col" data-category="danh-bong-da">
                    <div class="aspect-[4/3] w-full bg-slate-100 overflow-hidden">
                        <img src="https://drive.google.com/thumbnail?id=1S_YaA0IhlBeHsUxLKUaAoe00gV1ZD519&sz=w700" 
                             alt="Cung cấp ốp lát và bảo dưỡng đá tự nhiên bàn bếp cầu thang" 
                             class="w-full h-full object-cover hover:scale-105 transition duration-300"
                             onerror="this.onerror=null;this.src='https://placehold.co/600x450/0c2340/ffffff?text=Da+Tu+Nhien';">
                    </div>
                    <div class="p-3 flex flex-col flex-1 justify-between gap-2">
                        <div>
                            <div class="text-[11px] font-semibold text-slate-500">Đánh bóng sàn đá</div>
                            <h3 class="product-title-full font-bold text-mc-dark text-xs sm:text-sm mt-0.5">
                                Thi công ốp lát, phủ chống thấm và đánh bóng đá tự nhiên mặt bếp, cầu thang, đại sảnh
                            </h3>
                        </div>
                        <div class="pt-2 border-t border-slate-100 flex items-center justify-between gap-1">
                            <span class="text-[11px] sm:text-xs font-extrabold text-red-600">180.000đ - 300.000đ/m²</span>
                            <a href="#bao-gia-lien-he" class="text-[11px] font-bold text-mc-primary hover:underline shrink-0">Báo giá</a>
                        </div>
                    </div>
                </div>

            </div>
        </div>
    </section>

    <!-- ===================================================================== -->
    <!-- VÌ SAO CHỌN MINH CHÂU STONE (THEO MẪU BACTRUNG.COM)                   -->
    <!-- ===================================================================== -->
    <section class="w-full py-8 bg-white border-t border-slate-200">
        <div class="flatsome-container">
            <div class="ux-section-title">
                <b></b>
                <span>VÌ SAO CHỌN MINH CHÂU STONE</span>
                <b></b>
            </div>
            <div class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-5 gap-3 sm:gap-4">
                <div class="p-4 rounded-xl bg-slate-50 border border-slate-200 text-center space-y-1.5">
                    <div class="w-10 h-10 mx-auto rounded-full bg-mc-dark text-mc-accent flex items-center justify-center text-base">
                        <i class="fa-solid fa-tags"></i>
                    </div>
                    <h3 class="font-bold text-xs sm:text-sm text-mc-dark">Giá thành cạnh tranh</h3>
                    <p class="text-xs text-slate-600 leading-relaxed">Tiết kiệm hơn 20% chi phí, báo giá minh bạch trực tiếp tại xưởng và công trình.</p>
                </div>
                <div class="p-4 rounded-xl bg-slate-50 border border-slate-200 text-center space-y-1.5">
                    <div class="w-10 h-10 mx-auto rounded-full bg-mc-dark text-mc-accent flex items-center justify-center text-base">
                        <i class="fa-solid fa-helmet-safety"></i>
                    </div>
                    <h3 class="font-bold text-xs sm:text-sm text-mc-dark">Năng lực chuyên môn cao</h3>
                    <p class="text-xs text-slate-600 leading-relaxed">Trực tiếp nhận thầu nhiều công trình lớn tại Đà Nẵng, đảm bảo tiến độ & thẩm mỹ.</p>
                </div>
                <div class="p-4 rounded-xl bg-slate-50 border border-slate-200 text-center space-y-1.5">
                    <div class="w-10 h-10 mx-auto rounded-full bg-mc-dark text-mc-accent flex items-center justify-center text-base">
                        <i class="fa-solid fa-medal"></i>
                    </div>
                    <h3 class="font-bold text-xs sm:text-sm text-mc-dark">Chất lượng ISO 9001</h3>
                    <p class="text-xs text-slate-600 leading-relaxed">Quy trình mài bóng 7 bước tiêu chuẩn, độ bóng gương bền bỉ theo thời gian.</p>
                </div>
                <div class="p-4 rounded-xl bg-slate-50 border border-slate-200 text-center space-y-1.5">
                    <div class="w-10 h-10 mx-auto rounded-full bg-mc-dark text-mc-accent flex items-center justify-center text-base">
                        <i class="fa-solid fa-wand-magic-sparkles"></i>
                    </div>
                    <h3 class="font-bold text-xs sm:text-sm text-mc-dark">Giá trị & Sự khác biệt</h3>
                    <p class="text-xs text-slate-600 leading-relaxed">Xử lý triệt để các hạng mục sàn đá ố vàng, trầy xước sâu và dự án độ khó cao.</p>
                </div>
                <div class="col-span-2 md:col-span-1 p-4 rounded-xl bg-slate-50 border border-slate-200 text-center space-y-1.5">
                    <div class="w-10 h-10 mx-auto rounded-full bg-mc-dark text-mc-accent flex items-center justify-center text-base">
                        <i class="fa-solid fa-leaf"></i>
                    </div>
                    <h3 class="font-bold text-xs sm:text-sm text-mc-dark">Thân thiện môi trường</h3>
                    <p class="text-xs text-slate-600 leading-relaxed">Sử dụng hóa chất đánh bóng, phủ chống thấm nhập khẩu an toàn tuyệt đối.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- ===================================================================== -->
    <!-- DANH MỤC CÁC DỰ ÁN TIÊU BIỂU Ở ĐÀ NẴNG TRÊN TRANG CHỦ                 -->
    <!-- ===================================================================== -->
    <section id="du-an-da-nang" class="w-full py-8 bg-slate-50 border-t border-slate-200">
        <div class="flatsome-container">
            <div class="ux-section-title">
                <b></b>
                <span>DỰ ÁN THI CÔNG THỰC TẾ TẠI ĐÀ NẴNG</span>
                <b></b>
            </div>

            <!-- Chia 2 cột trên điện thoại, 4 cột trên máy tính -->
            <div class="grid grid-cols-2 lg:grid-cols-4 gap-3 sm:gap-4">
                
                <div class="bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm flex flex-col">
                    <div class="aspect-[16/10] w-full overflow-hidden bg-slate-100">
                        <img src="https://drive.google.com/thumbnail?id=1QDZrsMiETa0VeHn5PFd8DgXq8nowxxT3&sz=w700" 
                             alt="Dự án Resort & Villa đường Trường Sa Ngũ Hành Sơn Đà Nẵng" 
                             class="w-full h-full object-cover">
                    </div>
                    <div class="p-3 flex-1 flex flex-col justify-between">
                        <div>
                            <span class="text-[11px] font-semibold text-mc-primary">Quận Ngũ Hành Sơn, Đà Nẵng</span>
                            <h3 class="product-title-full font-bold text-xs sm:text-sm text-mc-dark mt-1">
                                Thi công đánh bóng sàn đá Marble & sảnh đón Khu nghỉ dưỡng ven biển Tân Trà - Ngũ Hành Sơn
                            </h3>
                        </div>
                        <p class="text-[11px] text-slate-500 mt-2">Hạng mục: Phục hồi đánh bóng 1.800m² sàn đá Marble</p>
                    </div>
                </div>

                <div class="bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm flex flex-col">
                    <div class="aspect-[16/10] w-full overflow-hidden bg-slate-100">
                        <img src="https://drive.google.com/thumbnail?id=1YSE0tN0WSfjeA0AYbRweC_pUP58nP02e&sz=w700" 
                             alt="Dự án đá mài Terrazzo Bảo tàng và Trường Đại học tại Đà Nẵng" 
                             class="w-full h-full object-cover">
                    </div>
                    <div class="p-3 flex-1 flex flex-col justify-between">
                        <div>
                            <span class="text-[11px] font-semibold text-mc-primary">Quận Hải Châu, Đà Nẵng</span>
                            <h3 class="product-title-full font-bold text-xs sm:text-sm text-mc-dark mt-1">
                                Thi công đá mài Terrazzo nghệ thuật tại Khu trưng bày & Tòa nhà văn phòng đường Trần Phú, Đà Nẵng
                            </h3>
                        </div>
                        <p class="text-[11px] text-slate-500 mt-2">Hạng mục: Đá mài Terrazzo nguyên khối & cầu thang</p>
                    </div>
                </div>

                <div class="bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm flex flex-col">
                    <div class="aspect-[16/10] w-full overflow-hidden bg-slate-100">
                        <img src="https://drive.google.com/thumbnail?id=1AXKSFrWkWGV_CIOqbGGYecZREk0VzU1k&sz=w700" 
                             alt="Dự án mài sàn bê tông và sơn Epoxy KCN Hòa Khánh Đà Nẵng" 
                             class="w-full h-full object-cover">
                    </div>
                    <div class="p-3 flex-1 flex flex-col justify-between">
                        <div>
                            <span class="text-[11px] font-semibold text-mc-primary">Quận Liên Chiểu, Đà Nẵng</span>
                            <h3 class="product-title-full font-bold text-xs sm:text-sm text-mc-dark mt-1">
                                Mài đánh bóng sàn bê tông lộ cốt liệu & Sơn Epoxy nhà xưởng tại KCN Hòa Khánh, TP Đà Nẵng
                            </h3>
                        </div>
                        <p class="text-[11px] text-slate-500 mt-2">Hạng mục: Mài bê tông 3.500m² & kẻ vạch Epoxy</p>
                    </div>
                </div>

                <div class="bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm flex flex-col">
                    <div class="aspect-[16/10] w-full overflow-hidden bg-slate-100">
                        <img src="https://drive.google.com/thumbnail?id=1g_-n827VKRmoUoQOfMVu6lJj4U7hmoc2&sz=w700" 
                             alt="Dự án thi công sàn Microcement Khách sạn Sơn Trà Đà Nẵng" 
                             class="w-full h-full object-cover">
                    </div>
                    <div class="p-3 flex-1 flex flex-col justify-between">
                        <div>
                            <span class="text-[11px] font-semibold text-mc-primary">Quận Sơn Trà, Đà Nẵng</span>
                            <h3 class="product-title-full font-bold text-xs sm:text-sm text-mc-dark mt-1">
                                Hoàn thiện sàn & tường hiệu ứng Microcement cho chuỗi Showroom, Cafe và Khách sạn ven biển Mỹ Khê
                            </h3>
                        </div>
                        <p class="text-[11px] text-slate-500 mt-2">Hạng mục: Sàn Microcement chống thấm liền mạch</p>
                    </div>
                </div>

            </div>
        </div>
    </section>

    <!-- ===================================================================== -->
    <!-- DANH MỤC CÁC BÀI VIẾT / TIN TỨC TRÊN TRANG CHỦ                        -->
    <!-- ===================================================================== -->
    <section id="tin-tuc" class="w-full py-8 bg-white border-t border-slate-200">
        <div class="flatsome-container">
            <div class="ux-section-title">
                <b></b>
                <span>DANH MỤC BÀI VIẾT & KINH NGHIỆM THI CÔNG</span>
                <b></b>
            </div>

            <div class="grid grid-cols-2 lg:grid-cols-4 gap-3 sm:gap-4">
                
                <article class="bg-slate-50 rounded-xl border border-slate-200 overflow-hidden flex flex-col">
                    <div class="aspect-[16/10] w-full bg-slate-200 overflow-hidden">
                        <img src="https://drive.google.com/thumbnail?id=1PsUMnTiNF0vzi9P834jOPQcQ9inXCHSm&sz=w600" 
                             alt="Quy trình 7 bước đánh bóng sàn đá Marble Granite" 
                             class="w-full h-full object-cover">
                    </div>
                    <div class="p-3 flex-1 flex flex-col justify-between">
                        <div>
                            <span class="text-[10.5px] font-bold text-mc-primary uppercase">Kỹ thuật sàn đá</span>
                            <h3 class="product-title-full font-bold text-xs sm:text-sm text-mc-dark mt-1">
                                Quy trình 7 bước mài phục hồi và đánh bóng sàn đá Marble, Granite đạt độ bóng gương tại Đà Nẵng
                            </h3>
                            <p class="text-xs text-slate-600 mt-1.5 hidden sm:block">
                                Hướng dẫn chi tiết cách xử lý đường ron ố vàng, mài lá số kim cương từ 50# đến 3000# và phủ chống thấm...
                            </p>
                        </div>
                        <a href="#bao-gia-lien-he" class="text-xs font-bold text-mc-primary hover:underline mt-2 inline-block">Xem chi tiết &raquo;</a>
                    </div>
                </article>

                <article class="bg-slate-50 rounded-xl border border-slate-200 overflow-hidden flex flex-col">
                    <div class="aspect-[16/10] w-full bg-slate-200 overflow-hidden">
                        <img src="https://drive.google.com/thumbnail?id=1RfQNvz0pxQNUMwzSYgFimrwg34O16VYV&sz=w600" 
                             alt="Hướng dẫn thi công đá mài Terrazzo bồn cây và hồ bơi" 
                             class="w-full h-full object-cover">
                    </div>
                    <div class="p-3 flex-1 flex flex-col justify-between">
                        <div>
                            <span class="text-[10.5px] font-bold text-mc-primary uppercase">Kiến thức Terrazzo</span>
                            <h3 class="product-title-full font-bold text-xs sm:text-sm text-mc-dark mt-1">
                                Hướng dẫn thi công hồ bơi, cầu thang và bồn cây bằng đá mài Terrazzo bền đẹp cho biệt thự
                            </h3>
                            <p class="text-xs text-slate-600 mt-1.5 hidden sm:block">
                                Bí quyết phối hạt đá Granite, đá cẩm thạch và thủy tinh tạo điểm nhấn sang trọng cho không gian xanh...
                            </p>
                        </div>
                        <a href="#bao-gia-lien-he" class="text-xs font-bold text-mc-primary hover:underline mt-2 inline-block">Xem chi tiết &raquo;</a>
                    </div>
                </article>

                <article class="bg-slate-50 rounded-xl border border-slate-200 overflow-hidden flex flex-col">
                    <div class="aspect-[16/10] w-full bg-slate-200 overflow-hidden">
                        <img src="https://drive.google.com/thumbnail?id=1tX9FDCFD64EgV2UM0c_P40ylsnGb4MP1&sz=w600" 
                             alt="Bảng giá mài đánh bóng sàn bê tông lộ cát tại Đà Nẵng" 
                             class="w-full h-full object-cover">
                    </div>
                    <div class="p-3 flex-1 flex flex-col justify-between">
                        <div>
                            <span class="text-[10.5px] font-bold text-mc-primary uppercase">Báo giá mài bê tông</span>
                            <h3 class="product-title-full font-bold text-xs sm:text-sm text-mc-dark mt-1">
                                Bảng giá dịch vụ mài đánh bóng sàn bê tông lộ cát, lộ đá hạt tiêu mới nhất tại Đà Nẵng
                            </h3>
                            <p class="text-xs text-slate-600 mt-1.5 hidden sm:block">
                                Phân tích các yếu tố ảnh hưởng đến đơn giá mài sàn bê tông: độ lộ cốt liệu, diện tích và độ cứng Mac bê tông...
                            </p>
                        </div>
                        <a href="#bao-gia-lien-he" class="text-xs font-bold text-mc-primary hover:underline mt-2 inline-block">Xem chi tiết &raquo;</a>
                    </div>
                </article>

                <article class="bg-slate-50 rounded-xl border border-slate-200 overflow-hidden flex flex-col">
                    <div class="aspect-[16/10] w-full bg-slate-200 overflow-hidden">
                        <img src="https://drive.google.com/thumbnail?id=1TXR9-xdfBuhNTGh1VVouv-qgJ4071leV&sz=w600" 
                             alt="Ứng dụng sàn Microcement và Sơn Epoxy trong nội thất" 
                             class="w-full h-full object-cover">
                    </div>
                    <div class="p-3 flex-1 flex flex-col justify-between">
                        <div>
                            <span class="text-[10.5px] font-bold text-mc-primary uppercase">Xu hướng vật liệu</span>
                            <h3 class="product-title-full font-bold text-xs sm:text-sm text-mc-dark mt-1">
                                So sánh sàn Microcement liền mạch và sơn sàn Epoxy tự san phẳng cho công trình hiện đại
                            </h3>
                            <p class="text-xs text-slate-600 mt-1.5 hidden sm:block">
                                Tư vấn lựa chọn giải pháp hoàn thiện bề mặt sàn tối ưu theo công năng sử dụng và ngân sách đầu tư...
                            </p>
                        </div>
                        <a href="#bao-gia-lien-he" class="text-xs font-bold text-mc-primary hover:underline mt-2 inline-block">Xem chi tiết &raquo;</a>
                    </div>
                </article>

            </div>
        </div>
    </section>

    <!-- ===================================================================== -->
    <!-- DANH MỤC CÁC ĐỐI TÁC & KHÁCH HÀNG TIÊU BIỂU                           -->
    <!-- ===================================================================== -->
    <section class="w-full py-8 bg-slate-50 border-t border-slate-200">
        <div class="flatsome-container">
            <div class="ux-section-title">
                <b></b>
                <span>ĐỐI TÁC & KHÁCH HÀNG CỦA MINH CHÂU STONE</span>
                <b></b>
            </div>
            <div class="grid grid-cols-2 sm:grid-cols-3 lg:grid-cols-6 gap-3">
                <div class="bg-white p-3.5 rounded-xl border border-slate-200 text-center flex flex-col items-center justify-center h-24 shadow-sm">
                    <i class="fa-solid fa-hotel text-xl text-mc-primary mb-1"></i>
                    <span class="font-extrabold text-xs text-mc-dark">SUN GROUP RESORT</span>
                    <span class="text-[10px] text-slate-500">Đối tác Dự án Nghỉ dưỡng</span>
                </div>
                <div class="bg-white p-3.5 rounded-xl border border-slate-200 text-center flex flex-col items-center justify-center h-24 shadow-sm">
                    <i class="fa-solid fa-building text-xl text-mc-primary mb-1"></i>
                    <span class="font-extrabold text-xs text-mc-dark">VINACONEX MIỀN TRUNG</span>
                    <span class="text-[10px] text-slate-500">Đối tác Xây dựng Hạ tầng</span>
                </div>
                <div class="bg-white p-3.5 rounded-xl border border-slate-200 text-center flex flex-col items-center justify-center h-24 shadow-sm">
                    <i class="fa-solid fa-city text-xl text-mc-primary mb-1"></i>
                    <span class="font-extrabold text-xs text-mc-dark">COTECCONS DESIGN</span>
                    <span class="text-[10px] text-slate-500">Tổng thầu Thi công</span>
                </div>
                <div class="bg-white p-3.5 rounded-xl border border-slate-200 text-center flex flex-col items-center justify-center h-24 shadow-sm">
                    <i class="fa-solid fa-flask text-xl text-mc-primary mb-1"></i>
                    <span class="font-extrabold text-xs text-mc-dark">KCC PAINT & EPOXY</span>
                    <span class="text-[10px] text-slate-500">Đối tác Hóa chất & Sơn</span>
                </div>
                <div class="bg-white p-3.5 rounded-xl border border-slate-200 text-center flex flex-col items-center justify-center h-24 shadow-sm">
                    <i class="fa-solid fa-industry text-xl text-mc-primary mb-1"></i>
                    <span class="font-extrabold text-xs text-mc-dark">SIKA VIỆT NAM</span>
                    <span class="text-[10px] text-slate-500">Phụ gia & Chống thấm</span>
                </div>
                <div class="bg-white p-3.5 rounded-xl border border-slate-200 text-center flex flex-col items-center justify-center h-24 shadow-sm">
                    <i class="fa-solid fa-gem text-xl text-mc-primary mb-1"></i>
                    <span class="font-extrabold text-xs text-mc-dark">3M FLOOR CARE</span>
                    <span class="text-[10px] text-slate-500">Thiết bị Pad Đánh bóng</span>
                </div>
            </div>
        </div>
    </section>

    <!-- ===================================================================== -->
    <!-- KHU VỰC TRANG CHỦ:                                                    -->
    <!-- 1. FORM YÊU CẦU TƯ VẤN VÀ BÁO GIÁ NHANH                               -->
    <!-- 2. FANPAGE FACEBOOK ĐƯA RA NGOÀI TRANG CHỦ                            -->
    <!-- 3. BẢN ĐỒ GOOGLE MAP ĐƯA RA NGOÀI TRANG CHỦ                           -->
    <!-- ===================================================================== -->
    <section id="bao-gia-lien-he" class="w-full py-8 bg-white border-t border-slate-200">
        <div class="flatsome-container">
            <div class="ux-section-title">
                <b></b>
                <span>YÊU CẦU BÁO GIÁ & KẾT NỐI TRỰC TIẾP</span>
                <b></b>
            </div>

            <div class="grid grid-cols-1 lg:grid-cols-12 gap-5 items-stretch">
                
                <!-- Cột 1 (5/12): Form Yêu Cầu & Báo Giá Trang Chủ -->
                <div class="lg:col-span-5 bg-slate-50 rounded-xl border border-slate-200 p-4 sm:p-5 flex flex-col justify-between shadow-sm">
                    <div>
                        <h3 class="text-base font-extrabold text-mc-dark uppercase flex items-center gap-2">
                            <i class="fa-solid fa-file-invoice-dollar text-mc-accent"></i> Đăng ký nhận báo giá miễn phí
                        </h3>
                        <p class="text-xs text-slate-600 mt-1 mb-4">
                            Điền thông tin diện tích và hạng mục cần thi công, kỹ thuật viên Minh Châu Stone sẽ gọi lại báo giá chi tiết trong 15 phút.
                        </p>

                        <form id="quoteForm" onsubmit="submitQuoteForm(event)" class="space-y-3">
                            <div>
                                <label class="block text-xs font-bold text-slate-700 mb-1">Họ và tên khách hàng *</label>
                                <input type="text" id="custName" required placeholder="Nhập họ và tên của bạn..." class="w-full px-3 py-2 text-xs sm:text-sm rounded-lg border border-slate-300 focus:outline-none focus:border-mc-primary bg-white">
                            </div>
                            <div class="grid grid-cols-1 sm:grid-cols-2 gap-3">
                                <div>
                                    <label class="block text-xs font-bold text-slate-700 mb-1">Số điện thoại / Zalo *</label>
                                    <input type="tel" id="custPhone" required placeholder="Ví dụ: 0975.796.543" class="w-full px-3 py-2 text-xs sm:text-sm rounded-lg border border-slate-300 focus:outline-none focus:border-mc-primary bg-white">
                                </div>
                                <div>
                                    <label class="block text-xs font-bold text-slate-700 mb-1">Diện tích ước tính (m²)</label>
                                    <input type="text" id="custArea" placeholder="Ví dụ: 150 m²" class="w-full px-3 py-2 text-xs sm:text-sm rounded-lg border border-slate-300 focus:outline-none focus:border-mc-primary bg-white">
                                </div>
                            </div>
                            <div>
                                <label class="block text-xs font-bold text-slate-700 mb-1">Hạng mục cần tư vấn & báo giá *</label>
                                <select id="custService" class="w-full px-3 py-2 text-xs sm:text-sm rounded-lg border border-slate-300 focus:outline-none focus:border-mc-primary bg-white">
                                    <option value="Đánh bóng sàn đá Marble / Granite">Đánh bóng sàn đá Marble / Granite</option>
                                    <option value="Thi công đá mài Terrazzo">Thi công đá mài Terrazzo</option>
                                    <option value="Mài đánh bóng sàn bê tông">Mài đánh bóng sàn bê tông</option>
                                    <option value="Thi công sơn sàn Epoxy">Thi công sơn sàn Epoxy</option>
                                    <option value="Thi công sàn & tường Microcement">Thi công sàn & tường Microcement</option>
                                    <option value="Cung cấp & ốp lát đá tự nhiên">Cung cấp & ốp lát đá tự nhiên</option>
                                </select>
                            </div>
                            <div>
                                <label class="block text-xs font-bold text-slate-700 mb-1">Địa chỉ công trình & Ghi chú</label>
                                <textarea id="custNote" rows="2" placeholder="Nhập địa chỉ công trình tại Đà Nẵng hoặc yêu cầu cụ thể..." class="w-full px-3 py-2 text-xs sm:text-sm rounded-lg border border-slate-300 focus:outline-none focus:border-mc-primary bg-white"></textarea>
                            </div>
                            <button type="submit" class="w-full bg-mc-dark hover:bg-mc-primary text-white font-extrabold text-xs sm:text-sm py-3 px-4 rounded-lg transition shadow flex items-center justify-center gap-2">
                                <i class="fa-solid fa-paper-plane text-mc-accent"></i> GỬI YÊU CẦU BÁO GIÁ NGAY
                            </button>
                        </form>

                        <!-- Hộp thông báo xác nhận gửi thành công (không dùng alert) -->
                        <div id="quoteSuccessBox" class="hidden mt-3 p-3 rounded-lg bg-emerald-50 border border-emerald-300 text-emerald-900 text-xs">
                            <p class="font-bold"><i class="fa-solid fa-circle-check text-emerald-600 mr-1"></i> Đã tiếp nhận yêu cầu báo giá!</p>
                            <p id="quoteSuccessText" class="mt-0.5"></p>
                        </div>
                    </div>
                </div>

                <!-- Cột 2 (3/12): Đưa Fanpage ra ngoài Trang Chủ -->
                <div class="lg:col-span-3 bg-slate-50 rounded-xl border border-slate-200 p-4 flex flex-col justify-between shadow-sm">
                    <div>
                        <h3 class="text-base font-extrabold text-mc-dark uppercase flex items-center gap-2 mb-3">
                            <i class="fa-brands fa-facebook text-[#1877F2]"></i> Fanpage Minh Châu Stone
                        </h3>

                        <!-- Khung hiển thị Fanpage trực quan ngoài trang chủ -->
                        <div class="rounded-xl overflow-hidden border border-slate-200 bg-white shadow-sm">
                            <div class="relative h-28 bg-mc-dark overflow-hidden">
                                <img src="https://drive.google.com/thumbnail?id=1QDZrsMiETa0VeHn5PFd8DgXq8nowxxT3&sz=w600" 
                                     alt="Ảnh bìa Fanpage Minh Châu Stone" 
                                     class="w-full h-full object-cover opacity-55">
                                <div class="absolute inset-0 bg-gradient-to-t from-black/80 via-black/30 to-transparent"></div>
                                <div class="absolute bottom-2.5 left-2.5 right-2.5 flex items-center gap-2.5">
                                    <img src="https://drive.google.com/thumbnail?id=11N1b7m-M43TQlNNmNUDPbXiDRWtZwVYB&sz=w200" 
                                         alt="Logo Fanpage" 
                                         class="w-12 h-12 rounded-lg border-2 border-white bg-white object-contain p-0.5 shrink-0">
                                    <div class="text-white overflow-hidden">
                                        <p class="font-extrabold text-xs sm:text-sm truncate">Minh Châu Stone Đà Nẵng</p>
                                        <p class="text-[11px] text-slate-200">4.850 người theo dõi • Đang hoạt động</p>
                                    </div>
                                </div>
                            </div>
                            <div class="p-3 space-y-2.5">
                                <p class="text-xs text-slate-600 leading-relaxed">
                                    Cập nhật hình ảnh công trình thi công đá mài Terrazzo, đánh bóng đá Marble - Granite, mài sàn bê tông thực tế mỗi ngày tại Đà Nẵng.
                                </p>
                                <div class="grid grid-cols-3 gap-1.5">
                                    <img src="https://drive.google.com/thumbnail?id=1PsUMnTiNF0vzi9P834jOPQcQ9inXCHSm&sz=w300" alt="Ảnh Fanpage 1" class="h-14 w-full object-cover rounded">
                                    <img src="https://drive.google.com/thumbnail?id=1YSE0tN0WSfjeA0AYbRweC_pUP58nP02e&sz=w300" alt="Ảnh Fanpage 2" class="h-14 w-full object-cover rounded">
                                    <img src="https://drive.google.com/thumbnail?id=1RfQNvz0pxQNUMwzSYgFimrwg34O16VYV&sz=w300" alt="Ảnh Fanpage 3" class="h-14 w-full object-cover rounded">
                                </div>
                                <div class="pt-1 flex gap-2">
                                    <a href="https://www.facebook.com" target="_blank" rel="noopener" class="flex-1 bg-[#1877F2] hover:bg-blue-700 text-white text-xs font-bold py-2 px-3 rounded text-center flex items-center justify-center gap-1.5">
                                        <i class="fa-brands fa-facebook-f"></i> Theo dõi Trang
                                    </a>
                                    <a href="https://zalo.me/0975796543" target="_blank" rel="noopener" class="flex-1 bg-slate-100 hover:bg-slate-200 text-mc-dark text-xs font-bold py-2 px-3 rounded text-center flex items-center justify-center gap-1.5">
                                        <i class="fa-brands fa-facebook-messenger text-[#1877F2]"></i> Nhắn tin
                                    </a>
                                </div>
                            </div>
                        </div>
                    </div>

                    <div class="mt-3 p-3 rounded-lg bg-white border border-slate-200 text-xs space-y-1">
                        <div class="font-bold text-mc-dark">Thông tin trực tuyến:</div>
                        <div><i class="fa-solid fa-globe text-mc-primary mr-1.5"></i>Website: <strong>minhchaustone.com</strong></div>
                        <div><i class="fa-solid fa-phone text-mc-primary mr-1.5"></i>Hotline: <strong>0975.796.543 - 0355.698.490</strong></div>
                    </div>
                </div>

                <!-- Cột 3 (4/12): Đưa Google Map ra ngoài Trang Chủ -->
                <div class="lg:col-span-4 bg-slate-50 rounded-xl border border-slate-200 p-4 flex flex-col justify-between shadow-sm">
                    <div>
                        <h3 class="text-base font-extrabold text-mc-dark uppercase flex items-center gap-2 mb-2">
                            <i class="fa-solid fa-map-location-dot text-red-600"></i> Bản đồ Google Map
                        </h3>
                        <p class="text-xs text-slate-600 mb-3">
                            <strong>Địa chỉ:</strong> Thửa đất số 217, Tờ bản đồ số 159, Lô 46-B2.21, TĐC Tân Trà, Phường Ngũ Hành Sơn, TP Đà Nẵng.
                        </p>
                        <div class="w-full h-64 sm:h-72 rounded-xl overflow-hidden border border-slate-300 shadow-inner bg-slate-200">
                            <iframe 
                                title="Bản đồ Công ty TNHH TM-DV Minh Châu Stone"
                                src="https://maps.google.com/maps?q=Khu%20T%C3%A1i%20%C4%90%E1%BB%8Bnh%20C%C6%B0%20T%C3%A2n%20Tr%C3%A0%2C%20Ng%C5%A9%20H%C3%A0nh%20S%C6%A1n%2C%20%C4%90%C3%A0%20N%E1%BA%B5ng&t=&z=15&ie=UTF8&iwloc=&output=embed" 
                                class="w-full h-full border-0" 
                                allowfullscreen="" 
                                loading="lazy" 
                                referrerpolicy="no-referrer-when-downgrade">
                            </iframe>
                        </div>
                    </div>
                    <div class="mt-3 flex items-center justify-between gap-2 pt-2 border-t border-slate-200 text-xs">
                        <span class="text-slate-600 font-medium"><i class="fa-solid fa-diamond-turn-right text-mc-primary mr-1"></i>Khu TĐC Tân Trà, Ngũ Hành Sơn</span>
                        <a href="https://www.google.com/maps/search/?api=1&query=T%C3%A2n+Tr%C3%A0+Ng%C5%A9+H%C3%A0nh+S%C6%A1n+%C4%90%C3%A0+N%E1%BA%B5ng" target="_blank" rel="noopener" class="font-bold text-mc-primary hover:underline shrink-0">
                            Mở bản đồ lớn &raquo;
                        </a>
                    </div>
                </div>

            </div>
        </div>
    </section>

    <!-- ===================================================================== -->
    <!-- KHU VỰC COPY MÃ SHORTCODE UX BUILDER FLATSOME DỄ DÀNG CHỈNH SỬA       -->
    <!-- ===================================================================== -->
    <section class="w-full py-6 bg-slate-100 border-t border-slate-200">
        <div class="flatsome-container">
            <div class="bg-white rounded-xl border border-slate-200 p-4 flex flex-col sm:flex-row items-start sm:items-center justify-between gap-3">
                <div>
                    <h3 class="text-xs sm:text-sm font-extrabold text-mc-dark flex items-center gap-2">
                        <i class="fa-solid fa-code text-mc-primary"></i> Mã cấu trúc chuẩn UX Builder Flatsome (Dành cho Quản trị viên)
                    </h3>
                    <p class="text-xs text-slate-600 mt-0.5">
                        Giao diện được thiết kế theo khối <code class="bg-slate-100 px-1 rounded">[section]</code>, <code class="bg-slate-100 px-1 rounded">[row]</code>, <code class="bg-slate-100 px-1 rounded">[col]</code> đơn giản để bạn dán vào trang chủ Flatsome và chỉnh sửa lại dễ dàng.
                    </p>
                </div>
                <div class="flex items-center gap-2 shrink-0">
                    <button onclick="toggleShortcodeModal()" class="bg-slate-800 hover:bg-slate-900 text-white text-xs font-bold py-2 px-3.5 rounded-lg transition">
                        Xem / Sao chép Shortcode UX Builder
                    </button>
                </div>
            </div>

            <div id="uxShortcodePanel" class="hidden mt-3 bg-slate-900 text-slate-100 rounded-xl p-4 text-xs font-mono">
                <div class="flex items-center justify-between pb-2 mb-2 border-b border-slate-700">
                    <span class="text-mc-accent font-bold">Shortcode UX Builder Flatsome (minhchaustone.com)</span>
                    <button onclick="copyUxShortcode()" id="copyShortcodeBtn" class="bg-mc-accent text-slate-950 font-sans font-bold px-3 py-1 rounded text-xs">
                        Sao chép mã
                    </button>
                </div>
                <textarea id="uxShortcodeText" readonly class="w-full h-44 bg-slate-950 text-emerald-300 p-3 rounded border border-slate-700 focus:outline-none text-xs">[section label="Banner Slider Minh Chau Stone" padding="0px"]
[ux_slider timer="4500" arrows="true" bullets="true"]
[ux_banner height="450px" height__sm="260px" bg="https://drive.google.com/thumbnail?id=1QDZrsMiETa0VeHn5PFd8DgXq8nowxxT3&sz=w1600" bg_overlay="rgba(12,35,64,0.75)"]
[text_box width="75" width__sm="92" position_x="50" position_y="50" text_align="center"]
<h4>CÔNG TY TNHH TM-DV MINH CHÂU STONE</h4>
<h2>CHUYÊN ĐÁNH BÓNG SÀN ĐÁ MARBLE, GRANITE & ĐÁ MÀI TERRAZZO ĐÀ NẴNG</h2>
<p>Hotline: 0975.796.543 - 0355.698.490 | Website: minhchaustone.com</p>
[/text_box]
[/ux_banner]
[ux_banner height="450px" height__sm="260px" bg="https://drive.google.com/thumbnail?id=1YSE0tN0WSfjeA0AYbRweC_pUP58nP02e&sz=w1600" bg_overlay="rgba(12,35,64,0.75)"]
[text_box width="75" width__sm="92" position_x="50" position_y="50" text_align="center"]
<h4>CÔNG NGHỆ MÀI BÓNG & PHỦ SÀN HIỆN ĐẠI</h4>
<h2>THI CÔNG SƠN EPOXY, MÀI BÊ TÔNG & SÀN MICROCEMENT ĐÀ NẴNG</h2>
<p>Địa chỉ: Thửa đất số 217, Tờ bản đồ số 159, Lô 46-B2.21, TĐC Tân Trà, P. Ngũ Hành Sơn, TP Đà Nẵng</p>
[/text_box]
[/ux_banner]
[/ux_slider]
[/section]

[section label="Danh muc Dich vu & San pham" padding="40px"]
[title style="center" text="DANH MỤC SẢN PHẨM & DỊCH VỤ THI CÔNG"]
[ux_products columns="5" columns__sm="2" ids="1,2,3,4,5,6,7,8,9,10"]
[/section]

[section label="Du an Da Nang" bg="#f8fafc" padding="40px"]
[title style="center" text="DỰ ÁN THI CÔNG THỰC TẾ TẠI ĐÀ NẴNG"]
[blog_posts style="normal" columns="4" columns__sm="2" posts="4"]
[/section]</textarea>
            </div>
        </div>
    </section>

    <!-- ===================================================================== -->
    <!-- FOOTER CHÂN TRANG GIỐNG MẪU BACTRUNG.COM                              -->
    <!-- ===================================================================== -->
    <footer class="bg-mc-dark text-slate-200 pt-10 pb-20 md:pb-8 border-t-4 border-mc-accent w-full mt-auto">
        <div class="flatsome-container">
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-12 gap-6 pb-8 border-b border-slate-700/80">
                
                <!-- Cột 1: Thông tin liên hệ -->
                <div class="lg:col-span-5 space-y-2.5">
                    <div class="flex items-center gap-2.5">
                        <img src="https://drive.google.com/thumbnail?id=11N1b7m-M43TQlNNmNUDPbXiDRWtZwVYB&sz=w200" 
                             alt="Logo Minh Châu Stone" 
                             class="w-10 h-10 rounded bg-white p-1 object-contain">
                        <div>
                            <h3 class="font-extrabold text-white text-sm sm:text-base uppercase">CÔNG TY TNHH TM-DV MINH CHÂU STONE</h3>
                            <p class="text-xs text-mc-accent font-semibold">Website: minhchaustone.com</p>
                        </div>
                    </div>
                    <ul class="text-xs space-y-2 text-slate-300 pt-1">
                        <li class="flex items-start gap-2">
                            <i class="fa-solid fa-location-dot text-mc-accent mt-1 shrink-0"></i>
                            <span><strong>Địa chỉ:</strong> Thửa đất số 217, Tờ bản đồ số 159, Lô 46-B2.21, TĐC Tân Trà, Phường Ngũ Hành Sơn, TP Đà Nẵng</span>
                        </li>
                        <li class="flex items-center gap-2">
                            <i class="fa-solid fa-phone-volume text-mc-accent shrink-0"></i>
                            <span><strong>Điện thoại / Hotline:</strong> 0975.796.543 - 0355.698.490</span>
                        </li>
                        <li class="flex items-center gap-2">
                            <i class="fa-solid fa-globe text-mc-accent shrink-0"></i>
                            <span><strong>Trang web:</strong> https://minhchaustone.com</span>
                        </li>
                    </ul>
                </div>

                <!-- Cột 2: Dịch vụ chính (Lấy từ web mẫu) -->
                <div class="lg:col-span-3 space-y-2">
                    <h4 class="font-extrabold text-white text-sm uppercase border-b border-slate-700 pb-1.5">DỊCH VỤ CHÍNH</h4>
                    <ul class="text-xs space-y-2 text-slate-300">
                        <li><a href="#san-pham-dich-vu" onclick="filterCategory('danh-bong-da')" class="hover:text-mc-accent transition"><i class="fa-solid fa-angle-right text-mc-accent mr-1.5"></i>Đánh bóng sàn đá Marble - Granite</a></li>
                        <li><a href="#san-pham-dich-vu" onclick="filterCategory('son-epoxy')" class="hover:text-mc-accent transition"><i class="fa-solid fa-angle-right text-mc-accent mr-1.5"></i>Thi công Sơn sàn Epoxy Đà Nẵng</a></li>
                        <li><a href="#san-pham-dich-vu" onclick="filterCategory('mai-be-tong')" class="hover:text-mc-accent transition"><i class="fa-solid fa-angle-right text-mc-accent mr-1.5"></i>Mài đánh bóng sàn bê tông</a></li>
                        <li><a href="#san-pham-dich-vu" onclick="filterCategory('terrazzo')" class="hover:text-mc-accent transition"><i class="fa-solid fa-angle-right text-mc-accent mr-1.5"></i>Thi công đá mài Terrazzo</a></li>
                        <li><a href="#san-pham-dich-vu" onclick="filterCategory('microcement')" class="hover:text-mc-accent transition"><i class="fa-solid fa-angle-right text-mc-accent mr-1.5"></i>Thi công sàn & tường Microcement</a></li>
                    </ul>
                </div>

                <!-- Cột 3: Chứng nhận & Hỗ trợ khách hàng -->
                <div class="lg:col-span-4 space-y-2">
                    <h4 class="font-extrabold text-white text-sm uppercase border-b border-slate-700 pb-1.5">THÔNG TIN HỖ TRỢ</h4>
                    <div class="grid grid-cols-2 gap-2 text-xs text-slate-300">
                        <a href="#du-an-da-nang" class="hover:text-mc-accent"><i class="fa-solid fa-angle-right text-mc-accent mr-1"></i>Hồ sơ năng lực</a>
                        <a href="#bao-gia-lien-he" class="hover:text-mc-accent"><i class="fa-solid fa-angle-right text-mc-accent mr-1"></i>Chính sách bảo hành</a>
                        <a href="#du-an-da-nang" class="hover:text-mc-accent"><i class="fa-solid fa-angle-right text-mc-accent mr-1"></i>Dự án tại Đà Nẵng</a>
                        <a href="#bao-gia-lien-he" class="hover:text-mc-accent"><i class="fa-solid fa-angle-right text-mc-accent mr-1"></i>Quy trình nghiệm thu</a>
                        <a href="#tin-tuc" class="hover:text-mc-accent"><i class="fa-solid fa-angle-right text-mc-accent mr-1"></i>Tin tức & Chia sẻ</a>
                        <a href="#bao-gia-lien-he" class="hover:text-mc-accent"><i class="fa-solid fa-angle-right text-mc-accent mr-1"></i>Liên hệ báo giá</a>
                    </div>
                </div>

            </div>

            <div class="pt-4 flex flex-col sm:flex-row items-center justify-between text-xs text-slate-400 gap-2 text-center">
                <p>Copyright 2026 © <strong>CÔNG TY TNHH TM-DV MINH CHÂU STONE</strong> (minhchaustone.com)</p>
                <p>Giao diện chuẩn Flatsome UX Builder - Tối ưu Máy tính (1500px) & Điện thoại</p>
            </div>
        </div>
    </footer>

    <!-- ===================================================================== -->
    <!-- CÁC NÚT LIÊN HỆ NỔI BẬT (ZALO, FACEBOOK, HOTLINE)                     -->
    <!-- TƯƠNG THÍCH MƯỢT MÀ TRÊN CẢ MÁY TÍNH VÀ ĐIỆN THOẠI                    -->
    <!-- ===================================================================== -->
    <div class="fixed bottom-4 left-3 z-50 flex flex-col gap-2.5 max-w-[calc(100vw-24px)]">
        
        <!-- Nút Facebook nổi bật -->
        <a href="https://www.facebook.com" target="_blank" rel="noopener" 
           class="flex items-center gap-2 bg-[#1877F2] hover:bg-blue-700 text-white rounded-full p-2 sm:pr-3.5 shadow-lg transition transform hover:-translate-y-0.5 w-fit">
            <span class="w-8 h-8 rounded-full bg-white text-[#1877F2] flex items-center justify-center font-bold text-base shrink-0">
                <i class="fa-brands fa-facebook-f"></i>
            </span>
            <span class="text-xs font-extrabold hidden sm:inline whitespace-nowrap">Facebook</span>
        </a>

        <!-- Nút Zalo nổi bật -->
        <a href="https://zalo.me/0975796543" target="_blank" rel="noopener" 
           class="flex items-center gap-2 bg-[#0068FF] hover:bg-blue-600 text-white rounded-full p-2 sm:pr-3.5 shadow-lg transition transform hover:-translate-y-0.5 w-fit">
            <span class="w-8 h-8 rounded-full bg-white text-[#0068FF] flex items-center justify-center font-extrabold text-[11px] shrink-0">
                Zalo
            </span>
            <span class="text-xs font-extrabold hidden sm:inline whitespace-nowrap">Chat Zalo: 0975.796.543</span>
        </a>

        <!-- Nút Hotline 1 & 2 nổi bật -->
        <div class="flex flex-wrap items-center gap-1.5">
            <a href="tel:0975796543" 
               class="pulse-btn flex items-center gap-2 bg-red-600 hover:bg-red-700 text-white rounded-full py-1.5 pl-2 pr-3.5 shadow-lg transition">
                <span class="w-7 h-7 rounded-full bg-white text-red-600 flex items-center justify-center text-xs shrink-0">
                    <i class="fa-solid fa-phone-volume"></i>
                </span>
                <span class="text-xs font-extrabold whitespace-nowrap">0975.796.543</span>
            </a>

            <a href="tel:0355698490" 
               class="flex items-center gap-1.5 bg-mc-dark hover:bg-mc-primary text-white border border-mc-accent rounded-full py-1.5 pl-2 pr-3 shadow-lg transition">
                <span class="w-7 h-7 rounded-full bg-mc-accent text-slate-950 flex items-center justify-center text-xs shrink-0">
                    <i class="fa-solid fa-phone"></i>
                </span>
                <span class="text-xs font-extrabold whitespace-nowrap">0355.698.490</span>
            </a>
        </div>
    </div>

    <!-- ===================================================================== -->
    <!-- JAVASCRIPT XỬ LÝ SLIDER TỰ TRƯỢT, LỌC DANH MỤC & FORM BÁO GIÁ         -->
    <!-- ===================================================================== -->
    <script>
        // 1. Tự động trượt 2 Banner chuyên nghiệp
        let currentSlideIndex = 0;
        const slides = document.querySelectorAll('.banner-slide');
        const totalSlides = slides.length;
        let slideInterval = null;

        function showSlide(index) {
            currentSlideIndex = (index + totalSlides) % totalSlides;
            slides.forEach((slide, idx) => {
                if (idx === currentSlideIndex) {
                    slide.classList.remove('hidden');
                    slide.classList.add('block');
                } else {
                    slide.classList.remove('block');
                    slide.classList.add('hidden');
                }
            });

            // Cập nhật chấm tròn
            const dot0 = document.getElementById('dot-0');
            const dot1 = document.getElementById('dot-1');
            if (dot0 && dot1) {
                if (currentSlideIndex === 0) {
                    dot0.className = 'w-6 h-2 rounded-full bg-mc-accent transition-all';
                    dot1.className = 'w-2.5 h-2 rounded-full bg-white/60 transition-all';
                } else {
                    dot1.className = 'w-6 h-2 rounded-full bg-mc-accent transition-all';
                    dot0.className = 'w-2.5 h-2 rounded-full bg-white/60 transition-all';
                }
            }
        }

        function changeSlide(step) {
            showSlide(currentSlideIndex + step);
            resetSlideTimer();
        }

        function goToSlide(index) {
            showSlide(index);
            resetSlideTimer();
        }

        function resetSlideTimer() {
            if (slideInterval) clearInterval(slideInterval);
            slideInterval = setInterval(() => {
                showSlide(currentSlideIndex + 1);
            }, 4800);
        }

        // 2. Bật / Tắt Menu Danh mục trên Điện thoại
        function toggleMobileMenu() {
            const drawer = document.getElementById('mobileMenuDrawer');
            if (drawer) {
                drawer.classList.toggle('hidden');
            }
        }

        // 3. Lọc sản phẩm theo Danh mục ở Trang chủ
        function filterCategory(category) {
            const cards = document.querySelectorAll('.product-card');
            const buttons = document.querySelectorAll('[data-cat-btn]');

            buttons.forEach(btn => {
                if (btn.getAttribute('data-cat-btn') === category) {
                    btn.classList.add('active');
                } else {
                    btn.classList.remove('active');
                }
            });

            cards.forEach(card => {
                const itemCat = card.getAttribute('data-category');
                if (category === 'all' || itemCat === category) {
                    card.classList.remove('hidden');
                    card.classList.add('flex');
                } else {
                    card.classList.remove('flex');
                    card.classList.add('hidden');
                }
            });
        }

        // 4. Xử lý gửi Form Yêu cầu & Báo giá trên Trang chủ
        function submitQuoteForm(e) {
            e.preventDefault();
            const name = document.getElementById('custName').value.trim();
            const phone = document.getElementById('custPhone').value.trim();
            const area = document.getElementById('custArea').value.trim() || 'Chưa xác định';
            const service = document.getElementById('custService').value;

            const box = document.getElementById('quoteSuccessBox');
            const text = document.getElementById('quoteSuccessText');

            text.textContent = `Cảm ơn ${name} (${phone}). Yêu cầu báo giá hạng mục "${service}" (Diện tích: ${area}) đã được ghi nhận. Bộ phận kỹ thuật Minh Châu Stone (0975.796.543 - 0355.698.490) sẽ liên hệ tư vấn ngay!`;
            box.classList.remove('hidden');
            document.getElementById('quoteForm').reset();
        }

        // 5. Xem và Sao chép Shortcode UX Builder Flatsome
        function toggleShortcodeModal() {
            const panel = document.getElementById('uxShortcodePanel');
            if (panel) panel.classList.toggle('hidden');
        }

        function copyUxShortcode() {
            const textarea = document.getElementById('uxShortcodeText');
            const btn = document.getElementById('copyShortcodeBtn');
            if (textarea) {
                textarea.select();
                document.execCommand('copy');
                btn.textContent = 'Đã sao chép!';
                setTimeout(() => {
                    btn.textContent = 'Sao chép mã';
                }, 2000);
            }
        }

        window.onload = function() {
            resetSlideTimer();
        };
    </script>
</body>
</html>
