# Airline-Data-Management-and-Analysis-Overview-

## Objective: To analyze and visualize airline data for operational insights, passenger management, and ticket booking trends using Power BI.

### TASK 1:
  Data Preparation and Cleaning:
    Extract and transform data in Power Query.
    Clean data: remove duplicates, handle missing values, and format columns.

### TASK 2:
  Data Modeling:
    Create relationships between datasets (FlightID as the key)
    Understand cardinality and configure the model appropriately.

### TASK 3:
  Enhanced Data Insights:
    Add a “conditional column” to classify flights as "Best" or "To Be Improved" based on status.
    Use “Column from Examples” to extract the flight number from FlightNumber.

### TASK 4:
  Calculations Using DAX:
    Total passengers for a specific flight.
    Total tickets booked.
    Filtered table showing "Best" flights only.

### TASK 5:
  Visualization and Interactive Features:
    Create visuals for:
      o Passenger count by airline.
      o Ticket booking statuses.
      o Flights by airline and destination.
    Add interactive features for:
      o Destination and Airline.
      o Quick views.
      o Airline-specific pages.

### TASK 6:
  Final Dashboard and Power BI Service:
    Design a comprehensive dashboard with key visuals and insights.
    Configure Row-Level Security (RLS) for Airline A data and assign it to a user.
    Set up a schedule refresh at 5 PM daily.

## Key Findings & Insights:
  1. Total Flights Operated: Total 200 flights are operated for different destination from different airlines.
  2. Airline Performance: Airline B has highest number of tickets booked. But we can see Airline D has highest number of           flights in best condition.
  3. Top Destinations: Houston and Los Angles are the two best destination for the passengers.
  4. Auto Refresh Schedule: Data is refreshed daily at 5:00 PM IST to keep reports up-to-date with the latest ticket and           flight information.

## Strategic Opportunities:
  1. Improve on-time performance for delayed destinations.
  2. Increase seat utilization to decrease cancellation on tickets.
  3. Improve number of airlines to the destination having a smaller number of flights.

