## Overview

Player adalah sebuah robot pesuruh di sebuah gudang penyuplai komponen teknologi​

## Narrative

Informasi narrative dari game ini, [[Narrative|bisa diakses di sini]]

## Gameplay

### Goal

Pemain akan memenangkan permainan ini jika berhasil mencapai [[OperationalDay|operational day]] terakhir

### Lose

Pemain akan mengalami game over jika [[PowerPoint|power point]] dari [[PowerGenerator|power generator]] mencapai 0 pada [[ThreatDay|threat day]]
Pemain juga akan mengalami game over jika [[power point]]-nya mencapai 0
Selain itu, pemain bisa mendapatkan [[Evaluasi|evaluasi buruk]] jika tidak berhasil memenuhi [[Demand|demand]]

### Warehouse management

Pemain bisa [[MembawaPackage|membawa]], [[MenumpukPackage|menumpuk]], dan [[MenyimpanPackage|menyimpan]] [[TetrominoPackage|tetromino package]]
Pada setiap awal [[OperationalDay|operational day]] pemain akan mendapatkan [[Supply|supply]] tetromino package
Pemain bisa harus [[MengelolaPenyimpanan|memutuskan pengelolaan]] penyimpanan tetromino package di dalam warehouse
Pemain harus memenuhi [[Demand|demand]] dari [[Customer|customer]] yang didapatkannya pada suatu [[OperationalDay|operational day]]
Terdapat beragam [[TipeDemand|tipe demand]] yang dipenuhi dengan cara yang beragam
Pemain bisa dibantu oleh [[SupportBot|support bot]] dalam melakukan aktivitas
Pemain bisa memanfaatkan [[ConveyorBelt|conveyor belt]] untuk memindahkan suatu tetromino package ke lokasi lain
Pemain bisa [[MembawaConveyor|membawa]] dan [[MenyimpanConveyor|menyimpan]] conveyor belt

### Tetromino

Pemain bisa [[MemutarPackage|memutar]] tetromino package untuk mengatur penyimpanannya
Posisi dan rotasi tetromino package menentukan pemenuhan sejumlah [[DemandBox|demand box]]
Pemain bisa [[MemposisikanPackage|memposisisikan]] tetromino package pada [[TetrisDemand|tetris demand]] maupun [[SpatialDemand|spatial demand]]

### Ability progression

Pemain bisa mendapatkan [[SatisfactionPoint|satisfaction point]] dari tiap [[MemenuhiDemand|pemenuhan demand]]
Pemain bisa menggunakan satisfaction point untuk [[MembukaAbility|membuka]] [[Ability|ability]]
maupun [[MembeliConveyor|membeli conveyor]] atau [[MembeliBot|bot]] yang mempermudah pekerjaan
Pemain bisa membuka ability atau membeli conveyor atau bot pada [[OperationalDayPhase|akhir operational day]]

### Warehouse defense

Suatu [[OperationalDay|operational day]] bisa menjadi [[ThreatDay|threat day]] di mana [[Customer|customer]] menjadi [[Threat|threat]]
Pada threat day customer berlari lurus ke arah [[PowerGenerator|power generator]]
Jika customer menyentuh power generator maka [[PowerPoint|power point]] akan berkurang
Jika customer menyentuh player character maka [[PowerPoint|power point]] akan berkurang
Untuk [[MengalahkanThreat|mengalahkan threat]] player harus melontarkan tetromino package yang sesuai ke customer dengan cara menyimpan tetromino package pada [[SlingerConveyor|slinger conveyor]]

## Referensi

### Wilmot Warehouse

Yang diambil dari sini adalah struktur fase gameplay (supply, manage, demand), sistem upgrade, dan struktur game spacenya. Ini digunakan sebagai referensi untuk struktur fase gameplay (operational day), sistem upgrade ability, dan struktur game space

### Tetrix 3D

Yang diambil dari sini adalah interaksi objek tetromino 3D pada suatu space. Ini digunakan sebagai referensi untuk interaksi pada tetris demand dan spatial demand

### Librarian Tidy Up the Arcane Library

Yang diambil dari sini adalah

### Plant versus Zombie

Yang diambil dari sini adalah aspek musuh yang berjalan lurus menuju line of defense player. Ini digunakan sebagai referensi untuk threat day
