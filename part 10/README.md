# بخش ۱۰ - شبکه

در این بخش با مفاهیم پایه و مهم شبکه آشنا می‌شویم و یاد می‌گیریم برنامه‌های Node.js چگونه با دنیای بیرون ارتباط برقرار می‌کنند.

هدف این بخش این است که قبل از ورود جدی‌تر به ساخت Web Server و REST API، مفاهیمی مانند HTTP، HTTPS، DNS، TCP/IP، Socket، WebSocket و معماری REST را به‌صورت مرحله‌به‌مرحله یاد بگیریم.

---

# 📚 فهرست مطالب

## فصل ۷۴ - HTTP

HTTP یکی از مهم‌ترین پروتکل‌ها در توسعه Backend و Web است و تقریباً تمام برنامه‌های وب Node.js به‌نوعی با آن سروکار دارند.

### مباحث این فصل

* HTTP چیست؟
* Client و Server
* Request و Response
* HTTP Methods
* GET
* POST
* PUT
* PATCH
* DELETE
* HTTP Headers
* HTTP Body
* HTTP Status Codes
* Query Parameters
* Path Parameters
* Content-Type
* MIME Type
* JSON
* HTTP Request در Node.js
* HTTP Response در Node.js
* ساخت HTTP Server ساده با Node.js
* ارسال Request با Node.js
* تفاوت HTTP/1.0، HTTP/1.1 و HTTP/2
* آشنایی مقدماتی با HTTP/3

**تمرین‌های زیاد**

**مینی‌پروژه:** ساخت یک HTTP Server ساده با Node.js

[مشاهده فصل ۷۴ ←](./10.1.md)

---

## فصل ۷۵ - HTTPS

HTTPS نسخه امن HTTP است و برای ارتباط امن بین Client و Server استفاده می‌شود.

### مباحث این فصل

* HTTPS چیست؟
* تفاوت HTTP و HTTPS
* Encryption
* SSL و TLS
* Certificate
* Public Key و Private Key
* مفهوم CA
* Handshake
* HTTPS در Node.js
* ساخت HTTPS Server
* استفاده از Certificate
* امنیت ارتباط بین Client و Server

**تمرین**

**مینی‌پروژه:** ساخت HTTPS Server ساده

[مشاهده فصل ۷۵ ←](./10.2.md)

---

## فصل ۷۶ - DNS

DNS مسئول تبدیل نام دامنه به آدرس IP است و یکی از پایه‌های اصلی ارتباطات اینترنتی محسوب می‌شود.

### مباحث این فصل

* DNS چیست؟
* Domain Name
* IP Address
* DNS Resolver
* DNS Server
* Name Server
* Recordهای DNS
* A Record
* AAAA Record
* CNAME
* MX
* TXT
* NS
* Reverse DNS
* DNS Lookup
* کار با DNS در Node.js
* Resolve کردن Domain
* مفهوم DNS Cache

**تمرین**

**مینی‌پروژه:** ساخت DNS Lookup Tool با Node.js

[مشاهده فصل ۷۶ ←](./10.3.md)

---

## فصل ۷۷ - TCP/IP

TCP/IP پایه ارتباط شبکه‌ای بسیاری از سرویس‌های اینترنتی است و درک آن برای یک برنامه‌نویس Backend بسیار مهم است.

### مباحث این فصل

* Network چیست؟
* Protocol چیست؟
* TCP چیست؟
* IP چیست؟
* IPv4
* IPv6
* IP Address
* Port
* TCP Connection
* Three-Way Handshake
* Packet
* مفهوم Client و Server در TCP
* تفاوت TCP و UDP
* Socket در TCP
* TCP در Node.js
* ایجاد TCP Server
* ایجاد TCP Client
* ارسال و دریافت Data

**تمرین**

**مینی‌پروژه:** ساخت TCP Client و Server ساده

[مشاهده فصل ۷۷ ←](./10.4.md)

---

## فصل ۷۸ - Socket

Socket یکی از مفاهیم مهم ارتباط مستقیم بین Client و Server است و در بسیاری از سیستم‌های Real-Time کاربرد دارد.

### مباحث این فصل

* Socket چیست؟
* ارتباط Client و Server
* TCP Socket
* Socket Address
* Port
* ایجاد Socket در Node.js
* `net` Module
* TCP Server
* TCP Client
* ارسال Data
* دریافت Data
* مدیریت Connection
* مدیریت Disconnect
* Error Handling
* چند Client همزمان
* Broadcast
* ارتباط Real-Time

**تمرین‌های زیاد**

**مینی‌پروژه:** ساخت Chat ساده با TCP Socket

[مشاهده فصل ۷۸ ←](./10.5.md)

---

## فصل ۷۹ - WebSocket

WebSocket برای ایجاد ارتباط دوطرفه و دائمی بین Client و Server استفاده می‌شود و یکی از فناوری‌های مهم برای برنامه‌های Real-Time است.

### مباحث این فصل

* WebSocket چیست؟
* تفاوت WebSocket و HTTP
* Persistent Connection
* Full-Duplex Communication
* WebSocket Handshake
* WebSocket Events
* Connection
* Message
* Close
* Error
* WebSocket Server
* WebSocket Client
* WebSocket در Node.js
* ارسال Message
* دریافت Message
* Broadcast
* مدیریت چند Client
* Real-Time Communication

**تمرین**

**مینی‌پروژه:** ساخت Chat Real-Time با WebSocket

[مشاهده فصل ۷۹ ←](./10.6.md)

---

## فصل ۸۰ - REST API

REST یکی از رایج‌ترین روش‌های طراحی API برای ارتباط بین Frontend، Backend و سرویس‌های مختلف است.

