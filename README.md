# NUMI — Personal Profile Site
## راهنمای کامل نصب و شخصی‌سازی

---

## ساختار فایل‌ها

```
numi-site/
├── index.html          ← فایل اصلی سایت
├── config.js           ← تمام تنظیمات قابل ویرایش
├── images/
│   ├── background.png  ← بک‌گراند سایت (جایگزین کن)
│   ├── profile.png     ← عکس پروفایل (جایگزین کن)
│   └── logo.png        ← لوگوی NUMI (جایگزین کن)
├── audio/
│   └── music.mp3       ← موزیک سایت (جایگزین کن)
└── fonts/
    ├── Vazirmatn.ttf   ← فونت فارسی
    └── Sora.ttf        ← فونت انگلیسی
```

---

## چطور شخصی‌سازی کنی؟

### 1. تغییر اطلاعات شخصی
فایل `config.js` رو باز کن:

```js
profile: {
  name: "MOBIN",           // اسمت
  age: 17,
  city: "رشت",
  province: "گیلان",
  birthYear: 2009,
  birthMonth: 6,           // ماه تولد (عدد)
  birthDay: 13,
  bio: "درود ...",         // متن بیو
  statusText: "آنلاین",
}
```

### 2. تغییر لینک‌های سوشال
```js
socials: {
  telegram: "https://t.me/USERNAME",
  instagram: "https://instagram.com/USERNAME",
  github: "https://github.com/USERNAME",
}
```

### 3. تغییر عکس پروفایل
فایل `images/profile.png` رو با عکس خودت عوض کن.

### 4. تغییر بک‌گراند
فایل `images/background.png` رو با بک‌گراند دلخواه عوض کن.

### 5. تغییر موزیک
فایل `audio/music.mp3` رو با موزیک دلخواهت عوض کن.

### 6. تغییر فونت
- فارسی: `fonts/Vazirmatn.ttf` رو عوض کن
- انگلیسی: `fonts/Sora.ttf` رو عوض کن

### 7. تغییر متن‌های تایپ شونده
```js
typingTexts: [
  "Developer & Designer",
  "Creative Mind",
  "هر چیزی که میخوای",
],
```

### 8. تغییر رمز ادمین
```js
admin: {
  password: "رمز_جدید",
}
```

---

## دانلود فونت‌ها

### Vazirmatn (فارسی)
https://github.com/rastikerdar/vazirmatn/releases

### Sora (انگلیسی)
https://fonts.google.com/specimen/Sora
(دانلود → Extract → فایل Sora-Regular.ttf رو بذار تو پوشه fonts با اسم Sora.ttf)

---

## اجرا روی سرور

برای اینکه بازدید واقعی ذخیره بشه، سایت رو روی هاست یا سرور بذار.
پیشنهاد رایگان: **Netlify**, **Vercel**, یا **GitHub Pages**

---

## پنل ادمین

1. پایین صفحه Messages بزن "ورود ادمین"
2. رمز رو وارد کن (پیش‌فرض: `mobin1234`)
3. زیر هر پیام دکمه "جواب" ظاهر میشه

---

Made with by NUMB
