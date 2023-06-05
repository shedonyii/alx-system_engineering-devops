ISSUE SUMMARY
•	The outage lasted from 10:00 AM to 11:00 AM GMT on June 1st, 2023.
•	The service was down for all users during the outage.
•	The root cause of the outage was a misconfiguration in the load balancer.
TIMELINE                                                                                                                                   The issue was detected at 10:00 AM GMT on June 1st, 2023.
•	The issue was detected by monitoring alerts.
•	The system logs were investigated and it was assumed that there was an issue with the database.
•	The database was checked and it was found to be working fine. This led to further investigation into the load balancer configuration.
•	The incident was escalated to the DevOps team.
•	The misconfiguration in the load balancer was corrected and service was restored at 11:00 AM GMT
ROOT CAUSE AND RESOLUTION

•	The misconfiguration in the load balancer caused all traffic to be routed to a single server which could not handle all requests.
•	The load balancer configuration was corrected to distribute traffic evenly across all servers.
CORRECTIVE AND PREVENTATIVE MEASURES
•	Monitoring alerts can be improved for faster detection of issues.
•	Performing a list of tasks to address the issue like a TODO, example: patch Nginx server, adding monitoring on server memory. Review and improvement of load balancer configuration. Review and improvement of system logs.
