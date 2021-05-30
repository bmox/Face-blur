# mediapipe blur face python
<p align="center">
  <img src="https://github.com/bmox/Face-blur/blob/main/demo/demo.gif" alt="animated" />
</p>
<br>
This web app only run on localhost <br>
Python version >=3.7 <br>

## step 1

```
pip install -r requirements.txt
```
## Run web app
To run the web app  or, double click on the run.py file

```
python run.py
```

![Demo](https://github.com/bmox/Face-blur/blob/main/demo/webapp.PNG)
#### Give a clear input file name like "video.mp4" not like "vid - 324$op _ 9363*.mp4"
#### If you increase "Face Detection Confidence" then face tracking will more accurate. <br>
#### If you reduce "Blur pixel size in face" then face blur pixel size will increase. <br>
#### In "Horizontally flip video" "yes" mean you can mirror your video. "No" mean nothing will happen.


## From webcam
Realtime face blur using webcam
```
python webcam.py
```
