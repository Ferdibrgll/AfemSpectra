<p align="center">
  <img src="docs/banner.png" alt="AfemSpectra" width="100%" />
</p>

# AfemSpectra

Alan adını gir, sitenin dışarıdan görünen güvenlik ayarlarını tek raporda incele. AfemSpectra tarayıcıda çalışır ve hesap açmadan kullanılabilir.

**[AfemSpectra’yı aç →](https://afemspectra.ferdibirgul.workers.dev/)**

<p align="center">
  <img src="docs/screenshots/01-ana-sayfa.png" alt="AfemSpectra ana sayfa" width="90%" />
</p>

## Nasıl kullanılır?

1. AfemSpectra’da kendi alan adını veya taramak için yazılı izin aldığın alan adını gir.
2. **Tara** düğmesine bas. Kontroller tamamlandığında sitenin puanı ve bulgular aynı ekranda görünür.
3. Önce yüksek önem dereceli bulguları incele. Önerilen değişiklikleri kendi sitende uyguladıktan sonra yeniden tarayarak sonucu karşılaştır.

<p align="center">
  <img src="docs/screenshots/03-uc-adim.png" alt="Üç adımda rapor" width="90%" />
</p>

## Siten hakkında neler görebilirsin?

Ana sayfadaki etkileşimli haritada her noktayı seçerek ilgili kontrolün neyi incelediğini ve neden önemli olduğunu görebilirsin.

| Kontrol | Raporda görebileceklerin |
| --- | --- |
| Güvenlik başlıkları ve çerezler | Tarayıcıya gönderilen güvenlik başlıkları ve yanıtta görülen çerezlerin güvenlik bayrakları |
| TLS ve HTTPS | HTTPS bağlantısının kurulup kurulamadığı ve HTTP ziyaretçilerinin HTTPS’ye yönlendirilip yönlendirilmediği |
| DNS ve e-posta | Alan adının SPF, DMARC ve CAA kayıtları |
| Alt alan adları | Herkese açık sertifika şeffaflık kayıtlarında görünen alt alan adları |
| Standart dosyalar | Güvenlik bildirimleri için `security.txt` ve arama motorları için `robots.txt` dosyalarının varlığı |
| Teknoloji izleri | Sitenin yanıtlarında görünen sunucu, CDN, yazılım çatısı ve sürüm bilgileri |

<p align="center">
  <img src="docs/screenshots/02-saldiri-yuzeyi.png" alt="Saldırı yüzeyi haritası" width="90%" />
</p>

## Rapor nasıl okunur?

**Skor**, kontrol edilen ayarların 100 üzerinden özetidir. Her yüksek önem dereceli bulgu puanı 25, orta dereceli bulgu 10, düşük dereceli bulgu 4 azaltır. Radar grafik kategorileri karşılaştırır. Tarama notları, site yanıt vermediğinde veya bir veri kaynağına ulaşılamadığında hangi sonuçların eksik kalabileceğini açıklar.

<p align="center">
  <img src="docs/screenshots/04-rapor.png" alt="Rapor ekranı" width="90%" />
</p>

**Bulgular** önem sırasına göre listelenir. Örneğin bir güvenlik başlığı eksikse, bulgunun açıklamasını okuyabilir ve siten `_headers` dosyası kullanıyorsa önerilen ayarı kopyalayıp yapılandırmana uyarlayabilirsin.

<p align="center">
  <img src="docs/screenshots/05-duzeltme-ve-bulgular.png" alt="Hazır düzeltme kodu ve bulgular" width="90%" />
</p>

Raporu JSON olarak indirebilir, yazdırabilir veya yazdırma ekranından PDF olarak kaydedebilirsin. Mobilde aynı rapor tek sütunda gösterilir.

<details>
<summary>Mobil rapor örneğini göster</summary>

<p align="center">
  <img src="docs/screenshots/06-mobil-rapor.png" alt="Mobil rapor görünümü" width="280" />
</p>

</details>

*Ekran görüntüleri `ornek.com` için hazırlanmış örnek verileri gösterir.*

## Geliştirici

**Ferdi Birgül** · IT & Network Support Specialist | Offensive Security

Ağ altyapısı, sistem yönetimi ve siber güvenlik alanlarında çalışıyorum. AfemSpectra’yı, bir site sahibinin “Önce hangi ayarı düzeltmeliyim?” sorusuna cevap verebilmesi için geliştirdim. Bu yüzden raporda her bulguyu önem derecesiyle birlikte gösteriyor, eksik güvenlik başlıkları için uygulanabilir ayar örnekleri sunuyorum.

[Portföy](https://ferdibirgul.com/) · [GitHub](https://github.com/Ferdibrgll) · [LinkedIn](https://www.linkedin.com/in/ferdibirg%C3%BCl)

Bir bulgunun hatalı olduğunu düşünüyorsan veya bir önerin varsa [GitHub üzerinden geri bildirim bırakabilirsin](https://github.com/Ferdibrgll/AfemSpectra/issues).

## Lisans

[MIT Lisansı](LICENSE)
