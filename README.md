<h1 align="center">Amharic-Text-to-speech</a></h1>

-  Audio sample at sound cloud - <a href="https://soundcloud.com/moan-bekele/download-11?si=5c9dfe63d0664a65bc20802c3a701067&utm_source=clipboard&utm_medium=text&utm_campaign=social_sharing">
  sample.wav
</a>

<a target="_blank" align="Left">
  <img align="right" top="500" width="100%" alt="GIF" src="colab.PNG">
  
</a>

<h3 align="left"><u>Main Resources Used</u></h3>




-  Tacotron 2 <a href="https://github.com/NVIDIA/tacotron2" target="blank">https://github.com/NVIDIA/tacotron2</a>

-  Waveglow <a href="https://phoenix.tech/griffyn/" target="blank">https://phoenix.tech/griffyn/</a>


<h3 align="left"><u>Training</u> </h3>
 <video src="https://github.com/moanbekele/Amharic-Text-to-speech/blob/main/download%20(11).mov" controls="controls" style="width: 100%"></video>

- I used a dataset of approximately 2 hours audio and text data for this results ,I used lyrics from  kassmase songs as a text dataset and my voice as the audio.
<a target="_blank" align="Left">
  <img align="right" top="500"  alt="GIF" src="https://github.com/moanbekele/Amharic-Text-to-speech/blob/main/GenuineTheseCottontail-max-1mb.gif">
</a>

-  <a href="https://colab.research.google.com/drive/1CRHrFqEKWxFi_le1Mos70cbldasw9BAq?usp=sharing" target="blank"> **This notebook**</a> holds the code responsibe for training the tacotron model  

-  Directory For audio **/wavs** , Audio should be formated project rate(hz) to 22050!, you can use Audacity it's much more simpler to convert project rates(hz).

- Training the model requires GPU so I recomend Colab or Kaggle 
<br/>

 
<h3 align="left"><u>The model</u></h3>
 
- The accuracy of the result was pretty decent, I'd recomend providing More training data.
-  <a href="https://colab.research.google.com/drive/1CRHrFqEKWxFi_le1Mos70cbldasw9BAq?usp=sharing" target="blank"> **This notebook**</a> holds the code responsibe for Testing the training model  

- The Max-decoder variable is directly proportional to the amount of minutes the model out puts 


