# My OpenCV tests and examples

My way to install Python/OpenCV in Windows 10:
- go to python.org, take official python distribution. During installation add it to PATH. 
- next actions shoud be in command prompt, not in PowerShell
- also pay attention to use 64 bit command prompt. Visual Studio 2019 developer command prompt for instance call 32 bit command prompt.
- install virtaulenvwrapper: `pip install virtualenvwrapper-win`
- create dedicated virtual environment: `mkvirtualenv opencv`, and activate it: `workon opencv`
- install full OpenCV package: `pip install opencv-contrib-python`

First of all, test that OpenCV is properly installed and working fine: 

```
python camera-test.py
```

To exit press `q`.

## OpenCV + C++

The simpliest path to work from C++ is to use pre-build binaries from [official site](https://opencv.org/releases/). Just download & unzip somethere.

## OpecCV.js

Download current JS library from `https://docs.opencv.org/4.3.0/opencv.js` (you can use current version or master for cutting edge release).

JS playground is in `js_test.html`
