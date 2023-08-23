# Hungry birds - Classification of blue tit nestling diet from video footage using machine learning

Computer vision in ecology is becoming increasingly popular as an efficient tool to analyze large data sets from wild populations. For instance, automating classification of behaviours from video footage can increase the breadth, duration, and repeatability of ecological studies, and removes the image processing bottleneck. Additionally, automated
systems provide a non-invasive way to observe wildlife and avoid the disruption created by catching and sampling individual birds. This work presents a novel machine-learning
pipeline to quantify the food provisioning rate of adult blue tits to their nestlings and classify the diet of nestlings. The pipeline is capable of detecting a bird entering a nest box, locating eyes and beak in the image, and classifying the food item carried. In the long run, this work can uncover evidence of action needed to aid birds living in our cities. The networks used to build this pipeline are YOLOv5, Keypoint R-CNN, and MobileNetv3. The food classifier achieved 69% accuracy. The bird detection component allows the researcher to look only at the relevant images of a bird carrying a food item instead of having to search for the visits in long videos.

## License
All the files distributed with this program are provided subject to the BSD-3-Clause license. A copy of the license is provided.
