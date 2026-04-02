---
title: "Coba Membuat Blog di Varcel Menggunakan Astrojs"
draft: false
date: 2026-03-28T02:12:40+08:00
lang: id
keywords: Astrojs, Hugo, Template, Varcel

image: /images/astro/browser.png

description: "Cara Membuat Blog di Varcel"
---

Platfrom ngeblog tidak hanya blogger dan wordpress melainkan ada beberapa banyak yang lebih instan dan tentu nya open source. 


Apabila menggunakan di blogger hanya itu aja dan tidak bisa open source, hanya dapat mengelola tulisan dan edit template aja, sedangkan dari wordpress kalian harus sewa hosting dan tentu nya harus backup sewaktu - waktu suatu saat blog tersebut kena hack dan lainnya, karena di wordpress self host ini kita di tuntut untuk standbye jika blog kita kena serangan dari hacker. 

Hosting di indonesia sekarang juga mahal - mahal walaupun ada yang murah terkadang hanya dapatkan kapasitas yang dikit. 

Nah karena hal itu saya memilih untuk memindah blog di Astro.js selain mudah di pahami Astro.js ini memiliki banyak sekali keunggunalan. 

## Apa itu Astro.js
{{< images src="/images/astro/astro.png" alt="Astro.js" >}}
Astro JS adalah framework web JavaScript modern yang dirancang khusus untuk membangun situs web berbasis konten yang sangat cepat, seperti blog, portofolio, dan e-commerce. Dengan pendekatan server-first dan arsitektur Island, Astro merender situs menjadi HTML statis ringan, hanya memuat JavaScript untuk komponen interaktif saja, menghasilkan performa SEO yang optimal. 

Berikut adalah poin-poin penting mengenai Astro JS:
1. Arsitektur Pulau (Astro Islands): Teknik ini memisahkan komponen interaktif menjadi "pulau" terisolasi di tengah
2. HTML statis, mengurangi beban JavaScript di browser.
3. Zero JavaScript by Default: Secara otomatis menghapus JavaScript yang tidak digunakan, sehingga situs web memuat lebih cepat.
4. Agnostik Framework: Anda dapat menggunakan komponen dari framework UI populer lainnya seperti React, Vue, Svelte, atau Solid secara bersamaan dalam satu proyek Astro.
5. Fleksibel (SSG/SSR): Meskipun unggul sebagai Static Site
6. Generator (SSG), Astro juga mendukung Server-Side Rendering (SSR) untuk konten yang lebih dinamis.
7. Mudah Dipelajari: Menggunakan sintaks yang mirip HTML, sehingga mudah dipahami oleh developer yang sudah menguasai HTML/CSS. 

Mungkin dari kalian yang mengerti mengenai HTML, CSS dan Javascript mungkin bisa membuat template sesuka hati menggunakan Astro.js ini dengan hosting di Varcel atau Cloudflare, Apa itu Varcel berikut ini penjelasan nya. 

## Apa itu Varcel App
{{< images src="/images/varcel/varcel.png" alt="Varcel Bluid" >}}
Vercel adalah platform cloud terkemuka untuk hosting dan deployment frontend serta aplikasi serverless secara cepat dan efisien. Dirancang untuk pengembang modern, Vercel memungkinkan deploy otomatis langsung dari GitHub/GitLab/Bitbucket, didukung fitur Preview Deployment dan Automatic HTTPS. Vercel juga optimal untuk React, Next.js, dan AI SDK. 

Berikut adalah detail mengenai Vercel App:

1. Hosting Frontend: Menghosting aplikasi web statis dan dinamis (React, Vue, Next.js) dengan performa tinggi.
2. Serverless Functions: Menjalankan kode backend API tanpa harus mengelola server fisik.
3. Proyek AI/Web Modern: Membangun dan men-deploy aplikasi berbasis AI, seperti menggunakan AI SDK.
4. Optimalisasi Gambar: Mengubah ukuran dan mengompresi gambar otomatis untuk mempercepat load times.
5. Preview/Collaborative Deployment: Membuat URL unik untuk setiap branch atau push agar tim dapat meninjau hasil deploy sebelum rilis.

Nah Varcel sendiri sama halnya cloudflare yang mana kalian bisa hosting disana serta bisa mengelola web misal nya menggunakan Astro.js ini untuk Deployment nya bisa di hubungkan di Github. 
