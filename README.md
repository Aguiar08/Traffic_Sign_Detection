# Traffic Sign Detection

    With the advance of self driving car technology, the demand for high quality computer vision systems is increasing. On roads, different signs offer important information to a human driver through their visual system.

    For a self driving system we gather this information with a camera and process it with the help of deep learning and computer vision. This could be very useful as a self driving system can be made more aware of the context of the area around it. This has impacts on car safety as well as even navigation where no GPS signal is available.


    In order to process road sign information the computer system must both localize the sign in space i.e. get the [x1,y1,x2,y2] pixel coordinates that define where the sign is in the image and perform a classification in order to define what the meaning of the sign is. In Machine Learning, the "type" of object is referred to as a 'class'.

    In this challenge the dataset contains 676 images of 4 separate classes:
    {'speedlimit': 0, 'stop': 1, 'crosswalk': 2, 'trafficlight': 3}
    with each number in the above dictionary representing its human understandable string.

    The challenge is based around the concept of performing both Regression and Classification simultaneously. The regression is to predict the bounding box coordinates of the sign and the classification to find its class.

    This challenge involves: image pre-processing ,building and training a deep neural network.