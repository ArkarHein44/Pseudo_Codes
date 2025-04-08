### Problem 16:
Write an algorithm in pseudo code that will input total amount of cost for purchasing and to decide the reduced amount of this customer.   
- if total amount < 10000, discount = 5%
- if total amount >= 10000 and total amount < 30000, discount = 10%
- if total amount >= 30000, discount = 15%

```{r, tidy=FALSE, eval=FALSE}
Use Variables: total_amount, discount, reducted_amount;
begin
	accept total_amount;
	if (total_amount < 10000) then
		discount = total_amount *(5/100);
	elseif (total_amount >= 10000 And total_amount < 30000) then
		discount = total_amount*(10/100);
	else
		discount = total_amount *(15/100);
	endif;
	reducted_amount = total_amount - discount;
	display "The amount is ",reducted_amount;
end
```