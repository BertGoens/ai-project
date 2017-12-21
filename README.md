# ai-project
Bert, Cedric, Michiel

# Requirements
**Client:** 
- [Osquery](https://osquery.io/downloads/)
- Powershell

**Server:**
- [Java JRE](https://java.com/en/download/win10.jsp)
- [Kibana](https://www.elastic.co/downloads/kibana)
- [All kibana plugins](https://www.elastic.co/products/x-pack)
- [ElasticSearch](https://www.elastic.co/products/elasticsearch)

# Install
Follow the [WindowsInstaller.ps1](./client/scripts/install/WindowsInstaller.ps1)

## Ideas
- Try to link osquery with Prometheus to get advanced info about the web server and / or the database.
- Change our SendLogs to send logs to an index of the day (Format: osquery-YYYY-MM-DD) akin logstash.
- Subscribe to githooks to automatically update the new config

