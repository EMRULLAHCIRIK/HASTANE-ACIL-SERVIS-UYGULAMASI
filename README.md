Bu proje, hastaların acil serviste öncelik durumlarına göre sıralanmasını sağlayan bir hasta yönetim sistemidir. Çocuk ve yetişkin hastalar ayrı listelerde tutulur ve HL7 formatında hasta bilgileri oluşturulur.

Özellikler

Hastaları "Çok Acil", "Acil" ve "Normal" öncelik seviyelerine göre sıralama

Çocuk ve yetişkin hastalar için ayrı kuyruk yönetimi

Hastalar için benzersiz reçete numarası oluşturma

HL7 formatında hasta bilgisi oluşturma

Mevcut hastaları listeleme

Kurulum

Dev-C++ veya başka bir C derleyicisini kurun.

Proje dosyasını indirin ve bir C derleyicisinde açın.

Derleyip çalıştırın.

Kullanım

Program çalıştırıldığında aşağıdaki menü görüntülenir:

--- Acil Servis Sistemi ---
1. Hasta Ekle
2. Acil Servisteki Hastaları Listele
3. Çocuk Acil'deki Hastaları Listele
4. Çıkış

1. Hasta Ekle: Hasta bilgileri girilir ve sistem öncelik sırasına göre listeye ekler.

2. Acil Servisteki Hastaları Listele: Yetişkin hastaları ve bilgilerini gösterir.

3. Çocuk Acil'deki Hastaları Listele: Çocuk hastaları ve bilgilerini gösterir.

4. Çıkış: Programdan çıkış yapar.

HL7 Formatı

Her hasta için HL7 formatında bir mesaj üretilir. Örnek:

PID|1||12345678901||Ali^Veli||30|Erkek|||Baş Ağrısı|||Acil||2001

Bu format, hasta bilgilerinin standartlaştırılmasını sağlar.
