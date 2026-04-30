# Fleet_data
This project uses synthetic data to calculate and predict fuel consumption for a variety of vehicles (vans to heavy-duty trucks). By analyzing specific engine types, service history, and live traffic data, the application provides an accurate fuel estimate for a trip before the vehicle even leaves the starting point.

This is specifically designed for logistics and supply chain managers to:

Budget Accuracy: Calculate the exact liters needed for routes (e.g., Point A to B, or Point A to B to C).

Diagnostic Alerts: Track maintenance history to explain vehicle behavior. If a vehicle consumes more fuel than predicted, it could be flagged as it needing servicing or cooling system checks.

Scalability: The underlying predictive logic can be adapted to track any resource consumption rate beyond just vehicles and fuel.

Key Features:
Comprehensive Vehicle Database: Includes actual models and engine specifications.

Maintenance Logic: Factors in the last serviced date to adjust consumption efficiency based on mechanical health.

Live Traffic Integration: Designed to pull real-time GPS and traffic readings to account for idling and congestion on routes.

Dynamic Planning: Estimates consumption based specifically on the intended time of departure.

Since real-world fleet data is private, this project utilizes Synthetic Data. I carefully generated this dataset to mirror real world engine behaviors and fuel burn rates to ensure the logic remains technically sound and scalable.

If you have questions or want to contribute to the logic:

Support: Open an Issue in this repository.

Maintainer: This project is maintained by Agbaje-Adeola.
