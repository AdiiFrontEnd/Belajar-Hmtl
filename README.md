# Belajar-Html



## Note
1. Elemen Di Html Punya Format ```<tag>kontent</tag>```.
- ```<tag>``` Di Sebut Opening Tag Dan ```</tag>``` Di Sebut Closing Tag.
- Elemen Adalah Bagian Dari Html Yang Menyusun,Struktur Dan Konten, Yang Terdiri Dari ```Opening Tag, Isi Dan Closing Tag```.

<br>
<br>

2. Atribut Adalah Kemampuan Yang Menempel Di Elemen Tepat Nya Di Opening Tag Yang Berfungsi Menambahkan Kemampuan Kepada Elemen Mau Itu Wajib Atau Tidak Wajib.
- ```<tag atribut="nilai">isi</tag>```.

<br>
<br>


## Heading
- Heading Adalah Elemen Html Yang Digunakan Untuk Membuat Judul Dan Sub Judul
- Maksud nya Sub Judul Dan Judul Adalah Seperti Ini



<br>
<br>
<br>
<br>

# INI JUDUL ```<h1>```
## INI SUB JUDUL ```<h2>```
### INI SUB JUDUL ```<h3>```
#### INI SUB JUDUL ```<h4>```
##### INI SUB JUDUL ```<h5>```
###### INI SUB JUDUL ```<h6>```
<br>
<br>
<br>
<br>
- Heading Terdiri Dari H1 -> H6 Semakin Besar Angkanya Semakin Kecil Headingnya

<br>
<br>

## Paragraf
- Paragraf Adalah sekumpulan kalimat yang ngebahas satu ide/topik, terus dipisahin dari kumpulan kalimat lain (paragraf lain) pake jarak atau baris baru.
- ```<p>``` Untuk Membuat Sekumpulan Teks Atau Kalimat
- ```<hr>``` Untuk Membuat Garis Pisah
- ```<br>``` Untuk Membuat Baris Baru
- ```<pre>``` Untuk Membuat Paragraf Sama Persis Dengan Apa Yang Dituliskan 
- Misal Kalo :
```
<pre>
Haloo Gak Jelas
ga
        Hai
</pre>
```
<br>
- Maka Outputnya Akan Sama Seperti Ini

<br>

```
Haloo Gak Jelas
ga
        Hai

```

<br>


## Formating
```formatting``` di HTML itu cara lo ngasih "gaya" atau penekanan khusus ke teks, biar teksnya nggak flat-flat aja. Jadi ini beda sama heading atau paragraf yang lebih ke struktur — formatting ini lebih ke "bagian teks ini gw mau bikin beda".

<br>

- Btw Ini Elemen elemen Nya



<br>
 
- ```<b>``` -> Untuk Membuat Teks Berbentuk Bold
- ```<strong>``` -> Untuk Membuat Teks Berbentuk Bold
- ```<small>``` -> Untuk Membuat Teks Berbentuk Kecil
- ```<i>``` -> Untuk Membuat Teks Berbentuk <i>Italic</i>
- ```<em>``` -> Untuk Membuat Teks Berbentuk <i>Italic</i>
- ```<mark>``` -> Untuk Membuat Teks Berbentuk <mark>Marked</mark>
- ```<del>``` -> Untuk Membuat Teks Berbentuk <del>Deleted</del>
- ```<ins>``` -> Untuk Membuat Teks Berbentuk <ins>Inserted</ins>
- ```<sub>``` -> Untuk Membuat Teks Berbentuk <sub>Subscript</sub> Contoh : O<sub>2</sub>

<br>

- ```<sup>``` -> Untuk Membuat Teks Berbentuk <sup>Superscript</sup> Contoh H<sup>2o</sup>

<br>


- ```<del>``` -> Untuk Membuat Teks Berbentuk <del>Deleted</del>


<br>

## Quotation
6. ```Quotation``` = kutipan. Artinya lo ngambil/nyalin ucapan atau tulisan dari sumber lain, terus lo taro di dalam konten lo, biasanya dikasih tanda khusus biar jelas itu bukan kata-kata lo sendiri.

<br>

- Berikut Adalah Elemen Elemenya


<br>

- ``` <blockquote> ``` -> Secara Visual Akan Menambahkan Tab Pada Paragraf Atau pun Heading
- ``` <q> ``` -> Secara Visual Akan Menambahkan Tanda Kutip Pada Teks ```"```
- ``` <abbr> ``` Secara Visual Akan Menambahkan Sebuah Teks Ketika Di Hover
- ```<address> ``` Secara Visual Akan Membuat Font Menjadi Italic<address> Alamat </address>
- ``` <cite>``` Secara Visual Akan Membuat Font Menjadi Italic<cite> Sumber </cite>



## Link
- link Adalah Sebuah Elemen Yang Berisi Url Atau Alamat Atau Resource , Yang Terkandung Dalam Isi ```<a href="#">Isi Ini</a>```

