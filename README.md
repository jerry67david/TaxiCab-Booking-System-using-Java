# TaxiCab-Booking-System-using-Java
Taxi Cab Booking System in Java
This is a console-based Taxi Booking System implemented in Java, which simulates real-time taxi allocation based on availability, distance, and earnings.

📌 Problem Scenario
The system simulates 6 fixed locations: A, B, C, D, E, F.

Each point is 15 km apart, and travel time between adjacent points is 1 hour.

Taxis start at location A at 6 AM by default.

Fares are calculated as:

₹100 for the first 5 km

₹10 per km for every km beyond that (from pickup to drop point only).

✅ Booking Logic
When a customer books a taxi:

A free taxi at the pickup point is preferred.

If unavailable, the system finds the nearest available taxi that can reach the customer before pickup time.

Among multiple taxis at the same location, the taxi with the least earnings is assigned.

If no taxi is available that meets the criteria, the booking is rejected.

💡 Features
🚖 Dynamic taxi assignment based on proximity and earnings

⏱️ Tracks each taxi's availability and location in real time

💰 Calculates fare and maintains earnings for each taxi

📊 Displays detailed reports for each taxi including:

Trip history

Earnings

Drop and pickup details
