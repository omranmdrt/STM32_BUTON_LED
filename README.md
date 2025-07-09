# STM32 Button-LED Control

## Proje Açıklaması

Bu proje, STM32F1 serisi mikrodenetleyici üzerinde bir buton ile bir LED’in kontrol edilmesini sağlar.  
Butona her basıldığında LED’in durumu (açık/kapalı) değişir. Projede buton sinyallerindeki "debouncing" sorunu yazılım ile çözülmüştür.

## Donanım Bağlantıları

- **LED:** PA1 pini  
- **Buton:** PA0 pini  

## Özellikler

- Buton ile LED açma/kapama kontrolü  
- Yazılım tabanlı debouncing uygulaması  

## Kullanılan Teknolojiler

- STM32F103 mikrodenetleyici  
- STM32 HAL kütüphanesi  
- C Programlama dili  

## Proje Yapısı

- `main.c` ve `main.h` dosyalarında uygulama kodları bulunmaktadır.  
- Buton durumu okuma, debouncing kontrolü ve LED durum değişikliği burada yapılmaktadır.

