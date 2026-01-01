# SOC Automation Lab: EDR to SOAR Integration

This project demonstrates the implementation of an end-to-end Security Operations Center (SOC) automation pipeline. The workflow integrates LimaCharlie EDR to ingest telemetry from a Linux Ubuntu endpoint, which is then orchestrated by Tines SOAR. The automation logic performs real-time threat intelligence enrichment via the VirusTotal API, enabling the system to take automated remediation actions (such as host isolation) or alert SOC analysts via Slack for manual intervention.

## Project Architecture & Flow
The Diagram below illustrates the flow of event from the intiial detection of event in the ubuntu server(endpoint) to the final remediation action:
*(Click to zoom)*
![Tines Workflow Diagram](images/tines_story_v2.png)
