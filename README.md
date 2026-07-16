# DataSentinel: Autonomous Agent-Based Data Auditing

DataSentinel is an autonomous, agent-based data auditing pipeline designed to automate the inspection and governance of data files. By utilizing a multi-agent architecture and the Model Context Protocol (MCP), it enables proactive anomaly identification and automated reporting.



## 🚀 Project Overview
* **Goal:** Reduce audit turnaround times and minimize human oversight in data governance.
* **Core Technology:** Model Context Protocol (MCP), Agent Development Kit (ADK), and Docker.

## 🛠 Project Structure
* `server.py`: Implements the `FastMCP` server, acting as the secure interface for data context.
* `agent.py`: The worker agent logic that utilizes the MCP tools to perform audits.
* `Dockerfile`: Containerizes the entire project for seamless deployment to cloud environments (Azure/GCP/AWS).

![Agent](https://github.com/fahmymahamud/DataSentinel/blob/main/agent.jpg)

![Server](https://github.com/fahmymahamud/DataSentinel/blob/main/server.jpg)

![Dockerfile](https://github.com/fahmymahamud/DataSentinel/blob/main/dockerfile.jpg)

## 🔗 Submission Links
* **Demo Video:** [https://www.youtube.com/watch?v=I2bmMyplGug]

## ⚡ How to Run
1. **Ensure your virtual environment is active:**
   ```powershell
   .venv\Scripts\Activate.ps1
