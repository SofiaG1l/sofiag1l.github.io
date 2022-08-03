---
title: "Facebook Data"
categories: ePortfolio
excerpt: |
  Facebook Data
output: word_document
feature_image: https://picsum.photos/1300/400?image=373
image: https://picsum.photos/1300/400?image=373
feature_text: null
---


## Facebook Data, what is it?

Researchers, outside of Facebook, have been using the Facebook Marketing Manager to extract the number of Facebook users that match certain demographic characteristics. 

In this [document](https://github.com/SofiaG1l/Taller_COLMEX_API/blob/main/Facebook_API/FB_GUI_Audience.pdf), I explain how to use the graphic user interface of the Facebook Marketing Manager. In it, I check the number of Facebook users that are German and older than 17 years old. As you can see, the Facebook Marketing Manager returns the "Estimated audience size" of Facebook users in Germany that are older than 17 years old, which in April 21st 2022 was between 40.4 million and 47.6 million.

## Why Facebook Data?

Sometimes, researchers face data availability problems. This means that there isn't data to study the population or social phenomena that they are interested in. For example, when studying human migration researchers may not have access to databases with updated values. This could be, for example, because in some countries the only information comes from censuses collected every 10 years.

One possible solution for data availability problems is to run a tailored survey. However, this can be very costly. Therefore, data from Facebook became appealing for research. As it is free and easy to access. 

## The Nais of Facebook Data

There are two main "Nais" to the use of Facebook Data. First, the data is an estimation of the Facebook users, and Facebook is not used by everyone in the world. Second, Facebook does not give access to the algorithms used to classify users as having certain attributes. So, researchers have to continuously test whether the data is reliable.

To understand the estimation problem, let's cite the United Nations estimation of the German population older than 17 years old  in 2021: around 70 million. This value is bigger than the estimated number of Facebook users we got before: between 40.4 million and 47.6 million. What does this mean? This means that the number of Facebook users is an underestimation of the real population size. Therefore, when using data retrieved from the Facebook Marketing Manager researchers always have to be careful on the interpretation of the results and the estimation of the data.

This lack of match between the Facebook estimation and the countries populations can be solved using different statistical instruments. As such, [Emilio Zagheni](https://www.demogr.mpg.de/en/about_us_6113/staff_directory_1899/emilio_zagheni_2243/) has many publications explaining how to do it, e.g. Zagheni et al. (2017). 

In the case of the reliability, this does not mean that Facebook is lying about the definitions. This means that the definition could come from the users' profiles or from black-box Facebook algorithms. As an example, let me cite one of my articles (Gil-Clavel et al. 2021). When studying older people's usage of technology an important variable to control for is education. Therefore, when I downloaded the Facebook data, I queried information broken down by level of education. What I found out is that there is a high level of missing data for the variable education in Facebook. This could be because Facebook users do not tend to disclose information about their education in their profile. Therefore, I had to discard the use of that variable in my study.

## How have I contributed to generate knowledge with it?

During my PhD, my contributions to research in terms of Facebook data came in three ways. First, I developed easy to use and to generalize R code to interact with the Facebook Marketing Manager through its Application Programming Interface. My code is quite robust to changes to the Application Programming Interface made by Meta (i.e. what used to be Facebook). These features make my code the best way to interact with the Application Programming Interface using R. I give more references to this in the section *Want to Download Facebook Data?*.

Second, I assessed Facebook penetration by gender, age, and country in the world. In the case of age, I found that gender-based discrepancies are mediated by age and generally don't exist for older users. In the case of gender, in Facebook women have larger close friend networks and use Facebook when traveling more. The results of this work can be found in my first dissertation article (Gil-Clavel & Zagheni, 2019).

Finally, based on the results of my first paper, I decided to study older people's close friends online and offline (Gil-Clavel et al., 2021). What I found is that "older migrants may be the ones that compensate for the potential lack of in-person close friendships with digital relationships. This is because migrants who use the internet are, on average, less likely to have close friends to interact with offline, but migrants who are Facebook users are more likely to have close friends online. This may be the result of a selection effect: migrants who have fewer friends offline are more likely to use social media to establish or maintain digital friendships." fragment taken from my [interview](https://www.demogr.mpg.de/en/news_events_6123/news_press_releases_4630/news/do_migrants_over_50_use_social_media_to_maintain_friendships_9858). 


## Want to Download Facebook Data?

To learn how to retrieve data using the Facebook API, you can follow this tutorial:

https://github.com/SofiaG1l/Taller_COLMEX_API/blob/main/Facebook_API/Facebook_API_FB_en.md



## References

* Gil-Clavel, Sofia, and Emilio Zagheni. “Demographic Differentials in Facebook Usage around the World.” Proceedings of the International AAAI Conference on Web and Social Media 13 (2019): 647–50. https://ojs.aaai.org//index.php/ICWSM/article/view/3263.

* Gil-Clavel, Sofia, Emilio Zagheni, and Valeria Bordone. “Close Social Networks Among Older Adults: The Online and Offline Perspectives.” Population Research and Policy Review, October 26, 2021. https://doi.org/10.1007/s11113-021-09682-3.


* Zagheni, Emilio, Ingmar Weber, and Krishna Gummadi. “Leveraging Facebook’s Advertising Platform to Monitor Stocks of Migrants: Leveraging Facebook’s Advertising Platform.” Population and Development Review 43, no. 4 (December 2017): 721–34. https://doi.org/10.1111/padr.12102.






