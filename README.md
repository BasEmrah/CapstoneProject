# Northwind Data Analysis Capstone Project

Bu proje, Northwind şirketine ait verilerin PostgreSQL kullanılarak analiz edilmesi ve elde edilen sonuçların Python ve PowerBI ile görselleştirilmesini içermektedir.

## İçindekiler

- [Proje Hakkında](#proje-hakkında)
- [Veri Tabloları](#veri-tabloları)
- [Analizler](#analizler)
  - [Çalışan Analizi](#çalışan-analizi)
  - [Finansal Analiz](#finansal-analiz)
  - [Lojistik Analiz](#lojistik-analiz)
  - [Müşteri Analizi](#müşteri-analizi)
  - [Satış Analizi](#satış-analizi)
  - [Stok Analizi](#stok-analizi)
  - [RFM Analizi](#rfm-analizi)
- [Dosyalar](#dosyalar)
- [Kullanım](#kullanım)

## Proje Hakkında

Bu Capstone projesi, Northwind şirketinin çeşitli verilerini analiz ederek iş süreçlerini ve performansını değerlendirmeyi amaçlamaktadır. Analizler PostgreSQL ile yapılmış olup, bazıları Python ve PowerBI kullanılarak görselleştirilmiştir.

## Veri Tabloları

Proje kapsamında analiz edilen veriler aşağıdaki tablolardan oluşmaktadır:

1. **categories (Kategoriler)**
2. **products (Ürünler)**
3. **suppliers (Tedarikçiler)**
4. **order_details (Sipariş Detayları)**
5. **orders (Siparişler)**
6. **customers (Müşteriler)**
7. **customer_customer_demo (Müşteri Demografisi)**
8. **customer_demographics (Müşteri Demografik Bilgileri)**
9. **employees (Çalışanlar)**
10. **employee_territories (Çalışan Bölgeleri)**
11. **territories (Bölgeler)**
12. **region (Regionlar)**
13. **shippers (Nakliyeciler)**
14. **us_states (ABD Eyaletleri)**

## Analizler

### Çalışan Analizi
Çalışan performanslarını ve demografik bilgilerini değerlendiren analizler. PowerBI ile görselleştirilmiştir.

### Finansal Analiz
Şirketin mali durumunu ve finansal performansını değerlendiren analizler. PowerBI ile görselleştirilmiştir.

### Lojistik Analiz
Nakliye ve lojistik süreçlerini değerlendiren analizler. Hem PostgreSQL sorguları hem de PowerBI ve Python ile görselleştirilmiştir.

### Müşteri Analizi
Müşteri davranışlarını ve demografik bilgilerini değerlendiren analizler. PowerBI ile görselleştirilmiştir.

### Satış Analizi
Satış performansını değerlendiren analizler. PowerBI ile görselleştirilmiştir.

### Stok Analizi
Stok durumunu ve yönetimini değerlendiren analizler. Hem PostgreSQL sorguları hem de Python ile görselleştirilmiştir.

### RFM Analizi
Müşteri segmentasyonunu değerlendiren RFM analizi.

## Dosyalar

Bu repo aşağıdaki dosyaları içermektedir:

- **EmrahBas_PowerBI_Capstone.pbix**: PowerBI dosyası, çeşitli analizlerin görselleştirmelerini içermektedir.
- **EmrahBas_PythonCapstone.ipynb**: Python Jupyter Notebook dosyası, stok ve lojistik analizlerin görselleştirmelerini içermektedir.
- **EmrahBas_SQL_Capstone.pdf**: PostgreSQL sorgularının yer aldığı PDF dosyası.
- **NorthWind.png**: Northwind şirketine ait PowerBI ekran görüntüsü.
- **Northwind_Overview.png**: Northwind şirketine genel bakış sağlayan PowerBI ekran görüntüsü.
- **NorthWindERD.png**: Northwind verisine ait ERD görseli.

## Kullanım

1. **PowerBI Dosyası**: PowerBI Desktop uygulaması ile `EmrahBas_PowerBI_Capstone.pbix` dosyasını açarak analizleri görüntüleyebilirsiniz.
2. **Python Notebook**: `EmrahBas_PythonCapstone.ipynb` dosyasını Jupyter Notebook veya Jupyter Lab ile açarak Python ile yapılan görselleştirmeleri inceleyebilirsiniz.
3. **PostgreSQL Sorguları**: `EmrahBas_SQL_Capstone.pdf` dosyasını inceleyerek PostgreSQL sorgularını görebilirsiniz.

