# ActionDetection

Training using yolov5 via google colab


To use yolov5 in an environment

1. install archiconda3 by following the installation guidelines at https://github.com/yqlbu/archiconda3


3. create new environment using conda create -n envname python=3.9 (replace envname in your preference) (yolov5 needs python ver 7 or higher)

4. if it requires permission, enter sudo chown -R <user> <path>/archiconda3 eg. sudo chown 1000:1000 /home/butter/archiconda3/pkgs/urls.txt

5. create env eg $ conda create -n yoloEnv python=3.9

6. clone yolov5 repository if you haven't

7. $cd yolov5

8. run $ pip install -r requirements.txt to install all the pre-requisite for yolov5


9. To launch the webcam inference, run $ python detect.py --weights best.pt --source 0
