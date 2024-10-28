# Proje: Menü Tabanlı Uygulama

## Amaç
Kullanıcının bir menü aracılığıyla belirli işlemleri seçerek gerçekleştirebileceği bir uygulama geliştirmek. Bu proje, kullanıcı etkileşimini ve switch-case yapısının kullanımını pekiştirmek amacıyla tasarlanmıştır.

## Gereksinimler
1. Uygulama, kullanıcının seçim yapabileceği bir menü sunar.
2. Menü seçenekleri:
   - 1: Öğrenci Ekle
   - 2: Öğrenci Sil
   - 3: Öğrenci Listesi
   - 4: Çıkış
3. Kullanıcı, menüdeki bir seçeneği girdiğinde, ilgili işlem gerçekleştirilir:
   - **Öğrenci Ekle:** Kullanıcıdan bir öğrencinin adını alır ve ekler.
   - **Öğrenci Sil:** Kullanıcıdan silinecek öğrencinin adını alır ve listeden siler.
   - **Öğrenci Listesi:** Mevcut öğrencilerin listesini gösterir.
   - **Çıkış:** Programı sonlandırır.

## Adımlar

1. **Menü Oluşturma:**
   - Kullanıcıya sunulacak menü seçeneklerini console.log() ile yazdırın.

2. **Kullanıcı Girişi Alma:**
   - `prompt()` kullanarak kullanıcıdan bir seçim alın.

3. **Switch-Case Yapısı:**
   - Kullanıcının seçtiği değere göre bir `switch` ifadesi kullanarak ilgili işlemleri gerçekleştirin.

4. **İşlemleri Gerçekleştirme:**
   - Her seçeneğe göre farklı işlemler yapın:
     - **Öğrenci Ekle:** Kullanıcıdan bir isim alın ve bir diziye ekleyin.
     - **Öğrenci Sil:** Kullanıcıdan bir isim alın ve diziden silin.
     - **Öğrenci Listesi:** Dizi içerisindeki tüm öğrencilerin isimlerini gösterin.
     - **Çıkış:** Programı sonlandırın.

5. **Geçersiz Girdi Kontrolü:**
   - Kullanıcının girdiği seçeneğin geçerli olup olmadığını kontrol edin. Geçersiz bir seçim yapıldığında uygun bir mesaj gösterin.
