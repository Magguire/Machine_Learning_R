# Machine_Learning_R

## Introduction

Machine Learning has enabled development of predicitive models for various aspects of business. Marketing for one, is an essential part of business as it contributes largely on customer attraction. The success of most businesses depends largely on profit and market demand. 

## Supervised Machine Learning

Supervised machine learning involves building supervised(use labelled data) prediciive models using appropriate algorithms in order to detect patterns in data. 
Our first project focuses on determining online customer characteristics that determine whether one will click an ad or not.

Characteristics of a viewer include:
* Age - age of the viewer
* Male - 0 for female viewer and 1 for male viewer 
* Country - Country the viewer is located
* City - the city the viewer is located
* Timestamp - the date and time the record of the viewer was taken.
* Area Income - Mean income of the viewer.
* Daily Internet usage - Daily internet usage(Mbs) of the viewer on the specific day.
* Daily time spent on site - Average daily time spent(Minutes) on the blog site by the viewer. 
* Clicked.on.ad - 0 if viewer didnt click on ad and 1 if viewer clicked on the ad
* Ad.Topic.Line - the topic of the ad while the viewer was viewing the blog page.
part1 
[Link text Here](https://rpubs.com/Magguire/910156)

## Unsupervised Machine Learning
Unupervised machine learning involves building unsupervised(use unlabelled data) prediciive models using appropriate algorithms in order to detect patterns in data.
In this project, we shall determine different types of customer groups based on some characteristics. These characteristics include:

* "Administrative", "Administrative Duration", "Informational", "Informational Duration", "Product Related" and "Product Related Duration" which represent the number of different types of pages visited by the visitor in that session and total time spent in each of these page categories. The values of these features are derived from the URL information of the pages visited by the user and updated in real-time when a user takes an action, e.g. moving from one page to another.

* The "Bounce Rate", "Exit Rate" and "Page Value" features represent the metrics measured by "Google Analytics" for each page in the e-commerce site. 

* The "Special Day" feature indicates the closeness of the site visiting time to a specific special day (e.g. Mother’s Day, Valentine's Day) in which the sessions are more likely to be finalized with the transaction. The value of this attribute is determined by considering the dynamics of e-commerce such as the duration between the order date and delivery date. For example, for Valentine's day, this value takes a non-zero value between February 2 and February 12, zero before and after this date unless it is close to another special day, and its maximum value of 1 on February 8.

* The dataset also includes the operating system, browser, region, traffic type, visitor type as returning or new visitor, a Boolean value indicating whether the date of the visit is weekend, and month of the year.

