# Hacker_Rank_Linux_Shell

## Easy

Write a bash script that prints the string "HELLO".
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

Given two integers, X  and Y, identify whether X < Y or X > Y or X = Y .

 Exactly one of the following lines:
 - X is less than Y
 - X is greater than Y
 - X is equal to Y

  ```
read x
read y

if (($x < $y))
  then 
    echo "X is less than Y"
elif (($x > $y))
  then 
    echo "X is greater than Y"
else 
  echo "X is equal to Y"
fi  
  ```
