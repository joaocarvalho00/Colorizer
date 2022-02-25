# Colorizer

I used this project to try and learn more about computer vision as I previously had done a project in NLP. The aim of this project was to take a black and white image and give it a realistic color scheme.

I tried to follow this paper:
http://iizuka.cs.tsukuba.ac.jp/projects/colorization/data/colorization_sig2016.pdf

I had problems when training this algorithm because the model proposed by the authors is way beyond my computing capabilities because I was trying to train this in my laptop and each epoch took increasingly more time with the first one being like 10 hours. 

Even so I learned a bit about computer vision and about color spaces as I had to work with different color spaces ( LAB and RGB ) and try to understand what each one of them represented.

The testing.ipynb file has one example of the algorithm trying to output an image in color, it is possible to see some splashes of color in the sky, the water and a little bit on the trees.
