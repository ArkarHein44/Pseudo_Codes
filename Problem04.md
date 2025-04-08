### Problem 4:
A company employs 100 staff. Design an algorithm to read all salaries from the file ‘salary_file’ and deduct 17% for tax.  The updated salaries should be written to the file ‘salary_after_tax_file’.

```{r, tidy=FALSE, eval=FALSE}
{Calculate Employee salary after Tax}
begin
	for (employee from 1 to 100) do
		read salary from salary_file;
		deduction <- (salary*17)/100
		net_salary <- salary-deduction
		write net_salary to salary_after_tax_file
	enddo;
end
```