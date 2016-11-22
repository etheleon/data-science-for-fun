```
$ docker build --force-rm=true -t pythoniris .
$ docker run --net host -d --name myiris pythoniris  
```

Testing
```
localhost:5000/prediction?slength=1.5&swidth=0.7&plength=1.3&pwidth=0.3
```
