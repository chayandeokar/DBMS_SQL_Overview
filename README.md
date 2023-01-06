# DBMS SQL Overview

## DBMS 1
--> About DBMS 


--> ER Diagram, Entity Set, Relationship, Cardinality Constraint, Attributes, Constraints


--> Keys


--> Functional Dependency


--> Decomposition of a Relation


--> Types of Decomposition


## DBMS 2
--> Normalization


--> Transaction 


--> Acid properties


--> Schedules


--> Relational Algebra

## DBMS 3
--> SQL 


--> DDL , DML , DCL 


--> SQL queries 


## Deadlocks (Important):
A situation where a set of processes are blocked because each process is holding a resource and waiting for another resource acquired by some other process. Deadlock can arise if following four conditions hold simultaneously (Necessary Conditions):

1. Mutual Exclusion – One or more than one resource is non-sharable (Only one process can use at a time).
2. Hold and Wait – A process is holding at least one resource and waiting for resources.
3. No Preemption – A resource cannot be taken from a process unless the process releases the resource.
4. Circular Wait – A set of processes are waiting for each other in circular form.

● Methods for handling deadlock: There are three ways to handle deadlock
1. Deadlock prevention or avoidance : The idea is to not let the system into a deadlock state.
2. Deadlock detection and recovery : Let deadlock occur, then do preemption to handle it once occurred.
3. Ignore the problem all together : If deadlock is very rare, then let it happen and reboot the system. This is the approach that both Windows and UNIX take.
