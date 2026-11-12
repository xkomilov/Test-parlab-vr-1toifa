# Hisobot — Parazitologiya (1-toifa, shifokor) testlari

**Rol:** test tuzuvchi, parazitologiya bo'yicha shifokor. **Manba:** `Мавзу 1-vrach.zip` (118 ta mavzu). **Natija:** `Тест/001.xlsx … 118.xlsx`. **Shablon:** `shablon.xlsx`.

## 1. Fayllar va savollar
- Fayllar: 118. Savollar: 1180 (har faylda 10 ta).
- Qat'iy QA (`build_tests.js`): xato 0. Qayta o'qish (jszip) tekshiruvi: savollar soni 10, ketma-ket uch marta bir xil harf yo'q, kirill aralashmasi yo'q, har izohda « » iqtibos bor.

## 2. A/B/C/D/E taqsimoti
A=236, B=236, C=236, D=236, E=236.

## 3. To'g'ri javob >10% uzun
16 ta savol (1,4%): 012, 023, 025, 026, 027, 029, 030, 064, 066, 067, 068 mavzularida. Hech biri 30% dan oshmaydi.

## 4. Mavzu matnlari o'rtasidagi farqlar va ziddiyatlar
1. 001: «ish stolida saqlash» va «tekis stol yoki yopiq shkaf» turlicha berilgan.
2. 002, 007: merozoitlar soni «tasdiqlanmagan»; 16–32 merozoit eritrotsitar shizontga tegishli.
3. 003, 040, 076, 084: «oxirgi egasi/boshlig'i» sarlavhadagi noaniq ibora; ho'kiz tasmasi nomi turlicha yozilgan.
4. 005, 035: dispanser kuzatuv muddati «tasdiqlanmagan». 28 kunlik kuzatuv 035 da bir joyda tasdiqlanmagan, boshqa joyda aniq fakt.
5. 006, 030: lichinka ko'payadigan suv «toza va turg'un» va «toza yoki sekin oqadigan» deb berilgan.
6. 008, 092: spirt konsentratsiyasi «96% ideal» va «70–96%».
7. 009: cho'chqa tasmasi umri tasdiqlanmagan; xulosa asosiy qism bilan mos emas.
8. 013, 088: harorat 20–28 °C «aniq raqam tasdiqlanmagan» deyilgan; 016 va 021/077: it roli bir joyda tasdiqlanmagan, boshqa joyda belgisiz.
9. 022: «6–12 soat» (tasdiqlanmagan) va «kamida 6 soat, odatda 12 soat»; kuzatuv muddati ham farqli.
10. 025, 106, 095: teniarinxoz va tenioz (T. saginata / T. solium), sistitserkoz aralashgan.
11. 037: P. vivax «eng keng tarqalgan» tasdiqlanmagan; 065: «asosan import» xulosada fakt, asosiy qismda tasdiqlanmagan.
12. 038: ma'lumot yig'ish va vaziyatni baholash bosqichlari tartibi mos emas.
13. 040: «skoleksda so'rg'ichlar bo'lmaydi» tibbiy jihatdan shubhali (savol qilinmadi).
14. 046, 104, 075, 067: davolashdan keyingi qayta tekshiruv muddati («2–3» va «2–4 hafta») turlicha.
15. 048, 060, 080, 111: sarlavha «qaysi viloyatlarda» deydi, matnda viloyat nomlari yo'q.
16. 052, 077, 096: qum pashshasi va chivin aralash ishlatilgan; 054: amastigotlar eritrotsitlarda deyilgan (aslida makrofaglarda).
17. 057 = 058, 072 = 079, 086 = 090: mazmunan deyarli bir xil (takror) mavzular.
18. 062: Anopheles turlari soni tasdiqlanmagan (400+ va ~40 farqli).
19. 063: tuxum yetilishi «bir necha hafta» va yashovchanligi «bir necha oy».
20. 094, 109: «primaxin» (aslida primaquin) imlo xatosi.
21. 101, 112, 098: sista yadrolari «2 yoki 4» va «to'rtta».
22. 105: tuxumlar «suv bilan» va «najas bilan» chiqadi deyilgan.
23. 114, 118: BM-SOM hujjatlari o'qilmagan; 113, 118 oxiri mazmunsiz takroriy jumlalar.
24. 115: sarlavhadagi metodik qo'llanma nomi matnda yo'q.

## 5. `(tasdiqlanmagan)` belgili faktlar
Barcha 118 mavzuda bor. Bunday jumlalar to'g'ri javob yoki iqtibos sifatida ishlatilmadi. Eng ko'plari: 103, 114, 115, 117, 118.

## Eslatma
Tibbiy mazmun (dozalar, muddatlar) mutaxassis tomonidan tekshirilishi kerak. Ayrim noto'g'ri variantlar matn so'zlaridan tuzilgani uchun mazmunan sun'iy bo'lishi mumkin — ayniqsa 084, 085, 088, 105 ni qo'lda ko'zdan kechirish tavsiya etiladi.
