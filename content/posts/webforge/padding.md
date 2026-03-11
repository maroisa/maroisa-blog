+++ 
draft = false
date = 2025-06-30T00:00:00+00:00
title = "Padding"
tags = ["web", "html", "tutorial"]
weight = 3
ShowPostNavLinks = true
showtoc = true
tocopen = true
+++

Setelah kalian mempelajari margin, seharusnya tidak susah untuk mempelajari padding.
Jika margin berfungsi untuk memberi jarak bagian luar, padding berfungsi untuk memberi jarak bagian dalam atau dari dalam elemen itu sendiri.

### Gambaran

Perhatikan kotak di bawah:
<div style="
    width: 140px;
    height: 140px;
    background-color: rgb(46, 46, 53);
    ">
    ini teks di dalam elemen div
</div>

Teks di dalam elemen terlihat sangat mepet kan? Untuk memberikan jarak di dalam kita bisa berikan padding, dan akan menjadi seperti ini:

<div style="
    width: 140px;
    height: 140px;
    background-color: rgb(46, 46, 53);
    padding: 1rem;
    ">
    ini teks di dalam elemen div
</div>

Lebih nyaman dilihat bukan?

### Cara Menggunakan

Cara menggunakan padding sama persis dengan margin. Jadi ada yang sisi spesifik:

```css
{
    /* Untuk memberi padding pada sisi atas */
    padding-top: UKURAN;

    /* Untuk memberi padding pada sisi kanan */
    padding-right: UKURAN;

    /* Untuk memberi padding pada sisi bawah */
    padding-bottom: UKURAN;

    /* Untuk memberi padding pada sisi kiri */
    padding-left: UKURAN;
}
```

dan yang umum `padding`. Aturan penggunaannya juga persis dengan properti `margin`.
