# 4week Ürün Üretim Programı

Bu proje, telefon ve laptop üretimi için basit bir konsol uygulamasıdır.  
Kullanıcıdan ürün türü seçimi yapması istenir, ardından ilgili ürün bilgileri alınır ve ekrana yazdırılır.

## Özellikler

- Telefon ve laptop için ayrı üretim süreçleri  
- 5 haneli seri numarası doğrulaması  
- Ürün bilgileri: isim, açıklama, işletim sistemi ve lisans bilgileri  
- Laptop için USB sayısı (2 veya 4) ve Bluetooth bilgisi  
- Kullanıcı isterse yeni ürün üretimine devam eder veya programdan çıkabilir  

## Kullanılan Yapılar

- `BaseMakine` abstract sınıfı ile ortak özellikler ve metodlar  
- `Telephone` ve `Laptop` sınıfları ile ürün çeşitlendirmesi  
- `ILisance`, `IUsb` ve `Ibluetooth` interface'leri ile ek özelliklerin tanımlanması  

## Kullanım

1. Program çalıştırılır.  
2. Telefon (1) veya Laptop (2) seçilir.  
3. Ürün bilgileri istenir (isim, seri numarası, açıklama, işletim sistemi, vb.)  
4. Ürün oluşturulur ve bilgileri gösterilir.  
5. Kullanıcı isterse yeni ürün üretimine devam eder veya program kapanır.

---
