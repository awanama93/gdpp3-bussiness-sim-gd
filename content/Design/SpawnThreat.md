Berikut adalah urutan yang terjadi ketika sistem melakukan spawn [[Threat]]:
Sistem mengambil nilai [[SpawnQuota]]
Sistem [[SpawnThreat#Pembuatan threat|membuat threat]] sebanyak spawn quota
Sistem memilih satu spawn point dari semua spawn point yang tersedia pada [[ThreatDay]] tersebut secara acak
Sistem melakukan spawn threat pertama, lalu memulai hitung mundur [[SpawnCooldown]] sebagai interval menuju spawn berikutnya
Spawn terus diulang sampai jumlah threat yang di-spawn mencapai spawn quota

## Pembuatan threat

Berikut adalah urutan dalam pembuatan threat:
Sistem menghitung total weight point dari semua [[TetrominoPackage]] yang ada di game space
Kalkulasi nilai distributable point.
Distributable point adalah nilai yang bisa didistribusikan ke seluruh threat yang bisa di-spawn pada threat day tersebut
Kalkulasi nilai distributable point menggunakan spawn quota dan total weight point. Selain itu digunakan nilai variabel yang dinamakan balancing point untuk memastikan agar tetap tersisa tetramino package ketika threat day selesai walaupun player membuat keputusan yang kurang optimal
Balancing point bernilai antara 0.1 - 0.3
Berikut adalah formula nilai distributable point

```text
distributable point = ceil((total weight point * balancing point)/spawn quota)
```

Misalnya, total weight point adalah 80 dan spawn quota adalah 5, maka perhitungannya adalah:

```text
distributable point = ceil((80 * 0.2) / 5)
distributable point = 4
```

Maka, satu threat akan memiliki 4 part sebagai [[DemandList]]pada [[ThreatDemand]]-nya

Sistem menentukan tipe part untuk threat tersebut sebanyak part pada demand listnya
Ulangi proses ini sampai threat dibuat sebanyak spawn quota
