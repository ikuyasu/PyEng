File: audio\create_wave.py
Error: 'import matplotlib.pyplot as plt' imported but unused.

File: audio\noisy.py
Warning: C:\ProgramData\Anaconda3\lib\site-packages\numpy\core\numeric.py:482: ComplexWarning: Casting complex values to real discards the imaginary part
return array(a, dtype, copy=False, order=order)
Comment: As long as you know you only need the real part, then it's fine.

File: blur.py
Error: mportError: DLL load failed: %1 is not a valid Win32 application.
Comment: After ModuleNotFoundError: No module named 'cv2', I used 'pip install
opencv-python' which seemed to have succesfully install the opencv. But the DLL
load error pops up after.

File: color_test.py
Error: SyntaxError: Missing parentheses in call to 'print'
Comment: After 'ModuleNotFoundError: No module named 'SimpleCV', I pip-installed
SimpleCV, which successfully installed the module. Apparently,
SimpleCV.base contains python2 print command.

File: color_train.py
Error: SyntaxError: Missing parentheses in call to 'print'
Comment: the same reason as color_test.py

File: count_cards.py
Error: ImportError: DLL load failed: %1 is not a valid Win32 application.
Comment: cv2 problem. Error in cv\__init__.py

File: display.py
Error: ImportError: DLL load failed: %1 is not a valid Win32 application.
Comment: cv2 problem in the same way.

###############
At this momment, I tried to install opencv because all of the errors were attributed
to the inanability to import cv2. I attempted the several methods on the web and one that seemed to
go through is to use 'pip install opencv_python-3.2.0-cp36-cp36m-win_amd64.whl' after downloading 
the .whl file from "http://www.lfd.uci.edu/~gohlke/pythonlibs/#opencv" using wheel (pip install wheel). 
I don't know if this is what you expect your readers to do though. Anyway, I reran all the codes I looked at 
so far.
###############

File: audio\create_wave.py
Error: No error, but nothign happened. 


File: audio\get_freq.py
Error: No error. 'The frequency is 1000 Hz' with one figure.


File: audio\noisy.py
Error: No erros.
Comment: Great looking figures.


File: Image_Video\blur.py
Error: image = cv2.imread(sys.argv[1])
IndexError: list index out of range


File: Image_Video\color_test.py
Error:  from SimpleCV.base import *
  File "C:\ProgramData\Anaconda3\lib\site-packages\SimpleCV\base.py", line 139
    print 'unit test'
                   ^
SyntaxError: Missing parentheses in call to 'print'


File: Image_Video\color_train.py
Error:     from SimpleCV.base import *
  File "C:\ProgramData\Anaconda3\lib\site-packages\SimpleCV\base.py", line 139
    print 'unit test'
                    ^
SyntaxError: Missing parentheses in call to 'print'


File: Image_Video\count_cards.py
Error: No error, and the code seemed to find the correct nunber of cards, 5 with 'Number of 
objects found = 5'.


File: Image_Video\display.py
Error:  image = cv2.imread(sys.argv[1])
IndexError: list index out of range


File: Image_Video\edge_detect.py
Error: image = cv2.imread(sys.argv[1])
IndexError: list index out of range


File: Image_Video\face_detect.py
Error: File "C:/PyEng/PyEng/Image_Video/face_detect.py", line 7, in <module>
    imgpath = sys.argv[1]
IndexError: list index out of range


File: Image_Video\motion_detect.py
Error: No error. Seems to work fine. The windows is very dark.


File: Image_Video\webcam_face_detect.py
Error: No error. It seems to work well. The window captures the scean from my webcam on the laptop.


File: machine\calc_correlation.py
Error: File "C:/PyEng/PyEng/machine/calc_correlation.py", line 43, in <module>
    with open(sys.argv[1], 'r') as f:

IndexError: list index out of range


File: machine\corr_dict.py
Error: No error, but nothing happened.


File: machine\ml_data1.py
Error: No error.


File: machine\main.py
Error: No error. Runs great.


File: Multiprocessig\thread.py
Error: No error. Job done.


File: Multiprocessig\single.py
Error. No error. Job done, done.


File: Multiprocessig\process.py
Error. No error, but nothing pops up.


File: Multiprocessig\get_rand.py
Error: No error as it's only a procedure.


File: Pandas\pandas_movie.py
Error: No error. Great looking tables and one barchart. 


File: Pandas\obesity.py
Error: No error. Great looking tables and three line time series graphs.


File: Plotting\list_comp.py
Error: No error


File: Plotting\graph_wave.py
Error: No error


File: Plotting\data_plot.py
Error: No error


File: Plotting\first_try.ipynb
Error: No error. As long as you know how to open the jupyter notebook file and use.


File: rpi\hello.py
Error: No error. I guess I have flask already installed. localhost:5000


File: rpi\webapp.py
Error: The server gets up with the "Please enter command to run", working good.
I typed print command but the browser is directed to the error page. My spyder
doesn't seem to like "from flask import *"


File: rpi\webapp_bootstrap.py
Error: Just as webapp.py, the server gets up with the "Please enter command to run", working good.
I typed print command but the browser is directed to the error page. My spyder
doesn't seem to like "from flask import *"


File: WordCount\word_count.py
Error: File "C:/PyEng/PyEng/WordCount/word_count.py", line 23, in <module>
    filename = sys.argv[1]

IndexError: list index out of range


File: WordCount\read_file.py
Error: No error. It reads a file fine.


File: WordCount\count_words.py
Error: No error. It seems to count words fine.


File: WordCount\count_lines_fixed.py
Error: No error. It seems to count the number of lines fine.


File recognise_face.py
Error:  File "C:/PyEng/PyEng/recognise_face.py", line 7, in <module>
    shan_image = face_recognition.load_image_file("shan.jpg")

NameError: name 'face_recognition' is not defined
Comment: I guess this file is misplaced in the repository somehow.



