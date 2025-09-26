# 🐶🐱 Dogs vs Cats – Akbank Derin Öğrenme Bootcamp

## Giriş
Bu projede, **CNN (Convolutional Neural Network)** kullanarak kedi ve köpek görüntülerini sınıflandıran bir model geliştirdim. Amaç, görüntü sınıflandırması ve derin öğrenme pratiği kazanmak, veri ön işleme, model oluşturma ve değerlendirme süreçlerini öğrenmektir.

## Veri Seti ve Önişleme
- Görüntüler **train**, **validation** ve **test** setlerine ayrıldı.  
- Veri artırma (rotation, flip, zoom, color jitter) ve normalizasyon yapıldı. Bu sayede model daha çeşitli görüntülerle eğitildi ve overfitting riski azaltıldı.  

## Model ve Eğitim
- **CNN tabanlı bir model** oluşturdum:
  - Convolutional ve Pooling katmanları ile özellik çıkarımı  
  - Dense katman ve Dropout ile sınıflandırma ve overfitting kontrolü  
  - ReLU ve Sigmoid aktivasyonları  
- Model **Adam optimizer** ve **binary crossentropy** ile derlendi.  
- Eğitim sırasında **accuracy ve loss** grafikleri izlendi.  

## Hiperparametre Optimizasyonu
- Keras Tuner kullanarak **katman sayısı, filtre sayısı, dropout oranı ve learning rate** gibi parametreleri optimize ettim.  
- En iyi hiperparametreler seçildi ve model bu parametrelerle eğitildi.

## Değerlendirme
- **Validation accuracy**: ~%75  
- Confusion matrix ve Grad-CAM ile modelin performansı ve hangi bölgeleri dikkate aldığı görselleştirildi.  
- Eğitim ve doğrulama süreçleri takip edilerek overfitting kontrolü sağlandı.

## Gelecek Çalışmalar
- Transfer Learning ile modelin güçlendirilmesi  
- Gerçek zamanlı sınıflandırma  
- Streamlit veya başka bir arayüz ile deployment  
- TensorBoard veya Weights & Biases ile model izleme  

## Kaggle Notebook
Dataset: 
Kaggle: 
