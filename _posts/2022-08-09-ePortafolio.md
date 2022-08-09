---
title: "Facebook Data"
categories: ePortfolio
excerpt: |
  Facebook Data
feature_text: |
   Here I write about my experiences with Data from Facebook.
feature_image: https://picsum.photos/1300/400?image=373
image: https://picsum.photos/1300/400?image=373
---
-   <a href="#facebook-data" id="toc-facebook-data">Facebook Data</a>
    -   <a href="#facebook-data-what-is-it"
        id="toc-facebook-data-what-is-it">Facebook Data, what is it?</a>
    -   <a href="#why-did-i-use-facebook-data"
        id="toc-why-did-i-use-facebook-data">Why did I use Facebook Data?</a>
    -   <a href="#my-contributions-to-research"
        id="toc-my-contributions-to-research">My Contributions to Research</a>
    -   <a href="#drawbacks-of-using-facebook-data"
        id="toc-drawbacks-of-using-facebook-data">Drawbacks of using Facebook
        Data</a>
    -   <a href="#references" id="toc-references">References</a>
    
# Facebook Data

During my PhD, I worked with data from Social Network Sites. One of those sources was Facebook. Therefore, in this post, I would like to give a short overview of: What Facebook data is; Why I used It; My Contributions to Research; and the Drawbacks of using Facebook Data.

## Facebook Data, what is it?

Researchers outside of Facebook use the Facebook Marketing Manager to extract the number of Facebook users that match certain demographic characteristics. In this [document](https://github.com/SofiaG1l/Taller_COLMEX_API/blob/main/Facebook_API/FB_GUI_Audience.pdf), I explain how to use the graphic user interface of the Facebook Marketing Manager. In it, I check the number of Facebook users that are in Germany and that are older than 17 years old. As you can see, the Facebook Marketing Manager returns the “Estimated audience size” of Facebook users in Germany that are older than 17 years old, which in April 21st 2022 was between 40.4 million and 47.6 million. 

## Why did I use Facebook Data?

Sometimes, researchers face data availability problems. This means that there isn’t data to study the population or social phenomena that they are interested in. For example, for my first PhD projects, I wanted to study older people’s usage of Information and Communication Technologies. Specifically, I was interested on whether the use of social network sites was associated with older people’s access to their family and friends. So far, researchers had mostly relied on qualitative analysis to answer this question. This means that researchers had performed in-depth interviews to small samples of participants (around 10 to 20). Therefore, research was still missing at the population level. 

Here is when data from Facebook became appealing for my research. Facebook is one of the largest social network sites used in Europe and their data is free and easy to access. So, I decided to combine data from a representative survey of older people in Europe and data from Facebook (which is representative of the people using the platform) to analyze whether the use of social network sites was associated with older people’s access their family and friends (Gil-Clavel et al. 2021).

## My Contributions to Research

During my PhD, my contributions to research in terms of Facebook data came in three ways. First, I developed easy to use and generalize R code to interact with the Facebook Marketing Manager through its Application Programming Interface. My code is quite robust to changes to the Application Programming Interface made by Meta (i.e., the parent company of Facebook). These features make my code the best way to interact with the Application Programming Interface using R.  To learn how to retrieve data using the Facebook API, you can follow this tutorial: [https://github.com/SofiaG1l/Taller_COLMEX_API/blob/main/Facebook_API/Facebook_API_FB_en.md](https://github.com/SofiaG1l/Taller_COLMEX_API/blob/main/Facebook_API/Facebook_API_FB_en.md)

Second, I assessed Facebook penetration by gender, age, and country in the world. In the case of age, I found that gender-based discrepancies are mediated by age and generally don’t exist for older users. In the case of gender, in Facebook women have larger close friend networks and use Facebook when traveling more. The results of this work can be found in my first dissertation article: Gil-Clavel & Zagheni (2019) ([link](https://ojs.aaai.org//index.php/ICWSM/article/view/3263)).

Finally, based on the results of my first paper, I decided to study older people’s close friends online and offline (Gil-Clavel et al., 2021 ([link](https://doi.org/10.1007/s11113-021-09682-3))). What I found is that older migrants may be the ones that compensate for the potential lack of in-person close friendships with digital relationships. This is because migrants who use the internet are, on average, less likely to have close friends to interact with offline, but migrants who are Facebook users are more likely to have close friends online. You can find more info in my [interview](https://www.demogr.mpg.de/en/news_events_6123/news_press_releases_4630/news/do_migrants_over_50_use_social_media_to_maintain_friendships_9858).

## Drawbacks of using Facebook Data

There are two main drawbacks to the use of Facebook Data. First, the data is an estimation of the number of Facebook users, and Facebook is not used by everyone in the world. Second, Facebook does not give access to the algorithms used to classify users as having certain attributes. So, researchers have to continuously test whether the data is reliable for their research.

To understand the estimation problem, let’s cite the United Nations estimation of the German population older than 17 years old in 2021 ([link](https://data.un.org/Data.aspx?d=POP&f=tableCode%3A22)): around 70 million. This value is bigger than the estimated number of Facebook users we got from the Facebook Marketing Manager: between 40.4 million and 47.6 million. What does this mean? This means that the number of Facebook users is an underestimation of the real population size. Therefore, when using data retrieved from the Facebook Marketing Manager researchers always have to be careful with the interpretation of the results and the estimation of the data. This lack of match between the Facebook estimation and the countries populations can be solved using different statistical instruments. As such, [Emilio Zagheni](https://www.demogr.mpg.de/en/about_us_6113/staff_directory_1899/emilio_zagheni_2243/) has many publications explaining how to do it, e.g., Zagheni et al. (2017).

In the case of reliability, this does not mean that Facebook is lying about the definitions. This means that they do not give access to how the variables are operationalized. The definitions could come from the users’ profiles or from black-box algorithms. As an example, let me refer to my article: Gil-Clavel et al. 2021. When studying older people’s usage of technology an important variable to control for is education. Therefore, when I downloaded the Facebook data, I queried information broken down by level of education. What I found out is that there is a high level of missing data for the variable education in Facebook. This could be because Facebook users do not tend to disclose information about their education in their profile. Therefore, I had to discard the use of that variable in my study. 


## References

* Gil-Clavel, Sofia, and Emilio Zagheni. “Demographic Differentials in Facebook Usage around the World.” Proceedings of the International AAAI Conference on Web and Social Media 13 (2019): 647–50. [https://ojs.aaai.org//index.php/ICWSM/article/view/3263](https://ojs.aaai.org//index.php/ICWSM/article/view/3263).

* Gil-Clavel, Sofia, Emilio Zagheni, and Valeria Bordone. “Close Social Networks Among Older Adults: The Online and Offline Perspectives.” Population Research and Policy Review, October 26, 2021. [https://doi.org/10.1007/s11113-021-09682-3](https://doi.org/10.1007/s11113-021-09682-3).


* Zagheni, Emilio, Ingmar Weber, and Krishna Gummadi. “Leveraging Facebook’s Advertising Platform to Monitor Stocks of Migrants: Leveraging Facebook’s Advertising Platform.” Population and Development Review 43, no. 4 (December 2017): 721–34. [https://doi.org/10.1111/padr.12102](https://doi.org/10.1111/padr.12102).






