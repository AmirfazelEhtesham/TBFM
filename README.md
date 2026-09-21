# TBFM — Tkinter Based Form Maker

> **TBFM (Tkinter Based Form Maker)** is a lightweight Python/Tkinter GUI tool for creating graphical forms and generating Python code from them.
>
> **Important:** TBFM's application UI is currently **English**. This README is bilingual and does not represent the UI language.

---

# 🇬🇧 English

## What is TBFM?

**TBFM** stands for **Tkinter Based Form Maker**.

TBFM is a Python/Tkinter application designed to make creating simple graphical interfaces easier.

Instead of starting with an empty Python file and manually writing every Tkinter widget, you can use TBFM to create a window, add supported elements, configure them, and save the resulting Python code.

The generated `.py` file can then be opened, edited, and run like a normal Python program.

---

## 🖥️ TBFM UI Language

The **TBFM application interface is English**.

This includes:

- Buttons
- Menus
- Dialogs
- Labels
- Options
- Editor controls
- Other application UI elements

The Persian sections in this README are only documentation.

---

# Main Features

## 🆕 Make New Window

**Make New Window** starts a new GUI project.

You can create a new window and add supported elements to it.

The general workflow is:

```text
Make New Window
       ↓
Configure Window
       ↓
Add Elements
       ↓
Configure Elements
       ↓
Save Python File
```

---

## 📂 Open New Window

**Open New Window** allows you to open an existing Python file.

TBFM reads the Python source and prepares it for working inside TBFM.

This is useful when you already have a Tkinter project and want to continue modifying its GUI.

Because TBFM works with Python source code, complicated or unusual projects may require manual correction.

---

# 🧩 Supported Elements

## Label

A **Label** displays text in the GUI.

Examples:

```text
Name:
Username:
Welcome!
Enter your information:
```

Labels are useful for titles, descriptions, instructions, and other static text.

---

## Entry / TextBox

An **Entry / TextBox** allows the user to enter text.

Examples:

```text
Username
Password
Age
Name
```

It can be used to create basic form fields.

---

## Button

A **Button** creates a clickable button.

Buttons can also contain custom Python code.

For example, you could make a button perform an action when the user clicks it.

This allows TBFM-created interfaces to become interactive instead of being purely visual.

> **Note:** Button commands are real Python code, so only use code that you understand and trust.

---

## 🖼️ Window Icon

TBFM can configure an icon for the generated window.

This allows your generated application to have its own custom window icon.

---

# 🐍 Python Code Generation

One of the main purposes of TBFM is generating Python/Tkinter code.

The workflow looks like this:

```text
TBFM
 │
 ├── Create Window
 │
 ├── Add Widgets
 │
 ├── Configure Widgets
 │
 ├── Add Python Commands
 │
 └── Save
       ↓
    Python .py
```

The output is a normal Python source file.

You can continue editing the generated code manually after saving it.

---

# 📄 Opening Existing Python Files

TBFM can work with existing `.py` files.

The process is approximately:

```text
Select Python File
       ↓
Read Source Code
       ↓
Prepare Code for TBFM
       ↓
Edit / Add Supported Elements
       ↓
Save
```

This feature is intended mainly for relatively simple Tkinter projects.

Python programs can be structured in many different ways, so complex source code may not always be compatible with TBFM's source-code processing.

---

# 💾 Saving Projects

After creating or modifying a form, TBFM can save the generated Python source.

The result is a `.py` file that can be run with Python.

For example:

```bash
python TBFM.py
```

or, depending on the system:

```bash
python3 TBFM.py
```

---

# ⚙️ Requirements

TBFM is built using:

- **Python**
- **Tkinter**
- Standard Python GUI functionality

The exact Tkinter installation requirements can depend on the operating system and Python distribution.

---

# 📦 Versions

## v1.0 — First Release

v1.0 was the first released version of TBFM.

It introduced the basic form-making workflow and initial GUI elements.

---

## v1.2 — Latest Release

**v1.2 is currently the latest published release of TBFM.**

It expanded the functionality of the original version with features including:

- Opening existing Python files
- Additional GUI elements
- TextBox support
- Window icon support
- Improved project workflow
- Continued GUI generation functionality

**Status: Released**

---

## 🚧 v1.3 — Under Development

**v1.3 has NOT been published yet.**

It is currently **under development**.

The v1.3 development version may contain major changes, unfinished functionality, and bugs.

Therefore:

> **v1.2 = latest official release**  
> **v1.3 = development version, not published**

---

# ⚠️ Current Limitations

Some TBFM functionality works by processing or modifying Python source code.

Because Python allows many different programming styles and structures, TBFM may not correctly handle every possible Python/Tkinter project.

TBFM is currently best suited for relatively simple Tkinter applications.

---

# 🎯 Who is TBFM For?

TBFM can be useful for:

