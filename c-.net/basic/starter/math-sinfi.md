---
description: Mamataliyev Diyorbek
---

# Math sinfi


Assalomu alaykum, yosh dasturchilar. Dasturlashni o'rganar ekansiz, matematikaga ishingiz tushishi tabiiy hol. Aytaylik, dasturingizda biror formula yoki ifodaning qiymatini hisoblashga to'g'ri kelib qolishi mumkin. Xo'sh, bu holatlarda matematik ifodalarni dastur kodiga qanday kiritamiz? Ifoda ichida qo'shish (+), ayirish (-), ko'paytirish (*), bo'lish (/) dan tashqari boshqa amallar qatnashgan bo'lsa, qo'shimcha metodlardan foydalanishga to'g'ri keladi. Buning uchun bizga **Math** sinfi metodlari yordam beradi. Bu metodlarni chaqirish uchun **Math** so'zidan keyin nuqta qo'yib, metod nomini yozamiz. Metod turiga qarab bir yoki bir nechta qiymatni kiritganimizda bizga hisoblangan qiymatni qaytaradi. Masalan, **Math.Abs(-3.5)** metodi 3.5 ni qaytaradi. Endi esa, sizga ko'proq **Math** sinfi metodlarini tanishtirishga harakat qilaman.

**Math.Abs()** – sonning absolyut qiymati (moduli) ni hisoblaydi. Kiruvchi parametr sifatida kiritilgan bitta son ixtiyoriy sonli tipda bo'lishi mumkin, faqat 2^64 dan katta bo'lib ketmasligi kerak. Qaysi tipda (*double, decimal, long, int, ..*) qiymat kiritilgan bo'lsa qaytarilgan qiymat ham shu tipda bo'ladi.

**Math.Acos()** – sonning arkkosinusini hisoblaydi. Kiruvchi va chiquvchi parametrlar faqat *double* tipida bo'ladi. Qaytarilgan burchak qiymati radianda ifodalangan bo'ladi. Math.Acos(0)=1,5707963267948966. 

**Math.Asin()** – sonning arksinusini hisoblaydi. Kiruvchi va chiquvchi parametrlar *double* tipida bo'ladi. Qaytarilgan burchak qiymati radianlarda ifodalanadi. Math.Asin(1)=1,5707963267948966.

**Math.Atan()** – sonning arktangensini hisoblaydi. *double* tipida ma'lumot qabul qiladi va qaytaradi. Qaytarilgan burchak qiymati radianlarda ifodalangan bo'ladi.
Math.Atan(1)=0,7853981633974483.

 **Math.BigMul()** –  ikki butun sonning ko’paytmasini hisoblaydi. *int* yoki *long* tipida ma'lumot qabul qiladi. *long* tipida qiymat qaytaradi. Masalan, Math.Bigmul(3,4)=12;
 
**Math.Ceiling()**  – kiritilgan sondan katta yoki unga teng bo'lgan eng yaqin butun sonni qaytaradi. *double* yoki *decimal* tipida ma'lumot qabul qiladi va qaytaradi. Math.Ceiling(3.14)=4,     Math.Ceiling(6.0)=6;     Math.Ceiling(-4.3)=-4;

**Math.Cos()** – burchakning kosinusini hisoblaydi. Burchak qiymati radianda kiritiladi.  Kiruvchi va qaytariluvchi parametrlar faqat *double* tipida bo'ladi. Math.Cos(3.141592653589793)=-1;

**Math.Cosh()** – burchakning giperbolik kosinusini hisoblaydi.

**Math.E** – konstanta, hech qanday amal bajarmaydi. O'zgarmas e sonini qaytaradi. e=2,718281828459045. 

**Math.Exp()** - o'zgarmas e sonini kiritilgan darajaga ko'tarilgandagi qiymatini qaytaradi. Kiruvchi va chiquvchi qiymatlar *double* tipida bo'ladi. Masalan, Math.Exp(1)=2,718281828459045;   Math.Exp(2)=4,4816890703380645. 

**Math.Floor()** - sonning butun qismi, kiritilgan sondan kichik yoki unga teng bo'lgan eng yaqin butun sonni qaytaradi. *double* yoki *decimal* tipida ma'lumot qabul qiladi va qaytaradi.       Math.Floor(1.5)=1;  Math.Floor(-1.5)=-2;  Math.Floor(1.0)=1.

**Math.IEEERemainder()** - bir sonni ikkinchisiga bo'lingandagi qoldiqni hisoblaydi. Lekin uning hisoblash algoritmi oddiy qoldiqnikidan boshqacharoq. a sonni b ga shu metoddan foydalanib bo'lsak, qoldiq IEEERemainder(a,b) = a - (b * Math.Round(a / b)) umumiy formula bilan hisoblanadi. Math.Round - butun songacha yaxlitlash metodi. Bundan shunday xulosa qilishimiz mumkin: agar a/b ning kasr qismi 0.5 dan kichik bo'lsa IEEERemainder metodi oddiy qoldiq bilan bir xil javob qaytaradi. Aks holda qoldiqdan b ni ayirilgan javobni qaytaradi. Masalan IEEEReaminder(10,3)=-1; IEEEReaminder(9,4)=1; 

**Math.Log()** - sonning logarifmini hisoblaydi. Agar **Math.Log(a)** ko'rinishida kiruvchi parametr sifatida bitta son kiritilsa  shu sonning natural logarifmini, agar **Math.Log(a,b)** ko'rinishida ikkita son kiritilsa a sonning b asosga ko'ra logarifmini hisoblaydi. *double* tipida ma'lumot qabul qiladi va qaytaradi.

**Math.Log10()** - sonning o'nli logarifmini hisoblaydi. *double* tipida ma'lumot qabul qiladi va qaytaradi.

**Math.Max()** - ikkita sondan kattasini topadi. Kiruvchi parametr sifatida istalgan sonli tipda (*int, byte, double, ..*) qiymat berish mumkin. Qaysi tipda qiymat berilsa huddi shu tipda qiymat qaytaradi.

**Math.Min()** - ikkita sondan kichigini topadi. Kiruvchi parametr sifatida istalgan sonli tipda (*int, byte, double, ..*) qiymat berish mumkin. Qaysi tipda qiymat berilsa huddi shu tipda qiymat qaytaradi.

**Math.PI** - konstanta. O'zgarmas pi sonining qiymatini qaytaradi. Math.PI=3,14159265358979.

**Math.Pow()** - sonni darajaga ko'taradi.
