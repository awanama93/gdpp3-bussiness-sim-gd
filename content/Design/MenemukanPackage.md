Setelah melakukan [[MembukaAbility|pembukaan ability]], player bisa mendapatkan informasi tentang lokasi package yang relevan
Informasi tersebut berwujud [[PackagePlacementPreview|bayangan preview lokasi]] yang bisa terlihat walaupun ada di bawah [[MenumpukPackage|tumpukan package lain]]

Penentuan relevansi package ditentukan dengan tahap berikut:
Player character [[MembawaPackage|membawa package]]
Player mengaktifkan [[Ability|ability]] menemukan package
Sistem melakukan pencarian ke semua package yang ada di game space dengan kriteria berikut:
Jika [[TetrominoPackageProperty#Jumlah part|jumlah part]] dan [[TipePart|tipe part]] sama dengan package yang sedang dibawa, maka package ditemukan
Untuk setiap package yang ditemukan, sistem menghighlightnya dengan wujud [[PackagePlacementPreview|bayangan preview lokasi]] yang bisa terlihat walaupun ada di bawah [[MenumpukPackage|tumpukan package lain]]
Sistem memulai hitung mundur untuk [[HighlightTime|highlight time]]
Selama highlight time > 0, maka bayangan preview lokasi itu akan tetap terlihat oleh player
Jika highlight time <= 0, maka bayangan preview lokasi tidak bisa dilihat oleh player, lalu mulai hitung mundur [[HighlightCooldown|highlight cooldown]]
Highlight cooldown adalah waktu yang dibutuhkan sampai ability ini bisa dilakukan kembali
