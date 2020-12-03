# LSGANs
Progressive Growing of Least Squares Generative Adversarial Networks (LSGANs)

The following is an implementation of a LSGANs architecture. This has the capability of growing resolutions 4x4 -> 8x8 -> … ->  4*n x 4*n where n is the step size selected. The step size can be changed on line 1080 of the code file. The dataset used to create the images shown below was a modified CelebA dataset which can be done in the main code file on line 1065. When changing that value to “Yes” the program will extract just the faces at a set resolution size from the CelebA dataset. Please change the file locations where applicable to your own. This file also has the capacity to calculate the Frechet Incpetion Distance and Inception Score by setting lines 1074 and 1075 to yes. 

The “totalnumImages” variable on line 1081 represents the number of images which will be randomly sampled from during the training. While, the “numSamples” variable on line 1112 is the number of images used to determine how many images will be shown per batch and epoch as calculated in the main code file.

![Images Generated](https://user-images.githubusercontent.com/28498567/100966204-5e178480-34fa-11eb-968a-01c083a44969.PNG)

