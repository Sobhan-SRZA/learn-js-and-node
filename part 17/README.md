# بخش ۱۷ - فریمورک‌های Node.js

وقتی با Node.js و مفاهیم اصلی Backend آشنا شدیم، وقت آن است که وارد دنیای **Frameworkها و ابزارهای حرفه‌ای Node.js** شویم.

در پروژه‌های واقعی معمولاً لازم نیست همه چیز را از صفر پیاده‌سازی کنیم. فریمورک‌ها و کتابخانه‌های Node.js امکاناتی مانند **Routing، Middleware، Validation، مدیریت Request و Response، ساخت API، معماری پروژه، Authentication و ارتباط Real-Time** را ساده‌تر و ساختاریافته‌تر می‌کنند.

در این بخش ابتدا با **Express.js** به‌عنوان یکی از مهم‌ترین فریمورک‌های Backend در اکوسیستم Node.js شروع می‌کنیم و سپس با فریمورک‌ها و ابزارهای دیگری مانند **Fastify، NestJS، Hono، Koa، AdonisJS و Socket.IO** آشنا می‌شویم.

هدف این بخش فقط یادگیری Syntax فریمورک‌ها نیست؛ بلکه باید بتوانیم تشخیص دهیم **هر فریمورک برای چه پروژه‌ای مناسب است، چه مزایا و محدودیت‌هایی دارد و چگونه با آن یک پروژه واقعی و قابل توسعه بسازیم.**

---

# 📚 فهرست مطالب

## فصل ۱۳۵ - Express.js

Express.js یکی از شناخته‌شده‌ترین فریمورک‌های Node.js برای ساخت Web Server و REST API است و نقطه شروع مناسبی برای ورود به توسعه حرفه‌ای Backend محسوب می‌شود.

### مباحث این فصل

* Express.js چیست؟
* چرا Express.js؟
* نصب Express.js
* ساخت اولین پروژه Express
* ساخت اولین Server
* Request و Response
* Route
* Routing
* HTTP Methods
* GET
* POST
* PUT
* PATCH
* DELETE
* Route Parameters
* Query Parameters
* Request Body
* Headers
* Status Code
* JSON Response
* Middleware
* Application Middleware
* Router Middleware
* Built-in Middleware
* Custom Middleware
* Error Middleware
* ترتیب اجرای Middlewareها
* Router
* Route Handler
* Controller
* جداسازی Route و Controller
* ساختار پروژه Express
* MVC
* Service Layer
* Repository Layer
* Validation
* مدیریت خطا
* Async Handler
* Authentication
* Authorization
* JWT
* Cookie
* Session
* CORS
* File Upload
* Static Files
* Logging
* Environment Variables
* اتصال Express به Database
* Express و PostgreSQL
* Express و MongoDB
* ساخت REST API
* Pagination
* Filtering
* Sorting
* Searching
* API Versioning
* Error Response استاندارد
* Security در Express
* Performance در Express
* Testing پروژه Express
* مدیریت Configuration
* Production Setup
* Graceful Shutdown
* Best Practices
* ساخت پروژه واقعی با Express

**تمرین‌های زیاد**

**پروژه کامل:** ساخت یک REST API حرفه‌ای با Express.js، Database، Authentication، Validation، Logging و Testing

[مشاهده فصل ۱۳۵ ←](./17.1.md)

---

## فصل ۱۳۶ - Fastify

Fastify یک فریمورک سریع و کم‌هزینه برای ساخت Server و APIهای Node.js است که روی Performance و ساختار مناسب تمرکز دارد.

### مباحث این فصل

* Fastify چیست؟
* چرا Fastify؟
* نصب Fastify
* ساخت اولین Server
* Route
* Request
* Response
* HTTP Methods
* Route Parameters
* Query Parameters
* Request Body
* Headers
* Status Code
* JSON Response
* Plugin
* Fastify Plugin System
* Hook
* Lifecycle
* Middleware
* Schema
* JSON Schema
* Validation
* Serialization
* Error Handling
* Logging
* Fastify Logger
* Authentication
* Authorization
* JWT
* Cookie
* CORS
* File Upload
* اتصال Database
* ساخت REST API
* Pagination
* Filtering
* API Versioning
* Performance
* Benchmark
* Testing
* ساختار پروژه Fastify
* مدیریت Configuration
* Production
* Graceful Shutdown
* Best Practices

