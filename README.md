# Image-Stitching-1.1 Proses-proses Dalam Image Stitching 
 
  Proses image stitching bisa dilihat dalam proses dibawah ini: 
 
 
1.	Input image semua potongan image yang akan dijadikan satu foto diinput ke program atau software.  
2.	Features Extraction gambar yang telah diinput sebelumnya akan ditandai seperti titik-titik. Bagian yang ditandai biasanya bersifat unik dan memiliki kesamaan dengan gambar setelah atau keseluruhan gambar.   
3.	Feature Maching 
Pada area yang telah ditandai akan dibandingkan bagian yang sama. Hal ini bertujuan untuk menemukan tempat gambar yang bisa di “tumpang tindih” dari titik tersebut. 
4.	Model estimation & image warping  proses ini akan memetakan foto-foto yang berhubungan sesuai satu sama lain.  
5.	Image blending setelah pemetaan dan posisi foto yang ingin digabung telah selesai, langkah terakhir adalah penggabungan foto tersebut hingga menjadi foto panorama hasil penggabungan semua input tadi.  
6.	Output image hasilnya akan keluar sebagai foto panorama. 
 
1.2 Instal Packages Yang Akan Digunakan 
Tujuan dari praktikum ini adalah untuk mengetahui cara kerja dari image stitching. Beberapa software telah disiapkan untuk praktikum image stitching seperti VM (Virtual Machine) tipe GUI yaitu ubuntu Desktop lalu install beberapa library python sebagai berikut:  
1.	Menginstal pip3 install imutils 
Untuk menginstal library gunakan perintah di bawah ini. di sini sudah terinstal pada ubuntu desktop 
  
Gambar 2. 1 pip3 install imutils 
2.	Menginstal pip3 install opencv-python 
  
Gambar 2. 2 pip3 install opencv-python 
 
 
 
 
 
 
 
3.	Menginstal pip3 install matplotlib 
  
Gambar 2. 3 Menginstal pip3 install matplotlib 
 
1.3 Eksekusi terhadap image stitching 
1.	Masuk ke dalam direktori yang berisi codingan image sttitching dan di dalamnya terdapat direktory image yang akan di gabungkan 
  
Gambar 3. 1 File dari image stitching 
2.	Image 
 
  
Gambar 3. 2 Panorama gunung 
 
 
 
 
 
3.	codingan python 
  
Gambar 3. 3 Code python image stitching 
4.	Menjalankan code python 
Kemudian lalukan perintah di terminal ubuntu dektop dengan perintah sebagai berikut. 
  
Gambar 3. 4 Perintah untuk menjalankan image stitching 
5.	Output
  
Gambar 3. 5 Hasil output dari image stitching 
 
