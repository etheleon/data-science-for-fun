docker run --rm -p 8888:8888  -v $PWD:/tmp/working -w=/tmp/working  sh -c "ipython notebook --ip=0.0.0.0 --no-browser"
