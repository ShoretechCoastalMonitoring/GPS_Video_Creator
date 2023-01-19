# GPS_video_creator
Python program to pair a map with live GPS position according to the position of a camera used for the video. Works in a Jupyter Notebook using the Anaconda Distribution. Useful in particular for shallow underwater surveys from a kayak. The example given is for Mooloolaba.

![alt text](https://github.com/ShoretechCoastalMonitoring/GPS_Video_Creator/blob/main/GPS_video_snapshot.JPG)

Use this video for the example code given:
https://drive.google.com/file/d/1L3xiVhYui-OiURuz-Z6dB1g7E-7DgeDt/view?usp=share_link

Outputs from example code given:
https://drive.google.com/file/d/1FFWMgmPcQZx6ZH2b84hNt9oisj0-wggH/view?usp=share_link
https://drive.google.com/file/d/1DYl6eISv_47zeaXXsz-im7cniSX67ebs/view?usp=share_link
https://drive.google.com/file/d/1_byeWMunXHYrwtxyOkyeh-UB0lEQWXci/view?usp=share_link

## Python libraries required:
- gpxpy
- numpy
- cv2

## Online tools required:
- https://geodesyapps.ga.gov.au/grid-coordinate-batch-processing - created by Geoscience Australia, licensed under http://creativecommons.org/licenses/by/4.0/legalcode
- Mapping software which provides a georeferenced map image (I used Nearmaps for this example).
- Video editing software (I used OpenShot Video Editor for this example).

## Equipment required:
- GPS device or smartphone which is waterproof (or inside a waterproof bag).
- Waterproof camera (e.g. Go Pro)
- Kayak
- Camera attachment to Kayak. I've used an adjustable fishing rod holder with an extendable Go Pro pole to allow the Go Pro to be extended below the water. Whatever mount you use you should still tether the camera to the kayak in case it breaks.

![alt text](https://github.com/ShoretechCoastalMonitoring/GPS_Video_Creator/blob/main/Surf_ski_setup.JPG)
My surf ski setup.

![alt text](https://github.com/ShoretechCoastalMonitoring/GPS_Video_Creator/blob/main/Camera_attachment.JPG)
My camera attachment setup.

## Problems to fix:
- time stamp seems to fall behind?

