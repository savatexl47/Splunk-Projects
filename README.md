# Splunk SIEM Log Analysis Projects

This repository contains a collection of projects for analyzing various types of logs using Splunk SIEM. Each project provides a structured guide for uploading sample log files, performing analysis, and gaining insights into specific types of log data.

## Projects

1. [Analyzing DNS Logs Using Splunk SIEM](https://github.com/savatexl47/Project1-Analyzing-DNS-Logs)
2. [Analyzing FTP Logs Using Splunk SIEM](https://github.com/savatexl47/Project2-Analyzing-FTP-Logs)
3. [Analyzing HTTP Logs Using Splunk SIEM](https://github.com/savatexl47/Project3-Analyzing-HTTP-Logs)
<!-- 
4. [Analyzing SSH Logs Using Splunk SIEM](https://github.com/yourusername/Project4-Analyzing-SSH-Logs)
5. [Analyzing Tunnel Logs Using Splunk SIEM](https://github.com/yourusername/Project5-Analyzing-Tunnel-Logs)
6. [Analyzing SMTP Logs Using Splunk SIEM](https://github.com/yourusername/Project6-Analyzing-SMTP-Logs)
7. [Analyzing DHCP Logs Using Splunk SIEM](https://github.com/yourusername/Project7-Analyzing-DHCP-Logs)
-->

## Prerequisites

Before starting any project, ensure the following:
- Splunk instance is installed and configured.
- Log data sources are configured to forward logs to Splunk.

## General Instructions

### Uploading Log Files to Splunk SIEM

1. **Prepare Sample Log Files:**
   - Obtain sample log files in a suitable format.
   - Save the sample log files in a directory accessible by the Splunk instance.

2. **Upload Log Files to Splunk:**
   - Log in to the Splunk web interface.
   - Navigate to **Settings** > **Add Data**.
   - Select **Upload** as the data input method.
   - Choose the sample log file.
   - Set the source type and review settings.
   - Click **Submit** to upload the sample log file to Splunk.

3. **Verify Upload:**
   - Navigate to the search bar in the Splunk interface.
   - Run a search query to verify that the uploaded log events are visible.

### Analyzing Log Files in Splunk SIEM

1. **Search for Log Events:**
   - Open Splunk interface and navigate to the search bar.
   - Enter the search query to retrieve log events.

2. **Extract Relevant Fields:**
   - Identify key fields in log files.
   - Use Splunk's field extraction capabilities or regular expressions to extract these fields.

3. **Analyze Patterns and Detect Anomalies:**
   - Perform statistical analysis and visualizations to identify patterns and anomalies.

4. **Monitor User Behavior:**
   - Track user activities and detect suspicious behavior.

## Conclusion

By following the projects in this repository, you will gain valuable insights into different types of log data and enhance your skills in using Splunk SIEM for security and network analysis.
