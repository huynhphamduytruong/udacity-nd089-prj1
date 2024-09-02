# Use a Pre-trained Image Classifier to Identify Dog Breeds

For this image classification task, you will be using an image classification application using a deep learning model called a convolutional neural network (often abbreviated as CNN). CNNs work particularly well for detecting features in images like colors, textures, and edges; then using these features to identify objects in the images. You'll use a CNN that has already learned the features from a giant dataset of 1.2 million images called [ImageNet](http://www.image-net.org/). There are different types of CNNs that have different structures (architectures) that work better or worse depending on your criteria. With this project, you'll explore the three different architectures (AlexNet, VGG, and ResNet) and determine which is best for your application.

### pip

To install these dependencies with pip, you can issue `pip3 install -r requirements.txt`.

### Running

1. cd to `intropyproject-classify-pet-images`

```bash
cd ./intropyproject-classify-pet-images
```

2. Run the script

```bash
./check_images.py
```

(For Windows)

```powershell
python ./check_images.py
```

### Test with all the supported models (resnet, alexnet, vgg)

Run `run_models_*` file (`.bat` for Windows and `.sh` for Linux/Mac)

> Note: the `*_uploaded*` file will be run with the images from `uploaded_images` folder

### Sources

- Cats & Dogs images in `uploaded_images` are from [Kaggle Cats and Dogs Dataset](https://www.microsoft.com/en-us/download/details.aspx?id=54765)
- Others are from the internet (mostly by searching Google Images)
