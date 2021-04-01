application up and running.

Things you may want to cover:
* Download dan jalakan xampp
* download dan install program rubynya dahulu di rubyinstaller.org (Harus terkoneksi internet)
* buat folder baru sebagai letak aplikasi ruby kita
* cek ruby berjalan atau tidak, ketik di cmd atau di visual studi code via terminal "ruby -v" tanpa tanda petik

# install rails

* gem install rails  <- tunggu sampai selesai

# cloning repository di atas atau bisa anda download juga file zipnya
* cloning repository dengan cara " git clone https://github.com/sayray303/rubydemo.git "

# jika sudah berhasil di download ketikkan perintah di bawah ini
# sebelumnya install aplikasi rmagick versi 7 (windows 10 x64), lalu buka folder installasinya 
* link rmagick
* http://ftp.icm.edu.pl/packages/ImageMagick/binaries/ImageMagick-7.0.10-29-Q16-HDRI-x64-dll.exe
# copykan file berformat "dll" ke dalam folder installasi Ruby/lib

* rake db:create
* gem install rmagick
* bundle install
* bundle update

# untuk menajalankan codenya ketik
* rails s

# buka browser ketik seperti berikut
* localhost:3000

# masuk ke halaman admin
* localhost:3000/admin
# username admin
* user :admin@demo.com
* pass : demo123

# untuk masuk sebagai customer
* user@demo.com
* user123
