`input` va `button` qo'ying. Tugmaga bosganingizda `input`dagi yozuv `alert` oynachasiga chiqishi kerak.  
`onclick="..."` dan foydanaling.

---

Ikkita `input` qo'ying. Birinchi `input`ga nimadir yozganingizda, ikkinchisida u paydo bo'lishi kerak.  
`oninput="..."` dan foydalaning.

---

Ikkita `input type="number"` qo'ying. Birinchi `input`ga sonni kiritganingizda, ikkinchisida o'sha sonni `10`ga ko'paytirib ko'rsatish kerak.  
`oninput="..."` dan foydalaning.

---

`select` qo'ying. `select`dan molni (misol uchun qahvaning turlari) tanlasangiz, tanlagan molning narxi `alert` oynachasida chiqishi kerak.

---

`input` va `button` qo'ying. Tugmaga bosganingizda `input`dagi yozuvni `document.write` qilib chiqaring.

---

`input`, `button`, va `h1` qo'ying. Tugmaga bosganingizda `input`dagi yozuvni `h1`ni ichiga `innerHTML`dan foydalanib solib qo'ying.

---

## addEventListener
Quyidagi topshiriqlarda `addEventListener` dan foydanalish kerak.

---

`input` va `button` qo'ying. Tugmaga bosganingizda `input`dagi yozuv `alert` oynachasiga chiqishi kerak.

---

Ikkita `input` qo'ying. Birinchi `input`ga nimadir yozganingizda, ikkinchisida u paydo bo'lishi kerak.  
`oninput="..."` dan foydalaning.

### Yechim

```html
<input type="text" id="salom">
<input type="text" id="tinchlik">

<script>
function soglik(hodisa) {
  var input = hodisa.target  // aslida salomInputi o'zgaruvchi bilan bitta narsa
  var yozilganMatn = input.value
  var tinchlikInputi = document.querySelector('#tinchlik')
  tinchlikInputi.value = yozilganMatn
}

var salomInputi = document.querySelector('#salom')
salomInputi.addEventListener('input', soglik)
</script>
```

Ikkita `input type="number"` qo'ying. Birinchi `input`ga sonni kiritganingizda, ikkinchisida o'sha sonni `10`ga ko'paytirib ko'rsatish kerak.  

---

`select` qo'ying. `select`dan molni (misol uchun qahvaning turlari) tanlasangiz, tanlagan molning narxi `alert` oynachasida chiqishi kerak.

---

`input` va `button` qo'ying. Tugmaga bosganingizda `input`dagi yozuvni `document.write` qilib chiqaring.

---

`input`, `button`, va `h1` qo'ying. Tugmaga bosganingizda `input`dagi yozuvni `h1`ni ichiga `innerHTML`dan foydalanib solib qo'ying.

---

`audio` va `input type="range"` qo'ying. `input`ni sijditganingizda `audio` tovushining balandligi o'zgarishi kerak.

---

10 rasm qo'ying. Har bitta rasmga sichqonchaning o'qini olib borsangiz, saytingizni o'rtasida shu rasmning tavsifi paydo bo'lishi kerak.
Misol uchun qahvaning rasmniga o'qni olib borsangiz - "Kuchli qahva, qadoqi 200 000 so'm" yozuv paydo bo'lishi kerak.

