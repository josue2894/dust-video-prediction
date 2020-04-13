{\rtf1\ansi\ansicpg1252\cocoartf2511
\cocoatextscaling0\cocoaplatform0{\fonttbl\f0\fnil\fcharset0 Menlo-Regular;}
{\colortbl;\red255\green255\blue255;\red0\green0\blue0;}
{\*\expandedcolortbl;;\csgray\c0;}
\margl1440\margr1440\vieww10100\viewh9920\viewkind0
\pard\tx560\tx1120\tx1680\tx2240\tx2800\tx3360\tx3920\tx4480\tx5040\tx5600\tx6160\tx6720\pardirnatural\partightenfactor0

\f0\fs22 \cf2 \CocoaLigature0 The following codes are on Jupiter Notebook using python3. \
\
1.) split_video2frames.ipynb \
2.) image_histogram.ipynb\
3.) Pre_Processing_Scaled.ipynb	\
4.) Dust_2.ipynb	\
5.) Post_Processing.ipynb		\
6.) Prediction_output.ipynb	\
\
\
1.) split_video2frames.ipynb \
This code is used to go through video directory and split videos into frames. Note that frame rate is set to 5 frames per second but due to AVI format video will split into 10 frames per second. \
\
2.) image_histogram.ipynb\
This code is used to take an input image and display a histogram. Program is set to compare RGB and HSV images for both dust and non_dust images. \
\
3.) Pre_Processing_Scaled.ipynb\
This code is used to take in frames and extract bands to form a data frame for both RGB and HSV colorspace. \
 \
4.) Dust_2.ipynb	\
This code is used to take in a data frame and train a feed forward neural network. 6 directories will be created; biases, confusion_matrix, miss, summary, weights for training cycle and validation directory with validation confusion matrix.\
\
5.) Post_Processing.ipynb		\
This code is used to take confusion_matrix directory and create a plot for accuracy vs iteration. An over all report is also created showing accuracy, recall, precision for an index where accuracy was maximized. \
\
6.) Prediction_output.ipynb	\
This code is used to predict frames with the best model weights and biases producing a text time with date and time of dust events. For the time being validation images are used. }