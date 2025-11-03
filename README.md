# trabzoniii# Yerel klasörü
git deposu olarak başlat
git init

# Uzak depo (GitHub) adresini tanımla
git remote add origin https://github.com/KULLANICI_ADINIZ/trabzon-rehberi.git 
# NOT: KULLANICI_ADINIZ kısmını kendi kullanıcı adınızla değiştirin.
# Tüm dosyaları takip listesine ekle
git add . 

# Değişiklikleri kaydet (commit) ve açıklama ekle
git commit -m "İlk commit: Trabzon rehber CLI uygulaması eklendi"
# Ana (main) dala gönder
git push -u origin main
