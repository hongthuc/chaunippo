<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
    <title>CÔNG TY TNHH CHÂU NIPPO - Nhà Máy Cán Tôn, Xà Gồ, Sắt Thép Đà Nẵng | chaunippo.com</title>
    <meta name="description" content="CÔNG TY TNHH CHÂU NIPPO (chaunippo.com) - Địa chỉ: 843B Nguyễn Lương Bằng, Phường Hải Vân, TP Đà Nẵng. Chuyên sản xuất và cung cấp Tôn lợp, Sắt hộp mạ kẽm, Xà gồ C-Z, Thép hình, Thép tấm, Thép xây dựng giá gốc nhà máy. Hotline: 0905.444.467.">
    
    <!-- Cấu hình Open Graph Thumbnail là Logo & Hình ảnh đại diện trang web khi gửi link -->
    <meta property="og:type" content="website">
    <meta property="og:url" content="https://chaunippo.com/">
    <meta property="og:title" content="CÔNG TY TNHH CHÂU NIPPO - Tôn Thép & Xà Gồ Đà Nẵng | chaunippo.com">
    <meta property="og:description" content="Nhà máy sản xuất và phân phối Tôn lợp, Sắt hộp mạ kẽm, Xà gồ C-Z, Thép hình, Thép tấm, Thép xây dựng uy tín tại 843B Nguyễn Lương Bằng, P. Hải Vân, TP Đà Nẵng. ĐT: 0905.444.467">
    <meta property="og:image" content="https://lh3.googleusercontent.com/d/1YpDntrTlvDoVUZz6fgo6aO57BSu_kJMg=w1200">
    <meta name="twitter:card" content="summary_large_image">
    <meta name="twitter:title" content="CÔNG TY TNHH CHÂU NIPPO - chaunippo.com">
    <meta name="twitter:image" content="https://lh3.googleusercontent.com/d/1YpDntrTlvDoVUZz6fgo6aO57BSu_kJMg=w1200">

    <!-- Favicon SVG đồng bộ với Logo Châu Nippo -->
    <link rel="icon" type="image/svg+xml" href="data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 100 100'%3E%3Crect width='100' height='100' rx='16' fill='%230B3C78'/%3E%3Cpath d='M16 44 L50 18 L84 44 L74 44 L50 26 L26 44 Z' fill='%23E63946'/%3E%3Ctext x='50' y='74' font-family='Arial,sans-serif' font-size='34' font-weight='900' fill='%23FFFFFF' text-anchor='middle'%3ECN%3C/text%3E%3C/svg%3E">

    <!-- Google Fonts: Inter -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&display=swap" rel="stylesheet">

    <!-- Font Awesome Icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">

    <!-- Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    fontFamily: {
                        sans: ['Inter', 'sans-serif'],
                    },
                    colors: {
                        nippo: {
                            blue: '#0B3C78',      /* Màu xanh đậm chủ đạo theo logo */
                            lightBlue: '#1554A1', /* Màu xanh trung gian */
                            sky: '#EBF3FC',       /* Màu nền xanh nhạt */
                            red: '#D92626',       /* Màu đỏ điểm nhấn mái tôn logo */
                            dark: '#1E293B',
                        }
                    },
                    maxWidth: {
                        'flatsome': '1500px',     /* Chiều ngang chuẩn 1500px trên máy tính */
                    }
                }
            }
        }
    </script>

    <style>
        /* Chống tràn viền tuyệt đối và không bị lệch sang phải trên mọi thiết bị */
        *, *::before, *::after {
            box-sizing: border-box;
        }
        html, body {
            margin: 0;
            padding: 0;
            width: 100%;
            max-width: 100vw;
            overflow-x: hidden;
            font-family: 'Inter', sans-serif;
            scroll-behavior: smooth;
            background-color: #F8FAFC;
            color: #1E293B;
        }

        /* Khung chuẩn Flatsome 1500px */
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

        /* Tên danh mục viết liền trên 1 hàng, không bao giờ tự ngắt dòng bên trong tên danh mục */
        .cat-nowrap {
            white-space: nowrap !important;
        }

        /* Tên sản phẩm hiển thị đầy đủ, tự động xuống hàng gọn gàng, không bị cắt chữ hay tràn khung */
        .product-title-full {
            white-space: normal;
            word-break: break-word;
            overflow-wrap: break-word;
            line-height: 1.38;
        }

        /* Hiệu ứng nút liên hệ nổi rung nhẹ */
        @keyframes pulse-ring {
            0% { transform: scale(0.95); box-shadow: 0 0 0 0 rgba(217, 38, 38, 0.6); }
            70% { transform: scale(1); box-shadow: 0 0 0 10px rgba(217, 38, 38, 0); }
            100% { transform: scale(0.95); box-shadow: 0 0 0 0 rgba(217, 38, 38, 0); }
        }
        .floating-pulse {
            animation: pulse-ring 2s infinite;
        }

        /* Tùy chỉnh thanh cuộn ngang cho danh mục trên mobile */
        .no-scrollbar::-webkit-scrollbar {
            display: none;
        }
        .no-scrollbar {
            -ms-overflow-style: none;
            scrollbar-width: none;
        }
    </style>
</head>
<body class="bg-slate-50 text-slate-800 antialiased">

    <!-- =====================================================================
         HEADER FLATSOME (KHÔNG ĐỂ NÚT GỌI NGAY ĐỂ TRÁNH TRÀN VIỀN, LOGO NHỎ GỌN)
         ===================================================================== -->
    <header id="header" class="bg-white shadow-sm sticky top-0 z-40 w-full border-b border-slate-200">
        
        <!-- Top Bar thông tin công ty -->
        <div class="bg-nippo-blue text-white text-[11px] sm:text-xs py-1.5 w-full">
            <div class="flatsome-container flex flex-wrap items-center justify-between gap-2">
                <div class="flex items-center gap-2 truncate">
                    <i class="fa-solid fa-location-dot text-red-400 shrink-0"></i>
                    <span class="truncate">843B Nguyễn Lương Bằng, Phường Hải Vân, TP Đà Nẵng</span>
                </div>
                <div class="hidden md:flex items-center gap-5 shrink-0">
                    <span><i class="fa-solid fa-globe text-sky-300 mr-1"></i>Website: <strong>chaunippo.com</strong></span>
                    <span><i class="fa-solid fa-clock text-sky-300 mr-1"></i>Làm việc: Thứ 2 - Thứ 7 (7:00 - 17:30)</span>
                    <a href="https://www.facebook.com/nguyenvan.chau.35" target="_blank" rel="noopener" class="hover:text-sky-200 transition">
                        <i class="fa-brands fa-facebook mr-1"></i>FB: Nguyễn Văn Châu
                    </a>
                </div>
            </div>
        </div>

        <!-- Header Main: Logo nhỏ gọn + Tên công ty + Tìm kiếm danh mục (Không có nút gọi ngay) -->
        <div class="flatsome-container py-2.5 flex items-center justify-between gap-3">
            
            <!-- Logo Châu Nippo Thiết Kế Mới Chuyên Nghiệp - Chỉnh Gọn Nhỏ Lại -->
            <a href="#trang-chu" class="flex items-center gap-2.5 shrink-0 group focus:outline-none">
                <div class="w-10 h-10 sm:w-11 sm:h-11 rounded-lg bg-nippo-blue flex items-center justify-center p-1 shadow-sm border border-nippo-lightBlue shrink-0">
                    <svg viewBox="0 0 120 120" class="w-full h-full" xmlns="http://www.w3.org/2000/svg">
                        <!-- Biểu tượng mái tôn sóng & khung thép chữ CN -->
                        <path d="M12 46 L60 14 L108 46 L94 46 L60 23 L26 46 Z" fill="#E63946"/>
                        <path d="M24 52 L60 28 L96 52 L85 52 L60 35 L35 52 Z" fill="#93C5FD"/>
                        <rect x="20" y="58" width="80" height="44" rx="6" fill="#0B3C78"/>
                        <text x="60" y="89" font-family="Inter, Arial, sans-serif" font-size="32" font-weight="900" fill="#FFFFFF" text-anchor="middle" letter-spacing="1">CN</text>
                        <rect x="20" y="96" width="80" height="5" rx="2" fill="#E63946"/>
                    </svg>
                </div>
                <div class="leading-tight">
                    <div class="text-xs sm:text-sm md:text-base font-extrabold text-nippo-blue tracking-tight">
                        CÔNG TY TNHH <span class="text-nippo-red">CHÂU NIPPO</span>
                    </div>
                    <div class="text-[10px] sm:text-[11px] font-medium text-slate-600">
                        NHÀ MÁY CÁN TÔN - XÀ GỒ - SẮT THÉP ĐÀ NẴNG
                    </div>
                </div>
            </a>

            <!-- Thanh tìm kiếm nhanh sản phẩm trên máy tính -->
            <div class="hidden lg:flex flex-1 max-w-md mx-4">
                <div class="relative w-full">
                    <input id="searchInput" type="text" oninput="filterProductsBySearch(this.value)" placeholder="Tìm tôn lợp, sắt hộp mạ kẽm, xà gồ C-Z, thép hình..." class="w-full pl-3.5 pr-9 py-1.5 text-xs border border-slate-300 rounded-lg focus:outline-none focus:border-nippo-blue bg-slate-50">
                    <i class="fa-solid fa-magnifying-glass absolute right-3 top-1/2 -translate-y-1/2 text-slate-400 text-xs"></i>
                </div>
            </div>

            <!-- Cam kết ngắn gọn trên máy tính (Không để nút gọi ngay tránh tràn viền) -->
            <div class="hidden xl:flex items-center gap-5 text-xs text-slate-700 shrink-0">
                <div class="flex items-center gap-2">
                    <i class="fa-solid fa-industry text-nippo-blue text-sm"></i>
                    <span>Giá gốc nhà máy</span>
                </div>
                <div class="flex items-center gap-2">
                    <i class="fa-solid fa-truck-fast text-nippo-red text-sm"></i>
                    <span>Giao tận công trình</span>
                </div>
            </div>

            <!-- Nút mở menu danh mục trên điện thoại -->
            <button onclick="toggleMobileMenu()" aria-label="Mở danh mục" class="lg:hidden p-2 rounded-lg border border-slate-200 text-nippo-blue hover:bg-slate-100 shrink-0">
                <i id="mobileMenuIcon" class="fa-solid fa-bars text-lg"></i>
            </button>
        </div>

        <!-- Thanh Danh Mục Trên Máy Tính: Viết liền trên 1 hàng chữ nhỏ gọn, không tự xuống dòng từng mục -->
        <nav class="bg-nippo-blue text-white border-t border-nippo-lightBlue hidden lg:block w-full">
            <div class="flatsome-container">
                <ul class="flex flex-wrap items-center justify-center xl:justify-between gap-x-1 gap-y-1 py-1">
                    <li>
                        <a href="#trang-chu" class="cat-nowrap inline-block px-2.5 py-1.5 text-[12px] xl:text-[12.5px] font-semibold rounded hover:bg-nippo-red transition">
                            <i class="fa-solid fa-house mr-1 text-[11px]"></i>Trang chủ
                        </a>
                    </li>
                    <li>
                        <a href="#gioi-thieu" class="cat-nowrap inline-block px-2.5 py-1.5 text-[12px] xl:text-[12.5px] font-semibold rounded hover:bg-nippo-red transition">
                            Giới thiệu
                        </a>
                    </li>
                    <li>
                        <a href="#san-pham" onclick="selectCategory('sat-hop')" class="cat-nowrap inline-block px-2.5 py-1.5 text-[12px] xl:text-[12.5px] font-semibold rounded hover:bg-nippo-red transition">
                            Giá sắt hộp mạ kẽm
                        </a>
                    </li>
                    <li>
                        <a href="#san-pham" onclick="selectCategory('bang-gia-ton')" class="cat-nowrap inline-block px-2.5 py-1.5 text-[12px] xl:text-[12.5px] font-semibold rounded hover:bg-nippo-red transition">
                            Bảng giá tôn
                        </a>
                    </li>
                    <li>
                        <a href="#san-pham" onclick="selectCategory('xa-go')" class="cat-nowrap inline-block px-2.5 py-1.5 text-[12px] xl:text-[12.5px] font-semibold rounded hover:bg-nippo-red transition">
                            Giá xà gồ C,Z
                        </a>
                    </li>
                    <li>
                        <a href="#san-pham" onclick="selectCategory('thep-hinh')" class="cat-nowrap inline-block px-2.5 py-1.5 text-[12px] xl:text-[12.5px] font-semibold rounded hover:bg-nippo-red transition">
                            Giá thép hình
                        </a>
                    </li>
                    <li>
                        <a href="#san-pham" onclick="selectCategory('thep-tam')" class="cat-nowrap inline-block px-2.5 py-1.5 text-[12px] xl:text-[12.5px] font-semibold rounded hover:bg-nippo-red transition">
                            Giá thép tấm
                        </a>
                    </li>
                    <li>
                        <a href="#san-pham" onclick="selectCategory('thep-xay-dung')" class="cat-nowrap inline-block px-2.5 py-1.5 text-[12px] xl:text-[12.5px] font-semibold rounded hover:bg-nippo-red transition">
                            Thép xây dựng
                        </a>
                    </li>
                    <li>
                        <a href="#san-pham" onclick="selectCategory('san-pham-khac')" class="cat-nowrap inline-block px-2.5 py-1.5 text-[12px] xl:text-[12.5px] font-semibold rounded hover:bg-nippo-red transition">
                            Sản phẩm khác
                        </a>
                    </li>
                    <li>
                        <a href="#du-an-da-nang" class="cat-nowrap inline-block px-2.5 py-1.5 text-[12px] xl:text-[12.5px] font-semibold rounded hover:bg-nippo-red transition">
                            Dự án Đà Nẵng
                        </a>
                    </li>
                    <li>
                        <a href="#doi-tac" class="cat-nowrap inline-block px-2.5 py-1.5 text-[12px] xl:text-[12.5px] font-semibold rounded hover:bg-nippo-red transition">
                            Đối tác
                        </a>
                    </li>
                    <li>
                        <a href="#tin-tuc" class="cat-nowrap inline-block px-2.5 py-1.5 text-[12px] xl:text-[12.5px] font-semibold rounded hover:bg-nippo-red transition">
                            Bài viết
                        </a>
                    </li>
                    <li>
                        <a href="#bao-gia-lien-he" class="cat-nowrap inline-block px-2.5 py-1.5 text-[12px] xl:text-[12.5px] font-semibold rounded hover:bg-nippo-red transition">
                            Báo giá & Liên hệ
                        </a>
                    </li>
                </ul>
            </div>
        </nav>

        <!-- Thanh trượt nhanh danh mục trên Điện Thoại (Gọn đẹp, chữ nhỏ gọn trên 1 hàng) -->
        <div class="lg:hidden bg-nippo-blue text-white border-t border-nippo-lightBlue w-full">
            <div class="flatsome-container flex items-center gap-1.5 overflow-x-auto no-scrollbar py-1.5">
                <a href="#san-pham" onclick="selectCategory('all')" class="cat-nowrap px-2.5 py-1 text-[11px] font-semibold bg-nippo-red rounded">Tất cả SP</a>
                <a href="#san-pham" onclick="selectCategory('sat-hop')" class="cat-nowrap px-2.5 py-1 text-[11px] font-medium bg-nippo-lightBlue/60 rounded">Giá sắt hộp mạ kẽm</a>
                <a href="#san-pham" onclick="selectCategory('bang-gia-ton')" class="cat-nowrap px-2.5 py-1 text-[11px] font-medium bg-nippo-lightBlue/60 rounded">Bảng giá tôn</a>
                <a href="#san-pham" onclick="selectCategory('xa-go')" class="cat-nowrap px-2.5 py-1 text-[11px] font-medium bg-nippo-lightBlue/60 rounded">Giá xà gồ C,Z</a>
                <a href="#san-pham" onclick="selectCategory('thep-hinh')" class="cat-nowrap px-2.5 py-1 text-[11px] font-medium bg-nippo-lightBlue/60 rounded">Giá thép hình</a>
                <a href="#san-pham" onclick="selectCategory('thep-tam')" class="cat-nowrap px-2.5 py-1 text-[11px] font-medium bg-nippo-lightBlue/60 rounded">Giá thép tấm</a>
                <a href="#san-pham" onclick="selectCategory('thep-xay-dung')" class="cat-nowrap px-2.5 py-1 text-[11px] font-medium bg-nippo-lightBlue/60 rounded">Thép xây dựng</a>
                <a href="#san-pham" onclick="selectCategory('san-pham-khac')" class="cat-nowrap px-2.5 py-1 text-[11px] font-medium bg-nippo-lightBlue/60 rounded">Sản phẩm khác</a>
                <a href="#du-an-da-nang" class="cat-nowrap px-2.5 py-1 text-[11px] font-medium bg-nippo-lightBlue/60 rounded">Dự án Đà Nẵng</a>
            </div>
        </div>

        <!-- Menu xổ xuống trên Điện Thoại -->
        <div id="mobileMenuDropdown" class="hidden lg:hidden bg-white border-b border-slate-200 shadow-lg w-full">
            <div class="flatsome-container py-3 space-y-2">
                <div class="relative mb-2">
                    <input type="text" oninput="filterProductsBySearch(this.value)" placeholder="Nhập tên sản phẩm tôn, thép cần tìm..." class="w-full pl-3 pr-8 py-1.5 text-xs border border-slate-300 rounded-lg">
                    <i class="fa-solid fa-magnifying-glass absolute right-3 top-1/2 -translate-y-1/2 text-slate-400 text-xs"></i>
                </div>
                <div class="grid grid-cols-2 gap-1.5 text-xs font-semibold text-slate-700">
                    <a href="#gioi-thieu" onclick="toggleMobileMenu()" class="cat-nowrap p-2 rounded bg-slate-50 hover:bg-nippo-sky hover:text-nippo-blue">Giới thiệu công ty</a>
                    <a href="#san-pham" onclick="selectCategory('sat-hop'); toggleMobileMenu()" class="cat-nowrap p-2 rounded bg-slate-50 hover:bg-nippo-sky hover:text-nippo-blue">Giá sắt hộp mạ kẽm</a>
                    <a href="#san-pham" onclick="selectCategory('bang-gia-ton'); toggleMobileMenu()" class="cat-nowrap p-2 rounded bg-slate-50 hover:bg-nippo-sky hover:text-nippo-blue">Bảng giá tôn lợp</a>
                    <a href="#san-pham" onclick="selectCategory('xa-go'); toggleMobileMenu()" class="cat-nowrap p-2 rounded bg-slate-50 hover:bg-nippo-sky hover:text-nippo-blue">Giá xà gồ C, Z</a>
                    <a href="#san-pham" onclick="selectCategory('thep-hinh'); toggleMobileMenu()" class="cat-nowrap p-2 rounded bg-slate-50 hover:bg-nippo-sky hover:text-nippo-blue">Giá thép hình V,U,I,H</a>
                    <a href="#san-pham" onclick="selectCategory('thep-tam'); toggleMobileMenu()" class="cat-nowrap p-2 rounded bg-slate-50 hover:bg-nippo-sky hover:text-nippo-blue">Giá thép tấm</a>
                    <a href="#san-pham" onclick="selectCategory('thep-xay-dung'); toggleMobileMenu()" class="cat-nowrap p-2 rounded bg-slate-50 hover:bg-nippo-sky hover:text-nippo-blue">Thép xây dựng</a>
                    <a href="#san-pham" onclick="selectCategory('san-pham-khac'); toggleMobileMenu()" class="cat-nowrap p-2 rounded bg-slate-50 hover:bg-nippo-sky hover:text-nippo-blue">Sản phẩm khác</a>
                    <a href="#du-an-da-nang" onclick="toggleMobileMenu()" class="cat-nowrap p-2 rounded bg-slate-50 hover:bg-nippo-sky hover:text-nippo-blue">Dự án tại Đà Nẵng</a>
                    <a href="#bao-gia-lien-he" onclick="toggleMobileMenu()" class="cat-nowrap p-2 rounded bg-slate-50 hover:bg-nippo-sky hover:text-nippo-blue">Yêu cầu báo giá</a>
                </div>
            </div>
        </div>
    </header>

    <!-- =====================================================================
         SECTION BANNER SLIDER TỰ TRƯỢT (2 SLIDE KÍCH THƯỚC BẰNG NHAU)
         Thiết kế riêng ảnh Banner Máy Tính và ảnh Banner Điện Thoại để chữ nhỏ gọn,
         nằm hoàn toàn bên trong ảnh, không bao giờ tràn viền.
         ===================================================================== -->
    <section id="trang-chu" class="w-full py-3 bg-white border-b border-slate-200">
        <div class="flatsome-container">
            <div class="relative w-full rounded-xl overflow-hidden shadow-md bg-nippo-blue">
                
                <!-- ================= SLIDE 1 ================= -->
                <div class="banner-slide block transition-opacity duration-500" data-slide="0">
                    
                    <!-- BANNER MÁY TÍNH SLIDE 1 (Cố định chiều cao 390px bằng nhau) -->
                    <div class="hidden md:grid md:grid-cols-12 h-[390px] w-full bg-gradient-to-r from-nippo-blue via-[#0F488E] to-nippo-lightBlue relative overflow-hidden">
                        <!-- Khối nội dung chữ bên trái: gọn gàng, nằm trọn trong khung -->
                        <div class="col-span-7 flex flex-col justify-center px-10 lg:px-14 py-6 z-10 text-white">
                            <p class="text-xs font-bold uppercase tracking-widest text-amber-300 mb-1.5">
                                NHÀ MÁY CÁN TÔN & PHÂN PHỐI SẮT THÉP UY TÍN ĐÀ NẴNG
                            </p>
                            <h1 class="text-xl lg:text-2xl xl:text-[26px] font-extrabold leading-snug mb-2.5 text-white">
                                CÔNG TY TNHH CHÂU NIPPO - CHAUNIPPO.COM
                            </h1>
                            <p class="text-xs lg:text-sm text-sky-100 leading-relaxed mb-4 max-w-xl">
                                Chuyên sản xuất và cung cấp Tôn lợp các loại, Sắt hộp mạ kẽm, Xà gồ C-Z, Thép hình U-I-V-H, Thép tấm, Thép ống và Thép xây dựng chính hãng giá gốc nhà máy, giao hàng tận chân công trình.
                            </p>
                            <div class="bg-white/10 backdrop-blur-sm border border-white/20 rounded-lg p-3 mb-4 max-w-lg text-xs space-y-1">
                                <div><i class="fa-solid fa-location-dot text-amber-300 mr-2"></i><strong>Địa chỉ:</strong> 843B Nguyễn Lương Bằng, Phường Hải Vân, TP Đà Nẵng</div>
                                <div><i class="fa-solid fa-phone-volume text-amber-300 mr-2"></i><strong>Hotline / Zalo báo giá:</strong> 0905.444.467</div>
                            </div>
                            <div class="flex items-center gap-3">
                                <a href="#bao-gia-lien-he" class="px-4 py-2 rounded-lg bg-nippo-red hover:bg-red-700 text-white text-xs font-bold transition shadow">
                                    Nhận Báo Giá Ngay
                                </a>
                                <a href="#san-pham" class="px-4 py-2 rounded-lg bg-white text-nippo-blue hover:bg-slate-100 text-xs font-bold transition">
                                    Xem Danh Mục Sản Phẩm
                                </a>
                            </div>
                        </div>
                        <!-- Khối ảnh thực tế từ Google Drive bên phải -->
                        <div class="col-span-5 h-full relative p-4 flex items-center justify-center">
                            <div class="grid grid-cols-2 gap-2.5 w-full h-[330px]">
                                <img src="https://lh3.googleusercontent.com/d/1YpDntrTlvDoVUZz6fgo6aO57BSu_kJMg=w800" 
                                     onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1YpDntrTlvDoVUZz6fgo6aO57BSu_kJMg&sz=w800';"
                                     alt="Nhà máy tôn thép Châu Nippo Đà Nẵng" 
                                     class="w-full h-full object-cover rounded-lg border-2 border-white/30 shadow-md">
                                <img src="https://lh3.googleusercontent.com/d/1m6eRU0XcFkROKvkM22CEgV_s7sop1miF=w800" 
                                     onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1m6eRU0XcFkROKvkM22CEgV_s7sop1miF&sz=w800';"
                                     alt="Sản xuất tôn xà gồ Châu Nippo" 
                                     class="w-full h-full object-cover rounded-lg border-2 border-white/30 shadow-md">
                            </div>
                        </div>
                    </div>

                    <!-- BANNER ĐIỆN THOẠI SLIDE 1 (Thiết kế riêng cho Mobile, cao 250px bằng nhau, chữ nhỏ gọn không tràn viền) -->
                    <div class="block md:hidden h-[250px] w-full relative overflow-hidden bg-nippo-blue">
                        <img src="https://lh3.googleusercontent.com/d/1YpDntrTlvDoVUZz6fgo6aO57BSu_kJMg=w800" 
                             onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1YpDntrTlvDoVUZz6fgo6aO57BSu_kJMg&sz=w800';"
                             alt="Công ty TNHH Châu Nippo" 
                             class="absolute inset-0 w-full h-full object-cover opacity-30">
                        <div class="relative z-10 h-full w-full flex flex-col justify-center px-5 py-4 text-white">
                            <span class="text-[10px] font-bold uppercase text-amber-300 tracking-wider mb-1">
                                CHAUNIPPO.COM - TÔN THÉP ĐÀ NẴNG
                            </span>
                            <h2 class="text-sm sm:text-base font-extrabold leading-snug mb-1.5">
                                CÔNG TY TNHH CHÂU NIPPO
                            </h2>
                            <p class="text-[11px] text-sky-100 leading-normal mb-2">
                                Chuyên Tôn lợp, Sắt hộp mạ kẽm, Xà gồ C-Z, Thép hình, Thép tấm, Thép xây dựng giá gốc nhà máy.
                            </p>
                            <div class="text-[10.5px] bg-black/35 rounded px-2.5 py-1.5 mb-2.5 space-y-0.5">
                                <div class="truncate"><i class="fa-solid fa-location-dot text-amber-300 mr-1"></i>843B Nguyễn Lương Bằng, P. Hải Vân, Đà Nẵng</div>
                                <div><i class="fa-solid fa-phone text-amber-300 mr-1"></i>Hotline/Zalo: <strong>0905.444.467</strong></div>
                            </div>
                            <div class="flex items-center gap-2">
                                <a href="#bao-gia-lien-he" class="px-3 py-1.5 rounded bg-nippo-red text-white text-[11px] font-bold">Nhận báo giá</a>
                                <a href="#san-pham" class="px-3 py-1.5 rounded bg-white text-nippo-blue text-[11px] font-bold">Xem sản phẩm</a>
                            </div>
                        </div>
                    </div>
                </div>

                <!-- ================= SLIDE 2 ================= -->
                <div class="banner-slide hidden transition-opacity duration-500" data-slide="1">
                    
                    <!-- BANNER MÁY TÍNH SLIDE 2 (Cố định chiều cao 390px bằng hoàn toàn Slide 1) -->
                    <div class="hidden md:grid md:grid-cols-12 h-[390px] w-full bg-gradient-to-r from-[#093266] via-nippo-blue to-[#174E96] relative overflow-hidden">
                        <div class="col-span-7 flex flex-col justify-center px-10 lg:px-14 py-6 z-10 text-white">
                            <p class="text-xs font-bold uppercase tracking-widest text-amber-300 mb-1.5">
                                ĐẠI LÝ PHÂN PHỐI TÔN THÉP CHÍNH HÃNG TẠI MIỀN TRUNG
                            </p>
                            <h2 class="text-xl lg:text-2xl xl:text-[26px] font-extrabold leading-snug mb-2.5 text-white">
                                CÁN TÔN THEO YÊU CẦU - GIAO HÀNG TẬN CÔNG TRÌNH
                            </h2>
                            <p class="text-xs lg:text-sm text-sky-100 leading-relaxed mb-4 max-w-xl">
                                Cung ứng trọn gói Tôn lạnh, Tôn màu, Tôn xốp cách nhiệt PU, Xà gồ C-Z đột lỗ theo bản vẽ, Sắt hộp mạ kẽm Hòa Phát, Hoa Sen, Đông Á, Minh Ngọc với chiết khấu cao cho nhà thầu.
                            </p>
                            <div class="bg-white/10 backdrop-blur-sm border border-white/20 rounded-lg p-3 mb-4 max-w-lg text-xs space-y-1">
                                <div><i class="fa-solid fa-warehouse text-amber-300 mr-2"></i><strong>Nhà máy:</strong> 843B Nguyễn Lương Bằng, Phường Hải Vân, TP Đà Nẵng</div>
                                <div><i class="fa-solid fa-headset text-amber-300 mr-2"></i><strong>Tư vấn & Báo giá 24/7:</strong> 0905.444.467 (Mr. Châu)</div>
                            </div>
                            <div class="flex items-center gap-3">
                                <a href="tel:0905444467" class="px-4 py-2 rounded-lg bg-nippo-red hover:bg-red-700 text-white text-xs font-bold transition shadow">
                                    Liên Hệ: 0905.444.467
                                </a>
                                <a href="#du-an-da-nang" class="px-4 py-2 rounded-lg bg-white text-nippo-blue hover:bg-slate-100 text-xs font-bold transition">
                                    Dự Án Tại Đà Nẵng
                                </a>
                            </div>
                        </div>
                        <div class="col-span-5 h-full relative p-4 flex items-center justify-center">
                            <div class="grid grid-cols-2 gap-2.5 w-full h-[330px]">
                                <img src="https://lh3.googleusercontent.com/d/1r9Qs-WsirV3L8aqqbA2I-8LQAJM5VUP6=w800" 
                                     onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1r9Qs-WsirV3L8aqqbA2I-8LQAJM5VUP6&sz=w800';"
                                     alt="Kho tôn thép Châu Nippo" 
                                     class="w-full h-full object-cover rounded-lg border-2 border-white/30 shadow-md">
                                <img src="https://lh3.googleusercontent.com/d/1-ZVRsDIwE5WxPzOfvxoeyXr1Ur6jZPA1=w800" 
                                     onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1-ZVRsDIwE5WxPzOfvxoeyXr1Ur6jZPA1&sz=w800';"
                                     alt="Vận chuyển tôn thép Châu Nippo" 
                                     class="w-full h-full object-cover rounded-lg border-2 border-white/30 shadow-md">
                            </div>
                        </div>
                    </div>

                    <!-- BANNER ĐIỆN THOẠI SLIDE 2 (Cố định chiều cao 250px bằng hoàn toàn Slide 1) -->
                    <div class="block md:hidden h-[250px] w-full relative overflow-hidden bg-[#093266]">
                        <img src="https://lh3.googleusercontent.com/d/1r9Qs-WsirV3L8aqqbA2I-8LQAJM5VUP6=w800" 
                             onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1r9Qs-WsirV3L8aqqbA2I-8LQAJM5VUP6&sz=w800';"
                             alt="Nhà máy cán tôn Châu Nippo" 
                             class="absolute inset-0 w-full h-full object-cover opacity-30">
                        <div class="relative z-10 h-full w-full flex flex-col justify-center px-5 py-4 text-white">
                            <span class="text-[10px] font-bold uppercase text-amber-300 tracking-wider mb-1">
                                SẢN XUẤT & GIAO HÀNG TẬN NƠI
                            </span>
                            <h2 class="text-sm sm:text-base font-extrabold leading-snug mb-1.5">
                                CÁN TÔN - XÀ GỒ - SẮT HỘP GIÁ SỈ
                            </h2>
                            <p class="text-[11px] text-sky-100 leading-normal mb-2">
                                Đại lý Tôn Hòa Phát, Đông Á, Hoa Sen, Sắt hộp mạ kẽm, Thép hình, Thép xây dựng chiết khấu cao.
                            </p>
                            <div class="text-[10.5px] bg-black/35 rounded px-2.5 py-1.5 mb-2.5 space-y-0.5">
                                <div class="truncate"><i class="fa-solid fa-warehouse text-amber-300 mr-1"></i>843B Nguyễn Lương Bằng, P. Hải Vân, Đà Nẵng</div>
                                <div><i class="fa-solid fa-phone text-amber-300 mr-1"></i>Tư vấn nhanh: <strong>0905.444.467</strong></div>
                            </div>
                            <div class="flex items-center gap-2">
                                <a href="tel:0905444467" class="px-3 py-1.5 rounded bg-nippo-red text-white text-[11px] font-bold">Gọi 0905.444.467</a>
                                <a href="#du-an-da-nang" class="px-3 py-1.5 rounded bg-white text-nippo-blue text-[11px] font-bold">Xem dự án</a>
                            </div>
                        </div>
                    </div>
                </div>

                <!-- Nút điều hướng Slide trái/phải & chấm tròn -->
                <button onclick="changeSlide(-1)" aria-label="Slide trước" class="absolute left-2 top-1/2 -translate-y-1/2 z-20 w-7 h-7 md:w-8 md:h-8 rounded-full bg-black/35 hover:bg-black/60 text-white flex items-center justify-center transition">
                    <i class="fa-solid fa-chevron-left text-xs"></i>
                </button>
                <button onclick="changeSlide(1)" aria-label="Slide tiếp theo" class="absolute right-2 top-1/2 -translate-y-1/2 z-20 w-7 h-7 md:w-8 md:h-8 rounded-full bg-black/35 hover:bg-black/60 text-white flex items-center justify-center transition">
                    <i class="fa-solid fa-chevron-right text-xs"></i>
                </button>
                <div class="absolute bottom-2.5 left-1/2 -translate-x-1/2 z-20 flex items-center gap-2">
                    <button onclick="goToSlide(0)" class="slide-dot w-2.5 h-2.5 rounded-full bg-white transition"></button>
                    <button onclick="goToSlide(1)" class="slide-dot w-2.5 h-2.5 rounded-full bg-white/40 transition"></button>
                </div>
            </div>
        </div>
    </section>

    <!-- =====================================================================
         SECTION DANH MỤC SẢN PHẨM TRANG CHỦ (TỐI ƯU ĐẸP TRÊN MÁY TÍNH & ĐIỆN THOẠI)
         Chữ danh mục nhỏ gọn, viết liền trên 1 hàng, không tự ngắt dòng tên danh mục.
         ===================================================================== -->
    <section class="py-5 bg-white border-b border-slate-200">
        <div class="flatsome-container">
            <div class="flex items-center justify-between mb-3">
                <h2 class="text-sm md:text-base font-extrabold text-nippo-blue uppercase tracking-wide flex items-center gap-2">
                    <span class="w-1.5 h-5 bg-nippo-red rounded"></span>
                    DANH MỤC SẢN PHẨM TÔN THÉP CHÂU NIPPO
                </h2>
                <span class="text-xs text-slate-500 hidden sm:inline">Chọn danh mục để lọc nhanh sản phẩm</span>
            </div>

            <!-- Danh mục hiển thị dạng thanh карточки gọn đẹp trên cả máy tính và điện thoại -->
            <div class="grid grid-cols-2 sm:grid-cols-4 lg:grid-cols-8 gap-2">
                <button onclick="selectCategory('all')" id="cat-btn-all" class="cat-card group flex items-center justify-center gap-1.5 px-2.5 py-2.5 rounded-lg border border-nippo-blue bg-nippo-blue text-white transition shadow-sm">
                    <i class="fa-solid fa-border-all text-xs shrink-0"></i>
                    <span class="cat-nowrap text-[11.5px] xl:text-[12px] font-bold">Tất cả sản phẩm</span>
                </button>

                <button onclick="selectCategory('sat-hop')" id="cat-btn-sat-hop" class="cat-card group flex items-center justify-center gap-1.5 px-2.5 py-2.5 rounded-lg border border-slate-200 bg-slate-50 hover:border-nippo-blue hover:bg-nippo-sky text-slate-800 transition">
                    <i class="fa-solid fa-cubes text-nippo-blue text-xs shrink-0"></i>
                    <span class="cat-nowrap text-[11.5px] xl:text-[12px] font-semibold">Giá sắt hộp mạ kẽm</span>
                </button>

                <button onclick="selectCategory('bang-gia-ton')" id="cat-btn-bang-gia-ton" class="cat-card group flex items-center justify-center gap-1.5 px-2.5 py-2.5 rounded-lg border border-slate-200 bg-slate-50 hover:border-nippo-blue hover:bg-nippo-sky text-slate-800 transition">
                    <i class="fa-solid fa-layer-group text-nippo-red text-xs shrink-0"></i>
                    <span class="cat-nowrap text-[11.5px] xl:text-[12px] font-semibold">Bảng giá tôn</span>
                </button>

                <button onclick="selectCategory('xa-go')" id="cat-btn-xa-go" class="cat-card group flex items-center justify-center gap-1.5 px-2.5 py-2.5 rounded-lg border border-slate-200 bg-slate-50 hover:border-nippo-blue hover:bg-nippo-sky text-slate-800 transition">
                    <i class="fa-solid fa-bars-staggered text-nippo-blue text-xs shrink-0"></i>
                    <span class="cat-nowrap text-[11.5px] xl:text-[12px] font-semibold">Giá xà gồ C,Z</span>
                </button>

                <button onclick="selectCategory('thep-hinh')" id="cat-btn-thep-hinh" class="cat-card group flex items-center justify-center gap-1.5 px-2.5 py-2.5 rounded-lg border border-slate-200 bg-slate-50 hover:border-nippo-blue hover:bg-nippo-sky text-slate-800 transition">
                    <i class="fa-solid fa-shapes text-nippo-red text-xs shrink-0"></i>
                    <span class="cat-nowrap text-[11.5px] xl:text-[12px] font-semibold">Giá thép hình</span>
                </button>

                <button onclick="selectCategory('thep-tam')" id="cat-btn-thep-tam" class="cat-card group flex items-center justify-center gap-1.5 px-2.5 py-2.5 rounded-lg border border-slate-200 bg-slate-50 hover:border-nippo-blue hover:bg-nippo-sky text-slate-800 transition">
                    <i class="fa-solid fa-vector-square text-nippo-blue text-xs shrink-0"></i>
                    <span class="cat-nowrap text-[11.5px] xl:text-[12px] font-semibold">Giá thép tấm</span>
                </button>

                <button onclick="selectCategory('thep-xay-dung')" id="cat-btn-thep-xay-dung" class="cat-card group flex items-center justify-center gap-1.5 px-2.5 py-2.5 rounded-lg border border-slate-200 bg-slate-50 hover:border-nippo-blue hover:bg-nippo-sky text-slate-800 transition">
                    <i class="fa-solid fa-building-columns text-nippo-red text-xs shrink-0"></i>
                    <span class="cat-nowrap text-[11.5px] xl:text-[12px] font-semibold">Thép xây dựng</span>
                </button>

                <button onclick="selectCategory('san-pham-khac')" id="cat-btn-san-pham-khac" class="cat-card group flex items-center justify-center gap-1.5 px-2.5 py-2.5 rounded-lg border border-slate-200 bg-slate-50 hover:border-nippo-blue hover:bg-nippo-sky text-slate-800 transition">
                    <i class="fa-solid fa-screwdriver-wrench text-nippo-blue text-xs shrink-0"></i>
                    <span class="cat-nowrap text-[11.5px] xl:text-[12px] font-semibold">Sản phẩm khác</span>
                </button>
            </div>
        </div>
    </section>

    <!-- =====================================================================
         SECTION GIỚI THIỆU CÔNG TY TNHH CHÂU NIPPO (GIỐNG MẪU TONTHEPDANANG.VN)
         ===================================================================== -->
    <section id="gioi-thieu" class="py-7 bg-slate-50 border-b border-slate-200">
        <div class="flatsome-container">
            <div class="grid grid-cols-1 lg:grid-cols-12 gap-6 items-center bg-white p-4 sm:p-6 rounded-xl border border-slate-200 shadow-sm">
                <!-- Cột văn bản giới thiệu -->
                <div class="lg:col-span-7 space-y-3">
                    <div class="text-xs font-bold text-nippo-red uppercase tracking-wider">GIỚI THIỆU VỀ CHÚNG TÔI</div>
                    <h2 class="text-lg sm:text-xl font-extrabold text-nippo-blue">
                        CÔNG TY TNHH CHÂU NIPPO - NHÀ MÁY CÁN TÔN & PHÂN PHỐI SẮT THÉP ĐÀ NẴNG
                    </h2>
                    <p class="text-xs sm:text-sm text-slate-600 leading-relaxed">
                        Lời đầu tiên, <strong>CÔNG TY TNHH CHÂU NIPPO</strong> (<span class="text-nippo-blue font-semibold">chaunippo.com</span>) xin gửi đến toàn thể Quý khách hàng, Quý nhà thầu và Đối tác lời chào trân trọng cùng lời chúc sức khỏe, thịnh vượng.
                    </p>
                    <p class="text-xs sm:text-sm text-slate-600 leading-relaxed">
                        Đặt nhà máy và văn phòng giao dịch tại <strong>843B Nguyễn Lương Bằng, Phường Hải Vân, TP Đà Nẵng</strong>, <strong>CHÂU NIPPO</strong> hoạt động chủ lực trong lĩnh vực cán tôn theo yêu cầu, gia công xà gồ C-Z và phân phối sỉ lẻ sắt hộp mạ kẽm, thép hình, thép tấm, thép ống, thép xây dựng, lưới B40 và phụ kiện ngũ kim cho hàng ngàn công trình dân dụng và công nghiệp tại Đà Nẵng và khu vực miền Trung.
                    </p>
                    <div class="grid grid-cols-2 sm:grid-cols-3 gap-2.5 pt-2">
                        <div class="p-2.5 rounded-lg bg-nippo-sky border border-blue-100">
                            <div class="text-sm font-extrabold text-nippo-blue">Chính Hãng 100%</div>
                            <div class="text-[11px] text-slate-600">Đủ quy cách, độ dày ly</div>
                        </div>
                        <div class="p-2.5 rounded-lg bg-nippo-sky border border-blue-100">
                            <div class="text-sm font-extrabold text-nippo-red">Giá Gốc Nhà Máy</div>
                            <div class="text-[11px] text-slate-600">Chiết khấu cao cho thầu</div>
                        </div>
                        <div class="p-2.5 rounded-lg bg-nippo-sky border border-blue-100 col-span-2 sm:col-span-1">
                            <div class="text-sm font-extrabold text-nippo-blue">Vận Chuyển Nhanh</div>
                            <div class="text-[11px] text-slate-600">Giao hàng tận công trình</div>
                        </div>
                    </div>
                </div>

                <!-- Cột hình ảnh thực tế tại nhà máy Châu Nippo từ Google Drive -->
                <div class="lg:col-span-5 grid grid-cols-2 gap-2.5">
                    <img src="https://lh3.googleusercontent.com/d/1vW9Jj94i4WSJ8fbHExzHjxtGyNHs-5NQ=w700"
                         onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1vW9Jj94i4WSJ8fbHExzHjxtGyNHs-5NQ&sz=w700';"
                         alt="Xưởng cán tôn Châu Nippo"
                         class="w-full h-36 sm:h-44 object-cover rounded-lg border border-slate-200">
                    <img src="https://lh3.googleusercontent.com/d/1dQoYMQKm2Ucz9RMPI8NTLp3JSlW5I7kU=w700"
                         onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1dQoYMQKm2Ucz9RMPI8NTLp3JSlW5I7kU&sz=w700';"
                         alt="Kho sắt thép Châu Nippo"
                         class="w-full h-36 sm:h-44 object-cover rounded-lg border border-slate-200">
                    <img src="https://lh3.googleusercontent.com/d/1OANVH-wB6mWZGvgdJJ26YI3Pt5kJe1qZ=w700"
                         onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1OANVH-wB6mWZGvgdJJ26YI3Pt5kJe1qZ&sz=w700';"
                         alt="Máy cán tôn xà gồ Châu Nippo"
                         class="w-full h-36 sm:h-44 object-cover rounded-lg border border-slate-200">
                    <img src="https://lh3.googleusercontent.com/d/1Jz0iprFCgWejooR1PbSnBuEZtj6s8D1J=w700"
                         onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1Jz0iprFCgWejooR1PbSnBuEZtj6s8D1J&sz=w700';"
                         alt="Sản phẩm tôn thép thực tế Châu Nippo"
                         class="w-full h-36 sm:h-44 object-cover rounded-lg border border-slate-200">
                </div>
            </div>
        </div>
    </section>

    <!-- =====================================================================
         SECTION BẢNG BÁO GIÁ TỔNG HỢP 6 HẠNG MỤC (THEO MẪU TONTHEPDANANG.VN)
         ===================================================================== -->
    <section class="py-7 bg-white border-b border-slate-200">
        <div class="flatsome-container">
            <div class="text-center max-w-3xl mx-auto mb-5">
                <h2 class="text-base sm:text-lg md:text-xl font-extrabold text-nippo-blue uppercase">
                    BÁO GIÁ TÔN THÉP CHÂU NIPPO MỚI NHẤT
                </h2>
                <p class="text-xs sm:text-sm text-slate-600 mt-1">
                    Bảng báo giá Tôn lợp – Sắt hộp mạ kẽm – Xà gồ C,Z – Thép hình – Thép tấm – Thép xây dựng tại Đà Nẵng. Liên hệ trực tiếp <strong>0905.444.467</strong> để nhận chiết khấu tốt nhất theo khối lượng đơn hàng.
                </p>
            </div>

            <div class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-6 gap-3">
                <div onclick="selectCategory('bang-gia-ton')" class="cursor-pointer bg-slate-50 hover:bg-nippo-sky border border-slate-200 rounded-xl overflow-hidden transition flex flex-col">
                    <img src="https://lh3.googleusercontent.com/d/1YpDntrTlvDoVUZz6fgo6aO57BSu_kJMg=w600"
                         onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1YpDntrTlvDoVUZz6fgo6aO57BSu_kJMg&sz=w600';"
                         alt="Báo giá tôn lợp xây dựng" class="w-full h-28 sm:h-32 object-cover">
                    <div class="p-3 flex-1 flex flex-col justify-between">
                        <h3 class="product-title-full text-xs sm:text-[13px] font-bold text-nippo-blue mb-1">Báo giá tôn lợp trong xây dựng</h3>
                        <p class="text-[11px] text-slate-600">Tôn lạnh, tôn màu, tôn xốp cách nhiệt PU, tôn giả ngói</p>
                    </div>
                </div>

                <div onclick="selectCategory('sat-hop')" class="cursor-pointer bg-slate-50 hover:bg-nippo-sky border border-slate-200 rounded-xl overflow-hidden transition flex flex-col">
                    <img src="https://lh3.googleusercontent.com/d/1m6eRU0XcFkROKvkM22CEgV_s7sop1miF=w600"
                         onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1m6eRU0XcFkROKvkM22CEgV_s7sop1miF&sz=w600';"
                         alt="Báo giá thép hộp mạ kẽm" class="w-full h-28 sm:h-32 object-cover">
                    <div class="p-3 flex-1 flex flex-col justify-between">
                        <h3 class="product-title-full text-xs sm:text-[13px] font-bold text-nippo-blue mb-1">Báo giá sắt hộp mạ kẽm</h3>
                        <p class="text-[11px] text-slate-600">Hộp vuông, hộp chữ nhật Hòa Phát, Hoa Sen, Minh Ngọc</p>
                    </div>
                </div>

                <div onclick="selectCategory('xa-go')" class="cursor-pointer bg-slate-50 hover:bg-nippo-sky border border-slate-200 rounded-xl overflow-hidden transition flex flex-col">
                    <img src="https://lh3.googleusercontent.com/d/1r9Qs-WsirV3L8aqqbA2I-8LQAJM5VUP6=w600"
                         onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1r9Qs-WsirV3L8aqqbA2I-8LQAJM5VUP6&sz=w600';"
                         alt="Báo giá xà gồ C Z" class="w-full h-28 sm:h-32 object-cover">
                    <div class="p-3 flex-1 flex flex-col justify-between">
                        <h3 class="product-title-full text-xs sm:text-[13px] font-bold text-nippo-blue mb-1">Báo giá xà gồ C, Z mạ kẽm</h3>
                        <p class="text-[11px] text-slate-600">Gia công cán xà gồ C, Z đột lỗ chuẩn kích thước</p>
                    </div>
                </div>

                <div onclick="selectCategory('thep-hinh')" class="cursor-pointer bg-slate-50 hover:bg-nippo-sky border border-slate-200 rounded-xl overflow-hidden transition flex flex-col">
                    <img src="https://lh3.googleusercontent.com/d/1-ZVRsDIwE5WxPzOfvxoeyXr1Ur6jZPA1=w600"
                         onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1-ZVRsDIwE5WxPzOfvxoeyXr1Ur6jZPA1&sz=w600';"
                         alt="Báo giá thép hình" class="w-full h-28 sm:h-32 object-cover">
                    <div class="p-3 flex-1 flex flex-col justify-between">
                        <h3 class="product-title-full text-xs sm:text-[13px] font-bold text-nippo-blue mb-1">Báo giá thép hình V, U, I, H</h3>
                        <p class="text-[11px] text-slate-600">Cung cấp sỉ lẻ thép hình kết cấu nhà xưởng chính hãng</p>
                    </div>
                </div>

                <div onclick="selectCategory('thep-tam')" class="cursor-pointer bg-slate-50 hover:bg-nippo-sky border border-slate-200 rounded-xl overflow-hidden transition flex flex-col">
                    <img src="https://lh3.googleusercontent.com/d/1nY1LkA70X0E-fNnwEbihGCDDj2YTd20D=w600"
                         onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1nY1LkA70X0E-fNnwEbihGCDDj2YTd20D&sz=w600';"
                         alt="Báo giá thép tấm thép ống" class="w-full h-28 sm:h-32 object-cover">
                    <div class="p-3 flex-1 flex flex-col justify-between">
                        <h3 class="product-title-full text-xs sm:text-[13px] font-bold text-nippo-blue mb-1">Báo giá thép tấm & thép ống</h3>
                        <p class="text-[11px] text-slate-600">Thép tấm SS400, Q235, Q345, bản mã, thép ống đúc</p>
                    </div>
                </div>

                <div onclick="selectCategory('san-pham-khac')" class="cursor-pointer bg-slate-50 hover:bg-nippo-sky border border-slate-200 rounded-xl overflow-hidden transition flex flex-col">
                    <img src="https://lh3.googleusercontent.com/d/1w0uJ42OWRANfD4oa4tBGyqP7y0J5v-Fv=w600"
                         onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1w0uJ42OWRANfD4oa4tBGyqP7y0J5v-Fv&sz=w600';"
                         alt="Báo giá dây thép lưới B40 phụ kiện" class="w-full h-28 sm:h-32 object-cover">
                    <div class="p-3 flex-1 flex flex-col justify-between">
                        <h3 class="product-title-full text-xs sm:text-[13px] font-bold text-nippo-blue mb-1">Báo giá dây thép, kẽm & phụ kiện</h3>
                        <p class="text-[11px] text-slate-600">Lưới B40, dây kẽm buộc, máng xối, diềm tôn, vít bắn tôn</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- =====================================================================
         SECTION DANH SÁCH SẢN PHẨM CHI TIẾT (LẤY TỪ MẪU TONTHEPDANANG.VN + ẢNH THỰC TẾ DRIVE)
         - Điện thoại: Chia 2 cột (grid-cols-2)
         - Không có nhãn dán đè lên ảnh sản phẩm
         - Tên sản phẩm hiển thị đầy đủ, không bị tràn hay thiếu chữ
         ===================================================================== -->
    <section id="san-pham" class="py-8 bg-slate-50 border-b border-slate-200">
        <div class="flatsome-container">
            <div class="flex flex-col sm:flex-row sm:items-center justify-between gap-2 mb-5 pb-2 border-b-2 border-nippo-blue">
                <div>
                    <h2 id="currentCategoryTitle" class="text-base sm:text-lg md:text-xl font-extrabold text-nippo-blue uppercase">
                        TẤT CẢ SẢN PHẨM TÔN THÉP CHÂU NIPPO
                    </h2>
                    <p class="text-xs text-slate-500">Hình ảnh thực tế tại nhà máy cán tôn & kho sắt thép Châu Nippo - 843B Nguyễn Lương Bằng, Đà Nẵng</p>
                </div>
                <div class="text-xs font-semibold text-nippo-red">
                    <i class="fa-solid fa-phone-volume mr-1"></i>Báo giá nhanh: 0905.444.467
                </div>
            </div>

            <!-- Grid sản phẩm: 2 cột trên điện thoại (grid-cols-2), 4 cột trên tablet, 5 cột trên máy tính 1500px -->
            <div id="productGrid" class="grid grid-cols-2 md:grid-cols-4 lg:grid-cols-5 gap-3 sm:gap-4">
                <!-- Danh sách sản phẩm được render tự động từ dữ liệu chuẩn bên dưới -->
            </div>
        </div>
    </section>

    <!-- =====================================================================
         SECTION TẠI SAO KHÁCH HÀNG CHỌN CHÚNG TÔI (THEO MẪU TONTHEPDANANG.VN)
         ===================================================================== -->
    <section class="py-7 bg-white border-b border-slate-200">
        <div class="flatsome-container">
            <div class="text-center mb-5">
                <h2 class="text-base sm:text-lg md:text-xl font-extrabold text-nippo-blue uppercase">
                    TẠI SAO KHÁCH HÀNG CHỌN CÔNG TY TNHH CHÂU NIPPO
                </h2>
            </div>
            <div class="grid grid-cols-1 md:grid-cols-3 gap-4">
                <div class="p-5 rounded-xl bg-slate-50 border border-slate-200 flex items-start gap-3.5">
                    <div class="w-11 h-11 rounded-lg bg-nippo-blue text-white flex items-center justify-center shrink-0">
                        <i class="fa-solid fa-medal text-lg"></i>
                    </div>
                    <div>
                        <h3 class="text-sm font-extrabold text-nippo-blue uppercase mb-1">SẢN PHẨM CHẤT LƯỢNG</h3>
                        <p class="text-xs text-slate-600 leading-relaxed">
                            Cung cấp các sản phẩm tôn lợp, xà gồ, sắt thép chính hãng từ các nhà máy uy tín hàng đầu (Hòa Phát, Đông Á, Hoa Sen, Minh Ngọc, Việt Úc) đúng độ dày, chuẩn zem và tiêu chuẩn kỹ thuật.
                        </p>
                    </div>
                </div>

                <div class="p-5 rounded-xl bg-slate-50 border border-slate-200 flex items-start gap-3.5">
                    <div class="w-11 h-11 rounded-lg bg-nippo-red text-white flex items-center justify-center shrink-0">
                        <i class="fa-solid fa-tags text-lg"></i>
                    </div>
                    <div>
                        <h3 class="text-sm font-extrabold text-nippo-blue uppercase mb-1">GIÁ THÀNH CẠNH TRANH</h3>
                        <p class="text-xs text-slate-600 leading-relaxed">
                            Trực tiếp gia công cán tôn, xà gồ tại nhà máy 843B Nguyễn Lương Bằng và phân phối thẳng đến chân công trình, tối ưu chi phí trung gian để mang lại mức giá tốt nhất cho khách hàng.
                        </p>
                    </div>
                </div>

                <div class="p-5 rounded-xl bg-slate-50 border border-slate-200 flex items-start gap-3.5">
                    <div class="w-11 h-11 rounded-lg bg-nippo-blue text-white flex items-center justify-center shrink-0">
                        <i class="fa-solid fa-truck-ramp-box text-lg"></i>
                    </div>
                    <div>
                        <h3 class="text-sm font-extrabold text-nippo-blue uppercase mb-1">TẬN TÂM VÀ TRÁCH NHIỆM</h3>
                        <p class="text-xs text-slate-600 leading-relaxed">
                            Đội ngũ nhân viên và hệ thống xe tải cẩu chuyên nghiệp tại Đà Nẵng luôn sẵn sàng phục vụ nhanh chóng, cắt cán tôn theo đúng kích thước yêu cầu, đảm bảo tiến độ mọi dự án.
                        </p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- =====================================================================
         SECTION DANH MỤC CÁC DỰ ÁN Ở ĐÀ NẴNG TRÊN TRANG CHỦ
         Sử dụng ảnh thực tế từ Google Drive kết hợp các công trình thực tế tại Đà Nẵng
         ===================================================================== -->
    <section id="du-an-da-nang" class="py-8 bg-slate-50 border-b border-slate-200">
        <div class="flatsome-container">
            <div class="flex flex-col sm:flex-row sm:items-center justify-between gap-2 mb-5 pb-2 border-b-2 border-nippo-blue">
                <div>
                    <h2 class="text-base sm:text-lg md:text-xl font-extrabold text-nippo-blue uppercase">
                        DỰ ÁN CUNG CẤP TÔN THÉP TIÊU BIỂU TẠI ĐÀ NẴNG
                    </h2>
                    <p class="text-xs text-slate-600">Các công trình nhà xưởng, khu công nghiệp và dân dụng tại Đà Nẵng do Công ty TNHH Châu Nippo cung ứng vật tư</p>
                </div>
                <a href="#bao-gia-lien-he" class="text-xs font-bold text-nippo-red hover:underline">
                    Đăng ký báo giá dự án <i class="fa-solid fa-arrow-right ml-1"></i>
                </a>
            </div>

            <div class="grid grid-cols-2 lg:grid-cols-4 gap-3 sm:gap-4">
                <!-- Dự án 1 -->
                <div class="bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm flex flex-col">
                    <img src="https://lh3.googleusercontent.com/d/1lNcMKSyynz4psjdTAtFi1-WfYu2jdcVw=w700"
                         onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1lNcMKSyynz4psjdTAtFi1-WfYu2jdcVw&sz=w700';"
                         alt="Dự án nhà xưởng Khu Công Nghiệp Liên Chiểu Đà Nẵng"
                         class="w-full h-36 sm:h-44 object-cover">
                    <div class="p-3 sm:p-4 flex-1 flex flex-col justify-between">
                        <div>
                            <h3 class="product-title-full text-xs sm:text-sm font-bold text-nippo-blue mb-1">
                                Cung Cấp Tôn Lợp & Xà Gồ Nhà Xưởng Khu Công Nghiệp Liên Chiểu
                            </h3>
                            <p class="text-[11px] sm:text-xs text-slate-600">
                                Địa điểm: Khu Công Nghiệp Liên Chiểu, Phường Hải Vân, TP Đà Nẵng. Hạng mục: Tôn lạnh mạ màu, xà gồ C200 mạ kẽm và sắt hộp.
                            </p>
                        </div>
                        <div class="mt-2 pt-2 border-t border-slate-100 text-[11px] font-semibold text-nippo-red">
                            Đơn vị cung ứng: Công ty TNHH Châu Nippo
                        </div>
                    </div>
                </div>

                <!-- Dự án 2 -->
                <div class="bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm flex flex-col">
                    <img src="https://lh3.googleusercontent.com/d/1vW9Jj94i4WSJ8fbHExzHjxtGyNHs-5NQ=w700"
                         onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1vW9Jj94i4WSJ8fbHExzHjxtGyNHs-5NQ&sz=w700';"
                         alt="Dự án Khu Công Nghiệp Hòa Khánh Đà Nẵng"
                         class="w-full h-36 sm:h-44 object-cover">
                    <div class="p-3 sm:p-4 flex-1 flex flex-col justify-between">
                        <div>
                            <h3 class="product-title-full text-xs sm:text-sm font-bold text-nippo-blue mb-1">
                                Thi Công Vật Tư Thép Hình & Tôn Cách Nhiệt KCN Hòa Khánh
                            </h3>
                            <p class="text-[11px] sm:text-xs text-slate-600">
                                Địa điểm: Khu Công nghiệp Hòa Khánh, Quận Liên Chiểu, TP Đà Nẵng. Hạng mục: Thép hình I, V, tôn xốp PU chống nóng nhà máy.
                            </p>
                        </div>
                        <div class="mt-2 pt-2 border-t border-slate-100 text-[11px] font-semibold text-nippo-red">
                            Đơn vị cung ứng: Công ty TNHH Châu Nippo
                        </div>
                    </div>
                </div>

                <!-- Dự án 3 -->
                <div class="bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm flex flex-col">
                    <img src="https://lh3.googleusercontent.com/d/1dQoYMQKm2Ucz9RMPI8NTLp3JSlW5I7kU=w700"
                         onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1dQoYMQKm2Ucz9RMPI8NTLp3JSlW5I7kU&sz=w700';"
                         alt="Dự án Khu Công Nghệ Cao Đà Nẵng"
                         class="w-full h-36 sm:h-44 object-cover">
                    <div class="p-3 sm:p-4 flex-1 flex flex-col justify-between">
                        <div>
                            <h3 class="product-title-full text-xs sm:text-sm font-bold text-nippo-blue mb-1">
                                Cung Ứng Sắt Hộp Mạ Kẽm & Thép Tấm Khu Công Nghệ Cao Đà Nẵng
                            </h3>
                            <p class="text-[11px] sm:text-xs text-slate-600">
                                Địa điểm: Khu công nghệ cao Đà Nẵng, Liên Chiểu, TP Đà Nẵng. Hạng mục: Sắt hộp mạ kẽm Hòa Phát, thép tấm SS400, xà gồ Z.
                            </p>
                        </div>
                        <div class="mt-2 pt-2 border-t border-slate-100 text-[11px] font-semibold text-nippo-red">
                            Đơn vị cung ứng: Công ty TNHH Châu Nippo
                        </div>
                    </div>
                </div>

                <!-- Dự án 4 -->
                <div class="bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm flex flex-col">
                    <img src="https://lh3.googleusercontent.com/d/1-ZVRsDIwE5WxPzOfvxoeyXr1Ur6jZPA1=w700"
                         onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1-ZVRsDIwE5WxPzOfvxoeyXr1Ur6jZPA1&sz=w700';"
                         alt="Dự án Kho Bãi Phụ Trợ Cảng Liên Chiểu Đà Nẵng"
                         class="w-full h-36 sm:h-44 object-cover">
                    <div class="p-3 sm:p-4 flex-1 flex flex-col justify-between">
                        <div>
                            <h3 class="product-title-full text-xs sm:text-sm font-bold text-nippo-blue mb-1">
                                Cung Cấp Tôn Sóng Công Nghiệp & Kết Cấu Thép Khu Vực Cảng Liên Chiểu
                            </h3>
                            <p class="text-[11px] sm:text-xs text-slate-600">
                                Địa điểm: Khu vực Cảng Liên Chiểu, Phường Hải Vân, TP Đà Nẵng. Hạng mục: Tôn lợp nhà kho, máng xối inox, thép ống mạ kẽm.
                            </p>
                        </div>
                        <div class="mt-2 pt-2 border-t border-slate-100 text-[11px] font-semibold text-nippo-red">
                            Đơn vị cung ứng: Công ty TNHH Châu Nippo
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- =====================================================================
         SECTION DANH MỤC CÁC ĐỐI TÁC & THƯƠNG HIỆU TÔN THÉP
         ===================================================================== -->
    <section id="doi-tac" class="py-7 bg-white border-b border-slate-200">
        <div class="flatsome-container">
            <div class="text-center mb-5">
                <h2 class="text-base sm:text-lg md:text-xl font-extrabold text-nippo-blue uppercase">
                    ĐỐI TÁC & THƯƠNG HIỆU TÔN THÉP PHÂN PHỐI
                </h2>
                <p class="text-xs text-slate-600 mt-1">Hợp tác trực tiếp cùng các tập đoàn sản xuất tôn thép hàng đầu Việt Nam</p>
            </div>

            <div class="grid grid-cols-2 sm:grid-cols-4 lg:grid-cols-8 gap-2.5">
                <div class="p-3 rounded-lg border border-slate-200 bg-slate-50 flex flex-col items-center justify-center text-center hover:border-nippo-blue transition">
                    <span class="text-xs font-extrabold text-nippo-blue">HÒA PHÁT</span>
                    <span class="text-[10px] text-slate-500 mt-0.5">Tôn & Thép Hòa Phát</span>
                </div>
                <div class="p-3 rounded-lg border border-slate-200 bg-slate-50 flex flex-col items-center justify-center text-center hover:border-nippo-blue transition">
                    <span class="text-xs font-extrabold text-nippo-red">HOA SEN</span>
                    <span class="text-[10px] text-slate-500 mt-0.5">Tôn Thép Hoa Sen</span>
                </div>
                <div class="p-3 rounded-lg border border-slate-200 bg-slate-50 flex flex-col items-center justify-center text-center hover:border-nippo-blue transition">
                    <span class="text-xs font-extrabold text-nippo-blue">TÔN ĐÔNG Á</span>
                    <span class="text-[10px] text-slate-500 mt-0.5">Tôn Lạnh & Tôn Màu</span>
                </div>
                <div class="p-3 rounded-lg border border-slate-200 bg-slate-50 flex flex-col items-center justify-center text-center hover:border-nippo-blue transition">
                    <span class="text-xs font-extrabold text-nippo-blue">MINH NGỌC</span>
                    <span class="text-[10px] text-slate-500 mt-0.5">Thép Hộp Minh Ngọc</span>
                </div>
                <div class="p-3 rounded-lg border border-slate-200 bg-slate-50 flex flex-col items-center justify-center text-center hover:border-nippo-blue transition">
                    <span class="text-xs font-extrabold text-nippo-red">PHƯƠNG NAM</span>
                    <span class="text-[10px] text-slate-500 mt-0.5">Tôn Việt Nhật SSSC</span>
                </div>
                <div class="p-3 rounded-lg border border-slate-200 bg-slate-50 flex flex-col items-center justify-center text-center hover:border-nippo-blue transition">
                    <span class="text-xs font-extrabold text-nippo-blue">NAM KIM</span>
                    <span class="text-[10px] text-slate-500 mt-0.5">Tôn Thép Nam Kim</span>
                </div>
                <div class="p-3 rounded-lg border border-slate-200 bg-slate-50 flex flex-col items-center justify-center text-center hover:border-nippo-blue transition">
                    <span class="text-xs font-extrabold text-nippo-blue">THÉP VAS</span>
                    <span class="text-[10px] text-slate-500 mt-0.5">Thép Việt Mỹ</span>
                </div>
                <div class="p-3 rounded-lg border border-slate-200 bg-slate-50 flex flex-col items-center justify-center text-center hover:border-nippo-blue transition">
                    <span class="text-xs font-extrabold text-nippo-red">VIỆT ÚC</span>
                    <span class="text-[10px] text-slate-500 mt-0.5">Thép Xây Dựng</span>
                </div>
            </div>
        </div>
    </section>

    <!-- =====================================================================
         SECTION DANH MỤC CÁC BÀI VIẾT TRANG CHỦ (TIN TỨC & KINH NGHIỆM)
         ===================================================================== -->
    <section id="tin-tuc" class="py-8 bg-slate-50 border-b border-slate-200">
        <div class="flatsome-container">
            <div class="flex flex-col sm:flex-row sm:items-center justify-between gap-2 mb-5 pb-2 border-b-2 border-nippo-blue">
                <div>
                    <h2 class="text-base sm:text-lg md:text-xl font-extrabold text-nippo-blue uppercase">
                        BÀI VIẾT & BẢNG GIÁ TÔN THÉP MỚI NHẤT
                    </h2>
                    <p class="text-xs text-slate-600">Cập nhật thông tin quy cách tôn lợp, xà gồ, sắt hộp và kinh nghiệm chọn vật liệu xây dựng tại Đà Nẵng</p>
                </div>
            </div>

            <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-4">
                <!-- Bài viết 1 -->
                <article class="bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm flex flex-col">
                    <img src="https://lh3.googleusercontent.com/d/1YpDntrTlvDoVUZz6fgo6aO57BSu_kJMg=w600"
                         onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1YpDntrTlvDoVUZz6fgo6aO57BSu_kJMg&sz=w600';"
                         alt="Bảng giá tôn lợp tại Đà Nẵng"
                         class="w-full h-40 object-cover">
                    <div class="p-4 flex-1 flex flex-col justify-between">
                        <div>
                            <h3 class="product-title-full text-xs sm:text-sm font-bold text-nippo-blue mb-1.5">
                                Cập Nhật Bảng Giá Tôn Lợp, Tôn Xốp Cách Nhiệt Tại Đà Nẵng Mới Nhất
                            </h3>
                            <p class="text-xs text-slate-600 leading-relaxed">
                                Hướng dẫn lựa chọn độ dày tôn lạnh, tôn màu, tôn xốp chống nóng PU phù hợp với khí hậu miền Trung và báo giá trực tiếp tại xưởng cán tôn Châu Nippo.
                            </p>
                        </div>
                        <a href="#bao-gia-lien-he" class="mt-3 text-xs font-bold text-nippo-red hover:underline inline-flex items-center">
                            Nhận bảng giá chi tiết <i class="fa-solid fa-angle-right ml-1"></i>
                        </a>
                    </div>
                </article>

                <!-- Bài viết 2 -->
                <article class="bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm flex flex-col">
                    <img src="https://lh3.googleusercontent.com/d/1m6eRU0XcFkROKvkM22CEgV_s7sop1miF=w600"
                         onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1m6eRU0XcFkROKvkM22CEgV_s7sop1miF&sz=w600';"
                         alt="Quy cách sắt hộp mạ kẽm"
                         class="w-full h-40 object-cover">
                    <div class="p-4 flex-1 flex flex-col justify-between">
                        <div>
                            <h3 class="product-title-full text-xs sm:text-sm font-bold text-nippo-blue mb-1.5">
                                Bảng Quy Cách Trọng Lượng Sắt Hộp Mạ Kẽm Hòa Phát, Hoa Sen, Minh Ngọc
                            </h3>
                            <p class="text-xs text-slate-600 leading-relaxed">
                                Tra cứu đầy đủ kích thước thép hộp vuông 14x14 đến 120x120 và thép hộp chữ nhật 13x26 đến 100x200 chuẩn độ dày ly phục vụ thi công cơ khí và kết cấu mái.
                            </p>
                        </div>
                        <a href="#bao-gia-lien-he" class="mt-3 text-xs font-bold text-nippo-red hover:underline inline-flex items-center">
                            Nhận bảng giá chi tiết <i class="fa-solid fa-angle-right ml-1"></i>
                        </a>
                    </div>
                </article>

                <!-- Bài viết 3 -->
                <article class="bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm flex flex-col">
                    <img src="https://lh3.googleusercontent.com/d/1r9Qs-WsirV3L8aqqbA2I-8LQAJM5VUP6=w600"
                         onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1r9Qs-WsirV3L8aqqbA2I-8LQAJM5VUP6&sz=w600';"
                         alt="Gia công xà gồ C Z tại Đà Nẵng"
                         class="w-full h-40 object-cover">
                    <div class="p-4 flex-1 flex flex-col justify-between">
                        <div>
                            <h3 class="product-title-full text-xs sm:text-sm font-bold text-nippo-blue mb-1.5">
                                Kinh Nghiệm Chọn Xà Gồ C, Z Mạ Kẽm Cho Nhà Xưởng Công Nghiệp
                            </h3>
                            <p class="text-xs text-slate-600 leading-relaxed">
                                So sánh ưu điểm của xà gồ C và xà gồ Z mạ kẽm cường độ cao, nhận gia công đột lỗ theo bản vẽ kỹ thuật nhanh chóng tại nhà máy Châu Nippo Đà Nẵng.
                            </p>
                        </div>
                        <a href="#bao-gia-lien-he" class="mt-3 text-xs font-bold text-nippo-red hover:underline inline-flex items-center">
                            Nhận bảng giá chi tiết <i class="fa-solid fa-angle-right ml-1"></i>
                        </a>
                    </div>
                </article>

                <!-- Bài viết 4 -->
                <article class="bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm flex flex-col">
                    <img src="https://lh3.googleusercontent.com/d/1OANVH-wB6mWZGvgdJJ26YI3Pt5kJe1qZ=w600"
                         onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1OANVH-wB6mWZGvgdJJ26YI3Pt5kJe1qZ&sz=w600';"
                         alt="Phụ kiện tôn lợp máng xối diềm tôn"
                         class="w-full h-40 object-cover">
                    <div class="p-4 flex-1 flex flex-col justify-between">
                        <div>
                            <h3 class="product-title-full text-xs sm:text-sm font-bold text-nippo-blue mb-1.5">
                                Gia Công Máng Xối, Diềm Tôn, Úp Nóc Theo Yêu Cầu Tại Quận Liên Chiểu - Hải Vân
                            </h3>
                            <p class="text-xs text-slate-600 leading-relaxed">
                                Chấn máng xối tôn mạ màu, inox, diềm mái, úp nóc và cung cấp đầy đủ phụ kiện vít bắn tôn, keo chống thấm đồng bộ cho mái nhà bền đẹp.
                            </p>
                        </div>
                        <a href="#bao-gia-lien-he" class="mt-3 text-xs font-bold text-nippo-red hover:underline inline-flex items-center">
                            Nhận bảng giá chi tiết <i class="fa-solid fa-angle-right ml-1"></i>
                        </a>
                    </div>
                </article>
            </div>
        </div>
    </section>

    <!-- =====================================================================
         SECTION FORM YÊU CẦU BÁO GIÁ + FACEBOOK + GOOGLE MAP NGOÀI TRANG CHỦ
         ===================================================================== -->
    <section id="bao-gia-lien-he" class="py-8 bg-white border-b border-slate-200">
        <div class="flatsome-container">
            <div class="grid grid-cols-1 lg:grid-cols-12 gap-6">
                
                <!-- Cột 1 (5/12): FORM YÊU CẦU VÀ BÁO GIÁ TRANG CHỦ -->
                <div class="lg:col-span-5 bg-slate-50 p-5 rounded-xl border border-slate-200 shadow-sm">
                    <div class="text-xs font-bold text-nippo-red uppercase tracking-wider mb-1">HỖ TRỢ NHANH 24/7</div>
                    <h2 class="text-base sm:text-lg font-extrabold text-nippo-blue uppercase mb-2">
                        FORM YÊU CẦU & NHẬN BÁO GIÁ TÔN THÉP
                    </h2>
                    <p class="text-xs text-slate-600 mb-4">
                        Quý khách vui lòng điền thông tin khối lượng hoặc quy cách cần báo giá, bộ phận kinh doanh <strong>Châu Nippo (0905.444.467)</strong> sẽ liên hệ gửi bảng giá ngay.
                    </p>

                    <form id="quoteForm" onsubmit="submitQuoteForm(event)" class="space-y-3">
                        <div>
                            <label class="block text-xs font-semibold text-slate-700 mb-1">Họ và tên Quý khách *</label>
                            <input type="text" id="custName" required placeholder="Nhập họ và tên..." class="w-full px-3 py-2 text-xs rounded-lg border border-slate-300 focus:outline-none focus:border-nippo-blue bg-white">
                        </div>

                        <div class="grid grid-cols-1 sm:grid-cols-2 gap-3">
                            <div>
                                <label class="block text-xs font-semibold text-slate-700 mb-1">Số điện thoại / Zalo *</label>
                                <input type="tel" id="custPhone" required placeholder="Ví dụ: 0905..." class="w-full px-3 py-2 text-xs rounded-lg border border-slate-300 focus:outline-none focus:border-nippo-blue bg-white">
                            </div>
                            <div>
                                <label class="block text-xs font-semibold text-slate-700 mb-1">Danh mục cần báo giá</label>
                                <select id="custCategory" class="w-full px-3 py-2 text-xs rounded-lg border border-slate-300 focus:outline-none focus:border-nippo-blue bg-white">
                                    <option value="Tôn lợp các loại">Bảng giá tôn lợp các loại</option>
                                    <option value="Sắt hộp mạ kẽm">Giá sắt hộp mạ kẽm</option>
                                    <option value="Xà gồ C, Z">Giá xà gồ C, Z</option>
                                    <option value="Thép hình V, U, I, H">Giá thép hình V, U, I, H</option>
                                    <option value="Thép tấm, thép ống">Giá thép tấm, thép ống</option>
                                    <option value="Thép xây dựng">Thép xây dựng</option>
                                    <option value="Lưới B40 & Phụ kiện khác">Sản phẩm & Phụ kiện khác</option>
                                </select>
                            </div>
                        </div>

                        <div>
                            <label class="block text-xs font-semibold text-slate-700 mb-1">Địa chỉ giao hàng / Công trình</label>
                            <input type="text" id="custAddress" placeholder="Ví dụ: Liên Chiểu, Đà Nẵng..." class="w-full px-3 py-2 text-xs rounded-lg border border-slate-300 focus:outline-none focus:border-nippo-blue bg-white">
                        </div>

                        <div>
                            <label class="block text-xs font-semibold text-slate-700 mb-1">Chi tiết quy cách, độ dày, số lượng cần báo giá</label>
                            <textarea id="custNote" rows="3" placeholder="Nhập quy cách tôn, sắt hộp, xà gồ hoặc yêu cầu cắt cán theo kích thước..." class="w-full px-3 py-2 text-xs rounded-lg border border-slate-300 focus:outline-none focus:border-nippo-blue bg-white"></textarea>
                        </div>

                        <button type="submit" class="w-full py-2.5 px-4 rounded-lg bg-nippo-red hover:bg-red-700 text-white font-bold text-xs uppercase tracking-wide transition shadow">
                            <i class="fa-solid fa-paper-plane mr-1.5"></i>GỬI YÊU CẦU BÁO GIÁ NGAY
                        </button>
                    </form>

                    <!-- Thông báo gửi thành công hiển thị trực tiếp (Không dùng alert) -->
                    <div id="quoteSuccessBox" class="hidden mt-3 p-3 rounded-lg bg-emerald-50 border border-emerald-300 text-emerald-800 text-xs">
                        <div class="font-bold mb-0.5"><i class="fa-solid fa-circle-check mr-1"></i>Đã ghi nhận yêu cầu báo giá thành công!</div>
                        <p id="quoteSuccessText"></p>
                    </div>
                </div>

                <!-- Cột 2 (7/12): FACEBOOK NGUYỄN VĂN CHÂU & BẢN ĐỒ GOOGLE MAP TRỰC TIẾP NGOÀI TRANG CHỦ -->
                <div class="lg:col-span-7 flex flex-col justify-between gap-4">
                    
                    <!-- Khối kết nối Facebook chính thức ngoài trang chủ -->
                    <div class="bg-slate-50 p-4 rounded-xl border border-slate-200 shadow-sm flex flex-col sm:flex-row items-start sm:items-center justify-between gap-4">
                        <div class="flex items-center gap-3.5">
                            <img src="https://lh3.googleusercontent.com/d/1YpDntrTlvDoVUZz6fgo6aO57BSu_kJMg=w300"
                                 onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1YpDntrTlvDoVUZz6fgo6aO57BSu_kJMg&sz=w300';"
                                 alt="Facebook Nguyễn Văn Châu - Châu Nippo"
                                 class="w-14 h-14 rounded-full object-cover border-2 border-nippo-blue shrink-0">
                            <div>
                                <div class="text-[11px] font-bold text-nippo-blue uppercase">KẾT NỐI FACEBOOK TRỰC TIẾP</div>
                                <h3 class="text-sm sm:text-base font-extrabold text-slate-800">
                                    Nguyễn Văn Châu (Công Ty TNHH Châu Nippo)
                                </h3>
                                <p class="text-xs text-slate-600">
                                    Theo dõi hình ảnh xuất hàng tôn thép thực tế mỗi ngày và nhắn tin nhận báo giá qua Facebook.
                                </p>
                            </div>
                        </div>
                        <a href="https://www.facebook.com/nguyenvan.chau.35" target="_blank" rel="noopener" class="shrink-0 px-4 py-2 rounded-lg bg-[#1877F2] hover:bg-blue-700 text-white text-xs font-bold flex items-center gap-2 shadow-sm transition">
                            <i class="fa-brands fa-facebook text-sm"></i>Xem Facebook Ngay
                        </a>
                    </div>

                    <!-- Khối Bản đồ & Ảnh Google Map 843B Nguyễn Lương Bằng ngoài trang chủ -->
                    <div class="bg-slate-50 p-4 rounded-xl border border-slate-200 shadow-sm flex-1 flex flex-col">
                        <div class="flex flex-col sm:flex-row sm:items-center justify-between gap-2 mb-3">
                            <div>
                                <h3 class="text-sm font-extrabold text-nippo-blue uppercase flex items-center gap-1.5">
                                    <i class="fa-solid fa-map-location-dot text-nippo-red"></i>
                                    BẢN ĐỒ GOOGLE MAP NHÀ MÁY CHÂU NIPPO
                                </h3>
                                <p class="text-xs text-slate-600">
                                    Địa chỉ: <strong>843B Nguyễn Lương Bằng, Phường Hải Vân, TP Đà Nẵng</strong>
                                </p>
                            </div>
                            <a href="https://share.google/N4kBiZ1pxLiWOrFnz" target="_blank" rel="noopener" class="inline-flex items-center gap-1.5 px-3 py-1.5 rounded-lg bg-nippo-blue hover:bg-nippo-lightBlue text-white text-xs font-bold transition shrink-0">
                                <i class="fa-solid fa-diamond-turn-right"></i>Mở Google Map Chỉ Đường
                            </a>
                        </div>

                        <!-- Bản đồ Google Maps nhúng trực tiếp + thẻ mở nhanh link Google Share -->
                        <div class="w-full h-60 sm:h-64 rounded-lg overflow-hidden border border-slate-300 relative bg-slate-200">
                            <iframe 
                                title="Bản đồ Công Ty TNHH Châu Nippo 843B Nguyễn Lương Bằng Đà Nẵng"
                                src="https://maps.google.com/maps?q=843B%20Nguy%E1%BB%85n%20L%C6%B0%C6%A1ng%20B%E1%BA%B1ng,%20%C4%90%C3%A0%20N%E1%BA%B5ng&t=&z=16&ie=UTF8&iwloc=&output=embed"
                                class="w-full h-full border-0"
                                loading="lazy"
                                referrerpolicy="no-referrer-when-downgrade">
                            </iframe>
                        </div>
                    </div>

                </div>
            </div>
        </div>
    </section>

    <!-- =====================================================================
         FOOTER CHÂN TRANG (ĐẦY ĐỦ THÔNG TIN CÔNG TY TNHH CHÂU NIPPO)
         ===================================================================== -->
    <footer class="bg-nippo-blue text-white pt-8 pb-6 w-full">
        <div class="flatsome-container">
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-6 pb-6 border-b border-white/15">
                
                <!-- Cột 1: Thông tin công ty -->
                <div class="space-y-2.5">
                    <div class="flex items-center gap-2.5">
                        <div class="w-9 h-9 rounded-lg bg-white flex items-center justify-center p-1 shrink-0">
                            <svg viewBox="0 0 120 120" class="w-full h-full" xmlns="http://www.w3.org/2000/svg">
                                <path d="M12 46 L60 14 L108 46 L94 46 L60 23 L26 46 Z" fill="#E63946"/>
                                <rect x="20" y="54" width="80" height="46" rx="6" fill="#0B3C78"/>
                                <text x="60" y="86" font-family="Inter, Arial, sans-serif" font-size="32" font-weight="900" fill="#FFFFFF" text-anchor="middle">CN</text>
                            </svg>
                        </div>
                        <div>
                            <div class="text-sm font-extrabold text-white">CÔNG TY TNHH CHÂU NIPPO</div>
                            <div class="text-[11px] text-sky-200">Website: chaunippo.com</div>
                        </div>
                    </div>
                    <p class="text-xs text-sky-100 leading-relaxed">
                        Nhà máy sản xuất và cung cấp Tôn lợp, Sắt hộp mạ kẽm, Xà gồ C-Z, Thép hình, Thép tấm, Thép ống, Lưới B40 và Thép xây dựng giá tốt nhất thị trường, giao hàng tận nơi tại Đà Nẵng và miền Trung.
                    </p>
                    <div class="text-xs space-y-1 text-sky-100 pt-1">
                        <div><i class="fa-solid fa-location-dot text-amber-300 mr-2"></i><strong>Địa chỉ:</strong> 843B Nguyễn Lương Bằng, Phường Hải Vân, TP Đà Nẵng</div>
                        <div><i class="fa-solid fa-phone text-amber-300 mr-2"></i><strong>Điện thoại / Zalo:</strong> <a href="tel:0905444467" class="font-bold text-white hover:underline">0905.444.467</a></div>
                        <div><i class="fa-solid fa-id-card text-amber-300 mr-2"></i><strong>Mã số thuế:</strong> 0401949902</div>
                    </div>
                </div>

                <!-- Cột 2: Danh mục sản phẩm -->
                <div>
                    <h3 class="text-xs font-extrabold uppercase tracking-wider text-amber-300 mb-3">DANH MỤC SẢN PHẨM</h3>
                    <ul class="grid grid-cols-2 gap-2 text-xs text-sky-100">
                        <li><a href="#san-pham" onclick="selectCategory('sat-hop')" class="hover:text-white">Sắt hộp mạ kẽm</a></li>
                        <li><a href="#san-pham" onclick="selectCategory('bang-gia-ton')" class="hover:text-white">Tôn lợp các loại</a></li>
                        <li><a href="#san-pham" onclick="selectCategory('xa-go')" class="hover:text-white">Xà gồ C, Z</a></li>
                        <li><a href="#san-pham" onclick="selectCategory('thep-hinh')" class="hover:text-white">Thép hình V,U,I,H</a></li>
                        <li><a href="#san-pham" onclick="selectCategory('thep-tam')" class="hover:text-white">Thép tấm SS400</a></li>
                        <li><a href="#san-pham" onclick="selectCategory('thep-xay-dung')" class="hover:text-white">Thép ống mạ kẽm</a></li>
                        <li><a href="#san-pham" onclick="selectCategory('thep-xay-dung')" class="hover:text-white">Thép xây dựng</a></li>
                        <li><a href="#san-pham" onclick="selectCategory('san-pham-khac')" class="hover:text-white">Lưới B40 & Dây thép</a></li>
                    </ul>
                </div>

                <!-- Cột 3: Liên kết nhanh & Kết nối -->
                <div>
                    <h3 class="text-xs font-extrabold uppercase tracking-wider text-amber-300 mb-3">KẾT NỐI VỚI CHÚNG TÔI</h3>
                    <div class="space-y-2 text-xs text-sky-100">
                        <a href="https://www.facebook.com/nguyenvan.chau.35" target="_blank" rel="noopener" class="flex items-center gap-2 p-2 rounded-lg bg-white/10 hover:bg-white/20 transition">
                            <i class="fa-brands fa-facebook text-base text-sky-300"></i>
                            <span>Facebook: Nguyễn Văn Châu</span>
                        </a>
                        <a href="https://zalo.me/0905444467" target="_blank" rel="noopener" class="flex items-center gap-2 p-2 rounded-lg bg-white/10 hover:bg-white/20 transition">
                            <i class="fa-solid fa-comment-dots text-base text-sky-300"></i>
                            <span>Zalo báo giá: 0905.444.467</span>
                        </a>
                        <a href="https://share.google/N4kBiZ1pxLiWOrFnz" target="_blank" rel="noopener" class="flex items-center gap-2 p-2 rounded-lg bg-white/10 hover:bg-white/20 transition">
                            <i class="fa-solid fa-map-pin text-base text-amber-300"></i>
                            <span>Chỉ đường Google Map</span>
                        </a>
                    </div>
                </div>

                <!-- Cột 4: Hình ảnh thực tế kho xưởng -->
                <div>
                    <h3 class="text-xs font-extrabold uppercase tracking-wider text-amber-300 mb-3">HÌNH ẢNH NHÀ MÁY CHÂU NIPPO</h3>
                    <div class="grid grid-cols-3 gap-1.5">
                        <img src="https://lh3.googleusercontent.com/d/1YpDntrTlvDoVUZz6fgo6aO57BSu_kJMg=w300" onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1YpDntrTlvDoVUZz6fgo6aO57BSu_kJMg&sz=w300';" alt="Ảnh thực tế 1" class="w-full h-14 object-cover rounded">
                        <img src="https://lh3.googleusercontent.com/d/1m6eRU0XcFkROKvkM22CEgV_s7sop1miF=w300" onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1m6eRU0XcFkROKvkM22CEgV_s7sop1miF&sz=w300';" alt="Ảnh thực tế 2" class="w-full h-14 object-cover rounded">
                        <img src="https://lh3.googleusercontent.com/d/1r9Qs-WsirV3L8aqqbA2I-8LQAJM5VUP6=w300" onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1r9Qs-WsirV3L8aqqbA2I-8LQAJM5VUP6&sz=w300';" alt="Ảnh thực tế 3" class="w-full h-14 object-cover rounded">
                        <img src="https://lh3.googleusercontent.com/d/1-ZVRsDIwE5WxPzOfvxoeyXr1Ur6jZPA1=w300" onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1-ZVRsDIwE5WxPzOfvxoeyXr1Ur6jZPA1&sz=w300';" alt="Ảnh thực tế 4" class="w-full h-14 object-cover rounded">
                        <img src="https://lh3.googleusercontent.com/d/1vW9Jj94i4WSJ8fbHExzHjxtGyNHs-5NQ=w300" onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1vW9Jj94i4WSJ8fbHExzHjxtGyNHs-5NQ&sz=w300';" alt="Ảnh thực tế 5" class="w-full h-14 object-cover rounded">
                        <img src="https://lh3.googleusercontent.com/d/1lNcMKSyynz4psjdTAtFi1-WfYu2jdcVw=w300" onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1lNcMKSyynz4psjdTAtFi1-WfYu2jdcVw&sz=w300';" alt="Ảnh thực tế 6" class="w-full h-14 object-cover rounded">
                    </div>
                </div>
            </div>

            <div class="pt-4 flex flex-col sm:flex-row items-center justify-between text-xs text-sky-200 gap-2">
                <div>Copyright © 2026 <strong>CÔNG TY TNHH CHÂU NIPPO (chaunippo.com)</strong>. All rights reserved.</div>
                <div>Địa chỉ: 843B Nguyễn Lương Bằng, Phường Hải Vân, TP Đà Nẵng | ĐT: 0905.444.467</div>
            </div>
        </div>
    </footer>

    <!-- =====================================================================
         CÁC NÚT LIÊN HỆ NỔI BẬT (ZALO, FACEBOOK, HOTLINE) TƯƠNG THÍCH MÁY TÍNH & ĐIỆN THOẠI
         Đặt gọn bên trong khung nhìn, không gây tràn màn hình.
         ===================================================================== -->
    <div class="fixed bottom-4 right-3 z-50 flex flex-col items-end gap-2.5">
        <!-- Nút Facebook -->
        <a href="https://www.facebook.com/nguyenvan.chau.35" target="_blank" rel="noopener" aria-label="Facebook Châu Nippo"
           class="flex items-center gap-2 bg-[#1877F2] hover:bg-blue-700 text-white px-3 py-2 rounded-full shadow-lg transition">
            <i class="fa-brands fa-facebook-f text-sm w-4 text-center"></i>
            <span class="text-xs font-bold hidden sm:inline">Facebook</span>
        </a>

        <!-- Nút Zalo -->
        <a href="https://zalo.me/0905444467" target="_blank" rel="noopener" aria-label="Zalo 0905.444.467"
           class="flex items-center gap-2 bg-[#0068FF] hover:bg-blue-600 text-white px-3 py-2 rounded-full shadow-lg transition">
            <span class="text-xs font-extrabold px-1 bg-white text-[#0068FF] rounded">Zalo</span>
            <span class="text-xs font-bold hidden sm:inline">0905.444.467</span>
        </a>

        <!-- Nút Hotline -->
        <a href="tel:0905444467" aria-label="Gọi 0905.444.467"
           class="floating-pulse flex items-center gap-2 bg-nippo-red hover:bg-red-700 text-white px-3.5 py-2.5 rounded-full shadow-xl transition">
            <i class="fa-solid fa-phone-volume text-sm"></i>
            <span class="text-xs font-extrabold">0905.444.467</span>
        </a>
    </div>

    <!-- =====================================================================
         JAVASCRIPT XỬ LÝ DANH MỤC SẢN PHẨM, BANNER SLIDER & FORM BÁO GIÁ
         ===================================================================== -->
    <script>
        /* Danh sách 11 ảnh thực tế từ Google Drive của Công ty TNHH Châu Nippo */
        const driveImages = {
            img1: 'https://lh3.googleusercontent.com/d/1YpDntrTlvDoVUZz6fgo6aO57BSu_kJMg=w700',
            img2: 'https://lh3.googleusercontent.com/d/1m6eRU0XcFkROKvkM22CEgV_s7sop1miF=w700',
            img3: 'https://lh3.googleusercontent.com/d/1r9Qs-WsirV3L8aqqbA2I-8LQAJM5VUP6=w700',
            img4: 'https://lh3.googleusercontent.com/d/1-ZVRsDIwE5WxPzOfvxoeyXr1Ur6jZPA1=w700',
            img5: 'https://lh3.googleusercontent.com/d/1vW9Jj94i4WSJ8fbHExzHjxtGyNHs-5NQ=w700',
            img6: 'https://lh3.googleusercontent.com/d/1dQoYMQKm2Ucz9RMPI8NTLp3JSlW5I7kU=w700',
            img7: 'https://lh3.googleusercontent.com/d/1OANVH-wB6mWZGvgdJJ26YI3Pt5kJe1qZ=w700',
            img8: 'https://lh3.googleusercontent.com/d/1Jz0iprFCgWejooR1PbSnBuEZtj6s8D1J=w700',
            img9: 'https://lh3.googleusercontent.com/d/1nY1LkA70X0E-fNnwEbihGCDDj2YTd20D=w700',
            img10: 'https://lh3.googleusercontent.com/d/1w0uJ42OWRANfD4oa4tBGyqP7y0J5v-Fv=w700',
            img11: 'https://lh3.googleusercontent.com/d/1lNcMKSyynz4psjdTAtFi1-WfYu2jdcVw=w700'
        };

        /* Dữ liệu đầy đủ các sản phẩm lấy từ web mẫu tonthepdanang.vn kết hợp 11 ảnh thực tế trong Drive */
        const productsData = [
            /* 1. Danh mục: Giá sắt hộp mạ kẽm */
            { id: 1, name: 'Sắt hộp mạ kẽm Hòa Phát', category: 'sat-hop', spec: 'Đủ quy cách hộp vuông & chữ nhật', img: driveImages.img2, fallbackId: '1m6eRU0XcFkROKvkM22CEgV_s7sop1miF' },
            { id: 2, name: 'Sắt hộp mạ kẽm Minh Ngọc', category: 'sat-hop', spec: 'Độ dày 1.0 ly - 3.0 ly chính hãng', img: driveImages.img6, fallbackId: '1dQoYMQKm2Ucz9RMPI8NTLp3JSlW5I7kU' },
            { id: 3, name: 'Sắt hộp mạ kẽm Hoa Sen', category: 'sat-hop', spec: 'Chống rỉ sét cao, bề mặt sáng bóng', img: driveImages.img8, fallbackId: '1Jz0iprFCgWejooR1PbSnBuEZtj6s8D1J' },
            { id: 4, name: 'Sắt hộp mạ kẽm Nam Kim', category: 'sat-hop', spec: 'Chuẩn độ dày, giao tận công trình', img: driveImages.img2, fallbackId: '1m6eRU0XcFkROKvkM22CEgV_s7sop1miF' },
            { id: 5, name: 'Thép hộp 100 x 200 mạ kẽm', category: 'sat-hop', spec: 'Thép hộp cỡ lớn kết cấu nhà xưởng', img: driveImages.img6, fallbackId: '1dQoYMQKm2Ucz9RMPI8NTLp3JSlW5I7kU' },
            { id: 6, name: 'Thép hộp vuông 120 x 120', category: 'sat-hop', spec: 'Chịu lực cao, chuẩn tiêu chuẩn', img: driveImages.img8, fallbackId: '1Jz0iprFCgWejooR1PbSnBuEZtj6s8D1J' },

            /* 2. Danh mục: Bảng giá tôn */
            { id: 7, name: 'Tôn lợp mạ màu & tôn lạnh cán sóng theo yêu cầu', category: 'bang-gia-ton', spec: 'Cán 5 sóng, 9 sóng, 11 sóng tại xưởng', img: driveImages.img1, fallbackId: '1YpDntrTlvDoVUZz6fgo6aO57BSu_kJMg' },
            { id: 8, name: 'Tôn xốp, tôn chống nóng cách nhiệt PU 3 lớp', category: 'bang-gia-ton', spec: 'Cách âm, chống nóng hiệu quả cao', img: driveImages.img5, fallbackId: '1vW9Jj94i4WSJ8fbHExzHjxtGyNHs-5NQ' },
            { id: 9, name: 'Bảng giá tôn Hòa Phát chính hãng', category: 'bang-gia-ton', spec: 'Đầy đủ màu sắc, độ dày 3.0 - 5.0 dem', img: driveImages.img7, fallbackId: '1OANVH-wB6mWZGvgdJJ26YI3Pt5kJe1qZ' },
            { id: 10, name: 'Giá tôn Đông Á & tôn Hoa Sen', category: 'bang-gia-ton', spec: 'Bảo hành chính hãng, cắt theo kích thước', img: driveImages.img11, fallbackId: '1lNcMKSyynz4psjdTAtFi1-WfYu2jdcVw' },
            { id: 11, name: 'Giá tôn Phương Nam - Tôn Việt Nhật', category: 'bang-gia-ton', spec: 'Độ bền cao cho công trình ven biển', img: driveImages.img1, fallbackId: '1YpDntrTlvDoVUZz6fgo6aO57BSu_kJMg' },
            { id: 12, name: 'Tôn giả ngói, tôn vòm & tôn nhựa lấy sáng', category: 'bang-gia-ton', spec: 'Gia công uốn vòm, dập tôn sóng ngói', img: driveImages.img5, fallbackId: '1vW9Jj94i4WSJ8fbHExzHjxtGyNHs-5NQ' },

            /* 3. Danh mục: Giá xà gồ C,Z */
            { id: 13, name: 'Xà gồ C mạ kẽm cán theo kích thước yêu cầu', category: 'xa-go', spec: 'C80, C100, C125, C150, C180, C200', img: driveImages.img3, fallbackId: '1r9Qs-WsirV3L8aqqbA2I-8LQAJM5VUP6' },
            { id: 14, name: 'Xà gồ Z mạ kẽm đột lỗ nhà xưởng công nghiệp', category: 'xa-go', spec: 'Z150, Z180, Z200, Z250 cường độ cao', img: driveImages.img9, fallbackId: '1nY1LkA70X0E-fNnwEbihGCDDj2YTd20D' },

            /* 4. Danh mục: Giá thép hình */
            { id: 15, name: 'Thép hình V30, Thép V40, V50, V63, V75', category: 'thep-hinh', spec: 'Thép V đen & mạ kẽm nhúng nóng', img: driveImages.img4, fallbackId: '1-ZVRsDIwE5WxPzOfvxoeyXr1Ur6jZPA1' },
            { id: 16, name: 'Thép hình U, Thép hình I, Thép hình H kết cấu', category: 'thep-hinh', spec: 'Đầy đủ quy cách cho khung kèo thép', img: driveImages.img10, fallbackId: '1w0uJ42OWRANfD4oa4tBGyqP7y0J5v-Fv' },

            /* 5. Danh mục: Giá thép tấm */
            { id: 17, name: 'Thép tấm Q235 & Thép tấm SS400', category: 'thep-tam', spec: 'Thép tấm trơn, tấm nhám chống trượt', img: driveImages.img9, fallbackId: '1nY1LkA70X0E-fNnwEbihGCDDj2YTd20D' },
            { id: 18, name: 'Thép tấm Q345, Thép lá mạ kẽm & Thép lá đen', category: 'thep-tam', spec: 'Cắt bản mã theo yêu cầu bản vẽ', img: driveImages.img10, fallbackId: '1w0uJ42OWRANfD4oa4tBGyqP7y0J5v-Fv' },

            /* 6. Danh mục: Thép xây dựng & Thép ống */
            { id: 19, name: 'Thép ống đúc phi 129, phi 168 & Thép ống mạ kẽm', category: 'thep-xay-dung', spec: 'Thép ống Hòa Phát, ống đúc chịu áp lực', img: driveImages.img4, fallbackId: '1-ZVRsDIwE5WxPzOfvxoeyXr1Ur6jZPA1' },
            { id: 20, name: 'Thép xây dựng Hòa Phát, Việt Úc, Việt Mỹ (VAS)', category: 'thep-xay-dung', spec: 'Thép cuộn, thép thanh vằn D10 - D32', img: driveImages.img6, fallbackId: '1dQoYMQKm2Ucz9RMPI8NTLp3JSlW5I7kU' },

            /* 7. Danh mục: Sản phẩm khác */
            { id: 21, name: 'Máng xối tôn, diềm tôn, úp nóc chấn theo yêu cầu', category: 'san-pham-khac', spec: 'Gia công chuẩn kích thước mái công trình', img: driveImages.img7, fallbackId: '1OANVH-wB6mWZGvgdJJ26YI3Pt5kJe1qZ' },
            { id: 22, name: 'Lưới thép B40, dây thép kẽm buộc & vít bắn tôn', category: 'san-pham-khac', spec: 'Đầy đủ phụ kiện lợp mái và rào chắn', img: driveImages.img11, fallbackId: '1lNcMKSyynz4psjdTAtFi1-WfYu2jdcVw' }
        ];

        const categoryTitles = {
            'all': 'TẤT CẢ SẢN PHẨM TÔN THÉP CHÂU NIPPO',
            'sat-hop': 'DANH MỤC: GIÁ SẮT HỘP MẠ KẼM',
            'bang-gia-ton': 'DANH MỤC: BẢNG GIÁ TÔN LỢP XÂY DỰNG',
            'xa-go': 'DANH MỤC: GIÁ XÀ GỒ C, Z MẠ KẼM',
            'thep-hinh': 'DANH MỤC: GIÁ THÉP HÌNH V, U, I, H',
            'thep-tam': 'DANH MỤC: GIÁ THÉP TẤM SS400, Q235, Q345',
            'thep-xay-dung': 'DANH MỤC: THÉP XÂY DỰNG & THÉP ỐNG',
            'san-pham-khac': 'DANH MỤC: LƯỚI B40, DÂY KẼM & PHỤ KIỆN TÔN'
        };

        /* Hàm hiển thị sản phẩm (Không có nhãn dán trên ảnh, chia 2 cột trên điện thoại, tên sản phẩm không bị cắt chữ) */
        function renderProducts(list) {
            const grid = document.getElementById('productGrid');
            if (!list.length) {
                grid.innerHTML = `
                    <div class="col-span-full bg-white p-6 rounded-xl border border-slate-200 text-center text-xs text-slate-600">
                        Không tìm thấy sản phẩm phù hợp. Quý khách vui lòng gọi trực tiếp <strong>0905.444.467</strong> để được tư vấn nhanh nhất.
                    </div>
                `;
                return;
            }

            grid.innerHTML = list.map(item => `
                <div class="bg-white rounded-xl border border-slate-200 hover:border-nippo-blue overflow-hidden shadow-sm transition flex flex-col justify-between">
                    <div>
                        <div class="w-full h-32 sm:h-40 bg-slate-100 overflow-hidden">
                            <img src="${item.img}" 
                                 onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=${item.fallbackId}&sz=w700';"
                                 alt="${item.name}" 
                                 class="w-full h-full object-cover hover:scale-105 transition duration-300">
                        </div>
                        <div class="p-2.5 sm:p-3.5">
                            <h3 class="product-title-full text-[12.5px] sm:text-[13.5px] font-bold text-nippo-blue mb-1">
                                ${item.name}
                            </h3>
                            <p class="product-title-full text-[11px] text-slate-500">
                                ${item.spec}
                            </p>
                        </div>
                    </div>
                    <div class="px-2.5 pb-2.5 sm:px-3.5 sm:pb-3.5 pt-1 flex items-center justify-between gap-1.5 border-t border-slate-100">
                        <span class="text-[11px] sm:text-xs font-extrabold text-nippo-red">Giá: Liên hệ</span>
                        <a href="#bao-gia-lien-he" onclick="prefillProductQuote('${item.name.replace(/'/g, "\\'")}')" class="px-2.5 py-1 rounded bg-nippo-blue hover:bg-nippo-lightBlue text-white text-[11px] font-semibold transition">
                            Báo giá
                        </a>
                    </div>
                </div>
            `).join('');
        }

        /* Lọc theo danh mục */
        function selectCategory(catKey) {
            const titleEl = document.getElementById('currentCategoryTitle');
            titleEl.textContent = categoryTitles[catKey] || categoryTitles['all'];

            document.querySelectorAll('.cat-card').forEach(btn => {
                btn.classList.remove('bg-nippo-blue', 'text-white', 'border-nippo-blue');
                btn.classList.add('bg-slate-50', 'text-slate-800', 'border-slate-200');
            });
            const activeBtn = document.getElementById('cat-btn-' + catKey);
            if (activeBtn) {
                activeBtn.classList.remove('bg-slate-50', 'text-slate-800', 'border-slate-200');
                activeBtn.classList.add('bg-nippo-blue', 'text-white', 'border-nippo-blue');
            }

            if (catKey === 'all') {
                renderProducts(productsData);
            } else {
                renderProducts(productsData.filter(p => p.category === catKey));
            }
        }

        /* Tìm kiếm sản phẩm */
        function filterProductsBySearch(keyword) {
            const q = keyword.trim().toLowerCase();
            if (!q) {
                renderProducts(productsData);
                return;
            }
            const filtered = productsData.filter(p => 
                p.name.toLowerCase().includes(q) || p.spec.toLowerCase().includes(q)
            );
            renderProducts(filtered);
        }

        /* Điền sẵn sản phẩm vào form báo giá */
        function prefillProductQuote(productName) {
            const noteEl = document.getElementById('custNote');
            if (noteEl) {
                noteEl.value = 'Tôi cần nhận báo giá sản phẩm: ' + productName;
                noteEl.focus();
            }
        }

        /* Xử lý gửi form báo giá không dùng alert() */
        function submitQuoteForm(e) {
            e.preventDefault();
            const name = document.getElementById('custName').value.trim();
            const phone = document.getElementById('custPhone').value.trim();
            const cat = document.getElementById('custCategory').value;
            const box = document.getElementById('quoteSuccessBox');
            const text = document.getElementById('quoteSuccessText');

            text.textContent = `Cảm ơn ${name} (${phone}). Yêu cầu báo giá mục "${cat}" đã được gửi tới Công ty TNHH Châu Nippo. Bộ phận kinh doanh sẽ liên hệ lại ngay qua SĐT/Zalo 0905.444.467!`;
            box.classList.remove('hidden');
            document.getElementById('quoteForm').reset();
        }

        /* Xử lý đóng/mở menu trên điện thoại */
        function toggleMobileMenu() {
            const menu = document.getElementById('mobileMenuDropdown');
            menu.classList.toggle('hidden');
        }

        /* Xử lý Banner Slider tự trượt 2 ảnh kích thước bằng nhau */
        let currentSlideIndex = 0;
        const slides = document.querySelectorAll('.banner-slide');
        const dots = document.querySelectorAll('.slide-dot');

        function showSlide(index) {
            currentSlideIndex = (index + slides.length) % slides.length;
            slides.forEach((slide, idx) => {
                if (idx === currentSlideIndex) {
                    slide.classList.remove('hidden');
                    slide.classList.add('block');
                } else {
                    slide.classList.remove('block');
                    slide.classList.add('hidden');
                }
            });
            dots.forEach((dot, idx) => {
                dot.className = idx === currentSlideIndex
                    ? 'slide-dot w-2.5 h-2.5 rounded-full bg-white transition'
                    : 'slide-dot w-2.5 h-2.5 rounded-full bg-white/40 transition';
            });
        }

        function changeSlide(step) {
            showSlide(currentSlideIndex + step);
        }

        function goToSlide(index) {
            showSlide(index);
        }

        window.onload = function () {
            renderProducts(productsData);
            setInterval(() => {
                changeSlide(1);
            }, 5500);
        };
    </script>
</body>
</html>
