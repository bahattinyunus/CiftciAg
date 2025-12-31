# ÇiftciAg 🌾 – Akıllı Tarım Yönetim Sistemi

<div align="center">
  <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" alt="React" />
  <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white" alt="Node.js" />
  <img src="https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white" alt="MongoDB" />
  <img src="https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white" alt="Express.js" />
</div>

<div align="center">
  <img src="https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript" />
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3" />
  <img src="https://img.shields.io/badge/JWT-000000?style=for-the-badge&logo=JSON%20web%20tokens&logoColor=white" alt="JWT" />
</div>

---

## 🌱 Genel Bakış: Tarımda Dijital Rönesans

**ÇiftciAg**, modern tarımın karşı karşıya olduğu karmaşık zorluklara teknolojik bir yanıt olarak doğmuştur. Küresel gıda güvenliği endişelerinin arttığı ve iklim krizinin tarımsal verimliliği tehdit ettiği bir çağda, yerel çiftçilerimizin elindeki en büyük güç veridir. Bu platform, sadece bir yönetim aracı değil; toprağın dilini dijital ortama tercüme eden bir köprüdür.

Uçtan uca tasarlanan bu ekosistem, geleneksel tarım yöntemlerini modern veri bilimi, IoT entegrasyonları ve bulut tabanlı karar destek sistemleri ile harmanlar. Amacımız, en küçük ölçekli üreticiden en büyük tarım işletmesine kadar herkesin, doğru zamanda doğru kararı vererek hem maliyetlerini düşürmesini hem de doğaya olan etkisini minimize etmesini sağlamaktır.

---

## ✨ Temel Özellikler

### 🌾 Stratejik Tarımsal Yönetim
- **Akıllı Sulama ve Su Yönetimi (Smart Irrigation)**
  - Mikroklimatik veriler ve anlık toprak nemi sensörleri (IoT) ile entegre çalışan algoritmalar sayesinde, bitkinin ihtiyaç duyduğu su miktarını nokta atışı tahmin eder.
  - Meteorolojik tahmin modelleri ile senkronize kalarak gereksiz sulamayı önler, su kaynaklarını korur ve enerji maliyetlerini %30'a varan oranlarda azaltır.

- **Biyolojik Güvenlik ve Ürün Takibi**
  - Görüntü işleme teknolojileri (Computer Vision) destekli modüller ile yapraklar üzerindeki anomalileri tespit eder, hastalık ve zararlı risklerini erkenden raporlar.
  - Ürün yaşam döngüsünü (tohumdan hasada) takip ederek, fenolojik evrelere göre özelleştirilmiş besleme ve bakım tavsiyeleri sunar.

- **Hiper-Yerel Hava Durumu Entegrasyonu**
  - Sadece genel hava tahminlerini değil, çiftliğinizin bulunduğu koordinatlara özel hiper-yerel verileri işler.
  - Don riski, aşırı sıcaklık dalgalanmaları ve fırtına gibi kritik olaylarda anlık "Erken Uyarı Bildirimleri" göndererek mahsul kaybını minimize eder.

### 👥 Sosyo-Ekonomik Kullanıcı Katmanı
- **Rol Tabanlı Dinamik Erişim Kontrolü**
  - **Üretici Paneli:** Operasyonel takvim, harcama analizleri ve üretim verimliliği grafiklerine erişim.
  - **Ziraat Mühendisi Portalı:** Uzaktan danışmanlık, saha analizi ve bilimsel veri yorumlama araçları.
  - **Yönetici Katmanı:** Sistem genelinde veri tutarlılığı, kullanıcı yönetimi ve stratejik raporlama.

- **Kolektif Bilgi ve Uzman Rehberliği**
  - Sürekli güncellenen "Dijital Kütüphane" ile tarımdaki en son teknik gelişmeleri, akademik makaleleri ve başarılı vaka analizlerini kullanıcılarına sunar.
  - Bölgesel topluluk forumları aracılığıyla çiftçiler arasında deneyim aktarımı ve dayanışma ağları oluşturur.

---

## 🚀 Başlarken

