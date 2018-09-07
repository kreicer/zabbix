# Description
Template and script for monitoring Redis Server, .conf file for zabbix agent.
Script forked from https://github.com/pavelnemirovsky/zabbix-redis-template/ and upgraded by me (added databases discovery)

# Installation
- Put .conf file into your zabbix conf directory on node(s)
- Put .sh file into your zabbix/scripts directory on node(s)
- Import zabbix templates to your zabbix server
- Add template "Redis Server" on node(s)
- Configure template with your needs
- Have fun

# Additional info
Template have some var attributes that you can configure:
- {$COMMAND_LATENCY} - max acceptable latency for command execution in ms (default - 0.3)
- {$EXPIRED_KEYS} - max acceptable number of expired keys with reached cap of time (default - 1000)
- {$MASTER_IO_TIME} - max acceptable time since last interaction with master node in sec (default - 60)
- {$MEMORY_DELTA} - max acceptable used memory delta for 5 minutes interval (default - 3G)
- {$RDB_TIME} - max acceptable time for RDB save operations in sec (default - 600)
- {$REDIS_PASSWORDS} - passwords list for access to redis server (default - )

# Feedback
Find the way make this template better? Feel free to share this info with me by mail or in "Issues" section
