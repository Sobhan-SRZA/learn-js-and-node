# بخش ۱۲ - پایگاه داده

پایگاه داده یکی از مهم‌ترین بخش‌های هر برنامه Backend است. تقریباً تمام پروژه‌های واقعی نیاز دارند اطلاعاتی مانند کاربران، محصولات، سفارش‌ها، تراکنش‌ها و سایر داده‌ها را ذخیره، مدیریت و بازیابی کنند.

در این بخش با مفاهیم پایگاه داده و دو دنیای مهم **SQL** و **NoSQL** آشنا می‌شویم و سپس کار با PostgreSQL، MongoDB، ORM و ODM، Migration و Transaction را در Node.js یاد می‌گیریم.

---

# 📚 فهرست مطالب

## فصل ۹۵ - Database

در این فصل ابتدا با مفهوم پایگاه داده و نقش آن در یک برنامه Backend آشنا می‌شویم.

### مباحث این فصل

* Database چیست؟
* چرا به Database نیاز داریم؟
* Data چیست؟
* Database Server
* Database Management System
* DBMS
* انواع Database
* Relational Database
* NoSQL Database
* SQL و NoSQL
* Table
* Row
* Column
* Record
* Primary Key
* Foreign Key
* Relationship
* CRUD
* Database در معماری Backend
* ارتباط Node.js با Database
* انتخاب Database مناسب برای پروژه

**تمرین‌های زیاد**

**مینی‌پروژه:** طراحی Database برای یک سیستم مدیریت کاربران

[مشاهده فصل ۹۵ ←](./12.1.md)

---

## فصل ۹۶ - SQL

SQL زبان اصلی کار با بسیاری از پایگاه‌های داده رابطه‌ای است.

### مباحث این فصل

* SQL چیست؟
* Relational Database
* Database
* Table
* Row
* Column
* Data Type
* CREATE
* ALTER
* DROP
* INSERT
* SELECT
* UPDATE
* DELETE
* WHERE
* AND
* OR
* NOT
* ORDER BY
* GROUP BY
* HAVING
* LIMIT
* OFFSET
* DISTINCT
* LIKE
* IN
* BETWEEN
* NULL
* Aggregate Functions
* COUNT
* SUM
* AVG
* MIN
* MAX
* JOIN
* INNER JOIN
* LEFT JOIN
* RIGHT JOIN
* FULL JOIN
* Subquery
* Primary Key
* Foreign Key
* Constraint
* UNIQUE
* NOT NULL
* DEFAULT
* CHECK

**تمرین‌های زیاد**

**مینی‌پروژه:** طراحی و پیاده‌سازی Database یک فروشگاه

[مشاهده فصل ۹۶ ←](./12.2.md)

---

## فصل ۹۷ - PostgreSQL

PostgreSQL یکی از قدرتمندترین Databaseهای رابطه‌ای است و در پروژه‌های Backend حرفه‌ای کاربرد زیادی دارد.

### مباحث این فصل

* PostgreSQL چیست؟
* نصب PostgreSQL
* ایجاد Database
* ایجاد User
* اتصال به PostgreSQL
* Table
* Column
* Data Type
* Primary Key
* Foreign Key
* Constraint
* CRUD
* Query
* JOIN
* Relationship
* Index
* Transaction
* اتصال Node.js به PostgreSQL
* اجرای Query از Node.js
* مدیریت Connection
* Connection Pool
* مدیریت خطاهای Database

**تمرین‌های زیاد**

**مینی‌پروژه:** ساخت API مدیریت کاربران با PostgreSQL

[مشاهده فصل ۹۷ ←](./12.3.md)

---

## فصل ۹۸ - MongoDB

MongoDB یک Database مبتنی بر Document است که در بسیاری از پروژه‌های Node.js استفاده می‌شود.

### مباحث این فصل

* MongoDB چیست؟
* NoSQL چیست؟
* Document Database
* Collection
* Document
* BSON
* ObjectId
* نصب MongoDB
* MongoDB Atlas
* ایجاد Database
* ایجاد Collection
* Insert
* Find
* Update
* Delete
* Query
* Filter
* Sort
* Pagination
* Embedded Document
* Reference
* Relationship در MongoDB
* Index
* Aggregation
* اتصال Node.js به MongoDB
* مدیریت Connection

**تمرین‌های زیاد**

**مینی‌پروژه:** ساخت API مدیریت محصولات با MongoDB

[مشاهده فصل ۹۸ ←](./12.4.md)

---

## فصل ۹۹ - ORM و ODM

در پروژه‌های واقعی معمولاً برای ساده‌تر شدن ارتباط برنامه با Database از ابزارهایی مانند ORM و ODM استفاده می‌کنیم.

### مباحث این فصل

* ORM چیست؟
* ODM چیست؟
* تفاوت ORM و ODM
* مزایا و معایب ORM
* مزایا و معایب ODM
* Model
* Schema
* Query Builder
* Relation
* Migration
* Validation
* Prisma
* Drizzle
* Mongoose
* انتخاب ORM/ODM مناسب
* استفاده از ORM/ODM در Node.js

### ابزارهای مورد بررسی

* Prisma
* Drizzle
* Mongoose

**تمرین‌های زیاد**

**مینی‌پروژه:** پیاده‌سازی یک API با ORM/ODM

[مشاهده فصل ۹۹ ←](./12.5.md)

---

## فصل ۱۰۰ - Migration

Migration برای مدیریت تغییرات ساختار Database در طول عمر پروژه استفاده می‌شود.

### مباحث این فصل

