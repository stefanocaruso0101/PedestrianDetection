# PedestrianDetection

Authors: Stefano Caruso Overview

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

During exploration of the topic I reviewed these resources for a deep understanding of the field and industry of autonomous driving and Pedestrian detection with CNN model utilization.

Modeling

Results

If this model were to be put to use, we believe we would fulfill the state approval.

Conclusion

One limitation

Repository Structure ├── Data <- Collection of provided data. ├── development-notebooks <- Narrative documentation of analysis in Jupyter notebook. ├── images <- Images used in PDF and README. ├── .gitignore <- Rules to ignore by Github. ├── README.md <- This file. └── green-housing-dev-analysis.ipynb <- Jupyter Notebook containing exploration and analysis of our data.
