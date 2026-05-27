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


<img width="743" height="318" alt="Ekran görüntüsü 2026-05-27 171702" src="https://github.com/user-attachments/assets/37d17bd8-2c25-4274-9484-0df7ca509986" />
<img width="402" height="328" alt="Ekran görüntüsü 2026-05-27 171417" src="https://github.com/user-attachments/assets/bf0a8cf9-b219-4cb9-b1ec-8bb433f26e0b" />
<img width="256" height="150" alt="Ekran görüntüsü 2026-05-27 171900" src="https://github.com/user-attachments/assets/4496691c-3b33-40be-bc9a-d693b5f40fa0" />
<img width="320" height="141" alt="Ekran görüntüsü 2026-05-27 171829" src="https://github.com/user-attachments/assets/75800500-7a03-4c5e-91bd-9eab09653aff" />
<img width="740" height="206" alt="Ekran görüntüsü 2026-05-27 171757" src="https://github.com/user-attachments/assets/a0e1e769-7424-4e51-9097-d346dfff427d" />
<img width="746" height="229" alt="Ekran görüntüsü 2026-05-27 171733" src="https://github.com/user-attachments/assets/23fc9d87-718e-4e9f-8124-094450400e57" />


## ⚙️ Kurulum ve Çalıştırma

Projeyi kendi bilgisayarınızda sorunsuz çalıştırmak için aşağıdaki dizin yapısının **kesinlikle** C diskinde oluşturulması gerekmektedir:

1. Yerel Disk (C:) içerisinde `P2Oyun` adında bir klasör oluşturun.
2. Bu klasörün içine `Resimler` ve `TXTDosyalar` adında iki alt klasör açın.
3. Adam asmaca resimlerini (1.jpg, 2.jpg ... 11.jpg) `Resimler` klasörüne atın.
4. `kelimeler.txt`, `log.txt`, `oyunlar.txt` ve `sifre.txt` dosyalarını `TXTDosyalar` klasörüne yerleştirin.
