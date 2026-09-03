# بخش ۹ - Package Manager

در این بخش با **Package Managerها در Node.js** و ابزارهایی که برای مدیریت Packageها و Dependencyهای پروژه استفاده می‌شوند آشنا می‌شویم.

در پروژه‌های واقعی Node.js معمولاً از کتابخانه‌ها و Packageهای مختلف استفاده می‌کنیم. Package Managerها به ما کمک می‌کنند این وابستگی‌ها را نصب، حذف، به‌روزرسانی و مدیریت کنیم و ساختار پروژه را به شکل استاندارد نگه داریم.

در این بخش ابتدا با npm و فایل `package.json` آشنا می‌شویم و سپس به سراغ Versioning، نصب Package، ساخت Package و در نهایت انتشار Package در npm می‌رویم.

---

# 📚 فهرست مطالب

## فصل ۶۷ - npm

در این فصل با npm و نقش آن در اکوسیستم Node.js آشنا می‌شویم.

* npm چیست؟
* Node Package Manager
* نصب و بررسی npm
* دستورات مهم npm
* ایجاد پروژه با npm
* نصب Dependencyها
* حذف Dependencyها
* به‌روزرسانی Packageها
* جستجو و استفاده از Packageها

**تمرین**

[مشاهده فصل ۶۷ ←](./9.1.md)

---

## فصل ۶۸ - package.json

در این فصل با فایل `package.json` و اطلاعاتی که برای مدیریت یک پروژه Node.js در آن قرار می‌گیرد آشنا می‌شویم.

* `package.json` چیست؟
* ساخت `package.json`
* `npm init`
* `npm init -y`
* `name`
* `version`
* `description`
* `main`
* `scripts`
* `keywords`
* `author`
* `license`
* `dependencies`
* `devDependencies`
* `engines`

**تمرین**

[مشاهده فصل ۶۸ ←](./9.2.md)

---

## فصل ۶۹ - package-lock

در این فصل با `package-lock.json` و نقش آن در ثبت دقیق Dependencyهای پروژه آشنا می‌شویم.

* `package-lock.json` چیست؟
* چرا package-lock ایجاد می‌شود؟
* تفاوت `package.json` و `package-lock.json`
* ثبت Version دقیق Packageها
* Dependency Tree
* اهمیت Lock File
* نصب Dependencyها بر اساس Lock File

**تمرین**

[مشاهده فصل ۶۹ ←](./9.3.md)

---

## فصل ۷۰ - Semantic Version

در این فصل با Semantic Versioning یا SemVer آشنا می‌شویم و یاد می‌گیریم Versionهای Packageها چگونه مشخص می‌شوند.

* Semantic Versioning چیست؟
* Major
* Minor
* Patch
* Version Range
* `^`
* `~`
* Version ثابت
* Breaking Changes
* سازگاری Versionها

**تمرین**

[مشاهده فصل ۷۰ ←](./9.4.md)

---

## فصل ۷۱ - نصب Package

در این فصل روش‌های مختلف نصب Packageها و مدیریت Dependencyهای پروژه را یاد می‌گیریم.

* نصب Package
* نصب Local
* نصب Global
* `npm install`
* `npm uninstall`
* `npm update`
* نصب Version مشخص
* نصب چند Package
* `dependencies`
* `devDependencies`
* نصب Package به‌عنوان Development Dependency

**تمرین**

[مشاهده فصل ۷۱ ←](./9.5.md)

---

## فصل ۷۲ - ساخت Package

در این فصل یاد می‌گیریم چگونه یک Package قابل استفاده مجدد برای Node.js ایجاد کنیم.

* Package چیست؟
* ساختار Package
* ایجاد پروژه Package
* `package.json`
* Entry Point
* Export کردن کد
* تست Package
* مدیریت Version
* آماده‌سازی Package برای انتشار

**تمرین**

[مشاهده فصل ۷۲ ←](./9.6.md)

---

## فصل ۷۳ - انتشار Package در npm

در این فصل یاد می‌گیریم چگونه Package ساخته‌شده را در Registry مربوط به npm منتشر کنیم تا دیگران نیز بتوانند از آن استفاده کنند.

