# eztest
```
(base) jear@ubuntu22:~$ k apply -f app.yaml -n hpe-ai-coe 
deployment.apps/springboot-app created
(base) jear@ubuntu22:~$ k apply -f app-svc.yaml -n hpe-ai-coe

# Get svc:port and test prime numbers
http://gwtest.gwtest.com:10038/prime?number=71

```
    
