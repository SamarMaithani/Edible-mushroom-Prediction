# Edible-mushroom-Prediction
ML model designed to predict the edible status of the Mushrooms

# About the Project
This Project aims to predict the class of the mushroom whether it is edible or poisonous based on the dataset provided by the organization. The dataset contains verity of features ranging from the cap-shape, to a mushroom’s stem to its habitat all very important features when one looks for figuring whether a particular type of mushroom is safe to eat or not.

To make any sort of prediction from the data, the data is first cleaned, all the duplicates and missing values and all are delt with, then some EDA is performed on the data to remove any outliers and to discover any correlation between the features and after applying some pre-processing techniques a classification ML model is used to figure out the mushroom’s class.


# About the Data
The data Presented to us consists of 60,000+ observations and 20 features + 1 class attribute. Attributes given in dataset as:
- Class: (binary value) --- poisonous(p), edible(e) 
- cap-diameter (m):float number in cm
- cap-shape (n):  bell=b, conical=c, convex=x, flat=f, sunken=s, spherical=p, others=o
- cap-surface (n): fibrous=i, grooves=g, scaly=y, smooth=s, shiny=h, leathery=l, silky=k, sticky=t, wrinkled=w, fleshy=e
- cap-color (n):  brown=n, buff=b, gray=g, green=r, pink=p, purple=u, red=e, white=w, yellow=y, blue=l, orange=o,  black=k
- does-bruise-bleed (n): bruises-or-bleeding=t, no=f
- gill-attachment (n): adnate=a, annexed=x, decurrent=d, free=e, sinuate=s, pores=p, none=f, unknown=?
- gill-spacing (n):   close=c, distant=d, none=f
- gill-color (n):  same as cap-color + none=f
- stem-height (m): float number in cm
- stem-width (m):	float number in mm  
- stem-root (n): bulbous=b, swollen=s, club=c, cup=u, equal=e, rhizomorphs=z, rooted=r
- stem-surface (n): see cap-surface + none=f
- stem-color (n): same as cap-color + none=f
- veil-type (n):   partial=p, universal=u
- veil-colour (n):  same as cap colours + none=f
- has-ring (n):    ring=t, none=f
- ring-type (n):   cobwebby=c, evanescent=e, flaring=r, grooved=g, large=l, pendant=p, sheathing=s, zone=z, scaly=y, movable=m, none=f, unknown=?
- spore-print-colour (n):   same as cap colours
- habitat (n): grasses=g, leaves=l, meadows=m, paths=p, heaths=h, urban=u, waste=w, woods=d
- season (n): Spring=s, summer=u, autumn=a, winter=w


# Conclusion
The project has demonstrated the application of Machine Learning in mushroom classification and how much remarkable potential it has in enhancing the accuracy of the prediction. And through the confusion matrix we saw that the train and test data is balanced. 

Through the utilization of ensemble techniques and vast dataset we have seen the development of a robust model that provides an accuracy of 100%! As the technology's advances, we can expect a greater stride in the accuracy and efficiency of the machine learning models which in turn will contribute to even safer foraging practices and even more understanding of the fungal environment. 
