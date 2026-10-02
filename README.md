# Ödül ve Disiplin Programı

Okul öğrenci ödül ve disiplin işlerini (olay kaydı, kurul kararı, tebligat, süre takibi, ödül belgeleri) MEB Ortaöğretim Kurumları
Yönetmeliği'ne göre düzenli tutmaya yardımcı, Windows için bir masaüstü programıdır.

* **Öğrenci verileri yalnızca okulun kendi bilgisayarında, şifreli olarak saklanır.** Bu depoda hiçbir okul verisi bulunmaz.
* Program okula özel **lisans dosyası** (`lisans.odl`) ile çalışır; lisans dosyası geliştirici tarafından ayrıca iletilir.
* Bu program Milli Eğitim Bakanlığı'nın resmî yazılımı değildir.

## Son sürüm: 1.2.0

İndirme: https://github.com/burhanaysan/odul-disiplin/raw/main/indir/OdulDisiplinProgrami_v1.2.0.zip

Dosyanın bozulmadığını denetlemek için (PowerShell):

```
Get-FileHash .\OdulDisiplinProgrami_v1.2.0.zip -Algorithm SHA256
```

Beklenen SHA-256: `28c162e78309f9079709d5a455ea36bf9a05b38c3fbe5d750be657b14eaa9611`

Kurulum ve kullanım ayrıntıları zip içindeki `OKUBENI.txt` dosyasındadır.

## Güncelleme ve internet

Program, internet varsa bu depodaki `guncelleme/` klasörünü okur (yalnızca okur; okul ya da öğrenci bilgisi göndermez).
Arayüz, mevzuat verisi ve lisans yenilemeleri geliştiricinin özel anahtarıyla **imzalıdır**: imzası geçersiz, değiştirilmiş ya da eski
hiçbir dosya kullanılmaz. Program kendi çalıştırılabilir dosyasını (exe) değiştirmez; yeni program sürümü yalnızca duyurulur ve
bu sayfadan elle indirilir. Kullanıcı, Ayarlar ekranından otomatik denetimi kapatabilir.
