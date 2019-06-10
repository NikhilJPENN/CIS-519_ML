# CIS-519_ML

This is course work project - sample code 

An interactive interface is designed to improve drawing skills and retrieve 3D shapes based
on sketch classification and sketch matching. The system involves input, output and
computational steps to recognise and classify free-hand sketch using deep learning neural
network approach. This paper explores the classifier built using a convolutional neural
network (CNN) based on the Sketch-a-Net’s CNN architecture. We not only replicated the
architecture but further experimented with the model by applying it to unseen data (“real
world data”) to understand zero-shot learning. Moreover, we have experimented with the
architecture with multi-channel generalisation that encodes sequential ordering in the
sketching process, and a multi-scale network ensemble with joint Bayesian fusion that
accounts for the different levels of abstraction exhibited in free-hand sketches. The primary
objective of this project is to develop and experiment with set of algorithms and classifiers in
order to accurately classify drawing / human drawn sketches into correct categories.


The data set contains a total of 20,000 sketches that were obtained by crowdsourcing and were
made by non-experts/(non artists), which provides vital because we want to capture the
“rough” or often “inaccurate” drawings that people uses to represent high level abstractions of
daily things like a bird or a toothbrush. Furthermore, the 20,000 sketches are divided into a total
of 250 categories that try to provide a representative sample of many of the daily words used in
human interactions. Each of the categories contains a total of 80 sketches.
