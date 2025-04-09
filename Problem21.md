### Problem 21:
Write an algorithm in pseudo code to search an item in a given array of length 40.

```{r, tidy=FALSE, eval=FALSE}
Using While-do Loop
{Search an item in a given array of length 40}
Use Variables: i, key, B:array[1..40];
begin
	accept key;
	i <- 1;
	while (i <= 40 And B[i] <> key) do
		i <- i+1;
	endo;

	if (B[i] = key And i <= 40) then
		print "Found at ",i;
	esle
		print "Not Found";
	endif;
end

Using For loop
{search an item in a given array of length 40}
Use Variables: i, key, found, B:array[1..40];
begin
	accept key;
	found <- false;
	for i from 1 to 50 do
		if (B[i] = key) then
			found <- true;
		endif;
		i <- i+1;
	endo;
	if (found = true) then
		print "Found at ", i;
	else
		print "Not Found";
	endif;
end;
```