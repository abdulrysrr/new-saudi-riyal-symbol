# مستودع رمز الريال السعودي الجديد

![رمز الريال السعودي](https://argaamplus.s3.amazonaws.com/5df02013-fa26-45d6-b6de-6a97e5c871d5.png)

هذا المستودع يوفر الرمز الجديد للريال السعودي (SAR) بصيغ متعددة، ومُحسَّن للدمج السلس في المواقع الإلكترونية. من خلال استخدام خط مخصص مع حرف يونيكود مخصص، يمكنك بسهولة تعديل اللون والحجم والتنسيق ليناسب احتياجات تصميمك.

## يونيكود  

<div dir="rtl">

الكيان `&#xea;` يمثل يونيكود السداسي العشري **U+00EA**، والذي نستخدمه في ملفات الخطوط لدينا لتمثيل الرمز الجديد.

</div>

## الصيغ المتاحة

### ملفات الخطوط
- **TTF**
- **OTF**
- **WOFF**
- **WOFF2**

### الرسومات المتجهة
- **SVG**
- **EPS**

### الصور النقطية
- **PNG**
- **JPG**

## معاينة الصفحة الرئيسية  
إليك لقطة شاشة لصفحة `index.html`:  

![لقطة شاشة لصفحة index.html](/demo/index.JPG)  

## استخدام الخط
يتضمن هذا المستودع خطًا مخصصًا يحتوي على رمز الريال السعودي مع حرف يونيكود مخصص، مما يسمح بمرونة أكبر في التنسيق، بما في ذلك الحجم واللون والوزن.

## التثبيت عبر npm
يمكنك تثبيت هذا الحزمة عبر npm:

```sh
npm install @abdulrysr/saudi-riyal-new-symbol-font
```

أو باستخدام yarn:

```sh
yarn add @abdulrysr/saudi-riyal-new-symbol-font
```

### طرق الاستخدام
#### استخدام ملف الأنماط المرفق
لإضافة الخط إلى مشروعك، قم باستيراد ملف الأنماط في ملف CSS الرئيسي:
```css
@import '/node_modules/@abdulrysr/saudi-riyal-new-symbol-font/style.css';
```
```html
<span class="icon-saudi_riyal">&#xea;</span>
```

#### إضافة النمط يدويًا
بدلًا من ذلك، يمكنك تعريف الخط في ملف CSS الخاص بك باستخدام أي صيغة للخط ترغب بها:

```css
@font-face {
    font-family: 'SaudiRiyalSymbol';
    src: url('saudiriyal.woff2') format('woff2'),
         url('saudiriyal.woff') format('woff'),
         url('saudiriyal.otf') format('opentype');
}
.symbol {
    font-family: 'SaudiRiyalSymbol', sans-serif;
    font-size: inherit;
    margin: 20px auto;
    color: inherit;
    font-weight: bold;
}
```

```html
<span class="symbol">&#xea;</span>
```

## إرشادات الاستخدام
للحفاظ على التناسق البصري، يرجى اتباع الإرشادات المقدمة من البنك المركزي السعودي  **[SAMA Guidelines](https://www.sama.gov.sa/en-US/Currency/SRS/Pages/Guidelines.aspx)**

- **الموضع**: ضع الرمز على يسار الرقم.
- **المسافات**: اترك مسافة بين الرمز والرقم.
- **النسب**: حافظ على الشكل الصحيح بدون تشويه.
- **المحاذاة**: يجب أن يكون ارتفاع الرمز متناسبًا مع النص المحيط.
- **الاتجاه**: يجب أن يتبع الرمز اتجاه النص.
- **التباين**: تأكد من وجود تباين كافٍ بين الرمز والخلفية.

للاطلاع على دليل الاستخدام الكامل: **[إرشادات SAMA](#)**

## اللغات المتاحة 🌍
<div dir="rtl">

- 🇺🇸 [English](README.md)
- ar [العربية](README.ar.md)

</div>

## LinkedIn  
<div dir="rtl">

[ملفي على LinkedIn](https://www.linkedin.com/in/abdulrehmanyaser/)

</div>

## المساهمة
إذا كنت ترغب في المساهمة أو تقديم اقتراحات للتحسين، فلا تتردد في إرسال طلب سحب أو فتح قضية.

