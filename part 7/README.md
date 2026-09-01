# بخش ۷ - برنامه‌نویسی شی‌گرا

در این بخش با **Object-Oriented Programming (OOP)** در JavaScript آشنا می‌شویم.

برنامه‌نویسی شی‌گرا یکی از مهم‌ترین روش‌های سازمان‌دهی و طراحی کد در پروژه‌های بزرگ است. در این بخش ابتدا با مفهوم Object و Prototype آشنا می‌شویم و سپس به سراغ Class، Constructor، Inheritance و سایر مفاهیم اصلی OOP می‌رویم.

هدف این بخش این است که بتوانیم کدهای خود را بهتر سازمان‌دهی کنیم و برای ساخت پروژه‌های بزرگ‌تر Node.js آماده شویم.

---

# 📚 فهرست مطالب

## فصل ۴۱ - Object Oriented Programming

در این فصل با مفهوم برنامه‌نویسی شی‌گرا و نحوه تفکر مبتنی بر Object آشنا می‌شویم.

* Object-Oriented Programming چیست؟
* Object چیست؟
* مفهوم Class
* مفهوم Instance
* ویژگی‌ها و رفتارها
* مزایای OOP
* OOP در JavaScript
* کاربرد OOP در Node.js

**تمرین**

[مشاهده فصل ۴۱ ←](./7.1.md)

---

## فصل ۴۲ - Prototype

در این فصل با Prototype و نحوه پیاده‌سازی وراثت در JavaScript آشنا می‌شویم.

* Prototype چیست؟
* Prototype Chain
* `prototype`
* `__proto__`
* ارتباط Object و Prototype
* Prototype Inheritance
* نحوه جستجوی Property و Method

**تمرین**

[مشاهده فصل ۴۲ ←](./7.2.md)

---

## فصل ۴۳ - Class

در این فصل با Class Syntax در JavaScript آشنا می‌شویم و یاد می‌گیریم چگونه ساختارهای شی‌گرا ایجاد کنیم.

* Class چیست؟
* تعریف Class
* ساخت Instance
* Properties
* Methods
* Static Members
* Getter
* Setter
* Private Fields

**تمرین**

[مشاهده فصل ۴۳ ←](./7.3.md)

---

## فصل ۴۴ - Constructor

در این فصل با Constructor و نقش آن هنگام ایجاد Instance از Class آشنا می‌شویم.

* Constructor چیست؟
* `constructor()`
* مقداردهی اولیه Properties
* دریافت Parameters
* استفاده از `this`
* Constructor در Class
* Constructor در Inheritance

**تمرین**

[مشاهده فصل ۴۴ ←](./7.4.md)

---

## فصل ۴۵ - Inheritance

در این فصل با مفهوم Inheritance یا وراثت آشنا می‌شویم و یاد می‌گیریم چگونه یک Class می‌تواند ویژگی‌ها و رفتارهای Class دیگری را به ارث ببرد.

* Inheritance چیست؟
* `extends`
* `super`
* Parent Class
* Child Class
* Method Inheritance
* Property Inheritance
* Method Overriding

**تمرین**

[مشاهده فصل ۴۵ ←](./7.5.md)

---

## فصل ۴۶ - Polymorphism

در این فصل با Polymorphism یا چندریختی آشنا می‌شویم و یاد می‌گیریم چگونه Objectهای مختلف می‌توانند رفتار متفاوتی برای یک Interface یا Method داشته باشند.

* Polymorphism چیست؟
* Method Overriding
* Polymorphism در JavaScript
* استفاده از Polymorphism در طراحی برنامه
* مثال‌های کاربردی

**تمرین**

[مشاهده فصل ۴۶ ←](./7.6.md)

---

## فصل ۴۷ - Encapsulation

در این فصل با Encapsulation یا کپسوله‌سازی آشنا می‌شویم و یاد می‌گیریم چگونه داده‌ها و رفتارهای مرتبط را در یک ساختار مشخص قرار دهیم.

* Encapsulation چیست؟
* کنترل دسترسی به داده‌ها
* Public Properties
* Private Properties
* Private Fields
* Getter و Setter
* محافظت از وضعیت داخلی Object

**تمرین**

[مشاهده فصل ۴۷ ←](./7.7.md)

---

## فصل ۴۸ - Abstraction

در این فصل با Abstraction یا انتزاع آشنا می‌شویم و یاد می‌گیریم چگونه جزئیات غیرضروری را از مصرف‌کننده کد پنهان کنیم.

* Abstraction چیست؟
* چرا به Abstraction نیاز داریم؟
* پنهان کردن جزئیات پیاده‌سازی
* طراحی Interface
* Abstraction در JavaScript
* Abstraction در پروژه‌های Node.js

**تمرین**

[مشاهده فصل ۴۸ ←](./7.8.md)

---

## فصل ۴۹ - this

در این فصل با یکی از مهم‌ترین و در عین حال چالش‌برانگیزترین مفاهیم JavaScript یعنی `this` آشنا می‌شویم.

* `this` چیست؟
* `this` در Global Context
* `this` در Function
* `this` در Method
* `this` در Arrow Function
* `this` در Class
* `this` در Constructor
* تغییر Context
* ارتباط `this` با Object

**تمرین**

