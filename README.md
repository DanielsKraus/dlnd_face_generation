# dlnd_face_generation
Face generation from celebrity images using Pytorch. 

## Project Overview
________________________________________________________________________________________________________________________________________
DCGAN Deep Convolutional Generative Adversarial Network for generating new celebrity faces by learning from Celeb datasets.  A GAN is a combination of to deep nueral networks that compete with each other.  One network looks for fake images and this is called a discriminator.  The other network tries to generate fake images that are less recognizable to the discrimator this is called the generator. Over time the generator will make progressively better images so that it can fool the discrimator.

## Project Instructions

### Instructions

1. Clone the repository and navigate to the downloaded folder.
	
	```	
		git clone https://github.com/udacity/deep-learning-v2-pytorch.git
		cd deep-learning-v2-pytorch/project-face-generation
	```
2. Make sure you have already installed the necessary Python packages according to the README in the program repository.
3. Open a terminal window and navigate to the project folder. Open the notebook and follow the instructions.
	
	```
		jupyter notebook dlnd_face_generation.ipynb
	```

__NOTE:__ In the notebook, you will need to train GAN in PyTorch.  If your GAN is taking too long to train, feel free to pursue one of the options under the section __Accelerating the Training Process__ below.



## (Optionally) Accelerating the Training Process 

If your code is taking too long to run, you will need to either reduce the complexity of your chosen GAN architecture or switch to running your code on a GPU.  If you'd like to use a GPU, you can spin up an instance of your own:
