بخش ۱۳ - تست

تست‌نویسی یکی از مهم‌ترین مهارت‌ها در توسعه نرم‌افزار حرفه‌ای است. با تست می‌توانیم مطمئن شویم بخش‌های مختلف برنامه همان‌طور که انتظار داریم کار می‌کنند و تغییرات جدید باعث خراب شدن قابلیت‌های قبلی نمی‌شوند.

در این بخش از مفاهیم پایه Testing شروع می‌کنیم و سپس به سراغ Unit Test، Integration Test، Jest، Mock و Coverage می‌رویم. هدف این است که بتوانیم برای برنامه‌های Node.js تست‌های قابل اعتماد، قابل نگهداری و کاربردی بنویسیم.

---

📚 فهرست مطالب

فصل ۱۰۲ - Testing چیست؟

در این فصل با مفهوم تست نرم‌افزار، دلیل استفاده از آن و نقش تست در پروژه‌های واقعی آشنا می‌شویم.

مباحث این فصل

- Testing چیست؟
- چرا تست می‌نویسیم؟
- اهمیت تست در پروژه‌های واقعی
- Bug چیست؟
- Test Case چیست؟
- Test Suite چیست؟
- Test Runner چیست؟
- Test Assertion چیست؟
- Test Environment
- تفاوت تست دستی و تست خودکار
- Automated Testing
- انواع تست نرم‌افزار
- Unit Test
- Integration Test
- End-to-End Test
- تفاوت انواع تست
- Test Pyramid
- تست در پروژه‌های Node.js
- ساختار مناسب فایل‌های تست
- اصول اولیه تست‌نویسی

تمرین‌های زیاد

مینی‌پروژه: طراحی سناریوهای تست برای یک برنامه ساده Node.js

"مشاهده فصل ۱۰۲ ←" (./13.1.md)

---

فصل ۱۰۳ - Unit Test

Unit Test برای بررسی کوچک‌ترین واحدهای قابل تست برنامه استفاده می‌شود.

مباحث این فصل

- Unit Test چیست؟
- Unit چیست؟
- هدف Unit Testing
- تست Function
- تست Method
- تست خروجی Function
- Input و Output
- Assertion
- Arrange
- Act
- Assert
- تست حالت موفق
- تست حالت ناموفق
- Edge Case
- تست Error
- Isolation
- ویژگی‌های یک Unit Test خوب
- نام‌گذاری تست‌ها
- ساختار فایل‌های Unit Test
- Unit Test در Node.js

تمرین‌های زیاد

مینی‌پروژه: نوشتن Unit Test برای مجموعه‌ای از Functionهای JavaScript

"مشاهده فصل ۱۰۳ ←" (./13.2.md)

---

فصل ۱۰۴ - Integration Test

Integration Test برای بررسی همکاری چند بخش مختلف برنامه با یکدیگر استفاده می‌شود.

مباحث این فصل

- Integration Test چیست؟
- تفاوت Unit Test و Integration Test
- تست ارتباط چند Module
- تست Service
- تست Database
- تست API
- تست Request و Response
- تست لایه‌های مختلف برنامه
- Database Testing
- Test Environment
- Test Data
- مدیریت داده‌های تست
- Setup و Teardown
- Integration Test در Node.js
- تست ارتباط Backend و Database
- مزایا و معایب Integration Testing

تمرین‌های زیاد

مینی‌پروژه: تست Integration برای یک API متصل به Database

"مشاهده فصل ۱۰۴ ←" (./13.3.md)

---

فصل ۱۰۵ - Jest

Jest یکی از ابزارهای محبوب برای تست پروژه‌های JavaScript و Node.js است.

مباحث این فصل

- Jest چیست؟
- نصب Jest
- تنظیم Jest
- ساخت اولین Test
- Test File
- "test"
- "it"
- "describe"
- "expect"
- Matcherها
- "toBe"
- "toEqual"
- "toContain"
- "toBeTruthy"
- "toBeFalsy"
- "toThrow"
- تست Async Code
- تست Promise
- تست Async/Await
- Setup
- Teardown
- "beforeEach"
- "afterEach"
- "beforeAll"
- "afterAll"
- اجرای تست‌ها
- اجرای یک Test خاص
- Watch Mode
- Jest در پروژه Node.js

تمرین‌های زیاد

مینی‌پروژه: ساخت مجموعه تست Jest برای یک پروژه Node.js

"مشاهده فصل ۱۰۵ ←" (./13.4.md)

---

فصل ۱۰۶ - Mock

Mock برای جدا کردن بخش مورد آزمایش از وابستگی‌های خارجی استفاده می‌شود.

مباحث این فصل

- Mock چیست؟
- چرا Mock استفاده می‌کنیم؟
- Dependency چیست؟
- Mock Object
- Mock Function
- Stub
- Spy
- Fake
- تفاوت Mock، Stub، Spy و Fake
- Mock کردن Function
- Mock کردن Module
- Mock کردن API
- Mock کردن Database
- Mock کردن Service
- بررسی نحوه فراخوانی Function
- بررسی تعداد فراخوانی
- بررسی Arguments
- Mock در Jest
- مدیریت Dependencyها در تست

تمرین‌های زیاد

مینی‌پروژه: تست یک Service با Mock کردن Database و API

