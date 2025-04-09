### Question:
Assume you input the length and width of a rectangular yard (in feet). Your company has a $20 charge just for showing up, plus 25 cents per square foot. Include 5% sales tax on the whole amount. Write an algorithm, in pseudo-code, to compute the cost for a given size of yard.

### Answer: 
```{r, tidy=FALSE, eval=FALSE}
{Calculate the cost for a given size of yard}
Use Variables: length, width, area, baseCharge, ratePerSqFt, serviceCharge, subTotal, tax, totalCost;
begin
	accept length;
	accept width;
	area <- length * width;
	baseCharge <- 20;
	ratePerSqFt <- 0.25;
	serviceCharge <- area * ratePerSqFt;
	subTotal <- baseCharge + serviceCharge;
	tax <- subTotal * (5/100);
	totalCost <- subTotal + tax;
	display "Total cost = ",totalCost;
end
```
