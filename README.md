# DVHOST GitHub Explorer

یک ابزار ساده و مدرن برای جستجوی پروژه‌های محبوب گیت‌هاب بر اساس کلمات کلیدی یا تگ‌ها، با طراحی شبیه به داشبورد گیت‌هاب.

## ✨ ویژگی‌ها

* جستجو بر اساس نام، توضیح یا تگ پروژه
* رتبه‌بندی بر اساس تعداد ستاره‌ها (stars)
* رابط کاربری Dark Mode با استایل GitHub
* پشتیبانی از پارامتر URL (`?q=react`) برای اشتراک‌گذاری جستجوها
* صفحه‌بندی تا 10 صفحه نتایج

## 📦 تکنولوژی‌ها

* HTML / CSS / JS خالص
* GitHub REST API (search/repositories)
* فونت فارسی Vazir

## 🚀 اجرا کردن پروژه

1. پروژه را کلون یا دانلود کنید.
2. فایل `index.html` را در مرورگر خود باز کنید.
3. در صورت نیاز برای افزایش limit می‌توانید GitHub Token خود را در بخش headers اضافه کنید:

```js
const headers = {
  'Authorization': 'Bearer YOUR_GITHUB_TOKEN'
};
```

## 🖼️ اسکرین‌شات

![screenshot](./screenshot-dark-ui.png)

## ✅ TODO

* [ ] پشتیبانی از جستجو با زدن Enter
* [ ] نسخه React با Tailwind و Router
* [ ] حالت Light Mode
* [ ] لودینگ در هنگام دریافت نتایج

## 📄 لایسنس

MIT © [DVHOST CLOUD](https://github.com/dev-ir)
