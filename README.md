# Proje: Basit Bir Oyun: Tahmin Et

## Amaç
Kullanıcının rastgele seçilen bir sayıyı tahmin etmesi gereken basit bir oyun geliştirmek.

## Gereksinimler
1. Bilgisayar rastgele 1 ile 100 arasında bir sayı seçer.
2. Kullanıcıdan bu sayıyı tahmin etmesini isteyin.
3. Kullanıcının tahmini doğru ise "Tebrikler, doğru tahmin ettiniz!" mesajı gösterin; yanlışsa, tahmininin ne kadar yüksek veya düşük olduğunu bildirin.
4. Kullanıcının doğru tahmini yapana kadar oyuna devam edin.

## Adımlar

### 1. Rastgele Sayı Oluşturma
`Math.random()` kullanarak 1 ile 100 arasında rastgele bir sayı oluşturun.

### 2. Kullanıcı Girişi Alma
`prompt()` ile kullanıcıdan bir tahmin alın.

### 3. Tahmin Kontrolü
Kullanıcının girdiği tahminin doğru olup olmadığını kontrol edin.
- Eğer yanlışsa, tahminin yüksek veya düşük olduğunu belirtin ve kullanıcıdan tekrar tahmin yapmasını isteyin.

### 4. Oyun Sonu
Kullanıcı doğru tahmini yaptığında, oyunu sonlandırın ve tebrik mesajı gösterin.

## İpuçları
- Kullanıcının geçersiz bir girdi yapması durumunda, uygun bir hata mesajı gösterin.
- Oyunun başlangıcında kullanıcıya hangi aralıkta tahmin yapması gerektiğini belirtin.
