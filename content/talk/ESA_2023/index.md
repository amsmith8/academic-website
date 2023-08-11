---
abstract: Species distribution models (SDMs) are widely used to gain ecological understanding and guide conservation decisions. Since their inception, SDMs have been developed with a wide variety of machine learning algorithms, which have improved considerably with the standardization of modelling workflows and thorough inter-model comparisons of predictive accuracy being performed. However, one property they all have in common is the use of predictors that strongly simplify the temporal variability of driving factors. On the other hand, recent architectures of deep learning neural networks allow dealing with fully explicit spatiotemporal dynamics and thus fitting SDMs without the need to simplify the temporal and spatial dimension of predictor data. One challenge that deserves particular attention is that of model overfitting or the process when a model learns the noise in the data, rather than the general relationships between predictors. Furthermore, models are susceptible to overfitting when statistical evaluations are limited to a single performance measure. Unlike for conventional methods, no such analysis has been done to determine the best working protocols for time series-based deep learning SDMs. This study aims to determine a consistent workflow for such cases and evaluated models on the following parameters: average epoch computation time; number of training iterations (i.e., epochs); architecture-type; and performance statistics. We used the curated presence-only and presence-absence species records from the National Centre for Ecological Analysis and Synthesis (NCEAS) for our analysis. For each species, we used Mcfly, a Python computing language automated model generating program, to create a series of candidate models for four popular deep learning architecture types useful for time-series, which include Convolutional neural networks (CNN), Long short term memory networks (LSTM), Residual networks (ResNet), and Inception time networks (ITN). Each model was optimized and evaluated on measured total accuracy, area under the receiver operating curve (ROC), area under the precision-recall curve (PR), and the average of all three. Average epoch time was 127 seconds across CNN, ResNet, and ITN, with CNN most efficient with an average time of 70 secs. Each model was allowed 500 epochs, but most models only needed an average of 6. Performance results for LSTMs are not yet complete, due to a much longer average computational time. We have found no clear pattern between which statistic to optimize and overall performance, suggesting that the best protocol may be species or study specific.
address:
  city:
  country: 
  postcode: 
  region: 
  street: 
all_day: false
authors: []
date: "2023-08-10T08:00:00Z"
date_end: "2030-06-01T10:00:00Z"
event: Ecological Society of America Annual Meeting 2023
event_url: https://esa2023.eventscribe.net/index.asp
featured: false
image:
  caption: 
  focal_point: Right

location: Portland, OR
math: true

projects:
- Deep-learning

publishDate: "2023-08-10T00:00:00Z"
slides: 
summary: Assessing deep learning protocols for optimizing time series-based species distribution models
tags: ["Machine Learning"]
title: Ecological Society of America annual meeting poster presentation
url_code: ""
url_pdf: "https://www.conferenceharvester.com/uploads/harvester/presentations/FPUUDFDK/FPUUDFDK-PDF-2507388-1391034-1-PDF.pdf"
url_slides: 
url_video: ""

---


