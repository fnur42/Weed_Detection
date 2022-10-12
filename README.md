# Weed_Detection
2022 Teknofest'te finalist olan KTUN ARMAS İKA takımının yazılım kaptanlığını yaptım. Takımda görüntü işleme alanında tek başıma çalıştım. 
15 bin yabani ot veri setini kendimiz çektik ve hepsini labelladım.
Real time olarak da bitkinin kameradan anlık tespiti gerçekleşebilmektedir.
Yazdığım kodda darknet kurulumu gerçekleştirip onun üzerinden verileri çektim.
Drive üzerinde obj.data, obj.names, process.py ve training dosyaları bulunmaktadır.
Process.py dosyası ile verilen yüzde kaçının test için yüzde kaçının train için çekileceğini belirledim. Bu şekilde otomatik olarak çekilmesini sağlandı.
obj.names dosyasında etiket ismi bulunmaktadır. obj.data dosyasında ise verilen kaydolacağı gerekli yollar verilmiştir.
Test sonucunda accuracy değeri %90 civarında çıkmıştır.
