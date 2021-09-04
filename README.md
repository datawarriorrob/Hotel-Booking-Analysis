# Hotel-Booking-Analysis
Have you ever wondered when the best time of year to book a hotel room is? Or the optimal length of stay in order to get the best daily rate? What if you wanted to predict whether or not a hotel was likely to receive a disproportionately high number of special requests? This hotel booking dataset can help you explore those questions!
This data set contains booking information for a city hotel and a resort hotel, and includes information such as when the booking was made, length of stay, the number of adults, children, and/or babies, and the number of available parking spaces, among other things.

# Dataset Specs
* Count of rows= 119390
* Count of columns= 32

# Programming Language
* Python 

# IDE
* Google Colaboratory

# Nomenclature
Naming our dataframe is very crutial for any data analysis project as you have to call the dataframe time and again for every set of operation which are to be performed for the in-depth analysis.

In this case, our copy of the dataframe will be called 'df' , simple and easy to recall.

# Data Variables Glossary

* **hotel**
Two hotels are given:
Resort Hotel
City Hotel
* **is_canceled**
1: Canceled
0: Not canceled
* **cancelation**
0 as not_canceled
1 as canceled
* **df_not_canceled_guests**
dataframe with just not_canceled bookings
* **lead_time**
gap between booking and arrival
* **arrival_date_year**
arrival year
* **arrival_date_month**
arrival month
* **arrival_date_week_number**
arrival week
* **arrival_date_day_of_month**
arrival date
* **stays_in_weekend_nights**
count of nights the guests booked the hotel during Sat-Sun
* **stays_in_week_nights**
count of nights the guests booked the hotel during Mon-Fri
* **total_stay_nights**
duration of stay including weekend nights and week nights stay
* **adults**
count of adults
* **children**
count of children
* **babies**
count of babies
* **meal**
meal type (no meal package; BB; HB; FB)
* **country**
country of guests
* **df_country_guests_top10**
top10 countries with most visitors
* **market_segment**
TA: Travel agents
TO: Tour operators
* **distribution_channel**
* **is_repeated_guest**
1: Yes
0: No
* **previous_cancellations**
count of previous bookings that were cancelled by the customer before final booking
* **previous_bookings_not_canceled**
count of no canceled bookings
* **reserved_room_type**
booked room category
* **assigned_room_type**
assigned room category
* **booking_changes**
count of changes made by the customer before final booking
* **deposit_type**
type of deposit made by the customer
* **agent**
travel agent id
* **company**
booking company id
* **days_in_waiting_list**
count of days the booking was in the waiting list before it was confirmed
* **customer_type**
Transient
Contract
Group
Transient-party
* **adr**
average daily rate for the booking
* **price**
total price spent by a guest entity
* **required_car_parking_spaces**
count of car parking spaces alloted by the customer
* **total_of_special_requests**
count of special requests made by the customer
* **reservation_status**
status of reservation
* **reservation_status_date**
date corresponding to status of reservation

# INTRODUCTION & OBJECTIVE OF THE CHASE
Vacations, business stay or a casual trip to a new city, hotel bookings are mandatory and each one of us desires to optimize our stay. Optimization, for someone could be booking a hotel where he/she pays less for a good deal, or maybe just getting the only luxurious suite, in a 7-star hotel during a non-peak period.

We are given a Hotel Booking dataset, which stores tabular information about the guests' booking pattern, stay duration, choice of meal and much more for a consecutive year range and we’ll be performing a profound analysis on the dataset, to dig out details and predict a few trends pertaining to the data. Firstly, I don't want to pay any surged random price for my booking rather, I will be happy to pay an optimized value for my stay. Secondly, I want my vacation to be safe, as I am accompanying my loved ones, so I would prefer a hotel with less crowd and well equipped with health and safety measures.

Our analysis, would be capable of helping prospective guests in choosing the right hotel, right stay duration and much more for their stay and moreover, would also be introspecting for hotel management in bringing out changes (if, any) in their services for the guests.

Let's begin the chase!

# SUMMARY OF CONCLUSIONS
* City Hotel is the most booked hotel with 62 percent not_canceled bookings.
* Resort Hotel is preferred over City Hotel by Adults and childrens.
* Resort Hotel has been preferred over City Hotel by larger group of guests or families.
* City Hotel canceled bookings is almost thrice the canceled booking of Resort Hotel. This might be due to no cancelation charges or no-deposit booking allowed by them.
Year 2016 observed most number of Bookings for the Hotels cumulatively.
* Month of August saw most number of arrivals in either of the hotels. So, if you want to be accompanied by a large number of co-guests then choose August for your visit.
* Also, guests are observed to be spending more week nights than weekend nights.
* City Resort could be tagged as a "Duo/Couple-Friendly Hotel" & "Children-Friendly Hotel". Whereas, Resort Hotel could be tagged as "Babies-Friendly Hotel"
* Arrival of guests is pretty high almost 75 percent and above from the countries with code: DEU, ESP, FRA, GBR and PRT
* There are very few repeated guests in each hotels.
* For City Hotel, most of their guests stayed back for 2 or 3 days.For Resort Hotel, most of their guests stayed back for 1 or 7 days.
* The City Hotel guests made a total of 64 percentage of total special requests while The Resort Hotel guests made only 36 percent of the total.
* City Hotel allows more No Deposit Bookings in count than Resort Hotel. But, the Percentage of No Deposit Bookings over total bookings is higher for Resort Hotel.
* The price variance and standard deviation for City Hotel is lower than Resort Hotel. The prices of Resort Hotel are more than City Hotel in the months of July, August,September and June. For rest of the months, Prices of City Hotel are consistently higher than Resort Hotel.
