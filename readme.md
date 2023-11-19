# نام پروژه

توضیحات مختصر در مورد پروژه شما.

## راه‌اندازی پروژه

### 1. دانلود پروژه
```bash
git clone https://github.com/SaEeD802/Beharfim.git
cd Beharfim
```

### 2. ایجاد محیط مجازی
```bash
python -m venv venv
```

### 3. فعال‌سازی محیط مجازی
```bash
venv\Scripts\activate
```

### 4. نصب کتابخانه‌ها
```bash
pip install -r requirements.txt
```

### 5. ایجاد جداول در پایگاه داده
```bash
py manage.py makemigrations
py manage.py migrate
```

### 6. اجرای سرور
```bash
py manage.py runserver
```

## استفاده از پروژه

حالا پروژه شما آماده به کار است! می‌توانید به [localhost:8000](http://localhost:8000) بروید و از آن به عنوان یک چت گروهی استفاده کنید.

**نکته:**
- ممکن است نیاز به تغییر تنظیمات پایگاه داده و دیگر تنظیمات داشته باشید. این تنظیمات در فایل `settings.py` قابل دسترسی هستند.
- برای خروج از محیط مجازی، دستور `deactivate` را اجرا کنید.
