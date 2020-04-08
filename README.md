# opencv4.1.1-for-google-coral

- Download the prebuilt libraries from this repository  
`git clone https://github.com/pjalusic/opencv4.1.1-for-google-coral.git`
  
- Copy the cv2.so file to /usr/local/lib/python3.7/dist-packages/  
`cp opencv4.1.1-for-google-coral/cv2.so /usr/local/lib/python3.7/dist-packages/cv2.so`
  
- Copy other .so files to /usr/local/lib/  
`sudo cp -r opencv4.1.1-for-google-coral/libraries/. /usr/local/lib`
  
- Check if it works.
```python
python3
>>> import cv2
>>> cv2.__version__
'4.1.1'
```

- More info on https://medium.com/krakensystems-blog/doing-machine-vision-on-google-coral-with-opencv-fb2e4d055357
