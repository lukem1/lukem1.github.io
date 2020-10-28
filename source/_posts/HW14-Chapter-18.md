---
title: 'HW14: Chapter 18'
date: 2020-10-22 04:00:00
tags: CSCI362
---
## 18.4
**Define an interface specification for the Currency Converter and Check Credit Ratings services shown in Figure 18.7.**

1. Currency Converter

| Operation |     Inputs      | Outputs |          Exceptions          |
| :-------: | :-------------: | :-----: | :--------------------------: |
|  Convert  | Value, From, To |  Value  | invalidCurrency, ivalidValue |

2. Check Credit Ratings

|   Operation  |    Inputs     |     Outputs    |   Exceptions   |
| :----------: | :-----------: | :------------: | :------------: |
| checkRating  | Name, DOB, ID |     Rating     | invalidRequest |
|  batchCheck  |     [IDs]     | [(Rating, ID)] | invalidRequest |
