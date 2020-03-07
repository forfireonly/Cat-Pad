# Cat-Pad

![3Csa1](https://user-images.githubusercontent.com/29640816/75206248-39081100-5733-11ea-86b7-2f7b51bb15ee.jpg)

If you work on a laptop, you likely know that the joy of your cat’s company can easily turn into annoyance as he or she 
takes over your keyboard, sending emails accidentally, getting in the way of your video call, and changing your work beyond recognition.

The primary objective of the project is to detect the cat on the keyboard and disable it for duration of cat's presence.

The solution is built using deep learning and computer vision algorithms powered by the Intel® Distribution of 
OpenVINO™ toolkit Model Optimizer.

## Workflow steps

###Colab stage

1. Installing OpenVino on Google Colab
2. Use resnet50-binary-0001 with OpenVino for identification of the cat in image.
3. Identification of cat in video.

###Local run

1. Installing OpenVino on Google Colab.
2. Identification of cat in real time.
3. Code to disable the keyboard as long as cat is present.
4. Increasing the presision of detection by training the model.