- Python beginners
- Tkinter learners
- People creating simple GUI applications
- Developers who want a quick GUI starting point
- People experimenting with Tkinter widgets
- Simple form-based applications

---

# 🧪 Example

Imagine creating a simple information form:

```text
┌─────────────────────────┐
│      My Form            │
│                         │
│ Name:                   │
│ [___________________]   │
│                         │
│ Age:                    │
│ [___________________]   │
│                         │
│       [ Submit ]        │
└─────────────────────────┘
```

This could contain:

```text
Window
 ├── Label → "Name:"
 ├── Entry → Name input
 ├── Label → "Age:"
 ├── Entry → Age input
 └── Button → Submit
```

TBFM helps create the GUI structure and generate the Python/Tkinter source for it.

---

# 🛠️ Development Philosophy

TBFM focuses on:

- Simplicity
- Lightweight GUI creation
- Python
- Tkinter
- Generated source code
- Easy experimentation
- Learning through building

It is designed to be a simple tool rather than a large professional GUI design suite.

---

# 📁 Project

**Repository:** `AmirFazelEhtesham/TBFM`

The project source code and official releases are hosted on GitHub.

---

# 👨‍💻 Creator

**Amirfazel Ehtesham**

© 2026 Amirfazel Ehtesham

---

# 🇮🇷 فارسی

## TBFM چیست؟

**TBFM** مخفف **Tkinter Based Form Maker** است.

TBFM یک برنامه سبک ساخته‌شده با **Python و Tkinter** است که برای ساخت رابط‌های گرافیکی و فرم‌های ساده طراحی شده است.

به‌جای اینکه تمام کدهای رابط کاربری را از صفر بنویسید، می‌توانید در TBFM پنجره ایجاد کنید، المان‌های مختلف را اضافه کنید و در نهایت کد Python مربوط به رابط را ذخیره کنید.

---

# 🖥️ زبان رابط کاربری

**رابط خود برنامه TBFM انگلیسی است.**

یعنی:

- دکمه‌ها
- منوها
- پنجره‌ها
- گزینه‌ها
- Labelهای برنامه
- کنترل‌های ویرایش

همگی در رابط فعلی TBFM به زبان انگلیسی هستند.

بخش فارسی این README فقط برای مستندسازی پروژه است.

---

# 🆕 Make New Window

گزینه **Make New Window** برای ساخت یک پروژه جدید استفاده می‌شود.

با استفاده از آن می‌توانید یک پنجره جدید ایجاد کرده و المان‌های مختلف را به آن اضافه کنید.

روند کلی:

```text
Make New Window
       ↓
تنظیم پنجره
       ↓
افزودن المان‌ها
       ↓
تنظیم المان‌ها
       ↓
ذخیره فایل Python
```

---

# 📂 Open New Window

گزینه **Open New Window** برای باز کردن یک فایل Python موجود استفاده می‌شود.

TBFM کد Python فایل را می‌خواند و آن را برای کار در محیط TBFM آماده می‌کند.

این قابلیت برای ادامه دادن پروژه‌های Tkinter موجود کاربرد دارد.

---

# 🧩 المان‌ها

## Label

**Label** برای نمایش متن استفاده می‌شود.

مثلاً:

```text
Name:
Username:
Welcome!
```

---

## Entry / TextBox

**Entry / TextBox** برای دریافت متن از کاربر استفاده می‌شود.

مثلاً:

```text
Name
Username
Age
```

---

## Button

**Button** یک دکمه قابل کلیک ایجاد می‌کند.

یکی از قابلیت‌های مهم TBFM امکان قرار دادن **کد Python سفارشی** برای Button است.

در نتیجه Button می‌تواند هنگام کلیک یک عملیات انجام دهد.

---

## 🖼️ Window Icon

TBFM امکان تعیین **آیکون پنجره** را نیز دارد.

این قابلیت باعث می‌شود برنامه تولیدشده بتواند از یک آیکون سفارشی استفاده کند.

---

# 🐍 تولید کد Python

هدف اصلی TBFM این است که ساخت رابط Tkinter را ساده‌تر کند و در نهایت یک فایل Python تولید کند.

روند کلی:

```text
TBFM
 │
 ├── ساخت پنجره
 │
 ├── افزودن المان‌ها
 │
 ├── تنظیم المان‌ها
 │
 ├── افزودن کد Python
 │
 └── ذخیره
       ↓
    فایل Python
```

فایل تولیدشده یک فایل معمولی `.py` است و می‌توانید بعداً آن را به صورت دستی نیز ویرایش کنید.

---

# 📄 باز کردن فایل‌های Python موجود

TBFM می‌تواند فایل‌های `.py` موجود را باز کند.

روند کلی:

```text
انتخاب فایل
     ↓
خواندن کد
     ↓
آماده‌سازی برای TBFM
     ↓
ویرایش
     ↓
ذخیره
```

این قابلیت بیشتر برای پروژه‌های نسبتاً ساده Tkinter مناسب است.

