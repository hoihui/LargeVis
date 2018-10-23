Modified for Python 3.6.6

```
cd Linux
g++ LargeVis.cpp main.cpp -o LargeVis -lm -pthread -lgsl -lgslcblas -Ofast -march=native -ffast-math
python setup.py install
```
