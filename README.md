# Erciyes Anadolu Holding ABAP Bootcamp Final Task
 Erciyes Anadolu Holding ve Patika.dev işbirliği kapsamında düzenlenen eğitimin final projesi.

## Proje İsterleri ve Önemli Kriterler:
1. Projede Z’li 2 adet tablo oluşturulacaktır. Bu tabloların biri header biri item tablosu olacak.

2. Selection Screen ekranı tasarlanacaktır. Ekranda Tab Panel oluşturulacak.

- Tabta - Sizin oluşturduğunuz 2 adet Z'li tablonun key alanları yer alacaktır.

- Tabta - File upload  alanı olacaktır.

3. Eğer birinci tab’daki alanlar dolu ise program rapor şeklinde çalışıp birinci tab’daki girilen değerlere göre Z’li tablolarınızdan veriyi çekerek ekrandaki ALV raporda gösterilecektir.

4. Eğer ikinci tab’daki file upload nesnesi dolu ise file upload’a klasör adresi girilen exceldeki veriler ALV raporunda gösterilecektir.

5. ALV raporun GUI statusune 3 adet buton yerleştirilecektir. Bu butonların 1.si eğer 2.tab paneldeki file upload alanındaki excel dosya yolu dolu ve exceldeki veriler ALV raporda gösteriliyor ise ALV rapordaki verileri Z’li tasarlanan 2 tabloya kayıt edecektir.

(Not : Excel dosyasındaki her satırda header ve item alanları olacaktır. Eğer ki program file upload boş ise kaydet butonuna basılırsa hata vermesi sağlanacaktır.)

6. Z’li tabloların sm30 bakım ekranı oluşturulacak. Her bir bakım ekranı transaction koda bağlanacaktır.

7. ALV raporun GUI statusundeki 2. ve 3. butonlara tıklanıldığında bu transaction kodlar call edilecektir.