**تمرین‌های زیاد**

**مینی‌پروژه:** ساخت REST API سریع با Fastify

[مشاهده فصل ۱۳۶ ←](./17.2.md)

---

## فصل ۱۳۷ - NestJS

NestJS یک فریمورک ساختاریافته برای Node.js است که برای ساخت برنامه‌های Backend بزرگ و قابل توسعه طراحی شده و از معماری ماژولار استفاده می‌کند.

### مباحث این فصل

* NestJS چیست؟
* چرا NestJS؟
* نصب NestJS CLI
* ساخت پروژه
* ساختار پروژه NestJS
* Module
* Controller
* Service
* Provider
* Dependency Injection
* Decorator
* Metadata
* Routing
* Request
* Response
* DTO
* Validation
* Pipes
* Guards
* Interceptors
* Middleware
* Exception Filters
* Custom Decorator
* Authentication
* Authorization
* JWT
* Passport
* Cookie
* Session
* CORS
* File Upload
* Configuration
* Environment Variables
* Database
* Prisma
* TypeORM
* Mongoose
* REST API
* API Versioning
* Pagination
* Swagger
* Documentation
* Testing
* Unit Test
* Integration Test
* E2E Test
* Logging
* Error Handling
* Performance
* Module Architecture
* Dynamic Modules
* Lifecycle Events
* Event-Based Architecture
* Queue
* Microservices
* WebSocket
* Gateway
* Production
* Graceful Shutdown
* Best Practices

**تمرین‌های زیاد**

**پروژه:** ساخت Backend ماژولار و حرفه‌ای با NestJS

[مشاهده فصل ۱۳۷ ←](./17.3.md)

---

## فصل ۱۳۸ - Hono

Hono یک فریمورک سبک و سریع برای ساخت Web Application و API است که با Web Standardها کار می‌کند و برای محیط‌های مختلف Runtime مناسب است.

### مباحث این فصل

* Hono چیست؟
* ویژگی‌های Hono
* نصب Hono
* ساخت اولین پروژه
* Route
* Request
* Response
* Context
* Middleware
* Custom Middleware
* Error Handling
* Validation
* Schema
* JSON Response
* Headers
* Cookies
* CORS
* Authentication
* JWT
* REST API
* Routing پیشرفته
* ساختار پروژه
* اتصال Database
* مدیریت Environment Variables
* Testing
* Performance
* Deployment
* استفاده از Hono در Node.js
* استفاده از Hono در Runtimeهای دیگر
* Web Standards
* Best Practices

**تمرین**

**مینی‌پروژه:** ساخت یک REST API سبک با Hono

[مشاهده فصل ۱۳۸ ←](./17.4.md)

---

## فصل ۱۳۹ - Koa

Koa یک فریمورک سبک از تیم سازندگان Express است که با تمرکز بر Middlewareهای مدرن و استفاده از قابلیت‌های Async JavaScript طراحی شده است.

### مباحث این فصل

* Koa چیست؟
* تفاوت Koa و Express
* نصب Koa
* ساخت اولین Server
* Context
* Request
* Response
* Middleware
* Middleware Onion Model
* Async Middleware
* Routing
* Router
* Request Body
* Headers
* Status Code
* Error Handling
* Custom Middleware
* Authentication
* Authorization
* JWT
* Cookie
* Session
* CORS
* Validation
* ساخت REST API
* اتصال Database
* Logging
* ساختار پروژه
* Testing
* Performance
* Production
* Best Practices

**تمرین**

**مینی‌پروژه:** ساخت REST API با Koa

[مشاهده فصل ۱۳۹ ←](./17.5.md)

---

## فصل ۱۴۰ - AdonisJS

AdonisJS یک فریمورک Full-featured برای Node.js است که امکانات متعددی را برای ساخت Backendهای ساختاریافته و پروژه‌های بزرگ در اختیار توسعه‌دهنده قرار می‌دهد.

