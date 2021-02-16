# Amazon_Vine_Analysis

![1](https://user-images.githubusercontent.com/73450637/108018980-2d1dfa80-6fe7-11eb-9ec3-97a20b768692.jpg)

## Analysis Overview

The Amazon Vine program is a service that allows manufacturers and publishers to receive reviews for their products. The diagram below gives an overview:

![2](https://user-images.githubusercontent.com/73450637/108019424-378cc400-6fe8-11eb-9eb2-6cf80b8cb5d3.png)

## Resources

* Data Source: Amazon Review datasets, Video Games Review dataset
* Software: Google Colab Notebook, PostgreSQL 11.9, pgAdmin 4, AWS

## Results

### I. Total number of reviews

#### * Vine Reviews

![3](https://user-images.githubusercontent.com/73450637/108019728-d7e2e880-6fe8-11eb-9758-d44e2304e315.png)

#### * Non-Vine Reviews

![4](https://user-images.githubusercontent.com/73450637/108019886-27c1af80-6fe9-11eb-9ccd-063b7a2f76f4.png)

### II. Total number of 5-star reviews

#### * Vine Reviews

![5](https://user-images.githubusercontent.com/73450637/108020232-ef6ea100-6fe9-11eb-9ab3-1cf1df3d766d.png)

#### * Non-Vine Reviews

![6](https://user-images.githubusercontent.com/73450637/108020237-f2699180-6fe9-11eb-8ae6-46754ceee88b.png)

### III. Percentage of 5-star reviews

#### * Vine Reviews

![7](https://user-images.githubusercontent.com/73450637/108020243-f39abe80-6fe9-11eb-8a85-b9f3d3afd214.png)

#### * Non-Vine Reviews

![8](https://user-images.githubusercontent.com/73450637/108020248-f5648200-6fe9-11eb-8023-7f57d0057ee9.png)

## Summary

51% of the reviews in the Vine program were 5 stars reviews whereas the percentage in the non-Vine reviews is only 39%. This shows a positivity bias for reviews in the Vine program.

Additionally we could provide additional analysis of the reviews by considering the genuinity of the accounts that made a review.
