قالب صفحه کاربری پنل ربکا
 📥 نصب و راه‌اندازی

<div>

### 1️⃣ دانلود فایل قالب

</div>

```bash
sudo wget -N -P /var/lib/rebecca/templates/subscription/ https://raw.githubusercontent.com/rohnox/Pro-Subscription-Template/refs/heads/main/index.html
```

<div>

### 2️⃣ ثبت تنظیمات در محیط ربکا

</div>

```bash
echo 'CUSTOM_TEMPLATES_DIRECTORY="/var/lib/rebecca/templates/"' | sudo tee -a /opt/rebecca/.env
echo 'SUBSCRIPTION_PAGE_TEMPLATE="subscription/index.html"' | sudo tee -a /opt/rebecca/.env
```

<div>
