# deteksi_pertanyaan_by_me

DETEKSI PERTANYAAN

dengan 4 fungsi
1) menghapus spasi setiap item atau elemen yang terdapat didalam variabel list kata_tanya
   contoh:
   kata_tanya = ["begitu kah", "siapa"]
   akan menjadi => ['begitukah', 'siapa']

2) mengecek pertanyaan apakah di ujung kalimat ada simbol tanda tanya
   contoh-1
   kalimat : apakah itu
   kesimpulan : kalimat tersebut bukan pertanyaan

   contoh-2
   kalimat : apakah itu ?
   kesimpulan : kalimat tersebut merupakan pertanyaan

3) mengecek kata tanya pada awal kalimat

4) mencari dan menggabungkan 2 atau lebih kata yang terdapat pada list kata_tanya menjadi 1 kata
   contoh-1
   begitu kah => begitukah

5) menggabungkan 2 kalimat 

6) membuat inputan kalimat-1 dan kalimat-2 menjadi lowercase
   
