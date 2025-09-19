Project Requirements
🔧 Tools & Platforms

Splunk Enterprise (Version 9.x or Splunk Cloud equivalent)

Splunk Dashboard Studio (built-in with Splunk Enterprise/Cloud)

Search Processing Language (SPL) for detections and queries

📂 Dataset Requirements

Dataset must be uploaded into Splunk with:

Index: main

Sourcetype: csv

Dataset Columns:

timestamp, masked_user, location_count, anomaly_bin, session_duration, 
session_complexity, event_count, session_source_ip, destination_ip, 
action, resource, protocol, access_result, location, device_type, 
protocol_SSH, protocol_RDP, device_desktop, device_mobile, device_tablet

📊 Dependencies

While Splunk doesn’t use Python libraries directly, here are the dependencies for smooth project execution:

Splunk Apps:

Search & Reporting (default)

Dashboard Studio (default)

Optional Add-ons (for extended use):

Splunk Machine Learning Toolkit (MLTK) – if anomaly detection is extended

GeoIP lookup – for enhanced map visualizations

🖥️ System Requirements

Operating System: Windows / macOS / Linux

RAM: Minimum 8GB (Splunk runs best on ≥16GB)

Disk Space: 20GB+ (for storing indexes and dashboards)

Browser: Chrome / Edge / Firefox (for Splunk Web UI access)

📌 Installation Steps

Install Splunk Enterprise (9.x) or sign up for Splunk Cloud Trial.

Start Splunk service and log in to Splunk Web (http://localhost:8000
).

Upload dataset via:
Settings → Add Data → Upload → Select CSV → Index=main Sourcetype=csv

Import provided Dashboard JSON template in Dashboard Studio.

Run SPL queries and confirm data is being indexed.
