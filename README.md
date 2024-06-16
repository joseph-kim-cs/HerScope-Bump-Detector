# HerScope Polyp Detector (Python 3.9)
Business Problem: Finding new alternative or innovative methods in medical device production by expanding into data science oriented solutions. 

Situation: After deciding to go down a route towards solutions in women's health, we interviewed OBGYN's and women's health experts. Through interviews, we were able to determine an area that needs improvement was in operational hysteroscopy, a minimally invasive procedure that allows a doctor to inspect the uterine cavity and perform surgical interventions. This lead us to determine the following needs statement: 
_A way to refine hysteroscopic navigation in women with abnormal uterine conditions to grant clinicians increased endometrium visibility in diagnostic hysteroscopy._

Approach: Examining the problem in a deeper level, we decided on two main approaches. The first was the development of a hardware solution in the form of a rotatable hysteroscope tip. This solution would help increase navigation with a 360° spin on the horizontal plane, and a 140° vertical tilt. With data obtained from this tip, the software aspect can chart a rough 3D map of the uterus. The second solution can examine polyp detection using machine learning. Through images obtained in recordings of polyps, an image-recognition software can be utilized to recognize abnormal polyps in uterine lining. 
As the software team lead, I lead the development of an image-recognition machine-learning application.

Solution: By developing a image-recognition neural network through TensorFlow in Python, we can use a classification supervised learning technique to determine whether a given image or not has a polyp in the picture. For testing purposes, we utilized acne and clear skin image datasets taken from Google. 
You can see the Jupyter notebook in the repo. 
