# Description
Templates for monitoring Filebeat (old versions).

# Requirements
Filebeat 5.x or older.

# Installation
- Import zabbix templates to your zabbix server
- Add template "Filebeat 5.x" on host(s)
- Have fun

# Additional info
Template have some var attributes that you can configure:
- {$LOGS_PATH} - path to your Filebeat log file (default - /var/log/filebeat/filebeat)
- {$DIFF_ALARM} - max acceptable difference between Zabbix server time and last changes in Filebeat log file in seconds (default - 120)

# TODO
Add more available metrics.

# Feedback
Find the way make this template better? Feel free to share this info with me by mail or in "Issues" section.
