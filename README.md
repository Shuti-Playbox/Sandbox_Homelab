# Sandbox_Homelab
In this project, I have set up a small Security Information and Event Management (SIEM) lab using Wazuh to collect, monitor, and analyze logs from multiple systems. The environment consists of:

  Wazuh Server (Kali Linux VM): Acts as the central management and monitoring server where all logs are aggregated, analyzed, and visualized.
  Kali Linux Agent VM: Sends system logs and events to the Wazuh server for monitoring and security analysis.
  Windows Agent VM: Demonstrates multi-platform log collection by forwarding Windows event logs to the Wazuh server.

Summary of Functionality
  The agents send real-time logs to the Wazuh server.
  The server monitors for suspicious activity, system changes, and security alerts.
  Logs are visualized using the Wazuh dashboard, allowing centralized monitoring of both Linux and Windows systems.
  
Through this setup, I learned:
  How to deploy Wazuh as a SIEM solution in a small network environment.
  How to configure Wazuh agents on both Linux and Windows systems.
  The basics of centralized log collection, monitoring, and alerting.
  How to analyze system events and security alerts to improve visibility into network activity.
  The importance of cross-platform log collection for comprehensive security monitoring.

While i am still currently playing aroudn with ideas and trying different attacks on the agents to see how it would show up in Wazuh,  i am also keen on trying to setup an AD lab of small size but that will problaby happen a bit furter into the future

//Shuti
