# My OpenCV tests and examples

My way to install OpenCV in Windows 10:
- go to python.org, take official python distribution. During installation add it to PATH. 
- install virtaulenvwrapper: ` pip install virtualenvwrapper-win`
- create dedicated virtual environment: `mkvirtualenv opencv`, and activate it: `workon opencv`
- install full OpenCV package: `pip install opencv-contrib-python`

First of all, test that OpenCV is properly installed and working fine: 

```
python camera-test.py
```

To exit press `q`.
