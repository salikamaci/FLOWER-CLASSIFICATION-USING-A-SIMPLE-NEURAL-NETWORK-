Doğada gördüğümüz bir çiçeğin, Zambak (veya süsen) bitkisi olduğu biliniyor. Üç farklı
türünden hangisine ait olduğunu bulduran bir algoritmanın yazılması istenmektedir. Elimizde
her bir çiçek türünden 150 örnek üzerinden ölçülerek alınan veriler bulunmaktadır. Her bir
örnek için 4’er adet özellik (çanak yaprak uzunluğu, çanak yaprak genişliği, taç yaprak
uzunluğu, taç yaprak genişliği) ve hangi sınıfta (tür) olduğu bilgisi hazır olarak verilmektedir.
Tablo 3’te 6 tanesine yer verilmiştir. Veriseti: https://archive.ics.uci.edu/ml/machine-learningdatabases/iris/iris.data bağlantısında yer almakta olup projede kullanılacaktır.

Gözetimli Öğrenmede (Supervised Learning), girdilerle beraber, olması gereken çıktı değerleri
(target) verilir / sistem tarafından sağlanır. Ağ eğitilirken yukarıda bağlantısı verilen iris.data
veri setinin kullanılması gerekmektedir. Eğitim setinde her biri
5.1,3.5,1.4,0.2,Iris-setosa
formatında 150 adet veri (bitki örneği) bulunmaktadır. Satırdaki ilk 4 değer, ilgili çiçek
örneğinin öznitelikleri olup ağa girdi olarak verilecek, sondaki değer ise ilgili zambak bitkisinin
türü olup çıktıda yer alacak, target yani beklenen değer olarak kullanılacaktır. 
