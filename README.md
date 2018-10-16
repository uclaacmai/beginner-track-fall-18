# Intro to ML: Beginner Track, Fall 2018

## Getting a Python and Machine Learning Environment Up and Running
Please complete these tasks before the workshop in order to hit the ground running! Don’t worry if you run into some errors though. Just let us know during one of the workshops and we'll help you out.

### Mac Installation Instructions
If you don't have brew, install it by using the command available [here](https://brew.sh/).

(Optional: We recommend a python3 installation. Your mac currently likely comes with Python 2 as the default built-in.)

If you don't have `python3` installed (check by typing `python3` in the terminal), run `brew install python3`. This will install `python3` and a package manager, `pip3` for you. This may take a while.

### Linux (Ubuntu/Debian) Installation Instructions
You probably have Python 2 and Python 3 installed if you're running the latest Ubuntu. To check whether you have Python 3 installed, run `python3` in the terminal. 

To get Python 3 (we recommend using this over Python 2), run `sudo apt-get update`, then `sudo apt-get install python3.6`

#### Get the Python libraries you'll need (Mac & Linux)
Run `pip3 install numpy matplotlib tensorflow sklearn jupyter scipy` if you are running Python3, otherwise run `pip install numpy matplotlib tensorflow jupyter sklearn scipy`. This command may have to be prefaced with the `sudo` keyword.

If you have installed any of these packages before, make sure to `run pip install [PACKAGE] --upgrade` to ensure that you have the latest version.

Execute the following Python program:

```import numpy as np
import matplotlib.pyplot as plt
import tensorflow as tf
import sklearn
hello = tf.constant('Hello, Tensorflow!')
sess = tf.Session()
print(sess.run(hello))
```
If it runs without any errors, then you're good to go!


### Windows Installation Instructions
Highly recommended: Installing with the Anaconda Distribution
Anaconda is a package managing tool for Python that can be installed for both Mac and Windows. We've found that going with Anaconda results in the least installation issues for those of you who are using Windows.
First, download Anaconda at this link: https://www.anaconda.com/download/#windows. We recommend downloading the Python 3.7 installation.

After Anaconda has downloaded, open it up and install it. The installation process takes a while, but after you should see a screen with the option "Register Anaconda as my default Python". Check this, and continue.

Once the installation is finished, you should be able to open up the Anaconda prompt, and invoke python. In the python interpreter, the commands `import sklearn` `import matplotlib` `import numpy` should all work.

Finally, install Tensorflow with the Anaconda package manager, known as conda: `conda install Tensorflow`. Now, you should be able to execute the following program without any issues:

```import numpy as np
import matplotlib.pyplot as plt
import tensorflow as tf
hello = tf.constant('Hello, Tensorflow!')
sess = tf.Session()
print(sess.run(hello))
```
For additional details on Anaconda installation, see [this](https://medium.com/@GalarnykMichael/install-python-on-windows-anaconda-c63c7c3d1444) helpful link.
