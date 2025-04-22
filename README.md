# Derin Öğrenme Eğitimi
Derin Öğrenme Modellerini Eğitme 
Nvidia ekran kartına sahip öğrenciler, CUDA ve cuDNN kurulumlarını gerçekleştirerek kişisel bilgisayarlarında derin öğrenme modelleri eğiteceklerdir. Mac veya farklı marka bilgisayar kullanan öğrenciler ise, kendi grafik kartlarını kullanarak model eğitimi yapmayı öğrenecek ve bu süreci kendi cihazlarında uygulayacaklardır. Eğitim sürecinde YOLO modeli kullanılmayacak, bunun yerine evrişimli sinir ağı (CNN) katmanları elle oluşturularak temel bir model geliştirilecektir. Model, sekiz farklı sınıfı ayırt edebilecek şekilde tasarlanacak ve bazı sınıflar birbirine benzer özellikler taşıyacaktır. Kullanılacak görsellerde, bazı fotoğraflarda içerisinde birden fazla nesne bulunmasına dikkat edilecektir.

**İLK SONUÇLAR**

Kullanılan cihaz: cpu
Epoch 1/5, Loss: 2.0911
Epoch 2/5, Loss: 2.0750
Epoch 3/5, Loss: 2.0526
Epoch 4/5, Loss: 1.9957
Epoch 5/5, Loss: 1.8448

Sınıflandırma Raporu:
              precision    recall  f1-score   support

           0       0.57      1.00      0.73        23
           1       0.72      0.96      0.82        24
           2       0.48      0.91      0.63        23
           3       0.48      0.95      0.63        21
           4       0.00      0.00      0.00        35
           5       0.53      1.00      0.69        21
           6       1.00      0.07      0.13        28
           7       0.00      0.00      0.00        25

    accuracy                           0.55       200
   macro avg       0.47      0.61      0.45       200
weighted avg       0.45      0.55      0.41       200

/usr/local/lib/python3.11/dist-packages/sklearn/metrics/_classification.py:1565: UndefinedMetricWarning: Precision is ill-defined and being set to 0.0 in labels with no predicted samples. Use `zero_division` parameter to control this behavior.
  _warn_prf(average, modifier, f"{metric.capitalize()} is", len(result))
/usr/local/lib/python3.11/dist-packages/sklearn/metrics/_classification.py:1565: UndefinedMetricWarning: Precision is ill-defined and being set to 0.0 in labels with no predicted samples. Use `zero_division` parameter to control this behavior.
  _warn_prf(average, modifier, f"{metric.capitalize()} is", len(result))
/usr/local/lib/python3.11/dist-packages/sklearn/metrics/_classification.py:1565: UndefinedMetricWarning: Precision is ill-defined and being set to 0.0 in labels with no predicted samples. Use `zero_division` parameter to control this behavior.
  _warn_prf(average, modifier, f"{metric.capitalize()} is", len(result))



