# AccessModifiers
  Javada Accesss mdodifikatorlari class, xususiyat field , metod yoki konstruktorning qaysi kontekslarda ishlatilishi mumkinligini belgilaydi.Ular kodning xavfsizligin ta'minlash ,
ma'lumotlarni yashirish encapsulation va class azolarning ko'rinishini nazorat qilish uchun ishlatiladi.Javada to'rtta Access modifikatori mavjud
public 
protetcetd
Default
Private
Access Modifiers
Public Modifier
public modifier
public modifikatori bilan belgilangan class,xususiyat , metod yoki konstruktorlar har qanday joydan
(boshqa classlar ,paketlar yoki modullar ) foydalanilishi mumkin.
1.Har qanday joydan kirish imkonini:public a'zolar istlagan class yoki paketdan chaqirilishi mumkin.
2.Merosa o'tishi:public a'zolar subcllaslarga meros qilib o'tadi va ulardan foydalanilishi mumkin.
3.Cheklov :public modifikatorlari mahaliy o'zgaruvchilar (local variables) qo'llanilmaydi, chunki 
mahalliy o'zgaruvchilar faqat o'z doirasida(scope) ishlatiladi.

PROTECTED MODIFIER
protected access modifikatori Javada class a'zolarning (xususiyatlari,metodlari,konstruktorlar,ichki classlar) ko'rinishini cheklash uchun ishlatiladi.
U public va default mdifikatorlari o'rtasidagi o'rta darajadagi kirish imkonini beraadi.
O'z class ichida foydalanish mumkin.
O'z paketi ichidagi barcha classlar  tomonidan ishlatilishi mumkin.
Boshqa paketdagi classlar tomonidan faqat meros(inheritance) orqali ishlatilishi mumkin.
protected modifikatori tashqi classlarga (outer class) qo'llanilmaydi.
DEFAULT MOFIFIER