### مباحث این فصل

* AdonisJS چیست؟
* چرا AdonisJS؟
* نصب AdonisJS
* AdonisJS CLI
* ساخت پروژه
* ساختار پروژه
* Routing
* Controller
* Middleware
* Validator
* Authentication
* Authorization
* Session
* Cookie
* Database
* ORM
* Lucid ORM
* Model
* Migration
* Seed
* Factory
* Relationship
* Query Builder
* Transaction
* REST API
* Validation
* File Upload
* Storage
* Mail
* Queue
* Events
* Logging
* Configuration
* Environment Variables
* Testing
* API Documentation
* Security
* Production
* Deployment
* Best Practices

**تمرین**

**مینی‌پروژه:** ساخت یک Backend ساختاریافته با AdonisJS

[مشاهده فصل ۱۴۰ ←](./17.6.md)

---

## فصل ۱۴۱ - Socket.IO

Socket.IO برای ساخت برنامه‌های Real-Time استفاده می‌شود و امکان برقراری ارتباط دوطرفه بین Client و Server را فراهم می‌کند.

### مباحث این فصل

* Real-Time چیست؟
* تفاوت HTTP و ارتباط Real-Time
* WebSocket چیست؟
* Socket.IO چیست؟
* تفاوت Socket.IO و WebSocket
* نصب Socket.IO
* ساخت Socket Server
* اتصال Client و Server
* Event
* Emit
* Listen
* Broadcast
* Room
* Namespace
* Private Room
* مدیریت Connection
* Disconnect
* Reconnect
* Authentication
* Authorization
* Middleware
* ارسال داده
* ارسال JSON
* مدیریت Error
* Connection State
* Presence
* Online Users
* Typing Indicator
* Notifications
* Chat
* Real-Time Updates
* Socket.IO و Express
* Socket.IO و NestJS
* Socket.IO و Database
* Scaling Socket.IO
* Redis Adapter
* چند Server
* Load Balancing
* Sticky Session
* Performance
* Security
* Testing
* Production
* Graceful Shutdown
* Best Practices

**تمرین‌های زیاد**

**پروژه:** ساخت چت آنلاین Real-Time

[مشاهده فصل ۱۴۱ ←](./17.7.md)

---

# 🗺️ مسیر یادگیری این بخش

```text
فریمورک‌های Node.js
│
├── Express.js
│   ├── Server
│   ├── Routing
│   ├── Middleware
│   ├── REST API
│   ├── Authentication
│   ├── Database
│   └── پروژه کامل
│
├── Fastify
│   ├── Routing
│   ├── Plugin
│   ├── Schema
│   ├── Validation
│   └── Performance
│
├── NestJS
│   ├── Module
│   ├── Controller
│   ├── Service
│   ├── Dependency Injection
│   ├── Guard
│   ├── Pipe
│   └── Architecture
│
├── Hono
│   ├── Routing
│   ├── Middleware
│   ├── Context
│   ├── Validation
│   └── Web Standards
│
├── Koa
│   ├── Context
│   ├── Middleware
│   ├── Onion Model
│   └── REST API
│
├── AdonisJS
│   ├── MVC
│   ├── ORM
│   ├── Migration
│   ├── Authentication
│   └── Full-stack Backend
│
└── Socket.IO
    ├── Real-Time
    ├── Event
    ├── Room
    ├── Namespace
    ├── Authentication
    └── Scaling
```

---

# 🎯 هدف بخش ۱۷

در پایان این بخش باید بتوانید:

