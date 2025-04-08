### Problem 10:
Write a pseudo to generate the following series of numbers 1,4,9,16,25,36.

```{r, tidy=FALSE, eval=FALSE}
	{Genetate the following series of numbers 1,4,9,16,25,36}
	Use Variables: i;
	begin
		for i from 1 to 6 do
			print i*i;
			i <- i+1;
		endo;
	end
```