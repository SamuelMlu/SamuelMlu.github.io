---
layout: page
title: tugas 3
description: reverse engineering apk
img: assets/img/project/apktool.png
importance: 3
category: work
---

###### 30 September 2022
# Reverse engineering

<pre >

</pre >

##### Melakukan reverse engineering menggunakan apktool.
 <a href="https://github.com/iBotPeaches/Apktool" target="_blank">apktool</a> adalah alat untuk melakukan reverse engineering. Menggunakan apktool, kita dapat melihat source code pada file apk.


<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/project/projek3.0.PNG" title="reverse pada wa.apk" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/project/projek3.1.PNG" title="reverse pada twitter.apk" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/project/projek3.2.PNG" title="reverse pada youtube.apk" class="img-fluid rounded z-depth-1" %}
    </div>
</div>


<div class="caption">
    apktool d namafile.apk
</div>


##### Perbedaan hasil reverse engineering

<pre >

</pre >

###### <b>whatsapp</b>
Whatsapp merupakan aplikasi native. Dukungan hardware diperlukan agar whatsap dapat berjalan dengan baik. Hardware yang dibutuhkan dalam menjalankan whatapp antara lain, penggunaan bluetooth, gps, camera, nfc, dll.
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/project/folder_wa.PNG" title="folder wa.apk menggunakan apktool" class="img-fluid rounded z-depth-1" %}
    </div>

     <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/project/uses-feature_androidhardware_wa.PNG" title="folder wa.apk menggunakan apktool" class="img-fluid rounded z-depth-1" %}
    </div>

 </div>

###### youtube
Youtue merupakan aplikasi web.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
         {% include figure.html path="assets/img/project/folder_youtube.PNG" title="folder youtube.apk menggunakan apktool" class="img-fluid rounded z-depth-1" %}
     </div>

     <div class="col-sm mt-3 mt-md-0">
         {% include figure.html path="assets/img/project/uses-feature_androidhardware_youtube.PNG" title="folder youtube.apk menggunakan apktool" class="img-fluid rounded z-depth-1" %}
    </div>
 </div>

###### twitter
Twitter merupakan aplikasi hybrid (gabungan aplikasi native dan aplikasi web).

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/project/folder_twitter.PNG" title="folder twitter.apk menggunakan apktool" class="img-fluid rounded z-depth-1" %}
     </div>

     <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/project/uses-feature_androidhardware_twitter.PNG" title="folder twitter.apk menggunakan apktool" class="img-fluid rounded z-depth-1" %}
     </div>
</div>