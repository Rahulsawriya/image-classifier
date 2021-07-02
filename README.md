# Image Classifier

In this project you will use a created image classifier to identify dog breeds

## Setup
Change to the "root" directory
```
cd image-classifier
```

Set up a virtual environment
```
# Python 3
python3 -m venv ./venv
source ./venv/bin/activate


Install the application requirements:
```
pip3 install -r requirements.txt
```

Then, Run project
Classifies pet images using a pretrained CNN model, compares these classifications to the true identity of the pets in the images, and summarizes how well the CNN performed on the image classification task.

python check_images.py --dir pet_images/ --arch vgg --dogfile dognames.txt