به دلیل تنوع بسیار زیاد ساختارهای Python، ممکن است بعضی پروژه‌های پیچیده به اصلاح دستی نیاز داشته باشند.

---

# 💾 ذخیره

بعد از ساخت یا ویرایش فرم، TBFM می‌تواند کد Python تولیدشده را ذخیره کند.

خروجی یک فایل `.py` است که می‌توانید آن را با Python اجرا کنید.

---

# ⚙️ پیش‌نیازها

TBFM با استفاده از موارد زیر ساخته شده است:

- **Python**
- **Tkinter**
- قابلیت‌های استاندارد GUI در Python

---

# 📦 نسخه‌ها

## v1.0 — اولین انتشار

v1.0 اولین نسخه منتشرشده TBFM بود.

این نسخه قابلیت‌های پایه ساخت فرم و رابط گرافیکی را معرفی کرد.

---

## v1.2 — آخرین نسخه منتشرشده

**v1.2 در حال حاضر آخرین نسخه رسمی و منتشرشده TBFM است.**

در این نسخه قابلیت‌هایی مانند موارد زیر اضافه یا گسترش داده شدند:

- باز کردن فایل‌های Python موجود
- پشتیبانی از المان‌های بیشتر
- TextBox
- Window Icon
- روند کاری بهتر
- قابلیت‌های بیشتر برای تولید GUI

**وضعیت: منتشرشده**

---

## 🚧 v1.3 — در حال توسعه

**v1.3 هنوز منتشر نشده است.**

این نسخه در حال حاضر **Under Development** است.

بنابراین ممکن است نسخه توسعه‌ای v1.3 دارای:

- باگ
- قابلیت‌های ناقص
- تغییرات آزمایشی
- تغییرات بزرگ در عملکرد

باشد.

### وضعیت فعلی:

> **v1.2 = آخرین نسخه رسمی منتشرشده**  
> **v1.3 = منتشر نشده و در حال توسعه**

---

# ⚠️ محدودیت‌های فعلی

بعضی از قابلیت‌های TBFM با پردازش و تغییر کد Python کار می‌کنند.

از آنجایی که Python امکان نوشتن کد به شکل‌های بسیار مختلف را دارد، ممکن است TBFM نتواند تمام پروژه‌های پیچیده Python/Tkinter را به شکل کامل پردازش کند.

در حال حاضر TBFM بیشتر برای پروژه‌های ساده Tkinter مناسب است.

---

# 🎯 TBFM برای چه کسانی مناسب است؟

TBFM می‌تواند برای این افراد مناسب باشد:

- افراد تازه‌کار Python
- کسانی که Tkinter یاد می‌گیرند
- سازندگان GUIهای ساده
- افرادی که یک نقطه شروع سریع برای رابط کاربری می‌خواهند
- کسانی که می‌خواهند Widgetهای Tkinter را آزمایش کنند
- پروژه‌های ساده فرم‌محور

---

# 🧪 مثال

فرض کنید می‌خواهید یک فرم ساده اطلاعات بسازید:

```text
┌─────────────────────────┐
│      My Form            │
│                         │
│ Name:                   │
│ [___________________]   │
│                         │
│ Age:                    │
│ [___________________]   │
│                         │
│       [ Submit ]        │
└─────────────────────────┘
```

این فرم می‌تواند شامل موارد زیر باشد:

```text
Window
 ├── Label → "Name:"
 ├── Entry → ورودی نام
 ├── Label → "Age:"
 ├── Entry → ورودی سن
 └── Button → Submit
```

TBFM به ساخت ساختار GUI و تولید کد Python/Tkinter آن کمک می‌کند.

---

# 🛠️ فلسفه TBFM

تمرکز TBFM روی موارد زیر است:

- سادگی
- سبک بودن
- Python
- Tkinter
- تولید کد قابل ویرایش
- آزمایش آسان
- یادگیری از طریق ساختن

هدف TBFM تبدیل شدن به یک نرم‌افزار بسیار سنگین طراحی GUI نیست؛ بلکه یک ابزار ساده برای ساخت رابط‌های Tkinter است.

---

# 📁 پروژه

**Repository:** `AmirFazelEhtesham/TBFM`

کد منبع و نسخه‌های رسمی پروژه در GitHub قرار دارند.

---

# 👨‍💻 سازنده

**Amirfazel Ehtesham**

© 2026 Amirfazel Ehtesham

---

# ⭐ خلاصه وضعیت پروژه

| Version | Status |
|---|---|
| **v1.0** | Released |
| **v1.2** | ✅ Latest Release |
| **v1.3** | 🚧 Under Development — Not Published |

---

**TBFM — Build your Tkinter GUI, then make it your own.**

**TBFM — رابط Tkinter خودت را بساز و بعد آن را به سبک خودت توسعه بده.**

© 2026 Amirfazel Ehtesham
