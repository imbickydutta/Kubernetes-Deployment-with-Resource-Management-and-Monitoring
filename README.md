# Kubernetes-Deployment-with-Resource-Management-and-Monitoring
3) 
CRITICAL METRICS: 
a) Cpu Consumption: Direct infuence on the autoscaling behaviour
b) Memory Footprint: Helps in detecting leaks and avoiding container termination
c) Request Failure Rate / response time: indicates application health under load

ALERT CONDITIONS
- Sustained CPU usage above 80% for several minutes
- repeated container restarts with a short interval
4) 
- Defined requests ensure baseline performance, while limits protect the cluster from resource exhaustion
- The autoscaler dynamically adjusts pod count to handle fluctuating traffic 
between 500 and 5000Rpm
- Readiness probes manage traffic flow and liveliness probes recover unhealthy containers automatically.
