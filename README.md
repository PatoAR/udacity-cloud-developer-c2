# Udagram Image Filtering Microservice

This is the submission code for the Image Filtering app project in Part 3 of Udacity's Cloud Developer Nanodegree.

The deleteLocalFiles([filteredpath]) is now working, but it deletes the file before the res.sendFile is finished. I have been trying to solve this but could not find a workable solution.

The link to the endpoint URL of the running elastic beanstalk is:

image-filter-pato-dev.us-east-1.elasticbeanstalk.com 

You can try to following image, showing it works well

http://image-filter-pato-dev.us-east-1.elasticbeanstalk.com/filteredimage?image_url=https://upload.wikimedia.org/wikipedia/commons/b/b8/Messi_vs_Nigeria_2018.jpg