### Gereksinimler
- Node.js (v14+)
- MongoDB (v4.4+)
- npm veya yarn
- Git

### Kurulum Adımları

1. Repoyu klonlayın:
```bash
git clone https://github.com/bahattinyunuscetin/CiftciAg.git
cd CiftciAg
Frontend ve backend bağımlılıklarını yükleyin:

bash
Kopyala
Düzenle
# Frontend
cd frontend
npm install

# Backend
cd ../backend
npm install
Ortam değişkenlerini ayarlayın:

bash
Kopyala
Düzenle
# Frontend
cp frontend/.env.example frontend/.env

# Backend
cp backend/.env.example backend/.env
Sunucuları başlatın:

bash
Kopyala
Düzenle
# Backend
cd backend
npm run dev

# Yeni terminalde frontend
cd frontend
npm start
Uygulama:

Frontend: http://localhost:3000

API: http://localhost:5000

🧪 Test Süreci
bash
Kopyala
Düzenle
# Frontend testleri
cd frontend
npm test

# Backend testleri
cd backend
npm test
## 🔒 Güvenlik: Mimari Bütünlük ve Veri Mahremiyeti

ÇiftciAg, kullanıcı verilerinin güvenliğini ve sistem bütünlüğünü en üst düzeyde tutmak için çok katmanlı bir güvenlik stratejisi izler:

- **JWT (JSON Web Token) Tabanlı Yetkilendirme:** Stateless kimlik doğrulama mekanizması ile sunucu yükünü azaltırken, güvenli oturum yönetimi sunar.
- **Granüler Rol Tabanlı Erişim Denetimi (RBAC):** Her kullanıcı rolü (Çiftçi, Mühendis, Admin) sadece kendi görev alanı ile sınırlı verilere ve işlemlere erişebilir.
- **Uçtan Uca Veri Doğrulama ve Sanitizasyon:** Tüm kullanıcı girişleri (input) XSS, SQL Injection ve NoSQL Injection saldırılarına karşı otomatik olarak temizlenir.
- **Güvenli İletişim Protokolleri:** API uç noktaları arasında CORS politikaları ile sıkılaştırılmış erişim kontrolü sağlanır.
- **Kriptografik Veri Güvenliği:** Hassas veriler ve kullanıcı şifreleri, sektör standardı olan Argon2 veya BCrypt algoritmaları ile tuzlanarak (salting) hashlenir.
- **Rate Limiting ve DDoS Koruması:** Sistem, anormal trafik modellerini algılayarak Brute-force ve Denial of Service saldırılarını engellemek için hız sınırlayıcı modüller kullanır.

## 📜 Lisans

Bu proje MIT lisansı ile lisanslanmıştır – detaylar için [LICENSE](LICENSE) dosyasına bakınız.

---

## 👨‍💻 Proje Sahibi

<table align="center">
  <tr>
    <td align="center">
      <img src="https://github.com/bahattinyunus.png" width="120px;" alt="Bahattin Yunus Çetin"/><br />
      <b>Bahattin Yunus Çetin</b><br />
      <sub>IT Architect & University Student</sub>
    </td>
    <td>
      <b>Hakkında:</b><br />
      Trabzon, Of'ta yaşayan bir üniversite öğrencisi ve IT mimarı olarak, tarım ve teknolojiyi bir araya getiren yenilikçi çözümler üzerine çalışmaktayım.
      <br /><br />
      <b>İletişim & Sosyal Medya:</b><br />
      - 💼 <b>LinkedIn:</b> <a href="https://www.linkedin.com/in/bahattinyunus/">bahattinyunus</a><br />
      - 🐙 <b>GitHub:</b> <a href="https://github.com/bahattinyunus">bahattinyunus</a><br />
      - 📧 <b>E-posta:</b> <a href="mailto:bahattinyunus@hotmail.com">bahattinyunus@hotmail.com</a><br />
      - 📸 <b>Instagram:</b> @ciftciag (yakında!)
    </td>
  </tr>
</table>

<div align="center">
  <p>© 2024 ÇiftciAg – Türkiye’nin Tarımsal Dijitalleşme Projesi</p>
</div>
