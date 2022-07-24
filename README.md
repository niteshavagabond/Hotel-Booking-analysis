# Hotel-Booking-analysis
EDA analysis
# Agenda
We get a Hotel Booking related data and our main objective is to go through every column to analyze this data from every prospectives, then we will raise some questions to ourselves and answer them with our own might 
# Dataset
Dataset contains 119390 bookings (no of rows) from 2015, 2016, and 2017 years and 32 features (no of columns) in it. Some of the key attributes consisting those variables which are taken under consideration for this project are listed below :

•	hotel : hotel name [Resort Hotel, City Hotel].

•	is_canceled : booking cancel status (0 is for false, 1 is for true).

•	lead_time : no of days from booking to actual arrival in the hotel.

•	arrival_date_year : year of booking [2015, 2016, 2017]

•	arrival_date_month : month of booking (Jan to dec)

•	arrival_date_week_number : number of week of year of booking

•	arrival_date_day_of_month : date of booking

•	stays_in_weekend_nights : no of weekends guest stays

•	stays_in_week_nights : no of week days guest stays

•	adults : no of adult guests

•	children : no of children with guest

•	babies : no of babies with guest

•	meal : type of meal 5 [BB: Bed and Breakfast, FB: Full Board(breakfast, lunch and dinner), HB: Half Board(Breakfast and dinner normally), SC: Self-catering and undefined]

•	country : abbreviation  of countries

•	market_segment : mode of booking through ['Direct', 'Corporate', 'Online TA', 'Offline TA/TO', 'Complementary', 'Groups', 'Undefined', 'Aviation'](TA:Travel Agent, TO: Travel operators)

•	distribution_channel : mode of booking through ['Direct', 'Corporate', 'TA/TO', 'Undefined', 'GDS']

•	is_repeated_guest : repeated guest or not

•	previous_bookings_not_canceled : no of not cancelled booking in past

•	reserved_room_type : reserved room type ['C', 'A', 'D', 'E', 'G', 'F', 'I', 'B', 'H', 'P', 'L', 'K'](A=AAA discount available; B=Complimentary breakfast; C=Complimentary coffee; D=Complimentary evening cocktail; E=European style hotel; F=Free local phone calls; G=Parking available; H= Complimentary use of health facilities   L=Complimentary local transportation shuttle; P=Indoor Pool; K=Kitchen facilities )

•	assigned_room_type : assigned room type ['C', 'A', 'D', 'E', 'G', 'F', 'I', 'B', 'H', 'P', 'L', 'K'](A=AAA discount available; B=Complimentary breakfast; C=Complimentary coffee; D=Complimentary evening cocktail; E=European style hotel; F=Free local phone calls; G=Parking available; H= Complimentary use of health facilities   L=Complimentary local transportation shuttle; P=Indoor Pool; K=Kitchen facilities )

•	booking_changes : no of booking changes

•	deposit_type : deposit type ['No Deposit', 'Refundable', 'Non Refund']

•	agent : agent id

•	company : company id

•	days_in_waiting_list : no of days on waiting list

•	customer_type : type of customer ['Transient', 'Contract', 'Transient-Party', 'Group'] Contract — when the booking has an allotment or other type of contract associated to it; Group — when the booking is associated to a group; Transient — when the booking is not part of a group or contract, and is not associated to other transient booking; Transient-party — when the booking is transient, but is associated to at least other transient booking

•	adr : average daily rate

•	required_car_parking_spaces : no of required car parking spaces

•	total_of _special_requests : total no of special requests

•	reservation_status : reservation status

•	reservation_status_date : reservation status date

Note : For the better interpretability we had converted name in colab notebook for own understanding.

Total number of rows in data: 119390

Total number of columns: 32

# Data cleaning process
1.Deal with columns name and give a proper name to columns.

2.Deal with duplicate rows if any

3.Drop columns, which are not required or having same values

4.Deal with null data or missing value

5.Deal with outliers in every columns

6.Change datatype of column if needed like children is an object dtype but should be an int type.

7.merge columns (e.g. [booking_day, booking_month, booking_year], [no_of_adults, no_of_children, no_of_babies] and [stays_in_weekend_nights, stays_in_week_nights])

