<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>تحالف السودان التأسيسي</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Tajawal:wght@400;500;700;900&display=swap');
        
        body {
            font-family: 'Tajawal', sans-serif;
        }
        
        .hero-pattern {
            background-image: url(https://scontent.fnbo9-1.fna.fbcdn.net/v/t39.30808-6/481079311_122108958914775565_6736187880556704441_n.jpg?_nc_cat=107&ccb=1-7&_nc_sid=cc71e4&_nc_ohc=VwX2GHHS3REQ7kNvwEmoTyw&_nc_oc=Adk1IT7LF8q_psXitoYKPku9300jiy2FGQRAd8eclCRphLpqtgndDQdpYkagM-RsH_Y&_nc_zt=23&_nc_ht=scontent.fnbo9-1.fna&_nc_gid=kCu5N8wSs7pxECK_YMAuyw&oh=00_AfVUQssLsp3Nhp_bGh4rRGlz-XEblYkbPhvgHMTJFQ8MBQ&oe=68AB7875 );
            background-size: cover;
            background-position: center;
            background-blend-mode: overlay;
        }
        
        .news-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 10px 20px rgba(0, 0, 0, 0.2);
        }
        
        .mobile-menu {
            transition: all 0.3s ease;
        }
    </style>
</head>
<body class="bg-gray-50 text-gray-800">
    <!-- Header -->
    <header class="bg-white shadow-md sticky top-0 z-50">
        <div class="container mx-auto px-4 py-3 flex justify-between items-center">
            <div class="flex items-center">
                <img src="logo_n.jpg" alt="شعار التحالف" class="h-12 mr-3">
                <h1 class="text-xl font-bold text-blue-800">تحالف السودان التأسيسي</h1>
            </div>
            
            <!-- Desktop Navigation -->
            <nav class="hidden md:flex space-x-6 space-x-reverse">
                <a href="#home" class="text-blue-800 hover:text-blue-600 font-medium">الرئيسية</a>
                <a href="#about" class="text-gray-700 hover:text-blue-600 font-medium">عن التحالف</a>
                <a href="#goals" class="text-gray-700 hover:text-blue-600 font-medium">أهدافنا</a>
                <a href="#news" class="text-gray-700 hover:text-blue-600 font-medium">الأخبار</a>
                <a href="#contact" class="text-gray-700 hover:text-blue-600 font-medium">اتصل بنا</a>
            </nav>
            
            <!-- Mobile Menu Button -->
            <button id="mobile-menu-button" class="md:hidden text-gray-700 focus:outline-none">
                <i class="fas fa-bars text-2xl"></i>
            </button>
        </div>
        
        <!-- Mobile Menu -->
        <div id="mobile-menu" class="mobile-menu hidden md:hidden bg-white py-2 px-4 shadow-lg">
            <a href="#home" class="block py-2 text-blue-800 font-medium">الرئيسية</a>
            <a href="#about" class="block py-2 text-gray-700 hover:text-blue-600">عن التحالف</a>
            <a href="#goals" class="block py-2 text-gray-700 hover:text-blue-600">أهدافنا</a>
            <a href="#news" class="block py-2 text-gray-700 hover:text-blue-600">الأخبار</a>
            <a href="#contact" class="block py-2 text-gray-700 hover:text-blue-600">اتصل بنا</a>
        </div>
    </header>

    <!-- Hero Section -->
    <section id="home" class="hero-pattern bg-blue-900 bg-opacity-70 text-white py-20">
        <div class="container mx-auto px-4 text-center">
            <h1 class="text-4xl md:text-5xl font-bold mb-6">تحالف السودان التأسيسي</h1>
            <p class="text-xl md:text-2xl mb-8 max-w-3xl mx-auto">نحو سودان ديمقراطي موحد يحقق تطلعات الشعب السوداني</p>
            <div class="flex flex-col sm:flex-row justify-center gap-4">
                <a href="#about" class="bg-white text-blue-800 px-8 py-3 rounded-lg font-bold hover:bg-gray-100 transition duration-300">تعرف علينا</a>
                <a href="#contact" class="bg-transparent border-2 border-white px-8 py-3 rounded-lg font-bold hover:bg-white hover:text-blue-800 transition duration-300">انضم إلينا</a>
            </div>
        </div>
    </section>

    <!-- About Section -->
    <section id="about" class="py-16 bg-white">
        <div class="container mx-auto px-4">
            <h2 class="text-3xl font-bold text-center mb-12 text-blue-800">عن التحالف</h2>
            <div class="flex flex-col lg:flex-row items-center gap-10">
                <div class="lg:w-1/2">
                    <img src="C:\Users\09108\Downloads\تحالف 2n.jpg" alt="تحالف السودان" class="w-full h-auto rounded-lg shadow-lg">
                </div>
                <div class="lg:w-1/2">
                    <p class="text-lg mb-6 leading-relaxed">
                        تحالف السودان التأسيسي هو تحالف سياسي يضم مجموعة من القوى السياسية والمجتمعية السودانية التي تلتزم ببناء سودان ديمقراطي موحد يحقق العدالة والحرية والسلام للشعب السوداني.
                    </p>
                    <p class="text-lg mb-6 leading-relaxed">
                        تأسس التحالف في عام 2025 كإطار جامع للقوى التي تؤمن بالحل السياسي الشامل والانتقال الديمقراطي السلمي، ويعمل على صياغة عقد اجتماعي جديد يضمن حقوق جميع مكونات الشعب السوداني.
                    </p>
                    <p class="text-lg leading-relaxed">
                        يتبنى التحالف رؤية واضحة لبناء دولة المواطنة المتساوية التي تقوم على الديمقراطية والتعددية واحترام حقوق الإنسان.
                    </p>
                </div>
            </div>
        </div>
    </section>

    <!-- Goals Section -->
    <section id="goals" class="py-16 bg-gray-50">
        <div class="container mx-auto px-4">
            <h2 class="text-3xl font-bold text-center mb-12 text-blue-800">أهدافنا</h2>
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
                <!-- Goal 1 -->
                <div class="bg-white p-6 rounded-lg shadow-md hover:shadow-lg transition duration-300">
                    <div class="text-blue-600 mb-4">
                        <i class="fas fa-handshake text-4xl"></i>
                    </div>
                    <h3 class="text-xl font-bold mb-3">السلام الشامل</h3>
                    <p class="text-gray-700">العمل على تحقيق سلام شامل وعادل ينهي النزاعات المسلحة ويعزز التعايش السلمي بين جميع مكونات الشعب السوداني.</p>
                </div>
                
                <!-- Goal 2 -->
                <div class="bg-white p-6 rounded-lg shadow-md hover:shadow-lg transition duration-300">
                    <div class="text-blue-600 mb-4">
                        <i class="fas fa-balance-scale text-4xl"></i>
                    </div>
                    <h3 class="text-xl font-bold mb-3">العدالة الانتقالية</h3>
                    <p class="text-gray-700">إقامة نظام للعدالة الانتقالية يكشف الحقيقة ويحقق المساءلة ويعوض الضحايا ويضمن عدم تكرار الانتهاكات.</p>
                </div>
                
                <!-- Goal 3 -->
                <div class="bg-white p-6 rounded-lg shadow-md hover:shadow-lg transition duration-300">
                    <div class="text-blue-600 mb-4">
                        <i class="fas fa-university text-4xl"></i>
                    </div>
                    <h3 class="text-xl font-bold mb-3">الدستور الدائم</h3>
                    <p class="text-gray-700">صياغة دستور دائم يعبر عن تطلعات الشعب السوداني ويضمن الحقوق والحريات الأساسية للجميع.</p>
                </div>
                
                <!-- Goal 4 -->
                <div class="bg-white p-6 rounded-lg shadow-md hover:shadow-lg transition duration-300">
                    <div class="text-blue-600 mb-4">
                        <i class="fas fa-vote-yea text-4xl"></i>
                    </div>
                    <h3 class="text-xl font-bold mb-3">الانتقال الديمقراطي</h3>
                    <p class="text-gray-700">إنجاز الانتقال الديمقراطي عبر انتخابات حرة ونزيهة تفضي إلى حكم مدني كامل.</p>
                </div>
                
                <!-- Goal 5 -->
                <div class="bg-white p-6 rounded-lg shadow-md hover:shadow-lg transition duration-300">
                    <div class="text-blue-600 mb-4">
                        <i class="fas fa-chart-line text-4xl"></i>
                    </div>
                    <h3 class="text-xl font-bold mb-3">الاقتصاد الوطني</h3>
                    <p class="text-gray-700">إصلاح الاقتصاد الوطني وتحقيق التنمية المتوازنة التي تخدم جميع مناطق السودان.</p>
                </div>
                
                <!-- Goal 6 -->
                <div class="bg-white p-6 rounded-lg shadow-md hover:shadow-lg transition duration-300">
                    <div class="text-blue-600 mb-4">
                        <i class="fas fa-globe-africa text-4xl"></i>
                    </div>
                    <h3 class="text-xl font-bold mb-3">السياسة الخارجية</h3>
                    <p class="text-gray-700">بناء سياسة خارجية متوازنة تعزز مصالح السودان وتدعم التعاون الإقليمي والدولي.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- News Section -->
    <section id="news" class="py-16 bg-white">
        <div class="container mx-auto px-4">
            <h2 class="text-3xl font-bold text-center mb-12 text-blue-800">أحدث الأخبار</h2>
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
                <!-- News 1 -->
                <div class="news-card bg-white rounded-lg overflow-hidden shadow-md transition duration-300">
                    <img src="https://rhinosd.net/wp-content/uploads/2025/02/%D8%B9%D8%B1%D8%B3-%D8%A7%D9%84%D8%B3%D9%88%D8%AF%D8%A7%D8%A7%D8%A7%D9%86.webp" alt="خبر 1" class="w-full h-48 object-cover">
                    <div class="p-6">
                        <span class="text-sm text-blue-600">15 يونيو 2025</span>
                        <h3 class="text-xl font-bold my-2">التحالف يعلن عن رؤيته للانتقال الديمقراطي</h3>
                        <p class="text-gray-700 mb-4">عقد تحالف السودان التأسيسي مؤتمره الصحفي الأول ليعلن عن رؤيته الشاملة للانتقال الديمقراطي وبناء الدولة المدنية.</p>
                        <a href="#" class="text-blue-600 font-medium hover:text-blue-800">اقرأ المزيد →</a>
                    </div>
                </div>
                
                <!-- News 2 -->
                <div class="news-card bg-white rounded-lg overflow-hidden shadow-md transition duration-300">
                    <img src="https://images.unsplash.com/photo-1521791055366-0d553872125f?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=1469&q=80" alt="خبر 2" class="w-full h-48 object-cover">
                    <div class="p-6">
                        <span class="text-sm text-blue-600">5 يونيو 2025</span>
                        <h3 class="text-xl font-bold my-2">اجتماع مع المبعوث الأممي إلى السودان</h3>
                        <p class="text-gray-700 mb-4">التقى وفد من التحالف بالمبعوث الأممي إلى السودان لمناقشة سبل دعم العملية السياسية والانتقال الديمقراطي.</p>
                        <a href="#" class="text-blue-600 font-medium hover:text-blue-800">اقرأ المزيد →</a>
                    </div>
                </div>
                
                <!-- News 3 -->
                <div class="news-card bg-white rounded-lg overflow-hidden shadow-md transition duration-300">
                    <img src="https://rhinosd.net/wp-content/uploads/2025/07/0b73a929-6c4a-43d5-b5b1-ba8487eb85ff-780x470.jpg">
                    <div class="p-6">
                        <span class="text-sm text-blue-600">28 مايو 2025</span>
                        <h3 class="text-xl font-bold my-2">إطلاق حملة الحوار المجتمعي</h3>
                        <p class="text-gray-700 mb-4">أطلق التحالف حملته للحوار المجتمعي في جميع ولايات السودان لجمع الرؤى حول الدستور المستقبلي.</p>
                        <a href="#" class="text-blue-600 font-medium hover:text-blue-800">اقرأ المزيد →</a>
                    </div>
                </div>
            </div>
            
            <div class="text-center mt-10">
                <a href="#" class="inline-block bg-blue-800 text-white px-6 py-3 rounded-lg font-bold hover:bg-blue-700 transition duration-300">المزيد من الأخبار</a>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="py-16 bg-gray-50">
        <div class="container mx-auto px-4">
            <h2 class="text-3xl font-bold text-center mb-12 text-blue-800">اتصل بنا</h2>
            <div class="flex flex-col lg:flex-row gap-10">
                <div class="lg:w-1/2">
                    <form class="bg-white p-6 rounded-lg shadow-md">
                        <div class="mb-4">
                            <label for="name" class="block text-gray-700 font-medium mb-2">الاسم الكامل</label>
                            <input type="text" id="name" class="w-full px-4 py-2 border border-gray-300 rounded-lg focus:outline-none focus:ring-2 focus:ring-blue-500">
                        </div>
                        <div class="mb-4">
                            <label for="email" class="block text-gray-700 font-medium mb-2">البريد الإلكتروني</label>
                            <input type="email" id="email" class="w-full px-4 py-2 border border-gray-300 rounded-lg focus:outline-none focus:ring-2 focus:ring-blue-500">
                        </div>
                        <div class="mb-4">
                            <label for="phone" class="block text-gray-700 font-medium mb-2">رقم الهاتف</label>
                            <input type="tel" id="phone" class="w-full px-4 py-2 border border-gray-300 rounded-lg focus:outline-none focus:ring-2 focus:ring-blue-500">
                        </div>
                        <div class="mb-4">
                            <label for="message" class="block text-gray-700 font-medium mb-2">الرسالة</label>
                            <textarea id="message" rows="4" class="w-full px-4 py-2 border border-gray-300 rounded-lg focus:outline-none focus:ring-2 focus:ring-blue-500"></textarea>
                        </div>
                        <button type="submit" class="w-full bg-blue-800 text-white py-3 rounded-lg font-bold hover:bg-blue-700 transition duration-300">إرسال الرسالة</button>
                    </form>
                </div>
                
                <div class="lg:w-1/2">
                    <div class="bg-white p-6 rounded-lg shadow-md h-full">
                        <h3 class="text-xl font-bold mb-6 text-blue-800">معلومات التواصل</h3>
                        <div class="space-y-4">
                            <div class="flex items-start">
                                <i class="fas fa-map-marker-alt text-blue-600 mt-1 mr-3"></i>
                                <p>السودان - نيالا - مبنى التحالف التأسيسي</p>
                            </div>
                            <div class="flex items-center">
                                <i class="fas fa-phone-alt text-blue-600 mr-3"></i>
                                <p>+249 123 456 789</p>
                            </div>
                            <div class="flex items-center">
                                <i class="fas fa-envelope text-blue-600 mr-3"></i>
                                <p>info@sudan-alliance.org</p>
                            </div>
                            <div class="flex items-center">
                                <i class="fas fa-globe text-blue-600 mr-3"></i>
                                <p>www.sudan-alliance.org</p>
                            </div>
                        </div>
                        
                        <h3 class="text-xl font-bold mt-8 mb-4 text-blue-800">تابعنا على</h3>
                        <div class="flex space-x-4 space-x-reverse">
                            <a href="#" class="bg-blue-600 text-white w-10 h-10 rounded-full flex items-center justify-center hover:bg-blue-700 transition duration-300">
                                <i class="fab fa-facebook-f"></i>
                            </a>
                            <a href="#" class="bg-blue-400 text-white w-10 h-10 rounded-full flex items-center justify-center hover:bg-blue-500 transition duration-300">
                                <i class="fab fa-twitter"></i>
                            </a>
                            <a href="#" class="bg-red-600 text-white w-10 h-10 rounded-full flex items-center justify-center hover:bg-red-700 transition duration-300">
                                <i class="fab fa-youtube"></i>
                            </a>
                            <a href="#" class="bg-gray-800 text-white w-10 h-10 rounded-full flex items-center justify-center hover:bg-gray-900 transition duration-300">
                                <i class="fab fa-telegram-plane"></i>
                            </a>
                        </div>
                        
                        <div class="mt-8">
                            <h3 class="text-xl font-bold mb-4 text-blue-800">ساعات العمل</h3>
                            <p class="mb-2">الأحد - الخميس: 8 صباحًا - 4 مساءً</p>
                            <p>الجمعة والسبت: إجازة</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Newsletter -->
    <section class="py-12 bg-blue-800 text-white">
        <div class="container mx-auto px-4 text-center">
            <h2 class="text-2xl font-bold mb-4">اشترك في نشرتنا البريدية</h2>
            <p class="mb-6 max-w-2xl mx-auto">ابق على اطلاع بآخر أخبار وأنشطة التحالف من خلال الاشتراك في نشرتنا البريدية</p>
            <form class="flex flex-col sm:flex-row justify-center gap-2 max-w-xl mx-auto">
                <input type="email" placeholder="بريدك الإلكتروني" class="flex-grow px-4 py-3 rounded-lg focus:outline-none text-gray-800">
                <button type="submit" class="bg-white text-blue-800 px-6 py-3 rounded-lg font-bold hover:bg-gray-100 transition duration-300">اشتراك</button>
            </form>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-gray-900 text-white py-12">
        <div class="container mx-auto px-4">
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-8">
                <div>
                    <h3 class="text-xl font-bold mb-4">تحالف السودان التأسيسي</h3>
                    <p class="mb-4">تحالف يضم القوى السياسية والمجتمعية السودانية الملتزمة ببناء سودان ديمقراطي موحد يحقق العدالة والحرية والسلام.</p>
                    <div class="flex space-x-4 space-x-reverse">
                        <a href="#" class="text-gray-400 hover:text-white"><i class="fab fa-facebook-f"></i></a>
                        <a href="#" class="text-gray-400 hover:text-white"><i class="fab fa-twitter"></i></a>
                        <a href="#" class="text-gray-400 hover:text-white"><i class="fab fa-youtube"></i></a>
                        <a href="#" class="text-gray-400 hover:text-white"><i class="fab fa-telegram-plane"></i></a>
                    </div>
                </div>
                
                <div>
                    <h3 class="text-xl font-bold mb-4">روابط سريعة</h3>
                    <ul class="space-y-2">
                        <li><a href="#home" class="text-gray-400 hover:text-white">الرئيسية</a></li>
                        <li><a href="#about" class="text-gray-400 hover:text-white">عن التحالف</a></li>
                        <li><a href="#goals" class="text-gray-400 hover:text-white">أهدافنا</a></li>
                        <li><a href="#news" class="text-gray-400 hover:text-white">الأخبار</a></li>
                        <li><a href="#contact" class="text-gray-400 hover:text-white">اتصل بنا</a></li>
                    </ul>
                </div>
                
                <div>
                    <h3 class="text-xl font-bold mb-4">الموارد</h3>
                    <ul class="space-y-2">
                        <li><a href="#" class="text-gray-400 hover:text-white">الوثائق التأسيسية</a></li>
                        <li><a href="#" class="text-gray-400 hover:text-white">البيانات الصحفية</a></li>
                        <li><a href="#" class="text-gray-400 hover:text-white">التقارير</a></li>
                        <li><a href="#" class="text-gray-400 hover:text-white">المرئيات</a></li>
                        <li><a href="#" class="text-gray-400 hover:text-white">الأسئلة الشائعة</a></li>
                    </ul>
                </div>
                
                <div>
                    <h3 class="text-xl font-bold mb-4">اتصل بنا</h3>
                    <address class="not-italic">
                        <p class="mb-2">السودان - شارع الجامعة</p>
                        <p class="mb-2">مبنى التحالف التأسيسي</p>
                        <p class="mb-2">هاتف: 249910809347</p>
                        <p class="mb-2">بريد إلكتروني: info@sudan-alliance.org</p>
                    </address>
                </div>
            </div>
            
            <div class="border-t border-gray-800 mt-10 pt-6 text-center text-gray-500">
                <p>© 2025 تحالف السودان التأسيسي. جميع الحقوق محفوظة.</p>
            </div>
        </div>
    </footer>

    <!-- Back to Top Button -->
    <button id="back-to-top" class="fixed bottom-6 right-6 bg-blue-800 text-white w-12 h-12 rounded-full shadow-lg hidden items-center justify-center">
        <i class="fas fa-arrow-up"></i>
    </button>

    <script>
        // Mobile Menu Toggle
        const mobileMenuButton = document.getElementById('mobile-menu-button');
        const mobileMenu = document.getElementById('mobile-menu');
        
        mobileMenuButton.addEventListener('click', () => {
            mobileMenu.classList.toggle('hidden');
        });
        
        // Back to Top Button
        const backToTopButton = document.getElementById('back-to-top');
        
        window.addEventListener('scroll', () => {
            if (window.pageYOffset > 300) {
                backToTopButton.classList.remove('hidden');
                backToTopButton.classList.add('flex');
            } else {
                backToTopButton.classList.add('hidden');
                backToTopButton.classList.remove('flex');
            }
        });
        
        backToTopButton.addEventListener('click', () => {
            window.scrollTo({
                top: 0,
                behavior: 'smooth'
            });
        });
        
        // Smooth scrolling for navigation links
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();
                
                const targetId = this.getAttribute('href');
                const targetElement = document.querySelector(targetId);
                
                if (targetElement) {
                    window.scrollTo({
                        top: targetElement.offsetTop - 80,
                        behavior: 'smooth'
                    });
                    
                    // Close mobile menu if open
                    if (!mobileMenu.classList.contains('hidden')) {
                        mobileMenu.classList.add('hidden');
                    }
                }
            });
        });
    </script>
</body>
</html>
