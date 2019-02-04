#### Group
* Look at what other groups are doing, try the same/similar things
* (A) How the number (or hexbin) of unmasked or density changed along x-y, y-z, x-z?
* (A) Apply box plot to density?
* Use statistics to test differences between z layers?

#### Akash
* What is the loss function being applied?
* What does regression look like for different degrees of the polynomial
* What is the description for knn and assumptions
* Check cluster densities? (how?)
* Anything interesting when rotating/comparing visualizing the centroid by density scatter plots?

#### Bijan
* Clean my 3d vector fields
* Clean my 2d vector fields
* Do some useful statistics on their qualities
* Clean my histograms, overlay, compare
* Redo clustering on initial slices to make sure the 4 are different

#### Emily
* See how synapse density in a layer varies in the X, Y, Z directions
* Looking at the y-layer: can we see layers of the cortex?
* How are synapses distributed in these possible "cortex layers"
* What bin is the spike in? Are the points included in the bin uniformly distributed?
* How does smoothing our data, say by applying a gaussian filter, affect the spike?

#### Jay
* Cluster data only with regards to density, i.e. do not consider coordinate positition. What's the optimal number of clusters?
* Plot clusters in 3D space. Is there any spatial relations between members of the same cluster, or does there appear to be an indepndent relationship between cluster label and spatial position? Also plot clusters against XY, XZ, YZ planes.
* Cluster using DBSCAN algorithm
* Use my gradient estimate to look for local max/mins (look for where gradient is 0). Do they form any clear boundaries between regions in the volume?
* Tying back to what I tried last week, treat underlying distributions as Poisson: try doing linear regression with logarithmic link function (i.e. run a Poisson regression).
