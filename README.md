# twitter-algorithmic-bias-challenge

Team name: GT-CLAWS  
Team members: Gaurav Verma, Jongseok Han, Rohit Sridhar, Vivek Anand, Mohit R, Srijan Kumar  
Affiliation: Georgia Institute of Technology 


# Qualitative analysis:
- [TODO]


# Quantitative analysis:
- The code for carrying out the quantitative analysis is present in `Final Image Crop Analysis.ipynb`. This code should use the `crop_api.py` and `image_manipulation.py` included in this repository (instead of the ones included in Twitter's official repository). These updated files automate the evaluation process and disable the display of images to ensure that execution time is low. 
- A GitHub gist for the notebook is provided here: https://gist.github.com/gaurav22verma/57b815339a2eeac831a97af4dff45eed. You can also open the notebook in Colab by clicking on the Google Colab link in the notebook.  
- This notebook can be used to run the code for all `5` types of biases that we have demonstrated by updating the directory from which the images need to be read (read the description of the dataset below) and updating the filenames. 


# Dataset for Twitter Algorithmi Bias Challenge
The dataset link is provided in the final report shared via the HackerOne portal. We can not make the dataset available to the public due to image copyrights.   
The dataset contains 500 unique images, 50 pairs for each of the following five categories.  
1. **Clothing bias**; 50 matched pairs, 100 images, 2500 all pairs. The images are stored in the folder `./clothing_bias`.
2. **Low Income Job bias**: 50 matched pairs, 100 images, 2500 all pairs. The images are stored in the folder `./lowIncomeJobs_bias`.
3. **Obesity bias**: 50 matched pairs, 100 images, 2500 all pairs. The images are stored in the folder `./obesity_bias`.
4. **Disability bias**: 50 matched pairs, 100 images, 2500 all pairs. The images are stored in the folder `./disability_bias`.
5. **Hairstyle bias**: 50 matched pairs, 100 images, 2500 all pairs. The images are stored in the folder `./hairstyle_bias`.

Across all the folders, the matched images are named as `<categoryA>num.jpg` and `<categoryB>num.jpg`. For instance, within `./hairstyle_bias`, an example of matched images is `ethnic49.jpg` and `straight49.jpg`. 
