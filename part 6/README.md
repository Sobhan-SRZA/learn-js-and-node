# بخش ۶ - مفاهیم پیشرفته JavaScript

در این بخش وارد مفاهیم عمیق‌تر **JavaScript در محیط Node.js** می‌شویم.

تا اینجا با Syntax و مفاهیم پایه JavaScript آشنا شده‌ایم. حالا لازم است بدانیم JavaScript در زمان اجرا چگونه کدها را مدیریت می‌کند، حافظه چگونه مورد استفاده قرار می‌گیرد، Event Loop چگونه کار می‌کند و عملیات Asynchronous چگونه در Node.js اجرا می‌شوند.

این بخش یکی از مهم‌ترین قسمت‌های مسیر یادگیری است؛ زیرا درک صحیح این مفاهیم برای کار حرفه‌ای با Node.js، Promise، Async/Await و برنامه‌های Asynchronous ضروری است.

---

# 📚 فهرست مطالب

## فصل ۳۱ - Execution Context

در این فصل با مفهوم Execution Context و محیطی که JavaScript برای اجرای کد ایجاد می‌کند آشنا می‌شویم.

* مفهوم Execution Context
* Global Execution Context
* Function Execution Context
* نحوه ایجاد Execution Context
* مراحل اجرای کد

[مشاهده فصل ۳۱ ←](./6.1.md)

---

## فصل ۳۲ - Call Stack

در این فصل با Call Stack و نحوه مدیریت اجرای Functionها در JavaScript آشنا می‌شویم.

* Call Stack چیست؟
* نحوه ورود Function به Stack
* نحوه خروج Function از Stack
* Stack Frame
* Stack Overflow
* ارتباط Call Stack با اجرای برنامه

[مشاهده فصل ۳۲ ←](./6.2.md)

---

## فصل ۳۳ - Memory

در این فصل با نحوه مدیریت حافظه در JavaScript و مفاهیم مرتبط با Memory آشنا می‌شویم.

* Memory چیست؟
* نحوه ذخیره داده‌ها
* Stack
* Heap
* Reference
* Primitive و Reference Values
* Memory Management

[مشاهده فصل ۳۳ ←](./6.3.md)

---

## فصل ۳۴ - Garbage Collection

در این فصل با Garbage Collection و نحوه آزادسازی حافظه‌های دیگر موردنیاز نیستند آشنا می‌شویم.

* Garbage Collection چیست؟
* چرا Garbage Collection لازم است؟
* نحوه تشخیص داده‌های غیرقابل دسترس
* آزادسازی حافظه
* Memory Leak
* جلوگیری از Memory Leak

[مشاهده فصل ۳۴ ←](./6.4.md)

---

## فصل ۳۵ - Event Loop

در این فصل با یکی از مهم‌ترین مفاهیم JavaScript و Node.js یعنی Event Loop آشنا می‌شویم.

* Event Loop چیست؟
* ارتباط Event Loop با Call Stack
* اجرای کدهای Synchronous
* اجرای کدهای Asynchronous
* Task Queue
* Microtask Queue
* Event Loop در Node.js
* ترتیب اجرای عملیات

[مشاهده فصل ۳۵ ←](./6.5.md)

---

## فصل ۳۶ - Callback

در این فصل با Callback Function و نقش آن در برنامه‌نویسی Asynchronous آشنا می‌شویم.

* Callback چیست؟
* Callback Function
* Callback به‌عنوان Argument
* Callback در عملیات Asynchronous
* Callback Hell
* مشکلات Callback
* مدیریت Callbackها

[مشاهده فصل ۳۶ ←](./6.6.md)

---

## فصل ۳۷ - Promise

در این فصل با Promise و روش مدرن‌تر مدیریت عملیات Asynchronous آشنا می‌شویم.

* Promise چیست؟
* Promise States
* `pending`
* `fulfilled`
* `rejected`
* `then`
* `catch`
* `finally`
* Promise Chaining
* مدیریت خطا در Promise

[مشاهده فصل ۳۷ ←](./6.7.md)

---

## فصل ۳۸ - Async Await

در این فصل با `async` و `await` آشنا می‌شویم و یاد می‌گیریم چگونه کدهای Asynchronous را خواناتر و قابل مدیریت‌تر بنویسیم.

* `async`
* `await`
* Async Function
* مدیریت خطا با `try/catch`
* اجرای عملیات Asynchronous
* Promise و Async/Await
* Promiseهای متعدد
* `Promise.all`
* `Promise.allSettled`
* `Promise.race`
* `Promise.any`

[مشاهده فصل ۳۸ ←](./6.8.md)

---

## فصل ۳۹ - Error Handling

در این فصل با روش‌های مدیریت خطا در JavaScript آشنا می‌شویم.

* مفهوم Error
* `try`
* `catch`
* `finally`
* `throw`
* ساخت Error
* مدیریت خطاهای Synchronous
* مدیریت خطاهای Asynchronous

**تمرین**

[مشاهده فصل ۳۹ ←](./6.9.md)

---

## فصل ۴۰ - Module System