#### Cara Bikinnya 
- ```<a>``` Anchor Sebuah Elemen Yang Bisa Diklik
- ``` href="" ``` Adalah Sebuah Atribut Wajib Isinya Alamat ,Tujuan(Url Atau Path) Ini Bisa Diartikan Sebagai Target Tujuan.


#### Atribut ```href=""``` bisa Mengarahkan Dengan Cara Berikut

#### 1.Link Ke Website Luar (Bukan Local)

```
<a href="https://www.baidu.com">Baidu</a>
```
#### 2.Link Ke Halaman Lain Local

```
<a href="halaman.html">Home</a>
```
#### 3. Link Mengarahkan Ke Bagian Tertentu (Misal ke H1)
```
<a href="#elemen1">Ke Elemen 1</a>


<h1 id="elemen1">Elemen 1</h1>
```

#### 4.Mengarahkan Ke Email, Pake : mailto:

```
<a href="mailto:aini@example.com">Kirim Email</a>
```
#### 5.Mengarahkan Ke No Telp , Pake tel:

```
<a href="tel:+62822167899">No Telp Gw</a>
```

### Atribut Lain Yang Berguna ```Support Atribut ```

#### Target
- Target = "_blank" -> ```Buka Tab Baru```
- Target = "_self" -> ```Buka  Di Tab Yang Sama```
- Target = "_Parent" -> ```Buka Tab Yang Parent```

#### Download
- Bikin Link JAdi Trigger Download Bukan Navigasi Halaman

```
<a href="file.pdf" download>Download Pdf</a>

Or

<a href="file.pdf" download="nama.pdf"> Pdf Donwload </a>
```

## Image 
Image adalah Sebuah elemen Untuk Menampilkan Sebuah Gambar DI Halaman Html

#### Note Img Itu Self Closing Jadi Ga Punya Closing Tag

- img Punya Atribut Wajib Yaitu ```Src=""``` Atau ```Source```
- src Adalah Sebuah Atribut Yang Menyediakan Url Atau Path Tempat Gambar Yang Ingin Ditampilkan

### Cara Memakai Atribut Src Sebagai Berikut

#### 1.Kalo Di Satu Folder Yang Sama

```
<img src="gambar.jpg">
```
#### 2.Kalo Beda Folder 

```
<img src="src/gambar.jpg>
```
#### 3.Ini Dari Website Luar Bukan Local

```
<img src="https://unsplash.com/coder">
```

### Atribut Pendukung Nya Sebagai Berikut
Ada Atribut Pendukung Untuk Membuat elemen Image Mendapat Kemampuan ```Pada Load Imagenya```


- #### Alt = Teks Alternatif Ketika Image Gagal Load




## Favicon
Favicon Adalah Sebuah Icon Kecil Muncul Di Tab Browser . Biasanya  
Logo Mini Situs 

<img src="image.png">

#### Cara Mengisi Favicon Pada Tab Adalah Sebagai Berikut
```
<head>
   <link rel="icon" href="image.png">
</head>
```

## Title 
Tittle Adalah Sebuah Teks Yang Berada Di Samping Ikon Kecil ```Favicon```

#### Cara Membuat 

```
<head>
    <title>Ini Judul</title>
</head>
```




## Table
Table Adalah Sebuah Elemen Untuk Membuat Susunan Informasi Yang Dipisahkan Oleh Baris Dan Kolom

### Referensi :
- ```<table>``` Tag Ini Memberi Tahu pada Html . Bahwa Saya Ingin Membuat Tabel
- ```<tr>``` Tag Ini Untuk Membuat Baris Baru
- ```<th>``` Tag Ini Untuk Header Table Biasanya Seperti Ini (Lebih Tebal)
<img src="image-1.png">
- ```<td>``` Tag Ini Untuk Kolom Table( Biasanya Berisi Data)
- ```<caption>``` Tag Ini Untuk Menambahkan Judul Pada Tabel

Coba Kita Liat Mana Itu Caption

<hr>

<table>

 <caption>Daftar nama Siswa</caption>
  <tr>
    <th>Person 1</th>
    <th>Person 2</th>
    <th>Person 3</th>
  </tr>
  <tr>
    <td>Emil</td>
    <td>Tobias</td>
    <td>Linus</td>
  </tr>
  <tr>
    <td>16</td>
    <td>14</td>
    <td>10</td>
  </tr>
</table>

<hr>
nah Daftar Nama Siswa Adalah Caption. Biasa nya Berada Di Atas

<br>

- ``` <colgrup> ``` adalah elemen HTML untuk mengelompokkan kolom dalam tabel, sehingga Anda bisa menerapkan style atau properti ke beberapa kolom sekaligus tanpa harus ngasih atribut ke setiap sel satu per satu.

#### Pengggambarannya :

<hr>

<table>
  <colgroup>
    <col style="background-color: white">
    <col span="2" style="background-color: white">
  </colgroup>
  <tr>
    <td>Kolom 1</td>
    <td>Kolom 2</td>
    <td>Kolom 3</td>
  </tr>
  <tr>
    <td>Data 1</td>
    <td>Data 2</td>
    <td>Data 3</td>
  </tr>
</table>


