# بخش ۱۵ - Performance

وقتی یک برنامه Node.js از حالت تمرینی خارج شده و وارد دنیای واقعی می‌شود، فقط درست کار کردن آن کافی نیست؛ برنامه باید **سریع، کم‌مصرف، مقیاس‌پذیر و پایدار** نیز باشد.

در این بخش با مفاهیم مهم Performance در Node.js آشنا می‌شویم و یاد می‌گیریم چگونه گلوگاه‌های برنامه را پیدا کنیم، مصرف منابع را کاهش دهیم، پاسخ‌دهی Server را بهتر کنیم و برنامه را برای تعداد کاربران و درخواست‌های بیشتر آماده کنیم.

---

# 📚 فهرست مطالب

## فصل ۱۱۹ - Performance Optimization

در این فصل با مفهوم Performance و روش‌های بهینه‌سازی برنامه‌های Node.js آشنا می‌شویم.

### مباحث این فصل

* Performance چیست؟
* چرا Performance مهم است؟
* Response Time
* Latency
* Throughput
* Requests Per Second
* Resource Utilization
* CPU Usage
* Memory Usage
* I/O
* Network Performance
* Database Performance
* Bottleneck چیست؟
* پیدا کردن Bottleneck
* بهینه‌سازی کد JavaScript
* بهینه‌سازی Async Code
* مدیریت صحیح Promiseها
* جلوگیری از عملیات غیرضروری
* بهینه‌سازی Loopها
* بهینه‌سازی Memory
* بهینه‌سازی I/O
* بهینه‌سازی HTTP Requestها
* بهینه‌سازی Database Queryها
* Lazy Loading
* Pagination
* Connection Pooling
* Performance در Node.js
* اصول بهینه‌سازی در Production
* Premature Optimization

**تمرین‌های زیاد**

**مینی‌پروژه:** شناسایی و بهینه‌سازی یک Backend کند

[مشاهده فصل ۱۱۹ ←](./15.1.md)

---

## فصل ۱۲۰ - Cache

Cache برای ذخیره موقت داده‌های پرمصرف استفاده می‌شود تا در درخواست‌های بعدی بتوانیم اطلاعات را سریع‌تر در اختیار کاربر قرار دهیم.

### مباحث این فصل

* Cache چیست؟
* چرا Cache استفاده می‌کنیم؟
* Cache Hit
* Cache Miss
* Cache Key
* Cache Value
* TTL
* Cache Invalidation
* انواع Cache
* In-Memory Cache
* Application Cache
* HTTP Cache
* Database Cache
* Cache در Node.js
* Cache کردن Response
* Cache کردن Query
* Cache کردن داده‌های پرمصرف
* Cache Strategy
* مشکلات Cache
* Cache Stampede
* Stale Data
* Cache Invalidation
* چه زمانی از Cache استفاده کنیم؟

**تمرین‌های زیاد**

**مینی‌پروژه:** اضافه کردن Cache به یک REST API

[مشاهده فصل ۱۲۰ ←](./15.2.md)

---

## فصل ۱۲۱ - Redis

Redis یک سیستم ذخیره‌سازی داده در حافظه است که کاربردهای متنوعی در پروژه‌های Backend دارد و یکی از ابزارهای مهم برای Cache و سیستم‌های توزیع‌شده محسوب می‌شود.

### مباحث این فصل

* Redis چیست؟
* نصب Redis
* اجرای Redis
* اتصال Node.js به Redis
* Redis Client
* Key و Value
* String
* List
* Set
* Sorted Set
* Hash
* TTL
* Expiration
* Cache با Redis
* Session با Redis
* Rate Limit با Redis
* Counter
* Pub/Sub
* Redis در پروژه‌های Node.js
* مدیریت Connection
* Connection Pool
* Redis در Production
* نکات مربوط به Performance
* مدیریت خطاهای Redis

**تمرین‌های زیاد**

**مینی‌پروژه:** ساخت سیستم Cache با Redis

[مشاهده فصل ۱۲۱ ←](./15.3.md)

---

## فصل ۱۲۲ - Compression

Compression حجم داده‌های منتقل‌شده بین Server و Client را کاهش می‌دهد و می‌تواند باعث کاهش مصرف پهنای باند و بهبود سرعت انتقال شود.

### مباحث این فصل

