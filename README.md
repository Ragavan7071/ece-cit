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
# Requirements for prelims
# colab
Use google colab which provoides free gpu to run this code

This code is designed to run in the colab
# Test dataset
we have to give the dataset path for poem generation in the 2nd cell,I had given my test dataset in the repository(test.txt) you can download it.
# step by step procedure for prelims
step1:upload the test dataset in colab(you can get the dateaset from github repo(test.txt))

step2:place the file path of dataset in the 2nd cell

step3:runtime-->run all (or)ctrl+F9

step4:the final cell is our output cell ,enter the input string 

step5:the output poem is generated

step6:for using api(telegram) function read the txt file in prelims folder 
# Team details
The team details.docx contains the details and work of each team members
