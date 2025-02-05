# Git Nedir? Ne İçin Kullanılır?

## Git Nedir?
Git, yazılım projelerinde versiyon kontrolü (version control) sağlamak için kullanılan açık kaynaklı ve dağıtık bir sistemdir. Yazılımcıların ve ekiplerin proje üzerinde yaptığı değişiklikleri kayıt altına almasını, geçmişteki sürümlere geri dönmesini ve projeyi birden fazla kişiyle eş zamanlı olarak geliştirmesini kolaylaştırır.

2005 yılında **Linus Torvalds** tarafından geliştirilmiştir ve bugün, yazılım dünyasında en yaygın kullanılan versiyon kontrol sistemlerinden biridir.

---

## Git Ne İçin Kullanılır?
Git'in kullanım alanları şunlardır:

### 1. **Versiyon Kontrolü**  
Projede yapılan her değişiklik kaydedilir ve geçmişe dönük olarak incelenebilir. Böylece bir hata durumunda önceki bir sürüme kolayca geri dönülebilir.

### 2. **İş Birliği (Collaboration)**  
Bir projeyi birden fazla kişiyle aynı anda geliştirmeyi sağlar. Geliştiriciler, aynı dosya üzerinde bile çalışırken birbirlerinin değişikliklerini kolayca birleştirebilirler.

### 3. **Kod Yedekleme**  
Git ile kodlar yerel bir depo (repository) olarak bilgisayarınıza kaydedilir. Ayrıca, GitHub gibi bir uzak sunucu kullanıldığında, projeleriniz çevrimiçi olarak da yedeklenir.

### 4. **Şube Yönetimi (Branching)**  
Farklı özellikler veya düzeltmeler üzerinde çalışmak için ayrı şubeler (branches) oluşturulur. Bu şubeler daha sonra ana projeye entegre edilebilir.

### 5. **Değişikliklerin İzlenmesi**  
Kim, ne zaman, hangi değişikliği yaptı? Bu soruların cevapları Git sayesinde kolayca bulunabilir.

---

## Git'in Avantajları
- **Hızlı ve Hafif**: Git, değişiklikleri hızlı bir şekilde kaydeder ve yönetir.  
- **Dağıtık Mimari**: Her geliştirici, projenin tam bir kopyasına sahip olur; bu, merkezi bir sunucunun arızasına karşı dayanıklılık sağlar.  
- **Kolay Şube Yönetimi**: Farklı geliştirme süreçlerini izole edebilir ve gerektiğinde birleştirebilirsiniz.  
- **Açık Kaynak**: Git, ücretsizdir ve sürekli olarak geliştirilmeye devam edilmektedir.

---

