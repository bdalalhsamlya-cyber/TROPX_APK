<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <title>تسجيل الدخول - TROPX_APK</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Tajawal:wght@300;400;500;700&display=swap');
        body { font-family: 'Tajawal', sans-serif; }
        .gradient-bg { background: linear-gradient(135deg, #1e3c72 0%, #2a5298 100%); }
    </style>
</head>
<body class="gradient-bg min-h-screen flex items-center justify-center">
    <div class="bg-white p-8 rounded-2xl shadow-xl w-full max-w-md">
        <div class="text-center mb-8">
            <i class="fas fa-cube text-5xl text-blue-600 mb-4"></i>
            <h2 class="text-2xl font-bold text-gray-800">مرحباً بك</h2>
            <p class="text-gray-600">سجل دخولك لاستخدام التطبيق</p>
        </div>
        
        <form>
            <div class="mb-4">
                <label class="block text-gray-700 mb-2">البريد الإلكتروني</label>
                <div class="relative">
                    <i class="fas fa-envelope absolute left-3 top-3 text-gray-400"></i>
                    <input type="email" class="w-full pr-10 pl-10 py-3 border rounded-lg focus:outline-none focus:ring-2 focus:ring-blue-500" placeholder="name@example.com">
                </div>
            </div>
            
            <div class="mb-6">
                <label class="block text-gray-700 mb-2">كلمة المرور</label>
                <div class="relative">
                    <i class="fas fa-lock absolute left-3 top-3 text-gray-400"></i>
                    <input type="password" class="w-full pr-10 pl-10 py-3 border rounded-lg focus:outline-none focus:ring-2 focus:ring-blue-500" placeholder="••••••••">
                    <i class="fas fa-eye absolute left-3 bottom-3 text-gray-400 cursor-pointer"></i>
                </div>
            </div>
            
            <button type="submit" class="w-full bg-blue-600 text-white py-3 rounded-lg font-bold hover:bg-blue-700 transition">
                تسجيل الدخول
            </button>
        </form>
        
        <div class="text-center mt-6">
            <a href="#" class="text-blue-600 hover:underline">نسيت كلمة المرور؟</a>
        </div>
        
        <div class="mt-8 text-center">
            <p class="text-gray-600">ليس لديك حساب؟ <a href="#" class="text-blue-600 font-bold hover:underline">إنشاء حساب</a></p>
        </div>
    </div>
</body>
</html>
