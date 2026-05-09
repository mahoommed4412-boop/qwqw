
html_content = '''<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>نيرون - وكالة الأتمتة الذكية | أتمتة الأعمال بالذكاء الاصطناعي</title>
    <meta name="description" content="نيرون - وكالة متخصصة في أتمتة الأعمال بالذكاء الاصطناعي وواتساب. نوفر حلول أتمتة متكاملة للمتاجر والمطاعم والعيادات في السعودية والخليج.">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Cairo:wght@300;400;500;600;700;800;900&display=swap" rel="stylesheet">
    <script src="https://cdn.tailwindcss.com"></script>
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    fontFamily: {
                        cairo: ['Cairo', 'sans-serif'],
                    },
                    colors: {
                        navy: {
                            50: '#f0f4f8',
                            100: '#d9e2ec',
                            200: '#bcccdc',
                            300: '#9fb3c8',
                            400: '#829ab1',
                            500: '#627d98',
                            600: '#486581',
                            700: '#334e68',
                            800: '#243b53',
                            900: '#102a43',
                            950: '#0f172a',
                        },
                        teal: {
                            50: '#f0fdfa',
                            100: '#ccfbf1',
                            200: '#99f6e4',
                            300: '#5eead4',
                            400: '#2dd4bf',
                            500: '#14b8a6',
                            600: '#0d9488',
                            700: '#0f766e',
                            800: '#115e59',
                            900: '#134e4a',
                        },
                        emerald: {
                            50: '#ecfdf5',
                            100: '#d1fae5',
                            200: '#a7f3d0',
                            300: '#6ee7b7',
                            400: '#34d399',
                            500: '#10b981',
                            600: '#059669',
                            700: '#047857',
                            800: '#065f46',
                            900: '#064e3b',
                        },
                        warm: {
                            50: '#fffbeb',
                            100: '#fef3c7',
                            200: '#fde68a',
                            300: '#fcd34d',
                            400: '#fbbf24',
                            500: '#f59e0b',
                            600: '#d97706',
                            700: '#b45309',
                            800: '#92400e',
                            900: '#78350f',
                        }
                    }
                }
            }
        }
    </script>
    <style>
        * {
            font-family: 'Cairo', sans-serif;
        }
        
        html {
            scroll-behavior: smooth;
        }
        
        body {
            overflow-x: hidden;
        }
        
        /* Custom scrollbar */
        ::-webkit-scrollbar {
            width: 8px;
        }
        ::-webkit-scrollbar-track {
            background: #0f172a;
        }
        ::-webkit-scrollbar-thumb {
            background: #14b8a6;
            border-radius: 4px;
        }
        
        /* Animations */
        @keyframes float {
            0%, 100% { transform: translateY(0px); }
            50% { transform: translateY(-20px); }
        }
        
        @keyframes floatSlow {
            0%, 100% { transform: translateY(0px) rotate(0deg); }
            50% { transform: translateY(-15px) rotate(2deg); }
        }
        
        @keyframes pulse-glow {
            0%, 100% { box-shadow: 0 0 20px rgba(20, 184, 166, 0.3); }
            50% { box-shadow: 0 0 40px rgba(20, 184, 166, 0.6); }
        }
        
        @keyframes gradient-shift {
            0% { background-position: 0% 50%; }
            50% { background-position: 100% 50%; }
            100% { background-position: 0% 50%; }
        }
        
        @keyframes slideInUp {
            from {
                opacity: 0;
                transform: translateY(40px);
            }
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }
        
        @keyframes slideInRight {
            from {
                opacity: 0;
                transform: translateX(-40px);
            }
            to {
                opacity: 1;
                transform: translateX(0);
            }
        }
        
        @keyframes fadeIn {
            from { opacity: 0; }
            to { opacity: 1; }
        }
        
        @keyframes scaleIn {
            from {
                opacity: 0;
                transform: scale(0.9);
            }
            to {
                opacity: 1;
                transform: scale(1);
            }
        }
        
        @keyframes shimmer {
            0% { background-position: -1000px 0; }
            100% { background-position: 1000px 0; }
        }
        
        .animate-float {
            animation: float 6s ease-in-out infinite;
        }
        
        .animate-float-slow {
            animation: floatSlow 8s ease-in-out infinite;
        }
        
        .animate-pulse-glow {
            animation: pulse-glow 3s ease-in-out infinite;
        }
        
        .animate-gradient {
            background-size: 200% 200%;
            animation: gradient-shift 8s ease infinite;
        }
        
        .glass {
            background: rgba(255, 255, 255, 0.05);
            backdrop-filter: blur(20px);
            -webkit-backdrop-filter: blur(20px);
            border: 1px solid rgba(255, 255, 255, 0.1);
        }
        
        .glass-dark {
            background: rgba(15, 23, 42, 0.7);
            backdrop-filter: blur(20px);
            -webkit-backdrop-filter: blur(20px);
            border: 1px solid rgba(255, 255, 255, 0.05);
        }
        
        .text-gradient {
            background: linear-gradient(135deg, #14b8a6 0%, #10b981 50%, #2dd4bf 100%);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            background-clip: text;
        }
        
        .text-gradient-warm {
            background: linear-gradient(135deg, #f59e0b 0%, #fbbf24 100%);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            background-clip: text;
        }
        
        .bg-gradient-premium {
            background: linear-gradient(135deg, #0f172a 0%, #1e293b 50%, #0f172a 100%);
        }
        
        .bg-gradient-hero {
            background: radial-gradient(ellipse at top right, rgba(20, 184, 166, 0.15) 0%, transparent 50%),
                        radial-gradient(ellipse at bottom left, rgba(16, 185, 129, 0.1) 0%, transparent 50%),
                        #0f172a;
        }
        
        .bg-gradient-card {
            background: linear-gradient(145deg, rgba(20, 184, 166, 0.1) 0%, rgba(15, 23, 42, 0.9) 100%);
        }
        
        .hover-lift {
            transition: all 0.4s cubic-bezier(0.4, 0, 0.2, 1);
        }
        
        .hover-lift:hover {
            transform: translateY(-8px);
            box-shadow: 0 20px 40px rgba(20, 184, 166, 0.15);
        }
        
        .reveal {
            opacity: 0;
            transform: translateY(30px);
            transition: all 0.8s cubic-bezier(0.4, 0, 0.2, 1);
        }
        
        .reveal.active {
            opacity: 1;
            transform: translateY(0);
        }
        
        .reveal-delay-1 { transition-delay: 0.1s; }
        .reveal-delay-2 { transition-delay: 0.2s; }
        .reveal-delay-3 { transition-delay: 0.3s; }
        .reveal-delay-4 { transition-delay: 0.4s; }
        .reveal-delay-5 { transition-delay: 0.5s; }
        
        .nav-scrolled {
            background: rgba(15, 23, 42, 0.95) !important;
            backdrop-filter: blur(20px);
            box-shadow: 0 4px 30px rgba(0, 0, 0, 0.3);
        }
        
        .faq-answer {
            max-height: 0;
            overflow: hidden;
            transition: max-height 0.4s ease-out, padding 0.4s ease;
        }
        
        .faq-item.active .faq-answer {
            max-height: 500px;
        }
        
        .faq-item.active .faq-icon {
            transform: rotate(180deg);
        }
        
        .faq-icon {
            transition: transform 0.3s ease;
        }
        
        .blob {
            position: absolute;
            border-radius: 50%;
            filter: blur(80px);
            opacity: 0.4;
            pointer-events: none;
        }
        
        .gradient-border {
            position: relative;
            background: #0f172a;
            border-radius: 16px;
        }
        
        .gradient-border::before {
            content: '';
            position: absolute;
            inset: -2px;
            border-radius: 18px;
            background: linear-gradient(135deg, #14b8a6, #10b981, #2dd4bf);
            z-index: -1;
            opacity: 0.5;
        }
        
        .counter-value {
            font-variant-numeric: tabular-nums;
        }
        
        .whatsapp-float {
            position: fixed;
            bottom: 30px;
            left: 30px;
            z-index: 50;
            animation: pulse-glow 2s ease-in-out infinite;
        }
        
        @media (max-width: 768px) {
            .whatsapp-float {
                bottom: 20px;
                left: 20px;
            }
        }
        
        .service-card::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            right: 0;
            height: 3px;
            background: linear-gradient(90deg, #14b8a6, #10b981);
            transform: scaleX(0);
            transition: transform 0.4s ease;
        }
        
        .service-card:hover::before {
            transform: scaleX(1);
        }
        
        .timeline-line {
            position: absolute;
            right: 24px;
            top: 0;
            bottom: 0;
            width: 2px;
            background: linear-gradient(to bottom, #14b8a6, #10b981);
        }
        
        @media (min-width: 768px) {
            .timeline-line {
                right: 50%;
                transform: translateX(50%);
            }
        }
        
        .testimonial-card {
            transition: all 0.4s ease;
        }
        
        .testimonial-card:hover {
            transform: translateY(-5px);
        }
        
        .stat-card {
            position: relative;
            overflow: hidden;
        }
        
        .stat-card::after {
            content: '';
            position: absolute;
            top: -50%;
            left: -50%;
            width: 200%;
            height: 200%;
            background: linear-gradient(
                45deg,
                transparent 30%,
                rgba(255, 255, 255, 0.03) 50%,
                transparent 70%
            );
            transform: rotate(45deg);
            transition: all 0.6s;
        }
        
        .stat-card:hover::after {
            transform: rotate(45deg) translate(50%, 50%);
        }
        
        .mobile-menu {
            transform: translateX(100%);
            transition: transform 0.3s ease-in-out;
        }
        
        .mobile-menu.open {
            transform: translateX(0);
        }
    </style>
</head>
<body class="bg-navy-950 text-white font-cairo antialiased">

    <!-- Navbar -->
    <nav id="navbar" class="fixed top-0 left-0 right-0 z-50 transition-all duration-300 bg-transparent">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex items-center justify-between h-20">
                <!-- Logo -->
                <a href="#" class="flex items-center gap-3 group">
                    <div class="w-10 h-10 rounded-xl bg-gradient-to-br from-teal-400 to-emerald-500 flex items-center justify-center shadow-lg shadow-teal-500/20 group-hover:shadow-teal-500/40 transition-all">
                        <svg class="w-6 h-6 text-white" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M13 10V3L4 14h7v7l9-11h-7z"/>
                        </svg>
                    </div>
                    <span class="text-2xl font-bold text-white">نيرون</span>
                </a>
                
                <!-- Desktop Navigation -->
                <div class="hidden lg:flex items-center gap-8">
                    <a href="#services" class="text-gray-300 hover:text-teal-400 transition-colors font-medium">خدماتنا</a>
                    <a href="#how-it-works" class="text-gray-300 hover:text-teal-400 transition-colors font-medium">كيف نعمل</a>
                    <a href="#benefits" class="text-gray-300 hover:text-teal-400 transition-colors font-medium">المميزات</a>
                    <a href="#testimonials" class="text-gray-300 hover:text-teal-400 transition-colors font-medium">آراء العملاء</a>
                    <a href="#faq" class="text-gray-300 hover:text-teal-400 transition-colors font-medium">الأسئلة الشائعة</a>
                </div>
                
                <!-- CTA Buttons -->
                <div class="hidden lg:flex items-center gap-4">
                    <a href="https://wa.me/966500000000" target="_blank" class="px-6 py-2.5 rounded-full border border-teal-500/30 text-teal-400 hover:bg-teal-500/10 transition-all font-semibold text-sm">
                        تواصل معنا
                    </a>
                    <a href="#contact" class="px-6 py-2.5 rounded-full bg-gradient-to-r from-teal-500 to-emerald-500 text-white hover:shadow-lg hover:shadow-teal-500/25 transition-all font-semibold text-sm animate-pulse-glow">
                        جرب مجاناً
                    </a>
                </div>
                
                <!-- Mobile Menu Button -->
                <button id="mobile-menu-btn" class="lg:hidden p-2 rounded-lg hover:bg-white/10 transition-colors">
                    <svg class="w-6 h-6 text-white" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16M4 18h16"/>
                    </svg>
                </button>
            </div>
        </div>
        
        <!-- Mobile Menu -->
        <div id="mobile-menu" class="mobile-menu fixed top-0 right-0 h-full w-80 bg-navy-900/98 backdrop-blur-xl z-50 p-8 lg:hidden">
            <button id="close-menu" class="absolute top-6 left-6 p-2 rounded-lg hover:bg-white/10 transition-colors">
                <svg class="w-6 h-6 text-white" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M6 18L18 6M6 6l12 12"/>
                </svg>
            </button>
            <div class="flex flex-col gap-6 mt-16">
                <a href="#services" class="text-xl text-gray-300 hover:text-teal-400 transition-colors font-semibold mobile-link">خدماتنا</a>
                <a href="#how-it-works" class="text-xl text-gray-300 hover:text-teal-400 transition-colors font-semibold mobile-link">كيف نعمل</a>
                <a href="#benefits" class="text-xl text-gray-300 hover:text-teal-400 transition-colors font-semibold mobile-link">المميزات</a>
                <a href="#testimonials" class="text-xl text-gray-300 hover:text-teal-400 transition-colors font-semibold mobile-link">آراء العملاء</a>
                <a href="#faq" class="text-xl text-gray-300 hover:text-teal-400 transition-colors font-semibold mobile-link">الأسئلة الشائعة</a>
                <a href="#contact" class="mt-4 px-6 py-3 rounded-full bg-gradient-to-r from-teal-500 to-emerald-500 text-white text-center font-bold mobile-link">
                    جرب مجاناً لـ 3 أيام
                </a>
            </div>
        </div>
    </nav>

    <!-- Hero Section -->
    <section class="relative min-h-screen flex items-center bg-gradient-hero overflow-hidden pt-20">
        <!-- Background Blobs -->
        <div class="blob w-96 h-96 bg-teal-500/20 top-20 -left-48 animate-float"></div>
        <div class="blob w-80 h-80 bg-emerald-500/15 bottom-20 -right-40 animate-float-slow"></div>
        <div class="blob w-64 h-64 bg-warm-500/10 top-1/2 left-1/3 animate-float"></div>
        
        <!-- Grid Pattern -->
        <div class="absolute inset-0 opacity-[0.03]" style="background-image: radial-gradient(circle, #fff 1px, transparent 1px); background-size: 50px 50px;"></div>
        
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 py-20 relative z-10">
            <div class="grid lg:grid-cols-2 gap-12 lg:gap-16 items-center">
                <!-- Content -->
                <div class="text-center lg:text-right">
                    <!-- Badge -->
                    <div class="reveal inline-flex items-center gap-2 px-4 py-2 rounded-full glass border-teal-500/20 mb-8">
                        <span class="w-2 h-2 rounded-full bg-emerald-400 animate-pulse"></span>
                        <span class="text-teal-300 text-sm font-semibold">تجربة مجانية لمدة 3 أيام بدون التزام</span>
                    </div>
                    
                    <!-- Headline -->
                    <h1 class="reveal reveal-delay-1 text-4xl sm:text-5xl lg:text-6xl xl:text-7xl font-black leading-tight mb-6">
                        <span class="text-white">أتمتة ذكية</span>
                        <br>
                        <span class="text-gradient">تُحدث ثورة</span>
                        <br>
                        <span class="text-white">في أعمالك</span>
                    </h1>
                    
                    <!-- Subheadline -->
                    <p class="reveal reveal-delay-2 text-lg sm:text-xl text-gray-400 leading-relaxed mb-10 max-w-2xl mx-auto lg:mx-0">
                        نوفر لك حلول أتمتة متكاملة بالذكاء الاصطناعي وواتساب. أتمت عملياتك، تواصل مع عملائك تلقائياً، وزد مبيعاتك بينما أنت نائم.
                    </p>
                    
                    <!-- CTAs -->
                    <div class="reveal reveal-delay-3 flex flex-col sm:flex-row gap-4 justify-center lg:justify-start mb-12">
                        <a href="https://wa.me/966500000000" target="_blank" class="group px-8 py-4 rounded-full bg-gradient-to-r from-teal-500 to-emerald-500 text-white font-bold text-lg hover:shadow-2xl hover:shadow-teal-500/30 transition-all flex items-center justify-center gap-3 animate-pulse-glow">
                            <svg class="w-6 h-6" fill="currentColor" viewBox="0 0 24 24">
                                <path d="M17.472 14.382c-.297-.149-1.758-.867-2.03-.967-.273-.099-.471-.148-.67.15-.197.297-.767.966-.94 1.164-.173.199-.347.223-.644.075-.297-.15-1.255-.463-2.39-1.475-.883-.788-1.48-1.761-1.653-2.059-.173-.297-.018-.458.13-.606.134-.133.298-.347.446-.52.149-.174.198-.298.298-.497.099-.198.05-.371-.025-.52-.075-.149-.669-1.612-.916-2.207-.242-.579-.487-.5-.669-.51-.173-.008-.371-.01-.57-.01-.198 0-.52.074-.792.372-.272.297-1.04 1.016-1.04 2.479 0 1.462 1.065 2.875 1.213 3.074.149.198 2.096 3.2 5.077 4.487.709.306 1.262.489 1.694.625.712.227 1.36.195 1.871.118.571-.085 1.758-.719 2.006-1.413.248-.694.248-1.289.173-1.413-.074-.124-.272-.198-.57-.347m-5.421 7.403h-.004a9.87 9.87 0 01-5.031-1.378l-.361-.214-3.741.982.998-3.648-.235-.374a9.86 9.86 0 01-1.51-5.26c.001-5.45 4.436-9.884 9.888-9.884 2.64 0 5.122 1.03 6.988 2.898a9.825 9.825 0 012.893 6.994c-.003 5.45-4.437 9.884-9.885 9.884m8.413-18.297A11.815 11.815 0 0012.05 0C5.495 0 .16 5.335.157 11.892c0 2.096.547 4.142 1.588 5.945L.057 24l6.305-1.654a11.882 11.882 0 005.683 1.448h.005c6.554 0 11.89-5.335 11.893-11.893a11.821 11.821 0 00-3.48-8.413z"/>
                            </svg>
                            ابدأ الآن عبر واتساب
                        </a>
                        <a href="#how-it-works" class="px-8 py-4 rounded-full border border-gray-600 text-white font-bold text-lg hover:border-teal-500 hover:text-teal-400 transition-all flex items-center justify-center gap-2">
                            <svg class="w-5 h-5" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M14.752 11.168l-3.197-2.132A1 1 0 0010 9.87v4.263a1 1 0 001.555.832l3.197-2.132a1 1 0 000-1.664z"/>
                                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M21 12a9 9 0 11-18 0 9 9 0 0118 0z"/>
                            </svg>
                            شاهد كيف يعمل
                        </a>
                    </div>
                    
                    <!-- Trust Indicators -->
                    <div class="reveal reveal-delay-4 flex flex-wrap items-center gap-6 justify-center lg:justify-start">
                        <div class="flex items-center gap-2 text-gray-400 text-sm">
                            <svg class="w-5 h-5 text-emerald-400" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 13l4 4L19 7"/>
                            </svg>
                            <span>بدون بطاقة ائتمان</span>
                        </div>
                        <div class="flex items-center gap-2 text-gray-400 text-sm">
                            <svg class="w-5 h-5 text-emerald-400" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 13l4 4L19 7"/>
                            </svg>
                            <span>إلغاء فوري في أي وقت</span>
                        </div>
                        <div class="flex items-center gap-2 text-gray-400 text-sm">
                            <svg class="w-5 h-5 text-emerald-400" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 13l4 4L19 7"/>
                            </svg>
                            <span>دعم فني على مدار الساعة</span>
                        </div>
                    </div>
                </div>
                
                <!-- Visual -->
                <div class="relative hidden lg:block">
                    <!-- Main Dashboard Card -->
                    <div class="reveal reveal-delay-2 relative z-10 glass rounded-2xl p-6 border-teal-500/20 shadow-2xl shadow-teal-500/10">
                        <div class="flex items-center justify-between mb-6">
                            <div class="flex items-center gap-3">
                                <div class="w-10 h-10 rounded-xl bg-gradient-to-br from-teal-400 to-emerald-500 flex items-center justify-center">
                                    <svg class="w-5 h-5 text-white" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                                        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M13 10V3L4 14h7v7l9-11h-7z"/>
                                    </svg>
                                </div>
                                <div>
                                    <div class="text-white font-bold">لوحة التحكم الذكية</div>
                                    <div class="text-gray-400 text-xs">نظام الأتمتة المتكامل</div>
                                </div>
                            </div>
                            <div class="flex items-center gap-2">
                                <span class="w-2 h-2 rounded-full bg-emerald-400 animate-pulse"></span>
                                <span class="text-emerald-400 text-xs font-semibold">متصل</span>
                            </div>
                        </div>
                        
                        <!-- Stats Row -->
                        <div class="grid grid-cols-3 gap-4 mb-6">
                            <div class="bg-white/5 rounded-xl p-4 text-center">
                                <div class="text-2xl font-bold text-teal-400">+147%</div>
                                <div class="text-gray-400 text-xs mt-1">زيادة المبيعات</div>
                            </div>
                            <div class="bg-white/5 rounded-xl p-4 text-center">
                                <div class="text-2xl font-bold text-emerald-400">2.4ث</div>
                                <div class="text-gray-400 text-xs mt-1">متوسط الرد</div>
                            </div>
                            <div class="bg-white/5 rounded-xl p-4 text-center">
                                <div class="text-2xl font-bold text-warm-400">98%</div>
                                <div class="text-gray-400 text-xs mt-1">رضا العملاء</div>
                            </div>
                        </div>
                        
                        <!-- Chat Preview -->
                        <div class="bg-white/5 rounded-xl p-4 space-y-3">
                            <div class="flex items-start gap-3">
                                <div class="w-8 h-8 rounded-full bg-teal-500/20 flex items-center justify-center flex-shrink-0">
                                    <svg class="w-4 h-4 text-teal-400" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                                        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9.75 17L9 20l-1 1h8l-1-1-.75-3M3 13h18M5 17h14a2 2 0 002-2V5a2 2 0 00-2-2H5a2 2 0 00-2 2v10a2 2 0 002 2z"/>
                                    </svg>
                                </div>
                                <div class="flex-1">
                                    <div class="text-white text-sm font-medium">الذكاء الاصطناعي</div>
                                    <div class="text-gray-400 text-xs">مرحباً! كيف يمكنني مساعدتك في طلبك اليوم؟</div>
                                </div>
                                <span class="text-gray-500 text-xs">الآن</span>
                            </div>
                            <div class="flex items-start gap-3">
                                <div class="w-8 h-8 rounded-full bg-warm-500/20 flex items-center justify-center flex-shrink-0">
                                    <svg class="w-4 h-4 text-warm-400" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                                        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M16 11V7a4 4 0 00-8 0v4M5 9h14l1 12H4L5 9z"/>
                                    </svg>
                                </div>
                                <div class="flex-1">
                                    <div class="text-white text-sm font-medium">طلب جديد #2847</div>
                                    <div class="text-gray-400 text-xs">تم تأكيد الطلب وإرساله تلقائياً للمستودع</div>
                                </div>
                                <span class="text-gray-500 text-xs">قبل دقيقة</span>
                            </div>
                            <div class="flex items-start gap-3">
                                <div class="w-8 h-8 rounded-full bg-emerald-500/20 flex items-center justify-center flex-shrink-0">
                                    <svg class="w-4 h-4 text-emerald-400" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                                        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 8l7.89 5.26a2 2 0 002.22 0L21 8M5 19h14a2 2 0 002-2V7a2 2 0 00-2-2H5a2 2 0 00-2 2v10a2 2 0 002 2z"/>
                                    </svg>
                                </div>
                                <div class="flex-1">
                                    <div class="text-white text-sm font-medium">متابعة تلقائية</div>
                                    <div class="text-gray-400 text-xs">تم إرسال رسالة المتابعة للعميل أحمد</div>
                                </div>
                                <span class="text-gray-500 text-xs">قبل 5 دقائق</span>
                            </div>
                        </div>
                    </div>
                    
                    <!-- Floating Cards -->
                    <div class="absolute -top-8 -right-8 glass rounded-xl p-4 animate-float border-teal-500/20 shadow-xl">
                        <div class="flex items-center gap-3">
                            <div class="w-10 h-10 rounded-full bg-emerald-500/20 flex items-center justify-center">
                                <svg class="w-5 h-5 text-emerald-400" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 12l2 2 4-4m6 2a9 9 0 11-18 0 9 9 0 0118 0z"/>
                                </svg>
                            </div>
                            <div>
                                <div class="text-white font-bold text-sm">تم الأتمتة</div>
                                <div class="text-gray-400 text-xs">1,247 عملية</div>
                            </div>
                        </div>
                    </div>
                    
                    <div class="absolute -bottom-6 -left-6 glass rounded-xl p-4 animate-float-slow border-warm-500/20 shadow-xl">
                        <div class="flex items-center gap-3">
                            <div class="w-10 h-10 rounded-full bg-warm-500/20 flex items-center justify-center">
                                <svg class="w-5 h-5 text-warm-400" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 8c-1.657 0-3 .895-3 2s1.343 2 3 2 3 .895 3 2-1.343 2-3 2m0-8c1.11 0 2.08.402 2.599 1M12 8V7m0 1v8m0 0v1m0-1c-1.11 0-2.08-.402-2.599-1M21 12a9 9 0 11-18 0 9 9 0 0118 0z"/>
                                </svg>
                            </div>
                            <div>
                                <div class="text-white font-bold text-sm">توفير</div>
                                <div class="text-gray-400 text-xs">42 ساعة/شهر</div>
                            </div>
                        </div>
                    </div>
                    
                    <div class="absolute top-1/2 -left-12 glass rounded-xl p-3 animate-float border-emerald-500/20 shadow-xl">
                        <div class="flex items-center gap-2">
                            <div class="w-8 h-8 rounded-full bg-teal-500/20 flex items-center justify-center">
                                <svg class="w-4 h-4 text-teal-400" fill="currentColor" viewBox="0 0 24 24">
                                    <path d="M17.472 14.382c-.297-.149-1.758-.867-2.03-.967-.273-.099-.471-.148-.67.15-.197.297-.767.966-.94 1.164-.173.199-.347.223-.644.075-.297-.15-1.255-.463-2.39-1.475-.883-.788-1.48-1.761-1.653-2.059-.173-.297-.018-.458.13-.606.134-.133.298-.347.446-.52.149-.174.198-.298.298-.497.099-.198.05-.371-.025-.52-.075-.149-.669-1.612-.916-2.207-.242-.579-.487-.5-.669-.51-.173-.008-.371-.01-.57-.01-.198 0-.52.074-.792.372-.272.297-1.04 1.016-1.04 2.479 0 1.462 1.065 2.875 1.213 3.074.149.198 2.096 3.2 5.077 4.487.709.306 1.262.489 1.694.625.712.227 1.36.195 1.871.118.571-.085 1.758-.719 2.006-1.413.248-.694.248-1.289.173-1.413-.074-.124-.272-.198-.57-.347m-5.421 7.403h-.004a9.87 9.87 0 01-5.031-1.378l-.361-.214-3.741.982.998-3.648-.235-.374a9.86 9.86 0 01-1.51-5.26c.001-5.45 4.436-9.884 9.888-9.884 2.64 0 5.122 1.03 6.988 2.898a9.825 9.825 0 012.893 6.994c-.003 5.45-4.437 9.884-9.885 9.884m8.413-18.297A11.815 11.815 0 0012.05 0C5.495 0 .16 5.335.157 11.892c0 2.096.547 4.142 1.588 5.945L.057 24l6.305-1.654a11.882 11.882 0 005.683 1.448h.005c6.554 0 11.89-5.335 11.893-11.893a11.821 11.821 0 00-3.48-8.413z"/>
                                </svg>
                            </div>
                            <div class="text-white text-xs font-bold">واتساب ذكي</div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
        
        <!-- Bottom Gradient Fade -->
        <div class="absolute bottom-0 left-0 right-0 h-32 bg-gradient-to-t from-navy-950 to-transparent"></div>
    </section>

    <!-- Stats Section -->
    <section class="py-16 relative">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="grid grid-cols-2 lg:grid-cols-4 gap-6">
                <div class="reveal stat-card glass rounded-2xl p-6 text-center border-teal-500/10">
                    <div class="text-3xl sm:text-4xl font-black text-gradient mb-2 counter-value" data-target="500">0</div>
                    <div class="text-gray-400 text-sm">عميل نشط</div>
                </div>
                <div class="reveal reveal-delay-1 stat-card glass rounded-2xl p-6 text-center border-teal-500/10">
                    <div class="text-3xl sm:text-4xl font-black text-gradient mb-2 counter-value" data-target="98">0</div>
                    <div class="text-gray-400 text-sm">% معدل الرضا</div>
                </div>
                <div class="reveal reveal-delay-2 stat-card glass rounded-2xl p-6 text-center border-teal-500/10">
                    <div class="text-3xl sm:text-4xl font-black text-gradient mb-2 counter-value" data-target="12">0</div>
                    <div class="text-gray-400 text-sm">مليون رسالة أتمتة</div>
                </div>
                <div class="reveal reveal-delay-3 stat-card glass rounded-2xl p-6 text-center border-teal-500/10">
                    <div class="text-3xl sm:text-4xl font-black text-gradient mb-2 counter-value" data-target="24">0</div>
                    <div class="text-gray-400 text-sm">/7 دعم فني</div>
                </div>
            </div>
        </div>
    </section>

    <!-- Problem Section -->
    <section id="problem" class="py-24 relative overflow-hidden">
        <div class="blob w-72 h-72 bg-red-500/5 top-0 right-0"></div>
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 relative z-10">
            <div class="text-center mb-16">
                <span class="reveal inline-block px-4 py-1.5 rounded-full bg-red-500/10 text-red-400 text-sm font-semibold mb-4">المشكلة</span>
                <h2 class="reveal reveal-delay-1 text-3xl sm:text-4xl lg:text-5xl font-black text-white mb-6">
                    هل تواجه هذه التحديات<br>في عملك؟
                </h2>
                <p class="reveal reveal-delay-2 text-gray-400 text-lg max-w-2xl mx-auto">
                    معظم أصحاب الأعمال في السعودية يفقدون فرصاً ذهبية يومياً بسبب العمليات اليدوية
                </p>
            </div>
            
            <div class="grid md:grid-cols-2 lg:grid-cols-3 gap-6">
                <div class="reveal glass rounded-2xl p-6 border-red-500/10 hover:border-red-500/30 transition-all hover-lift">
                    <div class="w-12 h-12 rounded-xl bg-red-500/10 flex items-center justify-center mb-4">
                        <svg class="w-6 h-6 text-red-400" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 8v4m0 4h.01M21 12a9 9 0 11-18 0 9 9 0 0118 0z"/>
                        </svg>
                    </div>
                    <h3 class="text-white font-bold text-lg mb-2">فقدان الطلبات</h3>
                    <p class="text-gray-400 text-sm leading-relaxed">تفوتك طلبات مهمة بسبب التأخر في الرد أو عدم المتابعة مع العملاء المحتملين في الوقت المناسب</p>
                </div>
                
                <div class="reveal reveal-delay-1 glass rounded-2xl p-6 border-red-500/10 hover:border-red-500/30 transition-all hover-lift">
                    <div class="w-12 h-12 rounded-xl bg-red-500/10 flex items-center justify-center mb-4">
                        <svg class="w-6 h-6 text-red-400" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 8v4l3 3m6-3a9 9 0 11-18 0 9 9 0 0118 0z"/>
                        </svg>
                    </div>
                    <h3 class="text-white font-bold text-lg mb-2">إهدار الوقت</h3>
                    <p class="text-gray-400 text-sm leading-relaxed">تقضي ساعات طويلة يومياً في مهام روتينية يمكن أتمتتها بذكاء مثل الردود والمتابعات والتقارير</p>
                </div>
                
                <div class="reveal reveal-delay-2 glass rounded-2xl p-6 border-red-500/10 hover:border-red-500/30 transition-all hover-lift">
                    <div class="w-12 h-12 rounded-xl bg-red-500/10 flex items-center justify-center mb-4">
                        <svg class="w-6 h-6 text-red-400" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M17 20h5v-2a3 3 0 00-5.356-1.857M17 20H7m10 0v-2c0-.656-.126-1.283-.356-1.857M7 20H2v-2a3 3 0 015.356-1.857M7 20v-2c0-.656.126-1.283.356-1.857m0 0a5.002 5.002 0 019.288 0M15 7a3 3 0 11-6 0 3 3 0 016 0zm6 3a2 2 0 11-4 0 2 2 0 014 0zM7 10a2 2 0 11-4 0 2 2 0 014 0z"/>
                        </svg>
                    </div>
                    <h3 class="text-white font-bold text-lg mb-2">ضعف التواصل</h3>
                    <p class="text-gray-400 text-sm leading-relaxed">عملاؤك ينتظرون ردوداً سريعة ولكن فريقك غير قادر على التعامل مع كل الاستفسارات في وقت واحد</p>
                </div>
                
                <div class="reveal glass rounded-2xl p-6 border-red-500/10 hover:border-red-500/30 transition-all hover-lift">
                    <div class="w-12 h-12 rounded-xl bg-red-500/10 flex items-center justify-center mb-4">
                        <svg class="w-6 h-6 text-red-400" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 19v-6a2 2 0 00-2-2H5a2 2 0 00-2 2v6a2 2 0 002 2h2a2 2 0 002-2zm0 0V9a2 2 0 012-2h2a2 2 0 012 2v10m-6 0a2 2 0 002 2h2a2 2 0 002-2m0 0V5a2 2 0 012-2h2a2 2 0 012 2v14a2 2 0 01-2 2h-2a2 2 0 01-2-2z"/>
                        </svg>
                    </div>
                    <h3 class="text-white font-bold text-lg mb-2">غياب البيانات</h3>
                    <p class="text-gray-400 text-sm leading-relaxed">لا تمتلك رؤية واضحة لأداء عملك بسبب عدم وجود تقارير ولوحات تحكم ذكية وتحليلات فورية</p>
                </div>
                
                <div class="reveal reveal-delay-1 glass rounded-2xl p-6 border-red-500/10 hover:border-red-500/30 transition-all hover-lift">
                    <div class="w-12 h-12 rounded-xl bg-red-500/10 flex items-center justify-center mb-4">
                        <svg class="w-6 h-6 text-red-400" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M13 7h8m0 0v8m0-8l-8 8-4-4-6 6"/>
                        </svg>
                    </div>
                    <h3 class="text-white font-bold text-lg mb-2">صعوبة التوسع</h3>
                    <p class="text-gray-400 text-sm leading-relaxed">كلما زاد عدد عملائك، زادت المشاكل التشغيلية وصعب عليك توسيع نطاق عملك بكفاءة</p>
                </div>
                
                <div class="reveal reveal-delay-2 glass rounded-2xl p-6 border-red-500/10 hover:border-red-500/30 transition-all hover-lift">
                    <div class="w-12 h-12 rounded-xl bg-red-500/10 flex items-center justify-center mb-4">
                        <svg class="w-6 h-6 text-red-400" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 8c-1.657 0-3 .895-3 2s1.343 2 3 2 3 .895 3 2-1.343 2-3 2m0-8c1.11 0 2.08.402 2.599 1M12 8V7m0 1v8m0 0v1m0-1c-1.11 0-2.08-.402-2.599-1M21 12a9 9 0 11-18 0 9 9 0 0118 0z"/>
                        </svg>
                    </div>
                    <h3 class="text-white font-bold text-lg mb-2">تكاليف مرتفعة</h3>
                    <p class="text-gray-400 text-sm leading-relaxed">تدفع رواتب عالية لموظفين يقومون بمهام يمكن للذكاء الاصطناعي إنجازها بكفاءة أعلى وتكلفة أقل</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Solution Section -->
    <section id="solution" class="py-24 relative overflow-hidden">
        <div class="blob w-96 h-96 bg-teal-500/10 -bottom-48 -left-48"></div>
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 relative z-10">
            <div class="grid lg:grid-cols-2 gap-16 items-center">
                <div class="order-2 lg:order-1">
                    <span class="reveal inline-block px-4 py-1.5 rounded-full bg-teal-500/10 text-teal-400 text-sm font-semibold mb-4">الحل</span>
                    <h2 class="reveal reveal-delay-1 text-3xl sm:text-4xl lg:text-5xl font-black text-white mb-6 leading-tight">
                        نيرون يحول<br>
                        <span class="text-gradient">عملك التقليدي</span><br>
                        إلى آلة ربحية
                    </h2>
                    <p class="reveal reveal-delay-2 text-gray-400 text-lg leading-relaxed mb-8">
                        نبني لك نظام أتمتة ذكي متكامل يعمل على مدار الساعة دون توقف. من الرد الآلي على واتساب إلى إدارة الطلبات والمتابعة التلقائية، نغطي كل جانب من جوانب عملك.
                    </p>
                    
                    <div class="space-y-4">
                        <div class="reveal reveal-delay-3 flex items-start gap-4">
                            <div class="w-6 h-6 rounded-full bg-teal-500/20 flex items-center justify-center flex-shrink-0 mt-1">
                                <svg class="w-4 h-4 text-teal-400" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 13l4 4L19 7"/>
                                </svg>
                            </div>
                            <div>
                                <h4 class="text-white font-bold mb-1">رد آلي ذكي على واتساب</h4>
                                <p class="text-gray-400 text-sm">الذكاء الاصطناعي يرد على عملائك فوراً وعلى مدار الساعة بشكل طبيعي ومهني</p>
                            </div>
                        </div>
                        
                        <div class="reveal reveal-delay-3 flex items-start gap-4">
                            <div class="w-6 h-6 rounded-full bg-teal-500/20 flex items-center justify-center flex-shrink-0 mt-1">
                                <svg class="w-4 h-4 text-teal-400" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 13l4 4L19 7"/>
                                </svg>
                            </div>
                            <div>
                                <h4 class="text-white font-bold mb-1">أتمتة كاملة لمتجر سلة</h4>
                                <p class="text-gray-400 text-sm">ربط مباشر مع متجرك على سلة لأتمتة الطلبات والمخزون والإشعارات</p>
                            </div>
                        </div>
                        
                        <div class="reveal reveal-delay-4 flex items-start gap-4">
                            <div class="w-6 h-6 rounded-full bg-teal-500/20 flex items-center justify-center flex-shrink-0 mt-1">
                                <svg class="w-4 h-4 text-teal-400" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 13l4 4L19 7"/>
                                </svg>
                            </div>
                            <div>
                                <h4 class="text-white font-bold mb-1">متابعة تلقائية للعملاء</h4>
                                <p class="text-gray-400 text-sm">نظام متابعة ذكي يتواصل مع العملاء تلقائياً في كل مرحلة من مراحل رحلتهم</p>
                            </div>
                        </div>
                        
                        <div class="reveal reveal-delay-4 flex items-start gap-4">
                            <div class="w-6 h-6 rounded-full bg-teal-500/20 flex items-center justify-center flex-shrink-0 mt-1">
                                <svg class="w-4 h-4 text-teal-400" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 13l4 4L19 7"/>
                                </svg>
                            </div>
                            <div>
                                <h4 class="text-white font-bold mb-1">تقارير ولوحات تحكم ذكية</h4>
                                <p class="text-gray-400 text-sm">رؤية شاملة لأداء عملك مع إحصائيات فورية وتحليلات متقدمة</p>
                            </div>
                        </div>
                    </div>
                </div>
                
                <div class="order-1 lg:order-2 relative">
                    <div class="reveal relative">
                        <div class="absolute inset-0 bg-gradient-to-r from-teal-500/20 to-emerald-500/20 rounded-3xl blur-3xl"></div>
                        <div class="relative glass rounded-3xl p-8 border-teal-500/20">
                            <div class="flex items-center justify-between mb-8">
                                <div class="text-white font-bold text-lg">قبل وبعد الأتمتة</div>
                                <div class="flex items-center gap-2">
                                    <span class="w-3 h-3 rounded-full bg-red-400"></span>
                                    <span class="w-3 h-3 rounded-full bg-warm-400"></span>
                                    <span class="w-3 h-3 rounded-full bg-emerald-400"></span>
                                </div>
                            </div>
                            
                            <!-- Before -->
                            <div class="mb-6">
                                <div class="flex items-center gap-2 mb-3">
                                    <span class="px-3 py-1 rounded-full bg-red-500/20 text-red-400 text-xs font-bold">قبل</span>
                                </div>
                                <div class="space-y-2">
                                    <div class="flex items-center justify-between bg-red-500/5 rounded-lg p-3">
                                        <span class="text-gray-400 text-sm">متوسط وقت الرد</span>
                                        <span class="text-red-400 font-bold">45 دقيقة</span>
                                    </div>
                                    <div class="flex items-center justify-between bg-red-500/5 rounded-lg p-3">
                                        <span class="text-gray-400 text-sm">الطلبات المفقودة</span>
                                        <span class="text-red-400 font-bold">23% شهرياً</span>
                                    </div>
                                    <div class="flex items-center justify-between bg-red-500/5 rounded-lg p-3">
                                        <span class="text-gray-400 text-sm">ساعات العمل اليدوي</span>
                                        <span class="text-red-400 font-bold">60+ ساعة/أسبوع</span>
                                    </div>
                                </div>
                            </div>
                            
                            <!-- Arrow -->
                            <div class="flex justify-center my-4">
                                <svg class="w-8 h-8 text-teal-400 animate-bounce" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 14l-7 7m0 0l-7-7m7 7V3"/>
                                </svg>
                            </div>
                            
                            <!-- After -->
                            <div>
                                <div class="flex items-center gap-2 mb-3">
                                    <span class="px-3 py-1 rounded-full bg-emerald-500/20 text-emerald-400 text-xs font-bold">بعد</span>
                                </div>
                                <div class="space-y-2">
                                    <div class="flex items-center justify-between bg-emerald-500/5 rounded-lg p-3">
                                        <span class="text-gray-400 text-sm">متوسط وقت الرد</span>
                                        <span class="text-emerald-400 font-bold">2.4 ثانية</span>
                                    </div>
                                    <div class="flex items-center justify-between bg-emerald-500/5 rounded-lg p-3">
                                        <span class="text-gray-400 text-sm">الطلبات المفقودة</span>
                                        <span class="text-emerald-400 font-bold">0%</span>
                                    </div>
                                    <div class="flex items-center justify-between bg-emerald-500/5 rounded-lg p-3">
                                        <span class="text-gray-400 text-sm">ساعات العمل اليدوي</span>
                                        <span class="text-emerald-400 font-bold">5 ساعات/أسبوع</span>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Services Section -->
    <section id="services" class="py-24 relative">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center mb-16">
                <span class="reveal inline-block px-4 py-1.5 rounded-full bg-teal-500/10 text-teal-400 text-sm font-semibold mb-4">خدماتنا</span>
                <h2 class="reveal reveal-delay-1 text-3xl sm:text-4xl lg:text-5xl font-black text-white mb-6">
                    حلول أتمتة <span class="text-gradient">شاملة ومتكاملة</span>
                </h2>
                <p class="reveal reveal-delay-2 text-gray-400 text-lg max-w-2xl mx-auto">
                    نقدم لك مجموعة متكاملة من خدمات الأتمتة الذكية المصممة خصيصاً لأعمال السعودية والخليج
                </p>
            </div>
            
            <div class="grid md:grid-cols-2 lg:grid-cols-3 gap-6">
                <!-- Service 1 -->
                <div class="reveal service-card relative glass rounded-2xl p-6 border-teal-500/10 hover-lift overflow-hidden group">
                    <div class="w-14 h-14 rounded-2xl bg-gradient-to-br from-teal-400/20 to-emerald-500/20 flex items-center justify-center mb-5 group-hover:scale-110 transition-transform">
                        <svg class="w-7 h-7 text-teal-400" fill="currentColor" viewBox="0 0 24 24">
                            <path d="M17.472 14.382c-.297-.149-1.758-.867-2.03-.967-.273-.099-.471-.148-.67.15-.197.297-.767.966-.94 1.164-.173.199-.347.223-.644.075-.297-.15-1.255-.463-2.39-1.475-.883-.788-1.48-1.761-1.653-2.059-.173-.297-.018-.458.13-.606.134-.133.298-.347.446-.52.149-.174.198-.298.298-.497.099-.198.05-.371-.025-.52-.075-.149-.669-1.612-.916-2.207-.242-.579-.487-.5-.669-.51-.173-.008-.371-.01-.57-.01-.198 0-.52.074-.792.372-.272.297-1.04 1.016-1.04 2.479 0 1.462 1.065 2.875 1.213 3.074.149.198 2.096 3.2 5.077 4.487.709.306 1.262.489 1.694.625.712.227 1.36.195 1.871.118.571-.085 1.758-.719 2.006-1.413.248-.694.248-1.289.173-1.413-.074-.124-.272-.198-.57-.347m-5.421 7.403h-.004a9.87 9.87 0 01-5.031-1.378l-.361-.214-3.741.982.998-3.648-.235-.374a9.86 9.86 0 01-1.51-5.26c.001-5.45 4.436-9.884 9.888-9.884 2.64 0 5.122 1.03 6.988 2.898a9.825 9.825 0 012.893 6.994c-.003 5.45-4.437 9.884-9.885 9.884m8.413-18.297A11.815 11.815 0 0012.05 0C5.495 0 .16 5.335.157 11.892c0 2.096.547 4.142 1.588 5.945L.057 24l6.305-1.654a11.882 11.882 0 005.683 1.448h.005c6.554 0 11.89-5.335 11.893-11.893a11.821 11.821 0 00-3.48-8.413z"/>
                        </svg>
                    </div>
                    <h3 class="text-white font-bold text-xl mb-3">أتمتة واتساب</h3>
                    <p class="text-gray-400 text-sm leading-relaxed mb-4">ردود آلية ذكية على واتساب تعمل على مدار الساعة. رد فوري، مهني، وذكي يفهم احتياجات عملائك.</p>
                    <div class="flex items-center gap-2 text-teal-400 text-sm font-semibold">
                        <span>اكتشف المزيد</span>
                        <svg class="w-4 h-4 group-hover:-translate-x-1 transition-transform" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M17 8l4 4m0 0l-4 4m4-4H3"/>
                        </svg>
                    </div>
                </div>
                
                <!-- Service 2 -->
                <div class="reveal reveal-delay-1 service-card relative glass rounded-2xl p-6 border-teal-500/10 hover-lift overflow-hidden group">
                    <div class="w-14 h-14 rounded-2xl bg-gradient-to-br from-emerald-400/20 to-teal-500/20 flex items-center justify-center mb-5 group-hover:scale-110 transition-transform">
                        <svg class="w-7 h-7 text-emerald-400" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9.75 17L9 20l-1 1h8l-1-1-.75-3M3 13h18M5 17h14a2 2 0 002-2V5a2 2 0 00-2-2H5a2 2 0 00-2 2v10a2 2 0 002 2z"/>
                        </svg>
                    </div>
                    <h3 class="text-white font-bold text-xl mb-3">دعم العملاء بالذكاء الاصطناعي</h3>
                    <p class="text-gray-400 text-sm leading-relaxed mb-4">ذكاء اصطناعي متقدم يتعامل مع استفسارات عملائك بحرفية عالية ويحل المشاكل تلقائياً دون تدخل بشري.</p>
                    <div class="flex items-center gap-2 text-teal-400 text-sm font-semibold">
                        <span>اكتشف المزيد</span>
                        <svg class="w-4 h-4 group-hover:-translate-x-1 transition-transform" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M17 8l4 4m0 0l-4 4m4-4H3"/>
                        </svg>
                    </div>
                </div>
                
                <!-- Service 3 -->
                <div class="reveal reveal-delay-2 service-card relative glass rounded-2xl p-6 border-teal-500/10 hover-lift overflow-hidden group">
                    <div class="w-14 h-14 rounded-2xl bg-gradient-to-br from-warm-400/20 to-orange-500/20 flex items-center justify-center mb-5 group-hover:scale-110 transition-transform">
                        <svg class="w-7 h-7 text-warm-400" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M16 11V7a4 4 0 00-8 0v4M5 9h14l1 12H4L5 9z"/>
                        </svg>
                    </div>
                    <h3 class="text-white font-bold text-xl mb-3">إدارة الطلبات الذكية</h3>
                    <p class="text-gray-400 text-sm leading-relaxed mb-4">نظام متكامل لإدارة الطلبات من الاستلام إلى التسليم مع تتبع آلي وإشعارات ذكية لكل مرحلة.</p>
                    <div class="flex items-center gap-2 text-teal-400 text-sm font-semibold">
                        <span>اكتشف المزيد</span>
                        <svg class="w-4 h-4 group-hover:-translate-x-1 transition-transform" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M17 8l4 4m0 0l-4 4m4-4H3"/>
                        </svg>
                    </div>
                </div>
                
                <!-- Service 4 -->
                <div class="reveal service-card relative glass rounded-2xl p-6 border-teal-500/10 hover-lift overflow-hidden group">
                    <div class="w-14 h-14 rounded-2xl bg-gradient-to-br from-blue-400/20 to-indigo-500/20 flex items-center justify-center mb-5 group-hover:scale-110 transition-transform">
                        <svg class="w-7 h-7 text-blue-400" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 8l7.89 5.26a2 2 0 002.22 0L21 8M5 19h14a2 2 0 002-2V7a2 2 0 00-2-2H5a2 2 0 00-2 2v10a2 2 0 002 2z"/>
                        </svg>
                    </div>
                    <h3 class="text-white font-bold text-xl mb-3">متابعة العملاء التلقائية</h3>
                    <p class="text-gray-400 text-sm leading-relaxed mb-4">نظام متابعة ذكي يتواصل مع العملاء تلقائياً بعد كل عملية شراء، ويرسل تذكيرات، ويعيد العملاء المترددين.</p>
                    <div class="flex items-center gap-2 text-teal-400 text-sm font-semibold">
                        <span>اكتشف المزيد</span>
                        <svg class="w-4 h-4 group-hover:-translate-x-1 transition-transform" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M17 8l4 4m0 0l-4 4m4-4H3"/>
                        </svg>
                    </div>
                </div>
                
                <!-- Service 5 -->
                <div class="reveal reveal-delay-1 service-card relative glass rounded-2xl p-6 border-teal-500/10 hover-lift overflow-hidden group">
                    <div class="w-14 h-14 rounded-2xl bg-gradient-to-br from-purple-400/20 to-pink-500/20 flex items-center justify-center mb-5 group-hover:scale-110 transition-transform">
                        <svg class="w-7 h-7 text-purple-400" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 19v-6a2 2 0 00-2-2H5a2 2 0 00-2 2v6a2 2 0 002 2h2a2 2 0 002-2zm0 0V9a2 2 0 012-2h2a2 2 0 012 2v10m-6 0a2 2 0 002 2h2a2 2 0 002-2m0 0V5a2 2 0 012-2h2a2 2 0 012 2v14a2 2 0 01-2 2h-2a2 2 0 01-2-2z"/>
                        </svg>
                    </div>
                    <h3 class="text-white font-bold text-xl mb-3">لوحات تحكم ذكية</h3>
                    <p class="text-gray-400 text-sm leading-relaxed mb-4">لوحات تحكم متقدمة تعرض لك كل ما يهم عملك في مكان واحد: مبيعات، عملاء، أداء، وتحليلات فورية.</p>
                    <div class="flex items-center gap-2 text-teal-400 text-sm font-semibold">
                        <span>اكتشف المزيد</span>
                        <svg class="w-4 h-4 group-hover:-translate-x-1 transition-transform" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M17 8l4 4m0 0l-4 4m4-4H3"/>
                        </svg>
                    </div>
                </div>
                
                <!-- Service 6 -->
                <div class="reveal reveal-delay-2 service-card relative glass rounded-2xl p-6 border-teal-500/10 hover-lift overflow-hidden group">
                    <div class="w-14 h-14 rounded-2xl bg-gradient-to-br from-cyan-400/20 to-teal-500/20 flex items-center justify-center mb-5 group-hover:scale-110 transition-transform">
                        <svg class="w-7 h-7 text-cyan-400" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M13 10V3L4 14h7v7l9-11h-7z"/>
                        </svg>
                    </div>
                    <h3 class="text-white font-bold text-xl mb-3">أتمتة متجر سلة</h3>
                    <p class="text-gray-400 text-sm leading-relaxed mb-4">ربط كامل ومتقدم مع منصة سلة لأتمتة كل شيء: المنتجات، الطلبات، العملاء، والتسويق التلقائي.</p>
                    <div class="flex items-center gap-2 text-teal-400 text-sm font-semibold">
                        <span>اكتشف المزيد</span>
                        <svg class="w-4 h-4 group-hover:-translate-x-1 transition-transform" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M17 8l4 4m0 0l-4 4m4-4H3"/>
                        </svg>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- How It Works -->
    <section id="how-it-works" class="py-24 relative overflow-hidden">
        <div class="blob w-96 h-96 bg-emerald-500/10 top-1/2 left-1/2 -translate-x-1/2 -translate-y-1/2"></div>
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 relative z-10">
            <div class="text-center mb-16">
                <span class="reveal inline-block px-4 py-1.5 rounded-full bg-teal-500/10 text-teal-400 text-sm font-semibold mb-4">كيف نعمل</span>
                <h2 class="reveal reveal-delay-1 text-3xl sm:text-4xl lg:text-5xl font-black text-white mb-6">
                    ابدأ في <span class="text-gradient">3 خطوات بسيطة</span>
                </h2>
                <p class="reveal reveal-delay-2 text-gray-400 text-lg max-w-2xl mx-auto">
                    عملية سلسة وسريعة تبدأ بالتواصل وتنتهي بتشغيل نظام الأتمتة الذكي الخاص بك
                </p>
            </div>
            
            <div class="relative max-w-4xl mx-auto">
                <div class="timeline-line hidden md:block"></div>
                
                <!-- Step 1 -->
                <div class="reveal relative mb-12 md:mb-0 md:grid md:grid-cols-2 md:gap-16 md:items-center">
                    <div class="md:text-left mb-6 md:mb-0">
                        <div class="glass rounded-2xl p-6 border-teal-500/20 hover-lift">
                            <div class="w-12 h-12 rounded-xl bg-gradient-to-br from-teal-400 to-emerald-500 flex items-center justify-center mb-4 shadow-lg shadow-teal-500/20">
                                <span class="text-white font-black text-xl">1</span>
                            </div>
                            <h3 class="text-white font-bold text-xl mb-3">تواصل معنا</h3>
                            <p class="text-gray-400 text-sm leading-relaxed">راسلنا على واتساب أو املأ النموذج وسنقوم بالتواصل معك خلال ساعة واحدة لفهم احتياجات عملك بدقة.</p>
                        </div>
                    </div>
                    <div class="hidden md:block"></div>
                    <div class="absolute right-4 md:right-1/2 md:translate-x-1/2 top-0 md:top-1/2 md:-translate-y-1/2 w-4 h-4 rounded-full bg-teal-400 shadow-lg shadow-teal-400/50 z-10"></div>
                </div>
                
                <!-- Step 2 -->
                <div class="reveal relative mb-12 md:mb-0 md:grid md:grid-cols-2 md:gap-16 md:items-center md:mt-16">
                    <div class="hidden md:block"></div>
                    <div class="md:text-right mb-6 md:mb-0">
                        <div class="glass rounded-2xl p-6 border-teal-500/20 hover-lift">
                            <div class="w-12 h-12 rounded-xl bg-gradient-to-br from-emerald-400 to-teal-500 flex items-center justify-center mb-4 shadow-lg shadow-emerald-500/20">
                                <span class="text-white font-black text-xl">2</span>
                            </div>
                            <h3 class="text-white font-bold text-xl mb-3">نصمم نظامك</h3>
                            <p class="text-gray-400 text-sm leading-relaxed">فريقنا المتخصص يقوم ببناء وتخصيص نظام الأتمتة بالكامل وفقاً لطبيعة عملك وأهدافك التجارية.</p>
                        </div>
                    </div>
                    <div class="absolute right-4 md:right-1/2 md:translate-x-1/2 top-0 md:top-1/2 md:-translate-y-1/2 w-4 h-4 rounded-full bg-emerald-400 shadow-lg shadow-emerald-400/50 z-10"></div>
                </div>
                
                <!-- Step 3 -->
                <div class="reveal relative md:grid md:grid-cols-2 md:gap-16 md:items-center md:mt-16">
                    <div class="md:text-left mb-6 md:mb-0">
                        <div class="glass rounded-2xl p-6 border-teal-500/20 hover-lift">
                            <div class="w-12 h-12 rounded-xl bg-gradient-to-br from-warm-400 to-orange-500 flex items-center justify-center mb-4 shadow-lg shadow-warm-500/20">
                                <span class="text-white font-black text-xl">3</span>
                            </div>
                            <h3 class="text-white font-bold text-xl mb-3">انطلق وأتمت</h3>
                            <p class="text-gray-400 text-sm leading-relaxed">نطلق نظامك ونوفر لك تدريباً كاملاً. ابدأ بتجربة مجانية لـ 3 أيام وشاهد الفرق فوراً في أداء عملك.</p>
                        </div>
                    </div>
                    <div class="hidden md:block"></div>
                    <div class="absolute right-4 md:right-1/2 md:translate-x-1/2 top-0 md:top-1/2 md:-translate-y-1/2 w-4 h-4 rounded-full bg-warm-400 shadow-lg shadow-warm-400/50 z-10"></div>
                </div>
            </div>
        </div>
    </section>

    <!-- Benefits Section -->
    <section id="benefits" class="py-24 relative">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center mb-16">
                <span class="reveal inline-block px-4 py-1.5 rounded-full bg-teal-500/10 text-teal-400 text-sm font-semibold mb-4">المميزات</span>
                <h2 class="reveal reveal-delay-1 text-3xl sm:text-4xl lg:text-5xl font-black text-white mb-6">
                    لماذا يختارك العملاء <span class="text-gradient">نيرون</span>؟
                </h2>
            </div>
            
            <div class="grid md:grid-cols-2 gap-8">
                <div class="reveal glass rounded-2xl p-8 border-teal-500/10 hover-lift">
                    <div class="flex items-start gap-5">
                        <div class="w-14 h-14 rounded-2xl bg-teal-500/10 flex items-center justify-center flex-shrink-0">
                            <svg class="w-7 h-7 text-teal-400" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 8v4l3 3m6-3a9 9 0 11-18 0 9 9 0 0118 0z"/>
                            </svg>
                        </div>
                        <div>
                            <h3 class="text-white font-bold text-xl mb-2">وفر 40+ ساعة شهرياً</h3>
                            <p class="text-gray-400 leading-relaxed">توقف عن إهدار وقتك في المهام الروتينية. دع الأتمتة تتولى العمل الشاق بينما تركز على تطوير استراتيجية عملك.</p>
                        </div>
                    </div>
                </div>
                
                <div class="reveal reveal-delay-1 glass rounded-2xl p-8 border-teal-500/10 hover-lift">
                    <div class="flex items-start gap-5">
                        <div class="w-14 h-14 rounded-2xl bg-emerald-500/10 flex items-center justify-center flex-shrink-0">
                            <svg class="w-7 h-7 text-emerald-400" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M13 7h8m0 0v8m0-8l-8 8-4-4-6 6"/>
                            </svg>
                        </div>
                        <div>
                            <h3 class="text-white font-bold text-xl mb-2">زيادة المبيعات 147%</h3>
                            <p class="text-gray-400 leading-relaxed">الرد السريع والمتابعة الذكية تحول المزيد من الزوار إلى عملاء وتزيد من قيمة كل عميل بشكل كبير.</p>
                        </div>
                    </div>
                </div>
                
                <div class="reveal glass rounded-2xl p-8 border-teal-500/10 hover-lift">
                    <div class="flex items-start gap-5">
                        <div class="w-14 h-14 rounded-2xl bg-warm-500/10 flex items-center justify-center flex-shrink-0">
                            <svg class="w-7 h-7 text-warm-400" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M14.828 14.828a4 4 0 01-5.656 0M9 10h.01M15 10h.01M21 12a9 9 0 11-18 0 9 9 0 0118 0z"/>
                            </svg>
                        </div>
                        <div>
                            <h3 class="text-white font-bold text-xl mb-2">رضا عملاء استثنائي</h3>
                            <p class="text-gray-400 leading-relaxed">عملاؤك يحصلون على ردود فورية ومهنية في أي وقت. لا مزيد من الانتظار أو الإحباط.</p>
                        </div>
                    </div>
                </div>
                
                <div class="reveal reveal-delay-1 glass rounded-2xl p-8 border-teal-500/10 hover-lift">
                    <div class="flex items-start gap-5">
                        <div class="w-14 h-14 rounded-2xl bg-blue-500/10 flex items-center justify-center flex-shrink-0">
                            <svg class="w-7 h-7 text-blue-400" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 12l2 2 4-4m5.618-4.016A11.955 11.955 0 0112 2.944a11.955 11.955 0 01-8.618 3.04A12.02 12.02 0 003 9c0 5.591 3.824 10.29 9 11.622 5.176-1.332 9-6.03 9-11.622 0-1.042-.133-2.052-.382-3.016z"/>
                            </svg>
                        </div>
                        <div>
                            <h3 class="text-white font-bold text-xl mb-2">صفر طلبات مفقودة</h3>
                            <p class="text-gray-400 leading-relaxed">كل استفسار وكل طلب يتم التعامل معه فوراً. لا تفوت فرصة بيع أبداً مهما كان حجم التدفق.</p>
                        </div>
                    </div>
                </div>
                
                <div class="reveal glass rounded-2xl p-8 border-teal-500/10 hover-lift">
                    <div class="flex items-start gap-5">
                        <div class="w-14 h-14 rounded-2xl bg-purple-500/10 flex items-center justify-center flex-shrink-0">
                            <svg class="w-7 h-7 text-purple-400" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 19v-6a2 2 0 00-2-2H5a2 2 0 00-2 2v6a2 2 0 002 2h2a2 2 0 002-2zm0 0V9a2 2 0 012-2h2a2 2 0 012 2v10m-6 0a2 2 0 002 2h2a2 2 0 002-2m0 0V5a2 2 0 012-2h2a2 2 0 012 2v14a2 2 0 01-2 2h-2a2 2 0 01-2-2z"/>
                            </svg>
                        </div>
                        <div>
                            <h3 class="text-white font-bold text-xl mb-2">بيانات وتحليلات فورية</h3>
                            <p class="text-gray-400 leading-relaxed">لوحات تحكم متقدمة تعرض لك أداء عملك لحظة بلحظة. اتخذ قراراتك بناءً على بيانات دقيقة.</p>
                        </div>
                    </div>
                </div>
                
                <div class="reveal reveal-delay-1 glass rounded-2xl p-8 border-teal-500/10 hover-lift">
                    <div class="flex items-start gap-5">
                        <div class="w-14 h-14 rounded-2xl bg-cyan-500/10 flex items-center justify-center flex-shrink-0">
                            <svg class="w-7 h-7 text-cyan-400" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M13 10V3L4 14h7v7l9-11h-7z"/>
                            </svg>
                        </div>
                        <div>
                            <h3 class="text-white font-bold text-xl mb-2">توسع بلا حدود</h3>
                            <p class="text-gray-400 leading-relaxed">نظامنا ينمو معك. سواء كان لديك 10 عملاء أو 10,000، الأتمتة تتعامل مع الجميع بكفاءة متساوية.</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Automation Examples -->
    <section class="py-24 relative overflow-hidden">
        <div class="blob w-96 h-96 bg-teal-500/10 -top-48 -right-48"></div>
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 relative z-10">
            <div class="text-center mb-16">
                <span class="reveal inline-block px-4 py-1.5 rounded-full bg-teal-500/10 text-teal-400 text-sm font-semibold mb-4">أمثلة عملية</span>
                <h2 class="reveal reveal-delay-1 text-3xl sm:text-4xl lg:text-5xl font-black text-white mb-6">
                    شاهد <span class="text-gradient">الأتمتة</span> في العمل
                </h2>
            </div>
            
            <div class="grid md:grid-cols-2 lg:grid-cols-3 gap-6">
                <!-- Example 1 -->
                <div class="reveal gradient-border rounded-2xl p-6">
                    <div class="flex items-center gap-3 mb-4">
                        <div class="w-10 h-10 rounded-xl bg-teal-500/20 flex items-center justify-center">
                            <svg class="w-5 h-5 text-teal-400" fill="currentColor" viewBox="0 0 24 24">
                                <path d="M17.472 14.382c-.297-.149-1.758-.867-2.03-.967-.273-.099-.471-.148-.67.15-.197.297-.767.966-.94 1.164-.173.199-.347.223-.644.075-.297-.15-1.255-.463-2.39-1.475-.883-.788-1.48-1.761-1.653-2.059-.173-.297-.018-.458.13-.606.134-.133.298-.347.446-.52.149-.174.198-.298.298-.497.099-.198.05-.371-.025-.52-.075-.149-.669-1.612-.916-2.207-.242-.579-.487-.5-.669-.51-.173-.008-.371-.01-.57-.01-.198 0-.52.074-.792.372-.272.297-1.04 1.016-1.04 2.479 0 1.462 1.065 2.875 1.213 3.074.149.198 2.096 3.2 5.077 4.487.709.306 1.262.489 1.694.625.712.227 1.36.195 1.871.118.571-.085 1.758-.719 2.006-1.413.248-.694.248-1.289.173-1.413-.074-.124-.272-.198-.57-.347m-5.421 7.403h-.004a9.87 9.87 0 01-5.031-1.378l-.361-.214-3.741.982.998-3.648-.235-.374a9.86 9.86 0 01-1.51-5.26c.001-5.45 4.436-9.884 9.888-9.884 2.64 0 5.122 1.03 6.988 2.898a9.825 9.825 0 012.893 6.994c-.003 5.45-4.437 9.884-9.885 9.884m8.413-18.297A11.815 11.815 0 0012.05 0C5.495 0 .16 5.335.157 11.892c0 2.096.547 4.142 1.588 5.945L.057 24l6.305-1.654a11.882 11.882 0 005.683 1.448h.005c6.554 0 11.89-5.335 11.893-11.893a11.821 11.821 0 00-3.48-8.413z"/>
                            </svg>
                        </div>
                        <span class="text-white font-bold">متجر إلكتروني</span>
                    </div>
                    <div class="space-y-3 text-sm">
                        <div class="flex items-center gap-2 text-gray-300">
                            <span class="w-1.5 h-1.5 rounded-full bg-teal-400"></span>
                            <span>العميل يرسل استفسار على واتساب</span>
                        </div>
                        <div class="flex items-center gap-2 text-gray-300">
                            <span class="w-1.5 h-1.5 rounded-full bg-teal-400"></span>
                            <span>الذكاء الاصطناعي يرد فوراً بالمعلومات</span>
                        </div>
                        <div class="flex items-center gap-2 text-gray-300">
                            <span class="w-1.5 h-1.5 rounded-full bg-teal-400"></span>
                            <span>يتم إنشاء الطلب تلقائياً في المتجر</span>
                        </div>
                        <div class="flex items-center gap-2 text-gray-300">
                            <span class="w-1.5 h-1.5 rounded-full bg-teal-400"></span>
                            <span>إشعار تلقائي للمستودع بالشحن</span>
                        </div>
                        <div class="flex items-center gap-2 text-gray-300">
                            <span class="w-1.5 h-1.5 rounded-full bg-teal-400"></span>
                            <span>متابعة تلقائية بعد التسليم</span>
                        </div>
                    </div>
                </div>
                
                <!-- Example 2 -->
                <div class="reveal reveal-delay-1 gradient-border rounded-2xl p-6">
                    <div class="flex items-center gap-3 mb-4">
                        <div class="w-10 h-10 rounded-xl bg-warm-500/20 flex items-center justify-center">
                            <svg class="w-5 h-5 text-warm-400" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M21 15.546c-.523 0-1.046.151-1.5.454a2.704 2.704 0 01-3 0 2.704 2.704 0 00-3 0 2.704 2.704 0 01-3 0 2.704 2.704 0 00-3 0 2.704 2.704 0 01-3 0 2.701 2.701 0 00-1.5-.454M9 6v2m3-2v2m3-2v2M9 3h.01M12 3h.01M15 3h.01M21 21v-7a2 2 0 00-2-2H5a2 2 0 00-2 2v7h18zm-3-9v-2a2 2 0 00-2-2H8a2 2 0 00-2 2v2h12z"/>
                            </svg>
                        </div>
                        <span class="text-white font-bold">مطعم</span>
                    </div>
                    <div class="space-y-3 text-sm">
                        <div class="flex items-center gap-2 text-gray-300">
                            <span class="w-1.5 h-1.5 rounded-full bg-warm-400"></span>
                            <span>العميل يطلب عبر واتساب</span>
                        </div>
                        <div class="flex items-center gap-2 text-gray-300">
                            <span class="w-1.5 h-1.5 rounded-full bg-warm-400"></span>
                            <span>القائمة تُعرض تلقائياً مع الأسعار</span>
                        </div>
                        <div class="flex items-center gap-2 text-gray-300">
                            <span class="w-1.5 h-1.5 rounded-full bg-warm-400"></span>
                            <span>تأكيد الطلب ووقت التجهيز</span>
                        </div>
                        <div class="flex items-center gap-2 text-gray-300">
                            <span class="w-1.5 h-1.5 rounded-full bg-warm-400"></span>
                            <span>إشعار للمطبخ بالطلب الجديد</span>
                        </div>
                        <div class="flex items-center gap-2 text-gray-300">
                            <span class="w-1.5 h-1.5 rounded-full bg-warm-400"></span>
                            <span>تذكير تلقائي عند استلام الطلب</span>
                        </div>
                    </div>
                </div>
                
                <!-- Example 3 -->
                <div class="reveal reveal-delay-2 gradient-border rounded-2xl p-6">
                    <div class="flex items-center gap-3 mb-4">
                        <div class="w-10 h-10 rounded-xl bg-emerald-500/20 flex items-center justify-center">
                            <svg class="w-5 h-5 text-emerald-400" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19.428 15.428a2 2 0 00-1.022-.547l-2.387-.477a6 6 0 00-3.86.517l-.318.158a6 6 0 01-3.86.517L6.05 15.21a2 2 0 00-1.806.547M8 4h8l-1 1v5.172a2 2 0 00.586 1.414l5 5c1.26 1.26.367 3.414-1.415 3.414H4.828c-1.782 0-2.674-2.154-1.414-3.414l5-5A2 2 0 009 10.172V5L8 4z"/>
                            </svg>
                        </div>
                        <span class="text-white font-bold">عيادة طبية</span>
                    </div>
                    <div class="space-y-3 text-sm">
                        <div class="flex items-center gap-2 text-gray-300">
                            <span class="w-1.5 h-1.5 rounded-full bg-emerald-400"></span>
                            <span>المريض يحجز عبر واتساب</span>
                        </div>
                        <div class="flex items-center gap-2 text-gray-300">
                            <span class="w-1.5 h-1.5 rounded-full bg-emerald-400"></span>
                            <span>النظام يعرض الأوقات المتاحة</span>
                        </div>
                        <div class="flex items-center gap-2 text-gray-300">
                            <span class="w-1.5 h-1.5 rounded-full bg-emerald-400"></span>
                            <span>تأكيد الحجز وإرسال التفاصيل</span>
                        </div>
                        <div class="flex items-center gap-2 text-gray-300">
                            <span class="w-1.5 h-1.5 rounded-full bg-emerald-400"></span>
                            <span>تذكير قبل الموعد بـ 24 ساعة</span>
                        </div>
                        <div class="flex items-center gap-2 text-gray-300">
                            <span class="w-1.5 h-1.5 rounded-full bg-emerald-400"></span>
                            <span>متابعة بعد الزيارة تلقائياً</span>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Testimonials -->
    <section id="testimonials" class="py-24 relative">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center mb-16">
                <span class="reveal inline-block px-4 py-1.5 rounded-full bg-teal-500/10 text-teal-400 text-sm font-semibold mb-4">آراء العملاء</span>
                <h2 class="reveal reveal-delay-1 text-3xl sm:text-4xl lg:text-5xl font-black text-white mb-6">
                    ماذا يقول <span class="text-gradient">عملاؤنا</span> عنا؟
                </h2>
            </div>
            
            <div class="grid md:grid-cols-2 lg:grid-cols-3 gap-6">
                <!-- Testimonial 1 -->
                <div class="reveal testimonial-card glass rounded-2xl p-6 border-teal-500/10">
                    <div class="flex items-center gap-1 mb-4">
                        <svg class="w-5 h-5 text-warm-400" fill="currentColor" viewBox="0 0 20 20"><path d="M9.049 2.927c.3-.921 1.603-.921 1.902 0l1.07 3.292a1 1 0 00.95.69h3.462c.969 0 1.371 1.24.588 1.81l-2.8 2.034a1 1 0 00-.364 1.118l1.07 3.292c.3.921-.755 1.688-1.54 1.118l-2.8-2.034a1 1 0 00-1.175 0l-2.8 2.034c-.784.57-1.838-.197-1.539-1.118l1.07-3.292a1 1 0 00-.364-1.118L2.98 8.72c-.783-.57-.38-1.81.588-1.81h3.461a1 1 0 00.951-.69l1.07-3.292z"/></svg>
                        <svg class="w-5 h-5 text-warm-400" fill="currentColor" viewBox="0 0 20 20"><path d="M9.049 2.927c.3-.921 1.603-.921 1.902 0l1.07 3.292a1 1 0 00.95.69h3.462c.969 0 1.371 1.24.588 1.81l-2.8 2.034a1 1 0 00-.364 1.118l1.07 3.292c.3.921-.755 1.688-1.54 1.118l-2.8-2.034a1 1 0 00-1.175 0l-2.8 2.034c-.784.57-1.838-.197-1.539-1.118l1.07-3.292a1 1 0 00-.364-1.118L2.98 8.72c-.783-.57-.38-1.81.588-1.81h3.461a1 1 0 00.951-.69l1.07-3.292z"/></svg>
                        <svg class="w-5 h-5 text-warm-400" fill="currentColor" viewBox="0 0 20 20"><path d="M9.049 2.927c.3-.921 1.603-.921 1.902 0l1.07 3.292a1 1 0 00.95.69h3.462c.969 0 1.371 1.24.588 1.81l-2.8 2.034a1 1 0 00-.364 1.118l1.07 3.292c.3.921-.755 1.688-1.54 1.118l-2.8-2.034a1 1 0 00-1.175 0l-2.8 2.034c-.784.57-1.838-.197-1.539-1.118l1.07-3.292a1 1 0 00-.364-1.118L2.98 8.72c-.783-.57-.38-1.81.588-1.81h3.461a1 1 0 00.951-.69l1.07-3.292z"/></svg>
                        <svg class="w-5 h-5 text-warm-400" fill="currentColor" viewBox="0 0 20 20"><path d="M9.049 2.927c.3-.921 1.603-.921 1.902 0l1.07 3.292a1 1 0 00.95.69h3.462c.969 0 1.371 1.24.588 1.81l-2.8 2.034a1 1 0 00-.364 1.118l1.07 3.292c.3.921-.755 1.688-1.54 1.118l-2.8-2.034a1 1 0 00-1.175 0l-2.8 2.034c-.784.57-1.838-.197-1.539-1.118l1.07-3.292a1 1 0 00-.364-1.118L2.98 8.72c-.783-.57-.38-1.81.588-1.81h3.461a1 1 0 00.951-.69l1.07-3.292z"/></svg>
                        <svg class="w-5 h-5 text-warm-400" fill="currentColor" viewBox="0 0 20 20"><path d="M9.049 2.927c.3-.921 1.603-.921 1.902 0l1.07 3.292a1 1 0 00.95.69h3.462c.969 0 1.371 1.24.588 1.81l-2.8 2.034a1 1 0 00-.364 1.118l1.07 3.292c.3.921-.755 1.688-1.54 1.118l-2.8-2.034a1 1 0 00-1.175 0l-2.8 2.034c-.784.57-1.838-.197-1.539-1.118l1.07-3.292a1 1 0 00-.364-1.118L2.98 8.72c-.783-.57-.38-1.81.588-1.81h3.461a1 1 0 00.951-.69l1.07-3.292z"/></svg>
                    </div>
                    <p class="text-gray-300 leading-relaxed mb-6">"منذ أن بدأنا مع نيرون، زادت مبيعاتنا 180%. النظام يتعامل مع كل استفسارات العملاء على واتساب بشكل احترافي ولا نفقد أي طلب بعد الآن."</p>
                    <div class="flex items-center gap-3">
                        <div class="w-12 h-12 rounded-full bg-gradient-to-br from-teal-400 to-emerald-500 flex items-center justify-center text-white font-bold">ف</div>
                        <div>
                            <div class="text-white font-bold">فهد العتيبي</div>
                            <div class="text-gray-400 text-sm">مالك متجر إلكتروني - الرياض</div>
                        </div>
                    </div>
                </div>
                
                <!-- Testimonial 2 -->
                <div class="reveal reveal-delay-1 testimonial-card glass rounded-2xl p-6 border-teal-500/10">
                    <div class="flex items-center gap-1 mb-4">
                        <svg class="w-5 h-5 text-warm-400" fill="currentColor" viewBox="0 0 20 20"><path d="M9.049 2.927c.3-.921 1.603-.921 1.902 0l1.07 3.292a1 1 0 00.95.69h3.462c.969 0 1.371 1.24.588 1.81l-2.8 2.034a1 1 0 00-.364 1.118l1.07 3.292c.3.921-.755 1.688-1.54 1.118l-2.8-2.034a1 1 0 00-1.175 0l-2.8 2.034c-.784.57-1.838-.197-1.539-1.118l1.07-3.292a1 1 0 00-.364-1.118L2.98 8.72c-.783-.57-.38-1.81.588-1.81h3.461a1 1 0 00.951-.69l1.07-3.292z"/></svg>
                        <svg class="w-5 h-5 text-warm-400" fill="currentColor" viewBox="0 0 20 20"><path d="M9.049 2.927c.3-.921 1.603-.921 1.902 0l1.07 3.292a1 1 0 00.95.69h3.462c.969 0 1.371 1.24.588 1.81l-2.8 2.034a1 1 0 00-.364 1.118l1.07 3.292c.3.921-.755 1.688-1.54 1.118l-2.8-2.034a1 1 0 00-1.175 0l-2.8 2.034c-.784.57-1.838-.197-1.539-1.118l1.07-3.292a1 1 0 00-.364-1.118L2.98 8.72c-.783-.57-.38-1.81.588-1.81h3.461a1 1 0 00.951-.69l1.07-3.292z"/></svg>
                        <svg class="w-5 h-5 text-warm-400" fill="currentColor" viewBox="0 0 20 20"><path d="M9.049 2.927c.3-.921 1.603-.921 1.902 0l1.07 3.292a1 1 0 00.95.69h3.462c.969 0 1.371 1.24.588 1.81l-2.8 2.034a1 1 0 00-.364 1.118l1.07 3.292c.3.921-.755 1.688-1.54 1.118l-2.8-2.034a1 1 0 00-1.175 0l-2.8 2.034c-.784.57-1.838-.197-1.539-1.118l1.07-3.292a1 1 0 00-.364-1.118L2.98 8.72c-.783-.57-.38-1.81.588-1.81h3.461a1 1 0 00.951-.69l1.07-3.292z"/></svg>
                        <svg class="w-5 h-5 text-warm-400" fill="currentColor" viewBox="0 0 20 20"><path d="M9.049 2.927c.3-.921 1.603-.921 1.902 0l1.07 3.292a1 1 0 00.95.69h3.462c.969 0 1.371 1.24.588 1.81l-2.8 2.034a1 1 0 00-.364 1.118l1.07 3.292c.3.921-.755 1.688-1.54 1.118l-2.8-2.034a1 1 0 00-1.175 0l-2.8 2.034c-.784.57-1.838-.197-1.539-1.118l1.07-3.292a1 1 0 00-.364-1.118L2.98 8.72c-.783-.57-.38-1.81.588-1.81h3.461a1 1 0 00.951-.69l1.07-3.292z"/></svg>
                        <svg class="w-5 h-5 text-warm-400" fill="currentColor" viewBox="0 0 20 20"><path d="M9.049 2.927c.3-.921 1.603-.921 1.902 0l1.07 3.292a1 1 0 00.95.69h3.462c.969 0 1.371 1.24.588 1.81l-2.8 2.034a1 1 0 00-.364 1.118l1.07 3.292c.3.921-.755 1.688-1.54 1.118l-2.8-2.034a1 1 0 00-1.175 0l-2.8 2.034c-.784.57-1.838-.197-1.539-1.118l1.07-3.292a1 1 0 00-.364-1.118L2.98 8.72c-.783-.57-.38-1.81.588-1.81h3.461a1 1 0 00.951-.69l1.07-3.292z"/></svg>
                    </div>
                    <p class="text-gray-300 leading-relaxed mb-6">"المطعم كان يفقد طلبات كثيرة بسبب عدم الرد السريع. الآن نظام نيرون يتعامل مع كل شيء تلقائياً ونستقبل طلبات على مدار الساعة حتى خارج أوقات العمل."</p>
                    <div class="flex items-center gap-3">
                        <div class="w-12 h-12 rounded-full bg-gradient-to-br from-warm-400 to-orange-500 flex items-center justify-center text-white font-bold">ع</div>
                        <div>
                            <div class="text-white font-bold">عبدالرحمن القحطاني</div>
                            <div class="text-gray-400 text-sm">مالك سلسلة مطاعم - جدة</div>
                        </div>
                    </div>
                </div>
                
                <!-- Testimonial 3 -->
                <div class="reveal reveal-delay-2 testimonial-card glass rounded-2xl p-6 border-teal-500/10">
                    <div class="flex items-center gap-1 mb-4">
                        <svg class="w-5 h-5 text-warm-400" fill="currentColor" viewBox="0 0 20 20"><path d="M9.049 2.927c.3-.921 1.603-.921 1.902 0l1.07 3.292a1 1 0 00.95.69h3.462c.969 0 1.371 1.24.588 1.81l-2.8 2.034a1 1 0 00-.364 1.118l1.07 3.292c.3.921-.755 1.688-1.54 1.118l-2.8-2.034a1 1 0 00-1.175 0l-2.8 2.034c-.784.57-1.838-.197-1.539-1.118l1.07-3.292a1 1 0 00-.364-1.118L2.98 8.72c-.783-.57-.38-1.81.588-1.81h3.461a1 1 0 00.951-.69l1.07-3.292z"/></svg>
                        <svg class="w-5 h-5 text-warm-400" fill="currentColor" viewBox="0 0 20 20"><path d="M9.049 2.927c.3-.921 1.603-.921 1.902 0l1.07 3.292a1 1 0 00.95.69h3.462c.969 0 1.371 1.24.588 1.81l-2.8 2.034a1 1 0 00-.364 1.118l1.07 3.292c.3.921-.755 1.688-1.54 1.118l-2.8-2.034a1 1 0 00-1.175 0l-2.8 2.034c-.784.57-1.838-.197-1.539-1.118l1.07-3.292a1 1 0 00-.364-1.118L2.98 8.72c-.783-.57-.38-1.81.588-1.81h3.461a1 1 0 00.951-.69l1.07-3.292z"/></svg>
                        <svg class="w-5 h-5 text-warm-400" fill="currentColor" viewBox="0 0 20 20"><path d="M9.049 2.927c.3-.921 1.603-.921 1.902 0l1.07 3.292a1 1 0 00.95.69h3.462c.969 0 1.371 1.24.588 1.81l-2.8 2.034a1 1 0 00-.364 1.118l1.07 3.292c.3.921-.755 1.688-1.54 1.118l-2.8-2.034a1 1 0 00-1.175 0l-2.8 2.034c-.784.57-1.838-.197-1.539-1.118l1.07-3.292a1 1 0 00-.364-1.118L2.98 8.72c-.783-.57-.38-1.81.588-1.81h3.461a1 1 0 00.951-.69l1.07-3.292z"/></svg>
                        <svg class="w-5 h-5 text-warm-400" fill="currentColor" viewBox="0 0 20 20"><path d="M9.049 2.927c.3-.921 1.603-.921 1.902 0l1.07 3.292a1 1 0 00.95.69h3.462c.969 0 1.371 1.24.588 1.81l-2.8 2.034a1 1 0 00-.364 1.118l1.07 3.292c.3.921-.755 1.688-1.54 1.118l-2.8-2.034a1 1 0 00-1.175 0l-2.8 2.034c-.784.57-1.838-.197-1.539-1.118l1.07-3.292a1 1 0 00-.364-1.118L2.98 8.72c-.783-.57-.38-1.81.588-1.81h3.461a1 1 0 00.951-.69l1.07-3.292z"/></svg>
                        <svg class="w-5 h-5 text-warm-400" fill="currentColor" viewBox="0 0 20 20"><path d="M9.049 2.927c.3-.921 1.603-.921 1.902 0l1.07 3.292a1 1 0 00.95.69h3.462c.969 0 1.371 1.24.588 1.81l-2.8 2.034a1 1 0 00-.364 1.118l1.07 3.292c.3.921-.755 1.688-1.54 1.118l-2.8-2.034a1 1 0 00-1.175 0l-2.8 2.034c-.784.57-1.838-.197-1.539-1.118l1.07-3.292a1 1 0 00-.364-1.118L2.98 8.72c-.783-.57-.38-1.81.588-1.81h3.461a1 1 0 00.951-.69l1.07-3.292z"/></svg>
                    </div>
                    <p class="text-gray-300 leading-relaxed mb-6">"العيادة كانت تواجه صعوبة في إدارة المواعيد والمتابعة. نظام نيرون حل كل شيء. التذكيرات التلقائية خفضت نسبة الغياب بنسبة 70%."</p>
                    <div class="flex items-center gap-3">
                        <div class="w-12 h-12 rounded-full bg-gradient-to-br from-emerald-400 to-teal-500 flex items-center justify-center text-white font-bold">ن</div>
                        <div>
                            <div class="text-white font-bold">د. نورة السبيعي</div>
                            <div class="text-gray-400 text-sm">مديرة عيادة تجميل - الدمام</div>
                        </div>
                    </div>
                </div>
                
                <!-- Testimonial 4 -->
                <div class="reveal testimonial-card glass rounded-2xl p-6 border-teal-500/10">
                    <div class="flex items-center gap-1 mb-4">
                        <svg class="w-5 h-5 text-warm-400" fill="currentColor" viewBox="0 0 20 20"><path d="M9.049 2.927c.3-.921 1.603-.921 1.902 0l1.07 3.292a1 1 0 00.95.69h3.462c.969 0 1.371 1.24.588 1.81l-2.8 2.034a1 1 0 00-.364 1.118l1.07 3.292c.3.921-.755 1.688-1.54 1.118l-2.8-2.034a1 1 0 00-1.175 0l-2.8 2.034c-.784.57-1.838-.197-1.539-1.118l1.07-3.292a1 1 0 00-.364-1.118L2.98 8.72c-.783-.57-.38-1.81.588-1.81h3.461a1 1 0 00.951-.69l1.07-3.292z"/></svg>
                        <svg class="w-5 h-5 text-warm-400" fill="currentColor" viewBox="0 0 20 20"><path d="M9.049 2.927c.3-.921 1.603-.921 1.902 0l1.07 3.292a1 1 0 00.95.69h3.462c.969 0 1.371 1.24.588 1.81l-2.8 2.034a1 1 0 00-.364 1.118l1.07 3.292c.3.921-.755 1.688-1.54 1.118l-2.8-2.034a1 1 0 00-1.175 0l-2.8 2.034c-.784.57-1.838-.197-1.539-1.118l1.07-3.292a1 1 0 00-.364-1.118L2.98 8.72c-.783-.57-.38-1.81.588-1.81h3.461a1 1 0 00.951-.69l1.07-3.292z"/></svg>
                        <svg class="w-5 h-5 text-warm-400" fill="currentColor" viewBox="0 0 20 20"><path d="M9.049 2.927c.3-.921 1.603-.921 1.902 0l1.07 3.292a1 1 0 00.95.69h3.462c.969 0 1.371 1.24.588 1.81l-2.8 2.034a1 1 0 00-.364 1.118l1.07 3.292c.3.921-.755 1.688-1.54 1.118l-2.8-2.034a1 1 0 00-1.175 0l-2.8 2.034c-.784.57-1.838-.197-1.539-1.118l1.07-3.292a1 1 0 00-.364-1.118L2.98 8.72c-.783-.57-.38-1.81.588-1.81h3.461a1 1 0 00.951-.69l1.07-3.292z"/></svg>
                        <svg class="w-5 h-5 text-warm-400" fill="currentColor" viewBox="0 0 20 20"><path d="M9.049 2.927c.3-.921 1.603-.921 1.902 0l1.07 3.292a1 1 0 00.95.69h3.462c.969 0 1.371 1.24.588 1.81l-2.8 2.034a1 1 0 00-.364 1.118l1.07 3.292c.3.921-.755 1.688-1.54 1.118l-2.8-2.034a1 1 0 00-1.175 0l-2.8 2.034c-.784.57-1.838-.197-1.539-1.118l1.07-3.292a1 1 0 00-.364-1.118L2.98 8.72c-.783-.57-.38-1.81.588-1.81h3.461a1 1 0 00.951-.69l1.07-3.292z"/></svg>
                        <svg class="w-5 h-5 text-warm-400" fill="currentColor" viewBox="0 0 20 20"><path d="M9.049 2.927c.3-.921 1.603-.921 1.902 0l1.07 3.292a1 1 0 00.95.69h3.462c.969 0 1.371 1.24.588 1.81l-2.8 2.034a1 1 0 00-.364 1.118l1.07 3.292c.3.921-.755 1.688-1.54 1.118l-2.8-2.034a1 1 0 00-1.175 0l-2.8 2.034c-.784.57-1.838-.197-1.539-1.118l1.07-3.292a1 1 0 00-.364-1.118L2.98 8.72c-.783-.57-.38-1.81.588-1.81h3.461a1 1 0 00.951-.69l1.07-3.292z"/></svg>
                    </div>
                    <p class="text-gray-300 leading-relaxed mb-6">"كنت أقضي 6 ساعات يومياً في الرد على العملاء. الآن أنظمة نيرون تتولى كل شيء وأنا أركز على تطوير المنتجات. أفضل استثمار قمت به لعملي."</p>
                    <div class="flex items-center gap-3">
                        <div class="w-12 h-12 rounded-full bg-gradient-to-br from-blue-400 to-indigo-500 flex items-center justify-center text-white font-bold">س</div>
                        <div>
                            <div class="text-white font-bold">سلطان الدوسري</div>
                            <div class="text-gray-400 text-sm">صاحب مصنع - الخبر</div>
                        </div>
                    </div>
                </div>
                
                <!-- Testimonial 5 -->
                <div class="reveal reveal-delay-1 testimonial-card glass rounded-2xl p-6 border-teal-500/10">
                    <div class="flex items-center gap-1 mb-4">
                        <svg class="w-5 h-5 text-warm-400" fill="currentColor" viewBox="0 0 20 20"><path d="M9.049 2.927c.3-.921 1.603-.921 1.902 0l1.07 3.292a1 1 0 00.95.69h3.462c.969 0 1.371 1.24.588 1.81l-2.8 2.034a1 1 0 00-.364 1.118l1.07 3.292c.3.921-.755 1.688-1.54 1.118l-2.8-2.034a1 1 0 00-1.175 0l-2.8 2.034c-.784.57-1.838-.197-1.539-1.118l1.07-3.292a1 1 0 00-.364-1.118L2.98 8.72c-.783-.57-.38-1.81.588-1.81h3.461a1 1 0 00.951-.69l1.07-3.292z"/></svg>
                        <svg class="w-5 h-5 text-warm-400" fill="currentColor" viewBox="0 0 20 20"><path d="M9.049 2.927c.3-.921 1.603-.921 1.902 0l1.07 3.292a1 1 0 00.95.69h3.462c.969 0 1.371 1.24.588 1.81l-2.8 2.034a1 1 0 00-.364 1.118l1.07 3.292c.3.921-.755 1.688-1.54 1.118l-2.8-2.034a1 1 0 00-1.175 0l-2.8 2.034c-.784.57-1.838-.197-1.539-1.118l1.07-3.292a1 1 0 00-.364-1.118L2.98 8.72c-.783-.57-.38-1.81.588-1.81h3.461a1 1 0 00.951-.69l1.07-3.292z"/></svg>
                        <svg class="w-5 h-5 text-warm-400" fill="currentColor" viewBox="0 0 20 20"><path d="M9.049 2.927c.3-.921 1.603-.921 1.902 0l1.07 3.292a1 1 0 00.95.69h3.462c.969 0 1.371 1.24.588 1.81l-2.8 2.034a1 1 0 00-.364 1.118l1.07 3.292c.3.921-.755 1.688-1.54 1.118l-2.8-2.034a1 1 0 00-1.175 0l-2.8 2.034c-.784.57-1.838-.197-1.539-1.118l1.07-3.292a1 1 0 00-.364-1.118L2.98 8.72c-.783-.57-.38-1.81.588-1.81h3.461a1 1 0 00.951-.69l1.07-3.292z"/></svg>
                        <svg class="w-5 h-5 text-warm-400" fill="currentColor" viewBox="0 0 20 20"><path d="M9.049 2.927c.3-.921 1.603-.921 1.902 0l1.07 3.292a1 1 0 00.95.69h3.462c.969 0 1.371 1.24.588 1.81l-2.8 2.034a1 1 0 00-.364 1.118l1.07 3.292c.3.921-.755 1.688-1.54 1.118l-2.8-2.034a1 1 0 00-1.175 0l-2.8 2.034c-.784.57-1.838-.197-1.539-1.118l1.07-3.292a1 1 0 00-.364-1.118L2.98 8.72c-.783-.57-.38-1.81.588-1.81h3.461a1 1 0 00.951-.69l1.07-3.292z"/></svg>
                        <svg class="w-5 h-5 text-warm-400" fill="currentColor" viewBox="0 0 20 20"><path d="M9.049 2.927c.3-.921 1.603-.921 1.902 0l1.07 3.292a1 1 0 00.95.69h3.462c.969 0 1.371 1.24.588 1.81l-2.8 2.034a1 1 0 00-.364 1.118l1.07 3.292c.3.921-.755 1.688-1.54 1.118l-2.8-2.034a1 1 0 00-1.175 0l-2.8 2.034c-.784.57-1.838-.197-1.539-1.118l1.07-3.292a1 1 0 00-.364-1.118L2.98 8.72c-.783-.57-.38-1.81.588-1.81h3.461a1 1 0 00.951-.69l1.07-3.292z"/></svg>
                    </div>
                    <p class="text-gray-300 leading-relaxed mb-6">"خدمة ممتازة وفريق محترف. النظام سهل الاستخدام والنتائج فورية. أنصح كل صاحب عمل في السعودية بتجربة نيرون."</p>
                    <div class="flex items-center gap-3">
                        <div class="w-12 h-12 rounded-full bg-gradient-to-br from-purple-400 to-pink-500 flex items-center justify-center text-white font-bold">م</div>
                        <div>
                            <div class="text-white font-bold">مها الزهراني</div>
                            <div class="text-gray-400 text-sm">صاحبة متجر أزياء - مكة</div>
                        </div>
                    </div>
                </div>
                
                <!-- Testimonial 6 -->
                <div class="reveal reveal-delay-2 testimonial-card glass rounded-2xl p-6 border-teal-500/10">
                    <div class="flex items-center gap-1 mb-4">
                        <svg class="w-5 h-5 text-warm-400" fill="currentColor" viewBox="0 0 20 20"><path d="M9.049 2.927c.3-.921 1.603-.921 1.902 0l1.07 3.292a1 1 0 00.95.69h3.462c.969 0 1.371 1.24.588 1.81l-2.8 2.034a1 1 0 00-.364 1.118l1.07 3.292c.3.921-.755 1.688-1.54 1.118l-2.8-2.034a1 1 0 00-1.175 0l-2.8 2.034c-.784.57-1.838-.197-1.539-1.118l1.07-3.292a1 1 0 00-.364-1.118L2.98 8.72c-.783-.57-.38-1.81.588-1.81h3.461a1 1 0 00.951-.69l1.07-3.292z"/></svg>
                        <svg class="w-5 h-5 text-warm-400" fill="currentColor" viewBox="0 0 20 20"><path d="M9.049 2.927c.3-.921 1.603-.921 1.902 0l1.07 3.292a1 1 0 00.95.69h3.462c.969 0 1.371 1.24.588 1.81l-2.8 2.034a1 1 0 00-.364 1.118l1.07 3.292c.3.921-.755 1.688-1.54 1.118l-2.8-2.034a1 1 0 00-1.175 0l-2.8 2.034c-.784.57-1.838-.197-1.539-1.118l1.07-3.292a1 1 0 00-.364-1.118L2.98 8.72c-.783-.57-.38-1.81.588-1.81h3.461a1 1 0 00.951-.69l1.07-3.292z"/></svg>
                        <svg class="w-5 h-5 text-warm-400" fill="currentColor" viewBox="0 0 20 20"><path d="M9.049 2.927c.3-.921 1.603-.921 1.902 0l1.07 3.292a1 1 0 00.95.69h3.462c.969 0 1.371 1.24.588 1.81l-2.8 2.034a1 1 0 00-.364 1.118l1.07 3.292c.3.921-.755 1.688-1.54 1.118l-2.8-2.034a1 1 0 00-1.175 0l-2.8 2.034c-.784.57-1.838-.197-1.539-1.118l1.07-3.292a1 1 0 00-.364-1.118L2.98 8.72c-.783-.57-.38-1.81.588-1.81h3.461a1 1 0 00.951-.69l1.07-3.292z"/></svg>
                        <svg class="w-5 h-5 text-warm-400" fill="currentColor" viewBox="0 0 20 20"><path d="M9.049 2.927c.3-.921 1.603-.921 1.902 0l1.07 3.292a1 1 0 00.95.69h3.462c.969 0 1.371 1.24.588 1.81l-2.8 2.034a1 1 0 00-.364 1.118l1.07 3.292c.3.921-.755 1.688-1.54 1.118l-2.8-2.034a1 1 0 00-1.175 0l-2.8 2.034c-.784.57-1.838-.197-1.539-1.118l1.07-3.292a1 1 0 00-.364-1.118L2.98 8.72c-.783-.57-.38-1.81.588-1.81h3.461a1 1 0 00.951-.69l1.07-3.292z"/></svg>
                        <svg class="w-5 h-5 text-warm-400" fill="currentColor" viewBox="0 0 20 20"><path d="M9.049 2.927c.3-.921 1.603-.921 1.902 0l1.07 3.292a1 1 0 00.95.69h3.462c.969 0 1.371 1.24.588 1.81l-2.8 2.034a1 1 0 00-.364 1.118l1.07 3.292c.3.921-.755 1.688-1.54 1.118l-2.8-2.034a1 1 0 00-1.175 0l-2.8 2.034c-.784.57-1.838-.197-1.539-1.118l1.07-3.292a1 1 0 00-.364-1.118L2.98 8.72c-.783-.57-.38-1.81.588-1.81h3.461a1 1 0 00.951-.69l1.07-3.292z"/></svg>
                    </div>
                    <p class="text-gray-300 leading-relaxed mb-6">"التكامل مع سلة كان سلساً جداً. كل شيء يعمل تلقائياً من استلام الطلب إلى الشحن والمتابعة. وفرت أكثر من 50 ساعة شهرياً."</p>
                    <div class="flex items-center gap-3">
                        <div class="w-12 h-12 rounded-full bg-gradient-to-br from-cyan-400 to-blue-500 flex items-center justify-center text-white font-bold">ي</div>
                        <div>
                            <div class="text-white font-bold">ياسر الشمري</div>
                            <div class="text-gray-400 text-sm">صاحب متجر إلكتروني - حائل</div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- FAQ Section -->
    <section id="faq" class="py-24 relative">
        <div class="max-w-4xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center mb-16">
                <span class="reveal inline-block px-4 py-1.5 rounded-full bg-teal-500/10 text-teal-400 text-sm font-semibold mb-4">الأسئلة الشائعة</span>
                <h2 class="reveal reveal-delay-1 text-3xl sm:text-4xl lg:text-5xl font-black text-white mb-6">
                    كل ما تريد <span class="text-gradient">معرفته</span>
                </h2>
            </div>
            
            <div class="space-y-4">
                <!-- FAQ 1 -->
                <div class="reveal faq-item glass rounded-2xl border-teal-500/10 overflow-hidden">
                    <button class="faq-trigger w-full flex items-center justify-between p-6 text-right hover:bg-white/5 transition-colors">
                        <span class="text-white font-bold text-lg">ما هي مدة التجربة المجانية؟</span>
                        <svg class="faq-icon w-6 h-6 text-teal-400 flex-shrink-0 mr-4" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 9l-7 7-7-7"/>
                        </svg>
                    </button>
                    <div class="faq-answer">
                        <div class="px-6 pb-6 text-gray-400 leading-relaxed">
                            نقدم لك تجربة مجانية كاملة لمدة 3 أيام بدون أي التزام أو حاجة لبطاقة ائتمان. خلال هذه الفترة، ستتمكن من تجربة جميع ميزات النظام ومعرفة كيف يمكنه تحسين عملك. إذا قررت عدم الاستمرار، لا يوجد أي التزام من جانبك.
                        </div>
                    </div>
                </div>
                
                <!-- FAQ 2 -->
                <div class="reveal reveal-delay-1 faq-item glass rounded-2xl border-teal-500/10 overflow-hidden">
                    <button class="faq-trigger w-full flex items-center justify-between p-6 text-right hover:bg-white/5 transition-colors">
                        <span class="text-white font-bold text-lg">هل النظام يدعم اللغة العربية؟</span>
                        <svg class="faq-icon w-6 h-6 text-teal-400 flex-shrink-0 mr-4" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 9l-7 7-7-7"/>
                        </svg>
                    </button>
                    <div class="faq-answer">
                        <div class="px-6 pb-6 text-gray-400 leading-relaxed">
                            نعم بالتأكيد. النظام مصمم خصيصاً للسوق السعودي والخليجي ويدعم اللغة العربية بشكل كامل. الذكاء الاصطناعي يتعامل مع اللهجات السعودية والخليجية باحترافية عالية ويقدم ردوداً طبيعية ومهنية باللغة العربية الفصحى أو العامية حسب رغبتك.
                        </div>
                    </div>
                </div>
                
                <!-- FAQ 3 -->
                <div class="reveal reveal-delay-2 faq-item glass rounded-2xl border-teal-500/10 overflow-hidden">
                    <button class="faq-trigger w-full flex items-center justify-between p-6 text-right hover:bg-white/5 transition-colors">
                        <span class="text-white font-bold text-lg">هل يمكن الربط مع متجري على سلة؟</span>
                        <svg class="faq-icon w-6 h-6 text-teal-400 flex-shrink-0 mr-4" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 9l-7 7-7-7"/>
                        </svg>
                    </button>
                    <div class="faq-answer">
                        <div class="px-6 pb-6 text-gray-400 leading-relaxed">
                            نعم، نحن نقدم تكاملاً كاملاً ومتقدماً مع منصة سلة. يمكن ربط نظام الأتمتة مع متجرك على سلة لأتمتة الطلبات، إدارة المخزون، إرسال الإشعارات التلقائية للعملاء، ومتابعة حالة الشحن. العملية سهلة ولا تتطلب أي خبرة تقنية.
                        </div>
                    </div>
                </div>
                
                <!-- FAQ 4 -->
                <div class="reveal faq-item glass rounded-2xl border-teal-500/10 overflow-hidden">
                    <button class="faq-trigger w-full flex items-center justify-between p-6 text-right hover:bg-white/5 transition-colors">
                        <span class="text-white font-bold text-lg">كم تستغرق عملية الإعداد؟</span>
                        <svg class="faq-icon w-6 h-6 text-teal-400 flex-shrink-0 mr-4" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 9l-7 7-7-7"/>
                        </svg>
                    </button>
                    <div class="faq-answer">
                        <div class="px-6 pb-6 text-gray-400 leading-relaxed">
                            عادة ما تستغرق عملية الإعداد والتشغيل من 24 إلى 48 ساعة فقط. فريقنا يتولى كل شيء من البداية إلى النهاية. سنقوم بفهم احتياجاتك، ثم بناء النظام، واختباره، وتدريبك على استخدامه. لا تحتاج لأي خبرة تقنية.
                        </div>
                    </div>
                </div>
                
                <!-- FAQ 5 -->
                <div class="reveal reveal-delay-1 faq-item glass rounded-2xl border-teal-500/10 overflow-hidden">
                    <button class="faq-trigger w-full flex items-center justify-between p-6 text-right hover:bg-white/5 transition-colors">
                        <span class="text-white font-bold text-lg">هل يمكنني تخصيص الردود الآلية؟</span>
                        <svg class="faq-icon w-6 h-6 text-teal-400 flex-shrink-0 mr-4" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 9l-7 7-7-7"/>
                        </svg>
                    </button>
                    <div class="faq-answer">
                        <div class="px-6 pb-6 text-gray-400 leading-relaxed">
                            بالتأكيد. يمكنك تخصيص كل جانب من جوانب الردود الآلية بما يتناسب مع هوية علامتك التجارية. من نبرة الصوت إلى المحتوى، يمكنك ضبط النظام ليعكس شخصية عملك. كما يمكنك إضافة أسئلة وأجوبة خاصة بمنتجاتك وخدماتك.
                        </div>
                    </div>
                </div>
                
                <!-- FAQ 6 -->
                <div class="reveal reveal-delay-2 faq-item glass rounded-2xl border-teal-500/10 overflow-hidden">
                    <button class="faq-trigger w-full flex items-center justify-between p-6 text-right hover:bg-white/5 transition-colors">
                        <span class="text-white font-bold text-lg">ما هي وسائل الدفع المتاحة؟</span>
                        <svg class="faq-icon w-6 h-6 text-teal-400 flex-shrink-0 mr-4" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 9l-7 7-7-7"/>
                        </svg>
                    </button>
                    <div class="faq-answer">
                        <div class="px-6 pb-6 text-gray-400 leading-relaxed">
                            ندعم جميع وسائل الدفع الشائعة في السعودية بما في ذلك: Apple Pay، مدى، فيزا، ماستركارد، والتحويل البنكي. كما نوفر خطط اشتراك مرنة تناسب جميع الأحجام من الشركات الناشئة إلى الشركات المتوسطة والكبيرة.
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Final CTA Section -->
    <section id="contact" class="py-24 relative overflow-hidden">
        <div class="absolute inset-0 bg-gradient-to-b from-navy-950 via-teal-950/20 to-navy-950"></div>
        <div class="blob w-96 h-96 bg-teal-500/20 top-1/2 left-1/2 -translate-x-1/2 -translate-y-1/2"></div>
        <div class="max-w-5xl mx-auto px-4 sm:px-6 lg:px-8 relative z-10 text-center">
            <div class="reveal glass rounded-3xl p-8 sm:p-12 lg:p-16 border-teal-500/20">
                <span class="inline-block px-4 py-1.5 rounded-full bg-warm-500/10 text-warm-400 text-sm font-semibold mb-6">ابدأ الآن</span>
                <h2 class="text-3xl sm:text-4xl lg:text-5xl font-black text-white mb-6 leading-tight">
                    جاهز لتحويل<br>
                    <span class="text-gradient">عملك إلى آلة ربحية؟</span>
                </h2>
                <p class="text-gray-400 text-lg max-w-2xl mx-auto mb-10">
                    انضم إلى مئات أصحاب الأعمال في السعودية والخليج الذين يستخدمون نيرون لأتمتة عملياتهم وزيادة أرباحهم. تجربتك المجانية تنتظرك.
                </p>
                
                <div class="flex flex-col sm:flex-row gap-4 justify-center mb-10">
                    <a href="https://wa.me/966500000000" target="_blank" class="group px-8 py-4 rounded-full bg-gradient-to-r from-teal-500 to-emerald-500 text-white font-bold text-lg hover:shadow-2xl hover:shadow-teal-500/30 transition-all flex items-center justify-center gap-3 animate-pulse-glow">
                        <svg class="w-6 h-6" fill="currentColor" viewBox="0 0 24 24">
                            <path d="M17.472 14.382c-.297-.149-1.758-.867-2.03-.967-.273-.099-.471-.148-.67.15-.197.297-.767.966-.94 1.164-.173.199-.347.223-.644.075-.297-.15-1.255-.463-2.39-1.475-.883-.788-1.48-1.761-1.653-2.059-.173-.297-.018-.458.13-.606.134-.133.298-.347.446-.52.149-.174.198-.298.298-.497.099-.198.05-.371-.025-.52-.075-.149-.669-1.612-.916-2.207-.242-.579-.487-.5-.669-.51-.173-.008-.371-.01-.57-.01-.198 0-.52.074-.792.372-.272.297-1.04 1.016-1.04 2.479 0 1.462 1.065 2.875 1.213 3.074.149.198 2.096 3.2 5.077 4.487.709.306 1.262.489 1.694.625.712.227 1.36.195 1.871.118.571-.085 1.758-.719 2.006-1.413.248-.694.248-1.289.173-1.413-.074-.124-.272-.198-.57-.347m-5.421 7.403h-.004a9.87 9.87 0 01-5.031-1.378l-.361-.214-3.741.982.998-3.648-.235-.374a9.86 9.86 0 01-1.51-5.26c.001-5.45 4.436-9.884 9.888-9.884 2.64 0 5.122 1.03 6.988 2.898a9.825 9.825 0 012.893 6.994c-.003 5.45-4.437 9.884-9.885 9.884m8.413-18.297A11.815 11.815 0 0012.05 0C5.495 0 .16 5.335.157 11.892c0 2.096.547 4.142 1.588 5.945L.057 24l6.305-1.654a11.882 11.882 0 005.683 1.448h.005c6.554 0 11.89-5.335 11.893-11.893a11.821 11.821 0 00-3.48-8.413z"/>
                        </svg>
                        تواصل عبر واتساب
                    </a>
                </div>
                
                <div class="flex flex-wrap items-center justify-center gap-6 text-sm text-gray-400">
                    <div class="flex items-center gap-2">
                        <svg class="w-5 h-5 text-emerald-400" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 13l4 4L19 7"/>
                        </svg>
                        <span>3 أيام مجانية</span>
                    </div>
                    <div class="flex items-center gap-2">
                        <svg class="w-5 h-5 text-emerald-400" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 13l4 4L19 7"/>
                        </svg>
                        <span>بدون التزام</span>
                    </div>
                    <div class="flex items-center gap-2">
                        <svg class="w-5 h-5 text-emerald-400" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 13l4 4L19 7"/>
                        </svg>
                        <span>إلغاء فوري</span>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="py-16 border-t border-white/5">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="grid md:grid-cols-2 lg:grid-cols-4 gap-12 mb-12">
                <!-- Brand -->
                <div class="lg:col-span-1">
                    <a href="#" class="flex items-center gap-3 mb-6">
                        <div class="w-10 h-10 rounded-xl bg-gradient-to-br from-teal-400 to-emerald-500 flex items-center justify-center">
                            <svg class="w-6 h-6 text-white" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M13 10V3L4 14h7v7l9-11h-7z"/>
                            </svg>
                        </div>
                        <span class="text-2xl font-bold text-white">نيرون</span>
                    </a>
                    <p class="text-gray-400 text-sm leading-relaxed mb-6">
                        وكالة متخصصة في أتمتة الأعمال بالذكاء الاصطناعي. نساعد الشركات السعودية والخليجية على النمو من خلال التحول الرقمي الذكي.
                    </p>
                    <div class="flex items-center gap-4">
                        <a href="#" class="w-10 h-10 rounded-full bg-white/5 flex items-center justify-center hover:bg-teal-500/20 transition-colors">
                            <svg class="w-5 h-5 text-gray-400" fill="currentColor" viewBox="0 0 24 24">
                                <path d="M24 12.073c0-6.627-5.373-12-12-12s-12 5.373-12 12c0 5.99 4.388 10.954 10.125 11.854v-8.385H7.078v-3.47h3.047V9.43c0-3.007 1.792-4.669 4.533-4.669 1.312 0 2.686.235 2.686.235v2.953H15.83c-1.491 0-1.956.925-1.956 1.874v2.25h3.328l-.532 3.47h-2.796v8.385C19.612 23.027 24 18.062 24 12.073z"/>
                            </svg>
                        </a>
                        <a href="#" class="w-10 h-10 rounded-full bg-white/5 flex items-center justify-center hover:bg-teal-500/20 transition-colors">
                            <svg class="w-5 h-5 text-gray-400" fill="currentColor" viewBox="0 0 24 24">
                                <path d="M12 2.163c3.204 0 3.584.012 4.85.07 3.252.148 4.771 1.691 4.919 4.919.058 1.265.069 1.645.069 4.849 0 3.205-.012 3.584-.069 4.849-.149 3.225-1.664 4.771-4.919 4.919-1.266.058-1.644.07-4.85.07-3.204 0-3.584-.012-4.849-.07-3.26-.149-4.771-1.699-4.919-4.92-.058-1.265-.07-1.644-.07-4.849 0-3.204.013-3.583.07-4.849.149-3.227 1.664-4.771 4.919-4.919 1.266-.057 1.645-.069 4.849-.069zm0-2.163c-3.259 0-3.667.014-4.947.072-4.358.2-6.78 2.618-6.98 6.98-.059 1.281-.073 1.689-.073 4.948 0 3.259.014 3.668.072 4.948.2 4.358 2.618 6.78 6.98 6.98 1.281.058 1.689.072 4.948.072 3.259 0 3.668-.014 4.948-.072 4.354-.2 6.782-2.618 6.979-6.98.059-1.28.073-1.689.073-4.948 0-3.259-.014-3.667-.072-4.947-.196-4.354-2.617-6.78-6.979-6.98-1.281-.059-1.69-.073-4.949-.073zm0 5.838c-3.403 0-6.162 2.759-6.162 6.162s2.759 6.163 6.162 6.163 6.162-2.759 6.162-6.163c0-3.403-2.759-6.162-6.162-6.162zm0 10.162c-2.209 0-4-1.79-4-4 0-2.209 1.791-4 4-4s4 1.791 4 4c0 2.21-1.791 4-4 4zm6.406-11.845c-.796 0-1.441.645-1.441 1.44s.645 1.44 1.441 1.44c.795 0 1.439-.645 1.439-1.44s-.644-1.44-1.439-1.44z"/>
                            </svg>
                        </a>
                        <a href="#" class="w-10 h-10 rounded-full bg-white/5 flex items-center justify-center hover:bg-teal-500/20 transition-colors">
                            <svg class="w-5 h-5 text-gray-400" fill="currentColor" viewBox="0 0 24 24">
                                <path d="M19.615 3.184c-3.604-.246-11.631-.245-15.23 0-3.897.266-4.356 2.62-4.385 8.816.029 6.185.484 8.549 4.385 8.816 3.6.245 11.626.246 15.23 0 3.897-.266 4.356-2.62 4.385-8.816-.029-6.185-.484-8.549-4.385-8.816zm-10.615 12.816v-8l8 3.993-8 4.007z"/>
                            </svg>
                        </a>
                    </div>
                </div>
                
                <!-- Services -->
                <div>
                    <h4 class="text-white font-bold mb-6">خدماتنا</h4>
                    <ul class="space-y-3">
                        <li><a href="#" class="text-gray-400 hover:text-teal-400 transition-colors text-sm">أتمتة واتساب</a></li>
                        <li><a href="#" class="text-gray-400 hover:text-teal-400 transition-colors text-sm">دعم العملاء بالذكاء الاصطناعي</a></li>
                        <li><a href="#" class="text-gray-400 hover:text-teal-400 transition-colors text-sm">إدارة الطلبات الذكية</a></li>
                        <li><a href="#" class="text-gray-400 hover:text-teal-400 transition-colors text-sm">متابعة العملاء التلقائية</a></li>
                        <li><a href="#" class="text-gray-400 hover:text-teal-400 transition-colors text-sm">لوحات التحكم الذكية</a></li>
                    </ul>
                </div>
                
                <!-- Company -->
                <div>
                    <h4 class="text-white font-bold mb-6">الشركة</h4>
                    <ul class="space-y-3">
                        <li><a href="#" class="text-gray-400 hover:text-teal-400 transition-colors text-sm">عن نيرون</a></li>
                        <li><a href="#" class="text-gray-400 hover:text-teal-400 transition-colors text-sm">كيف نعمل</a></li>
                        <li><a href="#" class="text-gray-400 hover:text-teal-400 transition-colors text-sm">الأسعار</a></li>
                        <li><a href="#" class="text-gray-400 hover:text-teal-400 transition-colors text-sm">المدونة</a></li>
                        <li><a href="#" class="text-gray-400 hover:text-teal-400 transition-colors text-sm">تواصل معنا</a></li>
                    </ul>
                </div>
                
                <!-- Contact -->
                <div>
                    <h4 class="text-white font-bold mb-6">تواصل معنا</h4>
                    <ul class="space-y-3">
                        <li class="flex items-center gap-3 text-gray-400 text-sm">
                            <svg class="w-5 h-5 text-teal-400" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 5a2 2 0 012-2h3.28a1 1 0 01.948.684l1.498 4.493a1 1 0 01-.502 1.21l-2.257 1.13a11.042 11.042 0 005.516 5.516l1.13-2.257a1 1 0 011.21-.502l4.493 1.498a1 1 0 01.684.949V19a2 2 0 01-2 2h-1C9.716 21 3 14.284 3 6V5z"/>
                            </svg>
                            <span>+966 50 000 0000</span>
                        </li>
                        <li class="flex items-center gap-3 text-gray-400 text-sm">
                            <svg class="w-5 h-5 text-teal-400" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 8l7.89 5.26a2 2 0 002.22 0L21 8M5 19h14a2 2 0 002-2V7a2 2 0 00-2-2H5a2 2 0 00-2 2v10a2 2 0 002 2z"/>
                            </svg>
                            <span>info@neuron.sa</span>
                        </li>
                        <li class="flex items-center gap-3 text-gray-400 text-sm">
                            <svg class="w-5 h-5 text-teal-400" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M17.657 16.657L13.414 20.9a1.998 1.998 0 01-2.827 0l-4.244-4.243a8 8 0 1111.314 0z"/>
                                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M15 11a3 3 0 11-6 0 3 3 0 016 0z"/>
                            </svg>
                            <span>الرياض، المملكة العربية السعودية</span>
                        </li>
                    </ul>
                </div>
            </div>
            
            <div class="border-t border-white/5 pt-8 flex flex-col md:flex-row items-center justify-between gap-4">
                <p class="text-gray-500 text-sm">© 2026 نيرون. جميع الحقوق محفوظة.</p>
                <div class="flex items-center gap-6">
                    <a href="#" class="text-gray-500 hover:text-teal-400 transition-colors text-sm">سياسة الخصوصية</a>
                    <a href="#" class="text-gray-500 hover:text-teal-400 transition-colors text-sm">شروط الاستخدام</a>
                </div>
            </div>
        </div>
    </footer>

    <!-- Floating WhatsApp Button -->
    <a href="https://wa.me/966500000000" target="_blank" class="whatsapp-float w-16 h-16 rounded-full bg-gradient-to-br from-emerald-500 to-green-600 flex items-center justify-center shadow-2xl shadow-emerald-500/30 hover:scale-110 transition-transform z-50">
        <svg class="w-8 h-8 text-white" fill="currentColor" viewBox="0 0 24 24">
            <path d="M17.472 14.382c-.297-.149-1.758-.867-2.03-.967-.273-.099-.471-.148-.67.15-.197.297-.767.966-.94 1.164-.173.199-.347.223-.644.075-.297-.15-1.255-.463-2.39-1.475-.883-.788-1.48-1.761-1.653-2.059-.173-.297-.018-.458.13-.606.134-.133.298-.347.446-.52.149-.174.198-.298.298-.497.099-.198.05-.371-.025-.52-.075-.149-.669-1.612-.916-2.207-.242-.579-.487-.5-.669-.51-.173-.008-.371-.01-.57-.01-.198 0-.52.074-.792.372-.272.297-1.04 1.016-1.04 2.479 0 1.462 1.065 2.875 1.213 3.074.149.198 2.096 3.2 5.077 4.487.709.306 1.262.489 1.694.625.712.227 1.36.195 1.871.118.571-.085 1.758-.719 2.006-1.413.248-.694.248-1.289.173-1.413-.074-.124-.272-.198-.57-.347m-5.421 7.403h-.004a9.87 9.87 0 01-5.031-1.378l-.361-.214-3.741.982.998-3.648-.235-.374a9.86 9.86 0 01-1.51-5.26c.001-5.45 4.436-9.884 9.888-9.884 2.64 0 5.122 1.03 6.988 2.898a9.825 9.825 0 012.893 6.994c-.003 5.45-4.437 9.884-9.885 9.884m8.413-18.297A11.815 11.815 0 0012.05 0C5.495 0 .16 5.335.157 11.892c0 2.096.547 4.142 1.588 5.945L.057 24l6.305-1.654a11.882 11.882 0 005.683 1.448h.005c6.554 0 11.89-5.335 11.893-11.893a11.821 11.821 0 00-3.48-8.413z"/>
        </svg>
    </a>

    <script>
        // Navbar scroll effect
        const navbar = document.getElementById('navbar');
        window.addEventListener('scroll', () => {
            if (window.scrollY > 50) {
                navbar.classList.add('nav-scrolled');
            } else {
                navbar.classList.remove('nav-scrolled');
            }
        });

        // Mobile menu
        const mobileMenuBtn = document.getElementById('mobile-menu-btn');
        const closeMenuBtn = document.getElementById('close-menu');
        const mobileMenu = document.getElementById('mobile-menu');
        const mobileLinks = document.querySelectorAll('.mobile-link');

        mobileMenuBtn.addEventListener('click', () => {
            mobileMenu.classList.add('open');
        });

        closeMenuBtn.addEventListener('click', () => {
            mobileMenu.classList.remove('open');
        });

        mobileLinks.forEach(link => {
            link.addEventListener('click', () => {
                mobileMenu.classList.remove('open');
            });
        });

        // Scroll reveal animation
        const revealElements = document.querySelectorAll('.reveal');
        const revealObserver = new IntersectionObserver((entries) => {
            entries.forEach(entry => {
                if (entry.isIntersecting) {
                    entry.target.classList.add('active');
                }
            });
        }, {
            threshold: 0.1,
            rootMargin: '0px 0px -50px 0px'
        });

        revealElements.forEach(el => revealObserver.observe(el));

        // Counter animation
        const counters = document.querySelectorAll('.counter-value');
        const counterObserver = new IntersectionObserver((entries) => {
            entries.forEach(entry => {
                if (entry.isIntersecting) {
                    const counter = entry.target;
                    const target = parseInt(counter.getAttribute('data-target'));
                    const duration = 2000;
                    const step = target / (duration / 16);
                    let current = 0;
                    
                    const updateCounter = () => {
                        current += step;
                        if (current < target) {
                            counter.textContent = Math.floor(current);
                            requestAnimationFrame(updateCounter);
                        } else {
                            counter.textContent = target;
                        }
                    };
                    
                    updateCounter();
                    counterObserver.unobserve(counter);
                }
            });
        }, { threshold: 0.5 });

        counters.forEach(counter => counterObserver.observe(counter));

        // FAQ Accordion
        const faqItems = document.querySelectorAll('.faq-item');
        faqItems.forEach(item => {
            const trigger = item.querySelector('.faq-trigger');
            trigger.addEventListener('click', () => {
                const isActive = item.classList.contains('active');
                
                // Close all
                faqItems.forEach(i => i.classList.remove('active'));
                
                // Open clicked if it wasn't active
                if (!isActive) {
                    item.classList.add('active');
                }
            });
        });

        // Smooth scroll for anchor links
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function(e) {
                e.preventDefault();
                const target = document.querySelector(this.getAttribute('href'));
                if (target) {
                    target.scrollIntoView({
                        behavior: 'smooth',
                        block: 'start'
                    });
                }
            });
        });
    </script>
</body>
</html>'''

with open('/mnt/agents/output/neuron-landing-page.html', 'w', encoding='utf-8') as f:
    f.write(html_content)

print("File saved successfully!")
print(f"File size: {len(html_content)} characters")