![image](https://github.com/user-attachments/assets/c7c6499f-1b11-47e1-808a-1254b713fe5a)



**İKİNCİ SONUÇLAR**
Kullanılan cihaz: cpu
Epoch 1/5, Loss: 2.1078
Epoch 2/5, Loss: 2.0767
Epoch 3/5, Loss: 2.0610
Epoch 4/5, Loss: 1.9888
Epoch 5/5, Loss: 1.7856

Sınıflandırma Raporu:
              precision    recall  f1-score   support

           0       0.83      0.83      0.83        23
           1       0.00      0.00      0.00        24
           2       0.95      0.78      0.86        23
           3       0.00      0.00      0.00        21
           4       1.00      0.06      0.11        35
           5       0.17      1.00      0.29        21
           6       0.94      0.61      0.74        28
           7       1.00      0.52      0.68        25

    accuracy                           0.45       200
   macro avg       0.61      0.47      0.44       200
weighted avg       0.65      0.45      0.43       200

/usr/local/lib/python3.11/dist-packages/sklearn/metrics/_classification.py:1565: UndefinedMetricWarning: Precision is ill-defined and being set to 0.0 in labels with no predicted samples. Use `zero_division` parameter to control this behavior.
  _warn_prf(average, modifier, f"{metric.capitalize()} is", len(result))
/usr/local/lib/python3.11/dist-packages/sklearn/metrics/_classification.py:1565: UndefinedMetricWarning: Precision is ill-defined and being set to 0.0 in labels with no predicted samples. Use `zero_division` parameter to control this behavior.
  _warn_prf(average, modifier, f"{metric.capitalize()} is", len(result))
/usr/local/lib/python3.11/dist-packages/sklearn/metrics/_classification.py:1565: UndefinedMetricWarning: Precision is ill-defined and being set to 0.0 in labels with no predicted samples. Use `zero_division` parameter to control this behavior.
  _warn_prf(average, modifier, f"{metric.capitalize()} is", len(result))


  ![image](https://github.com/user-attachments/assets/938e15f2-3fee-4b4d-9dc9-3c65d08d3e85)



  **ÜÇÜNCÜ SONUÇLAR**
  Kullanılan cihaz: cpu
Epoch 1/5, Loss: 2.1012
Epoch 2/5, Loss: 2.0770
Epoch 3/5, Loss: 2.0632
Epoch 4/5, Loss: 2.0110
Epoch 5/5, Loss: 1.8734

Sınıflandırma Raporu:
              precision    recall  f1-score   support

           0       1.00      0.70      0.82        23
           1       1.00      0.04      0.08        24
           2       1.00      0.70      0.82        23
           3       1.00      0.33      0.50        21
           4       0.27      1.00      0.42        35
           5       0.61      0.81      0.69        21
           6       1.00      0.07      0.13        28
           7       0.00      0.00      0.00        25

    accuracy                           0.47       200
   macro avg       0.73      0.46      0.43       200
weighted avg       0.71      0.47      0.42       200

/usr/local/lib/python3.11/dist-packages/sklearn/metrics/_classification.py:1565: UndefinedMetricWarning: Precision is ill-defined and being set to 0.0 in labels with no predicted samples. Use `zero_division` parameter to control this behavior.
  _warn_prf(average, modifier, f"{metric.capitalize()} is", len(result))
/usr/local/lib/python3.11/dist-packages/sklearn/metrics/_classification.py:1565: UndefinedMetricWarning: Precision is ill-defined and being set to 0.0 in labels with no predicted samples. Use `zero_division` parameter to control this behavior.
  _warn_prf(average, modifier, f"{metric.capitalize()} is", len(result))
/usr/local/lib/python3.11/dist-packages/sklearn/metrics/_classification.py:1565: UndefinedMetricWarning: Precision is ill-defined and being set to 0.0 in labels with no predicted samples. Use `zero_division` parameter to control this behavior.
  _warn_prf(average, modifier, f"{metric.capitalize()} is", len(result))


  ![image](https://github.com/user-attachments/assets/d51d7b77-7d45-4fc6-a254-89836d2e3ad8)


  ***SON SONUÇLAR***

  Kullanılan cihaz: cpu
Epoch 1/5, Loss: 2.1160
Epoch 2/5, Loss: 2.0777
Epoch 3/5, Loss: 2.0728
Epoch 4/5, Loss: 2.0577
Epoch 5/5, Loss: 2.0195

Sınıflandırma Raporu:
              precision    recall  f1-score   support

           0       0.15      1.00      0.27        23
           1       0.00      0.00      0.00        24
           2       0.00      0.00      0.00        23
           3       0.00      0.00      0.00        21
           4       0.93      0.77      0.84        35
           5       1.00      0.76      0.86        21
           6       1.00      0.18      0.30        28
           7       1.00      0.04      0.08        25

    accuracy                           0.36       200
   macro avg       0.51      0.34      0.29       200
weighted avg       0.55      0.36      0.32       200

/usr/local/lib/python3.11/dist-packages/sklearn/metrics/_classification.py:1565: UndefinedMetricWarning: Precision is ill-defined and being set to 0.0 in labels with no predicted samples. Use `zero_division` parameter to control this behavior.
  _warn_prf(average, modifier, f"{metric.capitalize()} is", len(result))
/usr/local/lib/python3.11/dist-packages/sklearn/metrics/_classification.py:1565: UndefinedMetricWarning: Precision is ill-defined and being set to 0.0 in labels with no predicted samples. Use `zero_division` parameter to control this behavior.
  _warn_prf(average, modifier, f"{metric.capitalize()} is", len(result))
/usr/local/lib/python3.11/dist-packages/sklearn/metrics/_classification.py:1565: UndefinedMetricWarning: Precision is ill-defined and being set to 0.0 in labels with no predicted samples. Use `zero_division` parameter to control this behavior.
  _warn_prf(average, modifier, f"{metric.capitalize()} is", len(result))


  ![image](https://github.com/user-attachments/assets/d4deaaff-65a2-4806-9797-0416526bc9c7)







