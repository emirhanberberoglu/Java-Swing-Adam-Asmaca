# 🎮 Java Swing Adam Asmaca (Hangman) Oyunu

Bu proje, Java ve Swing arayüz kütüphanesi kullanılarak geliştirilmiş, gelişmiş dosya ve log yönetimi içeren kapsamlı bir Adam Asmaca oyunudur. Kullanıcı dostu arayüzü ve güvenlik önlemleriyle klasik bir oyunu modern bir masaüstü uygulamasına dönüştürür.

## 🚀 Özellikler

* **Güvenli Giriş Sistemi:** Oyuna erişim, şifreli bir giriş ekranı ile sağlanır. 3 hatalı girişte sistem kendini kilitler.
* **Dinamik Oyun Motoru:** Kelimeler `.txt` dosyasından rastgele çekilir ve arayüze dinamik olarak yansıtılır.
* **Zamanlayıcı (Timer):** Oyun süresi saniye cinsinden anlık olarak takip edilir.
* **Loglama Sistemi:** Başarılı girişler, hatalı denemeler ve şifre belirleme işlemleri zaman damgasıyla (tarih/saat) birlikte `log.txt` dosyasına kaydedilir.
* **Skor Tablosu:** Oynanan oyunların sonuçları (Kazanma/Kaybetme durumu ve süre) anında tabloya (JTable) aktarılır.
* **Şifreli Veri Temizliği:** Skor ve Log tablolarını temizlemek için ana şifrenin girilmesi zorunludur.

## 🛠️ Kullanılan Teknolojiler

* **Dil:** Java (JDK 11+)
* **Arayüz (GUI):** Java Swing (JFrame, JPanel, JTabbedPane, JTable)
* **Dosya Yönetimi:** `java.io.File`, `FileWriter`, `BufferedReader`, `Scanner`
* **Geliştirme Ortamı:** Apache NetBeans IDE

## 📸 Ekran Görüntüleri

*Giriş Ekranı, Oyun Ekranı ve Log/Skor Tablolarının resimlerini buraya sürükleyip bırakabilirsiniz.*

## ⚙️ Kurulum ve Çalıştırma

Projeyi kendi bilgisayarınızda sorunsuz çalıştırmak için aşağıdaki dizin yapısının **kesinlikle** C diskinde oluşturulması gerekmektedir:

1. Yerel Disk (C:) içerisinde `P2Oyun` adında bir klasör oluşturun.
2. Bu klasörün içine `Resimler` ve `TXTDosyalar` adında iki alt klasör açın.
3. Adam asmaca resimlerini (1.jpg, 2.jpg ... 11.jpg) `Resimler` klasörüne atın.
4. `kelimeler.txt`, `log.txt`, `oyunlar.txt` ve `sifre.txt` dosyalarını `TXTDosyalar` klasörüne yerleştirin.
