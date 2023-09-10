# Riskiyatul-Hasanah_Investigate-Business-Hotel-using-Data-Visualization-
Table of Content
Business Understanding
Problem Statement
Goals
Objectives
Data Preparation
Data Description
Libraries & Dataset
Import Libraries
Import Dataset
Data Understanding
Exploring Dataset
Basic Dataset Information
Checking Duplicate Rows
Checking Missing Value
Division by Type of Data
Statistical Summary
Data Cleansing/Prepocessing
Handling Missing Value
Handling Duplicate Rows
Data Type Information
Handling Invalid Value
Drop Unnecessary Data
Exploring Business Insight
Business Understanding
Problem Statement
Business performance is very important for a company. It can help to increase customer satisfaction and loyalty for our services provided. In this case, we will focus on the business in the hospitality sector. Our focus is to find out how our customers behave in making hotel bookings, and the relationship to the cancellation rate of hotel bookings. The results of the insights we find, will be presented in the form of visualization and data story telling to make it easier to understand for our costumers

Goals
The company want to improve business perfomance based on customer behavior in ordering hotel ticket bookings and looking for the factors that influence the cancellation rate of hotel ticket bookings

Objectives
Making business insights through hotel business performance by using visualization and data storytelling

Data Preparation
Data Description
This dataset contains 119390 rows and 29 features, below is description of dataset :

hotel - Hotel (H1 = Resort Hotel or H2 = City Hotel)
City Hotel - Type of hotel location in urban centers and it's tipically found in large cities
Resort Hotel - Type of hotel usually located in places frequented for relaxation or recreation, it's usually offering scenic and natural views
is_canceled - Value indicating if the booking was canceled (1) or not (0)
lead_time - Number of days that elapsed between the entering date of the booking into the PMS and the arrival date
arrival_date_year - Year of arrival date
arrival_date_month - Month of arrival date
arrival_date_week_number - Week number of year for arrival date
arrival_date_day_of_month - Day of arrival date
stay_in_weekend_nights - Number of weekend nights (Saturday or Sunday) the guest stayed or booked to stay at the hotel
stay_in_weekdays_nights - Number of week nights (Monday to Friday) the guest stayed or booked to stay at the hotel
adults - Number of adults
children- Number of children
babies - Number of babies
meal - Type of meal booked. Categories are presented in standard hospitality meal packages:
Undefined/SC – no meal
BB - Bed and breakfast
HB - Half board (breakfast and one other meal, usually dinner)
FB - Full board (breakfast, lunch, and dinner)
city - city name
market_segment - Market segment designation. In categories, the term “TA” means “Travel Agents” and “TO” means “Tour Operators”
distribution_channel - Booking distribution channel. The term “TA” means “Travel Agents” and “TO” means “Tour Operators”
is_repeated_guest - Value indicating if the booking name was from a repeated guest (1) or not (0)
previous_cancellation - Number of previous bookings that were cancelled by the customer prior to the current booking
previous_bookings_not_canceled - Number of previous bookings not cancelled by the customer prior to the current booking
booking_changes - Number of changes/amendments made to the booking from the moment the booking was entered on the PMS untill
                the moment of check-in or cancellation
deposit_type - Indication on if the customer made a deposit to guarantee the booking. This variable can assume three categories:
No Deposit - No deposit was made
Non Refund - A deposit was made in the value of the total stay cost
Refundable - A deposit was made with a value under the total cost of stay Note : The deposit is security deposit that will be paid back to you as a customer. However, on condition that none of the facilities then the deposit money will be returned 100% customer after no damage to this hotel's facilities
agent - ID of the travel agency that made the booking
company - ID of the company/entity that made the booking or responsible for paying the booking. ID is presented instead of designation for
days_in_waiting_list - Number of days the booking was in the waiting list before it was confirmed to the customer
customer_type - Type of booking, assuming one of four categories:
Contract - When the booking has an allotment or other type of contract associated to it
Group - When the booking is associated to a group
Transient - When the booking is not part of a group or contract, and is not associated to other transient booking
adr - Average Daily Rate as defined by dividing the sum of all lodging transactions by the total number of staying nights
required_car_special_request - Number of car parking spaces required by the customer
total_of_special_request - Number of special requests made by the customer (e.g. twin bed or high floor)
reservation_status - Reservation last status, assuming one of three categories:
Canceled – Booking was canceled by the customer
Check-Out - Customer did not checked in but already departed
No-Show - Customer did not check-in and di inform the hotel of the reason why
Resouces : https://www.kaggle.com/datasets/jessemostipak/hotel-booking-demand