<hr>

- ```<col>``` Adalah Sebuah Elemen Untuk Menargetkan Kolom Tabel Mana yang Akan Di Styling. Penargetannya Adalah Dengan Berurutan. col ke 1 Mengatur kolom ke 1, col ke 2 Mengatur kolom Ke 2.
- ```#``` Note Untuk Membuat Tag ```<col>``` Bisa Styling 2 Atau Lebih Kolom Sekaligus Maka Gunakan Atribut 
```
span="(Berapa Banyak tabel yang Mau Di Styling)"
```
<hr>

- Contoh
```span="2"``` Menargetkan 2 Kolom Sekaligus!!

- Nah Tapi Kalo Mau Lebih Terstruktur Dan Jelas Gunakan

1. ```<thead>``` Untuk Membuat Header Table
2. ```<tbody>``` Untuk Membuat Body Table
3. ```<tfoot>``` Untuk Membuat Footer Table

#### Contoh

<table border="1">
  <caption>Daftar Nilai</caption>
  
  <!-- Header Tabel -->
  <thead>
    <tr>
      <th>Nama</th>
      <th>Matematika</th>
      <th>Bahasa Indonesia</th>
    </tr>
  </thead>
  
  <!-- Isi Tabel -->
  <tbody>
    <tr>
      <td>Andi</td>
      <td>85</td>
      <td>90</td>
    </tr>
    <tr>
      <td>Budi</td>
      <td>78</td>
      <td>82</td>
    </tr>
  </tbody>
  
  <!-- Footer Tabel -->
  <tfoot>
    <tr>
      <td>Rata-rata</td>
      <td>81.5</td>
      <td>86</td>
    </tr>
  </tfoot>
</table>

Memang Kelihatan Sama Tapi Ini Lebih Mudah Dimengerti

### Note :
 Jadi Jika Ingin Membuat Lebih Dari 3 Baris Maka Bisa Menggunakan ```<tbody>``` Lebih Dari Satu!!

 ..



<br>
<br>


## Styling Pada Table Menggunakan CSS

last Commit

<!DOCTYPE html>
<html class="scroll-smooth" lang="en">

