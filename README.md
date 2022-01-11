# Anomaly-Detection-on-KDD-Cup-1999-with-OC-SVM
The One-Class SVM is a modified support vector machine model that is well-suited for novelty detection (an example of semi-supervised anomaly detection). The idea is
that the model trains on normal data and is used to detect anomalies when new data is presented to it. While the OC-SVM might seem best suited to semi-supervised anomaly
detection, since training on only one class means it’s still “partially labeled” when considering the entire data set, it can also be used for unsupervised anomaly detection. We will perform semi-supervised anomaly detection on the same KDDCUP 1999 data. Similar to the isolation forest, the OC-SVM is also good for high-dimensional data. Additionally, the OC-SVM can capture the shape of the data set pretty well.
