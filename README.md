# Basic-Documents---DevOps
Various **limited** documents from my work tools when i used to work as DevOps Engineer, these are **basic usage and limited testing** results ( because I don't have the premission to publicize the full documents that I have written for my work ) 

**For better understanding and more explanations please read my blog ( https://navidmalek.blog.ir/) posts referring to the documents and repositories here.**

**Description**:

**ETCD_CLUSTER.pdf** ==> Setting up an ETCD cluster
objective:
• setup an etcd cluster on 3 servers
• write appropriate service to be sure ETCD will be always running
- ETCD version ==> 3.3.9
- server OS ==> CentOS7

The related ansible code are in the **mycontrolansible** directory.


**LizardFS.pdf** ==> Setting up LizardFS and testing it
objective:
• setup simple LizardFS master on one server
• test LizardFS performance on 3,5,7 chunk servers (HDD)
• test LizardFS performance on SSD
- LizardFS version ==> 3.12


**GrafanaPrometheus.pdf** ==> Setup Prometheus and Grafana for monitoring
objectives:
• setup Prometheus server
• setup Prometheus exporters
• setup Grafana server
• setup Grafana dashboard

**GalleraCluster.pdf** ==> Setting up a MySQL Gallera cluster
objective:
• setup an MySQL Gallera cluster on 3 servers
• write apporopiate service to be sure MySQL Gallera cluster will be always running
- MySQL version ==> 5.7
- MySQL-wsrep ==> 5.7
- server OS ==> CentOS7

**ProxySQL.pdf** ==> Set up and testing ProxySQL
objectives:
• setup ProxySQL load balancer on one server
• configuring ProxySQL
• test the performance and load balancing of ProxySQL with SYSBENCH
• setup ProxySQL architecture with no single point of failure


**telegrafLogparser.pdf** ==> Using Telegraf to Parse Custom Logs
objective:
• read custom logs with telegraf
• parse custom logs with telegraf
• generate an output from custom logs to influxdb
The TIG stack [ telegraf, influxdb, grafana ]


**DatabaseTestDoc.pdf** ==> Testing Database response time
We will test 4 databases ( **this doc is very limited and acts as a road map for more professional tests** ):
RDB:
-mysql
-postgres
No-SQL:
-mongo
-cassandra

**TCP_tune.pdf** ==> Some TCP tuning parameters that i have gathered form internet ( **this is a messy doc, just gathered information from Internet, for more info on TCP_TUNING refer to my blog!** )


