# Ödül ve Disiplin Programı

Okul öğrenci ödül ve disiplin işlerini (olay kaydı, kurul kararı, tebligat, süre takibi, ödül belgeleri) MEB Ortaöğretim Kurumları
Yönetmeliği'ne göre düzenli tutmaya yardımcı, Windows için bir masaüstü programıdır.

* **Öğrenci verileri yalnızca okulun kendi bilgisayarında, şifreli olarak saklanır.** Bu depoda hiçbir okul verisi bulunmaz.
* Program okula özel **lisans dosyası** (`lisans.odl`) ile çalışır; lisans dosyası geliştirici tarafından ayrıca iletilir.
* Bu program Milli Eğitim Bakanlığı'nın resmî yazılımı değildir.

## Son sürüm: 1.1.0

İndirme: https://github.com/burhanaysan/odul-disiplin/raw/main/indir/OdulDisiplinProgrami_v1.1.0.zip

Dosyanın bozulmadığını denetlemek için (PowerShell):

```
Get-FileHash .\OdulDisiplinProgrami_v1.1.0.zip -Algorithm SHA256
```

Beklenen SHA-256: `c6a5d23b7d93ab7162f49bf4778eb29ea82083a438567e0119dc2f203fdf68b7`

Kurulum ve kullanım ayrıntıları zip içindeki `OKUBENI.txt` dosyasındadır.

## Güncelleme ve internet

Program, internet varsa bu depodaki `guncelleme/` klasörünü okur (yalnızca okur; okul ya da öğrenci bilgisi göndermez).
Arayüz, mevzuat verisi ve lisans yenilemeleri geliştiricinin özel anahtarıyla **imzalıdır**: imzası geçersiz, değiştirilmiş ya da eski
hiçbir dosya kullanılmaz. Program kendi çalıştırılabilir dosyasını (exe) değiştirmez; yeni program sürümü yalnızca duyurulur ve
bu sayfadan elle indirilir. Kullanıcı, Ayarlar ekranından otomatik denetimi kapatabilir.
