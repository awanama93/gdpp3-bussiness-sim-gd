Container unloading adalah event dalam game ini di mana [[Container]] mengeluarkan [[TetrominoPackage|tetromino package]] berdasarkan [[UnloadingList|unloading list]]

## Unloading property

Proses unloading menggunakan property berikut:

![[UnloadingList]]

### UnloadPackage

Jumlah package adalah property yang menentukan berapa banyak package yang akan di-unload dari container tersebut

## Proses unloading

- Sistem menentukan apa saja package yang available
- Sistem memasukkan informasi package yang available ke dalam unloading list
- Sistem meng-unload package sebanyak nilai pada unload package
  - Setiap kali sistem melakukan unload, sistem memilih secara acak tipe package dari unload list

Selama proses unloading berlangsung, player mendapatkan informasi entry door sebelah mana yang sedang melakukan prosesnya
