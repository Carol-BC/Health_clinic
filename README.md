# Health_clinic
First Power BI project

This project was created under specific parameters for the Data Analytics and Lean Six Sigma course, as part of my MBA in Process Management.

First, I needed to separate the datasheet, and I chose the **star schema** to do so. Once I had all the main areas subdivided I went on to create the **dCalendar table**: In here, I chose to utilize the DAX calculation and, instead of CALENDAR AUTO(), went with "CALENDAR(<start_date>, <end_date>)" to have my table reflect the exact dates from the data sheet. Once they were all generated, I continue to the subdivision by weeks, months and by year to have it all easily accessible, as one of the requirements was a subdivision to understand the peak service hours during the weekdays.

- Measures:
I created a few **measures** such as Year To Date Revenue (YTD), Client Returns to calculate churn and total quantities for clients and consults.

- Filters:
As requested by the customer, I added 2 data segmentation options: By year and trimester; and by doctor
I created two extra **filters** using buttons and the selection field, creating specific indicators. This will ensure the stakeholders may have full focus in each part of the report: Revenue and Customer Success.

- Charts:
As per specifications to showcase the total average for customer satisfaction, I decided to go with a **gouge chart** to demonstrate this information clearly, this will be shown through all the pages and views.

For Revenue, I chose to display only the earnings and averages regarding the treatments, using a **stacked area chart** for the revenue by year and so they can better visualize the business growth; On the other part, visualize the revenue by number of consults month by month utilizing a **stacked bar chart with line** to show the differences. At the same time, I used **cards** for the average price per consult and total revenue, they will fully change as needed according to the time and doctor selected.

For Customer Success, I chose to erase the revenue metrics and focus in the customer experience and satisfaction. I used the **stacked bar chart** once again to show the absolute numbers of client returns comparable to the total of consults by month to provide a better understanding of the business. I went on with a conscious decision to not use the Churn Rate explicitly in my metrics, as the datasheet provided and the information about the business indicated it was a small and locally run business, so I decided to "keep things simple".
I have also added a **tile grid heatmap** for another of the customer parameters, to show the peak service hours by days of the week and hours, that will automatically bring the most busy days to the top.
Also as requested, besides the gauge chart mentioned, I've separated the average satisfaction by procedure category using a **horizontal bar chart**, which will provide a better view of all procedures and their performance through the eyes of the pacient. The **cards** in this section will provide a better view of totals such as total consults, total wait time, total number of pacients and total number of clients that returned for a second time or more.

In the second page, as also instructed in the initial parameters, I have used a **infografic designer**, along with quick and simple photoshop skills to showcase the division of customers by gender. 
The classic **heatmap** was used to present the coverage area of the business, focusing on where its customers are located. I also chose a **table** for all the spendings and total quantity of procedures devided by customer - following LGPD guidelines to not include identifiable information. These last two will provide interesting insights on where the business should focus its marketing and which group of customers and neighborhoods are the less likely to return, along with other metrics important for the data-driven decision making.
