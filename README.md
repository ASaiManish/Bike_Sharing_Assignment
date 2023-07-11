# Bike Sharing Assignment
Problem Statement:
A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short-term basis for a price or free. A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state.

Essentially, the company wants to know:

* Which variables are significant in predicting the demand for shared bikes.
* How well those variables describe the bike demands


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- Provide general information about your project here.
- What is the background of your project?
- What is the business probem that your project is trying to solve?
- What is the dataset that is being used?

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions

**R2-Squared of lm_rfe_3 model is 0.832 where as r2_score on test data is 0.807. Which we can see difference of 2.5**

**Overall the model lm_rfe_3 we developed is decent model.**

We can see that the equation of our best fitted line is:

𝑐𝑛𝑡 = 0.2635 × + 0.2356 × 𝑦𝑒𝑎𝑟 + 0.3883 × 𝑡𝑒𝑚𝑝 − 0.1535 ×𝑤𝑖𝑛𝑑𝑠𝑝𝑒𝑒𝑑 −0.1467 × 𝑆𝑝𝑟𝑖𝑛𝑔 + 0.0515 × 𝑤𝑜𝑟𝑘𝑖𝑛𝑔𝑑𝑎𝑦 − 0.2821 × 𝐿𝑖𝑔ℎ𝑡𝑆𝑛𝑜𝑤𝑅𝑎𝑖𝑛 − 0.0834 × 𝑀𝑖𝑠𝑡𝐶𝑙𝑜𝑢𝑑𝑦 − 0.0710 × 𝐽𝑢𝑙𝑦 + 0.0531 × 𝑆𝑒𝑝 + 0.0641 × 𝑆𝑢𝑛
 
**The top 8 variables that are seen significant in predicting the demand for shared bikes are as follows:**

Positively correlated top 4 variables:

* Temperature   :  0.3883
* Year	        :  0.2356
* Sunday        :  0.0641
* working_day	:  0.0515


Negatively correlated top 4 variables:

* Light_Snow_Rain	        : -0.2821
* windspeed : -0.1535
* Spring Season : -0.1467
* Mist_Cloudy : -0.0834


## Contact
Created by ASaiManish- feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
