# Build Project

1. Öncelikle, projeyi GitHub'dan klonlayın.
2. Proje klasörünün içine girin.
3. İlgili paketleri yükleyin.

```bash
1- git clone https://github.com/diyarcolakk/upenerjiTaskk.git
2- cd upenerjiTaskk
3- npm install
```
# Firebase Configuration
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

# Gereksinimler
```bash
1. Kullanıcı Kimlik Doğrulaması (Authentication)
Firebase Authentication kullanarak, kullanıcıların e-posta ve şifreyle giriş yapmalarını sağladım.
Firebase Authentication projeye dahil edilerek, kullanıcı doğrulama işlemleri kolaylıkla entegre edildi.
Kullanıcı kaydı, giriş işlemleri için gerekli fonksiyonlar oluşturuldu ve ilgili UI bileşenleri
React bileşenleriyle tasarlandı.

2. State Yönetimi (Redux Toolkit)
Redux Toolkit kullanarak , statelerin yönetimi ve işlemlerin yapılabilmesi sağlandı.Kredi kartı
veya Kredi ile ödeme yapıldığında bakiye artışı sağlandı.Kupon oluşturma özelliği eklendi.

3. Yönlendirme (React Router) 
React Router kullanarak , yeni tabloların başka sayfalara yönlendirelerek ekranda render edilmesi sağlandı.

4-Tasarım (Tailwind)
Tailwind.css kullanılarak bazı hazır componentlerin ve tasarımların kullanılması ile uygulama yapısının
responsive olması sağlandı.

5- Veri Depolama (Firebase - LocalStorage)
Herhangi bir veri depolama yöntemi kullanılmadı.
İstenilen analiz dökümanında belli bir şekilde verinin depolanması gerektiği söylenmedi.
Bir initial state içerisinde uygun olan ilk mock değerler tutuldu ve üzerlerinde işlem yapıldı.
Client refreshlenmediği sürece bu verilerin kaybolması oluşturulan projede mümkün değil.
```
