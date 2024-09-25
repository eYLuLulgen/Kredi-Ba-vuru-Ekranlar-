.NET platformu üzerinde C# kullanarak banka şubelerinde kullanılan "Kredi Başvuru Ekranları" benzer sıfırdan ekranlar tasarlandı ve geliştirildi.Projede Windows Forms, MSSQL entegrasyonu, veri tabanı işlemleri, kullanıcı arayüzü tasarımı ve kredi başvuru sistemleri gibi konularda derinlemesine çalışmalar yapılmıştır.Müşteri bilgileri , kredi türleri ve koşulları,kredi kartı türleri ve koşulları, başvuru bilgileri veri tabanına kaydedilmiştir.

Uygulama çalıştığında bizi karşılayan ekranımız "Kredİ Ekranı"dır.

1)KREDİ ÖN BAŞVURU EKRANI
"Kredi Ekranı" içinde sekme olarak yer alan "Kredi Ön Başvuru" ekranında önceden yapılan kredi başvurularını görüntüleyebilir ya da veritabanına kayıtlı olan müşterilerin müşteri no'larını girerek yeni kredi başvurusu oluşturabiliriz. <br><br>
<img width="526" alt="image" src="https://github.com/user-attachments/assets/67645a8a-addc-476a-a683-5e3df8675fa0"><br>



Bu ekrandan bir başvuru seçilip ardından Detay butonuna basılırsa ikinci ekranımız olan 
"Detay Ekranı" bizi karşılar.

2)DETAY EKRANI
Bu ekranda, "Kredi Ön Başvuru" ekranından seçtiğimiz başvurunun ayrıntılarını görüntüleyebilir ve "Başvuru Detay" panelinde başvurunun kalan bilgilerini girebiliriz. <br><br>
<img width="572" alt="Detay Ekranı" src="https://github.com/user-attachments/assets/337d3c13-4619-40fe-9637-73a7da5050de"> <br>


Bu ekranda bulunan "Ürün Güncelleme" butonuna basıldığında üçüncü ekranımız olan "Ürün Güncelleme"ye geçiş yapar.

3)ÜRÜN GÜNCELLEME
Ekranımızın sol panelinde önceden tanımlı olan Kredi Türlerimizi güncelleyebilir ya da silebiliriz.Sağ panelinde ise yeni Kredi Türleri oluşturabiliriz. <br><br>
<img width="382" alt="image" src="https://github.com/user-attachments/assets/923d159b-179b-4d2e-abf1-24ef0ee37769"> <br>


4)KREDİ KARTI BAŞVURU EKRANI
"Kredi Ekranı" içinde sekme olarak yer alan "Kredi Kartı Başvuru" ekranında kredi kartı başvurusu yapılır. <br><br>
<img width="531" alt="image" src="https://github.com/user-attachments/assets/7d0e2eeb-0272-4d40-a2a5-601c888fd267"> <br>


Veri Tabanı Tabloları
1)Müşteri Bilgileri
Müşteri bilgileri "MusteriBilgiler" adlı tabloya kaydedilir.<br><br>
<img width="305" alt="image" src="https://github.com/user-attachments/assets/cb09f320-8bd9-43bd-96a7-69f07777484f"><br>

2)Kredi Başvuruları
"Kredi Ön Başvuru" ekranında oluşturulan başvurular "Basvurular"adlı tabloya kaydedilir.<br><br>
<img width="740" alt="image" src="https://github.com/user-attachments/assets/eecd0190-4ac7-41ab-96fc-633e812accf8"><br>

3)Kredi Türleri
Kredi türleri ve koşulları "Urun" adlı tabloya kaydedilir.<br><br>
<img width="740" alt="image" src="https://github.com/user-attachments/assets/18ff01ef-45a5-4768-9dd8-664f2fd8b447"><br>

4)Başvuru Detay
"Detay Ekranı"ndan alınan bilgiler buraya kaydedilir.<br><br>
<img width="488" alt="image" src="https://github.com/user-attachments/assets/4a4b9ef1-4734-4054-aa8b-c569a524357d"><br>

5)Kredi Kartı Başvuru
"Kredi Kartı Başvuru" ekranından girilen bilgiler buraya kaydedilir.<br><br>
<img width="824" alt="image" src="https://github.com/user-attachments/assets/d5da5d61-9de2-4287-adec-1ea080a104e0"><br>


6)Bireysel Kredi Kartları
"Kredi Kartı Başvuru" ekranında sunulan bireysel kredi kartları türleri "BireyselKrediKartlari"nda kaydedilir.<br><br>
<img width="200" alt="image" src="https://github.com/user-attachments/assets/84585d7b-6fc9-4d15-a2f8-32db879f8bfe"><br>


7)Ticari Kredi Kartları
"Kredi Kartı Başvuru" ekranında sunulan ticari kredi kartları türleri "TicariKrediKartlari"nda kaydedilir.<br><br>
<img width="197" alt="image" src="https://github.com/user-attachments/assets/de56cc55-7ed9-4f74-b983-d8081ee5f9ef"><br>

8)İl Seçenekleri
"Kredi Kartı Başvuru" ekranında sunulan iller "Il"e kaydedilir.<br><br>
<img width="199" alt="image" src="https://github.com/user-attachments/assets/2bf77fa9-1f15-4dbb-adfa-667efa94145f"><br>
