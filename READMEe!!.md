PyTest'deki dekoratörler, test fonksiyonlarınızın çalışmasını kontrol etmenize, yapılandırmanıza ve özelleştirmenize olanak tanıyan güçlü araçlardır. İşlevsellikleri, kodunuzu daha okunaklı, daha sürdürülebilir ve daha yeniden kullanılabilir hale getirir.

İşte PyTest'deki en yaygın kullanılan dekoratörlerden bazıları:

@pytest.fixture: Bu dekoratör, test fonksiyonlarına bağımlılıkları enjekte etmek için kullanılır. Fixture'lar, örneğin veritabanı bağlantıları veya başka kaynaklar gibi testlerinizde kullanmanız gereken ortamları oluşturmanıza olanak tanır. Fixture'lar, özellikle karmaşık test senaryolarında çok yararlıdır.

@pytest.mark.parametrize: Bu dekoratör, tek bir test fonksiyonunu farklı parametrelerle çalıştırmanızı sağlar. Bu, özellikle birkaç benzer test senaryosu için kod tekrarından kaçınmak istediğinizde yararlıdır.

@pytest.mark.skip: Bu dekoratör, belirli bir testin çalışmasını geçici olarak atlamak için kullanılır. Örneğin, henüz çözülmeyen bir hata varsa veya başka bir nedenle testin şu anda çalışmaması gerekiyorsa bu dekoratörü kullanabilirsiniz.

@pytest.mark.xfail: Bu dekoratör, belirli bir testin bilinen bir hata durumunda başarısız olması gerektiğini belirtmek için kullanılır. Bu, kodunuzdaki hataları izlemek ve düzeltmek için çok yararlıdır.

@pytest.mark.timeout: Bu dekoratör, bir testin belirli bir sürede tamamlanması gerektiğini belirtmek için kullanılır. Bu, özellikle testlerinizi yavaşlatan veya sonsuz döngüye neden olan hataları izlemek için yararlıdır.

@pytest.mark.parametrize: Bu dekoratör, aynı test fonksiyonunu birden fazla giriş parametresiyle çalıştırmak için kullanılır. Örneğin, bir hesap makinesi işlevini test etmek isterseniz, birçok giriş parametresiyle test edebilirsiniz.

@pytest.fixture(scope="module"): Bu dekoratör, bir modül düzeyindeki ortamları oluşturmak için kullanılır. Bu, bir test paketi veya uygulama için tek bir ortamın oluşturulmasını sağlar.

Bu, yalnızca en yaygın kullanılan dekoratörlerin bir kısmıdır ve PyTest'in daha fazla dekoratörü vardır.
