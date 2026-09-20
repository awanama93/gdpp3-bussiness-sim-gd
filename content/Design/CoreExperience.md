## Overview

[[PlayerCharacter]] adalah sebuah robot pesuruh di sebuah [[Prop#Game space layout|warehouse]] penyuplai komponen teknologi​

## Narrative

Informasi narrative dari game ini, [[Narrative|bisa diakses di sini]]

## Gameplay

### Goal

Player akan memenangkan permainan ini jika berhasil mencapai [[Day|day]] terakhir ^goal-block

### Lose

Player akan mengalami game over jika [[PowerPoint|power point]] dari [[TheBox|the box]] mencapai 0 pada [[ThreatDay|threat day]] ^lose-box

Player juga akan mengalami game over jika [[PowerPoint|power point]]-nya mencapai 0 ^lose-playercharacter

Selain itu, Player bisa mendapatkan [[Evaluasi|evaluasi buruk]] jika tidak berhasil memenuhi [[Demand|demand]]

### Warehouse management

Player bisa [[MembawaPackage|membawa]], [[MenumpukPackage|menumpuk]], dan [[MenyimpanPackage|menyimpan]] [[TetrominoPackage|tetromino package]]
Pada setiap awal [[OperationalDay|operational day]] Player akan mendapatkan [[Supply|supply]] tetromino package
Player bisa harus [[MengelolaPenyimpanan|memutuskan pengelolaan]] penyimpanan tetromino package di dalam warehouse
Player harus [[MemenuhiDemand|memenuhi]] [[Demand|demand]] dari [[Customer|customer]] yang didapatkannya pada suatu [[OperationalDay|operational day]]
Terdapat beragam [[TipeDemand|tipe demand]] yang dipenuhi dengan cara yang beragam
Player bisa memanfaatkan [[ConveyorBelt]] untuk memindahkan suatu tetromino package ke lokasi lain
Player bisa [[MembawaConveyor|membawa]] dan [[MenyimpanConveyor|menyimpan]] conveyor belt

### Tetromino

Player bisa [[MemutarPackage|memutar]] tetromino package untuk mengatur penyimpanannya
Posisi dan rotasi tetromino package menentukan pemenuhan sejumlah [[DemandBox|demand box]]
Player bisa [[MemposisikanPackage|memposisisikan]] tetromino package pada [[TetrisDemand|tetris demand]]

### Ability progression

Player bisa mendapatkan [[SatisfactionPoint|satisfaction point]] dari tiap [[MemenuhiDemand|pemenuhan demand]]
Player bisa menggunakan satisfaction point untuk [[MembukaAbility|membuka]] [[Ability|ability]]
maupun [[MembeliConveyor|membeli conveyor]] yang mempermudah pekerjaan
Player bisa membuka ability atau membeli conveyor pada [[OperationalDay#Evaluate and upgrade phase|Evaluate and upgrade phase]]

### Warehouse defense

Suatu [[Day|day]] bisa menjadi [[ThreatDay|threat day]] di mana [[Customer|customer]] menjadi [[Threat|threat]]
Pada threat day customer berlari menuju [[TheBox]]
Jika customer menyentuh power generator maka [[PowerPoint|power point]] akan berkurang
Jika customer menyentuh player character maka [[PowerPoint|power point]] akan berkurang
Untuk [[MengalahkanThreat|mengalahkan threat]] player harus melontarkan tetromino package yang sesuai ke customer dengan cara menyimpan tetromino package pada [[ConveyorBelt]]

## Referensi

### Wilmot Warehouse

Yang diambil dari sini adalah struktur fase gameplay (supply, manage, demand), sistem upgrade, dan struktur game spacenya. Ini digunakan sebagai referensi untuk struktur fase gameplay (operational day), sistem upgrade ability, dan struktur game space

### Tetrix 3D

Yang diambil dari sini adalah interaksi objek tetromino 3D pada suatu space. Ini digunakan sebagai referensi untuk interaksi pada tetris demand

### Librarian Tidy Up the Arcane Library

Yang diambil dari sini adalah mekanik player bisa membawa lebih dari 1 buku dalam satu waktu. Ini digunakan sebagai referensi untuk mekanik memikul lebih dari satu tetromino package dalam satu waktu, dan aspek physics dari object yang perlu disusun oleh player

### Plant versus Zombie

Yang diambil dari sini adalah aspek musuh yang berjalan lurus menuju line of defense player. Ini digunakan sebagai referensi untuk threat day
