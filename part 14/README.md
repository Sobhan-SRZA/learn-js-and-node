# بخش ۱۴ - امنیت

امنیت یکی از مهم‌ترین بخش‌های توسعه Backend است. یک برنامه Node.js علاوه بر اینکه باید درست کار کند، باید در برابر حملات، سوءاستفاده‌ها و ورود داده‌های مخرب نیز مقاوم باشد.

در این بخش با مهم‌ترین مفاهیم امنیت در Node.js آشنا می‌شویم و یاد می‌گیریم چگونه اطلاعات حساس کاربران را محافظت کنیم، ورودی‌ها را کنترل کنیم و در برابر حملات رایج مانند XSS، CSRF، SQL Injection و NoSQL Injection از برنامه محافظت کنیم.

---

# 📚 فهرست مطالب

## فصل ۱۰۸ - امنیت در Node.js

در این فصل با مفاهیم پایه امنیت و تهدیدهای رایج در برنامه‌های Backend آشنا می‌شویم.

### مباحث این فصل

* امنیت چیست؟
* چرا امنیت در Backend مهم است؟
* Security Threat
* Vulnerability
* Exploit
* Attack Surface
* امنیت Application
* امنیت Server
* امنیت API
* امنیت اطلاعات کاربران
* اطلاعات حساس
* اصل Least Privilege
* Defense in Depth
* Secure by Default
* Input Validation
* Output Encoding
* مدیریت Secretها
* Dependency Security
* به‌روزرسانی Packageها
* مدیریت خطا و اطلاعات حساس
* امنیت در Development و Production
* OWASP
* آشنایی با OWASP Top 10
* تهدیدهای رایج در Node.js

**تمرین‌های زیاد**

**مینی‌پروژه:** بررسی امنیتی یک API ساده Node.js و شناسایی آسیب‌پذیری‌ها

[مشاهده فصل ۱۰۸ ←](./14.1.md)

---

## فصل ۱۰۹ - Hash Password

رمز عبور کاربران نباید به‌صورت خام در Database ذخیره شود. در این فصل با Hash کردن Password و روش صحیح نگهداری رمزهای عبور آشنا می‌شویم.

### مباحث این فصل

* Password Hashing چیست؟
* تفاوت Encryption و Hashing
* چرا نباید Password را Plain Text ذخیره کرد؟
* Hash
* Salt
* Salt چیست؟
* Hash کردن Password
* بررسی Password
* Password Verification
* الگوریتم‌های Hash
* bcrypt
* Argon2
* انتخاب الگوریتم مناسب
* Password Strength
* مدیریت Password در Node.js
* تغییر Password
* Reset Password
* نکات امنیتی Password
* اشتباهات رایج در نگهداری Password

**تمرین‌های زیاد**

**مینی‌پروژه:** ساخت سیستم ثبت‌نام و ورود امن با Password Hashing

[مشاهده فصل ۱۰۹ ←](./14.2.md)

---

## فصل ۱۱۰ - Encryption

Encryption برای محافظت از اطلاعاتی استفاده می‌شود که نباید افراد غیرمجاز بتوانند آن‌ها را مشاهده کنند.

### مباحث این فصل

* Encryption چیست؟
* تفاوت Encryption و Hashing
* تفاوت Encoding و Encryption
* Symmetric Encryption
* Asymmetric Encryption
* Secret Key
* Public Key
* Private Key
* Encryption و Decryption
* AES
* RSA
* Key Management
* Encrypt کردن اطلاعات
* Decrypt کردن اطلاعات
* Encryption در Node.js
* ماژول `crypto`
* مدیریت کلیدهای رمزنگاری
* نکات امنیتی Encryption
* چه زمانی از Encryption استفاده کنیم؟

**تمرین**

**مینی‌پروژه:** ساخت ابزار رمزنگاری و رمزگشایی اطلاعات با Node.js

[مشاهده فصل ۱۱۰ ←](./14.3.md)

---

## فصل ۱۱۱ - Helmet

Helmet مجموعه‌ای از Middlewareها برای افزایش امنیت HTTP Headerهای برنامه‌های Node.js است.

### مباحث این فصل

