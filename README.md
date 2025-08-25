# Picobishi
### (Mitsubishi-PLC-FX1N)
 Raspberry pi Pico PLC Firmware

Bu firmware'i Pico'ya yüklediyseniz, tebrik ederim.. 7$ (+kdv) gibi bir ücret ödeyerek, 10 giriş ve 7 çıkışa sahip bir plc sahibi oldunuz demektir.. Picobishi ile plc dünyasına giriş yapmak çok kolay ve ekonomik olacaktır. Plc işlerine yeni başlayanlar için çok faydalı olacağına inandığım **"Picobishi nası bişi"** konulu yazı dizimin ilk yazısı blog sayfamda yayınlanmıştır.<br>
[erolcum.blogspot.com](https://erolcum.blogspot.com)

### Pico'yu PLC'ye dönüştürme
1. Dosyayı indirin. Bunun için yukarıda bulunan **Firmware.ino.1.08.zip** dosyasına tıklayın. Ardından **View raw** linkine tıklayın.
2. İndirilen zipli dosyayı, bir klasöre açın
3. Pico'nun üstünde bulunan butona basarak, Pico'yu bilgisayara usb kablosu ile bağlayın
4. Parmağınızı 1-2 saniye sonra butondan çekebilirsiniz
5. Pico, flash sürücü moduna geçecektir. Windows gezgini ile RPI klasörünü açın. **uf2** uzantılı dosyayı, mouse ile tutun ve açılan klasöre bırakın

**Önemli Not :** Pico'nun usb soketine bağladığınız kablo sadece şarj kablosu olup içinde data telleri olmayabilir. Bu durumda Pico'ya firmware atamazsınız. Durum böyleyse yeni bir data kablosu bulmanız gerekir.

### Pico'yu formatlama
Bir nedenden Pico'nun kafası karışabiliyor. Fabrika ayarlarına döndürmek veya sıfırlamak için **flash_nuke.uf2** dosyasını RPI klasörüne kopyalayın. Bütün flash hafızası silinecektir.
   
![Picobishi_PLC_Pinout_2023](https://github.com/erolcum/Picobishi/blob/main/my%20files/Pico_PLC_Pinout_2023.png)
 
