# Biyokimya Metabolizma Testi

Bu proje, metabolizma, glikoliz, TCA döngüsü ve glikojen metabolizması gibi temel biyokimya konularında bilgi seviyesini ölçmek için tasarlanmış interaktif bir test uygulamasıdır. Kullanıcı dostu arayüzü ve anlık geri bildirimleri ile öğrenme sürecini destekler.

## Özellikler

-   **50 Soruluk Kapsamlı Test:** Metabolizmanın farklı alanlarından özenle seçilmiş sorular.
-   **İnteraktif Arayüz:** Anlaşılır ve modern bir tasarım.
-   **Anlık Geri Bildirim:** Her cevaptan sonra doğru/yanlış durumunu ve sorunun detaylı açıklamasını gösterir.
-   **İpucu Sistemi:** Zorlandığınız sorularda size yol gösterecek ipuçları.
-   **Sonuç Ekranı:** Test sonunda başarı yüzdenizi ve puanınızı gösteren detaylı bir özet.
-   **Duyarlı Tasarım:** Mobil, tablet ve masaüstü cihazlarda sorunsuz çalışır.

## Teknolojiler

-   **React 18**
-   **TypeScript**
-   **Vite**
-   **Tailwind CSS**

## Kurulum ve Yerel Geliştirme

Projeyi kendi bilgisayarınızda çalıştırmak için aşağıdaki adımları izleyin:

1.  **Node.js ve npm'in yüklü olduğundan emin olun.**
2.  **Proje bağımlılıklarını yükleyin:**
    ```bash
    npm install
    ```
3.  **Geliştirme sunucusunu başlatın:**
    ```bash
    npm run dev
    ```
    Bu komut, projeyi `http://localhost:5173` gibi bir adreste çalıştıracak ve yaptığınız her değişikliği anında tarayıcıda gösterecektir.

## GitHub Pages ile Yayınlama

Bu proje, `gh-pages` paketi sayesinde tek bir komutla kolayca yayınlanabilir.

1.  **İlk Kurulum (Sadece bir kere):**
    -   GitHub deponuzda `Settings` -> `Pages` sekmesine gidin.
    -   `Build and deployment` altında, `Source` olarak `Deploy from a branch` seçeneğini belirleyin.
    -   Branch olarak **`gh-pages`** dalını ve klasör olarak `/(root)` seçin. `Save` butonuna tıklayın. (Eğer `gh-pages` dalı henüz yoksa, ilk dağıtımdan sonra bu seçenek görünecektir. Önce 2. adımı yapıp sonra buraya dönebilirsiniz).

2.  **Projenizi Yayınlayın veya Güncelleyin:**
    -   Projenizde istediğiniz değişiklikleri yaptıktan sonra, projenizin ana dizininde terminali açın ve aşağıdaki komutu çalıştırın:
        ```bash
        npm run deploy
        ```
    -   Bu komut otomatik olarak:
        -   Projenizi derleyip `dist` klasörünü oluşturacak (`npm run build`).
        -   `dist` klasörünün içeriğini `gh-pages` dalına gönderecek.

    Birkaç dakika içinde web siteniz `package.json` dosyasındaki `homepage` adresinde canlıya alınacaktır!
