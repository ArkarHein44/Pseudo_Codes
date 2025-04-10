### Question
1.Write a pseudo code to print the average of odd numbers in the given array.

### Answer
```{r, tidy=FALSE, eval=FALSE}
{Calculate the average of odd numbers in the given array}
Use Variables: i, n, count, sum, avg, A:array[1..n] of integer;
begin
	accept n;
	count <- 0;
	sum	<- 0;
	for i from 1 to n
	do
		if (A[i] mod 2 <> 0) then
			sum	<- sum+A[i];
			count <- count+1;
		endif;
	endo;
	if (count > 0) then
		avg	<- sum/count;
		display “the average of odd numbers: ”, avg;
	else
		display “no odd number found”;
	endif;
end
```