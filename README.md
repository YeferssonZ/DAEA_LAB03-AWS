build -t testphp .

docker login

docker tag testphp yefersson/part2php

docker push  yefersson/part2php 
