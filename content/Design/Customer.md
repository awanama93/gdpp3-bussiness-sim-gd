Customer adalah nonplayable character yang dimunculkan ketika:

- [[OperationalDay#Demand phase|Demand phase]] pada [[OperationalDay]] di [[ServiceBay]]
- [[ThreatDay#Spawn phase|Spawn phase]] pada [[ThreatDay]] dari salah satu [[EntryDoor]]

## Customer Action

Customer bisa melakukan action berikut:

### Mengajukan demand

Pada [[OperationalDay]] customer bisa mengajukan [[Demand]] yang [[DemandList]]-nya harus [[MemenuhiDemand|dipenuhi]] player

![[MenerimaPackage]]

### Menjadi threat

Pada [[ThreatDay]] customer bisa menjadi [[Threat]] yang berlari menuju [[TheBox]] untuk menghabiskan [[PowerPoint]]-nya

![[MenghancurkanPackage]]

### Mengalahkan player

Sepanjang permainan mungkin saja, ketika [[Customer#Menjadi threat|Menjadi threat]] customer menabrak player character
Jika player character dan threat bertabrakan maka [[PowerPoint]] dari player character berkurang satu, tetapi tidak terjadi apa-apa pada customer

## Customer property

Customer bisa memiliki beberapa property, yaitu:

### Demand

Detail tentang demand bisa dicek pada [[Demand|bagian ini]]

### Menentukan demand

Untuk memastikan agar semua demand yang diajukan customer itu solvable, maka terdapat tahapan berikut untuk menentukan demand dari suatu customer pada suatu operational day:

- Sistem mengaudit semua [[TetrominoPackage|tetromino package]] yang ada di game space
- Sistem melakukan penentuan [[TipeDemand]] untuk 4 customer secara acak dengan ketentuan setidaknya harus ada 1 box demand dan 1 tetris demand, sisanya sepenuhnya acak
  - Untuk setiap [[BoxDemand]], sistem menentukan jumlah tetromino package dan tipe tetromino yang diminta
    - Paling banyak terdapat 4 tetromino package untuk suatu box demand
    - Tipe tetrominonya ditentukan sepenuhnya acak berdasarkan package yang ada di game space
  - Untuk setiap [[TetrisDemand]], sistem memilih satu pattern dari tetris pattern pool, lalu menentukan jumlah tetromino package dan tipe tetromino yang diminta dari situ
    - Suatu pattern pada tetris pattern pool memiliki informasi tentang [[TipePart]] apa yang perlu ada di suatu [[Grid]]. Dari situ bisa dikalkulasikan jumlah dan tipe tetromino yang dibutuhkan untuk demand tersebut
  - Untuk setiap [[ThreatDemand]], sistem menggunakan proses yang sama dengan penentuan demand untuk box demand
- Semua package yang sudah ditentukan untuk suatu demand, dinyatakan tidak akan dipakai untuk demand list untuk demand lain

![[RunSpeed]]
