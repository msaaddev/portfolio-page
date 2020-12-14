---
title: Shortify
layout: page
---

## Inspiration

There are a couple of reasons why I decided to build this web application. One of them is to save the readers time. Students who just want to go through a chapter can paste the entire chapter in this application and can get an overview. People who don't have time to read the entire article because of their busy schedules can use this application to get a gist of what they are reading.

## What it does

Shortify is a web application that is designed with a key point in mind i.e., to save user's time. It uses a Natural Language Processing (NLP) technique called BERT summarization extraction to provide the user a gist/summary of any article whatsoever. The client-side of the application uses React.js whereas the backend is designed in Flask, a python framework.

## How I built it

I made use of the following technologies for this project.

### 🌐 React.js

As mentioned earlier, the clientside of the application is using React.js. It is a JavaScript frontend library developed by the folks at Facebook Inc. For writing the code, I made use of the following React.js practices:

- Controlled Components for state management
- Functional Components (Recommended by Facebook)
- React.js hooks for making API requests and dealing with the state

### 💥 Flask

I chose to work with Flask because the NLP model I used was written in python. The overall architecture is as simple as it gets. To make the clientside and backend talk, I wrote a route that was taking the content or the URL from the frontend and then sending the summary content as a response.

### 📦 BERT Model

In this project, we're using an NLP model (BERT). This model utilizes the HuggingFace Pytorch transformers library to run extractive summarizations. This works by first embedding the sentences, then running a clustering algorithm, finding the sentences that are closest to the cluster's centroids. This library also uses coreference techniques, utilizing the [Neural Coref](https://github.com/huggingface/neuralcoref) library to resolve words in summaries that need more context.

## Challenges I ran into

I ran into the following challenges during bringing this application to life:

1. Most of us were completely new to Machine Learning. Only one of the teammates had past experience with ML.
2. All of us were mostly proficient with JavaScript. So working with python for the backend development was fairly new to us.
3. Making the BERT extraction model run was one of the biggest challenges.

## Accomplishments that we're proud of

There are two accomplishments of which I are really proud of.

1. Having a working prototype at the end of the hackathon.
2. Integrating the URL feature that takes an article URL and then generates its summary.

## What I learned

1. All of us learned how to work with Python and how to integrate a JavaScript frontend with a Python backend.
2. I learned to use models in our application which most of us previously had no idea how to do.
3. I also have an overview now about how the Machine Learning specifically NLP works.

## What's next for Shortify

I are open to suggestions. Right now, I need to work on the following:

1. Our website is not responsive. The first thing that I would do is make it mobile-friendly.
2. Improve the model to decrease the summarization time.

## Open Source Projects Used

I used the following open-source projects in our application.

- React.js for frontend
- BERT Extraction Model for NLP
- VuePress for building documentation website

## Documentation

[Click here](https://shortify-docs.vercel.app/) to see Shortify documentation website.
