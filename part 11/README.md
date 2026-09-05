# بخش ۱۱ - ساخت سرور

در این بخش وارد دنیای واقعی Backend با Node.js می‌شویم و یاد می‌گیریم چگونه یک Server کاربردی بسازیم و آن را برای دریافت و پردازش درخواست‌های کاربران آماده کنیم.

در این بخش مفاهیمی مانند Routing، Middleware، MVC، Validation، Authentication، Authorization، JWT، Cookie، Session، Upload و Logging را مرحله‌به‌مرحله یاد می‌گیریم و در کنار هر مبحث، تمرین و پروژه‌های عملی خواهیم داشت.

---

# 📚 فهرست مطالب

## فصل ۸۲ - Web Server

در این فصل با مفهوم Web Server و نحوه ساخت یک Server ساده با Node.js آشنا می‌شویم.

### مباحث این فصل

* Web Server چیست؟
* Client و Server
* نحوه دریافت Request
* نحوه ارسال Response
* HTTP Server در Node.js
* ماژول `http`
* ایجاد Server
* Port
* Request Object
* Response Object
* HTTP Method
* HTTP Status Code
* Header
* Body
* ارسال JSON
* ارسال HTML
* مدیریت خطاهای Server

**تمرین‌های زیاد**

**مینی‌پروژه:** ساخت Web Server ساده با Node.js

[مشاهده فصل ۸۲ ←](./11.1.md)

---

## فصل ۸۳ - Routing

Routing مشخص می‌کند هر درخواست به کدام بخش از برنامه ارسال شود.

### مباحث این فصل

* Routing چیست؟
* Route چیست؟
* Endpoint
* Path
* HTTP Method
* GET Route
* POST Route
* PUT Route
* PATCH Route
* DELETE Route
* Route Parameters
* Query Parameters
* Route Handler
* مدیریت Routeهای مختلف
* Route Not Found
* ساخت Router ساده با Node.js

**تمرین‌های زیاد**

**مینی‌پروژه:** ساخت Router برای یک API

[مشاهده فصل ۸۳ ←](./11.2.md)

---

## فصل ۸۴ - Middleware

Middleware یکی از مهم‌ترین مفاهیم Backend است و در بسیاری از قابلیت‌های Server مورد استفاده قرار می‌گیرد.

### مباحث این فصل

* Middleware چیست؟
* نحوه اجرای Middleware
* Request و Response
* مفهوم `next`
* Middleware عمومی
* Middleware اختصاصی
* چند Middleware
* ترتیب اجرای Middlewareها
* Authentication Middleware
* Authorization Middleware
* Validation Middleware
* Logging Middleware
* Error Middleware
* ساخت Middleware با Node.js

**تمرین‌های زیاد**

**مینی‌پروژه:** ساخت سیستم Middleware ساده

[مشاهده فصل ۸۴ ←](./11.3.md)

---

## فصل ۸۵ - MVC

در این فصل با معماری MVC آشنا می‌شویم و یاد می‌گیریم چگونه کدهای Server را ساختاریافته و قابل نگهداری بنویسیم.

### مباحث این فصل

* MVC چیست؟
* Model
* View
* Controller
* نقش هر بخش
* جداسازی مسئولیت‌ها
* ارتباط Controller و Model
* ارتباط Controller و View
* ساختار پروژه MVC
* Routing در MVC
* Service Layer
* مدیریت کدهای بزرگ
* مزایا و معایب MVC

**تمرین**

**مینی‌پروژه:** ساخت یک Backend با ساختار MVC

[مشاهده فصل ۸۵ ←](./11.4.md)

---

## فصل ۸۶ - Validation

Validation برای بررسی صحت داده‌هایی است که از Client دریافت می‌کنیم.

### مباحث این فصل

* Validation چیست؟
* چرا Validation ضروری است؟
* اعتبارسنجی Request
* Validation برای Body
* Validation برای Query
* Validation برای Params
* Required
* Optional
* String Validation
* Number Validation
* Boolean Validation
* Email Validation
* Password Validation
* Length Validation
* Format Validation
* Validation Error
* ساخت Validation دستی
* استفاده از کتابخانه‌های Validation

**تمرین‌های زیاد**

**مینی‌پروژه:** ساخت سیستم Validation برای API کاربران

[مشاهده فصل ۸۶ ←](./11.5.md)

---

## فصل ۸۷ - Authentication

Authentication برای تشخیص هویت کاربران استفاده می‌شود.

### مباحث این فصل

* Authentication چیست؟
* Authentication و Authorization
* ثبت‌نام کاربر
* Login
* Logout
* User Identity
* Password
* Hash Password
* بررسی اطلاعات ورود
* Authentication Middleware
* مدیریت کاربر واردشده
* Authentication در API
* طراحی سیستم Login
* مدیریت خطاهای Authentication

**تمرین**

**مینی‌پروژه:** ساخت سیستم ثبت‌نام و ورود کاربران

