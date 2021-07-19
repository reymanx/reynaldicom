---
title: "Pakai Static Site Generator"
date: 2021-07-14 10:10:0 +0700
toc : true
categories:
  - blog
tags:
  - Jekyll
  - update
---
# Cerita awal
Dari dulu suka gonta ganti blog, sekedar untuk memuaskan penasaran. Udah beberapa tahun pakai php-mysql-apache, biasa hosting di server sendiri. Pernah coba pakai [DigitalOcean](https://digitalocean.com) , pernah pakai server gratisan, pernah nyempil di hosting kantor.

Sekarang mau coba pakai static web. Mirip jaman `Geocities` dulu, statatic web kita bikin dalam bentuk file. Bedanya, dulu pakai `html`, lalu langsung dipublish. Sekarang pakai, misal `Ruby`, lalu ada proses generate yg menggunakan framework, misal `Jekyll`, setelah itu langsung ditampilkan oleh server. Proses menampilkan jadi lebih cepat, karena tidak memerlukan database jadi web kita lebih cepat dikirim ke CDN atau Content Delivery Netwok dimana content kita akan disebar ke berbagai belahan dunia. Saya baru belajar, jadi kalau ada yg salah tolong kasih masukan :) 

# Apa saja yang dipakai.
## Sisi Github / Server
Yang saya gunakan semua "free", dalam artian selama tidak digunakan melewati kapasitas yang diperbolehkan. 
1. [Github Pages](https://github.com) untuk menyimpan file, menampilkan dengan sub-domain milik mereka.
2. [Cloudflare Pages](https://cloudflare.com) untuk menampilkan dengan domain sendiri.
3. [Jekyll](https://jekyllrb.com) Static Site Generator, simple, tidak pakai database. 
## Sisi Desktop/client
Jadi ini semua yang saya pakai. Untuk desktop, saya install:
1. [Ruby for windows](https://rubyinstaller.org/downloads/) untuk menginstall dan mengcompile Jekyll.
2. [Github Desktop](https://desktop.gihub.com) untuk upload(commit) ke Github
3. [Visual Studio](https://visualstudio.com) untuk IDE atau editornya.
4. [Jekyll](https://jekyllrb.com) Di local (komputer sendiri) juga diinstall Jekyll, agar kita bisa cek gimana hasil web yang kita kerjakan sebelum kita upload ke GitHub. Bisa diakses di http://localhost:4000. 
Ya, kurang lebih ini yang saya pakai. Kalau ada masukan bisa langsung email aja, saya belum bisa menambah `comment` jadi belum ada comment disini. :) 
