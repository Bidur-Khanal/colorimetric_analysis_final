# colorimetric_analysis
This repo contains all the source code, and relevant data and reported results of all machine learning algorithm investigated in our paper.

# Folder structure

├── data
|	├── downsamled_image_data		# contains the pickle files of downsampled images after processing (refer to notebooks/Extract_downsampled_features.ipynb to see how they were created)
|	├── mean_value_data			# contains csv file with mean color values extracted after preprocessing the images (refer to notebooks/Extract_Mean_Pixels_New.ipynb to see how they were created)
├── new_figures 				# contains the figures used in the paper
├── notebooks 
| 	├── ANN.ipynb 				# jupyter notebook code to train, cross-validate and test ANN
|	├── Extract_Mean_Pixels_New.ipynb   	# jupyter notebook code to process and extract mean color values from the images
|	├── Extract_downsampled_features.ipynb 	# jupyter notebook code to process/downsample images and save in pickle files
|	├── Plotting Codes.ipynb		# code used to plot figures and analyze
|	├── Test_Classifiers.iypnb 		# jupyter notebook code to train and test Logistic Regression, Random Forest and SVM on mean color values
|	├── train_and_cross_validation.ipynb	# jupyter notebook code to train and cross-validate Logistic Regresison, Random Forest and SVM on downsampled images saved as pickle files
|	├── train_and_test_on_testset.ipynb	# jupyter notebook code to train and test Logistic Regresison, Random Forest and SVM on downsampled images saved as pickle files
├── results					# contains all results obtained after our experiments in a table format

*For additional information on code structure, please see the comments inside the codes*

# Image Dataset Release 
We also provide the raw image data with corresponsing labels. You need to preprocess the raw images according to use for your case. Please cite our paper if you are using our image dataset

### Image Dataset Structure
├── All food color training data		# contains raw training images of food color and a csv file with corresponding class/label information.
├── All food color test data			# contains raw test images of food color and a csv file with corresponding class/label information. 
├── All pesticide training data			# contains raw training images of pesticide assay and a csv file with corresponding class/label information.
├── All pesticide test data			# contains raw test images of pesticide assay and a csv file with corresponding class/label information.
	
# Citations

If you are using this code, please cite our paper.

```
@article{Khanal_2021,
  doi = {10.33774/chemrxiv-2021-0zbwm},
  url = {https://doi.org/10.33774%2Fchemrxiv-2021-0zbwm},
  year = {2021},
  month = {sep},
  publisher = {Cambridge University Press ({CUP})},
  author = {Bidur Khanal and Pravin Pokhrel and Bishesh Khanal and Basant Giri},
  title = {{Colorimetric detection on paper analytical device using machine learning}},
}
```