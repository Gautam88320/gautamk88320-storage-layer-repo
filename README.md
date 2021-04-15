

-
-----------------------------







1. A Trigger is a stored program invoked automatically in response to an event such as insert, update, or delete that occurs in the associated table.
 2. types:-
 There are 6 different types of triggers in MySQL:
Before Update Trigger
After Update Trigger
Before Insert Trigger
After Insert Trigger
Before Delete Trigger
After Delete Trigger

syntax for trigger........
CREATE TRIGGER `event_name` 
BEFORE/AFTER INSERT/UPDATE/DELETE ON `database`. `table` FOR EACH ROW BEGIN 
-- trigger body 
-- this code is applied to every 
-- inserted/updated/deleted row 
END; 
---------------------------------
1. FUNCTION VS PROCEDURE
Ans- function
1  syntax create function fun_name
 2  function must be return somthing
3 it can be called from select statement
4 
procedure
1 syntax
2 return 0 or 1 values, so we not used return keyword
3 can not used select /where/having so on statement
4 can not used join clause 
--------------------------------------------------
view vs procedure


A view is a “virtual” table whose data is the result of a stored query. It is derived each time you query against the view. It allows the selection of only particular columns or only particular rows of data so is useful in minimizing the storage required for result sets. It may also be used to enforce security rules.

A procedure is a set of SQL commands that perform specific functions. It is compiled once and may be re-executed. It may be designed to act on input parameter values.
