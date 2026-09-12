# بخش ۱۶ - ابزارهای توسعه

وقتی یک پروژه Node.js از مرحله یادگیری و تمرین عبور می‌کند، فقط نوشتن کد کافی نیست؛ یک برنامه‌نویس حرفه‌ای باید بتواند **کد را مدیریت، بررسی، استانداردسازی، نسخه‌بندی، اجرا، تست و در نهایت Deploy** کند.

در این بخش با ابزارهایی آشنا می‌شویم که در پروژه‌های واقعی Node.js بسیار پرکاربرد هستند. از **Git و GitHub** برای مدیریت نسخه و همکاری تیمی شروع می‌کنیم، سپس به ابزارهای کیفیت و استاندارد کد مانند **ESLint و Prettier** می‌رسیم و در ادامه با **Husky و Nodemon**، کانتینرسازی با **Docker و Docker Compose** و در نهایت **CI/CD** آشنا می‌شویم.

هدف این بخش این است که علاوه بر یادگیری Node.js، با **Workflow واقعی توسعه نرم‌افزار** نیز آشنا شوید.

---

# 📚 فهرست مطالب

## فصل ۱۲۶ - Git

Git یکی از مهم‌ترین ابزارهای مدیریت نسخه است و تقریباً در تمام پروژه‌های حرفه‌ای نرم‌افزاری استفاده می‌شود.

### مباحث این فصل

* Version Control چیست؟
* Git چیست؟
* چرا Git مهم است؟
* نصب Git
* تنظیمات اولیه Git
* Git Config
* ساخت Repository
* Git Repository
* Working Directory
* Staging Area
* Commit
* وضعیت فایل‌ها
* `git status`
* `git add`
* `git commit`
* مشاهده Commitها
* `git log`
* اصلاح Commit
* حذف فایل از Git
* `.gitignore`
* Branch
* ساخت Branch
* تغییر Branch
* حذف Branch
* Merge
* Merge Conflict
* حل Conflict
* Rebase
* تفاوت Merge و Rebase
* Stash
* Tag
* Git Diff
* Git Restore
* Git Reset
* Git Revert
* Cherry-pick
* Remote Repository
* Push
* Pull
* Fetch
* تفاوت Pull و Fetch
* Git Workflow
* Git در پروژه‌های Node.js
* مدیریت `node_modules`
* مدیریت فایل‌های حساس
* Commit Message استاندارد
* Git Best Practices

**تمرین‌های زیاد**

**مینی‌پروژه:** مدیریت نسخه یک پروژه Node.js با Git

[مشاهده فصل ۱۲۶ ←](./16.1.md)

---

## فصل ۱۲۷ - GitHub

GitHub یک پلتفرم برای میزبانی Repositoryهای Git و همکاری تیمی روی پروژه‌های نرم‌افزاری است.

### مباحث این فصل

* GitHub چیست؟
* تفاوت Git و GitHub
* ساخت حساب GitHub
* ساخت Repository
* اتصال پروژه Node.js به GitHub
* Remote
* Push کردن پروژه
* Pull کردن پروژه
* Clone
* Fork
* Branch در GitHub
* Pull Request
* Code Review
* Merge Pull Request
* Issue
* Label
* Milestone
* Project
* README
* `.gitignore`
* License
* Release
* Tag
* GitHub Actions چیست؟
* مدیریت Secretها
* GitHub Profile
* ساخت GitHub حرفه‌ای
* مشارکت در Open Source
* Contribution
* مدیریت پروژه تیمی
* GitHub Workflow

**تمرین‌های زیاد**

**مینی‌پروژه:** انتشار یک پروژه Node.js در GitHub و ایجاد Pull Request

[مشاهده فصل ۱۲۷ ←](./16.2.md)

---

## فصل ۱۲۸ - ESLint

ESLint ابزاری برای پیدا کردن مشکلات، خطاهای احتمالی و الگوهای نامناسب در کد JavaScript است.

### مباحث این فصل

* Linter چیست؟
* ESLint چیست؟
* چرا Linting مهم است؟
* نصب ESLint
* راه‌اندازی ESLint
* Configuration
* Rule
* Error و Warning
* اجرای ESLint
* بررسی فایل‌ها
* بررسی کل پروژه
* Auto Fix
* `eslint --fix`
* ESLint در پروژه Node.js
* ESLint و JavaScript
* ESLint Rules
* قوانین مربوط به Variables
* قوانین مربوط به Functions
* قوانین مربوط به Async Code
* قوانین مربوط به Promise
* قوانین مربوط به Error Handling
* ESLint و ES Modules
* ESLint و CommonJS
* Ignore کردن فایل‌ها
* Config کردن ESLint
* استفاده از Presetها
* Pluginها
* تنظیم ESLint برای پروژه واقعی
* ESLint در تیم
* ESLint در CI/CD