"مشاهده فصل ۱۰۶ ←" (./13.5.md)

---

فصل ۱۰۷ - Coverage

Coverage به ما کمک می‌کند بفهمیم چه مقدار از کد برنامه توسط تست‌ها پوشش داده شده است.

مباحث این فصل

- Code Coverage چیست؟
- چرا Coverage مهم است؟
- Line Coverage
- Statement Coverage
- Function Coverage
- Branch Coverage
- Coverage Report
- اجرای Coverage در Jest
- مشاهده گزارش Coverage
- تفسیر Coverage Report
- Coverage بالا و Coverage پایین
- آیا 100٪ Coverage همیشه خوب است؟
- شناسایی کدهای بدون تست
- تست Branchهای مختلف
- Coverage در پروژه‌های واقعی
- تنظیم حداقل Coverage
- Coverage Threshold
- بهبود Coverage
- محدودیت‌های Code Coverage

تمرین‌های زیاد

مینی‌پروژه: افزایش Coverage یک پروژه Node.js و تحلیل گزارش آن

"مشاهده فصل ۱۰۷ ←" (./13.6.md)

---

🗺️ مسیر یادگیری این بخش

تست
│
├── Testing چیست؟
│   ├── Test Case
│   ├── Test Suite
│   ├── Assertion
│   └── انواع تست
│
├── Unit Test
│   ├── Unit
│   ├── Arrange
│   ├── Act
│   ├── Assert
│   └── Edge Cases
│
├── Integration Test
│   ├── Module Integration
│   ├── API Testing
│   ├── Database Testing
│   └── Test Environment
│
├── Jest
│   ├── Test
│   ├── Describe
│   ├── Expect
│   ├── Matchers
│   └── Async Testing
│
├── Mock
│   ├── Mock
│   ├── Stub
│   ├── Spy
│   ├── Fake
│   └── Dependency Isolation
│
└── Coverage
    ├── Line Coverage
    ├── Statement Coverage
    ├── Function Coverage
    ├── Branch Coverage
    └── Coverage Threshold

---

🎯 هدف بخش ۱۳

در پایان این بخش باید بتوانید:

- مفهوم Testing را درک کنید.
- اهمیت تست در پروژه‌های واقعی را بدانید.
- انواع اصلی تست نرم‌افزار را بشناسید.
- Unit Test بنویسید.
- Integration Test بنویسید.
- تفاوت Unit و Integration Test را درک کنید.
- تست‌های پروژه Node.js را ساختاربندی کنید.
- با Jest کار کنید.
- Assertion و Matcherهای مختلف را استفاده کنید.
- کدهای Async را تست کنید.
- Dependencyهای برنامه را Mock کنید.
- تفاوت Mock، Stub، Spy و Fake را درک کنید.
- Database و API را در تست‌ها مدیریت کنید.
- Code Coverage را اندازه‌گیری کنید.
- Coverage Report را تحلیل کنید.
- Branchهای مختلف کد را تست کنید.
- برای پروژه‌های Node.js تست‌های قابل اعتماد بنویسید.

---

🧩 تمرین‌های این بخش

تمرین‌های این بخش از تست کردن Functionهای ساده شروع می‌شوند و به تست API، Database، Dependencyها و بررسی Coverage پروژه می‌رسند.

تمرین‌ها شامل:

- نوشتن Test Case
- نوشتن Unit Test
- تست Functionهای مختلف
- تست Edge Case
- تست Error
- نوشتن Integration Test
- تست API
- تست Database
- کار با Jest
- کار با Matcherها
- تست Promise و Async/Await
- Mock کردن Function
- Mock کردن Module
- Mock کردن API
- Mock کردن Database
- بررسی Coverage
- افزایش Coverage
- تحلیل Coverage Report

تمام تمرین‌ها همراه با پاسخ تشریحی ارائه خواهند شد.

---

🚀 پروژه‌های پیشنهادی این بخش

برای ترکیب مباحث این بخش، پروژه‌های زیر به‌صورت مرحله‌ای انجام می‌شوند:

1. تست Functionهای یک Calculator
2. Unit Test برای Utilityهای پروژه
3. Unit Test برای Serviceها
4. Integration Test برای API
5. Integration Test با Database
6. تست Authentication
7. Mock کردن Serviceهای خارجی
8. Mock کردن Database
9. ساخت Test Suite کامل با Jest
10. بررسی و افزایش Code Coverage
11. پروژه نهایی بخش: اضافه کردن سیستم تست کامل به یک Backend شامل Unit Test، Integration Test، Mock و Coverage

---

⏭️ بخش بعدی

بعد از یادگیری تست‌نویسی، نوبت به یکی از مهم‌ترین موضوعات توسعه Backend می‌رسد:

امنیت

در بخش بعدی با امنیت در Node.js، Hash کردن Password، Encryption، Helmet، Rate Limit، CORS، XSS، CSRF، SQL Injection، NoSQL Injection و Environment Variables آشنا خواهیم شد.

"مشاهده بخش ۱۴ - امنیت →" (../part%2014/)

---

<div align="center">"⬅️ بخش قبل" (../part%2012/) • "📚 فهرست مطالب" (../readme.md) • "بخش بعد ➡️" (../part%2014/)

</div>
