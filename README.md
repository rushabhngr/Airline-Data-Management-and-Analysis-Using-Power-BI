#  Airline Data Management and Analysis Using Power BI  

##  Overview  
The airline industry operates with numerous complexities, requiring effective data management and insights into flight schedules, passenger details, and ticketing systems. This project leverages **Power BI** to analyze and visualize airline data for improved operational efficiency and customer satisfaction.  

---

##  Dataset  
The analysis is based on three datasets:  

1. **Flight Information** – FlightID, FlightNumber, Airline, Destination, Status.  
2. **Passenger Information** – PassengerID, FlightID, SeatNumber.  
3. **Ticket Information** – TicketID, FlightID, BookingStatus.  

---

##  Project Objectives  
- Clean and prepare datasets using **Power Query**.  
- Build a robust **data model** with relationships.  
- Create **DAX calculations** for metrics.  
- Develop **interactive dashboards** with insights into flights, passengers, and ticketing.  
- Configure **Row-Level Security (RLS)** and automated refresh for deployment.  

---

##  Project Tasks  

### **Task 1: Data Preparation and Cleaning**  
- Extracted and transformed data in **Power Query**.  
- Removed duplicates, handled missing values, and formatted columns.  
- **Deliverable:** Screenshot of cleaned data in Power Query.  

### **Task 2: Data Modeling**  
- Created relationships between datasets using **FlightID** as the key.  
- Configured cardinality and cross-filtering.  
- **Deliverable:** Screenshot of data model with relationships.  

### **Task 3: Enhanced Data Insights**  
- Created a conditional column to classify flights as **“Best”** or **“To Be Improved”**.  
- Used *Column from Examples* to extract Flight Number.  
- **Deliverable:** Screenshot of transformed data.  

### **Task 4: Calculations Using DAX**  
- Built DAX measures for:  
  - Total passengers per flight.  
  - Total tickets booked.  
  - Filtered table for **“Best” flights** only.  
- **Deliverable:** Screenshot of DAX calculations and results.  

### **Task 5: Visualization and Interactive Features**  
- Visuals created:  
  - Passenger count by airline.  
  - Ticket booking statuses.  
  - Flights by airline and destination.  
- Interactive features:  
  - Destination & Airline filters.  
  - Quick views.  
  - Airline-specific drill-through pages.  
- **Deliverable:** Screenshots of all visuals & interactions.  

### **Task 6: Final Dashboard and Power BI Service**  
- Designed a **comprehensive dashboard** combining key visuals and KPIs.  
- Configured **Row-Level Security (RLS)** for Airline A.  
- Scheduled daily refresh at **5 PM**.  
- **Deliverable:** Final dashboard screenshot and Power BI Service deployment.  

---

##  Tools & Skills Used  
- **Power BI Desktop** – Power Query, Data Modeling, DAX.  
- **Visualization** – Interactive dashboards, filters, drill-throughs.  
- **Power BI Service** – Row-Level Security (RLS), scheduled refresh.  

---

##  Outcome  
- Built an **end-to-end Power BI solution** for airline operations.  
- Enabled insights into passenger volumes, ticketing trends, and flight performance.  
- Delivered a scalable **dashboard with security & automation** for real-world use.  

---



