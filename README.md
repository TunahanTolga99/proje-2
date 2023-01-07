# proje-2
proje 2


[16,21,11,8,12,22] -> Merge Sort

Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
Big-O gösterimini yazınız.

[16,21,11,8,12,22] ilk olarak olabildiğince ortadan sıra dizini ikiye ayrılır.
[16,21,11] [8,12,22] daha sonra elemanlar tek kalana kadar ayrılmaya devam edilir.
[16] [21] [11] [8] [12] [22] soldan başlayarak ve aralarında küçükten büyüğe doğru 2 şer gruplar halinde sıralanır.
[16,21] [8,11] [12,22] ilk 2 grup aralarında karşılaştırma yapılarak yeni bir grup oluşturur.
[8,11,16,21] [12,22] sonda kalan grupta dizine sıralanarak eklenir.
[8,11,12,16,21,22]

Big-O :n(logn)
