# SSD---Anggi-Yulianto

Project ini dibuat guna memenuhi Technical Hands-On Test

Project CMS dengan Portal web spasial menjadi 1 project.
User Akses CMS :
user : administrator
pass : master

Akses portal web spasial :
http://localhost/ssd-anggi-yulianto/api/get_maps. -> untuk peta faskes
http://localhost/ssd-anggi-yulianto/api/get_maps2 -> untuk peta kelurahan
mohon maaf saya belum bisa menggabungkan kedua peta tersebut dengan basemap yang sama.

untuk mengecek Api peta kelurahan aktif atau tidak :
http://localhost/ssd-anggi-yulianto/api/get_kelurahan

untuk mendapatkan token (tested postman):
http://localhost/ssd-anggi-yulianto/api/token
Authorization : Bearer MGU5ODlkNDM1ZDoxZTk0ZTQwNDdiYzFhYTZlN2NhMDc3ZTY1ZmNiNDdhYg==

untuk mendapatkan endpoint API seluruh Faskes:
http://localhost/ssd-anggi-yulianto/api/getfaskes
Authorization : (hasil token diatas)

untuk mendapatkan endpoint API Faskes tertentu: http://localhost/ssd-anggi-yulianto/api/getfaskes 
Authorization : (hasil token diatas)
body :
{
   "nama_faskes":"nama" 
}