* Migration چیست؟
* چرا Migration مهم است؟
* Schema Migration
* ایجاد Migration
* اجرای Migration
* Rollback
* Versioning
* تغییر Table
* اضافه کردن Column
* حذف Column
* تغییر Schema
* Migration در تیم‌های برنامه‌نویسی
* Migration در Production
* مدیریت Migrationها
* Migration با ORM
* Migration با Prisma
* Migration با ابزارهای دیگر

**تمرین**

**مینی‌پروژه:** مدیریت نسخه‌های Database یک پروژه با Migration

[مشاهده فصل ۱۰۰ ←](./12.6.md)

---

## فصل ۱۰۱ - Transaction

Transaction برای اجرای چند عملیات Database به‌صورت یک واحد منطقی استفاده می‌شود.

### مباحث این فصل

* Transaction چیست؟
* چرا Transaction مهم است؟
* مفهوم Atomicity
* ACID
* Atomicity
* Consistency
* Isolation
* Durability
* COMMIT
* ROLLBACK
* اجرای چند Query در Transaction
* مدیریت خطا در Transaction
* Transaction در PostgreSQL
* Transaction در MongoDB
* Transaction در Node.js
* Transaction با ORM
* کاربرد Transaction در پروژه‌های واقعی
* انتقال وجه
* ثبت سفارش
* مدیریت موجودی

**تمرین‌های زیاد**

**مینی‌پروژه:** ساخت سیستم ثبت سفارش با Transaction

[مشاهده فصل ۱۰۱ ←](./12.7.md)

---

# 🗺️ مسیر یادگیری این بخش

```text
پایگاه داده
│
├── Database
│   ├── DBMS
│   ├── Relational Database
│   ├── NoSQL
│   └── CRUD
│
├── SQL
│   ├── Query
│   ├── CRUD
│   ├── JOIN
│   ├── Constraint
│   └── Relationship
│
├── PostgreSQL
│   ├── Database
│   ├── Table
│   ├── Query
│   ├── Index
│   └── Transaction
│
├── MongoDB
│   ├── Collection
│   ├── Document
│   ├── Query
│   ├── Aggregation
│   └── Index
│
├── ORM / ODM
│   ├── Prisma
│   ├── Drizzle
│   └── Mongoose
│
├── Migration
│   ├── Schema
│   ├── Versioning
│   └── Rollback
│
└── Transaction
    ├── ACID
    ├── COMMIT
    ├── ROLLBACK
    └── Real-World Transactions
```

---

# 🎯 هدف بخش ۱۲

در پایان این بخش باید بتوانید:

* مفهوم Database را به‌خوبی درک کنید.
* تفاوت SQL و NoSQL را بدانید.
* مفاهیم پایه Database را بشناسید.
* SQL را برای کار با Database یاد بگیرید.
* Queryهای مختلف SQL بنویسید.
* از JOIN استفاده کنید.
* Relationship بین داده‌ها را طراحی کنید.
* با PostgreSQL کار کنید.
* PostgreSQL را به Node.js متصل کنید.
* با MongoDB کار کنید.
* MongoDB را به Node.js متصل کنید.
* تفاوت Database رابطه‌ای و Document Database را درک کنید.
* با ORM و ODM آشنا شوید.
* با Prisma، Drizzle و Mongoose کار کنید.
* ساختار Database را با Migration مدیریت کنید.
* Transaction را درک و پیاده‌سازی کنید.
* اصول ACID را بشناسید.
* Database مناسب برای یک پروژه را انتخاب کنید.
* در پروژه‌های Node.js با Database به شکل اصولی کار کنید.

---

# 🧩 تمرین‌های این بخش

تمرین‌های این بخش از مفاهیم ساده Database شروع شده و به طراحی Database و استفاده از آن در Backendهای واقعی می‌رسند.

تمرین‌ها شامل:

* طراحی Table
* نوشتن Queryهای SQL
* انجام عملیات CRUD
* کار با JOIN
* طراحی Relationship
* ساخت Database با PostgreSQL
* اتصال PostgreSQL به Node.js
* کار با MongoDB
* اتصال MongoDB به Node.js
* کار با Prisma
* کار با Drizzle
* کار با Mongoose
* ساخت Migration
* Rollback کردن Migration
* اجرای Transaction
* مدیریت خطا در Transaction

تمام تمرین‌ها همراه با **پاسخ تشریحی** ارائه خواهند شد.

---

# 🚀 پروژه‌های پیشنهادی این بخش

برای ترکیب مباحث این بخش، پروژه‌های زیر به‌صورت مرحله‌ای انجام می‌شوند:

1. طراحی Database سیستم کاربران
2. Database فروشگاه
3. CRUD کاربران با PostgreSQL
4. CRUD محصولات با PostgreSQL
5. API محصولات با MongoDB
6. سیستم مدیریت کاربران با MongoDB
7. API با Prisma
8. API با Drizzle
9. API با Mongoose
10. مدیریت Database با Migration
11. سیستم ثبت سفارش با Transaction
12. **پروژه نهایی بخش:** ساخت Backend فروشگاه با PostgreSQL، ORM، Migration و Transaction

---

# ⏭️ بخش بعدی

بعد از یادگیری Database و نحوه ذخیره و مدیریت داده‌ها، باید یاد بگیریم چگونه صحت عملکرد برنامه خود را بررسی کنیم.

در **بخش ۱۳ - تست** با مفاهیم Testing، Unit Test، Integration Test، Jest، Mock و Coverage آشنا خواهیم شد.

[مشاهده بخش ۱۳ - تست →](../part%2013/README.md)

---

<div align="center">

[بخش بعد ➡️](../part%2013/) • [📚 فهرست مطالب](../readme.md) • [⬅️ بخش قبل](../part%2011/)

</div>
