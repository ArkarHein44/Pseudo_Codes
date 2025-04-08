### Problem 13:
Write an algorithm in pseudo code that will input n integer and to find the  number of odd numbers.

```{r, tidy=FALSE, eval=FALSE}
{Find the odd numbers from the input of nth times}
Use Variables: i, n, num, count;
begin
	accept n;
	count <- 0;
	for i from 1 to n do
		accept num;
		if (num mod 2 <> 0) then
			count <- count + 1;
		endif
	endo;
	display "The count of odd numbers is ",count;
end
```