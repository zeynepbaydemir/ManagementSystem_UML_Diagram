# Management System UML Diagrams

## UML Diagram for University Management System

### Üniversite Yönetim Sistemi

- Üniversiteye ait sınıflıklar, çalışma ofisleri ve departmanlar vardır.
- Departmanlara ait ofisler vardır.
- Üniversiteye ait çalışanlar vardır. Bu çalışanlar profesör veya memur olabilir.
- Her çalışan bir ofiste çalışır.
- Bu sistemi tasvir eden Class (Sınıf) diyagramını çiziniz.

Not : Sınıflara ait nitelik ve davranışların belirtilmesine gerek yoktur.


![UniversityMSUML](https://user-images.githubusercontent.com/78684394/129797360-e899ecc7-6ec5-4a91-b79f-f9a39ccb3fe1.png)



## UML Diagram for Zoo Management System

### Hayvanat Bahçesi Yönetim Sistemi

Hayvanat Bahçesi

Bir hayvanat bahçesindeki hayvanlar hakkındaki bilgileri takip etmek için bir sistem tasarlıyorsunuz.

Hayvanlar:

- Atlar (atlar, zebralar, eşekler vb.),
- Kedigiller (kaplanlar, aslanlar vb.),
- Kemirgenler (sıçanlar, kunduzlar vb.) gibi gruplardaki türlerle karakterize edilir.
- Hayvanlar hakkında depolanan bilgilerin çoğu tüm gruplamalar için aynıdır.
tür adı, ağırlığı, yaşı vb.
- Sistem ayrıca her hayvan için belirli ilaçların dozajını alabilmeli => getDosage ()
- Sistem Yem verme zamanlarını hesaplayabilmelidir => getFeedSchedule ()
- Sistemin bu işlevleri yerine getirme mantığı, her gruplama için farklı olacaktır. Örneğin, atlar için yem verme algoritması farklı olup, kaplanlar için farklı olacaktır.


Polimorfizm modelini kullanarak, yukarıda açıklanan durumu ele almak için bir sınıf diyagramı tasarlayın.

![ZooUML](https://user-images.githubusercontent.com/78684394/131577310-566254e8-8466-401d-ab37-f81edb1b7699.png)

