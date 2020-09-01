# Pulsar Classifier
 A classifier using logistic regression and other machine learning models to classify potential pulsars.
 
 The original dataset (https://www.kaggle.com/pavanraj159/predicting-a-pulsar-star) contains a sample of potential pulsars that, in this project, was used to classify pulsars (determine if they were indeed pulsars according to certain features).
 
 Here is some basic information on the topic from Dr Robert Lyon, who led the effort in creating this dataset:
 
 "HTRU2 is a data set which describes a sample of pulsar candidates collected during the High Time Resolution Universe Survey .

Pulsars are a rare type of Neutron star that produce radio emission detectable here on Earth. They are of considerable scientific interest as probes of space-time, the inter-stellar medium, and states of matter .

As pulsars rotate, their emission beam sweeps across the sky, and when this crosses our line of sight, produces a detectable pattern of broadband radio emission. As pulsars
rotate rapidly, this pattern repeats periodically. Thus pulsar search involves looking for periodic radio signals with large radio telescopes.

Each pulsar produces a slightly different emission pattern, which varies slightly with each rotation . Thus a potential signal detection known as a 'candidate', is averaged over many rotations of the pulsar, as determined by the length of an observation. In the absence of additional info, each candidate could potentially describe a real pulsar. However in practice almost all detections are caused by radio frequency interference (RFI) and noise, making legitimate signals hard to find.

Machine learning tools are now being used to automatically label pulsar candidates to facilitate rapid analysis. Classification systems in particular are being widely adopted,
which treat the candidate data sets as binary classification problems. Here the legitimate pulsar examples are a minority positive class, and spurious examples the majority negative class.

The data set shared here contains 16,259 spurious examples caused by RFI/noise, and 1,639 real pulsar examples. These examples have all been checked by human annotators."

Included in the Jupyter Notebook code are visualizations that show the distributions of certain features, as well as how well each given features correlates to its classification outcome. Logistic Regression and KNN were used for predictions. A few different methods were used to determine the accuracy of the classifications. Potential updates to the project could include adding SVM predictions and adding more visuals to compare the outcomes for the different algorithms.
