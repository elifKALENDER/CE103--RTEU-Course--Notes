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
header: 'VS code'
footer: '![height:50px](http://erdogan.edu.tr/Images/Uploads/MyContents/L_379-20170718142719217230.jpg) patika.dev week-1'
title: "VS CODE"
author: "Author: kodluyoruz team"
date:
subtitle: "Using Vscode "
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
footer-left: "© Asst. Prof. Dr. Uğur CORUH"
footer-center: "License: WTFPL"
footer-right:
subparagraph: true
lang: en-US 

math: katex
---

<!-- _backgroundColor: aquq -->

<!-- _color: orange -->

<!-- paginate: false -->

## VS CODE

### Week-1 (Quide Vs code )

#### Fall Semester, 2022-2023

Download [DOC](week-1.en.md_doc.pdf), [SLIDE](week-1.en.md_slide.pdf), [PPTX](week-1.en.md_slide.pptx)

<iframe width=700, height=500 frameBorder=0 src="../week-1.en.md_slide.html"></iframe>

---

<!-- paginate: true -->

### Content

- Visual Studio Code Kullanımı
- Explorer
- Search
- Extensions

---

## **VS Code**

---

### **Using Visual Studio Code**

- Overview, Theme and File Icon Settings

   In this article, we will tell you about the general appearance, theme and file icon settings on Visual Studio Code.
---

### Vs code 

 After successfully logging into Visual Studio Code, a menu bar greets us on the left. Let's start by addressing this menu bar.

![bg right:40% h:100x](https://raw.githubusercontent.com/Kodluyoruz/taskforce/main/editor-kullanimi/visual-studio-code/vs-genelgorunum/figures/vs-men%C3%BCbar.png)

---

### Vs code

- **Explorer(1)**
The first part in the menu bar is "Explorer". In this section, we can view the project folder that is open in Visual Studio Code. When we look at the image above, we can see that no project folder has been opened yet. In such a case, we can open the project folder by clicking the "Open Project" option.
![bg right:40% h:400px](https://raw.githubusercontent.com/Kodluyoruz/taskforce/main/editor-kullanimi/visual-studio-code/vs-genelgorunum/figures/vs-men%C3%BCbar2exp.png)

---

### Vs code

- **explorer(2)**
After successfully opening the project folder, we see an image similar to the image above. In this section, besides viewing the project folder, we can perform various operations such as opening new folders and files by clicking the icons marked in the image. If you have difficulty in opening the project folder and remembering which button performs which action, you can find them in the previous topic.

![bg left:40% h:400px](https://raw.githubusercontent.com/Kodluyoruz/taskforce/main/editor-kullanimi/visual-studio-code/vs-genelgorunum/figures/vs-men%C3%BCbar3exp.png)

---

### Vs code

- **Search(1)**

The "Search" section appears second in the menu bar. In this section, you can search within your project folder. Let's take a look at a small example.
![bg right h:400px](https://raw.githubusercontent.com/Kodluyoruz/taskforce/main/editor-kullanimi/visual-studio-code/vs-genelgorunum/figures/vs-search.png)

---

### Vs code

In our example, we can see that we searched for "we're coding" inside the project folder and the editor returned two results for this search. The "Replace" part in the example allows us to change the search results in bulk. What do we mean?

![bg left:50% h:400px](https://raw.githubusercontent.com/Kodluyoruz/taskforce/main/editor-kullanimi/visual-studio-code/vs-genelgorunum/figures/vs-kod.png)

---

### Vs code

Let's try to explain a little more what we mean with this image. In our example, we can see that we wrote "code.org" in the replace section and when we continue with the process, we can see that "we are coding.org" is now written on the lines that used to be written "we are coding".

![bg right:40% h:400px](https://raw.githubusercontent.com/Kodluyoruz/taskforce/main/editor-kullanimi/visual-studio-code/vs-genelgorunum/figures/vs-org.png)

---

### Vs code

- **Source Control**
The third part is the "Source Control", that is, the "Version Control" part. In this part, you can create an automatic version control system and share it on "Github".

![bg left:40% h:400px](https://raw.githubusercontent.com/Kodluyoruz/taskforce/main/editor-kullanimi/visual-studio-code/vs-genelgorunum/figures/vs-source.png)

---

### Vs code

- **Run**
"Run" welcomes us as the fourth part in the menu bar. We can run the codes we wrote in this section or the "Debug" system.

![bg right:40% h:400px](https://raw.githubusercontent.com/Kodluyoruz/taskforce/main/editor-kullanimi/visual-studio-code/vs-genelgorunum/figures/vs-debug.png)


---

### Vs code

- **Extensions**
The fifth part is the "Extensions" part. In this section, we can install popular plugins. "What do plugins do?" You seem to be asking the question :) Don't worry, we'll talk about add-ons in our upcoming articles.
After examining the structures in the upper parts of the menu bar, we can continue by examining the lower parts.

![bg left:40% h:400px](https://raw.githubusercontent.com/Kodluyoruz/taskforce/main/editor-kullanimi/visual-studio-code/vs-genelgorunum/figures/vs-ext.png)

---

### Vs code

- **Extensions(2)**
In this section, we first meet a section where we can synchronize our own settings. With this feature, you can synchronize your settings if you are using different computers or want to switch to another computer.

![bg right:40% h:400px](https://raw.githubusercontent.com/Kodluyoruz/taskforce/main/editor-kullanimi/visual-studio-code/vs-genelgorunum/figures/vs-alt.png)


--- 

### Vs code

- **Extensions(3)**
In the other and last part of the menu bar, there is a section where we can view the command palette, access the settings easily, change the theme and file icon settings of the editor.

![bg left:40% h:400px](https://raw.githubusercontent.com/Kodluyoruz/taskforce/main/editor-kullanimi/visual-studio-code/vs-genelgorunum/figures/vs-ayar.png)


--- 

### Vs code

- **Tema ve Dosya İkonu Ayarları**
For theme and file icon settings, you must first click on the last icon we introduced in the menu bar. Then you will see;

![bg right:40% h:400px](https://raw.githubusercontent.com/Kodluyoruz/taskforce/main/editor-kullanimi/visual-studio-code/vs-genelgorunum/figures/vs-tema.png)

--- 

### Vs code

In the other and last part of the menu bar, there is a section where we can view the command palette, access the settings easily, change the theme and file icon settings of the editor.

--- 

### Vs code

- **You can set the theme of your editor by clicking on the "Color Theme" option.**


![center :70% h:500px](https://raw.githubusercontent.com/Kodluyoruz/taskforce/main/editor-kullanimi/visual-studio-code/vs-genelgorunum/figures/vs-tema.gif)

--- 
### Vs code

- **You can change the file icons in your editor by clicking "File Icon Theme".**


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
