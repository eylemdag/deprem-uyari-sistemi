MPU6050 TABANLI SARSINTI ALGILAMA ve SMS UYARI SİSTEMİ
-


PROJENİN AMACI
-
- Yapilarin anlik sismik tepkilerini izlemek  
- Mikro titresimleri algilayarak erken uyari uretmek  
- Riskli durumlarda buzzer ve LED ile yerel uyari vermek  
- Kritik esiklerde SMS veya arama ile uzaktan bildirim yapmak  
- Role kontroluyle elektrik, su ve dogal gaz hatlarini otomatik kesmek  
- Dusuk maliyetli, sahada uygulanabilir bir sistem gelistirmek  

SİSTEM BİLEŞENLERİ
-
- Arduino Uno – Ana kontrol birimi  
- MPU6050 – 3 eksenli ivmeolcer sensoru  
- SIM800L GSM Modulu – SMS ve arama ile bildirim  
- 16x2 LCD Ekran – Anlik durum ve olcum bilgileri  
- 5V Role Modulu – Hatlarin kesilmesi  
- Buzzer ve LED – Yerel uyari  
- Li-Ion Piller – Tasinabilir guc kaynagi  
- Breadboard, jumper kablolar, potansiyometre

ÇALIŞMA MANTIĞI
-
1. MPU6050 sensorunden ivme verileri surekli okunur.  
2. Veriler belirlenen 1. esik ile karsilastirilir.  
   - Asilirsa: Buzzer ve LED aktif olur.  
3. Veriler 2. esik degerini asarsa:  
   - Buzzer ve LED aktif olur  
   - SIM800L ile SMS veya arama gonderilir  
   - Role devreyi keser (elektrik, su, gaz)  

Bu yapi sayesinde hem yerel hem de uzaktan erken uyari saglanir ve ikincil afet riskleri azaltirilir.

PROJE RAPORU
-
(report/DEPREM_ALGILAMA_SENSORU.docx)


Bu proje; konutlar, apartmanlar, kucuk isletmeler ve deprem riski yuksek bolgelerde
yapi guvenligini artirmaya yonelik, gelistirilebilir ve yayginlastirilabilir bir
erken uyari cozumu sunmaktadir.
