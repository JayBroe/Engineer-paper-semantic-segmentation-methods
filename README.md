# Engineer-paper-semantic-segmentation-methods

TL;DR PL

W niniejszej pracy dokonano opisu oraz porównania dwóch metod segmentacji semantycz-
nej terenu. Pierwsza z nich wykorzystuje głębokie sieci neuronowe (architektury DenseNet,
SegNet oraz AdapNet będącą zmodyfikowaną wersją architektury ResNet), druga zaś wyko-
rzystuje metodę klasyfikatorów opartą o algorytm RandomForest. Praca obejmuje teoretyczne
informacje poruszonego zagadnienia oraz jej praktyczne zastosowanie. Przywołuje także rys
historyczny omawianych technologii. Zarówno część działająca w oparciu o sieć neuronową jak
i klasyfikatory zostaną zaprezentowane z użyciem grafik, schematów działania oraz parame-
trów opisujących jakość ich klasyfikacji. W przypadku pierwszej metody sprawdzono, na ile
odmienny w efektywności jest zakodowanie wysokości na dwóch róznych kanałach w przypadku
zapisu informacji w formacie HSV. Druga metoda natomiast prezentuje wyniki segmentacji
semantycznej dla modeli RGB, oraz HSV. Rozstrzygnięto również, która metoda okazała się
bardziej efektywna.

TL;DR ENG

This thesis presents description and comparison of two methods of semantic segmentation.
First of them uses deep neural networks (architectures DenseNet, SegNet and AdapNet),
whereas the second one is based on RandomForest classifiers. The thesis includes theoretical
informations about discussed questions and it’s practical usage. It also mentions historical
view of the considered technologies. Also a part based of convolutional neural networks and
classifiers will be presented by graphics, schemes and parameters which describe the quality
of classification. In case of the first method it was examined, which way of notation of map
elevation is better in HSV format. Whereas, the second method presented results of semantic
segmentation for RGB and HSV models. It was also decided which method is more effective.
