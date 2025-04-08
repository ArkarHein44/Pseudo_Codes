### Problem 8:
Write an algorithm in pseudo code that compute the average of n integers.

```{r, tidy=FALSE, eval=FALSE}
Using for loop
{Calculate the average of n integers}
Use Variables: i, n, num, sum, avg;
begin
	accept n;
	sum <- 0;
	for i from 1 to n do
		accept num;
		sum <- sum+num;
		i <- i+1;
	endo;
	avg <- sum/n;
	display "the average is ",avg;
end

Using While-do loop
{Calculate the average of n integers}
Use Variables: i, n, num, sum, avg;
begin
	accept n;
	sum <- 0;
	i <- 1;
	while i <= n do
		accept num;
		sum <- sum+num;
	endo;

	avg <- sum/n;
	print "the average is ", avg;
end

Using repeat-until loop
{Calculate the average of n integers}
Use Variables: i, n, num, sum, avg;
begin
	accept n;
	sum <- 0;
	i <- 0;
	repeat
		accept num;
		sum <- sum+num;
		i <- i+1;
	until (i = n+1);

	avg <- sum/n;

	print "the average is ",avg;
end
```