### Problem 23:
Write an algorithm in pseudo code to sort the ascending order for a given array.<br>
Given array: A = [30, 7, 88, 23, 62, 1]

```{r, tidy=FALSE, eval=FALSE}
{To Sort the ascending order}
Use Variables: n, i, j, temp, A:array[1..n] of integer;
begin
	// n is the size of an array
	accept n;
	for i from 1 to n-1 do
		for j from 1 to n-i do
			if (A[j] > A[j+1]) then
				// temp is temporary array to sort
				temp <- A[j];
				A[j] <- A[j+1];
				A[j+1] <- temp
			endif;
		endo;
	endo;
	display "sorted array: ", A;
end
```