# README.md - فارسی

# پورفای (PourFi) - سیستم فروش فایل و پشتیبانی

![PourFi](https://img.shields.io/badge/PourFi-v1.0-blue)
![Laravel](https://img.shields.io/badge/Laravel-11.x-red)
![Filament](https://img.shields.io/badge/Filament-3.x-green)
![PHP](https://img.shields.io/badge/PHP-8.2+-purple)
![License](https://img.shields.io/badge/License-GPLv3-blue)

## 📝 معرفی

**پورفای** یک سیستم جامع فروش فایل و پشتیبانی آنلاین است که با **لاراول** و **فیلامنت** توسعه یافته است. این سیستم با ارائه امکانات کامل مدیریت محتوا، فروش محصولات دیجیتال، پشتیبانی آنلاین و مدیریت کاربران، یک پلتفرم قدرتمند برای کسب‌وکارهای آنلاین فراهم می‌کند.

## 📸 تصاویر

![صفحه اصلی](http://pourfi.ir/assets/images/screenshot/1.jpg)

![داشبورد مدیریت](http://pourfi.ir/assets/images/screenshot/2.jpg)

![مدیریت محصولات](http://pourfi.ir/assets/images/screenshot/3.jpg)

![مدیریت وبلاگ](http://pourfi.ir/assets/images/screenshot/4.jpg)

![سیستم تیکتینگ](http://pourfi.ir/assets/images/screenshot/5.jpg)

![مدیریت کاربران](http://pourfi.ir/assets/images/screenshot/6.jpg)

![پنل کاربری](http://pourfi.ir/assets/images/screenshot/7.jpg)

![مدیریت سفارشات](http://pourfi.ir/assets/images/screenshot/8.jpg)

![دسته‌بندی محصولات](http://pourfi.ir/assets/images/screenshot/9.jpg)

## ✨ ویژگی‌های اصلی

### 🔧 نصب و راه‌اندازی
- **نصب‌کننده خودکار** با رابط کاربری زیبا (بوت‌استرپ)
- تنظیم خودکار فایل `.env`
- ایمپورت خودکار دیتابیس
- ایجاد APP_KEY به صورت تصادفی

### 💳 درگاه پرداخت
- **اتصال به درگاه زرین‌پال** (Zarinpal)
- مدیریت تراکنش‌ها و وضعیت پرداخت
- صدور فاکتور خودکار

### 📦 مدیریت محصولات
- محصولات با دسته‌بندی‌های مختلف
- فایل‌های قابل دانلود برای هر محصول
- نمایش قیمت و تخفیف
- وضعیت انتشار (فعال/غیرفعال)

### 📝 مدیریت محتوا
- **وبلاگ** با دسته‌بندی‌های مختلف
- **مدیریت صفحات** (درباره ما، تماس با ما، ...)
- **سیستم دیدگاه‌ها** (نظرات و امتیازات)
- بهینه‌سازی سئو (SEO)

### 👥 مدیریت کاربران
- **سیستم احراز هویت** کامل (ورود/ثبت‌نام)
- **پنل کاربری** اختصاصی
- **پروفایل کاربری** با قابلیت ویرایش
- **مدیریت محصولات خریداری شده**
- **مدیریت فاکتورها** و تاریخچه خرید

### 🎫 سیستم پشتیبانی
- **تیکت‌های پشتیبانی** با اولویت‌بندی
- بخش‌های مختلف (پشتیبانی، فروش، مدیریت)
- پاسخ‌دهی دوطرفه (کاربر/ادمین)
- وضعیت‌های پیگیری (باز، پاسخ داده، بسته)

### 👨‍💼 مدیریت پنل ادمین
- **داشبورد مدیریتی** کامل با فیلامنت
- **مدیریت نقش‌ها و دسترسی‌ها** (RBAC)
- مدیریت کاربران و مدیران سیستم
- آمار و گزارش‌های پیشرفته
- سفارشی‌سازی کامل پنل

## 🛠 تکنولوژی‌ها

- **Backend:** Laravel 11.x
- **Admin Panel:** Filament 3.x (TALL Stack)
- **Frontend:** Bootstrap 5, Livewire, Alpine.js
- **Database:** MySQL/MariaDB
- **PHP:** 8.2+

## 📋 پیش‌نیازها

- PHP 8.2 یا بالاتر
- Composer
- MySQL/MariaDB
- Node.js & NPM (برای توسعه)

## 🚀 نصب و راه‌اندازی

### روش اول - نصب خودکار (ساده)

1. فایل‌های پروژه را روی هاست خود آپلود کنید
2. فایل `installer.php` را در مرورگر باز کنید
3. اطلاعات دیتابیس و سایت را وارد کنید
4. روی **شروع نصب** کلیک کنید
5. پس از اتمام، پوشه `install` و `installer.php` را حذف کنید

### روش دوم - نصب دستی

1. کلون کردن پروژه
git clone https://github.com/your-username/pourfi.git

2. نصب وابستگی‌ها
composer install
npm install

3. کپی فایل محیط
cp .env.example .env

4. تنظیمات دیتابیس در فایل .env
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=pourfi
DB_USERNAME=root
DB_PASSWORD=

5. تولید کلید
php artisan key:generate

6. اجرای مایگریشن‌ها
php artisan migrate

7. تولید لینک ذخیره‌سازی
php artisan storage:link

8. اجرای سرور
php artisan serve

## 🔐 اطلاعات ورود پیش‌فرض

| نقش | ایمیل | رمز عبور |
|------|-------|----------|
| **مدیر اصلی** | `admin@site.com` | `00000000` |
| **مدیر فروش** | `sale@site.com` | `00000000` |

⚠️ **توجه امنیتی:** پس از ورود، حتماً رمز عبور خود را تغییر دهید.

## 📁 ساختار پروژه

pourfi/
├── app/
│   ├── Filament/          # پنل ادمین فیلامنت
│   ├── Http/              # کنترلرها و میدلورها
│   ├── Models/            # مدل‌های دیتابیس
│   └── Providers/         # سرویس‌پروایدرها
├── database/
│   ├── migrations/        # مایگریشن‌ها
│   └── seeders/           # دیتاهای اولیه
├── public/
│   └── install/           # فایل‌های نصب
├── resources/
│   └── views/             # ویوهای کاربری
├── routes/
│   ├── web.php            # روت‌های سایت
│   └── filament/          # روت‌های ادمین
└── .env                   # تنظیمات محیطی

## 📊 ویژگی‌های پنل ادمین

### داشبورد مدیریتی
- آمار کلی فروش و کاربران
- نمودارهای تحلیلی
- آخرین سفارش‌ها و تیکت‌ها

### مدیریت محتوا
- **وبلاگ:** ایجاد، ویرایش و حذف پست‌ها
- **دسته‌بندی:** مدیریت دسته‌بندی وبلاگ و محصولات
- **صفحات:** مدیریت صفحات استاتیک (درباره ما، تماس با ما)
- **دیدگاه‌ها:** تأیید و مدیریت نظرات

### مدیریت فروش
- **محصولات:** افزودن/ویرایش محصولات دیجیتال
- **دسته‌بندی:** مدیریت دسته‌بندی محصولات
- **سفارشات:** مشاهده و مدیریت سفارشات
- **فایل‌ها:** مدیریت فایل‌های قابل دانلود

### مدیریت کاربران
- **کاربران:** مدیریت تمام کاربران سیستم
- **نقش‌ها:** تعریف نقش‌های مختلف
- **دسترسی‌ها:** تنظیم سطح دسترسی هر نقش

### مدیریت پشتیبانی
- **تیکت‌ها:** مشاهده و پاسخ به تیکت‌ها
- **اولویت‌بندی:** تعیین اولویت تیکت‌ها
- **وضعیت‌ها:** مدیریت وضعیت تیکت‌ها

## 🤝 مشارکت در توسعه

1. Fork مخزن
2. ایجاد Branch جدید (`git checkout -b feature/AmazingFeature`)
3. Commit تغییرات (`git commit -m 'Add some AmazingFeature'`)
4. Push به Branch (`git push origin feature/AmazingFeature`)
5. ایجاد Pull Request

## 📄 لایسنس

پروژه تحت لایسنس **GNU General Public License v3.0** منتشر شده است.

برای مشاهده متن کامل لایسنس، فایل [LICENSE](LICENSE) را مطالعه کنید.

## 📞 ارتباط با ما

- **وبسایت:** [https://pourfi.dv](https://pourfi.dv)
- **ایمیل:** [info@pourfi.dv](mailto:info@pourfi.dv)

---

**پورفای** - راهکار هوشمند فروش فایل و پشتیبانی آنلاین 🚀


# README.md - English

# PourFi - File Sales & Support System

![PourFi](https://img.shields.io/badge/PourFi-v1.0-blue)
![Laravel](https://img.shields.io/badge/Laravel-11.x-red)
![Filament](https://img.shields.io/badge/Filament-3.x-green)
![PHP](https://img.shields.io/badge/PHP-8.2+-purple)
![License](https://img.shields.io/badge/License-GPLv3-blue)

## 📝 Introduction

**PourFi** is a comprehensive file sales and online support system built with **Laravel** and **Filament**. It provides complete content management, digital product sales, online support, and user management capabilities, making it a powerful platform for online businesses.

## 📸 Screenshots

![Homepage](http://pourfi.ir/assets/images/screenshot/1.jpg)

![Admin Dashboard](http://pourfi.ir/assets/images/screenshot/2.jpg)

![Product Management](http://pourfi.ir/assets/images/screenshot/3.jpg)

![Blog Management](http://pourfi.ir/assets/images/screenshot/4.jpg)

![Ticket System](http://pourfi.ir/assets/images/screenshot/5.jpg)

![User Management](http://pourfi.ir/assets/images/screenshot/6.jpg)

![User Panel](http://pourfi.ir/assets/images/screenshot/7.jpg)

![Order Management](http://pourfi.ir/assets/images/screenshot/8.jpg)

![Product Categories](http://pourfi.ir/assets/images/screenshot/9.jpg)

## ✨ Key Features

### 🔧 Installation & Setup
- **Automatic Installer** with beautiful UI (Bootstrap)
- Auto-configure `.env` file
- Auto-import database
- Random APP_KEY generation

### 💳 Payment Gateway
- **Zarinpal** payment integration
- Transaction and payment status management
- Automatic invoice generation

### 📦 Product Management
- Products with multiple categories
- Downloadable files for each product
- Price and discount management
- Publication status (active/inactive)

### 📝 Content Management
- **Blog** with various categories
- **Page management** (About Us, Contact Us, ...)
- **Comment system** (reviews and ratings)
- SEO optimization

### 👥 User Management
- **Complete authentication system** (login/register)
- **User dashboard** (personal panel)
- **User profiles** with editing capabilities
- **Purchased products management**
- **Invoice management** and purchase history

### 🎫 Support System
- **Support tickets** with priority levels
- Multiple departments (Support, Sales, Management)
- Two-way communication (user/admin)
- Status tracking (open, replied, closed)

### 👨‍💼 Admin Panel Management
- **Complete admin dashboard** with Filament
- **Role-Based Access Control** (RBAC)
- User and system admin management
- Advanced statistics and reports
- Fully customizable admin panel

## 🛠 Technologies

- **Backend:** Laravel 11.x
- **Admin Panel:** Filament 3.x (TALL Stack)
- **Frontend:** Bootstrap 5, Livewire, Alpine.js
- **Database:** MySQL/MariaDB
- **PHP:** 8.2+

## 📋 Requirements

- PHP 8.2 or higher
- Composer
- MySQL/MariaDB
- Node.js & NPM (for development)

## 🚀 Installation

### Method 1 - Automatic Installation (Easy)

1. Upload project files to your hosting
2. Open `installer.php` in your browser
3. Enter database and site information
4. Click **Start Installation**
5. After completion, delete the `install` folder and `installer.php`

### Method 2 - Manual Installation

1. Clone the project
git clone https://github.com/your-username/pourfi.git

2. Install dependencies
composer install
npm install

3. Copy environment file
cp .env.example .env

4. Configure database in .env file
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=pourfi
DB_USERNAME=root
DB_PASSWORD=

5. Generate application key
php artisan key:generate

6. Run migrations
php artisan migrate

7. Create storage link
php artisan storage:link

8. Start the server
php artisan serve

## 🔐 Default Login Credentials

| Role | Email | Password |
|------|-------|----------|
| **Super Admin** | `admin@site.com` | `00000000` |
| **Sales Manager** | `sale@site.com` | `00000000` |

⚠️ **Security Notice:** Change your password immediately after first login.

## 📁 Project Structure

pourfi/
├── app/
│   ├── Filament/          # Filament admin panel
│   ├── Http/              # Controllers & Middlewares
│   ├── Models/            # Database models
│   └── Providers/         # Service providers
├── database/
│   ├── migrations/        # Database migrations
│   └── seeders/           # Initial data
├── public/
│   └── install/           # Installation files
├── resources/
│   └── views/             # Frontend views
├── routes/
│   ├── web.php            # Frontend routes
│   └── filament/          # Admin routes
└── .env                   # Environment settings

## 📊 Admin Panel Features

### Management Dashboard
- Overall sales and user statistics
- Analytics charts
- Latest orders and tickets

### Content Management
- **Blog:** Create, edit, and delete posts
- **Categories:** Manage blog and product categories
- **Pages:** Manage static pages (About, Contact)
- **Comments:** Moderate and manage user comments

### Sales Management
- **Products:** Add/edit digital products
- **Categories:** Product category management
- **Orders:** View and manage customer orders
- **Files:** Manage downloadable files

### User Management
- **Users:** Manage all system users
- **Roles:** Define different user roles
- **Permissions:** Assign permissions to roles

### Support Management
- **Tickets:** View and respond to tickets
- **Priority:** Set ticket priorities
- **Status:** Manage ticket statuses

## 🤝 Contributing

1. Fork the repository
2. Create a new branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the **GNU General Public License v3.0**.

For the full license text, please see the [LICENSE](LICENSE) file.

## 📞 Contact

- **Website:** [https://pourfi.dv](https://pourfi.dv)
- **Email:** [info@pourfi.dv](mailto:info@pourfi.dv)

---

**PourFi** - Smart File Sales & Online Support Solution 🚀
