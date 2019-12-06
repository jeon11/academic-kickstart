---
title: Yelp Dataset Challenge
subtitle: Predicting Positive/Negative Yelp Reviews Using Textual Features
summary: By analyzing Yelp’s dataset, specifically star ratings and text reviews, we created a classifier that predicts whether reviews are positive (star ratings of four or five) or negative (star ratings of one or two). We excluded star ratings of three because we weren’t sure whether they were positive or negative. While Yelp’s star ratings are helpful for concise overview of local businesses
tags:
- research
- cognition
- classifier
- python
date: "2016-12-10T00:00:00Z"


# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: ""
  focal_point: Smart
  preview_only: true

url_code: "https://github.com/jeon11/YelpDatasetChallenge"
url_pdf: "/pdf/YelpDatabaseChallenge.pdf"
url_slides: "https://drive.google.com/file/d/0B9S8oX9rcjjjdnhnaTdma1RjTlE/view?usp=sharing"
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---

By analyzing Yelp’s dataset, specifically star ratings and text reviews, we created a classifier that predicts whether reviews are positive (star ratings of four or five) or negative (star ratings of one or two). We excluded star ratings of three because we weren’t sure whether they were positive or negative. While Yelp’s star ratings are helpful for concise overview of local businesses, they are also crucial metrics for businesses as the ratings reflect their reputations. However, we realized that star ratings are often misleading as they are subject to user bias and preference. Thus, we wanted to predict ratings solely based on textual features of the reviews and exclude any potential human errors and biases. Performing logistic regression with the combined five features, we were able to correctly predict the reviews with an overall accuracy of 79%.
