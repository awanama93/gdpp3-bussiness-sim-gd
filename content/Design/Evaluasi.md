# Tipe Evaluasi

Terdapat beberapa tipe evaluasi dalam game ini, yakni:

## Evaluasi Service

Setiap kali player [[MemenuhiDemand|memenuhi]] (atau gagal memenuhi) [[Demand]] maka sistem akan mengevaluasi [[PlayerPerformance|player performance]] berdasarkan [[UnwantedPart|unwanted part]] yang ditaruh pada [[DemandBox|demand box]] saat itu terjadi. Lalu, itu dikalkulasikan menjadi [[SatisfactionPoint|satisfaction point]]

### Kalkulasi Satisfaction Point

Berikut adalah formula untuk kalkulasi nilai satisfaction point
(TBD)

![[Serving performance#Serving performance]]

## Evaluasi Day

Pada akhir dari suatu [[Day]] maka sistem akan mengevaluasi [[PlayerPerformance|player performance]] berdasarkan jumlah [[Customer]] yang berhasil [[MemenuhiDemand|dipenuhi demand]]-nya
Kalkulasi ini dilakukan untuk menghasilkan day performance

### Kalkulasi Day Performance

Berikut adalah formula untuk kalkulasi day performance bonus

```text
Day performance = (jumlah serving performance yang setidaknya mid/total jumlah customer) * 10
```

![[PlayerPerformance#Day performance]]
