//membuat sebuah folder kosong dengan nama dini 
mkdir dini

//berpindah ke directory dini 
cd dini

//membuat folder sekolah
mkdir sekolah

//membuat folder kerja
mkdir kerja

//masuk ke dalam folder sekolah
cd sekolah

//membuat file dengan nama ijazah.txt
touch ijazah.txt

//mengedit isi file ijazah.txt
nano

//tampilkan isi dari file ijazah.txt menggunakan CLI command
nano ijazah.txt

//kemudian membuat 1 file lagi dengan nama portfolio.txt
touch portfolio.txt

//mengedit isi file portfolio.txt
nano

//keluar dari folder sekolah
cd ..

//masuk kedalam folder kerja
cd kerja

//membuat file dengan nama cv.txt
touch cv.txt

//mengedit isi file cv.txt
nano

//tampilkan isi dari file tersebut menggunakan CLI command
nano cv.txt

//keluar dari folder kerja
cd ..

//memindah file portfolio.txt yang awalnya di folder sekolah ke dalam folder kerja
mv sekolah/portfolio.txt kerja/

