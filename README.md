# CS668_CapstoneProject
Indoor scene recognition using Deep Learning Model

# Dataset Used: 
Dataset URL: https://bit.ly/41Fkh1m <br /> 
Country: USA (MIT university) <br /> 
15620 images in all  67 Indoor categories (Living Room, Airport) <br /> 
A minimum of  100 photos in each category <br /> 
Every image is in the jpg format. <br /> 
The data set is 2.61 GB.<br /> 

<img width="536" alt="Screen Shot 2023-05-09 at 10 32 43 AM" src="https://github.com/PriyankaNigade1992/CS668_CapstoneProject/assets/97001443/43055b1e-2c17-4a47-ae57-5694cc8d4f46">

# Methodology:
Data Augmentation: Two transformation pipelines are utilized using PyTorch's transformations module to standardise input images.<br /> 
The split-folders package is used to ensure an even distribution of each class across Train and test subsets.<br /> 
Models utilized are: ResNet34, ResNext101_32x16d_wsl, GoogleNet and ShuffleNet.(Minimize risk of vanishing gradient, light weight, state-of-the-art performance , Requires limited computational resources)<br /> 
Model selection is based on complexity, accuracy, and suitability for the available computational resources and dataset size.<br /> 
Model accuracy is used as a measure of performance.

# Testing

<img width="447" alt="Screen Shot 2023-05-09 at 10 37 26 AM" src="https://github.com/PriyankaNigade1992/CS668_CapstoneProject/assets/97001443/4cd4c0a1-e3ce-4db5-9ec7-67f2d39a51a3">
</br>
<img width="460" alt="Screen Shot 2023-05-09 at 10 37 11 AM" src="https://github.com/PriyankaNigade1992/CS668_CapstoneProject/assets/97001443/9ed0b0ff-10b8-4fc8-9a84-431316683a1f">
