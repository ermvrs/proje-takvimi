# Proje yöneticisinin haftalık özeti

Tek proje yöneticisinin projelerini üst yönetime aktaracağı renkli ve sade şablon. Üç örnek proje içerir. PowerPoint'teki **Üretim Hattı tamamlanması, verilen oran doğrultusunda %30** olarak ayarlanmıştır. Diğer proje bilgileri örnektir.

| Dosya | İçerik | İndir |
| --- | --- | --- |
| Excel | **Tek sekme ve tek yazdırma sayfası.** Veri girişleri, otomatik hesaplamalar ve güncellenen grafik. | [Excel’i indir](./Proje_Takvimi.xlsx?raw=true) |
| PowerPoint | **2 düzenlenebilir slayt.** İlerleme karşılaştırması, haftalık üretim grafiği, proje tabloları ve BEKLENTİ. | [PowerPoint’i indir](./Proje_Sunumu.pptx?raw=true) |
| PDF | **2 sayfa.** PowerPoint’in telefondan görüntülenebilen sürümü. | [PDF’yi aç](./Proje_Sunumu.pdf?raw=true) |

## Ekranda neler var?

- **Proje durumu:** Güncel aşama, gerçek ve planlanan ilerleme, bitiş tarihleri, gecikme ve risk seviyesi.
- **Efor ve maliyet:** Kişi sayısı, toplam saat, birimlere göre saat, gerçekleşen ve kalan maliyet, bütçe ve bütçe farkı.
- **Haftalık işler:** Yapılanlar ve sıradaki iş.
- **BEKLENTİ:** Üst yönetimden istenen karar veya destek, karar mercii, son tarih ve gecikirse etkisi.

## Excel önizlemesi

![Tek sayfalık proje yöneticisi ekranı](./onizleme/yonetici-ozeti.png)

## PowerPoint grafiklerini haftalık güncelleme

Grafikler resim değildir. Her grafiğin dosyanın içine gömülü, düzenlenebilir bir Excel veri tablosu vardır.

1. PowerPoint'te grafiğe sağ tıklayıp **Verileri Düzenle** seçeneğini açın. Masaüstü PowerPoint'te bu seçenek **Grafik Tasarımı → Verileri Düzenle** yolunda da bulunur.
2. İlk slayttaki karşılaştırma grafiğinde **Üretim Hattı / Gerçek (%)** hücresindeki `30` değerini güncelleyin. Örneğin `40` yazdığınızda çubuk ve veri etiketi **%40**, `25` yazdığınızda **%25** olur. Değerleri **0–100 arasında, yüzde işareti olmadan** girin. Planlanan oranı da aynı veri tablosunda değiştirebilirsiniz.
3. İkinci slayttaki **Üretim: haftalık ilerleme** grafiği, **1. Hafta = 30** kaydıyla başlar. Önceki haftayı saklayarak sonraki satıra `2. Hafta` ve yeni oranı ekleyin. Verileri Düzenle penceresindeki **mavi veri aralığını yeni satırı kapsayacak şekilde genişletin**. Böylece noktalar bir çizgiyle bağlanır ve haftalar arasındaki artış veya azalış görünür.
4. Sonraki haftalarda aynı adımı tekrarlayın. Geçmiş hafta oranları paylaşılmadığı için dosyaya geçmiş değerler eklenmemiştir.

**İki grafiğin veri tabloları ayrıdır.** Güncel oranı karşılaştırma grafiğinde, haftalık kaydı ilerleme grafiğinde güncelleyin. Slayttaki normal tablonun yüzdesi de ayrıca düzenlenir; tabloya yazılan sayı grafiği otomatik değiştirmez. Ayrı Excel dosyasıyla otomatik bağlantı yoktur. Bu güncellemede yalnızca PowerPoint ve onun PDF/önizlemeleri yenilenmiştir.

**iPhone:** Sunumu ve PDF'yi görüntüleyebilirsiniz. Grafik verisi düzenleme seçenekleri mobil sürüme göre değişebilir; haftalık veri girişini masaüstü PowerPoint'te yapın. PDF ve PNG önizlemeleri sabittir; grafik verisi bunlardan düzenlenmez.

## Excel kullanımı

1. Proje yöneticisini, rapor tarihini ve **açık sarı giriş alanlarını** güncelleyin. Her satır bir projedir. Planlanan yüzde, kişi/saat, birim dağılımı ve maliyet özetlerini yönetici girer.
2. Yüzde ve gün sapması, tahmini toplam maliyet, bütçe farkı ve özet göstergeleri otomatik hesaplanır. Grafik, ilerleme yüzdeleriyle güncellenir. Beyaz hesaplama alanlarını koruyun.
3. **BEKLENTİ** alanına genel bir açıklama yerine istenen karar veya desteği, kimden istendiğini ve tarihini yazın.
4. Haftalık geçmiş için dosyanın bir kopyasını rapor tarihiyle saklayın. Bu sade sürümde ayrı arşiv ve veri sekmeleri yoktur.

Excel tutarları **TL ve KDV hariç**, sunumdaki maliyet tablosu **bin TL ve KDV hariçtir**. Bütçe farkı bütçe eksi tahmini toplamdır. Negatif fark aşım, pozitif takvim günü gecikme demektir. Kalan maliyet yoksa **0** girin; boş bırakılan maliyet eksik bilgi olarak gösterilir.

Excel, A3 yatayda tek sayfaya yazdırılacak şekilde ayarlanmıştır. PowerPoint tabloları ve grafikleri düzenlenebilir. PDF, sunumun kayıt anındaki görünümüdür.

**iPhone:** Bu sayfayı Safari’de açıp indirme bağlantısını kullanın. İnen dosyayı **Dosyalar → İndirilenler → Paylaş → Excel / PowerPoint** yoluyla açabilirsiniz. Hızlı görüntüleme için PDF bağlantısını kullanın.

[Sunum 1. sayfa önizlemesi](./onizleme/sunum-1.png) · [Sunum 2. sayfa önizlemesi](./onizleme/sunum-2.png)