[مشاهده فصل ۸۷ ←](./11.6.md)

---

## فصل ۸۸ - Authorization

Authorization مشخص می‌کند یک کاربر پس از احراز هویت، چه دسترسی‌هایی دارد.

### مباحث این فصل

* Authorization چیست؟
* تفاوت Authentication و Authorization
* Permission
* Role
* Role-Based Access Control
* User Role
* Admin
* User
* بررسی Permission
* Authorization Middleware
* دسترسی به Routeها
* محدود کردن عملیات
* مدیریت دسترسی کاربران

**تمرین‌های زیاد**

**مینی‌پروژه:** ساخت سیستم Role و Permission

[مشاهده فصل ۸۸ ←](./11.7.md)

---

## فصل ۸۹ - JWT

JWT یکی از روش‌های رایج برای مدیریت Authentication در APIها است.

### مباحث این فصل

* JWT چیست؟
* ساختار JWT
* Header
* Payload
* Signature
* Token
* ایجاد Token
* Verify کردن Token
* Decode کردن Token
* Access Token
* Refresh Token
* Expiration
* JWT Authentication
* ارسال JWT در Request
* Bearer Token
* JWT Middleware
* مدیریت خطاهای JWT
* نکات امنیتی JWT

**تمرین‌های زیاد**

**مینی‌پروژه:** ساخت Authentication با JWT

[مشاهده فصل ۸۹ ←](./11.8.md)

---

## فصل ۹۰ - Cookie

Cookie برای ذخیره اطلاعات کوچک در سمت Client و انتقال آن‌ها بین درخواست‌ها استفاده می‌شود.

### مباحث این فصل

* Cookie چیست؟
* نحوه کار Cookie
* ایجاد Cookie
* خواندن Cookie
* حذف Cookie
* Cookie Attributes
* `HttpOnly`
* `Secure`
* `SameSite`
* `Max-Age`
* `Expires`
* Session Cookie
* Persistent Cookie
* Cookie در Node.js
* نکات امنیتی Cookie

**تمرین**

**مینی‌پروژه:** ساخت سیستم Login با Cookie

[مشاهده فصل ۹۰ ←](./11.9.md)

---

## فصل ۹۱ - Session

Session برای نگهداری وضعیت کاربر در سمت Server استفاده می‌شود.

### مباحث این فصل

* Session چیست؟
* Stateless و Stateful
* تفاوت Session و Cookie
* Session ID
* ایجاد Session
* ذخیره Session
* خواندن Session
* حذف Session
* Session Expiration
* Session Store
* Memory Store
* Session با Database
* Session با Redis
* Authentication با Session
* Logout
* مدیریت Session امن

**تمرین**

**مینی‌پروژه:** ساخت سیستم Login مبتنی بر Session

[مشاهده فصل ۹۱ ←](./11.10.md)

---

## فصل ۹۲ - Upload File

در بسیاری از پروژه‌های واقعی کاربران باید بتوانند فایل‌هایی مانند تصویر، PDF و سایر فایل‌ها را روی Server ارسال کنند.

### مباحث این فصل

* File Upload چیست؟
* Multipart Form Data
* دریافت فایل در Node.js
* نام فایل
* File Size
* File Type
* MIME Type
* ذخیره فایل
* مسیر فایل
* محدود کردن حجم فایل
* محدود کردن نوع فایل
* Multiple File Upload
* مدیریت خطاهای Upload
* حذف فایل
* امنیت File Upload
* ذخیره فایل روی Server
* آشنایی با Object Storage

**تمرین‌های زیاد**

**مینی‌پروژه:** ساخت API آپلود تصویر پروفایل

[مشاهده فصل ۹۲ ←](./11.11.md)

---

## فصل ۹۳ - Logging

Logging برای مشاهده رفتار برنامه، پیدا کردن خطاها و بررسی وضعیت Server ضروری است.

### مباحث این فصل

* Logging چیست؟
* چرا Logging مهم است؟
* Log Level
* Debug
* Info
* Warn
* Error
* Log Message
* Timestamp
* Request Logging
* Response Logging
* Error Logging
* ذخیره Log در File
* Log Rotation
* ساخت Logger
* استفاده از کتابخانه‌های Logging
* Logging در Production
* مدیریت اطلاعات حساس در Log

**تمرین**

**مینی‌پروژه:** ساخت سیستم Logger برای یک Web Server

[مشاهده فصل ۹۳ ←](./11.12.md)

---

## فصل ۹۴ - Error Handling حرفه‌ای

مدیریت صحیح خطا یکی از مهم‌ترین بخش‌های یک Backend حرفه‌ای است.

### مباحث این فصل

