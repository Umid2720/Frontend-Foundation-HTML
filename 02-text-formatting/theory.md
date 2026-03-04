# 2-dars — Text formatting

## Paragraph (p)

HTML’da matn yozish uchun `<p>` tegi ishlatiladi.

Misol:

<p>Bu birinchi paragraf.</p>
<p>Bu ikkinchi paragraf.</p>

Brauzer har bir `<p>` ni alohida matn bloki sifatida ko‘rsatadi.

---

## Strong

`<strong>` tegi matn muhim ekanligini bildiradi.  
Brauzer odatda uni qalin (bold) qilib ko‘rsatadi.

Misol:

<p>Bu <strong>muhim</strong> so‘z.</p>

---

## Em

`<em>` tegi matnga urg‘u beradi.  
Brauzer odatda uni o‘ng tomonga yotgan (italic) qilib ko‘rsatadi.

Misol:

<p>Bu <em>urg‘uli</em> so‘z.</p>

---

## Nesting (ichma-ich yozish)

HTML’da teglarga boshqa teglarni ichiga yozish mumkin.

Qoida:  
Birinchi ochilgan teg oxirida yopiladi.

Misol:

<p><strong><em>Hello, World!</em></strong></p>

Natijada matn ham qalin, ham italic ko‘rinadi.

---

## br

`<br>` tegi yangi qatorga o‘tkazish uchun ishlatiladi.

Misol:

<p>
Hello<br>
World
</p>