**تمرین‌های زیاد**

**مینی‌پروژه:** استانداردسازی یک پروژه Node.js با ESLint

[مشاهده فصل ۱۲۸ ←](./16.3.md)

---

## فصل ۱۲۹ - Prettier

Prettier ابزاری برای قالب‌بندی خودکار کد است و کمک می‌کند تمام اعضای تیم از یک Style یکسان استفاده کنند.

### مباحث این فصل

* Formatter چیست؟
* Prettier چیست؟
* چرا Formatting مهم است؟
* نصب Prettier
* اجرای Prettier
* Format کردن فایل‌ها
* Format کردن کل پروژه
* Auto Format
* تنظیمات Prettier
* `.prettierrc`
* `.prettierignore`
* Formatting در VS Code
* Format on Save
* تفاوت Prettier و ESLint
* استفاده همزمان ESLint و Prettier
* جلوگیری از Conflict بین ESLint و Prettier
* استانداردسازی Style پروژه
* Prettier در پروژه Node.js
* Prettier در تیم
* Prettier در CI/CD
* Best Practices

**تمرین**

**مینی‌پروژه:** اضافه کردن Prettier به یک پروژه Node.js

[مشاهده فصل ۱۲۹ ←](./16.4.md)

---

## فصل ۱۳۰ - Husky

Husky برای اجرای Scriptها و بررسی خودکار پروژه هنگام رخ دادن Git Hookها استفاده می‌شود.

### مباحث این فصل

* Git Hooks چیست؟
* Husky چیست؟
* چرا Husky استفاده می‌شود؟
* نصب Husky
* راه‌اندازی Husky
* Pre-commit
* Pre-push
* اجرای ESLint هنگام Commit
* اجرای Prettier هنگام Commit
* اجرای Test هنگام Commit
* جلوگیری از Commit کد مشکل‌دار
* اجرای Scriptهای npm
* Husky در پروژه Node.js
* Husky و Git
* Hookهای کاربردی
* مدیریت Configuration
* Husky در تیم
* Husky در پروژه‌های واقعی
* Best Practices

**تمرین**

**مینی‌پروژه:** ساخت Pre-commit Hook برای بررسی و Format کردن کد

[مشاهده فصل ۱۳۰ ←](./16.5.md)

---

## فصل ۱۳۱ - Nodemon

Nodemon ابزاری برای توسعه Node.js است که هنگام تغییر فایل‌ها، برنامه را به‌صورت خودکار Restart می‌کند.

### مباحث این فصل

* Nodemon چیست؟
* چرا Nodemon استفاده می‌شود؟
* نصب Nodemon
* نصب Local و Global
* اجرای پروژه با Nodemon
* Scriptهای npm
* Watch کردن فایل‌ها
* Ignore کردن فایل‌ها
* تنظیمات Nodemon
* `nodemon.json`
* اجرای Server با Nodemon
* Nodemon و Express
* Nodemon و Environment Variables
* Restart خودکار
* تفاوت Nodemon و اجرای مستقیم Node.js
* Nodemon در Development
* استفاده صحیح از Nodemon
* مشکلات رایج Nodemon
* Best Practices

**تمرین**

**مینی‌پروژه:** ساخت محیط Development خودکار برای یک Node.js Server

[مشاهده فصل ۱۳۱ ←](./16.6.md)

---

## فصل ۱۳۲ - Docker

Docker امکان اجرای برنامه‌ها را در محیط‌های ایزوله و قابل‌انتقال فراهم می‌کند و یکی از ابزارهای مهم در توسعه و استقرار پروژه‌های Node.js است.

### مباحث این فصل

* Container چیست؟
* Docker چیست؟
* چرا Docker استفاده می‌شود؟
* تفاوت Container و Virtual Machine
* نصب Docker
* Docker CLI
* Image چیست؟
* Container چیست؟
* Registry چیست؟
* Docker Hub
* ساخت Container
* اجرای Container
* توقف Container
* حذف Container
* مشاهده Containerها
* مشاهده Imageها
* Dockerfile
* ساخت Docker Image
* `FROM`
* `WORKDIR`
* `COPY`
* `RUN`
* `CMD`
* `ENTRYPOINT`
* `EXPOSE`
* `.dockerignore`
* Docker کردن پروژه Node.js
* نصب Dependencyها در Container
* Production Image
* Development Container
* Environment Variables
* Port Mapping
* Volume
* Bind Mount
* Container Networking
* Docker Network
* Multi-stage Build
* کاهش حجم Image
* اجرای Node.js در Docker
* مدیریت `node_modules`
* Docker Best Practices
* امنیت Container
* Docker در Production

**تمرین‌های زیاد**

