### Question:
1.Write an algorithm in pseudo code that reads in a continuous string of text character by character. Your algorithm should terminate when ' z ' is input.<br>
Your algorithm should also calculate and print;
-  the number of times ' a '  was input.
-  the number of times ' e '  was input.


### Answer:
```{r, tidy=FALSE, eval=FALSE}
Use Variables: char, countOfa, countOfe;
begin
	countOfa <- 0;
	countOfe <- 0;	
repeat
	read char;
		if (char = “a” ) then
			countOfa <- countOfa + 1;
		elseif (char = “e”) then
			countOfe <- countOfe+1; 
		endif;
	until (char = z);
	print “the number of times ‘a’ was inpiut ”, countOfa;
	print “the number of times ‘e’ was inpiut ”, countOfe;
end
```

