#  Project11-Analyzing Business
  - In companies, industries or business institutions, management keeps track, monitor and assess the success or failure of various business processes. Companies keeps track
of the overall health of the business through the result of measurements called metrics, e.g. revenue and average order values.
Examples of metrics that are followed by governments are GDP, inflation, and unemployment rate.
  - In this project, we'll focus on some business metrics, and explore some metrics in different business scenarios. What's important to understand is that metrics are observed 
across time. Metrics are calculated separately at specific points in time.

## Following two types of business metrics that we will work on:
   1. [**Net Promoter Score(NPS)**](https://github.com/Fiza-Iftikhar/Data_Science_Projects/blob/main/Project11-Analyzing%20Business/Project11.1-Net%20Promoter%20Score(NPS).ipynb)
   - **Net Promoter Score (NPS)** is an indicator to measure the customer's loyalty. **NPS** is a metric that assesses the willingness of the customers to recommend a company's products or services to other people. **NPS** metric used by many companies to track cuutomer's satisfaction. The main aim is to identify customers who are less satisfied with the customer experience or product and transform them into the company's promoters. The higher the **NPS**, the greater the customer has loyalty towards a company, brand or service etc. 

### How to calculate Net Promoter Score?
   - **NPS** calculation is based on a customer survey. In the survey one question is mostly framed as "On a scale of 0 to 10, how likely would you recommend our product/service to other people?"
   - Based on their responses, all respondents are broken down in three categories:
       - **Detractors:** Customers who rate your product in the range **(0-6)**, Are those customers who are unhappy and spread negative reviews about your product/service. 
       - **Passive:** who give response **(7-8)**. Satisfied but unenthusiastic customers who can be taken by competitors.
       - **Promoters:** who give response **(9-10)**. Loyal customers who can spread positive reviews of a company.
    
   - The range of Detractor, Passive and Promoter are generally defined by the company. Companies set their range according to the business need.     
   - **Net Promoter Score = Promoter(%) - Detractors(%)** 
   - The higher the **NPS** is associated with healthier and more successful busniesses.

### From this dataset, we calculate the Net Promoter Score(NPS) on monthly basis.

![Monthly NPS Comparison](https://user-images.githubusercontent.com/70064467/121932349-a4476f00-ccf9-11eb-92f6-ed9b56680e8d.png)

### CONCLUSION:
   - We can see that the NPS varies every month, from high to low. From the starting year, NPS is higher but we can see that at the end of the year NPS is at its lowest point. From that, we can say that customers are not satisfied with the business products or services. Or maybe the company was changed their policy, product/service rates or make new strategies that didn't work for them. The company should keenly observe the impact on the business due to the changes they made.  
 - It is not necessary that if NPS is low then it means your customer is not satisfied or your business is not working good. A company should compare their NPS with their industry. There is a possibility that the pandemic and the subsequent limitations have hit hard to the market but your business NPS is good as compared to other industries.
 - To understand your Net Promoter Score better, start by comparing it with the average scores within your industry, and against competitors. This is also referred to as the relative method, as opposed to the absolute method, which involves benchmarking your number to an agreed standard across industries for what a good NPS is. When comparing NPS scores, it’s important to understand what market you’re operating in. Some businesses have a more positive image than others.
  
   2. [**Churn Rate**](https://github.com/Fiza-Iftikhar/Data_Science_Projects/blob/main/Project11-Analyzing%20Business/Project11.2-Analyzing%20Business(Churn%20Rate).ipynb)
     - **Churn Rate:** Churn means the number of customers or subscribers who stop using your services during a given period.
     - **How to calculate Churn Rate:**
        - **Churn Rate  =  No. of customers left / (No. of customers left + No. of customers existing)**
     ### A hypothetical scenario is created to analyze the one of business metric i.e. Churn Rate
      - **Scenario:** It is a local gym "Muscle labs" subscription dataset. This gym was bought by some other person on 1 January 2013. Now it's early December 2014 and the gym owner wants to check the one-year performance of the gym.
   
### As a data analyst, we aim to find out the churn rate of the gym.
  
![Churn Rate of the gym](https://user-images.githubusercontent.com/70064467/122606277-85184c80-d02d-11eb-9f19-995513cd4e2f.png)

### CONCLUSION
   - From the analysis, we can see that the churn rate is very erratic at the beginning. In the starting months when we take over the business in January 2013, the churn rate started to become more stable.
   - But there at the end of 2013 and beginning of 2014, there was a relatively large spike in the churn rate (circled). Maybe the increased rate is due to the subscription expired because one year is completed. And when the subscription expired automatically person is churned.
   - A few actions that we could take to reactivate these customers are:
        - Make a new promotion specifically for the quitters.
        - Make a new promotion specifically for the customers who attended the gym until the end.
        - Throw in some perks in addition to the standard service for the customers who didn't quit.

      



