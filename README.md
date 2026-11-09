# Kıyı Vardiyası (Shore Shift)

Liman ve kıyı pistlerinde geçen, drift ve turbo üzerine kurulu bir kart yarışı oyunu. Windows için.
Bu depoda yalnızca oyunun hazır (derlenmiş) sürümü var; kaynak kodu burada değil.

## İndir ve oyna

1. **[KiyiVardiyasi.exe'yi indir](https://github.com/mehmetrooki/RushCard-Oyun/releases/latest/download/KiyiVardiyasi.exe)**
2. Çift tıkla. Windows "Bilgisayarınız korundu" derse **Ek bilgi → Yine de çalıştır** (program imzasız olduğu için sorar).
3. Oyun (yaklaşık 1,6 GB) kendiliğinden iner, kurulur ve açılır. Masaüstüne **Kıyı Vardiyası** kısayolu konur.

Sonraki açılışlarda yeni sürüm varsa önce onu indirir, yoksa oyunu hemen açar. İndirme yarıda kalırsa programı
yeniden aç, kaldığı yerden sürer. Oyun `%LOCALAPPDATA%\RushCard\Oyun` klasörüne kurulur (yönetici izni gerekmez);
ilerlemen güncellemelerde korunur. Kaldırmak için o klasörü ve masaüstündeki kısayolu silmen yeterli.

İnternetsiz kurulum: [Releases](https://github.com/mehmetrooki/RushCard-Oyun/releases/latest) sayfasındaki
`RushCard_Oyun.zip`'i indir, bir klasöre çıkar, içindeki `RushCard.exe`'yi çalıştır. Ayrıntılar zipteki
`NASIL_OYNANIR.txt`'de.

## Gerekenler

- Windows 10 / 11, 64 bit
- DirectX 12 destekli ekran kartı (NVIDIA GTX 1060 / AMD RX 580 ya da daha yeni, güncel sürücüyle)
- Yaklaşık 4 GB boş alan (indirme + kurulum)

## Kontroller

| | Klavye | Kumanda |
|---|---|---|
| Gaz / fren-geri | W / S | A / X |
| Direksiyon | A / D | Sol çubuk |
| Zıpla, tut + yön = drift | Space | RB |
| Drift turbosu | Sol Shift | LB |
| Eşya / korna | E | B |
| Roketi arkaya ateşle | Q (basılı) + E | LT (basılı) + B |
| Arkaya bak / kamera | Q / C | LT / RT |
| Mola | Esc | Menu |

Oyun İngilizce açılır; Settings > Driving > "Language · Dil" satırından Türkçe yapılır.

## Lisanslar ve atıflar

Oyundaki üçüncü taraf modeller, sesler ve yazı tipleri ile lisansları [CREDITS.md](CREDITS.md) dosyasında
(CC BY modellerin yazarları dahil). Yazı tipleri SIL Open Font License ve DejaVu lisansıyla gelir; lisans metinleri
oyun klasöründe `RushCard\Content\RushData\Fonts` içinde.

---

**English:** a kart racer for Windows. Download
[KiyiVardiyasi.exe](https://github.com/mehmetrooki/RushCard-Oyun/releases/latest/download/KiyiVardiyasi.exe) and run
it: it downloads the game (about 1.6 GB), installs it under `%LOCALAPPDATA%\RushCard` and starts it, and on later runs
fetches new versions. If Windows SmartScreen warns about the unsigned program, choose *More info → Run anyway*.
Needs Windows 10/11 64-bit and a DirectX 12 graphics card. Third-party credits: [CREDITS.md](CREDITS.md).
