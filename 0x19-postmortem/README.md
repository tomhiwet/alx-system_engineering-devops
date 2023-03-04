One of the services which are given by a bank is Internet Banking and Commercial bank of Ethiopia is one of them. 
Internet Banking was down on Mar-01 due to core banking server cache memory being too high. 
Because of this the whole Internet Banking users of the Bank were out of service for about 30 minutes until the 
incident was solved.   
The incident happened on March 01 2023 2:00 PM and the monitoring team detected it using a monitoring tool grafana.
The grafana shows a color alert to the users and the monitoring team created an incident ticket to the second and third 
level support to interfere. The monitor team tried to investigate the root cause but their privilege doesn’t 
allow them further investigation and second and third level support was engaged on the specific task. 
The second and the third level support team was engaged and investigated the cause which is that the 
core banking server cache memory is too high or above threshold. And they decided to clear the cache
 memory and restart the server. Then the service was back to work.
Root cause of the incident is server cache memory issue
After that a new dashboard was designed to investigate Internet Banking server issues before it was happening.

