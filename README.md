## Domain web local 
### Setting domain untuk intranet dengan mikrotik
Web local  biasanya di gunakan untuk membantu mempermudah akses ke suatu sistem informasi atau website lokal dalam intranet misal ada sistem informasi  pemerintahan dimana dalam instansi tersebut terdapat banyak server sistem informasi, Domain local digunakan untuk mempermudah akses ke server, tidak perlu repot menghafal atau bookmark ip server cukup dengan menggunakan domain local intranet.

### DNS Static Mikrotik
Untuk membuat local domain kita bisa menggunakan fitur DNS Static dalam mikrotik router os , dimana mikrotik akan di fungsikan juga sebagai dns server dan akan menerjemahkan request dns ke alamat ip sesuai dengan yang kita setting di DNS Static. Misal contoh saya ingin mengarahkan atau menerjemahkan domain untuk sistem informasi Laporan Bulanan web desa domainnya : sajiramekar.desa.id, disini domain bisa sesuai dengan selera atau kreasi kita sendiri.

![sameknet](https://1.bp.blogspot.com/-4yuFwT2y2LA/WhPQWDZxmeI/AAAAAAAAA9s/2eyEp1j6puElau6Agz-rz7tW_fU_qbmnwCLcBGAs/s1600/sameknet.png)

"Penulisan domain di akhiri titik dibelakang". Setingan ini hanyalah untuk lebih mengenalkan atau menerjemahkan nama hostname ke IP address.

Banyak domain bisa mengarah ke 1 ip komputer server , dengan catatan setiap domain adalah vhost dari satu server tsb.

Untuk testing domain lokal yang sudah kita buat, langsung saja lakukan ping ke alamat domain .
