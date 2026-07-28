# بخش اول — آشنایی با Node.js

# فصل ۳ — اولین برنامه

---

# مقدمه

تا اینجا با Node.js آشنا شدیم و محیط توسعه خود را آماده کردیم.

اکنون زمان آن رسیده است که اولین برنامه Node.js خود را بنویسیم.

این فصل شاید ساده به نظر برسد، اما مفاهیمی که در آن یاد می‌گیرید، پایه و اساس تمام پروژه‌های آینده شما خواهند بود.

در این فصل با نحوه اجرای فایل‌های JavaScript، ساخت اولین پروژه، ترمینال، REPL و فایل `package.json` آشنا خواهیم شد.

---

# اولین پروژه Node.js

یک پوشه جدید ایجاد کنید.

```text
first-node-project
```

سپس وارد پوشه شوید.

```bash
cd first-node-project
```

داخل آن فایلی با نام زیر بسازید.

```text
index.js
```

ساختار پروژه شما باید به شکل زیر باشد.

```text
first-node-project/
│
└── index.js
```

---

# اولین کد Node.js

فایل `index.js` را باز کنید و کد زیر را بنویسید.

```javascript
console.log("Hello Node.js!");
```

این اولین برنامه Node.js شما است.

---

# اجرای برنامه

ترمینال را باز کنید.

اگر داخل پوشه پروژه هستید، دستور زیر را اجرا کنید.

```bash
node index.js
```

خروجی:

```text
Hello Node.js!
```

تبریک!

شما اولین برنامه Node.js خود را اجرا کردید.

---

# پشت صحنه چه اتفاقی افتاد؟

وقتی دستور زیر را اجرا می‌کنید:

```bash
node index.js
```

Node.js مراحل زیر را انجام می‌دهد:

1. فایل را پیدا می‌کند.
2. کد JavaScript را می‌خواند.
3. آن را توسط موتور V8 اجرا می‌کند.
4. خروجی را در ترمینال نمایش می‌دهد.
5. پس از پایان برنامه، فرآیند (Process) را می‌بندد.

به صورت ساده:

```text
index.js
      │
      ▼
Node.js Runtime
      │
      ▼
V8 Engine
      │
      ▼
Execution
      │
      ▼
Terminal Output
```

---

# اگر فایل وجود نداشته باشد

فرض کنید دستور زیر را اجرا کنید.

```bash
node app.js
```

در حالی که فایل `app.js` وجود ندارد.

Node.js خطایی مشابه زیر نمایش می‌دهد.

```text
Error: Cannot find module 'app.js'
```

این یکی از رایج‌ترین خطاهایی است که توسعه‌دهندگان تازه‌کار با آن مواجه می‌شوند.

---

# آیا نام فایل مهم است؟

خیر.

تمام فایل‌های JavaScript را می‌توان اجرا کرد.

مثلاً:

```text
server.js
```

```text
main.js
```

```text
app.js
```

```text
bot.js
```

```text
index.js
```

همگی فایل‌های معتبر JavaScript هستند.

اما در بیشتر پروژه‌ها فایل ورودی معمولاً یکی از نام‌های زیر است:

* `index.js`
* `app.js`
* `server.js`
* `main.js`

---

# اجرای چند دستور

می‌توانید چندین خروجی چاپ کنید.

```javascript
console.log("Hello");
console.log("Node.js");
console.log("Developer");
```

خروجی:

```text
Hello
Node.js
Developer
```

هر بار که `console.log()` فراخوانی می‌شود، یک خط جدید در ترمینال چاپ می‌شود.

---

# چاپ متغیرها

```javascript
const name = "Sobhan";

console.log(name);
```

خروجی:

```text
Sobhan
```

---

# چاپ چند مقدار

```javascript
const language = "JavaScript";
const runtime = "Node.js";

console.log(language, runtime);
```

خروجی:

```text
JavaScript Node.js
```

---

# استفاده از Template Literal

