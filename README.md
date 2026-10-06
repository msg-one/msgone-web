# msgone.net — MSG One kurumsal sayfası

Tek sayfalık kurumsal vitrin. Dış bağımlılık yok: tek `index.html`, web fontu indirmez.

**Tasarım dili** `msgdeneme.com` ile aynı (Apple sistem yazı tipi yığını, aynı renk
değişkenleri ve yarıçaplar). Tek fark vurgu rengi: MSG One moru `#6A3DF5`.

## Vitrin alanına yeni ürün eklemek

`<section class="vitrin">` içindeki `.rail`'e ikinci bir `<article class="slide">`
ekleyin ve `--c` değişkenine ürünün rengini verin. Kaydırma, nokta göstergeleri ve
erişilebilirlik etiketleri kendiliğinden çalışır — JavaScript'e dokunmak gerekmez.

## Ürün renkleri

| Ürün | Renk | Alan adı |
|---|---|---|
| Deneme | `#1E7BF2` | msgdeneme.com — **yayında** |
| Okul | `#1FC77E` | msgokul.com |
| Kurs | `#F26A2E` | msgkurs.com |
| PDR | `#E8318A` | msgpdr.com |
| Evrak | `#12C4D6` | msgevrak.net |
| Sanat | `#F7A81B` | msgsanat.com |
| Spor | `#E8232A` | msgspor.net |

## Yayın

GitHub Pages, `main` dalı kökünden. Özel alan adı `CNAME` dosyasında.
