# TICE.v1
Threat Intelligence Correlation Engine (TICE)  TICE is a web tool that gathers threat data from Shodan, VirusTotal, and IPInfo, correlates the results, and generates a risk score to quickly identify malicious IPs.

⚠️ API Failure / No Response Handling
If the dashboard stops showing results, the issue is likely due to API limits or downtime from OSINT providers (Shodan, VirusTotal, IPInfo). Simply log in to the respective service, generate a new API key, replace the old key in your .env file, and run the app again.
