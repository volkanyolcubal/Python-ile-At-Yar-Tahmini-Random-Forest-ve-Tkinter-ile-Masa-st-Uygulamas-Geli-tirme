Eğitimdir garanti kapsamaz canlı hayvanlar ne yapacağı belli olmaz bu yüzden tutma garantisi asla yoktur
Python ile at yarışı tahmini yapan bir makine öğrenmesi modelinin nasıl oluşturulduğunu gösteriyor! Sadece komut satırı çıktılarıyla sınırlı kalmayıp, programı Tkinter kullanarak şık ve interaktif bir arayüze sahip bir masaüstü uygulamasına dönüştürdüm.

 göreceğiniz gibi, modelimiz geçmiş yarış verilerini kullanarak kazanan atları tahmin ediyor. Ayrıca, tahminleri "Favoriler" ve "Sürprizler" olarak filtreleyebiliyoruz. En önemlisi, modelin tahmin ettiği atların AGF, Ganyan, Jokey ve Kilo gibi kritik bilgilerini de anında görebiliyoruz.

Bu proje, makine öğrenmesinin gerçek dünyada nasıl kullanılabileceğine dair mükemmel bir örnek sunuyor. İşte kodun neler yapabildiği:

Veri Analizi: Geçmiş TJK verilerini işleyerek model için uygun hale getirme.

Makine Öğrenmesi Modeli: Python'ın güçlü kütüphaneleri scikit-learn ve pandas kullanarak Random Forest algoritmasıyla bir tahmin modeli oluşturma.

Grafik Arayüz (GUI): Tkinter ile kullanıcı dostu, pencereli bir uygulama tasarlama.

Akıllı Filtreleme: Kullanıcı tercihlerine göre sonuçları anlık olarak filtreleme.


Kullanılan Kütüphaneler:

pandas: Veri işleme ve analizi için.

scikit-learn: Makine öğrenmesi modeli oluşturmak için.

tkinter: Grafik kullanıcı arayüzü (GUI) geliştirmek için.

joblib: Modeli kaydetmek ve yüklemek için.

os, glob, re, numpy: Diğer temel işlemler için.
