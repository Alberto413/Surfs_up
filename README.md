# Surfs_up

Analyzing weather data in jupyter notebook

## Overview of analysis

The purpose of our analysis is to see temperature statistics for June and December to see if running a surf shop is sustainable year around. The way we get the temperature data is by running two seperate queries, one being for June and the other being December. Once we run our queries we store the temperatures in a list then convert them to a dataframe. Once our dataframe is created we are able to get our summary statistics by using the .describe() method. Here is what we found:

## Results 

- In June we had a total count of 1700, mean of 74.9, min of 64.0 and max of 85.0

<img width="136" alt="Screen Shot 2022-02-21 at 12 34 24 PM" src="https://user-images.githubusercontent.com/95304774/155003565-5e823cad-b0b5-4284-a072-30843cc5004c.png">

- In December we had a total count of 1517, mean of 71.0, min of 56.0 and max of 83.0

<img width="136" alt="Screen Shot 2022-02-21 at 12 35 41 PM" src="https://user-images.githubusercontent.com/95304774/155003746-11227bd8-968e-4573-a875-3dcc85be39e0.png">

- Standard deviation is 3.25 in June and 3.75 in December, making a .5 difference. 

## Summary 

From our data we can tell what our temperatures are but since there are other attributes to the weather such as precipitation it shows that we can run additional queries to let us know whether or not people can come and visit the shop. If we are able to gain more data for the area we can run even more queries, From there we can decide how we would like to build the shop and what areas would make this a more prominent location for visitors to come.
