### Problem 7:
Write an algorithm in pseudo code that compute the sum of 1 to 5 .

```{r, tidy=FALSE, eval=FALSE}
{Calculate the sum of 1 to 5}
Use Variables: i, sum;
begin
	sum <- 0;
	i <- 1;
	for i from 1 to 5 do
		sum <- sum+i;
		i <- i+1;
	enddo	
	display "the sum is ",sum;
end
```