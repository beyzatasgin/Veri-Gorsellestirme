# Veri Görselleştirme Projesi

Bu proje, Airbnb kullanıcı verileri üzerinde çeşitli veri görselleştirme tekniklerini uygulayan bir Jupyter Notebook projesidir.

## 📋 Proje Hakkında

Proje, kullanıcı verilerini analiz ederek farklı görselleştirme kütüphaneleri (matplotlib, seaborn, plotly) kullanarak çeşitli grafikler oluşturmaktadır.

## 🎯 Özellikler

- **Çubuk Grafik**: En çok rezervasyon yapılan 10 ülke
- **Çizgi Grafik**: Yıllara göre kullanıcı kayıtları
- **Pasta Grafik**: Kullanıcıların cinsiyet dağılımı
- **Histogram**: Kullanıcı yaş dağılımı
- **Dağılım Grafiği**: Yaş ve kayıt yılı ilişkisi

## 🛠️ Kullanılan Teknolojiler

- **Python 3.x**
- **Pandas**: Veri manipülasyonu ve analizi
- **Matplotlib**: Temel görselleştirme
- **Seaborn**: İstatistiksel görselleştirme
- **Plotly**: İnteraktif görselleştirme
- **Jupyter Notebook**: Geliştirme ortamı

## 📦 Kurulum

1. Projeyi klonlayın:
```bash
git clone https://github.com/kullaniciadi/verigorsellestirme.git
cd verigorsellestirme
```

2. Gerekli kütüphaneleri yükleyin:
```bash
pip install -r requirements.txt
```

3. Jupyter Notebook'u başlatın:
```bash
jupyter notebook
```

4. `VeriGorsellestirme.ipynb` dosyasını açın ve çalıştırın.

## 📊 Veri Seti

Proje, `train_users_2.csv` dosyasını kullanmaktadır. Bu dosyayı proje klasörüne eklemeniz gerekmektedir.

**Not**: Veri seti dosyası boyutu nedeniyle repository'ye eklenmemiş olabilir. Veri setini kendi kaynağınızdan indirip proje klasörüne eklemeniz gerekmektedir.

## 🚀 Kullanım

1. Veri setini (`train_users_2.csv`) proje klasörüne ekleyin
2. Jupyter Notebook'u açın
3. Hücreleri sırayla çalıştırın
4. Grafikleri görüntüleyin

## 📝 Notlar

- Veri seti dosyasını (`train_users_2.csv`) proje klasörüne eklemeniz gerekmektedir
- Bazı grafikler interaktif olabilir (Plotly grafikleri)
- Veri setinde eksik değerler olabilir, kod bunları otomatik olarak işler

## 👤 Yazar

Bu proje bir staj projesi kapsamında geliştirilmiştir.

## 📤 GitHub'a Yükleme

Projenizi GitHub'a yüklemek için aşağıdaki adımları izleyin:

1. **GitHub'da yeni bir repository oluşturun:**
   - GitHub.com'a gidin ve yeni bir repository oluşturun
   - Repository adını belirleyin (örn: `verigorsellestirme`)
   - Public veya Private seçin

2. **Proje klasöründe Git repository'sini başlatın:**
   ```bash
   git init
   ```

3. **Dosyaları ekleyin:**
   ```bash
   git add README.md requirements.txt .gitignore VeriGorsellestirme.ipynb
   ```

4. **İlk commit'i yapın:**
   ```bash
   git commit -m "İlk commit: Veri görselleştirme projesi"
   ```

5. **GitHub repository'nizi remote olarak ekleyin:**
   ```bash
   git remote add origin https://github.com/KULLANICI_ADINIZ/REPOSITORY_ADI.git
   ```
   (KULLANICI_ADINIZ ve REPOSITORY_ADI kısımlarını kendi bilgilerinizle değiştirin)

6. **Ana branch'i main olarak ayarlayın:**
   ```bash
   git branch -M main
   ```

7. **Dosyaları GitHub'a yükleyin:**
   ```bash
   git push -u origin main
   ```

**Not:** İlk kez push yapıyorsanız, GitHub kullanıcı adı ve şifreniz (veya Personal Access Token) istenebilir.

## 📄 Lisans

Bu proje eğitim amaçlıdır.