* Helmet چیست؟
* HTTP Security Headers
* چرا Security Headerها مهم هستند؟
* نصب Helmet
* استفاده از Helmet
* تنظیمات Helmet
* Content Security Policy
* X-Content-Type-Options
* Referrer Policy
* HSTS
* مدیریت Security Headerها
* Helmet در پروژه‌های Node.js
* تنظیم Helmet برای Development
* تنظیم Helmet برای Production
* اشتباهات رایج در استفاده از Helmet

**تمرین**

**مینی‌پروژه:** امن‌سازی Headerهای یک Web Server با Helmet

[مشاهده فصل ۱۱۱ ←](./14.4.md)

---

## فصل ۱۱۲ - Rate Limit

Rate Limiting برای جلوگیری از ارسال بیش‌ازحد درخواست و کاهش حملات مختلف مانند Brute Force و برخی حملات DoS استفاده می‌شود.

### مباحث این فصل

* Rate Limiting چیست؟
* چرا Rate Limit مهم است؟
* Request Limit
* Time Window
* IP-based Rate Limit
* User-based Rate Limit
* Global Rate Limit
* Route-specific Rate Limit
* Login Rate Limit
* Brute Force
* جلوگیری از سوءاستفاده از API
* HTTP 429
* Rate Limit در Node.js
* استفاده از Middleware
* Rate Limit با Redis
* Rate Limit در محیط‌های چندسروری
* تنظیم مناسب Limit
* مدیریت درخواست‌های مجاز و غیرمجاز

**تمرین‌های زیاد**

**مینی‌پروژه:** ساخت Rate Limiter برای API ورود کاربران

[مشاهده فصل ۱۱۲ ←](./14.5.md)

---

## فصل ۱۱۳ - CORS

CORS مشخص می‌کند مرورگرها اجازه دارند درخواست‌های یک Origin به Origin دیگری را چگونه مدیریت کنند.

### مباحث این فصل

* CORS چیست؟
* Same-Origin Policy
* Origin چیست؟
* Same-Origin
* Cross-Origin
* CORS Request
* Simple Request
* Preflight Request
* OPTIONS
* Access-Control-Allow-Origin
* Access-Control-Allow-Methods
* Access-Control-Allow-Headers
* Credentials
* Cookie و CORS
* تنظیم CORS در Node.js
* CORS برای Development
* CORS برای Production
* تنظیم Originهای مجاز
* اشتباهات رایج CORS

**تمرین**

**مینی‌پروژه:** تنظیم CORS امن برای یک REST API

[مشاهده فصل ۱۱۳ ←](./14.6.md)

---

## فصل ۱۱۴ - XSS

XSS یکی از حملات رایج Web است که در آن مهاجم تلاش می‌کند کد مخرب را در محتوای نمایش‌داده‌شده به کاربران اجرا کند.

### مباحث این فصل

* XSS چیست؟
* Cross-Site Scripting
* نحوه وقوع XSS
* Stored XSS
* Reflected XSS
* DOM-based XSS
* JavaScript Injection
* Input Sanitization
* Output Encoding
* جلوگیری از اجرای Script مخرب
* Content Security Policy
* XSS و Cookie
* XSS و `HttpOnly`
* XSS در API
* محافظت از داده‌های کاربران
* تست آسیب‌پذیری XSS
* اشتباهات رایج در مقابله با XSS

**تمرین‌های زیاد**

**مینی‌پروژه:** شناسایی و رفع XSS در یک برنامه Web ساده

[مشاهده فصل ۱۱۴ ←](./14.7.md)

---

## فصل ۱۱۵ - CSRF

CSRF حمله‌ای است که در آن مهاجم تلاش می‌کند کاربر را وادار کند در یک سایت دیگر، درخواست ناخواسته‌ای به برنامه‌ای که در آن احراز هویت شده ارسال کند.

### مباحث این فصل

* CSRF چیست؟
* Cross-Site Request Forgery
* نحوه انجام حمله CSRF
* Browser Cookies
* Session-based Authentication
* CSRF Token
* Synchronizer Token Pattern
* SameSite Cookie
* Origin
* Referer
* محافظت از Requestها
* CSRF در Node.js
* CSRF در API
* تفاوت CSRF و XSS
* چه زمانی CSRF خطرناک است؟
* روش‌های مقابله با CSRF

