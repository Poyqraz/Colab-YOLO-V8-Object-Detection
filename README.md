# V8-Object-Detection

+ yolov8 github: https://github.com/ultralytics/ultralytics
+ yolov8 docs: https://docs.ultralytics.com/quickstart/

# DATA HAZIRLAMA AŞAMASI #

1) Google Drive'da "yolov8" isimli bir klasör oluşturunuz.

2) "yolov8" klasörünün içine sırasıyla "data,output,test_images" klasörlerini oluşturunuz.

3) data klasörünün içine etiketleme için kullandığınız resimleri ve etiketleme eylemi sonrası oluşan (etiket koordinatlarını içeren) .txt dosyalarını yükleyiniz.

4)Paylaştığım dataset.yaml dosyasını, oluşturduğunuz "yolov8" klasörünün içine yükleyiniz.

5)Paylaştığım colab kodlarından ilk 5 hücreyi çalıştırınız.

!! Buraya kadar herhangi sorun ile karşılaşmadıysanız devam edebilirsiniz. !!

# dataset.yaml #


6) Paylaşmış olduğum dataset.yaml dosyasını herhangi bir text editör ile açınız.

7) train ve val klasörlerinin dosya yolları buraya kadar yazdığım anlatımımı doğru bir şekilde uygulamış iseniz, doğrudur.

8) Gelelim "classes" bölümüne

9) "nc:" yazan kısımın önüne etiketlemede kaç tane class kullandıysanız o kadar değer yazınız.

10) "names" yazan kısımın önüne ise (burası önemli) etiketleme sonucu oluşan -classes.txt- dosyasında yazan sıra ile " örnek olarak ['human',[car]  " formatında classlarınızı yazınız.

# TRAIN (EĞİTİM) AŞAMASI


11) Ultralytics kütüphanemizin kontrolleri yapıldıktan sonra şu bilgileri vermekte fayda var.

12) Eğitim aşamasının başlayacağı 7.hücreyi açıklamak gerekirse ![indir](https://github.com/Poyqraz/V8-Object-Detection/assets/48729799/fa173de1-9f60-49cb-a8f1-0cc0058ecd69)

13) Sırasıyla; görevimiz(task) tespit olarak, modumuz(train) eğitim olarak, modelimiz yolonun v8m modeli olarak, datanın işleneceği dosya yolunu, epochs ise modelizi kaç basamakla eğitmek istediğinizi, training_results ise train sonucunu hangi isimle kaydetmek istediğinizi temsil etmektedir.

14) Eğitim aşaması kullandığınız modele ve eğitim basamağına göre değişiklik gösterebilir.

15) Diğer hücreler , hücre üstlerinde yorum satırı olarak anlatışmıştır.

------------------------------------------------------------------------------------------------------------------------------------------------------

!! Sadece test yapmak için oluşturulmuştur. Hiçbir art niyet ve çıkar gözetilmemektedir. Oluşabilecek herhangi bir sorunun sorumluluğu üslenmiyoruz. !!
