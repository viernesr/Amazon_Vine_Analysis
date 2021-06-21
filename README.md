# Amazon Vine Analysis

## Overview

The purpose of this report is analyze Amazon reviews written by members of the paid Amazon Vine program. The Amazon Vine program allows manufacturers and publishers to receive reviews for their products. There are 50 readily available Amazon Review datasets, one will be picked to extract and transform the data. Afterwards, the data is then checked to see if there is any bias towards favourable reviews from Vine members in the dataset.

## Results

The dataset chosen was the reviews for videogames. Few points of interest after transforming the data:

* 94 reviews were from Vine members, and 40,471 reviews were regular reviewers
* 48 Vine reviews were 5 stars, while 15,663 regular reviews were 5 stars
* Roughly 51% of Vine reviewers rated games 5 stars, while 38.7% of regular reviewers rated games 5 stars

## Summary

Looking at both percentages, there is an approximate 12% increase in 5 star reviews from Vine reviewers, comapred to regular reviewers. This could suggest a positivty bias. The program itself states that companies are required to pay a small fee to Amazon and provide products to Amazon Vine members. This leads to incentives in being part of the program, possibly affecting how members would review products. One way to tell if the Vine and non-Vine datasets are significantly different is by performing a student's t-test on the percentage of 5 star reviews.
