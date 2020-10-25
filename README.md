
# license plate recognition using python

## Video

[![Video](https://img.youtube.com/vi/D_G4SXqw2EU/0.jpg)](https://www.youtube.com/watch?v=D_G4SXqw2EU)
--------------------

1. Install darkflow

    clone darkflow from [here](https://github.com/thtrieu/darkflow) , you must have C++ build tools to be able to build the source, download it from [here](https://visualstudio.microsoft.com/downloads/#build-tools-for-visual-studio-2019)


        cd darkflow-master
        python3 setup.py build_ext --inplace
        pip install Cython
        pip install numpy
        pip install -e .

2. Install tensorflow old version

    you must have anaconda installed, pip only has tensorflow 2, also your python version in conda environment should be 3.6 or lower
    
        conda install python=3.6
        conda install -c conda-forge tensorflow

3. Install opencv, opencv is deprecated, it doesn't have a wheelfile on pip so don't try to pip install it

    luckily conda has it compiled for windows, otherwise, you might have to build it yourself as I did

        conda install -c conda-forge opencv
        conda install -c conda-forge imutils

4. download dataset from [here](https://drive.google.com/drive/folders/17gxw7tv7jy3KgJFhQiHX0IilYObFbIJp) and
    put it next to main .py

5. run and It :)

-------------------------

[main source](https://github.com/TheophileBuy/LicensePlateRecognition)

[main article](https://medium.com/@theophilebuyssens/license-plate-recognition-using-opencv-yolo-and-keras-f5bfe03afc65)
