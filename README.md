# Liveness-ReadinessProbe


![image](https://user-images.githubusercontent.com/80065996/170356500-8cb83d50-da52-40e0-aaef-98f8bfb66af3.png)


# 1) Readiness probe -- 'service' object will send traffic to pods only if the application running inside the container of the pod is ready to recieve traffic.
# 2) Liveness probe -- 'service' object will check whether the pod is alive or not. if you pod is alive, kubernetes will leave as it is or else kubernetes will restart the pod.
