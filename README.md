# KCFpy3
Use python3 to implement kcf
Python implementation of
[High-Speed Tracking with Kernelized Correlation Filters](https://arxiv.org/abs/1404.7584)

**Requirements**

*python3.8

*numpy

*numba

*opencv-python

**USE**
```
git clone https://github.com/ollehhello/KCFpy3.git
cd KCFpy
python run.py
```
It will open the default camera of your computer, you can also open a different camera or a video
```
python run.py 2
```
```
python run.py ./test.avi  
```
Try different options (hog/gray, fixed/flexible window, singlescale/multiscale) of KCF tracker by modifying the arguments in line tracker = kcftracker.KCFTracker(False, True, False) # hog, fixed_window, multiscale in run.py.

**Thanks**

Thanks to his source code[KCFpy](https://github.com/uoip/KCFpy), my code is an improvement based on his code.
