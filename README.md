# Sea turtle Head Detection

<p align="center">
    <img src="https://www.unidformazione.com/wp-content/uploads/2018/04/unipd-universita-di-padova.png" width="250" alt="University of Padua"/>
</p>

Artificial Intelligence has seen a huge development over the years. Thanks to this potential, it is of the uttermost importance to use AI for the well-being of humans and of the world they are living in.
The 2030 Agenda for Sustainable Development, adopted by all United Nations Member States in 2015, provides a shared blueprint for peace and prosperity for people and the planet, now and into the future. At its heart are the 17 Sustainable Development Goals (SDGs), which are an urgent call for action by all countries - developed and developing - in a global partnership. 

<p align="center">
    <img src="https://ec.europa.eu/eurostat/documents/4187653/8661125/E_SDG+goals_icons-individual-rgb-14.jpg/bc3ed89f-9fa9-4c27-a4c0-bb6d9ccac270?t=1533797139000" alt="Life Under Water">
</p>

Among these goals, n.14, "Life Under Water", got my attention and that is why I decided to implement an object detection model that is able to localize in an image turtles' heads. 
I used RetinaNet for the Object detection task and the results were quite promising: 87% IoU score.

<p align='center'>
    <img src="./Prediction_Example.png">
</p>

In this repo you can find the report of my research along with the notebooks I used:
- [Report](AI_report.pdf) (read first): The report contains an explanation of the problem, why it is important for humanity and the Earth, and technically the approaches that were used for predicting the bounding boxes.
- [Regression with RetinaNet](https://github.com/AlbertoFormaggio1/turtle-head-detection/blob/main/sea_turtle_keras_cv.ipynb): in this notebook I used RetinaNet along with several backbones in order to find the best setting for finding turtles' heads in an image.
- [Naive Regression](sea_turtle_regression.ipynb): in this notebook instead I just used some backbones followed by regression layers to predict the 4 corners of the bounding box directly.


<p align="center">
    <img src="https://www.fisheries.noaa.gov/s3/styles/original/s3/dam-migration/1280x800-sea-turtle-ucsc-edu.jpg" alt="Sea Turtle">
</p>
