# 💻 Git & GitHub Rehberi

Bu rehber, Git ve GitHub'ın temel kullanımını öğrenmek isteyenler için hazırlanmıştır. 🚀  
Versiyon kontrol sistemine giriş, temel komutlar ve GitHub’a proje yükleme adımları bu belgede! 🔧

---

## 🧠 Git Nedir?

Git, projendeki değişiklikleri adım adım takip etmene 📝  
gerektiğinde eski sürümlere dönmene ⏪  
ve ekip arkadaşlarınla düzenli çalışmana olanak sağlayan bir **versiyon kontrol sistemidir**. 🤝

---

## 🌐 GitHub Nedir?

GitHub, Git ile yönetilen projeleri çevrim içi olarak saklamanı ☁️  
paylaşmanı 📤 ve başkalarıyla iş birliği yapmanı 👨‍💻👩‍💻 sağlayan bir platformdur.

---

## 🛠️ Temel Git Komutları

🔹 `git init` → Yeni bir Git projesi başlatır  
🔹 `git clone <url>` → GitHub'daki projeyi yerel bilgisayara indirir  
🔹 `git status` → Dosyaların güncel durumunu gösterir  
🔹 `git add <dosya>` → Belirli dosyayı Git’e ekler  
🔹 `git add .` → Tüm değişiklikleri ekler  
🔹 `git commit -m "açıklama"` → Değişiklikleri açıklama ile kaydeder  
🔹 `git push` → Yerel değişiklikleri GitHub’a gönderir  
🔹 `git pull` → GitHub’daki son değişiklikleri alır  
🔹 `git branch` → Branch listesini gösterir  
🔹 `git checkout -b yeni-branch` → Yeni branch oluşturur ve geçer

---

## 📤 GitHub’a Proje Yükleme Adımları

1️⃣ Terminal veya komut satırı üzerinden proje klasörüne git:  
```bash
cd proje-klasoru
```

2️⃣ Git deposunu başlat:  
```bash
git init
```

3️⃣ Tüm dosyaları Git’e ekle ve ilk commit’i yap:  
```bash
git add .
git commit -m "İlk commit"
```

4️⃣ GitHub’da yeni bir repo oluştur ve uzaktan bağlantıyı ekle:  
```bash
git remote add origin https://github.com/kullaniciadi/repo-adi.git
```

5️⃣ Projeyi GitHub’a gönder:  
```bash
git push -u origin main
```

---

## 🚫 .gitignore Nedir?

`.gitignore`, Git’in takip etmesini istemediğin dosya ve klasörleri belirtmene yarar.  
Bu sayede gizli veya gereksiz dosyalar repoya eklenmez. 🔐

🗂️ Örnek `.gitignore` içeriği:

```
node_modules/
.env
*.log
```

---

## 🧾 Özet

✅ Git ile kodlarının geçmişini tutabilir, her adımı kayıt altına alabilirsin.  
✅ GitHub ile projelerini internette yedekleyebilir ve başkalarıyla paylaşabilirsin.  
✅ Basit komutlarla büyük işler başarabilir, kod yazarken düzenli ve güvenli kalabilirsin!

---