### مباحث این فصل

* API چیست؟
* REST چیست؟
* Resource
* Endpoint
* RESTful API
* HTTP Methods در REST
* GET
* POST
* PUT
* PATCH
* DELETE
* HTTP Status Codes
* Request Body
* Query Parameters
* Path Parameters
* Headers
* JSON Response
* Stateless بودن REST
* CRUD
* طراحی Endpoint
* Naming Convention
* Versioning
* Pagination
* Filtering
* Sorting
* Searching
* Error Response
* REST API در Node.js

**تمرین‌های زیاد**

**مینی‌پروژه:** ساخت REST API مدیریت کاربران

[مشاهده فصل ۸۰ ←](./10.7.md)

---

## فصل ۸۱ - GraphQL

GraphQL روشی برای طراحی و مصرف API است که امکان درخواست دقیق داده‌های موردنیاز را در اختیار Client قرار می‌دهد.

### مباحث این فصل

* GraphQL چیست؟
* تفاوت GraphQL و REST
* Schema
* Type
* Query
* Mutation
* Subscription
* Resolver
* Arguments
* Variables
* Input Types
* Object Types
* Scalar Types
* ارتباط بین Typeها
* Error Handling
* GraphQL در Node.js
* ساخت API ساده با GraphQL
* مصرف GraphQL API

**تمرین**

**مینی‌پروژه:** ساخت API مدیریت کاربران و محصولات با GraphQL

[مشاهده فصل ۸۱ ←](./10.8.md)

---

# 🗺️ مسیر یادگیری این بخش

```text
شبکه
│
├── HTTP
│   ├── Request
│   ├── Response
│   ├── Methods
│   └── Status Codes
│
├── HTTPS
│   ├── SSL
│   ├── TLS
│   └── Certificate
│
├── DNS
│   ├── Domain
│   ├── IP
│   └── DNS Records
│
├── TCP/IP
│   ├── TCP
│   ├── IP
│   ├── Port
│   └── Connection
│
├── Socket
│   ├── TCP Socket
│   ├── Client
│   └── Server
│
├── WebSocket
│   ├── Persistent Connection
│   ├── Full-Duplex
│   └── Real-Time
│
├── REST API
│   ├── Resource
│   ├── Endpoint
│   ├── CRUD
│   └── HTTP Methods
│
└── GraphQL
    ├── Schema
    ├── Query
    ├── Mutation
    └── Resolver
```

---

# 🎯 هدف بخش ۱۰

در پایان این بخش باید بتوانید:

* مفهوم شبکه را درک کنید.
* نحوه ارتباط Client و Server را توضیح دهید.
* HTTP را به‌خوبی بشناسید.
* Request و Response را تحلیل کنید.
* با HTTP Methods کار کنید.
* HTTP Status Codeها را بشناسید.
* تفاوت HTTP و HTTPS را بدانید.
* مفهوم SSL و TLS را درک کنید.
* نحوه کار DNS را بفهمید.
* مفهوم IP و Port را درک کنید.
* TCP/IP را بشناسید.
* با Socket کار کنید.
* ارتباط Real-Time را درک کنید.
* WebSocket را بشناسید.
* یک WebSocket Server ساده بسازید.
* مفهوم API را درک کنید.
* اصول طراحی REST API را یاد بگیرید.
* CRUD API طراحی کنید.
* با مفاهیم پایه GraphQL آشنا شوید.
* تفاوت REST و GraphQL را درک کنید.
* ارتباطات شبکه‌ای را در Node.js پیاده‌سازی کنید.

---

# 🧩 تمرین‌های این بخش

در این بخش تمرین‌ها از مفاهیم ساده شبکه شروع می‌شوند و به ساخت سرویس‌های واقعی‌تر می‌رسند.

تمرین‌ها شامل:

* تحلیل HTTP Request و Response
* کار با HTTP Methods
* کار با Status Codeها
* ساخت HTTP Server
* ساخت HTTPS Server
* DNS Lookup
* کار با IP و Port
* ساخت TCP Server
* ساخت TCP Client
* ارتباط چند Client با Socket
* ساخت Chat با Socket
* ساخت WebSocket Server
* ارسال پیام Real-Time
* طراحی REST API
* طراحی CRUD API
* طراحی API با GraphQL
* مقایسه REST و GraphQL

هر تمرین همراه با **پاسخ تشریحی** خواهد بود تا علاوه بر رسیدن به جواب، دلیل انتخاب راه‌حل نیز مشخص شود.

---

# 🚀 پروژه‌های پیشنهادی این بخش

برای تثبیت مفاهیم این بخش، پروژه‌های زیر به‌صورت مرحله‌ای انجام می‌شوند:

1. HTTP Server ساده
2. HTTPS Server
3. DNS Lookup Tool
4. TCP Client/Server
5. TCP Chat
6. WebSocket Chat
7. REST API کاربران
8. REST API مدیریت محصولات
9. GraphQL API کاربران و محصولات

---

# ⏭️ بخش بعدی

بعد از یادگیری مفاهیم شبکه، آماده ورود به دنیای ساخت سرویس‌های Backend واقعی با Node.js می‌شویم.

در بخش بعدی با ساخت Web Server، Routing، Middleware، MVC، Validation، Authentication، Authorization، JWT، Cookie، Session، Upload و Logging کار خواهیم کرد.

[مشاهده بخش ۱۱ - ساخت سرور →](../part%2011/README.md)

---

<div align="center">

[بخش بعد ➡️](../part%2011/) • [📚 فهرست مطالب](../readme.md) • [⬅️ بخش قبل](../part%209/)

</div>
