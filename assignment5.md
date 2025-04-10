### Question:
1. Write an algorithm in pseudo code for finding the middle on of three numbers

### Answer:
```{r, tidy=FALSE, eval=FALSE}
{Find the middle on of the three numbers}
Use Variables: num1, num2, num3, middle;
begin 
	accept num1;
	accept num2;
	accept num3;
	
	// for all equal numbers
	if (num1 = num2 And num2 = num3) then
		middle <- num1;
	endif;

	// for 2 equal numbers
	if (num1 = num2 Or num1 = num3) then
		middle <- num1;
	elseif (num2 = num3) then
		middle <- num2;
	endif;

	// for all different numbers
	if ((num1 > num2 And num1 < num3) Or (num1 > num3 And num1 < num2)) then
		middle <- num1;
	elseif ((num2 > num1 And num2 < num3) Or (num2 > num3 And num2 < num1)) then
		middle <- num2;
	else
		middle <- num3;
	endif;

	print “The middle is “,middle;
end
```

