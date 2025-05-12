Windows 10 ve 11 Aktivasyonu
Bu depo, Windows 10 ve 11'i 40 saniyeden kısa sürede etkinleştirmenin bir yolunu içerir. Her iki yöntem de Windows'un Home, Home N, Home Single Language, Home Country Specific, Professional, Education ve Enterprise sürümleriyle uyumludur.

> **_Yöntem 1 (Tavsiye Edilir)_**

PowerShell ile Anlık Windows Aktivasyonu

_İpucu_
Windows 10 ve 11'de PowerShell'i çalıştırmanın birçok yolu vardır.

Adım 1: Başlat veya arama simgesine tıklayın ve arama kutusuna "PowerShell" yazın.

Adım 2: "Yönetici olarak çalıştır" seçeneğine tıklayın.

Adım 3: Aşağıdaki satırı kopyalayın:

_Kopyala_

irm https://get.activated.win | iex

Adım 4: Sağ tıklayıp yapıştırın ve Enter tuşuna basın. Açılan pencerede birkaç seçenek göreceksiniz; 1. seçeneği seçin ve işlemi tamamlamak için birkaç saniye bekleyin.

Tebrikler, Windows'unuz etkinleştirildi. Artık CMD'den çıkmak için Enter tuşuna basabilir ve PowerShell'i kapatabilirsiniz.

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------

>_**Yöntem 2**_

CMD (Komut İstemi) ile Anlık Windows Aktivasyonu

_Not_

İnternete bağlı olun.

VPN gerekmez.

Adım 1: Başlat veya arama simgesine tıklayın ve "CMD" yazın. Komut İstemi seçeneğini yönetici olarak çalıştırın.

Lisans Anahtarları Listesi

_Anahtar	Sürüm_

**TX9XD-98N7V-6WMQ6-BX7FG-H8Q99	Home**

**3KHY7-WNT83-DGQKR-F7HPR-844BM	Home N**

**7HNRX-D7KGG-3K4RQ-4WPJ4-YTDFH	Home SL**

**PVMJN-6DFY6–9CCP6–7BKTT-D3WVR	Home CS**

**W269N-WFGWX-YVC9B-4J6C9-T83GX	Professional**

**MH37W-N47XK-V7XM9-C7227-GCQG9	Professional N**

**NW6C2-QMPVW-D7KKK-3GKT6-VCFB2	Education**

**2WH4N-8QGBV-H22JP-CT43Q-MDWWJ	Education N**

**NPPR9-FWDCX-D2C8J-H872K-2YT43	Enterprise**

**DPH2V-TTNVB-4X9Q3-TJR4H-KHJW4	Enterprise N**


Adım 2: KMS istemci anahtarını yükleyin. Aşağıdaki komutu kullanın:


_Kopyala_

slmgr /ipk yourlicensekey

Not: Lisans anahtarlarından birini seçin ve "yourlicensekey" ifadesi ile değiştirin.

Adım 3: KMS makine adresini ayarlayın. Aşağıdaki komutu kullanın:

_Kopyala_

slmgr /skms kms8.msguides.com

Adım 4: Windows'unuzu etkinleştirin. Aşağıdaki komutu kullanın:


_Kopyala_

slmgr /ato

Adım 5: Aktivasyon durumunu kontrol edin.

Tamam ✅ Windows'unuz başarıyla etkinleştirildi.