**مینی‌پروژه:** Dockerize کردن یک Node.js REST API

[مشاهده فصل ۱۳۲ ←](./16.7.md)

---

## فصل ۱۳۳ - Docker Compose

Docker Compose برای اجرای چند Container مرتبط با یکدیگر استفاده می‌شود و برای پروژه‌های Node.js دارای Database و سرویس‌های مختلف بسیار کاربردی است.

### مباحث این فصل

* Docker Compose چیست؟
* چرا Docker Compose استفاده می‌شود؟
* فایل Compose
* `compose.yaml`
* Service
* Image
* Build
* Container
* Port
* Environment
* Volume
* Network
* Dependency بین سرویس‌ها
* `depends_on`
* اجرای Compose
* Stop کردن سرویس‌ها
* Restart کردن سرویس‌ها
* مشاهده Logs
* اجرای Command داخل Container
* Development Environment
* Node.js + PostgreSQL
* Node.js + MongoDB
* Node.js + Redis
* چند سرویس در یک پروژه
* ارتباط Containerها
* مدیریت Environment Variables
* Persistent Data
* Health Check
* Docker Compose در پروژه‌های واقعی
* Compose برای Development
* تفاوت Docker و Docker Compose
* Best Practices

**تمرین‌های زیاد**

**مینی‌پروژه:** اجرای Node.js + Database + Redis با Docker Compose

[مشاهده فصل ۱۳۳ ←](./16.8.md)

---

## فصل ۱۳۴ - CI/CD

CI/CD مجموعه‌ای از روش‌ها و فرآیندها برای خودکارسازی Build، Test و Delivery/Deployment نرم‌افزار است.

### مباحث این فصل

* CI چیست؟
* CD چیست؟
* Continuous Integration
* Continuous Delivery
* Continuous Deployment
* چرا CI/CD مهم است؟
* Pipeline چیست؟
* Workflow چیست؟
* Build
* Test
* Lint
* Format Check
* Environment
* Secret
* Artifact
* GitHub Actions
* Workflow File
* Trigger
* Job
* Step
* Runner
* اجرای Pipeline با Push
* اجرای Pipeline با Pull Request
* اجرای Test خودکار
* اجرای ESLint
* اجرای Prettier Check
* Build کردن پروژه
* Environment Variables
* Secrets
* Docker در CI/CD
* ساخت Docker Image
* Push کردن Image
* Deployment
* Rollback
* Branch Strategy
* Development Pipeline
* Production Pipeline
* CI/CD برای Node.js
* CI/CD برای پروژه‌های Docker
* مدیریت خطاهای Pipeline
* Best Practices

**تمرین‌های زیاد**

**مینی‌پروژه:** ساخت Pipeline کامل CI برای یک پروژه Node.js

[مشاهده فصل ۱۳۴ ←](./16.9.md)

---

# 🗺️ مسیر یادگیری این بخش

```text
ابزارهای توسعه
│
├── Git
│   ├── Repository
│   ├── Commit
│   ├── Branch
│   ├── Merge
│   ├── Rebase
│   └── Remote
│
├── GitHub
│   ├── Repository
│   ├── Pull Request
│   ├── Issue
│   ├── Code Review
│   └── GitHub Actions
│
├── ESLint
│   ├── Linting
│   ├── Rules
│   ├── Plugins
│   └── Auto Fix
│
├── Prettier
│   ├── Formatting
│   ├── Configuration
│   └── Format on Save
│
├── Husky
│   ├── Git Hooks
│   ├── Pre-commit
│   └── Pre-push
│
├── Nodemon
│   ├── Watch
│   ├── Auto Restart
│   └── Development
│
├── Docker
│   ├── Image
│   ├── Container
│   ├── Dockerfile
│   ├── Volume
│   └── Network
│
├── Docker Compose
│   ├── Services
│   ├── Database
│   ├── Redis
│   ├── Volume
│   └── Network
│
└── CI/CD
    ├── CI
    ├── CD
    ├── Pipeline
    ├── GitHub Actions
    ├── Test
    ├── Build
    └── Deployment
```

---

# 🎯 هدف بخش ۱۶

در پایان این بخش باید بتوانید:

