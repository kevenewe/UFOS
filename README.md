# Surfs_up

Analyzing weather data using Jupyter Notebook and making an app that uses sql alchemy to read data from a given data set.

# overview of Analysis

The purpose of the analysis was to see the temperature statistics for the months of June and December. With the goal to see if it was viable to run a surf shop year round.  We got the data by running two seperat queries using Sql Alchemy, one for June and the other for December. After running the queries the data of the temperatures awas stored in a list and then converted into a panda dataframe. From the dataframe we were able to get the summary statistics by using the .describe() method. The following is what we found:

# Results

From June there was a total count of 1700, mean of 74.9, min of 64 and max of 85.

![June stats](https://user-images.githubusercontent.com/117044267/214887740-3e227f51-b06c-4460-a202-fd77d51f493a.PNG)

From December there was a total count of 1517, mean of 71.04, min of 56, and a max of 83.

![December Stats](https://user-images.githubusercontent.com/117044267/214887771-0ea3a2e6-c324-4496-afba-68934b32fc81.PNG)


# Summary
From the data used you can se what the temeraturea are, however ther are other attribues to weather such as clouds, precipitation. The data shows that we can run additional queries to let us know whether or not people with come and visit the sop.  Obtaining more data for the area would allow us to run those queries. After we have the additional data analysed then it can be decided on how to build the surf shop and what areas would make the best locations for visitors to come. 
