 # Identifying Ghost Forest Hotspots Using CNN modeling
 ### By Chibuike Okafor Ajani Adovor

We will be replicating a CNN model to map individual dead trees near the Alligator River Wildlife Refuge to indicate hotspots of tree
morality. This is inspired by a paper in review for Nature, titled ‘Overlooked and extensive ghost forest formation across the US Atlantic coast’ that found extensive tree mortality mostly caused by salinization across the east coast.

Problem Statement/Question: 
Are there previously unidentified instances of tree morality in Alligator River Wildlife Refuge?

Objective:
Identify hotspots of tree morality using CNN model published in ‘Overlooked and extensive ghost forest formation across the US Atlantic coast’

Datasets:
The data is found on [Zenodo] (https://zenodo.org/records/16380867). All of the data was derived from National Agriculture Imagery Program (NAIP) images in 2020.

Packages:
pandas, numpy, matplotlib.pyplot, matplotlib.dates, sklearn.preprocessing, rasterio, and tensorflow

Methods: 
Using the CNN model explained in the [Nature] paper (https://www.researchsquare.com/article/rs-6396849/v1), we will replicate mechanism for mapping and identifying dead trees. To enhance the training data, we will use data augmentation, including flipping, cropping, gaussian blur, contrast stretch, and affine transformation.

Expected outcomes:
Hopefully we will be able to produce a map similar to this:
!(/Users/chiokafor/Desktop/Screenshot 2025-10-29 at 1.52.01 PM.png)

Any other relevant information, images/tables, references, etc:
!(/Users/chiokafor/Desktop/float_image2.jpeg "Figure of distribution of dead tree")

(https://zenodo.org/records/16380867)
(https://www.researchsquare.com/article/rs-6396849/v1)
(https://ee-chihgyeung.projects.earthengine.app/view/treedeath-atlanticus)
(https://www.science.org/content/article/ai-reveals-vast-ghost-forests-along-u-s-coast)

