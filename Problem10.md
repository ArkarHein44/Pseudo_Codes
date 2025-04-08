### Problem 10:
Write an algorithm in pseudo code to find the sum of odd numbers between 1 and 100.

```{r, tidy=FALSE, eval=FALSE}
Using for loop
{Calculate the sum of odd numbers between 1 and 100}
Use Variables: i,sum;
begin 
	sum <- 0;
	i <- 1;
	for i from 1 to 99 do
		sum <- sum+i;
		i <- i+2;
	endo;
	display "the sum of odd integers = ",sum;
end

Using While-do Loop
{Calculate the sum of odd numbers between 1 and 100}
Use Variables: i,sum;
begin 
	sum <- 0;
	i <- 1;
	while (i <= 99) do
		sum <- sum+i;
		i <- i+2;
	endo;
	display "the sum of odd integers = ",sum;
end

Using repeat-untill loop
{Calculate the sum of odd numbers between 1 and 100}
Use Variables: i,sum;
begin 
	sum <- 0;
	i <- 1;
	repeat
		sum <- sum+i;
		i <- i+2;
	until (i = 101);
	display "the sum of odd integers = ",sum;
end
```