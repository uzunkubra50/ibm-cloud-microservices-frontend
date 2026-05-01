# IBM Cloud Microservices: Dealer Evaluation App

Bu proje, **IBM Cloud Code Engine** üzerinde dağıtılan (deploy edilen) mikroservis tabanlı bir web uygulamasıdır. Uygulama, farklı ürünlerin farklı bayilerdeki fiyatlarını karşılaştırmak için dinamik bir ön yüz ve iki ayrı arka uç (backend) servisinden oluşmaktadır.

## 🚀 Teknik Mimari
Proje, birbirinden bağımsız çalışan üç ana bileşenden oluşur:
*   **Ürünler Servisi (prodlist):** Ürün listesini sağlayan mikroservis.
*   **Bayi Detayları Servisi (dealerdetails):** Bayi ve fiyat bilgilerini yöneten mikroservis.
*   **Ön Yüz (frontend):** Kullanıcının verileri görüntülediği, JavaScript tabanlı dinamik web arayüzü.

## 🛠️ Kullanılan Teknolojiler
*   **Bulut Platformu:** IBM Cloud (Code Engine, IBM Cloud Container Registry)
*   **Programlama Dilleri:** Python (Flask/Node.js backend yapıları), JavaScript (Frontend)
*   **Araçlar:** Git, Docker, IBM Cloud CLI, Theia IDE

## 🔧 Yapılan İşlemler
1.  **Konteynerleştirme:** Uygulama servisleri Docker imajları olarak yapılandırıldı ve IBM Cloud Container Registry'ye yüklendi.
2.  **Dağıtım (Deployment):** IBM Cloud Code Engine kullanılarak mikroservisler canlıya alındı.
3.  **Entegrasyon:** Frontend tarafındaki `index.html` dosyası, canlıdaki mikroservislerin API uç noktalarıyla (endpoints) haberleşecek şekilde güncellendi.
4.  **Versiyon Kontrolü:** Tüm süreç Git üzerinden yönetilerek GitHub portföyüne aktarıldı.

## 📈 Öğrenim Kazanımları
Bu proje ile aşağıdaki konularda pratik deneyim kazandım:
*   Bulut tabanlı uygulama mimarisi ve dağıtım süreçleri.
*   Mikroservislerin birbirleriyle API üzerinden haberleşmesi.
*   IBM Cloud ekosisteminde proje yönetimi.
