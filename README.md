# Energy-Plant-recommendation-for-Biofuel
Every year in the months of harvest,(October, November) Farmers from Punjab and Haryana burn paddy straw( around 35 million tonnes) to clear the paddy fields, to quickly clear the fields. They have 25 days before they have to prepare the fields for the wheat crop. The burning is harmful to the environment as well as to the soil nutrients and to health. They not only help in reducing pollution but also incentivizes farmers to not to burn. They are in the process of expanding to 22 Districts of Punjab. This business couldn’t survive if the transportation cost is too high. So we used Data analytics to recommend the locations which are dense in paddy fields to use their plants to the fullest capacity and also minimize the transportation cost. To do so , we scraped the google satellite data to find dense farmlands in the form of images which are then processed further for patch detection.

# objectives
Extract zoom level images of a region (approximately 30km radius) <br />
Perform Image segmentation on the images and mask out paddy fields. <br />
Attach the images to create a clear map <br />
Calculate the area of each patch <br />
Recommend Top N patches using various heuristics. <br />

# Problem Formulation
### Image Extraction: 
Images of a region can be taken from the Internet using Google API and python Requests library. <br />
### Image Segmentation: 
Kmeans Algorithm is a fast and efficient clustering algorithm which can
be applied on an image to reduce the gradient effect and form clear segments. Then selecting a
particular segment which contains paddy field, turning it into white and remaining into black. <br />
### Region Map: 
Storing the sequence of order in which images are generated can be applied to the
set of images to bind them into a clear Map. <br />
### Recommendations: 
Calculating the area of each patch and then sort them according to the area
and distance from a certain point.


# Level 1 DFD
![](https://github.com/arshahuja/Energy-Plant-recommendation-for-Biofuel/blob/master/level%201%20dfd.png) <br />

# Scratched Image with Google API
![](https://github.com/arshahuja/Energy-Plant-recommendation-for-Biofuel/blob/master/scraped%20images%20with%20google%20api.png) <br />

# Extracted Images
![](https://github.com/arshahuja/Energy-Plant-recommendation-for-Biofuel/blob/master/extracted%20image.png) <br />

# Stiched Images into a single map
![](https://github.com/arshahuja/Energy-Plant-recommendation-for-Biofuel/blob/master/stitched%20images.png)

# Top N recommendation
![](https://github.com/arshahuja/Energy-Plant-recommendation-for-Biofuel/blob/master/recommendation.png)
