# Ready-to-use Google Colab file: https://colab.research.google.com/drive/1QWI94mivkWGZLvrB4cUoaw3dH6Cf45mw?usp=sharing
# Yolov7-cigarette-censor-and-smokers-face-recorder
* **Cencoring and counting all cigarettes on the screen and saving smoker's faces in the folder or any database**
* **Usefull for public non-smoking areas**
* **Code can run on Both (CPU & GPU)**
* **Video/WebCam/External Camera/IP Stream Supported**

## It is super easy to run
* **We are going to copy my repo and just download "traced_model.pt" which is already given by me in the code,
and we are good to go!**
 
## Steps to run Code
* clone the repository:
* ```git clone https://github.com/muratali016/Yolov7-cigarette-censor-and-smokers-face-recorder.git```
* Download traced_model.pt by link:https://drive.google.com/file/d/1ovsR0biNCnOZ9174bSkNS-5IMtYGa52b/view?usp=sharing and move this model to ypur directory 

### Upgrade pip with mentioned command below.
``` pip install --upgrade pip ```

### Install requirements with mentioned command below.
 ``` pip install -r requirements.txt ```

### Using counter
 * ```%cd /content/Yolov7-cigarette-censor-and-smokers-face-recorder```
* ```%!python detect.py --weights best_cigarette.pt --conf 0.1 --source /content/Yolov7-cigarette-censor-and-smokers-face-recorder/example_img.jpg --cigarette_blurrate 50 --shape_detector /content/Yolov7-cigarette-censor-and-smokers-face-recorder/shape_predictor_68_face_landmarks.dat```
 
 
### Results!



### Inference on a video:

