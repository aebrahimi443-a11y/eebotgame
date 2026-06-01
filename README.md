# ⚡ Hokm Telegram Mini App

بازی کارتی حکم با تم مهندسی برق

## امکانات

- 🃏 بازی کامل حکم (۴ نفره، تیمی)
- 🔒 رمز ۴ رقمی با صفحه‌کلید پین‌پد
- 🏠 سیستم اتاق‌ها با نام و شناسه
- ⚡ تم مهندسی برق (مدار، سیگنال، ولتاژ)
- 🌑 دارک تم کامل
- 📱 طراحی موبایل‌فرست

---

## 🚀 دپلوی روی Render

1. یک ریپوزیتوری GitHub جدید بساز
2. فایل `index.html` و `render.yaml` را push کن
3. به [render.com](https://render.com) برو
4. روی **New > Static Site** کلیک کن
5. ریپوزیتوری را وصل کن
6. تنظیمات:
   - **Build Command:** `echo done`
   - **Publish Directory:** `.`
7. Deploy

---

## 🤖 ساخت بات تلگرام

```bash
# با BotFather صحبت کن:
/newbot         → نام و یوزرنیم بده
/newapp         → Web App بساز
# URL را وارد کن: https://your-app.onrender.com
```

---

## 🛠 اجرا در RunMyApp

فایل `index.html` را مستقیم آپلود کن.

---

## ساختار کد

```
index.html
├── CSS Variables (تم برقی)
├── Screen: Lobby     (لیست اتاق‌ها)
├── Screen: Waiting   (انتظار برای بازیکن)
├── Screen: Game      (صفحه بازی)
├── Modal: Create Room (ساخت اتاق + پین‌پد)
├── Modal: Join PIN    (ورود با رمز)
├── Modal: Hokm Select (انتخاب حکم)
└── Modal: Win Screen  (برنده)
```
