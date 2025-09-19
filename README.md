# BEHAVIORAL-ANALYTICS-Splunk-

📌 Project Overview

This project focuses on building a Splunk Security Dashboard that detects and visualizes suspicious login activities and anomalies. The dashboard provides real-time insights into user login behavior, anomalies, and possible malicious activities.

It is designed as part of a cybersecurity case study to improve threat detection and monitoring using Splunk’s SIEM capabilities.

🎯 Problem Statement

Organizations often struggle to detect:

Multiple failed login attempts (brute force)

Logins from unknown or unusual locations

Abnormal session durations

Accessing restricted resources

Traditional logs make it hard for security teams to identify these issues quickly.
This project solves that problem by creating visual dashboards & anomaly detections in Splunk.

🚀 Features Implemented

📊 KPI Panels: Failed vs Successful login attempts

🕒 Time-Series Trend Analysis: Login activity over time

🌍 Geographic Map: Login attempts by location

⚠️ Anomaly Detection: Detects abnormal sessions using anomaly scores

🔑 Resource Accessibility: Highlights restricted resource access

🖥️ Device Analysis: Detects login attempts by device type (Desktop, Mobile, etc.)

🔔 Alerts: Turn reports into alerts for real-time monitoring

📂 Project Structure
├── data/                 # Sample dataset used for Splunk ingestion

├── detections/           # SPL queries for anomaly detection

├── dashboard/            # JSON template for Splunk Dashboard Studio

├── screenshots/          # Dashboard screenshots

└── README.md             # Project documentation

⚡ Technologies Used

Splunk Enterprise / Splunk Cloud

Splunk Dashboard Studio

SPL (Search Processing Language)

JSON (for dashboard template)

🔍 Key Detections

Excessive Failed Logins

Logins from Unknown Locations

Resource Accessibility Violations

Sessions with High Complexity & Malicious Target

Anomaly Score ≥ 0.5 (possible abnormal activity)

🖼️ Dashboard Preview

🛠️ How to Use

Upload the provided sample dataset into Splunk (index=main sourcetype=csv).

Import the JSON dashboard template into Splunk Dashboard Studio.

Run the SPL queries to verify data population.

Explore the dashboard panels for login trends, anomalies, and maps.

(Optional) Enable alerts for real-time detection.

📌 Future Enhancements

Integrate real-time alerts with email/SMS notifications.

Add User Behavior Analytics (UBA).

Expand to detect insider threats and data exfiltration.

Connect with external threat intelligence feeds.

👩‍💻 Author

Faith Jackson Nkuba

