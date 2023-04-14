---
layout: page
title: Turkey Food Passport
description: 
img: assets/img/tfpcover.png
importance: 1
category: projects
---
Ülkemizi ziyarette bulunan turistlerin, ülkemizin coğrafi işaretli, tescilli ürünlerini denemesinin teşvik edilmesi amacıyla bir NFT koleksiyon uygulaması geliştirdim. Yaptığım uygulamada turistler hesap oluşturarak, coğrafi işaretli ürünler denediklerinde uygulamalarındaki cüzdana blok zinciri üzerinde barındırılacak NFT aktarılacaktır. Böylece turistlerin ülkemizin değerlerini ve kültürünü denemesi teşvik edilmiş olacaktır. Ayrıca turistler denedikleri ürünlerin standartlara uygun olup olmadığını kontrol edebilecektir. Telefon ve web uygulamalarını React Native kullanarak geliştirdim. Coğrafi İşaret veri tabanından verilerin çekilmesini ve NFT oluşturulmasını sağlayacak bir sistemi de sunucusuz mimariye uygun olarak geliştirdim. NFT oluşturulmasında kullanılacak akıllı kontratı openzeppelin kütüphanesi kullanarak Solidity dilinde ERC1155 standardına göre geliştirdim ve Blokchain üzerinde yayınladım. 
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/tfpcover.png" title="Uygulamadan Örnek Görseller" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
Türk Patent Coğrafi İşaret veri tabanından elde edilen veriler Github Actions (AWS Lambda servisine benzer) üzerinde barındırılan yazılım ile OpenSea uyumlu metaveri üretilmekte ve Pinata gibi IPFS pinning hizmetine aktarılmakta ya da statik olarak host edilmektedir. Bulunulan şehirdeki coğrafi ürünlerin bilgilerini ve fotoğraflarını listeleyecek API servisi de aynı yolla tasarlanmıştır.
Örnek Şehir API: https://ruzgarerik.com/turkeyfoodpassport/city/sivas.json
Örnek Ürün Metaverisi: https://ruzgarerik.com/turkeyfoodpassport/sivas_koftesi.json
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/tfp1.png" title="Sunucusuz API Çalışma Prensibi" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

Akıllı Kontrat Adresi : https://goerli.etherscan.io/address/0xf8e73f42f02e4a6c430cc3f1284f16747f2dcb35

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/tfparch.png" title="Uygulama Mimarisi" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
Uygulamada Ethereum ağı ile etkileşime girebilmek  için web3.js ve Alchemy API kullandım. Uygulamaya giriş ve kullanıcı oluşturulma işlemlerini Google Firebase kullanarak sağladım.

|     Telefon Uygulamaları Kaynak Kodu    |     https://github.com/RuzgarErik/turkeyfoodpassport-app    |
|-----------------------------------------|-------------------------------------------------------------|
|     API Kaynak Kodları                  |     https://github.com/RuzgarErik/turkeyfoodpassport        |
| Tanıtım Sitesi Kaynak Kodu              | https://github.com/RuzgarErik/yemekpasaportu                |
|     Uygulama Tanıtım Sitesi             |     https://ruzgarerik.com/yemekpasaportu/                  |

