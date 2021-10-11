# Face detection - DNN
Application to detect faces with or without mask on images.
### Usage:
- Clone this repo

- Install requirements: ```pip3 install requirements.txt```

- On the main folder, Run:
  - ```python3 detec.py [xxx].jpg```
  
  For detec one single picture, or
  
  - ```python3 detec.py dataset/[xxx]/```
  
  To loop throughout folder and generate a log file with the time and filename along <br />
  with the pic results on the "[xxx]/output/".
  
### Extra:  
- /dataset/base20 and ../base21  contains the dataset sent to robocup 2020 and 2021.
- /dataset/RoboCup2021 contains the dataset received from robocup 2021.
- /models/ contais the models used to detec faces and mask.
