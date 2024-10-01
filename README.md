# SSIM-index

This project aims at reimplementing in python the Structural Similarity index (SSIM), an alogirthm used for assessing the quality of a distorted image w.r.t the reference one.
It was introduced by the 2004 paper titled "Image quality assessment: from error visibility to structural similarity". 

We made a presentation on the paper and re-emplemented the algorithm to answer 3 questions:
1. What is the best online AI image upscaling software up to date?
2. Downscaling and upscaling an image by a fixed ratio, how does the quality change as I do this hundreds of times?
3. Downscaling and upscaling an image a fixed number of times, how does the quality of an image change as a function of how much it is downscaled each time (100%, 99.9%, 99.8%...0.1%)?

In this folder are present the 3 scripts we made to answer these questions. 

We used pandas, scikit-image, matplotlib and we worked with the Remini API. 

To install the required dependencies, run the following command:
"pip install -r requirements.txt"


Enjoy ;)
