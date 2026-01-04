# TZ-itpark-0401
# 🌐 WEB SAYT SAHIFALARI
## 📚 Mini Ta’lim Markazi Boshqaruv Tizimi

---

## 1. Umumiy tavsif

Ushbu bo‘lim web saytning **asosiy sahifalari**, ularning vazifasi va
foydalanuvchi bilan qanday ishlashini tavsiflaydi.

Loyiha kichik bo‘lgani sababli:
- sahifalar soni kam
- murakkab UX talab qilinmaydi
- asosan ma’lumot ko‘rish va boshqarish maqsad qilingan

---

## 2. Sahifalar ro‘yxati

1. Bosh sahifa
2. O‘quvchilar sahifasi
3. Mentorlar sahifasi
4. Kurslar sahifasi
5. Guruhlar sahifasi
6. Guruh tafsilotlari sahifasi

---

## 3. Sahifalar tavsifi

---

## 3.1 🏠 Bosh sahifa (Home)

### Vazifasi:
- Tizim haqida qisqacha ma’lumot berish
- Umumiy statistikani ko‘rsatish

### Ko‘rsatiladigan ma’lumotlar:
- Jami o‘quvchilar soni
- Faol o‘quvchilar soni
- Jami mentorlar
- Faol guruhlar

---

## 3.2 👨‍🎓 O‘quvchilar sahifasi (Students)

### Vazifasi:
- O‘quvchilar ro‘yxatini ko‘rsatish

### Funksiyalar:
- Status bo‘yicha filter (ACTIVE / INACTIVE / FINISHED)
- Telefon yoki ism bo‘yicha qidiruv

### Jadval ustunlari:
- Ism
- Familiya
- Telefon
- Status
- Ro‘yxatdan o‘tgan sana

---

## 3.3 👨‍🏫 Mentorlar sahifasi (Mentors)

### Vazifasi:
- Mentorlar ro‘yxatini ko‘rsatish

### Funksiyalar:
- Daraja bo‘yicha filter (JUNIOR / MIDDLE / SENIOR)
- Faollik bo‘yicha filter

### Jadval ustunlari:
- Ism
- Familiya
- Daraja
- Holati (Active / Inactive)

---

## 3.4 📘 Kurslar sahifasi (Courses)

### Vazifasi:
- Mavjud kurslarni ko‘rsatish

### Funksiyalar:
- Kurs turi bo‘yicha filter (PROGRAMMING / ENGLISH / DESIGN)
- Faqat faol kurslarni ko‘rsatish

### Jadval ustunlari:
- Kurs nomi
- Kurs turi
- Davomiyligi (oy)
- Holati

---

## 3.5 👥 Guruhlar sahifasi (Groups)

### Vazifasi:
- Guruhlar ro‘yxatini ko‘rsatish

### Funksiyalar:
- Dars kunlari bo‘yicha filter (ODD / EVEN)
- Mentor bo‘yicha filter

### Jadval ustunlari:
- Guruh nomi
- Kurs
- Mentor
- Dars kunlari
- Boshlanish sanasi

---

## 3.6 📄 Guruh tafsilotlari sahifasi (Group Detail)

### Vazifasi:
- Bitta guruh haqidagi to‘liq ma’lumotni ko‘rsatish

### Ko‘rsatiladigan ma’lumotlar:
- Guruh nomi
- Kurs nomi va turi
- Mentor ma’lumotlari
- Dars kunlari
- Boshlanish sanasi

### Qo‘shimcha:
- Shu guruhga biriktirilgan o‘quvchilar ro‘yxati
- O‘quvchi statuslari ko‘rsatiladi

---

## 4. Navigatsiya talablari

Saytning yuqori qismida (navbar):
- Bosh sahifa
- O‘quvchilar
- Mentorlar
- Kurslar
- Guruhlar

---

## 5. Ruxsat darajalari (soddalashtirilgan)

| Rol | Sahifalarni ko‘rish |
|----|-------------------|
| Admin | Barcha sahifalar |
| Mentor | Guruhlar va o‘quvchilar |
| Guest | Faqat bosh sahifa |

---

## 6. Texnik eslatmalar

- Sahifalar Django CBV yoki FBV orqali amalga oshiriladi
- Filter va search `models.Manager` orqali ishlashi tavsiya etiladi
- Status va tanlovlar `models.TextChoices` orqali chiqariladi

---

## 7. Yakuniy natija

Web sayt:
- kichik
- tushunarli
- o‘quv maqsadiga mos
- Django ORM imkoniyatlarini ko‘rsatib beruvchi

tizim bo‘lishi kerak.
