# Football-Ball-Detection

You can run Football_Object_Detector.ipynb file on google colab. It has most of the required packages pre-installed and the notebook also installs tensorflow object detctor for you.

Steps:

1.) Add this dataset to your google drive: link
2.) Download Football_Object_Detector.ipynb, pipeline.config, label_map.pbtxt, generate_record.py files and upload them to colab
3.) Run it! 


Note:
1.) You need to stop training manually, after sometime. After 20,000 steps, it is safe to stop the training. The accuracy increases very slightly after 20,000 steps. 

The model is just trained on 195 images of white football ball, and we are predicting on yellow football ball. It still performs quite good. 


You can see the demo video here:


