# Htmllesson1 — Feedback jurnali va umumiy prompt materiali

Maqsad: darsdagi kamchiliklarni yozib borish, yechim berish, va yakunda barchasini
**umumiy prompt**ga aylantirish — keyingi darsliklar shu xatolarni qaytarmasligi uchun.

Holat belgilari: ✅ tuzatildi · 🔄 jarayonda · ⏳ kutilmoqda

---

## 1. Murojaat odobi — sen-forma o'rniga siz-forma ✅

**Muammo:** O'quvchiga qaratilgan ayrim matnlar "sen"lab yozilgan edi:
- Debugging xulosasi: "Topding va tuzatding"
- 5 ta nishon (achievement) tavsifi: "yig'ding", "yozding", "tuzatding", "takrorlading", "yakunlading"
- "Yarat" tugmasi va mentor matnida "«Yarat» bosing"

**Yechim:** Hammasi siz-formaga o'tkazildi ("Topdingiz va tuzatdingiz", "yig'dingiz"...),
tugma neytral harakat otiga o'zgartirildi: "Yarat" → "Yaratish".

**Umumiy qoida (promptga):**
> O'quvchiga qaratilgan BARCHA matn — tugmalar, nishon tavsiflari, mentor gaplari,
> xulosalar, xato/muvaffaqiyat xabarlari — faqat siz-formada bo'lsin ("bosing",
> "topdingiz"). Tugma nomlari uchun neytral harakat oti afzal: "Yaratish",
> "Yuborish", "Boshlash". Sen-forma faqat o'quvchining O'ZI mashinaga buyruq
> berganida joiz (masalan, dinozavrga "Yur"/"Sakra" buyruqlari, AI'ga "rasm qo'sh"
> prompti) — chunki bu "kod = kompyuterga buyruq" g'oyasini o'rgatadi.

---

## 2. Nishon (achievement) nomlari tushunarsiz ✅

**Muammo:** "Skelet ustasi", "Flashcard usta", "A'lochi", "HTML bitiruvchisi" —
bolaga tushunarsiz yoki rasmiy/kattalar tili.

**Yechim:** "Sahifa quruvchi", "Takrorlash chempioni", "100% to'g'ri", "HTML qahramoni".

**Umumiy qoida:** nishon `name` — bolaga bir o'qishda tushunarli; `desc` — siz-formada
aynan nima qilgani.

---

## 3. Matn ↔ UI nomuvofiqlik (1-sahifa) ✅

**Muammo:** Mentor «"Sayt" tugmasini bosib, ichida nima borligini ko'ring» deydi,
lekin ichini (kodni) "</> Kod" tugmasi ochadi — o'quvchi noto'g'ri tugmani bosadi.

**Yechim:** Matn (va audio) «"</> Kod" tugmasini bosib...» ga o'zgartirildi.

**Umumiy qoida:** matnda tilga olingan tugma nomi ekrandagi tugma yozuvi bilan
AYNAN bir xil bo'lishi shart.

---

## 4. Tugma nomlari buyruq formasida (3-sahifa) ✅

**Muammo:** "↺ Tozala", "▶ Ishga tushir".

**Yechim:** "↺ Tozalash", "▶ Ishga tushirish" — boshqa tugmalar bilan bir uslub.

---

## 5. Qizil fon xato bo'lmagan bloklarda (10/11/12/14-sahifalar) ✅

**Muammo:** "Sizning loyihangiz...", Telegram-teg xulosasi, ul/ol maslahat bloklari
qizil (accentSoft) fonda — o'quvchi "xato qildim" deb o'ylaydi.

**Yechim:** to'rttala blok yashilga o'tkazildi: `frame-success` klassi yoki
`successSoft` fon + `success` chap chiziq (`.cmp-merge`, `.cmp2-concl`).

**Umumiy qoida:** qizil/accent fon FAQAT xato-ogohlantirishda; xulosa, maslahat,
"Sizning loyihangiz" — yashil.

---

## 6. Bosiladigan joylar noaniq (6-sahifa, skelet) ✅

**Muammo:** o'quvchi chizmada aynan nimani bosishni bilmaydi (4 qism: DOCTYPE,
html, head, body).

**Yechim:** (1) yo'riqnoma + jonli hisoblagich «👆 4 ta qismni birma-bir bosing — 2/4»;
(2) bosilmagan qismlar pulsatsiya (`tap-hint` animatsiya); (3) bosilganlarga ✓ belgi;
(4) mentor matni aniqlashtirildi.

**Umumiy qoida:** "bosib o'rgan" ekranlarda affordance majburiy: yo'riqnoma +
hisoblagich + pulsatsiya + ✓.

---

## 7. CoddyHoot → CodeStrike rebrend ✅

**Yechim:** arena nomi "CodeStrike" (wordmark `Code|Strike`), CTA "⚡ CodeStrike jangi",
boyqush (QzOwl) o'rniga chaqmoq mascot (QzBolt: gradient kvadrat + oq chaqmoq + uchqunlar).

**Umumiy qoida:** barcha yangi darslarda arena brendi CodeStrike; "CoddyHoot"/QzOwl
ishlatilmasin.

---

## 8. Flashcard jonli darsda ko'rinmasin ✅

**Muammo:** jonli dars (mentor bilan) paytida flashcard sahifasi vaqt oladi;
u mustaqil takrorlash uchun mo'ljallangan.

**Yechim:** navigatsiya darajasida (`advance`/`prev`) `sflash` ekrani sakrab o'tiladi,
agar jonli sessiya faol bo'lsa (o'quvchi: mentor tirik va sessiya tugamagan;
mentor: sessiya tugamagan). "Erkin qilish"dan keyin, mentor uzilganda yoki yakka
o'qishda flashcard ko'rinadi — orqaga qaytib ham ochsa bo'ladi.

**Umumiy qoida:** o'z tezligida ishlanadigan qismlar (flashcard kabi) jonli darsda
yashirinadi, erkin rejimda ochiladi; skip komponentda emas, navigatsiyada qilinadi.

---

*Barcha qoidalar 2026-07-07 da DARS_ETALON.md ga kiritildi (1, 8.2, 10, 11.6, 11.7,
12-buglar jadvali, 14-checklist).*
