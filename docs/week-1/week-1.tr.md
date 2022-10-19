---
marp: true
theme: default
style: |
    img[alt~="center"] {
      display: block;
      margin: 0 auto;
    }
_class: lead
paginate: true
backgroundColor: #fff
backgroundImage: url('https://marp.app/assets/hero-background.svg')
header: 'Vs code'
footer: '![height:50px](http://erdogan.edu.tr/Images/Uploads/MyContents/L_379-20170718142719217230.jpg) RTEU CE204 Hafta-1'
title: "VS CODE"
author: "Author: kodluyoruz ekibi"
date:
subtitle: "Vscode kullanımı"
geometry: "left=2.54cm,right=2.54cm,top=1.91cm,bottom=1.91cm"
titlepage: true
titlepage-color: "FFFFFF"
titlepage-text-color: "000000"
titlepage-rule-color: "CCCCCC"
titlepage-rule-height: 4
logo: "assets/2021-10-19-15-01-36-image.png"
logo-width: 100 
page-background:
page-background-opacity:
links-as-notes: true
lot: true
lof: true
listings-disable-line-numbers: true
listings-no-page-break: false
disable-header-and-footer: false
header-left:
header-center:
header-right:
footer-left: "© Dr. Öğr. Üyesi Uğur CORUH"
footer-center: "License: WTFPL"
footer-right:
subparagraph: true
lang: en-US 

math: katex
---

<!-- _backgroundColor: aquq -->

<!-- _color: orange -->

<!-- paginate: false -->

## Örnek Ders Adı

### Hafta-1 (Vs code rehberi)

#### Güz Dönemi, 2022-2023

İndir [DOC](week-1.tr.md_doc.pdf), [SLIDE](week-1.tr.md_slide.pdf), [PPTX](week-1.tr.md_slide.pptx)

<iframe width=700, height=500 frameBorder=0 src="../week-1.tr.md_slide.html"></iframe>

---

<!-- paginate: true -->


### içerik

- Visual Studio Code Kullanımı
- Explorer
- Search
- Extensions

---

## **VS Code**

---

### **Visual Studio Code Kullanımı**

- Genel Görünüm, Tema ve Dosya İkonu Ayarları

   Bu yazımızda sizlere Visual Studio Code üzerinde genel görünüm,tema ve dosya ikonu ayarlarını anlatacağız.
---

### Vs code 

 Visual Studio Code'a başarılı bir şekilde giriş yaptıktan sonra bizleri sol tarafta bir menü çubuğu karşılıyor. Bu menü çubuğunu ele alarak başlayalım.

