### Problem 22:
Write an algorithm in pseudo code to search an item and display the address of this item for a given array. And dry-run for this algorithm.<br>
Given array: A = [6, 13, 14, 9, 8]

```{r, tidy=FALSE, eval=FALSE}
{Search an item and display the address of given array}
Use Variables: i, key, A:array[1..5];
begin 
1	accept key;
2	i <- 1;
3	while (A[i] <> key And i <= 5) do
4		i <- i+1;
5	endo;
6	if (A[i] = key And key <= 5>) then
7		display "Found =  ", key;
8		display "Address is ", i;
9	else
10		display "Not Found";
11	endif;
end
```

---

### Dry Run for search item exist in a given array: Key = 9

| line No. | key | i      | A[i]    | A[i] <> key And i <= 5> | A[i] = key ? | Display         |
| :------: | :-: | :----: | :----:  | :---------------------: | :----------: | :-------------: |
| 1        | 9   |        |         |                         |              |                 |
| 2        |     | 1      |         |                         |              |                 |
| 3        |     |        | A[1]=6  | Yes                     |              |                 |
| 4        |     | 1+1=2  |         |                         |              |                 |
| 3        |     |        | A[2]=13 | Yes                     |              |                 |
| 4        |     | 2+1=3  |         |                         |              |                 |
| 3        |     |        | A[3]=14 | Yes                     |              |                 |
| 4        |     | 3+1=4  |         |                         |              |                 |
| 3        |     |        | A[4]=9  | No                      |              |                 |
| 5        |     |        |         |                         |              |                 |
| 6        |     |        |         |                         | Yes          |                 |
| 7        |     |        |         |                         |              | Found = 9       |
| 8        |     |        |         |                         |              | Address is 4    |

---

### Dry Run for search item does not exist in a given array: Key = 10

| line No. | key | i      | A[i]    | A[i] <> key And i <= 5> | A[i] = key ? | Display         |
| :------: | :-: | :----: | :----:  | :---------------------: | :----------: | :-------------: |
| 1        | 10  |        |         |                         |              |                 |
| 2        |     | 1      |         |                         |              |                 |
| 3        |     |        | A[1]=6  | Yes                     |              |                 |
| 4        |     | 1+1=2  |         |                         |              |                 |
| 3        |     |        | A[2]=13 | Yes                     |              |                 |
| 4        |     | 2+1=3  |         |                         |              |                 |
| 3        |     |        | A[3]=14 | Yes                     |              |                 |
| 4        |     | 3+1=4  |         |                         |              |                 |
| 3        |     |        | A[4]=9  | Yes                     |              |                 |
| 4        |     | 4+1=5  |         |                         |              |                 |
| 3        |     |        | A[5]=8  | Yes                     |              |                 |
| 4        |     | 5+1=6  |         |                         |              |                 |
| 3        |     |        |         | No, i > 5               |              |                 |
| 5        |     |        |         |                         |              |                 |
| 9        |     |        |         |                         | No           |                 |
| 10       |     |        |         |                         |              | Not Found       |
