<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=700&size=28&pause=1000&color=00FF66&center=true&vCenter=true&width=600&height=60&lines=⚡+PARSA+BASIRIAN+%E2%80%A2+PARSA7400;🚀+Developer+Center+%26+Portfolio;🔥+Powered+by+GitHub+REST+API" alt="Typing SVG" />
</p>

<div align="center">

[![GitHub Pages](https://img.shields.io/badge/STATUS-ONLINE_%F0%9F%94%A5-00ff66?style=for-the-badge&logo=githubpages&logoColor=black)](https://parsa7400.github.io)
[![GitHub API](https://img.shields.io/badge/BACKEND-GITHUB_API-1f427f?style=for-the-badge&logo=github&logoColor=white)](https://docs.github.com/en/rest)
[![Author](https://img.shields.io/badge/DEVELOPER-PARSA7400-blueviolet?style=for-the-badge&logo=github)](https://github.com/parsa7400)
[![License](https://img.shields.io/badge/LICENSE-MIT-purple?style=for-the-badge)](LICENSE)

<p align="center">
  <a href="https://parsa7400.github.io"><b>🌐 Explore Live Demo</b></a> •
  <a href="#-core-architecture"><b>🏗️ Architecture</b></a> •
  <a href="#-admin-panel-capabilities"><b>🔐 Admin Panel</b></a>
</p>

</div>

---

## 🎯 نمای کلی پروژه (Overview)

پروژه **Developer Center** پورتفولیوی شخصی و حرفه‌ای **`parsa7400`** است؛ یک سیستم فوق‌العاده سریع، واکنش‌گرا و تعاملی که مرز بین فرانت‌اند مدرن و ابزارهای توسعه‌دهنده را جابجا کرده است. ویژگی کلیدی این پلتفرم، مجهز بودن به یک **پنل مدیریت داخلی امن** است که بدون نیاز به سرور یا دیتابیس مجزا، مستقیماً از طریق **GitHub Contents API** تغییرات را روی مخزن اعمال می‌کند.

---

## 🔐 قابلیت‌های پنل ادمین (Admin Panel Capabilities)

> سیستم مدیریت محتوا کاملاً درون‌برنامه (In-App) تعبیه شده است و با توکن‌های امنیتی گیت‌هاب (`Fine-grained PAT`) توسط **`parsa7400`** مدیریت می‌شود.

| بخش قابل مدیریت | قابلیت‌ها و جزئیات فنی |
| :--- | :--- |
| 👤 **پروفایل کاربری** | ویرایش زنده نام، عنوان شغلی، بیوگرافی کوتاه و متن‌های درباره من. |
| 📊 **سیستم مهارت‌ها (Skills)** | افزودن، ویرایش و حذف مهارت‌ها به همراه کنترل پویای درصدها و نوارها. |
| 🚀 **پروژه‌ها (Projects)** | مدیریت کامل کارت‌های پروژه، لینک‌ها، توضیحات و تکنولوژی‌ها. |
| 🌐 **چندزبانی (i18n)** | کنترل و شخصی‌سازی متن‌های چندزبانه (فارسی / انگلیسی) به صورت آنی. |
| 💾 **همگام‌سازی گیت‌هاب** | کامیت و ذخیره‌سازی خودکار تغییرات در فایل `portfolio.json` با بررسی تداخل SHA. |

---

## ✨ ویژگی‌های برجسته بصری (UI & UX Highlights)

- **📊 انیمیشن‌های شمارش (Count-up & Meters):** لود همزمان اعداد و مترهای درصد مهارت‌ها به محض ورود به بخش مربوطه (`IntersectionObserver`).
- **🧊 کارت‌های سه‌بعدی (3D Tilt Effect):** واکنش تعاملی و سه‌بعدی کارت‌ها نسبت به حرکت موس.
- **🌊 دکمه‌های موج‌دار (Ripple Effects):** افکت‌های کلیک مدرن و چشم‌نواز در سراسر رابط کاربری.
- **⚡ عملکرد فوق‌العاده:** بدون وابستگی به فریم‌ورک‌های سنگین (React/Vue)، کاملاً بهینه با جاوااسکریپت خالص.

---

## 🏗️ ساختار مخزن (Repository Architecture)
```text
parsa7400.github.io/
├── 📄 index.html          # هسته اصلی فرانت‌اند، پنل ادمین و استایل‌های یکپارچه
├── 📊 portfolio.json      # پایگاه داده ساختاریافته JSON (منبع داده‌های سایت)
└── 📜 README.md           # مستندات حرفه‌ای پروژه
