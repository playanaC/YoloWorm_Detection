# *Caenorhabditis Elegans* Detection Using YOLOv5 and Faster R-CNN Networks
![image](https://github.com/playanaC/YoloWorm_Detection/blob/main/pipeline.png)

The detection of *Caenorhabditis elegans* (*C. elegans*) is a complex problem due to the variety of poses they can adopt, the aggregations and the problems of dirt accumulation on the plates. Artificial neural networks have achieved great results in detection tasks in recent years.

In this article, two detection network architectures have been compared: YOLOv5s and Faster R-CNN. Accuracy and computational cost have been used as comparison criteria. The results show that both models perform similar in terms of accuracy but the smaller version of the YOLOv5 network (YOLOv5s) is able to obtain better results in computational cost.

# Image adquisition system:
- Images were captured by an [open hardware system](https://github.com/JCPuchalt/SiViS).


# References:
- Puchalt, J. C., Sánchez-Salmerón, A.-J., Martorell Guerola, P. & Genovás Martínez, S. "Active backlight for automating visual monitoring: An analysis of a lighting control technique for *Caenorhabditis elegans* cultured on standard Petri plates". PLOS ONE 14.4 (2019) [doi paper](https://doi.org/10.1371/journal.pone.0215548)

- Puchalt, J.C., Sánchez-Salmerón, A.-J., Ivorra, E. "Improving lifespan automation for *Caenorhabditis elegans* by using image processing and a post-processing adaptive data filter". Scientific Reports (2020) [doi paper](https://doi.org/10.1038/s41598-020-65619-4).

- Puchalt, J.C., Sánchez-Salmerón, A.-J., Ivorra, E., Llopis, S., Martínez, R., Martorell, P. "Small flexible automated system for monitoring *Caenorhabditis elegans* lifespan based on active vision and image processing techniques.". Scientific Reports (2021) [doi paper](https://doi.org/10.1038/s41598-021-91898-6).

- # Citation:
```
@InProceedings{Guardiola2022,
author="Rico-Guardiola, Ernesto Jesús and Layana-Castro, Pablo E. and García-Garví, Antonio and Sánchez-Salmerón, Antonio-José",
editor="Pereira, Ana I. and Ko{\v{s}}ir, Andrej nd Fernandes, Florbela P. and Pacheco, Maria F. and Teixeira, Jo{\~a}o P. and Lopes, Rui P.",
title="Caenorhabditis Elegans Detection Using YOLOv5 and Faster R-CNN Networks",
booktitle="Optimization, Learning Algorithms and Applications",
year="2022",
publisher="Springer International Publishing",
address="Cham",
pages="776--787",
abstract="The detection of *Caenorhabditis elegans* (*C. elegans*) is a complex problem due to the variety of poses they can adopt, the aggregations and the problems of dirt accumulation on the plates. Artificial neural networks have achieved great results in detection tasks in recent years.",
isbn="978-3-031-23236-7"
}
```
