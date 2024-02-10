# IoT Projesi: Sıcaklık ve Nem Ölçümü

Bu proje, ESP32 mikrodenetleyici kartını kullanarak DHT11 sensöründen alınan sıcaklık ve nem verilerini Adafruit IO'ya göndermektedir. Bu sayede, nerede olursanız olun, internet bağlantısı olan herhangi bir cihaz üzerinden bu verilere erişebilirsiniz.

## Kullanılan Donanım ve Kütüphaneler

- ESP32 mikrodenetleyici kartı
- DHT11 sıcaklık ve nem sensörü
- WiFi bağlantısı için `WiFi.h`
- MQTT iletişimi için `Adafruit_MQTT` ve `Adafruit_MQTT_Client`
- Sıcaklık ve nem verilerini göndermek için Adafruit IO kullanılmıştır.

## Kurulum

1. Arduino IDE'yi açın ve gerekli kütüphaneleri yükleyin. (WiFi, Adafruit MQTT, SimpleDHT)
2. `main.ino` dosyasını Arduino IDE'de açın.
3. WiFi bağlantı bilgilerinizi (`WLAN_SSID` ve `WLAN_PASS`) ve Adafruit IO bilgilerinizi (`IO_USERNAME` ve `IO_KEY`) güncelleyin.
4. Adafruit IO web arayüzü üzerinden [bu bağlantıya](https://io.adafruit.com/tunahangezer/dashboards/temp-and-humu) tıklayarak sıcaklık ve nem verilerinizi gerçek zamanlı olarak takip edebilirsiniz.

## Nasıl Çalışır?

1. ESP32 cihazınızı bilgisayarınıza USB üzerinden bağlayın.
2. Arduino IDE üzerinden kodu yükleyin ve ESP32'yi başlatın.
3. Adafruit IO web arayüzü üzerinden sıcaklık ve nem verilerinizi takip edin.

## Notlar

- Bu projeyi kişisel Adafruit IO hesabınıza bağlamak için, Adafruit IO web sitesinde bir hesap oluşturmanız gerekmektedir.
