# Hotel-Booking-Analysis-EDA-Capstone-Project-
We are provided with a hotel bookings dataset. This dataset contains booking information for a city hotel and a resort hotel. 

1.	Total number of rows in data: 119390
2.	Total number of columns: 32

1.Problem Statement:
Out main objective is perform EDA on the given dataset and draw useful conclusions about general trends in hotel bookings and how factors governing hotel bookings interact with each other.

2.Data Cleaning & Feature Engineering:
    
    - There were columns like column company,agent,country and children contains  
        missing values.
      
     - We can drop 'company' column as it contains too many missing values.
        
     - In Children column we have 4 missing values, so we are filling those missing 
       values with average value of children column and we are type-casting float 
       values to integer value.
      
    - In agent column, we had 16340 missing values, so we replaced those values 
       with 'unknown'. Also we typecast the ID of Agent to integer values.
     
    -And last we Removed outlier data from dataset where adr is greater than 1000.

3.Overview of the Hotel Type:

1.	What is the percentage of booking done in different hotels?

2.	How many total bookings done in different Years?

3.	How many total bookings done in different months?

4.	Total Number of Booking Cancelled in different months?

5.	Total Number of Non-Cancelled Bookings in different months?

4.Analysis on Hotels & Bookings: 

1.	How many days customers prefer to stay in week night?

2.	How many days customers prefer to stay in weekend night?

3.	what is the most preferred meal type by customers?

4.	How many customers are making special Request?

5.	Which one is most preferred room type?

5.Overview of Market Segments:

1.	What are the top 20 countries from where we are getting more customers?

2.	What Deposit Type most customer choose?

3.	From which market segment we are getting more number of Booking Cancellation?

4.	From which market segment we are getting more customers who are not cancelling their booking?

5.	Which Agent(id) is booking the most number of hotels?

6.Conclusions:

•	Majority of the hotels booked are city hotel. Definitely need to spend the most targeting fund on those hotel.

•	We should also target months between May to Aug. Those are peak months due to the summer period.

•	We also realize that the high rate of cancellations can be due high no deposit policies.

•	 Cancellations are high when done through agents compared to direct bookings. Hotels need to do marketing and give special incentives for direct bookings as these  may establish personal one to one relationships promoting customer loyalty.

•	Given that we do not have repeated guests, we should target our advertisement on guests to increase returning guests.


