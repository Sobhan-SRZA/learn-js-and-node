# JavaScript چیست؟

قبل از اینکه Node.js را یاد بگیریم باید بدانیم JavaScript دقیقا چیست.

JavaScript یک زبان برنامه‌نویسی سطح بالا (High-Level Programming Language) است که در ابتدا برای ایجاد صفحات وب پویا ساخته شد، اما امروزه تقریباً در هر جایی استفاده می‌شود.

امروزه با JavaScript می‌توان:

- Backend توسعه داد.
- Frontend توسعه داد.
- برنامه دسکتاپ نوشت.
- اپلیکیشن موبایل ساخت.
- ربات Discord ساخت.
- ربات Telegram ساخت.
- REST API توسعه داد.
- Microservice ساخت.
- CLI Tool نوشت.
- Game Server توسعه داد.
- پروژه‌های هوش مصنوعی را مدیریت کرد.

به همین دلیل JavaScript یکی از محبوب‌ترین زبان‌های برنامه‌نویسی جهان است.

---

## JavaScript چگونه اجرا می‌شود؟

JavaScript به تنهایی اجرا نمی‌شود.

برای اجرای آن به یک Runtime نیاز داریم.

مشهورترین Runtimeها:

- Browser
- Node.js
- Bun
- Deno

هر Runtime امکانات مخصوص خودش را دارد.

مثلاً Browser به DOM دسترسی دارد.

اما Node.js به File System دسترسی دارد.

---

## JavaScript مرورگر

در مرورگر می‌توان به:

- document
- window
- navigator
- localStorage

دسترسی داشت.

مثال:

```js
document.title = "Hello";
```

این کد فقط داخل مرورگر اجرا می‌شود.

---

## JavaScript داخل Node.js

در Node خبری از document و window نیست.

در عوض امکاناتی مانند:

- File System
- HTTP Server
- Process
- OS
- Path
- Stream
- Buffer

وجود دارند.

مثال:

```js
console.log(process.version);
```

یا

```js
const fs = require("fs");
```

این کدها داخل مرورگر اجرا نمی‌شوند.

---

## آیا باید JavaScript مرورگر را بلد باشیم؟

خیر.

اگر هدفت Backend است، نیازی نیست:

- DOM
- HTML Events
- CSS Manipulation
- Browser API

را بلد باشی.

در این آموزش فقط JavaScript موردنیاز Node.js را یاد می‌گیری.

---

## تمرین ۱

Node.js را نصب کن.

سپس دستور زیر را اجرا کن.

```bash
node -v
```

اگر نسخه Node نمایش داده شد، یعنی نصب موفق بوده است.

---

## تمرین ۲

فایل زیر را بساز.

```text
index.js
```

داخل آن بنویس:

```js
console.log("Hello Node.js");
```

سپس اجرا کن:

```bash
node index.js
```

خروجی:

```text
Hello Node.js
```

---

## تمرین ۳

نسخه Node را چاپ کن.

راهنمایی:

از شیء process استفاده کن.

---

## پاسخ تمرین

```js
console.log(process.version);
```

---

## پروژه کوچک

یک فایل بساز.

```text
about.js
```

اطلاعات زیر را چاپ کن.

- نام
- سن
- زبان برنامه‌نویسی موردعلاقه
- نسخه Node

نمونه خروجی:

```text
Name : Sobhan
Age : 20
Favorite Language : JavaScript
Node : v24.4.1
```

در پایان این فصل با مفهوم JavaScript، تفاوت آن با JavaScript مرورگر و نقش Node.js به‌عنوان Runtime آشنا شدی و اولین برنامه Node.js خود را اجرا کردی.