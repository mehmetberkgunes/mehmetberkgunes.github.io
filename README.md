# GitHub CV ve Yayınlar Sitesi

Bu paket, GitHub Pages üzerinde yayımlanabilecek basit bir akademik CV / yayınlar sitesi şablonudur.

## Kurulum

1. GitHub'da yeni repository oluşturun.
2. Repository adını GitHub kullanıcı adınızla aynı olacak şekilde yazın:
   `kullaniciadiniz.github.io`
   Örnek: `berk199194.github.io`
3. Bu klasördeki `index.html`, `style.css` ve `assets` klasörünü repository içine yükleyin.
4. CV PDF dosyanızı `assets/Mehmet_Berk_Gunes_CV.pdf` adıyla yükleyin.
5. GitHub'da Settings > Pages bölümünden kaynağın `main` branch ve `/root` olduğundan emin olun.
6. Site birkaç dakika içinde şu adreste görünür:
   `https://kullaniciadiniz.github.io`

## Yayın Ekleme

`index.html` içinde `publications` bölümündeki örnek `article` bloğunu kopyalayarak yeni yayın ekleyebilirsiniz.

Örnek yapı:

```html
<article class="publication">
  <h3>Yayın Başlığı</h3>
  <p class="meta">Dergi adı, yıl</p>
  <p>Kısa açıklama.</p>
  <p class="links">
    <a href="DOI_LINKI">DOI</a>
    <a href="PDF_LINKI">PDF</a>
  </p>
</article>
```

## Önerilen Bölümler

- Hakkımda
- CV
- Yayınlar
- Bildiriler
- Devam eden çalışmalar
- Dersler
- Araştırma alanları
- İletişim
- ORCID / Google Scholar / ResearchGate bağlantıları