* Compression چیست؟
* چرا Compression مهم است؟
* فشرده‌سازی Response
* فشرده‌سازی Request
* Gzip
* Brotli
* Deflate
* Content-Encoding
* Accept-Encoding
* Compression در HTTP
* Compression در Node.js
* Middleware مربوط به Compression
* چه داده‌هایی باید Compress شوند؟
* چه داده‌هایی نباید Compress شوند؟
* تأثیر Compression روی CPU
* تأثیر Compression روی Network
* Compression در Production
* انتخاب الگوریتم مناسب

**تمرین**

**مینی‌پروژه:** اضافه کردن Compression به یک Web Server

[مشاهده فصل ۱۲۲ ←](./15.4.md)

---

## فصل ۱۲۳ - Cluster

Cluster امکان اجرای چند Process از یک برنامه Node.js را فراهم می‌کند تا بتوانیم بهتر از منابع سیستم استفاده کنیم.

### مباحث این فصل

* Cluster چیست؟
* چرا از Cluster استفاده می‌کنیم؟
* Process و Thread
* Worker Process
* Primary Process
* استفاده از چند CPU Core
* ایجاد Cluster
* Workerها
* مدیریت Workerها
* Restart کردن Worker
* ارتباط بین Processها
* Load Distribution
* Cluster در Node.js
* محدودیت‌های Cluster
* Cluster و Shared State
* Cluster در Production
* تفاوت Cluster و Worker Threads

**تمرین**

**مینی‌پروژه:** اجرای یک Web Server با چند Worker

[مشاهده فصل ۱۲۳ ←](./15.5.md)

---

## فصل ۱۲۴ - Load Balancing

Load Balancing برای تقسیم درخواست‌ها بین چند Server یا Process استفاده می‌شود.

### مباحث این فصل

* Load Balancing چیست؟
* چرا Load Balancer استفاده می‌کنیم؟
* Server Pool
* تقسیم درخواست‌ها
* Load Balancer
* Reverse Proxy
* الگوریتم‌های Load Balancing
* Round Robin
* Least Connections
* Weighted Load Balancing
* Health Check
* Failover
* High Availability
* Horizontal Scaling
* Vertical Scaling
* Load Balancing با Node.js
* Load Balancing با Nginx
* Load Balancing و Cluster
* Session در محیط چندسروری
* Shared State
* Load Balancing در Production

**تمرین‌های زیاد**

**مینی‌پروژه:** اجرای چند Instance از یک Node.js Server و تقسیم درخواست‌ها

[مشاهده فصل ۱۲۴ ←](./15.6.md)

---

## فصل ۱۲۵ - Profiling

Profiling به ما کمک می‌کند بفهمیم برنامه دقیقاً در کدام قسمت‌ها زمان و منابع مصرف می‌کند.

### مباحث این فصل

* Profiling چیست؟
* چرا Profiling مهم است؟
* Performance Measurement
* CPU Profiling
* Memory Profiling
* CPU Profile
* Flame Graph
* Hot Path
* Bottleneck Detection
* بررسی Functionها
* بررسی Call Stack
* بررسی Memory Usage
* Heap Snapshot
* Memory Leak
* Garbage Collection
* Node.js Profiler
* Performance Hooks
* ابزارهای Profiling
* تحلیل نتایج Profiling
* مقایسه Before و After
* Profiling در Development
* Profiling در Production
* بهینه‌سازی بر اساس داده واقعی

**تمرین‌های زیاد**

**مینی‌پروژه:** پیدا کردن و رفع یک Bottleneck واقعی در برنامه Node.js

[مشاهده فصل ۱۲۵ ←](./15.7.md)

---

# 🗺️ مسیر یادگیری این بخش

```text
Performance
│
├── Performance Optimization
│   ├── Latency
│   ├── Throughput
│   ├── Resource Usage
│   └── Bottleneck
│
├── Cache
│   ├── Cache Hit
│   ├── Cache Miss
│   ├── TTL
│   └── Invalidation
│
├── Redis
│   ├── Data Types
│   ├── Cache
│   ├── Session
│   ├── Rate Limit
│   └── Pub/Sub
│
├── Compression
│   ├── Gzip
│   ├── Brotli
│   ├── Deflate
│   └── HTTP Compression
│
├── Cluster
│   ├── Primary
│   ├── Worker
│   ├── Multi-Core
│   └── Process Management
│
├── Load Balancing
│   ├── Load Balancer
│   ├── Round Robin
│   ├── Health Check
│   └── High Availability
│
└── Profiling
    ├── CPU Profiling
    ├── Memory Profiling
    ├── Flame Graph
    ├── Heap Snapshot
    └── Bottleneck Detection
```

