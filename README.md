# Hotel-Booking-EDA
The hotel booking dataset contains city hotel and resort hotel booking details over a period of three years, which includes lead time, cancellation details, year month, week number, date of month, stays in weekend nights, stays in week nights, adults, children, babies, meal, country, market segment distribution_channel, repeated guest, previous cancellations, previous bookings which are not canceled, reserved_room_type, assigned room type, booking changes, deposit type, agent, company, days in waiting list, customer type, adr,
required car parking spaces, total of special requests, reservation status, reservation status date. Considering the given details to be variables, the correlation between few variables can be found to analyse the bookings and cancellations. From the provided dataset, univariate and bivariate analyses may be performed to determine which country has contributed to more bookings, the ideal days to stay in both hotels, which year they had the most bookings and many other factors which effect bookings.
# Table of contents
* Data cleaning and manipulation
* Data Visualizations
* Conclusion
* Tools
# Data cleaning and manipulation
The dataset has 119390 rows and 32 columns. children, company and agent  columns had null values which are replaced with 0, median and 0 respectively. A list of required columns is made and a new dataframe is created from them. Two new columns were added to the new dataframe i.e., total_stays, which tells about the total number of weeknights and weekend nights were booked by the customer and the second column is total_members, which tells about the total number of people who stayed. Additionally since there are only two types of hotels in hotel column, city hotel and resort hotels rows are seggregated for better understanding. Therefore, the new dataset consists of 119390 rows and 30 columns.
# Data Visualizations
* Which hotel had more bookings
* Visualising lead time through histogram
* Which year had more bookings
* Bookings through different market segments
* Correlation between lead time and cancellations
* Visualising customer type in hotels
* Contribution of bookings through distribution channels
* Which meal was preferred more
* Which hotel had more repeated guests
* Which country has contributed the most bookings to the city hotel and resort hotel
* Which hotel had maximum booking changes
* Which hotel needed more car parking space
* Which agent has contributed the most bookings to the city and resort hotel
* Which month had more number of stays in city hotel
* Which month had more number of stays in resort hotel
* Which room type had maximum adr
* Ideal days people would like to stay in a hotel
* which month gave more revenue
* Which deposit type customers are most likely to cancel bookings
* What is the relation between adr and total members in both hotels
* What is the ideal number of days to stay in order to get best daily rate in both hotels
* Which market segment required disproportionately special requests
# Conclusion
After performing few analysis for the given dataset, it can be concluded that
*   From the analysis, it is observed that the ideal days to stay in city hotel is in between 10 to 15 days and around a week in resort hotel.
*   Almost all the market segment bookings had dispropotionate guests.
*   Most of the bookings are for city hotel, more optimistic price plans and marketing strategies to be implemented to maintain the bookings
*   There are high cancellations due to no deposit type, which has to be replaced with proper cancellation policies.
*   The room types which gave higher revenue has to be installed more.
*   Transient customers are high in number and they contribute to most of the bookings.
*   The customers are booking rooms through online TA/TO.
*   As the total members increases, adr increases. Also, for a single person adr is below 100 in resort hotel and slightly above 100 in city hotel.
*   7 days would be ideal to book in city hotel and resort hotel to get best daily rates.

Also, strategies to reduce cancellations could be by having strict cancellation policies, giving discounts for direct booking, and many optimized price plans so that customers are more attracted to this hotel than other hotels.
# Tool
Google colab 





























































