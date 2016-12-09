~~~~
docker build -t Titanic .
~~~~
~~~~ 
docker run -d -p 8888:8888  -v $PWD:/tmp/working -w=/tmp/working Titanic sh -c "ipython notebook --ip=0.0.0.0 --no-browser" 
~~~~