* مفهوم Framework در Node.js را درک کنید.
* تفاوت Node.js و Framework را بدانید.
* یک Server با Express.js بسازید.
* Routing را در Express مدیریت کنید.
* Middlewareهای مختلف ایجاد کنید.
* REST API حرفه‌ای طراحی کنید.
* Validation و Error Handling را پیاده‌سازی کنید.
* Authentication و Authorization را مدیریت کنید.
* Express را به Database متصل کنید.
* یک پروژه Express را به‌صورت ساختاریافته طراحی کنید.
* با Fastify کار کنید.
* تفاوت Fastify و Express را درک کنید.
* از Schema و Validation در Fastify استفاده کنید.
* مفهوم Plugin در Fastify را بشناسید.
* با NestJS و معماری ماژولار آن کار کنید.
* Module، Controller و Service را درک کنید.
* Dependency Injection را در پروژه واقعی استفاده کنید.
* از Guard، Pipe و Interceptor استفاده کنید.
* APIهای حرفه‌ای با NestJS بسازید.
* با Hono آشنا شوید.
* APIهای سبک با Hono ایجاد کنید.
* Middleware و Context در Hono را استفاده کنید.
* با Koa و Onion Middleware Model کار کنید.
* تفاوت Koa و Express را درک کنید.
* با AdonisJS و امکانات Full-featured آن آشنا شوید.
* با ORM و Migration در AdonisJS کار کنید.
* مفهوم Real-Time Application را درک کنید.
* WebSocket و Socket.IO را بشناسید.
* Event، Room و Namespace را مدیریت کنید.
* یک Chat Application با Socket.IO بسازید.
* Socket.IO را برای چند Server مقیاس‌پذیر کنید.
* تفاوت و کاربرد Frameworkهای مختلف Node.js را مقایسه کنید.
* برای یک پروژه واقعی Framework مناسب انتخاب کنید.

---

# 🧩 تمرین‌های این بخش

تمرین‌های این بخش از ساخت Serverهای ساده شروع می‌شوند و به ساخت APIهای حرفه‌ای و برنامه‌های Real-Time می‌رسند.

تمرین‌ها شامل:

* ساخت اولین Express Server
* ساخت Routeهای مختلف
* کار با Request و Response
* ساخت Middleware
* ساخت Custom Middleware
* مدیریت Error
* ساخت REST API
* پیاده‌سازی Pagination
* پیاده‌سازی Filtering
* پیاده‌سازی Authentication
* پیاده‌سازی Authorization
* اتصال API به Database
* ساخت API با Fastify
* استفاده از Plugin در Fastify
* استفاده از Schema Validation
* ساخت Module در NestJS
* ساخت Controller و Service
* استفاده از Dependency Injection
* ساخت Guard
* ساخت Pipe
* ساخت API با Hono
* ساخت Middleware در Hono
* ساخت API با Koa
* پیاده‌سازی Onion Middleware
* ساخت پروژه با AdonisJS
* کار با ORM در AdonisJS
* ساخت WebSocket Server
* ایجاد Connection با Socket.IO
* کار با Event
* ساخت Room
* ارسال پیام خصوصی
* Broadcast کردن پیام
* مدیریت کاربران Online
* ساخت Notification Real-Time

تمام تمرین‌ها همراه با **پاسخ تشریحی** ارائه خواهند شد.

---

# 🚀 پروژه‌های پیشنهادی این بخش

برای یادگیری عملی Frameworkها، پروژه‌ها به‌صورت مرحله‌ای طراحی می‌شوند:

1. Web Server ساده با Express.js
2. REST API کاربران با Express.js
3. سیستم Authentication با Express.js
4. REST API متصل به Database
5. **پروژه کامل Express.js:** Backend یک فروشگاه کوچک
6. REST API سریع با Fastify
7. **پروژه Fastify:** Task Manager API
8. ساخت Backend ماژولار با NestJS
9. **پروژه NestJS:** سیستم مدیریت کاربران و نقش‌ها
10. REST API با Hono
11. REST API با Koa
12. Backend ساختاریافته با AdonisJS
13. WebSocket Server
14. سیستم Notification Real-Time با Socket.IO
15. **پروژه Chat:** ساخت چت آنلاین با Room و Authentication
16. **پروژه نهایی بخش:** مقایسه و پیاده‌سازی یک Backend در چند Framework و انتخاب Framework مناسب بر اساس نیاز پروژه

---

# ⚖️ مقایسه کلی Frameworkها

در این بخش فقط Syntax فریمورک‌ها را یاد نمی‌گیریم؛ بلکه از نظر **معماری، Performance، امکانات، Community، سادگی، مقیاس‌پذیری و کاربرد در پروژه‌های واقعی** نیز آن‌ها را بررسی می‌کنیم.