---

# 🎯 هدف بخش ۱۵

در پایان این بخش باید بتوانید:

* مفهوم Performance را درک کنید.
* معیارهای مهم Performance را بشناسید.
* Bottleneckهای برنامه را شناسایی کنید.
* کدهای Node.js را برای Performance بهتر بهینه کنید.
* مصرف CPU و Memory را مدیریت کنید.
* Cache را در برنامه‌ها پیاده‌سازی کنید.
* Cache Hit و Cache Miss را درک کنید.
* TTL و Cache Invalidation را مدیریت کنید.
* Redis را نصب و استفاده کنید.
* Node.js را به Redis متصل کنید.
* از Redis برای Cache استفاده کنید.
* از Redis برای Session و Rate Limiting استفاده کنید.
* Responseهای HTTP را Compress کنید.
* تفاوت Gzip و Brotli را درک کنید.
* برنامه Node.js را با Cluster روی چند Core اجرا کنید.
* چند Instance از Server را مدیریت کنید.
* مفهوم Load Balancing را درک کنید.
* درخواست‌ها را بین چند Server تقسیم کنید.
* Health Check و Failover را بشناسید.
* مفهوم Horizontal Scaling را درک کنید.
* برنامه Node.js را Profiling کنید.
* CPU و Memory را بررسی کنید.
* Flame Graph و Heap Snapshot را تحلیل کنید.
* Memory Leak را شناسایی کنید.
* بر اساس داده‌های واقعی، Performance برنامه را بهبود دهید.

---

# 🧩 تمرین‌های این بخش

تمرین‌های این بخش از بهینه‌سازی ساده کد شروع می‌شوند و به Cache، Redis، Compression، اجرای چند Process، Load Balancing و Profiling می‌رسند.

تمرین‌ها شامل:

* پیدا کردن Bottleneck
* اندازه‌گیری Response Time
* بهینه‌سازی Functionها
* بهینه‌سازی عملیات Async
* پیاده‌سازی Cache
* مدیریت TTL
* پیاده‌سازی Cache با Redis
* ذخیره Session در Redis
* ساخت Rate Limiter با Redis
* فعال‌سازی Compression
* مقایسه Gzip و Brotli
* اجرای Node.js با Cluster
* اجرای چند Worker
* ساخت Load Balancer
* Health Check کردن Serverها
* Profiling برنامه
* بررسی CPU Usage
* بررسی Memory Usage
* شناسایی Memory Leak
* تحلیل Flame Graph
* مقایسه Performance قبل و بعد از Optimization

تمام تمرین‌ها همراه با **پاسخ تشریحی** ارائه خواهند شد.

---

# 🚀 پروژه‌های پیشنهادی این بخش

برای ترکیب مباحث این بخش، پروژه‌های زیر به‌صورت مرحله‌ای انجام می‌شوند:

1. Performance Benchmark برای یک API
2. بهینه‌سازی یک API کند
3. Cache کردن API Response
4. سیستم Cache با Redis
5. Session Store با Redis
6. Rate Limiter با Redis
7. Web Server با Compression
8. Node.js Cluster Server
9. Multi-Instance Backend
10. Load Balancer برای چند Node.js Server
11. Profiling و رفع Bottleneck
12. شناسایی و رفع Memory Leak
13. **پروژه نهایی بخش:** ساخت Backend مقیاس‌پذیر با Redis، Cache، Compression، Cluster، Load Balancing و Performance Monitoring

---

# ⏭️ بخش بعدی

بعد از یادگیری Performance و مقیاس‌پذیری، باید با ابزارهایی آشنا شویم که در توسعه حرفه‌ای پروژه‌های Node.js روزانه استفاده می‌شوند.

در **بخش ۱۶ - ابزارهای توسعه** با Git، GitHub، ESLint، Prettier، Husky، Nodemon، Docker، Docker Compose و CI/CD کار خواهیم کرد.

[مشاهده بخش ۱۶ - ابزارهای توسعه →](../part%2016/README.md)

---

<div align="center">

[بخش بعد ➡️](../part%2016/) • [📚 فهرست مطالب](../readme.md) • [⬅️ بخش قبل](../part%2014/)

</div>