* مفهوم Version Control را درک کنید.
* با Git پروژه‌های Node.js را مدیریت کنید.
* Repository بسازید و Commit ایجاد کنید.
* Branch بسازید و مدیریت کنید.
* Merge و Rebase را انجام دهید.
* Merge Conflict را حل کنید.
* با Remote Repository کار کنید.
* پروژه Node.js را در GitHub قرار دهید.
* Pull Request ایجاد کنید.
* Code Review انجام دهید.
* Issue و Project را مدیریت کنید.
* یک GitHub حرفه‌ای داشته باشید.
* کد JavaScript و Node.js را با ESLint بررسی کنید.
* Ruleهای ESLint را مدیریت کنید.
* کد را با Prettier استاندارد و Format کنید.
* ESLint و Prettier را در کنار یکدیگر استفاده کنید.
* Git Hook ایجاد کنید.
* با Husky عملیات قبل از Commit و Push را خودکار کنید.
* هنگام تغییر کد، پروژه Node.js را با Nodemon به‌صورت خودکار Restart کنید.
* مفهوم Container و Image را درک کنید.
* برای پروژه Node.js یک Dockerfile بنویسید.
* پروژه Node.js را Dockerize کنید.
* Volume و Network را در Docker مدیریت کنید.
* پروژه‌های چندسرویسی را با Docker Compose اجرا کنید.
* Node.js را در کنار Database و Redis اجرا کنید.
* مفهوم CI/CD را درک کنید.
* Pipeline ایجاد کنید.
* Test و Lint را به Pipeline اضافه کنید.
* پروژه Node.js را به‌صورت خودکار Build کنید.
* با GitHub Actions یک Workflow واقعی ایجاد کنید.
* Secretها و Environment Variables را در CI/CD مدیریت کنید.
* یک Workflow استاندارد برای توسعه پروژه‌های Node.js داشته باشید.

---

# 🧩 تمرین‌های این بخش

تمرین‌های این بخش از دستورات ساده Git شروع می‌شوند و به ساخت یک Workflow حرفه‌ای برای پروژه Node.js می‌رسند.

تمرین‌ها شامل:

* ساخت Repository
* ایجاد Commit
* کار با Branch
* Merge کردن Branchها
* حل Merge Conflict
* استفاده از Stash
* کار با Remote
* Push و Pull
* ساخت Repository در GitHub
* ایجاد Pull Request
* انجام Code Review
* ساخت `.gitignore`
* تنظیم ESLint
* رفع خطاهای ESLint
* تنظیم Prettier
* Format کردن پروژه
* ترکیب ESLint و Prettier
* ساخت Git Hook
* اجرای ESLint هنگام Commit
* اجرای Test هنگام Push
* راه‌اندازی Nodemon
* ساخت Dockerfile
* Dockerize کردن Node.js
* ساخت Image
* اجرای Container
* مدیریت Volume
* ساخت Network
* اجرای چند Container
* ساخت Docker Compose
* اتصال Node.js به PostgreSQL
* اتصال Node.js به Redis
* ساخت CI Pipeline
* اجرای خودکار Test
* اجرای ESLint در Pipeline
* Build کردن پروژه
* ساخت Docker Image در CI/CD

تمام تمرین‌ها همراه با **پاسخ تشریحی** ارائه خواهند شد.

---

# 🚀 پروژه‌های پیشنهادی این بخش

برای اینکه ابزارها فقط به‌صورت تئوری یاد گرفته نشوند، آن‌ها را در چند پروژه مرحله‌ای استفاده خواهیم کرد:

1. مدیریت یک پروژه Node.js با Git
2. انتشار پروژه در GitHub
3. ساخت Workflow تیمی با Branch و Pull Request
4. استانداردسازی پروژه با ESLint
5. Format خودکار پروژه با Prettier
6. ساخت Pre-commit Hook با Husky
7. محیط Development خودکار با Nodemon
8. Dockerize کردن یک Node.js API
9. اجرای Node.js + PostgreSQL با Docker Compose
10. اجرای Node.js + Redis با Docker Compose
11. ساخت محیط کامل Development با چند Container
12. ساخت CI Pipeline برای یک REST API
13. اجرای Test و Lint به‌صورت خودکار
14. ساخت Docker Image در Pipeline
15. **پروژه نهایی بخش:** ساخت Workflow حرفه‌ای برای یک پروژه Node.js شامل Git، GitHub، ESLint، Prettier، Husky، Docker، Docker Compose و CI/CD

---

# ⏭️ بخش بعدی

بعد از یادگیری ابزارهای توسعه، آماده می‌شویم تا وارد دنیای **فریمورک‌های Node.js** شویم و با ابزارهایی کار کنیم که توسعه Backend واقعی را سریع‌تر، ساختاریافته‌تر و حرفه‌ای‌تر می‌کنند.

در **بخش ۱۷ - فریمورک‌های Node.js** ابتدا با Express.js شروع می‌کنیم و سپس سراغ Fastify، NestJS، Hono، Koa، AdonisJS و Socket.IO می‌رویم.

[مشاهده بخش ۱۷ - فریمورک‌های Node.js →](../part%2017/README.md)

---

<div align="center">

[بخش بعد ➡️](../part%2017/) • [📚 فهرست مطالب](../readme.md) • [⬅️ بخش قبل](../part%2015/)

</div>
