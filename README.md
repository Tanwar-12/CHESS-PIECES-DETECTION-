# 𝑪𝑯𝑬𝑺𝑺 𝑷𝑰𝑬𝑪𝑬𝑺 𝑫𝑬𝑻𝑬𝑪𝑻𝑰𝑶𝑵 𝒀𝑶𝑳𝑶𝑽5
![TF (2)](https://github.com/Tanwar-12/Chess-Pieces-Detection/assets/110081008/7f75ccfc-b8de-4b52-9a08-eeadffa05eae)

### 𝑶𝒗𝒆𝒓𝒗𝒊𝒆𝒘 : The goal of this project is able to identify chess pieces on a board or in a video using yolov5.
![image](https://github.com/Tanwar-12/Chess-Pieces-Detection/assets/110081008/df740dc6-0aba-4ea9-99f3-01dd8c5c65cf)
![image](https://github.com/Tanwar-12/Chess-Pieces-Detection/assets/110081008/efef9d71-49da-4a24-8d32-297d55f1713f)
### 📁 𝑫𝒂𝒕𝒂𝒔𝒆𝒕 𝑼𝒔𝒆𝒅 :  https://universe.roboflow.com/projects-ehrjz/chess-detection-i0woo
**The dataset consists of 13 classes:**
- 'bishop'
- 'black-bishop'
- 'black-king'
- 'black-knight'
- 'black-pawn'
- 'black-queen'
- 'black-rook'
- 'white-bishop'
- 'white-king'
- 'white-knight'
- 'white-pawn'
- 'white-queen'
- 'white-rook
 ## 𝑫𝒂𝒕𝒂 𝑷𝒓𝒆𝒑𝒂𝒓𝒂𝒕𝒊𝒐𝒏:
  * Create a bounding boxes with the help of label-img And makesense.ai website according to YoloV5.
  * Prepare folder structure that can be accept by YoloV5.
    ## 𝑺𝒕𝒆𝒑𝒔 𝒕𝒐 𝒖𝒔𝒆 𝒀𝒐𝒍𝒐𝒗5:
* Cloning the YoloV5 file from official repository.
* Changing the directory of yolov5
* Installing the dependencies
* Download all versions pre-trained weights.
 ## 𝑺𝒕𝒆𝒑𝒔 𝑩𝒆𝒇𝒐𝒓𝒆 𝑻𝒓𝒂𝒊𝒏𝒊𝒏𝒈 𝑪𝒖𝒔𝒕𝒐𝒎 𝑫𝒂𝒕𝒂𝒔𝒆𝒕:
* Go to yolov5/data/.
* Open data.yaml
* Edit the following inside it:

 1. Training and Validation file path
 2. Number of classes and Class names.

  ## 𝑻𝒓𝒂𝒊𝒏𝒊𝒏𝒈 𝒀𝑶𝑳𝑶𝑽5 𝑴𝒐𝒅𝒆𝒍:
* Set images size 640 with batch of 8.
* Total 606 images for training and 58 images for validation present in 13 classes.
* Train model around 600 epochs .Stopping training early as no improvement observed in last 100 epochs. Best results observed at epoch 201, best model saved as best.pt.
* Visualise the training metrics with the help of tensorboard.
   ## 𝑻𝒆𝒔𝒕𝒊𝒏𝒈 𝑰𝒎𝒂𝒈𝒆𝒔 𝑼𝒔𝒊𝒏𝒈 𝑻𝒆𝒔𝒕 𝑫𝒂𝒕𝒂:
  ![image](https://github.com/Tanwar-12/Chess-Pieces-Detection/assets/110081008/3ae8cfbd-e3fe-4600-8751-5902cc2bc373)

![image](https://github.com/Tanwar-12/Chess-Pieces-Detection/assets/110081008/8e8ca728-c606-46ab-b9b2-efb9774e4594)


## 𝑻𝒆𝒔𝒕𝒊𝒏𝒈 𝑽𝒊𝒅𝒆𝒐 𝑫𝒆𝒎𝒐:


https://github.com/Tanwar-12/Chess-Pieces-Detection/assets/110081008/564d2002-c637-4021-8017-440a6224af0c


  
