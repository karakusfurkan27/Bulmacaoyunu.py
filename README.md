### README: Bulmaca Oyunu

#### Açıklama
Bu proje, **Python** programlama dilinde basit bir kelime bulmaca oyunudur. Oyun, karışık bir şekilde verilen harflerden oluşan kelimenin doğru halini tahmin etmeye dayalıdır. Kullanıcı, verilen karışık harflerden kelimeyi çözmeye çalışır.

#### Özellikler
- Rastgele bir kelime seçilir ve harfleri karıştırılır.
- Kullanıcıdan bir tahmin girmesi istenir.
- Kullanıcının tahmini doğruysa tebrik edilir, yanlışsa doğru cevap gösterilir.

#### Gereksinimler
- Python 3.x
- `random` modülü (Python’un yerleşik kütüphaneleri arasında yer alır.)

#### Kullanım
1. Projeyi çalıştırmak için dosyayı bir Python IDE'sinde ya da terminalde çalıştırın.
2. Program başladığında ekranda karışık bir kelime gösterilecektir.
3. Kullanıcıdan bu kelimenin doğru halini tahmin etmesi istenecektir.
4. Tahmininizi yazıp **Enter** tuşuna bastığınızda, doğru olup olmadığı belirtilecektir.

#### Çalıştırma
1. Projeyi çalıştırmak için aşağıdaki adımları izleyin:
   - Terminal veya komut istemcisinde dosya yolunu belirterek programı çalıştırın:
     ```
     python bulmaca_oyunu.py
     ```
   - Alternatif olarak bir Python IDE'sinde çalıştırabilirsiniz.
   
2. Program çalıştığında, ekrana karışık harflerden oluşan bir kelime gelecektir.

#### Örnek Çalıştırma
- Ekranda şu şekilde bir çıktı görebilirsiniz:
  ```
  Bulmaca Oyunu'na Hoş Geldiniz!
  Bu karişik harflerden oluşan kelimeyi çözmeye çalişin: tiayzrloamg
  Kelimeyi tahmin edin: algoritma
  Tebrikler! Doğru tahmin.
  ```

#### Geliştirme Notları
- Kelime listesini genişletmek isterseniz, `kelimeler` adlı listeye yeni kelimeler ekleyebilirsiniz.
- Harfleri karıştırma işlemi için `random.sample` fonksiyonu kullanılmıştır.
- Oyunda daha fazla özellik eklemek için kullanıcı puanı veya deneme hakkı gibi mekanizmalar ekleyebilirsiniz.

#### İletişim
Bu proje hakkında herhangi bir sorunuz ya da öneriniz varsa, iletişime geçmekten çekinmeyin.
