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