## Ek Kaynaklar
- [Git Resmi Belgeleri](https://git-scm.com/doc)  
- [GitHub ve Git Farkı](https://guides.github.com/introduction/git-handbook/)  

# Git'in Temel Komutları
| Komut         | Açıklama                              |
|---------------|--------------------------------------|
| `git init`    | Yeni bir depo başlatır.              |
| `git clone`   | Var olan bir depoyu kopyalar.        |
| `git add`     | Değişiklikleri aşamaya ekler.        |
| `git commit`  | Değişiklikleri kaydeder.            |
| `git push`    | Uzak depoya değişiklikleri gönderir. |
| `git pull`    | Uzak depodan güncellemeleri çeker.   |
| `git merge`   | Şubeleri birleştirir.               |
| `git status`  | Depo durumu hakkında bilgi verir.    |
| `git log`     | Commit geçmişini gösterir.           |
| `git branch`  | Şube oluşturur veya listeler.        |

# Git İş Akışları (Branching, Pull Request, Merge Conflicts)

### Açıklamalar:
1. **Branching (Şube Yönetimi)**: Yeni özellik eklemek veya düzeltme yapmak için kendi şubenizi oluşturup bağımsız olarak çalışabilirsiniz.
2. **Pull Request**: Değişikliklerinizi ana projeye entegre etmeden önce inceleme ve onay süreci başlatır.
3. **Merge Conflicts**: Farklı şubelerdeki aynı dosya üzerindeki değişikliklerin birleştirilmesi sırasında ortaya çıkan çatışmaların çözülmesini içerir.

Bu bilgilerle README.md dosyanızı zenginleştirebilir ve Git iş akışlarını açık bir şekilde anlatabilirsiniz.

# Design Patterns (Tasarım Desenleri)

## Design Patterns Nedir?
**Design Patterns** (Tasarım Desenleri), yazılım geliştirme süreçlerinde karşılaşılan ortak sorunlara çözüm sağlamak için tekrarlanan ve test edilmiş yöntemlerdir. Tasarım desenleri, belirli bir yazılım tasarımında karşılaşılan problemi çözmek için yaygın olarak kabul edilen ve uygulanan en iyi pratikleri sunar. Bu desenler, yazılımın daha esnek, sürdürülebilir ve genişletilebilir olmasını sağlar.

Tasarım desenleri, yazılım mühendisliği literatüründe genellikle 3 ana kategoride sınıflandırılır:
1. **Creational Patterns** (Yaratıcı Desenler)
2. **Structural Patterns** (Yapısal Desenler)
3. **Behavioral Patterns** (Davranışsal Desenler)

---

## Yazılımda Neden Kullanılır?

### 1. **Kodun Tekrarını Azaltma**
Tasarım desenleri, yazılım geliştirme sürecinde daha önce çözülmüş sorunların tekrarlanmasını önler. Çeşitli problemler için test edilmiş ve kanıtlanmış çözümler sunarak, aynı çözümleri yeniden yazmaya gerek kalmaz.

### 2. **Kodun Bakımını Kolaylaştırma**
Tasarım desenleri, yazılımın yapısını net bir şekilde tanımlar ve modüler hale getirir. Bu sayede, kodun bakımı ve güncellenmesi daha kolay olur. Yeni özellikler eklemek veya mevcut özellikleri değiştirmek için daha az risk ve karmaşıklık vardır.

### 3. **Esneklik ve Genişletilebilirlik Sağlama**
Tasarım desenleri, yazılımı esnek hale getirir. Sistemdeki bileşenler arasında gevşek bağlılık (loose coupling) sağlar, bu da sistemi değiştirmeyi veya genişletmeyi kolaylaştırır. Ayrıca, yeni işlevsellik eklerken mevcut kodu etkilemeden çalışmanızı sağlar.

### 4. **İletişim ve Paylaşılan Dil**
Tasarım desenleri, yazılım geliştiricileri arasında ortak bir dil ve anlayış sağlar. Aynı tasarım desenini kullanan geliştiriciler, kodu daha kolay okuyabilir ve anlayabilir. Bu, ekip içindeki iletişimi geliştirir ve sorunları daha hızlı çözmelerini sağlar.

### 5. **Verimli ve Hızlı Geliştirme Süreci**
Tasarım desenleri, yazılım geliştirme sürecini hızlandırır çünkü yazılımcılar zaten test edilmiş ve onaylanmış çözümleri kullanarak problemleri daha hızlı çözebilirler. Bu, geliştirme süresinin kısalmasına ve hata oranının düşmesine yol açar.

---

## Design Patterns Türleri

### 1. **Creational Patterns** (Yaratıcı Desenler)
Bu desenler, nesne yaratma süreçlerini ele alır. Yaratıcı desenler, nesne yaratma işlemini soyutlar, böylece nesne oluşturma sürecini daha esnek hale getirir. Örnekler:
- **Singleton Pattern**: Sadece bir nesne örneği oluşturulmasını sağlar.
- **Factory Method Pattern**: Nesne oluşturma işlemini alt sınıflara bırakır.
- **Abstract Factory Pattern**: Birbiriyle ilişkili nesnelerin oluşturulmasını sağlayan bir arayüz sunar.

### 2. **Structural Patterns** (Yapısal Desenler)
Yapısal desenler, nesneler ve sınıflar arasındaki ilişkileri tanımlar. Bu desenler, daha karmaşık yapılar oluşturmak için daha küçük bileşenlerin birleştirilmesini sağlar. Örnekler:
- **Adapter Pattern**: İki uyumsuz arayüzü uyumlu hale getirir.
- **Composite Pattern**: Nesneleri ağaç yapısında düzenler ve her bir bileşeni tek bir nesne gibi işler.
- **Facade Pattern**: Karmaşık bir sistemi basit bir arayüzle sunar.

### 3. **Behavioral Patterns** (Davranışsal Desenler)
Davranışsal desenler, nesneler arasındaki iletişim ve görevlerin dağıtımını tanımlar. Bu desenler, nesneler arasındaki etkileşimleri optimize eder ve genellikle daha esnek bir yapı sağlar. Örnekler:
- **Observer Pattern**: Bir nesne durum değişikliğinde, bağlı olan diğer nesneleri bilgilendirir.
- **Strategy Pattern**: Çeşitli algoritmaların birbirinin yerine kullanılmasını sağlar.
- **Command Pattern**: Bir işlemi nesne olarak temsil eder, böylece işlemlerin sırasını değiştirmeyi ve geri almayı kolaylaştırır.

---

## Sonuç
Tasarım desenleri, yazılım mühendisliğinde karşılaşılan yaygın problemleri çözmek için etkili ve tekrar kullanılabilir çözümler sunar. Bu desenler, yazılımın sürdürülebilirliğini artırır, geliştirici ekiplerin daha verimli çalışmasını sağlar ve sistemin esnekliğini artırır. Farklı türdeki desenler, belirli yazılım tasarımı ihtiyaçlarına göre seçilebilir ve kullanılabilir.

---

## Ek Kaynaklar
- [Design Patterns: Elements of Reusable Object-Oriented Software](https://www.amazon.com/Design-Patterns-Elements-Reusable-Object-Oriented/dp/0201633612) (Kitap)
- [Refactoring Guru - Design Patterns](https://refactoring.guru/design-patterns)

# Backend-API: API Nedir?

## API Nedir?
**API (Application Programming Interface)**, farklı yazılım uygulamaları arasında iletişim ve veri alışverişi sağlamak için kullanılan bir ara yüzdür. API'ler, bir yazılımın belirli işlevlerini dışarıya açarak diğer yazılımların bu işlevleri kullanmasına olanak tanır. 

API'ler, bir uygulamanın iç işleyişine erişim sağlamadan, yalnızca belirli bir protokol veya standart üzerinden erişim sağlar. Bu, uygulamalar arasında veri alışverişi ve iş birliği yapılmasını kolaylaştırır.

---

## Backend ve API İlişkisi
**Backend**, bir yazılımın arka planda çalışan ve genellikle veritabanı, iş mantığı ve işlevselliklerin yönetiminden sorumlu olan kısmıdır. **API**, Backend'in dış dünyaya açılan kapısıdır. Bir API, bir uygulamanın frontend (kullanıcı arayüzü) kısmıyla backend kısmı arasında veya tamamen farklı uygulamalar arasında veri alışverişini sağlar.

Örneğin:
- Bir e-ticaret sitesinde ürünlerin listesi, fiyatları ve kullanıcı bilgileri gibi veriler bir **Backend** üzerinde tutulur.
- Kullanıcılar tarayıcı veya mobil uygulama üzerinden bu verilere erişmek istediklerinde, **API** bu verilerin alınıp gönderilmesini sağlar.

---

## API'nin Özellikleri
- **Platformlar Arası İletişim:** API'ler, farklı teknolojilerle yazılmış sistemler arasında veri paylaşımı sağlar.
- **Güvenli Erişim:** API, genellikle belirli bir yetkilendirme (ör. OAuth, API key) gerektirerek güvenli bir erişim sunar.
- **Standartlaştırılmış İletişim:** API'ler, genellikle REST, GraphQL, SOAP gibi standart protokoller üzerinden çalışır.

---

## API Türleri
1. **REST API** (Representational State Transfer):  
   HTTP protokolünü kullanarak çalışan, hafif ve yaygın bir API türüdür.  
   Örnek HTTP yöntemleri:  
   - `GET`: Veri almak için kullanılır.  
   - `POST`: Veri oluşturmak için kullanılır.  
   - `PUT`: Veriyi güncellemek için kullanılır.  
   - `DELETE`: Veriyi silmek için kullanılır.

2. **GraphQL API**:  
   Veri sorgulama ve manipulasyon için kullanılan bir API türüdür. Daha esnek veri sorgulamaları sağlar.

3. **SOAP API** (Simple Object Access Protocol):  
   Daha karmaşık veri yapıları için kullanılan bir API protokolüdür.

4. **WebSocket API**:  
   İki yönlü sürekli bağlantılar sağlayarak gerçek zamanlı veri iletimi için kullanılır.

---

## API Kullanım Senaryoları
- **Mobil Uygulama Backend'i:** Mobil uygulamalar, genellikle sunuculardan veri almak ve işlemek için API kullanır.
- **Üçüncü Taraf Entegrasyonlar:** Harita hizmetleri (Google Maps API), ödeme ağ geçitleri (Stripe API) gibi hizmetler, uygulamalara dışarıdan entegre edilebilir.
- **Mikroservisler:** Büyük uygulamalar, birden fazla mikroservis arasında iletişim sağlamak için API kullanır.

---

## Örnek Bir REST API Kullanımı
Aşağıdaki örnek, bir REST API'nin temel çalışma mantığını göstermektedir.

### 1. API İsteği (Request)
Bir kullanıcı tarayıcıdan bir ürün listesi almak istediğinde, frontend şu isteği gönderebilir:
```http
GET /api/products HTTP/1.1
Host: www.example.com
Authorization: Bearer <token>
```
### 2. API Yanıtı (Response)
API, Backend'deki veritabanından ürünleri alır ve şu şekilde bir JSON yanıt döner:
```http
{
  "products": [
    { "id": 1, "name": "Laptop", "price": 1000 },
    { "id": 2, "name": "Mouse", "price": 25 }
  ]
}
```

# RESTful API ve GraphQL Farkları

## RESTful API Nedir?
**RESTful API** (Representational State Transfer), HTTP protokolü üzerinden veri paylaşımı için kullanılan, mimari bir tasarım ilkesidir. REST API'ler, sistemdeki kaynakları temsil eden URL'ler aracılığıyla çalışır ve genellikle JSON formatında veri döner. Her kaynak, belirli bir URI (Uniform Resource Identifier) ile tanımlanır ve HTTP yöntemleri (GET, POST, PUT, DELETE) kullanılarak bu kaynaklarla işlem yapılır.

---

## GraphQL Nedir?
**GraphQL**, API'lere veri sorgulama ve manipülasyon için kullanılan bir sorgu dilidir. Facebook tarafından geliştirilmiştir ve REST'e alternatif olarak yaygınlaşmıştır. GraphQL, istemcinin sadece ihtiyaç duyduğu veriyi talep etmesine olanak tanır. Tek bir uç nokta (endpoint) üzerinden çalışır ve esnek sorgular sayesinde fazla veri taşınmasını önler.

---

## RESTful API ve GraphQL Karşılaştırması

| **Kriter**              | **RESTful API**                                                      | **GraphQL**                                                       |
|--------------------------|----------------------------------------------------------------------|-------------------------------------------------------------------|
| **Veri Alımı**           | Sabit endpoint'ler üzerinden önceden tanımlı veri döner.            | İstemci, sadece ihtiyaç duyduğu veriyi sorgular.                  |
| **Endpoint Yönetimi**    | Her kaynak için ayrı ayrı endpoint gerektirir.                      | Tek bir endpoint üzerinden çalışır.                              |
| **Veri Fazlalığı**       | Gerekenden fazla veya eksik veri dönebilir (overfetching/underfetching). | İstemci ihtiyacı olan spesifik alanları sorgulayabilir.           |
| **Performans**           | Daha fazla istek ve yanıt gerektirebilir.                           | Daha az istek ve daha az veri aktarımıyla optimize edilebilir.    |
| **Esneklik**             | Daha az esnek; veriler önceden tanımlı şekilde döner.               | Daha esnek; veriler sorgu bazlı özelleştirilebilir.               |
| **Hata Yönetimi**        | HTTP durum kodlarına dayanır.                                        | Hatalar, sorgu yanıtında dönen özel hata mesajlarıyla iletilir.   |
| **Öğrenme Eğrisi**       | Daha yaygın ve öğrenmesi kolaydır.                                   | Daha karmaşık; GraphQL sorgularını öğrenmek gerekir.              |
| **Gerçek Zamanlı Destek**| Doğrudan destek sunmaz, genellikle WebSocket gibi ek araçlar gerekir. | GraphQL, gerçek zamanlı veri için "subscriptions" kullanır.       |
| **N+1 Sorgu Problemi**   | Yoktur.                                                             | Çözülmesi gereken potansiyel bir performans sorununa yol açabilir. |
| **Dokümantasyon**        | Manuel dokümantasyon oluşturulmalıdır.                              | Kendi kendine dokümante olabilen bir yapıya sahiptir.             |

---

## RESTful API ve GraphQL Kullanım Senaryoları

### RESTful API'nin Uygun Olduğu Durumlar:
1. **Basit Sistemler:** API'nin karmaşık sorgular yapması gerekmiyorsa, REST daha kolay uygulanabilir.
2. **Statik Veri:** Verilerin yapısı ve istemci ihtiyaçları zaman içinde çok değişmiyorsa.
3. **Geniş Topluluk Desteği:** REST, daha yaygın olduğundan, ekosistemde daha fazla kaynak bulunur.

### GraphQL'in Uygun Olduğu Durumlar:
1. **Karmaşık ve Özelleştirilmiş Sorgular:** İstemcinin farklı veri setlerine aynı anda erişmesi gerekiyorsa.
2. **Gerçek Zamanlı Uygulamalar:** Örneğin, bir canlı sohbet veya bildirim sistemi.
3. **Esneklik Gerektiren Durumlar:** Farklı istemciler farklı veri ihtiyaçlarına sahipse (ör. web ve mobil istemciler).

---

## Örnek Karşılaştırma

### RESTful API:
Bir kullanıcı profili ve bu kullanıcının yazdığı gönderileri almak için:
1. Kullanıcı verisini almak için `/users/:id` endpoint'i çağrılır.
2. Kullanıcının gönderilerini almak için `/users/:id/posts` endpoint'i çağrılır.

Bu, iki ayrı istek gerektirir.

```http
GET /users/123
```
Yanıt;
```http
{
  "id": 123,
  "name": "John Doe",
  "email": "john@example.com"
}
```
```http
GET /users/123/posts
```
Yanıt;
```http
[
  { "id": 1, "title": "My First Post", "content": "Hello world!" },
  { "id": 2, "title": "GraphQL Rocks", "content": "GraphQL is amazing!" }
]
```
### GraphQL:
Aynı veriyi tek bir sorgu ile alabilirsiniz:
```http
query {
  user(id: 123) {
    name
    email
    posts {
      title
      content
    }
  }
}
```http
{
  "data": {
    "user": {
      "name": "John Doe",
      "email": "john@example.com",
      "posts": [
        { "title": "My First Post", "content": "Hello world!" },
        { "title": "GraphQL Rocks", "content": "GraphQL is amazing!" }
      ]
    }
  }
}
```
Özet
RESTful API, basit ve yaygın bir standart olup, özellikle iyi tanımlı endpoint'lere sahip uygulamalarda başarılıdır.
GraphQL, esneklik ve özelleştirme gerektiren uygulamalarda daha etkili bir çözüm sunar.
Her iki yaklaşımın da güçlü ve zayıf yönleri vardır; seçim, projenin ihtiyaçlarına ve ölçeğine bağlıdır.

## Ek Kaynaklar

- [RESTful API Nedir?](https://restfulapi.net/)  
  REST mimarisi ve RESTful API'nin temel prensiplerini öğrenmek için kapsamlı bir rehber.

- [GraphQL Resmi Sitesi](https://graphql.org/)  
  GraphQL'in resmi sitesi; temel bilgiler, dokümantasyon ve örnekler içerir.

- [REST vs. GraphQL - Aralarındaki Farklar](https://www.howtographql.com/basics/3-big-picture/)  
  REST ve GraphQL arasındaki temel farkları ve kullanım alanlarını açıklayan ayrıntılı bir karşılaştırma.

# Swagger ve Postman Gibi Araçlar

## Swagger Nedir?
**Swagger**, API'lerin tasarımı, geliştirilmesi, dokümantasyonu ve test edilmesi için kullanılan popüler bir araçtır. Özellikle **OpenAPI Specification (OAS)** standardını kullanan RESTful API'ler için geliştirilmiştir. Swagger, hem geliştiricilere hem de API kullanıcılarına kolaylık sağlar.

### Swagger'in Temel Özellikleri:
- **API Dokümantasyonu**: Swagger, API uç noktalarını (endpoint), istek/yanıt yapılarını ve parametreleri detaylı şekilde belgeler.
- **Interaktif API Testi**: Swagger UI ile API'yi test edebilir ve sorguları doğrudan arayüz üzerinden çalıştırabilirsiniz.
- **Otomasyon**: Swagger Codegen sayesinde API dokümantasyonundan istemci veya sunucu kodları otomatik olarak üretilebilir.
- **Standartlara Uygunluk**: OpenAPI standardını kullanarak uyumluluğu garanti eder.

### Kullanım Alanları:
- API tasarımı ve dokümantasyonu oluşturmak.
- Takım içi API geliştirme süreçlerini kolaylaştırmak.
- Müşterilere veya üçüncü taraf geliştiricilere API'yi anlamaları için rehber sağlamak.

---

## Postman Nedir?
**Postman**, API geliştirme ve test süreçlerini kolaylaştıran bir başka güçlü araçtır. REST, GraphQL, SOAP ve diğer API türlerini destekler. API geliştirme döngüsünün her aşamasında kullanılabilecek kapsamlı bir araçtır.

### Postman'in Temel Özellikleri:
- **API Testi ve Debugging**: İstekler (requests) oluşturarak API'yi test edebilir, yanıtları (responses) gözlemleyebilir ve hata ayıklayabilirsiniz.
- **Kolay Kullanıcı Arayüzü**: Kullanıcı dostu bir arayüz ile karmaşık API'leri test etmek kolaydır.
- **Koleksiyonlar (Collections)**: İlgili API isteklerini organize etmek için koleksiyonlar oluşturabilir ve paylaşabilirsiniz.
- **Otomasyon**: Testleri otomatikleştirmek ve sürekli entegrasyon (CI) süreçlerine entegre etmek mümkündür.
- **API Simülasyonu (Mocking)**: Henüz tamamlanmamış API'ler için simülasyonlar oluşturabilir ve test yapabilirsiniz.

### Kullanım Alanları:
- API isteklerini hızlıca test etmek.
- Otomatik API test senaryoları hazırlamak.
- API entegrasyonları sırasında debugging yapmak.
- API'ler için simülasyonlar oluşturmak ve paylaşmak.

---

## Swagger ve Postman Arasındaki Farklar

| **Özellik**                  | **Swagger**                                         | **Postman**                                        |
|-------------------------------|----------------------------------------------------|---------------------------------------------------|
| **Amaç**                     | API tasarımı ve dokümantasyonu                     | API testi, debugging ve otomasyon                 |
| **Interaktif Kullanım**       | Swagger UI ile API dokümantasyonundan teste geçiş | Postman uygulaması ile istek oluşturma ve test    |
| **Kod Üretimi**               | API dokümantasyonundan istemci/sunucu kodu üretir | Kod üretme desteği yoktur                         |
| **Mock API Desteği**          | Sınırlı                                           | Güçlü mocking özellikleri                        |
| **Desteklediği API Türleri**  | Ağırlıklı olarak RESTful API                       | REST, GraphQL, SOAP, WebSocket                   |
| **Kullanım Kolaylığı**        | API tasarımı ve entegrasyon odaklıdır             | Geliştirici dostu, test odaklı bir arayüz sunar   |

---

## Kullanım Senaryoları:
1. **Swagger**:
   - API'lerin belgelenmesi ve anlaşılır bir şekilde sunulması gerektiğinde.
   - Otomatik kod üretimi ve OpenAPI Specification desteği gerektiğinde.

2. **Postman**:
   - API testleri yapmak ve hata ayıklamak için.
   - API entegrasyonu sırasında debugging ve simülasyon ihtiyaçlarında.
   - Birden fazla API isteğini organize etmek ve paylaşmak için.

---

## Örnek Kullanımlar

### Swagger Örneği:
Bir API endpoint'i dokümante etmek için Swagger'da bir OpenAPI tanımı:
```yaml
paths:
  /users:
    get:
      summary: Kullanıcı listesini al.
      responses:
        '200':
          description: Başarılı
          content:
            application/json:
              schema:
                type: array
                items:
                  type: object
                  properties:
                    id:
                      type: integer
                    name:
                      type: string
```
### Postman Örneği:

**URL:** https://api.example.com/users

**HTTP Yöntemi:** `POST`
**Gönderilecek Veri:**
```http
{
  "name": "John Doe",
  "email": "john@example.com"
}
```
## Özet

- **Swagger**: API'lerin tasarımını, dokümantasyonunu ve entegrasyonunu kolaylaştırır. Özellikle **OpenAPI Specification** uyumlu API geliştirme projelerinde yaygındır.

- **Postman**: API geliştirme ve test süreçlerinde güçlü bir araçtır. Mock API oluşturma, debugging ve test otomasyonu gibi özellikler sunar.

- **Genel**: Her iki araç da modern API geliştirme süreçlerinin ayrılmaz bir parçasıdır ve genellikle bir arada kullanılır.

## Ek Kaynaklar

- [Swagger Resmi Sitesi](https://swagger.io/)  
  API tasarımı, dokümantasyonu ve testleri için Swagger'ın resmi sitesi.

- [Postman Resmi Sitesi](https://www.postman.com/)  
  API test ve geliştirme aracı olan Postman'ın resmi sitesi.

- [Swagger vs. Postman - Hangisi Ne İçin Kullanılmalı?](https://blog.postman.com/swagger-vs-postman/)  
  Swagger ve Postman arasındaki farkları açıklayan bir yazı.

# Backend Nedir, Frontend ile Nasıl İletişim Kurar?

## Backend Nedir?
Backend, bir uygulamanın arka planda çalışan, kullanıcı tarafından doğrudan görülmeyen kısmıdır.  
Genellikle aşağıdaki bileşenlerden oluşur:

- **Sunucu (Server):** Gelen istekleri işler ve uygun yanıtları döner.
- **Veritabanı (Database):** Verileri saklar ve yönetir.
- **Uygulama Mantığı:** İş kurallarını ve veri işleme süreçlerini yönetir.
- **API (Application Programming Interface):** Backend ile frontend arasındaki iletişimi sağlar.

Backend, web ve mobil uygulamalarda **Python (Django, Flask), JavaScript (Node.js), PHP, Java (Spring), C# (.NET)** gibi dillerle geliştirilir.

---

## Backend ve Frontend Nasıl İletişim Kurar?
Frontend (kullanıcının gördüğü arayüz) ve backend (verilerin işlendiği kısım) **API’ler** aracılığıyla iletişim kurar.  

### 1. **Frontend’den Backend’e İstek (Request) Gönderme**
- Kullanıcı, frontend üzerinden bir işlem yapar (örneğin, form doldurup gönderir).
- Bu işlem, HTTP istekleri aracılığıyla backend'e iletilir.
- HTTP Yöntemleri:
  - `GET` → Veri çekme
  - `POST` → Veri gönderme
  - `PUT` → Veri güncelleme
  - `DELETE` → Veri silme

**Örnek İstek (Request) - Kullanıcı Kaydetme:**
```json
{
  "name": "Jane Doe",
  "email": "jane.doe@example.com"
}
```
Backend İsteği İşler ve Yanıt (Response) Döner
Backend, gelen isteği işler (veriyi işler, doğrulama yapar, veritabanına kaydeder vb.).
Yanıt olarak frontend'e genellikle JSON veya XML formatında veri döner.
Örnek Yanıt (Response):
```json
{
  "status": "success",
  "message": "Kullanıcı başarıyla kaydedildi."
}
 Frontend Yanıtı Kullanıcıya Gösterir
```

#Backend’den gelen yanıt frontend tarafından işlenir.
Kullanıcıya bir bildirim gösterilir veya ekran güncellenir.
Backend ile Frontend İletişim Yöntemleri

##🟢 RESTful API
Backend ile frontend arasındaki en yaygın iletişim yöntemidir.
JSON veya XML formatında veri iletilir.
HTTP protokolü kullanılarak çalışır.

##🔵 GraphQL
Daha esnek ve optimize veri sorgulama sağlar.
İstemci, sadece ihtiyacı olan veriyi çekebilir.
Tek bir endpoint üzerinden çalışır.

##🟠 WebSocket
Gerçek zamanlı veri iletişimi sağlar.
Sohbet uygulamaları, canlı skorlar ve bildirimler için kullanılır.
Sürekli açık bağlantı ile çift yönlü veri aktarımı yapar.
