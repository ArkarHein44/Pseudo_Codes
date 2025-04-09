### Problem 20:
Write an algorithm in pseudo code to display the sum of the numbers from an array A[1..4] and Dry-Run.
A = [5, 2, 15, 8];

```{r, tidy=FALSE, eval=FALSE}
{display the sum of the numbers of an array of size 4}
Use Variables: i, sum, A:array[1..4];
begin
1	sum <- 0;
2	for i from 1 to 4 do
3		sum <- sum + A[i];
4	endo;
5	display "The sum is ", sum;
end
```

### Dry Run

| line No. | Sum      | i   | A[i] | i<=4 | Display         |
| :------: | :------: | :-: | :--: | :--: | :-------------: |
| 1        | 0        |     |      |      |                 |
| 2        |          | 1   | 5    | Yes  |                 |
| 3        | 0+5=5    |     |      |      |                 |
| 2        |          | 2   | 2    | Yes  |                 |
| 3        | 5+2=7    |     |      |      |                 |
| 2        |          | 3   | 15   | Yes  |                 |
| 3        | 7+15=22  |     |      |      |                 |
| 2        |          | 4   |  8   | Yes  |                 |
| 3        | 22+ 8=30 |     |      |      |                 |
| 2        |          | 5   |      | No   |                 |
| 4        |          |     |      |      |                 |
| 5        |          |     |      |      | the sum is 30   |