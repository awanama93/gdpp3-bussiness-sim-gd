Sling cooldown adalah property tentang durasi paling lambat yang dibutuhkan oleh [[ConveyorBelt]] untuk [[PackageThrow|melontarkan package]]

Sling cooldown akan dipengaruhi [[TetrominoPackageProperty#Jumlah part|jumlah part]] dari suatu [[TetrominoPackage]]
Durasi sling cooldown akan semakin singkat jika makin sedikit [[Part]] yang dimiliki oleh suatu package

Satuan dari sling cooldown adalah detik

## Kalkulasi sling cooldown

```text
Real sling cooldown = (jumlah part dari tetromino package / 4) * default sling cooldown
```

Dari sini bisa dilihat bahwa, jika player character menggunakan tetromino dengan 4 part, maka durasinya akan mengikuti durasi default sling cooldown
