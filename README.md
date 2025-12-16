V.1 terjadi kesalahan pada menu login yang tidak bisa melakukan login dikarenakan username yang di masukan pada menu login tidak di integrasikan dengan database
solusi dengan menambahkan where username = '$username'; akan melakukan intergrasi atau menyamakan username yang dimasukan dan username yang di database sama


V.2 bug tidak ada nya akses tiap role atau aktor yang memungkinkan ada limit akses fitur
solusi dengan menambahkan role atau aktor dan juga mengidentifikasi aktor mana yang sedang login agar pada menu dashboard dan menu lain akan menyesuaikan dengan akses limit tiap role atau aktor
