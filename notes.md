computer vision is bascally enabling the models to learn abou the images and videos . the inout is an image which passes through a dl,ml ,non-mml models and gives us some predictions 


# MACHINE LEARNING VS DEEP LEARNING :
in trditional machine lerning we gve data + feature extractiona and then feed it to th model and then it makes the prediction ....... but in the Deep learning we just feed the data and  the neural network does the feature extraction and classification by its own and give us the prediction because we struggle a lot in the feature extraction and here deep learning got so much importance 

# TRADITIONAL CV WITH TH USE OF FILTERS :
filters are the matrices which we hand written with some logi behind it .then this convoled with the image to detect the edges,shapes,corners,horizontal lines,edges ,vertical edges and any other features in the image .
![alt text](image.png) 
we multiply each filter ntry with the corresponding pixel intensity and the poduct produces the new single intensity... agar padding nahi dale to jo output image rahegi wo output ke dimesnion ki hi rshegi (simply dekhneka ki kernel kitne baar ek pur row me float karta to utn he dimension ka ouput image rahega ) and padding dale to image ke dimension ka he output rahwega 

# edge : sudden chage in the intensity pixel 
agar pixel value very low value se achanak jump karti hai to high value and vice versa rhen we can say there is a presence of the edges 

# types of filters 
# 1.sobel and prewitt
sobel and prewit have 2 filtes gx and gy whihc detecs edges in the vertical and horizontal edeges 

# 2.laplacian filter
it uses the second derivtive of image intensity and detectes the edegs all at onces measn there are no 2 filters for x axis and y axis  so in a single response only it can detect the edges all at once 


# learing rate :-
it means how quickly model is updating and if it too small it wil be too small nd too bifg then we can mis the local minima 

# hyperparametrs
epochs
learning rate
batch size 
nodes in hidden layer 
img height/width

# W&B is used today in real-world ML and AI engineering workflows. It is especially useful when teams train multiple models, compare experiments, tune hyperparameters, and track results.
uv add wandb
wandb login