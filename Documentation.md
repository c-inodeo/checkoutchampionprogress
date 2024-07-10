**SQL Database Diagrams:** ![[Pasted image 20240710103041.png]]



**Class Diagrams**
![[Pasted image 20240710144113.png]]
**Pitfalls**:
- before pushing changes, conduct regressions - especially the changes are big and method refactored is common to some classes that uses it
- consider designing the tables especially table that are related, what I did is design the table on-the-go, but what happened is that I encountered difficulty when I implemented the many-to-many relationship for my Product and Category table. 
- started as a single layer application, when the code got bigger it's hard to keep track of the changes and the classes related. In my experience, it should be at least code should be separated by concern.
