## Kredi-karti-kumeleme K-Means 
Kredi kartı kümelemesi, büyük bir kredi kartı kullanıcı grubunu, benzer harcama alışkanlıkları ve diğer ortak özelliklere göre daha küçük, yönetilebilir gruplara ayırma işlemidir. Bu sayede, her bir gruptaki müşterilere özel pazarlama stratejileri geliştirilerek daha etkili sonuçlar elde edilebilir.

## Amaç:

Bu proje, bir bankanın kredi kartı müşterilerini harcama alışkanlıkları, kredi limiti ve bakiye gibi özelliklere göre kümelere ayırarak daha hedefli pazarlama stratejileri oluşturmasını amaçlamaktadır. K-Means kümeleme algoritması kullanılarak müşteriler benzer özelliklere sahip gruplara ayrılmaktadır.

## Veri Seti:

CC GENERAL.csv: Bu dosya, müşterilerin kredi kartı bilgileri içermektedir.
BALANCE: Kredi kartı bakiyesi
PURCHASES: Yapılan harcamalar
CREDIT_LIMIT: Kredi limiti
CREDIT_CARD_SEGMENTS: Oluşturulan kümeler

 ## Kullanılan Kütüphaneler

Pandas: Veri manipülasyonu ve analiz
NumPy: Nümerik hesaplamalar
Scikit-learn: Makine öğrenimi algoritmaları
Plotly: Veri görselleştirme

## Proje Adımları:

** Veri Yükleme: Veri seti Pandas ile yüklenir ve ilk 5 satır incelenerek veri hakkında genel bir fikir edinilir.

** Eksik Veri Analizi: Veri setindeki eksik değerler tespit edilir ve gerekli düzenlemeler yapılır. Bu projede eksik değerler düşürülmüştür.

## Veri Önişleme:
** Özellik Seçimi: Analiz için gerekli olan özellikler seçilir (BALANCE, PURCHASES, CREDIT_LIMIT).

** Ölçeklendirme: Veriler, K-Means algoritmasının daha iyi çalışması için MinMaxScaler ile ölçeklendirilir.

## Kümeleme:
** Optimal Küme Sayısı: Elbow metodu veya Silhouette skorunu kullanarak optimal küme sayısı belirlenir.

** K-Means Uygulaması: Belirlenen küme sayısı ile K-Means algoritması çalıştırılır ve müşteriler kümelere ayrılır.

## Sonuçların Değerlendirilmesi:
** Küme Etiketleme: Oluşturulan kümelere anlamlı isimler verilir.

** Görselleştirme: 3 boyutlu scatter plot ile kümeler görselleştirilir.

** Analiz: Her bir kümenin özellikleri incelenerek müşteri segmentleri hakkında çıkarımlar yapılır.

## Lisans
Bu proje MIT Lisansı altında alınmıştır.
