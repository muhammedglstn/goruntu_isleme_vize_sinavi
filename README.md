# Görüntü İsleme Vize sınavı
# Ad, Soyad = Muhammed Gülistan
# Okul no = 2023688034

# El Hareketleri ile Ekran Parlaklığı Kontrolü:
Bu proje, kullanıcının el hareketlerini kameradan gerçek zamanlı olarak algılayıp, baş parmak ile işaret parmağı arasındaki mesafeyi ölçerek bu mesafeye bağlı şekilde ekran parlaklığını otomatik olarak ayarlayan bir görüntü işleme uygulamasıdır. El tespiti ve izleme işlemleri Google MediaPipe kütüphanesiyle gerçekleştirilmiştir.

# Proje Özeti:
Uygulama, kullanıcının elini kamera aracılığıyla algılar. Baş parmak (landmark 4) ile işaret parmağı (landmark 8) arasındaki mesafeyi ölçer. Bu mesafe temel alınarak ekran parlaklığı %0 ile %100 arasında dinamik olarak değiştirilir. Aynı zamanda elin hangi elde (sağ/sol) olduğu da ekranda yazı olarak gösterilir.

# Gereksinimler:
Projenin çalışması için aşağıdaki yazılım ve kütüphaneler gereklidir:

Python 3.8 veya üzeri

opencv-python

mediapipe

numpy

screen_brightness_control

Ayrıca MediaPipe tarafından sağlanan el izleme model dosyasına da ihtiyaç vardır:
hand_landmarker.task

# KURULUM:
Python yüklü değilse https://www.python.org/downloads/ adresinden yüklenmelidir.

Gerekli Python kütüphanelerini yüklemek için terminal veya komut istemcisinde aşağıdaki komut çalıştırılır:
pip install opencv-python mediapipe screen-brightness-control numpy

# Uygulama Özellikleri:
Gerçek zamanlı el algılama ve işaretleme

Baş parmak ile işaret parmağı arasındaki mesafenin ölçülmesi

Mesafeye bağlı olarak ekran parlaklığının değiştirilmesi

Elin sağ mı sol mu olduğunun ekranda gösterilmesi

Görüntü üzerine görsel anotasyonlar (çizgiler, daireler, yazılar)
