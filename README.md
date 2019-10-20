# Energy-Plant-recommendation-for-Biofuel
Every year in the months of harvest,(October, November) Farmers from Punjab and Haryana burn paddy straw( around 35 million tonnes) to clear the paddy fields, to quickly clear the fields. They have 25 days before they have to prepare the fields for the wheat crop. The burning is harmful to the environment as well as to the soil nutrients and to health. They not only help in reducing pollution but also incentivizes farmers to not to burn. They are in the process of expanding to 22 Districts of Punjab. This business couldn’t survive if the transportation cost is too high. So we used Data analytics to recommend the locations which are dense in paddy fields to use their plants to the fullest capacity and also minimize the transportation cost. To do so , we scraped the google satellite data to find dense farmlands in the form of images which are then processed further for patch detection.

# objectives
Extract zoom level images of a region (approximately 30km radius) <br />
Perform Image segmentation on the images and mask out paddy fields. <br />
Attach the images to create a clear map <br />
Calculate the area of each patch <br />
Recommend Top N patches using various heuristics. <br />

