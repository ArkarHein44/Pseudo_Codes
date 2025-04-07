### Problem 3:
Design an algorithm that a user can follow to make a simple phone call to a friend from a standard phone. 
<br>
(You can assume the user has the correct number to call)
<br>
Simple Phone Call Example

```{r, tidy=FALSE, eval=FALSE}
begin
	Lift Receiver;
	if (no dial tone) then
		print "Can't Make Call";
	else
		dial number;
		if (number busy) then
			print "the number you have dialed is busy now"
		else
			Talk
		endif
	endif
end
```