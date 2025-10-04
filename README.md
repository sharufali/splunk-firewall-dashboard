# Splunk Firewall Monitoring Dashboard

This is a custom Splunk XML dashboard that visualizes firewall traffic.

## Features
- Blocked vs Allowed Connections
- External Source and Destination IPs
- Network Traffic by Action (time-based)
- Protocol Distribution (TCP/UDP/ICMP)
- Top Countries by Blocked Connections
- Top Sources by Blocked Connections
- Top Blocked Traffic Categories

## Usage
1. Copy the XML from `firewall_dashboard.xml`.
2. In Splunk, go to **Dashboards → Create New Dashboard → Source Mode**.
3. Paste the XML and save.
4. The dashboard will now show real-time firewall monitoring metrics.
