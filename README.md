🚀 Proje Başlığı: End-to-End Automated CI/CD Pipeline with Docker & GitHub Actions



📋 Proje Özeti
Bu proje, manuel uygulama paketleme ve dağıtım süreçlerini tamamen otonom hale getiren modern bir DevOps hattını temsil eder. Bir web uygulamasının geliştirme aşamasından bulut deposuna (Docker Hub) kadar olan yolculuğu, GitHub Actions kullanılarak "Zero-Touch" (El değmeden) prensibiyle kurgulanmıştır.


🛠️ Kullanılan Teknolojiler & Mimari
Linux (Ubuntu): Geliştirme ortamı ve sistem yönetimi.

Docker: Uygulamanın konteynerize edilmesi ve imaj yönetimi.

GitHub Actions: Sürekli Entegrasyon (CI) otomasyonu.

Git: Versiyon kontrolü ve kaynak kod yönetimi.

Docker Hub: Merkezi bulut imaj deposu.

💡 Teknik Çözümler ve Kazanımlar
Otomasyon (Automation): git push komutu ile tetiklenen workflow sayesinde, manuel build ve push işlemleri robotik bir sürece devredilmiştir.

Güvenlik (Security): Hassas veriler (Docker şifreleri) GitHub Secrets (Kasa) mimarisi kullanılarak güvenli bir şekilde yönetilmiştir.

Problem Çözme (Troubleshooting): Proje sürecinde karşılaşılan "Personal Access Token" yetkilendirme (Workflow Scope) ve ağ kesintisi (SSH Timeout) gibi kritik engeller, log analizleri ve sistem müdahalesiyle başarıyla aşılmıştır.

📈 Sonuç
Bu mimari sayesinde, kod üzerinde yapılan herhangi bir değişiklik 60 saniyeden kısa bir sürede otomatik olarak paketlenip dünyanın her yerinden erişilebilir bir "Container Image" haline gelmektedir.
