---
layout: page
title: speech emotion recognition
description: how machines recognize emotions in speech
img: assets/img/6.jpg
importance: 3
---

Speech emotion recognition by machines is a difficult task due to the subjective nature of emotions, as opposed to the effortless perception of emotions in the speech by humans. How does the classification of emotional utterances by human raters differ from machine learning models? Which emotion types show a strong correlation between human raters’ performance and modeling results? 

To answer these two questions, in addition to gathering human ratings of emotional utterances, this project uses the openSMILE Python package to extract a large set of features. A subset of selected features is then used to train support vector machines (SVM) and convolutional neural network (CNN) classifiers to predict the emotion labels of utterances. The work is still ongoing and preliminary findings will be reported in the ASA meeting in Chicago in May.

<div class="publications">

{% bibliography -f project_2 --group_by section, year --group_order descending, descending %}

</div>