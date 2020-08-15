# covid or not
Make cool Corona Virus detection web app on chest X-Ray images from [Pneumonia dataset](https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia "kaggel dataset")<br/>

### Key Highlights:
1- Training on TPU (5 hours on gpu to 4 minutes on TPU!! 😳🤯)<br/>
2- Transfer Learning <br/>
3- Testing three famous CNN architectures (VGG16, InceptionV3 and Xception) 🤓 <br/>
4- Working with GCS <br/>
5- Deploying model as a web app with Anvil<br/>
    [*watch this*](https://www.youtube.com/watch?v=yh0B4HjQxOU&t=58s "anvil intro & tutorial") for making web app <br/>

### Results:
1- VGG16 : *accuracy: 1.0000 - precision: 1.0000 - recall: 1.0000 - val_loss: 0.0325 - val_accuracy: 0.9873 - val_precision: 0.9972 - val_recall: 0.9849*<br/>
2- Inception V3 : *accuracy: 1.0000 - precision: 1.0000 - recall: 1.0000 - val_loss: 0.0933 - val_accuracy: 0.9795 - val_precision: 0.9876 - val_recall: 0.9835*<br/>
3- Xcpetion : *accuracy: 1.0000 - precision: 1.0000 - recall: 1.0000 - val_loss: 0.0620 - val_accuracy: 0.9785 - val_precision: 0.9917 - val_recall: 0.9782*<br/>

### To Run:
Colab notebook is provided, simply run the cells to re produce the results <br/>
For the Web App simply create a quick app on anvil (tutorial link provided above). Client side code is in the colab notebook. Server code is in server file <br/>
Pretrained VGG16 [model weights ](https://drive.google.com/file/d/1EaojfSMs9L2o4P2_9nMFQ8Dr-5Ce-DlL/view?usp=sharing "pre-trained model weights") 
<br/>
<br/>
![image 1 of web app](https://github.com/khawar56/covid-or-not-/master/image/1.png?raw=true)

#### Enjoy Computer Vision 🥂✌️

