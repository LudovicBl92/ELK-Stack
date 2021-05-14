# ELK

These playbook allows ELK's installation with some modules. I install:
	- Elasticsearch
	- Kibana
	- openJDk
	- Logstash
	- Nginx
	- Filebeat
	- Metricbeat

To test if the services works;
- do a "systemctl status <your SERVICE> command" 
- go on your web browser and <your @IP:5601>
- Check the Index patterns on Kibana and Index Management on Elasticsearch
- Create the index patterns nginx and select @Timestamp before to finish the creation
- make a curl request on your IP adress and go on Discover tab to see the result
- to check the metric go to your home, click on Add Data and System Metric. In the page click on check Data and Finaly System metrics Dashboard
