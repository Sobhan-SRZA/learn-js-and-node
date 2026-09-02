# بخش ۸ - Node.js Core

در این بخش وارد دنیای **هسته اصلی Node.js** می‌شویم و با مفاهیمی آشنا می‌شویم که نحوه کار Node.js را در سطح عمیق‌تری توضیح می‌دهند.

در بخش‌های قبلی با JavaScript و مفاهیم پیشرفته آن آشنا شدیم. حالا وقت آن است که بفهمیم Node.js چگونه این کدها را اجرا می‌کند، چگونه عملیات ورودی و خروجی را مدیریت می‌کند و چگونه با سیستم‌عامل، فایل‌ها، شبکه و منابع سیستم ارتباط برقرار می‌شود.

این بخش پایه بسیار مهمی برای ادامه مسیر Backend با Node.js است و درک آن باعث می‌شود رفتار برنامه‌های Node.js را بهتر تحلیل و عیب‌یابی کنید.

---

# 📚 فهرست مطالب

## فصل ۵۱ - معماری Node.js

در این فصل با معماری کلی Node.js و اجزای اصلی تشکیل‌دهنده آن آشنا می‌شویم.

* معماری Node.js
* JavaScript Engine
* V8
* Node.js Runtime
* Libuv
* Node.js APIs
* ارتباط اجزای مختلف Node.js
* نحوه اجرای یک برنامه Node.js

[مشاهده فصل ۵۱ ←](./8.1.md)

---

## فصل ۵۲ - Event Driven

در این فصل با معماری Event-Driven در Node.js آشنا می‌شویم و یاد می‌گیریم برنامه‌ها چگونه بر اساس Eventها عمل می‌کنند.

* Event چیست؟
* Event-Driven Architecture
* Event Listener
* Event Handler
* Event Emitter
* Event-Driven در Node.js
* کاربرد Eventها در برنامه‌های واقعی

[مشاهده فصل ۵۲ ←](./8.2.md)

---

## فصل ۵۳ - Single Thread

در این فصل با مدل Single Thread در Node.js آشنا می‌شویم و بررسی می‌کنیم چگونه Node.js با وجود یک Thread اصلی می‌تواند تعداد زیادی عملیات را مدیریت کند.

* Thread چیست؟
* Single Thread چیست؟
* Main Thread
* JavaScript Thread
* مزایا و محدودیت‌های Single Thread
* ارتباط Single Thread با Asynchronous Programming
* CPU-Bound و I/O-Bound Operations

[مشاهده فصل ۵۳ ←](./8.3.md)

---

## فصل ۵۴ - Libuv

در این فصل با Libuv و نقش آن در اجرای عملیات Asynchronous در Node.js آشنا می‌شویم.

* Libuv چیست؟
* نقش Libuv در Node.js
* Thread Pool
* I/O Operations
* Event Loop و Libuv
* عملیات File System
* عملیات Network
* مدیریت عملیات خارج از Thread اصلی

[مشاهده فصل ۵۴ ←](./8.4.md)

---

## فصل ۵۵ - EventEmitter

در این فصل با `EventEmitter` آشنا می‌شویم و یاد می‌گیریم چگونه سیستم Event را در برنامه‌های Node.js ایجاد و مدیریت کنیم.

* `EventEmitter` چیست؟
* ایجاد EventEmitter
* `on`
* `emit`
* `once`
* `off`
* `removeListener`
* Event Listenerها
* مدیریت Eventها

**تمرین**

[مشاهده فصل ۵۵ ←](./8.5.md)

---

## فصل ۵۶ - Process

در این فصل با Object مربوط به `process` آشنا می‌شویم و یاد می‌گیریم چگونه به اطلاعات و امکانات مربوط به Process جاری Node.js دسترسی داشته باشیم.

* `process` چیست؟
* `process.argv`
* `process.env`
* `process.cwd()`
* `process.exit()`
* `process.pid`
* `process.platform`
* `process.version`
* Exit Code
* Signals

**تمرین**

[مشاهده فصل ۵۶ ←](./8.6.md)

---

## فصل ۵۷ - Buffer

در این فصل با Buffer و نحوه کار Node.js با داده‌های Binary آشنا می‌شویم.

* Buffer چیست؟
* Binary Data
* ایجاد Buffer
* `Buffer.from()`
* `Buffer.alloc()`
* خواندن Buffer
* تبدیل Buffer به String
* Encoding
* UTF-8
* کاربرد Buffer در Node.js

**تمرین**

[مشاهده فصل ۵۷ ←](./8.7.md)

---

## فصل ۵۸ - Streams

در این فصل با Streams آشنا می‌شویم و یاد می‌گیریم چگونه داده‌های حجیم را به‌صورت تدریجی پردازش کنیم.

* Stream چیست؟
* چرا از Stream استفاده می‌کنیم؟
* Readable
* Writable
* Duplex
* Transform
* Pipe
* `pipe()`
* پردازش داده به‌صورت Stream
* کاربرد Stream در File System و Network

