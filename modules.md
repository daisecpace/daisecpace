---
layout: page
title: Modules
permalink: /modules/
---


**Module 1 -   Identify Machine Generated Domain Names

Domain Name Data Set: Legitimate domains (labeled as negative cases) are collected from the Alexa list of top web sites. The Alexa Top Sites web service provides access to a list of web sites ordered by Alexa Traffic Rank. We collected about one million entries from Alexa’s list on September, 2017.

DGA domain data is collected from the DataDrivenSecurity website. These DGA domains are from recent botnets including “Cryptolocker”, two separate “Game-Over Zeus” algorithms, and an anonymous collection of algorithmically generated domains. In total, there are 52,665 entries DGA domains in this data set. In this tutorial, we will use 1000 DGA domains randomly selected from this data set for the analysis.


Please download the tutorial and the dataset.





**Module 2 – Fraud Detection Analysis

Online transactions dataset: For this module, we modified a readily available dataset to promote answering open ended question with analytics. Specificely, we used UCSD DataMining Contest 2009 Dataset that was downloaded from https://www.cs.purdue.edu/commugrate/data/credit_card/. Online transactions dataset simulates credit card transactions of an e-commerce website. Sample data is as below.

amnt 	hr 	day 	state 	zip1 	custAttr1 	CustomerEmail 	CC type 	Mobile 	Balance 	Till Expiration 	Susp. Cat 	Susp. Tx. 	F 1 	F 2 	F 3 	F 4 	F 5 	Fraud 
12.95 	0 	1 	WA 	986 	12345 	luhxsodzmjhng7 	0 	0 	-723 	19 	0 	0 	0 	0 	0 	0 	1 	0 
38.85 	0 	1 	WA 	980 	12345 	pfixypvkcg 	3 	1 	5497 	14 	1 	0 	0 	0 	1 	0 	1 	0 

Customers: Second we prepared a “customers” dataset derived from the transactions. This dataset aggregates the transactional data at the customer level. Sample data is as below

Customer 	Average of amount 	# Tnx 	 # Fraud 	bal avg 	Bal std 	F 1 	F 2 	F 3 	F 4 
aaajfenizilbv@yahoo.com 	49.95 	1 	0 	-3384.00 	0.00 	0 	0 	0 	0 
aaawmprmbeldr58@comcast.net 	49.95 	1 	0 	-2193.00 	0.00 	0 	1 	0 	0 


Please download the tutorial and the dataset.



**Module 3 – Image Manipulation Detection

Twitter Dataset: Face Swap images were downloaded from Twitter searching from hashtags like #FaceSwap that indicates the image suffered some kind of manipulation. The Celebrity Face Dataset is a free public dataset that contains face images without any manipulation. There are 2546 images in total; 1039 images are non-manipulated and 1507 are manipulated. Below are some examples from each category.

Doctored Images Dataset:  This dataset consists of a series of more general images than face images in dataset 1. There are 566 original images collected from a varying number of situations, and they form category one: Original dataset. Each of these images was manipulated using some image editing tools like photoshop, and they form category two: Doctored dataset. The purpose of collecting dataset 2 is to test how deep learning models can detect manipulated images from more general situations.

A 16-page tutorial was created to instruct students to train and test a convolutional neural network (CNN) for detecting manipulated images 

In addition to the modules, the following manuscripts were generated

Manuscript 1 –  Detecting Algorithmically Generated Domains Using N-grams Methods

Abstract— Domain generation algorithms (DGA) has quickly become the main method for attackers to communicate with their bot and malicious software. Various families of recent botnets such as Necurs, Dridex and Kraken have used DGA to generate a large number of random domains dynamically so that static domain lists become ineffective. Some researchers have introduced many detection methods and had moderate success. However, their methods either had high false positives or failed to detect those DGA use variations forms. This goal of this article is to explore how artificial intelligence, particularly text processing and machine learning, is leveraged to detect machine generated domain names. We tested traditional methods in classification of domain names has low accuracy on dictionary-based DGA. We purposed a new benchmark method based on N-grams that can be leveraged in the DGA detections. In addition, we compare our model with other DGA detecting models and our experimental results show that the analysis of N-Gram methods can make a great progress with 99.79% detection accuracy rate and 0.67% false positive rate. At last, we found an optimal N values in N-gram methods for domain names

Manuscript 2 –  Understanding Nigerian Email Scams: a Content Analysis Approach


Abstract—Nigerian email scams have been around for a long time and they are still remarkably successful. Understanding these scams requires in depth analysis of email content.  In this study, we explore using computational content analysis techniques for investigating such email scams – a process usually done with qualitative analysis of email messages.  We then experiment using our findings to further study characteristics of the scammers.


