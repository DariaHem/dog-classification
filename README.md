
## Goal of the project
The goal of this project is to make program that can classify dog breed using Convolutional Neural Networks (CNN).


## features of the project
1) The classifier decides if the photo represents the dog, human or category named "others". 
If the decision is: dog, the classifier should classify the dog breed. 
If the decision is: human, the classifier should point to which dog breed the human on the photo is similar to.

## Steps:
1) I created the human detection program. For this purpose I used cv2.CascadeClassifier in cv2 libarary.

2) I created the dog detection program and used transfer learning of VGG16 and used all the parameters already trained.

3) I created the classification program to detect 1 of 133 dog breeds (ImageNet data contains 133 sorts of dogs). 
For this purpose I used transfer learning by VGG16 but changed last classifier linear model to 133 final classes

4) Connected all the steps to make one executable program.


