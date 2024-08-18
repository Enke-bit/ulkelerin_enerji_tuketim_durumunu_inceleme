# Enerji Tüketimi Tahmin Projesi

Bu proje, enerji tüketimi verilerini analiz etmek ve tahminlerde bulunmak için bir model kurmayı amaçlar. Projede, belirli ülkelerin enerji tüketimi verilerini görselleştirdik, bir lineer regresyon modeli kurduk ve gelecekteki enerji tüketimini tahmin ettik. Ayrıca, kullanıcıların tahminler yapabilmesi için bir Tkinter arayüzü geliştirdik.

## İçindekiler

1. [Veriye İlk Temas](#veriye-ilk-temas)
2. [Veri Görselleştirmesi](#veri-görselleştirmesi)
   - [US Enerji Tüketim Değerini İnceleme](#us-enerji-tüketim-değerini-inceleme)
   - [Canada Enerji Tüketimini İnceleme](#canada-enerji-tüketimini-inceleme)
   - [Mexico Enerji Tüketimini İnceleme](#mexico-enerji-tüketimini-inceleme)
   - [Turkey Tüketimini Ülkeler Açısından İnceleme](#turkey-tüketimini-ülkeler-açısından-inceleme)
3. [Model Kurma](#model-kurma)
   - [Türkiye ile Model Kurma ve Değerlendirme](#türkiye-ile-model-kurma-ve-değerlendirme)
   - [Veri Setindeki Gerçek Değerler ve Tahmin Değerlerini Yazdırma](#veri-setindeki-gerçek-değerler-ve-tahmin-değerlerini-yazdırma)
   - [Tahminlerin Görselleştirilmesi](#tahminlerin-görselleştirilmesi)
   - [Tkinter Arayüzü ile Tahmin Yapma](#tkinter-arayüzü-ile-tahmin-yapma)
4. [Değerlendirme Yapma](#değerlendirme-yapma)
5. [Kurulum ve Kullanım](#kurulum-ve-kullanım)

## Veriye İlk Temas

Projeye başlamadan önce enerji tüketimi verisini içe aktardık ve veri setini inceledik. Bu aşamada veri temizliği ve ön işleme adımlarını gerçekleştirdik.

## Veri Görselleştirmesi

1. **US Enerji Tüketim Değerini İnceleme**: ABD'nin enerji tüketim verilerini yıllara göre görselleştirdik.
2. **Canada Enerji Tüketimini İnceleme**: Kanada'nın enerji tüketimini analiz ettik ve görselleştirdik.
3. **Mexico Enerji Tüketimini İnceleme**: Meksika'nın enerji tüketimini inceledik ve grafiklerle sunduk.
4. **Turkey Tüketimini Ülkeler Açısından İnceleme**: Türkiye'nin enerji tüketimini diğer ülkelerle karşılaştırarak görselleştirdik.

## Model Kurma

1. **Türkiye ile Model Kurma ve Değerlendirme**: Türkiye'nin enerji tüketimi verilerini kullanarak bir lineer regresyon modeli oluşturduk ve değerlendirdik.
2. **Veri Setindeki Gerçek Değerler ve Tahmin Değerlerini Yazdırma**: Modelimiz tarafından tahmin edilen değerler ve gerçek değerlerle karşılaştırdık.
3. **Tahminlerin Görselleştirilmesi**: Tahminlerimizi grafiklerle görselleştirdik.
4. **Tkinter Arayüzü ile Tahmin Yapma**: Kullanıcının gelecekteki yıllar için enerji tüketimini tahmin edebilmesi için bir Tkinter arayüzü geliştirdik.

## Değerlendirme Yapma

Modelimizin performansını değerlendirdik ve tahminlerin doğruluğunu inceledik. Sonuçlar, modelin doğruluğunu ve geçerliliğini gösterir.

## License.txt

MIT License

Telif Hakkı (c) 2024 İbrahim Püsküllü

Bu yazılım ve ilişkili belgeler ("Yazılım"), lisans sahibi tarafından kullanım, kopyalama, değiştirme, birleştirme, yayımlama, dağıtma, alt lisanslama ve/veya satma dahil olmak üzere sınırlama olmaksızın işlenir ve kullanılır, 
böylece aşağıdaki koşullar yerine getirilir:

Yukarıdaki telif hakkı bildirimi ve bu izin bildirimi, yazılımın tüm kopyalarında veya önemli kısımlarında yer almalıdır.

YAZILIM "AS IS" DURUMUNDA, HERHANGİ BİR GARANTİ OLMAKSIZIN, AÇIK VEYA ZIMNİ, SATILABİLİRLİK, BELİRLİ BİR AMACA UYGUNLUK VEYA İHLAL OLMAMASI DA DAHİL ANCAK BUNLARLA SINIRLI OLMAKSIZIN HİÇBİR GARANTİ VERMEKSİZİN SAĞLANIR. 
HİÇBİR KOŞULDA YAZARLAR VEYA TELİF HAKKI SAHİPLERİ HERHANGİ BİR TALEP, ZARAR VEYA DİĞER SORUMLULUK İÇİN, 
YAZILIMLA VEYA YAZILIMIN KULLANIMI VEYA BAŞKA BAĞLANTI BİÇİMLERİ İLE İLGİLİ, SÖZLEŞME, HAKKANİYET VEYA BAŞKA BİR SEBEPLE SORUMLU TUTULAMAZ. BU YAZILIMIN KULLANIMI HAKKINDA HERHANGİ BİR İDDİAYI KABUL ETMEYİNİZ.

## Kurulum ve Kullanım

Proje, Python 3.x ve gerekli kütüphanelerle çalıştırılabilir. Gerekli kütüphaneleri yüklemek için aşağıdaki komutu kullanabilirsiniz:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn tk
