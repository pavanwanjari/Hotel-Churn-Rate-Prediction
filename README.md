# Hotel-Churn-Rate-Prediction
To predict whether the customer is going to cancel booking or not.
**Dataset details:-** This dataset contains booking information for a ciy hotel and a resort hotel and includes information such as when the booking was made, length of stay, the number of adults, children and/ or babies and the number of available parking spaces.
### Dataset Description

| Column Names	| Description |
| ------------- | ----------- |
| hotel | Two Hotel Type Available : Resort Hotel , City Hotel |
| is_canceled	| Values: Booking Cancelled -0 ,Booking Not Canceled - 1 |
| lead_time	| The time taken between when a customer makes a reservation and their actual arrival is called the Lead Time.Lead Time is in hrs. We can convert it to days. |
| arrival_date_year |	Year of arrival date. Available Years - 2015,2016,2017 |
| arrival_date_month	| Month of arrival date |
| arrival_date_week_number	| "Week number of year for arrival date Values : 1 -53" |
| arrival_date_day_of_month	| Day of arrival date .Values : 1-31 |
| stays_in_weekend_nights	 | Number of weekend nights (Saturday or Sunday) the guest stayed or booked to stay at the hotel Values : 0,1,2,3,4,5,6,7,8,9,10,12,13,14,16,18,19 . Values such as 11 ,15,17 are not present |
| stays_in_week_nights	| Number of week nights (Monday to Friday) the guest stayed or booked to stay at the hotel. |
| adults	| Distinct Values : 0,1,2,3,4,5,6,10,20,26,27,40,50,55 |
| children	| Values : 0,1,2,3,10,NA |
| babies	| Values : 0,1,2,9,10 |
| meal	| Values :BB means Bead and Breakfast, which is the most common meal basis encountered in hotels. Breakfast is included in the room rate. There are two main types of breakfast: buffet and continental.FB is short of Full Board and means that all three meals are included – breakfast, lunch, and dinner.HB (Half Board) is when both breakfast and evening meal are included in your room rate.SC means Self Catering. Undefined : No meal package |
| country	| Country of origin. Categories are represented in the ISO 3155–3:2013 format |
| market_segment	| Market segment designation. In categories, the term “TA” means “Travel Agents” and “TO” means “Tour Operators” |
| distribution_channel	| Booking distribution channel. The term “TA” means “Travel Agents” and “TO” means “Tour Operators” |
| is_repeated_guest	| If the booking name was from a repeated guest (1) or not (0) |
| previous_cancellations	| Number of previous bookings that were cancelled by the customer prior to the current booking |
| previous_bookings_not_canceled	| Number of previous bookings not cancelled by the customer prior to the current booking |
| reserved_room_type	| Code of room type reserved. Code is presented instead of designation for anonymity reasons |
| assigned_room_type	| Code for the type of room assigned to the booking. Sometimes the assigned room type differs from the reserved room type due to hotel operation reasons (e.g. overbooking) or by customer request. Code is presented instead of designation for anonymity reasons. |
| booking_changes	| Number of changes/amendments made to the booking from the moment the booking was entered on the PMS until the moment of check-in or cancellation |
| deposit_type	| "Indication on if the customer made a deposit to guarantee the booking. This variable can assume three categories: * **No Deposit** – no deposit was made * **Non Refund** - a deposit was made in the value of the total stay cost * **Refundable** – a deposit was made with a value under the total cost of stay." |
| agent	| ID of the travel agency that made the booking |
| company	| ID of the company/entity that made the booking or responsible for paying the booking. ID is presented instead of designation for anonymity reasons |
| days_in_waiting_list	| Number of days the booking was in the waiting list before it was confirmed to the customer |
| customer_type	| "Type of booking, assuming one of four categories: * **Contract** - when the booking has an allotment or other type of contract associated to it * **Group** – when the booking is associated to a group * **Transient** – when the booking is not part of a group or contract, and is not associated to other transient booking * **Transient-party** – when the booking is transient, but is associated to at least other transient booking" |
| adr	| Average Daily Rate as defined by dividing the sum of all lodging transactions by the total number of staying nights |
| required_car_parking_spaces	| Number of car parking spaces required by the customer |
| total_of_special_requests	| Number of special requests made by the customer (e.g. twin bed or high floor) |
| reservation_status	| "Reservation last status, assuming one of three categories: * **Canceled** – booking was canceled by the customer * **Check-Out** – customer has checked in but already departed * **No-Show** – customer did not check-in and did inform the hotel of the reason why" |
| reservation_status_date	| Date at which the last status was set. This variable can be used in conjunction with the ReservationStatus to understand when was the booking canceled or when did the customer checked-out of the hotel |

![image](https://user-images.githubusercontent.com/92113558/168455806-023c1700-1c59-4fef-b7a3-051895993f29.png)
