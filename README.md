The goal of this project is to apply supervised learning algorithems to classify a given microbiome sample at the OTU level into one of two cohorts of samples,
i.e, one group consist of healthy subjects samples and the other group consist of samples related to subjects with spesific disorder. The data of each cohort consist 
set of samples, the fearures are the OTU's. the numerical values of each OTU represent the relative abundance inside the sample, i.e, the sum over the sample is equals
to 1. The traditional and more straight forward method to classify sample into one of two cohorts is to measure the mean distance (Bray-Curtis dissimilarity is often
in use) of a given sample from both cohorts and than classify the sample to the cohort with the lowest mean distance. In this work I analize a cohort of Autistic 
spectrum disorder (ASD) patiants and a cohort of control group.
At firs I will check wether a Bray-Curtis dissimilarity PCoA analysis separets the two cohorts into two different clouds
