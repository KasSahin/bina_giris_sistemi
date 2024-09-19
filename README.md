# bina_giris_sistemi
 Yüz Tanıma ve Göz Takibi ile Kapı Açma Sistemi
Bu proje, Raspberry Pi kullanarak yüz tanıma ve göz hareketi algılaması ile bir kapı açma sistemini simüle eder. Sistem, bir kamera aracılığıyla alınan görüntüleri işler, kişiyi tanır ve göz durumu ile baş hareketlerini takip ederek kapıyı açar.


Proje Özeti
Kamera: Raspberry Pi'ye bağlı bir kamera kullanılarak gerçek zamanlı görüntü yakalanır.
Yüz Tanıma: Dlib ve face_recognition kütüphaneleri ile yüz algılama ve tanıma yapılır.
Göz Takibi: Yüzdeki göz ve burun landmark'larına bakarak göz mesafeleri hesaplanır.
Kapı Açma Mekanizması: PWM kullanılarak servo motor kontrol edilir ve doğru yüz tanındığında kapı açılır.


Kullanılan Teknolojiler
Python: Ana dil
OpenCV: Görüntü işleme ve video akışı
Dlib: Yüz landmark belirleme
face_recognition: Yüz tanıma
RPi.GPIO: Raspberry Pi'nin GPIO pinlerini kontrol etmek
sklearn: Lineer regresyon modeli ile göz hareketi tahmini


Donanım Gereksinimleri
Raspberry Pi 3/4
Raspberry Pi Kamera Modülü
Servo Motor
Jumper Kablolar
3D baskı kapı açma mekanizması (isteğe bağlı)
Open cv kütüphanesinin doğru bir şekilde kulanılabilmesi için rasbery pi eski sürüm işletim sistemleri ile kulanılması daha verimli bir proje ortaya koyacaktır.
