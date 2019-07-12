# Mysql Loops
  If you want to put while loop inside the MySQL then Follow the Procedure.

BEFORE start you need to set Delimiter
default its ' : ' you need to change it ' $$ '

* SETP-ONE 
  
  MySQL stored procedure using CREATE PROCEDURE statement.
  
  <CODE> CREATE PROCEDURE GetAllProducts() </CODE>

* STEP-TWO

  You need to start the Procedure
  
  <CODE> BEGIN </CODE>

* STEP-THREE
  
  If you want to declair any varabile for making loops 
  
  <CODE> DECLARE variable_name INT DEFAULT 0; </CODE>

  if you want to initialise the value for varianle then
  
  <CODE> SET variable_name = 1; </CODE>

* STEP-FOUR
  
  Here you can Write Any functionlity or loops 
  
  <CODE> WHILE variable_name < 10 DO </CODE<

  Then Write statesment for the loop ( we are putting insert query here)
  
  <CODE>INSERT INTO `table`(`field_one`, `field_two`) VALUES ('value_one','value_two');</CODE> 

  if you want to make Incriment then you again need to use SET to initianlise the value
  
  <CODE> SET variable_name = variable_name+1; </CODE>

  you must end the loop if you started 
  
  <CODE> END WHILE; </CODE>

* STEP- FIVE
  
  END of the procedure
  
  <CODE> END </CODE>




