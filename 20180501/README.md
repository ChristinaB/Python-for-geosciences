## 2018-05-01. Satellite radar image processing with python on Amazon Web Services (AWS)

**[Scott Henderson](http://scottyhq.github.io), [UW eScience](http://escience.washington.edu)**

PDF slides in this directory [here](./PythonGeosciences-Henderson.pdf)

Demonstration repository is here:
[https://github.com/scottyhq/landsat-aws-demo](https://github.com/scottyhq/landsat-aws-demo)

Satellite remote sensing of the Earth is utilized extensively by the geoscience community, and computational tools must continuously evolve to keep pace with increasing data volumes. NASA has estimated that by 2025 it will be responsible for storing upwards of 250 Petabytes (PB) of data, and the agency has signaled that it will migrate storage and distribution to Amazon Web Services (AWS). The traditional approaches used by geoscientists to download these data for local processing and analysis is strained due to costly download times and local hardware limitations. One way to break through the bottleneck is to utilize scalable commercial Cloud resources. In this presentation I will discuss an approach to process and analyze large amounts of satellite radar data efficiently on AWS. I will describe what is meant by “Cloud-optimized imagery” and demonstrate several python libraries that are designed to take advantage of geospatial analysis on the commercial Cloud.
