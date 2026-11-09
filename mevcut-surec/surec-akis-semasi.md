
# Ön Süreç Akış Şeması

Bu şema, triko işletmesinin üretim ve izlenebilirlik sürecine ilişkin mevcut bilgilerden hazırlanmış kavramsal bir gösterimdir.

```mermaid
flowchart TD
    A["Üretim Siparişi"]
    B["Örme Üretimi"]
    C["Çuvallama ve QR Etiketi"]
    D["Konfeksiyon"]
    E["Bitmiş Ürün ve Sevk"]

    A --> B
    B --> C
    C --> D
    D --> E

    style C fill:#D8F1EB,stroke:#2A897B,color:#20384C
```

## Açıklama

- Üretim siparişinin ardından örme işlemleri gerçekleştirilir.
- Üretilen parçalar çuvallanarak QR etiketiyle tanımlanır.
- Çuvallar konfeksiyon işlemlerine gönderilir.
- Konfeksiyon sürecinin ardından bitmiş ürünler hazırlanır ve sevk edilir.

**Önemli not:** Bu diyagram, doğrulanmış mevcut durum süreç haritası değildir. Gerçek kayıt akışı, QR okutma noktaları ve çuval–bitmiş ürün ilişkileri saha çalışmasında doğrulanacaktır.
