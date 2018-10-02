# A variation of the Expectation Maximization method optimized for clusters that are of elongated shape or forming line segments
#### My undergraduate thesis in Department of Informatics and Telecommunications of University of Athens
----
**This is just the mirror public repo of this project. The code is currently private and will be posted here upon completion.**
----
Codebase of a probabilistic clustering algorithm based on Mixture Models method that estimates the parameters of a number of defined "line segment based" probability distribution functions that best fit a given dataset.  
A detailed presentation along with performance and application reports will be available upon completion. Specifically, an intended application of the algorithm is in image processing for extracting Edge Line Segments of an image, after an Edge Detection filter is applied to the pixels. For that regard, the implementation is focused on the two dimension space only.

Some features of the algorithm include:  
 - A newly defined two dimensional PDF centred around a line segment
 - An initialization step for Edge Segments Detection applications (derived from literature)
 - An overestimation of the number of clusters along with a cluster elimination mechanism
 - A fast method of approximating the principal axis of a given set of points (derived from literature)
