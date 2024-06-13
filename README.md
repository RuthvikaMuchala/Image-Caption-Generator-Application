# Image Caption Generator Application

*Image caption generator is a model which generates caption based on the features present in the input image.*

- **Overview :** The basic working of the project is that the features are extracted from the images using pre-trained VGG16 model and then fed to the LSTM
model along with the captions to train. The trained model is then capable of generating captions for any images that are fed to it.

- **Dataset :**  The dataset consists of around 8091 images along with 5 captions for each images.
  - Kaggle Source : https://www.kaggle.com/datasets/adityajn105/flickr8k
  - Drive link : https://drive.google.com/file/d/1Gikp74XpqGggphWM80esOVMG9v3XvmNn/view?usp=sharing

- **Analysis :** After the model is trained we have to test the models prediction capabilities on test dataset. Traditional accuracy metric cant be used on
predictions. For text evaluations we have a metric called as *BLEU Score*. BLEU stands for Bilingual Evaluation Understudy, it is a score for
mparing a candidate text to one or more reference text.

- **Sample Output :** <br>
 ![image](https://github.com/RuthvikaMuchala/Image-Caption-Generator-Application/assets/92968569/0a1f7776-51c7-4631-9ffd-060d7a47db76)


