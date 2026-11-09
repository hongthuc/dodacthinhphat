<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
    <title>CÔNG TY TNHH ĐO ĐẠC BẢN ĐỒ THỊNH PHÁT - dodacthinhphat.com</title>
    <meta name="description" content="Công Ty TNHH Đo Đạc Bản Đồ Thịnh Phát (dodacthinhphat.com) chuyên dịch vụ đo đạc địa chính, khảo sát địa hình, quan trắc công trình tại Đà Nẵng và phân phối máy trắc địa chính hãng. Hotline: 0933.210.234">
    <meta name="keywords" content="đo đạc thịnh phát, dodacthinhphat.com, đo đạc đà nẵng, đo đạc điện bàn, máy thủy bình, máy toàn đạc, máy gps rtk, công ty đo đạc bản đồ thịnh phát">
    
    <!-- Open Graph / Thumbnail là ảnh Logo trang web khi gửi link -->
    <meta property="og:type" content="website">
    <meta property="og:url" content="https://dodacthinhphat.com/">
    <meta property="og:site_name" content="dodacthinhphat.com">
    <meta property="og:title" content="CÔNG TY TNHH ĐO ĐẠC BẢN ĐỒ THỊNH PHÁT | dodacthinhphat.com">
    <meta property="og:description" content="Đơn vị chuyên dịch vụ đo đạc bản đồ, khảo sát trắc địa, giấy tờ nhà đất tại Đà Nẵng và cung cấp máy đo đạc trắc địa chính hãng. Địa chỉ: 03 Hoàng Diệu, Phường Điện Bàn, TP Đà Nẵng. ĐT: 0933.210.234">
    <meta property="og:image" content="https://lh3.googleusercontent.com/d/1ylpV3nYsUV8yzyT1BcMmwl435tdVhAtk">
    <meta property="og:image:secure_url" content="https://lh3.googleusercontent.com/d/1ylpV3nYsUV8yzyT1BcMmwl435tdVhAtk">
    <meta property="og:image:alt" content="Logo Công Ty TNHH Đo Đạc Bản Đồ Thịnh Phát">
    <meta name="twitter:card" content="summary_large_image">
    <meta name="twitter:title" content="CÔNG TY TNHH ĐO ĐẠC BẢN ĐỒ THỊNH PHÁT - dodacthinhphat.com">
    <meta name="twitter:image" content="https://lh3.googleusercontent.com/d/1ylpV3nYsUV8yzyT1BcMmwl435tdVhAtk">
    <link rel="icon" type="image/png" href="https://lh3.googleusercontent.com/d/1ylpV3nYsUV8yzyT1BcMmwl435tdVhAtk">
    <link rel="apple-touch-icon" href="https://lh3.googleusercontent.com/d/1ylpV3nYsUV8yzyT1BcMmwl435tdVhAtk">

    <!-- Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- Font Awesome Icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">
    <!-- Google Fonts: Inter & Roboto chuẩn Flatsome -->
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&display=swap" rel="stylesheet">

    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        brand: {
                            DEFAULT: '#0B4F8A',
                            dark: '#073661',
                            light: '#EBF4FC',
                            accent: '#E65100',
                            gold: '#F59E0B'
                        }
                    },
                    fontFamily: {
                        sans: ['Inter', 'sans-serif']
                    }
                }
            }
        }
    </script>

    <style>
        /* Chống tràn viền và chống lệch phải tuyệt đối trên mọi thiết bị */
        *, *::before, *::after {
            box-sizing: border-box;
        }
        html, body {
            width: 100%;
            max-width: 100vw;
            overflow-x: hidden;
            margin: 0;
            padding: 0;
            font-family: 'Inter', sans-serif;
            background-color: #f8fafc;
            color: #1e293b;
            scroll-behavior: smooth;
        }

        /* Khung chuẩn Flatsome 1500px trên máy tính */
        .flatsome-container {
            width: 100%;
            max-width: 1500px;
            margin-left: auto;
            margin-right: auto;
            padding-left: 12px;
            padding-right: 12px;
        }
        @media (min-width: 1024px) {
            .flatsome-container {
                padding-left: 20px;
                padding-right: 20px;
            }
        }

        /* Tối ưu tên danh mục trên máy tính: viết liền trên 1 hàng, không tự xuống dòng trong từng tên danh mục */
        .nav-cat-list {
            display: flex;
            flex-wrap: wrap;
            align-items: center;
            justify-content: center;
            gap: 2px 4px;
        }
        .nav-cat-item {
            white-space: nowrap !important;
            display: inline-flex;
            align-items: center;
            font-size: 12px;
            font-weight: 600;
            padding: 7px 9px;
            border-radius: 4px;
            transition: all 0.2s ease;
            line-height: 1.2;
        }
        @media (min-width: 1280px) {
            .nav-cat-item {
                font-size: 12.5px;
                padding: 8px 10px;
            }
        }
        .nav-cat-item:hover {
            background-color: rgba(255, 255, 255, 0.16);
        }

        /* Dropdown menu chuẩn Flatsome */
        .has-dropdown {
            position: relative;
        }
        .dropdown-menu {
            display: none;
            position: absolute;
            top: 100%;
            left: 0;
            min-width: 230px;
            background: #ffffff;
            box-shadow: 0 10px 25px rgba(0, 0, 0, 0.15);
            border-top: 3px solid #E65100;
            border-radius: 0 0 6px 6px;
            z-index: 100;
            padding: 6px 0;
        }
        .has-dropdown:hover .dropdown-menu {
            display: block;
        }
        .dropdown-menu a {
            display: block;
            padding: 8px 14px;
            font-size: 12.5px;
            color: #1e293b;
            font-weight: 500;
            white-space: nowrap;
            border-bottom: 1px solid #f1f5f9;
        }
        .dropdown-menu a:last-child {
            border-bottom: none;
        }
        .dropdown-menu a:hover {
            background-color: #EBF4FC;
            color: #0B4F8A;
            padding-left: 18px;
            transition: all 0.15s ease;
        }

        /* Danh mục chọn nhanh ở trang chủ chữ nhỏ gọn, viết liền trên 1 hàng trong từng nút */
        .home-cat-pill {
            white-space: nowrap !important;
            font-size: 12px;
            line-height: 1.25;
            padding: 7px 12px;
            border-radius: 6px;
            font-weight: 600;
            transition: all 0.2s ease;
            cursor: pointer;
            border: 1px solid #cbd5e1;
            background: #ffffff;
            color: #0f172a;
        }
        .home-cat-pill:hover, .home-cat-pill.active {
            background: #0B4F8A;
            color: #ffffff;
            border-color: #0B4F8A;
        }

        /* Tiêu đề Section chuẩn Flatsome (Section Title Divider) */
        .flatsome-section-title {
            display: flex;
            align-items: center;
            justify-content: space-between;
            border-bottom: 2px solid #e2e8f0;
            margin-bottom: 18px;
            padding-bottom: 8px;
        }
        .flatsome-section-title h2 {
            position: relative;
            font-weight: 800;
            text-transform: uppercase;
            color: #0B4F8A;
            letter-spacing: 0.2px;
        }
        .flatsome-section-title h2::after {
            content: '';
            position: absolute;
            bottom: -10px;
            left: 0;
            width: 100%;
            height: 3px;
            background-color: #E65100;
        }

        /* Tên sản phẩm hiển thị đầy đủ, không bị cắt chữ hoặc tràn viền */
        .product-title-full {
            white-space: normal !important;
            overflow: visible !important;
            text-overflow: clip !important;
            word-break: break-word;
            line-height: 1.38;
        }

        /* Hiệu ứng nút liên hệ nổi */
        @keyframes pulse-ring {
            0% { transform: scale(0.95); box-shadow: 0 0 0 0 rgba(230, 81, 0, 0.7); }
            70% { transform: scale(1); box-shadow: 0 0 0 10px rgba(230, 81, 0, 0); }
            100% { transform: scale(0.95); box-shadow: 0 0 0 0 rgba(230, 81, 0, 0); }
        }
        .pulse-btn {
            animation: pulse-ring 2s infinite;
        }
    </style>
