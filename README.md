# WordCounter
Basic algorithm implemented by technology MapReduce

```
g++ map.cpp -o map
g++ reduce.cpp -o reduce
g++ mapreduce.cpp -o mapreduce -lpthread -lboost_system

./mapreduce map ./map input.txt aftermap.txt
./mapreduce reduce ./reduce aftermap.txt result.txt
```
