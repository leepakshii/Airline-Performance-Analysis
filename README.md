#  Airline Data Management and Analysis (Power BI Project)

##  Overview
This project focuses on **airline data management** and performance analysis using **Power BI**.  
It integrates flight, passenger, and ticketing data to create an interactive dashboard that helps improve **operational efficiency** and **customer satisfaction**.  

---

##  Project Structure

---

##  Datasets Used
1. **Flight Information** → FlightID, FlightNumber, Airline, Destination, Status  
2. **Passenger Information** → PassengerID, FlightID, SeatNumber  
3. **Ticket Information** → TicketID, FlightID, BookingStatus  

---

##  Key Steps
1. **Data Preparation & Cleaning**
   - Cleaned datasets for passengers, tickets, and flights  
   - Extracted flight numbers  

2. **Data Modeling**
   - Created relationships using `FlightID` as the primary key  
   - One-to-Many and Many-to-One cardinalities  

3. **Enhanced Data Insights**
   - Classified flights as *Best*, *To Be Improved*, or *Cancelled*  
   - Applied row-level security for airline-specific dashboards  

4. **DAX Calculations**
   - `TotalPassengers = DISTINCTCOUNT(PassengerID)`  
   - `TotalTickets = DISTINCTCOUNT(TicketID)`  
   - `TotalFlights = DISTINCTCOUNT(FlightID)`  

5. **Visualization**
   - Passenger count by airline  
   - Ticket booking status  
   - Flights by airline & destination  
   - Airline-specific report pages  

6. **Deployment**
   - Published to Power BI Service  
   - Enabled daily refresh at 5 PM  

---



