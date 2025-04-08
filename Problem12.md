### Problem 12:
Write an algorithm in pseudo code to accept the integers before the number is -999 and find out how many number is accepted.
<br>
Note : This problem does not predefine the number of integers. Thus, we can not know the terminate value or repeated time. This means that we should not use for –loop. Assume that when you want to terminate this process, enter number -999.  

```{r, tidy=FALSE, eval=FALSE}
	{To accept the integer and count the number of integers}
	Use Variables: count, num;
	begin
		count <- 0;
		repeat
			accept num;
			count <- count + 1;
		until (num = -999)
		count <- count - 1;
		display "the count of integers is ", count;
	end
```