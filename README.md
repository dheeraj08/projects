# Projects
This is a repository that contains projects I've worked on in the field of Data Science and AI. They cover areas from Data Cleaning and Visualisation all the way to NLP and beyond.
Some of the key summaries of projects contained within the repository are listed below:

# Uber Ride Sharing Analysis
Utilizing a masked data set much like how the data analysts at Uber handle, the goal is to analyse a major problem faced by all ride share companies, driver cancellation and non availability of cars leading to a loss of revenue.

# Finance and Risk Analytics
In the recent past, the industry of wealth management has seen a lot of growth. Individuals and businesses actively seek maximum returns. However, in many cases, they lack either the skills to identify the right investment opportunities or the time to find such opportunities. This challenge gave rise to the dedicated individuals who perform this task on behalf of the investors for a commission: portfolio managers.

A portfolio manager makes investment decisions and carries out other related activities on behalf of vested investors. They work with a team of analysts and researchers, and their main objective is to realize the needs of the investor and suggest a suitable portfolio that meets all the expectations. They are responsible for establishing the best investment strategy and selecting appropriate investments with the right allocations. However, in doing so, they face a lot of competition in the form of other portfolio managers and rival firms. Therefore, the portfolio manager has to use the available resources to provide the best solution to the investor.

<b>The goal was to consider yourself working for an associate at an investment firm that manages accounts for private clients. Your role requires you to analyze a portfolio of stocks to provide consultation on investment management based on client requirements.</b>

# Click Through Rate Prediction
Most of the websites you visit include ads. The online advertising industry is huge, and players such as Google, Amazon, and Facebook generate billions of dollars by targeting the correct audiences with relevant ads.
Most of the decisions about ads are data-driven solutions such as the following: 

<b>How do you know which ad to use and who to target?</b>
<b>Many companies advertise products in the same category, so how do you decide whose ad to display?</b>
<b>Which ad should be placed on which part of the web page?</b>
<b>Should a particular ad be pushed on a mobile device or remain on a desktop or laptop?</b>

An important exercise marketing companies need to do before making any of the above decisions is a <b>click-through rate (CTR) prediction</b>. The objective is to predict whether the audience will click on an ad or not and thus help the marketing team answer ad placement-related questions.

The goal is to analyze a dataset of <b>100,000 rows and 27 columns</b> to predict whether a user will click on an advertisement or not. 

# Healthcare NER
Consider a hypothetical health tech company, BeHealthy, which aims to connect medical communities with millions of patients through a web platform. The platform enables doctors to list their services, manage patient interactions, and provide services such as booking appointments and ordering medicines online. Using this platform, doctors can easily organize appointments, track a patient’s past medical records, and provide e-prescriptions. 

Companies like BeHealthy generate large volumes of data by providing medical services, prescriptions, and online consultations. Let’s take a look at the following snippet of medical data that may be generated when a doctor writes notes to their patient or prepares reviews of their patient.

When such health data is generated for a large volume of customers, we have the potential to tap into it. <b>The goal of this project is to build a custom NER solution to identify diseases and their common treatment types.</b>

# Image Captioning using Neural Networks
The goal with this project is to create a deep learning model which can explain the contents of an image in the form of speech through caption generation with an attention mechanism on Flickr8K dataset. This kind of model is a use-case for blind people so that they can understand any image with the help of speech. The caption generated through a <b>CNN-RNN model</b> will be converted to speech using a text to speech library. 

This problem statement is an application of both <b>deep learning and natural language processing.</b> The features of an image will be extracted by a <b>CNN-based encoder and this will be decoded by an RNN model.</b>

The dataset is taken from the Kaggle website and it consists of sentence-based image descriptions having a list of 8,000 images that are each paired with five different captions which provide clear descriptions of the salient entities and events of the image.

# Attention Based Neural Machine Translation
The goal with this project is to build an attention-based sequence-to-sequence model that can effectively understand the context of Spanish sentences and translate them into clear and coherent English sentences. This was done out of an interest to grasp the knowledge of <b>End to End Sequence to Sequence models.</b>

# Skin Cancer Modelling using Neural Networks
The goal with this project was to build a <b>CNN based model</b> which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for <b>75% of skin cancer deaths.</b> A solution which can evaluate images and alert the dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.

The dataset consists of <b>2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC).</b> All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant.
The data set contains the following diseases:

1. Actinic keratosis
2. Basal cell carcinoma
3. Dermatofibroma
4. Melanoma
5. Nevus
6. Pigmented benign keratosis
7. Seborrheic keratosis
8. Squamous cell carcinoma
9. Vascular lesion
