# homework

# Markdown nedir?
 
markdown düz metinleri kullanarak karmaşık kodlar kullanmadan kolayca metinleri biçimlendimeyi sağlayan hafif bir metin işaretleme dilidir

## Örnekler ile anlayalım


###  "#" **başlık oluşturmaya yarar**
 
 satır başına "#" koyulan cümleler başlık olur yan yana koyulan #'ler başlığı yan başlığa çevirir.
mesela

```
 # başlık

 ## başlık

 ### başlık

 #### başlık
```
yazarsak

# başlık

## başlık

### başlık
 
#### başlık

çıkar.

###  **kalın** ve *italik* 
**kalın** ve *italik* yazı ile kelimeyi yada kelimeleri vurgulayabiliriz. **kalın** yazıyı kelime yanlarına iki yıldız kullanarak, *italik* yazıyı kelime yanlarına 1 yıldız koyarak oluşturabiliriz.
mesela
```
**kalın**

*italik*

*** kalın ve italik***
```
yazarsak

#### **kalın**

#### *italik*

#### ***kalın ve italik***

çıkar.

### sıralı liste
sıralı listeleri satır başına "-"(kısa çizgi) kullanarak oluşturabiliriz
```
- kıyma

- yoğurt

- sebze
```
yazarsak

- kıyma

- yoğurt

- sebze

çıkar.

### alıntı oluşturma
bir alıntı kutucuğu oluşturur, alıntı yaptığımız şeyleri satır başına ">"(küçüktür işareti) kullanarak gösterebiliriz.

mesela
```
> bu bir alıntıdır
```
yazarsak

> bu bir alıntıdır
 
çıkar.

### kod bloğu 
eğer bir kodu göstermek istiyorsak bunu bu kodu kullanarak yazarız. yazcağımız şeylerin bir satır üstüne ve altına "```" (üç ters kesme işareti) yazarız.
mesela
```
####bu 

**bir** 

*kod*

***bloğudur***
```
buna bir örnektir, gördüğünüz gibi kodlar çalışmak yerine gözükyorlar.
### Internet link'i ekleme
internet linki eklemek için "[]" ve "()" (köşeli parantez ve parantez) kullanırız
mesela
```
hadi [link](https//github.com) 'a girelim
```
yazarsak
hadi [link](https//github.com) 'a girelim yazmış oluruz ve
sizi github'a yönlendirecek bir link oluşur

# **README NEDİR NE İŞE YARAR**

## ***README nedir?***

GİTHUB'da bir projeye tıkladığınızda
Projeyi tanıtan, nasıl kurulcağını açıklayan şey, *README.md* dosyasıdır.
Ayrıca projenin kök dizisine eklenen ve genellikle markdown.md ile yazılan bir tanıtım belgesidir.

## ***README NE İŞE YARAR***

- Projeyi tanıtır, hangi amaçla hangi ders için yapıldığını açıklar

- kurulum rehberidir, projeyi indiren başka birinin kodu nasıl çalıştıracağobı açıklar

- Teknolojileri listeler, kodun yazılırken hangi programlama dilinin yada hangi kütüphanler ile yazıldığını belirler

- iletişim kurar,Projeyi kimlerin yazdığını belirterek projenin sahibini gösterir

# *PROJE Versiyonları Nedir Nasıl Belirlenir?*

## *PROJE Versiyonları Nedir?* 

Proje versiyonları, projenize yaptığınız her düzeltmede, değişiklikte ve güncellemede değişen 1.0.0 yada 3.4.6 gibi sayılardır, numaralardır.
Bu numaralar projeyi kullanan kişiye projenin kaç defa değiştiğini gösterir.


## *PROJE versiyonları nasıl belirlenir?*

#### proje versiyonları bir kaç şekilde belirlenebilir, değişebilir

### 1. PATCH(yama/düzeltme)

- Projedeki kodların çalışmasını etkilemeden oluşan hataları düzelttiğinizde yada ufak tefek ekelmeler yaptığınızsa en sağdaki rakama bir adet artar

- #### Örneğin 
bir hatayı düzelttiğinizde 1.0.0'dan 1.0.1'e yükselir

### MINOR(yeni sürüm/özellik)

- Projenize eski çalışan özellikleri *bozmadan* **Tamamen yemi bir işlev yada özellik** eklerseniz ortadaki rakam bir adet artar

- #### Örneğin
 projenize yeni bir menü eklediniz 1.0.1'den 1.1.0'a yükseldi

### 3. MAJOR (ANA sürüm/büyük değişim)

- Projede köklü bir değişim yaptığınızda, tasarımı komple değiştirdiğinizde veya eski kodların artık çalışmayacağı kadar büyük bir yenilik yaptığınızda en soldaki rakam bir adet artar ve diğer iki rakam sıfırlanır

- #### ÖRNEĞİN
projenizi tamamen tekrar yazdınız yada alt yapısını değiştirdiniz.
1.1.0 olan sürüm 2.0.0'a yükseldi.

## İLK SÜRÜM NASIL OLUŞUR

-**Projeye** ilk başladığınızda yada daha geliştirme aşamasındayken genellikle sürüm 0.1.0 olarak başlar.

- ***PROJENİZ tamamen bittiğinde, hatasız çalıştığında, teslim edilmeye hazır olduğunda*** Projenizin ilk resmi sürümü 1.0.0 olur.