| Framework / Tool | تمرکز اصلی               | مناسب برای                                 |
| ---------------- | ------------------------ | ------------------------------------------ |
| Express.js       | سادگی و انعطاف‌پذیری      | REST API و Backendهای عمومی                |
| Fastify          | Performance و Schema     | APIهای سریع و سرویس‌های High Performance    |
| NestJS           | Architecture و ساختار    | Backendهای بزرگ و Enterprise               |
| Hono             | سبک و Web Standards      | APIهای سبک و Runtimeهای مختلف              |
| Koa              | Middleware و انعطاف‌پذیری | Backendهای سبک و سفارشی                    |
| AdonisJS         | امکانات کامل Backend     | پروژه‌های ساختاریافته و Full-featured       |
| Socket.IO        | Real-Time                | Chat، Notification و Applicationهای لحظه‌ای |

---

# 🧠 چگونه Framework مناسب انتخاب کنیم؟

در پایان این بخش باید بتوانیم بر اساس نیاز پروژه تصمیم بگیریم:

```text
آیا پروژه Real-Time است؟
│
├── بله
│   └── Socket.IO / WebSocket
│
└── خیر
    │
    ├── Backend ساده و انعطاف‌پذیر؟
    │   └── Express.js
    │
    ├── Performance بالا و API سریع؟
    │   └── Fastify
    │
    ├── پروژه بزرگ و معماری ساختاریافته؟
    │   └── NestJS
    │
    ├── Framework سبک و Web Standard؟
    │   └── Hono
    │
    ├── Middleware محور؟
    │   └── Koa
    │
    └── Framework کامل با امکانات Backend؟
        └── AdonisJS
```

---

# 🔗 ارتباط این بخش با بخش‌های قبلی

در فصل‌های قبلی، مفاهیم موردنیاز برای ورود به Frameworkها را یاد گرفتیم:

```text
JavaScript
    ↓
Async / Await
    ↓
Promise
    ↓
Module System
    ↓
Node.js Core
    ↓
HTTP
    ↓
REST API
    ↓
Database
    ↓
Authentication
    ↓
Security
    ↓
Performance
    ↓
Development Tools
    ↓
Frameworks
```

به همین دلیل در این بخش، مفاهیمی مانند **HTTP، Middleware، Authentication، Database، Testing و Security** را دیگر از صفر تعریف نمی‌کنیم، بلکه آن‌ها را در قالب Frameworkهای واقعی به کار می‌گیریم.

---

# 🏆 دستاورد نهایی بخش ۱۷

در پایان این بخش باید بتوانید برای یک پروژه واقعی Node.js، فقط بر اساس محبوبیت یک Framework تصمیم نگیرید؛ بلکه با بررسی **نیاز پروژه، معماری، Performance، پیچیدگی، تیم توسعه و قابلیت‌های موردنیاز**، Framework مناسب را انتخاب کنید.

همچنین باید بتوانید یک Backend واقعی را با یکی از Frameworkهای اصلی Node.js پیاده‌سازی کرده و برای پروژه‌های **REST API، Web Application، Real-Time Application، Microservice و Backendهای بزرگ** آماده باشید.

---

# ⏭️ بخش بعدی

پس از یادگیری Frameworkهای Node.js، وارد مرحله‌ای می‌شویم که هدف آن ترکیب تمام مهارت‌هایی است که تا اینجا یاد گرفته‌ایم و استفاده از آن‌ها در **پروژه‌های آموزشی و واقعی** است.

در **بخش ۱۸ - پروژه‌های آموزشی** چندین پروژه را از سطح ساده تا پیشرفته پیاده‌سازی می‌کنیم تا مفاهیم JavaScript و Node.js به مهارت عملی تبدیل شوند.

[مشاهده بخش ۱۸ - پروژه‌های آموزشی →](../part%2018/README.md)

---

<div align="center">

[بخش بعد ➡️](../part%2018/) • [📚 فهرست مطالب](../readme.md) • [⬅️ بخش قبل](../part%2016/)

</div>