<head>
    <meta charset="utf-8" />
    <meta content="width=device-width, initial-scale=1.0" name="viewport" />
    <title>DEV.UI | Portfolio</title>
    <script src="https://cdn.tailwindcss.com?plugins=forms,container-queries"></script>
    <link
        href="https://fonts.googleapis.com/css2?family=Syne:wght@700;800&amp;family=Plus+Jakarta+Sans:wght@400;500;600&amp;family=Inter:wght@600&amp;display=swap"
        rel="stylesheet" />
    <link
        href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:wght,FILL@100..700,0..1&amp;display=swap"
        rel="stylesheet" />
    <!-- Tambahkan GSAP & ScrollTrigger -->
    <script src="https://cdnjs.cloudflare.com/ajax/libs/gsap/3.12.2/gsap.min.js"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/gsap/3.12.2/ScrollTrigger.min.js"></script>

    <script id="tailwind-config">
        tailwind.config = {
            darkMode: "class",
            theme: {
                extend: {
                    "colors": {
                        "on-secondary-fixed": "#02006d",
                        "tertiary-container": "#1b1b1b",
                        "surface-container-highest": "#e2e2e2",
                        "surface-dim": "#dadada",
                        "surface-gray": "#F4F4F4",
                        "on-primary-fixed-variant": "#474747",
                        "error-container": "#ffdad6",
                        "surface-container-low": "#f3f3f3",
                        "on-tertiary": "#ffffff",
                        "tertiary-fixed-dim": "#c6c6c6",
                        "on-primary-container": "#848484",
                        "inverse-surface": "#303030",
                        "outline-variant": "#cfc4c5",
                        "vibrant-green": "#28C76F",
                        "electric-blue": "#2E31FF",
                        "primary": "#000000",
                        "secondary-fixed-dim": "#bfc2ff",
                        "surface-container": "#eeeeee",
                        "on-tertiary-fixed": "#1b1b1b",
                        "on-primary": "#ffffff",
                        "on-secondary-container": "#cccdff",
                        "primary-fixed": "#e2e2e2",
                        "on-surface-variant": "#4c4546",
                        "on-tertiary-fixed-variant": "#474747",
                        "secondary-container": "#2f32ff",
                        "surface-container-high": "#e8e8e8",
                        "outline": "#7e7576",
                        "error": "#ba1a1a",
                        "secondary-fixed": "#e0e0ff",
                        "background": "#f9f9f9",
                        "surface-variant": "#e2e2e2",
                        "surface-tint": "#5e5e5e",
                        "on-error": "#ffffff",
                        "tertiary-fixed": "#e2e2e2",
                        "on-tertiary-container": "#848484",
                        "inverse-primary": "#c6c6c6",
                        "surface-bright": "#f9f9f9",
                        "surface": "#f9f9f9",
                        "on-surface": "#1b1b1b",
                        "on-secondary": "#ffffff",
                        "inverse-on-surface": "#f1f1f1",
                        "tertiary": "#000000",
                        "surface-container-lowest": "#ffffff",
                        "on-background": "#1b1b1b",
                        "on-primary-fixed": "#1b1b1b",
                        "charcoal": "#1A1A1A",
                        "on-secondary-fixed-variant": "#0d00ee",
                        "secondary": "#0c00e0",
                        "primary-container": "#1b1b1b",
                        "primary-fixed-dim": "#c6c6c6",
                        "on-error-container": "#93000a"
                    },
                    "borderRadius": {
                        "DEFAULT": "0.125rem",
                        "lg": "0.25rem",
                        "xl": "0.5rem",
                        "full": "0.75rem"
                    },
                    "spacing": {
                        "grid-margin": "2rem",
                        "grid-gutter": "1.5rem",
                        "wild-offset-sm": "-20px",
                        "wild-offset-lg": "-60px",
                        "section-padding": "8rem"
                    },
                    "fontFamily": {
                        "label-caps": ["Inter"],
                        "display-lg-mobile": ["Syne"],
                        "body-lg": ["Plus Jakarta Sans"],
                        "headline-md": ["Syne"],
                        "display-lg": ["Syne"],
                        "display-xl": ["Syne"],
                        "body-md": ["Plus Jakarta Sans"],
                        "display-xl-mobile": ["Syne"]
                    },
                    "fontSize": {
                        "label-caps": ["12px", {
                            "lineHeight": "1.0",
                            "letterSpacing": "0.1em",
                            "fontWeight": "600"
                        }],
                        "display-lg-mobile": ["36px", {
                            "lineHeight": "1.1",
                            "fontWeight": "700"
                        }],
                        "body-lg": ["18px", {
                            "lineHeight": "1.6",
                            "fontWeight": "400"
                        }],
                        "headline-md": ["32px", {
                            "lineHeight": "1.2",
                            "fontWeight": "700"
                        }],
                        "display-lg": ["64px", {
                            "lineHeight": "1.1",
                            "letterSpacing": "-0.02em",
                            "fontWeight": "700"
                        }],
                        "display-xl": ["80px", {
                            "lineHeight": "1.0",
                            "letterSpacing": "-0.04em",
                            "fontWeight": "800"
                        }],
                        "body-md": ["16px", {
                            "lineHeight": "1.5",
                            "fontWeight": "400"
                        }],
                        "display-xl-mobile": ["48px", {
                            "lineHeight": "1.0",
                            "fontWeight": "800"
                        }]
                    }
                },
            },
        }
    </script>
    <style>
        .material-symbols-outlined {
            font-variation-settings: 'FILL' 0, 'wght' 400, 'GRAD' 0, 'opsz' 24;
        }

        .wild-element {
            transition: transform 0.2s cubic-bezier(0.17, 0.67, 0.83, 0.67);
            will-change: transform;
        }

        .hard-shadow {
            box-shadow: 6px 6px 0px 0px rgba(0, 0, 0, 1);
        }

        .hard-shadow-sm {
            box-shadow: 3px 3px 0px 0px rgba(0, 0, 0, 1);
        }

        .hover-hard-shadow:hover {
            box-shadow: 0px 0px 0px 0px rgba(0, 0, 0, 1);
            transform: translate(4px, 4px);
        }

        @keyframes float {
            0% {
                transform: translateY(0px) rotate(0deg);
            }

            50% {
                transform: translateY(-20px) rotate(2deg);
            }

            100% {
                transform: translateY(0px) rotate(0deg);
            }
        }

        .animate-float {
            animation: float 6s ease-in-out infinite;
        }

        .stamp-rotate {
            animation: spin 12s linear infinite;
        }

        @keyframes spin {
            from {
                transform: rotate(0deg);
            }

            to {
                transform: rotate(360deg);
            }
        }

        /* CSS Tambahan untuk Overlapping Section */
        .stack-section {
            position: relative;
            z-index: 1;
        }
    </style>
</head>

