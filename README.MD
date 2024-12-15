1. useState

useState — bu React kutubxonasidagi hooklardan biri bo‘lib, komponentlar ichida holat (state) saqlash va uni boshqarish imkonini beradi. React komponentlari odatda statik bo‘lib ko‘rinadi, lekin useState bilan siz komponentdagi ma'lumotlarni dinamik ravishda o‘zgartirish va render qilish imkoniyatiga egasiz.

2. useEffect

useEffect — bu React kutubxonasidagi hooklardan biri bo‘lib, komponentlar hayot tsikli bilan bog‘liq bo‘lgan effektlarni boshqaradi. Masalan, komponent render qilingandan so‘ng, ma'lumotlarni olish, DOM manipulyatsiyasi yoki boshqa yon funksiyalarni bajarish uchun ishlatiladi.

3. useContext

useContext — bu React kutubxonasidagi hooklardan biri bo‘lib, React konteksti orqali komponentlar o‘rtasida holatni (state) almashish imkonini beradi. Bu hook, ko‘pincha Context API bilan birga ishlatiladi, va komponentlar o‘rtasida ma'lumotlarni uzatishda props drilling (propsni chuqur va ko‘p qatlamli komponentlarga uzatish) muammosini hal qilishga yordam beradi.

4. useReducer

useReducer — bu React kutubxonasidagi hooklardan biri bo‘lib, holatni boshqarish (state management) uchun ishlatiladi. useReducer ko‘pincha useState ga o‘xshash tarzda ishlaydi, ammo u murakkab holatlar yoki ko‘p o‘zgaruvchilarni boshqarishda qulayroq bo‘lishi mumkin. useReducer odatda kompleks holatlar (masalan, bir nechta o‘zgaruvchi yoki murakkab holatlarni boshqarish) uchun ishlatiladi, ayniqsa, useState orqali holatni boshqarish qiyin bo‘lganda.

5. useCallback

useCallback — bu React kutubxonasidagi hooklardan biri bo‘lib, funksiya referensiyasini optimallashtirish uchun ishlatiladi. useCallback hooki, ayniqsa, rendere vaqtida funksiyalarni qayta yaratishni oldini olish uchun foydalidir. Bu funksiya referensiyasini (manzilini) saqlaydi va faqat zarur bo‘lganda yangilaydi.

6. useRef

useRef — bu React kutubxonasidagi hooklardan biri bo‘lib, DOM elementlariga yoki qiymatlarni saqlash uchun ishlatiladi. useRef yordamida biz komponentning holatini saqlamay, balki referensiyalarni saqlaymiz. Bu hook, asosan DOM elementlariga murojaat qilish yoki o‘zgarmas qiymatlarni saqlash uchun ishlatiladi, ularning qiymati renderlar o‘tgandan so‘ng ham o‘zgarishini davom ettiradi.