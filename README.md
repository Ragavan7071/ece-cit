# Tutorials
The final round folder contains code and submission details for final round,along with the tutorial video(final.mp4) to run that code.

Similarly,the prelims folder contains code and submission details for prelims round,along with the tutorial video(adalove.mp4) to run that code. 
# Requirements for final
# colab
Use google colab which provoides free gpu to run this code

This code is designed to run in the colab
# yolov3 weights
It will be downloaded automatically while runing the code,it will take around 237 mb.

The file path is referred in the 4th cell,if you want to run on your own image weights you can change the path according to the weights file path

The configuration for that weights are available in the repository(detect.cfg)it is a standard object detection configuration.it is also cloned from the repository while runing the code
# Test datset
The test dataset for poem generation is fetched from the cloned github repository.
The file path is referred in 7th cell
# Gallery
Since the object detection weights are limited to only 80 objects ,some photos cannot recognized.
Please refer names-->coco.names for giving input images. 

The gallery folder contains input images you can also download it for testing the code.
# step by step procedure for final round
step 1:Click on runtime-->run all (or) ctrl+F9

step 2:The yolov3 weights are downloaded automatically,which is the pretrained weights for about 80 objects.

in the 3rd cell github repository is coned for fetching the dataset

step 3:The weights path is referred in the 4th cell

step 4:Once the weights are downloaded the code excecute within few seconds

step 5:Download the input images from github repository-->gallery folder

step6:in the output cell upload the input image ,the output poem will be generated 
# Requirements for prelims
# colab
Use google colab which provoides free gpu to run this code

This code is designed to run in the colab
# Test dataset
we have to give the dataset path for poem generation in the 2nd cell,I had given my dataset in the repository(test.txt) you can download it.
# step by step procedure for prelims
step 1:Upload the input dataset for sonnet in colab(you can get the dateaset from github repo(test.txt))

step 2:Place the file path of dataset in the 2nd cell

step 3:Click on runtime-->run all (or)ctrl+F9

step 4:The final cell is our output cell ,enter the input string 

step 5:The output poem is generated

step 6:For using api(telegram) function read the readme.txt file in prelims folder and also refer the tutorial video in it.
# Team details
The team details.docx contains the details and work of each team members

#Inovation
The (final_poetry genrator with audio.ipyb)is similar to the final round model,but has an advantage,it no only a sonnet which gives text output it also narrate the poem with audio .
