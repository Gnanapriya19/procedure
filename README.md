REPLACE: It recreates the procedure if it already exists. 
PROCEDURE: It is the name of the procedure to be created.  
ARGUMENT: It is the name of the argument to the procedure. 
Parenthesis can be omitted if no arguments are present.  
IN: Specifies that a value for the argument must be specified when calling the procedure ie.,
used to pass values to a sub-program. This is the default parameter.  
OUT: Specifies that the procedure passes a value for this argument back to it‟s calling environment after execution ie.
used to return values to a caller of the sub-program. INOUT: Specifies that a value for the argument must be specified 
when calling the procedure and that procedure passes a value for this argument back to it‟s calling environment after
execution.  
RETURN: It is the data type of the function‟s return value because every function must return a value,
this clause is required. 
Syntax :  create or replace procedure <procedure name> (argument {in,out,inout} datatype ) {is,as}
variable declaration; constant declaration; begin 
PL/SQL subprogram body; exception exception PL/SQL block; end; 
FUNCTIONS 
Syntax: create or replace function <function name> (argument in datatype,……) return datatype 
{is,as} variable declaration; constant declaration; begin 
PL/SQL subprogram body; exception exception PL/SQL block; end; 

