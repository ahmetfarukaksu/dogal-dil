# Dogal Dil

Bu proje, Flutter kullanılarak geliştirilmiş bir sohbet uygulamasıdır. Kullanıcılar, Dify API'si aracılığıyla bir chatbot ile etkileşime geçebilirler.

## Proje Yapısı

- *lib/main.dart*: Ana uygulama kodu. Flutter uygulamasının başlangıç noktasıdır. MyApp, DifyApiClient, ChatScreen gibi sınıflar burada tanımlanmıştır.
- *pubspec.yaml*: Proje bağımlılıklarını ve yapılandırmasını içerir.
- *android/, **ios/, **web/, **macos/, **linux/, **windows/*: Farklı platformlar için gerekli yapılandırma dosyalarını içerir.

## Kurulum

1. *Flutter SDK'yı Yükleyin*: [Flutter'ın resmi web sitesinden](https://flutter.dev/docs/get-started/install) Flutter SDK'yı indirin ve kurulumu tamamlayın.

2. *Projeyi Klonlayın*: Projeyi yerel makinenize klonlayın.
   bash
   git clone https://github.com/ahmetfarukaksu/dogal-dil.git
   cd dogal-dil
   

3. *Bağımlılıkları Yükleyin*: Proje dizininde aşağıdaki komutu çalıştırarak gerekli bağımlılıkları yükleyin.
   bash
   flutter pub get
   

4. *Uygulamayı Çalıştırın*: Uygulamayı çalıştırmak için aşağıdaki komutu kullanın.
   bash
   flutter run
   flutter run -d chrome
   

## Geliştirme

- *Dify API Anahtarı*: Uygulamanın çalışması için geçerli bir Dify API anahtarı gereklidir. lib/main.dart dosyasında DifyApiClient sınıfında apiKey değişkenini güncelleyin.
- *Endpoint*: Dify API'nin doğru endpoint'ini lib/main.dart dosyasında DifyApiClient sınıfında endpoint değişkenini güncelleyin.

## Katkıda Bulunma

1. Projeyi fork edin.
2. Yeni bir özellik dalı oluşturun (git checkout -b feature/amazing-feature).
3. Değişikliklerinizi commit edin (git commit -m 'Add some amazing feature').
4. Dalınıza push yapın (git push origin feature/amazing-feature).
5. Bir Pull Request açın.

## Lisans

Bu proje MIT lisansı altında lisanslanmıştır. Daha fazla bilgi için LICENSE dosyasına bakın.
