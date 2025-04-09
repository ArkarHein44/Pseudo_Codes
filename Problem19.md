### Problem 19:
Write an algorithm in pseudo code to display the sum and average of the numbers from an array A[1..100].

```{r, tidy=FALSE, eval=FALSE}
{Display the sum and average of an array of size 100}
Use Variables: i, sum, avg, A:array[1..100];
begin
	sum <- 0;
	for i from 1 to 100 do
		sum <- sum + A[i];
	endo;

	avg <- sum/100;
	display "The sum is ",sum;
	display "The average is ",avg;
end
```