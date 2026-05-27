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

* Oyuna Giriş Ekranı
  
<img width="402" height="328" alt="Ekran görüntüsü 2026-05-27 171417" src="https://github.com/user-attachments/assets/78ece4f9-42e1-433e-88cb-2ff23e118132" />

* Oyun Ana Ekranından Oynanış Ve Sekmeler İle İlgili Ekran Görüntüleri

<img width="743" height="318" alt="Ekran görüntüsü 2026-05-27 171702" src="https://github.com/user-attachments/assets/b37cbed8-7e70-49c8-a428-06816f76ad1d" />
<img width="746" height="229" alt="Ekran görüntüsü 2026-05-27 171733" src="https://github.com/user-attachments/assets/4fe04f33-6584-4f46-b6a1-560a774fde38" />
<img width="740" height="206" alt="Ekran görüntüsü 2026-05-27 171757" src="https://github.com/user-attachments/assets/e3e630c8-eb1c-42be-9fc4-35d7f7534fca" />

* Oyun İçi Mesajlar

<img width="320" height="141" alt="Ekran görüntüsü 2026-05-27 171829" src="https://github.com/user-attachments/assets/45ff6eed-f452-4078-b5a7-ca3ba8f965ca" />
<img width="256" height="150" alt="Ekran görüntüsü 2026-05-27 171900" src="https://github.com/user-attachments/assets/1ac3cd2d-2406-4322-9c6a-f8a4b1945230" />









## ⚙️ Kurulum ve Çalıştırma

Projeyi kendi bilgisayarınızda sorunsuz çalıştırmak için aşağıdaki dizin yapısının **kesinlikle** C diskinde oluşturulması gerekmektedir:

1. Yerel Disk (C:) içerisinde `P2Oyun` adında bir klasör oluşturun.
2. Bu klasörün içine `Resimler` ve `TXTDosyalar` adında iki alt klasör açın.
3. Adam asmaca resimlerini (1.jpg, 2.jpg ... 11.jpg) `Resimler` klasörüne atın.
4. `kelimeler.txt`, `log.txt`, `oyunlar.txt` ve `sifre.txt` dosyalarını `TXTDosyalar` klasörüne yerleştirin.
