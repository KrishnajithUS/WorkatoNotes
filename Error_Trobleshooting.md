# Error Troubleshooting
---- Recipe Design-Time Errors ----
1. Formula Errors
   > mispelled formulas
   > Formula syntax errors
   > Symbols in wrong Format
   > Improper spacing between formulas and operators
   > Invalid Datapills
   > App connection errors
     >> App credentials were changed
     >> User does nto have permissions to read or write selected records
     >> Connected user permissions were changed
2. Trigger Errors 
> It occurs when recipe fails to fetch trigger events successfully.
  >> As no tirgger event data was retrieved , the recipe does not create a job in the first place
3. Job Errors
> When an active recipe processes a trigger event.(ie. actions in the recipe are executed,it results in a job)
> Different Job Errors
  >> Formula Errors
  >>Data type Errors
  >> Missing Required fields at run-time
  >> Timeouts
## Common Errors and Error Codes
  >> 500 Internal Server Errors - Use Monitor and Handle Error
## Recipe Login Error
  >> Incorrect recipe step indentations
  >> Incorrect list management
  >> Infinite looping
  >> Unexpected trigger events(data duplication)
  >> Missing trigger events