* آماده‌سازی Package
* ساخت حساب npm
* ورود به npm
* `npm login`
* بررسی Package
* نام Package
* Version
* `npm publish`
* به‌روزرسانی Package
* انتشار Version جدید
* حذف یا مدیریت Package

**پروژه**

[مشاهده فصل ۷۳ ←](./9.7.md)

---

# 🗺️ مسیر یادگیری این بخش

```text
بخش ۹ - Package Manager
│
├── فصل ۶۷ - npm
│   ├── npm چیست؟
│   ├── دستورات مهم
│   ├── نصب Package
│   ├── حذف Package
│   └── به‌روزرسانی Package
│
├── فصل ۶۸ - package.json
│   ├── ساختار
│   ├── scripts
│   ├── dependencies
│   ├── devDependencies
│   └── تنظیمات پروژه
│
├── فصل ۶۹ - package-lock
│   ├── package-lock.json
│   ├── Dependency Tree
│   └── Lock File
│
├── فصل ۷۰ - Semantic Version
│   ├── Major
│   ├── Minor
│   ├── Patch
│   ├── ^
│   └── ~
│
├── فصل ۷۱ - نصب Package
│   ├── Local
│   ├── Global
│   ├── npm install
│   ├── npm uninstall
│   └── npm update
│
├── فصل ۷۲ - ساخت Package
│   ├── Package
│   ├── package.json
│   ├── Entry Point
│   ├── Export
│   └── Version
│
└── فصل ۷۳ - انتشار Package در npm
    ├── npm login
    ├── npm publish
    ├── Version جدید
    └── مدیریت Package
```

---

# 🎯 هدف بخش ۹

در پایان این بخش باید بتوانید:

* مفهوم Package Manager را درک کنید.
* با npm کار کنید.
* پروژه Node.js را با npm مدیریت کنید.
* فایل `package.json` ایجاد و مدیریت کنید.
* بخش‌های مختلف `package.json` را بشناسید.
* Dependency و Development Dependency را از یکدیگر تشخیص دهید.
* نقش `package-lock.json` را در پروژه درک کنید.
* Dependencyهای پروژه را نصب، حذف و به‌روزرسانی کنید.
* Package را در Version مشخص نصب کنید.
* مفهوم Semantic Versioning را درک کنید.
* تفاوت Major، Minor و Patch را بدانید.
* Version Rangeهای `^` و `~` را درک کنید.
* یک Package برای Node.js ایجاد کنید.
* ساختار استاندارد یک Package را بشناسید.
* Package خود را برای انتشار آماده کنید.
* Package را در npm منتشر کنید.
* Version جدید برای Package منتشر کنید.
* از Packageهای ساخته‌شده توسط دیگران در پروژه‌های Node.js استفاده کنید.

---

# 🧩 تمرین‌های این بخش

در طول این بخش تمرین‌های مختلفی برای کار با npm و Packageها ارائه می‌شود.

تمرین‌ها از دستورات ساده npm شروع شده و به‌تدریج به مدیریت Dependencyها، Semantic Versioning، ساخت Package و انتشار Package در npm می‌رسند.

هدف تمرین‌ها این است که بتوانید **مدیریت Dependencyهای یک پروژه واقعی Node.js** را به‌صورت عملی انجام دهید.

---

# 🚀 پروژه پیشنهادی این بخش

در پایان این بخش یک Package کاربردی Node.js ایجاد می‌کنیم و مراحل مختلف آن را از ابتدا تا انتشار دنبال خواهیم کرد.

مراحل پروژه:

* ایجاد پروژه
* طراحی ساختار Package
* ایجاد `package.json`
* نوشتن کد Package
* Export کردن قابلیت‌ها
* تست Package
* تعیین Version
* آماده‌سازی برای انتشار
* انتشار در npm
* انتشار Version جدید

---

# ⏭️ بخش بعدی

پس از یادگیری Package Managerها، در بخش بعدی وارد **مباحث شبکه در Node.js** می‌شویم و با HTTP، HTTPS، DNS، TCP/IP، Socket، WebSocket، REST API و GraphQL آشنا خواهیم شد.

[بخش ۱۰ - شبکه →](../part%2010/README.md)

---

<div align="center">

[بخش بعد ➡️](../part%2010/) • [📚 فهرست مطالب](../readme.md) • [⬅️ بخش قبل](../part%208/)

</div>
