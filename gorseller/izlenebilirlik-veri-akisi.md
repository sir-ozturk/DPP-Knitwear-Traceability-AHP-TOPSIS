
# İzlenebilirlik Veri İlişkileri

Bu diyagram, triko üretiminde mevcut kayıtların
incelenmesi ve geliştirilmesi gereken veri
bağlantılarının belirlenmesi amacıyla
hazırlanmış kavramsal bir modeldir.

```mermaid
flowchart TD
    A["ERP Üretim Kayıtları"]
    B["Çuval QR Kimliği"]
    C["Konfeksiyon Kayıtları"]
    D["Bitmiş Ürün Kimliği"]

    A --> B
    B -.-> C
    C -.-> D

    style A fill:#DBEAFE,stroke:#2563EB,color:#1E3A8A
    style B fill:#CCFBF1,stroke:#0D9488,color:#134E4A
    style C fill:#FEF3C7,stroke:#D97706,color:#78350F
    style D fill:#FEF3C7,stroke:#D97706,color:#78350F
```

## Diyagramın Açıklaması

**ERP üretim kayıtları:**
Üretim bilgilerinin takip edildiği mevcut
sistem kayıtlarını temsil eder.

**Çuval QR kimliği:**
Üretimden konfeksiyona gönderilen çuvalların
tanımlanmasında kullanılan mevcut yapıdır.

**Konfeksiyon kayıtları:**
Çuval içerisindeki parçaların sonraki
işlemlerle ilişkilendirilmesinde
incelenecek veri alanlarını temsil eder.

**Bitmiş ürün kimliği:**
Bitmiş ürün ile kaynak çuval ya da çuvallar
arasında kurulması hedeflenen ilişkiyi
temsil eder.

## Gösterim

- Düz oklar: Ön bilgilerden hareketle
  incelenecek mevcut kayıt ilişkisi.
- Kesikli oklar: Saha çalışması sırasında
  doğrulanması ve geliştirilmesi gereken
  veri bağlantıları.

**Not:** Diyagram gerçek veri tabanı
mimarisini veya tamamlanmış bir
entegrasyonu göstermemektedir.
