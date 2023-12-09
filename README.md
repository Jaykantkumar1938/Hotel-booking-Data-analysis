# Hotel-Booking-Analysis

The project contains the real world data record of hotel bookings of a city and a resort hotel containing details like bookings, cancellations, guest details etc. from 2015 to 2017. In this project we are going to analyze Hotel Booking Data in order to find out valuable insights and give suggestions to increase revenue of hotels.

##  Programming Language : Python

##  Libraries used : Pandas, Numpy, Matplotlib, Seaborn

##  NoteBook : Jupyter Notebook

##  Dataset Source : Kaggle.

# Objective
We are provided with a hotel bookings dataset.

The main purpose of this study is to perform EDA on the given dataset and draw useful conclusions about the trends in hotel bookings and how factors that control hotel bookings influence each other.

Dataset
We are given a hotel bookings dataset. This dataset contains booking information for a city hotel and a resort hotel. It contains the following features.

- hotel: Name of hotel ( City or Resort)
- is_canceled: Whether the booking is canceled or not (0 for no canceled and 1 for canceled)
- arrival_date_year: Year of arrival
- arrival_date_month: month of arrival
- arrival_date_week_number: week number of arrival date.
- arrival_date_day_of_month: Day of month of arrival date
- stays_in_weekend_nights: No. of weekend nights spent in a hotel
- stays_in_week_nights: No. of weeknights spent in a hotel
- adults: No. of adults in single booking record.
- children: No. of children in single booking record.
- babies: No. of babies in single booking record. 
- meal: Type of meal chosen 
- country: Country of origin of customers (as mentioned by them)
- market_segment: What segment via booking was made and for what purpose.
- distribution_channel: Via which medium booking was made.
- is_repeated_guest: Whether the customer has made any booking before(0 for No and 1 for Yes)
- previous_cancellations: No. of previous canceled bookings.
- previous_bookings_not_canceled: No. of previous non-canceled bookings.
- reserved_room_type: Room type reserved by a customer.
- assigned_room_type: Room type assigned to the customer.
- booking_changes: No. of booking changes done by customers
- deposit_type: Type of deposit at the time of making a booking (No deposit/ Refundable/ No refund)
- agent: Id of agent for booking
- company: Id of the company making a booking
- days_in_waiting_list: No. of days on waiting list.
- customer_type: Type of customer(Transient, Group, etc.)
- adr: Average Daily rate.
- required_car_parking_spaces: No. of car parking asked in booking
- total_of_special_requests: total no. of special request.
- reservation_status: Whether a customer has checked out or canceled,or not showed 
- reservation_status_date: Date of making reservation status.
Total number of rows in data: 119390
Total number of columns: 32

# Data Cleaning 

(1) Handling null values
column containing high null value was deleted.

(2) Removing Duplicate rows
All duplicate rows were dropped.

(3) Converting columns to appropriate data types
Changed data type of children, company, agent to int type.

(4) Removing outliers
One outlier was found in the average_daily_rate column. Dropping them.

# Exploratory Data Analysis

Performed EDA and tried answering the following questions:

 Q1) Which hotel has more no of bookings and What is the  percentage of bookings in each hotel ?
 
 Q2) Hotel Wise Bookings based on Month and year also What is the trend of bookings within a month ?
 
 Q3) Country Wise - Number of Bookings ?
 
 Q4) Which agent is making maximum Bookings ?
 
 Q5) Cancellation rates in both the hotels also arival year?
 
 Q6) What is the Average daily rate month wise also which are the most busy months?
 
 Q7) What is the Average daily rate with respect to per person?
 
 Q8) Which channel is mostly used for the booking of hotels? 

Mainly performed using Matplotlib and Seaborn library and the following graph and plots had been used:

Bar Plot.

Pie Chart.

Line Plot.

Box Plot

# Analysis:

Performed analysis and made following conclusions:

 1.) 61% bookings are for City hotel and 39% bookings are for Resort hotel, therefore City Hotel is busier than Resort hotel. 
 
 2.) July- August are the most busier and profitable months for both of hotels.
 
 3.) Most of the guests came from european countries, with highest number of guests from Portugal.
 
 4.) Guests use different channels for making bookings out of which most preferred way is TA/TO. 
 
 5.) Overall average daily rate of City hotel is slightly higher than Resort hotel and no. of bookings of City hotel is also higher than Resort hotel. Hence, City hotel is makes more revenue.
 
 6.) Cancelation rate is higher in city hotel. With lead time more than 100 there is more possibility of cancellation.
 
 7.) Arrivals in hotels increases at weekends and also the average daily rate tends to go up as month ends. 
 
 8.) Moslty bookings are done by couples(bookings have two adults.)
 
# Conclusion

(1) 61% bookings are for City hotel and 39% bookings are for Resort hotel, therefore City Hotel is busier than Resort hotel. Also the overall average daily rate of City hotel is slightly higher than Resort hotel.

(2) Most of the guests came from european countries, with most of guests coming from Portugal.

(3) We should also target months between May to Aug. Those are peak month for Hotel revenue generation.

(4) Within a month, average daily rate gradually increases as month ends, with small sudden rise on weekends.

(5) November, December, January and February are the months which has least bookings so in this periods you can get rooms with less average daily rate.
And many more conclusion

# Challenges

(1) Lot of null values were present in the dataset.

(2) Data type of some Data was in wrong format.

(3) Which visualization techniques to use was a challenge?
