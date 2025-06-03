# GitHub Pages Yayınlama Adımları

## 1. GitHub Hesabı Oluşturma (Zaten varsa atlayın)
1. [github.com](https://github.com) adresine gidin
2. "Sign up" butonuna tıklayın
3. Kullanıcı adı, e-posta ve şifre belirleyin

## 2. Repository'yi GitHub'a Yükleme

### Komut Satırı Yöntemi:
```bash
# 1. GitHub'da yeni repository oluşturun (privacy-policy adında)
# 2. Aşağıdaki komutları sırayla çalıştırın:

git init
git add .
git commit -m "Add privacy policy"
git branch -M main
git remote add origin https://github.com/demrdev/privacy-policy.git
git push -u origin main
```

### GitHub Desktop Yöntemi:
1. [GitHub Desktop](https://desktop.github.com/) uygulamasını indirin
2. File > Add Local Repository
3. Bu klasörü seçin
4. Publish repository butonuna tıklayın

## 3. GitHub Pages'i Aktifleştirme
1. GitHub'da repository sayfanıza gidin
2. Settings (Ayarlar) sekmesine tıklayın
3. Sol menüden "Pages" seçeneğini bulun
4. Source bölümünde:
   - Branch: main
   - Folder: / (root)
5. Save butonuna tıklayın

## 4. URL'nizi Kontrol Etme
Birkaç dakika sonra gizlilik politikanız şu adreste yayınlanacak:
```
https://demrdev.github.io/privacy-policy/
```

## 5. Google Play Store'a Ekleme
1. Google Play Console'a giriş yapın
2. Uygulamanızı seçin
3. App content > Privacy policy bölümüne gidin
4. GitHub Pages URL'nizi yapıştırın
5. Save butonuna tıklayın

## Önemli Notlar:
- GitHub Pages tamamen ücretsizdir
- URL dünya çapında erişilebilir olacaktır
- Otomatik olarak HTTPS kullanır
- Değişiklik yapmak için index.html dosyasını düzenleyip tekrar push edin

## Sorun Giderme:
- Eğer sayfa görünmüyorsa 5-10 dakika bekleyin
- Repository'nin public olduğundan emin olun
- Settings > Pages'de yeşil tik işareti görünmelidir