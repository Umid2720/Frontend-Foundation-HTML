# 1-dars — HTML bilan tanishuv

## HTML nima?

HTML (HyperText Markup Language) — bu web sahifalarni yaratish uchun ishlatiladigan belgilash tili (markup language).

HTML dasturlash tili emas.
U sahifadagi matn, sarlavha, rasm va boshqa elementlarning tuzilishini belgilash uchun ishlatiladi.

---

## Asosiy tushunchalar

HTML’da 3 ta asosiy tushuncha mavjud:

- tag
- element
- attribute

---

## 1. Tag

Tag — bu HTML’dagi asosiy belgi.

Misol:

<p>Hello</p>

Ochuvchi tag:
<p>

Yopuvchi tag:
</p>

Yopuvchi tagda nom oldidan `/` belgisi qo‘yiladi.

---

## ⚠ Muhim qoida

Har bir ochilgan tag yopilishi kerak.

❌ Noto‘g‘ri:
<p>Hello

✔ To‘g‘ri:
<p>Hello</p>

---

## 2. Element

Element — bu:

ochuvchi tag + content + yopuvchi tag

Misol:

<p>Hello World</p>

Bu yerda:
- <p> ochuvchi tag
- Hello World content
- </p> yopuvchi tag

---

## 3. Attribute

Attribute — bu tag ichida qo‘shimcha ma’lumot berish uchun ishlatiladi.

Misol:

<a href="https://google.com">Google</a>

Bu yerda:
- href — attribute nomi
- "https://google.com" — attribute qiymati

---

## HTML sahifaning asosiy tuzilishi

Har bir HTML fayl quyidagi asosiy strukturaga ega bo‘lishi kerak:

```html
<!DOCTYPE html>
<html lang="uz">
<head>
    <meta charset="UTF-8">
    <title>Lesson 1</title>
</head>
<body>

<h1>Hello World</h1>

</body>
</html>