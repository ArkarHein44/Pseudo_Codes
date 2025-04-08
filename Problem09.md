### Problem 9:
Write an algorithm in pseudo code to find the average for the sum of integers from 1 to 100 .

```{r, tidy=FALSE, eval=FALSE}
Using for loop
{Calculate the average of integers from 1 to 100}
Use Variables: i, sum;
begin
	sum <- 0;
	i <- 1;
	for i from 1 to 100 do
		sum <- sum+i;
		i <- i+1;
	endo;
	avg <- sum/100;
	display "The average = ", avg;
end

Using While loop
{Calculate the average of integers from 1 to 100}
Use Variables: i, sum;
begin
	sum <- 0;
	i <- 1;
	while (i <= 100) do
		sum <- sum+i;
		i <- i+1;
	endo;
	avg <- sum/100;
	display "The average = ", avg;
end

Using repeat-until loop
{Calculate the average of integers from 1 to 100}
Use Variables: i, sum;
begin
	sum <- 0;
	i <- 1;
	repeat 
		sum <- sum+i;
		i <- i+1;
	until (i = 101);

	avg <- sum/100;
	display "The average = ", avg;
end
```