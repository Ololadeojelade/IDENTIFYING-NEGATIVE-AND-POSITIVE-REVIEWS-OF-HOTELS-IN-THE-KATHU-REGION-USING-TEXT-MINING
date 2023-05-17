# IDENTIFYING-NEGATIVE-AND-POSITIVE-REVIEWS-OF-HOTELS-IN-THE-KATHU-REGION-USING-TEXT-MINING

## INTRODUCTION

Text mining is also known as text data mining. It is the process of converting unstructured text into a structured format with the purpose of identifying significant patterns and fresh insights. The data being worked on could either be structured, unstructured or semi-structured data. Structured data is a standardized data in tabular format which may have lots of rows and columns that makes it very easy to process and keep for analysis or machine learning algorithms. Unstructured data does not have a predefined format and this type of data could be gotten from product reviews which is an example of the type of dataset that is being used for this course work. A semi structured data set is a blend between the structured and the unstructured dataset and an example of this data set can be gotten from HTML files.
Text mining is a method that consists of various steps that let you infer information from unstructured text data. 

The process of cleaning and converting text data into a usable format is called text preprocessing, and it must be done before you can use any of the various text mining techniques.
There are several types of text mining techniques. However, for the purpose of this course work we would be looking at tokenization, stemming, text categorization and sentiment analysis.
Tokenization is the process of breaking out long form text into sentences and words called “tokens”.

Stemming refers to the process of separating the prefixes and suffixes from words to derive the root word form and meaning.

Text categorization is responsible for analyzing text documents and classifying them based on predefined topics or categories.

Sentiment analysis This activity allows you to monitor changes in the attitude of a variable over time by detecting positive or negative sentiment from internal or external data sources.


## EXPLANATION AND PREPARATION OF DATASET

The hotels were selected based on the different regions where the hotels are located. According to trip advisor the Kathu region provides one of the cheapest and affordable hotels within the regions in the country. There are several hotels that offer very good services and Thai Express - Turtle Village is one of the to ten hotels within the region.