```javascript
const name = "Ali";
const age = 20;

console.log(`My name is ${name} and I'm ${age} years old.`);
```

خروجی:

```text
My name is Ali and I'm 20 years old.
```

در فصل‌های آینده Template Literal را به‌طور کامل بررسی خواهیم کرد.

---

# اجرای فایل‌های مختلف

فرض کنید ساختار زیر را داشته باشید.

```text
project/

├── app.js
├── test.js
├── index.js
└── server.js
```

هر فایل را می‌توانید جداگانه اجرا کنید.

```bash
node app.js
```

یا

```bash
node server.js
```

یا

```bash
node test.js
```

---

# REPL چیست؟

یکی از قابلیت‌های جذاب Node.js محیطی به نام **REPL** است.

REPL مخفف عبارت زیر است:

```text
Read
Evaluate
Print
Loop
```

این محیط برای آزمایش سریع کدها استفاده می‌شود.

برای ورود به REPL کافی است دستور زیر را اجرا کنید.

```bash
node
```

خروجی مشابه زیر خواهد بود.

```text
>
```

اکنون هر کد JavaScript را می‌توانید اجرا کنید.

مثلاً:

```javascript
2 + 5
```

خروجی:

```text
7
```

یا:

```javascript
const name = "Node";
```

سپس:

```javascript
name
```

خروجی:

```text
Node
```

---

# خروج از REPL

برای خروج می‌توانید یکی از روش‌های زیر را استفاده کنید.

روش اول:

```text
.exit
```

روش دوم:

```
Ctrl + C
```

دو بار پشت سر هم.

---

# REPL چه کاربردی دارد؟

REPL برای موارد زیر بسیار مفید است:

* تست سریع کدها
* آزمایش توابع
* بررسی خروجی دستورات
* یادگیری JavaScript
* تست ماژول‌ها
* اشکال‌زدایی اولیه

بسیاری از توسعه‌دهندگان حرفه‌ای برای آزمایش ایده‌های کوچک از REPL استفاده می‌کنند.

---

# ساخت package.json

تقریباً تمام پروژه‌های Node.js دارای فایلی به نام `package.json` هستند.

این فایل اطلاعات پروژه را نگهداری می‌کند.

برای ساخت آن دستور زیر را اجرا کنید.

```bash
npm init
```

Node.js چند سؤال از شما می‌پرسد.

از جمله:

* نام پروژه
* نسخه
* توضیحات
* فایل اصلی
* نویسنده
* مجوز

در پایان فایل `package.json` ساخته می‌شود.

---

# ساخت سریع package.json

اگر نمی‌خواهید به سؤالات پاسخ دهید، از دستور زیر استفاده کنید.

```bash
npm init -y
```

خروجی:

```json
{
  "name": "first-node-project",
  "version": "1.0.0",
  "description": "",
  "main": "index.js",
  "scripts": {
    "test": "echo \"Error: no test specified\" && exit 1"
  },
  "keywords": [],
  "author": "",
  "license": "ISC"
}
```

در فصل‌های آینده تمام بخش‌های این فایل را به‌صورت کامل بررسی خواهیم کرد.

---

# ساختار پروژه

پس از ساخت `package.json` پروژه شما به شکل زیر خواهد بود.

```text
first-node-project/

