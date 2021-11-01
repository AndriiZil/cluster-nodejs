### Clustering NodeJS Application

```
    npm install -g loadtest
```

### Try to check API without clustering
```
    loadtest http://localhost:3000/api/nocluster -n 1000 -c 100
```

### Try to check API with clustering
```
    loadtest http://localhost:3001/api/withcluster -n 1000 -c 100
```
