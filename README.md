# Hacker_Rank_Linux_Shell

## Write a bash script that prints the string "HELLO".
```
echo "HELLO"
```

Write a Bash script which accepts name as input and displays the greeting "Welcome (name)"
```
read input
echo "Welcome $input"
```

Use a for loop to display the natural numbers from 1 to 50.
```
for i in {1..50}
do
    echo "$i"
done
```
Given two integers, X and Y, find their sum, difference, product, and quotient.
```
read x 
read y

echo $((x + y))
echo $((x - y))
echo $((x * y))
echo $((x / y))
```

## Given two integers, X  and Y, identify whether X < Y or X > Y or X = Y .

 Exactly one of the following lines:
 - X is less than Y
 - X is greater than Y
 - X is equal to Y

  ```
  #!/bin/bash
read x 
read y 
read z 

if [$x -eq $y] && [$y -eq $z];
    then 
        echo "EQUILATERAL"
elif [$x -en $y] && [$x -en $z];
    then 
        echo "equal"
else 
    echo "working"
fi
  ```