**تمرین**

**مینی‌پروژه:** محافظت از سیستم انتقال اطلاعات در برابر CSRF

[مشاهده فصل ۱۱۵ ←](./14.8.md)

---

## فصل ۱۱۶ - SQL Injection

SQL Injection یکی از خطرناک‌ترین آسیب‌پذیری‌های Backend است که در اثر ساخت Queryهای ناامن می‌تواند باعث دسترسی یا تغییر غیرمجاز داده‌ها شود.

### مباحث این فصل

* SQL Injection چیست؟
* نحوه شکل‌گیری SQL Injection
* User Input
* Dynamic Query
* Query امن و ناامن
* Parameterized Query
* Prepared Statement
* جلوگیری از SQL Injection
* SQL Injection در Node.js
* SQL Injection در PostgreSQL
* SQL Injection در API
* نقش ORM در کاهش ریسک
* Input Validation
* Principle of Least Privilege
* شناسایی SQL Injection
* تست امنیتی Queryها
* اشتباهات رایج

**تمرین‌های زیاد**

**مینی‌پروژه:** امن‌سازی یک API دارای Queryهای ناامن

[مشاهده فصل ۱۱۶ ←](./14.9.md)

---

## فصل ۱۱۷ - NoSQL Injection

NoSQL Injection مشابه SQL Injection است، اما در Databaseهای NoSQL و Queryهای آن‌ها اتفاق می‌افتد.

### مباحث این فصل

* NoSQL Injection چیست؟
* تفاوت SQL Injection و NoSQL Injection
* نحوه شکل‌گیری NoSQL Injection
* User Input
* Query Object
* Query Manipulation
* MongoDB Injection
* جلوگیری از NoSQL Injection
* Input Validation
* Type Validation
* Sanitization
* استفاده امن از Query
* NoSQL Injection در Node.js
* NoSQL Injection در MongoDB
* نقش ODMها
* شناسایی Query ناامن
* تست امنیتی API
* اشتباهات رایج

**تمرین**

**مینی‌پروژه:** شناسایی و رفع NoSQL Injection در یک API مبتنی بر MongoDB

[مشاهده فصل ۱۱۷ ←](./14.10.md)

---

## فصل ۱۱۸ - Environment Variables

اطلاعات حساس پروژه مانند Secretها، Passwordها و API Keyها نباید مستقیماً داخل Source Code قرار بگیرند.

### مباحث این فصل

* Environment Variable چیست؟
* چرا Environment Variable مهم است؟
* `process.env`
* فایل `.env`
* مدیریت Secretها
* Database URL
* API Key
* JWT Secret
* Encryption Key
* تفاوت Development و Production
* `.gitignore`
* جلوگیری از انتشار Secret
* Secret Management
* مدیریت Environment Variable در Node.js
* Validation متغیرهای محیطی
* Required Environment Variables
* Default Value
* Configuration Management
* اشتباهات رایج در مدیریت Secretها

**تمرین‌های زیاد**

**مینی‌پروژه:** ساخت سیستم Configuration امن برای یک پروژه Node.js

[مشاهده فصل ۱۱۸ ←](./14.11.md)

---

# 🗺️ مسیر یادگیری این بخش

```text
امنیت در Node.js
│
├── مبانی امنیت
│   ├── Vulnerability
│   ├── Exploit
│   ├── Attack Surface
│   └── OWASP
│
├── Password Security
│   ├── Hashing
│   ├── Salt
│   ├── bcrypt
│   └── Argon2
│
├── Encryption
│   ├── Symmetric
│   ├── Asymmetric
│   ├── AES
│   └── RSA
│
├── HTTP Security
│   ├── Helmet
│   ├── Security Headers
│   └── CSP
│
├── Rate Limiting
│   ├── Request Limit
│   ├── Brute Force
│   ├── HTTP 429
│   └── Redis
│
├── CORS
│   ├── Origin
│   ├── Same-Origin Policy
│   ├── Preflight
│   └── Credentials
│
├── XSS
│   ├── Stored XSS
│   ├── Reflected XSS
│   ├── DOM XSS
│   └── Sanitization
│
├── CSRF
│   ├── CSRF Token
│   ├── SameSite
│   └── Request Protection
│
├── SQL Injection
│   ├── Unsafe Query
│   ├── Parameterized Query
│   └── Prepared Statement
│
├── NoSQL Injection
│   ├── Query Manipulation
│   ├── MongoDB
│   └── Sanitization
│
└── Environment Variables
    ├── process.env
    ├── .env
    ├── Secrets
    └── Configuration Management
```

