# Wazuh-Deployment
Wazuh is an open-source tool that functions as a host-based intrusion detection system (endpoint). 
It performs log analysis, integrity checking, Windows registry monitoring, rootkit detection, time-based alerting, and active response.

Wazuh is a tool that provides deeper security visibility into an infrastructure by monitoring hosts at both the operating system and application levels. Wazuh consists of two main components: the Wazuh Server and the Wazuh Agent.

- The Wazuh Server serves as the management platform for agents and provides a monitoring dashboard for file integrity, intrusion detection, and log management.

- The Wazuh Agent is installed on endpoint devices to read system data, collect logs, and send them securely to the Wazuh Server.

Wazuh offers several key features:

- Log management and analysis: The Wazuh Agent reads operating system and application logs, then securely forwards them to the Wazuh Server for analysis and storage.

- File integrity monitoring: Wazuh monitors the file system, detecting changes in content, permissions, ownership, and file attributes.

- Intrusion and anomaly detection: The Wazuh Agent scans the system for malware, rootkits, and suspicious anomalies. It can detect hidden files, stealth processes, unauthorized network listeners, and inconsistencies in system call responses.

- Policy and compliance monitoring: Wazuh checks configuration files to ensure compliance with security policies, standards, or hardening guidelines based on security frameworks. Agents perform regular scans to detect vulnerable, unpatched, or misconfigured applications.

These diverse capabilities are delivered by integrating OSSEC, OpenSCAP, and the Elastic Stack, creating a unified solution that simplifies configuration and management.

After that, the next configurations are attached here in several configuration files.
