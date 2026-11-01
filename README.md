<div align="center">

# ⚡ Parsa Basirian | Developer Center & Portfolio
### *High-Performance, Dynamic Personal Portfolio with a GitHub-Powered Admin Panel*

[![GitHub Pages](https://img.shields.io/badge/Status-Live%20%F0%9F%94%A5-success?style=for-the-badge&logo=githubpages)](https://parsa7400.github.io)
[![GitHub API](https://img.shields.io/badge/Backend-GitHub%20REST%20API-blue?style=for-the-badge&logo=github)](https://docs.github.com/en/rest)
[![JavaScript](https://img.shields.io/badge/Frontend-Vanilla%20JS%20(ES6+)-yellow?style=for-the-badge&logo=javascript)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![License: MIT](https://img.shields.io/badge/License-MIT-purple.svg?style=for-the-badge)](LICENSE)

[🌐 مشاهده زنده وب‌سایت (Live Demo)](https://parsa7400.github.io)

</div>

---

## 🌟 درباره پروژه (About Project)

این پروژه یک **پورتفولیوی شخصی و مرکز توسعه فوق‌العاده مدرن، تعاملی و واکنش‌گرا** است که بر روی **GitHub Pages** میزبانی می‌شود. 
ویژگی منحصربه‌فرد این سیستم، داشتن یک **پنل مدیریت (Admin Panel) داخلی و امن** است که مستقیماً از طریق **GitHub Contents API** به مخزن متصل شده و به شما اجازه می‌دهد تمام اطلاعات سایت (پروفایل، مهارت‌ها، پروژه‌ها و متن‌ها) را به صورت زنده، بدون نیاز به هاست مجزا یا دیتابیس سنگین، مستقیماً در گیت‌هاب ویرایش و ذخیره کنید.

---

## 🚀 ویژگی‌های کلیدی (Key Features)

- **🔥 پنل ادمین اختصاصی با اتصال مستقیم به گیت‌هاب:** مدیریت کامل محتوا از طریق API و ذخیره خودکار تغییرات در قالب Commit مستقیم روی مخزن با استفاده از Fine-grained PAT.
- **📊 انیمیشن‌های روان و پویا (Count-up & Meter):** انیمیشن‌های شمارش اعداد و درصد مهارت‌ها همزمان با لود اسکرول صفحه (`IntersectionObserver`).
- **🧊 جلوه‌های بصری سه‌بعدی (3D Tilt Cards):** کارت‌های تعاملی جذاب با افکت‌های حرکتی موس و دکمه‌های موج‌دار (`Ripple Effects`).
- **🌐 چندزبانه هوشمند (i18n):** قابلیت سوئیچ و مدیریت کامل متن‌ها و محتوا به زبان‌های مختلف (فارسی و انگلیسی).
- **⚡ عملکرد فوق‌العاده سریع:** پیاده‌سازی شده با Vanilla JavaScript خالص بدون وابستگی به فریم‌ورک‌های سنگین.

---

## 🛠️ تکنولوژی‌های استفاده شده (Tech Stack)

* **فرانت‌اند:** HTML5, CSS3, Modern ES6+ JavaScript
* **لایه داده:** Structured JSON (`portfolio.json`)
* **ارتباطات و احراز هویت:** GitHub REST API (Fine-grained Tokens with Contents Read/Write permissions)
* **میزبانی و هاستینگ:** GitHub Pages

---

## 📁 ساختار مخزن (Project Structure)
```text
parsa7400.github.io/
├── index.html          # صفحه اصلی پورتفولیو و پنل ادمین یکپارچه
├── portfolio.json      # پایگاه داده ساختاریافته و مرکزی محتوای سایت
└── README.md           # مستندات پروژه