![bg right:40% h:100x](https://raw.githubusercontent.com/Kodluyoruz/taskforce/main/editor-kullanimi/visual-studio-code/vs-genelgorunum/figures/vs-men%C3%BCbar.png)

---

### Vs code

- **Explorer(1)**
Menü çubuğundaki ilk kısım "Explorer"dır. Bu kısımda Visual Studio Code içerisinde açık olan proje klasörünü görüntüleyebiliriz. Üstteki görsele baktığımızda henüz herhangi bir proje klasörünün açılmadığını görebiliriz. Böyle bir durumda "Open Project" seçeneğine tıklayarak proje klasörünü açabiliriz.

![bg right:40% h:400px](https://raw.githubusercontent.com/Kodluyoruz/taskforce/main/editor-kullanimi/visual-studio-code/vs-genelgorunum/figures/vs-men%C3%BCbar2exp.png)

---

### Vs code

- **explorer(2)**
Proje klasörünü başarılı bir şekilde açtıktan sonra yukarıdaki görsele benzer bir görüntü ile karşılaşırız. Bu kısımda proje klasörünü görüntülemekle beraber görselde işaretlenen ikonlara tıklayarak yeni klasör ve dosya açmak gibi çeşitli işlemleri gerçekleştirebiliriz. Proje klasörünü açmakta ve hangi butonun hangi işlemi gerçekleştirdiğini hatırlamakta zorlanıyorsanız bunlara bir önceki konudan ulaşabilirsiniz.

![bg left:40% h:400px](https://raw.githubusercontent.com/Kodluyoruz/taskforce/main/editor-kullanimi/visual-studio-code/vs-genelgorunum/figures/vs-men%C3%BCbar3exp.png)

---

### Vs code

- **Search(1)**
Menü çubuğunda ikinci olarak karşımıza "Search" kısmı çıkıyor. Bu kısımda proje klasörünüz içinde aramalar yapabilirsiniz. Gelin sizlerle küçük bir örneğe bakalım.

![bg right h:400px](https://raw.githubusercontent.com/Kodluyoruz/taskforce/main/editor-kullanimi/visual-studio-code/vs-genelgorunum/figures/vs-search.png)

---

### Vs code

Örneğimizde proje klasörünün içinde "kodluyoruz"u arattığımızı ve editörün bu arama sonucunda iki sonuç verdiğini görebiliriz. Örnekte yer alan "Replace" kısmı bizlere arama sonuçlarını toplu bir şekilde değiştirme imkanı veriyor. Ne demek istiyoruz?

![bg left:50% h:400px](https://raw.githubusercontent.com/Kodluyoruz/taskforce/main/editor-kullanimi/visual-studio-code/vs-genelgorunum/figures/vs-kod.png)

---

### Vs code

Ne demek istediğimizi bu görselle biraz daha açıklamaya çalışalım. Örneğimizde replace kısmına "kodluyoruz.org" yazdığımızı ve işleme devam ettiğimizde eskiden "kodluyoruz" yazılı satırlarda artık "kodluyoruz.org" yazdığını görebiliriz.

![bg right:40% h:400px](https://raw.githubusercontent.com/Kodluyoruz/taskforce/main/editor-kullanimi/visual-studio-code/vs-genelgorunum/figures/vs-org.png)

---

### Vs code

- **Source Control**
Üçüncü olarak karşımıza çıkan kısım "Source Control" yani "Versiyon Kontrol" kısmıdır. Bu kısımda otomatik bir versiyon kontrol sistem oluşturabilir ve bunu "Github"ta paylaşabilirsiniz.

![bg left:40% h:400px](https://raw.githubusercontent.com/Kodluyoruz/taskforce/main/editor-kullanimi/visual-studio-code/vs-genelgorunum/figures/vs-source.png)

---

### Vs code

- **Run**
Menü çubuğunda dördüncü kısım olarak bizleri "Run" karşılıyor. Bu kısımda yazdığımız kodları ya da "Debug" yani hata ayıklama sistemini çalıştırabiliriz.
![bg right:40% h:400px](https://raw.githubusercontent.com/Kodluyoruz/taskforce/main/editor-kullanimi/visual-studio-code/vs-genelgorunum/figures/vs-debug.png)


---

### Vs code

- **Extensions**
Beşinci kısım "Extensions" yani eklentiler kısmıdır. Bu kısımda popüler olan eklentileri yükleyebiliriz. "Eklentiler ne işe yarar?" sorusunu sorar gibisiniz :) Endişelenmeyin, ilerleyen yazılarımızda eklentilerden bahsedeceğiz.
Menü çubuğunun üst kısımlarındaki yapıları inceledikten sonra, alt kısımlarını inceleyerek devam edebiliriz.

![bg left:40% h:400px](https://raw.githubusercontent.com/Kodluyoruz/taskforce/main/editor-kullanimi/visual-studio-code/vs-genelgorunum/figures/vs-ext.png)

---

### Vs code

- **Extensions(2)**
Bu kısımda bizleri ilk öncelikle, kendi ayarlarımızı senkronize edebileceğimiz bir kısım karşılıyor. Bu özellikle birlikte, eğer farklı bilgisayarlar kullanıyorsanız ya da başka bir bilgisayara geçiş yapmak istiyorsanız, ayarlarınızı senkronize edebilirsiniz.

![bg right:40% h:400px](https://raw.githubusercontent.com/Kodluyoruz/taskforce/main/editor-kullanimi/visual-studio-code/vs-genelgorunum/figures/vs-alt.png)


--- 

### Vs code

- **Extensions(3)**
Menü çubuğundaki diğer ve son kısımda da komut paletini görüntüleyebileceğimiz, kolaylıkla ayarlara ulaşabileceğimiz, editörün tema ve dosya ikonu ayarlarını değiştirebileceğimiz bir kısım bulunuyor.

![bg left:40% h:400px](https://raw.githubusercontent.com/Kodluyoruz/taskforce/main/editor-kullanimi/visual-studio-code/vs-genelgorunum/figures/vs-ayar.png)


--- 

### Vs code

- **Tema ve Dosya İkonu Ayarları**
Tema ve dosya ikonu ayarları için ilk önce, menü çubuğunda tanıttığımız son ikona tıklamalısınız. Sonrasında karşınıza çıkacak;

![bg right:40% h:400px](https://raw.githubusercontent.com/Kodluyoruz/taskforce/main/editor-kullanimi/visual-studio-code/vs-genelgorunum/figures/vs-tema.png)

--- 
### Vs code

- ****
Menü çubuğundaki diğer ve son kısımda da komut paletini görüntüleyebileceğimiz, kolaylıkla ayarlara ulaşabileceğimiz, editörün tema ve dosya ikonu ayarlarını değiştirebileceğimiz bir kısım bulunuyor.

--- 

### Vs code

- **"Color Theme" seçeniğine tıklayarak editörünüzün temasını ayarlayabilirsiniz.**


![center :70% h:500px](https://raw.githubusercontent.com/Kodluyoruz/taskforce/main/editor-kullanimi/visual-studio-code/vs-genelgorunum/figures/vs-tema.gif)

--- 
### Vs code

- **"File Icon Theme" seçeneğine tıklayarak editörünüzdeki dosya ikonlarını değiştirebilirsiniz.**


![center :70% h:500px](https://raw.githubusercontent.com/Kodluyoruz/taskforce/main/editor-kullanimi/visual-studio-code/vs-genelgorunum/figures/vs-fileikon.gif)

--- 

## References

- https://avesis.erdogan.edu.tr/ugur.coruh
- https://www.linkedin.com/in/ugurcoruh/
- https://www.hindawi.com/journals/scn/2018/6563089/ 
- https://dl.acm.org/doi/abs/10.1145/3410352.3410836
- https://www.sciencedirect.com/science/article/abs/pii/S2214212621002623 
-https://app.patika.dev/courses/visual-studio-code-kullanimi/vs-genelgorunum

---

$End-Of-Week-1-Module$