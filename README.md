Emergency Facility Management System
Project Overview
The Emergency Facility Management System is a dynamic resource allocation system designed to assist during emergencies such as natural disasters, large-scale accidents, or evacuation events. It optimizes the assignment of facilities (e.g., hospitals, shelters) to evacuees or patients based on priority, proximity, and availability. By leveraging key data structures and efficient algorithms, the system ensures timely responses and fair handling of requests.

Features
Proximity-Based Facility Allocation:

Facilities are allocated based on their distance from the emergency zone to minimize transportation time.

Priority Handling:

VIP (critical) requests are prioritized over non-critical ones to ensure life-saving resources are allocated appropriately.

Real-Time Data Updates:

Facility occupancy and capacity are updated dynamically as requests are processed.

Queue Management:

Requests are managed in critical and non-critical queues for fair and priority-based handling.

Scalability:

Designed to handle large-scale emergencies with multiple facilities and thousands of requests.

Key Technologies
Data Structures Used
Binary Search Tree (BST):

Facilities are stored in a hierarchical structure based on proximity (distance).

BST enables fast search for the nearest available facility.

Queue:

Critical and non-critical requests are stored in queues and processed sequentially based on priority.

HashMap:

Facility details (ID, capacity, occupancy) are stored in a HashMap for constant-time retrieval and updates.

Database Integration (Optional)
JDBC is used for storing and managing persistent facility and request data in relational databases (e.g., MySQL).

System Workflow
Initialization:

Facilities are preloaded into the system with attributes like distance, capacity, and VIP designation.

Adding Requests:

Evacuees or patients submit their requests with IDs and priority (critical/non-critical).

Facility Allocation:

Requests are processed:

Search for the nearest available facility using the BST.

Verify availability using the HashMap.

Allocate the facility and update its occupancy.

Real-Time Monitoring:

Facility statuses and queue contents are displayed dynamically for operational transparency.

Real-World Applications
Disaster response (e.g., earthquakes, floods).

Evacuation planning for large-scale events.

Resource allocation during crises in public or private sectors.

How to Run the Project
Ensure you have Java installed.

Compile and run the program in your IDE or console.

Follow the interactive menu to add requests, allocate facilities, and monitor statuses.

Future Enhancements
AI Predictions:

Predict facility demand based on past data trends.

IoT Integration:

Enable automatic facility updates through IoT sensors.

Mobile Accessibility:

Develop a mobile application for evacuees to submit requests remotely.
