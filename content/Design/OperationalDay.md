Operational day adalah salah satu tipe [[Day|day]] yang ada dalam game ini

Operational day juga menjadi pengatur progresi dari permainan, yakni:
![[CoreExperience#^goal-block]]

## Day goal

Goal dari tipe day ini adalah

[[MemenuhiDemand|memenuhi demand]] dari semua [[Customer]]  ^goal-operational

## Fase operational day

Suatu operational day terdiri atas beberapa fase, yaitu:

### Supply phase

Supply phase adalah fase pertama dari operational day
Suatu operational day dimulai oleh supply phase
Pada supply phase satu atau lebih [[EntryDoor|entry door]] akan dibuka
Lalu, [[Container|container]] akan terlihat masuk sedikit lewat entry door
Lalu container akan melakukan [[ContainerUnloading|unloading]] [[TetrominoPackage|tetromino package]] yang terlihat seperti dia melontarkan tetromino package tersebut secara bertahap
Supply phase dinyatakan selesai jika unloading selesai dilakukan

### Manage phase

Manage phase adalah fase kedua dari operational day
Pada manage phase [[PlayerCharacter|player character]] diberi [[ManageTime|waktu]] untuk mengatur lokasi [[TetrominoPackage|tetromino package]] sesuai kehendaknya
Setelah waktu tersebut habis, manage phase dinyatakan selesai

### Demand phase

Demand phase adalah fase ketiga dari operational day
Pada awal demand phase [[Customer|customer]] muncul di [[ServiceBay|service bay]] dengan [[Demand|demand]]-nya bersama [[DemandBox|demand box]]-nya setelah sistem [[Customer#Menentukan demand|Menentukan demand]] untuk setiap customer
Setelah semua customer muncul, lalu player sudah [[MelihatDemand|melihat semua demand]]-nya, maka demand phase dinyatakan selesai

### Service phase

Service phase adalah fase keempat dari operational day
Pada awal service phase hitung mundur [[ServiceTime|service time]] dimulai
Pada fase ini [[PlayerCharacter|player character]] harus memenuhi [[Demand|demand]] dari customer dalam urutan sesuai kehendak player
Selama fase ini berlangsung [[PlayerPerformance|performance]] dari player dinilai dengan mempertimbangkan patience time customer sebagai faktor
Player character bisa saja tidak memenuhi satu atau lebih demand customer
Setelah service time habis, maka service phase dinyatakan selesai

### Evaluate and upgrade phase

Evaluate and upgrade phase adalah fase kelima (fase terakhir) dari operational day

Pada awal fase ini, player bisa melihat [[Evaluasi|evaluasi]] dari [[PlayerPerformance|performance]] player character ^phase-show-evaluate
Setelah player memutuskan untuk selesai melihat informasi itu, player bisa melihat informasi [[MembukaAbility]] yang berisi informasi untuk [[MembukaAbility|membuka ability]] maupun [[MembeliConveyor|membeli conveyor]]
Setelah player memutuskan untuk selesai melihat informasi itu, evaluate and upgrade phase dinyatakan selesai ^772b91

### Next day

Lalu, day bertambah satu hari
Jika [[Day|day]] berikutnya adalah operational day, maka lakukan supply phase untuk day berikutnya dijalankan
Tetapi jika day berikutnya adalah [[ThreatDay|threat day]], maka mulai [[ThreatDay#Alert phase|alert phase]] dari [[ThreatDay#Fase threat day|fase threat day]]
