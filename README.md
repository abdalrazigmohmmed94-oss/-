<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>VOGUE Youth |متجر التركي للملابس والماركات الكمبالية</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://fonts.googleapis.com/css2?family=Cairo:wght@400;700&display=swap" rel="stylesheet">
    <style>
        body { font-family: 'Cairo', sans-serif; background-color: #f8f9fa; }
        .glass { background: rgba(255, 255, 255, 0.8); backdrop-filter: blur(10px); }
    </style>
</head>
<body>

    <nav class="sticky top-0 z-50 glass border-b border-gray-200 p-4 flex justify-between items-center">
        <h1 class="text-2xl font-bold tracking-tighter text-black">VOGUE <span class="text-indigo-600">YOUTH</span></h1>
        <div class="space-x-4 space-x-reverse">
            <button class="relative">
                <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M16 11V7a4 4 0 00-8 0v4M5 9h14l1 12H4L5 9z" />
                </svg>
            </button>
        </div>
    </nav>

    <header class="relative h-64 bg-gray-900 flex items-center justify-center text-white overflow-hidden">
        <img src="https://images.unsplash.com/photo-1523381235212-d73f8613ef1e?auto=format&fit=crop&w=800&q=80" class="absolute inset-0 w-full h-full object-cover opacity-50" alt="Fashion">
        <div class="relative text-center px-4">
            <h2 class="text-3xl font-extrabold mb-2">تشكيلة الشتاء الحصرية</h2>
            <p class="text-sm opacity-90">كن فريداً، كن أنت.</p>
        </div>
    </header>

    <main class="p-4 grid grid-cols-2 gap-4">
        <div class="bg-white rounded-2xl overflow-hidden shadow-sm border border-gray-100">
            <img src="https://images.unsplash.com/photo-1552374196-1ab2a1c593e8?auto=format&fit=crop&w=400&q=80" class="w-full h-48 object-cover">
            <div class="p-3">
                <h3 class="font-bold text-gray-800 text-sm">سترة "أوربان" قطنية</h3>
                <p class="text-indigo-600 font-bold mt-1">ج.س4000 </p>
                <button class="w-full mt-3 bg-black text-white py-2 rounded-lg text-xs font-bold uppercase">إضافة للسلة</button>
            </div>
        </div>

        <div class="bg-white rounded-2xl overflow-hidden shadow-sm border border-gray-100">
            <img src="https://images.unsplash.com/photo-1503342217505-b0a15ec3261c?auto=format&fit=crop&w=400&q=80" class="w-full h-48 object-cover">
            <div class="p-3">
                <h3 class="font-bold text-gray-800 text-sm">تيشيرت "ليميتد"</h3>
                <p class="text-indigo-600 font-bold mt-1">ج.س30000 </p>
                <button class="w-full mt-3 bg-black text-white py-2 rounded-lg text-xs font-bold uppercase">إضافة للسلة</button>
            </div>
        </div>
    </main>

    <footer class="bg-white mt-10 p-8 border-t border-gray-200">
        <div class="text-center">
            <h3 class="font-bold text-lg mb-4">تواصل معنا</h3>
            <div class="flex justify-center gap-6 mb-6">
                <a href="https://wa.me/123456789" class="text-green-500 font-bold text-sm">0961920882</a>
                <a href="https://instagram.com" class="text-pink-500 font-bold text-sm">abdo.M</a>
                <a href="mailto:info@vogue.com" class="text-blue-500 font-bold text-sm">abdalrazigmohmmed94@gmail.com</a>
            </div>
            <p class="text-gray-400 text-xs">© 2026 VOGUE YOUTH. جميع الحقوق محفوظة.</p>
        </div>
    </footer>

</body>
</html>
