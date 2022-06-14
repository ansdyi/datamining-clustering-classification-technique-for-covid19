# datamining-clustering-classification-technique-for-covid19
  COVID-19 is an infectious disease caused by newly discovered type of
coronavirus. The new virus and the disease it causes were not known before the
outbreak in Wuhan - China in Desember 2019 and has now become a pandemic in
many countries around the world. People can be infected COVID-19 from another
people who are already infected with this virus. COVID-19 can be spread mainly
from person to person trough droplets from the nose or mouth that come out when a
person infected with COVID-19 coughs, sneezes or talks.
  This research aims to mapping COVID-19 vurnerable areas using the
Hierarchical Clustering algorithm clustering technique and evaluation using the
Silhouette Coefficient, and early detection based on symptoms confirmed result by
Positive COVID-19 using the Naïve Bayes algorithm classification technique and
evaluation using the Confusion Matrix. The data source used is data compiled and
published on Github website from the Johns Hopkins University Center for Systems
Science and Engineering (JHU CSSE) for the Region dataset and from the data.gov.il
API for symptoms dataset.
  The software used for modeling data processing is the Orange application,
using the Euclidean Distance with Single Linkage technique formed a mapping with 3
cluster groups that were evaluated with the Silhouette Coefficient on the Hierarchical
Clustering algorithm. While using the Naïve Bayes Classifier technique on the Naïve
Bayes algorithm resulted in a Confusion Matrix performance evaluation with k-10
Cross Validation namely Accuracy of 0.847, Precision of 0.906, Recall of 0.871, and
F1 of 0.888.