**پروژه**

[مشاهده فصل ۵۸ ←](./8.8.md)

---

## فصل ۵۹ - File System (fs)

در این فصل با Module مربوط به File System آشنا می‌شویم و یاد می‌گیریم چگونه با فایل‌ها و پوشه‌ها در Node.js کار کنیم.

* Module `fs`
* خواندن فایل
* نوشتن فایل
* ایجاد فایل
* حذف فایل
* Rename
* Copy
* کار با پوشه‌ها
* عملیات Synchronous
* عملیات Asynchronous
* `fs/promises`
* کار با Streamهای فایل

**تمرین**

**پروژه**

[مشاهده فصل ۵۹ ←](./8.9.md)

---

## فصل ۶۰ - Path

در این فصل با Module مربوط به Path آشنا می‌شویم و یاد می‌گیریم چگونه مسیر فایل‌ها و پوشه‌ها را به‌صورت صحیح مدیریت کنیم.

* Module `path`
* `join`
* `resolve`
* `basename`
* `dirname`
* `extname`
* `parse`
* `format`
* مسیر نسبی
* مسیر مطلق
* مدیریت Path در Node.js

**تمرین**

[مشاهده فصل ۶۰ ←](./8.10.md)

---

## فصل ۶۱ - OS

در این فصل با Module مربوط به سیستم‌عامل آشنا می‌شویم و یاد می‌گیریم چگونه اطلاعات سیستم را از طریق Node.js دریافت کنیم.

* Module `os`
* اطلاعات سیستم‌عامل
* CPU
* Memory
* Network Interfaces
* Platform
* Architecture
* Uptime
* اطلاعات کاربران سیستم

**تمرین**

[مشاهده فصل ۶۱ ←](./8.11.md)

---

## فصل ۶۲ - URL

در این فصل با URL و ابزارهای Node.js برای پردازش و مدیریت URLها آشنا می‌شویم.

* URL چیست؟
* ساخت URL
* Parse کردن URL
* URL Components
* Protocol
* Host
* Port
* Pathname
* Search Params
* Hash
* `URL`
* `URLSearchParams`

**تمرین**

[مشاهده فصل ۶۲ ←](./8.12.md)

---

## فصل ۶۳ - Crypto

در این فصل با قابلیت‌های Cryptography در Node.js آشنا می‌شویم.

* Module `crypto`
* Hashing
* Hash Function
* Random Data
* UUID
* HMAC
* Encryption
* Decryption
* Key Generation
* کاربردهای Crypto در Node.js

**تمرین**

[مشاهده فصل ۶۳ ←](./8.13.md)

---

## فصل ۶۴ - Timers

در این فصل با Timerها و APIهای مربوط به زمان‌بندی عملیات در Node.js آشنا می‌شویم.

* `setTimeout`
* `setInterval`
* `setImmediate`
* `clearTimeout`
* `clearInterval`
* `clearImmediate`
* Timer در Node.js
* تفاوت Timerها
* ارتباط Timerها با Event Loop

**تمرین**

[مشاهده فصل ۶۴ ←](./8.14.md)

---

## فصل ۶۵ - Child Process

در این فصل با اجرای Processهای جداگانه در Node.js آشنا می‌شویم.

* Child Process چیست؟
* Module `child_process`
* `exec`
* `execFile`
* `spawn`
* `fork`
* تفاوت روش‌های اجرای Process
* دریافت خروجی Process
* مدیریت Processهای خارجی
* کاربردهای عملی

**تمرین**

[مشاهده فصل ۶۵ ←](./8.15.md)

---

## فصل ۶۶ - Worker Threads

در این فصل با Worker Threads آشنا می‌شویم و یاد می‌گیریم چگونه عملیات CPU-intensive را خارج از Thread اصلی اجرا کنیم.

* Worker Thread چیست؟
* Module `worker_threads`
* Worker
* Main Thread
* `parentPort`
* `workerData`
* ارسال Message بین Threadها
* CPU-Bound Tasks
* تفاوت Worker Threads و Child Process
* کاربردهای Worker Threads

**تمرین**

[مشاهده فصل ۶۶ ←](./8.16.md)

---

# 🗺️ مسیر یادگیری این بخش

