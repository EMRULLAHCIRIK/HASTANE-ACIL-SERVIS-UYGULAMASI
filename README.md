Acil Servis Hasta Yönetim Sistemi

Bu proje, hastaların acil serviste öncelik durumlarına göre sıralanmasını sağlayan bir hasta yönetim sistemidir. Çocuk ve yetişkin hastalar ayrı listelerde tutulur ve HL7 formatında hasta bilgileri oluşturulur. Sistem, acil servis yönetimini kolaylaştırmak için hasta kayıtlarını düzenli bir şekilde saklar ve öncelik seviyelerine göre yönetir.

📌 Özellikler

Hastaları öncelik sırasına göre sıralama: "Çok Acil", "Acil" ve "Normal" kategorilerine ayrılır.

Çocuk ve yetişkin hastalar için ayrı listeler: Küçük yaştaki hastalar ayrı bir kuyrukta saklanır.

Benzersiz reçete numarası oluşturma: Her hasta için sistem tarafından otomatik üretilir.

HL7 formatında hasta bilgisi oluşturma: Hasta bilgileri uluslararası sağlık standartlarına uygun şekilde düzenlenir.

Hasta listelerini görüntüleme: Mevcut hasta kayıtları listelenebilir.

📥 Kurulum

Gereksinimler:

Dev-C++ veya başka bir C derleyicisi

C programlama dili bilgisi

Kodları İndirme ve Çalıştırma:

Proje dosyalarını indirin.

Derleyicinizde açın ve çalıştırın.

🚀 Kullanım

Program başlatıldığında aşağıdaki menü görüntülenir:

--- Acil Servis Sistemi ---
1. Hasta Ekle
2. Acil Servisteki Hastaları Listele
3. Çocuk Acil'deki Hastaları Listele
4. Çıkış

1. Hasta Ekle: Kullanıcı hasta bilgilerini girer. Sistem, hastayı öncelik sırasına ve yaş grubuna göre ilgili listeye ekler.

2. Acil Servisteki Hastaları Listele: Yetişkin hastaları ve öncelik seviyelerini görüntüler.

3. Çocuk Acil'deki Hastaları Listele: Çocuk hastaları ve öncelik seviyelerini gösterir.

4. Çıkış: Programdan güvenli bir şekilde çıkış yapar.

🏥 HL7 Formatı

Her hasta kaydı, HL7 formatında bir mesaj ile saklanır. Bu format, sağlık sektöründe hasta bilgilerini standardize etmek için kullanılır.

Örnek HL7 Mesajı:

PID|1||12345678901||Ali^Veli||30|Erkek|||Baş Ağrısı|||Acil||2001

Bu format sayesinde, hastaların tıbbi bilgileri sağlık sistemlerine entegre edilebilir.

📝 Örnek Kullanım Senaryosu

Hasta ekleme:

Hasta "YAŞAR EMRULLAH CIRIK" acil servise başvurur.

"Bağ ağrısı" şikayetiyle kaydedilir ve "Acil" öncelik seviyesi atanır.

Sistem, hastayı öncelik sırasına göre listeye ekler ve reçete numarası üretir.

Listeleme:

Kullanıcı, mevcut hasta listesini görüntülemek için "Acil Servisteki Hastaları Listele" seçeneğini kullanır.

Sistem, hastaları öncelik sırasına göre listeler.
