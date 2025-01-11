# nginx-controller
# This is first header line
Testing formating

*This line is italicized*

**This is bold line**

1. first
1. second
1. third

---

- First item
- second item
- third item

[cnbc](https://www.cnbc.com)

` git pull something`

Test Tables

|City|Status|
|------|------------|
|Delhi|bad|
|Mumbai|Good|

```
apiVersion: apps/v1
kind: Deployment
metadata:
  name: test
  label: xyz
spec:
  selector:
    matchLabels:
      app: my-app
  template:
    metadata:
      labels:
        app: my-app
    spec:
      containers:
      - name: pod1
        image: docker/nginx:latest
```
    