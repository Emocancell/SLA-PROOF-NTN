# GitHub'a Güvenli Yükleme Rehberi

## 1) Herkese açık tanıtım deposu

1. GitHub'da **New repository** ile `SLA-PROOF-NTN-Overview` adlı depoyu oluşturun; görünürlüğü **Public** seçin.
2. Bu ZIP dosyasını bilgisayarınızda açın. **ZIP dosyasını tek dosya olarak yüklemeyin**; içindeki `README.md`, PDF'ler, görseller ve alt klasörleri yükleyin.
3. GitHub web arayüzünde `Add file > Upload files` yoluyla dosyaları seçin. Alt klasör ve `.gitignore` dahil bütün dosyaların aktarılmış olduğunu kontrol edin.
4. `README.md` görüntüsünü, PDF bağlantılarını ve `DEMO_VIDEO.mp4` bağlantısını kontrol edin.
5. `CONTACT.md` içindeki iletişim bilgisini ve `docs/TURKCELL_APPLICATION_TEXT.md` içindeki `KULLANICI_ADI` bölümünü kendi bilgilerinizle tamamlayın.
6. [Yayımlama kontrol listesi](docs/BEFORE_PUBLISH_CHECKLIST.md) maddelerini iki ekip üyesi birlikte doğrulayın.

**Alternatif Git komutları (yerel terminalde, açılan public paket klasöründe):**

```bash
git init
git add .
git status --short
git diff --cached --name-only
git commit -m "Add public technical overview"
git branch -M main
git remote add origin https://github.com/KULLANICI_ADI/SLA-PROOF-NTN-Overview.git
git push -u origin main
```

`KULLANICI_ADI` gerçek GitHub kullanıcı adınızla değiştirilmelidir. Git komutlarını çalıştırmadan önce kaynak kodu ve sır dosyası olmadığı kontrol edilmelidir. Halihazırda README eklenerek oluşturulmuş bir depoya doğrudan push etmeden önce mevcut geçmişle uyumu kontrol edin.

## 2) Özel geliştirme deposu

1. Ayrı ve **Private** görünürlükte `SLA-PROOF-NTN-Core` oluşturun.
2. Ayrı sunulan `SLA_PROOF_NTN_GitHub_PRIVATE_Template.zip` içeriğini başlangıç yapısı olarak ekleyin.
3. MATLAB kaynak kodlarını yalnızca özel deponun `src/` klasöründe tutun; gerçek sırları, kimlik bilgilerini ve operatör verilerini oraya da commit etmeyin.
4. Ekip arkadaşını en az gerekli erişim yetkisiyle davet edin; iki faktörlü doğrulamayı etkinleştirin.
5. Kaynak kodu kamuya açmadan önce fikrî mülkiyet değerlendirmesini yapın.

## 3) Başvuruya konulacak gerçek bağlantı

`https://github.com/KULLANICI_ADI/SLA-PROOF-NTN-Overview`

Yalnızca depo GitHub üzerinde gerçekten oluşturulup erişimi doğrulandıktan sonra başvuruya ekleyin.
