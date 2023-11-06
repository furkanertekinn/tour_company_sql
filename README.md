# Techcareer SQL Bootcamp Bitirme Projesi

## `1.Adım`
### Projeye başlangıç olarak bir diyagramdan başlamak istedim. Oluşturduğum diyagram ile genel şemanın, veri tiplerinin, kolonların ve hangi tablonun hangisiyle bağlantısı olduğunu genel anlamda görerek, işimi kolaylaştırmak istedim. Oluşturduğum tablolardaki kolonların ne olacağını belirledikten sonra yanlarına veri tiplerini yazdım ve tablo ilişkilendirmelerini belirledim.
![Screenshot 2023-11-06 163114](https://github.com/furkanertekinn/tour_company_sql/assets/96014529/c9bb33f1-7dff-438b-9916-ca1c6820d701)

## `2.Adım`
### Bu adımda ise SQL Server'ı açarak projemi artık uygulamaya dökmeye başladım. TourCompany adında DB oluşturdum. Ben New Query yoluyla manuel bir şekilde oluşturmayı tercih ettim ama DB üzerine sağ tıklayıncada başka bir seçenek New Database olarak çıkmaktadır.
<> ![Screenshot 2023-11-06 164144](https://github.com/furkanertekinn/tour_company_sql/assets/96014529/af320494-b21d-4aac-99fa-42291e59a02b)

<> ![Screenshot 2023-11-06 164420](https://github.com/furkanertekinn/tour_company_sql/assets/96014529/d44c0844-5a4c-4b44-8f33-221746fda4fc)

## `3.Adım`
### Bu adımda tabloları oluşturduktan sonra kolonları oluşturmaya geldim. Kolonları aynı tabloları oluşturduğum gibi New Query yoluyla manuel bir şekilde oluşturmayı tercih ettim ama Table üzerine sağ tıklandığında başka bir seçenek New > Table olarak çıkmaktadır.
<>![Screenshot 2023-11-06 172509](https://github.com/furkanertekinn/tour_company_sql/assets/96014529/d549b7a1-da06-46c1-913b-60cd8feb469c)

<>![Screenshot 2023-11-06 172528](https://github.com/furkanertekinn/tour_company_sql/assets/96014529/cad01da8-71d5-47c6-a411-eca65915762d)

## `4.Adım`
### Gerçekleştirdiğimiz adımlar sonrasında Database Diagramını oluşturdum. Tabloları birbiriyle ilişkilendirdim. FK'leri belirledim.
<>![Screenshot 2023-11-06 173000](https://github.com/furkanertekinn/tour_company_sql/assets/96014529/4bc6e3d1-8dbd-4596-ba1f-486e1dc7014f)

<>

## `5.Adım`
### Tablolara veri girişi yaptım. Bunları gerçekleştirirken komutları kullanmak benim için tabi ki önemli oldu. Insert, update, delete...
<>![Screenshot 2023-11-06 215836](https://github.com/furkanertekinn/tour_company_sql/assets/96014529/ffc6b596-4e89-4e53-af3f-d7972e690b33)

## '6.Adım'
### Devamında her seferinde bu şekilde veri girişi yapmak / güncellemek / silmek yerine Stored Procedures kısacası SP yazmanın daha mantıklı olduğunu düşündüm. Çünkü daha kullanışlı, hızlı ve kolay olacaktı. Backend tarafında da kod kalabalığını önleyerek, daha düzenli ve okunaklı hale getirecekti. SP yazarken insert, update, delete dışında create, alter kullanılarak da yazılabilir.
<>![Screenshot 2023-11-06 222514](https://github.com/furkanertekinn/tour_company_sql/assets/96014529/8de86c52-70b8-4fb2-a5ee-94c8cb19fe2c)

<>![Screenshot 2023-11-06 222718](https://github.com/furkanertekinn/tour_company_sql/assets/96014529/f7f9c3d3-d03b-443d-a8c6-daf509774adf)

<>![Screenshot 2023-11-06 222746](https://github.com/furkanertekinn/tour_company_sql/assets/96014529/36d56386-05dd-4a48-8f80-22305a3edcb7)

<>![Screenshot 2023-11-06 222801](https://github.com/furkanertekinn/tour_company_sql/assets/96014529/c625676e-5251-41f3-8a79-e07ef268bd28)

<>![Screenshot 2023-11-06 225306](https://github.com/furkanertekinn/tour_company_sql/assets/96014529/722a5874-7ef3-4b2b-9274-3b0e70d9576c)

## '7.Adım'
### Şirkette 65 yaş üstüne %15 indirim olduğu için sık sık ekrana 65 yaşından büyük turistleri getirmek gerekmektedir. Bunun için ise sadece görüntüden ibaret olan Views'ı kullandım. Her seferinde bu uzun sorguyu yazmak yerine, sorguyu bir View haline getirerek daha kullanışlı bir yapı oluşturdum. Ek olarak Views'larda insert, update, delete komutları kullanılmaz.
<>![Screenshot 2023-11-06 223840](https://github.com/furkanertekinn/tour_company_sql/assets/96014529/2f116575-6475-4724-b3ab-8342760cee38)

<>![Screenshot 2023-11-06 223921](https://github.com/furkanertekinn/tour_company_sql/assets/96014529/686b31bb-e7d4-4e8f-8530-7fef90f5f13b)



