<p float="left">

 <img src="https://github.com/rconfa/Digital-Signal-and-Image-Management-Project/blob/main/images/DSLogo.png" width = "500"/>
 <img src="https://github.com/rconfa/Digital-Signal-and-Image-Management-Project/blob/main/images/BicoccaLogo.png" width = "100" align="right"/>
</p>
<h2 align="center">Digital Signal and Image Management project</h2>

# Overview
The project consists in the development of an application for the recognition of one-dimensional signals (audio) and two-dimensional signals (images). Specifically we have developed three different task:

* Processing-1D: Recognize the identity of the group member starting from a two-second audio with ML and DL models 
* Processing-2D: Recognize the identity of the group member starting from an image with ML and DL models 
* Retrieval: Find the ten most famous VIP faces for each member of the group 

# Data
All the data used for this project were collected directly in the following ways:
* Processing-1D: recording 100 audios for each five-second person. These audio were subsequently cut every 2 seconds and a data augmentation was applied, modifying their pitch and speed to increase the available data.
* Processing-2D: taking 100 photos with variations of light and expression
* Retrieval: three photos taken from the previous task were used 

If you have question about the data or you need them please <i>write me</i>!

# Notebook 

* [Processing-1D](https://github.com/rconfa/Digital-Signal-and-Image-Management-Project/tree/main/Notebook/Processing-1D). For this task we have developed three different notebook:
  - [<b>1_AudioAcquisition</b>](https://github.com/rconfa/Digital-Signal-and-Image-Management-Project/blob/main/Notebook/Processing-1D/1_AudioAcquisition.ipynb): This notebook must be executed locally. It uses the default microphone for automatically registering all audios needed for the project.
  - [<b>2_AudioRecognition</b>](https://github.com/rconfa/Digital-Signal-and-Image-Management-Project/blob/main/Notebook/Processing-1D/2_AudioRecognition.ipynb): This notebook contains all the ML and DL models developed for solve this task. It also contains the code used for splitting and augmenting the data starting from the original five seconds audios.
  - [<b>3_DemoLive</b>](https://github.com/rconfa/Digital-Signal-and-Image-Management-Project/blob/main/Notebook/Processing-1D/3_DemoLive.ipynb): This notebook must be run locally, it uses the microphone and the camera to create a sort of live demo in which to demonstrate the effectiveness of the models developed for the voice recognition task. 
* [Processing-2D](https://github.com/rconfa/Digital-Signal-and-Image-Management-Project/tree/main/Notebook/Processing-2D). Again we have developed three different notebook with the same purpose but ready for images processing:
  - [<b>1_ImageAcquisition</b>](https://github.com/rconfa/Digital-Signal-and-Image-Management-Project/blob/main/Notebook/Processing-2D/1_ImageAcquisition.ipynb): This notebook must be executed locally, as before it automatically snaps all the images needed by using the default camera. 
  - [<b>2_FaceRecognition</b>](https://github.com/rconfa/Digital-Signal-and-Image-Management-Project/blob/main/Notebook/Processing-2D/2_FaceRecognition.ipynb): This notebook contains all the ML and DL models developed for solve this second task. In this folder you can also find a link to dowload the weights used for the VGGFace model.
  - [<b>3_DemoLive</b>](https://github.com/rconfa/Digital-Signal-and-Image-Management-Project/blob/main/Notebook/Processing-2D/3_DemoLive.ipynb): This notebook must be run locally, it uses the camera to create a sort of live demo in which to demonstrate the effectiveness of the models developed for the face recognition task. 
* [Retrieval](https://github.com/rconfa/Digital-Signal-and-Image-Management-Project/tree/main/Notebook/Retrieval). This folder contains only one [notebook](https://github.com/rconfa/Digital-Signal-and-Image-Management-Project/blob/main/Notebook/Retrieval/Retrieval.ipynb) that implement all the code necessary for solve the retrieval task. The dataset used with vip's faces can be download [here](https://skydrive.live.com/?cid=1e04f731c1dd71bc&id=1E04F731C1DD71BC!105).

You can also find the [<b>report</b>](https://github.com/rconfa/Digital-Signal-and-Image-Management-Project/blob/main/DSIM_Report_ITA.pdf) and [<b>presentation</b>](https://github.com/rconfa/Digital-Signal-and-Image-Management-Project/blob/main/DSIM_Presentation_ITA.pdf) made for the exam. Both in <i>italian language</i>. <br>
If you need the <b>trained models</b> that we implemented please feel free to <i>write me</i> because their weights exceed the GitHub maximum allowed.

# How to run code
Unless otherwise specified in the notebook section all codes can be runned in [Google Colaboratory](https://colab.research.google.com/) platform. All notebooks all already setted to import the necessary packages and also in this way you can easily use a GPU! <br>
Unfortunately for the notebook that performs live demo and automatic acquisition you will need to use local environment because their required cams and microphone, for this notebook you need to install all the packages reported in the requirements file that you can find in each different folder. <br>
Anyway if you have any problem just contact me for further information!

# References
[1] S. Bianco, “Dispense e slide del corso digital signal and image management” 2021. <br>
[2] O. M. Parkhi, A. Vedaldi, and A. Zisserman, “Deep face recognition", 2015 <br>.

# About us

#### Riccardo Confalonieri - Data Science Student @ University of Milano-Bicocca
  * r.confalonieri5@campus.unimib.it
  * [GitHub](https://github.com/rconfa)
  * [LinkedIn](https://www.linkedin.com/in/riccardo-confalonieri-5250b0201/)

#### Lorenzo Mora - Data Science Student @ University of Milano-Bicocca
  * l.mora4@campus.unimib.it
  * [GitHub](https://github.com/lomProg)

#### Ginevra Mariani - Data Science Student @ University of Milano-Bicocca
  * g.mariani34@campus.unimib.it
  * [GitHub](https://github.com/enigarv)