</head>
<body class="bg-slate-50 text-slate-800">

    <!-- TOP BAR CHUẨN FLATSOME (Không hiển thị thanh chỉnh sửa UX Builder) -->
    <div class="bg-brand-dark text-white text-[11.5px] sm:text-xs py-1.5 border-b border-white/10">
        <div class="flatsome-container flex flex-wrap items-center justify-between gap-2">
            <div class="flex items-center gap-3 sm:gap-5 flex-wrap">
                <span class="inline-flex items-center gap-1.5 font-medium">
                    <i class="fa-solid fa-building text-amber-400"></i>
                    <span>CÔNG TY TNHH ĐO ĐẠC BẢN ĐỒ THỊNH PHÁT</span>
                </span>
                <span class="hidden md:inline-flex items-center gap-1.5 text-slate-200">
                    <i class="fa-solid fa-location-dot text-amber-400"></i>
                    <span>03 Hoàng Diệu, Phường Điện Bàn, TP Đà Nẵng</span>
                </span>
            </div>
            <div class="flex items-center gap-3 sm:gap-4 ml-auto">
                <a href="https://dodacthinhphat.com" class="hover:text-amber-300 inline-flex items-center gap-1">
                    <i class="fa-solid fa-globe text-amber-400"></i>
                    <span>dodacthinhphat.com</span>
                </a>
                <span class="text-white/30">|</span>
                <a href="https://www.facebook.com/Thinhphatdodac" target="_blank" rel="noopener noreferrer" class="hover:text-amber-300 inline-flex items-center gap-1">
                    <i class="fa-brands fa-facebook text-amber-400"></i>
                    <span>Fanpage Thịnh Phát</span>
                </a>
                <span class="text-white/30 hidden sm:inline">|</span>
                <a href="https://maps.app.goo.gl/HaoxaQqEpM7oMdmp6" target="_blank" rel="noopener noreferrer" class="hidden sm:inline-flex hover:text-amber-300 items-center gap-1">
                    <i class="fa-solid fa-map-location-dot text-amber-400"></i>
                    <span>Chỉ đường Map</span>
                </a>
            </div>
        </div>
    </div>

    <!-- HEADER CHÍNH (Logo chỉnh gọn nhỏ lại, KHÔNG để nút gọi ngay trên header tránh tràn viền) -->
    <header class="bg-white shadow-sm sticky top-0 z-50 border-b border-slate-200">
        <div class="flatsome-container py-2.5 flex items-center justify-between gap-3">
            <!-- Logo gọn nhỏ + Tên Công Ty -->
            <a href="#trang-chu" class="flex items-center gap-2.5 min-w-0">
                <img 
                    src="https://lh3.googleusercontent.com/d/1ylpV3nYsUV8yzyT1BcMmwl435tdVhAtk" 
                    onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1ylpV3nYsUV8yzyT1BcMmwl435tdVhAtk&sz=w400';"
                    alt="Logo Công Ty TNHH Đo Đạc Bản Đồ Thịnh Phát" 
                    class="w-10 h-10 sm:w-11 sm:h-11 object-contain rounded border border-slate-200 p-0.5 bg-white shrink-0"
                >
                <div class="min-w-0">
                    <div class="text-brand font-extrabold text-[13px] sm:text-[15px] md:text-[16px] leading-tight uppercase truncate">
                        ĐO ĐẠC BẢN ĐỒ THỊNH PHÁT
                    </div>
                    <div class="text-[11px] sm:text-xs text-slate-500 font-medium truncate">
                        dodacthinhphat.com • 03 Hoàng Diệu, Điện Bàn, Đà Nẵng
                    </div>
                </div>
            </a>

            <!-- Ô tìm kiếm sản phẩm & dịch vụ trên máy tính -->
            <div class="hidden lg:flex items-center flex-1 max-w-md mx-4">
                <div class="relative w-full">
                    <input 
                        type="text" 
                        id="searchInputDesktop"
                        oninput="handleSearchProduct(this.value)"
                        placeholder="Tìm máy thủy bình, máy RTK, toàn đạc, dịch vụ đo đạc..." 
                        class="w-full pl-3.5 pr-9 py-1.5 text-xs border border-slate-300 rounded-md focus:outline-none focus:border-brand"
                    >
                    <button type="button" class="absolute right-2.5 top-1/2 -translate-y-1/2 text-slate-400 hover:text-brand">
                        <i class="fa-solid fa-magnifying-glass text-xs"></i>
                    </button>
                </div>
            </div>

            <!-- Thông tin địa chỉ & giờ làm việc dạng chữ gọn (Không để nút gọi ngay) -->
            <div class="hidden xl:flex items-center gap-5 text-xs text-slate-600 shrink-0">
                <div class="flex items-center gap-2">
                    <i class="fa-solid fa-certificate text-brand text-sm"></i>
                    <div>
                        <div class="font-bold text-slate-800">Chuẩn TCVN & Pháp Lý</div>
                        <div class="text-[11px] text-slate-500">Thiết bị chính hãng 100%</div>
                    </div>
                </div>
                <div class="flex items-center gap-2">
                    <i class="fa-solid fa-clock text-brand text-sm"></i>
                    <div>
                        <div class="font-bold text-slate-800">Hỗ Trợ Kỹ Thuật 24/7</div>
                        <div class="text-[11px] text-slate-500">Đà Nẵng & Toàn Quốc</div>
                    </div>
                </div>
            </div>

            <!-- Nút mở Menu Danh Mục trên Điện Thoại -->
            <button 
                type="button" 
                onclick="toggleMobileMenu()" 
                aria-label="Mở danh mục"
                class="lg:hidden inline-flex items-center gap-1.5 px-2.5 py-1.5 rounded bg-brand text-white text-xs font-semibold shrink-0"
            >
                <i class="fa-solid fa-bars"></i>
                <span>DANH MỤC</span>
            </button>
        </div>

        <!-- THANH DANH MỤC TRÊN MÁY TÍNH (Chữ nhỏ gọn, viết liền trên 1 hàng, không xuống dòng giữa tên danh mục) -->
        <nav class="hidden lg:block bg-brand text-white border-t border-brand-dark">
            <div class="flatsome-container py-1">
                <ul class="nav-cat-list">
                    <li>
                        <a href="#trang-chu" class="nav-cat-item bg-brand-accent text-white">
                            <i class="fa-solid fa-house mr-1 text-[11px]"></i>TRANG CHỦ
                        </a>
                    </li>
                    <li class="has-dropdown">
                        <a href="#dich-vu-trac-dia" class="nav-cat-item">
                            DỊCH VỤ TRẮC ĐỊA <i class="fa-solid fa-angle-down ml-1 text-[10px]"></i>
                        </a>
                        <div class="dropdown-menu">
                            <a href="#dich-vu-trac-dia">Đo Đạc Nhà Đất Đà Nẵng</a>
                            <a href="#dich-vu-trac-dia">Giấy Tờ Nhà Đất & Sổ Đỏ</a>
                            <a href="#dich-vu-trac-dia">Xin Phép Xây Dựng</a>
                            <a href="#dich-vu-trac-dia">Xác Định Ranh Đất & Cắm Mốc</a>
                            <a href="#dich-vu-trac-dia">Đề Cương Quan Trắc Lún Nghiêng</a>
                        </div>
                    </li>
                    <li class="has-dropdown">
                        <a href="#san-pham" onclick="filterCategory('may-thuy-binh')" class="nav-cat-item">
                            MÁY THUỶ BÌNH <i class="fa-solid fa-angle-down ml-1 text-[10px]"></i>
                        </a>
                        <div class="dropdown-menu">
                            <a href="#san-pham" onclick="filterCategory('may-thuy-binh')">Máy Thủy Bình Bán Chạy</a>
                            <a href="#san-pham" onclick="filterCategory('may-thuy-binh')">Máy Thủy Bình Giá Rẻ</a>
                            <a href="#san-pham" onclick="filterCategory('may-thuy-binh')">Máy Thủy Bình Leica</a>
                            <a href="#san-pham" onclick="filterCategory('may-thuy-binh')">Máy Thủy Bình Sokkia</a>
                            <a href="#san-pham" onclick="filterCategory('may-thuy-binh')">Máy Thủy Bình Topcon</a>
                            <a href="#san-pham" onclick="filterCategory('may-thuy-binh')">Máy Thủy Bình Pentax</a>
                            <a href="#san-pham" onclick="filterCategory('may-thuy-binh')">Máy Thủy Bình Bosch</a>
                            <a href="#san-pham" onclick="filterCategory('may-thuy-binh')">Máy Thủy Bình Nikon</a>
                            <a href="#san-pham" onclick="filterCategory('may-thuy-binh')">Máy Thủy Bình SatLab & Hi-Target</a>
                        </div>
                    </li>
                    <li class="has-dropdown">
                        <a href="#san-pham" onclick="filterCategory('may-do-laser')" class="nav-cat-item">
                            MÁY ĐO LASER <i class="fa-solid fa-angle-down ml-1 text-[10px]"></i>
                        </a>
                        <div class="dropdown-menu">
                            <a href="#san-pham" onclick="filterCategory('may-do-laser')">Máy Cân Bằng Laser</a>
                            <a href="#san-pham" onclick="filterCategory('may-do-laser')">Thước Đo Khoảng Cách Laser</a>
                            <a href="#san-pham" onclick="filterCategory('may-do-laser')">Máy Cân Bằng Laisai</a>
                            <a href="#san-pham" onclick="filterCategory('may-do-laser')">Máy Cân Bằng Sincon & Geotes</a>
                            <a href="#san-pham" onclick="filterCategory('may-do-laser')">Phụ Kiện Máy Laser</a>
                        </div>
                    </li>
                    <li class="has-dropdown">
                        <a href="#san-pham" onclick="filterCategory('may-gps-rtk')" class="nav-cat-item">
                            MÁY GPS GNSS RTK <i class="fa-solid fa-angle-down ml-1 text-[10px]"></i>
                        </a>
                        <div class="dropdown-menu">
                            <a href="#san-pham" onclick="filterCategory('may-gps-rtk')">Máy GNSS RTK 2 Tần Số</a>
                            <a href="#san-pham" onclick="filterCategory('may-gps-rtk')">Máy Định Vị GPS Garmin</a>
                        </div>
                    </li>
                    <li class="has-dropdown">
                        <a href="#san-pham" onclick="filterCategory('may-toan-dac')" class="nav-cat-item">
                            MÁY TOÀN ĐẠC <i class="fa-solid fa-angle-down ml-1 text-[10px]"></i>
                        </a>
                        <div class="dropdown-menu">
                            <a href="#san-pham" onclick="filterCategory('may-toan-dac')">Máy Toàn Đạc Leica</a>
                            <a href="#san-pham" onclick="filterCategory('may-toan-dac')">Máy Toàn Đạc Nikon</a>
                            <a href="#san-pham" onclick="filterCategory('may-toan-dac')">Máy Toàn Đạc Sokkia</a>
                            <a href="#san-pham" onclick="filterCategory('may-toan-dac')">Máy Toàn Đạc Topcon</a>
                            <a href="#san-pham" onclick="filterCategory('may-toan-dac')">Máy Toàn Đạc Geomax</a>
                        </div>
                    </li>
                    <li class="has-dropdown">
                        <a href="#san-pham" onclick="filterCategory('may-kinh-vi-bo-dam')" class="nav-cat-item">
                            MÁY KINH VĨ & BỘ ĐÀM <i class="fa-solid fa-angle-down ml-1 text-[10px]"></i>
                        </a>
                        <div class="dropdown-menu">
                            <a href="#san-pham" onclick="filterCategory('may-kinh-vi-bo-dam')">Máy Kinh Vĩ Điện Tử</a>
                            <a href="#san-pham" onclick="filterCategory('may-kinh-vi-bo-dam')">Máy Đo Sâu Hồi Âm</a>
                            <a href="#san-pham" onclick="filterCategory('may-kinh-vi-bo-dam')">Bộ Đàm Cầm Tay Motorola</a>
                        </div>
                    </li>
                    <li class="has-dropdown">
                        <a href="#san-pham" onclick="filterCategory('phu-kien-trac-dia')" class="nav-cat-item">
                            PHỤ KIỆN TRẮC ĐỊA <i class="fa-solid fa-angle-down ml-1 text-[10px]"></i>
                        </a>
                        <div class="dropdown-menu">
                            <a href="#san-pham" onclick="filterCategory('phu-kien-trac-dia')">Chân – Mia – Mốc – Bọt Thủy – Đế Máy</a>
                            <a href="#san-pham" onclick="filterCategory('phu-kien-trac-dia')">Pin – Sạc – Adapter – Cáp Trút</a>
                            <a href="#san-pham" onclick="filterCategory('phu-kien-trac-dia')">Thước Thép – Thước Cuộn – Thước Dây</a>
                            <a href="#san-pham" onclick="filterCategory('phu-kien-trac-dia')">Gương Sáo – Kẹp Máy Toàn Đạc</a>
                            <a href="#san-pham" onclick="filterCategory('phu-kien-trac-dia')">Bánh Xe Đo Khoảng Cách</a>
                        </div>
                    </li>
                    <li>
                        <a href="#san-pham" onclick="filterCategory('cho-thue-may')" class="nav-cat-item">
                            CHO THUÊ MÁY ĐO ĐẠC
                        </a>
                    </li>
                    <li>
                        <a href="#du-an-da-nang" class="nav-cat-item">
                            DỰ ÁN ĐÀ NẴNG
                        </a>
                    </li>
                    <li>
                        <a href="#hinh-anh-thuc-te" class="nav-cat-item">
                            HÌNH ẢNH THỰC TẾ
                        </a>
                    </li>
                    <li>
                        <a href="#bai-viet" class="nav-cat-item">
                            BÀI VIẾT
                        </a>
                    </li>
                    <li>
                        <a href="#form-bao-gia" class="nav-cat-item">
                            LIÊN HỆ BÁO GIÁ
                        </a>
                    </li>
                </ul>
            </div>
        </nav>

        <!-- MENU DANH MỤC TRÊN ĐIỆN THOẠI (Thiết kế gọn đẹp, rõ ràng) -->
        <div id="mobileMenuDrawer" class="hidden lg:hidden bg-white border-t border-slate-200 px-3 py-3 shadow-inner">
            <div class="mb-2.5">
                <input 
                    type="text" 
                    oninput="handleSearchProduct(this.value)"
                    placeholder="Tìm nhanh sản phẩm, máy đo đạc..." 
                    class="w-full px-3 py-1.5 text-xs border border-slate-300 rounded focus:outline-none focus:border-brand"
                >
            </div>
            <div class="grid grid-cols-2 gap-1.5 text-xs font-semibold">
                <a href="#dich-vu-trac-dia" onclick="toggleMobileMenu()" class="p-2 rounded bg-slate-100 text-brand flex items-center gap-1.5">
                    <i class="fa-solid fa-compass-drafting text-brand-accent"></i> Dịch Vụ Trắc Địa
                </a>
                <a href="#san-pham" onclick="filterCategory('may-thuy-binh'); toggleMobileMenu()" class="p-2 rounded bg-slate-100 text-slate-700 flex items-center gap-1.5">
                    <i class="fa-solid fa-crosshairs text-brand"></i> Máy Thuỷ Bình
                </a>
                <a href="#san-pham" onclick="filterCategory('may-gps-rtk'); toggleMobileMenu()" class="p-2 rounded bg-slate-100 text-slate-700 flex items-center gap-1.5">
                    <i class="fa-solid fa-satellite-dish text-brand"></i> Máy GPS GNSS RTK
                </a>
                <a href="#san-pham" onclick="filterCategory('may-toan-dac'); toggleMobileMenu()" class="p-2 rounded bg-slate-100 text-slate-700 flex items-center gap-1.5">
                    <i class="fa-solid fa-bullseye text-brand"></i> Máy Toàn Đạc
                </a>
                <a href="#san-pham" onclick="filterCategory('may-do-laser'); toggleMobileMenu()" class="p-2 rounded bg-slate-100 text-slate-700 flex items-center gap-1.5">
                    <i class="fa-solid fa-bolt text-brand"></i> Máy Đo Laser
                </a>
                <a href="#san-pham" onclick="filterCategory('may-kinh-vi-bo-dam'); toggleMobileMenu()" class="p-2 rounded bg-slate-100 text-slate-700 flex items-center gap-1.5">
                    <i class="fa-solid fa-walkie-talkie text-brand"></i> Kinh Vĩ & Bộ Đàm
                </a>
                <a href="#san-pham" onclick="filterCategory('phu-kien-trac-dia'); toggleMobileMenu()" class="p-2 rounded bg-slate-100 text-slate-700 flex items-center gap-1.5">
                    <i class="fa-solid fa-screwdriver-wrench text-brand"></i> Phụ Kiện Trắc Địa
                </a>
                <a href="#san-pham" onclick="filterCategory('cho-thue-may'); toggleMobileMenu()" class="p-2 rounded bg-slate-100 text-slate-700 flex items-center gap-1.5">
                    <i class="fa-solid fa-handshake text-brand"></i> Cho Thuê Máy
                </a>
                <a href="#du-an-da-nang" onclick="toggleMobileMenu()" class="p-2 rounded bg-slate-100 text-slate-700 flex items-center gap-1.5">
                    <i class="fa-solid fa-city text-brand"></i> Dự Án Đà Nẵng
                </a>
                <a href="#form-bao-gia" onclick="toggleMobileMenu()" class="p-2 rounded bg-brand-accent text-white flex items-center gap-1.5">
                    <i class="fa-solid fa-file-signature"></i> Nhận Báo Giá Ngay
                </a>
            </div>
        </div>
    </header>

    <!-- =====================================================================
         SECTION BANNER TỰ TRƯỢT 2 SLIDE KÍCH THƯỚC BẰNG NHAU
         Thiết kế tách biệt:
         1. Banner Máy Tính (md:block): Bố cục ngang rộng, chữ gọn nằm trọn bên trong.
         2. Banner Điện Thoại (md:hidden): Thiết kế mới riêng cho điện thoại, chữ nhỏ gọn không tràn viền.
    ====================================================================== -->
    <section id="trang-chu" class="py-3 bg-white border-b border-slate-200">
        <div class="flatsome-container">
            <div class="relative rounded-lg overflow-hidden shadow-md border border-slate-200">

                <!-- 1. BANNER DÀNH RIÊNG CHO MÁY TÍNH (2 ảnh tự trượt kích thước bằng nhau 400px) -->
                <div class="hidden md:block relative w-full h-[390px] lg:h-[410px] overflow-hidden bg-brand-dark">
                    <!-- Slide 1 Desktop -->
                    <div class="desktop-banner-slide absolute inset-0 transition-opacity duration-700 opacity-100 flex items-center bg-gradient-to-r from-[#062c50] via-[#0B4F8A] to-[#0f5fa6]">
                        <div class="w-full h-full grid grid-cols-12 items-center px-10 lg:px-14 gap-6">
                            <div class="col-span-7 text-white space-y-3 pr-4">
                                <div class="inline-block bg-amber-500 text-slate-950 font-bold text-xs px-3 py-1 rounded uppercase tracking-wider">
                                    CÔNG TY TNHH ĐO ĐẠC BẢN ĐỒ THỊNH PHÁT • DODACTHINHPHAT.COM
                                </div>
                                <h1 class="text-2xl lg:text-3xl font-extrabold leading-snug uppercase text-white">
                                    DỊCH VỤ ĐO ĐẠC ĐỊA CHÍNH, KHẢO SÁT BẢN ĐỒ & QUAN TRẮC CÔNG TRÌNH TẠI ĐÀ NẴNG
                                </h1>
                                <p class="text-xs lg:text-sm text-slate-100 leading-relaxed max-w-2xl">
                                    Chuyên đo đạc nhà đất, cắm mốc ranh giới, lập bản đồ hiện trạng, hồ sơ xin phép xây dựng, hoàn công và quan trắc lún nghiêng chuẩn TCVN. Chính xác từng mm – Nhanh chóng – Đúng pháp lý.
                                </p>
                                <div class="grid grid-cols-2 gap-2 pt-1 text-xs text-amber-200 font-medium">
                                    <div><i class="fa-solid fa-circle-check text-amber-400 mr-1.5"></i>Địa chỉ: 03 Hoàng Diệu, P. Điện Bàn, TP Đà Nẵng</div>
                                    <div><i class="fa-solid fa-phone-volume text-amber-400 mr-1.5"></i>Hotline/Zalo kỹ sư: 0933.210.234</div>
                                </div>
                                <div class="pt-2 flex items-center gap-3">
                                    <a href="#form-bao-gia" class="bg-brand-accent hover:bg-orange-700 text-white text-xs font-bold px-5 py-2.5 rounded shadow transition">
                                        ĐĂNG KÝ TƯ VẤN & BÁO GIÁ
                                    </a>
                                    <a href="#du-an-da-nang" class="bg-white/15 hover:bg-white/25 text-white border border-white/30 text-xs font-semibold px-4 py-2.5 rounded transition">
                                        XEM DỰ ÁN ĐÀ NẴNG
                                    </a>
                                </div>
                            </div>
                            <div class="col-span-5 h-full py-5 flex items-center justify-center">
                                <div class="grid grid-cols-2 gap-2.5 w-full max-w-md h-[320px]">
                                    <img 
                                        src="https://lh3.googleusercontent.com/d/1kCcHmSxEfBLvAaDoNEChg6BXeU59GDpb" 
                                        onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1kCcHmSxEfBLvAaDoNEChg6BXeU59GDpb&sz=w800';"
                                        alt="Hoạt động đo đạc thực tế Thịnh Phát" 
                                        class="w-full h-full object-cover rounded-lg border-2 border-white/30 shadow-lg"
                                    >
                                    <img 
                                        src="https://lh3.googleusercontent.com/d/1O8mgjTDAcUwEIDSWSqGMW4YcSnVg37UK" 
                                        onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1O8mgjTDAcUwEIDSWSqGMW4YcSnVg37UK&sz=w800';"
                                        alt="Thiết bị đo đạc bản đồ Thịnh Phát" 
                                        class="w-full h-full object-cover rounded-lg border-2 border-white/30 shadow-lg"
                                    >
                                </div>
                            </div>
                        </div>
                    </div>

                    <!-- Slide 2 Desktop (Kích thước bằng hệt Slide 1) -->
                    <div class="desktop-banner-slide absolute inset-0 transition-opacity duration-700 opacity-0 pointer-events-none flex items-center bg-gradient-to-r from-[#073661] via-[#0B4F8A] to-[#083b66]">
                        <div class="w-full h-full grid grid-cols-12 items-center px-10 lg:px-14 gap-6">
                            <div class="col-span-7 text-white space-y-3 pr-4">
                                <div class="inline-block bg-emerald-400 text-slate-950 font-bold text-xs px-3 py-1 rounded uppercase tracking-wider">
                                    PHÂN PHỐI & CHO THUÊ THIẾT BỊ TRẮC ĐỊA CHÍNH HÃNG
                                </div>
                                <h2 class="text-2xl lg:text-3xl font-extrabold leading-snug uppercase text-white">
                                    MÁY GPS GNSS RTK, MÁY TOÀN ĐẠC, MÁY THỦY BÌNH & MÁY LASER GIÁ TỐT NHẤT
                                </h2>
                                <p class="text-xs lg:text-sm text-slate-100 leading-relaxed max-w-2xl">
                                    Cung cấp đầy đủ máy đo đạc Leica, Topcon, Sokkia, Nikon, Hi-Target, Garmin, Bosch cùng phụ kiện chân, mia, gương sáo, bộ đàm. Kiểm định miễn phí, giao hàng và chuyển giao kỹ thuật tận nơi.
                                </p>
                                <div class="grid grid-cols-2 gap-2 pt-1 text-xs text-amber-200 font-medium">
                                    <div><i class="fa-solid fa-shield-halved text-amber-400 mr-1.5"></i>Bảo hành chính hãng – Có tem kiểm định</div>
                                    <div><i class="fa-solid fa-headset text-amber-400 mr-1.5"></i>Tư vấn kỹ thuật: 0933.210.234 (Mr. Mến)</div>
                                </div>
                                <div class="pt-2 flex items-center gap-3">
                                    <a href="#san-pham" class="bg-amber-500 hover:bg-amber-600 text-slate-950 text-xs font-bold px-5 py-2.5 rounded shadow transition">
                                        XEM DANH MỤC SẢN PHẨM
                                    </a>
                                    <a href="#form-bao-gia" class="bg-white/15 hover:bg-white/25 text-white border border-white/30 text-xs font-semibold px-4 py-2.5 rounded transition">
                                        YÊU CẦU BÁO GIÁ THIẾT BỊ
                                    </a>
                                </div>
                            </div>
                            <div class="col-span-5 h-full py-5 flex items-center justify-center">
                                <div class="grid grid-cols-2 gap-2.5 w-full max-w-md h-[320px]">
                                    <img 
                                        src="https://lh3.googleusercontent.com/d/1UP8YbcBZP0FX1BBqQ22VaWO8x_SrUuKd" 
                                        onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1UP8YbcBZP0FX1BBqQ22VaWO8x_SrUuKd&sz=w800';"
                                        alt="Máy đo đạc trắc địa Thịnh Phát" 
                                        class="w-full h-full object-cover rounded-lg border-2 border-white/30 shadow-lg"
                                    >
                                    <img 
                                        src="https://lh3.googleusercontent.com/d/1ZP9TYdHxPGeRZIfF4tUGS14FrQmbosyB" 
                                        onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1ZP9TYdHxPGeRZIfF4tUGS14FrQmbosyB&sz=w800';"
                                        alt="Máy RTK và Toàn đạc Thịnh Phát" 
                                        class="w-full h-full object-cover rounded-lg border-2 border-white/30 shadow-lg"
                                    >
                                </div>
                            </div>
                        </div>
                    </div>
                </div>

                <!-- 2. BANNER THIẾT KẾ MỚI DÀNH RIÊNG CHO ĐIỆN THOẠI (Chữ nhỏ gọn nằm hết trong ảnh banner, không tràn viền, 2 slide bằng nhau 275px) -->
                <div class="block md:hidden relative w-full h-[275px] overflow-hidden bg-brand-dark">
                    <!-- Slide 1 Mobile -->
                    <div class="mobile-banner-slide absolute inset-0 transition-opacity duration-700 opacity-100 flex flex-col justify-between p-3.5 bg-gradient-to-br from-[#062c50] via-[#0B4F8A] to-[#0a3f70]">
                        <div class="flex items-center gap-2">
                            <span class="bg-amber-400 text-slate-950 font-bold text-[10px] px-2 py-0.5 rounded uppercase">
                                dodacthinhphat.com
                            </span>
                            <span class="text-[10.5px] text-amber-200 font-medium truncate">
                                ĐT/Zalo: 0933.210.234
                            </span>
                        </div>
                        <div class="grid grid-cols-12 gap-2.5 items-center my-auto">
                            <div class="col-span-7 text-white space-y-1">
                                <h2 class="text-[13px] font-extrabold uppercase leading-snug text-white">
                                    CÔNG TY TNHH ĐO ĐẠC BẢN ĐỒ THỊNH PHÁT
                                </h2>
                                <p class="text-[11px] text-slate-100 leading-tight">
                                    Chuyên đo đạc nhà đất, cắm mốc ranh giới, tách thửa, xin phép xây dựng & quan trắc tại Đà Nẵng.
                                </p>
                                <div class="text-[10.5px] text-amber-300 font-medium leading-tight pt-0.5">
                                    Đ/c: 03 Hoàng Diệu, P. Điện Bàn, TP Đà Nẵng
                                </div>
                            </div>
                            <div class="col-span-5">
                                <img 
                                    src="https://lh3.googleusercontent.com/d/1kCcHmSxEfBLvAaDoNEChg6BXeU59GDpb" 
                                    onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1kCcHmSxEfBLvAaDoNEChg6BXeU59GDpb&sz=w500';"
                                    alt="Đo đạc Thịnh Phát Đà Nẵng" 
                                    class="w-full h-[135px] object-cover rounded border border-white/40"
                                >
                            </div>
                        </div>
                        <div class="flex items-center justify-between gap-2 pt-1 border-t border-white/15">
                            <a href="#form-bao-gia" class="bg-brand-accent text-white text-[11px] font-bold px-3 py-1.5 rounded text-center flex-1">
                                NHẬN BÁO GIÁ ĐO ĐẠC
                            </a>
                            <a href="#du-an-da-nang" class="bg-white/15 text-white text-[11px] font-semibold px-3 py-1.5 rounded text-center flex-1">
                                DỰ ÁN ĐÀ NẴNG
                            </a>
                        </div>
                    </div>

                    <!-- Slide 2 Mobile (Kích thước 275px bằng hệt Slide 1) -->
                    <div class="mobile-banner-slide absolute inset-0 transition-opacity duration-700 opacity-0 pointer-events-none flex flex-col justify-between p-3.5 bg-gradient-to-br from-[#073661] via-[#0B4F8A] to-[#062d52]">
                        <div class="flex items-center gap-2">
                            <span class="bg-emerald-400 text-slate-950 font-bold text-[10px] px-2 py-0.5 rounded uppercase">
                                Thiết Bị Chính Hãng
                            </span>
                            <span class="text-[10.5px] text-amber-200 font-medium truncate">
                                Bảo hành & Kiểm định TCVN
                            </span>
                        </div>
                        <div class="grid grid-cols-12 gap-2.5 items-center my-auto">
                            <div class="col-span-7 text-white space-y-1">
                                <h2 class="text-[13px] font-extrabold uppercase leading-snug text-white">
                                    MÁY RTK, TOÀN ĐẠC, THỦY BÌNH & LASER
                                </h2>
                                <p class="text-[11px] text-slate-100 leading-tight">
                                    Cung cấp & cho thuê máy đo đạc Leica, Sokkia, Topcon, Nikon, Hi-Target, phụ kiện trắc địa giá tốt.
                                </p>
                                <div class="text-[10.5px] text-amber-300 font-medium leading-tight pt-0.5">
                                    Giao máy tận công trình • Hỗ trợ 24/7
                                </div>
                            </div>
                            <div class="col-span-5">
                                <img 
                                    src="https://lh3.googleusercontent.com/d/1UP8YbcBZP0FX1BBqQ22VaWO8x_SrUuKd" 
                                    onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1UP8YbcBZP0FX1BBqQ22VaWO8x_SrUuKd&sz=w500';"
                                    alt="Máy trắc địa Thịnh Phát" 
                                    class="w-full h-[135px] object-cover rounded border border-white/40"
                                >
                            </div>
                        </div>
                        <div class="flex items-center justify-between gap-2 pt-1 border-t border-white/15">
                            <a href="#san-pham" class="bg-amber-400 text-slate-950 text-[11px] font-bold px-3 py-1.5 rounded text-center flex-1">
                                XEM SẢN PHẨM
                            </a>
                            <a href="#form-bao-gia" class="bg-white/15 text-white text-[11px] font-semibold px-3 py-1.5 rounded text-center flex-1">
                                TƯ VẤN KỸ THUẬT
                            </a>
                        </div>
                    </div>
                </div>

                <!-- Nút điều hướng Slide Banner -->
                <button type="button" onclick="changeBannerSlide(-1)" aria-label="Slide trước" class="absolute left-2 top-1/2 -translate-y-1/2 w-7 h-7 sm:w-8 sm:h-8 rounded-full bg-black/35 hover:bg-black/60 text-white flex items-center justify-center z-20">
                    <i class="fa-solid fa-chevron-left text-xs"></i>
                </button>
                <button type="button" onclick="changeBannerSlide(1)" aria-label="Slide tiếp" class="absolute right-2 top-1/2 -translate-y-1/2 w-7 h-7 sm:w-8 sm:h-8 rounded-full bg-black/35 hover:bg-black/60 text-white flex items-center justify-center z-20">
                    <i class="fa-solid fa-chevron-right text-xs"></i>
                </button>
                <div class="absolute bottom-2 left-1/2 -translate-x-1/2 flex items-center gap-2 z-20">
                    <button type="button" onclick="goToBannerSlide(0)" id="bannerDot0" class="w-6 h-1.5 rounded-full bg-amber-400 transition-all"></button>
                    <button type="button" onclick="goToBannerSlide(1)" id="bannerDot1" class="w-2.5 h-1.5 rounded-full bg-white/60 transition-all"></button>
                </div>
            </div>
        </div>
    </section>

    <!-- =====================================================================
         SECTION 1: CÁC HẠNG MỤC DỊCH VỤ TRẮC ĐỊA CHUYÊN NGHIỆP (Giống web mẫu nguyenhoangdodac.com)
    ====================================================================== -->
    <section id="dich-vu-trac-dia" class="py-6 sm:py-8">
        <div class="flatsome-container">
            <div class="flatsome-section-title">
                <h2 class="text-sm sm:text-base md:text-lg">CÁC HẠNG MỤC DỊCH VỤ ĐO ĐẠC TRẮC ĐỊA CHUYÊN NGHIỆP</h2>
                <a href="#form-bao-gia" class="text-xs font-semibold text-brand hover:text-brand-accent whitespace-nowrap">
                    Nhận báo giá nhanh <i class="fa-solid fa-arrow-right ml-1"></i>
                </a>
            </div>

            <div class="grid grid-cols-2 md:grid-cols-4 gap-3 sm:gap-4">
                <!-- Dịch vụ 1 -->
                <div class="bg-white rounded-lg border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col">
                    <img 
                        src="https://lh3.googleusercontent.com/d/1kCcHmSxEfBLvAaDoNEChg6BXeU59GDpb" 
                        onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1kCcHmSxEfBLvAaDoNEChg6BXeU59GDpb&sz=w600';"
                        alt="Đo Đạc Nhà Đất Đà Nẵng" 
                        class="w-full h-36 sm:h-44 object-cover"
                    >
                    <div class="p-3 sm:p-4 flex flex-col flex-1 justify-between">
                        <div>
                            <h3 class="font-bold text-xs sm:text-sm text-brand uppercase product-title-full">
                                ĐO ĐẠC NHÀ ĐẤT & HIỆN TRẠNG
                            </h3>
                            <p class="text-[11.5px] sm:text-xs text-slate-600 mt-1.5 leading-relaxed">
                                Đo vẽ bản đồ hiện trạng nhà đất, đo tách thửa, hợp thửa, phục vụ cấp mới và cấp đổi giấy chứng nhận tại Đà Nẵng.
                            </p>
                        </div>
                        <a href="#form-bao-gia" onclick="prefillService('Đo đạc nhà đất & hiện trạng')" class="mt-3 inline-block text-center py-1.5 px-3 rounded bg-brand-light text-brand hover:bg-brand hover:text-white text-xs font-semibold transition">
                            Yêu cầu tư vấn
                        </a>
                    </div>
                </div>

                <!-- Dịch vụ 2 -->
                <div class="bg-white rounded-lg border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col">
                    <img 
                        src="https://lh3.googleusercontent.com/d/1nCMnRmj98lMlRMzoG9KKGuoxXIeADqLj" 
                        onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1nCMnRmj98lMlRMzoG9KKGuoxXIeADqLj&sz=w600';"
                        alt="Giấy Tờ Nhà Đất" 
                        class="w-full h-36 sm:h-44 object-cover"
                    >
                    <div class="p-3 sm:p-4 flex flex-col flex-1 justify-between">
                        <div>
                            <h3 class="font-bold text-xs sm:text-sm text-brand uppercase product-title-full">
                                GIẤY TỜ NHÀ ĐẤT & HOÀN CÔNG
                            </h3>
                            <p class="text-[11.5px] sm:text-xs text-slate-600 mt-1.5 leading-relaxed">
                                Tư vấn thủ tục hồ sơ pháp lý nhà đất, bản vẽ hoàn công công trình xây dựng, trích lục bản đồ địa chính chuẩn quy định.
                            </p>
                        </div>
                        <a href="#form-bao-gia" onclick="prefillService('Giấy tờ nhà đất & Hoàn công')" class="mt-3 inline-block text-center py-1.5 px-3 rounded bg-brand-light text-brand hover:bg-brand hover:text-white text-xs font-semibold transition">
                            Yêu cầu tư vấn
                        </a>
                    </div>
                </div>

                <!-- Dịch vụ 3 -->
                <div class="bg-white rounded-lg border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col">
                    <img 
                        src="https://lh3.googleusercontent.com/d/167OPIOUV5gCQmJi5cGimSpVXyUmPUT1_" 
                        onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=167OPIOUV5gCQmJi5cGimSpVXyUmPUT1_&sz=w600';"
                        alt="Xin Phép Xây Dựng & Trắc Địa Công Trình" 
                        class="w-full h-36 sm:h-44 object-cover"
                    >
                    <div class="p-3 sm:p-4 flex flex-col flex-1 justify-between">
                        <div>
                            <h3 class="font-bold text-xs sm:text-sm text-brand uppercase product-title-full">
                                XIN PHÉP XÂY DỰNG & ĐỀ CƯƠNG QUAN TRẮC
                            </h3>
                            <p class="text-[11.5px] sm:text-xs text-slate-600 mt-1.5 leading-relaxed">
                                Lập bản vẽ xin phép xây dựng, định vị tim cọc, bu lông móng nhà xưởng và quan trắc lún nghiêng công trình.
                            </p>
                        </div>
                        <a href="#form-bao-gia" onclick="prefillService('Xin phép xây dựng & Quan trắc')" class="mt-3 inline-block text-center py-1.5 px-3 rounded bg-brand-light text-brand hover:bg-brand hover:text-white text-xs font-semibold transition">
                            Yêu cầu tư vấn
                        </a>
                    </div>
                </div>

                <!-- Dịch vụ 4 -->
                <div class="bg-white rounded-lg border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col">
                    <img 
                        src="https://lh3.googleusercontent.com/d/1dUprwy90bMe1p55R81-NMyiH4_N7WuMr" 
                        onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1dUprwy90bMe1p55R81-NMyiH4_N7WuMr&sz=w600';"
                        alt="Xác Định Ranh Đất" 
                        class="w-full h-36 sm:h-44 object-cover"
                    >
                    <div class="p-3 sm:p-4 flex flex-col flex-1 justify-between">
                        <div>
                            <h3 class="font-bold text-xs sm:text-sm text-brand uppercase product-title-full">
                                XÁC ĐỊNH RANH ĐẤT & CẮM MỐC TỌA ĐỘ
                            </h3>
                            <p class="text-[11.5px] sm:text-xs text-slate-600 mt-1.5 leading-relaxed">
                                Đo đạc khôi phục mốc ranh giới thửa đất bằng máy RTK và Toàn đạc điện tử độ chính xác cao, giải quyết chồng lấn.
                            </p>
                        </div>
                        <a href="#form-bao-gia" onclick="prefillService('Xác định ranh đất & Cắm mốc')" class="mt-3 inline-block text-center py-1.5 px-3 rounded bg-brand-light text-brand hover:bg-brand hover:text-white text-xs font-semibold transition">
                            Yêu cầu tư vấn
                        </a>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- =====================================================================
         SECTION 2: DANH MỤC SẢN PHẨM & THIẾT BỊ TRẮC ĐỊA (Lấy đúng danh mục web mẫu nguyenhoangdodac.com)
         - Chữ danh mục ở trang chủ nhỏ gọn, viết liền trên 1 hàng trong từng nút.
         - Sản phẩm chia 2 cột trên điện thoại (grid-cols-2), không nhãn dán, tên sản phẩm không bị cắt chữ.
    ====================================================================== -->
    <section id="san-pham" class="py-6 sm:py-8 bg-white border-y border-slate-200">
        <div class="flatsome-container">
            <div class="flatsome-section-title">
                <h2 class="text-sm sm:text-base md:text-lg">DANH MỤC MÁY ĐO ĐẠC TRẮC ĐỊA & PHỤ KIỆN CHÍNH HÃNG</h2>
                <span class="text-xs text-slate-500 hidden sm:inline">Đầy đủ CO/CQ & Giấy kiểm định</span>
            </div>

            <!-- Thanh danh mục sản phẩm tối ưu trên máy tính & điện thoại: mỗi tên danh mục viết liền trên 1 hàng -->
            <div class="flex flex-wrap items-center gap-1.5 sm:gap-2 mb-5">
                <button type="button" onclick="filterCategory('all')" data-cat="all" class="home-cat-pill active">
                    Tất Cả Sản Phẩm
                </button>
                <button type="button" onclick="filterCategory('may-thuy-binh')" data-cat="may-thuy-binh" class="home-cat-pill">
                    Máy Thuỷ Bình
                </button>
                <button type="button" onclick="filterCategory('may-gps-rtk')" data-cat="may-gps-rtk" class="home-cat-pill">
                    Máy GPS GNSS RTK
                </button>
                <button type="button" onclick="filterCategory('may-toan-dac')" data-cat="may-toan-dac" class="home-cat-pill">
                    Máy Toàn Đạc
                </button>
                <button type="button" onclick="filterCategory('may-do-laser')" data-cat="may-do-laser" class="home-cat-pill">
                    Máy Đo Laser
                </button>
                <button type="button" onclick="filterCategory('may-kinh-vi-bo-dam')" data-cat="may-kinh-vi-bo-dam" class="home-cat-pill">
                    Máy Kinh Vĩ & Bộ Đàm
                </button>
                <button type="button" onclick="filterCategory('phu-kien-trac-dia')" data-cat="phu-kien-trac-dia" class="home-cat-pill">
                    Phụ Kiện Máy Trắc Địa
                </button>
                <button type="button" onclick="filterCategory('cho-thue-may')" data-cat="cho-thue-may" class="home-cat-pill">
                    Cho Thuê Máy Đo Đạc
                </button>
            </div>

            <!-- Danh sách danh mục con từ nguyenhoangdodac.com hiển thị gọn đẹp -->
            <div class="bg-slate-50 border border-slate-200 rounded-lg p-2.5 sm:p-3 mb-5">
                <div class="flex flex-wrap items-center gap-x-3 gap-y-1.5 text-[11.5px] text-slate-600">
                    <span class="font-bold text-brand whitespace-nowrap"><i class="fa-solid fa-layer-group mr-1"></i>Phân loại nhanh:</span>
                    <button type="button" onclick="filterCategory('may-thuy-binh')" class="hover:text-brand whitespace-nowrap">Máy Thủy Bình Leica</button>
                    <span>•</span>
                    <button type="button" onclick="filterCategory('may-thuy-binh')" class="hover:text-brand whitespace-nowrap">Máy Thủy Bình Sokkia</button>
                    <span>•</span>
                    <button type="button" onclick="filterCategory('may-thuy-binh')" class="hover:text-brand whitespace-nowrap">Máy Thủy Bình Topcon</button>
                    <span>•</span>
                    <button type="button" onclick="filterCategory('may-thuy-binh')" class="hover:text-brand whitespace-nowrap">Máy Thủy Bình Nikon</button>
                    <span>•</span>
                    <button type="button" onclick="filterCategory('may-do-laser')" class="hover:text-brand whitespace-nowrap">Máy Cân Bằng Laisai / Sincon</button>
                    <span>•</span>
                    <button type="button" onclick="filterCategory('may-gps-rtk')" class="hover:text-brand whitespace-nowrap">Máy Định Vị GPS Garmin</button>
                    <span>•</span>
                    <button type="button" onclick="filterCategory('may-toan-dac')" class="hover:text-brand whitespace-nowrap">Máy Toàn Đạc Leica / Topcon / Sokkia</button>
                    <span>•</span>
                    <button type="button" onclick="filterCategory('phu-kien-trac-dia')" class="hover:text-brand whitespace-nowrap">Chân – Mia – Mốc – Bọt Thủy – Đế Máy</button>
                    <span>•</span>
                    <button type="button" onclick="filterCategory('phu-kien-trac-dia')" class="hover:text-brand whitespace-nowrap">Thước Thép – Gương Sáo – Pin Sạc</button>
                </div>
            </div>

            <!-- LƯỚI SẢN PHẨM: Chia đúng 2 cột trên điện thoại (grid-cols-2), 4-5 cột trên máy tính, KHÔNG để nhãn dán ở trang chủ, tên sản phẩm đầy đủ không tràn -->
            <div id="productGrid" class="grid grid-cols-2 sm:grid-cols-3 md:grid-cols-4 lg:grid-cols-5 gap-2.5 sm:gap-4">
                <!-- Các sản phẩm được render từ danh sách chuẩn bên dưới -->
            </div>
        </div>
    </section>

    <!-- =====================================================================
         SECTION 3: HÌNH ẢNH THỰC TẾ TỪ GOOGLE DRIVE (Đưa toàn bộ ảnh thực tế của Công ty Thịnh Phát lên trang chủ)
    ====================================================================== -->
    <section id="hinh-anh-thuc-te" class="py-6 sm:py-8">
        <div class="flatsome-container">
            <div class="flatsome-section-title">
                <h2 class="text-sm sm:text-base md:text-lg">HÌNH ẢNH THỰC TẾ THIẾT BỊ & HOẠT ĐỘNG ĐO ĐẠC THỊNH PHÁT</h2>
                <span class="text-xs text-slate-500 hidden sm:inline">Ảnh thực tế tại công trình & văn phòng</span>
            </div>

            <div class="grid grid-cols-2 sm:grid-cols-3 lg:grid-cols-5 gap-2.5 sm:gap-3.5">
                <div class="bg-white rounded-lg border border-slate-200 p-2 shadow-sm">
                    <img src="https://lh3.googleusercontent.com/d/1kCcHmSxEfBLvAaDoNEChg6BXeU59GDpb" onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1kCcHmSxEfBLvAaDoNEChg6BXeU59GDpb&sz=w600';" alt="Thực tế đo đạc Thịnh Phát 1" class="w-full h-36 sm:h-44 object-cover rounded">
                    <p class="text-[11.5px] font-semibold text-slate-700 mt-2 text-center product-title-full">Đo đạc khảo sát thực địa tại Đà Nẵng</p>
                </div>
                <div class="bg-white rounded-lg border border-slate-200 p-2 shadow-sm">
                    <img src="https://lh3.googleusercontent.com/d/1O8mgjTDAcUwEIDSWSqGMW4YcSnVg37UK" onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1O8mgjTDAcUwEIDSWSqGMW4YcSnVg37UK&sz=w600';" alt="Thực tế đo đạc Thịnh Phát 2" class="w-full h-36 sm:h-44 object-cover rounded">
                    <p class="text-[11.5px] font-semibold text-slate-700 mt-2 text-center product-title-full">Thiết bị máy trắc địa độ chính xác cao</p>
                </div>
                <div class="bg-white rounded-lg border border-slate-200 p-2 shadow-sm">
                    <img src="https://lh3.googleusercontent.com/d/1UP8YbcBZP0FX1BBqQ22VaWO8x_SrUuKd" onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1UP8YbcBZP0FX1BBqQ22VaWO8x_SrUuKd&sz=w600';" alt="Thực tế đo đạc Thịnh Phát 3" class="w-full h-36 sm:h-44 object-cover rounded">
                    <p class="text-[11.5px] font-semibold text-slate-700 mt-2 text-center product-title-full">Kiểm định & hiệu chuẩn máy đo đạc</p>
                </div>
                <div class="bg-white rounded-lg border border-slate-200 p-2 shadow-sm">
                    <img src="https://lh3.googleusercontent.com/d/1ZP9TYdHxPGeRZIfF4tUGS14FrQmbosyB" onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1ZP9TYdHxPGeRZIfF4tUGS14FrQmbosyB&sz=w600';" alt="Thực tế đo đạc Thịnh Phát 4" class="w-full h-36 sm:h-44 object-cover rounded">
                    <p class="text-[11.5px] font-semibold text-slate-700 mt-2 text-center product-title-full">Vận hành máy GNSS RTK & Toàn đạc</p>
                </div>
                <div class="bg-white rounded-lg border border-slate-200 p-2 shadow-sm">
                    <img src="https://lh3.googleusercontent.com/d/1kAFP7UQniZTymYgfu912MCupDO4qZKkr" onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1kAFP7UQniZTymYgfu912MCupDO4qZKkr&sz=w600';" alt="Thực tế đo đạc Thịnh Phát 5" class="w-full h-36 sm:h-44 object-cover rounded">
                    <p class="text-[11.5px] font-semibold text-slate-700 mt-2 text-center product-title-full">Đo đạc cắm mốc ranh giới thửa đất</p>
                </div>
                <div class="bg-white rounded-lg border border-slate-200 p-2 shadow-sm">
                    <img src="https://lh3.googleusercontent.com/d/1nCMnRmj98lMlRMzoG9KKGuoxXIeADqLj" onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1nCMnRmj98lMlRMzoG9KKGuoxXIeADqLj&sz=w600';" alt="Thực tế đo đạc Thịnh Phát 6" class="w-full h-36 sm:h-44 object-cover rounded">
                    <p class="text-[11.5px] font-semibold text-slate-700 mt-2 text-center product-title-full">Khảo sát địa hình dự án hạ tầng</p>
                </div>
                <div class="bg-white rounded-lg border border-slate-200 p-2 shadow-sm">
                    <img src="https://lh3.googleusercontent.com/d/167OPIOUV5gCQmJi5cGimSpVXyUmPUT1_" onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=167OPIOUV5gCQmJi5cGimSpVXyUmPUT1_&sz=w600';" alt="Thực tế đo đạc Thịnh Phát 7" class="w-full h-36 sm:h-44 object-cover rounded">
                    <p class="text-[11.5px] font-semibold text-slate-700 mt-2 text-center product-title-full">Trắc địa định vị tim trục công trình</p>
                </div>
                <div class="bg-white rounded-lg border border-slate-200 p-2 shadow-sm">
                    <img src="https://lh3.googleusercontent.com/d/1dUprwy90bMe1p55R81-NMyiH4_N7WuMr" onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1dUprwy90bMe1p55R81-NMyiH4_N7WuMr&sz=w600';" alt="Thực tế đo đạc Thịnh Phát 8" class="w-full h-36 sm:h-44 object-cover rounded">
                    <p class="text-[11.5px] font-semibold text-slate-700 mt-2 text-center product-title-full">Bàn giao mốc tọa độ & hồ sơ bản vẽ</p>
                </div>
                <div class="bg-white rounded-lg border border-slate-200 p-2 shadow-sm">
                    <img src="https://lh3.googleusercontent.com/d/1T7oYR_UOH23klAmpo9qd8lZDqVHPqfl1" onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1T7oYR_UOH23klAmpo9qd8lZDqVHPqfl1&sz=w600';" alt="Thực tế đo đạc Thịnh Phát 9" class="w-full h-36 sm:h-44 object-cover rounded">
                    <p class="text-[11.5px] font-semibold text-slate-700 mt-2 text-center product-title-full">Đội ngũ kỹ sư trắc địa Thịnh Phát</p>
                </div>
                <div class="bg-white rounded-lg border border-slate-200 p-2 shadow-sm flex flex-col items-center justify-center text-center">
                    <img src="https://lh3.googleusercontent.com/d/1ylpV3nYsUV8yzyT1BcMmwl435tdVhAtk" onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1ylpV3nYsUV8yzyT1BcMmwl435tdVhAtk&sz=w600';" alt="Logo Thịnh Phát" class="w-24 h-24 object-contain mb-2">
                    <p class="text-[11.5px] font-bold text-brand uppercase product-title-full">CÔNG TY TNHH ĐO ĐẠC BẢN ĐỒ THỊNH PHÁT</p>
                    <p class="text-[11px] text-slate-500 mt-0.5">Hotline: 0933.210.234</p>
                </div>
            </div>
        </div>
    </section>

    <!-- =====================================================================
         SECTION 4: DANH MỤC CÁC DỰ ÁN TIÊU BIỂU Ở ĐÀ NẴNG
    ====================================================================== -->
    <section id="du-an-da-nang" class="py-6 sm:py-8 bg-white border-y border-slate-200">
        <div class="flatsome-container">
            <div class="flatsome-section-title">
                <h2 class="text-sm sm:text-base md:text-lg">DANH MỤC CÁC DỰ ÁN ĐO ĐẠC TIÊU BIỂU TẠI ĐÀ NẴNG</h2>
                <a href="#form-bao-gia" class="text-xs font-semibold text-brand hover:text-brand-accent whitespace-nowrap">
                    Tư vấn dự án <i class="fa-solid fa-angle-right ml-1"></i>
                </a>
            </div>

            <div class="grid grid-cols-2 md:grid-cols-3 gap-3 sm:gap-5">
                <!-- Dự án 1 -->
                <div class="bg-slate-50 rounded-lg border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col">
                    <img src="https://lh3.googleusercontent.com/d/1kCcHmSxEfBLvAaDoNEChg6BXeU59GDpb" onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1kCcHmSxEfBLvAaDoNEChg6BXeU59GDpb&sz=w600';" alt="Dự án Đo đạc Điện Bàn Đà Nẵng" class="w-full h-36 sm:h-48 object-cover">
                    <div class="p-3 sm:p-4 flex-1 flex flex-col justify-between">
                        <div>
                            <h3 class="font-bold text-xs sm:text-sm text-brand product-title-full">
                                Dự Án Đo Đạc Địa Chính & Cắm Mốc Ranh Giới Khu Đô Thị Điện Bàn – TP. Đà Nẵng
                            </h3>
                            <p class="text-[11.5px] sm:text-xs text-slate-600 mt-1.5 leading-relaxed">
                                Thực hiện đo đạc hiện trạng, xác định mốc tọa độ VN-2000 và lập hồ sơ kỹ thuật thửa đất phục vụ quy hoạch hạ tầng đô thị tại Phường Điện Bàn, TP. Đà Nẵng.
                            </p>
                        </div>
                        <div class="mt-2.5 pt-2 border-t border-slate-200 text-[11px] text-slate-500 font-medium">
                            <i class="fa-solid fa-location-dot text-brand-accent mr-1"></i>Khu vực: Phường Điện Bàn, TP. Đà Nẵng
                        </div>
                    </div>
                </div>

                <!-- Dự án 2 -->
                <div class="bg-slate-50 rounded-lg border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col">
                    <img src="https://lh3.googleusercontent.com/d/167OPIOUV5gCQmJi5cGimSpVXyUmPUT1_" onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=167OPIOUV5gCQmJi5cGimSpVXyUmPUT1_&sz=w600';" alt="Dự án Trắc địa nhà xưởng Hòa Khánh Đà Nẵng" class="w-full h-36 sm:h-48 object-cover">
                    <div class="p-3 sm:p-4 flex-1 flex flex-col justify-between">
                        <div>
                            <h3 class="font-bold text-xs sm:text-sm text-brand product-title-full">
                                Dự Án Trắc Địa Nhà Xưởng & Định Vị Bu Lông Móng KCN Hòa Khánh – Liên Chiểu, Đà Nẵng
                            </h3>
                            <p class="text-[11.5px] sm:text-xs text-slate-600 mt-1.5 leading-relaxed">
                                Đo đạc truyền dẫn mốc cao độ, định vị tim cọc, kiểm tra độ thẳng đứng kết cấu thép và lập bản vẽ hoàn công nhà xưởng chuẩn TCVN.
                            </p>
                        </div>
                        <div class="mt-2.5 pt-2 border-t border-slate-200 text-[11px] text-slate-500 font-medium">
                            <i class="fa-solid fa-location-dot text-brand-accent mr-1"></i>Khu vực: Liên Chiểu, TP. Đà Nẵng
                        </div>
                    </div>
                </div>

                <!-- Dự án 3 -->
                <div class="bg-slate-50 rounded-lg border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col">
                    <img src="https://lh3.googleusercontent.com/d/1nCMnRmj98lMlRMzoG9KKGuoxXIeADqLj" onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1nCMnRmj98lMlRMzoG9KKGuoxXIeADqLj&sz=w600';" alt="Dự án Quan trắc lún nghiêng Sơn Trà Đà Nẵng" class="w-full h-36 sm:h-48 object-cover">
                    <div class="p-3 sm:p-4 flex-1 flex flex-col justify-between">
                        <div>
                            <h3 class="font-bold text-xs sm:text-sm text-brand product-title-full">
                                Dự Án Quan Trắc Lún Nghiêng & Chuyển Vị Tòa Nhà Cao Tầng Ven Biển Sơn Trà, Đà Nẵng
                            </h3>
                            <p class="text-[11.5px] sm:text-xs text-slate-600 mt-1.5 leading-relaxed">
                                Lập đề cương quan trắc và thực hiện đo lún, đo nghiêng định kỳ theo TCVN 9360:2012 và TCVN 9364:2012 bảo vệ pháp lý công trình.
                            </p>
                        </div>
                        <div class="mt-2.5 pt-2 border-t border-slate-200 text-[11px] text-slate-500 font-medium">
                            <i class="fa-solid fa-location-dot text-brand-accent mr-1"></i>Khu vực: Sơn Trà, TP. Đà Nẵng
                        </div>
                    </div>
                </div>

                <!-- Dự án 4 -->
                <div class="bg-slate-50 rounded-lg border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col">
                    <img src="https://lh3.googleusercontent.com/d/1dUprwy90bMe1p55R81-NMyiH4_N7WuMr" onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1dUprwy90bMe1p55R81-NMyiH4_N7WuMr&sz=w600';" alt="Dự án Đo vẽ bản đồ Ngũ Hành Sơn Đà Nẵng" class="w-full h-36 sm:h-48 object-cover">
                    <div class="p-3 sm:p-4 flex-1 flex flex-col justify-between">
                        <div>
                            <h3 class="font-bold text-xs sm:text-sm text-brand product-title-full">
                                Dự Án Khảo Sát Địa Hình 1/500 Khu Du Lịch Ven Biển Ngũ Hành Sơn – TP. Đà Nẵng
                            </h3>
                            <p class="text-[11.5px] sm:text-xs text-slate-600 mt-1.5 leading-relaxed">
                                Đo vẽ bản đồ địa hình tỷ lệ 1/500, lưới khống chế mặt bằng và độ cao phục vụ thiết kế quy hoạch tổng mặt bằng kiến trúc.
                            </p>
                        </div>
                        <div class="mt-2.5 pt-2 border-t border-slate-200 text-[11px] text-slate-500 font-medium">
                            <i class="fa-solid fa-location-dot text-brand-accent mr-1"></i>Khu vực: Ngũ Hành Sơn, TP. Đà Nẵng
                        </div>
                    </div>
                </div>

                <!-- Dự án 5 -->
                <div class="bg-slate-50 rounded-lg border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col">
                    <img src="https://lh3.googleusercontent.com/d/1kAFP7UQniZTymYgfu912MCupDO4qZKkr" onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1kAFP7UQniZTymYgfu912MCupDO4qZKkr&sz=w600';" alt="Dự án Tách thửa Hòa Xuân Cẩm Lệ Đà Nẵng" class="w-full h-36 sm:h-48 object-cover">
                    <div class="p-3 sm:p-4 flex-1 flex flex-col justify-between">
                        <div>
                            <h3 class="font-bold text-xs sm:text-sm text-brand product-title-full">
                                Dự Án Đo Đạc Phân Lô Tách Thửa & Xác Định Ranh Đất Khu Đô Thị Hòa Xuân – Cẩm Lệ, Đà Nẵng
                            </h3>
                            <p class="text-[11.5px] sm:text-xs text-slate-600 mt-1.5 leading-relaxed">
                                Đo đạc kiểm tra diện tích thực tế, cắm mốc ranh giới bằng máy RTK 2 tần số và hoàn thiện hồ sơ tách thửa cho chủ sử dụng đất.
                            </p>
                        </div>
                        <div class="mt-2.5 pt-2 border-t border-slate-200 text-[11px] text-slate-500 font-medium">
                            <i class="fa-solid fa-location-dot text-brand-accent mr-1"></i>Khu vực: Cẩm Lệ, TP. Đà Nẵng
                        </div>
                    </div>
                </div>

                <!-- Dự án 6 -->
                <div class="bg-slate-50 rounded-lg border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col">
                    <img src="https://lh3.googleusercontent.com/d/1T7oYR_UOH23klAmpo9qd8lZDqVHPqfl1" onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1T7oYR_UOH23klAmpo9qd8lZDqVHPqfl1&sz=w600';" alt="Dự án Khảo sát giao thông Hòa Vang Đà Nẵng" class="w-full h-36 sm:h-48 object-cover">
                    <div class="p-3 sm:p-4 flex-1 flex flex-col justify-between">
                        <div>
                            <h3 class="font-bold text-xs sm:text-sm text-brand product-title-full">
                                Dự Án Khảo Sát Trắc Địa Tuyến Giao Thông & Hạ Tầng Kỹ Thuật Hòa Vang – TP. Đà Nẵng
                            </h3>
                            <p class="text-[11.5px] sm:text-xs text-slate-600 mt-1.5 leading-relaxed">
                                Đo trắc dọc, trắc ngang, tính toán khối lượng đào đắp san lấp mặt bằng và bàn giao mốc thi công cho chủ đầu tư.
                            </p>
                        </div>
                        <div class="mt-2.5 pt-2 border-t border-slate-200 text-[11px] text-slate-500 font-medium">
                            <i class="fa-solid fa-location-dot text-brand-accent mr-1"></i>Khu vực: Hòa Vang, TP. Đà Nẵng
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- =====================================================================
         SECTION 5: VỀ CHÚNG TÔI & TẠI SAO CHỌN THỊNH PHÁT & QUY TRÌNH LÀM VIỆC (Chuẩn mẫu nguyenhoangdodac.com)
    ====================================================================== -->
    <section class="py-6 sm:py-8">
        <div class="flatsome-container space-y-6">
            <!-- Khối Về Chúng Tôi -->
            <div class="bg-white rounded-lg border border-slate-200 p-4 sm:p-6 shadow-sm">
                <div class="grid grid-cols-1 lg:grid-cols-12 gap-5 items-center">
                    <div class="lg:col-span-7 space-y-3">
                        <div class="text-xs font-bold text-brand-accent uppercase">VỀ CHÚNG TÔI • DODACTHINHPHAT.COM</div>
                        <h2 class="text-base sm:text-xl font-extrabold text-brand uppercase">
                            CÔNG TY TNHH ĐO ĐẠC BẢN ĐỒ THỊNH PHÁT
                        </h2>
                        <p class="text-xs sm:text-sm text-slate-600 leading-relaxed">
                            <strong>Công Ty TNHH Đo Đạc Bản Đồ Thịnh Phát</strong> (MST: 4001175930) có trụ sở tại <strong>03 Hoàng Diệu, Phường Điện Bàn, TP Đà Nẵng</strong> là đơn vị uy tín chuyên cung cấp các dịch vụ đo đạc địa chính, khảo sát địa hình, trắc địa công trình, thiết kế kiến trúc – tổng mặt bằng và phân phối thiết bị trắc địa chính hãng.
                        </p>
                        <p class="text-xs sm:text-sm text-slate-600 leading-relaxed">
                            Với đội ngũ kỹ sư trắc địa giàu kinh nghiệm thực chiến cùng hệ thống máy móc hiện đại (Máy toàn đạc Leica/Topcon, máy GNSS RTK 2 tần số, máy thủy bình chuẩn TCVN), chúng tôi cam kết mang đến giải pháp chính xác từng milimet, đúng tiến độ và tối ưu chi phí cho khách hàng cá nhân lẫn doanh nghiệp.
                        </p>
                        <div class="grid grid-cols-2 sm:grid-cols-4 gap-2.5 pt-2">
                            <div class="bg-brand-light p-2.5 rounded text-center border border-brand/15">
                                <div class="text-base sm:text-lg font-extrabold text-brand">1.500+</div>
                                <div class="text-[11px] text-slate-600 font-medium">Hồ sơ & Dự án</div>
                            </div>
                            <div class="bg-brand-light p-2.5 rounded text-center border border-brand/15">
                                <div class="text-base sm:text-lg font-extrabold text-brand">100%</div>
                                <div class="text-[11px] text-slate-600 font-medium">Chuẩn Pháp Lý TCVN</div>
                            </div>
                            <div class="bg-brand-light p-2.5 rounded text-center border border-brand/15">
                                <div class="text-base sm:text-lg font-extrabold text-brand">15+</div>
                                <div class="text-[11px] text-slate-600 font-medium">Kỹ Sư Chuyên Môn</div>
                            </div>
                            <div class="bg-brand-light p-2.5 rounded text-center border border-brand/15">
                                <div class="text-base sm:text-lg font-extrabold text-brand">24/7</div>
                                <div class="text-[11px] text-slate-600 font-medium">Hỗ Trợ Tận Nơi</div>
                            </div>
                        </div>
                    </div>
                    <div class="lg:col-span-5 grid grid-cols-2 gap-2.5">
                        <img src="https://lh3.googleusercontent.com/d/1O8mgjTDAcUwEIDSWSqGMW4YcSnVg37UK" onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1O8mgjTDAcUwEIDSWSqGMW4YcSnVg37UK&sz=w600';" alt="Giới thiệu Thịnh Phát 1" class="w-full h-44 sm:h-52 object-cover rounded-lg border border-slate-200">
                        <img src="https://lh3.googleusercontent.com/d/1ZP9TYdHxPGeRZIfF4tUGS14FrQmbosyB" onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1ZP9TYdHxPGeRZIfF4tUGS14FrQmbosyB&sz=w600';" alt="Giới thiệu Thịnh Phát 2" class="w-full h-44 sm:h-52 object-cover rounded-lg border border-slate-200">
                    </div>
                </div>
            </div>

            <!-- Cam kết & Quy trình làm việc 4 bước giống mẫu nguyenhoangdodac.com -->
            <div class="grid grid-cols-2 md:grid-cols-4 gap-3 sm:gap-4">
                <div class="bg-white p-3.5 sm:p-4 rounded-lg border border-slate-200 shadow-sm">
                    <div class="w-9 h-9 rounded-full bg-brand text-white flex items-center justify-center font-bold text-xs mb-2.5">01</div>
                    <h3 class="font-bold text-xs sm:text-sm text-brand uppercase">TIẾP NHẬN YÊU CẦU</h3>
                    <p class="text-[11.5px] sm:text-xs text-slate-600 mt-1">Tư vấn sơ bộ hồ sơ pháp lý, nhu cầu đo đạc hoặc thiết bị trắc địa qua Hotline/Zalo 0933.210.234.</p>
                </div>
                <div class="bg-white p-3.5 sm:p-4 rounded-lg border border-slate-200 shadow-sm">
                    <div class="w-9 h-9 rounded-full bg-brand text-white flex items-center justify-center font-bold text-xs mb-2.5">02</div>
                    <h3 class="font-bold text-xs sm:text-sm text-brand uppercase">KHẢO SÁT & LẬP KẾ HOẠCH</h3>
                    <p class="text-[11.5px] sm:text-xs text-slate-600 mt-1">Kiểm tra thông tin thửa đất/công trình, báo giá minh bạch, thống nhất phương án kỹ thuật.</p>
                </div>
                <div class="bg-white p-3.5 sm:p-4 rounded-lg border border-slate-200 shadow-sm">
                    <div class="w-9 h-9 rounded-full bg-brand text-white flex items-center justify-center font-bold text-xs mb-2.5">03</div>
                    <h3 class="font-bold text-xs sm:text-sm text-brand uppercase">THỰC HIỆN ĐO ĐẠC</h3>
                    <p class="text-[11.5px] sm:text-xs text-slate-600 mt-1">Kỹ sư sử dụng máy Toàn đạc & GPS RTK đo đạc thực địa chính xác theo hệ tọa độ VN-2000.</p>
                </div>
                <div class="bg-white p-3.5 sm:p-4 rounded-lg border border-slate-200 shadow-sm">
                    <div class="w-9 h-9 rounded-full bg-brand text-white flex items-center justify-center font-bold text-xs mb-2.5">04</div>
                    <h3 class="font-bold text-xs sm:text-sm text-brand uppercase">BÁO CÁO & BÀN GIAO</h3>
                    <p class="text-[11.5px] sm:text-xs text-slate-600 mt-1">Nội nghiệp xử lý số liệu, xuất bản vẽ CAD/PDF có pháp lý và bàn giao mốc ngoài thực địa.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- =====================================================================
         SECTION 6: DANH MỤC CÁC BÀI VIẾT TRANG CHỦ (Tin tức & Kinh nghiệm đo đạc)
    ====================================================================== -->
    <section id="bai-viet" class="py-6 sm:py-8 bg-white border-y border-slate-200">
        <div class="flatsome-container">
            <div class="flatsome-section-title">
                <h2 class="text-sm sm:text-base md:text-lg">DANH MỤC BÀI VIẾT & KIẾN THỨC ĐO ĐẠC BẢN ĐỒ</h2>
                <span class="text-xs text-slate-500 hidden sm:inline">Cập nhật quy định & kỹ thuật trắc địa mới nhất</span>
            </div>

            <div class="grid grid-cols-2 md:grid-cols-4 gap-3 sm:gap-4">
                <!-- Bài viết 1 -->
                <article class="bg-slate-50 rounded-lg border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col">
                    <img src="https://lh3.googleusercontent.com/d/1kCcHmSxEfBLvAaDoNEChg6BXeU59GDpb" onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1kCcHmSxEfBLvAaDoNEChg6BXeU59GDpb&sz=w600';" alt="Chi phí đo đạc địa chính Đà Nẵng" class="w-full h-32 sm:h-40 object-cover">
                    <div class="p-3 flex-1 flex flex-col justify-between">
                        <div>
                            <h3 class="font-bold text-xs sm:text-sm text-slate-800 hover:text-brand product-title-full">
                                Chi phí đo đạc địa chính, tách thửa và xác định ranh đất tại Đà Nẵng là bao nhiêu?
                            </h3>
                            <p class="text-[11px] sm:text-xs text-slate-600 mt-1.5 leading-relaxed">
                                Bảng báo giá chi tiết dịch vụ đo vẽ hiện trạng nhà đất, cắm mốc ranh giới và lập hồ sơ kỹ thuật thửa đất tại Điện Bàn, Đà Nẵng.
                            </p>
                        </div>
                        <a href="#form-bao-gia" class="text-[11.5px] font-semibold text-brand mt-2.5 inline-block">
                            Nhận bảng giá chi tiết <i class="fa-solid fa-angle-right ml-0.5"></i>
                        </a>
                    </div>
                </article>

                <!-- Bài viết 2 -->
                <article class="bg-slate-50 rounded-lg border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col">
                    <img src="https://lh3.googleusercontent.com/d/1UP8YbcBZP0FX1BBqQ22VaWO8x_SrUuKd" onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1UP8YbcBZP0FX1BBqQ22VaWO8x_SrUuKd&sz=w600';" alt="Hướng dẫn chọn máy thủy bình" class="w-full h-32 sm:h-40 object-cover">
                    <div class="p-3 flex-1 flex flex-col justify-between">
                        <div>
                            <h3 class="font-bold text-xs sm:text-sm text-slate-800 hover:text-brand product-title-full">
                                Kinh nghiệm chọn mua Máy Thủy Bình Leica, Sokkia, Topcon chính hãng cho kỹ sư xây dựng
                            </h3>
                            <p class="text-[11px] sm:text-xs text-slate-600 mt-1.5 leading-relaxed">
                                So sánh độ phóng đại, sai số tiêu chuẩn trên 1km đo đi về và độ bền của các dòng máy thủy chuẩn phổ biến nhất hiện nay.
                            </p>
                        </div>
                        <a href="#san-pham" onclick="filterCategory('may-thuy-binh')" class="text-[11.5px] font-semibold text-brand mt-2.5 inline-block">
                            Xem các dòng máy <i class="fa-solid fa-angle-right ml-0.5"></i>
                        </a>
                    </div>
                </article>

                <!-- Bài viết 3 -->
                <article class="bg-slate-50 rounded-lg border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col">
                    <img src="https://lh3.googleusercontent.com/d/1ZP9TYdHxPGeRZIfF4tUGS14FrQmbosyB" onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1ZP9TYdHxPGeRZIfF4tUGS14FrQmbosyB&sz=w600';" alt="Ứng dụng máy GPS RTK 2 tần số" class="w-full h-32 sm:h-40 object-cover">
                    <div class="p-3 flex-1 flex flex-col justify-between">
                        <div>
                            <h3 class="font-bold text-xs sm:text-sm text-slate-800 hover:text-brand product-title-full">
                                Ứng dụng máy định vị vệ tinh GPS GNSS RTK 2 tần số gắn trạm CORS trong đo đạc bản đồ
                            </h3>
                            <p class="text-[11px] sm:text-xs text-slate-600 mt-1.5 leading-relaxed">
                                Giải pháp đo RTK kết nối trạm Base và mạng lưới trạm CORS Cục Đo đạc giúp tăng gấp 3 lần năng suất khảo sát ngoại nghiệp.
                            </p>
                        </div>
                        <a href="#san-pham" onclick="filterCategory('may-gps-rtk')" class="text-[11.5px] font-semibold text-brand mt-2.5 inline-block">
                            Xem máy GPS RTK <i class="fa-solid fa-angle-right ml-0.5"></i>
                        </a>
                    </div>
                </article>

                <!-- Bài viết 4 -->
                <article class="bg-slate-50 rounded-lg border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col">
                    <img src="https://lh3.googleusercontent.com/d/167OPIOUV5gCQmJi5cGimSpVXyUmPUT1_" onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=167OPIOUV5gCQmJi5cGimSpVXyUmPUT1_&sz=w600';" alt="Quy trình quan trắc lún nghiêng" class="w-full h-32 sm:h-40 object-cover">
                    <div class="p-3 flex-1 flex flex-col justify-between">
                        <div>
                            <h3 class="font-bold text-xs sm:text-sm text-slate-800 hover:text-brand product-title-full">
                                Quy trình lập đề cương và quan trắc lún nghiêng công trình theo TCVN 9360:2012 & 9364:2012
                            </h3>
                            <p class="text-[11px] sm:text-xs text-slate-600 mt-1.5 leading-relaxed">
                                Hướng dẫn chi tiết chu kỳ quan trắc chuyển vị ngang, lún nền móng và nghiêng công trình lân cận phục vụ nghiệm thu hoàn công.
                            </p>
                        </div>
                        <a href="#form-bao-gia" class="text-[11.5px] font-semibold text-brand mt-2.5 inline-block">
                            Tư vấn đề cương <i class="fa-solid fa-angle-right ml-0.5"></i>
                        </a>
                    </div>
                </article>
            </div>
        </div>
    </section>

    <!-- =====================================================================
         SECTION 7: DANH MỤC CÁC ĐỐI TÁC & THƯƠNG HIỆU ĐỒNG HÀNH
    ====================================================================== -->
    <section id="doi-tac" class="py-6 sm:py-8">
        <div class="flatsome-container">
            <div class="flatsome-section-title">
                <h2 class="text-sm sm:text-base md:text-lg">DANH MỤC CÁC ĐỐI TÁC & THƯƠNG HIỆU THIẾT BỊ</h2>
                <span class="text-xs text-slate-500 hidden sm:inline">Đối tác phân phối & thi công trắc địa</span>
            </div>

            <div class="grid grid-cols-2 sm:grid-cols-4 lg:grid-cols-8 gap-2.5 sm:gap-3">
                <div class="bg-white border border-slate-200 rounded-lg p-3 text-center shadow-sm flex flex-col items-center justify-center">
                    <div class="font-black text-sm sm:text-base text-red-700 tracking-wide">LEICA</div>
                    <div class="text-[10.5px] text-slate-500 mt-0.5">Thụy Sĩ • Geosystems</div>
                </div>
                <div class="bg-white border border-slate-200 rounded-lg p-3 text-center shadow-sm flex flex-col items-center justify-center">
                    <div class="font-black text-sm sm:text-base text-amber-600 tracking-wide">TOPCON</div>
                    <div class="text-[10.5px] text-slate-500 mt-0.5">Nhật Bản • Positioning</div>
                </div>
                <div class="bg-white border border-slate-200 rounded-lg p-3 text-center shadow-sm flex flex-col items-center justify-center">
                    <div class="font-black text-sm sm:text-base text-blue-800 tracking-wide">SOKKIA</div>
                    <div class="text-[10.5px] text-slate-500 mt-0.5">Nhật Bản • Trắc Địa</div>
                </div>
                <div class="bg-white border border-slate-200 rounded-lg p-3 text-center shadow-sm flex flex-col items-center justify-center">
                    <div class="font-black text-sm sm:text-base text-slate-800 tracking-wide">NIKON</div>
                    <div class="text-[10.5px] text-slate-500 mt-0.5">Nhật Bản • Quang Học</div>
                </div>
                <div class="bg-white border border-slate-200 rounded-lg p-3 text-center shadow-sm flex flex-col items-center justify-center">
                    <div class="font-black text-sm sm:text-base text-orange-600 tracking-wide">HI-TARGET</div>
                    <div class="text-[10.5px] text-slate-500 mt-0.5">GNSS RTK • Surveying</div>
                </div>
                <div class="bg-white border border-slate-200 rounded-lg p-3 text-center shadow-sm flex flex-col items-center justify-center">
                    <div class="font-black text-sm sm:text-base text-sky-700 tracking-wide">GARMIN</div>
                    <div class="text-[10.5px] text-slate-500 mt-0.5">Hoa Kỳ • Định Vị GPS</div>
                </div>
                <div class="bg-white border border-slate-200 rounded-lg p-3 text-center shadow-sm flex flex-col items-center justify-center">
                    <div class="font-black text-sm sm:text-base text-emerald-700 tracking-wide">BOSCH</div>
                    <div class="text-[10.5px] text-slate-500 mt-0.5">CHLB Đức • Máy Laser</div>
                </div>
                <div class="bg-white border border-slate-200 rounded-lg p-3 text-center shadow-sm flex flex-col items-center justify-center">
                    <div class="font-black text-sm sm:text-base text-indigo-800 tracking-wide">MOTOROLA</div>
                    <div class="text-[10.5px] text-slate-500 mt-0.5">Bộ Đàm Công Trình</div>
                </div>
            </div>
        </div>
    </section>

    <!-- =====================================================================
         SECTION 8: FORM YÊU CẦU TƯ VẤN & BÁO GIÁ + FANPAGE FACEBOOK + GOOGLE MAP NGOÀI TRANG CHỦ
    ====================================================================== -->
    <section id="form-bao-gia" class="py-6 sm:py-8 bg-white border-t border-slate-200">
        <div class="flatsome-container">
            <div class="flatsome-section-title">
                <h2 class="text-sm sm:text-base md:text-lg">FORM YÊU CẦU BÁO GIÁ • FANPAGE & BẢN ĐỒ GOOGLE MAP</h2>
                <span class="text-xs text-brand font-bold">Hotline/Zalo: 0933.210.234</span>
            </div>

            <div class="grid grid-cols-1 lg:grid-cols-12 gap-5">
                <!-- Cột 1 (5/12): FORM YÊU CẦU VÀ BÁO GIÁ TRANG CHỦ -->
                <div class="lg:col-span-5 bg-slate-50 rounded-lg border border-slate-200 p-4 sm:p-5 shadow-sm">
                    <h3 class="text-sm sm:text-base font-extrabold text-brand uppercase mb-1">
                        GỬI YÊU CẦU TƯ VẤN & NHẬN BÁO GIÁ
                    </h3>
                    <p class="text-xs text-slate-600 mb-4">
                        Quý khách cần đo đạc nhà đất tại Đà Nẵng hoặc báo giá máy trắc địa, vui lòng điền thông tin bên dưới:
                    </p>

                    <form id="quoteRequestForm" onsubmit="submitQuoteForm(event)" class="space-y-3">
                        <div>
                            <label class="block text-xs font-semibold text-slate-700 mb-1">Họ và tên khách hàng *</label>
                            <input type="text" id="custName" required placeholder="Nhập họ và tên của bạn" class="w-full px-3 py-2 text-xs bg-white border border-slate-300 rounded focus:outline-none focus:border-brand">
                        </div>
                        <div class="grid grid-cols-1 sm:grid-cols-2 gap-3">
                            <div>
                                <label class="block text-xs font-semibold text-slate-700 mb-1">Số điện thoại / Zalo *</label>
                                <input type="tel" id="custPhone" required placeholder="VD: 0933210234" class="w-full px-3 py-2 text-xs bg-white border border-slate-300 rounded focus:outline-none focus:border-brand">
                            </div>
                            <div>
                                <label class="block text-xs font-semibold text-slate-700 mb-1">Khu vực / Địa chỉ</label>
                                <input type="text" id="custArea" placeholder="Điện Bàn, Hải Châu, Cẩm Lệ..." class="w-full px-3 py-2 text-xs bg-white border border-slate-300 rounded focus:outline-none focus:border-brand">
                            </div>
                        </div>
                        <div>
                            <label class="block text-xs font-semibold text-slate-700 mb-1">Hạng mục cần tư vấn / báo giá *</label>
                            <select id="custService" class="w-full px-3 py-2 text-xs bg-white border border-slate-300 rounded focus:outline-none focus:border-brand">
                                <option value="Đo đạc nhà đất, tách thửa, cắm mốc ranh giới">Đo đạc nhà đất, tách thửa, cắm mốc ranh giới</option>
                                <option value="Giấy tờ nhà đất, xin phép xây dựng, hoàn công">Giấy tờ nhà đất, xin phép xây dựng, hoàn công</option>
                                <option value="Khảo sát địa hình, định vị công trình, quan trắc lún">Khảo sát địa hình, định vị công trình, quan trắc lún</option>
                                <option value="Báo giá Máy Thủy Bình / Máy Toàn Đạc / Máy GPS RTK">Báo giá Máy Thủy Bình / Máy Toàn Đạc / Máy GPS RTK</option>
                                <option value="Báo giá Máy Đo Laser / Bộ Đàm / Phụ Kiện Trắc Địa">Báo giá Máy Đo Laser / Bộ Đàm / Phụ Kiện Trắc Địa</option>
                                <option value="Thuê máy đo đạc trắc địa tại Đà Nẵng">Thuê máy đo đạc trắc địa tại Đà Nẵng</option>
                            </select>
                        </div>
                        <div>
                            <label class="block text-xs font-semibold text-slate-700 mb-1">Nội dung chi tiết</label>
                            <textarea id="custNote" rows="3" placeholder="Nhập diện tích thửa đất, vị trí hoặc tên máy trắc địa cần báo giá..." class="w-full px-3 py-2 text-xs bg-white border border-slate-300 rounded focus:outline-none focus:border-brand"></textarea>
                        </div>
                        <button type="submit" class="w-full bg-brand-accent hover:bg-orange-700 text-white font-bold text-xs sm:text-sm py-2.5 rounded shadow transition uppercase">
                            <i class="fa-solid fa-paper-plane mr-1.5"></i>GỬI YÊU CẦU BÁO GIÁ NGAY
                        </button>
                    </form>

                    <!-- Hộp thông báo gửi thành công (không dùng alert) -->
                    <div id="formSuccessBox" class="hidden mt-3 p-3 rounded bg-emerald-50 border border-emerald-300 text-emerald-800 text-xs">
                        <div class="font-bold"><i class="fa-solid fa-circle-check mr-1"></i>Đã ghi nhận yêu cầu báo giá!</div>
                        <p id="formSuccessText" class="mt-1"></p>
                    </div>
                </div>

                <!-- Cột 2 (3/12): ĐƯA FANPAGE RA NGOÀI TRANG CHỦ -->
                <div class="lg:col-span-3 bg-slate-50 rounded-lg border border-slate-200 p-4 flex flex-col justify-between shadow-sm">
                    <div>
                        <h3 class="text-sm font-extrabold text-brand uppercase mb-2 flex items-center gap-1.5">
                            <i class="fa-brands fa-facebook text-blue-600 text-base"></i>
                            <span>FANPAGE CHÍNH THỨC</span>
                        </h3>
                        <!-- Khung thông tin Fanpage trực quan + Plugin Facebook -->
                        <div class="bg-white rounded-lg border border-slate-200 overflow-hidden shadow-sm">
                            <div class="relative h-24 bg-gradient-to-r from-brand-dark to-brand p-3 flex items-end">
                                <div class="flex items-center gap-2.5">
                                    <img 
                                        src="https://lh3.googleusercontent.com/d/1ylpV3nYsUV8yzyT1BcMmwl435tdVhAtk" 
                                        onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1ylpV3nYsUV8yzyT1BcMmwl435tdVhAtk&sz=w300';"
                                        alt="Logo Fanpage Thịnh Phát" 
                                        class="w-12 h-12 rounded-md bg-white p-0.5 object-contain border border-white shadow"
                                    >
                                    <div class="text-white min-w-0">
                                        <a href="https://www.facebook.com/Thinhphatdodac" target="_blank" rel="noopener noreferrer" class="font-bold text-xs hover:underline block truncate">
                                            Đo Đạc Bản Đồ Thịnh Phát
                                        </a>
                                        <span class="text-[11px] text-amber-200 block">@Thinhphatdodac</span>
                                    </div>
                                </div>
                            </div>
                            <div class="p-3 space-y-2 text-xs">
                                <p class="text-slate-600 text-[11.5px] leading-relaxed">
                                    Chuyên đo đạc bản đồ, khảo sát địa chính, cắm mốc ranh giới và cung cấp máy trắc địa tại Đà Nẵng.
                                </p>
                                <!-- Nhúng Facebook Page Plugin chuẩn -->
                                <div class="w-full overflow-hidden rounded border border-slate-100 bg-slate-50">
                                    <iframe 
                                        title="Fanpage Đo Đạc Thịnh Phát"
                                        src="https://www.facebook.com/plugins/page.php?href=https%3A%2F%2Fwww.facebook.com%2FThinhphatdodac&tabs&width=280&height=130&small_header=true&adapt_container_width=true&hide_cover=false&show_facepile=true" 
                                        width="100%" 
                                        height="130" 
                                        style="border:none;overflow:hidden" 
                                        scrolling="no" 
                                        frameborder="0" 
                                        allowfullscreen="true" 
                                        allow="autoplay; clipboard-write; encrypted-media; picture-in-picture; web-share">
                                    </iframe>
                                </div>
                            </div>
                        </div>
                    </div>

                    <div class="mt-3 space-y-2">
                        <a 
                            href="https://www.facebook.com/Thinhphatdodac" 
                            target="_blank" 
                            rel="noopener noreferrer"
                            class="w-full py-2 px-3 rounded bg-[#1877F2] hover:bg-blue-700 text-white font-bold text-xs flex items-center justify-center gap-1.5 shadow-sm transition"
                        >
                            <i class="fa-brands fa-facebook-messenger"></i>
                            <span>TRUY CẬP FANPAGE THỊNH PHÁT</span>
                        </a>
                        <div class="text-[11px] text-slate-500 text-center">
                            facebook.com/Thinhphatdodac
                        </div>
                    </div>
                </div>

                <!-- Cột 3 (4/12): ĐƯA ẢNH & BẢN ĐỒ GOOGLE MAP RA NGOÀI TRANG CHỦ -->
                <div class="lg:col-span-4 bg-slate-50 rounded-lg border border-slate-200 p-4 flex flex-col justify-between shadow-sm">
                    <div>
                        <h3 class="text-sm font-extrabold text-brand uppercase mb-2 flex items-center gap-1.5">
                            <i class="fa-solid fa-map-location-dot text-red-600 text-base"></i>
                            <span>BẢN ĐỒ GOOGLE MAP TRỤ SỞ</span>
                        </h3>
                        <p class="text-xs text-slate-700 font-semibold mb-2">
                            <i class="fa-solid fa-location-dot text-brand-accent mr-1"></i>03 Hoàng Diệu, Phường Điện Bàn, TP Đà Nẵng
                        </p>

                        <!-- Bản đồ Google Map trực tiếp ngoài trang chủ -->
                        <div class="rounded-lg overflow-hidden border border-slate-300 bg-white shadow-sm">
                            <iframe 
                                title="Bản đồ Công Ty TNHH Đo Đạc Bản Đồ Thịnh Phát - 03 Hoàng Diệu, Điện Bàn, Đà Nẵng"
                                src="https://maps.google.com/maps?q=03%20Ho%C3%A0ng%20Di%E1%BB%87u,%20%C4%90i%E1%BB%87n%20B%C3%A0n,%20%C4%90%C3%A0%20N%E1%BA%B5ng&t=&z=16&ie=UTF8&iwloc=&output=embed"
                                width="100%" 
                                height="225" 
                                style="border:0;" 
                                allowfullscreen="" 
                                loading="lazy" 
                                referrerpolicy="no-referrer-when-downgrade">
                            </iframe>
                        </div>
                    </div>

                    <div class="mt-3 flex flex-col sm:flex-row items-center gap-2">
                        <a 
                            href="https://maps.app.goo.gl/HaoxaQqEpM7oMdmp6" 
                            target="_blank" 
                            rel="noopener noreferrer"
                            class="w-full py-2 px-3 rounded bg-brand hover:bg-brand-dark text-white font-bold text-xs flex items-center justify-center gap-1.5 shadow-sm transition"
                        >
                            <i class="fa-solid fa-diamond-turn-right"></i>
                            <span>MỞ BẢN ĐỒ GOOGLE MAPS CHỈ ĐƯỜNG</span>
                        </a>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- =====================================================================
         FOOTER CHUẨN FLATSOME
    ====================================================================== -->
    <footer class="bg-brand-dark text-slate-200 pt-8 pb-20 md:pb-8 border-t-4 border-brand-accent">
        <div class="flatsome-container">
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-12 gap-6 pb-6 border-b border-white/10">
                <!-- Cột thông tin công ty -->
                <div class="lg:col-span-5 space-y-2.5">
                    <div class="flex items-center gap-2.5">
                        <img 
                            src="https://lh3.googleusercontent.com/d/1ylpV3nYsUV8yzyT1BcMmwl435tdVhAtk" 
                            onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1ylpV3nYsUV8yzyT1BcMmwl435tdVhAtk&sz=w300';"
                            alt="Logo Công Ty TNHH Đo Đạc Bản Đồ Thịnh Phát" 
                            class="w-10 h-10 rounded bg-white p-0.5 object-contain shrink-0"
                        >
                        <div>
                            <h3 class="font-extrabold text-sm sm:text-base text-white uppercase">
                                CÔNG TY TNHH ĐO ĐẠC BẢN ĐỒ THỊNH PHÁT
                            </h3>
                            <p class="text-[11px] text-amber-300 font-medium">Website: dodacthinhphat.com • MST: 4001175930</p>
                        </div>
                    </div>
                    <p class="text-xs text-slate-300 leading-relaxed">
                        Đơn vị chuyên cung cấp dịch vụ đo đạc địa chính, khảo sát địa hình, trắc địa công trình, tư vấn thiết kế và phân phối máy đo đạc trắc địa chính hãng tại Đà Nẵng & toàn quốc.
                    </p>
                    <ul class="space-y-1.5 text-xs text-slate-200 pt-1">
                        <li><i class="fa-solid fa-location-dot text-amber-400 w-5"></i>Địa chỉ: 03 Hoàng Diệu, Phường Điện Bàn, TP Đà Nẵng</li>
                        <li><i class="fa-solid fa-phone-volume text-amber-400 w-5"></i>Hotline / Zalo: <a href="tel:0933210234" class="font-bold text-amber-300 hover:underline">0933.210.234</a></li>
                        <li><i class="fa-solid fa-globe text-amber-400 w-5"></i>Website: <a href="https://dodacthinhphat.com" class="hover:underline">www.dodacthinhphat.com</a></li>
                        <li><i class="fa-brands fa-facebook text-amber-400 w-5"></i>Fanpage: <a href="https://www.facebook.com/Thinhphatdodac" target="_blank" rel="noopener noreferrer" class="hover:underline">facebook.com/Thinhphatdodac</a></li>
                        <li><i class="fa-solid fa-map-pin text-amber-400 w-5"></i>Google Map: <a href="https://maps.app.goo.gl/HaoxaQqEpM7oMdmp6" target="_blank" rel="noopener noreferrer" class="hover:underline">maps.app.goo.gl/HaoxaQqEpM7oMdmp6</a></li>
                    </ul>
                </div>

                <!-- Cột Dịch vụ -->
                <div class="lg:col-span-3 space-y-2">
                    <h4 class="font-bold text-xs sm:text-sm text-white uppercase border-b border-white/15 pb-1.5">
                        DỊCH VỤ ĐO ĐẠC TRẮC ĐỊA
                    </h4>
                    <ul class="space-y-1.5 text-xs text-slate-300">
                        <li><a href="#dich-vu-trac-dia" class="hover:text-amber-300"><i class="fa-solid fa-angle-right mr-1.5 text-amber-400"></i>Đo đạc nhà đất & tách thửa</a></li>
                        <li><a href="#dich-vu-trac-dia" class="hover:text-amber-300"><i class="fa-solid fa-angle-right mr-1.5 text-amber-400"></i>Xác định ranh đất & cắm mốc</a></li>
                        <li><a href="#dich-vu-trac-dia" class="hover:text-amber-300"><i class="fa-solid fa-angle-right mr-1.5 text-amber-400"></i>Giấy tờ nhà đất & hoàn công</a></li>
                        <li><a href="#dich-vu-trac-dia" class="hover:text-amber-300"><i class="fa-solid fa-angle-right mr-1.5 text-amber-400"></i>Xin phép xây dựng Đà Nẵng</a></li>
                        <li><a href="#dich-vu-trac-dia" class="hover:text-amber-300"><i class="fa-solid fa-angle-right mr-1.5 text-amber-400"></i>Đề cương & Quan trắc lún nghiêng</a></li>
                        <li><a href="#du-an-da-nang" class="hover:text-amber-300"><i class="fa-solid fa-angle-right mr-1.5 text-amber-400"></i>Dự án đo đạc tại Đà Nẵng</a></li>
                    </ul>
                </div>

                <!-- Cột Danh mục sản phẩm -->
                <div class="lg:col-span-4 space-y-2">
                    <h4 class="font-bold text-xs sm:text-sm text-white uppercase border-b border-white/15 pb-1.5">
                        DANH MỤC MÁY TRẮC ĐỊA
                    </h4>
                    <div class="grid grid-cols-2 gap-1.5 text-xs text-slate-300">
                        <a href="#san-pham" onclick="filterCategory('may-thuy-binh')" class="hover:text-amber-300"><i class="fa-solid fa-angle-right mr-1 text-amber-400"></i>Máy Thuỷ Bình</a>
                        <a href="#san-pham" onclick="filterCategory('may-gps-rtk')" class="hover:text-amber-300"><i class="fa-solid fa-angle-right mr-1 text-amber-400"></i>Máy GPS GNSS RTK</a>
                        <a href="#san-pham" onclick="filterCategory('may-toan-dac')" class="hover:text-amber-300"><i class="fa-solid fa-angle-right mr-1 text-amber-400"></i>Máy Toàn Đạc Điện Tử</a>
                        <a href="#san-pham" onclick="filterCategory('may-do-laser')" class="hover:text-amber-300"><i class="fa-solid fa-angle-right mr-1 text-amber-400"></i>Máy Cân Bằng Laser</a>
                        <a href="#san-pham" onclick="filterCategory('may-kinh-vi-bo-dam')" class="hover:text-amber-300"><i class="fa-solid fa-angle-right mr-1 text-amber-400"></i>Máy Kinh Vĩ Điện Tử</a>
                        <a href="#san-pham" onclick="filterCategory('may-kinh-vi-bo-dam')" class="hover:text-amber-300"><i class="fa-solid fa-angle-right mr-1 text-amber-400"></i>Bộ Đàm Motorola</a>
                        <a href="#san-pham" onclick="filterCategory('phu-kien-trac-dia')" class="hover:text-amber-300"><i class="fa-solid fa-angle-right mr-1 text-amber-400"></i>Phụ Kiện Trắc Địa</a>
                        <a href="#san-pham" onclick="filterCategory('cho-thue-may')" class="hover:text-amber-300"><i class="fa-solid fa-angle-right mr-1 text-amber-400"></i>Cho Thuê Máy Đo Đạc</a>
                    </div>
                </div>
            </div>

            <div class="pt-4 flex flex-col sm:flex-row items-center justify-between text-xs text-slate-400 gap-2">
                <div>© Bản quyền thuộc về <strong>CÔNG TY TNHH ĐO ĐẠC BẢN ĐỒ THỊNH PHÁT</strong> (dodacthinhphat.com).</div>
                <div>Thiết kế chuẩn bố cục Flatsome UX Builder • Tối ưu máy tính (1500px) & điện thoại.</div>
            </div>
        </div>
    </footer>

    <!-- =====================================================================
         CÁC NÚT LIÊN HỆ NỔI BẬT (ZALO, FACEBOOK, HOTLINE) TƯƠNG THÍCH MÁY TÍNH & ĐIỆN THOẠI
         Đặt gọn bên trong khung nhìn, không gây tràn viền
    ====================================================================== -->
    <div class="fixed bottom-3 right-3 z-50 flex flex-col items-end gap-2.5">
        <!-- Nút Zalo nổi bật -->
        <a 
            href="https://zalo.me/0933210234" 
            target="_blank" 
            rel="noopener noreferrer"
            class="flex items-center gap-2 bg-[#0068FF] hover:bg-blue-700 text-white pl-3 pr-3.5 py-2 rounded-full shadow-lg transition transform hover:-translate-y-0.5"
            title="Chat Zalo: 0933.210.234"
        >
            <span class="w-6 h-6 rounded-full bg-white text-[#0068FF] font-black text-[10px] flex items-center justify-center shrink-0">Zalo</span>
            <span class="text-xs font-bold whitespace-nowrap">Chat Zalo</span>
        </a>

        <!-- Nút Facebook Fanpage nổi bật -->
        <a 
            href="https://www.facebook.com/Thinhphatdodac" 
            target="_blank" 
            rel="noopener noreferrer"
            class="flex items-center gap-2 bg-[#1877F2] hover:bg-blue-800 text-white pl-3 pr-3.5 py-2 rounded-full shadow-lg transition transform hover:-translate-y-0.5"
            title="Fanpage Đo Đạc Thịnh Phát"
        >
            <i class="fa-brands fa-facebook-f w-6 h-6 rounded-full bg-white text-[#1877F2] flex items-center justify-center text-xs shrink-0"></i>
            <span class="text-xs font-bold whitespace-nowrap">Facebook</span>
        </a>

        <!-- Nút Hotline nổi bật -->
        <a 
            href="tel:0933210234" 
            class="pulse-btn flex items-center gap-2 bg-brand-accent hover:bg-orange-700 text-white pl-3 pr-4 py-2.5 rounded-full shadow-xl transition"
            title="Gọi ngay Hotline: 0933.210.234"
        >
            <i class="fa-solid fa-phone-volume w-6 h-6 rounded-full bg-white text-brand-accent flex items-center justify-center text-xs shrink-0"></i>
            <span class="text-xs sm:text-sm font-extrabold whitespace-nowrap">0933.210.234</span>
        </a>
    </div>

    <!-- =====================================================================
         JAVASCRIPT XỬ LÝ SLIDER BANNER, LỌC DANH MỤC SẢN PHẨM & FORM BÁO GIÁ
    ====================================================================== -->
    <script>
        // Danh sách sản phẩm lấy từ danh mục web mẫu nguyenhoangdodac.com kết hợp 9 ảnh thực tế Google Drive
        const productsData = [
            // 1. Máy Thủy Bình
            {
                id: 1,
                category: 'may-thuy-binh',
                catName: 'Máy Thuỷ Bình',
                name: 'Bộ Máy Thủy Bình Tự Động Leica NA532 Chính Hãng (32X)',
                price: 'Liên hệ: 0933.210.234',
                img: 'https://lh3.googleusercontent.com/d/1UP8YbcBZP0FX1BBqQ22VaWO8x_SrUuKd',
                fallback: 'https://drive.google.com/thumbnail?id=1UP8YbcBZP0FX1BBqQ22VaWO8x_SrUuKd&sz=w600'
            },
            {
                id: 2,
                category: 'may-thuy-binh',
                catName: 'Máy Thuỷ Bình',
                name: 'Bộ Máy Thủy Bình Sokkia B40A Nhật Bản Kèm Chân Nhôm & Mia 5m',
                price: 'Liên hệ: 0933.210.234',
                img: 'https://lh3.googleusercontent.com/d/1O8mgjTDAcUwEIDSWSqGMW4YcSnVg37UK',
                fallback: 'https://drive.google.com/thumbnail?id=1O8mgjTDAcUwEIDSWSqGMW4YcSnVg37UK&sz=w600'
            },
            {
                id: 3,
                category: 'may-thuy-binh',
                catName: 'Máy Thuỷ Bình',
                name: 'Máy Thủy Bình Tự Động Topcon AT-B4A Chống Nước IPX6',
                price: 'Liên hệ: 0933.210.234',
                img: 'https://lh3.googleusercontent.com/d/1ZP9TYdHxPGeRZIfF4tUGS14FrQmbosyB',
                fallback: 'https://drive.google.com/thumbnail?id=1ZP9TYdHxPGeRZIfF4tUGS14FrQmbosyB&sz=w600'
            },
            {
                id: 4,
                category: 'may-thuy-binh',
                catName: 'Máy Thuỷ Bình',
                name: 'Máy Thủy Bình Nikon AC-2S / AX-2S Chính Hãng Đầy Đủ Kiểm Định',
                price: 'Liên hệ: 0933.210.234',
                img: 'https://lh3.googleusercontent.com/d/1kAFP7UQniZTymYgfu912MCupDO4qZKkr',
                fallback: 'https://drive.google.com/thumbnail?id=1kAFP7UQniZTymYgfu912MCupDO4qZKkr&sz=w600'
            },
            {
                id: 5,
                category: 'may-thuy-binh',
                catName: 'Máy Thuỷ Bình',
                name: 'Máy Thủy Bình Pentax AP-228 & Bosch GOL 26D Chuyên Công Trình',
                price: 'Liên hệ: 0933.210.234',
                img: 'https://lh3.googleusercontent.com/d/167OPIOUV5gCQmJi5cGimSpVXyUmPUT1_',
                fallback: 'https://drive.google.com/thumbnail?id=167OPIOUV5gCQmJi5cGimSpVXyUmPUT1_&sz=w600'
            },

            // 2. Máy GPS GNSS RTK
            {
                id: 6,
                category: 'may-gps-rtk',
                catName: 'Máy GPS GNSS RTK',
                name: 'Máy Định Vị Vệ Tinh GNSS RTK 2 Tần Số Hi-Target V200 Bù Nghiêng IMU',
                price: 'Liên hệ: 0933.210.234',
                img: 'https://lh3.googleusercontent.com/d/1kCcHmSxEfBLvAaDoNEChg6BXeU59GDpb',
                fallback: 'https://drive.google.com/thumbnail?id=1kCcHmSxEfBLvAaDoNEChg6BXeU59GDpb&sz=w600'
            },
            {
                id: 7,
                category: 'may-gps-rtk',
                catName: 'Máy GPS GNSS RTK',
                name: 'Máy GNSS RTK SatLab SL7 / E-Survey E300 Pro Kết Nối Trạm CORS Đà Nẵng',
                price: 'Liên hệ: 0933.210.234',
                img: 'https://lh3.googleusercontent.com/d/1nCMnRmj98lMlRMzoG9KKGuoxXIeADqLj',
                fallback: 'https://drive.google.com/thumbnail?id=1nCMnRmj98lMlRMzoG9KKGuoxXIeADqLj&sz=w600'
            },
            {
                id: 8,
                category: 'may-gps-rtk',
                catName: 'Máy GPS GNSS RTK',
                name: 'Máy Định Vị GPS Cầm Tay Garmin GPSMAP 65s / eTrex 22x Đo Diện Tích',
                price: 'Liên hệ: 0933.210.234',
                img: 'https://lh3.googleusercontent.com/d/1dUprwy90bMe1p55R81-NMyiH4_N7WuMr',
                fallback: 'https://drive.google.com/thumbnail?id=1dUprwy90bMe1p55R81-NMyiH4_N7WuMr&sz=w600'
            },

            // 3. Máy Toàn Đạc Điện Tử
            {
                id: 9,
                category: 'may-toan-dac',
                catName: 'Máy Toàn Đạc',
                name: 'Máy Toàn Đạc Điện Tử Leica TS06 Plus / TS07 Độ Chính Xác Cao',
                price: 'Liên hệ: 0933.210.234',
                img: 'https://lh3.googleusercontent.com/d/1T7oYR_UOH23klAmpo9qd8lZDqVHPqfl1',
                fallback: 'https://drive.google.com/thumbnail?id=1T7oYR_UOH23klAmpo9qd8lZDqVHPqfl1&sz=w600'
            },
            {
                id: 10,
                category: 'may-toan-dac',
                catName: 'Máy Toàn Đạc',
                name: 'Máy Toàn Đạc Điện Tử Topcon GM-52 / GM-55 Đo Không Gương 500m',
                price: 'Liên hệ: 0933.210.234',
                img: 'https://lh3.googleusercontent.com/d/1O8mgjTDAcUwEIDSWSqGMW4YcSnVg37UK',
                fallback: 'https://drive.google.com/thumbnail?id=1O8mgjTDAcUwEIDSWSqGMW4YcSnVg37UK&sz=w600'
            },
            {
                id: 11,
                category: 'may-toan-dac',
                catName: 'Máy Toàn Đạc',
                name: 'Máy Toàn Đạc Điện Tử Sokkia IM-52 & Nikon XF Chính Hãng',
                price: 'Liên hệ: 0933.210.234',
                img: 'https://lh3.googleusercontent.com/d/1UP8YbcBZP0FX1BBqQ22VaWO8x_SrUuKd',
                fallback: 'https://drive.google.com/thumbnail?id=1UP8YbcBZP0FX1BBqQ22VaWO8x_SrUuKd&sz=w600'
            },

            // 4. Máy Đo Laser
            {
                id: 12,
                category: 'may-do-laser',
                catName: 'Máy Đo Laser',
                name: 'Máy Cân Bằng Laser Tia Xanh Laisai LSG686SPD & Sincon 5 Tia Xanh',
                price: 'Liên hệ: 0933.210.234',
                img: 'https://lh3.googleusercontent.com/d/1ZP9TYdHxPGeRZIfF4tUGS14FrQmbosyB',
                fallback: 'https://drive.google.com/thumbnail?id=1ZP9TYdHxPGeRZIfF4tUGS14FrQmbosyB&sz=w600'
            },
            {
                id: 13,
                category: 'may-do-laser',
                catName: 'Máy Đo Laser',
                name: 'Thước Đo Khoảng Cách Laser Leica Disto D2 / Bosch GLM 50-27 CG',
                price: 'Liên hệ: 0933.210.234',
                img: 'https://lh3.googleusercontent.com/d/1kAFP7UQniZTymYgfu912MCupDO4qZKkr',
                fallback: 'https://drive.google.com/thumbnail?id=1kAFP7UQniZTymYgfu912MCupDO4qZKkr&sz=w600'
            },

            // 5. Máy Kinh Vĩ Điện Tử & Bộ Đàm
            {
                id: 14,
                category: 'may-kinh-vi-bo-dam',
                catName: 'Máy Kinh Vĩ & Bộ Đàm',
                name: 'Máy Kinh Vĩ Điện Tử Nikon NE-100 / NE-101 & Máy Đo Sâu Hồi Âm',
                price: 'Liên hệ: 0933.210.234',
                img: 'https://lh3.googleusercontent.com/d/167OPIOUV5gCQmJi5cGimSpVXyUmPUT1_',
                fallback: 'https://drive.google.com/thumbnail?id=167OPIOUV5gCQmJi5cGimSpVXyUmPUT1_&sz=w600'
            },
            {
                id: 15,
                category: 'may-kinh-vi-bo-dam',
                catName: 'Máy Kinh Vĩ & Bộ Đàm',
                name: 'Bộ Đàm Cầm Tay Motorola GP-3588 Plus Chuyên Dụng Công Trình Đo Đạc',
                price: 'Liên hệ: 0933.210.234',
                img: 'https://lh3.googleusercontent.com/d/1dUprwy90bMe1p55R81-NMyiH4_N7WuMr',
                fallback: 'https://drive.google.com/thumbnail?id=1dUprwy90bMe1p55R81-NMyiH4_N7WuMr&sz=w600'
            },

            // 6. Phụ Kiện Máy Trắc Địa
            {
                id: 16,
                category: 'phu-kien-trac-dia',
                catName: 'Phụ Kiện Trắc Địa',
                name: 'Chân Nhôm Máy Thủy Bình & Chân Máy Toàn Đạc 2 Khóa Loại Tốt + Mia Nhôm 5m',
                price: 'Liên hệ: 0933.210.234',
                img: 'https://lh3.googleusercontent.com/d/1nCMnRmj98lMlRMzoG9KKGuoxXIeADqLj',
                fallback: 'https://drive.google.com/thumbnail?id=1nCMnRmj98lMlRMzoG9KKGuoxXIeADqLj&sz=w600'
            },
            {
                id: 17,
                category: 'phu-kien-trac-dia',
                catName: 'Phụ Kiện Trắc Địa',
                name: 'Gương Đơn, Gương Mini, Sào Gương, Kẹp Sào, Đế Máy, Pin Sạc & Thước Thép',
                price: 'Liên hệ: 0933.210.234',
                img: 'https://lh3.googleusercontent.com/d/1T7oYR_UOH23klAmpo9qd8lZDqVHPqfl1',
                fallback: 'https://drive.google.com/thumbnail?id=1T7oYR_UOH23klAmpo9qd8lZDqVHPqfl1&sz=w600'
            },
            {
                id: 18,
                category: 'phu-kien-trac-dia',
                catName: 'Phụ Kiện Trắc Địa',
                name: 'Mốc Sứ Địa Chính, Mốc Quan Trắc Lún, Bánh Xe Đo Khoảng Cách & Bọt Thủy',
                price: 'Liên hệ: 0933.210.234',
                img: 'https://lh3.googleusercontent.com/d/1kCcHmSxEfBLvAaDoNEChg6BXeU59GDpb',
                fallback: 'https://drive.google.com/thumbnail?id=1kCcHmSxEfBLvAaDoNEChg6BXeU59GDpb&sz=w600'
            },

            // 7. Cho Thuê Máy Đo Đạc
            {
                id: 19,
                category: 'cho-thue-may',
                catName: 'Cho Thuê Máy Đo Đạc',
                name: 'Dịch Vụ Cho Thuê Máy Định Vị GPS GNSS RTK 2 Tần Số Theo Ngày/Tháng Tại Đà Nẵng',
                price: 'Liên hệ: 0933.210.234',
                img: 'https://lh3.googleusercontent.com/d/1O8mgjTDAcUwEIDSWSqGMW4YcSnVg37UK',
                fallback: 'https://drive.google.com/thumbnail?id=1O8mgjTDAcUwEIDSWSqGMW4YcSnVg37UK&sz=w600'
            },
            {
                id: 20,
                category: 'cho-thue-may',
                catName: 'Cho Thuê Máy Đo Đạc',
                name: 'Dịch Vụ Cho Thuê Máy Toàn Đạc Điện Tử Leica/Topcon & Máy Thủy Bình Tự Động',
                price: 'Liên hệ: 0933.210.234',
                img: 'https://lh3.googleusercontent.com/d/1UP8YbcBZP0FX1BBqQ22VaWO8x_SrUuKd',
                fallback: 'https://drive.google.com/thumbnail?id=1UP8YbcBZP0FX1BBqQ22VaWO8x_SrUuKd&sz=w600'
            }
        ];

        let currentCategory = 'all';
        let currentSearchQuery = '';

        // Render danh sách sản phẩm (Không để nhãn dán trên sản phẩm, tên sản phẩm đầy đủ không cắt chữ)
        function renderProducts() {
            const grid = document.getElementById('productGrid');
            if (!grid) return;

            const filtered = productsData.filter(item => {
                const matchCat = currentCategory === 'all' || item.category === currentCategory;
                const matchSearch = !currentSearchQuery || 
                    item.name.toLowerCase().includes(currentSearchQuery.toLowerCase()) ||
                    item.catName.toLowerCase().includes(currentSearchQuery.toLowerCase());
                return matchCat && matchSearch;
            });

            if (filtered.length === 0) {
                grid.innerHTML = `
                    <div class="col-span-full py-8 text-center text-xs sm:text-sm text-slate-500 bg-slate-50 rounded border border-slate-200">
                        Không tìm thấy sản phẩm phù hợp. Vui lòng liên hệ Hotline/Zalo <strong>0933.210.234</strong> để được hỗ trợ ngay!
                    </div>
                `;
                return;
            }

            grid.innerHTML = filtered.map(item => `
                <div class="bg-white rounded-lg border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col justify-between">
                    <div>
                        <div class="w-full h-32 sm:h-40 bg-slate-100 overflow-hidden border-b border-slate-100">
                            <img 
                                src="${item.img}" 
                                onerror="this.onerror=null;this.src='${item.fallback}';"
                                alt="${item.name}" 
                                class="w-full h-full object-cover hover:scale-105 transition duration-300"
                            >
                        </div>
                        <div class="p-2.5 sm:p-3">
                            <div class="text-[10.5px] text-slate-500 font-medium mb-1">
                                ${item.catName}
                            </div>
                            <h3 class="font-bold text-xs sm:text-[13px] text-slate-800 hover:text-brand product-title-full">
                                ${item.name}
                            </h3>
                        </div>
                    </div>
                    <div class="px-2.5 pb-2.5 sm:px-3 sm:pb-3 pt-1">
                        <div class="text-xs font-extrabold text-brand-accent mb-2">
                            ${item.price}
                        </div>
                        <a 
                            href="#form-bao-gia" 
                            onclick="prefillService('${item.name.replace(/'/g, "\\'")}')"
                            class="block w-full text-center py-1.5 px-2 rounded bg-brand hover:bg-brand-dark text-white text-[11px] sm:text-xs font-semibold transition"
                        >
                            Nhận báo giá
                        </a>
                    </div>
                </div>
            `).join('');
        }

        function filterCategory(cat) {
            currentCategory = cat;
            document.querySelectorAll('.home-cat-pill').forEach(btn => {
                if (btn.getAttribute('data-cat') === cat) {
                    btn.classList.add('active');
                } else {
                    btn.classList.remove('active');
                }
            });
            renderProducts();
        }

        function handleSearchProduct(query) {
            currentSearchQuery = query || '';
            renderProducts();
        }

        function toggleMobileMenu() {
            const drawer = document.getElementById('mobileMenuDrawer');
            if (drawer) {
                drawer.classList.toggle('hidden');
            }
        }

        function prefillService(serviceText) {
            const noteInput = document.getElementById('custNote');
            if (noteInput) {
                noteInput.value = 'Tôi cần tư vấn & báo giá: ' + serviceText;
            }
        }

        function submitQuoteForm(event) {
            event.preventDefault();
            const name = document.getElementById('custName').value.trim();
            const phone = document.getElementById('custPhone').value.trim();
            const service = document.getElementById('custService').value;
            const box = document.getElementById('formSuccessBox');
            const text = document.getElementById('formSuccessText');

            if (box && text) {
                text.textContent = `Cảm ơn ${name} (${phone}). Yêu cầu "${service}" đã được gửi đến bộ phận kỹ thuật Công Ty TNHH Đo Đạc Bản Đồ Thịnh Phát. Chúng tôi sẽ liên hệ lại ngay hoặc quý khách có thể nhắn trực tiếp Zalo 0933.210.234.`;
                box.classList.remove('hidden');
            }
        }

        // Xử lý tự trượt 2 ảnh Banner trên cả Máy tính và Điện thoại
        let currentBannerIndex = 0;
        let bannerInterval = null;

        function updateBannerSlides() {
            const desktopSlides = document.querySelectorAll('.desktop-banner-slide');
            const mobileSlides = document.querySelectorAll('.mobile-banner-slide');
            const dot0 = document.getElementById('bannerDot0');
            const dot1 = document.getElementById('bannerDot1');

            desktopSlides.forEach((slide, idx) => {
                if (idx === currentBannerIndex) {
                    slide.classList.remove('opacity-0', 'pointer-events-none');
                    slide.classList.add('opacity-100');
                } else {
                    slide.classList.remove('opacity-100');
                    slide.classList.add('opacity-0', 'pointer-events-none');
                }
            });

            mobileSlides.forEach((slide, idx) => {
                if (idx === currentBannerIndex) {
                    slide.classList.remove('opacity-0', 'pointer-events-none');
                    slide.classList.add('opacity-100');
                } else {
                    slide.classList.remove('opacity-100');
                    slide.classList.add('opacity-0', 'pointer-events-none');
                }
            });

            if (dot0 && dot1) {
                if (currentBannerIndex === 0) {
                    dot0.className = 'w-6 h-1.5 rounded-full bg-amber-400 transition-all';
                    dot1.className = 'w-2.5 h-1.5 rounded-full bg-white/60 transition-all';
                } else {
                    dot0.className = 'w-2.5 h-1.5 rounded-full bg-white/60 transition-all';
                    dot1.className = 'w-6 h-1.5 rounded-full bg-amber-400 transition-all';
                }
            }
        }

        function changeBannerSlide(step) {
            currentBannerIndex = (currentBannerIndex + step + 2) % 2;
            updateBannerSlides();
            resetBannerTimer();
        }

        function goToBannerSlide(index) {
            currentBannerIndex = index;
            updateBannerSlides();
            resetBannerTimer();
        }

        function resetBannerTimer() {
            if (bannerInterval) clearInterval(bannerInterval);
            bannerInterval = setInterval(() => {
                currentBannerIndex = (currentBannerIndex + 1) % 2;
                updateBannerSlides();
            }, 5000);
        }

        window.onload = function() {
            renderProducts();
            resetBannerTimer();
        };
    </script>
</body>
</html>