├── index.js
└── package.json
```

تقریباً تمام پروژه‌های Node.js از همین ساختار اولیه شروع می‌شوند.

---

# اجرای برنامه پس از ساخت package.json

وجود فایل `package.json` تغییری در نحوه اجرای برنامه ایجاد نمی‌کند.

همچنان از دستور زیر استفاده می‌کنیم.

```bash
node index.js
```

در فصل‌های بعد یاد می‌گیریم چگونه برنامه را با استفاده از `npm run` اجرا کنیم.

---

# اشتباهات رایج

❌ اجرای دستور `node` در پوشه اشتباه

❌ فراموش کردن پسوند `.js` در نام فایل

❌ تایپ اشتباه نام فایل هنگام اجرا

❌ حذف تصادفی فایل `package.json`

❌ ویرایش مستقیم فایل `package.json` بدون شناخت ساختار آن

---

# نکات حرفه‌ای

* در بیشتر پروژه‌ها فایل ورودی را `index.js` یا `server.js` نام‌گذاری می‌کنند.
* از REPL برای آزمایش کدهای کوتاه استفاده کنید و برای پروژه‌های واقعی از فایل‌های `.js`.
* تقریباً هر پروژه Node.js باید دارای فایل `package.json` باشد.
* از همان ابتدا ساختار پروژه‌های خود را مرتب و ساده نگه دارید.

---

# جمع‌بندی

در این فصل یاد گرفتیم که:

* اولین فایل Node.js را ایجاد کنیم.
* برنامه را با دستور `node` اجرا کنیم.
* از `console.log()` برای نمایش خروجی استفاده کنیم.
* فایل‌های مختلف را اجرا کنیم.
* با محیط REPL آشنا شویم.
* فایل `package.json` را ایجاد کنیم.
* ساختار اولیه یک پروژه Node.js را بشناسیم.

اکنون آماده هستیم تا از فصل بعد وارد یادگیری JavaScript مخصوص Node.js شویم و مفاهیم پایه زبان را از دید یک توسعه‌دهنده Node.js بررسی کنیم.

---

# تمرین‌ها

### تمرین ۱

فایلی به نام `hello.js` ایجاد کنید که متن زیر را چاپ کند.

```text
Welcome to Node.js
```

<details>
<summary>پاسخ</summary>

```javascript
console.log("Welcome to Node.js");
```

اجرا:

```bash
node hello.js
```

</details>

---

### تمرین ۲

برنامه‌ای بنویسید که نام، سن و شغل شما را در سه خط جداگانه نمایش دهد.

<details>
<summary>پاسخ</summary>

```javascript
console.log("Sobhan");
console.log(20);
console.log("Node.js Developer");
```

</details>

---

### تمرین ۳

با استفاده از متغیرها، جمله زیر را چاپ کنید.

```text
My favorite language is JavaScript.
```

<details>
<summary>پاسخ</summary>

```javascript
const language = "JavaScript";

console.log(`My favorite language is ${language}.`);
```

</details>

---

### تمرین ۴

فایل `package.json` را بدون پاسخ دادن به سؤالات ایجاد کنید.

<details>
<summary>پاسخ</summary>

```bash
npm init -y
```

</details>

---

### تمرین ۵

وارد محیط REPL شوید، مقدار `15 * 8` را محاسبه کنید و سپس از محیط خارج شوید.

<details>
<summary>پاسخ</summary>

ورود:

```bash
node
```

محاسبه:

```javascript
15 * 8
```

خروج:

```text
.exit
```

یا دو بار `Ctrl + C`.

</details>

---

# پروژه کوچک

## پروژه: معرفی خود در Node.js

### هدف

ساخت اولین برنامه واقعی و آشنایی با اجرای فایل‌های JavaScript.

### مراحل

1. پوشه‌ای با نام `my-profile` ایجاد کنید.
2. فایل `index.js` را داخل آن بسازید.
3. فایل `package.json` را با دستور `npm init -y` ایجاد کنید.
4. برنامه‌ای بنویسید که اطلاعات زیر را نمایش دهد:

   * نام
   * سن
   * زبان برنامه‌نویسی مورد علاقه
   * نسخه Node.js (با استفاده از `process.version`)
5. برنامه را با دستور زیر اجرا کنید:

```bash
node index.js
```

### چالش

برنامه را به‌گونه‌ای تغییر دهید که خروجی آن به صورت یک پیام خوشامدگویی قالب‌بندی‌شده نمایش داده شود و علاوه بر اطلاعات بالا، نام سیستم‌عامل (`process.platform`) و معماری پردازنده (`process.arch`) را نیز چاپ کند. سعی کنید برای ساخت پیام از **Template Literal** استفاده کنید؛ این تمرین مقدمه‌ای برای مباحث فصل‌های آینده خواهد بود.
