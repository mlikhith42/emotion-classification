# emotion-classification

flattened 101*101 pixels image into vector .

used dimensionality technique "principle Component analysis ".

found the best k for which the seperation between the classes is maximum.

build the model  using fisher classifer to detect the emotion on the face.
    S_b gives the covariance between classes
    and S_w gives the covariance within the class.
    To get the best classifier , the covariance between classes should be maximum 
    and covariance within class points is minimum.
    the fisher classifier is defined as the max eigen vector of the inv(S_w)S_b.
    
 Got an accuracy of 100% on the test data.
