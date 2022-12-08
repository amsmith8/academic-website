---
abstract: **Background/Question/Methods:** Species distribution models (SDMs) have become indispensable tools for relating species occurrences to environmental conditions. Most commonly, these models utilize machine learning algorithms to statistically evaluate environmental covariates to determine the relative suitability of locations on the landscape. Currently these models are limited to static predictors, usually constructed from averaging climate data over extended periods. Deep learning neural networks have been used in other fields of research to interpret time series dynamics and can be used to fit SDMs without averaging or simplifying input data, and enable dynamic processes to better inform the models. We tested this modeling architecture using thirty years of monthly bioclimatic data to predict species distribution for four previously studied, globally invasive species: wild boar, kudzu, Asian Harlequin ladybird, and monk parakeet. We compared four deep-learning architectures to traditional methods that used gradient boosted machines (GBM), Maximum Entropy (MaxEnt) and Random Forest (RF) and 19 Bioclim variables. Each model was trained on 35% of collected data (At) and tested on a separate 35% (Av) for internal model accuracy, with 10,000 pseudo-absences and 10,000 bootstrapped occurrences used for each species. **Results/Conclusions:** Of the four deep-learning architectures considered, Convolutional neural networks (CNN), Recurrent neural networks (RNNs), Residual networks (ResNet), and Inception time networks (ITN), we found the ResNet architecture provided the best model for all four species. Final model area under the receiver operating curves (AUCs) were 0.99 for kudzu, Asian Harlequin ladybird, and monk parakeet and 0.93 for wild boar. In all cases, the deep-learning models perform as well or better than than the best model out of GBM, MaxEnt, and RF. The deep learning models required more computation time, with an average of 40 epochs required to achieve the best model fits. Deep learning approaches provided high performing species distribution models and have the distinct advantage of avoiding feature construction that can obscure informative predictors.
address:
  city: Stanford
  country: United States
  postcode: "94305"
  region: CA
  street: 450 Serra Mall
all_day: false
authors: []
date: "2030-06-01T13:00:00Z"
date_end: "2030-06-01T15:00:00Z"
event: Academic Theme Conference
event_url: https://example.org
featured: false
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/bzdhc5b3Bxs)'
  focal_point: Right
links:
- icon: twitter
  icon_pack: fab
  name: Follow
  url: https://twitter.com/georgecushen
location: Source Themes HQ
math: true
projects:
- internal-project
publishDate: "2017-01-01T00:00:00Z"
slides: example
summary: An example talk using Academic's Markdown slides feature.
tags: []
title: Example Talk
url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""
---

{{% alert note %}}
Click on the **Slides** button above to view the built-in slides feature.
{{% /alert %}}

Slides can be added in a few ways:

- **Create** slides using Academic's [*Slides*](https://sourcethemes.com/academic/docs/managing-content/#create-slides) feature and link using `slides` parameter in the front matter of the talk file
- **Upload** an existing slide deck to `static/` and link using `url_slides` parameter in the front matter of the talk file
- **Embed** your slides (e.g. Google Slides) or presentation video on this page using [shortcodes](https://sourcethemes.com/academic/docs/writing-markdown-latex/).

Further talk details can easily be added to this page using *Markdown* and $\rm \LaTeX$ math code.
