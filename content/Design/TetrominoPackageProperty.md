Suatu [[TetrominoPackage]]bisa memiliki property berikut:

## Jumlah part

Jumlah part adalah property yang menentukan kuantitas part yang membentuk suatu package. Satu package minimal terdiri atas satu [[Part]] sampai maksimal empat part yang dipengaruhi oleh tipe susunannya

![[TipePart]]

## Kombinasi part

Satu package bisa terdiri atas satu part dengan tipe part yang sama atau bisa juga memiliki lebih dari satu tipe part
![[Asset/IMGContohkombinasipart.png|389]]

## Tipe susunan part

Terdapat beberapa tipe susunan part dari suatu tetromino package, yaitu:
![[Asset/IMGTipesusunanpart.png|389]]

### Dotmino

Dot adalah package yang terdiri hanya atas satu part

### Shortmino

Shortmino adalah package yang terdiri atas dua part yang disusun lurus

### Imino

Imino adalah package yang terdiri atas empat part yang disusun lurus memanjang

### Omino

Omino adalah package yang terdiri atas empat part yang disusun seperti kotak besar

### Tmino

Tmino adalah package yang terdiri atas empat part yang disusun seperti huruf T

### Lmino

Lmino adalah package yang terdiri atas empat part yang disusun seperti huruf L

### Jmino

Jmino adalah package yang terdiri atas empat part yang disusun seperti huruf J

### Smino

Smino adalah package yang terdiri atas empat part yang disusun seperti huruf S

### Zmino

Zmino adalah package yang terdiri atas empat part yang disusun seperti huruf  Z

## Weight point

- Weight point adalah property dari package yang digunakan sebagai faktor dalam kalkulasi [[CarryCapacity|carry capacity]]
- Satu [[Part]] bernilai 1 weight point

## Availability

- Availability adalah property dari package yang digunakan untuk menandai apakah package tersebut tersedia untuk dimasukkan ke dalam [[UnloadingList|unloading list]]
- Availability sebuah package ditentukan  [[Day]] saat ini

![[PackagePhysic]]