```text
بخش ۸ - Node.js Core
│
├── فصل ۵۱ - معماری Node.js
│   ├── V8
│   ├── Node.js Runtime
│   ├── Libuv
│   └── Node.js APIs
│
├── فصل ۵۲ - Event Driven
│   ├── Event
│   ├── Event Listener
│   ├── Event Handler
│   └── Event Emitter
│
├── فصل ۵۳ - Single Thread
│   ├── Thread
│   ├── Main Thread
│   ├── Single Thread
│   └── CPU-Bound / I/O-Bound
│
├── فصل ۵۴ - Libuv
│   ├── Event Loop
│   ├── Thread Pool
│   ├── I/O
│   └── Async Operations
│
├── فصل ۵۵ - EventEmitter
│   ├── on
│   ├── emit
│   ├── once
│   └── removeListener
│
├── فصل ۵۶ - Process
│   ├── argv
│   ├── env
│   ├── cwd
│   ├── exit
│   └── Signals
│
├── فصل ۵۷ - Buffer
│   ├── Binary Data
│   ├── Buffer.from
│   ├── Buffer.alloc
│   └── Encoding
│
├── فصل ۵۸ - Streams
│   ├── Readable
│   ├── Writable
│   ├── Duplex
│   ├── Transform
│   └── Pipe
│
├── فصل ۵۹ - File System
│   ├── fs
│   ├── fs/promises
│   ├── File
│   ├── Directory
│   └── File Streams
│
├── فصل ۶۰ - Path
│   ├── join
│   ├── resolve
│   ├── basename
│   ├── dirname
│   └── extname
│
├── فصل ۶۱ - OS
│   ├── CPU
│   ├── Memory
│   ├── Platform
│   └── Network
│
├── فصل ۶۲ - URL
│   ├── URL
│   ├── URLSearchParams
│   └── URL Components
│
├── فصل ۶۳ - Crypto
│   ├── Hashing
│   ├── HMAC
│   ├── Encryption
│   └── Random Data
│
├── فصل ۶۴ - Timers
│   ├── setTimeout
│   ├── setInterval
│   ├── setImmediate
│   └── Clear Methods
│
├── فصل ۶۵ - Child Process
│   ├── exec
│   ├── execFile
│   ├── spawn
│   └── fork
│
└── فصل ۶۶ - Worker Threads
    ├── Worker
    ├── parentPort
    ├── workerData
    └── Message Passing
```

---

# 🎯 هدف بخش ۸

در پایان این بخش باید بتوانید:

* معماری کلی Node.js را درک کنید.
* نقش V8 و Libuv را توضیح دهید.
* معماری Event-Driven را درک کنید.
* مدل Single Thread در Node.js را بشناسید.
* تفاوت عملیات CPU-Bound و I/O-Bound را درک کنید.
* با `EventEmitter` کار کنید.
* اطلاعات Process جاری Node.js را مدیریت کنید.
* با `Buffer` و داده‌های Binary کار کنید.
* فایل‌ها و پوشه‌ها را با `fs` مدیریت کنید.
* مسیر فایل‌ها را با `path` مدیریت کنید.
* اطلاعات سیستم‌عامل را با `os` دریافت کنید.
* URLها را پردازش و مدیریت کنید.
* با قابلیت‌های پایه `crypto` کار کنید.
* عملیات زمان‌بندی را با Timerها انجام دهید.
* Processهای خارجی را با `child_process` اجرا و مدیریت کنید.
* عملیات CPU-intensive را با Worker Threads از Thread اصلی جدا کنید.
* مفهوم Streams را درک کنید.
* از Readable، Writable، Duplex و Transform Stream استفاده کنید.
* مفاهیم اصلی Node.js Core را در پروژه‌های واقعی به کار ببرید.

---

# 🧩 تمرین‌های این بخش

در این بخش تمرین‌ها از کار با APIهای ساده Node.js شروع شده و به‌تدریج به مفاهیم عمیق‌تر و کاربردی‌تر می‌رسند.

تمرین‌ها شامل کار با:

* `process`
* `EventEmitter`
* `Buffer`
* `fs`
* `path`
* `os`
* `URL`
* `crypto`
* Timerها
* Child Process
* Worker Threads
* Streams

خواهند بود.

هدف این تمرین‌ها این است که بتوانید **قابلیت‌های Core Node.js را بدون وابستگی به Frameworkها** درک و استفاده کنید.

---

# 🚀 پروژه‌های پیشنهادی این بخش

برای تثبیت مفاهیم Node.js Core می‌توان پروژه‌های کوچک زیر را پیاده‌سازی کرد:

* File Manager ساده
* سیستم ثبت و مدیریت Log
* برنامه Backup فایل‌ها
* File Downloader مبتنی بر Stream
* سیستم پردازش فایل‌های حجیم
* ابزار CLI برای دریافت اطلاعات سیستم
* Process Manager ساده
* سیستم اجرای Taskهای پس‌زمینه
* ابزار Hash Generator
* ابزار بررسی اطلاعات URL
* سیستم Event-driven ساده
* پردازش موازی داده‌های سنگین با Worker Threads

---

# ⏭️ بخش بعدی

پس از یادگیری Node.js Core، در بخش بعدی وارد دنیای **Package Managerها** می‌شویم و با npm، package.json، مدیریت Dependencyها، Semantic Versioning و ساخت و انتشار Package آشنا خواهیم شد.

[بخش ۹ - Package Manager →](../part%209/READM
E.md)

---

<div align="center">

[بخش بعد ➡️](../part%209/) • [📚 فهرست مطالب](../readme.md) • [⬅️ بخش قبل](../part%207/)

</div>
