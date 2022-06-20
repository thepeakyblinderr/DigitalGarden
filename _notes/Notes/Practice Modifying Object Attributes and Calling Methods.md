# adding column
```py
from prettytable import PrettyTable  
  
table = PrettyTable()  
table.add_column("Friends", ["tejas", "ojas", "prajwal"])  
  
print(table)
```
![[Pasted image 20220620154854.png]]

# changing alignment
```py
from prettytable import PrettyTable  
  
table = PrettyTable()  
table.add_column("Friends", ["tejas", "ojas", "prajwal"])  
table.add_column("where they live", ["anjangaon", "pune", "nagpur"])  
  
table.align = "l"  
print(table)
```
![[Pasted image 20220620154824.png]]

