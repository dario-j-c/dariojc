---
date: "2021-04-25"
external_link: ""
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/S8MSj5VzHxQ)'
  focal_point: Smart
links:
- icon: archive
  icon_pack: fas
  name: Data
  url: https://d396qusza40orc.cloudfront.net/dsscapstone/dataset/Coursera-SwiftKey.zip
- icon: github
  icon_pack: fab
  name: Github Code
  url: https://github.com/dario-j-c/Data-Science-Specialization-SwiftKey-Capstone
# slides: example
summary: Predicting words using n-grams
tags:
- word prediction
- NLP
- Shiny
- r
title: Word Prediction
url_code: "https://dario-j-c.shinyapps.io/nlp_model/"
url_pdf: ""
url_slides: ""
url_video: ""
---


This project uses n-grams generated from provided text to generate a word. The text was sourced by SwiftKey and was taken from blogs, news sites, and twitter.

I chose to use the modified Kneser-Ney algorithm for interpolation which took some time to implement, but found creating a model which fit within the size limitations of the app to be an unexpected road bump.

The app allows you to type whatever you like, you then click 'Predict' and it predicts what the next word for your sentence may be.

Please note, this app is hosted on the free version of Shiny and thus may not be available if the amount of allowed monthly usage has been surpassed.
