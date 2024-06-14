# PASSING NEUTRINOS
## Azimuth and Zenith prediction based on Neural Networks

**Context:** This report explores the study of subatomic particles known as neutrinos. These particles are nearly massless, carry no
electric charge, and, despite being the most abundant particles in the universe, are incredibly difficult to detect. However, the IceCube
Neutrino Observatory, a telescope installed in the ice of the South Pole, is able to detect these elusive particles, enabling scientists to
study their trajectories through the Earth.

**Aims:** A recently closed challenge on Kaggle tasked participants with predicting the direction of these particles, specifically their
azimuth and zenith angles.

**Methods:** The top-performing solutions demonstrated that this prediction is feasible by representing each neutrino event as a graph
and utilizing transformer-based models. My objective was to tackle this task by employing simpler neural networks and a matrix
representation of the data, while also addressing the computational limitations of the available resources.

**Results:** Simpler neural networks achieved good results using only activation timestamps or both timestamps and charge values.The
most performing has been LSTM Layer-based neural network, although at the expense of time. 

**__Datasets__: ** i dataset originali sono presenti su Kaggle al seguente link [https://www.kaggle.com/competitions/icecube-neutrinos-in-deep-ice.](https://www.kaggle.com/competitions/icecube-neutrinos-in-deep-ice/data) In particular, the icecube_3 dataset was created by linking the first three rows of the train folder (batch_1.parquet, batch_10.parquet, batch_100.parquet.
