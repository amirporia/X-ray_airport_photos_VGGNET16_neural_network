# https-github.com-amirporia-X-Ray/Airport
Abstract:

  this project is made for Bachelor Project , deep learning with python 
  for this project were Studied for one week 
  Unfortunately, the current X-ray baggage image database is not big enough in count and diversity for CNN model training.
  Finally, to verify whether the generated images belong to its corresponding class or not, a cross-validation scheme based on a CNN model is implemented. The experimental results   show that most of the generated images can be classified correctly by the CNN model. This implies that the generated prohibited item images can be used as the extended samples     to augment an X-ray image database.
  
  
  
Introduction:


  X-ray security baggage screening systems are widely installed in almost every station/airport to ensure public transport security. Support Vector Machine (SVM) and CNN were       combined together for making X-ray baggage image classification and detection.  proposed an attention-based CNNmodel of detecting the prohibited items in X-ray images.
  Certainly, a big database with enough image samples is indispensable for training the above deep models. Unfortunately, a desirable X-ray image database suitable for training     CNN models has not been reported.
  Usually, it is difficult to collect enough X-ray images containing the prohibited items with great variations in pose and scale. The insufficiency of training images actually     results in a great difficulty for developing reliable deepbased approaches suitable for prohibited item detection.
  
  
DataBase:

  Here, all the X-ray prohibited item images are collected by a X-ray machine working at our Lab. They consist of several item classes, such as handguns, lighters, knives etc.       2 prohibited item classes contain around 180 images.All the images are resized to 96 * 96. Then, we extract prohibited item images using a matting-based method. 
  
  90 * 2 ===> training { dangerous , undangerous }
  
  45 * 2 ===> validate { dangerous , undangerous } 
  
  45 * 2 ===> test { dangerous , undangerous }
  
  
sources that were taken :
  - BOOK , deep learning with python , François Chollet
