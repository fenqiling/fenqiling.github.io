---
layout: page
title: emotion recognition
description: how machines recognize emotions in speech
img: assets/img/6.jpg
importance: 2
---

Speech emotion recognition by machines is a challenging task due to the subjective nature of emotions, contrasting with humans' seemingly effortless perception of emotions in speech. Two critical questions arise: How does the classification of emotional utterances by human raters differ from that by machine learning models? Which emotion types demonstrate a strong correlation between human raters’ assessments and modeling results?

To address these questions, this project not only collects human ratings of emotional utterances but also utilizes the openSMILE Python package to extract a comprehensive set of features. A carefully selected subset of these features is then employed to train classifiers, including support vector machines (SVM) and convolutional neural networks (CNN), to predict the emotional labels of utterances.

More findings from this research will be available soon. Please stay tuned for updates.

<div class="publications">

{% bibliography -f project_2 --group_by section, year --group_order descending, descending %}

</div>