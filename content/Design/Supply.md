Supply adalah event di dalam game di mana [[Container]] melakukan [[ContainerUnloading|unloading]] [[TetrominoPackage|tetromino package]] melalui satu [[EntryDoor|entry door]]

## Supply property

Supply bisa menggunakan property berikut

### Door Count

Door count adalah property tentang berapa [[EntryDoor|entry door]] yang digunakan dalam proses supply pada [[Day]] tersebut

### Door ID

Door ID adalah property tentang entry door mana saja yang digunakan dalam proses supply pada [[Day]] tersebut

## Proses supply

- Sistem menentukan berapa banyak entry door yang akan digunakan pada day tersebut
- Sistem menentukan entry door mana saja yang akan digunakan pada day tersebut
- Sistem menjalankan proses [[ContainerUnloading|unloading]] pada suatu entry door
  - Jika terdapat lebih dari satu entry door yang digunakan, maka lakukan proses unloading secara bertahap (tidak bersamaan)
