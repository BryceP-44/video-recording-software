# video-recording-software
I am using yolov5 to track my face and paste it onto a capture of my screen. Also puts pulsating rainbows around the floating face and borders of the screen.
<br />
Here is a screenshot of the output video. Adjust the xoffset and y offset as needed. I also uploaded the pytorch file needed for the weights for my face. 
run with:
<br />
python detectbryce.py --weights brycesmall.pt --img 96 --conf-thres 0.4 --source 0
<br />
this runs at about 25ms on my CPU only (R3-1200g)
<br />
Obviously, you need to have the whole yolov5 folder running correctly.

<br /><br />
![screenshot of output video](https://github.com/BryceP-44/video-recording-software/blob/main/videorecord%20software.png)

