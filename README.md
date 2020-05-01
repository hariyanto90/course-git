# course-git

## Bekerja pada git master di terminal
- Create New Repository
- Clone/Download pilih SSH 
- Buat Folder Baru $mkdir folder
- Masuk Ke folder dengan $cd namafolder
- lalu paste SSH clone $git clone git@github.com....
- Pastikan anda bekerja di master dengan mengecek posisi $git branch
- Masuk ke folder Repository 
- lihat isi folder dengan $ls -ah 
- edit file dengan $kate README.md (contoh file yang mau di edit)
- Simpan (Save)
- ketik $git status (untuk melihat perubahan, ditandai dengan warna merah
- ketik $git add . (untuk mengupdate file yang sebelumnya di tambahkan/edit
- ketik $git status untuk melihat perubahan, ditandai dengan warna hijau
- file telah tersimpan di lokal 
- lakukan memberi commit dengan perintah $git commit -am'menambahkan detail step by step bekerja pada git master'
- Update file di website/ di server global dengan $git push 
- cek website github 

## Bekerja Pada Branch di Pycharm 
- lihat Issues apa yang mau dikerjakan 
- Clone/Download SSH
- Buka Pycharm lalu pastekan SSH dan clone 
- Pastikan kita selalu mendapatkan update master
- dengan git pull 
- klik master di pojok kanan bawah lalu new branch 
- Buat/Edit file atau program yang ingin ditambahkan
- setelah selesai ctrl + K 
- Periksa kembali baris perbaris program/file 
- isi commit dan commit dan push
- setelah itu singkronkan Branch BUK-1 dengan master 
- BUK-1 di pojok kanan bawah, lalu pilih master dan checkout
- dan pilih kembali branch anda (BUK-1)
- merger

## bekerja pada branch di terminal
- clone/Download
- buat folder 
- lihat file 
- lihat posisi branch
- buat branch $git checkout -b BUK-2
- kirim branch ke server $git push origin BUK-2
- edit file/program yang mau di ubah $kate README.md
- simpan perubahan $git add .
- commit dengan $git commit -am'simpan perubahan di BUK-2
- lalu simpan keserver dengan $git push 
- masuk ke master dengan $git checkout master 
- pastikan posisi branch sekarang
- gabungkan file/ program yang kita buat ke master dengan $git merge BUK-2
- lakukan commit $git commit -am'tambahkan cara delete branch di terminal'
- lalu push atau kirim ke server dengan $git push
- cek website untuk melihat perubahan master

## Hapus branch pada terminal
- masuk ke master dengan $git checkout master
- hapus BUK-3 dengan perintah $git branch -d BUK-3
- hapus BUK-3 di server website $git push origin --delete BUK3
- get push 