# Exploratory Data Analysis

performing EDA on the basis of following catogorical columns -
## Analysis on the Basis of columns
1.Analysis on the basis of hotel

2.Analysis on the basis of booking and cancellation

3.Analysis on the basis of adr(average daily rate)

4.Analysis on the basis of distribution channel

5.Analysis on the basis of deposit type

6.Analysis on the basis of meal type

7.Analysis on the basis of customer type

8.Analysis on the basis of room type

9.Analysis on the basis of country

## Now we try to answer following questions -

Q1. Which hotel type is preferred the most?

Q2. which hotel has a higher booking cancellation?

Q3. How long do people prefer to stay in both hotels?

Q4. Which hotel require more car parking spaces?

Q5. Which hotel generates the most revenue?

Q6. Which are the busiest months for hotel? 

Q7. Which hotel has the highest lead time?

Q8. Was a hotel likely to receive a disproportionately high number of special requests?

Q9. Visualization of monthly bookings and monthly cancellations.

Q10. Relationship between lead time and cancellation.

Q11. Which type of customers book hotels the most?

Q12. Which type of customers make the special requests?

Q13. Which customer type has the highest cancellation of bookings?

Q14. When the best time of year to book a hotel room is?

Q15. Relationship between ADR and the total number of stays.

Q16. Which hotel generates the highest revenue i.e. Average Daily Rate Per Person?

Q17. Which distribution channel is mostly used?

Q18. Which distribution channel generates the most revenue for hotels?

Q19. analyzing which deposit type is preferred most?

Q20. Which type of meal is most and least preferred by the customers?

Q21. Analyzing customer retention on customer type.

Q22. Which room type is in most demand and which room type generates the highest average daily rate?

Q23.Which country has the greatest number of guests? 

# Conclusion :

•	Around 61% people booked City Hotel and 39% people booked Resort Hotel. on the basis of percentage, we can assume that city hotel is more popular than Resort Hotel.

•	People prefer to stay in City Hotels for shorter duration like for 4-5 days and they prefer Resort Hotel for longer durations like for 7-14 days.

•	City Hotel booking cancellation is higher than Resort hotel.

•	Every year Resort Hotels require more car parking space than City Hotel.

•	We can see that City Hotel generates the most revenue

•	Busiest months for hotels are July and August

•	Resort Hotel has the highest average lead time.

•	In City hotels bookings and cancellations are high during the months of May , September and October, In case of resort hotels there is not much variations in bookings and cancellations. Bookings and cancellations are highest during the month of October

•	Higher lead time leads to high booking cancellations and lower lead time leads to low booking cancellations.

•	Transient(when the booking is not part of a group or contract, and is not associated to other transient booking) customers make most bookings.

•	Most no of special requests comes from Transient customers.

•	booking cancellation is greater for Transient customers.

•	Minimum adr per person is lowest in January for Resort Hotel and January, February and November for City hotel, these months are best deal for hotel booking.

•	There is a negative correlation between the Total stay and the ADR, which means as the length of total stay increases the adr decreases.

•	It is clearly seen that Price of Resort hotel are much higher and Prices of city Hotel are less fluctuating . Hence , we can conclude that Resort type hotel generates much more revenue than city hotel in busiest months i.e. July and August.

•	79.11% bookings are made by TA/TO(Travel agent/Travel operators), so we can say that TA/TO distribution channel is mostly use by groups.

•	We can say that GDS(Global Distribution System) generates more revenue for City Hotel and Undefined for Resort Hotel.

•	Most preferred deposit type is No Deposit.

•	Most preferred meal type is 'BB' i.e. Bed and Breakfast and the least preferred one is 'FB' i.e. FB: Full Board(breakfast, lunch and dinner).


•	Transient Customer is more loyal in both hotels but City Hotel's Transient Customers are more loyal compared to Resort Hotel's Transient Customers.

•	Most demanding room is** A (Room with discount available)** type but according to above bar chart H (Complimentary use of health facilities) room type is generates greatest ADR.

•	Most guests come from Southern Europe and Portugal has the greatest number of guests.
