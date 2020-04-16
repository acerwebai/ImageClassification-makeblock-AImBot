# ImageClassification-makeblock-AImBot
ImageClassification makeblock AImBot. 
Use AI Image Classification to control makeblock mBot.

# Standard Operation Procedure
## Image Classification
Use Google Teachable Machine to training image classification AI model.
https://teachablemachine.withgoogle.com/train/image

Define 5 classes as "GO", "BACK", "Right", "Left", and "OTHER"(stop).
Use the "webcam" button to capture each class image.

After preparing all images for each class, press "Train Model" to train your own model.
Note: Do NOT switch the Tab.

When training done, export your model as Tensorflow.js format and download it.
There are three files "metadata.json", "model.json", and "weights.bin" in your download.
And then copy the javascript code which provide from export diagram as classification.js

Prepare one simple HTML index.html to be your User Interface.



