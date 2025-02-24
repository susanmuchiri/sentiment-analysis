                                                                              SENTIMENT ANALYSIS PROJECT
                                                                              NAME:SUSAN WANJIRU 
                                                                                  PHASE 4


                       BUSINESS UNDERSTANDING

 We live in a world that most people use social platforms in communication and expressing how they feel about a certain topic.

Sentiment analysis, a natural language processing (NLP) technique, is a powerful tool that helps businesses understand the overall mood behind customer feedback, whether positive, negative, or neutral.

By analyzing tweets, companies can monitor their brand reputation, gauge customer satisfaction, and even identify areas of improvement for their products.                      


                         PROBLEM STATEMENT

Best buy, a leading reseller of iPhone and Google products, faces the challenge of stocking its inventory to match customer preferences. The absence of a systematic approach to analyze user sentiments on platforms like Twitter hinders data-driven stocking decisions. This project aims to leverage Twitter sentiment analysis to understand customer opinions better. By gaining insights into user sentiments, Best Buy seeks to improve stocking decisions, ensuring availability of products aligned with customer preferences and enhancing overall satisfaction and loyalty     

                          MAIN OBJECTIVES

1. Improve resource allocation
By using the twitter analysis ,Google and Apple will be able to know which resources are preffered by customers according to how most of them react to the different products.

2.Enhance customer satisfaction
The sentiments from various customers will be able to predict to the companies on what products are most liked by the customers and how they can improve them inorder to make them like the products better.

3.Increase companys profitability.
Ultimately,when the customers are satisfied with the products provided by the companies ,their sentiments on twitter will sell the products to other custoers who never knew about their products ,therefore this wil increase the sales of the companies therfore increasing the profits.


                               DATA COLLECTION

The dataset used for this analysis was sourced from the CrowdFlower dataset available on Data.World. Here is the link to the data. https://data.world/crowdflower/brands-and-product-emotions


                                 FINDINGS


 - Based on the analysis of customer sentiment on Twitter, it was found that Google and Apple brands had the highest number of customers expressing a neutral emotion, followed by a positive emotion. Negative sentiments were least common for both brands.
- It was observed that the SXSW event had a significant influence on customer sentiment and received the highest number of mentions. The release of new products by Apple and Google coincided with an increase in positive sentiment expressed on Twitter.
- The sentiment analysis of tweets revealed a notable amount of negativity towards the design of the iPad device. The Apple Store stood out as a feature that garnered notable positivity among users. Apple's iPhone and iPad devices received the highest positive sentiment among consumers, reinforcing their esteemed reputation within the Apple brand lineup. Among Google products and services, Android devices and Google Maps received the most mentions. 
- Pre-resampling, Naive Bayes model showed poor performance, with a recall of only 2%. However,  Random Forest demonstrated robust performance even before resampling. The resampling method led to improvements across all metrics, further enhancing the effectiveness of the classifiers.


                         RECOMMENDATIONS

  **Further Data Collection**: Given the limitations of dataset size and class imbalance, collecting a larger and more balanced dataset would greatly improve the model's performance and generalization. Consider incorporating more diverse data sources.
- **Context and Sentiment Subtlety**: The model struggles with understanding implicit and subtle expressions of sentiment. Future iterations should incorporate more sophisticated context understanding, perhaps using transfer learning with pre-trained models that can capture nuanced text meaning.
- **Real-Time Processing Capabilities**: As sentiment analysis tools are often needed in real-time applications (e.g., for social media monitoring), focus on building a scalable system that can efficiently handle large volumes of data in real time.                                     
