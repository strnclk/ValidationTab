# Quasar Tab Validation

Bu proje, Quasar Framework ve Vue.js kullanılarak oluşturulmuş bir uygulamanın tab yapısında geçiş sırasında validasyon kontrolü gerçekleştirmeyi amaçlamaktadır. Kullanıcıların tablar arasında geçiş yaparken boş alan bırakmamalarını sağlamak için bir uyarı mekanizması geliştirilmiştir.

## Amaç

Uygulama, tab yapısı içerisinde form alanlarının validasyonunu kontrol ederek kullanıcı deneyimini iyileştirmeyi hedefler. Eğer kullanıcı geçiş yapmak istediği tabda gerekli alanları doldurmadıysa, uygulama uyarı verir.

## Teknolojiler

- **Vue.js**
- **Quasar Framework**

## Özellikler

- **Tab Yapısı**: Kullanıcıların tablar arasında geçiş yaparken validasyon kontrolleri.
- **Uyarı Mekanizması**: Boş alan bırakıldığında kullanıcıya uyarı verilmesi sağlandı.
- **Script Setup**: Vue 3'ün `script setup` özelliği kullanılarak bileşen yapısı oluşturuldu.

## Kurulum

Projenizi çalıştırmak için aşağıdaki adımları izleyin:

1. **Vue.js Kurulumu**  
   Vue.js'i kurmak için terminal veya komut istemcisinde şu komutu çalıştırın:
   ```bash
   npm install -g @vue/cli
   ```

2. **Quasar Kurulumu**  
   Quasar Framework'i kurmak için:
   ```bash
   npm install -g @quasar/cli
   ```

3. **Proje Dizini**  
   Proje dizinine gidin:
   ```bash
   cd yourProjectName
   ```

4. **Proje Bağımlılıklarını Yükleyin**  
   Proje bağımlılıklarını yüklemek için aşağıdaki komutu çalıştırın:
   ```bash
   npm install
   ```

5. **Uygulamayı Başlatın**  
   Uygulamayı başlatmak için:
   ```bash
   quasar dev
   ```

## Kullanım

Tab yapısında geçiş yaparken, boş alan bırakıldığında kullanıcıya uyarı verilecektir. Kullanıcı, gerekli alanları doldurduktan sonra tablar arasında geçiş yapabilir.


