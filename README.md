# makerere-fall-armyworm-crop
Computer Vision - Agriculture

Fall armyworm is a devastating pest in Africa, where it has no natural predators - African farmers say the pest causes average maize losses of 31% annually. Maize is the most widely grown crop in Africa and a staple for around half the continent’s people - over 300 million Africans depend on the crop for food and nutritional security. For smallholder farmers in particular, maize is popular for its wide adaptability, valuable by-products and high yields.

Because of this reliance on staple crops for food security, Viral pests and diseases like fall armyworm are one of the leading causes of food insecurity and poverty in Africa. Thus there is an urgent need to design early intervention mechanisms to help prevent crop losses for smallholder farmers.

In this project, the objective is to classify if a plant has been affected by a fall armyworm. 
see more: https://zindi.africa/competitions/makerere-fall-armyworm-crop-challenge

# Method
1. downloading data 
2. preprocessing
3. classification

# Downloading data
see preprocessingV2.ipynb

# Preprocessing
see preprocessing.ipynb
step 1 : rotate images to keep same alignement
step 2 : resize images
step 3 : split into train, val, test
step 4 : apply augmentation on training data by affine transformations

# Classifcation
see classification.ipynb
training MobileNetV2 on various configurations
score: AUC 0.9983
