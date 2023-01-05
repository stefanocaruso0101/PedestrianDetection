# PedestrianDetection

Authors: Stefano Caruso 


Overview

Pedestrian classification Model for Motional
Our client Motional has been able to advance autonomous vehicle(AV) technology to the point where their driverless vehicles have driven 1.5 million miles and completed 100,000 passenger trips on public roadways – without a single at-fault accident.
Pedestrian detection is a small subset to the much larger field of object detection that is essential for numerous applications such as person tracking, intelligent surveillance system, abnormal scene detection and our focus today autonomous driving along with many more.

Datasets trained on the basic person detection problem contains only images labelled with person objects.
I obtained a dataset for addressing the false positives that occur during the person detection process. Some objects have very similar features to those of a person. If a model is trained using a dataset containing only persons, it leads to several false positives since it cannot differentiate such objects from that of a person. This dataset includes person and person-like objects. Person-like objects that we introduce in our dataset are statues, mannequins, scarecrows, and robots.



Business Understanding
Billions of people jump in their car every morning and drive to work or run arrands for the day. Moving effortlessly throughout numerous cities across the world. At some point during the day we are confronted by a pedestrian walking a dog, in a parking lot, at a cross walk not realizing how complex our vision is. We detect movement at the slightest glance and instantly calculate if there is danger while driving. Clearly humans make mistakes but our vision is very accuracte, we can not say the same for computer vision unless trained properly it might be more efficient and that is our task at hand, to use machine learning to improve a model that detects pedestrians for our client "MOTIONAL".
Computer Vision consulting (Stefano Caruso) will be representing Motional, the task is to provide a accuracte pedestrian detection machine learning model that I will first trian on person / person like because of its quality and results. Motional must pass government regulation and state level saftey laws prior to autonomous driving in real world applications.
Pedestrian detection is a key factor for the automotive industry to obtain autonomous driving, with over one billion vehicles worldwide, some say the goal is to have them all be autonomous to make the roads a safer place. Before this happens, we need to start with computer vision and image classification.
The problem is a vehicle needs to detect all images accurately or it could lead to system malfunction or worse casualties. We use ML, specifically computer vision to detect pedestrians in many industries including autonomous driving, security surveillance, train stations, cross walks and many more useful applications.
Tesla has started the revolution for autonomous driving, other automotive manufacturers are scrambling to hire top engineers to join their team and build the technology efficiently. Not only is it difficult for the AI to detect pedestrians the speed at which is does the calculation is of great importance.
The impact would not only make the roads safer, it will calculate the best route, save lives, create countless jobs and free up time for other task.



Modeling

Build a CNN model to train on the images to address our business problem of pedestrian detection.
The classes are the target person / person like. After numerous hyperparameter tuning, A valuable final model will have high accuracy score and reduced error. A CNN model is good for image classificatoin because the tensorflow can train on 3 channels values well (colors pixels rbg, 3). Also can detect latent features whith CNN.

Results
We believe that 72% accuracy score on unseen data was satisfying b/c of the testing data size of only 235 images, potentially once we increase the testing size we will achieve our 98% score that we obtained on the training data.
If this model were to be put to use, we believe we would fulfill the state approval.

Conclusion

Training a model on person / person will have a better outcome then training on just pedestrian detection. Applying this strategy will upgrade the autonomous driving applications performance.

The trained modeled performed well on the testing data, of the 230 images in the test data our model was able to correctly detect person / person like 162 times, this is good but I will continue tuning new models and increase the accuaracy rate.

A new technique to look into is combining all the splits together which is 1,339 images and taking a larger split on the testing data of 375 images, I believe this will be significent positive impact.

The next models generated will have more crative regulation systems built into them as well as larger epochs and different batch sizes to obtain higher reliability to assist with safety and government approval.

PARAMS - 660,000 +

Testing data Accuracy - 72%

One limitation
data size and diversity

Repository Structure ├── Data <- Collection of provided data. ├── development-notebooks <- Narrative documentation of analysis in Jupyter notebook. ├── images <- Images used in PDF and README. ├── .gitignore <- Rules to ignore by Github. ├── README.md <- This file. └── green-housing-dev-analysis.ipynb <- Jupyter Notebook containing exploration and analysis of our data.
