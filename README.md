# The-Many-Faced-Bot
It is a BOT that can recognise anyone whose Face is present in the database. GOT fans will get it!! ;p

**Isn't it pretty cool to have a BOT recognise your face and unlock your laptop with a welcome sound? Sounds like Jarvis!!**

**If you are interested in building such a BOT, Welcome to Braavos.. Together let's build *The-Many-Faced-Bot***

## Introduction
Folks going through deeplearning must have come across the google's fascinating research paper *FaceNet* and it's *Triplet Loss* which is the best possible face-recognition algorithm right now. *To understand the concept of Triplet Loss quickly go and checkout this [blog](https://towardsdatascience.com/siamese-network-triplet-loss-b4ca82c1aec8)*.
**In this project, I have trained a model on the basis of the paper and used that model to make this BOT and a working prototype is ready**
## Workflow of the prototype
1. To register new user, The-Many-Faced-Bot detects the face->crops the face->Stores the face of the user.
2. To recognise a user, The-Many-Faced-Bot detects the face->crops the face->checks the similarity of this new face with the other faces in the database and gives the result obtained.  
**The-Many-Faced-Bot is so professional that it needs only a single face per user in the database of faces**
### Requirements to run this project
* Tensorflow-gpu
* Keras
* OpenCV
### Instructions to run this project
* Go to terminal and type "python3 many_faced_bot.py"
* Follow the instructions further displayed on the screen(*Press 1 to add face, 2 to recognise face, 3 to exit) 
## Milestones
- [x] Make a model and train it on LFW dataset
- [x] Test model for accuracy(more than 99% achieved)
- [x] Save the model and deploy it on CLI application
- [x] Capture and Store Photos in a database and use those to **Recognise**
- [ ] Make a GUI application and Deploy it on webapp or window-based-app(*for webapp Django is preferred*)
- [ ] For Face-Detection only the **lively face** is detected and not a printed photo or anything
- [ ] Integrate the BOT with Ubuntu-OS and make a Face-Unlock-System
## Prerequisites
* Knowledge of CNNs, Siamese Networks, Triplet Loss is welcome but not necessary as I have already implemented that part in code.(as you can see in **Milestones**)
* Knowldege of Web-Application or Window-Based-Application in python to solve the 3rd last problem.(*If you know any other language then it's on you to integrate python with that language*)
* Knowledge of OpenCV to solve the 2nd Last problem.(*Any other technique is also welcome*)
* Knowledge of Linux or Ubuntu to solve the last problem.(*If you can implement in Windows then you are welcome*)
## Contribution
You can contact me regarding your visualisation and techniques to solve any of the unsolved mentioned problems and for contribution to this project. You can make pull requests if you want to contribute. *If you have any other feature that can be included then feel free to contact me or issue feature request*.
## Mentor
* [Suraj Kumar](https://github.com/shazz10) - (Email- sksuraj2136@gmail.com)

**If you liked the project and found it useful then you can star it**

**If you want to know more about the architecture of the model email me for it**
