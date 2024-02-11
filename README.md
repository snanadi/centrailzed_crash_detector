## Centralized Crash Detector
The Centralized Crash Detector project aims to integrate the Crash Analyzer with k8s deployment to enhance scalability and improve crash detection efficiency. The project targets a 20% reduction in missed crashes and a 30% enhancement in data retrieval and analysis speed through centralized database implementation. This project is developed internally in Parallel Wireless.

## Key Features and Implementation
AWS Deployment Integration: The project integrates the Crash Analyzer with AWS deployment to enhance scalability and reliability.

Improved Crash Detection: With AWS integration, the project aims to reduce missed crashes by 20%, ensuring comprehensive crash analysis across various VMs.

Centralized Database Implementation: By implementing a centralized database, the project targets a 30% improvement in data retrieval and analysis speed. This centralized approach facilitates efficient data storage, retrieval, and analysis across multiple machines.

Data Centralization Process: Crash uploads from different VMs are stored in S3 buckets. Individual machines host Docker containers with crash analysis components for crash detection and analysis. Once a crash is successfully analyzed, the data is transferred to a central server containing frontend, backend, and MongoDB. The frontend provides crash records of all VMs for comprehensive monitoring and analysis.

Tools Used
The Centralized Crash Detector project utilizes the following tools:

Docker: Used for containerization and deployment of crash analysis components.
MongoDB: Serves as the centralized database for storing crash data.
Node.js: Powers the backend server for handling data transfer and analysis.
React: Utilized for developing the frontend interface, enabling users to monitor and analyze crash records.
Nginx: Acts as the web server for serving static content and reverse proxy for backend services.
Redis: Provides caching and session management capabilities for improved performance and scalability.
Use and Advantages
The Centralized Crash Detector project offers the following benefits:

Comprehensive Crash Detection: Ensures that crashes are not missed, leading to improved system reliability and performance.
Time Savings: By analyzing crashes in real-time and providing dynamic filtering capabilities, the project saves time in identifying and addressing critical issues.
Statistical Analysis: Provides statistical data on crashes, builds, and versions, facilitating informed decision-making and system optimization.
Getting Started
To get started with the Centralized Crash Detector project:

Clone the repository to your local machine.
Ensure Docker, MongoDB, Node.js, React, Nginx, and Redis are installed and configured.
Configure AWS deployment settings and integrate with the project.
Follow the provided documentation for setup instructions and deployment procedures.
Access the frontend interface to monitor crash records and analyze statistical data.
