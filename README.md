# Experiments with Incremental Learning
Experiments and frameworks for incremental machine learning.

<strong>Why attempt to learn incrementally?</strong>

There are two primary reasons for attempting to build a model that learns incrementally:

<strong>1. Limited Data/Cold start problem</strong>
(<a href="https://en.wikipedia.org/wiki/Cold_start_(computing)"><strong>Cold Start Problem</strong><em>~ Concerns the issue that the system cannot draw any inferences for users or items about which it has not yet gathered sufficient information).</em></a> As we know, building a machine learning model requires a lot of data. This can hamper the inevitable problem of getting started ("Guess we can add ML once we have more data..."). But what if the model could start providing limited (admittedly low accuracy) predictions today and build up over time? 

<strong>2. Data Privacy</strong>
The transfer of large files (training) to the cloud creates data privacy and security issues. Using incremental learning, we can build a model without the need to store sensitive files in the cloud. With this method, any private data can be encrypted in transit and only the model itself is stored on disk. 
