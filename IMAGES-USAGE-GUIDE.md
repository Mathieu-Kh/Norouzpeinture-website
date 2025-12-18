# راهنمای استفاده از تصاویر - سایت نوروز پینتور

## تصاویر آماده شده برای سایت 🎨

### 📁 ساختار پوشه تصاویر
```
images/
├── hero/
│   └── hero-painter.jpg          # تصویر اصلی صفحه (Hero Section)
├── services/
│   ├── paint-tools.jpg          # ابزار نقاشی
│   ├── before-after.jpg         # قبل و بعد
│   └── color-samples.jpg        # نمونه رنگ
├── testimonials/
│   └── satisfied-customers.jpg  # مشتریان راضی
└── articles/
    └── article-headers/         # تصاویر مقالات
```

## 🎯 تصاویر پیشنهادی با نام‌گذاری صحیح

### 1. تصویر Hero (صفحه اصلی)
**فایل:** `hero_painter_9.jpg` (1600x1067px - بهترین کیفیت)
**نام جدید:** `images/hero/hero-painter.jpg`
**کاربرد:** تصویر اصلی صفحه اول که در background hero section نمایش داده می‌شود

### 2. تصاویر خدمات
**الف) ابزار نقاشی:** `paint_tools_0.jpg` → `images/services/paint-tools.jpg`
**ب) قبل و بعد:** `before_after_5.jpg` (بهترین کیفیت) → `images/services/before-after.jpg`
**ج) نمونه رنگ:** `color_samples_0.jpg` → `images/services/color-samples.jpg`

### 3. تصویر مشتریان راضی
**فایل:** `satisfied_customers_7.jpg` (1280x960px - بهترین کیفیت)
**نام جدید:** `images/testimonials/satisfied-customers.jpg`

## 🚀 مراحل جایگزینی تصاویر

### مرحله 1: ایجاد پوشه‌ها
```bash
# در پوشه اصلی سایت، پوشه‌های زیر را ایجاد کنید:
mkdir -p images/hero
mkdir -p images/services
mkdir -p images/testimonials
mkdir -p images/articles/article-headers
```

### مرحله 2: کپی کردن تصاویر
تصاویر دانلود شده را با نام‌های جدید کپی کنید:

```bash
# تصویر Hero
cp hero_painter_9.jpg images/hero/hero-painter.jpg

# تصاویر خدمات
cp paint_tools_0.jpg images/services/paint-tools.jpg
cp before_after_5.jpg images/services/before-after.jpg
cp color_samples_0.jpg images/services/color-samples.jpg

# تصویر مشتریان
cp satisfied_customers_7.jpg images/testimonials/satisfied-customers.jpg
```

### مرحله 3: ویرایش فایل‌های HTML
در فایل `index.html` مسیر تصاویر را آپدیت کنید:

**Hero Section:**
```html
<!-- خط 45 حدودی - تصویر hero -->
<div class="hero" style="background-image: url('images/hero/hero-painter.jpg')">
```

**Services Section:**
```html
<!-- تصاویر خدمات - خطوط مختلف -->
<img src="images/services/paint-tools.jpg" alt="ابزار نقاشی حرفه‌ای">
<img src="images/services/before-after.jpg" alt="قبل و بعد از نقاشی">
<img src="images/services/color-samples.jpg" alt="نمونه رنگ">
```

**Testimonials:**
```html
<!-- تصویر مشتریان راضی -->
<img src="images/testimonials/satisfied-customers.jpg" alt="مشتریان راضی">
```

## 📝 فهرست کامل تصاویر دانلود شده

### ✅ تصاویر با کیفیت بالا (توصیه شده):
1. **Hero:** `hero_painter_9.jpg` (1600x1067px, 179.5KB)
2. **Before/After:** `before_after_5.jpg` (790x1070px, 770.9KB)
3. **Customers:** `satisfied_customers_7.jpg` (1280x960px, 212.1KB)
4. **Paint Tools:** `paint_tools_0.jpg` (894x950px, 62.3KB)
5. **Color Samples:** `color_samples_0.jpg` (1000x1000px, 79.3KB)

### 🔄 تصاویر جایگزین (در صورت نیاز):
- **Hero:** `hero_painter_4.jpg` (894x596px)
- **Before/After:** `before_after_2.jpg` (790x920px)
- **Customers:** `satisfied_customers_2.jpg` (1200x630px)
- **Paint Tools:** `paint_tools_8.webp` (800x800px)
- **Color Samples:** `color_samples_9.png` (1000x1000px)

## ⚡ نکات مهم

1. **حجم فایل‌ها:** تصاویر قبل از استفاده را optimize کنید (حداکثر 200KB)
2. **فرمت:** JPG برای عکس‌های واقعی، PNG برای تصاویر با شفافیت
3. **ابعاد:** تصاویر Hero حداقل 1200px عرض داشته باشند
4. **Alt Text:** متن جایگزین برای SEO مهم است

## 🎯 نتیجه نهایی
بعد از جایگزینی تصاویر، سایت شما:
- ✅ ظاهری حرفه‌ای و جذاب خواهد داشت
- ✅ سرعت لود بهتری خواهد داشت
- ✅ برای موتورهای جستجو بهینه خواهد بود
- ✅ در تمام دستگاه‌ها به درستی نمایش داده می‌شود

## 📞 پشتیبانی
اگر در هر مرحله مشکل داشتید، بگویید تا کمکتان کنم! 😊