[مشاهده فصل ۴۹ ←](./7.9.md)

---

## فصل ۵۰ - bind، call و apply

در این فصل با متدهای `bind`، `call` و `apply` آشنا می‌شویم و یاد می‌گیریم چگونه Context اجرای Function را کنترل کنیم.

* `call`
* `apply`
* `bind`
* تفاوت `call` و `apply`
* تفاوت `bind` با `call` و `apply`
* تغییر مقدار `this`
* کاربردهای عملی
* استفاده در پروژه‌های واقعی

**تمرین‌های کامل**

[مشاهده فصل ۵۰ ←](./7.10.md)

---

# 🗺️ مسیر یادگیری این بخش

```text
بخش ۷ - برنامه‌نویسی شی‌گرا
│
├── فصل ۴۱ - Object Oriented Programming
│   ├── Object
│   ├── Class
│   ├── Instance
│   ├── Properties
│   └── Methods
│
├── فصل ۴۲ - Prototype
│   ├── Prototype
│   ├── Prototype Chain
│   ├── prototype
│   ├── __proto__
│   └── Prototype Inheritance
│
├── فصل ۴۳ - Class
│   ├── Class
│   ├── Instance
│   ├── Properties
│   ├── Methods
│   ├── Static
│   ├── Getter
│   ├── Setter
│   └── Private Fields
│
├── فصل ۴۴ - Constructor
│   ├── constructor()
│   ├── Parameters
│   ├── this
│   └── Initialization
│
├── فصل ۴۵ - Inheritance
│   ├── extends
│   ├── super
│   ├── Parent Class
│   ├── Child Class
│   └── Method Overriding
│
├── فصل ۴۶ - Polymorphism
│   ├── Polymorphism
│   ├── Method Overriding
│   └── رفتارهای متفاوت
│
├── فصل ۴۷ - Encapsulation
│   ├── Public
│   ├── Private
│   ├── Private Fields
│   ├── Getter
│   └── Setter
│
├── فصل ۴۸ - Abstraction
│   ├── Abstraction
│   ├── Interface
│   └── پنهان کردن جزئیات
│
├── فصل ۴۹ - this
│   ├── Global
│   ├── Function
│   ├── Method
│   ├── Arrow Function
│   └── Class
│
└── فصل ۵۰ - bind / call / apply
    ├── call
    ├── apply
    ├── bind
    └── کنترل this
```

---

# 🎯 هدف بخش ۷

در پایان این بخش باید بتوانید:

* مفهوم Object-Oriented Programming را درک کنید.
* Object، Class و Instance را از یکدیگر تشخیص دهید.
* با Prototype و Prototype Chain کار کنید.
* نحوه وراثت در JavaScript را درک کنید.
* Class ایجاد کنید.
* Constructor تعریف کنید.
* از `this` به‌درستی استفاده کنید.
* بین Classها Inheritance ایجاد کنید.
* از `extends` و `super` استفاده کنید.
* Methodها را Override کنید.
* مفهوم Polymorphism را درک کنید.
* داده‌ها و رفتارهای Object را با Encapsulation مدیریت کنید.
* از Private Fields استفاده کنید.
* مفهوم Abstraction را در طراحی کد درک کنید.
* رفتار `this` را در Contextهای مختلف پیش‌بینی کنید.
* از `call`، `apply` و `bind` استفاده کنید.
* کدهای شی‌گرا و قابل‌مدیریت‌تری برای پروژه‌های Node.js بنویسید.

---

# 🧩 تمرین‌های این بخش

در این بخش تمرین‌ها از مفاهیم ساده Object و Class شروع می‌شوند و به‌تدریج به Prototype، Inheritance، Polymorphism، Encapsulation، Abstraction و مدیریت `this` می‌رسند.

تمرین‌ها به‌گونه‌ای طراحی می‌شوند که مفاهیم OOP فقط به‌صورت تئوری یاد گرفته نشوند و بتوانید آن‌ها را در ساختار پروژه‌های واقعی Node.js به کار ببرید.

---

# 🚀 پروژه‌های پیشنهادی این بخش

برای تثبیت مفاهیم OOP می‌توان پروژه‌های کوچک زیر را پیاده‌سازی کرد:

* سیستم مدیریت کاربران
* سیستم مدیریت محصولات
* سیستم حساب بانکی
* سیستم مدیریت کتابخانه
* سیستم مدیریت کارها (Task Manager)
* سیستم مدیریت سفارش‌ها
* سیستم ساده فروشگاه
* سیستم مدیریت کارمندان

در این پروژه‌ها تلاش می‌کنیم ساختار برنامه را با استفاده از **Class، Encapsulation، Inheritance و Polymorphism** طراحی کنیم.

---

# ⏭️ بخش بعدی

پس از یادگیری JavaScript و مفاهیم OOP، وارد بخش **Node.js Core** می‌شویم و با معماری Node.js، Event-Driven Architecture، Libuv، EventEmitter، Process، Buffer، Streams و سایر قابلیت‌های اصلی Node.js آشنا خواهیم شد.

[بخش ۸ - Node.js Core →](../part%208/README.md)

---

<div align="center">

[بخش بعد ➡️](../part%208/) • [📚 فهرست مطالب](../readme.md) • [⬅️ بخش قبل](../part%206/)

</div>
