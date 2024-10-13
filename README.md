Bu proje, kamera görüntüleri üzerinde trafik işaretleri ve yol bozulmalarını (çukur vb.) 
tespit eden ve mesafe hesaplayan bir görüntü işleme sistemidir. Bilgisayar kamerası veya 
önceden kaydedilmiş video dosyaları kullanılarak gerçek zamanlı olarak trafik işaretlerinin 
ve yol bozulmalarının tespiti yapılır. Sistem, tespit edilen nesnelerin mesafesini hesaplar 
ve sesli bildirimler sağlar. Ayrıca, tespit edilen trafik işaretlerinin türünü ve mesafesini 
ekranda gösterir.

Proje Özellikleri
*Gerçek zamanlı kamera veya video analizi
*Trafik işareti ve yol bozulması (çukur) tespiti
*Nesnelerin mesafesini hesaplama
*Ekran üzerinde işaret türü ve mesafenin gösterimi
*Sesli bildirim sistemi

Kullanılan Teknolojiler
*OpenCV: Görüntü işleme ve kamera görüntülerinin yakalanması için kullanıldı.
*YOLOv8: Nesne tespiti modeli olarak kullanıldı. Trafik işaretleri ve yol bozulmaları gibi nesneleri yüksek doğrulukla tanır.
*Tkinter: Kullanıcı arayüzü oluşturmak için kullanıldı. Video veya görüntü dosyalarının seçimi ve görüntülenmesi Tkinter ile sağlandı.
*PIL (Python Imaging Library): Görüntüleri işleyip kullanıcı arayüzünde görüntülemek için kullanıldı.
*pyttsx3: Sesli bildirim sistemi için kullanıldı. Tespit edilen nesneler hakkında kullanıcıya sesli bildirim yapılır.
*SpeechRecognition: Sesli komutları algılayarak interaktif bir kullanım deneyimi sağlar.
*Python: Projenin temel programlama dili olarak Python kullanıldı.

YOLOv8 Modelleri
Proje kapsamında iki farklı model kullanılmıştır:

1. Trafik İşareti Tespit Modeli: Trafik işaretlerini tanır ve işaretlerin mesafesini hesaplar.
2. Yol Bozulması (Çukur) Tespit Modeli: Yollardaki bozulmaları ve çukurları tespit eder.
