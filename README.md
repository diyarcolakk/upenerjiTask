# Build Project

1. Öncelikle, projeyi GitHub'dan klonlayın.
2. Proje klasörünün içine girin.
3. İlgili paketleri yükleyin.

```bash
1- git clone https://github.com/diyarcolakk/upenerjiTaskk.git
2- cd upenerjiTaskk
3- npm install
```
# Firebase Configuration
```bash

1.Firebase Console'a gidin.
2.Yeni bir Firebase projesi oluşturun veya mevcut birini kullanın.
3.Firebase Console'da, Authentication bölümüne gidin ve Email/Password sign-in yöntemini etkinleştirin.
4.Firebase Console'da, Project settings (dişli simgesi) bölümüne gidin ve Your apps kısmına kadar aşağı kaydırın.
5.Add app ikonuna (</>) tıklayın ve Web seçeneğini belirleyin.
6.Uygulamayı kaydedin ve bir Firebase yapılandırma nesnesi alacaksınız. Bu yapılandırma nesnesini kopyalayın.
```
# Configuration File

1. Proje dizininde, config.js adında yeni bir dosya oluşturun.
2. Firebase yapılandırma nesnesini config.js dosyasına aşağıdaki gibi yapıştırın:
  ```bash

// Config.js
const firebaseConfig = {
apiKey: "YOUR_API_KEY",
authDomain: "YOUR_AUTH_DOMAIN",
projectId: "YOUR_PROJECT_ID",
storageBucket: "YOUR_STORAGE_BUCKET",
messagingSenderId: "YOUR_MESSAGING_SENDER_ID",
appId: "YOUR_APP_ID",
};
```
# Start Project

Projeyi başlatmak için ;

```bash
npm start
```
