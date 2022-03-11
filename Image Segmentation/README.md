# The Data
The original data set: https://www.kaggle.com/franciscoescobar/satellite-images-of-water-bodies
## Water Bodies Dataset
### Images
Given are about 3000 pictures of bodies of water
### Masks
These are transformed versions of the files in Images to black and white images

# The Project
Image segmentation is the problem of breaking an image up into its constituent parts; that is, it's the process of breaking an image down into clusters.
Important applications of image segmentation include medical imaging, facial recognition, and many topic in computer vision.

This project will require more programming, and dealing with messier data but is good 'real-world' experince with image processing.

This project will require learning how to take an image, map it to a graph, and then apply different methods to this graph in determining the 'community structure'.
Methods like spectral clustering and the Louvain algorithm are used on graphs to then determine similar looking segments of the image.
The data set given is a suggested one, although any image repository will work as well.

Possible steps for this project:
- Determine a mapping from an image to a graph, either from a research paper or something you determined.:
- Analyze the graph using community detection
- Map the communities you found, or didn't find, back to the image
- Analyze the results and the steps in this process
- Report on your findings

## Resources
Python
- Google Colab,, for collaboritve coding environment https://colab.research.google.com/
- Scikit-Image, for image processing https://scikit-image.org/
- CDLib, for community detection https://cdlib.readthedocs.io
- Networkx, for generating graphs https://networkx.org/
- Numpy, for image processing https://scipy-lectures.org/advanced/image_processing/

Links
- Wikipedia https://en.wikipedia.org/wiki/Image_segmentation
- Image Processing using Numpy https://www.analyticsvidhya.com/blog/2021/05/image-processing-using-numpy-with-practical-implementation-and-code/
- Spectral Clustering for Image processing https://people.eecs.berkeley.edu/~malik/papers/SM-ncut.pdf