در این فصل با سیستم Module در JavaScript و نحوه تقسیم برنامه به فایل‌ها و بخش‌های مستقل آشنا می‌شویم.

* Module چیست؟
* چرا از Module استفاده می‌کنیم؟
* CommonJS
* `require`
* `module.exports`
* ES Modules
* `import`
* `export`
* تفاوت CommonJS و ES Modules
* استفاده از Moduleها در Node.js

**تمرین**

[مشاهده فصل ۴۰ ←](./6.10.md)

---

# 🗺️ مسیر یادگیری این بخش

```text
بخش ۶ - مفاهیم پیشرفته JavaScript
│
├── فصل ۳۱ - Execution Context
│
├── فصل ۳۲ - Call Stack
│
├── فصل ۳۳ - Memory
│   ├── Stack
│   ├── Heap
│   ├── Reference
│   └── Memory Management
│
├── فصل ۳۴ - Garbage Collection
│   ├── Garbage Collection
│   ├── Memory Leak
│   └── مدیریت حافظه
│
├── فصل ۳۵ - Event Loop
│   ├── Call Stack
│   ├── Event Loop
│   ├── Task Queue
│   ├── Microtask Queue
│   └── Asynchronous Operations
│
├── فصل ۳۶ - Callback
│   ├── Callback Function
│   ├── Asynchronous Callback
│   └── Callback Hell
│
├── فصل ۳۷ - Promise
│   ├── pending
│   ├── fulfilled
│   ├── rejected
│   ├── then
│   ├── catch
│   ├── finally
│   └── Promise Chaining
│
├── فصل ۳۸ - Async Await
│   ├── async
│   ├── await
│   ├── try/catch
│   └── Promise Methods
│
├── فصل ۳۹ - Error Handling
│   ├── try
│   ├── catch
│   ├── finally
│   └── throw
│
└── فصل ۴۰ - Module System
    ├── CommonJS
    ├── require
    ├── module.exports
    ├── ES Modules
    ├── import
    └── export
```

---

# 🎯 هدف بخش ۶

در پایان این بخش باید بتوانید:

* مفهوم Execution Context را درک کنید.
* نحوه اجرای Functionها در Call Stack را توضیح دهید.
* تفاوت Stack و Heap را درک کنید.
* نحوه مدیریت حافظه در JavaScript را بشناسید.
* مفهوم Garbage Collection را درک کنید.
* مفهوم Memory Leak را بشناسید.
* نحوه کار Event Loop را درک کنید.
* تفاوت عملیات Synchronous و Asynchronous را تشخیص دهید.
* Callbackها را ایجاد و مدیریت کنید.
* مشکل Callback Hell را درک کنید.
* با Promiseها کار کنید.
* وضعیت‌های مختلف Promise را بشناسید.
* Promise Chain ایجاد کنید.
* از `async/await` برای نوشتن کدهای Asynchronous استفاده کنید.
* خطاهای کدهای Synchronous و Asynchronous را مدیریت کنید.
* از `try/catch/finally` و `throw` استفاده کنید.
* با CommonJS و ES Modules کار کنید.
* Moduleهای مختلف را در پروژه‌های Node.js ایجاد و استفاده کنید.
* ساختار برنامه‌های خود را با Moduleها بهتر سازمان‌دهی کنید.

---

# 🧩 تمرین‌های این بخش

در طول فصل‌های این بخش تمرین‌های مختلفی برای درک بهتر نحوه اجرای JavaScript و کار با عملیات Asynchronous ارائه می‌شود.

تمرین‌ها از مفاهیم ساده مانند Call Stack و Callback شروع شده و به مباحثی مانند Promise، Async/Await، مدیریت خطا و Module System می‌رسند.

هدف این تمرین‌ها این است که فقط Syntax را حفظ نکنید، بلکه **نحوه اجرای کد JavaScript و رفتار برنامه در Node.js** را نیز درک کنید.

---

# 🚀 پروژه‌های پیشنهادی این بخش

برای تثبیت مفاهیم این بخش می‌توان پروژه‌های کوچکی مانند موارد زیر را پیاده‌سازی کرد:

* برنامه اجرای چند عملیات Asynchronous
* سیستم ساده مدیریت Taskهای Asynchronous
* برنامه دریافت چند داده به‌صورت هم‌زمان با Promise
* برنامه پردازش فایل با Async/Await
* سیستم ساده مدیریت خطا
* پروژه چندفایلی با CommonJS
* پروژه چندفایلی با ES Modules

---

# ⏭️ بخش بعدی

پس از یادگیری مفاهیم پیشرفته JavaScript، در بخش بعدی وارد **برنامه‌نویسی شی‌گرا (OOP)** می‌شویم و با مفاهیمی مانند Prototype، Class، Inheritance، Polymorphism، Encapsulation و Abstraction آشنا خواهیم شد.

[بخش ۷ - برنامه‌نویسی شی‌گرا →](../part%207/README.md)

---

<div align="center">

[بخش بعد ➡️](../part%207/) • [📚 فهرست مطالب](../readme.md) • [⬅️ بخش قبل](../part%205/)

</div>
