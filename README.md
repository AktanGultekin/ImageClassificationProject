GLOBALAIHUB - IMAGE CLASSIFICATION PROJECT (CIFAR10)

Tensorflow kütüphanesinin Keras uzantısında bulunan Cifar10 adlı görsel veriseti kullanılarak görsel sınıflandırma modeli oluşturuldu. 
Bu veriseti 50000'i eğitim, 10000'i doğrulama olarak toplam 60000 görüntüden oluşmaktadır. 
Bu model eğitilirken birden çok algoritma denendi. Bunların ilki K-Nearest Neighbour algoritmasıdır. Bu algoritma, kullanılan verisetinin kompleks ve büyük çapta bir görsel veriseti olmasından dolayı verimli bir sonuç vermemiş olup, ortaya çıkan modelin doğruluk oranı %30 civarındadır.
Daha sonra bir derin öğrenme algoritması olan CNN (Convolutional Neural Networks) yani evreşimli nöral ağlar kullanıldı. Bu algoritma, model eğitmede oldukça verimli sonuçlar vermiş, ortaya çıkan modelin doğruluk oranı yüzde 86 civarında çıkmıştır. Bu projeden çıkardığım bulgular ise modelin genellikle renk ve boyut itibariyle birbirine benzeyen varlıkları tahmin ederken doğruğunun düşmesidir. Ayrıca görsellerin çekim perspektiflerine göre de 
varlıkların algılanması model açısından tahminlerini zorlamaktadır.