![image](https://github.com/Orlawlardey/IDENTIFYING-NEGATIVE-AND-POSITIVE-REVIEWS-OF-HOTELS-IN-THE-KATHU-REGION-USING-TEXT-MINING/assets/124607057/480a93bc-4c69-4eb2-9fed-afb63096fe63)

## IMPLEMENTATION IN PYTHON

The required libraries were imported into python to enable the easy completion of the task.

![image](https://github.com/Orlawlardey/IDENTIFYING-NEGATIVE-AND-POSITIVE-REVIEWS-OF-HOTELS-IN-THE-KATHU-REGION-USING-TEXT-MINING/assets/124607057/f204ca6d-ff14-4a5e-a2ea-6c6f9d93c325)

After importing the necessary libraries, the file for the task was imported into python.

![image](https://github.com/Orlawlardey/IDENTIFYING-NEGATIVE-AND-POSITIVE-REVIEWS-OF-HOTELS-IN-THE-KATHU-REGION-USING-TEXT-MINING/assets/124607057/cfe8b542-47e0-4436-8451-3eeeb7de5a92)


The duplicates in the file were removed from the dataset to avoid repetition of derived values.

![image](https://github.com/Orlawlardey/IDENTIFYING-NEGATIVE-AND-POSITIVE-REVIEWS-OF-HOTELS-IN-THE-KATHU-REGION-USING-TEXT-MINING/assets/124607057/123275a6-8ec7-475a-95b7-44581cc29ef5)

From the entire dataset the reviews from 30 hotels in 6 different locations were used for This task.

![image](https://github.com/Orlawlardey/IDENTIFYING-NEGATIVE-AND-POSITIVE-REVIEWS-OF-HOTELS-IN-THE-KATHU-REGION-USING-TEXT-MINING/assets/124607057/fb1b0adb-dfd9-49e0-85af-5ee6bc47675b)


After removing the duplicates in the entire dataset, we would therefore do a sentiment analysis on the reviews on the entire dataset, the negative reviews, the positive reviews and the neutral reviews of the dataset.

![image](https://github.com/Orlawlardey/IDENTIFYING-NEGATIVE-AND-POSITIVE-REVIEWS-OF-HOTELS-IN-THE-KATHU-REGION-USING-TEXT-MINING/assets/124607057/be69ef69-df54-45e6-9da5-e6dbdd3a0594)

![image](https://github.com/Orlawlardey/IDENTIFYING-NEGATIVE-AND-POSITIVE-REVIEWS-OF-HOTELS-IN-THE-KATHU-REGION-USING-TEXT-MINING/assets/124607057/672a3334-66bd-4b16-9ae1-ebf37d83a237)


The description of the above shows that there are no missing values in the entire dataset as the count of all the columns are equal and the same.

![image](https://github.com/Orlawlardey/IDENTIFYING-NEGATIVE-AND-POSITIVE-REVIEWS-OF-HOTELS-IN-THE-KATHU-REGION-USING-TEXT-MINING/assets/124607057/75b6f8af-1b45-40d3-9e42-1b6c7f141a1e)


From the entire dataset, we can see that we have more responses between 0.50 and 1.00 and a count of over 500 reviews from the entire dataset.

![image](https://github.com/Orlawlardey/IDENTIFYING-NEGATIVE-AND-POSITIVE-REVIEWS-OF-HOTELS-IN-THE-KATHU-REGION-USING-TEXT-MINING/assets/124607057/10b4592d-e628-4b21-aaf3-ca47c5d7d123)


![image](https://github.com/Orlawlardey/IDENTIFYING-NEGATIVE-AND-POSITIVE-REVIEWS-OF-HOTELS-IN-THE-KATHU-REGION-USING-TEXT-MINING/assets/124607057/6bc3abc7-1c8b-4354-8cc5-99e3653419bf)


![image](https://github.com/Orlawlardey/IDENTIFYING-NEGATIVE-AND-POSITIVE-REVIEWS-OF-HOTELS-IN-THE-KATHU-REGION-USING-TEXT-MINING/assets/124607057/3c1e724c-d278-435e-8d9d-0b05bd9feb9e)


![image](https://github.com/Orlawlardey/IDENTIFYING-NEGATIVE-AND-POSITIVE-REVIEWS-OF-HOTELS-IN-THE-KATHU-REGION-USING-TEXT-MINING/assets/124607057/516b41ce-4541-4fb4-afc0-d10262075f5e)


![image](https://github.com/Orlawlardey/IDENTIFYING-NEGATIVE-AND-POSITIVE-REVIEWS-OF-HOTELS-IN-THE-KATHU-REGION-USING-TEXT-MINING/assets/124607057/0b51811f-afed-45d0-baee-d2625711106a)


From the reviews we can see that Thai Express – Turtle Village has the highest number of negative reviews while Thong Dee The Kathu Brasserie and The Cove Phuket have the lowest number of negative reviews.

![image](https://github.com/Orlawlardey/IDENTIFYING-NEGATIVE-AND-POSITIVE-REVIEWS-OF-HOTELS-IN-THE-KATHU-REGION-USING-TEXT-MINING/assets/124607057/71c40f65-7363-4fa9-b892-8c617a854045)


![image](https://github.com/Orlawlardey/IDENTIFYING-NEGATIVE-AND-POSITIVE-REVIEWS-OF-HOTELS-IN-THE-KATHU-REGION-USING-TEXT-MINING/assets/124607057/d4da6bcb-1b22-425e-85dd-38df20901880)


![image](https://github.com/Orlawlardey/IDENTIFYING-NEGATIVE-AND-POSITIVE-REVIEWS-OF-HOTELS-IN-THE-KATHU-REGION-USING-TEXT-MINING/assets/124607057/30d4ed83-f5b4-42e1-8982-99a7cb829746)


This was also represented in the bar chart shown below.

![image](https://github.com/Orlawlardey/IDENTIFYING-NEGATIVE-AND-POSITIVE-REVIEWS-OF-HOTELS-IN-THE-KATHU-REGION-USING-TEXT-MINING/assets/124607057/b7c4c70f-9da3-4fc1-a12a-a8a3cefef64b)


![image](https://github.com/Orlawlardey/IDENTIFYING-NEGATIVE-AND-POSITIVE-REVIEWS-OF-HOTELS-IN-THE-KATHU-REGION-USING-TEXT-MINING/assets/124607057/470b156d-c961-422b-a96f-49db08fa512d)


![image](https://github.com/Orlawlardey/IDENTIFYING-NEGATIVE-AND-POSITIVE-REVIEWS-OF-HOTELS-IN-THE-KATHU-REGION-USING-TEXT-MINING/assets/124607057/4f1a3d27-73ed-4bd7-852b-84f503634c65)


![image](https://github.com/Orlawlardey/IDENTIFYING-NEGATIVE-AND-POSITIVE-REVIEWS-OF-HOTELS-IN-THE-KATHU-REGION-USING-TEXT-MINING/assets/124607057/5fcb1d99-25af-456d-b9ba-07fc66c8d27d)


From the image derived using word-cloud we can see that the customers are displeased with the staff, food, service, price, chicken, waiter, waitress and a lot of other things at the Thai Express - Turtle Village restaurant.

![image](https://github.com/Orlawlardey/IDENTIFYING-NEGATIVE-AND-POSITIVE-REVIEWS-OF-HOTELS-IN-THE-KATHU-REGION-USING-TEXT-MINING/assets/124607057/cf9e0b99-2b35-4a14-9724-7ab5e054514f)


![image](https://github.com/Orlawlardey/IDENTIFYING-NEGATIVE-AND-POSITIVE-REVIEWS-OF-HOTELS-IN-THE-KATHU-REGION-USING-TEXT-MINING/assets/124607057/4c1dd9de-f4d6-4edd-8015-593c18ae04f5)


From the image derived using word-cloud we can see that customers who patronized the Thai Express - Turtle Village are pleased with portions of food served, the price of food, the staff, the resort, the dish, menu amongst other things.

![image](https://github.com/Orlawlardey/IDENTIFYING-NEGATIVE-AND-POSITIVE-REVIEWS-OF-HOTELS-IN-THE-KATHU-REGION-USING-TEXT-MINING/assets/124607057/3bfac3e7-6d0a-4719-b273-44331d0b4267)

The image above shows that frequency of how many times these positive words were mentioned every time a review was done for the Thai Express - Turtle Village hotel.

![image](https://github.com/Orlawlardey/IDENTIFYING-NEGATIVE-AND-POSITIVE-REVIEWS-OF-HOTELS-IN-THE-KATHU-REGION-USING-TEXT-MINING/assets/124607057/aa1c1419-74a7-412a-9cbe-d0826c058291)


The image above shows that frequency of how many times these negative words were mentioned every time a review was done for the Thai Express - Turtle Village hotel.

![image](https://github.com/Orlawlardey/IDENTIFYING-NEGATIVE-AND-POSITIVE-REVIEWS-OF-HOTELS-IN-THE-KATHU-REGION-USING-TEXT-MINING/assets/124607057/f4fd8937-b987-45e0-a951-cf06d8356838)


![image](https://github.com/Orlawlardey/IDENTIFYING-NEGATIVE-AND-POSITIVE-REVIEWS-OF-HOTELS-IN-THE-KATHU-REGION-USING-TEXT-MINING/assets/124607057/8daa9ebb-8a41-4de3-9710-da4d3b87bf14)


The frequency plot shows that food has the highest mentions while small has the lowest from the selected number of words made in the positive reviews.

![image](https://github.com/Orlawlardey/IDENTIFYING-NEGATIVE-AND-POSITIVE-REVIEWS-OF-HOTELS-IN-THE-KATHU-REGION-USING-TEXT-MINING/assets/124607057/da1db169-93d0-4b09-81e6-97432a4727a3)


![image](https://github.com/Orlawlardey/IDENTIFYING-NEGATIVE-AND-POSITIVE-REVIEWS-OF-HOTELS-IN-THE-KATHU-REGION-USING-TEXT-MINING/assets/124607057/f6d1b1f1-5c3f-4a7f-b4e8-37fe72ad104b)


The frequency plot shows that food has the highest mentions while small has the lowest from the selected number of words made in the negative reviews.


## RESULT ANALYSIS AND DISCUSSION
From the derived results, we can see that we have been able to get the total number of reviews for each hotel within the data set. We have also been able to make use of word cloud to get both words made both in the positive and negative reviews done by customers. We are not just able to see the words, but we can also see the number of times the words appeared when the reviews were done by customers.

## CONCLUSION
In conclusion, the sentiment analysis carried out on the data set has helped us with knowing the positive and negative feedback of customers who patronized the hotel with the highest negative and positive reviews. We can also see that some of the words like food, staff and price occurred both in the negative and positive reviews. This simply means that there were individuals who were satisfied about some services that made other individuals displeased. This could be because of the preference of different individuals and not necessarily because the hotels are not up to the expected standard.





