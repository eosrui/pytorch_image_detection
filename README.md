1. Utilized Python and Keras to extracted features from 40,000 images using the VGG16 model. Employed pooling to transform the dimensions into 2D for subsequent similarity calculation. 
2. Inputted the query image into the network, calculated the cosine similarity between the query image and the images in the library, and returned the Top-K image with the highest similarity.Achieved image search by identifying images with the closest features, achieving an accuracy of 87%.
3. Integrated it with AWS S3 and AWS CloudFront to ensure seamless deployment and enhance performance.
