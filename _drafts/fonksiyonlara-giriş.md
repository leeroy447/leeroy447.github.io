---
tags:
- kalkülüs öncesi
- matematik
- fonksiyonlar
layout: ''
title: Fonksiyonlara Giriş
date: 
excerpt: ''
author: Kıvanç Yüksel
categories: []

---
Fonksiyonlar matematikte çok önemli bir yere sahiptir. Bunun sebebi aslında en kolayından en zoruna matematikteki bütün konularda fonksiyonları kullanıyor olmamızdandır. Maalesef bu konunun önemi genellikle bir çok matematik dersinde atlanıyor, anlatılmıyor. Bu nedenle biri size fonksiyon dediği zaman aklınıza aşağıdaki gibi birşey geliyordur muhtemelen:

$$f(x) = 3x + 4$$

Evet, bu bir fonksiyonun gösterimi, ancak fonksiyonların ne yaptığını anlamadan, bu, bize pek birşey ifade etmiyor. Peki fonksiyon nedir?

# Jumbotron İçinde: İçine  konulan nesneyi değiştirerek çıkartan, kararlı bir yapıdır.

# Put here box image for function

Bu basit tanımı genel olarak düşünürsek eğer, etrafımızdaki bir çok şeyin aslında bir fonksiyon görevi gördüğünün farkına varabiliriz. Bir çamaşır makinesi içine konulan kirli kıyafetleri temizleyerek (değiştirerek) çıkartan bir fonksiyon olarak düşünülebilir. Bunun gibi birçok örnek üretilebilir; bulaşık makinesi, meyve sıkacağı, mikrafon, hoparlör, ve benzeri (bu örnekler fonksiyonların birebir analojisi olmasada, yinede büyük resmi görmenizde size yardımcı olabileceğini düşünüyorum)... Fonsiyonun yukarıdaki basit tanımına tekrardan bakarsanız, "kararlı " kelimesinin geçtiğini görürsünüz. Bu ne demektir? Fonksiyonlar girişlerine konulan nesneleri her defasında aynı şekilde değiştirerek çıkışına gönderir. Yani, meyve sıkacağı örneğine dönersek, meyve sıkacağınızın içine ne zaman bir elma koysanız, çıkışından elma suyu alırsınız. Hiç, meyve sıkacağınıza elma koyduktan sonra, çıkışından portakal suyu aldığınız oldumu? :) . Bunun gibi, bir fonksiyonun girişine sürekli aynı nesneyi koyarsanız, çıkışından sürekli aynı nesneyi elde edersiniz.

Biz genellikle bir fonksiyona ne koyup çıkışından ne almak istediğimizi biliriz. Bunları biliyorsak eğer, geriye kalan tek şey bunların arasındaki bağlantıyı sağlayan fonksiyonu bulmaktır. Bulaşık makinesine kirli bulaşıkları koyacağımızı ve makinenin işi bittikten sonra temiz bulaşık elde etmek istediğimizi biliriz, ancak böyle bir makineyi nasıl yapmalı? Örnekler çeşitli olmasına rağmen özünde yapmak istediğimiz, yada bulmak istediğimiz, şey hep aynı: istediğimizi yapabilecek bir fonksiyon.

Mesela, ben "Makine Öğrenimi Mühendisi (Machine Learning Engineer)" olarak çalışıyorum. İşimin büyük bir kısmı fotoğraflarla uğraşmakla geçiyor. Yaptığım işlerden bir tanesi mesela, verilen fotoğrafların içindeki nesneleri bulmak. Diyelimki, verilen bir fotoğrafın içindeki atların yerini bulmak istiyoruz. Yani yapmak istediğimiz şey aslında:

# Put here horse example image

Peki bunu nasıl yapacağız? Bu işlem size biraz tanıdık geldi mi? Bide şu şekilde bakın:

# Put here horse example with input/output

Ihtiyaçımız olan şey,  içine bir at resmi konulduğu zaman, resimdeki her bir at için bize atı çevreleyen dikdörtgenin koordinatlarını çıkartan bir fonksiyon. Bu fonksiyonu bulmaya çalışmak benim günlük olarak yaptığım işlerden bir tanesi. Bu blogda bu konularıda göreceğiz, ve şu anda bu konular için temel oluşturuyoruz. 

Eveeet, giriş yazısı için bu kadar konuşmak yeter. Son olarak, bu bölümde göreceğimiz konuların başlıklarına bakalım:

# Konu basliklarini koy buraya