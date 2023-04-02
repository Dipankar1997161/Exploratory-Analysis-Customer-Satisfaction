# Exploratory-Analysis-Customer-Satisfaction
In-depth EDA and customer sentiment analysis


## Introduction

Customers interact with your business or service every day, and the quality of the interaction experience can get your brand ahead. Brands that want to stay in the game and advance in the market know that they need to continuously listen to the customers to provide services in line with customer expectations.

Using customer data to improve customer experience can help retain customers, which is more straightforward than acquiring new customers. A happy customer will not only return to your service but is likely to promote your company through word of mouth.

<p align = 'center'>
    <img src = "https://user-images.githubusercontent.com/85514219/229327948-4a3bdc90-7cd7-4f25-a958-8c26e0cf83f7.png", high = "400px", width = "500px" >
</p>

### Importance of Data Science for Customer Experience

### 1. Facilitates Hyper-Personalization 

A recent report shows that 80% of customers will likely purchase from a brand that provides them with a personalized experience.
One of the most buzzworthy benefits of data science for businesses is the ability to understand their audience on a very granular level. With this knowledge, businesses can create the best possible customer experiences.

### 2. Improves Products and Services

Data science is one of the most effective tools businesses and companies use to understand the market position of their products and services.
This understanding is crucial to remain relevant to both customers and the competition. 

### 3. Provides a Better Customer Journey

The first step companies take is implementing the right sensor for data collection, meaning capturing the associated metadata and interactions from every individual customer.
With data science, businesses can easily collect the right data, find models of positive customer journeys, and many more. Furthermore, companies can develop a customer experience that reflects their goals by understanding what is most valuable to their prospects.

### 4. Collects and Uses Customer Data Effectively 

Businesses use multiple customer service platforms through contact center solutions. This allows customers to communicate through various media, including emails, social media, phone calls, etc. This creates several data streams that should be integrated. 

### 5. Improves Agent Productivity 

Productive customer service representatives create happy and satisfied customers. A satisfied customer is a buying customer. Data science and reports can be used internally to evaluate the performance of agents. As such, you can see which agents work best and in which areas.

## Experiment:
- Performed depth EDA with the data
- Trained on 6 models using pipeline and provided a comparison
- Used GridSearch to improve the low accuracy model

## Results:
### EDA

![satis1](https://user-images.githubusercontent.com/85514219/229328362-67cda89e-a657-4652-aba9-916930fc765c.png)

#### Numerical Attributes
![satis2](https://user-images.githubusercontent.com/85514219/229328361-5d2f5b07-b7c6-44ac-bef7-b6b67e1a31a0.png)


#### Categorical Attributes
![satis3](https://user-images.githubusercontent.com/85514219/229328359-be75f9d0-3350-489b-a847-a16aee9372dd.png)


![satis4](https://user-images.githubusercontent.com/85514219/229328358-d643185a-86cf-434b-a6ff-bf0631656c75.png)


### Model Results

![models](https://user-images.githubusercontent.com/85514219/229328425-be10a544-3084-4d61-a21c-11fd1f5b80ca.png)

![models acc](https://user-images.githubusercontent.com/85514219/229328424-a3964e33-6bfd-4d14-af65-b178f701825e.png)


### GridSearch on KNN

![KNN after grid](https://user-images.githubusercontent.com/85514219/229328448-1b572b22-3df6-47cc-9e96-0ded035947f1.png)

## Final Verdict:

Customer Satisfaction is a core part of Business growth. Therefore, careful Analysis and accurate model development needs to be taken care. 
In this project, ** RANDOM FOREST ** algorithm performed the best and using ** GridSearch ** on K-Nearest-neighbour model, The model showed better improvement. 
