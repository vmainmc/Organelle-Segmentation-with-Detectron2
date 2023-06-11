# Organelle-Segmentation-with-Detectron2
Projenin modeli facebook tarafından oluşturulan detectron2 kütüphanesi içerisindeki mask R-CNN modeliydi. Detectron2, end-to-end nesne algılama ve segmentasyon görevlerini gerçekleştirmek için bir dizi popüler model (örneğin Faster R-CNN, Mask R-CNN) ve optimizasyon teknikleri (örneğin deformable convolutions) sunar. Ayrıca, modelleri eğitmek, sonuçları görselleştirmek ve model performansını değerlendirmek için bir dizi kullanışlı araç ve yardımcı işlev içerir.

<img width="334" alt="dete" src="https://github.com/vmainmc/Organelle-Segmentation-with-Detectron2/assets/63164307/d0b2289f-99fb-487c-9526-6e0392f0b2f0">

Veri seti hücre içi resimlerden oluşuyor. Hücre içerisindeki mitokondrilerin tespitini gerçekleştirmek projenin amacıydı.


![testing-011](https://github.com/vmainmc/Organelle-Segmentation-with-Detectron2/assets/63164307/327e8d25-89e0-4773-b114-5ef492f6ea79)

%96 lık bir accuracy ve %70 lik bir jaccard değeri elde edild.(Jaccard değeri segmentasyon maskelerinin alanlarının kesişim oranından elde edilen bir doğruluk metriği)

![projeçıktısı](https://github.com/vmainmc/Organelle-Segmentation-with-Detectron2/assets/63164307/813066b7-dc0e-4346-97df-8194a2b1c1ad)

Resimdeki görüntüler sırasıyla : Orjinal resim - prediction sonuçları - prediction maskesi
