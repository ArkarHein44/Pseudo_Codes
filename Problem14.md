### Problem 14:
Write an algorithm in pseudo code that will input two numbers and find the maximum number and minimum number.

```{r, tidy=FALSE, eval=FALSE}
{Find the maximun number and minimum number from two numbers}
Use Variables: num1, num2;
begin
	accept num1, num2;
	if (num1 > num2) then do
		display "The maximun number is ",num1;
		display "The minimum number is ",num2;
	else
		display "The maximun number is ",num2;
		display "The minimum number is ",num1;
	endif;
end
```