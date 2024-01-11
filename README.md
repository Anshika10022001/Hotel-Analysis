
![beautiful-resort-wallpaper-preview](https://github.com/Anshika10022001/Hotel-Analysis/assets/128470731/02ab787f-47d2-4c06-a71b-c92770997e73)

# Hotel Booking Analysis
## Project Description

Aimed to analyze the Hotel Booking data and created Power BI Dashboard showing useful insights.

## Analysis Framework
 
- Data Gathering: Collected the releveant data from [Website](https://absentdata.com/data-analysis/where-to-find-data/) into the MS Excel
- Data preparation: The project involved using SQL aggregations to prepare and clean data for analysis. This included aggregating data from multiple sources and tables, filtering out irrelevant information, and performing calculations to derive meaningful insights.
- Generating important insights to present to the stakeholders and answering some important questions from the analysis:
#### 1. Is the hotel revenue growing year by year?
#### 2. Should the parking lot size be increased?
#### 3. What trends can we see in the data?
  
### The whole code can be seen step by step in the pdf file created in this repository [SQL Analysis](https://github.com/Anshika10022001/Hotel-Analysis/blob/main/hotel_project.pdf)

## The Dataset

![h1](https://github.com/Anshika10022001/Hotel-Analysis/assets/128470731/7d1f3b18-901b-4186-9323-5d4c3fc704cc)

![h2](https://github.com/Anshika10022001/Hotel-Analysis/assets/128470731/8604c27b-cec8-4ee7-80ac-e5fc4d4ea8a0)

Here's an explanation of each column:

- hotel: Name of the hotel.
- is_canceled: Binary variable indicating whether the booking was canceled (1) or not (0).
- lead_time: Number of days between booking date and arrival date.
- arrival_date_year: Year of arrival.
- arrival_date_month: Month of arrival.
- arrival_date_week_number: Week number of arrival date.
- arrival_date_day_of_month: Day of the month of arrival.
- stays_in_weekend_nights: Number of weekend nights (Saturday or Sunday) the guest stayed.
- stays_in_week_nights: Number of weekday nights the guest stayed.
- adults: Number of adults.
- children: Number of children.
- babies: Number of babies.
- meal: Type of meal booked.
- costofmeal: Cost of the meal.
- country: Country of origin of the guest.
- market_segment: Market segment designation (e.g., Online Travel Agents, Direct, Corporate).
- discount: Discount offered on the booking.
- distribution_channel: Booking distribution channel (e.g., Direct, Travel Agents).
- is_repeated_guest: Binary variable indicating whether the guest is a repeated guest (1) or not (0).
- previous_cancellations: Binary variable indicating whether the guest had previous cancellations (1) or not (0).
- previous_bookings_not_canceled: Binary variable indicating whether the guest had previous bookings that were not canceled (1) or not (0).
- reserved_room_type: Type of room reserved.
- assigned_room_type: Type of room assigned at check-in.
- booking_changes: Binary variable indicating whether changes were made to the booking (1) or not (0).
- deposit_type: Type of deposit made for the reservation.
- agent: ID of the travel agency making the booking.
- company: ID of the company making the booking.
- days_in_waiting_list: Number of days the booking was in the waiting list before it was confirmed.
- customer_type: Type of booking (e.g., Transient, Contract, Group).
- adr: Daily rate for the booking.
- required_car_parking_spaces: Number of car parking spaces required by the guest.
- total_of_special_requests: Total number of special requests made by the guest.
- reservation_status: Reservation status (e.g., Canceled, Check-Out, No-Show).
- reservation_status_date: Date of the last update of the reservation status.


## Interactive Dashboard
- Dashboard: To present the analyzed information, the project included the development of an interactive dashboard. The dashboard was designed to be user-friendly and visually appealing, with features such as filters, graphs, and tables that allowed users to explore the data and discover key insights.
- Key insights: The dashboard provided useful insights about if the revenue is increasing year by year, total nights the customers stayed in hotel, average daily rate of the hotel, percentage of parking occupied by people on a night, etc. These insights were derived from the data analysis and were presented in an easy-to-understand format on the dashboard.


## Visualizations

The following report was successfully created in Microsoft PowerBI.

![DB1](https://github.com/Anshika10022001/Hotel-Analysis/assets/128470731/ff9b1988-7979-4895-9628-6dcd5acfc023)

![DB2](https://github.com/Anshika10022001/Hotel-Analysis/assets/128470731/96b73bf9-ef49-4ffb-9f8b-bb518dbca422)

## Tech Stack

<table style="border: none; border-collapse: collapse;">
  <tr>
    <td style="vertical-align: middle;">
      <a href="https://www.mysql.com/" target="_blank" rel="noreferrer">
        <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mysql/mysql-original-wordmark.svg" alt="mysql" width="80" height="80"/>
      </a>
    </td>
    <td style="vertical-align: middle; padding-left: 10px;">
      Aggregations, joins, Window Functions, Complex Calculations
    </td>
  </tr>
</table>

<table style="border: none; border-collapse: collapse;">
  <tr>
    <td style="vertical-align: middle;">
      <a href="https://learn.microsoft.com/en-us/power-bi/" target="_blank" rel="noreferrer">
        <img src="https://upload.wikimedia.org/wikipedia/commons/c/cf/New_Power_BI_Logo.svg" alt="powerbi" width="80" height="80"/>
      </a>
    </td>
    <td style="vertical-align: middle; padding-left: 10px;">
      Data Cleaning, Power Query, Dashboarding, Visualizations
    </td>
  </tr>
</table>


## Future Scope

- Actionable recommendations: Based on the insights generated from the dashboard, the project can provide actionable recommendations for policymakers and stakeholders. For example, recommendations could include investing in hotel infrastructure such as increased parking lot so that more tourists could stay,etc.