---

# 🎯 هدف بخش ۱۴

در پایان این بخش باید بتوانید:

* مفاهیم پایه امنیت در Backend را درک کنید.
* آسیب‌پذیری و تهدید امنیتی را بشناسید.
* اصول اولیه امنیت برنامه‌های Node.js را رعایت کنید.
* Password کاربران را به‌صورت امن Hash کنید.
* تفاوت Hashing و Encryption را درک کنید.
* از Encryption برای محافظت از اطلاعات حساس استفاده کنید.
* با `crypto` در Node.js آشنا شوید.
* Security Headerها را مدیریت کنید.
* از Helmet استفاده کنید.
* Rate Limiting پیاده‌سازی کنید.
* API را در برابر درخواست‌های بیش‌ازحد محافظت کنید.
* مفهوم CORS را به‌خوبی درک کنید.
* Origin و Preflight Request را بشناسید.
* در برابر XSS از برنامه محافظت کنید.
* در برابر CSRF از برنامه محافظت کنید.
* SQL Injection را بشناسید و از آن جلوگیری کنید.
* NoSQL Injection را بشناسید و از آن جلوگیری کنید.
* Secretها و اطلاعات حساس را در Source Code قرار ندهید.
* Environment Variableها را به‌صورت صحیح مدیریت کنید.
* اصول امنیتی را در پروژه‌های Node.js رعایت کنید.

---

# 🧩 تمرین‌های این بخش

تمرین‌های این بخش به‌صورت مرحله‌ای از مفاهیم پایه امنیت شروع شده و به بررسی و امن‌سازی بخش‌های مختلف یک Backend واقعی می‌رسند.

تمرین‌ها شامل:

* شناسایی آسیب‌پذیری‌های امنیتی
* Hash کردن Password
* بررسی Password
* Encryption و Decryption
* تنظیم Security Headerها
* ساخت Rate Limiter
* تنظیم CORS
* شناسایی XSS
* جلوگیری از XSS
* محافظت در برابر CSRF
* شناسایی SQL Injection
* امن‌سازی Queryهای SQL
* شناسایی NoSQL Injection
* امن‌سازی Queryهای MongoDB
* مدیریت Secretها
* مدیریت Environment Variableها
* بررسی امنیت یک API کامل

تمام تمرین‌ها همراه با **پاسخ تشریحی** ارائه خواهند شد.

---

# 🚀 پروژه‌های پیشنهادی این بخش

برای ترکیب مباحث این بخش، پروژه‌های زیر به‌صورت مرحله‌ای انجام می‌شوند:

1. Password Hashing Service
2. Encryption و Decryption Tool
3. Secure HTTP Server
4. Rate Limiter
5. CORS Configuration
6. XSS Protection Demo
7. CSRF Protection Demo
8. SQL Injection Prevention API
9. NoSQL Injection Prevention API
10. Secure Environment Configuration
11. Security Audit یک API
12. **پروژه نهایی بخش:** امن‌سازی یک Backend کامل Node.js شامل Authentication، Password Hashing، JWT، Rate Limiting، CORS، Security Headers، Validation و مدیریت Secretها

---

# ⏭️ بخش بعدی

بعد از یادگیری امنیت، نوبت به بهبود سرعت، مصرف منابع و مقیاس‌پذیری برنامه‌های Node.js می‌رسد.

در **بخش ۱۵ - Performance** با Performance Optimization، Cache، Redis، Compression، Cluster، Load Balancing و Profiling آشنا خواهیم شد.

[مشاهده بخش ۱۵ - Performance →](../part%2015/README.md)

---

<div align="center">

[بخش بعد ➡️](../part%2015/) • [📚 فهرست مطالب](../readme.md) • [⬅️ بخش قبل](../part%2013/)

</div>
