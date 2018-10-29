# EKstack Metricbeat Packetbeat
Ansible role voor het installeren van Elasticsearch, Kibana, Metricbeat, Packetbeat

## Monitoring server
De role heeft maar 1 variabele, deze moet aangepast worden naargelang de netwerk configuratie.  
Als metricbeat_ip: 'localhost' (default) is, dan wordt de role volledig geïnstalleerd op huidige machine.  


## Monitoring client  
Als je een systeem wilt installeren als een metricbeat client dan dien je de variabele 'metricbeat_ip' aan te passen naar het ip adres van de elasticsearch server.  

## Defaults  
`metricbeat_ip:'localhost'`
