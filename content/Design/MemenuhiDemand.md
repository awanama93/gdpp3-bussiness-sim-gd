Player character bisa memenuhi [[Demand]] dari [[Customer]]
Tapi player character juga mungkin tidak bisa memenuhi demand dari customer

## Tahap memenuhi demand

Pada [[OperationalDay#Demand phase|Demand phase]] maupun [[OperationalDay#Service phase|Service phase]] player bisa [[MelihatDemand|melihat demand]]
Setelah itu, player character bisa melakukan [[PlayerCharacterAction#Package related action|Package related action]] untuk membawa [[TetrominoPackage|tetromino package]] dari penyimpanannya ke [[ServiceBay|service bay]]
Lalu, di service bay player bisa [[DemandBoxInteraction|berinteraksi]] dengan [[DemandBox|demand box]]

![[DemandBoxInteraction]]

### Kondisi demand tidak terpenuhi

Player mungkin juga tidak bisa memenuhi demand
Ini bisa terjadi karena faktor [[ServiceTime|service time]] telanjur habis sebelum kriteria pemenuhan demand terpenuhi

### Customer feedback

Baik ketika customer menerima package maupun ketika demand tidak terpenuhi, tahapan akan masuk ke dalam customer feedback

Pada tahap ini dilakukan [[Evaluasi#Evaluasi Service|evaluasi service]]
Lalu, player bisa melihat visual feedback berupa balon kata yang muncul di world space (istilah Unity) dan menunjukkan [[FeedbackEmoji|emoji]] tentang [[Serving performance#Serving performance|serving performance]]

![[FeedbackEmoji]]

Lalu customer itu hilang dari pengelihatan player
