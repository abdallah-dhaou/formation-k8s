### LAB1 (PODS)

- Create a pod from ubuntu/apache2 from command line
- Create a pod based on nginx with manifest file.
- Create a pod based on tomcat:8.99, investigate what's wrong with that pod!
- copy this code into a manifest file and run it on your cluster, do the necessary to make it working.
```bash
    apiVersion: apps/v1
    kind: Pod
    metadata:
      name: nginx
    spec:
      containers:
      - name: nginx
        image: nginx:1.14.2
```