* Error Handling چیست؟
* خطاهای قابل پیش‌بینی
* خطاهای غیرقابل پیش‌بینی
* `try/catch`
* Promise Error
* Async Error
* Custom Error
* Error Class
* HTTP Error
* Error Middleware
* Error Code
* Error Message
* Response استاندارد برای خطا
* Validation Error
* Authentication Error
* Authorization Error
* Not Found Error
* Internal Server Error
* مدیریت خطا در Production
* Logging خطاها
* جلوگیری از نمایش اطلاعات حساس
* Global Error Handler

**تمرین‌های زیاد**

**مینی‌پروژه:** ساخت سیستم Error Handling حرفه‌ای برای API

[مشاهده فصل ۹۴ ←](./11.13.md)

---

# 🗺️ مسیر یادگیری این بخش

```text
ساخت سرور
│
├── Web Server
│   ├── HTTP Server
│   ├── Request
│   └── Response
│
├── Routing
│   ├── Route
│   ├── Endpoint
│   ├── Params
│   └── Query
│
├── Middleware
│   ├── Request Middleware
│   ├── Authentication
│   ├── Validation
│   └── Error Middleware
│
├── MVC
│   ├── Model
│   ├── View
│   ├── Controller
│   └── Service
│
├── Validation
│   ├── Body
│   ├── Params
│   ├── Query
│   └── Validation Error
│
├── Authentication
│   ├── Register
│   ├── Login
│   └── Logout
│
├── Authorization
│   ├── Role
│   ├── Permission
│   └── Access Control
│
├── JWT
│   ├── Access Token
│   ├── Refresh Token
│   └── JWT Middleware
│
├── Cookie
│   ├── Create
│   ├── Read
│   └── Security
│
├── Session
│   ├── Session ID
│   ├── Session Store
│   └── Authentication
│
├── File Upload
│   ├── Multipart
│   ├── Validation
│   └── File Storage
│
├── Logging
│   ├── Request Logs
│   ├── Error Logs
│   └── Production Logs
│
└── Error Handling
    ├── Custom Error
    ├── Error Middleware
    └── Global Error Handler
```

---

# 🎯 هدف بخش ۱۱

در پایان این بخش باید بتوانید:

* یک Web Server با Node.js بسازید.
* Request و Response را مدیریت کنید.
* Routing ایجاد کنید.
* Middleware طراحی و استفاده کنید.
* پروژه را با معماری MVC ساختاربندی کنید.
* داده‌های ورودی را Validation کنید.
* سیستم ثبت‌نام و Login بسازید.
* Authentication را پیاده‌سازی کنید.
* Authorization و Role/Permission ایجاد کنید.
* با JWT کار کنید.
* Access Token و Refresh Token را درک کنید.
* Cookie را مدیریت کنید.
* Session ایجاد و مدیریت کنید.
* File Upload پیاده‌سازی کنید.
* برای پروژه Logger ایجاد کنید.
* خطاهای برنامه را به‌صورت حرفه‌ای مدیریت کنید.
* یک Backend ساختاریافته و قابل توسعه ایجاد کنید.

---

# 🧩 تمرین‌های این بخش

تمرین‌های این بخش از ساخت یک Server ساده شروع می‌شوند و به ساخت یک Backend دارای Authentication، Authorization، File Upload، Logging و Error Handling حرفه‌ای می‌رسند.

تمرین‌ها شامل:

* ساخت Web Server
* ساخت Router
* طراحی Middleware
* ساخت پروژه MVC
* Validation داده‌های کاربران
* ثبت‌نام و Login
* Role و Permission
* Authentication با JWT
* کار با Cookie
* Session Authentication
* Upload فایل
* ساخت Logger
* مدیریت خطاهای مختلف
* ساخت Global Error Handler

تمام تمرین‌ها همراه با **پاسخ تشریحی** ارائه می‌شوند.

---

# 🚀 پروژه‌های پیشنهادی این بخش

برای ترکیب مباحث این بخش، پروژه‌های زیر به‌صورت مرحله‌ای انجام می‌شوند:

1. Web Server ساده
2. Router اختصاصی
3. Middleware System
4. Backend با معماری MVC
5. User Authentication API
6. Role & Permission System
7. JWT Authentication API
8. Session Authentication
9. File Upload API
10. Logging System
11. Professional Error Handling System
12. **پروژه نهایی بخش:** ساخت یک Backend کامل با Authentication، Authorization، Validation، File Upload، Logging و Error Handling

---

# ⏭️ بخش بعدی

بعد از ساخت Server و یادگیری مفاهیم اصلی Backend، نوبت به یکی از مهم‌ترین بخش‌های توسعه برنامه‌های واقعی می‌رسد:

**پایگاه داده**

در بخش بعدی با Database، SQL، PostgreSQL، MongoDB، ORM و ODM، Migration و Transaction کار خواهیم کرد.

[مشاهده بخش ۱۲ - پایگاه داده →](../part%2012/README.md)

---

<div align="center">

[بخش بعد ➡️](../part%2012/) • [📚 فهرست مطالب](../readme.md) • [⬅️ بخش قبل](../part%2010/)

</div>
