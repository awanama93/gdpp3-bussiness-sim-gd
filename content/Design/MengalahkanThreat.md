Pada [[ThreatDay]] player bisa mengalahkan [[Threat]] dengan cara melakukan [[PackageThrow]] ke arah threat tersebut

Threat akan kalah jika [[DemandList]] dari [[ThreatDemand]]-nya sudah terpenuhi

Berikut adalah urutannya:

- Player character [[MenaruhPackageDiConveyor|menaruh package di conveyor]]
- [[ConveyorBelt]] melakukan [[PackageThrow|package throw]]
- Package dilontarkan
- Package bertabrakan dengan threat
- Sistem mengevaluasi apakah ada [[Part]] dari [[TetrominoPackage|tetromino package]] tersebut yang [[TipeSesuai|sesuai]] dalam hal [[TipePart|tipe part]] pada  [[DemandList]] dari [[ThreatDemand]]-nya
- Setiap satu part yang sesuai tipenya, akan memenuhi satu part bertipe sama dari threat listnya
- > \[!warning] Perhatian

> misalnya suatu  \[[](DemandList.md)dari \[[](ThreatDemand.md)memiliki lebih dari satu part bertipe sama, maka satu part dari package itu hanya mengurangi satu part tersebut. Dia tidak langsung memenuhi semua part tersebut

- Jika semua part pada [[DemandList]] dari [[ThreatDemand]]-nya sudah terpenuhi, maka threat akan kalah
  - > \[!warning] Perhatian
  > Tidak ada penalti jika package yang dilontarkan memiliki part yang tidak ada pada part dari  [[DemandList]] dari [[ThreatDemand]]-nya
- Jika threat kalah, maka player mendapatkan [[SatisfactionPoint|satisfaction point]]
