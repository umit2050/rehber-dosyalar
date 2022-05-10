# Markdown örnek dosyası

**Markdown**, 2004 yılında John Gruber ve Aaron Swartz tarafından oluşturulan _düz-metin-biçimlendirme_ sözdizimine sahip hafif bir [işaretleme dilidir](https://tr.wikipedia.org/wiki/Markdown). Bu dilin geliştirilmesinin amacı, okuma yazması kolay düz metin biçimini kullanarak istendiğinde XHTML veya HTML'ye dönüştürülebilmesiydi.

## Commonmark

2012'den itibaren Jeff Atwood ve John MacFarlane dahil bir grup insan Atwood'un standartlaştırma çabası olarak nitelendirdiği şeyi başlattı. Eylül 2014'te Gruber, [**CommonMark**](https://commonmark.org/) adında yeni bir lehçe olarak yeniden adlandırıldı.


## Markdown ile neler yapabilirsiniz?

* Başlıklar (Başlık1, 2, 3)
* Listeler
  * Sırasız ve sıralı listeler
  * Alt listeler
* Tablolar
* Metin biçimlendirme (kalın, italik)
* Bağlantı ekleme
* Görsel ekleme
* Alıntılar
* Kod blokları (programlama diline göre renklendirme)
* Yatay çizgiler

---

## Tablo örneği

| Başlık 1 | Başlık 2 | Başlık 3 | Başlık 4 | Başlık 5 | Başlık 6 |
| :--- | ---: | ---: | ---: | ---: | ---: |
| Madde | 100 | 50 | 200 | 40 | 25 |
| Madde 2 | 220 | 75 | 410 | 700 | 45 |
| Madde 3 | 80 | 90 | 300 | 60 | 150 |

Tablo sütunlarının hizalaması için:\
:--- Sola yanaşık \
---: Sağa yanaşık \
:---: Ortalanmış

## Alıntı örneği

> *"Daha büyük ve daha küçük bir şey daima vardır."*\
`Anaksagoras`

## `Kod bloğu` örneği

    Girinti ile yapılan bir kod bloğu örneği

```javascript
console.log("Merhaba Dünya");
document.getElementById("id").inner.HTML ="deneme";
```

```json
"Adı": "Ümit",
"Soyadı": "Büyükyıldırım"
"eposta": "kullanici@eposta.com"
```

## Metin biçimlendirme

Markdown ile **kalın**, _ilatik_, _**hem kalın hem italik**_ ve ~~üstü çizili metin~~ kullanabilirsiniz.

## Matematiksel ifadeler

$2^2$, \
$\frac{a}{b}$ \
$x = y $ \
$\pi$ = 3,14 \
$\{1, 2, 3\}$

Matematiksel ifadelerin tamamı için [burayı][1] ziyaret edebilirsiniz.

## Görsel ekleme

![](https://commonmark.org/help/images/favicon.png "Markdown logo")

![image][2]

## Ek kaynaklar 🚀
Markdown hakkında daha fazla bilgi için aşağıdaki kaynaklar kullanılabilir

[Commonmark][3]

[1]: https://rpruim.github.io/s341/S19/from-class/MathinRmd.html
[2]: https://commonmark.org/help/images/favicon.png 
[3]: https://commonmark.org/help/

