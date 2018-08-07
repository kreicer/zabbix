# Description
Templates for monitoring Elastic Search cluster and nodes, .conf file for zabbix agent.

# Requirements
This script https://github.com/adel-s/zabbix/tree/master/ElasticSearch on each node.

# Installation
- Put .conf file into your zabbix conf directory
- Improt zabbix templates to your zabbix server
- Add template "Elastic Search - Health and Cluster" on master node
- Add template "Elastic Search - Node" on each node in cluster (include master node)
- Have fun

# Feddback
Find the way make this template better? Feel free to share this info with me by mail or in "Issues" section
