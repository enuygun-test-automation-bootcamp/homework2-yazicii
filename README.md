# homework2
##JUnit nedir?
Java tabanlı kodların test edilmesi için kullanılan bir Unit Test – Birim Testi kütüphanesidir.
Junit kütüphanesi projemize pom.xml dosyasına eklenerek kullanılır.
```<dependency>
<groupId>junit</groupId>
<artifactId>junit</artifactId>
<version>4.13.2</version>
<scope>test</scope>
</dependency>
```
##Unit Test nedir?
Unit test veya birim testi programları oluşturulan alt parçaların-birimlerin test edilmesidir.
##Junit Test Notasyonları
- @BeforeClass : Bütün testler başlamadan önce çalışacak metottur.
- @AfterClass : Bütün testler bittikten sonra çalışacak metottur.
- @Before : Before notasyonu da test adımlarından önce başlamaktadır.Veri okuması ve testin öncesinde yapılması gereken işlemler test adımlarını hızlandırmak için yani zamandan tasarruf etmek için bu metot da tanımlanır. Model ve nesnelerine atama işlemlerinin burada gerçekleştiririz.
- @After : After notasyonu ise test metodlarından sonra çalışmaktadır. After notasyonun da en çok yapılan işlem, test metodlarından sonra her seferinde atanan değerlere null değerler gönderilmektedir.
- @Test : Test notasyonu içerisinde test case’mizde yer alacak adımları tanımlarız.
- @Ignore : Yazdığımız test metotlarının çalıştırılmasını istemiyorsak bu amaç ile kullanabileceğimiz bir notasyondur.