<body class="bg-background text-on-background selection:bg-electric-blue selection:text-white overflow-x-hidden">
    <!-- TopNavBar -->
    <nav
        class="sticky top-0 w-full z-50 bg-surface/80 backdrop-blur-md border-b border-charcoal/10 flex justify-between items-center px-grid-margin py-4 max-w-full mx-auto">
        <div class="font-display-lg text-headline-md tracking-tighter text-primary">DEV.UI</div>
        <div class="hidden md:flex items-center gap-8">
            <a class="font-label-caps text-label-caps text-on-surface-variant hover:text-electric-blue transition-colors"
                href="#work">Work</a>
            <a class="font-label-caps text-label-caps text-on-surface-variant hover:text-electric-blue transition-colors"
                href="#skills">Skills</a>
            <a class="font-label-caps text-label-caps text-on-surface-variant hover:text-electric-blue transition-colors"
                href="#about">About</a>
            <a class="font-label-caps text-label-caps text-on-surface-variant hover:text-electric-blue transition-colors"
                href="#contact">Contact</a>
        </div>
        <div class="flex items-center gap-4">
            <button
                class="material-symbols-outlined text-primary scale-95 active:scale-90 transition-transform">terminal</button>
            <button
                class="bg-primary text-on-primary font-label-caps text-label-caps px-6 py-2 hover:bg-electric-blue transition-all duration-300 scale-95 active:scale-90">Hire
                Me</button>
        </div>
    </nav>

    <main class="relative">
        <!-- Hero Section -->
        <section class="stack-section relative min-h-[90vh] flex items-center px-grid-margin pt-20 bg-background">
            <div class="absolute inset-0 grid grid-cols-12 gap-grid-gutter opacity-[0.03] pointer-events-none">
                <div class="border-r border-charcoal h-full"></div>
                <div class="border-r border-charcoal h-full"></div>
                <div class="border-r border-charcoal h-full"></div>
                <div class="border-r border-charcoal h-full"></div>
                <div class="border-r border-charcoal h-full"></div>
                <div class="border-r border-charcoal h-full"></div>
                <div class="border-r border-charcoal h-full"></div>
                <div class="border-r border-charcoal h-full"></div>
                <div class="border-r border-charcoal h-full"></div>
                <div class="border-r border-charcoal h-full"></div>
                <div class="border-r border-charcoal h-full"></div>
                <div class="border-r border-charcoal h-full"></div>
            </div>
            <div class="z-10 w-full max-w-7xl mx-auto grid grid-cols-12 gap-grid-gutter relative">
                <div class="col-span-12 md:col-span-10">
                    <h1
                        class="font-display-xl-mobile md:font-display-xl text-display-xl-mobile md:text-display-xl leading-none">
                        JUNIOR <span class="text-electric-blue">DEVELOPER.</span><br />
                        CODED WITH <span class="text-vibrant-green italic">CHAOS.</span>
                    </h1>
                </div>
                <div
                    class="absolute -top-12 -left-12 md:-left-24 animate-float wild-element pointer-events-none hidden md:block">
                    <img class="w-48 h-48 object-contain"
                        src="https://lh3.googleusercontent.com/aida-public/AB6AXuDJFivjtW838rWYAZYoyOhgibPmf7YvRYu4efLHzP55pgyWUdyS-ZdOuD1kjgTa5Ykyt_mTwC7hLXAaH5ASronLNpkLCGS7AT7qNvmzD2ZOuz2ERVhSIS4lBDm2O4l1oPEjkjm637IufevzWfyACHM8FoqkVjpVxN82Aj60eXEFSbxtaWWzp9s7Tk1TRv4gJssa8_NZDqdNRLWg56FS849Sv7X9UR6ccc161javBYIGL4lpF9iHCGhTYw" />
                </div>
                <div class="col-span-12 md:col-span-6 mt-12">
                    <p
                        class="font-body-lg text-body-lg text-on-surface-variant border-l-4 border-electric-blue pl-6 py-2">
                        Breaking standard UI patterns to create digital experiences that feel alive. I specialize in
                        React, Tailwind, and breaking containers.
                    </p>
                </div>
            </div>
            <div class="absolute right-0 bottom-20 md:right-grid-margin animate-float wild-element hidden md:block"
                style="animation-delay: -3s;">
                <img class="w-64 h-64 object-contain"
                    src="https://lh3.googleusercontent.com/aida-public/AB6AXuDKMIBDKcawLpkJ5cZI1mg_yxJOw2aPtwLN5qkRTiyDk-Bgl4Jguc3O2XmfqAlkgvRNQdAeMbO_HNWU0jBnztl0_7_aDJdHyixGobUmQdYvXDHu9XxHSPuCEVkdq-VCvGSUMJFfA2Tw4ar58dS2y1QM65LHsbH-cbttxAh4WL4D1TmRam_GBtftPoGHsk99aXUvihZB9nStGWtS5qnKxphNbmgHseGTMWZOgWnnJHsjYioNnWvJ6V1xsA" />
            </div>
        </section>

        <!-- NEW component: Velocity Scroll Section -->
        <section class="stack-section relative overflow-hidden py-6 bg-charcoal border-y-2 border-primary z-20">
            <div
                class="velocity-container flex whitespace-nowrap text-white font-display-xl text-5xl md:text-7xl tracking-tighter uppercase pointer-events-none select-none">
                <div class="velocity-text flex gap-8 items-center px-4">
                    <span>Coded with Chaos</span> <span class="text-electric-blue">•</span>
                    <span>Break the Containers</span> <span class="text-vibrant-green">•</span>
                    <span>Design Poetry</span> <span class="text-electric-blue">•</span>
                    <span>User Interface Lever</span> <span class="text-vibrant-green">•</span>
                </div>
                <div class="velocity-text flex gap-8 items-center px-4">
                    <span>Coded with Chaos</span> <span class="text-electric-blue">•</span>
                    <span>Break the Containers</span> <span class="text-vibrant-green">•</span>
                    <span>Design Poetry</span> <span class="text-electric-blue">•</span>
                    <span>User Interface Lever</span> <span class="text-vibrant-green">•</span>
                </div>
            </div>
        </section>

        <!-- Work/Projects Section (Overlapping) -->
        <section class="stack-section py-section-padding px-grid-margin bg-background border-t-2 border-charcoal"
            id="work">
            <div class="max-w-7xl mx-auto">
                <div class="flex justify-between items-end mb-20">
                    <h2 class="font-display-lg text-headline-md border-b-4 border-primary pb-2 uppercase">Selected Chaos
                    </h2>
                    <span class="font-label-caps text-label-caps text-on-surface-variant">01 / PROJECTS</span>
                </div>
                <div class="grid grid-cols-1 md:grid-cols-2 gap-16">
                    <!-- Project Card Alpha -->
                    <div class="relative group">
                        <div class="aspect-video bg-charcoal relative overflow-visible border-2 border-charcoal">
                            <img class="w-full h-full object-cover grayscale group-hover:grayscale-0 transition-all duration-500"
                                src="https://lh3.googleusercontent.com/aida-public/AB6AXuBv_Bjsz3_JrZOJLPUuMEJmosuTfi0rA3GOake7BUJYazOuBTbEMNUBRO0TJsC7iRbNU72Bzs0dP4W6NzSoyXR32X8IabSUJKSMnC5F0_deRqunYcWajYT8bSBYbYUnwtD_9d08XZ25dXgBvgYsXjqE_ZPNuE4hz-eDTeofM3w35PPNoZPvyD8sD2b2LHHkCPUWNLrd-58PK9BVGt2JpksNZDcEc7WJ1JnZz7MChiWnVLlwrAdVqJ_Jsw" />
                            <div
                                class="absolute -top-4 -right-4 bg-vibrant-green text-primary font-label-caps text-label-caps px-4 py-2 hard-shadow rotate-3 group-hover:rotate-0 transition-transform">
                                LIVE NOW
                            </div>
                        </div>
                        <div class="mt-8 flex justify-between items-start">
                            <div>
                                <h3 class="font-headline-md text-headline-md">Project Alpha</h3>
                                <p class="font-body-md text-body-md text-on-surface-variant mt-2 max-w-sm">A
                                    high-performance dashboard utilizing real-time WebSockets and chaotic layouts.</p>
                            </div>
                            <button
                                class="material-symbols-outlined text-headline-md hover:text-electric-blue transition-colors">arrow_outward</button>
                        </div>
                    </div>
                    <!-- Project Card Beta -->
                    <div class="relative group md:mt-24">
                        <div class="aspect-video bg-charcoal relative overflow-visible border-2 border-charcoal">
                            <img class="w-full h-full object-cover grayscale group-hover:grayscale-0 transition-all duration-500"
                                src="https://lh3.googleusercontent.com/aida-public/AB6AXuC_cw3kpxo6LjeRthD1qETXoKOtgn2rp1kkvmigtilQFjwKJ0IuQVnn6yYenoa_ucVYYBkeobTykS-f4ThGuPyhtvoeO94ljtk3m248xLvUC66ZyebKtH19JVESpvzUP3EM_CZkzr7f5XZQDcqX9Vwt-eN5KlxCuEDxXasiwu5z11pZOhTCydluOAG0DQrTsA5wHqU-0YhxmRKBHWpsZiVH7h_n7ZsgeJELWQKMUsCdJL-yxhU0GooXbA" />
                            <div
                                class="absolute -bottom-6 -left-6 bg-electric-blue text-white font-label-caps text-label-caps px-4 py-2 hard-shadow -rotate-2 group-hover:rotate-0 transition-transform">
                                OPEN SOURCE
                            </div>
                        </div>
                        <div class="mt-8 flex justify-between items-start">
                            <div>
                                <h3 class="font-headline-md text-headline-md">Project Beta</h3>
                                <p class="font-body-md text-body-md text-on-surface-variant mt-2 max-w-sm">Experimental
                                    typography engine built for creative-first developers.</p>
                            </div>
                            <button
                                class="material-symbols-outlined text-headline-md hover:text-electric-blue transition-colors">arrow_outward</button>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- Skills Section (Overlapping) -->
        <section class="stack-section py-section-padding bg-surface-container-low border-t-2 border-charcoal"
            id="skills">
            <div class="px-grid-margin max-w-7xl mx-auto grid grid-cols-12 gap-grid-gutter relative z-10">
                <div class="col-span-12 md:col-span-4">
                    <h2 class="font-display-lg text-headline-md leading-none mb-8">TECH STACK <span
                            class="block text-electric-blue">LEVERS.</span></h2>
                    <p class="font-body-md text-body-md text-on-surface-variant">Manipulating the DOM with precision and
                        a hint of recklessness. Always building, never settling.</p>
                </div>
                <div class="col-span-12 md:col-span-8 grid grid-cols-2 md:grid-cols-3 gap-4">
                    <div
                        class="bg-surface border border-charcoal/10 p-6 flex flex-col justify-between hover-hard-shadow transition-all group">
                        <span class="material-symbols-outlined text-headline-md text-electric-blue">javascript</span>
                        <span class="font-label-caps text-label-caps mt-8">JAVASCRIPT</span>
                    </div>
                    <div
                        class="bg-surface border border-charcoal/10 p-6 flex flex-col justify-between hover-hard-shadow transition-all group">
                        <span class="material-symbols-outlined text-headline-md text-vibrant-green">terminal</span>
                        <span class="font-label-caps text-label-caps mt-8">REACT.JS</span>
                    </div>
                    <div
                        class="bg-surface border border-charcoal/10 p-6 flex flex-col justify-between hover-hard-shadow transition-all group">
                        <span class="material-symbols-outlined text-headline-md text-primary">grid_view</span>
                        <span class="font-label-caps text-label-caps mt-8">TAILWIND CSS</span>
                    </div>
                    <div
                        class="bg-surface border border-charcoal/10 p-6 flex flex-col justify-between hover-hard-shadow transition-all group">
                        <span class="material-symbols-outlined text-headline-md text-electric-blue">database</span>
                        <span class="font-label-caps text-label-caps mt-8">NODE.JS</span>
                    </div>
                    <div
                        class="bg-surface border border-charcoal/10 p-6 flex flex-col justify-between hover-hard-shadow transition-all group">
                        <span class="material-symbols-outlined text-headline-md text-vibrant-green">cloud</span>
                        <span class="font-label-caps text-label-caps mt-8">NEXT.JS</span>
                    </div>
                    <div
                        class="bg-surface border border-charcoal/10 p-6 flex flex-col justify-between hover-hard-shadow transition-all group">
                        <span class="material-symbols-outlined text-headline-md text-primary">animation</span>
                        <span class="font-label-caps text-label-caps mt-8">THREE.JS</span>
                    </div>
                </div>
                <div class="absolute -right-20 -top-20 animate-float wild-element opacity-20 pointer-events-none">
                    <img class="w-80 h-80 object-contain"
                        src="https://lh3.googleusercontent.com/aida-public/AB6AXuCy7tbTGfm6RqKRRmTd-0IhVjSOH5gtYhpGjO2hcebH59oMyyeWb6-1dgj2DR48f5RJk2SmnHFuRJSBM2749U2AH2wZiBlX1wUx58maO1J1IPCwKiHJZyBspNm79VgqvOhmQyg3lCht6k9VxtfIzzil__bkSlXu1xZQ2xqleJ-GlUAItiS8oEL10TdxZERA5Jn_d0ZN5gSGZB2fanEFBOclSDVfvjI51To5ZuyPmN0FlbR9Et86QHwYRQ" />
                </div>
            </div>
        </section>

        <!-- About Section (Overlapping) -->
        <section class="stack-section py-section-padding bg-background border-t-2 border-charcoal" id="about">
            <div class="max-w-7xl mx-auto grid grid-cols-12 gap-grid-gutter items-center">
                <div class="col-span-12 md:col-span-6 relative">
                    <div class="relative z-10 border-2 border-charcoal hard-shadow">
                        <img class="w-full aspect-square object-cover"
                            src="https://lh3.googleusercontent.com/aida-public/AB6AXuCV0JkvupQTFy0JdCdCyhJw1oQTTNuB4jMp3B3BaXDuDm5TAZEXvzfNSPalgkM8QKlgkNVcRUfIAC-E_qerWr8RBJKB3KkggI7HDI8B7s2Bs7UwiNg0GuwiccAWTexje0VYeLPCFnR3pHYjWnRM4T7hDtdOqSTXAlHdC9GA4dZNG7p0Y4DQK3pYZugLq9POtLo-tM4SN2vd11jpoTJ9y_v4CJoRwHfWISaB_vLh-fH2Ym30u1MHIZzaYQ" />
                    </div>
                    <div class="absolute -bottom-10 -right-10 bg-primary text-on-primary p-8 md:p-12 z-20">
                        <p class="font-display-lg text-headline-md leading-tight">BASED IN<br /><span
                                class="text-vibrant-green">THE CLOUD.</span></p>
                    </div>
                </div>
                <div class="col-span-12 md:col-span-5 md:offset-1 mt-20 md:mt-0">
                    <h2 class="font-headline-md text-display-lg-mobile md:text-headline-md mb-8">BUILDING THE FUTURE,
                        ONE <span class="underline decoration-electric-blue">BUG</span> AT A TIME.</h2>
                    <p class="font-body-lg text-body-lg text-on-surface-variant mb-6">
                        I am a developer who believes that UI shouldn't be boring. My journey started with a fascination
                        for how code can translate complex ideas into visual poetry.
                    </p>
                    <p class="font-body-md text-body-md text-on-surface-variant mb-12">
                        When I'm not coding, I'm exploring the intersection of 3D art and web performance, always
                        looking for the next "Wild Element" to add to my arsenal.
                    </p>
                    <a class="inline-flex items-center gap-4 font-label-caps text-label-caps border-b-2 border-primary pb-2 hover:text-electric-blue hover:border-electric-blue transition-all"
                        href="#">
                        DOWNLOAD MANIFESTO (CV) <span class="material-symbols-outlined">download</span>
                    </a>
                </div>
            </div>
        </section>

        <!-- Contact Section -->
        <section class="stack-section py-section-padding bg-charcoal text-white border-t-2 border-primary z-30"
            id="contact">
            <div class="max-w-7xl mx-auto text-center relative">
                <h2 class="font-display-xl text-display-xl-mobile md:text-display-xl mb-12">WANT TO <span
                        class="text-vibrant-green">COLLABORATE?</span></h2>
                <div class="flex flex-col md:flex-row justify-center gap-8 items-center mb-12">
                    <a class="text-display-lg-mobile md:text-headline-md font-display-lg hover:text-electric-blue transition-colors"
                        href="mailto:hello@dev.ui">hello@dev.ui</a>
                    <div class="h-1 w-20 bg-vibrant-green hidden md:block"></div>
                    <span class="font-body-lg text-body-lg">+1 (555) 000-0000</span>
                </div>
                <div class="grid grid-cols-2 md:grid-cols-4 gap-8 max-w-2xl mx-auto">
                    <a class="border border-white/20 py-4 font-label-caps text-label-caps hover:bg-white hover:text-charcoal transition-all"
                        href="#">GITHUB</a>
                    <a class="border border-white/20 py-4 font-label-caps text-label-caps hover:bg-white hover:text-charcoal transition-all"
                        href="#">LINKEDIN</a>
                    <a class="border border-white/20 py-4 font-label-caps text-label-caps hover:bg-white hover:text-charcoal transition-all"
                        href="#">TWITTER</a>
                    <a class="border border-white/20 py-4 font-label-caps text-label-caps hover:bg-white hover:text-charcoal transition-all"
                        href="#">DRIBBBLE</a>
                </div>
            </div>
        </section>
    </main>

    <!-- Footer -->


    <script>
        // Registrasi ScrollTrigger
        gsap.registerPlugin(ScrollTrigger);

        // 1. ANIMASI VELOCITY SCROLL TEXT
        const velocityContainer = document.querySelector('.velocity-container');
        const velocityTexts = document.querySelectorAll('.velocity-text');

        // Animasi dasar loop text berjalan kekiri
        let loopTween = gsap.to(velocityTexts, {
            xPercent: -100,
            repeat: -1,
            duration: 20,
            ease: "none"
        }).totalProgress(0.5);

        // Deteksi kecepatan scroll untuk mengubah speed teks
        ScrollTrigger.create({
            trigger: "body",
            start: "top top",
            end: "bottom bottom",
            onUpdate: (self) => {
                // Dapatkan velocity/kecepatan scroll saat ini
                let velocity = self.getVelocity();
                let skew = velocity * 0.005;
                let timeScale = Math.abs(velocity * 0.005);

                // Batasi minimal dan maksimal kecepatan teks agar tetap terlihat natural
                timeScale = gsap.utils.clamp(0.5, 6, timeScale);

                // Terapkan efek skew dan akselerasi teks berbasis kecepatan scroll
                gsap.to(loopTween, {
                    timeScale: timeScale,
                    duration: 0.3
                });
                gsap.to(velocityContainer, {
                    skewX: skew,
                    duration: 0.2
                });
            }
        });


        // 2. ANIMASI OVERLAPPING SECTIONS
        const sections = gsap.utils.toArray('.stack-section:not(#contact)');

        sections.forEach((section, i) => {
            ScrollTrigger.create({
                trigger: section,
                start: "top top",
                pin: true, // Pin section saat menyentuh bagian paling atas layar
                pinSpacing: false, // Menghilangkan whitespace di bawah agar section berikutnya menumpuk di atasnya
                scrub: true
            });
        });


        // 3. PARALLAX UNTUK WILD ELEMENTS (Kode Asli yang dioptimasi)
        window.addEventListener('scroll', () => {
            const scrolled = window.pageYOffset;
            const wildElements = document.querySelectorAll('.wild-element');

            wildElements.forEach((el, index) => {
                const speed = 0.05 + (index * 0.02);
                const rotation = scrolled * 0.02;
                el.style.transform =
                    `translateY(${scrolled * speed}px) rotate(${rotation * (index % 2 === 0 ? 1 : -1)}deg)`;
            });
        });

        // 4. INTERAKSI HOVER PROJECT CARD (Kode Asli)
        document.querySelectorAll('.group').forEach(card => {
            card.addEventListener('mousemove', (e) => {
                const badge = card.querySelector('.hard-shadow');
                if (badge) {
                    const rect = card.getBoundingClientRect();
                    const x = (e.clientX - rect.left) / rect.width - 0.5;
                    const y = (e.clientY - rect.top) / rect.height - 0.5;
                    badge.style.transform = `translate(${x * 20}px, ${y * 20}px) rotate(${x * 10}deg)`;
                }
            });
            card.addEventListener('mouseleave', () => {
                const badge = card.querySelector('.hard-shadow');
                if (badge) badge.style.transform = '';
            });
        });
    </script>
</body>

</html>





